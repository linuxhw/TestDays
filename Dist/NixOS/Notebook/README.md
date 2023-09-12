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

Total: 137

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Precision 5680              | [fdcb7ce5d4](https://linux-hardware.org/?probe=fdcb7ce5d4) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 20HES2RC00    | [390104a086](https://linux-hardware.org/?probe=390104a086) | Aug 28, 2023 |
| Dell          | Wyse 5470                   | [6d45205020](https://linux-hardware.org/?probe=6d45205020) | Aug 27, 2023 |
| Lenovo        | G50-70 20351                | [aed7eacff0](https://linux-hardware.org/?probe=aed7eacff0) | Aug 20, 2023 |
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
| NixOS 23.05                      | 28        | 25.93%  |
| NixOS 22.11                      | 27        | 25%     |
| NixOS 22.05                      | 18        | 16.67%  |
| NixOS 23.11                      | 12        | 11.11%  |
| NixOS 21.11                      | 9         | 8.33%   |
| NixOS                            | 2         | 1.85%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.93%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.93%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.93%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.93%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.93%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.93%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.93%   |
| NixOS 20.09pre-git               | 1         | 0.93%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.93%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.93%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.93%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 95        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Notebooks | Percent |
|------------------|-----------|---------|
| 6.3.8            | 4         | 3.51%   |
| 6.3.3            | 3         | 2.63%   |
| 6.1.38           | 3         | 2.63%   |
| 5.15.74          | 3         | 2.63%   |
| 5.15.43          | 3         | 2.63%   |
| 6.4.0            | 2         | 1.75%   |
| 6.3.1            | 2         | 1.75%   |
| 6.1.41           | 2         | 1.75%   |
| 6.1.35           | 2         | 1.75%   |
| 6.1.34           | 2         | 1.75%   |
| 6.1.0            | 2         | 1.75%   |
| 6.0.10           | 2         | 1.75%   |
| 5.16.15          | 2         | 1.75%   |
| 5.15.72          | 2         | 1.75%   |
| 5.15.68          | 2         | 1.75%   |
| 5.15.64          | 2         | 1.75%   |
| 5.15.26          | 2         | 1.75%   |
| 5.13.7           | 2         | 1.75%   |
| 6.4.8            | 1         | 0.88%   |
| 6.4.6            | 1         | 0.88%   |
| 6.4.2            | 1         | 0.88%   |
| 6.4.14           | 1         | 0.88%   |
| 6.3.9            | 1         | 0.88%   |
| 6.3.5            | 1         | 0.88%   |
| 6.2.9-lqx1       | 1         | 0.88%   |
| 6.2.9            | 1         | 0.88%   |
| 6.2.8            | 1         | 0.88%   |
| 6.2.7            | 1         | 0.88%   |
| 6.2.14           | 1         | 0.88%   |
| 6.2.0            | 1         | 0.88%   |
| 6.1.7-xanmod1    | 1         | 0.88%   |
| 6.1.47           | 1         | 0.88%   |
| 6.1.45           | 1         | 0.88%   |
| 6.1.43           | 1         | 0.88%   |
| 6.1.42           | 1         | 0.88%   |
| 6.1.39           | 1         | 0.88%   |
| 6.1.27           | 1         | 0.88%   |
| 6.1.25           | 1         | 0.88%   |
| 6.1.24           | 1         | 0.88%   |
| 6.1.22-hardened1 | 1         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.8   | 4         | 3.51%   |
| 6.3.3   | 3         | 2.63%   |
| 6.1.38  | 3         | 2.63%   |
| 6.0.10  | 3         | 2.63%   |
| 5.15.74 | 3         | 2.63%   |
| 5.15.43 | 3         | 2.63%   |
| 6.4.0   | 2         | 1.75%   |
| 6.3.1   | 2         | 1.75%   |
| 6.2.9   | 2         | 1.75%   |
| 6.1.41  | 2         | 1.75%   |
| 6.1.35  | 2         | 1.75%   |
| 6.1.34  | 2         | 1.75%   |
| 6.1.0   | 2         | 1.75%   |
| 5.16.15 | 2         | 1.75%   |
| 5.15.72 | 2         | 1.75%   |
| 5.15.68 | 2         | 1.75%   |
| 5.15.64 | 2         | 1.75%   |
| 5.15.26 | 2         | 1.75%   |
| 5.13.7  | 2         | 1.75%   |
| 6.4.8   | 1         | 0.88%   |
| 6.4.6   | 1         | 0.88%   |
| 6.4.2   | 1         | 0.88%   |
| 6.4.14  | 1         | 0.88%   |
| 6.3.9   | 1         | 0.88%   |
| 6.3.5   | 1         | 0.88%   |
| 6.2.8   | 1         | 0.88%   |
| 6.2.7   | 1         | 0.88%   |
| 6.2.14  | 1         | 0.88%   |
| 6.2.0   | 1         | 0.88%   |
| 6.1.7   | 1         | 0.88%   |
| 6.1.47  | 1         | 0.88%   |
| 6.1.45  | 1         | 0.88%   |
| 6.1.43  | 1         | 0.88%   |
| 6.1.42  | 1         | 0.88%   |
| 6.1.39  | 1         | 0.88%   |
| 6.1.27  | 1         | 0.88%   |
| 6.1.25  | 1         | 0.88%   |
| 6.1.24  | 1         | 0.88%   |
| 6.1.22  | 1         | 0.88%   |
| 6.1.21  | 1         | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 31        | 27.93%  |
| 6.1     | 22        | 19.82%  |
| 6.3     | 11        | 9.91%   |
| 6.4     | 6         | 5.41%   |
| 6.2     | 6         | 5.41%   |
| 6.0     | 6         | 5.41%   |
| 5.16    | 6         | 5.41%   |
| 5.8     | 3         | 2.7%    |
| 5.19    | 3         | 2.7%    |
| 5.13    | 3         | 2.7%    |
| 5.10    | 3         | 2.7%    |
| 5.7     | 2         | 1.8%    |
| 5.4     | 2         | 1.8%    |
| 5.18    | 2         | 1.8%    |
| 5.17    | 2         | 1.8%    |
| 4.19    | 2         | 1.8%    |
| 5.12    | 1         | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 94        | 98.95%  |
| i686   | 1         | 1.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 44        | 44%     |
| GNOME        | 15        | 15%     |
| sway         | 11        | 11%     |
| KDE5         | 9         | 9%      |
| Hyprland     | 7         | 7%      |
| none+i3      | 4         | 4%      |
| XFCE         | 3         | 3%      |
| none+xmonad  | 2         | 2%      |
| KDE          | 2         | 2%      |
| X-Cinnamon   | 1         | 1%      |
| none+bspwm   | 1         | 1%      |
| none+awesome | 1         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 48        | 47.52%  |
| Wayland | 33        | 32.67%  |
| X11     | 17        | 16.83%  |
| Tty     | 3         | 2.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 52        | 53.61%  |
| GDM     | 20        | 20.62%  |
| SDDM    | 13        | 13.4%   |
| LightDM | 12        | 12.37%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 49        | 50.52%  |
| Unknown | 32        | 32.99%  |
| en_GB   | 4         | 4.12%   |
| en_DK   | 2         | 2.06%   |
| en_CA   | 2         | 2.06%   |
| ru_RU   | 1         | 1.03%   |
| ro_RO   | 1         | 1.03%   |
| lv_LV   | 1         | 1.03%   |
| it_IT   | 1         | 1.03%   |
| fr_FR   | 1         | 1.03%   |
| es_MX   | 1         | 1.03%   |
| en_IN   | 1         | 1.03%   |
| de_DE   | 1         | 1.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 86        | 90.53%  |
| BIOS | 9         | 9.47%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 52        | 52.53%  |
| Btrfs   | 17        | 17.17%  |
| Tmpfs   | 11        | 11.11%  |
| Zfs     | 8         | 8.08%   |
| Xfs     | 8         | 8.08%   |
| Unknown | 3         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 90        | 92.78%  |
| Unknown | 5         | 5.15%   |
| MBR     | 2         | 2.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 80.41%  |
| Yes       | 19        | 19.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 73.68%  |
| Yes       | 25        | 26.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 36        | 37.89%  |
| Dell                   | 17        | 17.89%  |
| ASUSTek Computer       | 11        | 11.58%  |
| Hewlett-Packard        | 6         | 6.32%   |
| Apple                  | 4         | 4.21%   |
| GPD                    | 3         | 3.16%   |
| MSI                    | 2         | 2.11%   |
| MECHREVO               | 2         | 2.11%   |
| Framework              | 2         | 2.11%   |
| Acer                   | 2         | 2.11%   |
| Toshiba                | 1         | 1.05%   |
| System76               | 1         | 1.05%   |
| OBSIDIAN-PC            | 1         | 1.05%   |
| Microtech              | 1         | 1.05%   |
| MACHENIKE              | 1         | 1.05%   |
| HUAWEI                 | 1         | 1.05%   |
| Gigabyte Technology    | 1         | 1.05%   |
| Blackview              | 1         | 1.05%   |
| Avell High Performance | 1         | 1.05%   |
| Alienware              | 1         | 1.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Latitude 7420                          | 2         | 2.11%   |
| Apple MacBookPro11,5                        | 2         | 2.11%   |
| Apple MacBookPro11,3                        | 2         | 2.11%   |
| Toshiba Satellite L50-B                     | 1         | 1.05%   |
| System76 Pangolin                           | 1         | 1.05%   |
| OBSIDIAN-PC N13_N140ZU                      | 1         | 1.05%   |
| MSI Bravo 15 B5DD                           | 1         | 1.05%   |
| MSI Alpha 15 B5EEK                          | 1         | 1.05%   |
| Microtech CoreBook Lite                     | 1         | 1.05%   |
| MECHREVO WUJIE 14                           | 1         | 1.05%   |
| MECHREVO Code01 Ver2.0                      | 1         | 1.05%   |
| MACHENIKE F117-7P                           | 1         | 1.05%   |
| Lenovo Yoga Slim 7 13ACN5 82CY              | 1         | 1.05%   |
| Lenovo Yoga 14sARE 2020 82A8                | 1         | 1.05%   |
| Lenovo ThinkPad X390 20Q0CTO1WW             | 1         | 1.05%   |
| Lenovo ThinkPad X260 20F5S6MF02             | 1         | 1.05%   |
| Lenovo ThinkPad X260 20F5S4BY00             | 1         | 1.05%   |
| Lenovo ThinkPad X250 20CLS18S0T             | 1         | 1.05%   |
| Lenovo ThinkPad X230 2333AZ2                | 1         | 1.05%   |
| Lenovo ThinkPad X230 23243E9                | 1         | 1.05%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW       | 1         | 1.05%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB007AUK | 1         | 1.05%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBCT01WW    | 1         | 1.05%   |
| Lenovo ThinkPad T580 20L90024PB             | 1         | 1.05%   |
| Lenovo ThinkPad T540p 20BE005YMH            | 1         | 1.05%   |
| Lenovo ThinkPad T490 20N2000LUK             | 1         | 1.05%   |
| Lenovo ThinkPad T480 20L5CTO1WW             | 1         | 1.05%   |
| Lenovo ThinkPad T470 20HES2RC00             | 1         | 1.05%   |
| Lenovo ThinkPad T460p 20FWCTO1WW            | 1         | 1.05%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW        | 1         | 1.05%   |
| Lenovo ThinkPad T14s Gen 3 21BR000MUS       | 1         | 1.05%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK       | 1         | 1.05%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT        | 1         | 1.05%   |
| Lenovo ThinkPad P50 20EN0005GE              | 1         | 1.05%   |
| Lenovo ThinkPad P14s Gen 3 21J5002KMH       | 1         | 1.05%   |
| Lenovo ThinkPad P14s Gen 1 20Y1S00C00       | 1         | 1.05%   |
| Lenovo ThinkPad E470 20H1006JIX             | 1         | 1.05%   |
| Lenovo ThinkPad E14 Gen 4 21EBCTO1WW        | 1         | 1.05%   |
| Lenovo ThinkBook 16 G4+ ARA 21D1            | 1         | 1.05%   |
| Lenovo Legion Y7000 2019 PG0 81T0           | 1         | 1.05%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 24        | 25.26%  |
| Dell XPS                   | 6         | 6.32%   |
| Lenovo Legion              | 5         | 5.26%   |
| Dell Latitude              | 5         | 5.26%   |
| ASUS ROG                   | 4         | 4.21%   |
| Apple MacBookPro11         | 4         | 4.21%   |
| Lenovo IdeaPad             | 3         | 3.16%   |
| HP EliteBook               | 3         | 3.16%   |
| Dell Precision             | 3         | 3.16%   |
| ASUS Zenbook               | 3         | 3.16%   |
| Lenovo Yoga                | 2         | 2.11%   |
| HP ProBook                 | 2         | 2.11%   |
| Framework Laptop           | 2         | 2.11%   |
| Dell Inspiron              | 2         | 2.11%   |
| Acer Aspire                | 2         | 2.11%   |
| Toshiba Satellite          | 1         | 1.05%   |
| System76 Pangolin          | 1         | 1.05%   |
| OBSIDIAN-PC N13            | 1         | 1.05%   |
| MSI Bravo                  | 1         | 1.05%   |
| MSI Alpha                  | 1         | 1.05%   |
| Microtech CoreBook         | 1         | 1.05%   |
| MECHREVO WUJIE             | 1         | 1.05%   |
| MECHREVO Code01            | 1         | 1.05%   |
| MACHENIKE F117-7P          | 1         | 1.05%   |
| Lenovo ThinkBook           | 1         | 1.05%   |
| Lenovo G50-70              | 1         | 1.05%   |
| HUAWEI NBLK-WAX9X          | 1         | 1.05%   |
| HP ZBook                   | 1         | 1.05%   |
| GPD WIN2                   | 1         | 1.05%   |
| GPD MicroPC                | 1         | 1.05%   |
| GPD G1621-02               | 1         | 1.05%   |
| Gigabyte Sabre             | 1         | 1.05%   |
| Dell Wyse                  | 1         | 1.05%   |
| Blackview AceBook          | 1         | 1.05%   |
| Avell High Performance A70 | 1         | 1.05%   |
| ASUS VivoBook              | 1         | 1.05%   |
| ASUS ProArt                | 1         | 1.05%   |
| ASUS ASUSPRO               | 1         | 1.05%   |
| ASUS 1005HA                | 1         | 1.05%   |
| Alienware 17               | 1         | 1.05%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 18        | 18.95%  |
| 2020 | 13        | 13.68%  |
| 2022 | 12        | 12.63%  |
| 2019 | 10        | 10.53%  |
| 2016 | 9         | 9.47%   |
| 2018 | 7         | 7.37%   |
| 2013 | 6         | 6.32%   |
| 2023 | 5         | 5.26%   |
| 2017 | 4         | 4.21%   |
| 2015 | 4         | 4.21%   |
| 2014 | 3         | 3.16%   |
| 2012 | 2         | 2.11%   |
| 2011 | 1         | 1.05%   |
| 2009 | 1         | 1.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 95        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 94        | 97.92%  |
| Enabled  | 2         | 2.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 94        | 98.95%  |
| Yes  | 1         | 1.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 25        | 26.04%  |
| 16.01-24.0  | 24        | 25%     |
| 8.01-16.0   | 22        | 22.92%  |
| 4.01-8.0    | 13        | 13.54%  |
| 64.01-256.0 | 6         | 6.25%   |
| 3.01-4.0    | 3         | 3.13%   |
| 24.01-32.0  | 2         | 2.08%   |
| 0.51-1.0    | 1         | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 32        | 29.09%  |
| 3.01-4.0   | 22        | 20%     |
| 2.01-3.0   | 17        | 15.45%  |
| 8.01-16.0  | 16        | 14.55%  |
| 1.01-2.0   | 9         | 8.18%   |
| 24.01-32.0 | 5         | 4.55%   |
| 0.51-1.0   | 4         | 3.64%   |
| 32.01-64.0 | 2         | 1.82%   |
| 16.01-24.0 | 2         | 1.82%   |
| 0.01-0.5   | 1         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 70        | 72.92%  |
| 2      | 24        | 25%     |
| 3      | 2         | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 91.58%  |
| Yes       | 8         | 8.42%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 68.37%  |
| No        | 31        | 31.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 98.95%  |
| No        | 1         | 1.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 91.75%  |
| No        | 8         | 8.25%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 17        | 17.89%  |
| UK          | 7         | 7.37%   |
| Russia      | 7         | 7.37%   |
| France      | 7         | 7.37%   |
| Italy       | 5         | 5.26%   |
| Germany     | 5         | 5.26%   |
| Ukraine     | 4         | 4.21%   |
| Poland      | 4         | 4.21%   |
| Canada      | 4         | 4.21%   |
| Netherlands | 3         | 3.16%   |
| Switzerland | 2         | 2.11%   |
| Japan       | 2         | 2.11%   |
| Iraq        | 2         | 2.11%   |
| India       | 2         | 2.11%   |
| Belgium     | 2         | 2.11%   |
| Austria     | 2         | 2.11%   |
| Uruguay     | 1         | 1.05%   |
| Sweden      | 1         | 1.05%   |
| Spain       | 1         | 1.05%   |
| Slovenia    | 1         | 1.05%   |
| Singapore   | 1         | 1.05%   |
| Serbia      | 1         | 1.05%   |
| Romania     | 1         | 1.05%   |
| Portugal    | 1         | 1.05%   |
| Peru        | 1         | 1.05%   |
| Mexico      | 1         | 1.05%   |
| Latvia      | 1         | 1.05%   |
| Kuwait      | 1         | 1.05%   |
| Iran        | 1         | 1.05%   |
| Hungary     | 1         | 1.05%   |
| Hong Kong   | 1         | 1.05%   |
| Denmark     | 1         | 1.05%   |
| Czechia     | 1         | 1.05%   |
| Colombia    | 1         | 1.05%   |
| China       | 1         | 1.05%   |
| Brazil      | 1         | 1.05%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 3         | 2.94%   |
| Vienna             | 2         | 1.96%   |
| Phoenix            | 2         | 1.96%   |
| Ottawa             | 2         | 1.96%   |
| Marki              | 2         | 1.96%   |
| Kharkiv            | 2         | 1.96%   |
| Halifax            | 2         | 1.96%   |
| Catania            | 2         | 1.96%   |
| Baghdad            | 2         | 1.96%   |
| Zurich             | 1         | 0.98%   |
| Yangzhou           | 1         | 0.98%   |
| Woodford           | 1         | 0.98%   |
| Woldegk            | 1         | 0.98%   |
| Warsaw             | 1         | 0.98%   |
| Villeurbanne       | 1         | 0.98%   |
| Verneuil-sur-Seine | 1         | 0.98%   |
| Valpacos           | 1         | 0.98%   |
| Trento             | 1         | 0.98%   |
| Tremestieri Etneo  | 1         | 0.98%   |
| Tottenham          | 1         | 0.98%   |
| Tolyatti           | 1         | 0.98%   |
| Tehran             | 1         | 0.98%   |
| Szigetszentmiklos  | 1         | 0.98%   |
| Stockholm          | 1         | 0.98%   |
| Staten Island      | 1         | 0.98%   |
| St Petersburg      | 1         | 0.98%   |
| Southampton        | 1         | 0.98%   |
| South Deerfield    | 1         | 0.98%   |
| Smolensk           | 1         | 0.98%   |
| Singapore          | 1         | 0.98%   |
| Seattle            | 1         | 0.98%   |
| Saratov            | 1         | 0.98%   |
| Santee             | 1         | 0.98%   |
| Rochester          | 1         | 0.98%   |
| Riga               | 1         | 0.98%   |
| Rho                | 1         | 0.98%   |
| Puebla City        | 1         | 0.98%   |
| Prague             | 1         | 0.98%   |
| Plymouth           | 1         | 0.98%   |
| Pittsburgh         | 1         | 0.98%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 35        | 48     | 29.66%  |
| Sandisk                     | 12        | 12     | 10.17%  |
| WDC                         | 8         | 8      | 6.78%   |
| SK hynix                    | 8         | 11     | 6.78%   |
| Toshiba                     | 6         | 6      | 5.08%   |
| Micron Technology           | 6         | 7      | 5.08%   |
| Apple                       | 5         | 7      | 4.24%   |
| Unknown                     | 4         | 4      | 3.39%   |
| Kingston                    | 4         | 5      | 3.39%   |
| Intel                       | 4         | 5      | 3.39%   |
| Crucial                     | 3         | 4      | 2.54%   |
| Yangtze Memory Technologies | 2         | 2      | 1.69%   |
| Transcend                   | 2         | 2      | 1.69%   |
| Seagate                     | 2         | 3      | 1.69%   |
| KIOXIA                      | 2         | 3      | 1.69%   |
| Kingston Technology Company | 2         | 2      | 1.69%   |
| A-DATA Technology           | 2         | 2      | 1.69%   |
| SPCC                        | 1         | 1      | 0.85%   |
| Micron/Crucial Technology   | 1         | 1      | 0.85%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.85%   |
| INNOVATION IT               | 1         | 1      | 0.85%   |
| Hitachi                     | 1         | 2      | 0.85%   |
| HGST                        | 1         | 1      | 0.85%   |
| Dogfish                     | 1         | 1      | 0.85%   |
| China                       | 1         | 1      | 0.85%   |
| Biwin Storage Technology    | 1         | 1      | 0.85%   |
| BIWIN                       | 1         | 1      | 0.85%   |
| ADATA Technology            | 1         | 2      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 8         | 6.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 5         | 4%      |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                  | 2         | 1.6%    |
| SK hynix PC801 NVMe 512GB                             | 2         | 1.6%    |
| Samsung SSD 850 EVO 500GB                             | 2         | 1.6%    |
| Samsung PM9A1 NVMe 1024GB                             | 2         | 1.6%    |
| Kingston OM8PCP3512F-AI1 512GB                        | 2         | 1.6%    |
| Apple SSD SM0512G 500GB                               | 2         | 1.6%    |
| Yangtze Memory ZHITAI TiPlus7100 2TB                  | 1         | 0.8%    |
| Yangtze Memory YMTC PC300-1TB-B                       | 1         | 0.8%    |
| WDC WDS480G2G0B-00EPW0 480GB SSD                      | 1         | 0.8%    |
| WDC WDS200T1X0E-00AFY0 2TB                            | 1         | 0.8%    |
| WDC WD7500BPKX-75HPJT0 752GB                          | 1         | 0.8%    |
| WDC WD10 JPLX-00MBPT0 1TB                             | 1         | 0.8%    |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                    | 1         | 0.8%    |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                  | 1         | 0.8%    |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB                    | 1         | 0.8%    |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB                  | 1         | 0.8%    |
| Unknown MMC Card  64GB                                | 1         | 0.8%    |
| Unknown MMC Card  250GB                               | 1         | 0.8%    |
| Unknown MMC Card  16GB                                | 1         | 0.8%    |
| Unknown MMC Card  128GB                               | 1         | 0.8%    |
| Transcend TS256GMTS800 256GB SSD                      | 1         | 0.8%    |
| Transcend TS256GMTS430S 256GB SSD                     | 1         | 0.8%    |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 1         | 0.8%    |
| Toshiba MQ01ACF050 500GB                              | 1         | 0.8%    |
| Toshiba MQ01ABD100 1TB                                | 1         | 0.8%    |
| Toshiba MK2565GSXV 250GB                              | 1         | 0.8%    |
| Toshiba KXG6AZNV512G 512GB                            | 1         | 0.8%    |
| Toshiba KXG50ZNV512G NVMe 512GB                       | 1         | 0.8%    |
| SPCC 2.5 SSD 1TB                                      | 1         | 0.8%    |
| SK hynix SC311 SATA 256GB SSD                         | 1         | 0.8%    |
| SK hynix PC711 HFS512GDE9X073N 512GB                  | 1         | 0.8%    |
| SK hynix NVMe SSD Drive 1TB                           | 1         | 0.8%    |
| SK hynix NVMe SSD Drive 1024GB                        | 1         | 0.8%    |
| SK hynix HFM001TD3JX013N 1TB                          | 1         | 0.8%    |
| Seagate ST2000LM007-1R8174 2TB                        | 1         | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB                        | 1         | 0.8%    |
| SanDisk X600 M.2 2280 SATA 128GB SSD                  | 1         | 0.8%    |
| Sandisk WD_BLACK SN770 2TB                            | 1         | 0.8%    |

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
| Samsung Electronics | 12        | 15     | 35.29%  |
| SanDisk             | 4         | 4      | 11.76%  |
| Apple               | 4         | 6      | 11.76%  |
| Transcend           | 2         | 2      | 5.88%   |
| Micron Technology   | 2         | 2      | 5.88%   |
| Crucial             | 2         | 3      | 5.88%   |
| WDC                 | 1         | 1      | 2.94%   |
| SPCC                | 1         | 1      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| Kingston            | 1         | 1      | 2.94%   |
| INNOVATION IT       | 1         | 1      | 2.94%   |
| Dogfish             | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| BIWIN               | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 65        | 88     | 59.09%  |
| SSD  | 31        | 40     | 28.18%  |
| HDD  | 10        | 12     | 9.09%   |
| MMC  | 4         | 4      | 3.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 65        | 88     | 61.9%   |
| SATA | 33        | 49     | 31.43%  |
| MMC  | 4         | 4      | 3.81%   |
| SAS  | 3         | 3      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 34     | 61.9%   |
| 0.51-1.0   | 15        | 17     | 35.71%  |
| 1.01-2.0   | 1         | 1      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 33        | 33.33%  |
| 1-20           | 28        | 28.28%  |
| 251-500        | 10        | 10.1%   |
| 501-1000       | 8         | 8.08%   |
| 101-250        | 7         | 7.07%   |
| More than 3000 | 5         | 5.05%   |
| 1001-2000      | 5         | 5.05%   |
| 2001-3000      | 3         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 33        | 32.67%  |
| 1-20           | 30        | 29.7%   |
| 101-250        | 13        | 12.87%  |
| 51-100         | 7         | 6.93%   |
| 21-50          | 6         | 5.94%   |
| 501-1000       | 5         | 4.95%   |
| 251-500        | 4         | 3.96%   |
| More than 3000 | 1         | 0.99%   |
| 2001-3000      | 1         | 0.99%   |
| 1001-2000      | 1         | 0.99%   |

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
| Works    | 90        | 124    | 84.11%  |
| Detected | 11        | 14     | 10.28%  |
| Malfunc  | 5         | 5      | 4.67%   |
| Failed   | 1         | 1      | 0.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 46        | 37.4%   |
| Samsung Electronics          | 28        | 22.76%  |
| SanDisk                      | 13        | 10.57%  |
| SK hynix                     | 7         | 5.69%   |
| Kingston Technology Company  | 5         | 4.07%   |
| AMD                          | 5         | 4.07%   |
| Toshiba America Info Systems | 4         | 3.25%   |
| Micron Technology            | 4         | 3.25%   |
| ADATA Technology             | 3         | 2.44%   |
| Yangtze Memory Technologies  | 2         | 1.63%   |
| Micron/Crucial Technology    | 2         | 1.63%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.81%   |
| Marvell Technology Group     | 1         | 0.81%   |
| KIOXIA                       | 1         | 0.81%   |
| Biwin Storage Technology     | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 9.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 7.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 6.35%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 3.97%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 3.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 3.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 3.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.17%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 2.38%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 3         | 2.38%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 2.38%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 1.59%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.59%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.59%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 1.59%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.59%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.59%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 1.59%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 2         | 1.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.59%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.59%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.59%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 1.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.59%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 1         | 0.79%   |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 0.79%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.79%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 0.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.79%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.79%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.79%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.79%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.79%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1         | 0.79%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 65        | 55.56%  |
| SATA | 44        | 37.61%  |
| RAID | 8         | 6.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 72.63%  |
| AMD    | 26        | 27.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 4.21%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 4         | 4.21%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 4         | 4.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 3.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 3         | 3.16%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 3.16%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 3.16%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 3         | 3.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 2.11%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 2.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 2.11%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 2.11%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 2         | 2.11%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 2         | 2.11%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 2         | 2.11%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 2.11%   |
| Intel 12th Gen Core i7-1260P               | 2         | 2.11%   |
| Intel 12th Gen Core i5-1240P               | 2         | 2.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 2.11%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 2         | 2.11%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 2.11%   |
| Intel Xeon E-2276M CPU @ 2.80GHz           | 1         | 1.05%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 1.05%   |
| Intel Pentium Gold 7505 @ 2.00GHz          | 1         | 1.05%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 1.05%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 1.05%   |
| Intel Core i7-7600U CPU @ 2.80GHz          | 1         | 1.05%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 1.05%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 1.05%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 1.05%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz         | 1         | 1.05%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 1.05%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz         | 1         | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 1.05%   |
| Intel Core i5-9300H CPU @ 2.40GHz          | 1         | 1.05%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 1         | 1.05%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 1         | 1.05%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 1         | 1.05%   |
| Intel Core i3-10110U CPU @ 2.10GHz         | 1         | 1.05%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 28        | 29.47%  |
| Other              | 17        | 17.89%  |
| AMD Ryzen 7        | 14        | 14.74%  |
| Intel Core i5      | 13        | 13.68%  |
| AMD Ryzen 9        | 5         | 5.26%   |
| AMD Ryzen 7 PRO    | 5         | 5.26%   |
| Intel Celeron      | 4         | 4.21%   |
| Intel Xeon         | 2         | 2.11%   |
| AMD Ryzen 5        | 2         | 2.11%   |
| Intel Pentium Gold | 1         | 1.05%   |
| Intel Core m3      | 1         | 1.05%   |
| Intel Core i9      | 1         | 1.05%   |
| Intel Core i3      | 1         | 1.05%   |
| Intel Atom         | 1         | 1.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 33        | 34.74%  |
| 8      | 28        | 29.47%  |
| 2      | 20        | 21.05%  |
| 12     | 5         | 5.26%   |
| 6      | 5         | 5.26%   |
| 24     | 1         | 1.05%   |
| 16     | 1         | 1.05%   |
| 14     | 1         | 1.05%   |
| 1      | 1         | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 95        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 89        | 93.68%  |
| 1      | 6         | 6.32%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 94        | 97.92%  |
| 32-bit         | 1         | 1.04%   |
| Unknown        | 1         | 1.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 25.25%  |
| 0x0a50000c | 11        | 11.11%  |
| 0x806c1    | 5         | 5.05%   |
| 0x08600106 | 5         | 5.05%   |
| 0x806ea    | 4         | 4.04%   |
| 0x406e3    | 4         | 4.04%   |
| 0x806ec    | 3         | 3.03%   |
| 0x806eb    | 3         | 3.03%   |
| 0x806e9    | 3         | 3.03%   |
| 0x40661    | 3         | 3.03%   |
| 0x306c3    | 3         | 3.03%   |
| 0x0a404102 | 3         | 3.03%   |
| 0x906ed    | 2         | 2.02%   |
| 0x906ea    | 2         | 2.02%   |
| 0x906a3    | 2         | 2.02%   |
| 0x706a8    | 2         | 2.02%   |
| 0x706a1    | 2         | 2.02%   |
| 0x40651    | 2         | 2.02%   |
| 0x306d4    | 2         | 2.02%   |
| 0x306a9    | 2         | 2.02%   |
| 0x08600104 | 2         | 2.02%   |
| 0x906e9    | 1         | 1.01%   |
| 0x806d1    | 1         | 1.01%   |
| 0x506e3    | 1         | 1.01%   |
| 0x106c2    | 1         | 1.01%   |
| 0x0a704103 | 1         | 1.01%   |
| 0x0a601203 | 1         | 1.01%   |
| 0x0a50000b | 1         | 1.01%   |
| 0x0a404101 | 1         | 1.01%   |
| 0x08108109 | 1         | 1.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 24.21%  |
| Zen 3            | 12        | 12.63%  |
| Skylake          | 9         | 9.47%   |
| Haswell          | 9         | 9.47%   |
| Unknown          | 9         | 9.47%   |
| Zen 2            | 7         | 7.37%   |
| TigerLake        | 7         | 7.37%   |
| Alderlake Hybrid | 6         | 6.32%   |
| Goldmont plus    | 4         | 4.21%   |
| IvyBridge        | 3         | 3.16%   |
| Icelake          | 2         | 2.11%   |
| Broadwell        | 2         | 2.11%   |
| Zen+             | 1         | 1.05%   |
| Bonnell          | 1         | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 50%     |
| Nvidia | 35        | 26.92%  |
| AMD    | 30        | 23.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 10        | 7.52%   |
| AMD Renoir                                                                            | 7         | 5.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 4.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 6         | 4.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 3.76%   |
| Intel UHD Graphics 620                                                                | 5         | 3.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 3.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 5         | 3.76%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 3.01%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 3.01%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 3.01%   |
| AMD Rembrandt [Radeon 680M]                                                           | 4         | 3.01%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 2.26%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 2.26%   |
| Intel HD Graphics 620                                                                 | 3         | 2.26%   |
| Intel HD Graphics 530                                                                 | 3         | 2.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 2.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 2.26%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 2.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 1.5%    |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 1.5%    |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.5%    |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 1.5%    |
| Intel HD Graphics 5500                                                                | 2         | 1.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 1.5%    |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 2         | 1.5%    |
| AMD Barcelo                                                                           | 2         | 1.5%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                | 1         | 0.75%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                                      | 1         | 0.75%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 0.75%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.75%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 0.75%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 0.75%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 0.75%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 0.75%   |
| Nvidia GK106M [GeForce GTX 765M]                                                      | 1         | 0.75%   |
| Nvidia GK106GLM [Quadro K2100M]                                                       | 1         | 0.75%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 38.95%  |
| Intel + Nvidia | 23        | 24.21%  |
| 1 x AMD        | 16        | 16.84%  |
| AMD + Nvidia   | 8         | 8.42%   |
| 1 x Nvidia     | 4         | 4.21%   |
| Intel + AMD    | 4         | 4.21%   |
| 2 x AMD        | 2         | 2.11%   |
| 2 x Intel      | 1         | 1.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 74        | 77.08%  |
| Proprietary | 20        | 20.83%  |
| Unknown     | 2         | 2.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 59.18%  |
| 0.01-0.5   | 16        | 16.33%  |
| 1.01-2.0   | 11        | 11.22%  |
| 3.01-4.0   | 7         | 7.14%   |
| 0.51-1.0   | 4         | 4.08%   |
| 7.01-8.0   | 1         | 1.02%   |
| 8.01-16.0  | 1         | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 19        | 16.38%  |
| BOE                  | 15        | 12.93%  |
| LG Display           | 12        | 10.34%  |
| Samsung Electronics  | 11        | 9.48%   |
| Chimei Innolux       | 9         | 7.76%   |
| Dell                 | 8         | 6.9%    |
| Sharp                | 6         | 5.17%   |
| PANDA                | 5         | 4.31%   |
| CSO                  | 5         | 4.31%   |
| Apple                | 4         | 3.45%   |
| Goldstar             | 3         | 2.59%   |
| Philips              | 2         | 1.72%   |
| Panasonic            | 2         | 1.72%   |
| InfoVision           | 2         | 1.72%   |
| Hewlett-Packard      | 2         | 1.72%   |
| HannStar             | 2         | 1.72%   |
| Toshiba              | 1         | 0.86%   |
| TMX                  | 1         | 0.86%   |
| Lenovo               | 1         | 0.86%   |
| JDI                  | 1         | 0.86%   |
| Eizo                 | 1         | 0.86%   |
| ASUSTek Computer     | 1         | 0.86%   |
| AOC                  | 1         | 0.86%   |
| Ancor Communications | 1         | 0.86%   |
| Acer                 | 1         | 0.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 2         | 1.72%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch               | 2         | 1.72%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                      | 2         | 1.72%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 2         | 1.72%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch         | 2         | 1.72%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch          | 2         | 1.72%   |
| Toshiba PI-KVM Video TSB8888 1920x1080                                 | 1         | 0.86%   |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch                | 1         | 0.86%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 1         | 0.86%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 1         | 0.86%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                | 1         | 0.86%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.86%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch                | 1         | 0.86%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                | 1         | 0.86%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch      | 1         | 0.86%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch      | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch   | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch  | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch  | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 1020x570mm 46.0-inch | 1         | 0.86%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch    | 1         | 0.86%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch      | 1         | 0.86%   |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch      | 1         | 0.86%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch               | 1         | 0.86%   |
| Philips PHL 272P7VU PHL093A 3840x2160 597x336mm 27.0-inch              | 1         | 0.86%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                | 1         | 0.86%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch                | 1         | 0.86%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch                | 1         | 0.86%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 1         | 0.86%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                | 1         | 0.86%   |
| LG Display LCD Monitor LGD06CE 1920x1200 288x180mm 13.4-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD068A 1920x1080 309x174mm 14.0-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch            | 1         | 0.86%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch            | 1         | 0.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 45        | 40.91%  |
| 3840x2160 (4K)     | 15        | 13.64%  |
| 1366x768 (WXGA)    | 11        | 10%     |
| 2880x1800          | 9         | 8.18%   |
| 2560x1440 (QHD)    | 9         | 8.18%   |
| 2560x1600          | 6         | 5.45%   |
| 1920x1200 (WUXGA)  | 4         | 3.64%   |
| 3440x1440          | 2         | 1.82%   |
| 2256x1504          | 2         | 1.82%   |
| 1600x900 (HD+)     | 2         | 1.82%   |
| 3840x2400          | 1         | 0.91%   |
| 1920x1280          | 1         | 0.91%   |
| 1680x1050 (WSXGA+) | 1         | 0.91%   |
| 1280x1024 (SXGA)   | 1         | 0.91%   |
| 1024x600           | 1         | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 31        | 27.19%  |
| 14     | 24        | 21.05%  |
| 13     | 15        | 13.16%  |
| 27     | 8         | 7.02%   |
| 12     | 7         | 6.14%   |
| 17     | 6         | 5.26%   |
| 16     | 6         | 5.26%   |
| 24     | 5         | 4.39%   |
| 23     | 3         | 2.63%   |
| 34     | 2         | 1.75%   |
| 31     | 2         | 1.75%   |
| 46     | 1         | 0.88%   |
| 26     | 1         | 0.88%   |
| 22     | 1         | 0.88%   |
| 21     | 1         | 0.88%   |
| 10     | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 57.52%  |
| 201-300     | 18        | 15.93%  |
| 501-600     | 16        | 14.16%  |
| 351-400     | 6         | 5.31%   |
| 601-700     | 3         | 2.65%   |
| 701-800     | 2         | 1.77%   |
| 401-500     | 2         | 1.77%   |
| 1001-1500   | 1         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 70        | 70.71%  |
| 16/10 | 22        | 22.22%  |
| 3/2   | 3         | 3.03%   |
| 21/9  | 2         | 2.02%   |
| 5/4   | 1         | 1.01%   |
| 4/3   | 1         | 1.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 32        | 28.07%  |
| 101-110        | 31        | 27.19%  |
| 301-350        | 9         | 7.89%   |
| 201-250        | 9         | 7.89%   |
| 71-80          | 7         | 6.14%   |
| 61-70          | 7         | 6.14%   |
| 121-130        | 6         | 5.26%   |
| 111-120        | 5         | 4.39%   |
| 351-500        | 4         | 3.51%   |
| 41-50          | 1         | 0.88%   |
| 251-300        | 1         | 0.88%   |
| 141-150        | 1         | 0.88%   |
| 501-1000       | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 42        | 38.89%  |
| 161-240       | 27        | 25%     |
| More than 240 | 13        | 12.04%  |
| 101-120       | 13        | 12.04%  |
| 51-100        | 12        | 11.11%  |
| 1-50          | 1         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 71        | 71%     |
| 2     | 21        | 21%     |
| 0     | 5         | 5%      |
| 3     | 3         | 3%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 70        | 48.61%  |
| Realtek Semiconductor             | 44        | 30.56%  |
| MediaTek                          | 8         | 5.56%   |
| Qualcomm Atheros                  | 7         | 4.86%   |
| Broadcom                          | 5         | 3.47%   |
| Qualcomm                          | 2         | 1.39%   |
| Lenovo                            | 2         | 1.39%   |
| Xiaomi                            | 1         | 0.69%   |
| QinHeng Electronics               | 1         | 0.69%   |
| Microsoft                         | 1         | 0.69%   |
| Fibocom                           | 1         | 0.69%   |
| Ericsson Business Mobile Networks | 1         | 0.69%   |
| D-Link                            | 1         | 0.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 14.86%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 9.14%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 8%      |
| Intel Wireless 8260                                               | 6         | 3.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 3.43%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.29%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 2.29%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.29%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 2.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 2.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.71%   |
| Intel Wireless-AC 9260                                            | 3         | 1.71%   |
| Intel Wireless 7265                                               | 3         | 1.71%   |
| Intel Wireless 7260                                               | 3         | 1.71%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.14%   |
| Intel Wireless 3165                                               | 2         | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.14%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.14%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 1.14%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.57%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.57%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.57%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 0.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 70        | 71.43%  |
| MediaTek                          | 8         | 8.16%   |
| Qualcomm Atheros                  | 6         | 6.12%   |
| Broadcom                          | 5         | 5.1%    |
| Realtek Semiconductor             | 3         | 3.06%   |
| Qualcomm                          | 2         | 2.04%   |
| Microsoft                         | 1         | 1.02%   |
| Fibocom                           | 1         | 1.02%   |
| Ericsson Business Mobile Networks | 1         | 1.02%   |
| D-Link                            | 1         | 1.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 14        | 14.29%  |
| Intel Wireless 8260                                            | 6         | 6.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 6.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 4.08%   |
| Intel Wireless 8265 / 8275                                     | 4         | 4.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 4.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 4.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 4.08%   |
| Intel Wireless-AC 9260                                         | 3         | 3.06%   |
| Intel Wireless 7265                                            | 3         | 3.06%   |
| Intel Wireless 7260                                            | 3         | 3.06%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.04%   |
| Intel Wireless 3165                                            | 2         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.04%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 2.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 2.04%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.02%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.02%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.02%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 1.02%   |
| Intel Wireless 3160                                            | 1         | 1.02%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 1         | 1.02%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.02%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 1         | 1.02%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 1.02%   |
| Ericsson Business Mobile Networks N5321 gw                     | 1         | 1.02%   |
| D-Link 802.11ac NIC                                            | 1         | 1.02%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 42        | 60%     |
| Intel                 | 22        | 31.43%  |
| Qualcomm Atheros      | 2         | 2.86%   |
| Lenovo                | 2         | 2.86%   |
| Xiaomi                | 1         | 1.43%   |
| Broadcom              | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 34.21%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 21.05%  |
| Intel Ethernet Connection I219-LM                                 | 5         | 6.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.63%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.63%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.63%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.32%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.32%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.32%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.32%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.32%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 94        | 57.67%  |
| Ethernet | 68        | 41.72%  |
| Modem    | 1         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 84.26%  |
| Ethernet | 17        | 15.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 53        | 55.79%  |
| 1     | 40        | 42.11%  |
| 3     | 2         | 2.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 74        | 77.08%  |
| Yes  | 22        | 22.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 71.91%  |
| MediaTek                        | 4         | 4.49%   |
| IMC Networks                    | 4         | 4.49%   |
| Apple                           | 4         | 4.49%   |
| Qualcomm Atheros Communications | 3         | 3.37%   |
| Realtek Semiconductor           | 2         | 2.25%   |
| Foxconn / Hon Hai               | 2         | 2.25%   |
| Broadcom                        | 2         | 2.25%   |
| USI                             | 1         | 1.12%   |
| Realtek                         | 1         | 1.12%   |
| Lite-On Technology              | 1         | 1.12%   |
| ASUSTek Computer                | 1         | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 16        | 17.98%  |
| Intel AX200 Bluetooth                          | 14        | 15.73%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 10        | 11.24%  |
| Intel Bluetooth Device                         | 8         | 8.99%   |
| Intel AX201 Bluetooth                          | 7         | 7.87%   |
| Intel AX210 Bluetooth                          | 6         | 6.74%   |
| MediaTek Wireless_Device                       | 4         | 4.49%   |
| Apple Bluetooth Host Controller                | 4         | 4.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 3         | 3.37%   |
| Realtek Bluetooth Radio                        | 2         | 2.25%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 2.25%   |
| IMC Networks Wireless_Device                   | 2         | 2.25%   |
| USI Bluetooth Device                           | 1         | 1.12%   |
| Realtek 802.11ac WLAN Adapter                  | 1         | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 1.12%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.12%   |
| IMC Networks Bluetooth Device                  | 1         | 1.12%   |
| IMC Networks BCM20702A0                        | 1         | 1.12%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 1.12%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 1         | 1.12%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 1.12%   |
| ASUS Broadcom Bluetooth 2.1                    | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 70        | 50%     |
| AMD                       | 28        | 20%     |
| Nvidia                    | 19        | 13.57%  |
| Lenovo                    | 4         | 2.86%   |
| C-Media Electronics       | 4         | 2.86%   |
| Realtek Semiconductor     | 3         | 2.14%   |
| Synaptics                 | 2         | 1.43%   |
| Trust                     | 1         | 0.71%   |
| Sennheiser Communications | 1         | 0.71%   |
| Satechi                   | 1         | 0.71%   |
| Logitech                  | 1         | 0.71%   |
| Kingston Technology       | 1         | 0.71%   |
| JMTek                     | 1         | 0.71%   |
| Focusrite-Novation        | 1         | 0.71%   |
| Creative Technology       | 1         | 0.71%   |
| Corsair                   | 1         | 0.71%   |
| (LCS) USB Audio Device    | 1         | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 26        | 15.03%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 17        | 9.83%   |
| Intel Sunrise Point-LP HD Audio                                         | 15        | 8.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 7         | 4.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 7         | 4.05%   |
| Intel Cannon Lake PCH cAVS                                              | 6         | 3.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 5         | 2.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 5         | 2.89%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 5         | 2.89%   |
| Nvidia Audio device                                                     | 4         | 2.31%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 2.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 4         | 2.31%   |
| Realtek Semiconductor USB Audio                                         | 3         | 1.73%   |
| Nvidia GA106 High Definition Audio Controller                           | 3         | 1.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 3         | 1.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 3         | 1.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 3         | 1.73%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                         | 2         | 1.16%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 1.16%   |
| Nvidia GK106 HDMI Audio Controller                                      | 2         | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                           | 2         | 1.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 1.16%   |
| Intel Haswell-ULT HD Audio Controller                                   | 2         | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                            | 2         | 1.16%   |
| Intel Broadwell-U Audio Controller                                      | 2         | 1.16%   |
| Intel 8 Series HD Audio Controller                                      | 2         | 1.16%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 1.16%   |
| Trust USB microphone                                                    | 1         | 0.58%   |
| Sennheiser Communications Headset [PC 8]                                | 1         | 0.58%   |
| Satechi Audio & PD Adapter                                              | 1         | 0.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 1         | 0.58%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.58%   |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 1         | 0.58%   |
| Logitech Blue Microphones                                               | 1         | 0.58%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                               | 1         | 0.58%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                            | 1         | 0.58%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                            | 1         | 0.58%   |
| Lenovo ThinkPad Dock USB Audio                                          | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 34        | 29.82%  |
| Micron Technology            | 20        | 17.54%  |
| SK hynix                     | 19        | 16.67%  |
| Crucial                      | 10        | 8.77%   |
| Kingston                     | 7         | 6.14%   |
| Unknown                      | 4         | 3.51%   |
| Unknown (ABCD)               | 3         | 2.63%   |
| Team                         | 3         | 2.63%   |
| Ramaxel Technology           | 2         | 1.75%   |
| A-DATA Technology            | 2         | 1.75%   |
| Unknown                      | 2         | 1.75%   |
| Patriot Memory (PDP Systems) | 1         | 0.88%   |
| Patriot                      | 1         | 0.88%   |
| GOODRAM                      | 1         | 0.88%   |
| G.Skill                      | 1         | 0.88%   |
| Corsair                      | 1         | 0.88%   |
| Avant                        | 1         | 0.88%   |
| Apacer                       | 1         | 0.88%   |
| AMD                          | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 3         | 2.46%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 2.46%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 2.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.46%   |
| Team RAM TEAMGROUP-SD4-3200 8192MB SODIMM DDR4 3200MT/s          | 2         | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.64%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.64%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.64%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.64%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.64%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 2         | 1.64%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.64%   |
| Unknown                                                          | 2         | 1.64%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.82%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.82%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.82%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.82%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.82%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.82%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.82%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.82%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s           | 1         | 0.82%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.82%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.82%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 0.82%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.82%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.82%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.82%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 0.82%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 1         | 0.82%   |
| SK hynix RAM H9JCNNNBK3MLYR-N6E 1GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.82%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.82%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.82%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.82%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.82%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.82%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 0.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 50        | 53.19%  |
| DDR3   | 15        | 15.96%  |
| LPDDR4 | 12        | 12.77%  |
| LPDDR5 | 9         | 9.57%   |
| LPDDR3 | 4         | 4.26%   |
| DDR5   | 3         | 3.19%   |
| SDRAM  | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 76.53%  |
| Row Of Chips | 20        | 20.41%  |
| Chip         | 2         | 2.04%   |
| Unknown      | 1         | 1.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 46        | 43.81%  |
| 16384 | 23        | 21.9%   |
| 4096  | 20        | 19.05%  |
| 32768 | 12        | 11.43%  |
| 2048  | 3         | 2.86%   |
| 1024  | 1         | 0.95%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 23        | 23.23%  |
| 2667    | 21        | 21.21%  |
| 1600    | 14        | 14.14%  |
| 6400    | 9         | 9.09%   |
| 2133    | 8         | 8.08%   |
| 4267    | 6         | 6.06%   |
| 2400    | 6         | 6.06%   |
| 4266    | 3         | 3.03%   |
| 3266    | 3         | 3.03%   |
| 5600    | 2         | 2.02%   |
| 1867    | 2         | 2.02%   |
| 4800    | 1         | 1.01%   |
| Unknown | 1         | 1.01%   |

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
| Chicony Electronics           | 20        | 23.53%  |
| IMC Networks                  | 14        | 16.47%  |
| Microdia                      | 12        | 14.12%  |
| Bison Electronics             | 8         | 9.41%   |
| Realtek Semiconductor         | 7         | 8.24%   |
| Sunplus Innovation Technology | 5         | 5.88%   |
| Logitech                      | 4         | 4.71%   |
| Lite-On Technology            | 3         | 3.53%   |
| Acer                          | 3         | 3.53%   |
| Syntek                        | 2         | 2.35%   |
| Quanta                        | 2         | 2.35%   |
| Sonix Technology              | 1         | 1.18%   |
| Primax Electronics            | 1         | 1.18%   |
| Luxvisions Innotech Limited   | 1         | 1.18%   |
| Alcor Micro                   | 1         | 1.18%   |
| 2M UVC CAMERA                 | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 13        | 14.94%  |
| Microdia Integrated_Webcam_HD                     | 6         | 6.9%    |
| IMC Networks USB2.0 HD UVC WebCam                 | 6         | 6.9%    |
| IMC Networks Integrated Camera                    | 5         | 5.75%   |
| Chicony HP HD Camera                              | 4         | 4.6%    |
| Logitech HD Pro Webcam C920                       | 3         | 3.45%   |
| Bison Integrated Camera                           | 3         | 3.45%   |
| Syntek Integrated Camera                          | 2         | 2.3%    |
| Sunplus Integrated_Webcam_HD                      | 2         | 2.3%    |
| Sunplus Integrated_Webcam_FHD                     | 2         | 2.3%    |
| Realtek Laptop Camera                             | 2         | 2.3%    |
| Realtek Integrated_Webcam_HD                      | 2         | 2.3%    |
| Microdia Webcam Vitade AF                         | 2         | 2.3%    |
| Lite-On Integrated Camera                         | 2         | 2.3%    |
| Bison HD Webcam                                   | 2         | 2.3%    |
| Sunplus Laptop Integrated Webcam FHD              | 1         | 1.15%   |
| Sonix USB2.0 FHD UVC WebCam                       | 1         | 1.15%   |
| Realtek USB Camera                                | 1         | 1.15%   |
| Realtek TV Camera                                 | 1         | 1.15%   |
| Realtek Lenovo EasyCamera                         | 1         | 1.15%   |
| Realtek Integrated Webcam                         | 1         | 1.15%   |
| Quanta VGA WebCam                                 | 1         | 1.15%   |
| Quanta HD WebCam                                  | 1         | 1.15%   |
| Primax HP HD Webcam [Fixed]                       | 1         | 1.15%   |
| Microdia USB 2.0 Camera                           | 1         | 1.15%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 1.15%   |
| Microdia Integrated Webcam                        | 1         | 1.15%   |
| Microdia HP Integrated Webcam                     | 1         | 1.15%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1.15%   |
| Logitech Webcam C310                              | 1         | 1.15%   |
| Lite-On HP HD Camera                              | 1         | 1.15%   |
| IMC Networks XHC Camera                           | 1         | 1.15%   |
| IMC Networks USB2.0 UVC 1.3M WebCam               | 1         | 1.15%   |
| IMC Networks ov9734_azurewave_camera              | 1         | 1.15%   |
| Chicony USB2.0 Camera                             | 1         | 1.15%   |
| Chicony Integrated IR Camera                      | 1         | 1.15%   |
| Chicony Integrated Camera [ThinkPad]              | 1         | 1.15%   |
| Bison SunplusIT Integrated Camera                 | 1         | 1.15%   |
| Bison Integrated RGB Camera                       | 1         | 1.15%   |
| Bison Integrated IR Camera                        | 1         | 1.15%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 39.13%  |
| Synaptics                  | 9         | 39.13%  |
| Shenzhen Goodix Technology | 4         | 17.39%  |
| Focal-systems.Corp         | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 5         | 21.74%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 13.04%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 8.7%    |
| Synaptics UWP WBDI Device                                | 2         | 8.7%    |
| Shenzhen Goodix  Fingerprint Device                      | 2         | 8.7%    |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 8.7%    |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 4.35%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 4.35%   |
| Validity Sensors VFS491                                  | 1         | 4.35%   |
| Validity Sensors Synaptics WBDI                          | 1         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 4.35%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.35%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 11        | 61.11%  |
| Yubico.com  | 3         | 16.67%  |
| Broadcom    | 3         | 16.67%  |
| Upek        | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 11        | 61.11%  |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 2         | 11.11%  |
| Broadcom 5880                                              | 2         | 11.11%  |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 5.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 42        | 42.86%  |
| 1     | 33        | 33.67%  |
| 2     | 20        | 20.41%  |
| 4     | 2         | 2.04%   |
| 3     | 1         | 1.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 25.93%  |
| Multimedia controller    | 17        | 20.99%  |
| Graphics card            | 14        | 17.28%  |
| Chipcard                 | 13        | 16.05%  |
| Net/wireless             | 3         | 3.7%    |
| Camera                   | 3         | 3.7%    |
| Bluetooth                | 3         | 3.7%    |
| Modem                    | 2         | 2.47%   |
| Card reader              | 2         | 2.47%   |
| Network                  | 1         | 1.23%   |
| Firewire controller      | 1         | 1.23%   |
| Communication controller | 1         | 1.23%   |

