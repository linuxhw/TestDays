NixOS - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for NixOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NixOS/Desktop/README.md) and [notebooks](/Dist/NixOS/Notebook/README.md).

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

Total: 269

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8470p             | Notebook    | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| AZW           | EQ                          | Desktop     | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | Notebook    | [c384115725](https://linux-hardware.org/?probe=c384115725) | Aug 05, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [13c8b276bb](https://linux-hardware.org/?probe=13c8b276bb) | Aug 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1abcf2ad6f](https://linux-hardware.org/?probe=1abcf2ad6f) | Aug 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| Teclast       | F5                          | Convertible | [76fcc31a43](https://linux-hardware.org/?probe=76fcc31a43) | Aug 01, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e452f85fb8](https://linux-hardware.org/?probe=e452f85fb8) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| System76      | Pangolin                    | Notebook    | [3b37a9bedb](https://linux-hardware.org/?probe=3b37a9bedb) | Jul 29, 2023 |
| Alienware     | 17                          | Notebook    | [25f67e59b8](https://linux-hardware.org/?probe=25f67e59b8) | Jul 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
| HP            | 1998                        | Desktop     | [ef5201611b](https://linux-hardware.org/?probe=ef5201611b) | Jul 24, 2023 |
| HP            | 1998                        | Desktop     | [5a95ac128d](https://linux-hardware.org/?probe=5a95ac128d) | Jul 24, 2023 |
| AZW           | EQ                          | Desktop     | [e065c16f2c](https://linux-hardware.org/?probe=e065c16f2c) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [46a76eeb81](https://linux-hardware.org/?probe=46a76eeb81) | Jul 23, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8d48a50003](https://linux-hardware.org/?probe=8d48a50003) | Jul 22, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c29abaca55](https://linux-hardware.org/?probe=c29abaca55) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [59a0d6a7bb](https://linux-hardware.org/?probe=59a0d6a7bb) | Jul 19, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [1e8eeb8513](https://linux-hardware.org/?probe=1e8eeb8513) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [8efa3cf99d](https://linux-hardware.org/?probe=8efa3cf99d) | Jul 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [9bb1b8fbca](https://linux-hardware.org/?probe=9bb1b8fbca) | Jul 12, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d7afc91d12](https://linux-hardware.org/?probe=d7afc91d12) | Jul 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a2dc9efa21](https://linux-hardware.org/?probe=a2dc9efa21) | Jul 06, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4d377fc8b8](https://linux-hardware.org/?probe=4d377fc8b8) | Jul 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [fd56f44c38](https://linux-hardware.org/?probe=fd56f44c38) | Jun 29, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [4c4d870bdb](https://linux-hardware.org/?probe=4c4d870bdb) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [cf6a7757d5](https://linux-hardware.org/?probe=cf6a7757d5) | Jun 26, 2023 |
| Microtech     | CoreBook Lite               | Notebook    | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [2812cf43d0](https://linux-hardware.org/?probe=2812cf43d0) | Jun 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| MECHREVO      | WUJIE 14                    | Notebook    | [a55e31b287](https://linux-hardware.org/?probe=a55e31b287) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | Notebook    | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85902981fd](https://linux-hardware.org/?probe=85902981fd) | Jun 11, 2023 |
| MACHENIKE     | F117-7P                     | Notebook    | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c9c4e5ddb5](https://linux-hardware.org/?probe=c9c4e5ddb5) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [4396db2f33](https://linux-hardware.org/?probe=4396db2f33) | May 22, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [aefc60eaea](https://linux-hardware.org/?probe=aefc60eaea) | May 11, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [c40c2cb964](https://linux-hardware.org/?probe=c40c2cb964) | May 10, 2023 |
| Acer          | Spin SP514-51N              | Convertible | [6b23655b4b](https://linux-hardware.org/?probe=6b23655b4b) | May 10, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [6ee65c19d2](https://linux-hardware.org/?probe=6ee65c19d2) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [493bc0b894](https://linux-hardware.org/?probe=493bc0b894) | Apr 29, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| Dell          | 0KFKMF A00                  | All in one  | [cbae954ecc](https://linux-hardware.org/?probe=cbae954ecc) | Apr 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [2063d4a9fc](https://linux-hardware.org/?probe=2063d4a9fc) | Apr 27, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [7fd17e2245](https://linux-hardware.org/?probe=7fd17e2245) | Apr 22, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | Notebook    | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [6ce8b7fb26](https://linux-hardware.org/?probe=6ce8b7fb26) | Apr 11, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [f53ad14ea5](https://linux-hardware.org/?probe=f53ad14ea5) | Mar 13, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [3326423f04](https://linux-hardware.org/?probe=3326423f04) | Mar 06, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [8bf9dd7b83](https://linux-hardware.org/?probe=8bf9dd7b83) | Mar 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c4f08a9fc3](https://linux-hardware.org/?probe=c4f08a9fc3) | Mar 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c4d51ca1b8](https://linux-hardware.org/?probe=c4d51ca1b8) | Mar 04, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [4f3c01941d](https://linux-hardware.org/?probe=4f3c01941d) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [616e689b13](https://linux-hardware.org/?probe=616e689b13) | Feb 19, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [5f59be48e1](https://linux-hardware.org/?probe=5f59be48e1) | Feb 16, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [68effccd60](https://linux-hardware.org/?probe=68effccd60) | Feb 16, 2023 |
| Teclast       | F5                          | Convertible | [e62bdaaa3b](https://linux-hardware.org/?probe=e62bdaaa3b) | Feb 13, 2023 |
| Teclast       | F5                          | Convertible | [30e30a5c3e](https://linux-hardware.org/?probe=30e30a5c3e) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8ac9c4b4ef](https://linux-hardware.org/?probe=8ac9c4b4ef) | Feb 09, 2023 |
| Acer          | Switch SW713-51GNP          | Tablet      | [46ecb88f1d](https://linux-hardware.org/?probe=46ecb88f1d) | Feb 08, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [eb768bf205](https://linux-hardware.org/?probe=eb768bf205) | Feb 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [75a3416ebc](https://linux-hardware.org/?probe=75a3416ebc) | Jan 31, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | Notebook    | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| Blackview     | AceBook 1                   | Notebook    | [ea4db42aa8](https://linux-hardware.org/?probe=ea4db42aa8) | Jan 19, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [b795f7c940](https://linux-hardware.org/?probe=b795f7c940) | Jan 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [0e4ba05b0f](https://linux-hardware.org/?probe=0e4ba05b0f) | Jan 15, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [226b8e5ff8](https://linux-hardware.org/?probe=226b8e5ff8) | Jan 15, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b99e4815bc](https://linux-hardware.org/?probe=b99e4815bc) | Jan 10, 2023 |
| Dell          | Latitude 7420               | Notebook    | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | Notebook    | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b721a47fa4](https://linux-hardware.org/?probe=b721a47fa4) | Jan 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d5df950832](https://linux-hardware.org/?probe=d5df950832) | Jan 03, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6a53c626dd](https://linux-hardware.org/?probe=6a53c626dd) | Jan 02, 2023 |
| Dell          | Precision M4800             | Notebook    | [505f1b47dc](https://linux-hardware.org/?probe=505f1b47dc) | Dec 30, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| Dell          | Inspiron 7586               | Convertible | [d670af270f](https://linux-hardware.org/?probe=d670af270f) | Dec 28, 2022 |
| GPD           | WIN2                        | Notebook    | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf62b1c520](https://linux-hardware.org/?probe=cf62b1c520) | Dec 20, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ee5f96d645](https://linux-hardware.org/?probe=ee5f96d645) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3c18fca709](https://linux-hardware.org/?probe=3c18fca709) | Dec 09, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [3dfa1ba4b1](https://linux-hardware.org/?probe=3dfa1ba4b1) | Dec 09, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [110e3eab7f](https://linux-hardware.org/?probe=110e3eab7f) | Dec 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [f698b715e4](https://linux-hardware.org/?probe=f698b715e4) | Nov 30, 2022 |
| Dell          | Inspiron 7586               | Convertible | [91dcb3265a](https://linux-hardware.org/?probe=91dcb3265a) | Nov 24, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [b79f103dd5](https://linux-hardware.org/?probe=b79f103dd5) | Nov 24, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [44a3785f1f](https://linux-hardware.org/?probe=44a3785f1f) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [0c889920b5](https://linux-hardware.org/?probe=0c889920b5) | Nov 12, 2022 |
| Dell          | Latitude E5540              | Notebook    | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [b60f8a187c](https://linux-hardware.org/?probe=b60f8a187c) | Nov 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [fce691523b](https://linux-hardware.org/?probe=fce691523b) | Oct 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | Notebook    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d79322ca4a](https://linux-hardware.org/?probe=d79322ca4a) | Oct 19, 2022 |
| Dell          | Precision 5760              | Notebook    | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa5ea0c17c](https://linux-hardware.org/?probe=aa5ea0c17c) | Oct 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ae775f1f89](https://linux-hardware.org/?probe=ae775f1f89) | Oct 13, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3a409e83a0](https://linux-hardware.org/?probe=3a409e83a0) | Oct 07, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [5eb1758869](https://linux-hardware.org/?probe=5eb1758869) | Oct 07, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8e301a5e4e](https://linux-hardware.org/?probe=8e301a5e4e) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3f823868fd](https://linux-hardware.org/?probe=3f823868fd) | Sep 15, 2022 |
| Dell          | Precision M4800             | Notebook    | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [ad69daf392](https://linux-hardware.org/?probe=ad69daf392) | Sep 11, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [a02c8258ba](https://linux-hardware.org/?probe=a02c8258ba) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7986ddc1d9](https://linux-hardware.org/?probe=7986ddc1d9) | Sep 11, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [ce872c873e](https://linux-hardware.org/?probe=ce872c873e) | Aug 24, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | Notebook    | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [982df0dba9](https://linux-hardware.org/?probe=982df0dba9) | Jun 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B+     | Soc         | [2911b2782c](https://linux-hardware.org/?probe=2911b2782c) | Jun 21, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6d5fdb800a](https://linux-hardware.org/?probe=6d5fdb800a) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d26f08ea88](https://linux-hardware.org/?probe=d26f08ea88) | Jun 12, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0123caa2f3](https://linux-hardware.org/?probe=0123caa2f3) | Jun 11, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | Notebook    | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | Notebook    | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [96b24b0640](https://linux-hardware.org/?probe=96b24b0640) | May 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | Notebook    | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | Notebook    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| Supermicro    | X8DT6                       | Server      | [0fd3b261c7](https://linux-hardware.org/?probe=0fd3b261c7) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| ASUSTek       | P8Q77-M                     | Desktop     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| GPD           | MicroPC                     | Notebook    | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | Notebook    | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | Notebook    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | Notebook    | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| Dell          | Latitude 7420               | Notebook    | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [e5dc04e6a5](https://linux-hardware.org/?probe=e5dc04e6a5) | Dec 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| Teclast       | F5                          | Convertible | [0854310843](https://linux-hardware.org/?probe=0854310843) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | Notebook    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [66d71367c1](https://linux-hardware.org/?probe=66d71367c1) | Aug 24, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bd919b4bd6](https://linux-hardware.org/?probe=bd919b4bd6) | Aug 22, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Inspiron 7391 2n1           | Convertible | [f632a64d73](https://linux-hardware.org/?probe=f632a64d73) | Jul 22, 2021 |
| Dell          | Latitude 7420               | Notebook    | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | Notebook    | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| ASUSTek       | Pro WS W480-ACE             | Desktop     | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| Lenovo        | ThinkPad T580 20L90024PB    | Notebook    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP            | 8055                        | Desktop     | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP            | 8055                        | Desktop     | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |
| Acer          | Aspire E5-576G              | Notebook    | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | Notebook    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| NixOS 22.11                      | 53        | 25.48%  |
| NixOS 23.05                      | 48        | 23.08%  |
| NixOS 22.05                      | 37        | 17.79%  |
| NixOS 21.11                      | 18        | 8.65%   |
| NixOS 23.11                      | 17        | 8.17%   |
| NixOS                            | 5         | 2.4%    |
| NixOS 21.05pre-git               | 2         | 0.96%   |
| NixOS 20.09pre-git               | 2         | 0.96%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.48%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.48%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.48%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.48%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.48%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.48%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.48%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.48%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.48%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.48%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.48%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.48%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.48%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.48%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.48%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.48%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.48%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.48%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.48%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.48%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.48%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.48%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.48%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.48%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.48%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 185       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Computers | Percent |
|-------------|-----------|---------|
| 5.15.74     | 5         | 2.24%   |
| 6.4.0       | 4         | 1.79%   |
| 6.3.8       | 4         | 1.79%   |
| 6.3.3       | 4         | 1.79%   |
| 5.15.86     | 4         | 1.79%   |
| 5.15.43     | 4         | 1.79%   |
| 6.3.1       | 3         | 1.35%   |
| 6.2.0-rc6   | 3         | 1.35%   |
| 6.1.38      | 3         | 1.35%   |
| 6.1.35      | 3         | 1.35%   |
| 6.1.0       | 3         | 1.35%   |
| 6.0.11      | 3         | 1.35%   |
| 6.0.10      | 3         | 1.35%   |
| 5.15.82     | 3         | 1.35%   |
| 5.15.72     | 3         | 1.35%   |
| 5.15.68     | 3         | 1.35%   |
| 5.15.47     | 3         | 1.35%   |
| 5.15.26     | 3         | 1.35%   |
| 6.4.7       | 2         | 0.9%    |
| 6.4.6       | 2         | 0.9%    |
| 6.1.41      | 2         | 0.9%    |
| 6.1.39      | 2         | 0.9%    |
| 6.1.37      | 2         | 0.9%    |
| 6.1.34      | 2         | 0.9%    |
| 6.1.31      | 2         | 0.9%    |
| 6.1.27      | 2         | 0.9%    |
| 6.1.24      | 2         | 0.9%    |
| 6.1.1       | 2         | 0.9%    |
| 5.8.1-zen1  | 2         | 0.9%    |
| 5.19.14     | 2         | 0.9%    |
| 5.18.19     | 2         | 0.9%    |
| 5.17.1      | 2         | 0.9%    |
| 5.16.8-zen1 | 2         | 0.9%    |
| 5.16.15     | 2         | 0.9%    |
| 5.15.96     | 2         | 0.9%    |
| 5.15.92     | 2         | 0.9%    |
| 5.15.90     | 2         | 0.9%    |
| 5.15.85     | 2         | 0.9%    |
| 5.15.64     | 2         | 0.9%    |
| 5.15.32     | 2         | 0.9%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.0   | 5         | 2.24%   |
| 5.15.74 | 5         | 2.24%   |
| 6.3.8   | 4         | 1.79%   |
| 6.3.3   | 4         | 1.79%   |
| 6.2.0   | 4         | 1.79%   |
| 6.1.0   | 4         | 1.79%   |
| 6.0.10  | 4         | 1.79%   |
| 5.15.86 | 4         | 1.79%   |
| 5.15.43 | 4         | 1.79%   |
| 6.3.1   | 3         | 1.35%   |
| 6.1.38  | 3         | 1.35%   |
| 6.1.35  | 3         | 1.35%   |
| 6.1.31  | 3         | 1.35%   |
| 6.0.11  | 3         | 1.35%   |
| 5.15.82 | 3         | 1.35%   |
| 5.15.72 | 3         | 1.35%   |
| 5.15.68 | 3         | 1.35%   |
| 5.15.47 | 3         | 1.35%   |
| 5.15.26 | 3         | 1.35%   |
| 6.4.7   | 2         | 0.9%    |
| 6.4.6   | 2         | 0.9%    |
| 6.4.4   | 2         | 0.9%    |
| 6.2.9   | 2         | 0.9%    |
| 6.2.11  | 2         | 0.9%    |
| 6.1.41  | 2         | 0.9%    |
| 6.1.39  | 2         | 0.9%    |
| 6.1.37  | 2         | 0.9%    |
| 6.1.34  | 2         | 0.9%    |
| 6.1.27  | 2         | 0.9%    |
| 6.1.24  | 2         | 0.9%    |
| 6.1.1   | 2         | 0.9%    |
| 6.0.2   | 2         | 0.9%    |
| 5.8.1   | 2         | 0.9%    |
| 5.19.14 | 2         | 0.9%    |
| 5.18.19 | 2         | 0.9%    |
| 5.17.1  | 2         | 0.9%    |
| 5.16.8  | 2         | 0.9%    |
| 5.16.15 | 2         | 0.9%    |
| 5.15.96 | 2         | 0.9%    |
| 5.15.92 | 2         | 0.9%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 61        | 28.77%  |
| 6.1     | 35        | 16.51%  |
| 5.10    | 14        | 6.6%    |
| 6.3     | 13        | 6.13%   |
| 6.2     | 13        | 6.13%   |
| 6.0     | 13        | 6.13%   |
| 6.4     | 11        | 5.19%   |
| 5.16    | 8         | 3.77%   |
| 5.4     | 7         | 3.3%    |
| 5.19    | 7         | 3.3%    |
| 5.8     | 6         | 2.83%   |
| 5.18    | 5         | 2.36%   |
| 5.13    | 4         | 1.89%   |
| 5.7     | 3         | 1.42%   |
| 5.17    | 3         | 1.42%   |
| 5.12    | 3         | 1.42%   |
| 5.14    | 2         | 0.94%   |
| 5.11    | 2         | 0.94%   |
| 4.19    | 2         | 0.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 179       | 96.76%  |
| aarch64 | 5         | 2.7%    |
| i686    | 1         | 0.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 92        | 47.67%  |
| GNOME        | 25        | 12.95%  |
| sway         | 19        | 9.84%   |
| KDE5         | 17        | 8.81%   |
| Hyprland     | 10        | 5.18%   |
| XFCE         | 8         | 4.15%   |
| none+i3      | 6         | 3.11%   |
| KDE          | 5         | 2.59%   |
| none+awesome | 3         | 1.55%   |
| X-Generic    | 2         | 1.04%   |
| none+xmonad  | 2         | 1.04%   |
| xsession     | 1         | 0.52%   |
| X-Cinnamon   | 1         | 0.52%   |
| none+bspwm   | 1         | 0.52%   |
| MATE         | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 88        | 45.36%  |
| Wayland | 52        | 26.8%   |
| X11     | 40        | 20.62%  |
| Tty     | 14        | 7.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 108       | 57.45%  |
| GDM     | 29        | 15.43%  |
| LightDM | 26        | 13.83%  |
| SDDM    | 25        | 13.3%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 90        | 48.13%  |
| Unknown    | 59        | 31.55%  |
| en_GB      | 8         | 4.28%   |
| en_DK      | 4         | 2.14%   |
| en_AU      | 4         | 2.14%   |
| de_DE      | 4         | 2.14%   |
| ru_RU      | 3         | 1.6%    |
| fr_FR      | 3         | 1.6%    |
| it_IT      | 2         | 1.07%   |
| en_CA      | 2         | 1.07%   |
| de_CH      | 2         | 1.07%   |
| ro_RO      | 1         | 0.53%   |
| pt_BR      | 1         | 0.53%   |
| lv_LV      | 1         | 0.53%   |
| es_MX      | 1         | 0.53%   |
| en_IN      | 1         | 0.53%   |
| en_IE.UTF8 | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 164       | 87.7%   |
| BIOS | 23        | 12.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 98        | 51.85%  |
| Btrfs   | 31        | 16.4%   |
| Zfs     | 18        | 9.52%   |
| Tmpfs   | 18        | 9.52%   |
| Xfs     | 17        | 8.99%   |
| Unknown | 6         | 3.17%   |
| Ext2    | 1         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 175       | 93.09%  |
| Unknown | 8         | 4.26%   |
| MBR     | 5         | 2.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 75.26%  |
| Yes       | 47        | 24.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 128       | 68.82%  |
| Yes       | 58        | 31.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 41        | 22.16%  |
| ASUSTek Computer                     | 38        | 20.54%  |
| Dell                                 | 21        | 11.35%  |
| MSI                                  | 13        | 7.03%   |
| Gigabyte Technology                  | 12        | 6.49%   |
| Hewlett-Packard                      | 11        | 5.95%   |
| Acer                                 | 7         | 3.78%   |
| ASRock                               | 6         | 3.24%   |
| Apple                                | 6         | 3.24%   |
| Pine Microsystems                    | 3         | 1.62%   |
| GPD                                  | 3         | 1.62%   |
| Supermicro                           | 2         | 1.08%   |
| Raspberry Pi Foundation              | 2         | 1.08%   |
| MECHREVO                             | 2         | 1.08%   |
| Intel                                | 2         | 1.08%   |
| Framework                            | 2         | 1.08%   |
| Toshiba                              | 1         | 0.54%   |
| Teclast                              | 1         | 0.54%   |
| System76                             | 1         | 0.54%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.54%   |
| OBSIDIAN-PC                          | 1         | 0.54%   |
| Microtech                            | 1         | 0.54%   |
| MACHENIKE                            | 1         | 0.54%   |
| HUAWEI                               | 1         | 0.54%   |
| Hardkernel                           | 1         | 0.54%   |
| EVGA                                 | 1         | 0.54%   |
| Blackview                            | 1         | 0.54%   |
| AZW                                  | 1         | 0.54%   |
| Avell High Performance               | 1         | 0.54%   |
| Alienware                            | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Pine Microsystems Pine64 PinePhone (1.2)   | 3         | 1.62%   |
| Lenovo 13w Yoga 82S1                       | 3         | 1.62%   |
| ASUS All Series                            | 3         | 1.62%   |
| MSI MS-7C56                                | 2         | 1.08%   |
| MSI MS-7C37                                | 2         | 1.08%   |
| Gigabyte B550I AORUS PRO AX                | 2         | 1.08%   |
| Gigabyte B450M DS3H                        | 2         | 1.08%   |
| Dell Latitude 7420                         | 2         | 1.08%   |
| ASUS Zenbook UX3402ZA_UX3402ZA             | 2         | 1.08%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 1.08%   |
| Apple MacBookPro11,5                       | 2         | 1.08%   |
| Apple MacBookPro11,3                       | 2         | 1.08%   |
| Apple iMac17,1                             | 2         | 1.08%   |
| Toshiba Satellite L50-B                    | 1         | 0.54%   |
| Teclast F5                                 | 1         | 0.54%   |
| System76 Pangolin                          | 1         | 0.54%   |
| Supermicro X8DT6                           | 1         | 0.54%   |
| Supermicro X10SLL-F                        | 1         | 0.54%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.54%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 1         | 0.54%   |
| RPi Raspberry Pi 3 Model B+                | 1         | 0.54%   |
| OBSIDIAN-PC N13_N140ZU                     | 1         | 0.54%   |
| MSI MS-7C95                                | 1         | 0.54%   |
| MSI MS-7C91                                | 1         | 0.54%   |
| MSI MS-7C84                                | 1         | 0.54%   |
| MSI MS-7C35                                | 1         | 0.54%   |
| MSI MS-7B89                                | 1         | 0.54%   |
| MSI MS-7B09                                | 1         | 0.54%   |
| MSI MS-7758                                | 1         | 0.54%   |
| MSI Bravo 15 B5DD                          | 1         | 0.54%   |
| MSI Alpha 15 B5EEK                         | 1         | 0.54%   |
| Microtech CoreBook Lite                    | 1         | 0.54%   |
| MECHREVO WUJIE 14                          | 1         | 0.54%   |
| MECHREVO Code01 Ver2.0                     | 1         | 0.54%   |
| MACHENIKE F117-7P                          | 1         | 0.54%   |
| Lenovo Yoga Slim 7 13ACN5 82CY             | 1         | 0.54%   |
| Lenovo Yoga 520-14IKB 81C8                 | 1         | 0.54%   |
| Lenovo Yoga 14sARE 2020 82A8               | 1         | 0.54%   |
| Lenovo ThinkPad X390 20Q0CTO1WW            | 1         | 0.54%   |
| Lenovo ThinkPad X260 20F5S6MF02            | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 23        | 12.43%  |
| ASUS ROG                                   | 9         | 4.86%   |
| ASUS PRIME                                 | 8         | 4.32%   |
| Dell XPS                                   | 6         | 3.24%   |
| Dell Inspiron                              | 6         | 3.24%   |
| ASUS Zenbook                               | 6         | 3.24%   |
| Lenovo Legion                              | 5         | 2.7%    |
| Dell Latitude                              | 5         | 2.7%    |
| Apple MacBookPro11                         | 4         | 2.16%   |
| Acer Aspire                                | 4         | 2.16%   |
| Pine Microsystems Pine64                   | 3         | 1.62%   |
| Lenovo Yoga                                | 3         | 1.62%   |
| Lenovo IdeaPad                             | 3         | 1.62%   |
| Lenovo 13w                                 | 3         | 1.62%   |
| HP EliteBook                               | 3         | 1.62%   |
| Gigabyte B450M                             | 3         | 1.62%   |
| Dell Precision                             | 3         | 1.62%   |
| ASUS All                                   | 3         | 1.62%   |
| RPi Raspberry                              | 2         | 1.08%   |
| MSI MS-7C56                                | 2         | 1.08%   |
| MSI MS-7C37                                | 2         | 1.08%   |
| Lenovo IdeaPadFlex                         | 2         | 1.08%   |
| HP Spectre                                 | 2         | 1.08%   |
| HP ProBook                                 | 2         | 1.08%   |
| HP EliteDesk                               | 2         | 1.08%   |
| Gigabyte X570                              | 2         | 1.08%   |
| Gigabyte B550I                             | 2         | 1.08%   |
| Framework Laptop                           | 2         | 1.08%   |
| ASUS TUF                                   | 2         | 1.08%   |
| Apple iMac17                               | 2         | 1.08%   |
| Toshiba Satellite                          | 1         | 0.54%   |
| Teclast F5                                 | 1         | 0.54%   |
| System76 Pangolin                          | 1         | 0.54%   |
| Supermicro X8DT6                           | 1         | 0.54%   |
| Supermicro X10SLL-F                        | 1         | 0.54%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.54%   |
| OBSIDIAN-PC N13                            | 1         | 0.54%   |
| MSI MS-7C95                                | 1         | 0.54%   |
| MSI MS-7C91                                | 1         | 0.54%   |
| MSI MS-7C84                                | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 34        | 18.38%  |
| 2022    | 24        | 12.97%  |
| 2019    | 24        | 12.97%  |
| 2021    | 20        | 10.81%  |
| 2018    | 18        | 9.73%   |
| 2016    | 13        | 7.03%   |
| 2017    | 9         | 4.86%   |
| 2013    | 9         | 4.86%   |
| 2015    | 8         | 4.32%   |
| 2014    | 6         | 3.24%   |
| 2012    | 6         | 3.24%   |
| 2023    | 5         | 2.7%    |
| Unknown | 5         | 2.7%    |
| 2011    | 2         | 1.08%   |
| 2010    | 1         | 0.54%   |
| 2009    | 1         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 92        | 49.73%  |
| Desktop        | 62        | 33.51%  |
| Convertible    | 17        | 9.19%   |
| Phone          | 3         | 1.62%   |
| All in one     | 3         | 1.62%   |
| Server         | 3         | 1.62%   |
| System on chip | 2         | 1.08%   |
| Mini pc        | 2         | 1.08%   |
| Tablet         | 1         | 0.54%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 184       | 98.92%  |
| Enabled  | 2         | 1.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 184       | 99.46%  |
| Yes  | 1         | 0.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 47        | 25%     |
| 16.01-24.0      | 45        | 23.94%  |
| 8.01-16.0       | 30        | 15.96%  |
| 64.01-256.0     | 23        | 12.23%  |
| 4.01-8.0        | 21        | 11.17%  |
| 24.01-32.0      | 10        | 5.32%   |
| 3.01-4.0        | 8         | 4.26%   |
| 0.51-1.0        | 2         | 1.06%   |
| More than 256.0 | 1         | 0.53%   |
| 1.01-2.0        | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 59        | 28.64%  |
| 8.01-16.0   | 33        | 16.02%  |
| 3.01-4.0    | 31        | 15.05%  |
| 2.01-3.0    | 26        | 12.62%  |
| 1.01-2.0    | 23        | 11.17%  |
| 32.01-64.0  | 8         | 3.88%   |
| 16.01-24.0  | 8         | 3.88%   |
| 0.51-1.0    | 8         | 3.88%   |
| 24.01-32.0  | 7         | 3.4%    |
| 0.01-0.5    | 2         | 0.97%   |
| 64.01-256.0 | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 103       | 53.65%  |
| 2      | 55        | 28.65%  |
| 3      | 14        | 7.29%   |
| 5      | 5         | 2.6%    |
| 6      | 4         | 2.08%   |
| 4      | 4         | 2.08%   |
| 7      | 2         | 1.04%   |
| 23     | 1         | 0.52%   |
| 17     | 1         | 0.52%   |
| 11     | 1         | 0.52%   |
| 8      | 1         | 0.52%   |
| 0      | 1         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 167       | 89.78%  |
| Yes       | 19        | 10.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 72.87%  |
| No        | 51        | 27.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 76.47%  |
| No        | 44        | 23.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 72.34%  |
| No        | 52        | 27.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 34        | 18.38%  |
| Germany      | 21        | 11.35%  |
| UK           | 13        | 7.03%   |
| France       | 12        | 6.49%   |
| Russia       | 11        | 5.95%   |
| Italy        | 11        | 5.95%   |
| Poland       | 8         | 4.32%   |
| Ukraine      | 7         | 3.78%   |
| Canada       | 7         | 3.78%   |
| Austria      | 5         | 2.7%    |
| Switzerland  | 4         | 2.16%   |
| Netherlands  | 4         | 2.16%   |
| Australia    | 4         | 2.16%   |
| India        | 3         | 1.62%   |
| Denmark      | 3         | 1.62%   |
| Czechia      | 3         | 1.62%   |
| Brazil       | 3         | 1.62%   |
| Belgium      | 3         | 1.62%   |
| Serbia       | 2         | 1.08%   |
| New Zealand  | 2         | 1.08%   |
| Japan        | 2         | 1.08%   |
| Iraq         | 2         | 1.08%   |
| Hungary      | 2         | 1.08%   |
| Uruguay      | 1         | 0.54%   |
| Taiwan       | 1         | 0.54%   |
| Sweden       | 1         | 0.54%   |
| Spain        | 1         | 0.54%   |
| South Africa | 1         | 0.54%   |
| Slovenia     | 1         | 0.54%   |
| Singapore    | 1         | 0.54%   |
| Romania      | 1         | 0.54%   |
| Portugal     | 1         | 0.54%   |
| Peru         | 1         | 0.54%   |
| Mexico       | 1         | 0.54%   |
| Latvia       | 1         | 0.54%   |
| Kyrgyzstan   | 1         | 0.54%   |
| Kuwait       | 1         | 0.54%   |
| Ireland      | 1         | 0.54%   |
| Iran         | 1         | 0.54%   |
| Hong Kong    | 1         | 0.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Kharkiv            | 5         | 2.53%   |
| Vienna             | 4         | 2.02%   |
| Milwaukee          | 4         | 2.02%   |
| Marki              | 4         | 2.02%   |
| Frankfurt am Main  | 4         | 2.02%   |
| Plymouth           | 3         | 1.52%   |
| Lyon               | 3         | 1.52%   |
| London             | 3         | 1.52%   |
| Cerami             | 3         | 1.52%   |
| Southampton        | 2         | 1.01%   |
| South Deerfield    | 2         | 1.01%   |
| Schaafheim         | 2         | 1.01%   |
| Rochester          | 2         | 1.01%   |
| Richardson         | 2         | 1.01%   |
| Prague             | 2         | 1.01%   |
| Phoenix            | 2         | 1.01%   |
| Perth              | 2         | 1.01%   |
| Ottawa             | 2         | 1.01%   |
| Melbourne          | 2         | 1.01%   |
| Krasnodar          | 2         | 1.01%   |
| Halifax            | 2         | 1.01%   |
| Gdansk             | 2         | 1.01%   |
| Darmstadt          | 2         | 1.01%   |
| Chelyabinsk        | 2         | 1.01%   |
| Catania            | 2         | 1.01%   |
| Belgrade           | 2         | 1.01%   |
| Baghdad            | 2         | 1.01%   |
| Austin             | 2         | 1.01%   |
| Amsterdam          | 2         | 1.01%   |
| Zurich             | 1         | 0.51%   |
| Yangzhou           | 1         | 0.51%   |
| Woodford           | 1         | 0.51%   |
| Woldegk            | 1         | 0.51%   |
| Wellington         | 1         | 0.51%   |
| Warsaw             | 1         | 0.51%   |
| Villeurbanne       | 1         | 0.51%   |
| Verneuil-sur-Seine | 1         | 0.51%   |
| Valpacos           | 1         | 0.51%   |
| Trento             | 1         | 0.51%   |
| Tremestieri Etneo  | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 76        | 141    | 26.95%  |
| Sandisk                     | 25        | 31     | 8.87%   |
| WDC                         | 23        | 45     | 8.16%   |
| Seagate                     | 18        | 51     | 6.38%   |
| Toshiba                     | 17        | 33     | 6.03%   |
| Intel                       | 12        | 19     | 4.26%   |
| Crucial                     | 12        | 19     | 4.26%   |
| Micron Technology           | 11        | 12     | 3.9%    |
| Kingston                    | 11        | 12     | 3.9%    |
| Unknown                     | 9         | 13     | 3.19%   |
| SK hynix                    | 7         | 10     | 2.48%   |
| Apple                       | 7         | 11     | 2.48%   |
| HGST                        | 5         | 15     | 1.77%   |
| Yangtze Memory Technologies | 3         | 4      | 1.06%   |
| Phison Electronics          | 3         | 6      | 1.06%   |
| KIOXIA                      | 3         | 4      | 1.06%   |
| Kingston Technology Company | 3         | 3      | 1.06%   |
| Hitachi                     | 3         | 6      | 1.06%   |
| Transcend                   | 2         | 2      | 0.71%   |
| SPCC                        | 2         | 2      | 0.71%   |
| Realtek Semiconductor       | 2         | 3      | 0.71%   |
| Plextor                     | 2         | 2      | 0.71%   |
| OCZ                         | 2         | 2      | 0.71%   |
| MAXIO Technology (Hangzhou) | 2         | 3      | 0.71%   |
| China                       | 2         | 2      | 0.71%   |
| ADATA Technology            | 2         | 4      | 0.71%   |
| A-DATA Technology           | 2         | 2      | 0.71%   |
| ZHITAI                      | 1         | 1      | 0.35%   |
| Teclast                     | 1         | 3      | 0.35%   |
| Silicon Motion              | 1         | 1      | 0.35%   |
| Phison                      | 1         | 1      | 0.35%   |
| Micron/Crucial Technology   | 1         | 1      | 0.35%   |
| MBED                        | 1         | 1      | 0.35%   |
| LITEON                      | 1         | 1      | 0.35%   |
| Lexar                       | 1         | 1      | 0.35%   |
| INNOVATION IT               | 1         | 1      | 0.35%   |
| Dogfish                     | 1         | 1      | 0.35%   |
| Corsair                     | 1         | 1      | 0.35%   |
| Biwin Storage Technology    | 1         | 1      | 0.35%   |
| BIWIN                       | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 10        | 2.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 8         | 2.39%   |
| Samsung SSD 860 EVO 500GB                           | 5         | 1.49%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 1.49%   |
| Unknown MMC Card  32GB                              | 4         | 1.19%   |
| SanDisk SSD PLUS 240GB                              | 4         | 1.19%   |
| Samsung SSD 860 QVO 1TB                             | 4         | 1.19%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3         | 0.9%    |
| Samsung SSD 970 EVO Plus 2TB                        | 3         | 0.9%    |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.9%    |
| Samsung SSD 970 EVO 500GB                           | 3         | 0.9%    |
| Micron MTFDKCD512TFK 512GB                          | 3         | 0.9%    |
| Intel SSDPEKNU010TZ 1TB                             | 3         | 0.9%    |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.9%    |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 2         | 0.6%    |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.6%    |
| Seagate ST3000DM001-1CH166 3TB                      | 2         | 0.6%    |
| Sandisk WD Black SN850 1TB                          | 2         | 0.6%    |
| SanDisk Ultra II 240GB SSD                          | 2         | 0.6%    |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.6%    |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.6%    |
| Samsung SSD 980 1TB                                 | 2         | 0.6%    |
| Samsung SSD 970 EVO 1TB                             | 2         | 0.6%    |
| Samsung SSD 870 EVO 500GB                           | 2         | 0.6%    |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.6%    |
| Samsung SSD 860 EVO 2TB                             | 2         | 0.6%    |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.6%    |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.6%    |
| Samsung SSD 840 EVO 250GB                           | 2         | 0.6%    |
| Samsung PM9A1 NVMe 1024GB                           | 2         | 0.6%    |
| Samsung NVMe SSD Drive 1TB                          | 2         | 0.6%    |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.6%    |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 0.6%    |
| HGST HTS721010A9E630 1TB                            | 2         | 0.6%    |
| Crucial CT250MX500SSD1 250GB                        | 2         | 0.6%    |
| Apple SSD SM0512G 500GB                             | 2         | 0.6%    |
| Apple SSD SM0128G 121GB                             | 2         | 0.6%    |
| Apple HDD ST2000DM001 2TB                           | 2         | 0.6%    |
| ZHITAI SC001 Active 512GB SSD                       | 1         | 0.3%    |
| Yangtze Memory ZHITAI TiPro7000 1TB                 | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 51     | 29.03%  |
| WDC                 | 17        | 37     | 27.42%  |
| Toshiba             | 12        | 25     | 19.35%  |
| HGST                | 5         | 15     | 8.06%   |
| Hitachi             | 3         | 6      | 4.84%   |
| Apple               | 3         | 3      | 4.84%   |
| Samsung Electronics | 2         | 2      | 3.23%   |
| ASMT                | 1         | 1      | 1.61%   |
| ASMedia             | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 68     | 34.74%  |
| SanDisk             | 11        | 16     | 11.58%  |
| Crucial             | 11        | 18     | 11.58%  |
| Kingston            | 7         | 7      | 7.37%   |
| Apple               | 6         | 8      | 6.32%   |
| Intel               | 5         | 7      | 5.26%   |
| WDC                 | 2         | 3      | 2.11%   |
| Transcend           | 2         | 2      | 2.11%   |
| SPCC                | 2         | 2      | 2.11%   |
| OCZ                 | 2         | 2      | 2.11%   |
| Micron Technology   | 2         | 2      | 2.11%   |
| China               | 2         | 2      | 2.11%   |
| ZHITAI              | 1         | 1      | 1.05%   |
| Toshiba             | 1         | 1      | 1.05%   |
| Teclast             | 1         | 3      | 1.05%   |
| SK hynix            | 1         | 1      | 1.05%   |
| Plextor             | 1         | 1      | 1.05%   |
| LITEON              | 1         | 1      | 1.05%   |
| INNOVATION IT       | 1         | 1      | 1.05%   |
| Dogfish             | 1         | 1      | 1.05%   |
| Corsair             | 1         | 1      | 1.05%   |
| BIWIN               | 1         | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 118       | 170    | 46.46%  |
| SSD     | 82        | 149    | 32.28%  |
| HDD     | 44        | 141    | 17.32%  |
| MMC     | 9         | 14     | 3.54%   |
| Unknown | 1         | 1      | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 118       | 170    | 51.75%  |
| SATA | 94        | 281    | 41.23%  |
| MMC  | 9         | 14     | 3.95%   |
| SAS  | 7         | 10     | 3.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 119    | 47.48%  |
| 0.51-1.0   | 41        | 67     | 29.5%   |
| 1.01-2.0   | 13        | 18     | 9.35%   |
| 4.01-10.0  | 9         | 53     | 6.47%   |
| 2.01-3.0   | 6         | 12     | 4.32%   |
| 3.01-4.0   | 3         | 15     | 2.16%   |
| 10.01-20.0 | 1         | 6      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 65        | 34.03%  |
| 1-20           | 42        | 21.99%  |
| 251-500        | 19        | 9.95%   |
| 501-1000       | 18        | 9.42%   |
| 101-250        | 16        | 8.38%   |
| 1001-2000      | 11        | 5.76%   |
| More than 3000 | 9         | 4.71%   |
| 2001-3000      | 9         | 4.71%   |
| 21-50          | 2         | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 65        | 33.16%  |
| 1-20           | 54        | 27.55%  |
| 101-250        | 20        | 10.2%   |
| 51-100         | 14        | 7.14%   |
| 501-1000       | 13        | 6.63%   |
| 21-50          | 12        | 6.12%   |
| 251-500        | 8         | 4.08%   |
| 1001-2000      | 5         | 2.55%   |
| More than 3000 | 3         | 1.53%   |
| 2001-3000      | 2         | 1.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| SanDisk SSD PLUS 240GB                         | 2         | 4      | 10.53%  |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1         | 1      | 5.26%   |
| WDC WD20EARX-008FB0 2TB                        | 1         | 1      | 5.26%   |
| WDC WD10EZEX-60ZF5A0 1TB                       | 1         | 1      | 5.26%   |
| WDC WD10 JPLX-00MBPT0 1TB                      | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 5.26%   |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 5.26%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 5.26%   |
| Seagate ST8000VN004-2M2101 8TB                 | 1         | 3      | 5.26%   |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 5.26%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 5.26%   |
| Samsung Electronics SSD 870 EVO 1TB            | 1         | 1      | 5.26%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 5.26%   |
| Intel SSDSC2BW240A4 240GB                      | 1         | 1      | 5.26%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 5.26%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 5.26%   |
| Crucial CT240M500SSD1 240GB                    | 1         | 1      | 5.26%   |
| ASMT 2115 64GB                                 | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 21.05%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Seagate             | 2         | 4      | 10.53%  |
| SanDisk             | 2         | 4      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| SK hynix            | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| Hitachi             | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |
| Crucial             | 1         | 1      | 5.26%   |
| ASMT                | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 36.36%  |
| Toshiba | 2         | 2      | 18.18%  |
| Seagate | 2         | 4      | 18.18%  |
| Hitachi | 1         | 1      | 9.09%   |
| HGST    | 1         | 1      | 9.09%   |
| ASMT    | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 13     | 55.56%  |
| SSD  | 6         | 8      | 33.33%  |
| NVMe | 2         | 2      | 11.11%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MG03ACA300 3TB                           | 1         | 1      | 33.33%  |
| Toshiba HDWG180 8TB                              | 1         | 4      | 33.33%  |
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 5      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 175       | 405    | 81.02%  |
| Detected | 23        | 41     | 10.65%  |
| Malfunc  | 15        | 23     | 6.94%   |
| Failed   | 3         | 6      | 1.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 89        | 33.09%  |
| Samsung Electronics          | 55        | 20.45%  |
| AMD                          | 42        | 15.61%  |
| SanDisk                      | 19        | 7.06%   |
| Micron Technology            | 9         | 3.35%   |
| Kingston Technology Company  | 7         | 2.6%    |
| SK hynix                     | 6         | 2.23%   |
| ASMedia Technology           | 6         | 2.23%   |
| Toshiba America Info Systems | 5         | 1.86%   |
| Phison Electronics           | 4         | 1.49%   |
| ADATA Technology             | 4         | 1.49%   |
| Yangtze Memory Technologies  | 3         | 1.12%   |
| LSI Logic / Symbios Logic    | 3         | 1.12%   |
| KIOXIA                       | 3         | 1.12%   |
| Broadcom / LSI               | 3         | 1.12%   |
| Realtek Semiconductor        | 2         | 0.74%   |
| Micron/Crucial Technology    | 2         | 0.74%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.74%   |
| Silicon Motion               | 1         | 0.37%   |
| Shenzhen Longsys Electronics | 1         | 0.37%   |
| Marvell Technology Group     | 1         | 0.37%   |
| Lite-On Technology           | 1         | 0.37%   |
| Biwin Storage Technology     | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 27        | 9.41%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 27        | 9.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 15        | 5.23%   |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 4.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.14%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 2.79%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 6         | 2.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2.09%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 2.09%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 2.09%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.74%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.74%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 4         | 1.39%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 4         | 1.39%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.05%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.05%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.05%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 1.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.05%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.05%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 2         | 0.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.7%    |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.7%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 0.7%    |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 0.7%    |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 118       | 46.09%  |
| SATA | 113       | 44.14%  |
| RAID | 16        | 6.25%   |
| SAS  | 6         | 2.34%   |
| IDE  | 3         | 1.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 112       | 60.54%  |
| AMD    | 68        | 36.76%  |
| ARM    | 5         | 2.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 2.7%    |
| ARM Processor                              | 5         | 2.7%    |
| AMD Ryzen 5 3600 6-Core Processor          | 5         | 2.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 2.16%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 4         | 2.16%   |
| Intel 12th Gen Core i7-1260P               | 4         | 2.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 4         | 2.16%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 4         | 2.16%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 4         | 2.16%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 4         | 2.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 3         | 1.62%   |
| Intel 12th Gen Core i5-1240P               | 3         | 1.62%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 1.62%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 1.62%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 3         | 1.62%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 1.62%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 3         | 1.62%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 1.08%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 1.08%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 1.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 1.08%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 1.08%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 2         | 1.08%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 2         | 1.08%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 2         | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 2         | 1.08%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 1.08%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 2         | 1.08%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 2         | 1.08%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 1.08%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 2         | 1.08%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 2         | 1.08%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 2         | 1.08%   |
| Intel Xeon W-1290P CPU @ 3.70GHz           | 1         | 0.54%   |
| Intel Xeon E-2276M CPU @ 2.80GHz           | 1         | 0.54%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 0.54%   |
| Intel Xeon CPU L5640 @ 2.27GHz             | 1         | 0.54%   |
| Intel Xeon CPU E5606 @ 2.13GHz             | 1         | 0.54%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz        | 1         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 41        | 22.16%  |
| Other                  | 31        | 16.76%  |
| Intel Core i5          | 24        | 12.97%  |
| AMD Ryzen 7            | 24        | 12.97%  |
| AMD Ryzen 5            | 22        | 11.89%  |
| AMD Ryzen 9            | 13        | 7.03%   |
| Intel Xeon             | 7         | 3.78%   |
| Intel Celeron          | 5         | 2.7%    |
| AMD Ryzen 7 PRO        | 5         | 2.7%    |
| Intel Core i3          | 4         | 2.16%   |
| AMD Ryzen Threadripper | 3         | 1.62%   |
| Intel Core i9          | 2         | 1.08%   |
| Intel Pentium Gold     | 1         | 0.54%   |
| Intel Core m3          | 1         | 0.54%   |
| Intel Atom             | 1         | 0.54%   |
| AMD FX                 | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 57        | 30.81%  |
| 8       | 40        | 21.62%  |
| 6       | 31        | 16.76%  |
| 2       | 24        | 12.97%  |
| 12      | 13        | 7.03%   |
| 16      | 5         | 2.7%    |
| Unknown | 5         | 2.7%    |
| 24      | 4         | 2.16%   |
| 10      | 3         | 1.62%   |
| 32      | 1         | 0.54%   |
| 14      | 1         | 0.54%   |
| 1       | 1         | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 178       | 96.22%  |
| Unknown | 5         | 2.7%    |
| 2       | 2         | 1.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 163       | 88.11%  |
| 1       | 17        | 9.19%   |
| Unknown | 5         | 2.7%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 184       | 98.92%  |
| 32-bit         | 1         | 0.54%   |
| Unknown        | 1         | 0.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 22.92%  |
| 0x0a50000c | 12        | 6.25%   |
| 0x306c3    | 10        | 5.21%   |
| 0x806c1    | 8         | 4.17%   |
| 0x0a50000d | 7         | 3.65%   |
| 0x08701021 | 7         | 3.65%   |
| 0x906ea    | 6         | 3.13%   |
| 0x806ea    | 6         | 3.13%   |
| 0x306a9    | 6         | 3.13%   |
| 0x506e3    | 5         | 2.6%    |
| 0x0a404102 | 5         | 2.6%    |
| 0x08600106 | 5         | 2.6%    |
| 0x806ec    | 4         | 2.08%   |
| 0x806eb    | 4         | 2.08%   |
| 0x406e3    | 4         | 2.08%   |
| 0x08701013 | 4         | 2.08%   |
| 0x906a3    | 3         | 1.56%   |
| 0x40661    | 3         | 1.56%   |
| 0x306d4    | 3         | 1.56%   |
| 0x906ed    | 2         | 1.04%   |
| 0x906e9    | 2         | 1.04%   |
| 0x806e9    | 2         | 1.04%   |
| 0x706a8    | 2         | 1.04%   |
| 0x706a1    | 2         | 1.04%   |
| 0x40651    | 2         | 1.04%   |
| 0x0a601203 | 2         | 1.04%   |
| 0x0a201204 | 2         | 1.04%   |
| 0x0a201025 | 2         | 1.04%   |
| 0x0a201016 | 2         | 1.04%   |
| 0x0a201009 | 2         | 1.04%   |
| 0x08600104 | 2         | 1.04%   |
| 0x08108109 | 2         | 1.04%   |
| 0x08001138 | 2         | 1.04%   |
| 0xa0653    | 1         | 0.52%   |
| 0xa0652    | 1         | 0.52%   |
| 0x906a4    | 1         | 0.52%   |
| 0x806d1    | 1         | 0.52%   |
| 0x406f1    | 1         | 0.52%   |
| 0x306f2    | 1         | 0.52%   |
| 0x206c2    | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 16.76%  |
| Zen 3            | 29        | 15.68%  |
| Zen 2            | 21        | 11.35%  |
| Unknown          | 18        | 9.73%   |
| Haswell          | 17        | 9.19%   |
| Skylake          | 14        | 7.57%   |
| Alderlake Hybrid | 11        | 5.95%   |
| TigerLake        | 10        | 5.41%   |
| IvyBridge        | 7         | 3.78%   |
| Goldmont plus    | 5         | 2.7%    |
| Zen+             | 4         | 2.16%   |
| Zen              | 4         | 2.16%   |
| Broadwell        | 4         | 2.16%   |
| CometLake        | 3         | 1.62%   |
| Westmere         | 2         | 1.08%   |
| Icelake          | 2         | 1.08%   |
| Piledriver       | 1         | 0.54%   |
| Gracemont        | 1         | 0.54%   |
| Bonnell          | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 88        | 39.11%  |
| Nvidia                     | 69        | 30.67%  |
| AMD                        | 65        | 28.89%  |
| Matrox Electronics Systems | 2         | 0.89%   |
| ASPEED Technology          | 1         | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 14        | 6.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 8         | 3.48%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 8         | 3.48%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 8         | 3.48%   |
| AMD Renoir                                                                            | 7         | 3.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 6         | 2.61%   |
| Intel UHD Graphics 620                                                                | 6         | 2.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 6         | 2.61%   |
| AMD Rembrandt [Radeon 680M]                                                           | 6         | 2.61%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 6         | 2.61%   |
| Intel HD Graphics 530                                                                 | 5         | 2.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 5         | 2.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 2.17%   |
| AMD Barcelo                                                                           | 5         | 2.17%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 1.74%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 1.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.74%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 3         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 1.3%    |
| Nvidia GK104 [GeForce GTX 760]                                                        | 3         | 1.3%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 1.3%    |
| Intel HD Graphics 620                                                                 | 3         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 1.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 1.3%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                 | 2         | 0.87%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 2         | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 0.87%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 2         | 0.87%   |
| Nvidia GM204 [GeForce GTX 970]                                                        | 2         | 0.87%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.87%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 0.87%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                         | 2         | 0.87%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 2         | 0.87%   |
| Intel HD Graphics 630                                                                 | 2         | 0.87%   |
| Intel HD Graphics 5500                                                                | 2         | 0.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 0.87%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 2         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 54        | 29.03%  |
| 1 x AMD        | 44        | 23.66%  |
| 1 x Nvidia     | 29        | 15.59%  |
| Intel + Nvidia | 28        | 15.05%  |
| AMD + Nvidia   | 12        | 6.45%   |
| Other          | 6         | 3.23%   |
| 2 x AMD        | 4         | 2.15%   |
| Intel + AMD    | 4         | 2.15%   |
| 1 x Matrox     | 2         | 1.08%   |
| 2 x Intel      | 1         | 0.54%   |
| 1 x ASPEED     | 1         | 0.54%   |
| AMD + ASPEED   | 1         | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 130       | 69.89%  |
| Proprietary | 46        | 24.73%  |
| Unknown     | 10        | 5.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 60.53%  |
| 0.01-0.5   | 23        | 12.11%  |
| 7.01-8.0   | 16        | 8.42%   |
| 1.01-2.0   | 15        | 7.89%   |
| 3.01-4.0   | 11        | 5.79%   |
| 8.01-16.0  | 5         | 2.63%   |
| 0.51-1.0   | 4         | 2.11%   |
| 16.01-24.0 | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 26        | 13.2%   |
| AU Optronics         | 24        | 12.18%  |
| Samsung Electronics  | 22        | 11.17%  |
| BOE                  | 19        | 9.64%   |
| Goldstar             | 12        | 6.09%   |
| LG Display           | 11        | 5.58%   |
| Chimei Innolux       | 10        | 5.08%   |
| Acer                 | 8         | 4.06%   |
| PANDA                | 6         | 3.05%   |
| Apple                | 6         | 3.05%   |
| Sharp                | 5         | 2.54%   |
| CSO                  | 5         | 2.54%   |
| Ancor Communications | 5         | 2.54%   |
| Hewlett-Packard      | 4         | 2.03%   |
| AOC                  | 4         | 2.03%   |
| Iiyama               | 3         | 1.52%   |
| Philips              | 2         | 1.02%   |
| Panasonic            | 2         | 1.02%   |
| InfoVision           | 2         | 1.02%   |
| HannStar             | 2         | 1.02%   |
| Eizo                 | 2         | 1.02%   |
| BenQ                 | 2         | 1.02%   |
| WST                  | 1         | 0.51%   |
| Vizio                | 1         | 0.51%   |
| ViewSonic            | 1         | 0.51%   |
| Unknown (AAA)        | 1         | 0.51%   |
| Toshiba              | 1         | 0.51%   |
| TMX                  | 1         | 0.51%   |
| RTK                  | 1         | 0.51%   |
| NEC Computers        | 1         | 0.51%   |
| MSI                  | 1         | 0.51%   |
| MPI                  | 1         | 0.51%   |
| Lenovo               | 1         | 0.51%   |
| JDI                  | 1         | 0.51%   |
| HVR                  | 1         | 0.51%   |
| Gigabyte Technology  | 1         | 0.51%   |
| ASUSTek Computer     | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 1.98%   |
| AU Optronics LCD Monitor AUO019C 1920x1200 286x178mm 13.3-inch        | 3         | 1.49%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 2         | 0.99%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.99%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 2         | 0.99%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 0.99%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2         | 0.99%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 0.99%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                   | 2         | 0.99%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 2         | 0.99%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 0.99%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 0.99%   |
| Apple iMac APPAE05 3840x2160 597x336mm 27.0-inch                      | 2         | 0.99%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2         | 0.99%   |
| WST KL.1350W.005 WST2C34 2256x1504 285x190mm 13.5-inch                | 1         | 0.5%    |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                 | 1         | 0.5%    |
| ViewSonic VX2758-SERIES VSCA738 2560x1440 598x336mm 27.0-inch         | 1         | 0.5%    |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1         | 0.5%    |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.5%    |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch               | 1         | 0.5%    |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.5%    |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch     | 1         | 0.5%    |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 0.5%    |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4160 3000x2000 285x190mm 13.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 1         | 0.5%    |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 597x336mm 27.0-inch    | 1         | 0.5%    |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 0.5%    |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch     | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 70        | 37.23%  |
| 3840x2160 (4K)     | 30        | 15.96%  |
| 2560x1440 (QHD)    | 19        | 10.11%  |
| 2880x1800          | 12        | 6.38%   |
| 1366x768 (WXGA)    | 11        | 5.85%   |
| 1920x1200 (WUXGA)  | 10        | 5.32%   |
| 2560x1600          | 8         | 4.26%   |
| 1280x1024 (SXGA)   | 6         | 3.19%   |
| 2560x1080          | 4         | 2.13%   |
| 3440x1440          | 3         | 1.6%    |
| 2256x1504          | 3         | 1.6%    |
| 1600x900 (HD+)     | 3         | 1.6%    |
| 1680x1050 (WSXGA+) | 2         | 1.06%   |
| 3840x2400          | 1         | 0.53%   |
| 3000x2000          | 1         | 0.53%   |
| 2160x1200          | 1         | 0.53%   |
| 1920x1280          | 1         | 0.53%   |
| 1440x900 (WXGA+)   | 1         | 0.53%   |
| 1280x720 (HD)      | 1         | 0.53%   |
| 1024x600           | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 33        | 17.01%  |
| 14      | 31        | 15.98%  |
| 27      | 22        | 11.34%  |
| 13      | 21        | 10.82%  |
| 24      | 18        | 9.28%   |
| 23      | 14        | 7.22%   |
| 17      | 9         | 4.64%   |
| 34      | 7         | 3.61%   |
| 12      | 7         | 3.61%   |
| 31      | 6         | 3.09%   |
| 16      | 6         | 3.09%   |
| 21      | 4         | 2.06%   |
| 25      | 2         | 1.03%   |
| 22      | 2         | 1.03%   |
| 19      | 2         | 1.03%   |
| 84      | 1         | 0.52%   |
| 49      | 1         | 0.52%   |
| 46      | 1         | 0.52%   |
| 38      | 1         | 0.52%   |
| 28      | 1         | 0.52%   |
| 26      | 1         | 0.52%   |
| 20      | 1         | 0.52%   |
| 11      | 1         | 0.52%   |
| 10      | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 74        | 39.15%  |
| 501-600     | 52        | 27.51%  |
| 201-300     | 27        | 14.29%  |
| 351-400     | 9         | 4.76%   |
| 601-700     | 8         | 4.23%   |
| 701-800     | 7         | 3.7%    |
| 401-500     | 7         | 3.7%    |
| 1001-1500   | 2         | 1.06%   |
| 801-900     | 1         | 0.53%   |
| 1501-2000   | 1         | 0.53%   |
| Unknown     | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 117       | 68.02%  |
| 16/10 | 36        | 20.93%  |
| 21/9  | 7         | 4.07%   |
| 5/4   | 5         | 2.91%   |
| 3/2   | 5         | 2.91%   |
| 4/3   | 1         | 0.58%   |
| 1.00  | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 39        | 20.1%   |
| 101-110        | 34        | 17.53%  |
| 201-250        | 29        | 14.95%  |
| 301-350        | 23        | 11.86%  |
| 351-500        | 14        | 7.22%   |
| 71-80          | 12        | 6.19%   |
| 251-300        | 9         | 4.64%   |
| 61-70          | 7         | 3.61%   |
| 121-130        | 6         | 3.09%   |
| 151-200        | 5         | 2.58%   |
| 111-120        | 5         | 2.58%   |
| 141-150        | 3         | 1.55%   |
| More than 1000 | 2         | 1.03%   |
| 501-1000       | 2         | 1.03%   |
| 51-60          | 1         | 0.52%   |
| 41-50          | 1         | 0.52%   |
| 131-140        | 1         | 0.52%   |
| Unknown        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 49        | 26.78%  |
| 121-160       | 44        | 24.04%  |
| 161-240       | 43        | 23.5%   |
| 101-120       | 25        | 13.66%  |
| More than 240 | 19        | 10.38%  |
| 1-50          | 2         | 1.09%   |
| Unknown       | 1         | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 126       | 65.97%  |
| 2     | 37        | 19.37%  |
| 0     | 23        | 12.04%  |
| 3     | 5         | 2.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 118       | 44.03%  |
| Realtek Semiconductor             | 88        | 32.84%  |
| MediaTek                          | 12        | 4.48%   |
| Qualcomm Atheros                  | 11        | 4.1%    |
| Broadcom                          | 9         | 3.36%   |
| Aquantia                          | 5         | 1.87%   |
| TP-Link                           | 3         | 1.12%   |
| Ralink Technology                 | 2         | 0.75%   |
| Qualcomm                          | 2         | 0.75%   |
| Microsoft                         | 2         | 0.75%   |
| Lenovo                            | 2         | 0.75%   |
| Xiaomi                            | 1         | 0.37%   |
| Texas Instruments                 | 1         | 0.37%   |
| STMicroelectronics                | 1         | 0.37%   |
| Standard Microsystems             | 1         | 0.37%   |
| Ralink                            | 1         | 0.37%   |
| QinHeng Electronics               | 1         | 0.37%   |
| Pulse-Eight                       | 1         | 0.37%   |
| Oculus VR                         | 1         | 0.37%   |
| ICS Advent                        | 1         | 0.37%   |
| Google                            | 1         | 0.37%   |
| Fibocom                           | 1         | 0.37%   |
| Ericsson Business Mobile Networks | 1         | 0.37%   |
| D-Link System                     | 1         | 0.37%   |
| D-Link                            | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56        | 17.89%  |
| Intel Wi-Fi 6 AX200                                               | 23        | 7.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 5.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 3.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 9         | 2.88%   |
| Intel I211 Gigabit Network Connection                             | 8         | 2.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 2.24%   |
| Intel Ethernet Controller I225-V                                  | 7         | 2.24%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 6         | 1.92%   |
| Intel Wireless 8260                                               | 6         | 1.92%   |
| Intel Wireless 7265                                               | 6         | 1.92%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.92%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 4         | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.28%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4         | 1.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 1.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.28%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 4         | 1.28%   |
| Intel Wireless-AC 9260                                            | 3         | 0.96%   |
| Intel Wireless 8265 / 8275                                        | 3         | 0.96%   |
| Intel Wireless 7260                                               | 3         | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.96%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.64%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.64%   |
| Intel Wireless 3165                                               | 2         | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.64%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.64%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 95        | 65.07%  |
| MediaTek                          | 12        | 8.22%   |
| Realtek Semiconductor             | 9         | 6.16%   |
| Qualcomm Atheros                  | 9         | 6.16%   |
| Broadcom                          | 7         | 4.79%   |
| TP-Link                           | 3         | 2.05%   |
| Ralink Technology                 | 2         | 1.37%   |
| Qualcomm                          | 2         | 1.37%   |
| Microsoft                         | 2         | 1.37%   |
| Ralink                            | 1         | 0.68%   |
| Fibocom                           | 1         | 0.68%   |
| Ericsson Business Mobile Networks | 1         | 0.68%   |
| D-Link System                     | 1         | 0.68%   |
| D-Link                            | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 23        | 15.75%  |
| Intel Alder Lake-P PCH CNVi WiFi                              | 9         | 6.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 7         | 4.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 6         | 4.11%   |
| Intel Wireless 8260                                           | 6         | 4.11%   |
| Intel Wireless 7265                                           | 6         | 4.11%   |
| Intel Wi-Fi 6 AX201                                           | 6         | 4.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 5         | 3.42%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 4         | 2.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 4         | 2.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 4         | 2.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 4         | 2.74%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 4         | 2.74%   |
| Intel Wireless-AC 9260                                        | 3         | 2.05%   |
| Intel Wireless 8265 / 8275                                    | 3         | 2.05%   |
| Intel Wireless 7260                                           | 3         | 2.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3         | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 3         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 3         | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 1.37%   |
| Microsoft Xbox 360 Wireless Adapter                           | 2         | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 1.37%   |
| Intel Wireless 3165                                           | 2         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 1.37%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 2         | 1.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 0.68%   |
| TP-Link 802.11ac NIC                                          | 1         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 0.68%   |
| Realtek 802.11ac NIC                                          | 1         | 0.68%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 0.68%   |
| Ralink RT5370 Wireless Adapter                                | 1         | 0.68%   |
| Ralink RT2800 802.11n PCI                                     | 1         | 0.68%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 1         | 0.68%   |
| Qualcomm QCA6390 Wireless Network Adapter                     | 1         | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 81        | 52.6%   |
| Intel                 | 54        | 35.06%  |
| Broadcom              | 5         | 3.25%   |
| Aquantia              | 5         | 3.25%   |
| Qualcomm Atheros      | 3         | 1.95%   |
| Lenovo                | 2         | 1.3%    |
| Xiaomi                | 1         | 0.65%   |
| Standard Microsystems | 1         | 0.65%   |
| ICS Advent            | 1         | 0.65%   |
| Google                | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56        | 34.57%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 11.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 6.79%   |
| Intel I211 Gigabit Network Connection                             | 8         | 4.94%   |
| Intel Ethernet Controller I225-V                                  | 7         | 4.32%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 3.09%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.47%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.85%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.23%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.23%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.23%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.23%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.23%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.23%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.62%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.62%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.62%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.62%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.62%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.62%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.62%   |
| ICS Advent 10/100M LAN                                            | 1         | 0.62%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.62%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 0.62%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.62%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 140       | 49.47%  |
| Ethernet | 138       | 48.76%  |
| Modem    | 5         | 1.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 119       | 62.3%   |
| Ethernet | 72        | 37.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 90        | 48.13%  |
| 2     | 83        | 44.39%  |
| 3     | 7         | 3.74%   |
| 0     | 6         | 3.21%   |
| 4     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 139       | 73.16%  |
| Yes  | 51        | 26.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 61.59%  |
| Realtek Semiconductor           | 10        | 7.25%   |
| MediaTek                        | 6         | 4.35%   |
| Cambridge Silicon Radio         | 6         | 4.35%   |
| Apple                           | 6         | 4.35%   |
| ASUSTek Computer                | 5         | 3.62%   |
| Qualcomm Atheros Communications | 4         | 2.9%    |
| IMC Networks                    | 4         | 2.9%    |
| Foxconn / Hon Hai               | 4         | 2.9%    |
| Broadcom                        | 4         | 2.9%    |
| USI                             | 1         | 0.72%   |
| Realtek                         | 1         | 0.72%   |
| Lite-On Technology              | 1         | 0.72%   |
| HTC (High Tech Computer)        | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 21        | 15.22%  |
| Intel Bluetooth wireless interface                                   | 17        | 12.32%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 13        | 9.42%   |
| Intel AX201 Bluetooth                                                | 13        | 9.42%   |
| Realtek Bluetooth Radio                                              | 10        | 7.25%   |
| Intel Bluetooth Device                                               | 9         | 6.52%   |
| MediaTek Wireless_Device                                             | 6         | 4.35%   |
| Intel AX210 Bluetooth                                                | 6         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 6         | 4.35%   |
| Apple Bluetooth Host Controller                                      | 4         | 2.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 2.17%   |
| Foxconn / Hon Hai Wireless_Device                                    | 3         | 2.17%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2         | 1.45%   |
| IMC Networks Wireless_Device                                         | 2         | 1.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 1.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 1.45%   |
| Apple Bluetooth USB Host Controller                                  | 2         | 1.45%   |
| USI Bluetooth Device                                                 | 1         | 0.72%   |
| Realtek 802.11ac WLAN Adapter                                        | 1         | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 0.72%   |
| IMC Networks Bluetooth Device                                        | 1         | 0.72%   |
| IMC Networks BCM20702A0                                              | 1         | 0.72%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.72%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 1         | 0.72%   |
| Broadcom HP Portable SoftSailing                                     | 1         | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 0.72%   |
| ASUS Broadcom Bluetooth 2.1                                          | 1         | 0.72%   |
| ASUS Bluetooth Device                                                | 1         | 0.72%   |
| ASUS ASUS USB-BT500                                                  | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 110       | 37.29%  |
| AMD                                  | 77        | 26.1%   |
| Nvidia                               | 51        | 17.29%  |
| C-Media Electronics                  | 7         | 2.37%   |
| Lenovo                               | 4         | 1.36%   |
| Creative Technology                  | 4         | 1.36%   |
| Texas Instruments                    | 3         | 1.02%   |
| Sennheiser Communications            | 3         | 1.02%   |
| Razer USA                            | 3         | 1.02%   |
| Kingston Technology                  | 3         | 1.02%   |
| Synaptics                            | 2         | 0.68%   |
| Realtek Semiconductor                | 2         | 0.68%   |
| Focusrite-Novation                   | 2         | 0.68%   |
| Trust                                | 1         | 0.34%   |
| Thomann                              | 1         | 0.34%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.34%   |
| Sony                                 | 1         | 0.34%   |
| Shure                                | 1         | 0.34%   |
| Schiit Audio                         | 1         | 0.34%   |
| Scarlett                             | 1         | 0.34%   |
| Satechi                              | 1         | 0.34%   |
| RODE Microphones                     | 1         | 0.34%   |
| PreSonus Audio Electronics           | 1         | 0.34%   |
| Logitech                             | 1         | 0.34%   |
| JMTek                                | 1         | 0.34%   |
| GYROCOM C&C                          | 1         | 0.34%   |
| Giga-Byte Technology                 | 1         | 0.34%   |
| Edifier Technology                   | 1         | 0.34%   |
| Dell                                 | 1         | 0.34%   |
| Creative Labs                        | 1         | 0.34%   |
| Corsair                              | 1         | 0.34%   |
| Conexant Systems                     | 1         | 0.34%   |
| ASUSTek Computer                     | 1         | 0.34%   |
| ASRock                               | 1         | 0.34%   |
| Apogee Electronics                   | 1         | 0.34%   |
| Antlion Audio                        | 1         | 0.34%   |
| (LCS) USB Audio Device               | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 36        | 10.06%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 25        | 6.98%   |
| AMD Starship/Matisse HD Audio Controller                                | 22        | 6.15%   |
| Intel Sunrise Point-LP HD Audio                                         | 16        | 4.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 11        | 3.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 10        | 2.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 10        | 2.79%   |
| Intel Cannon Lake PCH cAVS                                              | 9         | 2.51%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 8         | 2.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 8         | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 7         | 1.96%   |
| AMD Navi 10 HDMI Audio                                                  | 7         | 1.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 6         | 1.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 6         | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 6         | 1.68%   |
| Nvidia TU106 High Definition Audio Controller                           | 5         | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 5         | 1.4%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 5         | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                           | 4         | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                         | 4         | 1.12%   |
| Nvidia GK104 HDMI Audio Controller                                      | 4         | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                           | 4         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 4         | 1.12%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 4         | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 3         | 0.84%   |
| Nvidia GP106 High Definition Audio Controller                           | 3         | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                           | 3         | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                      | 3         | 0.84%   |
| Nvidia GA104 High Definition Audio Controller                           | 3         | 0.84%   |
| Nvidia Audio device                                                     | 3         | 0.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 3         | 0.84%   |
| Intel Comet Lake PCH-LP cAVS                                            | 3         | 0.84%   |
| Intel Comet Lake PCH cAVS                                               | 3         | 0.84%   |
| Intel Broadwell-U Audio Controller                                      | 3         | 0.84%   |
| Intel 200 Series PCH HD Audio                                           | 3         | 0.84%   |
| Creative Technology SoundBlaster Live! 24-bit External SB0490           | 3         | 0.84%   |
| Texas Instruments PCM2902 Audio Codec                                   | 2         | 0.56%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 0.56%   |
| Sennheiser Communications Headset [PC 8]                                | 2         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 43        | 20.67%  |
| SK hynix                     | 28        | 13.46%  |
| Micron Technology            | 26        | 12.5%   |
| Kingston                     | 25        | 12.02%  |
| Corsair                      | 22        | 10.58%  |
| Crucial                      | 15        | 7.21%   |
| G.Skill                      | 14        | 6.73%   |
| Unknown                      | 6         | 2.88%   |
| Team                         | 6         | 2.88%   |
| Unknown (ABCD)               | 5         | 2.4%    |
| A-DATA Technology            | 4         | 1.92%   |
| Ramaxel Technology           | 2         | 0.96%   |
| GOODRAM                      | 2         | 0.96%   |
| AMD                          | 2         | 0.96%   |
| Unknown (0x59B)              | 1         | 0.48%   |
| Strontium                    | 1         | 0.48%   |
| Patriot Memory (PDP Systems) | 1         | 0.48%   |
| Patriot                      | 1         | 0.48%   |
| GLOWAY                       | 1         | 0.48%   |
| Avant                        | 1         | 0.48%   |
| Apacer                       | 1         | 0.48%   |
| Unknown                      | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 4         | 1.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 4         | 1.79%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s             | 3         | 1.35%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                      | 3         | 1.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.35%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s              | 3         | 1.35%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s            | 3         | 1.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 2         | 0.9%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s            | 2         | 0.9%    |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s            | 2         | 0.9%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s            | 2         | 0.9%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s             | 2         | 0.9%    |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s     | 2         | 0.9%    |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s           | 2         | 0.9%    |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.9%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 2         | 0.9%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s            | 2         | 0.9%    |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s               | 2         | 0.9%    |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s               | 2         | 0.9%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s               | 2         | 0.9%    |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s            | 2         | 0.9%    |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s               | 1         | 0.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1         | 0.45%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.45%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s               | 1         | 0.45%   |
| Unknown RAM Module 1GB SODIMM SDRAM                               | 1         | 0.45%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                     | 1         | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1         | 0.45%   |
| Unknown (0x59B) RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 0.45%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s               | 1         | 0.45%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s                | 1         | 0.45%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s               | 1         | 0.45%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s             | 1         | 0.45%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s                | 1         | 0.45%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.45%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                      | 1         | 0.45%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.45%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.45%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s              | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 105       | 58.99%  |
| DDR3   | 32        | 17.98%  |
| LPDDR4 | 16        | 8.99%   |
| LPDDR5 | 12        | 6.74%   |
| LPDDR3 | 6         | 3.37%   |
| DDR5   | 6         | 3.37%   |
| SDRAM  | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 89        | 48.9%   |
| DIMM         | 60        | 32.97%  |
| Row Of Chips | 29        | 15.93%  |
| Chip         | 2         | 1.1%    |
| RIMM         | 1         | 0.55%   |
| Unknown      | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 82        | 41.41%  |
| 16384 | 55        | 27.78%  |
| 4096  | 29        | 14.65%  |
| 32768 | 25        | 12.63%  |
| 2048  | 5         | 2.53%   |
| 1024  | 2         | 1.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 46        | 23.83%  |
| 1600    | 25        | 12.95%  |
| 2667    | 21        | 10.88%  |
| 2133    | 15        | 7.77%   |
| 2400    | 14        | 7.25%   |
| 6400    | 12        | 6.22%   |
| 3600    | 9         | 4.66%   |
| 4267    | 8         | 4.15%   |
| 3000    | 5         | 2.59%   |
| 1867    | 5         | 2.59%   |
| 3733    | 4         | 2.07%   |
| 4800    | 3         | 1.55%   |
| 4266    | 3         | 1.55%   |
| 1333    | 3         | 1.55%   |
| 5600    | 2         | 1.04%   |
| 3400    | 2         | 1.04%   |
| 3334    | 2         | 1.04%   |
| 3266    | 2         | 1.04%   |
| 2933    | 2         | 1.04%   |
| 6000    | 1         | 0.52%   |
| 4000    | 1         | 0.52%   |
| 3866    | 1         | 0.52%   |
| 3666    | 1         | 0.52%   |
| 3534    | 1         | 0.52%   |
| 2800    | 1         | 0.52%   |
| 2134    | 1         | 0.52%   |
| 2132    | 1         | 0.52%   |
| 1066    | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Xerox  | 1         | 50%     |
| Canon  | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| Xerox Phaser 6125N  | 1         | 50%     |
| Canon TR8500 series | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 20        | 17.24%  |
| IMC Networks                  | 17        | 14.66%  |
| Logitech                      | 14        | 12.07%  |
| Microdia                      | 13        | 11.21%  |
| Acer                          | 12        | 10.34%  |
| Realtek Semiconductor         | 11        | 9.48%   |
| Sunplus Innovation Technology | 5         | 4.31%   |
| Syntek                        | 3         | 2.59%   |
| Quanta                        | 3         | 2.59%   |
| MacroSilicon                  | 3         | 2.59%   |
| Lite-On Technology            | 3         | 2.59%   |
| Apple                         | 3         | 2.59%   |
| SunplusIT                     | 1         | 0.86%   |
| Sonix Technology              | 1         | 0.86%   |
| Primax Electronics            | 1         | 0.86%   |
| OPPO Electronics              | 1         | 0.86%   |
| Microsoft                     | 1         | 0.86%   |
| Luxvisions Innotech Limited   | 1         | 0.86%   |
| Bison Electronics             | 1         | 0.86%   |
| Alcor Micro                   | 1         | 0.86%   |
| 2M UVC CAMERA                 | 1         | 0.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 13        | 10.92%  |
| IMC Networks USB2.0 HD UVC WebCam                 | 9         | 7.56%   |
| Acer Integrated Camera                            | 7         | 5.88%   |
| Microdia Integrated_Webcam_HD                     | 6         | 5.04%   |
| Realtek Integrated_Webcam_HD                      | 5         | 4.2%    |
| IMC Networks Integrated Camera                    | 5         | 4.2%    |
| Chicony HP HD Camera                              | 4         | 3.36%   |
| Syntek Integrated Camera                          | 3         | 2.52%   |
| MacroSilicon USB Video                            | 3         | 2.52%   |
| Logitech HD Pro Webcam C920                       | 3         | 2.52%   |
| Sunplus Integrated_Webcam_FHD                     | 2         | 1.68%   |
| Realtek Laptop Camera                             | 2         | 1.68%   |
| Microdia Webcam Vitade AF                         | 2         | 1.68%   |
| Logitech Webcam C270                              | 2         | 1.68%   |
| Logitech StreamCam                                | 2         | 1.68%   |
| Lite-On Integrated Camera                         | 2         | 1.68%   |
| Apple FaceTime HD Camera (Built-in)               | 2         | 1.68%   |
| Acer HD Webcam                                    | 2         | 1.68%   |
| SunplusIT MTD camera                              | 1         | 0.84%   |
| Sunplus Laptop Integrated Webcam FHD              | 1         | 0.84%   |
| Sunplus Integrated_Webcam_HD                      | 1         | 0.84%   |
| Sunplus HD WebCam                                 | 1         | 0.84%   |
| Sonix USB2.0 FHD UVC WebCam                       | 1         | 0.84%   |
| Realtek TV Camera                                 | 1         | 0.84%   |
| Realtek Realtek USB MIC                           | 1         | 0.84%   |
| Realtek Lenovo EasyCamera                         | 1         | 0.84%   |
| Realtek Integrated Webcam                         | 1         | 0.84%   |
| Realtek EasyCamera                                | 1         | 0.84%   |
| Quanta VGA WebCam                                 | 1         | 0.84%   |
| Quanta HP True Vision HD Camera                   | 1         | 0.84%   |
| Quanta HD WebCam                                  | 1         | 0.84%   |
| Primax HP HD Webcam [Fixed]                       | 1         | 0.84%   |
| OPPO Oppo N1                                      | 1         | 0.84%   |
| Microsoft LifeCam HD-3000                         | 1         | 0.84%   |
| Microdia USB 2.0 Camera                           | 1         | 0.84%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 0.84%   |
| Microdia Integrated Webcam                        | 1         | 0.84%   |
| Microdia HP Integrated Webcam                     | 1         | 0.84%   |
| Microdia Camera                                   | 1         | 0.84%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 0.84%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 39.29%  |
| Validity Sensors           | 8         | 28.57%  |
| Shenzhen Goodix Technology | 7         | 25%     |
| Gingytech                  | 1         | 3.57%   |
| Focal-systems.Corp         | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 5         | 17.86%  |
| Shenzhen Goodix Fingerprint Reader                       | 5         | 17.86%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 10.71%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 7.14%   |
| Synaptics UWP WBDI Device                                | 2         | 7.14%   |
| Synaptics UWP WBDI                                       | 2         | 7.14%   |
| Shenzhen Goodix  Fingerprint Device                      | 2         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 3.57%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 3.57%   |
| Validity Sensors VFS491                                  | 1         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 3.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Gingytech Fingerprint sensor                             | 1         | 3.57%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 10        | 55.56%  |
| Yubico.com  | 3         | 16.67%  |
| Broadcom    | 3         | 16.67%  |
| Upek        | 1         | 5.56%   |
| OmniKey     | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 10        | 55.56%  |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 2         | 11.11%  |
| Broadcom 5880                                              | 2         | 11.11%  |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 5.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5.56%   |
| OmniKey CardMan Smart@Link                                 | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 111       | 57.51%  |
| 1     | 53        | 27.46%  |
| 2     | 26        | 13.47%  |
| 4     | 2         | 1.04%   |
| 3     | 1         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 26        | 23.42%  |
| Multimedia controller    | 23        | 20.72%  |
| Graphics card            | 19        | 17.12%  |
| Chipcard                 | 13        | 11.71%  |
| Net/wireless             | 8         | 7.21%   |
| Camera                   | 5         | 4.5%    |
| Bluetooth                | 5         | 4.5%    |
| Unassigned class         | 3         | 2.7%    |
| Modem                    | 2         | 1.8%    |
| Card reader              | 2         | 1.8%    |
| Storage/ata              | 1         | 0.9%    |
| Network                  | 1         | 0.9%    |
| Firewire controller      | 1         | 0.9%    |
| Dvb card                 | 1         | 0.9%    |
| Communication controller | 1         | 0.9%    |

