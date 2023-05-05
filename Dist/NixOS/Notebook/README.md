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

Total: 97

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| NixOS 22.11                      | 25        | 32.89%  |
| NixOS 22.05                      | 18        | 23.68%  |
| NixOS 23.05                      | 10        | 13.16%  |
| NixOS 21.11                      | 9         | 11.84%  |
| NixOS                            | 2         | 2.63%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 1.32%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 1.32%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 1.32%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 1.32%   |
| NixOS 21.05.2132.733682c3292     | 1         | 1.32%   |
| NixOS 21.05.20210423.c21475e     | 1         | 1.32%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 1.32%   |
| NixOS 20.09pre-git               | 1         | 1.32%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 1.32%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 1.32%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 1.32%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 1.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 66        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Notebooks | Percent |
|------------------|-----------|---------|
| 5.15.74          | 3         | 3.8%    |
| 5.15.43          | 3         | 3.8%    |
| 6.1.0            | 2         | 2.53%   |
| 6.0.10           | 2         | 2.53%   |
| 5.16.15          | 2         | 2.53%   |
| 5.15.72          | 2         | 2.53%   |
| 5.15.68          | 2         | 2.53%   |
| 5.15.64          | 2         | 2.53%   |
| 5.15.26          | 2         | 2.53%   |
| 5.13.7           | 2         | 2.53%   |
| 6.2.9-lqx1       | 1         | 1.27%   |
| 6.2.8            | 1         | 1.27%   |
| 6.2.7            | 1         | 1.27%   |
| 6.2.0            | 1         | 1.27%   |
| 6.1.7-xanmod1    | 1         | 1.27%   |
| 6.1.25           | 1         | 1.27%   |
| 6.1.24           | 1         | 1.27%   |
| 6.1.21           | 1         | 1.27%   |
| 6.1.1            | 1         | 1.27%   |
| 6.0.2-xanmod1-tt | 1         | 1.27%   |
| 6.0.11           | 1         | 1.27%   |
| 6.0.10-zen2      | 1         | 1.27%   |
| 6.0.0-xanmod1    | 1         | 1.27%   |
| 5.8.4            | 1         | 1.27%   |
| 5.8.16-hardened  | 1         | 1.27%   |
| 5.8.11           | 1         | 1.27%   |
| 5.7.4            | 1         | 1.27%   |
| 5.7.17           | 1         | 1.27%   |
| 5.4.24           | 1         | 1.27%   |
| 5.4.209          | 1         | 1.27%   |
| 5.4.187          | 1         | 1.27%   |
| 5.19.2           | 1         | 1.27%   |
| 5.19.17          | 1         | 1.27%   |
| 5.19.0           | 1         | 1.27%   |
| 5.18.7-zen1      | 1         | 1.27%   |
| 5.18.0           | 1         | 1.27%   |
| 5.17.1           | 1         | 1.27%   |
| 5.17.0           | 1         | 1.27%   |
| 5.16.8-zen1      | 1         | 1.27%   |
| 5.16.7           | 1         | 1.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.10  | 3         | 3.8%    |
| 5.15.74 | 3         | 3.8%    |
| 5.15.43 | 3         | 3.8%    |
| 6.1.0   | 2         | 2.53%   |
| 5.16.15 | 2         | 2.53%   |
| 5.15.72 | 2         | 2.53%   |
| 5.15.68 | 2         | 2.53%   |
| 5.15.64 | 2         | 2.53%   |
| 5.15.26 | 2         | 2.53%   |
| 5.13.7  | 2         | 2.53%   |
| 6.2.9   | 1         | 1.27%   |
| 6.2.8   | 1         | 1.27%   |
| 6.2.7   | 1         | 1.27%   |
| 6.2.0   | 1         | 1.27%   |
| 6.1.7   | 1         | 1.27%   |
| 6.1.25  | 1         | 1.27%   |
| 6.1.24  | 1         | 1.27%   |
| 6.1.21  | 1         | 1.27%   |
| 6.1.1   | 1         | 1.27%   |
| 6.0.2   | 1         | 1.27%   |
| 6.0.11  | 1         | 1.27%   |
| 6.0.0   | 1         | 1.27%   |
| 5.8.4   | 1         | 1.27%   |
| 5.8.16  | 1         | 1.27%   |
| 5.8.11  | 1         | 1.27%   |
| 5.7.4   | 1         | 1.27%   |
| 5.7.17  | 1         | 1.27%   |
| 5.4.24  | 1         | 1.27%   |
| 5.4.209 | 1         | 1.27%   |
| 5.4.187 | 1         | 1.27%   |
| 5.19.2  | 1         | 1.27%   |
| 5.19.17 | 1         | 1.27%   |
| 5.19.0  | 1         | 1.27%   |
| 5.18.7  | 1         | 1.27%   |
| 5.18.0  | 1         | 1.27%   |
| 5.17.1  | 1         | 1.27%   |
| 5.17.0  | 1         | 1.27%   |
| 5.16.8  | 1         | 1.27%   |
| 5.16.7  | 1         | 1.27%   |
| 5.16.3  | 1         | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 40.26%  |
| 6.1     | 7         | 9.09%   |
| 6.0     | 6         | 7.79%   |
| 5.16    | 6         | 7.79%   |
| 6.2     | 4         | 5.19%   |
| 5.8     | 3         | 3.9%    |
| 5.19    | 3         | 3.9%    |
| 5.13    | 3         | 3.9%    |
| 5.10    | 3         | 3.9%    |
| 5.7     | 2         | 2.6%    |
| 5.4     | 2         | 2.6%    |
| 5.18    | 2         | 2.6%    |
| 5.17    | 2         | 2.6%    |
| 4.19    | 2         | 2.6%    |
| 5.12    | 1         | 1.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 65        | 98.48%  |
| i686   | 1         | 1.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 41        | 57.75%  |
| GNOME        | 7         | 9.86%   |
| sway         | 6         | 8.45%   |
| KDE5         | 5         | 7.04%   |
| Hyprland     | 3         | 4.23%   |
| XFCE         | 2         | 2.82%   |
| none+xmonad  | 2         | 2.82%   |
| none+i3      | 2         | 2.82%   |
| none+bspwm   | 1         | 1.41%   |
| none+awesome | 1         | 1.41%   |
| KDE          | 1         | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 43        | 61.43%  |
| X11     | 13        | 18.57%  |
| Wayland | 12        | 17.14%  |
| Tty     | 2         | 2.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 42        | 62.69%  |
| LightDM | 9         | 13.43%  |
| SDDM    | 8         | 11.94%  |
| GDM     | 8         | 11.94%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 30        | 44.12%  |
| en_US   | 29        | 42.65%  |
| en_GB   | 2         | 2.94%   |
| ru_RU   | 1         | 1.47%   |
| ro_RO   | 1         | 1.47%   |
| lv_LV   | 1         | 1.47%   |
| fr_FR   | 1         | 1.47%   |
| en_DK   | 1         | 1.47%   |
| en_CA   | 1         | 1.47%   |
| de_DE   | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 57        | 86.36%  |
| BIOS | 9         | 13.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 37        | 52.86%  |
| Btrfs   | 12        | 17.14%  |
| Xfs     | 7         | 10%     |
| Zfs     | 6         | 8.57%   |
| Tmpfs   | 5         | 7.14%   |
| Unknown | 3         | 4.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 61        | 89.71%  |
| Unknown | 5         | 7.35%   |
| MBR     | 2         | 2.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 77.94%  |
| Yes       | 15        | 22.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 74.24%  |
| Yes       | 17        | 25.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 26        | 39.39%  |
| Dell                   | 13        | 19.7%   |
| ASUSTek Computer       | 7         | 10.61%  |
| Hewlett-Packard        | 4         | 6.06%   |
| GPD                    | 3         | 4.55%   |
| Framework              | 2         | 3.03%   |
| Apple                  | 2         | 3.03%   |
| Acer                   | 2         | 3.03%   |
| Toshiba                | 1         | 1.52%   |
| OBSIDIAN-PC            | 1         | 1.52%   |
| MSI                    | 1         | 1.52%   |
| MECHREVO               | 1         | 1.52%   |
| Gigabyte Technology    | 1         | 1.52%   |
| Blackview              | 1         | 1.52%   |
| Avell High Performance | 1         | 1.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Latitude 7420                       | 2         | 3.03%   |
| Toshiba Satellite L50-B                  | 1         | 1.52%   |
| OBSIDIAN-PC N13_N140ZU                   | 1         | 1.52%   |
| MSI Bravo 15 B5DD                        | 1         | 1.52%   |
| MECHREVO Code01 Ver2.0                   | 1         | 1.52%   |
| Lenovo Yoga Slim 7 13ACN5 82CY           | 1         | 1.52%   |
| Lenovo ThinkPad X390 20Q0CTO1WW          | 1         | 1.52%   |
| Lenovo ThinkPad X260 20F5S6MF02          | 1         | 1.52%   |
| Lenovo ThinkPad X260 20F5S4BY00          | 1         | 1.52%   |
| Lenovo ThinkPad X250 20CLS18S0T          | 1         | 1.52%   |
| Lenovo ThinkPad X230 2333AZ2             | 1         | 1.52%   |
| Lenovo ThinkPad X230 23243E9             | 1         | 1.52%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 1.52%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBCT01WW | 1         | 1.52%   |
| Lenovo ThinkPad T580 20L90024PB          | 1         | 1.52%   |
| Lenovo ThinkPad T540p 20BE005YMH         | 1         | 1.52%   |
| Lenovo ThinkPad T490 20N2000LUK          | 1         | 1.52%   |
| Lenovo ThinkPad T480 20L5CTO1WW          | 1         | 1.52%   |
| Lenovo ThinkPad T460p 20FWCTO1WW         | 1         | 1.52%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW     | 1         | 1.52%   |
| Lenovo ThinkPad T14s Gen 3 21BR000MUS    | 1         | 1.52%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK    | 1         | 1.52%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT     | 1         | 1.52%   |
| Lenovo ThinkPad P50 20EN0005GE           | 1         | 1.52%   |
| Lenovo ThinkPad P14s Gen 3 21J5002KMH    | 1         | 1.52%   |
| Lenovo ThinkPad E470 20H1006JIX          | 1         | 1.52%   |
| Lenovo ThinkPad E14 Gen 4 21EBCTO1WW     | 1         | 1.52%   |
| Lenovo Legion S7 15ACH6 82K8             | 1         | 1.52%   |
| Lenovo Legion 5 17ARH05H 82GN            | 1         | 1.52%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 1         | 1.52%   |
| Lenovo G50-70 20351                      | 1         | 1.52%   |
| HP ZBook Studio G5                       | 1         | 1.52%   |
| HP ProBook 450 G4                        | 1         | 1.52%   |
| HP ProBook 445 G7                        | 1         | 1.52%   |
| HP EliteBook 845 G8 Notebook PC          | 1         | 1.52%   |
| GPD WIN2                                 | 1         | 1.52%   |
| GPD MicroPC                              | 1         | 1.52%   |
| GPD G1621-02                             | 1         | 1.52%   |
| Gigabyte Sabre 15                        | 1         | 1.52%   |
| Framework Laptop (12th Gen Intel Core)   | 1         | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 21        | 31.82%  |
| Dell XPS                   | 6         | 9.09%   |
| ASUS ROG                   | 4         | 6.06%   |
| Dell Latitude              | 3         | 4.55%   |
| Lenovo Legion              | 2         | 3.03%   |
| HP ProBook                 | 2         | 3.03%   |
| Framework Laptop           | 2         | 3.03%   |
| Dell Precision             | 2         | 3.03%   |
| Dell Inspiron              | 2         | 3.03%   |
| Apple MacBookPro11         | 2         | 3.03%   |
| Acer Aspire                | 2         | 3.03%   |
| Toshiba Satellite          | 1         | 1.52%   |
| OBSIDIAN-PC N13            | 1         | 1.52%   |
| MSI Bravo                  | 1         | 1.52%   |
| MECHREVO Code01            | 1         | 1.52%   |
| Lenovo Yoga                | 1         | 1.52%   |
| Lenovo IdeaPad             | 1         | 1.52%   |
| Lenovo G50-70              | 1         | 1.52%   |
| HP ZBook                   | 1         | 1.52%   |
| HP EliteBook               | 1         | 1.52%   |
| GPD WIN2                   | 1         | 1.52%   |
| GPD MicroPC                | 1         | 1.52%   |
| GPD G1621-02               | 1         | 1.52%   |
| Gigabyte Sabre             | 1         | 1.52%   |
| Blackview AceBook          | 1         | 1.52%   |
| Avell High Performance A70 | 1         | 1.52%   |
| ASUS ZenBook               | 1         | 1.52%   |
| ASUS ASUSPRO               | 1         | 1.52%   |
| ASUS 1005HA                | 1         | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 14        | 21.21%  |
| 2020 | 10        | 15.15%  |
| 2019 | 8         | 12.12%  |
| 2016 | 7         | 10.61%  |
| 2022 | 6         | 9.09%   |
| 2018 | 6         | 9.09%   |
| 2013 | 4         | 6.06%   |
| 2017 | 3         | 4.55%   |
| 2015 | 3         | 4.55%   |
| 2014 | 2         | 3.03%   |
| 2012 | 2         | 3.03%   |
| 2009 | 1         | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 66        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 66        | 98.51%  |
| Enabled  | 1         | 1.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 65        | 98.48%  |
| Yes  | 1         | 1.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 20        | 29.85%  |
| 16.01-24.0  | 18        | 26.87%  |
| 8.01-16.0   | 15        | 22.39%  |
| 4.01-8.0    | 7         | 10.45%  |
| 64.01-256.0 | 3         | 4.48%   |
| 3.01-4.0    | 2         | 2.99%   |
| 24.01-32.0  | 1         | 1.49%   |
| 0.51-1.0    | 1         | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 22        | 28.57%  |
| 3.01-4.0   | 14        | 18.18%  |
| 8.01-16.0  | 12        | 15.58%  |
| 2.01-3.0   | 11        | 14.29%  |
| 1.01-2.0   | 6         | 7.79%   |
| 24.01-32.0 | 5         | 6.49%   |
| 0.51-1.0   | 3         | 3.9%    |
| 16.01-24.0 | 2         | 2.6%    |
| 32.01-64.0 | 1         | 1.3%    |
| 0.01-0.5   | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 79.1%   |
| 2      | 13        | 19.4%   |
| 3      | 1         | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 90.91%  |
| Yes       | 6         | 9.09%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 72.46%  |
| No        | 19        | 27.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 98.48%  |
| No        | 1         | 1.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 88.24%  |
| No        | 8         | 11.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 12.12%  |
| France      | 7         | 10.61%  |
| UK          | 5         | 7.58%   |
| Russia      | 4         | 6.06%   |
| Poland      | 4         | 6.06%   |
| Canada      | 4         | 6.06%   |
| Ukraine     | 3         | 4.55%   |
| Netherlands | 3         | 4.55%   |
| Italy       | 3         | 4.55%   |
| Germany     | 3         | 4.55%   |
| Switzerland | 2         | 3.03%   |
| Belgium     | 2         | 3.03%   |
| Austria     | 2         | 3.03%   |
| Uruguay     | 1         | 1.52%   |
| Sweden      | 1         | 1.52%   |
| Spain       | 1         | 1.52%   |
| Slovenia    | 1         | 1.52%   |
| Romania     | 1         | 1.52%   |
| Portugal    | 1         | 1.52%   |
| Latvia      | 1         | 1.52%   |
| Japan       | 1         | 1.52%   |
| Iraq        | 1         | 1.52%   |
| Iran        | 1         | 1.52%   |
| India       | 1         | 1.52%   |
| Denmark     | 1         | 1.52%   |
| Czechia     | 1         | 1.52%   |
| Colombia    | 1         | 1.52%   |
| China       | 1         | 1.52%   |
| Brazil      | 1         | 1.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Vienna             | 2         | 2.74%   |
| Ottawa             | 2         | 2.74%   |
| Marki              | 2         | 2.74%   |
| London             | 2         | 2.74%   |
| Halifax            | 2         | 2.74%   |
| Zurich             | 1         | 1.37%   |
| Yangzhou           | 1         | 1.37%   |
| Woodford           | 1         | 1.37%   |
| Warsaw             | 1         | 1.37%   |
| Villeurbanne       | 1         | 1.37%   |
| Verneuil-sur-Seine | 1         | 1.37%   |
| Valpacos           | 1         | 1.37%   |
| Trento             | 1         | 1.37%   |
| Tottenham          | 1         | 1.37%   |
| Tolyatti           | 1         | 1.37%   |
| Tokyo              | 1         | 1.37%   |
| Tehran             | 1         | 1.37%   |
| Stockholm          | 1         | 1.37%   |
| South Deerfield    | 1         | 1.37%   |
| Saratov            | 1         | 1.37%   |
| Riga               | 1         | 1.37%   |
| Rho                | 1         | 1.37%   |
| Prague             | 1         | 1.37%   |
| Plymouth           | 1         | 1.37%   |
| Pittsburgh         | 1         | 1.37%   |
| Odense             | 1         | 1.37%   |
| Nantes             | 1         | 1.37%   |
| Mykolayiv          | 1         | 1.37%   |
| Montpellier        | 1         | 1.37%   |
| Montevideo         | 1         | 1.37%   |
| Mons               | 1         | 1.37%   |
| Milwaukee          | 1         | 1.37%   |
| Messina            | 1         | 1.37%   |
| Melsele            | 1         | 1.37%   |
| Medvode            | 1         | 1.37%   |
| Meaux              | 1         | 1.37%   |
| Lyon               | 1         | 1.37%   |
| Los Angeles        | 1         | 1.37%   |
| Lehrte             | 1         | 1.37%   |
| Krasnodar          | 1         | 1.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 24        | 33     | 30.38%  |
| SK hynix                    | 7         | 10     | 8.86%   |
| Sandisk                     | 7         | 7      | 8.86%   |
| WDC                         | 6         | 6      | 7.59%   |
| Toshiba                     | 5         | 5      | 6.33%   |
| Micron Technology           | 4         | 4      | 5.06%   |
| Kingston                    | 3         | 3      | 3.8%    |
| Crucial                     | 3         | 4      | 3.8%    |
| Transcend                   | 2         | 2      | 2.53%   |
| Seagate                     | 2         | 3      | 2.53%   |
| KIOXIA                      | 2         | 3      | 2.53%   |
| Kingston Technology Company | 2         | 2      | 2.53%   |
| Apple                       | 2         | 4      | 2.53%   |
| Yangtze Memory Technologies | 1         | 1      | 1.27%   |
| Intel                       | 1         | 1      | 1.27%   |
| INNOVATION IT               | 1         | 1      | 1.27%   |
| Hitachi                     | 1         | 1      | 1.27%   |
| HGST                        | 1         | 1      | 1.27%   |
| Dogfish                     | 1         | 1      | 1.27%   |
| China                       | 1         | 1      | 1.27%   |
| Biwin Storage Technology    | 1         | 1      | 1.27%   |
| BIWIN                       | 1         | 1      | 1.27%   |
| A-DATA Technology           | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| SK hynix SKHynix_HFS001TDE9X084N 1024GB               | 2         | 2.38%   |
| Samsung SSD 850 EVO 500GB                             | 2         | 2.38%   |
| Samsung PM9A1 NVMe 1024GB                             | 2         | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 2         | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 2         | 2.38%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                  | 1         | 1.19%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                      | 1         | 1.19%   |
| WDC WDS200T1X0E-00AFY0 2TB                            | 1         | 1.19%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                    | 1         | 1.19%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                  | 1         | 1.19%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB                    | 1         | 1.19%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB                  | 1         | 1.19%   |
| Transcend TS256GMTS800 256GB SSD                      | 1         | 1.19%   |
| Transcend TS256GMTS430S 256GB SSD                     | 1         | 1.19%   |
| Toshiba MQ01ACF050 500GB                              | 1         | 1.19%   |
| Toshiba MQ01ABD100 1TB                                | 1         | 1.19%   |
| Toshiba MK2565GSXV 250GB                              | 1         | 1.19%   |
| Toshiba KXG6AZNV512G 512GB                            | 1         | 1.19%   |
| Toshiba KXG50ZNV512G NVMe 512GB                       | 1         | 1.19%   |
| SK hynix SC311 SATA 256GB SSD                         | 1         | 1.19%   |
| SK hynix PC801 NVMe 512GB                             | 1         | 1.19%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                  | 1         | 1.19%   |
| SK hynix NVMe SSD Drive 1TB                           | 1         | 1.19%   |
| SK hynix NVMe SSD Drive 1024GB                        | 1         | 1.19%   |
| SK hynix HFM001TD3JX013N 1024GB                       | 1         | 1.19%   |
| Seagate ST2000LM007-1R8174 2TB                        | 1         | 1.19%   |
| Seagate ST1000LM035-1RK172 970GB                      | 1         | 1.19%   |
| Sandisk WD_BLACK SN770 2TB                            | 1         | 1.19%   |
| Sandisk WD_BLACK SN770 1TB                            | 1         | 1.19%   |
| Sandisk WD Black SN850 1TB                            | 1         | 1.19%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 500GB | 1         | 1.19%   |
| SanDisk SDSSDXPS480G 480GB                            | 1         | 1.19%   |
| SanDisk NVMe SSD Drive 1TB                            | 1         | 1.19%   |
| SanDisk 3.2 Gen 1 496GB SSD                           | 1         | 1.19%   |
| Samsung SSD 970 EVO Plus 1TB                          | 1         | 1.19%   |
| Samsung SSD 970 EVO 500GB                             | 1         | 1.19%   |
| Samsung SSD 870 EVO 500GB                             | 1         | 1.19%   |
| Samsung SSD 860 EVO 250GB                             | 1         | 1.19%   |
| Samsung SSD 860 EVO 1TB                               | 1         | 1.19%   |
| Samsung SSD 840 EVO 250GB                             | 1         | 1.19%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 42.86%  |
| Seagate | 2         | 3      | 28.57%  |
| Hitachi | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 38.46%  |
| Transcend           | 2         | 2      | 7.69%   |
| SanDisk             | 2         | 2      | 7.69%   |
| Crucial             | 2         | 3      | 7.69%   |
| Apple               | 2         | 4      | 7.69%   |
| WDC                 | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |
| INNOVATION IT       | 1         | 1      | 3.85%   |
| Dogfish             | 1         | 1      | 3.85%   |
| China               | 1         | 1      | 3.85%   |
| BIWIN               | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 44        | 58     | 58.67%  |
| SSD  | 24        | 30     | 32%     |
| HDD  | 7         | 8      | 9.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 44        | 58     | 61.97%  |
| SATA | 25        | 36     | 35.21%  |
| SAS  | 2         | 2      | 2.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 26     | 67.74%  |
| 0.51-1.0   | 9         | 11     | 29.03%  |
| 1.01-2.0   | 1         | 1      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 31        | 44.29%  |
| 1-20           | 16        | 22.86%  |
| 101-250        | 6         | 8.57%   |
| 1001-2000      | 5         | 7.14%   |
| 251-500        | 4         | 5.71%   |
| More than 3000 | 3         | 4.29%   |
| 501-1000       | 3         | 4.29%   |
| 2001-3000      | 2         | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| Unknown   | 31        | 44.29%  |
| 1-20      | 18        | 25.71%  |
| 101-250   | 7         | 10%     |
| 501-1000  | 4         | 5.71%   |
| 251-500   | 3         | 4.29%   |
| 21-50     | 3         | 4.29%   |
| 51-100    | 2         | 2.86%   |
| 2001-3000 | 1         | 1.43%   |
| 1001-2000 | 1         | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 25%     |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 25%     |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 25%     |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 2      | 50%     |
| SK hynix          | 1         | 1      | 25%     |
| Micron Technology | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 50%     |
| NVMe | 1         | 1      | 25%     |
| SSD  | 1         | 1      | 25%     |

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
| Works    | 62        | 81     | 83.78%  |
| Detected | 7         | 10     | 9.46%   |
| Malfunc  | 4         | 4      | 5.41%   |
| Failed   | 1         | 1      | 1.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 32        | 37.65%  |
| Samsung Electronics          | 17        | 20%     |
| SanDisk                      | 10        | 11.76%  |
| SK hynix                     | 6         | 7.06%   |
| Kingston Technology Company  | 4         | 4.71%   |
| AMD                          | 4         | 4.71%   |
| Toshiba America Info Systems | 3         | 3.53%   |
| Micron Technology            | 3         | 3.53%   |
| Yangtze Memory Technologies  | 1         | 1.18%   |
| Micron/Crucial Technology    | 1         | 1.18%   |
| Marvell Technology Group     | 1         | 1.18%   |
| KIOXIA                       | 1         | 1.18%   |
| Biwin Storage Technology     | 1         | 1.18%   |
| ADATA Technology             | 1         | 1.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 10.59%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 8.24%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 4.71%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 3         | 3.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 3.53%   |
| Micron NVMe Storage Controller                                                 | 3         | 3.53%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 3.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 3.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 3.53%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 2.35%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 2.35%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 2.35%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 2.35%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 2.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.35%   |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 1.18%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 1.18%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                               | 1         | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.18%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.18%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.18%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.18%   |
| Samsung Electronics SATA controller                                            | 1         | 1.18%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 1.18%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 1.18%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.18%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.18%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 1.18%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 1.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 44        | 54.32%  |
| SATA | 32        | 39.51%  |
| RAID | 5         | 6.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 50        | 75.76%  |
| AMD    | 16        | 24.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 6.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 4.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 3         | 4.55%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 4.55%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 4.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 3.03%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 3.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 3.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 2         | 3.03%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 2         | 3.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 3.03%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 3.03%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 1.52%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 1.52%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 1.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 1.52%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 1.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 1         | 1.52%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 1.52%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 1.52%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 1.52%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 1.52%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz         | 1         | 1.52%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 1         | 1.52%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 1.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 1.52%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 1         | 1.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 1         | 1.52%   |
| Intel Core i3-10110U CPU @ 2.10GHz         | 1         | 1.52%   |
| Intel Celeron N4120 CPU @ 1.10GHz          | 1         | 1.52%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 1         | 1.52%   |
| Intel Atom CPU N280 @ 1.66GHz              | 1         | 1.52%   |
| Intel 12th Gen Core i7-1270P               | 1         | 1.52%   |
| Intel 12th Gen Core i7-1260P               | 1         | 1.52%   |
| Intel 12th Gen Core i5-1240P               | 1         | 1.52%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz    | 1         | 1.52%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz    | 1         | 1.52%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 1         | 1.52%   |
| AMD Ryzen 9 5900HS with Radeon Graphics    | 1         | 1.52%   |
| AMD Ryzen 9 4900HS with Radeon Graphics    | 1         | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 23        | 34.85%  |
| Other           | 12        | 18.18%  |
| AMD Ryzen 7     | 9         | 13.64%  |
| Intel Core i5   | 8         | 12.12%  |
| AMD Ryzen 7 PRO | 4         | 6.06%   |
| AMD Ryzen 9     | 3         | 4.55%   |
| Intel Celeron   | 2         | 3.03%   |
| Intel Xeon      | 1         | 1.52%   |
| Intel Core m3   | 1         | 1.52%   |
| Intel Core i9   | 1         | 1.52%   |
| Intel Core i3   | 1         | 1.52%   |
| Intel Atom      | 1         | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 25        | 37.88%  |
| 8      | 20        | 30.3%   |
| 2      | 14        | 21.21%  |
| 12     | 3         | 4.55%   |
| 6      | 3         | 4.55%   |
| 1      | 1         | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 66        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 63        | 95.45%  |
| 1      | 3         | 4.55%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 65        | 97.01%  |
| 32-bit         | 1         | 1.49%   |
| Unknown        | 1         | 1.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 23.53%  |
| 0x0a50000c | 8         | 11.76%  |
| 0x806ea    | 4         | 5.88%   |
| 0x806c1    | 4         | 5.88%   |
| 0x806ec    | 3         | 4.41%   |
| 0x08600106 | 3         | 4.41%   |
| 0x906ea    | 2         | 2.94%   |
| 0x906a3    | 2         | 2.94%   |
| 0x806eb    | 2         | 2.94%   |
| 0x806e9    | 2         | 2.94%   |
| 0x406e3    | 2         | 2.94%   |
| 0x40661    | 2         | 2.94%   |
| 0x40651    | 2         | 2.94%   |
| 0x306d4    | 2         | 2.94%   |
| 0x306c3    | 2         | 2.94%   |
| 0x0a404102 | 2         | 2.94%   |
| 0x08600104 | 2         | 2.94%   |
| 0x906ed    | 1         | 1.47%   |
| 0x906e9    | 1         | 1.47%   |
| 0x806d1    | 1         | 1.47%   |
| 0x706a8    | 1         | 1.47%   |
| 0x706a1    | 1         | 1.47%   |
| 0x506e3    | 1         | 1.47%   |
| 0x306a9    | 1         | 1.47%   |
| 0x0a50000b | 1         | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 27.27%  |
| Zen 3            | 9         | 13.64%  |
| Skylake          | 7         | 10.61%  |
| TigerLake        | 6         | 9.09%   |
| Haswell          | 6         | 9.09%   |
| Zen 2            | 5         | 7.58%   |
| Alderlake Hybrid | 3         | 4.55%   |
| Unknown          | 3         | 4.55%   |
| IvyBridge        | 2         | 3.03%   |
| Icelake          | 2         | 3.03%   |
| Goldmont plus    | 2         | 3.03%   |
| Broadwell        | 2         | 3.03%   |
| Bonnell          | 1         | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 51.65%  |
| Nvidia | 25        | 27.47%  |
| AMD    | 19        | 20.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 8         | 8.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 6.45%   |
| AMD Renoir                                                                            | 5         | 5.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 4.3%    |
| Intel UHD Graphics 620                                                                | 4         | 4.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 4.3%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 3.23%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 3         | 3.23%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 3.23%   |
| Intel HD Graphics 530                                                                 | 3         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 3.23%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 3         | 3.23%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 2.15%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 2.15%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 2.15%   |
| Intel HD Graphics 620                                                                 | 2         | 2.15%   |
| Intel HD Graphics 5500                                                                | 2         | 2.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 2.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 2.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 2.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 2.15%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 2.15%   |
| AMD Rembrandt [Radeon 680M]                                                           | 2         | 2.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 1.08%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                | 1         | 1.08%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 1.08%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 1.08%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.08%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 1.08%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 1.08%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 1         | 1.08%   |
| Nvidia GK106GLM [Quadro K2100M]                                                       | 1         | 1.08%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 1.08%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 1         | 1.08%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                    | 1         | 1.08%   |
| Intel UHD Graphics 615                                                                | 1         | 1.08%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 1         | 1.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 42.42%  |
| Intel + Nvidia | 16        | 24.24%  |
| 1 x AMD        | 9         | 13.64%  |
| AMD + Nvidia   | 7         | 10.61%  |
| 1 x Nvidia     | 2         | 3.03%   |
| Intel + AMD    | 2         | 3.03%   |
| 2 x Intel      | 1         | 1.52%   |
| 2 x AMD        | 1         | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 52        | 77.61%  |
| Proprietary | 13        | 19.4%   |
| Unknown     | 2         | 2.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 60.87%  |
| 0.01-0.5   | 11        | 15.94%  |
| 1.01-2.0   | 7         | 10.14%  |
| 3.01-4.0   | 6         | 8.7%    |
| 0.51-1.0   | 3         | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 12        | 14.63%  |
| LG Display          | 10        | 12.2%   |
| BOE                 | 9         | 10.98%  |
| Dell                | 8         | 9.76%   |
| Samsung Electronics | 7         | 8.54%   |
| Chimei Innolux      | 6         | 7.32%   |
| PANDA               | 5         | 6.1%    |
| Sharp               | 4         | 4.88%   |
| CSO                 | 4         | 4.88%   |
| Panasonic           | 2         | 2.44%   |
| InfoVision          | 2         | 2.44%   |
| Hewlett-Packard     | 2         | 2.44%   |
| Apple               | 2         | 2.44%   |
| Philips             | 1         | 1.22%   |
| Lenovo              | 1         | 1.22%   |
| JDI                 | 1         | 1.22%   |
| HannStar            | 1         | 1.22%   |
| Goldstar            | 1         | 1.22%   |
| Eizo                | 1         | 1.22%   |
| ASUSTek Computer    | 1         | 1.22%   |
| AOC                 | 1         | 1.22%   |
| Acer                | 1         | 1.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic VVY13F001G10 MEI96A2 1920x1080 344x193mm 15.5-inch          | 2         | 2.44%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 2.44%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 2.44%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 2.44%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 1.22%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 1.22%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 1.22%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 1.22%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 1.22%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 1.22%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 1.22%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 1.22%   |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch     | 1         | 1.22%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1         | 1.22%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 1.22%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch               | 1         | 1.22%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 1.22%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 1.22%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 1         | 1.22%   |
| LG Display LCD Monitor LGD06CE 1920x1200 288x180mm 13.4-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 1.22%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.22%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 1.22%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.22%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 1.22%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 1.22%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch           | 1         | 1.22%   |
| Hewlett-Packard Z27 HPN3538 3840x2160 597x336mm 27.0-inch             | 1         | 1.22%   |
| Hewlett-Packard Z27 HPN3535 3840x2160 597x336mm 27.0-inch             | 1         | 1.22%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.22%   |
| Goldstar ULTRAGEAR GSM774A 3440x1440 800x335mm 34.1-inch              | 1         | 1.22%   |
| Eizo L568 ENC1734 1280x1024 338x270mm 17.0-inch                       | 1         | 1.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 32        | 41.03%  |
| 3840x2160 (4K)     | 13        | 16.67%  |
| 1366x768 (WXGA)    | 9         | 11.54%  |
| 2560x1440 (QHD)    | 8         | 10.26%  |
| 2560x1600          | 3         | 3.85%   |
| 1920x1200 (WUXGA)  | 3         | 3.85%   |
| 3440x1440          | 2         | 2.56%   |
| 2880x1800          | 2         | 2.56%   |
| 2256x1504          | 2         | 2.56%   |
| 3840x2400          | 1         | 1.28%   |
| 1680x1050 (WSXGA+) | 1         | 1.28%   |
| 1280x1024 (SXGA)   | 1         | 1.28%   |
| 1024x600           | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 23        | 28.4%   |
| 14     | 13        | 16.05%  |
| 13     | 13        | 16.05%  |
| 27     | 7         | 8.64%   |
| 24     | 5         | 6.17%   |
| 12     | 5         | 6.17%   |
| 17     | 4         | 4.94%   |
| 34     | 2         | 2.47%   |
| 31     | 2         | 2.47%   |
| 23     | 2         | 2.47%   |
| 16     | 2         | 2.47%   |
| 46     | 1         | 1.23%   |
| 22     | 1         | 1.23%   |
| 10     | 1         | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 52.5%   |
| 201-300     | 15        | 18.75%  |
| 501-600     | 13        | 16.25%  |
| 601-700     | 3         | 3.75%   |
| 351-400     | 3         | 3.75%   |
| 701-800     | 2         | 2.5%    |
| 401-500     | 1         | 1.25%   |
| 1001-1500   | 1         | 1.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 77.94%  |
| 16/10 | 10        | 14.71%  |
| 3/2   | 2         | 2.94%   |
| 21/9  | 2         | 2.94%   |
| 5/4   | 1         | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 28.4%   |
| 81-90          | 19        | 23.46%  |
| 71-80          | 7         | 8.64%   |
| 301-350        | 7         | 8.64%   |
| 201-250        | 7         | 8.64%   |
| 61-70          | 5         | 6.17%   |
| 351-500        | 4         | 4.94%   |
| 121-130        | 3         | 3.7%    |
| 111-120        | 2         | 2.47%   |
| 41-50          | 1         | 1.23%   |
| 251-300        | 1         | 1.23%   |
| 141-150        | 1         | 1.23%   |
| 501-1000       | 1         | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 36.49%  |
| 161-240       | 19        | 25.68%  |
| 101-120       | 10        | 13.51%  |
| 51-100        | 9         | 12.16%  |
| More than 240 | 8         | 10.81%  |
| 1-50          | 1         | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 47        | 66.2%   |
| 2     | 17        | 23.94%  |
| 0     | 5         | 7.04%   |
| 3     | 2         | 2.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 53        | 51.46%  |
| Realtek Semiconductor             | 33        | 32.04%  |
| Qualcomm Atheros                  | 5         | 4.85%   |
| Qualcomm                          | 2         | 1.94%   |
| MediaTek                          | 2         | 1.94%   |
| Lenovo                            | 2         | 1.94%   |
| Broadcom                          | 2         | 1.94%   |
| Xiaomi                            | 1         | 0.97%   |
| Microsoft                         | 1         | 0.97%   |
| Fibocom                           | 1         | 0.97%   |
| Ericsson Business Mobile Networks | 1         | 0.97%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 13.6%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 10.4%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 8.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 4.8%    |
| Intel Wireless 8260                                               | 4         | 3.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 2.4%    |
| Intel Wireless-AC 9260                                            | 3         | 2.4%    |
| Intel Wireless 7265                                               | 3         | 2.4%    |
| Intel Wireless 7260                                               | 3         | 2.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 2.4%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 2.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.6%    |
| Intel Wireless 8265 / 8275                                        | 2         | 1.6%    |
| Intel Wireless 3165                                               | 2         | 1.6%    |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.6%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.6%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.8%    |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.8%    |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.8%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.8%    |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 0.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.8%    |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.8%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.8%    |
| Intel Wireless 3160                                               | 1         | 0.8%    |
| Intel I210 Gigabit Network Connection                             | 1         | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 79.1%   |
| Qualcomm Atheros      | 5         | 7.46%   |
| Qualcomm              | 2         | 2.99%   |
| MediaTek              | 2         | 2.99%   |
| Broadcom              | 2         | 2.99%   |
| Realtek Semiconductor | 1         | 1.49%   |
| Microsoft             | 1         | 1.49%   |
| Fibocom               | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 11        | 16.42%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 8.96%   |
| Intel Wireless 8260                                            | 4         | 5.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 4.48%   |
| Intel Wireless-AC 9260                                         | 3         | 4.48%   |
| Intel Wireless 7265                                            | 3         | 4.48%   |
| Intel Wireless 7260                                            | 3         | 4.48%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 4.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 4.48%   |
| Intel Wireless 8265 / 8275                                     | 2         | 2.99%   |
| Intel Wireless 3165                                            | 2         | 2.99%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 2.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.49%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.49%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.49%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 1.49%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.49%   |
| Intel Wireless 3160                                            | 1         | 1.49%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 1.49%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 1.49%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 1.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 32        | 60.38%  |
| Intel                 | 17        | 32.08%  |
| Lenovo                | 2         | 3.77%   |
| Xiaomi                | 1         | 1.89%   |
| Qualcomm Atheros      | 1         | 1.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 29.82%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 22.81%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 5.26%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 5.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.51%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.51%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 3.51%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.75%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.75%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.75%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.75%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 55.56%  |
| Ethernet | 51        | 43.59%  |
| Modem    | 1         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 81.58%  |
| Ethernet | 14        | 18.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 38        | 57.58%  |
| 1     | 27        | 40.91%  |
| 3     | 1         | 1.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 80.6%   |
| Yes  | 13        | 19.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 80%     |
| Qualcomm Atheros Communications | 3         | 5%      |
| Apple                           | 2         | 3.33%   |
| USI                             | 1         | 1.67%   |
| Realtek Semiconductor           | 1         | 1.67%   |
| MediaTek                        | 1         | 1.67%   |
| Lite-On Technology              | 1         | 1.67%   |
| Foxconn / Hon Hai               | 1         | 1.67%   |
| Broadcom                        | 1         | 1.67%   |
| ASUSTek Computer                | 1         | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 12        | 20%     |
| Intel AX200 Bluetooth                          | 11        | 18.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 6         | 10%     |
| Intel AX210 Bluetooth                          | 6         | 10%     |
| Intel AX201 Bluetooth                          | 6         | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 3         | 5%      |
| Qualcomm Atheros  Bluetooth Device             | 2         | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 3.33%   |
| Intel Bluetooth Device                         | 2         | 3.33%   |
| Apple Bluetooth Host Controller                | 2         | 3.33%   |
| USI Bluetooth Device                           | 1         | 1.67%   |
| Realtek Bluetooth Radio                        | 1         | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 1.67%   |
| MediaTek Wireless_Device                       | 1         | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.67%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 1.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 1.67%   |
| ASUS Broadcom Bluetooth 2.1                    | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 51        | 52.04%  |
| AMD                       | 17        | 17.35%  |
| Nvidia                    | 11        | 11.22%  |
| Lenovo                    | 3         | 3.06%   |
| C-Media Electronics       | 3         | 3.06%   |
| Synaptics                 | 2         | 2.04%   |
| Realtek Semiconductor     | 2         | 2.04%   |
| Trust                     | 1         | 1.02%   |
| Sennheiser Communications | 1         | 1.02%   |
| Satechi                   | 1         | 1.02%   |
| Logitech                  | 1         | 1.02%   |
| Kingston Technology       | 1         | 1.02%   |
| Focusrite-Novation        | 1         | 1.02%   |
| Creative Technology       | 1         | 1.02%   |
| Corsair                   | 1         | 1.02%   |
| (LCS) USB Audio Device    | 1         | 1.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 16        | 13.45%  |
| AMD Renoir Radeon High Definition Audio Controller                  | 12        | 10.08%  |
| Intel Sunrise Point-LP HD Audio                                     | 11        | 9.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 6         | 5.04%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 4         | 3.36%   |
| Intel Cannon Lake PCH cAVS                                          | 4         | 3.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4         | 3.36%   |
| Intel Tiger Lake-H HD Audio Controller                              | 3         | 2.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 3         | 2.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 3         | 2.52%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                 | 2         | 1.68%   |
| Realtek Semiconductor USB Audio                                     | 2         | 1.68%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2         | 1.68%   |
| Nvidia GA106 High Definition Audio Controller                       | 2         | 1.68%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2         | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 1.68%   |
| Intel Haswell-ULT HD Audio Controller                               | 2         | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                        | 2         | 1.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 2         | 1.68%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 1.68%   |
| Intel 8 Series HD Audio Controller                                  | 2         | 1.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 1.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2         | 1.68%   |
| Trust USB microphone                                                | 1         | 0.84%   |
| Sennheiser Communications Headset [PC 8]                            | 1         | 0.84%   |
| Satechi Audio & PD Adapter                                          | 1         | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                       | 1         | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]       | 1         | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 0.84%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 0.84%   |
| Nvidia Audio device                                                 | 1         | 0.84%   |
| Logitech Blue Microphones                                           | 1         | 0.84%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                           | 1         | 0.84%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                        | 1         | 0.84%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                        | 1         | 0.84%   |
| Kingston Technology HyperX 7.1 Audio                                | 1         | 0.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 1         | 0.84%   |
| Intel KinMax-AB Digital Audio                                       | 1         | 0.84%   |
| Intel CM238 HD Audio Controller                                     | 1         | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 37.97%  |
| Micron Technology   | 11        | 13.92%  |
| Crucial             | 9         | 11.39%  |
| SK hynix            | 8         | 10.13%  |
| Kingston            | 5         | 6.33%   |
| Unknown             | 3         | 3.8%    |
| Team                | 3         | 3.8%    |
| Unknown (ABCD)      | 2         | 2.53%   |
| Ramaxel Technology  | 1         | 1.27%   |
| GOODRAM             | 1         | 1.27%   |
| G.Skill             | 1         | 1.27%   |
| Corsair             | 1         | 1.27%   |
| Avant               | 1         | 1.27%   |
| AMD                 | 1         | 1.27%   |
| A-DATA Technology   | 1         | 1.27%   |
| Unknown             | 1         | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 2.33%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 2.33%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 2.33%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 2.33%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 2.33%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 2.33%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.33%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 2.33%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 1.16%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.16%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 1.16%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 1.16%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 1.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.16%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.16%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 1         | 1.16%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 1.16%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.16%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 1.16%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.16%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.16%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 1.16%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.16%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1600MT/s                   | 1         | 1.16%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.16%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.16%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.16%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.16%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s             | 1         | 1.16%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 1         | 1.16%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 1         | 1.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 37        | 56.92%  |
| DDR3   | 11        | 16.92%  |
| LPDDR4 | 9         | 13.85%  |
| LPDDR5 | 3         | 4.62%   |
| LPDDR3 | 3         | 4.62%   |
| SDRAM  | 1         | 1.54%   |
| DDR5   | 1         | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 77.94%  |
| Row Of Chips | 12        | 17.65%  |
| Chip         | 2         | 2.94%   |
| Unknown      | 1         | 1.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 29        | 39.73%  |
| 16384 | 19        | 26.03%  |
| 4096  | 12        | 16.44%  |
| 32768 | 9         | 12.33%  |
| 2048  | 3         | 4.11%   |
| 1024  | 1         | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 18        | 26.47%  |
| 2667    | 15        | 22.06%  |
| 1600    | 10        | 14.71%  |
| 2133    | 6         | 8.82%   |
| 4267    | 5         | 7.35%   |
| 2400    | 4         | 5.88%   |
| 6400    | 3         | 4.41%   |
| 4266    | 2         | 2.94%   |
| 1867    | 2         | 2.94%   |
| 4800    | 1         | 1.47%   |
| 3266    | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

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
| Chicony Electronics           | 16        | 26.23%  |
| Microdia                      | 10        | 16.39%  |
| IMC Networks                  | 8         | 13.11%  |
| Realtek Semiconductor         | 5         | 8.2%    |
| Bison Electronics             | 5         | 8.2%    |
| Acer                          | 4         | 6.56%   |
| Sunplus Innovation Technology | 3         | 4.92%   |
| Logitech                      | 3         | 4.92%   |
| Quanta                        | 2         | 3.28%   |
| Lite-On Technology            | 2         | 3.28%   |
| Syntek                        | 1         | 1.64%   |
| Alcor Micro                   | 1         | 1.64%   |
| 2M UVC CAMERA                 | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 10        | 16.13%  |
| Microdia Integrated_Webcam_HD        | 6         | 9.68%   |
| IMC Networks USB2.0 HD UVC WebCam    | 3         | 4.84%   |
| IMC Networks Integrated Camera       | 3         | 4.84%   |
| Chicony HP HD Camera                 | 3         | 4.84%   |
| Sunplus Integrated_Webcam_FHD        | 2         | 3.23%   |
| Realtek Laptop Camera                | 2         | 3.23%   |
| Logitech HD Pro Webcam C920          | 2         | 3.23%   |
| Bison Integrated Camera              | 2         | 3.23%   |
| Acer Integrated IR Camera            | 2         | 3.23%   |
| Syntek Integrated Camera             | 1         | 1.61%   |
| Sunplus Integrated_Webcam_HD         | 1         | 1.61%   |
| Realtek TV Camera                    | 1         | 1.61%   |
| Realtek Realtek USB MIC              | 1         | 1.61%   |
| Realtek Lenovo EasyCamera            | 1         | 1.61%   |
| Realtek Integrated Webcam            | 1         | 1.61%   |
| Quanta VGA WebCam                    | 1         | 1.61%   |
| Quanta HD WebCam                     | 1         | 1.61%   |
| Microdia Webcam Vitade AF            | 1         | 1.61%   |
| Microdia USB 2.0 Camera              | 1         | 1.61%   |
| Microdia Laptop_Integrated_Webcam_HD | 1         | 1.61%   |
| Microdia Integrated Webcam           | 1         | 1.61%   |
| Logitech Webcam C310                 | 1         | 1.61%   |
| Lite-On Integrated Camera            | 1         | 1.61%   |
| Lite-On HP HD Camera                 | 1         | 1.61%   |
| IMC Networks XHC Camera              | 1         | 1.61%   |
| IMC Networks USB2.0 UVC 1.3M WebCam  | 1         | 1.61%   |
| Chicony USB2.0 Camera                | 1         | 1.61%   |
| Chicony Integrated Camera [ThinkPad] | 1         | 1.61%   |
| Chicony HD Webcam                    | 1         | 1.61%   |
| Bison SunplusIT Integrated Camera    | 1         | 1.61%   |
| Bison Integrated RGB Camera          | 1         | 1.61%   |
| Bison HD Webcam                      | 1         | 1.61%   |
| Alcor Micro SHUNCCM2MP               | 1         | 1.61%   |
| Acer ThinkPad P50 Integrated Camera  | 1         | 1.61%   |
| Acer Integrated Camera               | 1         | 1.61%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam  | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 47.06%  |
| Validity Sensors           | 7         | 41.18%  |
| Shenzhen Goodix Technology | 2         | 11.76%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 4         | 23.53%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 17.65%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 11.76%  |
| Synaptics UWP WBDI Device                                | 2         | 11.76%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 5.88%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 5.88%   |
| Shenzhen Goodix  Fingerprint Device                      | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 10        | 71.43%  |
| Yubico.com  | 2         | 14.29%  |
| Upek        | 1         | 7.14%   |
| Broadcom    | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 10        | 71.43%  |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 7.14%   |
| Yubico.com Yubikey 4 U2F+CCID                              | 1         | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 27        | 39.71%  |
| 1     | 25        | 36.76%  |
| 2     | 13        | 19.12%  |
| 4     | 2         | 2.94%   |
| 3     | 1         | 1.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 24.59%  |
| Graphics card            | 13        | 21.31%  |
| Multimedia controller    | 11        | 18.03%  |
| Chipcard                 | 10        | 16.39%  |
| Net/wireless             | 3         | 4.92%   |
| Modem                    | 2         | 3.28%   |
| Camera                   | 2         | 3.28%   |
| Bluetooth                | 2         | 3.28%   |
| Network                  | 1         | 1.64%   |
| Communication controller | 1         | 1.64%   |
| Card reader              | 1         | 1.64%   |

