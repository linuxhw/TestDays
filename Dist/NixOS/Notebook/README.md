NixOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

Total: 118

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4d377fc8b8](https://linux-hardware.org/?probe=4d377fc8b8) | Jul 01, 2023 |
| Dell          | Latitude E5470              | [fd56f44c38](https://linux-hardware.org/?probe=fd56f44c38) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Microtech     | CoreBook Lite               | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [2812cf43d0](https://linux-hardware.org/?probe=2812cf43d0) | Jun 23, 2023 |
| HP            | EliteBook 820 G3            | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| MECHREVO      | WUJIE 14                    | [a55e31b287](https://linux-hardware.org/?probe=a55e31b287) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| MACHENIKE     | F117-7P                     | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| Dell          | Latitude 5290 2-in-1        | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Lenovo        | G50-70 20351                | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| Apple         | MacBookPro11,5              | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| UNOWHY        | Y13G011S4EI                 | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| Lenovo        | G50-70 20351                | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [2063d4a9fc](https://linux-hardware.org/?probe=2063d4a9fc) | Apr 27, 2023 |
| Apple         | MacBookPro11,3              | [7fd17e2245](https://linux-hardware.org/?probe=7fd17e2245) | Apr 22, 2023 |
| Avell High... | A70 MOB                     | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Dell          | XPS 9320                    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| GPD           | G1621-02                    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| ASUSTek       | 1005HA                      | [3326423f04](https://linux-hardware.org/?probe=3326423f04) | Mar 06, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| Toshiba       | Satellite L50-B             | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| Blackview     | AceBook 1                   | [ea4db42aa8](https://linux-hardware.org/?probe=ea4db42aa8) | Jan 19, 2023 |
| Dell          | Latitude 7420               | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| Dell          | Precision M4800             | [505f1b47dc](https://linux-hardware.org/?probe=505f1b47dc) | Dec 30, 2022 |
| GPD           | WIN2                        | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| MSI           | Raider GE67HX 12UGS         | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| Dell          | XPS 15 7590                 | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| Acer          | Aspire A315-54K             | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [0c889920b5](https://linux-hardware.org/?probe=0c889920b5) | Nov 12, 2022 |
| Dell          | Latitude E5540              | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [b60f8a187c](https://linux-hardware.org/?probe=b60f8a187c) | Nov 04, 2022 |
| Dell          | Inspiron 5570               | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Toshiba       | Satellite L50-B             | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| Dell          | Precision 5760              | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Dell          | XPS 13 9310                 | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| Dell          | Inspiron 15 7510            | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Dell          | Precision M4800             | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Apple         | MacBookPro11,5              | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
| Apple         | MacBookPro11,5              | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| Dell          | XPS 13 9310                 | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| Apple         | MacBookPro11,5              | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| GPD           | MicroPC                     | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| MSI           | Bravo 15 B5DD               | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Dell          | Latitude 7420               | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | ProBook 445 G7              | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Latitude 7420               | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| HP            | ZBook Studio G5             | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| Lenovo        | ThinkPad T580 20L90024PB    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| Dell          | XPS 15 9550                 | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| Acer          | Aspire E5-576G              | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| NixOS 22.11                      | 27        | 29.35%  |
| NixOS 23.05                      | 20        | 21.74%  |
| NixOS 22.05                      | 18        | 19.57%  |
| NixOS 21.11                      | 9         | 9.78%   |
| NixOS 23.11                      | 4         | 4.35%   |
| NixOS                            | 2         | 2.17%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 1.09%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 1.09%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 1.09%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 1.09%   |
| NixOS 21.05.2132.733682c3292     | 1         | 1.09%   |
| NixOS 21.05.20210423.c21475e     | 1         | 1.09%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 1.09%   |
| NixOS 20.09pre-git               | 1         | 1.09%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 1.09%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 1.09%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 1.09%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 1.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 82        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Notebooks | Percent |
|------------------|-----------|---------|
| 6.3.8            | 4         | 4.12%   |
| 6.3.3            | 3         | 3.09%   |
| 5.15.74          | 3         | 3.09%   |
| 5.15.43          | 3         | 3.09%   |
| 6.3.1            | 2         | 2.06%   |
| 6.1.35           | 2         | 2.06%   |
| 6.1.34           | 2         | 2.06%   |
| 6.1.0            | 2         | 2.06%   |
| 6.0.10           | 2         | 2.06%   |
| 5.16.15          | 2         | 2.06%   |
| 5.15.72          | 2         | 2.06%   |
| 5.15.68          | 2         | 2.06%   |
| 5.15.64          | 2         | 2.06%   |
| 5.15.26          | 2         | 2.06%   |
| 5.13.7           | 2         | 2.06%   |
| 6.3.9            | 1         | 1.03%   |
| 6.3.5            | 1         | 1.03%   |
| 6.2.9-lqx1       | 1         | 1.03%   |
| 6.2.9            | 1         | 1.03%   |
| 6.2.8            | 1         | 1.03%   |
| 6.2.7            | 1         | 1.03%   |
| 6.2.14           | 1         | 1.03%   |
| 6.2.0            | 1         | 1.03%   |
| 6.1.7-xanmod1    | 1         | 1.03%   |
| 6.1.27           | 1         | 1.03%   |
| 6.1.25           | 1         | 1.03%   |
| 6.1.24           | 1         | 1.03%   |
| 6.1.21           | 1         | 1.03%   |
| 6.1.1            | 1         | 1.03%   |
| 6.0.2-xanmod1-tt | 1         | 1.03%   |
| 6.0.11           | 1         | 1.03%   |
| 6.0.10-zen2      | 1         | 1.03%   |
| 6.0.0-xanmod1    | 1         | 1.03%   |
| 5.8.4            | 1         | 1.03%   |
| 5.8.16-hardened  | 1         | 1.03%   |
| 5.8.11           | 1         | 1.03%   |
| 5.7.4            | 1         | 1.03%   |
| 5.7.17           | 1         | 1.03%   |
| 5.4.24           | 1         | 1.03%   |
| 5.4.209          | 1         | 1.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.8   | 4         | 4.12%   |
| 6.3.3   | 3         | 3.09%   |
| 6.0.10  | 3         | 3.09%   |
| 5.15.74 | 3         | 3.09%   |
| 5.15.43 | 3         | 3.09%   |
| 6.3.1   | 2         | 2.06%   |
| 6.2.9   | 2         | 2.06%   |
| 6.1.35  | 2         | 2.06%   |
| 6.1.34  | 2         | 2.06%   |
| 6.1.0   | 2         | 2.06%   |
| 5.16.15 | 2         | 2.06%   |
| 5.15.72 | 2         | 2.06%   |
| 5.15.68 | 2         | 2.06%   |
| 5.15.64 | 2         | 2.06%   |
| 5.15.26 | 2         | 2.06%   |
| 5.13.7  | 2         | 2.06%   |
| 6.3.9   | 1         | 1.03%   |
| 6.3.5   | 1         | 1.03%   |
| 6.2.8   | 1         | 1.03%   |
| 6.2.7   | 1         | 1.03%   |
| 6.2.14  | 1         | 1.03%   |
| 6.2.0   | 1         | 1.03%   |
| 6.1.7   | 1         | 1.03%   |
| 6.1.27  | 1         | 1.03%   |
| 6.1.25  | 1         | 1.03%   |
| 6.1.24  | 1         | 1.03%   |
| 6.1.21  | 1         | 1.03%   |
| 6.1.1   | 1         | 1.03%   |
| 6.0.2   | 1         | 1.03%   |
| 6.0.11  | 1         | 1.03%   |
| 6.0.0   | 1         | 1.03%   |
| 5.8.4   | 1         | 1.03%   |
| 5.8.16  | 1         | 1.03%   |
| 5.8.11  | 1         | 1.03%   |
| 5.7.4   | 1         | 1.03%   |
| 5.7.17  | 1         | 1.03%   |
| 5.4.24  | 1         | 1.03%   |
| 5.4.209 | 1         | 1.03%   |
| 5.4.187 | 1         | 1.03%   |
| 5.19.2  | 1         | 1.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 32.63%  |
| 6.1     | 12        | 12.63%  |
| 6.3     | 11        | 11.58%  |
| 6.2     | 6         | 6.32%   |
| 6.0     | 6         | 6.32%   |
| 5.16    | 6         | 6.32%   |
| 5.8     | 3         | 3.16%   |
| 5.19    | 3         | 3.16%   |
| 5.13    | 3         | 3.16%   |
| 5.10    | 3         | 3.16%   |
| 5.7     | 2         | 2.11%   |
| 5.4     | 2         | 2.11%   |
| 5.18    | 2         | 2.11%   |
| 5.17    | 2         | 2.11%   |
| 4.19    | 2         | 2.11%   |
| 5.12    | 1         | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 81        | 98.78%  |
| i686   | 1         | 1.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 42        | 48.28%  |
| GNOME        | 11        | 12.64%  |
| sway         | 10        | 11.49%  |
| KDE5         | 6         | 6.9%    |
| Hyprland     | 6         | 6.9%    |
| XFCE         | 3         | 3.45%   |
| none+i3      | 3         | 3.45%   |
| none+xmonad  | 2         | 2.3%    |
| KDE          | 2         | 2.3%    |
| none+bspwm   | 1         | 1.15%   |
| none+awesome | 1         | 1.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 44        | 51.16%  |
| Wayland | 26        | 30.23%  |
| X11     | 14        | 16.28%  |
| Tty     | 2         | 2.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 60.71%  |
| GDM     | 13        | 15.48%  |
| SDDM    | 10        | 11.9%   |
| LightDM | 10        | 11.9%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 39        | 46.43%  |
| Unknown | 31        | 36.9%   |
| en_GB   | 4         | 4.76%   |
| en_DK   | 2         | 2.38%   |
| ru_RU   | 1         | 1.19%   |
| ro_RO   | 1         | 1.19%   |
| lv_LV   | 1         | 1.19%   |
| it_IT   | 1         | 1.19%   |
| fr_FR   | 1         | 1.19%   |
| en_IN   | 1         | 1.19%   |
| en_CA   | 1         | 1.19%   |
| de_DE   | 1         | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 73        | 89.02%  |
| BIOS | 9         | 10.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 43        | 50%     |
| Btrfs   | 15        | 17.44%  |
| Tmpfs   | 9         | 10.47%  |
| Zfs     | 8         | 9.3%    |
| Xfs     | 8         | 9.3%    |
| Unknown | 3         | 3.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 77        | 91.67%  |
| Unknown | 5         | 5.95%   |
| MBR     | 2         | 2.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 78.57%  |
| Yes       | 18        | 21.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 61        | 74.39%  |
| Yes       | 21        | 25.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 33        | 40.24%  |
| Dell                   | 15        | 18.29%  |
| ASUSTek Computer       | 8         | 9.76%   |
| Hewlett-Packard        | 5         | 6.1%    |
| GPD                    | 3         | 3.66%   |
| Apple                  | 3         | 3.66%   |
| MSI                    | 2         | 2.44%   |
| MECHREVO               | 2         | 2.44%   |
| Framework              | 2         | 2.44%   |
| Acer                   | 2         | 2.44%   |
| Toshiba                | 1         | 1.22%   |
| OBSIDIAN-PC            | 1         | 1.22%   |
| Microtech              | 1         | 1.22%   |
| MACHENIKE              | 1         | 1.22%   |
| Gigabyte Technology    | 1         | 1.22%   |
| Blackview              | 1         | 1.22%   |
| Avell High Performance | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Latitude 7420                          | 2         | 2.44%   |
| Apple MacBookPro11,5                        | 2         | 2.44%   |
| Toshiba Satellite L50-B                     | 1         | 1.22%   |
| OBSIDIAN-PC N13_N140ZU                      | 1         | 1.22%   |
| MSI Bravo 15 B5DD                           | 1         | 1.22%   |
| MSI Alpha 15 B5EEK                          | 1         | 1.22%   |
| Microtech CoreBook Lite                     | 1         | 1.22%   |
| MECHREVO WUJIE 14                           | 1         | 1.22%   |
| MECHREVO Code01 Ver2.0                      | 1         | 1.22%   |
| MACHENIKE F117-7P                           | 1         | 1.22%   |
| Lenovo Yoga Slim 7 13ACN5 82CY              | 1         | 1.22%   |
| Lenovo Yoga 14sARE 2020 82A8                | 1         | 1.22%   |
| Lenovo ThinkPad X390 20Q0CTO1WW             | 1         | 1.22%   |
| Lenovo ThinkPad X260 20F5S6MF02             | 1         | 1.22%   |
| Lenovo ThinkPad X260 20F5S4BY00             | 1         | 1.22%   |
| Lenovo ThinkPad X250 20CLS18S0T             | 1         | 1.22%   |
| Lenovo ThinkPad X230 2333AZ2                | 1         | 1.22%   |
| Lenovo ThinkPad X230 23243E9                | 1         | 1.22%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW       | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB007AUK | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBCT01WW    | 1         | 1.22%   |
| Lenovo ThinkPad T580 20L90024PB             | 1         | 1.22%   |
| Lenovo ThinkPad T540p 20BE005YMH            | 1         | 1.22%   |
| Lenovo ThinkPad T490 20N2000LUK             | 1         | 1.22%   |
| Lenovo ThinkPad T480 20L5CTO1WW             | 1         | 1.22%   |
| Lenovo ThinkPad T460p 20FWCTO1WW            | 1         | 1.22%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW        | 1         | 1.22%   |
| Lenovo ThinkPad T14s Gen 3 21BR000MUS       | 1         | 1.22%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK       | 1         | 1.22%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT        | 1         | 1.22%   |
| Lenovo ThinkPad P50 20EN0005GE              | 1         | 1.22%   |
| Lenovo ThinkPad P14s Gen 3 21J5002KMH       | 1         | 1.22%   |
| Lenovo ThinkPad P14s Gen 1 20Y1S00C00       | 1         | 1.22%   |
| Lenovo ThinkPad E470 20H1006JIX             | 1         | 1.22%   |
| Lenovo ThinkPad E14 Gen 4 21EBCTO1WW        | 1         | 1.22%   |
| Lenovo ThinkBook 16 G4+ ARA 21D1            | 1         | 1.22%   |
| Lenovo Legion Y7000 2019 PG0 81T0           | 1         | 1.22%   |
| Lenovo Legion S7 15ACH6 82K8                | 1         | 1.22%   |
| Lenovo Legion Pro 7 16IRX8H 82WQ            | 1         | 1.22%   |
| Lenovo Legion 5 17ARH05H 82GN               | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 23        | 28.05%  |
| Dell XPS                   | 6         | 7.32%   |
| Dell Latitude              | 5         | 6.1%    |
| Lenovo Legion              | 4         | 4.88%   |
| ASUS ROG                   | 4         | 4.88%   |
| Apple MacBookPro11         | 3         | 3.66%   |
| Lenovo Yoga                | 2         | 2.44%   |
| Lenovo IdeaPad             | 2         | 2.44%   |
| HP ProBook                 | 2         | 2.44%   |
| HP EliteBook               | 2         | 2.44%   |
| Framework Laptop           | 2         | 2.44%   |
| Dell Precision             | 2         | 2.44%   |
| Dell Inspiron              | 2         | 2.44%   |
| ASUS Zenbook               | 2         | 2.44%   |
| Acer Aspire                | 2         | 2.44%   |
| Toshiba Satellite          | 1         | 1.22%   |
| OBSIDIAN-PC N13            | 1         | 1.22%   |
| MSI Bravo                  | 1         | 1.22%   |
| MSI Alpha                  | 1         | 1.22%   |
| Microtech CoreBook         | 1         | 1.22%   |
| MECHREVO WUJIE             | 1         | 1.22%   |
| MECHREVO Code01            | 1         | 1.22%   |
| MACHENIKE F117-7P          | 1         | 1.22%   |
| Lenovo ThinkBook           | 1         | 1.22%   |
| Lenovo G50-70              | 1         | 1.22%   |
| HP ZBook                   | 1         | 1.22%   |
| GPD WIN2                   | 1         | 1.22%   |
| GPD MicroPC                | 1         | 1.22%   |
| GPD G1621-02               | 1         | 1.22%   |
| Gigabyte Sabre             | 1         | 1.22%   |
| Blackview AceBook          | 1         | 1.22%   |
| Avell High Performance A70 | 1         | 1.22%   |
| ASUS ASUSPRO               | 1         | 1.22%   |
| ASUS 1005HA                | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 17        | 20.73%  |
| 2020 | 12        | 14.63%  |
| 2022 | 9         | 10.98%  |
| 2019 | 9         | 10.98%  |
| 2016 | 9         | 10.98%  |
| 2018 | 7         | 8.54%   |
| 2015 | 4         | 4.88%   |
| 2013 | 4         | 4.88%   |
| 2017 | 3         | 3.66%   |
| 2014 | 3         | 3.66%   |
| 2023 | 2         | 2.44%   |
| 2012 | 2         | 2.44%   |
| 2009 | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 82        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 82        | 98.8%   |
| Enabled  | 1         | 1.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 81        | 98.78%  |
| Yes  | 1         | 1.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 23        | 27.71%  |
| 16.01-24.0  | 22        | 26.51%  |
| 8.01-16.0   | 19        | 22.89%  |
| 4.01-8.0    | 10        | 12.05%  |
| 3.01-4.0    | 3         | 3.61%   |
| 64.01-256.0 | 3         | 3.61%   |
| 24.01-32.0  | 2         | 2.41%   |
| 0.51-1.0    | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 27        | 28.72%  |
| 3.01-4.0   | 18        | 19.15%  |
| 2.01-3.0   | 15        | 15.96%  |
| 8.01-16.0  | 14        | 14.89%  |
| 1.01-2.0   | 7         | 7.45%   |
| 24.01-32.0 | 5         | 5.32%   |
| 0.51-1.0   | 3         | 3.19%   |
| 32.01-64.0 | 2         | 2.13%   |
| 16.01-24.0 | 2         | 2.13%   |
| 0.01-0.5   | 1         | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 62        | 74.7%   |
| 2      | 19        | 22.89%  |
| 3      | 2         | 2.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 92.68%  |
| Yes       | 6         | 7.32%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 68.24%  |
| No        | 27        | 31.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 98.78%  |
| No        | 1         | 1.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 90.48%  |
| No        | 8         | 9.52%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 11        | 13.41%  |
| UK          | 7         | 8.54%   |
| France      | 7         | 8.54%   |
| Russia      | 6         | 7.32%   |
| Italy       | 5         | 6.1%    |
| Ukraine     | 4         | 4.88%   |
| Poland      | 4         | 4.88%   |
| Germany     | 4         | 4.88%   |
| Canada      | 4         | 4.88%   |
| Netherlands | 3         | 3.66%   |
| Switzerland | 2         | 2.44%   |
| Japan       | 2         | 2.44%   |
| Iraq        | 2         | 2.44%   |
| India       | 2         | 2.44%   |
| Belgium     | 2         | 2.44%   |
| Austria     | 2         | 2.44%   |
| Uruguay     | 1         | 1.22%   |
| Sweden      | 1         | 1.22%   |
| Spain       | 1         | 1.22%   |
| Slovenia    | 1         | 1.22%   |
| Singapore   | 1         | 1.22%   |
| Romania     | 1         | 1.22%   |
| Portugal    | 1         | 1.22%   |
| Peru        | 1         | 1.22%   |
| Latvia      | 1         | 1.22%   |
| Iran        | 1         | 1.22%   |
| Denmark     | 1         | 1.22%   |
| Czechia     | 1         | 1.22%   |
| Colombia    | 1         | 1.22%   |
| China       | 1         | 1.22%   |
| Brazil      | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 3         | 3.37%   |
| Vienna             | 2         | 2.25%   |
| Phoenix            | 2         | 2.25%   |
| Ottawa             | 2         | 2.25%   |
| Marki              | 2         | 2.25%   |
| Kharkiv            | 2         | 2.25%   |
| Halifax            | 2         | 2.25%   |
| Catania            | 2         | 2.25%   |
| Baghdad            | 2         | 2.25%   |
| Zurich             | 1         | 1.12%   |
| Yangzhou           | 1         | 1.12%   |
| Woodford           | 1         | 1.12%   |
| Woldegk            | 1         | 1.12%   |
| Warsaw             | 1         | 1.12%   |
| Villeurbanne       | 1         | 1.12%   |
| Verneuil-sur-Seine | 1         | 1.12%   |
| Valpacos           | 1         | 1.12%   |
| Trento             | 1         | 1.12%   |
| Tremestieri Etneo  | 1         | 1.12%   |
| Tottenham          | 1         | 1.12%   |
| Tolyatti           | 1         | 1.12%   |
| Tehran             | 1         | 1.12%   |
| Stockholm          | 1         | 1.12%   |
| Staten Island      | 1         | 1.12%   |
| St Petersburg      | 1         | 1.12%   |
| Southampton        | 1         | 1.12%   |
| South Deerfield    | 1         | 1.12%   |
| Smolensk           | 1         | 1.12%   |
| Singapore          | 1         | 1.12%   |
| Saratov            | 1         | 1.12%   |
| Riga               | 1         | 1.12%   |
| Rho                | 1         | 1.12%   |
| Prague             | 1         | 1.12%   |
| Plymouth           | 1         | 1.12%   |
| Pittsburgh         | 1         | 1.12%   |
| Odense             | 1         | 1.12%   |
| Nukuiminamicho     | 1         | 1.12%   |
| Nantes             | 1         | 1.12%   |
| Mykolayiv          | 1         | 1.12%   |
| Montpellier        | 1         | 1.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 30        | 41     | 29.7%   |
| Sandisk                     | 10        | 10     | 9.9%    |
| WDC                         | 7         | 7      | 6.93%   |
| SK hynix                    | 7         | 10     | 6.93%   |
| Micron Technology           | 6         | 7      | 5.94%   |
| Toshiba                     | 5         | 5      | 4.95%   |
| Kingston                    | 4         | 4      | 3.96%   |
| Apple                       | 4         | 6      | 3.96%   |
| Unknown                     | 3         | 3      | 2.97%   |
| Crucial                     | 3         | 4      | 2.97%   |
| Yangtze Memory Technologies | 2         | 2      | 1.98%   |
| Transcend                   | 2         | 2      | 1.98%   |
| Seagate                     | 2         | 3      | 1.98%   |
| KIOXIA                      | 2         | 3      | 1.98%   |
| Kingston Technology Company | 2         | 2      | 1.98%   |
| A-DATA Technology           | 2         | 2      | 1.98%   |
| SPCC                        | 1         | 1      | 0.99%   |
| Intel                       | 1         | 1      | 0.99%   |
| INNOVATION IT               | 1         | 1      | 0.99%   |
| Hitachi                     | 1         | 1      | 0.99%   |
| HGST                        | 1         | 1      | 0.99%   |
| Dogfish                     | 1         | 1      | 0.99%   |
| China                       | 1         | 1      | 0.99%   |
| Biwin Storage Technology    | 1         | 1      | 0.99%   |
| BIWIN                       | 1         | 1      | 0.99%   |
| ADATA Technology            | 1         | 2      | 0.99%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 6         | 5.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 3.74%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB             | 2         | 1.87%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 1.87%   |
| Samsung PM9A1 NVMe 1024GB                           | 2         | 1.87%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 1.87%   |
| Apple SSD SM0512G 500GB                             | 2         | 1.87%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                | 1         | 0.93%   |
| Yangtze Memory YMTC PC300-1TB-B                     | 1         | 0.93%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                    | 1         | 0.93%   |
| WDC WDS200T1X0E-00AFY0 2TB                          | 1         | 0.93%   |
| WDC WD10 JPLX-00MBPT0 1TB                           | 1         | 0.93%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                  | 1         | 0.93%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 0.93%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB                  | 1         | 0.93%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB                | 1         | 0.93%   |
| Unknown MMC Card  64GB                              | 1         | 0.93%   |
| Unknown MMC Card  250GB                             | 1         | 0.93%   |
| Unknown MMC Card  128GB                             | 1         | 0.93%   |
| Transcend TS256GMTS800 256GB SSD                    | 1         | 0.93%   |
| Transcend TS256GMTS430S 256GB SSD                   | 1         | 0.93%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 0.93%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.93%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 0.93%   |
| Toshiba KXG6AZNV512G 512GB                          | 1         | 0.93%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 0.93%   |
| SPCC 2.5 SSD 1TB                                    | 1         | 0.93%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 0.93%   |
| SK hynix PC801 NVMe 512GB                           | 1         | 0.93%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 1         | 0.93%   |
| SK hynix NVMe SSD Drive 1TB                         | 1         | 0.93%   |
| SK hynix NVMe SSD Drive 1024GB                      | 1         | 0.93%   |
| SK hynix HFM001TD3JX013N 1TB                        | 1         | 0.93%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 0.93%   |
| Sandisk WD_BLACK SN770 2TB                          | 1         | 0.93%   |
| Sandisk WD_BLACK SN770 1TB                          | 1         | 0.93%   |
| Sandisk WD Blue SN570 1TB                           | 1         | 0.93%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 500GB     | 1         | 0.93%   |
| Sandisk WD Black SN850 1TB                          | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 33.33%  |
| Seagate | 2         | 3      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |
| Apple   | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 33.33%  |
| SanDisk             | 3         | 3      | 10%     |
| Apple               | 3         | 5      | 10%     |
| Transcend           | 2         | 2      | 6.67%   |
| Micron Technology   | 2         | 2      | 6.67%   |
| Crucial             | 2         | 3      | 6.67%   |
| WDC                 | 1         | 1      | 3.33%   |
| SPCC                | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 1      | 3.33%   |
| Kingston            | 1         | 1      | 3.33%   |
| INNOVATION IT       | 1         | 1      | 3.33%   |
| Dogfish             | 1         | 1      | 3.33%   |
| China               | 1         | 1      | 3.33%   |
| BIWIN               | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 56        | 74     | 58.95%  |
| SSD  | 27        | 35     | 28.42%  |
| HDD  | 9         | 10     | 9.47%   |
| MMC  | 3         | 3      | 3.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 56        | 74     | 61.54%  |
| SATA | 29        | 42     | 31.87%  |
| SAS  | 3         | 3      | 3.3%    |
| MMC  | 3         | 3      | 3.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 30     | 64.86%  |
| 0.51-1.0   | 12        | 14     | 32.43%  |
| 1.01-2.0   | 1         | 1      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 33        | 38.37%  |
| 1-20           | 20        | 23.26%  |
| 251-500        | 9         | 10.47%  |
| 101-250        | 7         | 8.14%   |
| 1001-2000      | 5         | 5.81%   |
| 501-1000       | 5         | 5.81%   |
| More than 3000 | 4         | 4.65%   |
| 2001-3000      | 3         | 3.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| Unknown   | 33        | 37.93%  |
| 1-20      | 22        | 25.29%  |
| 101-250   | 10        | 11.49%  |
| 51-100    | 6         | 6.9%    |
| 21-50     | 5         | 5.75%   |
| 501-1000  | 5         | 5.75%   |
| 251-500   | 4         | 4.6%    |
| 2001-3000 | 1         | 1.15%   |
| 1001-2000 | 1         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10 JPLX-00MBPT0 1TB                      | 1         | 1      | 20%     |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 20%     |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 20%     |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 20%     |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 2      | 40%     |
| WDC               | 1         | 1      | 20%     |
| SK hynix          | 1         | 1      | 20%     |
| Micron Technology | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| NVMe | 1         | 1      | 20%     |
| SSD  | 1         | 1      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 77        | 103    | 82.8%   |
| Detected | 10        | 13     | 10.75%  |
| Malfunc  | 5         | 5      | 5.38%   |
| Failed   | 1         | 1      | 1.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 39        | 36.79%  |
| Samsung Electronics          | 24        | 22.64%  |
| SanDisk                      | 12        | 11.32%  |
| SK hynix                     | 6         | 5.66%   |
| Kingston Technology Company  | 5         | 4.72%   |
| Micron Technology            | 4         | 3.77%   |
| AMD                          | 4         | 3.77%   |
| Toshiba America Info Systems | 3         | 2.83%   |
| ADATA Technology             | 3         | 2.83%   |
| Yangtze Memory Technologies  | 2         | 1.89%   |
| Micron/Crucial Technology    | 1         | 0.94%   |
| Marvell Technology Group     | 1         | 0.94%   |
| KIOXIA                       | 1         | 0.94%   |
| Biwin Storage Technology     | 1         | 0.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 11        | 10.28%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 8         | 7.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 7         | 6.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 5         | 4.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 4         | 3.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 3.74%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 4         | 3.74%   |
| SanDisk WD Black SN770 NVMe SSD                                               | 3         | 2.8%    |
| Kingston Company Company Non-Volatile memory controller                       | 3         | 2.8%    |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 2.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 2.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 3         | 2.8%    |
| Yangtze Memory Non-Volatile memory controller                                 | 2         | 1.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 2         | 1.87%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 1.87%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 2         | 1.87%   |
| Samsung NVMe SSD Controller SM951/PM951                                       | 2         | 1.87%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 1.87%   |
| Samsung Electronics SATA controller                                           | 2         | 1.87%   |
| Micron NVMe Storage Controller                                                | 2         | 1.87%   |
| Micron 2450 NVMe SSD (DRAM-less)                                              | 2         | 1.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.87%   |
| Intel Tiger Lake SATA AHCI Controller                                         | 2         | 1.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 2         | 1.87%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                          | 1         | 0.93%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                            | 1         | 0.93%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                            | 1         | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 0.93%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 0.93%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 0.93%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 0.93%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 0.93%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                    | 1         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                | 1         | 0.93%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                         | 1         | 0.93%   |
| Kingston Company OM3PDP3 NVMe SSD                                             | 1         | 0.93%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 1         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 56        | 55.45%  |
| SATA | 38        | 37.62%  |
| RAID | 7         | 6.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 61        | 74.39%  |
| AMD    | 21        | 25.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 4.88%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 4         | 4.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 4         | 4.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 3.66%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 3.66%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 3.66%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 3         | 3.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 2.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 2.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 2.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 2.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 2         | 2.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 2         | 2.44%   |
| Intel 12th Gen Core i7-1260P               | 2         | 2.44%   |
| Intel 12th Gen Core i5-1240P               | 2         | 2.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 2.44%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 2.44%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 1.22%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 1.22%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 1.22%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 1.22%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 1.22%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 1.22%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz         | 1         | 1.22%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 1.22%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 1.22%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz         | 1         | 1.22%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 1         | 1.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 1.22%   |
| Intel Core i5-9300H CPU @ 2.40GHz          | 1         | 1.22%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 1         | 1.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 1         | 1.22%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 1         | 1.22%   |
| Intel Core i3-10110U CPU @ 2.10GHz         | 1         | 1.22%   |
| Intel Celeron N4120 CPU @ 1.10GHz          | 1         | 1.22%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 1         | 1.22%   |
| Intel Celeron N4020 CPU @ 1.10GHz          | 1         | 1.22%   |
| Intel Atom CPU N280 @ 1.66GHz              | 1         | 1.22%   |
| Intel 13th Gen Core i9-13900HX             | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 25        | 30.49%  |
| Other           | 16        | 19.51%  |
| AMD Ryzen 7     | 13        | 15.85%  |
| Intel Core i5   | 12        | 14.63%  |
| AMD Ryzen 7 PRO | 5         | 6.1%    |
| Intel Celeron   | 3         | 3.66%   |
| AMD Ryzen 9     | 3         | 3.66%   |
| Intel Xeon      | 1         | 1.22%   |
| Intel Core m3   | 1         | 1.22%   |
| Intel Core i9   | 1         | 1.22%   |
| Intel Core i3   | 1         | 1.22%   |
| Intel Atom      | 1         | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 29        | 35.37%  |
| 8      | 26        | 31.71%  |
| 2      | 17        | 20.73%  |
| 12     | 5         | 6.1%    |
| 6      | 3         | 3.66%   |
| 24     | 1         | 1.22%   |
| 1      | 1         | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 78        | 95.12%  |
| 1      | 4         | 4.88%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 81        | 97.59%  |
| 32-bit         | 1         | 1.2%    |
| Unknown        | 1         | 1.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 28.24%  |
| 0x0a50000c | 9         | 10.59%  |
| 0x08600106 | 5         | 5.88%   |
| 0x806ea    | 4         | 4.71%   |
| 0x806c1    | 4         | 4.71%   |
| 0x406e3    | 4         | 4.71%   |
| 0x806ec    | 3         | 3.53%   |
| 0x806eb    | 3         | 3.53%   |
| 0x906ea    | 2         | 2.35%   |
| 0x906a3    | 2         | 2.35%   |
| 0x806e9    | 2         | 2.35%   |
| 0x706a8    | 2         | 2.35%   |
| 0x40661    | 2         | 2.35%   |
| 0x40651    | 2         | 2.35%   |
| 0x306d4    | 2         | 2.35%   |
| 0x306c3    | 2         | 2.35%   |
| 0x0a404102 | 2         | 2.35%   |
| 0x08600104 | 2         | 2.35%   |
| 0x906ed    | 1         | 1.18%   |
| 0x906e9    | 1         | 1.18%   |
| 0x806d1    | 1         | 1.18%   |
| 0x706a1    | 1         | 1.18%   |
| 0x506e3    | 1         | 1.18%   |
| 0x306a9    | 1         | 1.18%   |
| 0x0a704103 | 1         | 1.18%   |
| 0x0a50000b | 1         | 1.18%   |
| 0x0a404101 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 25.61%  |
| Zen 3            | 10        | 12.2%   |
| Skylake          | 9         | 10.98%  |
| Zen 2            | 7         | 8.54%   |
| Haswell          | 7         | 8.54%   |
| Unknown          | 7         | 8.54%   |
| TigerLake        | 6         | 7.32%   |
| Alderlake Hybrid | 5         | 6.1%    |
| Goldmont plus    | 3         | 3.66%   |
| IvyBridge        | 2         | 2.44%   |
| Icelake          | 2         | 2.44%   |
| Broadwell        | 2         | 2.44%   |
| Bonnell          | 1         | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 51.33%  |
| Nvidia | 29        | 25.66%  |
| AMD    | 26        | 23.01%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 9         | 7.76%   |
| AMD Renoir                                                                            | 7         | 6.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 5.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 6         | 5.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 4.31%   |
| Intel UHD Graphics 620                                                                | 5         | 4.31%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 5         | 4.31%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 3.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 3.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 2.59%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 3         | 2.59%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 2.59%   |
| Intel HD Graphics 530                                                                 | 3         | 2.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 2.59%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 2.59%   |
| AMD Rembrandt [Radeon 680M]                                                           | 3         | 2.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 1.72%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 1.72%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.72%   |
| Intel HD Graphics 620                                                                 | 2         | 1.72%   |
| Intel HD Graphics 5500                                                                | 2         | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 1.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 1.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 1.72%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 2         | 1.72%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.86%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                | 1         | 0.86%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 0.86%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.86%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 0.86%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 0.86%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 0.86%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 0.86%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 1         | 0.86%   |
| Nvidia GK106GLM [Quadro K2100M]                                                       | 1         | 0.86%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 0.86%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 1         | 0.86%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                    | 1         | 0.86%   |
| Nvidia AD104M [GeForce RTX 4080 Max-Q / Mobile]                                       | 1         | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 40.24%  |
| Intel + Nvidia | 20        | 24.39%  |
| 1 x AMD        | 13        | 15.85%  |
| AMD + Nvidia   | 7         | 8.54%   |
| Intel + AMD    | 4         | 4.88%   |
| 2 x AMD        | 2         | 2.44%   |
| 1 x Nvidia     | 2         | 2.44%   |
| 2 x Intel      | 1         | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 77.11%  |
| Proprietary | 17        | 20.48%  |
| Unknown     | 2         | 2.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 60%     |
| 0.01-0.5   | 13        | 15.29%  |
| 1.01-2.0   | 10        | 11.76%  |
| 3.01-4.0   | 7         | 8.24%   |
| 0.51-1.0   | 3         | 3.53%   |
| 7.01-8.0   | 1         | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 16        | 16.16%  |
| BOE                  | 13        | 13.13%  |
| LG Display           | 11        | 11.11%  |
| Samsung Electronics  | 9         | 9.09%   |
| Dell                 | 8         | 8.08%   |
| Chimei Innolux       | 7         | 7.07%   |
| Sharp                | 5         | 5.05%   |
| PANDA                | 5         | 5.05%   |
| CSO                  | 5         | 5.05%   |
| Apple                | 3         | 3.03%   |
| Panasonic            | 2         | 2.02%   |
| InfoVision           | 2         | 2.02%   |
| Hewlett-Packard      | 2         | 2.02%   |
| TMX                  | 1         | 1.01%   |
| Philips              | 1         | 1.01%   |
| Lenovo               | 1         | 1.01%   |
| JDI                  | 1         | 1.01%   |
| HannStar             | 1         | 1.01%   |
| Goldstar             | 1         | 1.01%   |
| Eizo                 | 1         | 1.01%   |
| ASUSTek Computer     | 1         | 1.01%   |
| AOC                  | 1         | 1.01%   |
| Ancor Communications | 1         | 1.01%   |
| Acer                 | 1         | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch          | 2         | 2.02%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 2         | 2.02%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 2.02%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 2.02%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 2.02%   |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch               | 1         | 1.01%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 1.01%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 1.01%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 1.01%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 1.01%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 1.01%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch     | 1         | 1.01%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 1.01%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 1         | 1.01%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 1.01%   |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch     | 1         | 1.01%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1         | 1.01%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 1.01%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch               | 1         | 1.01%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 1.01%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.01%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 1         | 1.01%   |
| LG Display LCD Monitor LGD06CE 1920x1200 288x180mm 13.4-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 1         | 1.01%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 1.01%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 1.01%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.01%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 1.01%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 1.01%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 40.43%  |
| 3840x2160 (4K)     | 13        | 13.83%  |
| 1366x768 (WXGA)    | 11        | 11.7%   |
| 2560x1440 (QHD)    | 9         | 9.57%   |
| 2880x1800          | 6         | 6.38%   |
| 2560x1600          | 5         | 5.32%   |
| 1920x1200 (WUXGA)  | 3         | 3.19%   |
| 3440x1440          | 2         | 2.13%   |
| 2256x1504          | 2         | 2.13%   |
| 3840x2400          | 1         | 1.06%   |
| 1920x1280          | 1         | 1.06%   |
| 1680x1050 (WSXGA+) | 1         | 1.06%   |
| 1280x1024 (SXGA)   | 1         | 1.06%   |
| 1024x600           | 1         | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 28        | 28.57%  |
| 14     | 19        | 19.39%  |
| 13     | 13        | 13.27%  |
| 27     | 7         | 7.14%   |
| 12     | 7         | 7.14%   |
| 24     | 5         | 5.1%    |
| 17     | 5         | 5.1%    |
| 16     | 4         | 4.08%   |
| 23     | 3         | 3.06%   |
| 34     | 2         | 2.04%   |
| 31     | 2         | 2.04%   |
| 46     | 1         | 1.02%   |
| 22     | 1         | 1.02%   |
| 10     | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 55.67%  |
| 201-300     | 18        | 18.56%  |
| 501-600     | 14        | 14.43%  |
| 351-400     | 4         | 4.12%   |
| 601-700     | 3         | 3.09%   |
| 701-800     | 2         | 2.06%   |
| 401-500     | 1         | 1.03%   |
| 1001-1500   | 1         | 1.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 62        | 73.81%  |
| 16/10 | 16        | 19.05%  |
| 3/2   | 3         | 3.57%   |
| 21/9  | 2         | 2.38%   |
| 5/4   | 1         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 28.57%  |
| 81-90          | 25        | 25.51%  |
| 201-250        | 8         | 8.16%   |
| 71-80          | 7         | 7.14%   |
| 61-70          | 7         | 7.14%   |
| 301-350        | 7         | 7.14%   |
| 351-500        | 4         | 4.08%   |
| 121-130        | 4         | 4.08%   |
| 111-120        | 4         | 4.08%   |
| 41-50          | 1         | 1.02%   |
| 251-300        | 1         | 1.02%   |
| 141-150        | 1         | 1.02%   |
| 501-1000       | 1         | 1.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 37.36%  |
| 161-240       | 24        | 26.37%  |
| More than 240 | 11        | 12.09%  |
| 101-120       | 11        | 12.09%  |
| 51-100        | 10        | 10.99%  |
| 1-50          | 1         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 61        | 70.11%  |
| 2     | 19        | 21.84%  |
| 0     | 5         | 5.75%   |
| 3     | 2         | 2.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 64        | 50.79%  |
| Realtek Semiconductor             | 39        | 30.95%  |
| Qualcomm Atheros                  | 6         | 4.76%   |
| MediaTek                          | 4         | 3.17%   |
| Broadcom                          | 3         | 2.38%   |
| Qualcomm                          | 2         | 1.59%   |
| Lenovo                            | 2         | 1.59%   |
| Xiaomi                            | 1         | 0.79%   |
| QinHeng Electronics               | 1         | 0.79%   |
| Microsoft                         | 1         | 0.79%   |
| Fibocom                           | 1         | 0.79%   |
| Ericsson Business Mobile Networks | 1         | 0.79%   |
| D-Link                            | 1         | 0.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 15.03%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 9.8%    |
| Intel Wi-Fi 6 AX200                                               | 13        | 8.5%    |
| Intel Wireless 8260                                               | 6         | 3.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 3.92%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 3.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 2.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 2.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 1.96%   |
| Intel Wireless-AC 9260                                            | 3         | 1.96%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.96%   |
| Intel Wireless 7265                                               | 3         | 1.96%   |
| Intel Wireless 7260                                               | 3         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.31%   |
| Intel Wireless 3165                                               | 2         | 1.31%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.31%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.31%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.31%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.31%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 1.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.65%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.65%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.65%   |
| QinHeng USB Single Serial                                         | 1         | 0.65%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.65%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 76.19%  |
| Qualcomm Atheros      | 6         | 7.14%   |
| MediaTek              | 4         | 4.76%   |
| Broadcom              | 3         | 3.57%   |
| Realtek Semiconductor | 2         | 2.38%   |
| Qualcomm              | 2         | 2.38%   |
| Microsoft             | 1         | 1.19%   |
| Fibocom               | 1         | 1.19%   |
| D-Link                | 1         | 1.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 13        | 15.48%  |
| Intel Wireless 8260                                            | 6         | 7.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 7.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 4.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 4.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 4.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 3.57%   |
| Intel Wireless-AC 9260                                         | 3         | 3.57%   |
| Intel Wireless 8265 / 8275                                     | 3         | 3.57%   |
| Intel Wireless 7265                                            | 3         | 3.57%   |
| Intel Wireless 7260                                            | 3         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.57%   |
| Intel Wireless 3165                                            | 2         | 2.38%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.38%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 2.38%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.19%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.19%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 1.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.19%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.19%   |
| Intel Wireless 3160                                            | 1         | 1.19%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 1         | 1.19%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 1.19%   |
| D-Link 802.11ac NIC                                            | 1         | 1.19%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 38        | 62.3%   |
| Intel                 | 19        | 31.15%  |
| Lenovo                | 2         | 3.28%   |
| Xiaomi                | 1         | 1.64%   |
| Qualcomm Atheros      | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 34.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 22.39%  |
| Intel Ethernet Connection I219-LM                                 | 5         | 7.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 4.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.99%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.99%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.99%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.49%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.49%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.49%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.49%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 81        | 57.04%  |
| Ethernet | 59        | 41.55%  |
| Modem    | 2         | 1.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 84.04%  |
| Ethernet | 15        | 15.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 54.88%  |
| 1     | 35        | 42.68%  |
| 3     | 2         | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 77.11%  |
| Yes  | 19        | 22.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 77.63%  |
| Qualcomm Atheros Communications | 3         | 3.95%   |
| MediaTek                        | 3         | 3.95%   |
| Apple                           | 3         | 3.95%   |
| Realtek Semiconductor           | 2         | 2.63%   |
| USI                             | 1         | 1.32%   |
| Lite-On Technology              | 1         | 1.32%   |
| IMC Networks                    | 1         | 1.32%   |
| Foxconn / Hon Hai               | 1         | 1.32%   |
| Broadcom                        | 1         | 1.32%   |
| ASUSTek Computer                | 1         | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 15        | 19.74%  |
| Intel AX200 Bluetooth                          | 13        | 17.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 8         | 10.53%  |
| Intel AX201 Bluetooth                          | 7         | 9.21%   |
| Intel AX210 Bluetooth                          | 6         | 7.89%   |
| Intel Bluetooth Device                         | 5         | 6.58%   |
| MediaTek Wireless_Device                       | 3         | 3.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 3         | 3.95%   |
| Apple Bluetooth Host Controller                | 3         | 3.95%   |
| Realtek Bluetooth Radio                        | 2         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 2.63%   |
| USI Bluetooth Device                           | 1         | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 1.32%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.32%   |
| IMC Networks Bluetooth Device                  | 1         | 1.32%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 1         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 1.32%   |
| ASUS Broadcom Bluetooth 2.1                    | 1         | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 62        | 52.1%   |
| AMD                       | 23        | 19.33%  |
| Nvidia                    | 14        | 11.76%  |
| Lenovo                    | 4         | 3.36%   |
| C-Media Electronics       | 3         | 2.52%   |
| Synaptics                 | 2         | 1.68%   |
| Realtek Semiconductor     | 2         | 1.68%   |
| Trust                     | 1         | 0.84%   |
| Sennheiser Communications | 1         | 0.84%   |
| Satechi                   | 1         | 0.84%   |
| Logitech                  | 1         | 0.84%   |
| Kingston Technology       | 1         | 0.84%   |
| Focusrite-Novation        | 1         | 0.84%   |
| Creative Technology       | 1         | 0.84%   |
| Corsair                   | 1         | 0.84%   |
| (LCS) USB Audio Device    | 1         | 0.84%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 21        | 14.29%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 15        | 10.2%   |
| Intel Sunrise Point-LP HD Audio                                         | 14        | 9.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 6         | 4.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 5         | 3.4%    |
| Intel Cannon Lake PCH cAVS                                              | 5         | 3.4%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 5         | 3.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 5         | 3.4%    |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 2.72%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 4         | 2.72%   |
| Nvidia GA106 High Definition Audio Controller                           | 3         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 3         | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 3         | 2.04%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 1.36%   |
| Realtek Semiconductor USB Audio                                         | 2         | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                         | 2         | 1.36%   |
| Nvidia GA104 High Definition Audio Controller                           | 2         | 1.36%   |
| Nvidia Audio device                                                     | 2         | 1.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 2         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                   | 2         | 1.36%   |
| Intel Comet Lake PCH-LP cAVS                                            | 2         | 1.36%   |
| Intel Broadwell-U Audio Controller                                      | 2         | 1.36%   |
| Intel 8 Series HD Audio Controller                                      | 2         | 1.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 2         | 1.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 1.36%   |
| Trust USB microphone                                                    | 1         | 0.68%   |
| Sennheiser Communications Headset [PC 8]                                | 1         | 0.68%   |
| Satechi Audio & PD Adapter                                              | 1         | 0.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 1         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 1         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                      | 1         | 0.68%   |
| Nvidia GK106 HDMI Audio Controller                                      | 1         | 0.68%   |
| Logitech Blue Microphones                                               | 1         | 0.68%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                               | 1         | 0.68%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                            | 1         | 0.68%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                            | 1         | 0.68%   |
| Lenovo ThinkPad Dock USB Audio                                          | 1         | 0.68%   |
| Kingston Technology HyperX 7.1 Audio                                    | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 32        | 32.65%  |
| Micron Technology            | 17        | 17.35%  |
| SK hynix                     | 13        | 13.27%  |
| Crucial                      | 9         | 9.18%   |
| Kingston                     | 5         | 5.1%    |
| Unknown                      | 4         | 4.08%   |
| Unknown (ABCD)               | 3         | 3.06%   |
| Team                         | 3         | 3.06%   |
| Ramaxel Technology           | 2         | 2.04%   |
| A-DATA Technology            | 2         | 2.04%   |
| Patriot Memory (PDP Systems) | 1         | 1.02%   |
| Patriot                      | 1         | 1.02%   |
| GOODRAM                      | 1         | 1.02%   |
| G.Skill                      | 1         | 1.02%   |
| Corsair                      | 1         | 1.02%   |
| Avant                        | 1         | 1.02%   |
| AMD                          | 1         | 1.02%   |
| Unknown                      | 1         | 1.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 2.83%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 2         | 1.89%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.89%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.89%   |
| Samsung RAM M471A2K43BB1-CPB 16384MB SODIMM DDR4 2133MT/s        | 2         | 1.89%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.89%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.89%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.89%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.89%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.94%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.94%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.94%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.94%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.94%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.94%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.94%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.94%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.94%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.94%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.94%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.94%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.94%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.94%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 1         | 0.94%   |
| SK hynix RAM H9JCNNNBK3MLYR-N6E 1GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.94%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.94%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.94%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.94%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.94%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.94%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 0.94%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1600MT/s                   | 1         | 0.94%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 0.94%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 0.94%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 44        | 54.32%  |
| DDR3   | 12        | 14.81%  |
| LPDDR4 | 11        | 13.58%  |
| LPDDR5 | 7         | 8.64%   |
| LPDDR3 | 4         | 4.94%   |
| DDR5   | 2         | 2.47%   |
| SDRAM  | 1         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 76.19%  |
| Row Of Chips | 17        | 20.24%  |
| Chip         | 2         | 2.38%   |
| Unknown      | 1         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 39        | 42.86%  |
| 16384 | 21        | 23.08%  |
| 4096  | 15        | 16.48%  |
| 32768 | 11        | 12.09%  |
| 2048  | 4         | 4.4%    |
| 1024  | 1         | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 20        | 23.81%  |
| 2667    | 17        | 20.24%  |
| 1600    | 11        | 13.1%   |
| 2133    | 8         | 9.52%   |
| 6400    | 7         | 8.33%   |
| 4267    | 6         | 7.14%   |
| 2400    | 6         | 7.14%   |
| 4266    | 2         | 2.38%   |
| 3266    | 2         | 2.38%   |
| 1867    | 2         | 2.38%   |
| 5600    | 1         | 1.19%   |
| 4800    | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 19        | 25.33%  |
| Microdia                      | 12        | 16%     |
| IMC Networks                  | 11        | 14.67%  |
| Realtek Semiconductor         | 7         | 9.33%   |
| Acer                          | 6         | 8%      |
| Bison Electronics             | 5         | 6.67%   |
| Sunplus Innovation Technology | 3         | 4%      |
| Logitech                      | 3         | 4%      |
| Lite-On Technology            | 3         | 4%      |
| Quanta                        | 2         | 2.67%   |
| Syntek                        | 1         | 1.33%   |
| Luxvisions Innotech Limited   | 1         | 1.33%   |
| Alcor Micro                   | 1         | 1.33%   |
| 2M UVC CAMERA                 | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 12        | 15.79%  |
| Microdia Integrated_Webcam_HD                     | 6         | 7.89%   |
| IMC Networks Integrated Camera                    | 5         | 6.58%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 4         | 5.26%   |
| Chicony HP HD Camera                              | 4         | 5.26%   |
| Sunplus Integrated_Webcam_FHD                     | 2         | 2.63%   |
| Realtek Laptop Camera                             | 2         | 2.63%   |
| Realtek Integrated_Webcam_HD                      | 2         | 2.63%   |
| Quanta VGA WebCam                                 | 2         | 2.63%   |
| Microdia Webcam Vitade AF                         | 2         | 2.63%   |
| Logitech HD Pro Webcam C920                       | 2         | 2.63%   |
| Lite-On Integrated Camera                         | 2         | 2.63%   |
| Bison Integrated Camera                           | 2         | 2.63%   |
| Acer Integrated IR Camera                         | 2         | 2.63%   |
| Acer HD Webcam                                    | 2         | 2.63%   |
| Syntek Integrated Camera                          | 1         | 1.32%   |
| Sunplus Integrated_Webcam_HD                      | 1         | 1.32%   |
| Realtek TV Camera                                 | 1         | 1.32%   |
| Realtek Realtek USB MIC                           | 1         | 1.32%   |
| Realtek Lenovo EasyCamera                         | 1         | 1.32%   |
| Realtek Integrated Webcam                         | 1         | 1.32%   |
| Microdia USB 2.0 Camera                           | 1         | 1.32%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 1.32%   |
| Microdia Integrated Webcam                        | 1         | 1.32%   |
| Microdia HP Integrated Webcam                     | 1         | 1.32%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1.32%   |
| Logitech Webcam C310                              | 1         | 1.32%   |
| Lite-On HP HD Camera                              | 1         | 1.32%   |
| IMC Networks XHC Camera                           | 1         | 1.32%   |
| IMC Networks USB2.0 UVC 1.3M WebCam               | 1         | 1.32%   |
| Chicony USB2.0 Camera                             | 1         | 1.32%   |
| Chicony Integrated IR Camera                      | 1         | 1.32%   |
| Chicony Integrated Camera [ThinkPad]              | 1         | 1.32%   |
| Bison ThinkPad P50 Integrated Camera              | 1         | 1.32%   |
| Bison SunplusIT Integrated Camera                 | 1         | 1.32%   |
| Bison BisonCam,NB Pro                             | 1         | 1.32%   |
| Alcor Micro USB 2.0 Camera                        | 1         | 1.32%   |
| Acer Integrated RGB Camera                        | 1         | 1.32%   |
| Acer Integrated Camera                            | 1         | 1.32%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam              | 1         | 1.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 45%     |
| Validity Sensors           | 7         | 35%     |
| Shenzhen Goodix Technology | 3         | 15%     |
| Focal-systems.Corp         | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 5         | 25%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 15%     |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 10%     |
| Synaptics UWP WBDI Device                                | 2         | 10%     |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 5%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 5%      |
| Shenzhen Goodix  Fingerprint Device                      | 1         | 5%      |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 10        | 62.5%   |
| Broadcom    | 3         | 18.75%  |
| Yubico.com  | 2         | 12.5%   |
| Upek        | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 10        | 62.5%   |
| Broadcom 5880                                              | 2         | 12.5%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 6.25%   |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 1         | 6.25%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 36        | 42.35%  |
| 1     | 29        | 34.12%  |
| 2     | 17        | 20%     |
| 4     | 2         | 2.35%   |
| 3     | 1         | 1.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 25.35%  |
| Multimedia controller    | 14        | 19.72%  |
| Graphics card            | 13        | 18.31%  |
| Chipcard                 | 12        | 16.9%   |
| Net/wireless             | 3         | 4.23%   |
| Bluetooth                | 3         | 4.23%   |
| Modem                    | 2         | 2.82%   |
| Card reader              | 2         | 2.82%   |
| Camera                   | 2         | 2.82%   |
| Network                  | 1         | 1.41%   |
| Communication controller | 1         | 1.41%   |

