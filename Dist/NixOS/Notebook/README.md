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

Total: 158

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6540              | [8fdc000f7e](https://linux-hardware.org/?probe=8fdc000f7e) | Oct 01, 2023 |
| Dell          | Latitude E6540              | [a5de8b78e7](https://linux-hardware.org/?probe=a5de8b78e7) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1135ddac8e](https://linux-hardware.org/?probe=1135ddac8e) | Sep 30, 2023 |
| Dell          | Latitude 5430               | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| Dell          | Latitude E6540              | [1478e1265d](https://linux-hardware.org/?probe=1478e1265d) | Sep 29, 2023 |
| Dell          | XPS 15 9560                 | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Dell          | Latitude E6540              | [7d9885cd7c](https://linux-hardware.org/?probe=7d9885cd7c) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| HP            | EliteBook 8470p             | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | [bf71bcd90e](https://linux-hardware.org/?probe=bf71bcd90e) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Apple         | MacBookPro9,2               | [4d2c8f9f07](https://linux-hardware.org/?probe=4d2c8f9f07) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| Dell          | Latitude E6540              | [ff29b23e60](https://linux-hardware.org/?probe=ff29b23e60) | Sep 13, 2023 |
| Acer          | Aspire E5-575G              | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S4RV00    | [8ae7288bf3](https://linux-hardware.org/?probe=8ae7288bf3) | Sep 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | [5778731f85](https://linux-hardware.org/?probe=5778731f85) | Sep 10, 2023 |
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
| NixOS 23.05                      | 38        | 31.4%   |
| NixOS 22.11                      | 27        | 22.31%  |
| NixOS 22.05                      | 18        | 14.88%  |
| NixOS 23.11                      | 15        | 12.4%   |
| NixOS 21.11                      | 9         | 7.44%   |
| NixOS                            | 2         | 1.65%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.83%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.83%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.83%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.83%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.83%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.83%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.83%   |
| NixOS 20.09pre-git               | 1         | 0.83%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.83%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.83%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.83%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 108       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version       | Notebooks | Percent |
|---------------|-----------|---------|
| 6.3.8         | 4         | 3.13%   |
| 6.1.51        | 4         | 3.13%   |
| 6.3.3         | 3         | 2.34%   |
| 6.1.53        | 3         | 2.34%   |
| 6.1.38        | 3         | 2.34%   |
| 5.15.74       | 3         | 2.34%   |
| 5.15.43       | 3         | 2.34%   |
| 6.4.0         | 2         | 1.56%   |
| 6.3.1         | 2         | 1.56%   |
| 6.1.47        | 2         | 1.56%   |
| 6.1.42        | 2         | 1.56%   |
| 6.1.41        | 2         | 1.56%   |
| 6.1.35        | 2         | 1.56%   |
| 6.1.34        | 2         | 1.56%   |
| 6.1.0         | 2         | 1.56%   |
| 6.0.10        | 2         | 1.56%   |
| 5.16.15       | 2         | 1.56%   |
| 5.15.72       | 2         | 1.56%   |
| 5.15.68       | 2         | 1.56%   |
| 5.15.64       | 2         | 1.56%   |
| 5.15.26       | 2         | 1.56%   |
| 5.13.7        | 2         | 1.56%   |
| 6.5.3         | 1         | 0.78%   |
| 6.5.2         | 1         | 0.78%   |
| 6.4.8         | 1         | 0.78%   |
| 6.4.6         | 1         | 0.78%   |
| 6.4.2         | 1         | 0.78%   |
| 6.4.14        | 1         | 0.78%   |
| 6.3.9         | 1         | 0.78%   |
| 6.3.5         | 1         | 0.78%   |
| 6.2.9-lqx1    | 1         | 0.78%   |
| 6.2.9         | 1         | 0.78%   |
| 6.2.8         | 1         | 0.78%   |
| 6.2.7         | 1         | 0.78%   |
| 6.2.14        | 1         | 0.78%   |
| 6.2.0         | 1         | 0.78%   |
| 6.1.7-xanmod1 | 1         | 0.78%   |
| 6.1.46        | 1         | 0.78%   |
| 6.1.45        | 1         | 0.78%   |
| 6.1.43        | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.8   | 4         | 3.13%   |
| 6.1.51  | 4         | 3.13%   |
| 6.3.3   | 3         | 2.34%   |
| 6.1.53  | 3         | 2.34%   |
| 6.1.38  | 3         | 2.34%   |
| 6.0.10  | 3         | 2.34%   |
| 5.15.74 | 3         | 2.34%   |
| 5.15.43 | 3         | 2.34%   |
| 6.4.0   | 2         | 1.56%   |
| 6.3.1   | 2         | 1.56%   |
| 6.2.9   | 2         | 1.56%   |
| 6.1.47  | 2         | 1.56%   |
| 6.1.42  | 2         | 1.56%   |
| 6.1.41  | 2         | 1.56%   |
| 6.1.35  | 2         | 1.56%   |
| 6.1.34  | 2         | 1.56%   |
| 6.1.0   | 2         | 1.56%   |
| 5.16.15 | 2         | 1.56%   |
| 5.15.72 | 2         | 1.56%   |
| 5.15.68 | 2         | 1.56%   |
| 5.15.64 | 2         | 1.56%   |
| 5.15.26 | 2         | 1.56%   |
| 5.13.7  | 2         | 1.56%   |
| 6.5.3   | 1         | 0.78%   |
| 6.5.2   | 1         | 0.78%   |
| 6.4.8   | 1         | 0.78%   |
| 6.4.6   | 1         | 0.78%   |
| 6.4.2   | 1         | 0.78%   |
| 6.4.14  | 1         | 0.78%   |
| 6.3.9   | 1         | 0.78%   |
| 6.3.5   | 1         | 0.78%   |
| 6.2.8   | 1         | 0.78%   |
| 6.2.7   | 1         | 0.78%   |
| 6.2.14  | 1         | 0.78%   |
| 6.2.0   | 1         | 0.78%   |
| 6.1.7   | 1         | 0.78%   |
| 6.1.46  | 1         | 0.78%   |
| 6.1.45  | 1         | 0.78%   |
| 6.1.43  | 1         | 0.78%   |
| 6.1.39  | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 33        | 26.4%   |
| 5.15    | 31        | 24.8%   |
| 6.3     | 11        | 8.8%    |
| 6.4     | 6         | 4.8%    |
| 6.2     | 6         | 4.8%    |
| 6.0     | 6         | 4.8%    |
| 5.16    | 6         | 4.8%    |
| 5.8     | 3         | 2.4%    |
| 5.19    | 3         | 2.4%    |
| 5.13    | 3         | 2.4%    |
| 5.10    | 3         | 2.4%    |
| 6.5     | 2         | 1.6%    |
| 5.7     | 2         | 1.6%    |
| 5.4     | 2         | 1.6%    |
| 5.18    | 2         | 1.6%    |
| 5.17    | 2         | 1.6%    |
| 4.19    | 2         | 1.6%    |
| 5.12    | 1         | 0.8%    |
| Unknown | 1         | 0.8%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 107       | 99.07%  |
| i686   | 1         | 0.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 47        | 41.23%  |
| GNOME        | 17        | 14.91%  |
| sway         | 13        | 11.4%   |
| KDE5         | 11        | 9.65%   |
| Hyprland     | 7         | 6.14%   |
| KDE          | 5         | 4.39%   |
| none+i3      | 4         | 3.51%   |
| XFCE         | 3         | 2.63%   |
| none+xmonad  | 2         | 1.75%   |
| X-Cinnamon   | 1         | 0.88%   |
| Pantheon     | 1         | 0.88%   |
| none+bspwm   | 1         | 0.88%   |
| none+awesome | 1         | 0.88%   |
| Budgie       | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 46.09%  |
| Wayland | 37        | 32.17%  |
| X11     | 20        | 17.39%  |
| Tty     | 5         | 4.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 57        | 51.82%  |
| GDM     | 22        | 20%     |
| SDDM    | 17        | 15.45%  |
| LightDM | 14        | 12.73%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 58        | 52.73%  |
| Unknown | 33        | 30%     |
| en_GB   | 5         | 4.55%   |
| en_DK   | 2         | 1.82%   |
| en_CA   | 2         | 1.82%   |
| ru_RU   | 1         | 0.91%   |
| ro_RO   | 1         | 0.91%   |
| pt_BR   | 1         | 0.91%   |
| lv_LV   | 1         | 0.91%   |
| it_IT   | 1         | 0.91%   |
| fr_FR   | 1         | 0.91%   |
| es_MX   | 1         | 0.91%   |
| en_IN   | 1         | 0.91%   |
| en_AU   | 1         | 0.91%   |
| de_DE   | 1         | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 97        | 89.81%  |
| BIOS | 11        | 10.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 60        | 53.57%  |
| Btrfs   | 17        | 15.18%  |
| Tmpfs   | 14        | 12.5%   |
| Zfs     | 10        | 8.93%   |
| Xfs     | 8         | 7.14%   |
| Unknown | 3         | 2.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 101       | 91.82%  |
| Unknown | 5         | 4.55%   |
| MBR     | 4         | 3.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 80.91%  |
| Yes       | 21        | 19.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 76.85%  |
| Yes       | 25        | 23.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 41        | 37.96%  |
| Dell                   | 20        | 18.52%  |
| ASUSTek Computer       | 11        | 10.19%  |
| Hewlett-Packard        | 8         | 7.41%   |
| Apple                  | 5         | 4.63%   |
| GPD                    | 3         | 2.78%   |
| Acer                   | 3         | 2.78%   |
| MSI                    | 2         | 1.85%   |
| MECHREVO               | 2         | 1.85%   |
| Framework              | 2         | 1.85%   |
| Toshiba                | 1         | 0.93%   |
| System76               | 1         | 0.93%   |
| OBSIDIAN-PC            | 1         | 0.93%   |
| Microtech              | 1         | 0.93%   |
| MACHENIKE              | 1         | 0.93%   |
| Intel                  | 1         | 0.93%   |
| HUAWEI                 | 1         | 0.93%   |
| Gigabyte Technology    | 1         | 0.93%   |
| Blackview              | 1         | 0.93%   |
| Avell High Performance | 1         | 0.93%   |
| Alienware              | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 8470p                          | 2         | 1.85%   |
| Dell Latitude 7420                          | 2         | 1.85%   |
| Apple MacBookPro11,5                        | 2         | 1.85%   |
| Apple MacBookPro11,3                        | 2         | 1.85%   |
| Toshiba Satellite L50-B                     | 1         | 0.93%   |
| System76 Pangolin                           | 1         | 0.93%   |
| OBSIDIAN-PC N13_N140ZU                      | 1         | 0.93%   |
| MSI Bravo 15 B5DD                           | 1         | 0.93%   |
| MSI Alpha 15 B5EEK                          | 1         | 0.93%   |
| Microtech CoreBook Lite                     | 1         | 0.93%   |
| MECHREVO WUJIE 14                           | 1         | 0.93%   |
| MECHREVO Code01 Ver2.0                      | 1         | 0.93%   |
| MACHENIKE F117-7P                           | 1         | 0.93%   |
| Lenovo Yoga Slim 7 13ACN5 82CY              | 1         | 0.93%   |
| Lenovo Yoga 14sARE 2020 82A8                | 1         | 0.93%   |
| Lenovo ThinkPad X390 20Q0CTO1WW             | 1         | 0.93%   |
| Lenovo ThinkPad X260 20F5S6MF02             | 1         | 0.93%   |
| Lenovo ThinkPad X260 20F5S4BY00             | 1         | 0.93%   |
| Lenovo ThinkPad X250 20CLS18S0T             | 1         | 0.93%   |
| Lenovo ThinkPad X230 2333AZ2                | 1         | 0.93%   |
| Lenovo ThinkPad X230 23243E9                | 1         | 0.93%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW       | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB007AUK | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBCT01WW    | 1         | 0.93%   |
| Lenovo ThinkPad T580 20L90024PB             | 1         | 0.93%   |
| Lenovo ThinkPad T540p 20BE005YMH            | 1         | 0.93%   |
| Lenovo ThinkPad T490 20N2000LUK             | 1         | 0.93%   |
| Lenovo ThinkPad T480s 20L7CTO1WW            | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L6S4RV00             | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L5CTO1WW             | 1         | 0.93%   |
| Lenovo ThinkPad T470s 20HF0000MX            | 1         | 0.93%   |
| Lenovo ThinkPad T470 20HES2RC00             | 1         | 0.93%   |
| Lenovo ThinkPad T460p 20FWCTO1WW            | 1         | 0.93%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW        | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 3 21BR000MUS       | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK       | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT        | 1         | 0.93%   |
| Lenovo ThinkPad S1 Yoga 20CD00B0US          | 1         | 0.93%   |
| Lenovo ThinkPad P50 20EN0005GE              | 1         | 0.93%   |
| Lenovo ThinkPad P14s Gen 3 21J5002KMH       | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 28        | 25.93%  |
| Dell XPS                   | 7         | 6.48%   |
| Dell Latitude              | 7         | 6.48%   |
| Lenovo Legion              | 5         | 4.63%   |
| HP EliteBook               | 5         | 4.63%   |
| Lenovo IdeaPad             | 4         | 3.7%    |
| ASUS ROG                   | 4         | 3.7%    |
| Apple MacBookPro11         | 4         | 3.7%    |
| Dell Precision             | 3         | 2.78%   |
| ASUS Zenbook               | 3         | 2.78%   |
| Acer Aspire                | 3         | 2.78%   |
| Lenovo Yoga                | 2         | 1.85%   |
| HP ProBook                 | 2         | 1.85%   |
| Framework Laptop           | 2         | 1.85%   |
| Dell Inspiron              | 2         | 1.85%   |
| Toshiba Satellite          | 1         | 0.93%   |
| System76 Pangolin          | 1         | 0.93%   |
| OBSIDIAN-PC N13            | 1         | 0.93%   |
| MSI Bravo                  | 1         | 0.93%   |
| MSI Alpha                  | 1         | 0.93%   |
| Microtech CoreBook         | 1         | 0.93%   |
| MECHREVO WUJIE             | 1         | 0.93%   |
| MECHREVO Code01            | 1         | 0.93%   |
| MACHENIKE F117-7P          | 1         | 0.93%   |
| Lenovo ThinkBook           | 1         | 0.93%   |
| Lenovo G50-70              | 1         | 0.93%   |
| Intel SharkBay             | 1         | 0.93%   |
| HUAWEI NBLK-WAX9X          | 1         | 0.93%   |
| HP ZBook                   | 1         | 0.93%   |
| GPD WIN2                   | 1         | 0.93%   |
| GPD MicroPC                | 1         | 0.93%   |
| GPD G1621-02               | 1         | 0.93%   |
| Gigabyte Sabre             | 1         | 0.93%   |
| Dell Wyse                  | 1         | 0.93%   |
| Blackview AceBook          | 1         | 0.93%   |
| Avell High Performance A70 | 1         | 0.93%   |
| ASUS VivoBook              | 1         | 0.93%   |
| ASUS ProArt                | 1         | 0.93%   |
| ASUS ASUSPRO               | 1         | 0.93%   |
| ASUS 1005HA                | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 18        | 16.67%  |
| 2022 | 13        | 12.04%  |
| 2020 | 13        | 12.04%  |
| 2019 | 11        | 10.19%  |
| 2016 | 10        | 9.26%   |
| 2018 | 9         | 8.33%   |
| 2013 | 7         | 6.48%   |
| 2017 | 6         | 5.56%   |
| 2023 | 5         | 4.63%   |
| 2015 | 5         | 4.63%   |
| 2014 | 4         | 3.7%    |
| 2012 | 4         | 3.7%    |
| 2011 | 2         | 1.85%   |
| 2009 | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 108       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 106       | 97.25%  |
| Enabled  | 3         | 2.75%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 99.07%  |
| Yes  | 1         | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 29        | 26.61%  |
| 32.01-64.0  | 25        | 22.94%  |
| 8.01-16.0   | 25        | 22.94%  |
| 4.01-8.0    | 16        | 14.68%  |
| 64.01-256.0 | 6         | 5.5%    |
| 3.01-4.0    | 4         | 3.67%   |
| 24.01-32.0  | 3         | 2.75%   |
| 0.51-1.0    | 1         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 32        | 26.02%  |
| 3.01-4.0   | 25        | 20.33%  |
| 2.01-3.0   | 19        | 15.45%  |
| 8.01-16.0  | 18        | 14.63%  |
| 1.01-2.0   | 11        | 8.94%   |
| 0.51-1.0   | 6         | 4.88%   |
| 24.01-32.0 | 5         | 4.07%   |
| 16.01-24.0 | 3         | 2.44%   |
| 32.01-64.0 | 2         | 1.63%   |
| 0.01-0.5   | 2         | 1.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 83        | 76.15%  |
| 2      | 24        | 22.02%  |
| 3      | 2         | 1.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 88.89%  |
| Yes       | 12        | 11.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 69.37%  |
| No        | 34        | 30.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 99.07%  |
| No        | 1         | 0.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 91.82%  |
| No        | 9         | 8.18%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 21        | 19.44%  |
| UK          | 8         | 7.41%   |
| Russia      | 7         | 6.48%   |
| France      | 7         | 6.48%   |
| Germany     | 6         | 5.56%   |
| Italy       | 5         | 4.63%   |
| Ukraine     | 4         | 3.7%    |
| Poland      | 4         | 3.7%    |
| Canada      | 4         | 3.7%    |
| Norway      | 3         | 2.78%   |
| Netherlands | 3         | 2.78%   |
| Switzerland | 2         | 1.85%   |
| Sweden      | 2         | 1.85%   |
| Japan       | 2         | 1.85%   |
| Iraq        | 2         | 1.85%   |
| India       | 2         | 1.85%   |
| Czechia     | 2         | 1.85%   |
| Brazil      | 2         | 1.85%   |
| Belgium     | 2         | 1.85%   |
| Austria     | 2         | 1.85%   |
| Uruguay     | 1         | 0.93%   |
| Spain       | 1         | 0.93%   |
| Slovenia    | 1         | 0.93%   |
| Singapore   | 1         | 0.93%   |
| Serbia      | 1         | 0.93%   |
| Romania     | 1         | 0.93%   |
| Portugal    | 1         | 0.93%   |
| Peru        | 1         | 0.93%   |
| Mexico      | 1         | 0.93%   |
| Latvia      | 1         | 0.93%   |
| Kuwait      | 1         | 0.93%   |
| Iran        | 1         | 0.93%   |
| Hungary     | 1         | 0.93%   |
| Hong Kong   | 1         | 0.93%   |
| Denmark     | 1         | 0.93%   |
| Colombia    | 1         | 0.93%   |
| China       | 1         | 0.93%   |
| Australia   | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 3         | 2.61%   |
| Vienna             | 2         | 1.74%   |
| Phoenix            | 2         | 1.74%   |
| Ottawa             | 2         | 1.74%   |
| Oslo               | 2         | 1.74%   |
| Marki              | 2         | 1.74%   |
| Kharkiv            | 2         | 1.74%   |
| Halifax            | 2         | 1.74%   |
| Craigsville        | 2         | 1.74%   |
| Catania            | 2         | 1.74%   |
| Baghdad            | 2         | 1.74%   |
| Zurich             | 1         | 0.87%   |
| Yangzhou           | 1         | 0.87%   |
| Woodford           | 1         | 0.87%   |
| Woldegk            | 1         | 0.87%   |
| Warsaw             | 1         | 0.87%   |
| Villeurbanne       | 1         | 0.87%   |
| Victorville        | 1         | 0.87%   |
| Verneuil-sur-Seine | 1         | 0.87%   |
| Valpacos           | 1         | 0.87%   |
| Trento             | 1         | 0.87%   |
| Tremestieri Etneo  | 1         | 0.87%   |
| Tover              | 1         | 0.87%   |
| Tottenham          | 1         | 0.87%   |
| Tolyatti           | 1         | 0.87%   |
| Tehran             | 1         | 0.87%   |
| Szigetszentmiklos  | 1         | 0.87%   |
| Stockholm          | 1         | 0.87%   |
| Staten Island      | 1         | 0.87%   |
| St Petersburg      | 1         | 0.87%   |
| Southampton        | 1         | 0.87%   |
| South Deerfield    | 1         | 0.87%   |
| Sollentuna         | 1         | 0.87%   |
| Sobral             | 1         | 0.87%   |
| Smolensk           | 1         | 0.87%   |
| Singapore          | 1         | 0.87%   |
| Seattle            | 1         | 0.87%   |
| Saratov            | 1         | 0.87%   |
| Santee             | 1         | 0.87%   |
| Rochester          | 1         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 38        | 51     | 29.01%  |
| Sandisk                        | 12        | 12     | 9.16%   |
| WDC                            | 8         | 8      | 6.11%   |
| SK hynix                       | 8         | 11     | 6.11%   |
| Toshiba                        | 7         | 7      | 5.34%   |
| Micron Technology              | 7         | 8      | 5.34%   |
| Kingston                       | 6         | 7      | 4.58%   |
| Apple                          | 5         | 7      | 3.82%   |
| Unknown                        | 4         | 4      | 3.05%   |
| Intel                          | 4         | 5      | 3.05%   |
| Crucial                        | 4         | 5      | 3.05%   |
| Yangtze Memory Technologies    | 2         | 2      | 1.53%   |
| Transcend                      | 2         | 2      | 1.53%   |
| Seagate                        | 2         | 3      | 1.53%   |
| KIOXIA                         | 2         | 3      | 1.53%   |
| Kingston Technology Company    | 2         | 2      | 1.53%   |
| A-DATA Technology              | 2         | 2      | 1.53%   |
| SPCC                           | 1         | 1      | 0.76%   |
| Solid State Storage Technology | 1         | 1      | 0.76%   |
| S3+                            | 1         | 1      | 0.76%   |
| PNY                            | 1         | 2      | 0.76%   |
| Micron/Crucial Technology      | 1         | 1      | 0.76%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.76%   |
| LITEONIT                       | 1         | 1      | 0.76%   |
| INNOVATION IT                  | 1         | 1      | 0.76%   |
| Hitachi                        | 1         | 2      | 0.76%   |
| HGST                           | 1         | 1      | 0.76%   |
| Dogfish                        | 1         | 1      | 0.76%   |
| Corsair                        | 1         | 1      | 0.76%   |
| China                          | 1         | 1      | 0.76%   |
| Biwin Storage Technology       | 1         | 1      | 0.76%   |
| BIWIN                          | 1         | 1      | 0.76%   |
| ADATA Technology               | 1         | 2      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 8         | 5.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 6         | 4.35%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 2         | 1.45%   |
| SK hynix PC801 NVMe 512GB                           | 2         | 1.45%   |
| Samsung SSD 870 EVO 500GB                           | 2         | 1.45%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 1.45%   |
| Samsung PM9A1 NVMe 1024GB                           | 2         | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 2         | 1.45%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 1.45%   |
| Apple SSD SM0512G 500GB                             | 2         | 1.45%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                | 1         | 0.72%   |
| Yangtze Memory YMTC PC300-1TB-B                     | 1         | 0.72%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                    | 1         | 0.72%   |
| WDC WDS200T1X0E-00AFY0 2TB                          | 1         | 0.72%   |
| WDC WD7500BPKX-75HPJT0 752GB                        | 1         | 0.72%   |
| WDC WD10 JPLX-00MBPT0 1TB                           | 1         | 0.72%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                  | 1         | 0.72%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 0.72%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB                  | 1         | 0.72%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB                | 1         | 0.72%   |
| Unknown MMC Card  64GB                              | 1         | 0.72%   |
| Unknown MMC Card  250GB                             | 1         | 0.72%   |
| Unknown MMC Card  16GB                              | 1         | 0.72%   |
| Unknown MMC Card  128GB                             | 1         | 0.72%   |
| Transcend TS256GMTS800 256GB SSD                    | 1         | 0.72%   |
| Transcend TS256GMTS430S 256GB SSD                   | 1         | 0.72%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 1         | 0.72%   |
| Toshiba XG4 NVMe SSD Controller 512GB               | 1         | 0.72%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 0.72%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.72%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 0.72%   |
| Toshiba KXG6AZNV512G 512GB                          | 1         | 0.72%   |
| Toshiba KXG50ZNV512G NVMe 512GB                     | 1         | 0.72%   |
| SPCC 2.5 SSD 1TB                                    | 1         | 0.72%   |
| Solid State Storage CL4-3D512-Q11 NVMe SSSTC 512GB  | 1         | 0.72%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 0.72%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 1         | 0.72%   |
| SK hynix NVMe SSD Drive 1TB                         | 1         | 0.72%   |
| SK hynix NVMe SSD Drive 1024GB                      | 1         | 0.72%   |
| SK hynix HFM001TD3JX013N 1024GB                     | 1         | 0.72%   |

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
| Samsung Electronics | 13        | 16     | 30.95%  |
| SanDisk             | 4         | 4      | 9.52%   |
| Apple               | 4         | 6      | 9.52%   |
| Kingston            | 3         | 3      | 7.14%   |
| Crucial             | 3         | 4      | 7.14%   |
| Transcend           | 2         | 2      | 4.76%   |
| Micron Technology   | 2         | 2      | 4.76%   |
| WDC                 | 1         | 1      | 2.38%   |
| SPCC                | 1         | 1      | 2.38%   |
| SK hynix            | 1         | 1      | 2.38%   |
| S3+                 | 1         | 1      | 2.38%   |
| PNY                 | 1         | 2      | 2.38%   |
| LITEONIT            | 1         | 1      | 2.38%   |
| INNOVATION IT       | 1         | 1      | 2.38%   |
| Dogfish             | 1         | 1      | 2.38%   |
| Corsair             | 1         | 1      | 2.38%   |
| China               | 1         | 1      | 2.38%   |
| BIWIN               | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 70        | 93     | 56.91%  |
| SSD  | 39        | 49     | 31.71%  |
| HDD  | 10        | 12     | 8.13%   |
| MMC  | 4         | 4      | 3.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 70        | 93     | 59.32%  |
| SATA | 41        | 58     | 34.75%  |
| MMC  | 4         | 4      | 3.39%   |
| SAS  | 3         | 3      | 2.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 41     | 66%     |
| 0.51-1.0   | 16        | 19     | 32%     |
| 1.01-2.0   | 1         | 1      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 34        | 30.36%  |
| 1-20           | 33        | 29.46%  |
| 251-500        | 11        | 9.82%   |
| 101-250        | 11        | 9.82%   |
| 501-1000       | 9         | 8.04%   |
| 1001-2000      | 6         | 5.36%   |
| More than 3000 | 5         | 4.46%   |
| 2001-3000      | 3         | 2.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 37        | 32.46%  |
| Unknown        | 34        | 29.82%  |
| 101-250        | 13        | 11.4%   |
| 21-50          | 10        | 8.77%   |
| 51-100         | 7         | 6.14%   |
| 501-1000       | 6         | 5.26%   |
| 251-500        | 4         | 3.51%   |
| More than 3000 | 1         | 0.88%   |
| 2001-3000      | 1         | 0.88%   |
| 1001-2000      | 1         | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10 JPLX-00MBPT0 1TB                      | 1         | 1      | 16.67%  |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 16.67%  |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 16.67%  |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 16.67%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 16.67%  |
| Corsair Force GS 240GB SSD                     | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 2      | 33.33%  |
| WDC               | 1         | 1      | 16.67%  |
| SK hynix          | 1         | 1      | 16.67%  |
| Micron Technology | 1         | 1      | 16.67%  |
| Corsair           | 1         | 1      | 16.67%  |

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
| HDD  | 3         | 3      | 50%     |
| SSD  | 2         | 2      | 33.33%  |
| NVMe | 1         | 1      | 16.67%  |

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
| Works    | 102       | 137    | 85%     |
| Detected | 11        | 14     | 9.17%   |
| Malfunc  | 6         | 6      | 5%      |
| Failed   | 1         | 1      | 0.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 56        | 40.58%  |
| Samsung Electronics            | 30        | 21.74%  |
| SanDisk                        | 13        | 9.42%   |
| SK hynix                       | 7         | 5.07%   |
| Toshiba America Info Systems   | 5         | 3.62%   |
| Micron Technology              | 5         | 3.62%   |
| Kingston Technology Company    | 5         | 3.62%   |
| AMD                            | 5         | 3.62%   |
| ADATA Technology               | 3         | 2.17%   |
| Yangtze Memory Technologies    | 2         | 1.45%   |
| Micron/Crucial Technology      | 2         | 1.45%   |
| Solid State Storage Technology | 1         | 0.72%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.72%   |
| Marvell Technology Group       | 1         | 0.72%   |
| KIOXIA                         | 1         | 0.72%   |
| Biwin Storage Technology       | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 9.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 7.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 6.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.26%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 3.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 3.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 3.55%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 3.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 2.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 2.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 2.13%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 3         | 2.13%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.13%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 1.42%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.42%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.42%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 1.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.42%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.42%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.42%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 2         | 1.42%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.42%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.42%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 1.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.42%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 1         | 0.71%   |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 0.71%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.71%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.71%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                         | 1         | 0.71%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.71%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.71%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.71%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.71%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 70        | 53.03%  |
| SATA | 52        | 39.39%  |
| RAID | 10        | 7.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 82        | 75.93%  |
| AMD    | 26        | 24.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 3.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz          | 4         | 3.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics     | 4         | 3.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 2.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 3         | 2.78%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 2.78%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 2.78%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 3         | 2.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 1.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 2         | 1.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 1.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 1.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 1.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 2         | 1.85%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 2         | 1.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 2         | 1.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 2         | 1.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 2         | 1.85%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 1.85%   |
| Intel 12th Gen Core i7-1260P               | 2         | 1.85%   |
| Intel 12th Gen Core i5-1240P               | 2         | 1.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 2         | 1.85%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 2         | 1.85%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 1.85%   |
| Intel Xeon E-2276M CPU @ 2.80GHz           | 1         | 0.93%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 0.93%   |
| Intel Pentium Gold 7505 @ 2.00GHz          | 1         | 0.93%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 0.93%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 0.93%   |
| Intel Core i7-7600U CPU @ 2.80GHz          | 1         | 0.93%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz          | 1         | 0.93%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 0.93%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz         | 1         | 0.93%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 0.93%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz         | 1         | 0.93%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz         | 1         | 0.93%   |
| Intel Core i7-4500U CPU @ 1.80GHz          | 1         | 0.93%   |
| Intel Core i7-3667U CPU @ 2.00GHz          | 1         | 0.93%   |
| Intel Core i7-3520M CPU @ 2.90GHz          | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 35        | 32.41%  |
| Other              | 18        | 16.67%  |
| Intel Core i5      | 17        | 15.74%  |
| AMD Ryzen 7        | 14        | 12.96%  |
| AMD Ryzen 9        | 5         | 4.63%   |
| AMD Ryzen 7 PRO    | 5         | 4.63%   |
| Intel Celeron      | 4         | 3.7%    |
| Intel Xeon         | 2         | 1.85%   |
| Intel Core i3      | 2         | 1.85%   |
| AMD Ryzen 5        | 2         | 1.85%   |
| Intel Pentium Gold | 1         | 0.93%   |
| Intel Core m3      | 1         | 0.93%   |
| Intel Core i9      | 1         | 0.93%   |
| Intel Atom         | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 37        | 34.26%  |
| 8      | 28        | 25.93%  |
| 2      | 28        | 25.93%  |
| 12     | 5         | 4.63%   |
| 6      | 5         | 4.63%   |
| 24     | 1         | 0.93%   |
| 16     | 1         | 0.93%   |
| 14     | 1         | 0.93%   |
| 10     | 1         | 0.93%   |
| 1      | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 108       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 102       | 94.44%  |
| 1      | 6         | 5.56%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 107       | 98.17%  |
| 32-bit         | 1         | 0.92%   |
| Unknown        | 1         | 0.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 26.55%  |
| 0x0a50000c | 11        | 9.73%   |
| 0x806ea    | 6         | 5.31%   |
| 0x806c1    | 5         | 4.42%   |
| 0x08600106 | 5         | 4.42%   |
| 0x806e9    | 4         | 3.54%   |
| 0x406e3    | 4         | 3.54%   |
| 0x306c3    | 4         | 3.54%   |
| 0x806ec    | 3         | 2.65%   |
| 0x806eb    | 3         | 2.65%   |
| 0x40661    | 3         | 2.65%   |
| 0x40651    | 3         | 2.65%   |
| 0x306d4    | 3         | 2.65%   |
| 0x306a9    | 3         | 2.65%   |
| 0x0a404102 | 3         | 2.65%   |
| 0x906ed    | 2         | 1.77%   |
| 0x906ea    | 2         | 1.77%   |
| 0x906e9    | 2         | 1.77%   |
| 0x906a3    | 2         | 1.77%   |
| 0x706a8    | 2         | 1.77%   |
| 0x706a1    | 2         | 1.77%   |
| 0x08600104 | 2         | 1.77%   |
| 0x906a4    | 1         | 0.88%   |
| 0x806d1    | 1         | 0.88%   |
| 0x506e3    | 1         | 0.88%   |
| 0x106c2    | 1         | 0.88%   |
| 0x0a704103 | 1         | 0.88%   |
| 0x0a601203 | 1         | 0.88%   |
| 0x0a50000b | 1         | 0.88%   |
| 0x0a404101 | 1         | 0.88%   |
| 0x08108109 | 1         | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 25.93%  |
| Zen 3            | 12        | 11.11%  |
| Haswell          | 11        | 10.19%  |
| Skylake          | 10        | 9.26%   |
| Unknown          | 9         | 8.33%   |
| Zen 2            | 7         | 6.48%   |
| TigerLake        | 7         | 6.48%   |
| Alderlake Hybrid | 7         | 6.48%   |
| IvyBridge        | 6         | 5.56%   |
| Goldmont plus    | 4         | 3.7%    |
| Broadwell        | 3         | 2.78%   |
| Icelake          | 2         | 1.85%   |
| Zen+             | 1         | 0.93%   |
| Bonnell          | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 77        | 52.74%  |
| Nvidia | 37        | 25.34%  |
| AMD    | 32        | 21.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 10        | 6.71%   |
| Intel UHD Graphics 620                                                                | 8         | 5.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 7         | 4.7%    |
| AMD Renoir                                                                            | 7         | 4.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 4.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 3.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 3.36%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 5         | 3.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 3.36%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 2.68%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 2.68%   |
| Intel HD Graphics 620                                                                 | 4         | 2.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 2.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 2.68%   |
| AMD Rembrandt [Radeon 680M]                                                           | 4         | 2.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 2.01%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 2.01%   |
| Intel HD Graphics 5500                                                                | 3         | 2.01%   |
| Intel HD Graphics 530                                                                 | 3         | 2.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 2.01%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 2.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 1.34%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 1.34%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.34%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 1.34%   |
| Intel HD Graphics 630                                                                 | 2         | 1.34%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 1.34%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 2         | 1.34%   |
| AMD Barcelo                                                                           | 2         | 1.34%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.67%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                | 1         | 0.67%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                                      | 1         | 0.67%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 0.67%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.67%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 0.67%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 0.67%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 0.67%   |
| Nvidia GM107 [GeForce 940MX]                                                          | 1         | 0.67%   |
| Nvidia GK208M [GeForce GT 730M]                                                       | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 42.59%  |
| Intel + Nvidia | 25        | 23.15%  |
| 1 x AMD        | 17        | 15.74%  |
| AMD + Nvidia   | 8         | 7.41%   |
| Intel + AMD    | 5         | 4.63%   |
| 1 x Nvidia     | 4         | 3.7%    |
| 2 x AMD        | 2         | 1.85%   |
| 2 x Intel      | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 86        | 78.9%   |
| Proprietary | 21        | 19.27%  |
| Unknown     | 2         | 1.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 62.16%  |
| 0.01-0.5   | 16        | 14.41%  |
| 1.01-2.0   | 12        | 10.81%  |
| 3.01-4.0   | 8         | 7.21%   |
| 0.51-1.0   | 4         | 3.6%    |
| 7.01-8.0   | 1         | 0.9%    |
| 8.01-16.0  | 1         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 22        | 16.79%  |
| BOE                  | 18        | 13.74%  |
| LG Display           | 15        | 11.45%  |
| Samsung Electronics  | 12        | 9.16%   |
| Chimei Innolux       | 12        | 9.16%   |
| Dell                 | 8         | 6.11%   |
| Sharp                | 7         | 5.34%   |
| PANDA                | 5         | 3.82%   |
| CSO                  | 5         | 3.82%   |
| Apple                | 5         | 3.82%   |
| Goldstar             | 3         | 2.29%   |
| Philips              | 2         | 1.53%   |
| Panasonic            | 2         | 1.53%   |
| InfoVision           | 2         | 1.53%   |
| Hewlett-Packard      | 2         | 1.53%   |
| HannStar             | 2         | 1.53%   |
| Toshiba              | 1         | 0.76%   |
| TMX                  | 1         | 0.76%   |
| Lenovo               | 1         | 0.76%   |
| JDI                  | 1         | 0.76%   |
| Eizo                 | 1         | 0.76%   |
| ASUSTek Computer     | 1         | 0.76%   |
| AOC                  | 1         | 0.76%   |
| Ancor Communications | 1         | 0.76%   |
| Acer                 | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 2         | 1.53%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch            | 2         | 1.53%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                      | 2         | 1.53%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch         | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 2         | 1.53%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch         | 2         | 1.53%   |
| Toshiba no-audio-HD TSB8888 1080x1920 1080x1920mm 86.7-inch            | 1         | 0.76%   |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch                | 1         | 0.76%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 1         | 0.76%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 1         | 0.76%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.76%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.76%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch                | 1         | 0.76%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 0.76%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                | 1         | 0.76%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch      | 1         | 0.76%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch      | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch   | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 1020x570mm 46.0-inch | 1         | 0.76%   |
| Samsung Electronics C43J89x SAM0F5B 3840x1200 1050x330mm 43.3-inch     | 1         | 0.76%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch      | 1         | 0.76%   |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 530x300mm 24.0-inch      | 1         | 0.76%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1         | 0.76%   |
| Philips PHL 272P7VU PHL093A 3840x2160 597x336mm 27.0-inch              | 1         | 0.76%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                | 1         | 0.76%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch                | 1         | 0.76%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch                | 1         | 0.76%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 1         | 0.76%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                | 1         | 0.76%   |
| LG Display LCD Monitor LGD06CE 1920x1200 288x180mm 13.4-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD068A 1920x1080 309x174mm 14.0-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 1         | 0.76%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 1         | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 54        | 43.55%  |
| 3840x2160 (4K)     | 15        | 12.1%   |
| 1366x768 (WXGA)    | 13        | 10.48%  |
| 2880x1800          | 9         | 7.26%   |
| 2560x1440 (QHD)    | 9         | 7.26%   |
| 2560x1600          | 6         | 4.84%   |
| 1920x1200 (WUXGA)  | 4         | 3.23%   |
| 1600x900 (HD+)     | 3         | 2.42%   |
| 3440x1440          | 2         | 1.61%   |
| 2256x1504          | 2         | 1.61%   |
| 3840x2400          | 1         | 0.81%   |
| 3840x1200          | 1         | 0.81%   |
| 1920x1280          | 1         | 0.81%   |
| 1680x1050 (WSXGA+) | 1         | 0.81%   |
| 1280x800 (WXGA)    | 1         | 0.81%   |
| 1280x1024 (SXGA)   | 1         | 0.81%   |
| 1024x600           | 1         | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 35        | 27.34%  |
| 14     | 27        | 21.09%  |
| 13     | 20        | 15.63%  |
| 27     | 8         | 6.25%   |
| 12     | 8         | 6.25%   |
| 17     | 6         | 4.69%   |
| 16     | 6         | 4.69%   |
| 24     | 5         | 3.91%   |
| 23     | 3         | 2.34%   |
| 34     | 2         | 1.56%   |
| 31     | 2         | 1.56%   |
| 86     | 1         | 0.78%   |
| 46     | 1         | 0.78%   |
| 43     | 1         | 0.78%   |
| 22     | 1         | 0.78%   |
| 21     | 1         | 0.78%   |
| 10     | 1         | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 75        | 59.06%  |
| 201-300     | 21        | 16.54%  |
| 501-600     | 15        | 11.81%  |
| 351-400     | 6         | 4.72%   |
| 601-700     | 3         | 2.36%   |
| 1001-1500   | 3         | 2.36%   |
| 701-800     | 2         | 1.57%   |
| 401-500     | 2         | 1.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 82        | 72.57%  |
| 16/10 | 23        | 20.35%  |
| 3/2   | 3         | 2.65%   |
| 21/9  | 2         | 1.77%   |
| 5/4   | 1         | 0.88%   |
| 3.20  | 1         | 0.88%   |
| 0.56  | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 39        | 30.47%  |
| 101-110        | 35        | 27.34%  |
| 201-250        | 9         | 7.03%   |
| 71-80          | 8         | 6.25%   |
| 61-70          | 8         | 6.25%   |
| 301-350        | 8         | 6.25%   |
| 121-130        | 6         | 4.69%   |
| 111-120        | 5         | 3.91%   |
| 351-500        | 4         | 3.13%   |
| 501-1000       | 2         | 1.56%   |
| More than 1000 | 1         | 0.78%   |
| 41-50          | 1         | 0.78%   |
| 251-300        | 1         | 0.78%   |
| 141-150        | 1         | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 50        | 40.98%  |
| 161-240       | 29        | 23.77%  |
| 101-120       | 16        | 13.11%  |
| More than 240 | 13        | 10.66%  |
| 51-100        | 12        | 9.84%   |
| 1-50          | 2         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 83        | 73.45%  |
| 2     | 21        | 18.58%  |
| 0     | 5         | 4.42%   |
| 3     | 4         | 3.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 80        | 50%     |
| Realtek Semiconductor             | 46        | 28.75%  |
| Qualcomm Atheros                  | 9         | 5.63%   |
| MediaTek                          | 8         | 5%      |
| Broadcom                          | 6         | 3.75%   |
| Qualcomm                          | 2         | 1.25%   |
| Lenovo                            | 2         | 1.25%   |
| Xiaomi                            | 1         | 0.63%   |
| QinHeng Electronics               | 1         | 0.63%   |
| Microsoft                         | 1         | 0.63%   |
| Fibocom                           | 1         | 0.63%   |
| Ericsson Business Mobile Networks | 1         | 0.63%   |
| Edimax Technology                 | 1         | 0.63%   |
| D-Link                            | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 14.07%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 8.04%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 7.04%   |
| Intel Wireless 8265 / 8275                                        | 7         | 3.52%   |
| Intel Wireless 8260                                               | 6         | 3.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 3.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.51%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 2.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.51%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 2.01%   |
| Intel Wireless 7260                                               | 4         | 2.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 2.01%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.51%   |
| Intel Wireless-AC 9260                                            | 3         | 1.51%   |
| Intel Wireless 7265                                               | 3         | 1.51%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.51%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.01%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.01%   |
| Intel Wireless 3165                                               | 2         | 1.01%   |
| Intel Wireless 3160                                               | 2         | 1.01%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.01%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 1.01%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.5%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.5%    |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.5%    |
| Qualcomm QCA6390 Wireless Network Adapter                         | 1         | 0.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 80        | 72.07%  |
| Qualcomm Atheros      | 8         | 7.21%   |
| MediaTek              | 8         | 7.21%   |
| Broadcom              | 6         | 5.41%   |
| Realtek Semiconductor | 3         | 2.7%    |
| Qualcomm              | 2         | 1.8%    |
| Microsoft             | 1         | 0.9%    |
| Fibocom               | 1         | 0.9%    |
| Edimax Technology     | 1         | 0.9%    |
| D-Link                | 1         | 0.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 14        | 12.61%  |
| Intel Wireless 8265 / 8275                                     | 7         | 6.31%   |
| Intel Wireless 8260                                            | 6         | 5.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 5.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 4.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 4.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 3.6%    |
| Intel Wireless 7260                                            | 4         | 3.6%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 3.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 3.6%    |
| Intel Wireless-AC 9260                                         | 3         | 2.7%    |
| Intel Wireless 7265                                            | 3         | 2.7%    |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.8%    |
| Intel Wireless 3165                                            | 2         | 1.8%    |
| Intel Wireless 3160                                            | 2         | 1.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.8%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 1.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 1.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.9%    |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.9%    |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.9%    |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 0.9%    |
| Intel Raptor Lake PCH CNVi WiFi                                | 1         | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.9%    |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.9%    |
| Intel Centrino Advanced-N 6235                                 | 1         | 0.9%    |
| Intel 700 Series Chipset Family Wi-Fi                          | 1         | 0.9%    |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 0.9%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 0.9%    |
| D-Link 802.11ac NIC                                            | 1         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 44        | 55%     |
| Intel                 | 29        | 36.25%  |
| Qualcomm Atheros      | 2         | 2.5%    |
| Lenovo                | 2         | 2.5%    |
| Broadcom              | 2         | 2.5%    |
| Xiaomi                | 1         | 1.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 32.56%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 18.6%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 5.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.81%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 4.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 3.49%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.33%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.16%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.16%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.16%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.16%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.16%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.16%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.16%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.16%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.16%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.16%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.16%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 107       | 57.22%  |
| Ethernet | 78        | 41.71%  |
| Modem    | 2         | 1.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 84.3%   |
| Ethernet | 19        | 15.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 63        | 58.33%  |
| 1     | 43        | 39.81%  |
| 3     | 2         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 84        | 77.06%  |
| Yes  | 25        | 22.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 70.3%   |
| Apple                           | 5         | 4.95%   |
| Qualcomm Atheros Communications | 4         | 3.96%   |
| MediaTek                        | 4         | 3.96%   |
| IMC Networks                    | 4         | 3.96%   |
| Broadcom                        | 3         | 2.97%   |
| Realtek Semiconductor           | 2         | 1.98%   |
| Lite-On Technology              | 2         | 1.98%   |
| Foxconn / Hon Hai               | 2         | 1.98%   |
| USI                             | 1         | 0.99%   |
| Realtek                         | 1         | 0.99%   |
| Integrated System Solution      | 1         | 0.99%   |
| ASUSTek Computer                | 1         | 0.99%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 21        | 20.79%  |
| Intel AX200 Bluetooth                          | 14        | 13.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 10        | 9.9%    |
| Intel Bluetooth Device                         | 7         | 6.93%   |
| Intel AX201 Bluetooth                          | 7         | 6.93%   |
| Intel AX210 Bluetooth                          | 6         | 5.94%   |
| MediaTek Wireless_Device                       | 4         | 3.96%   |
| Apple Bluetooth Host Controller                | 4         | 3.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 3         | 2.97%   |
| Realtek Bluetooth Radio                        | 2         | 1.98%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 1.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 2         | 1.98%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 1.98%   |
| IMC Networks Wireless_Device                   | 2         | 1.98%   |
| Broadcom HP Portable SoftSailing               | 2         | 1.98%   |
| USI Bluetooth Device                           | 1         | 0.99%   |
| Realtek Bluetooth Radio                        | 1         | 0.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 0.99%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 0.99%   |
| Integrated System Solution Bluetooth Device    | 1         | 0.99%   |
| IMC Networks Bluetooth Device                  | 1         | 0.99%   |
| IMC Networks BCM20702A0                        | 1         | 0.99%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 0.99%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 1         | 0.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 0.99%   |
| ASUS Broadcom Bluetooth 2.1                    | 1         | 0.99%   |
| Apple Bluetooth USB Host Controller            | 1         | 0.99%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 83        | 53.55%  |
| AMD                       | 29        | 18.71%  |
| Nvidia                    | 20        | 12.9%   |
| Lenovo                    | 4         | 2.58%   |
| C-Media Electronics       | 4         | 2.58%   |
| Realtek Semiconductor     | 3         | 1.94%   |
| Synaptics                 | 2         | 1.29%   |
| Trust                     | 1         | 0.65%   |
| Sennheiser Communications | 1         | 0.65%   |
| Satechi                   | 1         | 0.65%   |
| Logitech                  | 1         | 0.65%   |
| Kingston Technology       | 1         | 0.65%   |
| JMTek                     | 1         | 0.65%   |
| Focusrite-Novation        | 1         | 0.65%   |
| Creative Technology       | 1         | 0.65%   |
| Corsair                   | 1         | 0.65%   |
| (LCS) USB Audio Device    | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 26        | 13.61%  |
| Intel Sunrise Point-LP HD Audio                                         | 20        | 10.47%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 17        | 8.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 8         | 4.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 7         | 3.66%   |
| Intel Cannon Lake PCH cAVS                                              | 6         | 3.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 6         | 3.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 6         | 3.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 5         | 2.62%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 5         | 2.62%   |
| Nvidia Audio device                                                     | 4         | 2.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 4         | 2.09%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 2.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 4         | 2.09%   |
| Realtek Semiconductor USB Audio                                         | 3         | 1.57%   |
| Nvidia GA106 High Definition Audio Controller                           | 3         | 1.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 3         | 1.57%   |
| Intel Haswell-ULT HD Audio Controller                                   | 3         | 1.57%   |
| Intel Broadwell-U Audio Controller                                      | 3         | 1.57%   |
| Intel 8 Series HD Audio Controller                                      | 3         | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 3         | 1.57%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                         | 2         | 1.05%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 2         | 1.05%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 1.05%   |
| Nvidia GK106 HDMI Audio Controller                                      | 2         | 1.05%   |
| Nvidia GA104 High Definition Audio Controller                           | 2         | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                            | 2         | 1.05%   |
| Intel CM238 HD Audio Controller                                         | 2         | 1.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 1.05%   |
| Trust USB microphone                                                    | 1         | 0.52%   |
| Sennheiser Communications Headset [PC 8]                                | 1         | 0.52%   |
| Satechi Audio & PD Adapter                                              | 1         | 0.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 1         | 0.52%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.52%   |
| Nvidia TU104 HD Audio Controller                                        | 1         | 0.52%   |
| Logitech Blue Microphones                                               | 1         | 0.52%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                               | 1         | 0.52%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                            | 1         | 0.52%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                            | 1         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 38        | 29.01%  |
| Micron Technology            | 23        | 17.56%  |
| SK hynix                     | 22        | 16.79%  |
| Kingston                     | 11        | 8.4%    |
| Crucial                      | 11        | 8.4%    |
| Unknown                      | 4         | 3.05%   |
| Unknown (ABCD)               | 3         | 2.29%   |
| Team                         | 3         | 2.29%   |
| Ramaxel Technology           | 3         | 2.29%   |
| A-DATA Technology            | 2         | 1.53%   |
| Unknown                      | 2         | 1.53%   |
| Smart Brazil                 | 1         | 0.76%   |
| Patriot Memory (PDP Systems) | 1         | 0.76%   |
| Patriot                      | 1         | 0.76%   |
| GOODRAM                      | 1         | 0.76%   |
| G.Skill                      | 1         | 0.76%   |
| Corsair                      | 1         | 0.76%   |
| Avant                        | 1         | 0.76%   |
| Apacer                       | 1         | 0.76%   |
| AMD                          | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 2.16%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 2.16%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 2.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.16%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 1.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.44%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.44%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.44%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.44%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.44%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 2         | 1.44%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.44%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s           | 2         | 1.44%   |
| Unknown                                                          | 2         | 1.44%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.72%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.72%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.72%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.72%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.72%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.72%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.72%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.72%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.72%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.72%   |
| SK hynix RAM HMT451S6AFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.72%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.72%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.72%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.72%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 0.72%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.72%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.72%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.72%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 0.72%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 1         | 0.72%   |
| SK hynix RAM H9JCNNNBK3MLYR-N6E 1GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.72%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 57        | 53.77%  |
| DDR3   | 20        | 18.87%  |
| LPDDR4 | 12        | 11.32%  |
| LPDDR5 | 9         | 8.49%   |
| LPDDR3 | 4         | 3.77%   |
| DDR5   | 3         | 2.83%   |
| SDRAM  | 1         | 0.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 78.18%  |
| Row Of Chips | 20        | 18.18%  |
| Chip         | 3         | 2.73%   |
| Unknown      | 1         | 0.91%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 53        | 44.17%  |
| 16384 | 26        | 21.67%  |
| 4096  | 25        | 20.83%  |
| 32768 | 12        | 10%     |
| 2048  | 3         | 2.5%    |
| 1024  | 1         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 25        | 21.93%  |
| 2667    | 24        | 21.05%  |
| 1600    | 19        | 16.67%  |
| 2400    | 10        | 8.77%   |
| 6400    | 9         | 7.89%   |
| 2133    | 9         | 7.89%   |
| 4267    | 6         | 5.26%   |
| 4266    | 3         | 2.63%   |
| 3266    | 3         | 2.63%   |
| 5600    | 2         | 1.75%   |
| 1867    | 2         | 1.75%   |
| 4800    | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

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
| Chicony Electronics                    | 23        | 23.47%  |
| IMC Networks                           | 15        | 15.31%  |
| Microdia                               | 14        | 14.29%  |
| Realtek Semiconductor                  | 8         | 8.16%   |
| Bison Electronics                      | 7         | 7.14%   |
| Sunplus Innovation Technology          | 6         | 6.12%   |
| Logitech                               | 4         | 4.08%   |
| Acer                                   | 4         | 4.08%   |
| Lite-On Technology                     | 3         | 3.06%   |
| Syntek                                 | 2         | 2.04%   |
| Quanta                                 | 2         | 2.04%   |
| Primax Electronics                     | 2         | 2.04%   |
| Alcor Micro                            | 2         | 2.04%   |
| webcamvendor                           | 1         | 1.02%   |
| Sonix Technology                       | 1         | 1.02%   |
| Samsung Electronics                    | 1         | 1.02%   |
| Luxvisions Innotech Limited            | 1         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.02%   |
| Apple                                  | 1         | 1.02%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 15        | 15%     |
| Microdia Integrated_Webcam_HD                     | 7         | 7%      |
| IMC Networks USB2.0 HD UVC WebCam                 | 6         | 6%      |
| IMC Networks Integrated Camera                    | 6         | 6%      |
| Chicony HP HD Camera                              | 4         | 4%      |
| Sunplus Integrated_Webcam_FHD                     | 3         | 3%      |
| Logitech HD Pro Webcam C920                       | 3         | 3%      |
| Bison Integrated Camera                           | 3         | 3%      |
| Syntek Integrated Camera                          | 2         | 2%      |
| Sunplus Integrated_Webcam_HD                      | 2         | 2%      |
| Realtek Laptop Camera                             | 2         | 2%      |
| Realtek Integrated_Webcam_HD                      | 2         | 2%      |
| Primax HP HD Webcam [Fixed]                       | 2         | 2%      |
| Microdia Webcam Vitade AF                         | 2         | 2%      |
| Microdia Integrated Webcam                        | 2         | 2%      |
| Lite-On Integrated Camera                         | 2         | 2%      |
| Bison HD Webcam                                   | 2         | 2%      |
| webcamvendor webcamproduct                        | 1         | 1%      |
| Sunplus Laptop Integrated Webcam FHD              | 1         | 1%      |
| Sonix USB2.0 FHD UVC WebCam                       | 1         | 1%      |
| Samsung Galaxy series, misc. (MTP mode)           | 1         | 1%      |
| Realtek USB Camera                                | 1         | 1%      |
| Realtek TV Camera                                 | 1         | 1%      |
| Realtek Lenovo EasyCamera                         | 1         | 1%      |
| Realtek Integrated Webcam                         | 1         | 1%      |
| Realtek HD WebCam                                 | 1         | 1%      |
| Quanta VGA WebCam                                 | 1         | 1%      |
| Quanta HD WebCam                                  | 1         | 1%      |
| Microdia USB 2.0 Camera                           | 1         | 1%      |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 1%      |
| Microdia HP Integrated Webcam                     | 1         | 1%      |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1%      |
| Logitech Webcam C310                              | 1         | 1%      |
| Lite-On HP HD Camera                              | 1         | 1%      |
| IMC Networks XHC Camera                           | 1         | 1%      |
| IMC Networks USB2.0 UVC 1.3M WebCam               | 1         | 1%      |
| IMC Networks ov9734_azurewave_camera              | 1         | 1%      |
| Chicony USB2.0 Camera                             | 1         | 1%      |
| Chicony Integrated IR Camera                      | 1         | 1%      |
| Chicony Integrated Camera [ThinkPad]              | 1         | 1%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 42.86%  |
| Synaptics                  | 11        | 39.29%  |
| Shenzhen Goodix Technology | 4         | 14.29%  |
| Focal-systems.Corp         | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 5         | 17.86%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 10.71%  |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 3         | 10.71%  |
| Validity Sensors VFS491                                  | 2         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 7.14%   |
| Validity Sensors Synaptics WBDI                          | 2         | 7.14%   |
| Synaptics UWP WBDI Device                                | 2         | 7.14%   |
| Shenzhen Goodix  Fingerprint Device                      | 2         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 7.14%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor        | 1         | 3.57%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 3.57%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 3.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 12        | 57.14%  |
| Broadcom    | 5         | 23.81%  |
| Yubico.com  | 3         | 14.29%  |
| Upek        | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 12        | 57.14%  |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 9.52%   |
| Broadcom 5880                                              | 2         | 9.52%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 4.76%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.76%   |
| Broadcom 58200                                             | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 48        | 42.86%  |
| 1     | 38        | 33.93%  |
| 2     | 23        | 20.54%  |
| 4     | 2         | 1.79%   |
| 3     | 1         | 0.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 26        | 28.57%  |
| Multimedia controller    | 17        | 18.68%  |
| Chipcard                 | 16        | 17.58%  |
| Graphics card            | 15        | 16.48%  |
| Camera                   | 4         | 4.4%    |
| Net/wireless             | 3         | 3.3%    |
| Bluetooth                | 3         | 3.3%    |
| Modem                    | 2         | 2.2%    |
| Card reader              | 2         | 2.2%    |
| Network                  | 1         | 1.1%    |
| Firewire controller      | 1         | 1.1%    |
| Communication controller | 1         | 1.1%    |

