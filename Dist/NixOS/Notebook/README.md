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

Total: 133

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8470p             | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | [c384115725](https://linux-hardware.org/?probe=c384115725) | Aug 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| System76      | Pangolin                    | [3b37a9bedb](https://linux-hardware.org/?probe=3b37a9bedb) | Jul 29, 2023 |
| Alienware     | 17                          | [25f67e59b8](https://linux-hardware.org/?probe=25f67e59b8) | Jul 26, 2023 |
| Apple         | MacBookPro11,3              | [8d48a50003](https://linux-hardware.org/?probe=8d48a50003) | Jul 22, 2023 |
| Apple         | MacBookPro11,3              | [c29abaca55](https://linux-hardware.org/?probe=c29abaca55) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASUSTek       | 1005HA                      | [59a0d6a7bb](https://linux-hardware.org/?probe=59a0d6a7bb) | Jul 19, 2023 |
| MSI           | Alpha 15 B5EEK              | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
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
| NixOS 22.11                      | 27        | 25.96%  |
| NixOS 23.05                      | 26        | 25%     |
| NixOS 22.05                      | 18        | 17.31%  |
| NixOS 23.11                      | 10        | 9.62%   |
| NixOS 21.11                      | 9         | 8.65%   |
| NixOS                            | 2         | 1.92%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.96%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.96%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.96%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.96%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.96%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.96%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.96%   |
| NixOS 20.09pre-git               | 1         | 0.96%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.96%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.96%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.96%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 92        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Notebooks | Percent |
|------------------|-----------|---------|
| 6.3.8            | 4         | 3.64%   |
| 6.3.3            | 3         | 2.73%   |
| 6.1.38           | 3         | 2.73%   |
| 5.15.74          | 3         | 2.73%   |
| 5.15.43          | 3         | 2.73%   |
| 6.4.0            | 2         | 1.82%   |
| 6.3.1            | 2         | 1.82%   |
| 6.1.41           | 2         | 1.82%   |
| 6.1.35           | 2         | 1.82%   |
| 6.1.34           | 2         | 1.82%   |
| 6.1.0            | 2         | 1.82%   |
| 6.0.10           | 2         | 1.82%   |
| 5.16.15          | 2         | 1.82%   |
| 5.15.72          | 2         | 1.82%   |
| 5.15.68          | 2         | 1.82%   |
| 5.15.64          | 2         | 1.82%   |
| 5.15.26          | 2         | 1.82%   |
| 5.13.7           | 2         | 1.82%   |
| 6.4.8            | 1         | 0.91%   |
| 6.4.6            | 1         | 0.91%   |
| 6.3.9            | 1         | 0.91%   |
| 6.3.5            | 1         | 0.91%   |
| 6.2.9-lqx1       | 1         | 0.91%   |
| 6.2.9            | 1         | 0.91%   |
| 6.2.8            | 1         | 0.91%   |
| 6.2.7            | 1         | 0.91%   |
| 6.2.14           | 1         | 0.91%   |
| 6.2.0            | 1         | 0.91%   |
| 6.1.7-xanmod1    | 1         | 0.91%   |
| 6.1.43           | 1         | 0.91%   |
| 6.1.42           | 1         | 0.91%   |
| 6.1.39           | 1         | 0.91%   |
| 6.1.27           | 1         | 0.91%   |
| 6.1.25           | 1         | 0.91%   |
| 6.1.24           | 1         | 0.91%   |
| 6.1.22-hardened1 | 1         | 0.91%   |
| 6.1.21           | 1         | 0.91%   |
| 6.1.1            | 1         | 0.91%   |
| 6.0.2-xanmod1-tt | 1         | 0.91%   |
| 6.0.11           | 1         | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.8   | 4         | 3.64%   |
| 6.3.3   | 3         | 2.73%   |
| 6.1.38  | 3         | 2.73%   |
| 6.0.10  | 3         | 2.73%   |
| 5.15.74 | 3         | 2.73%   |
| 5.15.43 | 3         | 2.73%   |
| 6.4.0   | 2         | 1.82%   |
| 6.3.1   | 2         | 1.82%   |
| 6.2.9   | 2         | 1.82%   |
| 6.1.41  | 2         | 1.82%   |
| 6.1.35  | 2         | 1.82%   |
| 6.1.34  | 2         | 1.82%   |
| 6.1.0   | 2         | 1.82%   |
| 5.16.15 | 2         | 1.82%   |
| 5.15.72 | 2         | 1.82%   |
| 5.15.68 | 2         | 1.82%   |
| 5.15.64 | 2         | 1.82%   |
| 5.15.26 | 2         | 1.82%   |
| 5.13.7  | 2         | 1.82%   |
| 6.4.8   | 1         | 0.91%   |
| 6.4.6   | 1         | 0.91%   |
| 6.3.9   | 1         | 0.91%   |
| 6.3.5   | 1         | 0.91%   |
| 6.2.8   | 1         | 0.91%   |
| 6.2.7   | 1         | 0.91%   |
| 6.2.14  | 1         | 0.91%   |
| 6.2.0   | 1         | 0.91%   |
| 6.1.7   | 1         | 0.91%   |
| 6.1.43  | 1         | 0.91%   |
| 6.1.42  | 1         | 0.91%   |
| 6.1.39  | 1         | 0.91%   |
| 6.1.27  | 1         | 0.91%   |
| 6.1.25  | 1         | 0.91%   |
| 6.1.24  | 1         | 0.91%   |
| 6.1.22  | 1         | 0.91%   |
| 6.1.21  | 1         | 0.91%   |
| 6.1.1   | 1         | 0.91%   |
| 6.0.2   | 1         | 0.91%   |
| 6.0.11  | 1         | 0.91%   |
| 6.0.0   | 1         | 0.91%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 28.97%  |
| 6.1     | 20        | 18.69%  |
| 6.3     | 11        | 10.28%  |
| 6.2     | 6         | 5.61%   |
| 6.0     | 6         | 5.61%   |
| 5.16    | 6         | 5.61%   |
| 6.4     | 4         | 3.74%   |
| 5.8     | 3         | 2.8%    |
| 5.19    | 3         | 2.8%    |
| 5.13    | 3         | 2.8%    |
| 5.10    | 3         | 2.8%    |
| 5.7     | 2         | 1.87%   |
| 5.4     | 2         | 1.87%   |
| 5.18    | 2         | 1.87%   |
| 5.17    | 2         | 1.87%   |
| 4.19    | 2         | 1.87%   |
| 5.12    | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 91        | 98.91%  |
| i686   | 1         | 1.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 44        | 45.36%  |
| GNOME        | 14        | 14.43%  |
| sway         | 10        | 10.31%  |
| KDE5         | 9         | 9.28%   |
| Hyprland     | 7         | 7.22%   |
| XFCE         | 3         | 3.09%   |
| none+i3      | 3         | 3.09%   |
| none+xmonad  | 2         | 2.06%   |
| KDE          | 2         | 2.06%   |
| X-Cinnamon   | 1         | 1.03%   |
| none+bspwm   | 1         | 1.03%   |
| none+awesome | 1         | 1.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 47        | 47.96%  |
| Wayland | 31        | 31.63%  |
| X11     | 17        | 17.35%  |
| Tty     | 3         | 3.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 54.26%  |
| GDM     | 19        | 20.21%  |
| SDDM    | 13        | 13.83%  |
| LightDM | 11        | 11.7%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 46        | 48.94%  |
| Unknown | 32        | 34.04%  |
| en_GB   | 4         | 4.26%   |
| en_DK   | 2         | 2.13%   |
| en_CA   | 2         | 2.13%   |
| ru_RU   | 1         | 1.06%   |
| ro_RO   | 1         | 1.06%   |
| lv_LV   | 1         | 1.06%   |
| it_IT   | 1         | 1.06%   |
| fr_FR   | 1         | 1.06%   |
| es_MX   | 1         | 1.06%   |
| en_IN   | 1         | 1.06%   |
| de_DE   | 1         | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 83        | 90.22%  |
| BIOS | 9         | 9.78%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 51        | 53.13%  |
| Btrfs   | 15        | 15.63%  |
| Tmpfs   | 11        | 11.46%  |
| Zfs     | 8         | 8.33%   |
| Xfs     | 8         | 8.33%   |
| Unknown | 3         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 87        | 92.55%  |
| Unknown | 5         | 5.32%   |
| MBR     | 2         | 2.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 79.79%  |
| Yes       | 19        | 20.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 72.83%  |
| Yes       | 25        | 27.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 35        | 38.04%  |
| Dell                   | 15        | 16.3%   |
| ASUSTek Computer       | 11        | 11.96%  |
| Hewlett-Packard        | 6         | 6.52%   |
| Apple                  | 4         | 4.35%   |
| GPD                    | 3         | 3.26%   |
| MSI                    | 2         | 2.17%   |
| MECHREVO               | 2         | 2.17%   |
| Framework              | 2         | 2.17%   |
| Acer                   | 2         | 2.17%   |
| Toshiba                | 1         | 1.09%   |
| System76               | 1         | 1.09%   |
| OBSIDIAN-PC            | 1         | 1.09%   |
| Microtech              | 1         | 1.09%   |
| MACHENIKE              | 1         | 1.09%   |
| HUAWEI                 | 1         | 1.09%   |
| Gigabyte Technology    | 1         | 1.09%   |
| Blackview              | 1         | 1.09%   |
| Avell High Performance | 1         | 1.09%   |
| Alienware              | 1         | 1.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Latitude 7420                          | 2         | 2.17%   |
| Apple MacBookPro11,5                        | 2         | 2.17%   |
| Apple MacBookPro11,3                        | 2         | 2.17%   |
| Toshiba Satellite L50-B                     | 1         | 1.09%   |
| System76 Pangolin                           | 1         | 1.09%   |
| OBSIDIAN-PC N13_N140ZU                      | 1         | 1.09%   |
| MSI Bravo 15 B5DD                           | 1         | 1.09%   |
| MSI Alpha 15 B5EEK                          | 1         | 1.09%   |
| Microtech CoreBook Lite                     | 1         | 1.09%   |
| MECHREVO WUJIE 14                           | 1         | 1.09%   |
| MECHREVO Code01 Ver2.0                      | 1         | 1.09%   |
| MACHENIKE F117-7P                           | 1         | 1.09%   |
| Lenovo Yoga Slim 7 13ACN5 82CY              | 1         | 1.09%   |
| Lenovo Yoga 14sARE 2020 82A8                | 1         | 1.09%   |
| Lenovo ThinkPad X390 20Q0CTO1WW             | 1         | 1.09%   |
| Lenovo ThinkPad X260 20F5S6MF02             | 1         | 1.09%   |
| Lenovo ThinkPad X260 20F5S4BY00             | 1         | 1.09%   |
| Lenovo ThinkPad X250 20CLS18S0T             | 1         | 1.09%   |
| Lenovo ThinkPad X230 2333AZ2                | 1         | 1.09%   |
| Lenovo ThinkPad X230 23243E9                | 1         | 1.09%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW       | 1         | 1.09%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB007AUK | 1         | 1.09%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBCT01WW    | 1         | 1.09%   |
| Lenovo ThinkPad T580 20L90024PB             | 1         | 1.09%   |
| Lenovo ThinkPad T540p 20BE005YMH            | 1         | 1.09%   |
| Lenovo ThinkPad T490 20N2000LUK             | 1         | 1.09%   |
| Lenovo ThinkPad T480 20L5CTO1WW             | 1         | 1.09%   |
| Lenovo ThinkPad T460p 20FWCTO1WW            | 1         | 1.09%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW        | 1         | 1.09%   |
| Lenovo ThinkPad T14s Gen 3 21BR000MUS       | 1         | 1.09%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK       | 1         | 1.09%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT        | 1         | 1.09%   |
| Lenovo ThinkPad P50 20EN0005GE              | 1         | 1.09%   |
| Lenovo ThinkPad P14s Gen 3 21J5002KMH       | 1         | 1.09%   |
| Lenovo ThinkPad P14s Gen 1 20Y1S00C00       | 1         | 1.09%   |
| Lenovo ThinkPad E470 20H1006JIX             | 1         | 1.09%   |
| Lenovo ThinkPad E14 Gen 4 21EBCTO1WW        | 1         | 1.09%   |
| Lenovo ThinkBook 16 G4+ ARA 21D1            | 1         | 1.09%   |
| Lenovo Legion Y7000 2019 PG0 81T0           | 1         | 1.09%   |
| Lenovo Legion S7 15ACH6 82K8                | 1         | 1.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 23        | 25%     |
| Dell XPS                   | 6         | 6.52%   |
| Lenovo Legion              | 5         | 5.43%   |
| Dell Latitude              | 5         | 5.43%   |
| ASUS ROG                   | 4         | 4.35%   |
| Apple MacBookPro11         | 4         | 4.35%   |
| Lenovo IdeaPad             | 3         | 3.26%   |
| HP EliteBook               | 3         | 3.26%   |
| ASUS Zenbook               | 3         | 3.26%   |
| Lenovo Yoga                | 2         | 2.17%   |
| HP ProBook                 | 2         | 2.17%   |
| Framework Laptop           | 2         | 2.17%   |
| Dell Precision             | 2         | 2.17%   |
| Dell Inspiron              | 2         | 2.17%   |
| Acer Aspire                | 2         | 2.17%   |
| Toshiba Satellite          | 1         | 1.09%   |
| System76 Pangolin          | 1         | 1.09%   |
| OBSIDIAN-PC N13            | 1         | 1.09%   |
| MSI Bravo                  | 1         | 1.09%   |
| MSI Alpha                  | 1         | 1.09%   |
| Microtech CoreBook         | 1         | 1.09%   |
| MECHREVO WUJIE             | 1         | 1.09%   |
| MECHREVO Code01            | 1         | 1.09%   |
| MACHENIKE F117-7P          | 1         | 1.09%   |
| Lenovo ThinkBook           | 1         | 1.09%   |
| Lenovo G50-70              | 1         | 1.09%   |
| HUAWEI NBLK-WAX9X          | 1         | 1.09%   |
| HP ZBook                   | 1         | 1.09%   |
| GPD WIN2                   | 1         | 1.09%   |
| GPD MicroPC                | 1         | 1.09%   |
| GPD G1621-02               | 1         | 1.09%   |
| Gigabyte Sabre             | 1         | 1.09%   |
| Blackview AceBook          | 1         | 1.09%   |
| Avell High Performance A70 | 1         | 1.09%   |
| ASUS VivoBook              | 1         | 1.09%   |
| ASUS ProArt                | 1         | 1.09%   |
| ASUS ASUSPRO               | 1         | 1.09%   |
| ASUS 1005HA                | 1         | 1.09%   |
| Alienware 17               | 1         | 1.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 18        | 19.57%  |
| 2020 | 13        | 14.13%  |
| 2022 | 11        | 11.96%  |
| 2019 | 10        | 10.87%  |
| 2016 | 9         | 9.78%   |
| 2018 | 7         | 7.61%   |
| 2013 | 6         | 6.52%   |
| 2023 | 4         | 4.35%   |
| 2015 | 4         | 4.35%   |
| 2017 | 3         | 3.26%   |
| 2014 | 3         | 3.26%   |
| 2012 | 2         | 2.17%   |
| 2011 | 1         | 1.09%   |
| 2009 | 1         | 1.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 92        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 91        | 97.85%  |
| Enabled  | 2         | 2.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 91        | 98.91%  |
| Yes  | 1         | 1.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 24        | 25.81%  |
| 16.01-24.0  | 24        | 25.81%  |
| 8.01-16.0   | 22        | 23.66%  |
| 4.01-8.0    | 12        | 12.9%   |
| 64.01-256.0 | 5         | 5.38%   |
| 3.01-4.0    | 3         | 3.23%   |
| 24.01-32.0  | 2         | 2.15%   |
| 0.51-1.0    | 1         | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 30        | 28.04%  |
| 3.01-4.0   | 21        | 19.63%  |
| 2.01-3.0   | 17        | 15.89%  |
| 8.01-16.0  | 16        | 14.95%  |
| 1.01-2.0   | 9         | 8.41%   |
| 24.01-32.0 | 5         | 4.67%   |
| 0.51-1.0   | 4         | 3.74%   |
| 32.01-64.0 | 2         | 1.87%   |
| 16.01-24.0 | 2         | 1.87%   |
| 0.01-0.5   | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 68        | 73.12%  |
| 2      | 23        | 24.73%  |
| 3      | 2         | 2.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 92.39%  |
| Yes       | 7         | 7.61%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 67.37%  |
| No        | 31        | 32.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 98.91%  |
| No        | 1         | 1.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 91.49%  |
| No        | 8         | 8.51%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 14        | 15.22%  |
| UK          | 7         | 7.61%   |
| Russia      | 7         | 7.61%   |
| France      | 7         | 7.61%   |
| Italy       | 5         | 5.43%   |
| Germany     | 5         | 5.43%   |
| Ukraine     | 4         | 4.35%   |
| Poland      | 4         | 4.35%   |
| Canada      | 4         | 4.35%   |
| Netherlands | 3         | 3.26%   |
| Switzerland | 2         | 2.17%   |
| Japan       | 2         | 2.17%   |
| Iraq        | 2         | 2.17%   |
| India       | 2         | 2.17%   |
| Belgium     | 2         | 2.17%   |
| Austria     | 2         | 2.17%   |
| Uruguay     | 1         | 1.09%   |
| Sweden      | 1         | 1.09%   |
| Spain       | 1         | 1.09%   |
| Slovenia    | 1         | 1.09%   |
| Singapore   | 1         | 1.09%   |
| Serbia      | 1         | 1.09%   |
| Romania     | 1         | 1.09%   |
| Portugal    | 1         | 1.09%   |
| Peru        | 1         | 1.09%   |
| Mexico      | 1         | 1.09%   |
| Latvia      | 1         | 1.09%   |
| Kuwait      | 1         | 1.09%   |
| Iran        | 1         | 1.09%   |
| Hungary     | 1         | 1.09%   |
| Hong Kong   | 1         | 1.09%   |
| Denmark     | 1         | 1.09%   |
| Czechia     | 1         | 1.09%   |
| Colombia    | 1         | 1.09%   |
| China       | 1         | 1.09%   |
| Brazil      | 1         | 1.09%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 3         | 3.03%   |
| Vienna             | 2         | 2.02%   |
| Phoenix            | 2         | 2.02%   |
| Ottawa             | 2         | 2.02%   |
| Marki              | 2         | 2.02%   |
| Kharkiv            | 2         | 2.02%   |
| Halifax            | 2         | 2.02%   |
| Catania            | 2         | 2.02%   |
| Baghdad            | 2         | 2.02%   |
| Zurich             | 1         | 1.01%   |
| Yangzhou           | 1         | 1.01%   |
| Woodford           | 1         | 1.01%   |
| Woldegk            | 1         | 1.01%   |
| Warsaw             | 1         | 1.01%   |
| Villeurbanne       | 1         | 1.01%   |
| Verneuil-sur-Seine | 1         | 1.01%   |
| Valpacos           | 1         | 1.01%   |
| Trento             | 1         | 1.01%   |
| Tremestieri Etneo  | 1         | 1.01%   |
| Tottenham          | 1         | 1.01%   |
| Tolyatti           | 1         | 1.01%   |
| Tehran             | 1         | 1.01%   |
| Szigetszentmiklos  | 1         | 1.01%   |
| Stockholm          | 1         | 1.01%   |
| Staten Island      | 1         | 1.01%   |
| St Petersburg      | 1         | 1.01%   |
| Southampton        | 1         | 1.01%   |
| South Deerfield    | 1         | 1.01%   |
| Smolensk           | 1         | 1.01%   |
| Singapore          | 1         | 1.01%   |
| Saratov            | 1         | 1.01%   |
| Santee             | 1         | 1.01%   |
| Rochester          | 1         | 1.01%   |
| Riga               | 1         | 1.01%   |
| Rho                | 1         | 1.01%   |
| Puebla City        | 1         | 1.01%   |
| Prague             | 1         | 1.01%   |
| Plymouth           | 1         | 1.01%   |
| Pittsburgh         | 1         | 1.01%   |
| Odense             | 1         | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 35        | 47     | 30.7%   |
| SanDisk                     | 11        | 11     | 9.65%   |
| WDC                         | 8         | 8      | 7.02%   |
| SK hynix                    | 7         | 10     | 6.14%   |
| Toshiba                     | 6         | 6      | 5.26%   |
| Micron Technology           | 6         | 7      | 5.26%   |
| Apple                       | 5         | 7      | 4.39%   |
| Kingston                    | 4         | 5      | 3.51%   |
| Intel                       | 4         | 5      | 3.51%   |
| Unknown                     | 3         | 3      | 2.63%   |
| Crucial                     | 3         | 4      | 2.63%   |
| Yangtze Memory Technologies | 2         | 2      | 1.75%   |
| Transcend                   | 2         | 2      | 1.75%   |
| Seagate                     | 2         | 3      | 1.75%   |
| KIOXIA                      | 2         | 3      | 1.75%   |
| Kingston Technology Company | 2         | 2      | 1.75%   |
| A-DATA Technology           | 2         | 2      | 1.75%   |
| SPCC                        | 1         | 1      | 0.88%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.88%   |
| INNOVATION IT               | 1         | 1      | 0.88%   |
| Hitachi                     | 1         | 2      | 0.88%   |
| HGST                        | 1         | 1      | 0.88%   |
| Dogfish                     | 1         | 1      | 0.88%   |
| China                       | 1         | 1      | 0.88%   |
| Biwin Storage Technology    | 1         | 1      | 0.88%   |
| BIWIN                       | 1         | 1      | 0.88%   |
| ADATA Technology            | 1         | 2      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 8         | 6.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 5         | 4.13%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 2         | 1.65%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 1.65%   |
| Samsung PM9A1 NVMe 1024GB                           | 2         | 1.65%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 1.65%   |
| Apple SSD SM0512G 500GB                             | 2         | 1.65%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                | 1         | 0.83%   |
| Yangtze Memory YMTC PC300-1TB-B                     | 1         | 0.83%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                    | 1         | 0.83%   |
| WDC WDS200T1X0E-00AFY0 2TB                          | 1         | 0.83%   |
| WDC WD7500BPKX-75HPJT0 752GB                        | 1         | 0.83%   |
| WDC WD10 JPLX-00MBPT0 1TB                           | 1         | 0.83%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                  | 1         | 0.83%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 0.83%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB                  | 1         | 0.83%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB                | 1         | 0.83%   |
| Unknown MMC Card  64GB                              | 1         | 0.83%   |
| Unknown MMC Card  250GB                             | 1         | 0.83%   |
| Unknown MMC Card  128GB                             | 1         | 0.83%   |
| Transcend TS256GMTS800 256GB SSD                    | 1         | 0.83%   |
| Transcend TS256GMTS430S 256GB SSD                   | 1         | 0.83%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 1         | 0.83%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 0.83%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.83%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 0.83%   |
| Toshiba KXG6AZNV512G 512GB                          | 1         | 0.83%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 0.83%   |
| SPCC 2.5 SSD 1TB                                    | 1         | 0.83%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 0.83%   |
| SK hynix PC801 NVMe 512GB                           | 1         | 0.83%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 1         | 0.83%   |
| SK hynix NVMe SSD Drive 1TB                         | 1         | 0.83%   |
| SK hynix NVMe SSD Drive 1024GB                      | 1         | 0.83%   |
| SK hynix HFM001TD3JX013N 1TB                        | 1         | 0.83%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 0.83%   |
| Sandisk WD_BLACK SN770 2TB                          | 1         | 0.83%   |
| Sandisk WD_BLACK SN770 1TB                          | 1         | 0.83%   |
| Sandisk WDC PC SN530 SDBPMPZ-256G-1101 256GB        | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| Seagate | 2         | 3      | 20%     |
| Hitachi | 1         | 2      | 10%     |
| HGST    | 1         | 1      | 10%     |
| Apple   | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 14     | 36.36%  |
| Apple               | 4         | 6      | 12.12%  |
| SanDisk             | 3         | 3      | 9.09%   |
| Transcend           | 2         | 2      | 6.06%   |
| Micron Technology   | 2         | 2      | 6.06%   |
| Crucial             | 2         | 3      | 6.06%   |
| WDC                 | 1         | 1      | 3.03%   |
| SPCC                | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| INNOVATION IT       | 1         | 1      | 3.03%   |
| Dogfish             | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |
| BIWIN               | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 63        | 86     | 59.43%  |
| SSD  | 30        | 38     | 28.3%   |
| HDD  | 10        | 12     | 9.43%   |
| MMC  | 3         | 3      | 2.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 63        | 86     | 62.38%  |
| SATA | 32        | 47     | 31.68%  |
| SAS  | 3         | 3      | 2.97%   |
| MMC  | 3         | 3      | 2.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 33     | 63.41%  |
| 0.51-1.0   | 14        | 16     | 34.15%  |
| 1.01-2.0   | 1         | 1      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 33        | 34.38%  |
| 1-20           | 26        | 27.08%  |
| 251-500        | 10        | 10.42%  |
| 501-1000       | 8         | 8.33%   |
| 101-250        | 7         | 7.29%   |
| 1001-2000      | 5         | 5.21%   |
| More than 3000 | 4         | 4.17%   |
| 2001-3000      | 3         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| Unknown   | 33        | 33.67%  |
| 1-20      | 28        | 28.57%  |
| 101-250   | 13        | 13.27%  |
| 51-100    | 7         | 7.14%   |
| 21-50     | 6         | 6.12%   |
| 501-1000  | 5         | 5.1%    |
| 251-500   | 4         | 4.08%   |
| 2001-3000 | 1         | 1.02%   |
| 1001-2000 | 1         | 1.02%   |

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
| Works    | 87        | 120    | 84.47%  |
| Detected | 10        | 13     | 9.71%   |
| Malfunc  | 5         | 5      | 4.85%   |
| Failed   | 1         | 1      | 0.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 45        | 37.5%   |
| Samsung Electronics          | 28        | 23.33%  |
| SanDisk                      | 13        | 10.83%  |
| SK hynix                     | 6         | 5%      |
| Kingston Technology Company  | 5         | 4.17%   |
| AMD                          | 5         | 4.17%   |
| Toshiba America Info Systems | 4         | 3.33%   |
| Micron Technology            | 4         | 3.33%   |
| ADATA Technology             | 3         | 2.5%    |
| Yangtze Memory Technologies  | 2         | 1.67%   |
| Micron/Crucial Technology    | 1         | 0.83%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.83%   |
| Marvell Technology Group     | 1         | 0.83%   |
| KIOXIA                       | 1         | 0.83%   |
| Biwin Storage Technology     | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 9.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 7.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 6.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 4.07%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 4.07%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 3.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.25%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 2.44%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 3         | 2.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 2.44%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.63%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 1.63%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.63%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.63%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 1.63%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 2         | 1.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.63%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.63%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.63%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 1.63%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.63%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 1         | 0.81%   |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 0.81%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.81%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.81%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 0.81%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.81%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.81%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.81%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1         | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.81%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1         | 0.81%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 63        | 55.26%  |
| SATA | 43        | 37.72%  |
| RAID | 8         | 7.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 71.74%  |
| AMD    | 26        | 28.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 4.35%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 4         | 4.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 4         | 4.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 3.26%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 3         | 3.26%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 3.26%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 3.26%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 3         | 3.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 2.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 2.17%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 2.17%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 2.17%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 2         | 2.17%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 2         | 2.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 2         | 2.17%   |
| Intel 12th Gen Core i7-1260P               | 2         | 2.17%   |
| Intel 12th Gen Core i5-1240P               | 2         | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 2.17%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 2         | 2.17%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 2.17%   |
| Intel Xeon E-2276M CPU @ 2.80GHz           | 1         | 1.09%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 1.09%   |
| Intel Pentium Gold 7505 @ 2.00GHz          | 1         | 1.09%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 1.09%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 1.09%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 1.09%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 1.09%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 1.09%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz         | 1         | 1.09%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 1.09%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz         | 1         | 1.09%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 1.09%   |
| Intel Core i5-9300H CPU @ 2.40GHz          | 1         | 1.09%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 1         | 1.09%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 1         | 1.09%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 1         | 1.09%   |
| Intel Core i3-10110U CPU @ 2.10GHz         | 1         | 1.09%   |
| Intel Celeron N4120 CPU @ 1.10GHz          | 1         | 1.09%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 1         | 1.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 27        | 29.35%  |
| Other              | 16        | 17.39%  |
| AMD Ryzen 7        | 14        | 15.22%  |
| Intel Core i5      | 13        | 14.13%  |
| AMD Ryzen 9        | 5         | 5.43%   |
| AMD Ryzen 7 PRO    | 5         | 5.43%   |
| Intel Celeron      | 3         | 3.26%   |
| Intel Xeon         | 2         | 2.17%   |
| AMD Ryzen 5        | 2         | 2.17%   |
| Intel Pentium Gold | 1         | 1.09%   |
| Intel Core m3      | 1         | 1.09%   |
| Intel Core i9      | 1         | 1.09%   |
| Intel Core i3      | 1         | 1.09%   |
| Intel Atom         | 1         | 1.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 32        | 34.78%  |
| 8      | 28        | 30.43%  |
| 2      | 19        | 20.65%  |
| 12     | 5         | 5.43%   |
| 6      | 5         | 5.43%   |
| 24     | 1         | 1.09%   |
| 16     | 1         | 1.09%   |
| 1      | 1         | 1.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 92        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 87        | 94.57%  |
| 1      | 5         | 5.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 91        | 97.85%  |
| 32-bit         | 1         | 1.08%   |
| Unknown        | 1         | 1.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 25%     |
| 0x0a50000c | 11        | 11.46%  |
| 0x806c1    | 5         | 5.21%   |
| 0x08600106 | 5         | 5.21%   |
| 0x806ea    | 4         | 4.17%   |
| 0x406e3    | 4         | 4.17%   |
| 0x806ec    | 3         | 3.13%   |
| 0x806eb    | 3         | 3.13%   |
| 0x40661    | 3         | 3.13%   |
| 0x306c3    | 3         | 3.13%   |
| 0x0a404102 | 3         | 3.13%   |
| 0x906ed    | 2         | 2.08%   |
| 0x906ea    | 2         | 2.08%   |
| 0x906a3    | 2         | 2.08%   |
| 0x806e9    | 2         | 2.08%   |
| 0x706a8    | 2         | 2.08%   |
| 0x40651    | 2         | 2.08%   |
| 0x306d4    | 2         | 2.08%   |
| 0x306a9    | 2         | 2.08%   |
| 0x08600104 | 2         | 2.08%   |
| 0x906e9    | 1         | 1.04%   |
| 0x806d1    | 1         | 1.04%   |
| 0x706a1    | 1         | 1.04%   |
| 0x506e3    | 1         | 1.04%   |
| 0x106c2    | 1         | 1.04%   |
| 0x0a704103 | 1         | 1.04%   |
| 0x0a601203 | 1         | 1.04%   |
| 0x0a50000b | 1         | 1.04%   |
| 0x0a404101 | 1         | 1.04%   |
| 0x08108109 | 1         | 1.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 22        | 23.91%  |
| Zen 3            | 12        | 13.04%  |
| Skylake          | 9         | 9.78%   |
| Haswell          | 9         | 9.78%   |
| Unknown          | 9         | 9.78%   |
| Zen 2            | 7         | 7.61%   |
| TigerLake        | 7         | 7.61%   |
| Alderlake Hybrid | 5         | 5.43%   |
| IvyBridge        | 3         | 3.26%   |
| Goldmont plus    | 3         | 3.26%   |
| Icelake          | 2         | 2.17%   |
| Broadwell        | 2         | 2.17%   |
| Zen+             | 1         | 1.09%   |
| Bonnell          | 1         | 1.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 49.21%  |
| Nvidia | 34        | 26.98%  |
| AMD    | 30        | 23.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 10        | 7.75%   |
| AMD Renoir                                                                            | 7         | 5.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 4.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 6         | 4.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 3.88%   |
| Intel UHD Graphics 620                                                                | 5         | 3.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 3.88%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 5         | 3.88%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 3.1%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 3.1%    |
| AMD Rembrandt [Radeon 680M]                                                           | 4         | 3.1%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 2.33%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 2.33%   |
| Intel HD Graphics 530                                                                 | 3         | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 2.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 2.33%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 2.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 1.55%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 1.55%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.55%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 1.55%   |
| Intel HD Graphics 620                                                                 | 2         | 1.55%   |
| Intel HD Graphics 5500                                                                | 2         | 1.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 1.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 1.55%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 2         | 1.55%   |
| AMD Barcelo                                                                           | 2         | 1.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                | 1         | 0.78%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                                      | 1         | 0.78%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 0.78%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.78%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 0.78%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 0.78%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 0.78%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 0.78%   |
| Nvidia GK106M [GeForce GTX 765M]                                                      | 1         | 0.78%   |
| Nvidia GK106GLM [Quadro K2100M]                                                       | 1         | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 38.04%  |
| Intel + Nvidia | 22        | 23.91%  |
| 1 x AMD        | 16        | 17.39%  |
| AMD + Nvidia   | 8         | 8.7%    |
| 1 x Nvidia     | 4         | 4.35%   |
| Intel + AMD    | 4         | 4.35%   |
| 2 x AMD        | 2         | 2.17%   |
| 2 x Intel      | 1         | 1.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 71        | 76.34%  |
| Proprietary | 20        | 21.51%  |
| Unknown     | 2         | 2.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 57.89%  |
| 0.01-0.5   | 16        | 16.84%  |
| 1.01-2.0   | 11        | 11.58%  |
| 3.01-4.0   | 7         | 7.37%   |
| 0.51-1.0   | 4         | 4.21%   |
| 7.01-8.0   | 1         | 1.05%   |
| 8.01-16.0  | 1         | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 19        | 17.12%  |
| BOE                  | 15        | 13.51%  |
| Samsung Electronics  | 11        | 9.91%   |
| LG Display           | 11        | 9.91%   |
| Dell                 | 8         | 7.21%   |
| Chimei Innolux       | 8         | 7.21%   |
| Sharp                | 5         | 4.5%    |
| PANDA                | 5         | 4.5%    |
| CSO                  | 5         | 4.5%    |
| Apple                | 4         | 3.6%    |
| Panasonic            | 2         | 1.8%    |
| InfoVision           | 2         | 1.8%    |
| Hewlett-Packard      | 2         | 1.8%    |
| HannStar             | 2         | 1.8%    |
| Goldstar             | 2         | 1.8%    |
| Toshiba              | 1         | 0.9%    |
| TMX                  | 1         | 0.9%    |
| Philips              | 1         | 0.9%    |
| Lenovo               | 1         | 0.9%    |
| JDI                  | 1         | 0.9%    |
| Eizo                 | 1         | 0.9%    |
| ASUSTek Computer     | 1         | 0.9%    |
| AOC                  | 1         | 0.9%    |
| Ancor Communications | 1         | 0.9%    |
| Acer                 | 1         | 0.9%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 1.8%    |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 2         | 1.8%    |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 2         | 1.8%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 1.8%    |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.9%    |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch               | 1         | 0.9%    |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.9%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.9%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.9%    |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.9%    |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.9%    |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch     | 1         | 0.9%    |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 1         | 0.9%    |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 0.9%    |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch     | 1         | 0.9%    |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1         | 0.9%    |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.9%    |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch               | 1         | 0.9%    |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 0.9%    |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.9%    |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 1         | 0.9%    |
| LG Display LCD Monitor LGD06CE 1920x1200 288x180mm 13.4-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.9%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.9%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 41        | 38.68%  |
| 3840x2160 (4K)     | 14        | 13.21%  |
| 1366x768 (WXGA)    | 11        | 10.38%  |
| 2880x1800          | 9         | 8.49%   |
| 2560x1440 (QHD)    | 9         | 8.49%   |
| 2560x1600          | 6         | 5.66%   |
| 1920x1200 (WUXGA)  | 4         | 3.77%   |
| 3440x1440          | 2         | 1.89%   |
| 2256x1504          | 2         | 1.89%   |
| 1600x900 (HD+)     | 2         | 1.89%   |
| 1280x1024 (SXGA)   | 2         | 1.89%   |
| 3840x2400          | 1         | 0.94%   |
| 1920x1280          | 1         | 0.94%   |
| 1680x1050 (WSXGA+) | 1         | 0.94%   |
| 1024x600           | 1         | 0.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 30        | 27.27%  |
| 14     | 23        | 20.91%  |
| 13     | 14        | 12.73%  |
| 27     | 7         | 6.36%   |
| 12     | 7         | 6.36%   |
| 17     | 6         | 5.45%   |
| 16     | 6         | 5.45%   |
| 24     | 5         | 4.55%   |
| 23     | 3         | 2.73%   |
| 34     | 2         | 1.82%   |
| 31     | 2         | 1.82%   |
| 46     | 1         | 0.91%   |
| 26     | 1         | 0.91%   |
| 22     | 1         | 0.91%   |
| 21     | 1         | 0.91%   |
| 10     | 1         | 0.91%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 62        | 56.88%  |
| 201-300     | 18        | 16.51%  |
| 501-600     | 15        | 13.76%  |
| 351-400     | 6         | 5.5%    |
| 601-700     | 3         | 2.75%   |
| 701-800     | 2         | 1.83%   |
| 401-500     | 2         | 1.83%   |
| 1001-1500   | 1         | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 67        | 70.53%  |
| 16/10 | 21        | 22.11%  |
| 3/2   | 3         | 3.16%   |
| 21/9  | 2         | 2.11%   |
| 5/4   | 1         | 1.05%   |
| 4/3   | 1         | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 30        | 27.27%  |
| 101-110        | 30        | 27.27%  |
| 201-250        | 9         | 8.18%   |
| 301-350        | 8         | 7.27%   |
| 71-80          | 7         | 6.36%   |
| 61-70          | 7         | 6.36%   |
| 121-130        | 6         | 5.45%   |
| 111-120        | 5         | 4.55%   |
| 351-500        | 4         | 3.64%   |
| 41-50          | 1         | 0.91%   |
| 251-300        | 1         | 0.91%   |
| 141-150        | 1         | 0.91%   |
| 501-1000       | 1         | 0.91%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 39        | 37.86%  |
| 161-240       | 26        | 25.24%  |
| More than 240 | 13        | 12.62%  |
| 101-120       | 13        | 12.62%  |
| 51-100        | 11        | 10.68%  |
| 1-50          | 1         | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 69        | 71.13%  |
| 2     | 21        | 21.65%  |
| 0     | 5         | 5.15%   |
| 3     | 2         | 2.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 67        | 48.2%   |
| Realtek Semiconductor             | 42        | 30.22%  |
| MediaTek                          | 8         | 5.76%   |
| Qualcomm Atheros                  | 7         | 5.04%   |
| Broadcom                          | 5         | 3.6%    |
| Qualcomm                          | 2         | 1.44%   |
| Lenovo                            | 2         | 1.44%   |
| Xiaomi                            | 1         | 0.72%   |
| QinHeng Electronics               | 1         | 0.72%   |
| Microsoft                         | 1         | 0.72%   |
| Fibocom                           | 1         | 0.72%   |
| Ericsson Business Mobile Networks | 1         | 0.72%   |
| D-Link                            | 1         | 0.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 14.79%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 8.88%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 8.28%   |
| Intel Wireless 8260                                               | 6         | 3.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 3.55%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.37%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 2.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 2.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 2.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.78%   |
| Intel Wireless-AC 9260                                            | 3         | 1.78%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.78%   |
| Intel Wireless 7265                                               | 3         | 1.78%   |
| Intel Wireless 7260                                               | 3         | 1.78%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.18%   |
| Intel Wireless 3165                                               | 2         | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.18%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.18%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.18%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 1.18%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.59%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.59%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 0.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 67        | 70.53%  |
| MediaTek                          | 8         | 8.42%   |
| Qualcomm Atheros                  | 6         | 6.32%   |
| Broadcom                          | 5         | 5.26%   |
| Realtek Semiconductor             | 3         | 3.16%   |
| Qualcomm                          | 2         | 2.11%   |
| Microsoft                         | 1         | 1.05%   |
| Fibocom                           | 1         | 1.05%   |
| Ericsson Business Mobile Networks | 1         | 1.05%   |
| D-Link                            | 1         | 1.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 14        | 14.74%  |
| Intel Wireless 8260                                            | 6         | 6.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 6.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4.21%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 4.21%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 4.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 4.21%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 4.21%   |
| Intel Wireless-AC 9260                                         | 3         | 3.16%   |
| Intel Wireless 8265 / 8275                                     | 3         | 3.16%   |
| Intel Wireless 7265                                            | 3         | 3.16%   |
| Intel Wireless 7260                                            | 3         | 3.16%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.11%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.11%   |
| Intel Wireless 3165                                            | 2         | 2.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.11%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 2.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 2.11%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.05%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.05%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.05%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 1.05%   |
| Intel Wireless 3160                                            | 1         | 1.05%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 1         | 1.05%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 1.05%   |
| Ericsson Business Mobile Networks N5321 gw                     | 1         | 1.05%   |
| D-Link 802.11ac NIC                                            | 1         | 1.05%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 40        | 59.7%   |
| Intel                 | 21        | 31.34%  |
| Qualcomm Atheros      | 2         | 2.99%   |
| Lenovo                | 2         | 2.99%   |
| Xiaomi                | 1         | 1.49%   |
| Broadcom              | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 34.25%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 20.55%  |
| Intel Ethernet Connection I219-LM                                 | 5         | 6.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.74%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.74%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.74%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.37%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.37%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.37%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.37%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.37%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.37%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.37%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 57.96%  |
| Ethernet | 65        | 41.4%   |
| Modem    | 1         | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 84.62%  |
| Ethernet | 16        | 15.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 51        | 55.43%  |
| 1     | 39        | 42.39%  |
| 3     | 2         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 72        | 77.42%  |
| Yes  | 21        | 22.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 70.93%  |
| MediaTek                        | 4         | 4.65%   |
| IMC Networks                    | 4         | 4.65%   |
| Apple                           | 4         | 4.65%   |
| Qualcomm Atheros Communications | 3         | 3.49%   |
| Realtek Semiconductor           | 2         | 2.33%   |
| Foxconn / Hon Hai               | 2         | 2.33%   |
| Broadcom                        | 2         | 2.33%   |
| USI                             | 1         | 1.16%   |
| Realtek                         | 1         | 1.16%   |
| Lite-On Technology              | 1         | 1.16%   |
| ASUSTek Computer                | 1         | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 15        | 17.44%  |
| Intel AX200 Bluetooth                          | 14        | 16.28%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 9         | 10.47%  |
| Intel AX201 Bluetooth                          | 7         | 8.14%   |
| Intel AX210 Bluetooth                          | 6         | 6.98%   |
| Intel Bluetooth Device                         | 5         | 5.81%   |
| MediaTek Wireless_Device                       | 4         | 4.65%   |
| Apple Bluetooth Host Controller                | 4         | 4.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 3         | 3.49%   |
| Realtek Bluetooth Radio                        | 2         | 2.33%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 2.33%   |
| IMC Networks Wireless_Device                   | 2         | 2.33%   |
| USI Bluetooth Device                           | 1         | 1.16%   |
| Realtek 802.11ac WLAN Adapter                  | 1         | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.16%   |
| IMC Networks Bluetooth Device                  | 1         | 1.16%   |
| IMC Networks BCM20702A0                        | 1         | 1.16%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 1.16%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 1         | 1.16%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 1.16%   |
| ASUS Broadcom Bluetooth 2.1                    | 1         | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 67        | 50%     |
| AMD                       | 28        | 20.9%   |
| Nvidia                    | 18        | 13.43%  |
| Lenovo                    | 4         | 2.99%   |
| C-Media Electronics       | 3         | 2.24%   |
| Synaptics                 | 2         | 1.49%   |
| Realtek Semiconductor     | 2         | 1.49%   |
| Trust                     | 1         | 0.75%   |
| Sennheiser Communications | 1         | 0.75%   |
| Satechi                   | 1         | 0.75%   |
| Logitech                  | 1         | 0.75%   |
| Kingston Technology       | 1         | 0.75%   |
| JMTek                     | 1         | 0.75%   |
| Focusrite-Novation        | 1         | 0.75%   |
| Creative Technology       | 1         | 0.75%   |
| Corsair                   | 1         | 0.75%   |
| (LCS) USB Audio Device    | 1         | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 26        | 15.57%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 17        | 10.18%  |
| Intel Sunrise Point-LP HD Audio                                         | 14        | 8.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 7         | 4.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 7         | 4.19%   |
| Intel Cannon Lake PCH cAVS                                              | 6         | 3.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 5         | 2.99%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 5         | 2.99%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 5         | 2.99%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 2.4%    |
| Nvidia GA106 High Definition Audio Controller                           | 3         | 1.8%    |
| Nvidia Audio device                                                     | 3         | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 3         | 1.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 3         | 1.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 3         | 1.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 3         | 1.8%    |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 1.2%    |
| Realtek Semiconductor USB Audio                                         | 2         | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                         | 2         | 1.2%    |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 1.2%    |
| Nvidia GK106 HDMI Audio Controller                                      | 2         | 1.2%    |
| Nvidia GA104 High Definition Audio Controller                           | 2         | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 1.2%    |
| Intel Haswell-ULT HD Audio Controller                                   | 2         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                            | 2         | 1.2%    |
| Intel Broadwell-U Audio Controller                                      | 2         | 1.2%    |
| Intel 8 Series HD Audio Controller                                      | 2         | 1.2%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 1.2%    |
| Trust USB microphone                                                    | 1         | 0.6%    |
| Sennheiser Communications Headset [PC 8]                                | 1         | 0.6%    |
| Satechi Audio & PD Adapter                                              | 1         | 0.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 1         | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.6%    |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 1         | 0.6%    |
| Logitech Blue Microphones                                               | 1         | 0.6%    |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                               | 1         | 0.6%    |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                            | 1         | 0.6%    |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                            | 1         | 0.6%    |
| Lenovo ThinkPad Dock USB Audio                                          | 1         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 33        | 30%     |
| Micron Technology            | 20        | 18.18%  |
| SK hynix                     | 18        | 16.36%  |
| Crucial                      | 9         | 8.18%   |
| Kingston                     | 7         | 6.36%   |
| Unknown                      | 4         | 3.64%   |
| Unknown (ABCD)               | 3         | 2.73%   |
| Team                         | 3         | 2.73%   |
| Ramaxel Technology           | 2         | 1.82%   |
| A-DATA Technology            | 2         | 1.82%   |
| Patriot Memory (PDP Systems) | 1         | 0.91%   |
| Patriot                      | 1         | 0.91%   |
| GOODRAM                      | 1         | 0.91%   |
| G.Skill                      | 1         | 0.91%   |
| Corsair                      | 1         | 0.91%   |
| Avant                        | 1         | 0.91%   |
| Apacer                       | 1         | 0.91%   |
| AMD                          | 1         | 0.91%   |
| Unknown                      | 1         | 0.91%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 2.54%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 2.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.54%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 2         | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.69%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.69%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.69%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.69%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.69%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 2         | 1.69%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.69%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.85%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.85%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.85%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.85%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.85%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.85%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.85%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.85%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 0.85%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.85%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 0.85%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 1         | 0.85%   |
| SK hynix RAM H9JCNNNBK3MLYR-N6E 1GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.85%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.85%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.85%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.85%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.85%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.85%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 0.85%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 48        | 52.75%  |
| DDR3   | 15        | 16.48%  |
| LPDDR4 | 12        | 13.19%  |
| LPDDR5 | 8         | 8.79%   |
| LPDDR3 | 4         | 4.4%    |
| DDR5   | 3         | 3.3%    |
| SDRAM  | 1         | 1.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 76.84%  |
| Row Of Chips | 19        | 20%     |
| Chip         | 2         | 2.11%   |
| Unknown      | 1         | 1.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 44        | 43.14%  |
| 16384 | 22        | 21.57%  |
| 4096  | 19        | 18.63%  |
| 32768 | 12        | 11.76%  |
| 2048  | 4         | 3.92%   |
| 1024  | 1         | 0.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 22        | 23.16%  |
| 2667    | 20        | 21.05%  |
| 1600    | 14        | 14.74%  |
| 6400    | 8         | 8.42%   |
| 2133    | 8         | 8.42%   |
| 4267    | 6         | 6.32%   |
| 2400    | 6         | 6.32%   |
| 4266    | 3         | 3.16%   |
| 5600    | 2         | 2.11%   |
| 3266    | 2         | 2.11%   |
| 1867    | 2         | 2.11%   |
| 4800    | 1         | 1.05%   |
| Unknown | 1         | 1.05%   |

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
| Chicony Electronics           | 20        | 24.69%  |
| IMC Networks                  | 14        | 17.28%  |
| Microdia                      | 12        | 14.81%  |
| Acer                          | 8         | 9.88%   |
| Realtek Semiconductor         | 7         | 8.64%   |
| Sunplus Innovation Technology | 4         | 4.94%   |
| Logitech                      | 3         | 3.7%    |
| Lite-On Technology            | 3         | 3.7%    |
| Syntek                        | 2         | 2.47%   |
| Quanta                        | 2         | 2.47%   |
| Sonix Technology              | 1         | 1.23%   |
| Primax Electronics            | 1         | 1.23%   |
| Luxvisions Innotech Limited   | 1         | 1.23%   |
| Bison Electronics             | 1         | 1.23%   |
| Alcor Micro                   | 1         | 1.23%   |
| 2M UVC CAMERA                 | 1         | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 13        | 15.48%  |
| Microdia Integrated_Webcam_HD                     | 6         | 7.14%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 6         | 7.14%   |
| IMC Networks Integrated Camera                    | 5         | 5.95%   |
| Chicony HP HD Camera                              | 4         | 4.76%   |
| Acer Integrated Camera                            | 3         | 3.57%   |
| Syntek Integrated Camera                          | 2         | 2.38%   |
| Sunplus Integrated_Webcam_FHD                     | 2         | 2.38%   |
| Realtek Laptop Camera                             | 2         | 2.38%   |
| Realtek Integrated_Webcam_HD                      | 2         | 2.38%   |
| Microdia Webcam Vitade AF                         | 2         | 2.38%   |
| Logitech HD Pro Webcam C920                       | 2         | 2.38%   |
| Lite-On Integrated Camera                         | 2         | 2.38%   |
| Acer HD Webcam                                    | 2         | 2.38%   |
| Sunplus Laptop Integrated Webcam FHD              | 1         | 1.19%   |
| Sunplus Integrated_Webcam_HD                      | 1         | 1.19%   |
| Sonix USB2.0 FHD UVC WebCam                       | 1         | 1.19%   |
| Realtek TV Camera                                 | 1         | 1.19%   |
| Realtek Realtek USB MIC                           | 1         | 1.19%   |
| Realtek Lenovo EasyCamera                         | 1         | 1.19%   |
| Realtek Integrated Webcam                         | 1         | 1.19%   |
| Quanta VGA WebCam                                 | 1         | 1.19%   |
| Quanta HD WebCam                                  | 1         | 1.19%   |
| Primax HP HD Webcam [Fixed]                       | 1         | 1.19%   |
| Microdia USB 2.0 Camera                           | 1         | 1.19%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 1.19%   |
| Microdia Integrated Webcam                        | 1         | 1.19%   |
| Microdia HP Integrated Webcam                     | 1         | 1.19%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1.19%   |
| Logitech Webcam C310                              | 1         | 1.19%   |
| Lite-On HP HD Camera                              | 1         | 1.19%   |
| IMC Networks XHC Camera                           | 1         | 1.19%   |
| IMC Networks USB2.0 UVC 1.3M WebCam               | 1         | 1.19%   |
| IMC Networks ov9734_azurewave_camera              | 1         | 1.19%   |
| Chicony USB2.0 Camera                             | 1         | 1.19%   |
| Chicony Integrated IR Camera                      | 1         | 1.19%   |
| Chicony Integrated Camera [ThinkPad]              | 1         | 1.19%   |
| Bison SunplusIT Integrated Camera                 | 1         | 1.19%   |
| Bison Integrated IR Camera                        | 1         | 1.19%   |
| Alcor Micro USB 2.0 Camera                        | 1         | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 40.91%  |
| Validity Sensors           | 8         | 36.36%  |
| Shenzhen Goodix Technology | 4         | 18.18%  |
| Focal-systems.Corp         | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 5         | 22.73%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 13.64%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 9.09%   |
| Synaptics UWP WBDI Device                                | 2         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                      | 2         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 4.55%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 4.55%   |
| Validity Sensors VFS491                                  | 1         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 4.55%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.55%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 10        | 58.82%  |
| Yubico.com  | 3         | 17.65%  |
| Broadcom    | 3         | 17.65%  |
| Upek        | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 10        | 58.82%  |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 2         | 11.76%  |
| Broadcom 5880                                              | 2         | 11.76%  |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 5.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 41        | 43.16%  |
| 1     | 33        | 34.74%  |
| 2     | 18        | 18.95%  |
| 4     | 2         | 2.11%   |
| 3     | 1         | 1.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 20        | 25.97%  |
| Multimedia controller    | 16        | 20.78%  |
| Graphics card            | 13        | 16.88%  |
| Chipcard                 | 12        | 15.58%  |
| Net/wireless             | 3         | 3.9%    |
| Camera                   | 3         | 3.9%    |
| Bluetooth                | 3         | 3.9%    |
| Modem                    | 2         | 2.6%    |
| Card reader              | 2         | 2.6%    |
| Network                  | 1         | 1.3%    |
| Firewire controller      | 1         | 1.3%    |
| Communication controller | 1         | 1.3%    |

