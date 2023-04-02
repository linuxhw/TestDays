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

Total: 90

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| NixOS 22.11                      | 22        | 31.88%  |
| NixOS 22.05                      | 18        | 26.09%  |
| NixOS 21.11                      | 9         | 13.04%  |
| NixOS 23.05                      | 6         | 8.7%    |
| NixOS                            | 2         | 2.9%    |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 1.45%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 1.45%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 1.45%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 1.45%   |
| NixOS 21.05.2132.733682c3292     | 1         | 1.45%   |
| NixOS 21.05.20210423.c21475e     | 1         | 1.45%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 1.45%   |
| NixOS 20.09pre-git               | 1         | 1.45%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 1.45%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 1.45%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 1.45%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 1.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 59        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Notebooks | Percent |
|------------------|-----------|---------|
| 5.15.74          | 3         | 4.17%   |
| 5.15.43          | 3         | 4.17%   |
| 6.1.0            | 2         | 2.78%   |
| 6.0.10           | 2         | 2.78%   |
| 5.16.15          | 2         | 2.78%   |
| 5.15.72          | 2         | 2.78%   |
| 5.15.68          | 2         | 2.78%   |
| 5.15.64          | 2         | 2.78%   |
| 5.15.26          | 2         | 2.78%   |
| 5.13.7           | 2         | 2.78%   |
| 6.2.7            | 1         | 1.39%   |
| 6.2.0            | 1         | 1.39%   |
| 6.1.7-xanmod1    | 1         | 1.39%   |
| 6.1.1            | 1         | 1.39%   |
| 6.0.2-xanmod1-tt | 1         | 1.39%   |
| 6.0.11           | 1         | 1.39%   |
| 6.0.10-zen2      | 1         | 1.39%   |
| 6.0.0-xanmod1    | 1         | 1.39%   |
| 5.8.4            | 1         | 1.39%   |
| 5.8.16-hardened  | 1         | 1.39%   |
| 5.8.11           | 1         | 1.39%   |
| 5.7.4            | 1         | 1.39%   |
| 5.7.17           | 1         | 1.39%   |
| 5.4.24           | 1         | 1.39%   |
| 5.4.209          | 1         | 1.39%   |
| 5.4.187          | 1         | 1.39%   |
| 5.19.2           | 1         | 1.39%   |
| 5.19.17          | 1         | 1.39%   |
| 5.19.0           | 1         | 1.39%   |
| 5.18.7-zen1      | 1         | 1.39%   |
| 5.18.0           | 1         | 1.39%   |
| 5.17.1           | 1         | 1.39%   |
| 5.17.0           | 1         | 1.39%   |
| 5.16.8-zen1      | 1         | 1.39%   |
| 5.16.7           | 1         | 1.39%   |
| 5.16.3           | 1         | 1.39%   |
| 5.16.10          | 1         | 1.39%   |
| 5.15.96          | 1         | 1.39%   |
| 5.15.94          | 1         | 1.39%   |
| 5.15.86          | 1         | 1.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.10  | 3         | 4.17%   |
| 5.15.74 | 3         | 4.17%   |
| 5.15.43 | 3         | 4.17%   |
| 6.1.0   | 2         | 2.78%   |
| 5.16.15 | 2         | 2.78%   |
| 5.15.72 | 2         | 2.78%   |
| 5.15.68 | 2         | 2.78%   |
| 5.15.64 | 2         | 2.78%   |
| 5.15.26 | 2         | 2.78%   |
| 5.13.7  | 2         | 2.78%   |
| 6.2.7   | 1         | 1.39%   |
| 6.2.0   | 1         | 1.39%   |
| 6.1.7   | 1         | 1.39%   |
| 6.1.1   | 1         | 1.39%   |
| 6.0.2   | 1         | 1.39%   |
| 6.0.11  | 1         | 1.39%   |
| 6.0.0   | 1         | 1.39%   |
| 5.8.4   | 1         | 1.39%   |
| 5.8.16  | 1         | 1.39%   |
| 5.8.11  | 1         | 1.39%   |
| 5.7.4   | 1         | 1.39%   |
| 5.7.17  | 1         | 1.39%   |
| 5.4.24  | 1         | 1.39%   |
| 5.4.209 | 1         | 1.39%   |
| 5.4.187 | 1         | 1.39%   |
| 5.19.2  | 1         | 1.39%   |
| 5.19.17 | 1         | 1.39%   |
| 5.19.0  | 1         | 1.39%   |
| 5.18.7  | 1         | 1.39%   |
| 5.18.0  | 1         | 1.39%   |
| 5.17.1  | 1         | 1.39%   |
| 5.17.0  | 1         | 1.39%   |
| 5.16.8  | 1         | 1.39%   |
| 5.16.7  | 1         | 1.39%   |
| 5.16.3  | 1         | 1.39%   |
| 5.16.10 | 1         | 1.39%   |
| 5.15.96 | 1         | 1.39%   |
| 5.15.94 | 1         | 1.39%   |
| 5.15.86 | 1         | 1.39%   |
| 5.15.83 | 1         | 1.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 29        | 41.43%  |
| 6.0     | 6         | 8.57%   |
| 5.16    | 6         | 8.57%   |
| 6.1     | 4         | 5.71%   |
| 5.8     | 3         | 4.29%   |
| 5.19    | 3         | 4.29%   |
| 5.13    | 3         | 4.29%   |
| 5.10    | 3         | 4.29%   |
| 6.2     | 2         | 2.86%   |
| 5.7     | 2         | 2.86%   |
| 5.4     | 2         | 2.86%   |
| 5.18    | 2         | 2.86%   |
| 5.17    | 2         | 2.86%   |
| 4.19    | 2         | 2.86%   |
| 5.12    | 1         | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 58        | 98.31%  |
| i686   | 1         | 1.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 41        | 64.06%  |
| GNOME       | 6         | 9.38%   |
| sway        | 5         | 7.81%   |
| KDE5        | 4         | 6.25%   |
| XFCE        | 2         | 3.13%   |
| none+xmonad | 2         | 3.13%   |
| none+i3     | 1         | 1.56%   |
| none+bspwm  | 1         | 1.56%   |
| KDE         | 1         | 1.56%   |
| Hyprland    | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 41        | 65.08%  |
| X11     | 11        | 17.46%  |
| Wayland | 9         | 14.29%  |
| Tty     | 2         | 3.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 40        | 66.67%  |
| SDDM    | 7         | 11.67%  |
| LightDM | 7         | 11.67%  |
| GDM     | 6         | 10%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 30        | 49.18%  |
| en_US   | 24        | 39.34%  |
| ru_RU   | 1         | 1.64%   |
| ro_RO   | 1         | 1.64%   |
| lv_LV   | 1         | 1.64%   |
| fr_FR   | 1         | 1.64%   |
| en_GB   | 1         | 1.64%   |
| en_DK   | 1         | 1.64%   |
| en_CA   | 1         | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 51        | 86.44%  |
| BIOS | 8         | 13.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 33        | 52.38%  |
| Btrfs   | 12        | 19.05%  |
| Zfs     | 5         | 7.94%   |
| Xfs     | 5         | 7.94%   |
| Tmpfs   | 5         | 7.94%   |
| Unknown | 3         | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 55        | 90.16%  |
| Unknown | 5         | 8.2%    |
| MBR     | 1         | 1.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 77.05%  |
| Yes       | 14        | 22.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 74.58%  |
| Yes       | 15        | 25.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 23        | 38.98%  |
| Dell                | 12        | 20.34%  |
| ASUSTek Computer    | 6         | 10.17%  |
| Hewlett-Packard     | 4         | 6.78%   |
| GPD                 | 3         | 5.08%   |
| Framework           | 2         | 3.39%   |
| Acer                | 2         | 3.39%   |
| Toshiba             | 1         | 1.69%   |
| OBSIDIAN-PC         | 1         | 1.69%   |
| MSI                 | 1         | 1.69%   |
| MECHREVO            | 1         | 1.69%   |
| Gigabyte Technology | 1         | 1.69%   |
| Blackview           | 1         | 1.69%   |
| Apple               | 1         | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Latitude 7420                       | 2         | 3.39%   |
| Toshiba Satellite L50-B                  | 1         | 1.69%   |
| OBSIDIAN-PC N13_N140ZU                   | 1         | 1.69%   |
| MSI Bravo 15 B5DD                        | 1         | 1.69%   |
| MECHREVO Code01 Ver2.0                   | 1         | 1.69%   |
| Lenovo Yoga Slim 7 13ACN5 82CY           | 1         | 1.69%   |
| Lenovo ThinkPad X390 20Q0CTO1WW          | 1         | 1.69%   |
| Lenovo ThinkPad X260 20F5S6MF02          | 1         | 1.69%   |
| Lenovo ThinkPad X260 20F5S4BY00          | 1         | 1.69%   |
| Lenovo ThinkPad X250 20CLS18S0T          | 1         | 1.69%   |
| Lenovo ThinkPad X230 2333AZ2             | 1         | 1.69%   |
| Lenovo ThinkPad X230 23243E9             | 1         | 1.69%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 1.69%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBCT01WW | 1         | 1.69%   |
| Lenovo ThinkPad T580 20L90024PB          | 1         | 1.69%   |
| Lenovo ThinkPad T540p 20BE005YMH         | 1         | 1.69%   |
| Lenovo ThinkPad T490 20N2000LUK          | 1         | 1.69%   |
| Lenovo ThinkPad T480 20L5CTO1WW          | 1         | 1.69%   |
| Lenovo ThinkPad T460p 20FWCTO1WW         | 1         | 1.69%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW     | 1         | 1.69%   |
| Lenovo ThinkPad T14s Gen 3 21BR000MUS    | 1         | 1.69%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK    | 1         | 1.69%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT     | 1         | 1.69%   |
| Lenovo ThinkPad P14s Gen 3 21J5002KMH    | 1         | 1.69%   |
| Lenovo ThinkPad E470 20H1006JIX          | 1         | 1.69%   |
| Lenovo Legion S7 15ACH6 82K8             | 1         | 1.69%   |
| Lenovo Legion 5 17ARH05H 82GN            | 1         | 1.69%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 1         | 1.69%   |
| HP ZBook Studio G5                       | 1         | 1.69%   |
| HP ProBook 450 G4                        | 1         | 1.69%   |
| HP ProBook 445 G7                        | 1         | 1.69%   |
| HP EliteBook 845 G8 Notebook PC          | 1         | 1.69%   |
| GPD WIN2                                 | 1         | 1.69%   |
| GPD MicroPC                              | 1         | 1.69%   |
| GPD G1621-02                             | 1         | 1.69%   |
| Gigabyte Sabre 15                        | 1         | 1.69%   |
| Framework Laptop (12th Gen Intel Core)   | 1         | 1.69%   |
| Framework Laptop                         | 1         | 1.69%   |
| Dell XPS 15 9570                         | 1         | 1.69%   |
| Dell XPS 15 9550                         | 1         | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 19        | 32.2%   |
| Dell XPS           | 5         | 8.47%   |
| Dell Latitude      | 3         | 5.08%   |
| ASUS ROG           | 3         | 5.08%   |
| Lenovo Legion      | 2         | 3.39%   |
| HP ProBook         | 2         | 3.39%   |
| Framework Laptop   | 2         | 3.39%   |
| Dell Precision     | 2         | 3.39%   |
| Dell Inspiron      | 2         | 3.39%   |
| Acer Aspire        | 2         | 3.39%   |
| Toshiba Satellite  | 1         | 1.69%   |
| OBSIDIAN-PC N13    | 1         | 1.69%   |
| MSI Bravo          | 1         | 1.69%   |
| MECHREVO Code01    | 1         | 1.69%   |
| Lenovo Yoga        | 1         | 1.69%   |
| Lenovo IdeaPad     | 1         | 1.69%   |
| HP ZBook           | 1         | 1.69%   |
| HP EliteBook       | 1         | 1.69%   |
| GPD WIN2           | 1         | 1.69%   |
| GPD MicroPC        | 1         | 1.69%   |
| GPD G1621-02       | 1         | 1.69%   |
| Gigabyte Sabre     | 1         | 1.69%   |
| Blackview AceBook  | 1         | 1.69%   |
| ASUS ZenBook       | 1         | 1.69%   |
| ASUS ASUSPRO       | 1         | 1.69%   |
| ASUS 1005HA        | 1         | 1.69%   |
| Apple MacBookPro11 | 1         | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 13        | 22.03%  |
| 2020 | 9         | 15.25%  |
| 2019 | 8         | 13.56%  |
| 2016 | 7         | 11.86%  |
| 2018 | 6         | 10.17%  |
| 2022 | 4         | 6.78%   |
| 2017 | 3         | 5.08%   |
| 2015 | 2         | 3.39%   |
| 2014 | 2         | 3.39%   |
| 2013 | 2         | 3.39%   |
| 2012 | 2         | 3.39%   |
| 2009 | 1         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 59        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 59        | 98.33%  |
| Enabled  | 1         | 1.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 58        | 98.31%  |
| Yes  | 1         | 1.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 19        | 31.67%  |
| 16.01-24.0  | 16        | 26.67%  |
| 8.01-16.0   | 14        | 23.33%  |
| 4.01-8.0    | 7         | 11.67%  |
| 3.01-4.0    | 1         | 1.67%   |
| 24.01-32.0  | 1         | 1.67%   |
| 64.01-256.0 | 1         | 1.67%   |
| 0.51-1.0    | 1         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 21        | 30%     |
| 3.01-4.0   | 12        | 17.14%  |
| 8.01-16.0  | 12        | 17.14%  |
| 2.01-3.0   | 11        | 15.71%  |
| 24.01-32.0 | 4         | 5.71%   |
| 1.01-2.0   | 4         | 5.71%   |
| 0.51-1.0   | 3         | 4.29%   |
| 32.01-64.0 | 1         | 1.43%   |
| 16.01-24.0 | 1         | 1.43%   |
| 0.01-0.5   | 1         | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 80%     |
| 2      | 12        | 20%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 93.22%  |
| Yes       | 4         | 6.78%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 70.97%  |
| No        | 18        | 29.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 98.31%  |
| No        | 1         | 1.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 88.52%  |
| No        | 7         | 11.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| France      | 7         | 11.86%  |
| USA         | 6         | 10.17%  |
| UK          | 5         | 8.47%   |
| Russia      | 4         | 6.78%   |
| Poland      | 4         | 6.78%   |
| Canada      | 4         | 6.78%   |
| Ukraine     | 3         | 5.08%   |
| Italy       | 3         | 5.08%   |
| Switzerland | 2         | 3.39%   |
| Netherlands | 2         | 3.39%   |
| Germany     | 2         | 3.39%   |
| Belgium     | 2         | 3.39%   |
| Austria     | 2         | 3.39%   |
| Uruguay     | 1         | 1.69%   |
| Sweden      | 1         | 1.69%   |
| Spain       | 1         | 1.69%   |
| Romania     | 1         | 1.69%   |
| Portugal    | 1         | 1.69%   |
| Latvia      | 1         | 1.69%   |
| Iraq        | 1         | 1.69%   |
| Iran        | 1         | 1.69%   |
| India       | 1         | 1.69%   |
| Denmark     | 1         | 1.69%   |
| Czechia     | 1         | 1.69%   |
| Colombia    | 1         | 1.69%   |
| China       | 1         | 1.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Vienna             | 2         | 3.03%   |
| Ottawa             | 2         | 3.03%   |
| Marki              | 2         | 3.03%   |
| London             | 2         | 3.03%   |
| Halifax            | 2         | 3.03%   |
| Zurich             | 1         | 1.52%   |
| Yangzhou           | 1         | 1.52%   |
| Woodford           | 1         | 1.52%   |
| Warsaw             | 1         | 1.52%   |
| Villeurbanne       | 1         | 1.52%   |
| Verneuil-sur-Seine | 1         | 1.52%   |
| Valpacos           | 1         | 1.52%   |
| Trento             | 1         | 1.52%   |
| Tottenham          | 1         | 1.52%   |
| Tolyatti           | 1         | 1.52%   |
| Tehran             | 1         | 1.52%   |
| Stockholm          | 1         | 1.52%   |
| South Deerfield    | 1         | 1.52%   |
| Saratov            | 1         | 1.52%   |
| Riga               | 1         | 1.52%   |
| Rho                | 1         | 1.52%   |
| Prague             | 1         | 1.52%   |
| Plymouth           | 1         | 1.52%   |
| Pittsburgh         | 1         | 1.52%   |
| Odense             | 1         | 1.52%   |
| Nantes             | 1         | 1.52%   |
| Mykolayiv          | 1         | 1.52%   |
| Montpellier        | 1         | 1.52%   |
| Montevideo         | 1         | 1.52%   |
| Mons               | 1         | 1.52%   |
| Milwaukee          | 1         | 1.52%   |
| Messina            | 1         | 1.52%   |
| Melsele            | 1         | 1.52%   |
| Meaux              | 1         | 1.52%   |
| Lyon               | 1         | 1.52%   |
| Lehrte             | 1         | 1.52%   |
| Krasnodar          | 1         | 1.52%   |
| Krakow             | 1         | 1.52%   |
| Kiel               | 1         | 1.52%   |
| Kharkiv            | 1         | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 22        | 30     | 31.43%  |
| WDC                         | 6         | 6      | 8.57%   |
| SK hynix                    | 6         | 9      | 8.57%   |
| SanDisk                     | 5         | 5      | 7.14%   |
| Toshiba                     | 4         | 4      | 5.71%   |
| Micron Technology           | 3         | 3      | 4.29%   |
| Kingston                    | 3         | 3      | 4.29%   |
| Crucial                     | 3         | 4      | 4.29%   |
| Transcend                   | 2         | 2      | 2.86%   |
| Seagate                     | 2         | 3      | 2.86%   |
| KIOXIA                      | 2         | 3      | 2.86%   |
| Kingston Technology Company | 2         | 2      | 2.86%   |
| Yangtze Memory Technologies | 1         | 1      | 1.43%   |
| Intel                       | 1         | 1      | 1.43%   |
| INNOVATION IT               | 1         | 1      | 1.43%   |
| Hitachi                     | 1         | 1      | 1.43%   |
| HGST                        | 1         | 1      | 1.43%   |
| Dogfish                     | 1         | 1      | 1.43%   |
| China                       | 1         | 1      | 1.43%   |
| Biwin Storage Technology    | 1         | 1      | 1.43%   |
| BIWIN                       | 1         | 1      | 1.43%   |
| Apple                       | 1         | 3      | 1.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| SK hynix SKHynix_HFS001TDE9X084N 1TB                  | 2         | 2.7%    |
| Samsung SSD 850 EVO 500GB                             | 2         | 2.7%    |
| Samsung PM9A1 NVMe 1024GB                             | 2         | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 2         | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 2         | 2.7%    |
| Yangtze Memory ZHITAI TiPlus7100 2TB                  | 1         | 1.35%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                      | 1         | 1.35%   |
| WDC WDS200T1X0E-00AFY0 2TB                            | 1         | 1.35%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                    | 1         | 1.35%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                  | 1         | 1.35%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB                    | 1         | 1.35%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB                  | 1         | 1.35%   |
| Transcend TS256GMTS800 256GB SSD                      | 1         | 1.35%   |
| Transcend TS256GMTS430S 256GB SSD                     | 1         | 1.35%   |
| Toshiba MQ01ABD100 1TB                                | 1         | 1.35%   |
| Toshiba MK2565GSXV 250GB                              | 1         | 1.35%   |
| Toshiba KXG6AZNV512G 512GB                            | 1         | 1.35%   |
| Toshiba KXG50ZNV512G NVMe 512GB                       | 1         | 1.35%   |
| SK hynix SC311 SATA 256GB SSD                         | 1         | 1.35%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                  | 1         | 1.35%   |
| SK hynix NVMe SSD Drive 1TB                           | 1         | 1.35%   |
| SK hynix NVMe SSD Drive 1024GB                        | 1         | 1.35%   |
| SK hynix HFM001TD3JX013N 1TB                          | 1         | 1.35%   |
| Seagate ST2000LM007-1R8174 2TB                        | 1         | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB                        | 1         | 1.35%   |
| Sandisk WD Black SN850 1TB                            | 1         | 1.35%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 256GB | 1         | 1.35%   |
| SanDisk SDSSDXPS480G 480GB                            | 1         | 1.35%   |
| SanDisk NVMe SSD Drive 1TB                            | 1         | 1.35%   |
| SanDisk 3.2 Gen 1 496GB SSD                           | 1         | 1.35%   |
| Samsung SSD 970 EVO Plus 1TB                          | 1         | 1.35%   |
| Samsung SSD 970 EVO 500GB                             | 1         | 1.35%   |
| Samsung SSD 870 EVO 500GB                             | 1         | 1.35%   |
| Samsung SSD 860 EVO 250GB                             | 1         | 1.35%   |
| Samsung SSD 860 EVO 1TB                               | 1         | 1.35%   |
| Samsung Portable SSD T5 500GB                         | 1         | 1.35%   |
| Samsung PM991a NVMe 512GB                             | 1         | 1.35%   |
| Samsung NVMe SSD Drive 512GB                          | 1         | 1.35%   |
| Samsung NVMe SSD Controller SM951/PM951 128GB         | 1         | 1.35%   |
| Samsung MZVLB512HBJQ-000L7 512GB                      | 1         | 1.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 33.33%  |
| Seagate | 2         | 3      | 33.33%  |
| Hitachi | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 34.78%  |
| Transcend           | 2         | 2      | 8.7%    |
| SanDisk             | 2         | 2      | 8.7%    |
| Crucial             | 2         | 3      | 8.7%    |
| WDC                 | 1         | 1      | 4.35%   |
| SK hynix            | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |
| Kingston            | 1         | 1      | 4.35%   |
| INNOVATION IT       | 1         | 1      | 4.35%   |
| Dogfish             | 1         | 1      | 4.35%   |
| China               | 1         | 1      | 4.35%   |
| BIWIN               | 1         | 1      | 4.35%   |
| Apple               | 1         | 3      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 39        | 52     | 59.09%  |
| SSD  | 21        | 27     | 31.82%  |
| HDD  | 6         | 7      | 9.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 39        | 52     | 61.9%   |
| SATA | 22        | 32     | 34.92%  |
| SAS  | 2         | 2      | 3.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 22     | 64.29%  |
| 0.51-1.0   | 9         | 11     | 32.14%  |
| 1.01-2.0   | 1         | 1      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 31        | 49.21%  |
| 1-20           | 13        | 20.63%  |
| 251-500        | 4         | 6.35%   |
| 101-250        | 4         | 6.35%   |
| More than 3000 | 3         | 4.76%   |
| 1001-2000      | 3         | 4.76%   |
| 501-1000       | 3         | 4.76%   |
| 2001-3000      | 2         | 3.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| Unknown   | 31        | 49.21%  |
| 1-20      | 15        | 23.81%  |
| 101-250   | 7         | 11.11%  |
| 251-500   | 3         | 4.76%   |
| 501-1000  | 2         | 3.17%   |
| 51-100    | 2         | 3.17%   |
| 21-50     | 1         | 1.59%   |
| 2001-3000 | 1         | 1.59%   |
| 1001-2000 | 1         | 1.59%   |

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
| Works    | 55        | 72     | 83.33%  |
| Detected | 7         | 10     | 10.61%  |
| Malfunc  | 4         | 4      | 6.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 29        | 39.19%  |
| Samsung Electronics          | 16        | 21.62%  |
| SanDisk                      | 8         | 10.81%  |
| SK hynix                     | 5         | 6.76%   |
| Kingston Technology Company  | 4         | 5.41%   |
| Toshiba America Info Systems | 3         | 4.05%   |
| AMD                          | 3         | 4.05%   |
| Micron Technology            | 2         | 2.7%    |
| Yangtze Memory Technologies  | 1         | 1.35%   |
| Micron/Crucial Technology    | 1         | 1.35%   |
| KIOXIA                       | 1         | 1.35%   |
| Biwin Storage Technology     | 1         | 1.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 12.16%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 9.46%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 6.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 4.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 4.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 4.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 4.05%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 4.05%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 2.7%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 2.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 2.7%    |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 2.7%    |
| Micron NVMe Storage Controller                                                 | 2         | 2.7%    |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.7%    |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 1.35%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 1.35%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.35%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.35%   |
| SanDisk NVMe Controller                                                        | 1         | 1.35%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.35%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.35%   |
| Samsung Electronics SATA controller                                            | 1         | 1.35%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 1.35%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.35%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 1.35%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 1.35%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.35%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.35%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 1.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.35%   |
| Biwin Storage Non-Volatile memory controller                                   | 1         | 1.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 39        | 54.93%  |
| SATA | 27        | 38.03%  |
| RAID | 5         | 7.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 76.27%  |
| AMD    | 14        | 23.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 6.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 5.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 3         | 5.08%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 5.08%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 5.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 3.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 3.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 2         | 3.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 3.39%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 3.39%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 1.69%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 1.69%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 1.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 1.69%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 1.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 1.69%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 1         | 1.69%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 1.69%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 1.69%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 1.69%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 1.69%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 1         | 1.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 1.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 1.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 1         | 1.69%   |
| Intel Core i3-10110U CPU @ 2.10GHz         | 1         | 1.69%   |
| Intel Celeron N4120 CPU @ 1.10GHz          | 1         | 1.69%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 1         | 1.69%   |
| Intel Atom CPU N280 @ 1.66GHz              | 1         | 1.69%   |
| Intel 12th Gen Core i7-1270P               | 1         | 1.69%   |
| Intel 12th Gen Core i5-1240P               | 1         | 1.69%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz    | 1         | 1.69%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz    | 1         | 1.69%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 1         | 1.69%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 1         | 1.69%   |
| AMD Ryzen 9 5900HS with Radeon Graphics    | 1         | 1.69%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics | 1         | 1.69%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics | 1         | 1.69%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 1         | 1.69%   |
| AMD Ryzen 7 5800U with Radeon Graphics     | 1         | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 21        | 35.59%  |
| Other           | 10        | 16.95%  |
| AMD Ryzen 7     | 8         | 13.56%  |
| Intel Core i5   | 7         | 11.86%  |
| AMD Ryzen 7 PRO | 4         | 6.78%   |
| Intel Celeron   | 2         | 3.39%   |
| AMD Ryzen 9     | 2         | 3.39%   |
| Intel Xeon      | 1         | 1.69%   |
| Intel Core m3   | 1         | 1.69%   |
| Intel Core i9   | 1         | 1.69%   |
| Intel Core i3   | 1         | 1.69%   |
| Intel Atom      | 1         | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 23        | 38.98%  |
| 8      | 17        | 28.81%  |
| 2      | 13        | 22.03%  |
| 6      | 3         | 5.08%   |
| 12     | 2         | 3.39%   |
| 1      | 1         | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 56        | 94.92%  |
| 1      | 3         | 5.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 58        | 96.67%  |
| 32-bit         | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 21.31%  |
| 0x0a50000c | 7         | 11.48%  |
| 0x806ea    | 4         | 6.56%   |
| 0x806c1    | 4         | 6.56%   |
| 0x806ec    | 3         | 4.92%   |
| 0x08600106 | 3         | 4.92%   |
| 0x906ea    | 2         | 3.28%   |
| 0x906a3    | 2         | 3.28%   |
| 0x806eb    | 2         | 3.28%   |
| 0x806e9    | 2         | 3.28%   |
| 0x406e3    | 2         | 3.28%   |
| 0x306d4    | 2         | 3.28%   |
| 0x306c3    | 2         | 3.28%   |
| 0x0a404102 | 2         | 3.28%   |
| 0x906ed    | 1         | 1.64%   |
| 0x906e9    | 1         | 1.64%   |
| 0x806d1    | 1         | 1.64%   |
| 0x706a8    | 1         | 1.64%   |
| 0x706a1    | 1         | 1.64%   |
| 0x506e3    | 1         | 1.64%   |
| 0x40661    | 1         | 1.64%   |
| 0x40651    | 1         | 1.64%   |
| 0x306a9    | 1         | 1.64%   |
| 0x0a50000b | 1         | 1.64%   |
| 0x08600104 | 1         | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 30.51%  |
| Zen 3            | 8         | 13.56%  |
| TigerLake        | 6         | 10.17%  |
| Skylake          | 6         | 10.17%  |
| Zen 2            | 4         | 6.78%   |
| Haswell          | 4         | 6.78%   |
| Unknown          | 3         | 5.08%   |
| IvyBridge        | 2         | 3.39%   |
| Goldmont plus    | 2         | 3.39%   |
| Broadwell        | 2         | 3.39%   |
| Alderlake Hybrid | 2         | 3.39%   |
| Icelake          | 1         | 1.69%   |
| Bonnell          | 1         | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 53.09%  |
| Nvidia | 21        | 25.93%  |
| AMD    | 17        | 20.99%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 8         | 9.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 7.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 4.82%   |
| Intel UHD Graphics 620                                                                | 4         | 4.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 4.82%   |
| AMD Renoir                                                                            | 4         | 4.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 3.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 3.61%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 2.41%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 2.41%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 2.41%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 2.41%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 2.41%   |
| Intel HD Graphics 620                                                                 | 2         | 2.41%   |
| Intel HD Graphics 5500                                                                | 2         | 2.41%   |
| Intel HD Graphics 530                                                                 | 2         | 2.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 2.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 2.41%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 2.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 2.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 2.41%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 2.41%   |
| AMD Rembrandt [Radeon 680M]                                                           | 2         | 2.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.2%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 1.2%    |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 1.2%    |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 1.2%    |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.2%    |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 1.2%    |
| Nvidia GK106GLM [Quadro K2100M]                                                       | 1         | 1.2%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 1.2%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 1         | 1.2%    |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                    | 1         | 1.2%    |
| Intel UHD Graphics 615                                                                | 1         | 1.2%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                            | 1         | 1.2%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 1         | 1.2%    |
| Intel HD Graphics 630                                                                 | 1         | 1.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 1.2%    |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 1         | 1.2%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                        | 1         | 1.2%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 44.07%  |
| Intel + Nvidia | 14        | 23.73%  |
| 1 x AMD        | 8         | 13.56%  |
| AMD + Nvidia   | 6         | 10.17%  |
| Intel + AMD    | 2         | 3.39%   |
| 2 x Intel      | 1         | 1.69%   |
| 2 x AMD        | 1         | 1.69%   |
| 1 x Nvidia     | 1         | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 49        | 81.67%  |
| Proprietary | 9         | 15%     |
| Unknown     | 2         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 59.68%  |
| 0.01-0.5   | 10        | 16.13%  |
| 1.01-2.0   | 7         | 11.29%  |
| 3.01-4.0   | 6         | 9.68%   |
| 0.51-1.0   | 2         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 12        | 16.22%  |
| LG Display          | 9         | 12.16%  |
| Dell                | 8         | 10.81%  |
| BOE                 | 7         | 9.46%   |
| Samsung Electronics | 5         | 6.76%   |
| Chimei Innolux      | 5         | 6.76%   |
| Sharp               | 4         | 5.41%   |
| PANDA               | 4         | 5.41%   |
| CSO                 | 4         | 5.41%   |
| Panasonic           | 2         | 2.7%    |
| InfoVision          | 2         | 2.7%    |
| Hewlett-Packard     | 2         | 2.7%    |
| Philips             | 1         | 1.35%   |
| Lenovo              | 1         | 1.35%   |
| JDI                 | 1         | 1.35%   |
| HannStar            | 1         | 1.35%   |
| Goldstar            | 1         | 1.35%   |
| Eizo                | 1         | 1.35%   |
| ASUSTek Computer    | 1         | 1.35%   |
| Apple               | 1         | 1.35%   |
| AOC                 | 1         | 1.35%   |
| Acer                | 1         | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch          | 2         | 2.7%    |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 2.7%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 2.7%    |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 2.7%    |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 1.35%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 1.35%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 1.35%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 1.35%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 1.35%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 1.35%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 1.35%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 1.35%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1         | 1.35%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 1.35%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch               | 1         | 1.35%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 1.35%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 1         | 1.35%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 1.35%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.35%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 1.35%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.35%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 1.35%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 1         | 1.35%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch           | 1         | 1.35%   |
| Hewlett-Packard Z27 HPN3538 3840x2160 597x336mm 27.0-inch             | 1         | 1.35%   |
| Hewlett-Packard Z27 HPN3535 3840x2160 597x336mm 27.0-inch             | 1         | 1.35%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.35%   |
| Goldstar ULTRAGEAR GSM774A 3440x1440 800x335mm 34.1-inch              | 1         | 1.35%   |
| Eizo L568 ENC1734 1280x1024 338x270mm 17.0-inch                       | 1         | 1.35%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 1         | 1.35%   |
| Dell S3220DGF DELD0F2 2560x1440 697x392mm 31.5-inch                   | 1         | 1.35%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 1.35%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                     | 1         | 1.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 40%     |
| 3840x2160 (4K)     | 12        | 17.14%  |
| 2560x1440 (QHD)    | 8         | 11.43%  |
| 1366x768 (WXGA)    | 8         | 11.43%  |
| 2560x1600          | 3         | 4.29%   |
| 3440x1440          | 2         | 2.86%   |
| 2256x1504          | 2         | 2.86%   |
| 1920x1200 (WUXGA)  | 2         | 2.86%   |
| 3840x2400          | 1         | 1.43%   |
| 2880x1800          | 1         | 1.43%   |
| 1680x1050 (WSXGA+) | 1         | 1.43%   |
| 1280x1024 (SXGA)   | 1         | 1.43%   |
| 1024x600           | 1         | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 19        | 26.03%  |
| 13     | 12        | 16.44%  |
| 14     | 11        | 15.07%  |
| 27     | 7         | 9.59%   |
| 12     | 5         | 6.85%   |
| 24     | 4         | 5.48%   |
| 17     | 4         | 5.48%   |
| 34     | 2         | 2.74%   |
| 31     | 2         | 2.74%   |
| 23     | 2         | 2.74%   |
| 16     | 2         | 2.74%   |
| 46     | 1         | 1.37%   |
| 22     | 1         | 1.37%   |
| 10     | 1         | 1.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 50%     |
| 201-300     | 14        | 19.44%  |
| 501-600     | 12        | 16.67%  |
| 601-700     | 3         | 4.17%   |
| 351-400     | 3         | 4.17%   |
| 701-800     | 2         | 2.78%   |
| 401-500     | 1         | 1.39%   |
| 1001-1500   | 1         | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 47        | 78.33%  |
| 16/10 | 8         | 13.33%  |
| 3/2   | 2         | 3.33%   |
| 21/9  | 2         | 3.33%   |
| 5/4   | 1         | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 26.03%  |
| 81-90          | 17        | 23.29%  |
| 301-350        | 7         | 9.59%   |
| 201-250        | 7         | 9.59%   |
| 71-80          | 6         | 8.22%   |
| 61-70          | 5         | 6.85%   |
| 351-500        | 4         | 5.48%   |
| 121-130        | 3         | 4.11%   |
| 111-120        | 2         | 2.74%   |
| 41-50          | 1         | 1.37%   |
| 141-150        | 1         | 1.37%   |
| 501-1000       | 1         | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 36.36%  |
| 161-240       | 17        | 25.76%  |
| More than 240 | 8         | 12.12%  |
| 101-120       | 8         | 12.12%  |
| 51-100        | 8         | 12.12%  |
| 1-50          | 1         | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 41        | 64.06%  |
| 2     | 16        | 25%     |
| 0     | 5         | 7.81%   |
| 3     | 2         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 48        | 52.75%  |
| Realtek Semiconductor             | 28        | 30.77%  |
| Qualcomm Atheros                  | 4         | 4.4%    |
| Qualcomm                          | 2         | 2.2%    |
| MediaTek                          | 2         | 2.2%    |
| Lenovo                            | 2         | 2.2%    |
| Xiaomi                            | 1         | 1.1%    |
| Microsoft                         | 1         | 1.1%    |
| Fibocom                           | 1         | 1.1%    |
| Ericsson Business Mobile Networks | 1         | 1.1%    |
| Broadcom                          | 1         | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 14.29%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 9.82%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 8.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 4.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 2.68%   |
| Intel Wireless-AC 9260                                            | 3         | 2.68%   |
| Intel Wireless 8260                                               | 3         | 2.68%   |
| Intel Wireless 7265                                               | 3         | 2.68%   |
| Intel Wireless 7260                                               | 3         | 2.68%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 2.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.79%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.79%   |
| Intel Wireless 3165                                               | 2         | 1.79%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.79%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.79%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.89%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.89%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.89%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 0.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.89%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.89%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.89%   |
| Intel Wireless 3160                                               | 1         | 0.89%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.89%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 80%     |
| Qualcomm Atheros      | 4         | 6.67%   |
| Qualcomm              | 2         | 3.33%   |
| MediaTek              | 2         | 3.33%   |
| Realtek Semiconductor | 1         | 1.67%   |
| Microsoft             | 1         | 1.67%   |
| Fibocom               | 1         | 1.67%   |
| Broadcom              | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 10        | 16.67%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 8.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 5%      |
| Intel Wireless-AC 9260                                         | 3         | 5%      |
| Intel Wireless 8260                                            | 3         | 5%      |
| Intel Wireless 7265                                            | 3         | 5%      |
| Intel Wireless 7260                                            | 3         | 5%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 5%      |
| Intel Wireless 8265 / 8275                                     | 2         | 3.33%   |
| Intel Wireless 3165                                            | 2         | 3.33%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.67%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.67%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.67%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 1.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.67%   |
| Intel Wireless 3160                                            | 1         | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 1.67%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 1.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 27        | 57.45%  |
| Intel                 | 16        | 34.04%  |
| Lenovo                | 2         | 4.26%   |
| Xiaomi                | 1         | 2.13%   |
| Qualcomm Atheros      | 1         | 2.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 31.37%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 21.57%  |
| Intel Ethernet Connection I219-LM                                 | 3         | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.92%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.92%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 3.92%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 3.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.96%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.96%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.96%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.96%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 55.77%  |
| Ethernet | 45        | 43.27%  |
| Modem    | 1         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 79.71%  |
| Ethernet | 14        | 20.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 34        | 57.63%  |
| 1     | 24        | 40.68%  |
| 3     | 1         | 1.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 83.33%  |
| Yes  | 10        | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 81.48%  |
| Qualcomm Atheros Communications | 2         | 3.7%    |
| USI                             | 1         | 1.85%   |
| Realtek Semiconductor           | 1         | 1.85%   |
| MediaTek                        | 1         | 1.85%   |
| Lite-On Technology              | 1         | 1.85%   |
| Foxconn / Hon Hai               | 1         | 1.85%   |
| Broadcom                        | 1         | 1.85%   |
| ASUSTek Computer                | 1         | 1.85%   |
| Apple                           | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 12        | 22.22%  |
| Intel AX200 Bluetooth                          | 10        | 18.52%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 6         | 11.11%  |
| Intel AX210 Bluetooth                          | 5         | 9.26%   |
| Intel AX201 Bluetooth                          | 5         | 9.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 3         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 3.7%    |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 3.7%    |
| USI Bluetooth Device                           | 1         | 1.85%   |
| Realtek Bluetooth Radio                        | 1         | 1.85%   |
| MediaTek Wireless_Device                       | 1         | 1.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.85%   |
| Intel Bluetooth Device                         | 1         | 1.85%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 1.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 1.85%   |
| ASUS Broadcom Bluetooth 2.1                    | 1         | 1.85%   |
| Apple Bluetooth Host Controller                | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 45        | 52.94%  |
| AMD                       | 15        | 17.65%  |
| Nvidia                    | 7         | 8.24%   |
| Lenovo                    | 3         | 3.53%   |
| C-Media Electronics       | 3         | 3.53%   |
| Synaptics                 | 2         | 2.35%   |
| Realtek Semiconductor     | 2         | 2.35%   |
| Trust                     | 1         | 1.18%   |
| Sennheiser Communications | 1         | 1.18%   |
| Satechi                   | 1         | 1.18%   |
| Kingston Technology       | 1         | 1.18%   |
| Focusrite-Novation        | 1         | 1.18%   |
| Creative Technology       | 1         | 1.18%   |
| Corsair                   | 1         | 1.18%   |
| (LCS) USB Audio Device    | 1         | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 14        | 13.59%  |
| Intel Sunrise Point-LP HD Audio                                     | 11        | 10.68%  |
| AMD Renoir Radeon High Definition Audio Controller                  | 10        | 9.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 6         | 5.83%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 4         | 3.88%   |
| Intel Cannon Lake PCH cAVS                                          | 4         | 3.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 3         | 2.91%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                 | 2         | 1.94%   |
| Realtek Semiconductor USB Audio                                     | 2         | 1.94%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2         | 1.94%   |
| Nvidia GA106 High Definition Audio Controller                       | 2         | 1.94%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 2         | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 1.94%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                        | 2         | 1.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 2         | 1.94%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 1.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 2         | 1.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 1.94%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2         | 1.94%   |
| Trust USB microphone                                                | 1         | 0.97%   |
| Sennheiser Communications Headset [PC 8]                            | 1         | 0.97%   |
| Satechi Audio & PD Adapter                                          | 1         | 0.97%   |
| Nvidia GK106 HDMI Audio Controller                                  | 1         | 0.97%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                           | 1         | 0.97%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                        | 1         | 0.97%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                        | 1         | 0.97%   |
| Kingston Technology HyperX 7.1 Audio                                | 1         | 0.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 1         | 0.97%   |
| Intel Haswell-ULT HD Audio Controller                               | 1         | 0.97%   |
| Intel CM238 HD Audio Controller                                     | 1         | 0.97%   |
| Intel 8 Series HD Audio Controller                                  | 1         | 0.97%   |
| Focusrite-Novation Scarlett Solo USB                                | 1         | 0.97%   |
| Creative Technology SoundBlaster Live! 24-bit External SB0490       | 1         | 0.97%   |
| Corsair HS70 Pro Wireless Gaming Headset                            | 1         | 0.97%   |
| C-Media Electronics USB Advanced Audio Device                       | 1         | 0.97%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 1         | 0.97%   |
| C-Media Electronics AmazonBasics Desktop Mini Mic                   | 1         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 40.58%  |
| Micron Technology   | 10        | 14.49%  |
| Crucial             | 8         | 11.59%  |
| SK hynix            | 7         | 10.14%  |
| Kingston            | 5         | 7.25%   |
| Unknown             | 3         | 4.35%   |
| Unknown (ABCD)      | 2         | 2.9%    |
| Team                | 1         | 1.45%   |
| GOODRAM             | 1         | 1.45%   |
| G.Skill             | 1         | 1.45%   |
| Corsair             | 1         | 1.45%   |
| Avant               | 1         | 1.45%   |
| AMD                 | 1         | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.63%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 2.63%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 2.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.63%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 2.63%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 1.32%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.32%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 1.32%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 1.32%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.32%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 1.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.32%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.32%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.32%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.32%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 1         | 1.32%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 1.32%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.32%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 1.32%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.32%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.32%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 1.32%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.32%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1600MT/s                   | 1         | 1.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.32%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.32%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.32%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.32%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.32%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s             | 1         | 1.32%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 1         | 1.32%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.32%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.32%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.32%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 1.32%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.32%   |
| Samsung RAM M425R4GA3BB0-CQKOD 32GB SODIMM DDR5 4800MT/s         | 1         | 1.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 56.9%   |
| LPDDR4 | 9         | 15.52%  |
| DDR3   | 9         | 15.52%  |
| LPDDR3 | 3         | 5.17%   |
| LPDDR5 | 2         | 3.45%   |
| SDRAM  | 1         | 1.72%   |
| DDR5   | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 77.05%  |
| Row Of Chips | 11        | 18.03%  |
| Chip         | 2         | 3.28%   |
| Unknown      | 1         | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 26        | 41.27%  |
| 16384 | 18        | 28.57%  |
| 4096  | 11        | 17.46%  |
| 32768 | 5         | 7.94%   |
| 2048  | 2         | 3.17%   |
| 1024  | 1         | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 15        | 25%     |
| 2667    | 14        | 23.33%  |
| 1600    | 8         | 13.33%  |
| 4267    | 5         | 8.33%   |
| 2133    | 5         | 8.33%   |
| 2400    | 4         | 6.67%   |
| 6400    | 2         | 3.33%   |
| 4266    | 2         | 3.33%   |
| 1867    | 2         | 3.33%   |
| 4800    | 1         | 1.67%   |
| 3266    | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

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
| Chicony Electronics           | 14        | 26.42%  |
| Microdia                      | 10        | 18.87%  |
| IMC Networks                  | 8         | 15.09%  |
| Acer                          | 5         | 9.43%   |
| Sunplus Innovation Technology | 3         | 5.66%   |
| Realtek Semiconductor         | 3         | 5.66%   |
| Quanta                        | 2         | 3.77%   |
| Logitech                      | 2         | 3.77%   |
| Bison Electronics             | 2         | 3.77%   |
| webcam                        | 1         | 1.89%   |
| Syntek                        | 1         | 1.89%   |
| Lite-On Technology            | 1         | 1.89%   |
| Alcor Micro                   | 1         | 1.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 9         | 16.36%  |
| Microdia Integrated_Webcam_HD        | 6         | 10.91%  |
| IMC Networks USB2.0 HD UVC WebCam    | 3         | 5.45%   |
| IMC Networks Integrated Camera       | 3         | 5.45%   |
| Chicony HP HD Camera                 | 3         | 5.45%   |
| Sunplus Integrated_Webcam_FHD        | 2         | 3.64%   |
| Realtek Laptop Camera                | 2         | 3.64%   |
| Quanta VGA WebCam                    | 2         | 3.64%   |
| Acer Integrated IR Camera            | 2         | 3.64%   |
| Acer Integrated Camera               | 2         | 3.64%   |
| webcam webcam                        | 1         | 1.82%   |
| Syntek Integrated Camera             | 1         | 1.82%   |
| Sunplus Integrated_Webcam_HD         | 1         | 1.82%   |
| Realtek Integrated Webcam            | 1         | 1.82%   |
| Microdia Webcam Vitade AF            | 1         | 1.82%   |
| Microdia USB 2.0 Camera              | 1         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_HD | 1         | 1.82%   |
| Microdia Integrated Webcam           | 1         | 1.82%   |
| Logitech Webcam C310                 | 1         | 1.82%   |
| Logitech HD Pro Webcam C920          | 1         | 1.82%   |
| Lite-On HP HD Camera                 | 1         | 1.82%   |
| IMC Networks XHC Camera              | 1         | 1.82%   |
| IMC Networks USB2.0 UVC 1.3M WebCam  | 1         | 1.82%   |
| Chicony USB2.0 Camera                | 1         | 1.82%   |
| Chicony Integrated Camera [ThinkPad] | 1         | 1.82%   |
| Bison Integrated RGB Camera          | 1         | 1.82%   |
| Bison Integrated Camera              | 1         | 1.82%   |
| Alcor Micro USB 2.0 Camera           | 1         | 1.82%   |
| Acer ThinkPad P50 Integrated Camera  | 1         | 1.82%   |
| Acer SunplusIT Integrated Camera     | 1         | 1.82%   |
| Acer HD Webcam                       | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 50%     |
| Validity Sensors           | 6         | 37.5%   |
| Shenzhen Goodix Technology | 2         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 4         | 25%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 2         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 12.5%   |
| Synaptics UWP WBDI Device                                | 2         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 6.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device                      | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 9         | 69.23%  |
| Yubico.com  | 2         | 15.38%  |
| Upek        | 1         | 7.69%   |
| Broadcom    | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 9         | 69.23%  |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 7.69%   |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 1         | 7.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 24        | 39.34%  |
| 1     | 22        | 36.07%  |
| 2     | 12        | 19.67%  |
| 4     | 2         | 3.28%   |
| 3     | 1         | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 24.56%  |
| Graphics card            | 13        | 22.81%  |
| Chipcard                 | 10        | 17.54%  |
| Multimedia controller    | 9         | 15.79%  |
| Net/wireless             | 3         | 5.26%   |
| Modem                    | 2         | 3.51%   |
| Camera                   | 2         | 3.51%   |
| Network                  | 1         | 1.75%   |
| Communication controller | 1         | 1.75%   |
| Card reader              | 1         | 1.75%   |
| Bluetooth                | 1         | 1.75%   |

