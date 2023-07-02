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

Total: 237

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| NixOS 22.11                      | 51        | 27.72%  |
| NixOS 22.05                      | 37        | 20.11%  |
| NixOS 23.05                      | 35        | 19.02%  |
| NixOS 21.11                      | 18        | 9.78%   |
| NixOS 23.11                      | 8         | 4.35%   |
| NixOS                            | 5         | 2.72%   |
| NixOS 21.05pre-git               | 2         | 1.09%   |
| NixOS 20.09pre-git               | 2         | 1.09%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.54%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.54%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.54%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.54%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.54%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.54%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.54%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.54%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.54%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.54%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.54%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.54%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.54%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.54%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.54%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.54%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.54%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.54%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.54%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.54%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.54%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.54%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.54%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.54%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.54%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 165       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Computers | Percent |
|-------------|-----------|---------|
| 5.15.74     | 5         | 2.55%   |
| 6.3.8       | 4         | 2.04%   |
| 6.3.3       | 4         | 2.04%   |
| 5.15.86     | 4         | 2.04%   |
| 5.15.43     | 4         | 2.04%   |
| 6.3.1       | 3         | 1.53%   |
| 6.2.0-rc6   | 3         | 1.53%   |
| 6.1.35      | 3         | 1.53%   |
| 6.1.0       | 3         | 1.53%   |
| 6.0.11      | 3         | 1.53%   |
| 6.0.10      | 3         | 1.53%   |
| 5.15.82     | 3         | 1.53%   |
| 5.15.72     | 3         | 1.53%   |
| 5.15.68     | 3         | 1.53%   |
| 5.15.47     | 3         | 1.53%   |
| 5.15.26     | 3         | 1.53%   |
| 6.1.34      | 2         | 1.02%   |
| 6.1.27      | 2         | 1.02%   |
| 6.1.24      | 2         | 1.02%   |
| 6.1.1       | 2         | 1.02%   |
| 5.8.1-zen1  | 2         | 1.02%   |
| 5.19.14     | 2         | 1.02%   |
| 5.18.19     | 2         | 1.02%   |
| 5.17.1      | 2         | 1.02%   |
| 5.16.8-zen1 | 2         | 1.02%   |
| 5.16.15     | 2         | 1.02%   |
| 5.15.96     | 2         | 1.02%   |
| 5.15.92     | 2         | 1.02%   |
| 5.15.90     | 2         | 1.02%   |
| 5.15.85     | 2         | 1.02%   |
| 5.15.64     | 2         | 1.02%   |
| 5.15.32     | 2         | 1.02%   |
| 5.15.25     | 2         | 1.02%   |
| 5.15.109    | 2         | 1.02%   |
| 5.15.107    | 2         | 1.02%   |
| 5.13.7      | 2         | 1.02%   |
| 5.13.2      | 2         | 1.02%   |
| 5.12.15     | 2         | 1.02%   |
| 5.10.102    | 2         | 1.02%   |
| 6.4.0-rc7   | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.74  | 5         | 2.55%   |
| 6.3.8    | 4         | 2.04%   |
| 6.3.3    | 4         | 2.04%   |
| 6.2.0    | 4         | 2.04%   |
| 6.1.0    | 4         | 2.04%   |
| 6.0.10   | 4         | 2.04%   |
| 5.15.86  | 4         | 2.04%   |
| 5.15.43  | 4         | 2.04%   |
| 6.3.1    | 3         | 1.53%   |
| 6.1.35   | 3         | 1.53%   |
| 6.0.11   | 3         | 1.53%   |
| 5.15.82  | 3         | 1.53%   |
| 5.15.72  | 3         | 1.53%   |
| 5.15.68  | 3         | 1.53%   |
| 5.15.47  | 3         | 1.53%   |
| 5.15.26  | 3         | 1.53%   |
| 6.2.9    | 2         | 1.02%   |
| 6.2.11   | 2         | 1.02%   |
| 6.1.34   | 2         | 1.02%   |
| 6.1.31   | 2         | 1.02%   |
| 6.1.27   | 2         | 1.02%   |
| 6.1.24   | 2         | 1.02%   |
| 6.1.1    | 2         | 1.02%   |
| 6.0.2    | 2         | 1.02%   |
| 5.8.1    | 2         | 1.02%   |
| 5.19.14  | 2         | 1.02%   |
| 5.18.19  | 2         | 1.02%   |
| 5.17.1   | 2         | 1.02%   |
| 5.16.8   | 2         | 1.02%   |
| 5.16.15  | 2         | 1.02%   |
| 5.15.96  | 2         | 1.02%   |
| 5.15.92  | 2         | 1.02%   |
| 5.15.90  | 2         | 1.02%   |
| 5.15.85  | 2         | 1.02%   |
| 5.15.83  | 2         | 1.02%   |
| 5.15.64  | 2         | 1.02%   |
| 5.15.32  | 2         | 1.02%   |
| 5.15.25  | 2         | 1.02%   |
| 5.15.109 | 2         | 1.02%   |
| 5.15.107 | 2         | 1.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 59        | 31.38%  |
| 6.1     | 23        | 12.23%  |
| 5.10    | 14        | 7.45%   |
| 6.3     | 13        | 6.91%   |
| 6.2     | 13        | 6.91%   |
| 6.0     | 13        | 6.91%   |
| 5.16    | 8         | 4.26%   |
| 5.4     | 7         | 3.72%   |
| 5.19    | 7         | 3.72%   |
| 5.8     | 6         | 3.19%   |
| 5.18    | 5         | 2.66%   |
| 5.13    | 4         | 2.13%   |
| 5.7     | 3         | 1.6%    |
| 5.17    | 3         | 1.6%    |
| 5.12    | 3         | 1.6%    |
| 5.14    | 2         | 1.06%   |
| 5.11    | 2         | 1.06%   |
| 4.19    | 2         | 1.06%   |
| 6.4     | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 159       | 96.36%  |
| aarch64 | 5         | 3.03%   |
| i686    | 1         | 0.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 89        | 51.45%  |
| sway         | 18        | 10.4%   |
| GNOME        | 18        | 10.4%   |
| KDE5         | 13        | 7.51%   |
| XFCE         | 8         | 4.62%   |
| Hyprland     | 8         | 4.62%   |
| none+i3      | 6         | 3.47%   |
| KDE          | 5         | 2.89%   |
| none+xmonad  | 2         | 1.16%   |
| none+awesome | 2         | 1.16%   |
| xsession     | 1         | 0.58%   |
| X-Generic    | 1         | 0.58%   |
| none+bspwm   | 1         | 0.58%   |
| MATE         | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 83        | 48.26%  |
| Wayland | 42        | 24.42%  |
| X11     | 34        | 19.77%  |
| Tty     | 13        | 7.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 105       | 62.5%   |
| LightDM | 25        | 14.88%  |
| SDDM    | 19        | 11.31%  |
| GDM     | 19        | 11.31%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 75        | 44.91%  |
| Unknown    | 57        | 34.13%  |
| en_GB      | 8         | 4.79%   |
| en_DK      | 4         | 2.4%    |
| de_DE      | 4         | 2.4%    |
| ru_RU      | 3         | 1.8%    |
| fr_FR      | 3         | 1.8%    |
| en_AU      | 3         | 1.8%    |
| it_IT      | 2         | 1.2%    |
| de_CH      | 2         | 1.2%    |
| ro_RO      | 1         | 0.6%    |
| pt_BR      | 1         | 0.6%    |
| lv_LV      | 1         | 0.6%    |
| en_IN      | 1         | 0.6%    |
| en_IE.UTF8 | 1         | 0.6%    |
| en_CA      | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 145       | 86.83%  |
| BIOS | 22        | 13.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 84        | 49.7%   |
| Btrfs   | 28        | 16.57%  |
| Zfs     | 18        | 10.65%  |
| Xfs     | 17        | 10.06%  |
| Tmpfs   | 15        | 8.88%   |
| Unknown | 6         | 3.55%   |
| Ext2    | 1         | 0.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 156       | 92.86%  |
| Unknown | 8         | 4.76%   |
| MBR     | 4         | 2.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 129       | 75.88%  |
| Yes       | 41        | 24.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 69.28%  |
| Yes       | 51        | 30.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 38        | 23.03%  |
| ASUSTek Computer                     | 31        | 18.79%  |
| Dell                                 | 21        | 12.73%  |
| MSI                                  | 13        | 7.88%   |
| Gigabyte Technology                  | 11        | 6.67%   |
| Hewlett-Packard                      | 9         | 5.45%   |
| ASRock                               | 6         | 3.64%   |
| Acer                                 | 6         | 3.64%   |
| Apple                                | 4         | 2.42%   |
| Pine Microsystems                    | 3         | 1.82%   |
| GPD                                  | 3         | 1.82%   |
| Supermicro                           | 2         | 1.21%   |
| Raspberry Pi Foundation              | 2         | 1.21%   |
| MECHREVO                             | 2         | 1.21%   |
| Intel                                | 2         | 1.21%   |
| Framework                            | 2         | 1.21%   |
| Toshiba                              | 1         | 0.61%   |
| Teclast                              | 1         | 0.61%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.61%   |
| OBSIDIAN-PC                          | 1         | 0.61%   |
| Microtech                            | 1         | 0.61%   |
| MACHENIKE                            | 1         | 0.61%   |
| Hardkernel                           | 1         | 0.61%   |
| EVGA                                 | 1         | 0.61%   |
| Blackview                            | 1         | 0.61%   |
| Avell High Performance               | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Pine Microsystems Pine64 PinePhone (1.2)   | 3         | 1.82%   |
| Lenovo 13w Yoga 82S1                       | 3         | 1.82%   |
| MSI MS-7C56                                | 2         | 1.21%   |
| MSI MS-7C37                                | 2         | 1.21%   |
| Gigabyte B550I AORUS PRO AX                | 2         | 1.21%   |
| Gigabyte B450M DS3H                        | 2         | 1.21%   |
| Dell Latitude 7420                         | 2         | 1.21%   |
| ASUS Zenbook UX3402ZA_UX3402ZA             | 2         | 1.21%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 1.21%   |
| ASUS All Series                            | 2         | 1.21%   |
| Apple MacBookPro11,5                       | 2         | 1.21%   |
| Toshiba Satellite L50-B                    | 1         | 0.61%   |
| Teclast F5                                 | 1         | 0.61%   |
| Supermicro X8DT6                           | 1         | 0.61%   |
| Supermicro X10SLL-F                        | 1         | 0.61%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.61%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 1         | 0.61%   |
| RPi Raspberry Pi 3 Model B+                | 1         | 0.61%   |
| OBSIDIAN-PC N13_N140ZU                     | 1         | 0.61%   |
| MSI MS-7C95                                | 1         | 0.61%   |
| MSI MS-7C91                                | 1         | 0.61%   |
| MSI MS-7C84                                | 1         | 0.61%   |
| MSI MS-7C35                                | 1         | 0.61%   |
| MSI MS-7B89                                | 1         | 0.61%   |
| MSI MS-7B09                                | 1         | 0.61%   |
| MSI MS-7758                                | 1         | 0.61%   |
| MSI Bravo 15 B5DD                          | 1         | 0.61%   |
| MSI Alpha 15 B5EEK                         | 1         | 0.61%   |
| Microtech CoreBook Lite                    | 1         | 0.61%   |
| MECHREVO WUJIE 14                          | 1         | 0.61%   |
| MECHREVO Code01 Ver2.0                     | 1         | 0.61%   |
| MACHENIKE F117-7P                          | 1         | 0.61%   |
| Lenovo Yoga Slim 7 13ACN5 82CY             | 1         | 0.61%   |
| Lenovo Yoga 520-14IKB 81C8                 | 1         | 0.61%   |
| Lenovo Yoga 14sARE 2020 82A8               | 1         | 0.61%   |
| Lenovo ThinkPad X390 20Q0CTO1WW            | 1         | 0.61%   |
| Lenovo ThinkPad X260 20F5S6MF02            | 1         | 0.61%   |
| Lenovo ThinkPad X260 20F5S4BY00            | 1         | 0.61%   |
| Lenovo ThinkPad X250 20CLS18S0T            | 1         | 0.61%   |
| Lenovo ThinkPad X230 2333AZ2               | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 23        | 13.94%  |
| ASUS ROG                                   | 9         | 5.45%   |
| ASUS PRIME                                 | 7         | 4.24%   |
| Dell XPS                                   | 6         | 3.64%   |
| Dell Inspiron                              | 6         | 3.64%   |
| Dell Latitude                              | 5         | 3.03%   |
| Lenovo Legion                              | 4         | 2.42%   |
| ASUS Zenbook                               | 4         | 2.42%   |
| Pine Microsystems Pine64                   | 3         | 1.82%   |
| Lenovo Yoga                                | 3         | 1.82%   |
| Lenovo 13w                                 | 3         | 1.82%   |
| Gigabyte B450M                             | 3         | 1.82%   |
| Dell Precision                             | 3         | 1.82%   |
| Apple MacBookPro11                         | 3         | 1.82%   |
| Acer Aspire                                | 3         | 1.82%   |
| RPi Raspberry                              | 2         | 1.21%   |
| MSI MS-7C56                                | 2         | 1.21%   |
| MSI MS-7C37                                | 2         | 1.21%   |
| Lenovo IdeaPad                             | 2         | 1.21%   |
| HP Spectre                                 | 2         | 1.21%   |
| HP ProBook                                 | 2         | 1.21%   |
| HP EliteBook                               | 2         | 1.21%   |
| Gigabyte X570                              | 2         | 1.21%   |
| Gigabyte B550I                             | 2         | 1.21%   |
| Framework Laptop                           | 2         | 1.21%   |
| ASUS All                                   | 2         | 1.21%   |
| Toshiba Satellite                          | 1         | 0.61%   |
| Teclast F5                                 | 1         | 0.61%   |
| Supermicro X8DT6                           | 1         | 0.61%   |
| Supermicro X10SLL-F                        | 1         | 0.61%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.61%   |
| OBSIDIAN-PC N13                            | 1         | 0.61%   |
| MSI MS-7C95                                | 1         | 0.61%   |
| MSI MS-7C91                                | 1         | 0.61%   |
| MSI MS-7C84                                | 1         | 0.61%   |
| MSI MS-7C35                                | 1         | 0.61%   |
| MSI MS-7B89                                | 1         | 0.61%   |
| MSI MS-7B09                                | 1         | 0.61%   |
| MSI MS-7758                                | 1         | 0.61%   |
| MSI Bravo                                  | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 32        | 19.39%  |
| 2019    | 22        | 13.33%  |
| 2022    | 19        | 11.52%  |
| 2021    | 19        | 11.52%  |
| 2018    | 17        | 10.3%   |
| 2016    | 13        | 7.88%   |
| 2017    | 8         | 4.85%   |
| 2015    | 8         | 4.85%   |
| 2013    | 6         | 3.64%   |
| 2012    | 6         | 3.64%   |
| 2014    | 5         | 3.03%   |
| Unknown | 5         | 3.03%   |
| 2023    | 2         | 1.21%   |
| 2011    | 1         | 0.61%   |
| 2010    | 1         | 0.61%   |
| 2009    | 1         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 82        | 49.7%   |
| Desktop        | 55        | 33.33%  |
| Convertible    | 15        | 9.09%   |
| Phone          | 3         | 1.82%   |
| Server         | 3         | 1.82%   |
| System on chip | 2         | 1.21%   |
| Mini pc        | 2         | 1.21%   |
| All in one     | 2         | 1.21%   |
| Tablet         | 1         | 0.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 165       | 99.4%   |
| Enabled  | 1         | 0.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 164       | 99.39%  |
| Yes  | 1         | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 42        | 25%     |
| 16.01-24.0  | 42        | 25%     |
| 8.01-16.0   | 26        | 15.48%  |
| 64.01-256.0 | 20        | 11.9%   |
| 4.01-8.0    | 18        | 10.71%  |
| 24.01-32.0  | 9         | 5.36%   |
| 3.01-4.0    | 8         | 4.76%   |
| 0.51-1.0    | 2         | 1.19%   |
| 1.01-2.0    | 1         | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 52        | 28.57%  |
| 8.01-16.0   | 29        | 15.93%  |
| 3.01-4.0    | 26        | 14.29%  |
| 2.01-3.0    | 22        | 12.09%  |
| 1.01-2.0    | 20        | 10.99%  |
| 32.01-64.0  | 8         | 4.4%    |
| 16.01-24.0  | 8         | 4.4%    |
| 24.01-32.0  | 7         | 3.85%   |
| 0.51-1.0    | 7         | 3.85%   |
| 0.01-0.5    | 2         | 1.1%    |
| 64.01-256.0 | 1         | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 92        | 53.8%   |
| 2      | 47        | 27.49%  |
| 3      | 13        | 7.6%    |
| 5      | 5         | 2.92%   |
| 6      | 4         | 2.34%   |
| 4      | 3         | 1.75%   |
| 7      | 2         | 1.17%   |
| 23     | 1         | 0.58%   |
| 17     | 1         | 0.58%   |
| 11     | 1         | 0.58%   |
| 8      | 1         | 0.58%   |
| 0      | 1         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 151       | 90.96%  |
| Yes       | 15        | 9.04%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 73.21%  |
| No        | 45        | 26.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 74.7%   |
| No        | 42        | 25.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 70.06%  |
| No        | 50        | 29.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 29        | 17.58%  |
| Germany     | 19        | 11.52%  |
| UK          | 13        | 7.88%   |
| France      | 11        | 6.67%   |
| Russia      | 10        | 6.06%   |
| Italy       | 10        | 6.06%   |
| Poland      | 8         | 4.85%   |
| Ukraine     | 7         | 4.24%   |
| Canada      | 7         | 4.24%   |
| Austria     | 5         | 3.03%   |
| Switzerland | 4         | 2.42%   |
| Netherlands | 4         | 2.42%   |
| India       | 3         | 1.82%   |
| Denmark     | 3         | 1.82%   |
| Czechia     | 3         | 1.82%   |
| Brazil      | 3         | 1.82%   |
| Australia   | 3         | 1.82%   |
| New Zealand | 2         | 1.21%   |
| Japan       | 2         | 1.21%   |
| Iraq        | 2         | 1.21%   |
| Belgium     | 2         | 1.21%   |
| Uruguay     | 1         | 0.61%   |
| Sweden      | 1         | 0.61%   |
| Spain       | 1         | 0.61%   |
| Slovenia    | 1         | 0.61%   |
| Singapore   | 1         | 0.61%   |
| Serbia      | 1         | 0.61%   |
| Romania     | 1         | 0.61%   |
| Portugal    | 1         | 0.61%   |
| Peru        | 1         | 0.61%   |
| Latvia      | 1         | 0.61%   |
| Kyrgyzstan  | 1         | 0.61%   |
| Iran        | 1         | 0.61%   |
| Hungary     | 1         | 0.61%   |
| Colombia    | 1         | 0.61%   |
| China       | 1         | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Kharkiv            | 5         | 2.81%   |
| Vienna             | 4         | 2.25%   |
| Marki              | 4         | 2.25%   |
| Frankfurt am Main  | 4         | 2.25%   |
| Plymouth           | 3         | 1.69%   |
| Milwaukee          | 3         | 1.69%   |
| Lyon               | 3         | 1.69%   |
| London             | 3         | 1.69%   |
| Cerami             | 3         | 1.69%   |
| Southampton        | 2         | 1.12%   |
| South Deerfield    | 2         | 1.12%   |
| Schaafheim         | 2         | 1.12%   |
| Richardson         | 2         | 1.12%   |
| Prague             | 2         | 1.12%   |
| Phoenix            | 2         | 1.12%   |
| Ottawa             | 2         | 1.12%   |
| Melbourne          | 2         | 1.12%   |
| Krasnodar          | 2         | 1.12%   |
| Halifax            | 2         | 1.12%   |
| Gdansk             | 2         | 1.12%   |
| Darmstadt          | 2         | 1.12%   |
| Chelyabinsk        | 2         | 1.12%   |
| Catania            | 2         | 1.12%   |
| Baghdad            | 2         | 1.12%   |
| Austin             | 2         | 1.12%   |
| Amsterdam          | 2         | 1.12%   |
| Zurich             | 1         | 0.56%   |
| Yangzhou           | 1         | 0.56%   |
| Woodford           | 1         | 0.56%   |
| Woldegk            | 1         | 0.56%   |
| Wellington         | 1         | 0.56%   |
| Warsaw             | 1         | 0.56%   |
| Villeurbanne       | 1         | 0.56%   |
| Verneuil-sur-Seine | 1         | 0.56%   |
| Valpacos           | 1         | 0.56%   |
| Trento             | 1         | 0.56%   |
| Tremestieri Etneo  | 1         | 0.56%   |
| Tottenham          | 1         | 0.56%   |
| Tolyatti           | 1         | 0.56%   |
| Tehran             | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 66        | 128    | 26.09%  |
| SanDisk                     | 24        | 30     | 9.49%   |
| WDC                         | 21        | 43     | 8.3%    |
| Seagate                     | 18        | 51     | 7.11%   |
| Toshiba                     | 15        | 31     | 5.93%   |
| Kingston                    | 11        | 11     | 4.35%   |
| Crucial                     | 11        | 18     | 4.35%   |
| Micron Technology           | 10        | 11     | 3.95%   |
| Unknown                     | 9         | 13     | 3.56%   |
| Intel                       | 8         | 14     | 3.16%   |
| SK hynix                    | 7         | 10     | 2.77%   |
| HGST                        | 5         | 15     | 1.98%   |
| Apple                       | 5         | 8      | 1.98%   |
| Phison Electronics          | 3         | 6      | 1.19%   |
| KIOXIA                      | 3         | 4      | 1.19%   |
| Kingston Technology Company | 3         | 3      | 1.19%   |
| Hitachi                     | 3         | 5      | 1.19%   |
| Yangtze Memory Technologies | 2         | 2      | 0.79%   |
| Transcend                   | 2         | 2      | 0.79%   |
| SPCC                        | 2         | 2      | 0.79%   |
| Realtek Semiconductor       | 2         | 2      | 0.79%   |
| Plextor                     | 2         | 2      | 0.79%   |
| China                       | 2         | 2      | 0.79%   |
| ADATA Technology            | 2         | 4      | 0.79%   |
| A-DATA Technology           | 2         | 2      | 0.79%   |
| Teclast                     | 1         | 2      | 0.4%    |
| Silicon Motion              | 1         | 1      | 0.4%    |
| Phison                      | 1         | 1      | 0.4%    |
| OCZ                         | 1         | 1      | 0.4%    |
| Micron/Crucial Technology   | 1         | 1      | 0.4%    |
| LITEON                      | 1         | 1      | 0.4%    |
| Lexar                       | 1         | 1      | 0.4%    |
| INNOVATION IT               | 1         | 1      | 0.4%    |
| Dogfish                     | 1         | 1      | 0.4%    |
| Corsair                     | 1         | 1      | 0.4%    |
| Biwin Storage Technology    | 1         | 1      | 0.4%    |
| BIWIN                       | 1         | 1      | 0.4%    |
| ASMT                        | 1         | 1      | 0.4%    |
| ASMedia                     | 1         | 1      | 0.4%    |
| Unknown                     | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7         | 2.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 7         | 2.32%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 1.66%   |
| Unknown MMC Card  32GB                              | 4         | 1.32%   |
| SanDisk SSD PLUS 240GB                              | 4         | 1.32%   |
| Samsung SSD 860 QVO 1TB                             | 4         | 1.32%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3         | 0.99%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3         | 0.99%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.99%   |
| Samsung SSD 970 EVO 500GB                           | 3         | 0.99%   |
| Samsung SSD 860 EVO 500GB                           | 3         | 0.99%   |
| Micron MTFDKCD512TFK 512GB                          | 3         | 0.99%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.99%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB             | 2         | 0.66%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.66%   |
| Seagate ST3000DM001-1CH166 3TB                      | 2         | 0.66%   |
| Sandisk WD Black SN850 1TB                          | 2         | 0.66%   |
| SanDisk Ultra II 240GB SSD                          | 2         | 0.66%   |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.66%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.66%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 0.66%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.66%   |
| Samsung SSD 860 EVO 2TB                             | 2         | 0.66%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.66%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.66%   |
| Samsung SSD 840 EVO 250GB                           | 2         | 0.66%   |
| Samsung PM9A1 NVMe 1024GB                           | 2         | 0.66%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 0.66%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.66%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 0.66%   |
| HGST HTS721010A9E630 1TB                            | 2         | 0.66%   |
| Crucial CT250MX500SSD1 250GB                        | 2         | 0.66%   |
| Apple SSD SM0512G 500GB                             | 2         | 0.66%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                | 1         | 0.33%   |
| Yangtze Memory YMTC PC300-1TB-B                     | 1         | 0.33%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                    | 1         | 0.33%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.33%   |
| WDC WDS200T1X0E-00AFY0 2TB                          | 1         | 0.33%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.33%   |
| WDC WD80EDAZ-11TA3A0 8TB                            | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 51     | 31.58%  |
| WDC                 | 15        | 35     | 26.32%  |
| Toshiba             | 11        | 24     | 19.3%   |
| HGST                | 5         | 15     | 8.77%   |
| Hitachi             | 3         | 5      | 5.26%   |
| Samsung Electronics | 2         | 2      | 3.51%   |
| Apple               | 2         | 2      | 3.51%   |
| ASMedia             | 1         | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 64     | 33.33%  |
| SanDisk             | 11        | 16     | 12.64%  |
| Crucial             | 10        | 17     | 11.49%  |
| Kingston            | 7         | 7      | 8.05%   |
| Intel               | 5         | 7      | 5.75%   |
| Apple               | 4         | 6      | 4.6%    |
| WDC                 | 2         | 3      | 2.3%    |
| Transcend           | 2         | 2      | 2.3%    |
| SPCC                | 2         | 2      | 2.3%    |
| Micron Technology   | 2         | 2      | 2.3%    |
| China               | 2         | 2      | 2.3%    |
| Toshiba             | 1         | 1      | 1.15%   |
| Teclast             | 1         | 2      | 1.15%   |
| SK hynix            | 1         | 1      | 1.15%   |
| Plextor             | 1         | 1      | 1.15%   |
| OCZ                 | 1         | 1      | 1.15%   |
| LITEON              | 1         | 1      | 1.15%   |
| INNOVATION IT       | 1         | 1      | 1.15%   |
| Dogfish             | 1         | 1      | 1.15%   |
| Corsair             | 1         | 1      | 1.15%   |
| BIWIN               | 1         | 1      | 1.15%   |
| ASMT                | 1         | 1      | 1.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 104       | 146    | 45.81%  |
| SSD  | 74        | 140    | 32.6%   |
| HDD  | 40        | 135    | 17.62%  |
| MMC  | 9         | 14     | 3.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 104       | 146    | 50.98%  |
| SATA | 85        | 266    | 41.67%  |
| MMC  | 9         | 14     | 4.41%   |
| SAS  | 6         | 9      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 111    | 48.03%  |
| 0.51-1.0   | 36        | 62     | 28.35%  |
| 1.01-2.0   | 11        | 16     | 8.66%   |
| 4.01-10.0  | 9         | 53     | 7.09%   |
| 2.01-3.0   | 6         | 12     | 4.72%   |
| 3.01-4.0   | 3         | 15     | 2.36%   |
| 10.01-20.0 | 1         | 6      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 64        | 37.43%  |
| 1-20           | 35        | 20.47%  |
| 251-500        | 17        | 9.94%   |
| 501-1000       | 14        | 8.19%   |
| 101-250        | 13        | 7.6%    |
| 1001-2000      | 10        | 5.85%   |
| More than 3000 | 9         | 5.26%   |
| 2001-3000      | 7         | 4.09%   |
| 21-50          | 2         | 1.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 64        | 36.78%  |
| 1-20           | 46        | 26.44%  |
| 101-250        | 16        | 9.2%    |
| 51-100         | 12        | 6.9%    |
| 501-1000       | 10        | 5.75%   |
| 21-50          | 9         | 5.17%   |
| 251-500        | 8         | 4.6%    |
| 1001-2000      | 4         | 2.3%    |
| More than 3000 | 3         | 1.72%   |
| 2001-3000      | 2         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| SanDisk SSD PLUS 240GB                         | 2         | 4      | 11.11%  |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1         | 1      | 5.56%   |
| WDC WD20EARX-008FB0 2TB                        | 1         | 1      | 5.56%   |
| WDC WD10EZEX-60ZF5A0 1TB                       | 1         | 1      | 5.56%   |
| WDC WD10 JPLX-00MBPT0 1TB                      | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 5.56%   |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 5.56%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 5.56%   |
| Seagate ST8000VN004-2M2101 8TB                 | 1         | 3      | 5.56%   |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 870 EVO 1TB            | 1         | 1      | 5.56%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 5.56%   |
| Intel SSDSC2BW240A4 240GB                      | 1         | 1      | 5.56%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 5.56%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 5.56%   |
| ASMT 2115 160GB                                | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 22.22%  |
| Toshiba             | 2         | 2      | 11.11%  |
| Seagate             | 2         | 4      | 11.11%  |
| SanDisk             | 2         | 4      | 11.11%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| SK hynix            | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |
| Hitachi             | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |
| ASMT                | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 40%     |
| Toshiba | 2         | 2      | 20%     |
| Seagate | 2         | 4      | 20%     |
| Hitachi | 1         | 1      | 10%     |
| HGST    | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 12     | 52.94%  |
| SSD  | 6         | 8      | 35.29%  |
| NVMe | 2         | 2      | 11.76%  |

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
| Works    | 156       | 370    | 80.83%  |
| Detected | 20        | 37     | 10.36%  |
| Malfunc  | 14        | 22     | 7.25%   |
| Failed   | 3         | 6      | 1.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 77        | 32.22%  |
| Samsung Electronics          | 47        | 19.67%  |
| AMD                          | 39        | 16.32%  |
| SanDisk                      | 18        | 7.53%   |
| Micron Technology            | 8         | 3.35%   |
| Kingston Technology Company  | 7         | 2.93%   |
| SK hynix                     | 6         | 2.51%   |
| ASMedia Technology           | 5         | 2.09%   |
| Toshiba America Info Systems | 4         | 1.67%   |
| Phison Electronics           | 4         | 1.67%   |
| ADATA Technology             | 4         | 1.67%   |
| LSI Logic / Symbios Logic    | 3         | 1.26%   |
| KIOXIA                       | 3         | 1.26%   |
| Broadcom / LSI               | 3         | 1.26%   |
| Yangtze Memory Technologies  | 2         | 0.84%   |
| Realtek Semiconductor        | 2         | 0.84%   |
| Micron/Crucial Technology    | 2         | 0.84%   |
| Silicon Motion               | 1         | 0.42%   |
| Shenzhen Longsys Electronics | 1         | 0.42%   |
| Marvell Technology Group     | 1         | 0.42%   |
| Lite-On Technology           | 1         | 0.42%   |
| Biwin Storage Technology     | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 26        | 10.24%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 9.84%   |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 4.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 4.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.54%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.76%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 2.36%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.97%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 5         | 1.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.97%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.97%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 4         | 1.57%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.18%   |
| Samsung Electronics SATA controller                                            | 3         | 1.18%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.18%   |
| Micron NVMe Storage Controller                                                 | 3         | 1.18%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.18%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.18%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.18%   |
| Yangtze Memory Non-Volatile memory controller                                  | 2         | 0.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.79%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.79%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.79%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2         | 0.79%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.79%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.79%   |
| Intel Comet Lake PCH-H RAID                                                    | 2         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 104       | 45.61%  |
| SATA | 100       | 43.86%  |
| RAID | 15        | 6.58%   |
| SAS  | 6         | 2.63%   |
| IDE  | 3         | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 100       | 60.61%  |
| AMD    | 60        | 36.36%  |
| ARM    | 5         | 3.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 3.03%   |
| ARM Processor                              | 5         | 3.03%   |
| AMD Ryzen 5 3600 6-Core Processor          | 5         | 3.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 2.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 4         | 2.42%   |
| Intel 12th Gen Core i7-1260P               | 4         | 2.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 4         | 2.42%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 4         | 2.42%   |
| Intel 12th Gen Core i5-1240P               | 3         | 1.82%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 1.82%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 1.82%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 3         | 1.82%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 3         | 1.82%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 1.82%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 3         | 1.82%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 3         | 1.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 1.21%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 1.21%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 1.21%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 1.21%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 1.21%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 1.21%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 2         | 1.21%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 2         | 1.21%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 1.21%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 2         | 1.21%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 1.21%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 2         | 1.21%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 2         | 1.21%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 2         | 1.21%   |
| Intel Xeon W-1290P CPU @ 3.70GHz           | 1         | 0.61%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 0.61%   |
| Intel Xeon CPU L5640 @ 2.27GHz             | 1         | 0.61%   |
| Intel Xeon CPU E5606 @ 2.13GHz             | 1         | 0.61%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz        | 1         | 0.61%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz       | 1         | 0.61%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 0.61%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 0.61%   |
| Intel Core i9-9900X CPU @ 3.50GHz          | 1         | 0.61%   |
| Intel Core i7-8700 CPU @ 3.20GHz           | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 36        | 21.82%  |
| Other                  | 29        | 17.58%  |
| Intel Core i5          | 22        | 13.33%  |
| AMD Ryzen 7            | 22        | 13.33%  |
| AMD Ryzen 5            | 20        | 12.12%  |
| AMD Ryzen 9            | 10        | 6.06%   |
| Intel Xeon             | 6         | 3.64%   |
| Intel Celeron          | 5         | 3.03%   |
| AMD Ryzen 7 PRO        | 5         | 3.03%   |
| Intel Core i3          | 3         | 1.82%   |
| Intel Core i9          | 2         | 1.21%   |
| AMD Ryzen Threadripper | 2         | 1.21%   |
| Intel Core m3          | 1         | 0.61%   |
| Intel Atom             | 1         | 0.61%   |
| AMD FX                 | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 51        | 30.91%  |
| 8       | 36        | 21.82%  |
| 6       | 27        | 16.36%  |
| 2       | 22        | 13.33%  |
| 12      | 13        | 7.88%   |
| Unknown | 5         | 3.03%   |
| 16      | 3         | 1.82%   |
| 10      | 3         | 1.82%   |
| 24      | 2         | 1.21%   |
| 32      | 1         | 0.61%   |
| 14      | 1         | 0.61%   |
| 1       | 1         | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 158       | 95.76%  |
| Unknown | 5         | 3.03%   |
| 2       | 2         | 1.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 146       | 88.48%  |
| 1       | 14        | 8.48%   |
| Unknown | 5         | 3.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 164       | 98.8%   |
| 32-bit         | 1         | 0.6%    |
| Unknown        | 1         | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 24.12%  |
| 0x0a50000c | 10        | 5.88%   |
| 0x806c1    | 7         | 4.12%   |
| 0x306c3    | 7         | 4.12%   |
| 0x0a50000d | 7         | 4.12%   |
| 0x08701021 | 7         | 4.12%   |
| 0x806ea    | 6         | 3.53%   |
| 0x906ea    | 5         | 2.94%   |
| 0x306a9    | 5         | 2.94%   |
| 0x08600106 | 5         | 2.94%   |
| 0x806ec    | 4         | 2.35%   |
| 0x806eb    | 4         | 2.35%   |
| 0x506e3    | 4         | 2.35%   |
| 0x406e3    | 4         | 2.35%   |
| 0x08701013 | 4         | 2.35%   |
| 0x906a3    | 3         | 1.76%   |
| 0x306d4    | 3         | 1.76%   |
| 0x0a404102 | 3         | 1.76%   |
| 0x906e9    | 2         | 1.18%   |
| 0x806e9    | 2         | 1.18%   |
| 0x706a8    | 2         | 1.18%   |
| 0x706a1    | 2         | 1.18%   |
| 0x40661    | 2         | 1.18%   |
| 0x40651    | 2         | 1.18%   |
| 0x0a201204 | 2         | 1.18%   |
| 0x0a201016 | 2         | 1.18%   |
| 0x0a201009 | 2         | 1.18%   |
| 0x08600104 | 2         | 1.18%   |
| 0x08001138 | 2         | 1.18%   |
| 0xa0653    | 1         | 0.59%   |
| 0xa0652    | 1         | 0.59%   |
| 0x906ed    | 1         | 0.59%   |
| 0x806d1    | 1         | 0.59%   |
| 0x406f1    | 1         | 0.59%   |
| 0x306f2    | 1         | 0.59%   |
| 0x206c2    | 1         | 0.59%   |
| 0x0a704103 | 1         | 0.59%   |
| 0x0a601203 | 1         | 0.59%   |
| 0x0a50000b | 1         | 0.59%   |
| 0x0a404101 | 1         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 17.58%  |
| Zen 3            | 26        | 15.76%  |
| Zen 2            | 20        | 12.12%  |
| Unknown          | 15        | 9.09%   |
| Skylake          | 13        | 7.88%   |
| Haswell          | 13        | 7.88%   |
| TigerLake        | 9         | 5.45%   |
| Alderlake Hybrid | 9         | 5.45%   |
| IvyBridge        | 6         | 3.64%   |
| Goldmont plus    | 5         | 3.03%   |
| Zen              | 4         | 2.42%   |
| Broadwell        | 4         | 2.42%   |
| Zen+             | 3         | 1.82%   |
| CometLake        | 3         | 1.82%   |
| Westmere         | 2         | 1.21%   |
| Icelake          | 2         | 1.21%   |
| Piledriver       | 1         | 0.61%   |
| Bonnell          | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 81        | 40.3%   |
| Nvidia                     | 59        | 29.35%  |
| AMD                        | 58        | 28.86%  |
| Matrox Electronics Systems | 2         | 1%      |
| ASPEED Technology          | 1         | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 13        | 6.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 8         | 3.88%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 8         | 3.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 8         | 3.88%   |
| AMD Renoir                                                                            | 7         | 3.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 6         | 2.91%   |
| Intel UHD Graphics 620                                                                | 6         | 2.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 6         | 2.91%   |
| Intel HD Graphics 530                                                                 | 5         | 2.43%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 5         | 2.43%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 5         | 2.43%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 1.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 1.94%   |
| AMD Rembrandt [Radeon 680M]                                                           | 4         | 1.94%   |
| AMD Barcelo                                                                           | 4         | 1.94%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 3         | 1.46%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 1.46%   |
| Nvidia GK104 [GeForce GTX 760]                                                        | 3         | 1.46%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 3         | 1.46%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 1.46%   |
| Intel HD Graphics 620                                                                 | 3         | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.46%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 0.97%   |
| Nvidia GM204 [GeForce GTX 970]                                                        | 2         | 0.97%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.97%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                         | 2         | 0.97%   |
| Intel HD Graphics 630                                                                 | 2         | 0.97%   |
| Intel HD Graphics 5500                                                                | 2         | 0.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 0.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 0.97%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 2         | 0.97%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                              | 2         | 0.97%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                            | 2         | 0.97%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                         | 2         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.49%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 50        | 30.12%  |
| 1 x AMD        | 38        | 22.89%  |
| Intel + Nvidia | 25        | 15.06%  |
| 1 x Nvidia     | 23        | 13.86%  |
| AMD + Nvidia   | 11        | 6.63%   |
| Other          | 6         | 3.61%   |
| 2 x AMD        | 4         | 2.41%   |
| Intel + AMD    | 4         | 2.41%   |
| 1 x Matrox     | 2         | 1.2%    |
| 2 x Intel      | 1         | 0.6%    |
| 1 x ASPEED     | 1         | 0.6%    |
| AMD + ASPEED   | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 117       | 70.48%  |
| Proprietary | 39        | 23.49%  |
| Unknown     | 10        | 6.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 61.18%  |
| 0.01-0.5   | 19        | 11.18%  |
| 7.01-8.0   | 15        | 8.82%   |
| 1.01-2.0   | 13        | 7.65%   |
| 3.01-4.0   | 11        | 6.47%   |
| 8.01-16.0  | 4         | 2.35%   |
| 0.51-1.0   | 3         | 1.76%   |
| 16.01-24.0 | 1         | 0.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 24        | 13.79%  |
| AU Optronics         | 21        | 12.07%  |
| Samsung Electronics  | 18        | 10.34%  |
| BOE                  | 16        | 9.2%    |
| LG Display           | 11        | 6.32%   |
| Goldstar             | 11        | 6.32%   |
| Chimei Innolux       | 9         | 5.17%   |
| Acer                 | 7         | 4.02%   |
| PANDA                | 6         | 3.45%   |
| Sharp                | 5         | 2.87%   |
| CSO                  | 5         | 2.87%   |
| Ancor Communications | 5         | 2.87%   |
| Hewlett-Packard      | 4         | 2.3%    |
| Apple                | 4         | 2.3%    |
| AOC                  | 3         | 1.72%   |
| Panasonic            | 2         | 1.15%   |
| InfoVision           | 2         | 1.15%   |
| Iiyama               | 2         | 1.15%   |
| Eizo                 | 2         | 1.15%   |
| WST                  | 1         | 0.57%   |
| Vizio                | 1         | 0.57%   |
| ViewSonic            | 1         | 0.57%   |
| Unknown (AAA)        | 1         | 0.57%   |
| TMX                  | 1         | 0.57%   |
| RTK                  | 1         | 0.57%   |
| Philips              | 1         | 0.57%   |
| NEC Computers        | 1         | 0.57%   |
| MSI                  | 1         | 0.57%   |
| MPI                  | 1         | 0.57%   |
| Lenovo               | 1         | 0.57%   |
| JDI                  | 1         | 0.57%   |
| HVR                  | 1         | 0.57%   |
| HannStar             | 1         | 0.57%   |
| Gigabyte Technology  | 1         | 0.57%   |
| BenQ                 | 1         | 0.57%   |
| ASUSTek Computer     | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 3         | 1.69%   |
| AU Optronics LCD Monitor AUO019C 1920x1200 286x178mm 13.3-inch          | 3         | 1.69%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch            | 2         | 1.13%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                       | 2         | 1.13%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                        | 2         | 1.13%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                       | 2         | 1.13%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                     | 2         | 1.13%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                       | 2         | 1.13%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                   | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch          | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch           | 2         | 1.13%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                    | 2         | 1.13%   |
| WST KL.1350W.005 WST2C34 2256x1504 285x190mm 13.5-inch                  | 1         | 0.56%   |
| Vizio D50-D1 VIZ1004 1920x1080 1100x620mm 49.7-inch                     | 1         | 0.56%   |
| ViewSonic VX2758-Series VSCA738 2560x1440 598x336mm 27.0-inch           | 1         | 0.56%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch             | 1         | 0.56%   |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch                 | 1         | 0.56%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                 | 1         | 0.56%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                 | 1         | 0.56%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                 | 1         | 0.56%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch                 | 1         | 0.56%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                 | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch    | 1         | 0.56%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch       | 1         | 0.56%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch       | 1         | 0.56%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch       | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4160 3000x2000 285x190mm 13.5-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch   | 1         | 0.56%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 600x340mm 27.2-inch      | 1         | 0.56%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch     | 1         | 0.56%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch       | 1         | 0.56%   |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch       | 1         | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 0.56%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                       | 1         | 0.56%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                | 1         | 0.56%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                 | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 62        | 37.58%  |
| 3840x2160 (4K)     | 27        | 16.36%  |
| 2560x1440 (QHD)    | 18        | 10.91%  |
| 1366x768 (WXGA)    | 11        | 6.67%   |
| 2880x1800          | 8         | 4.85%   |
| 1920x1200 (WUXGA)  | 8         | 4.85%   |
| 2560x1600          | 7         | 4.24%   |
| 1280x1024 (SXGA)   | 5         | 3.03%   |
| 2560x1080          | 4         | 2.42%   |
| 2256x1504          | 3         | 1.82%   |
| 3440x1440          | 2         | 1.21%   |
| 1680x1050 (WSXGA+) | 2         | 1.21%   |
| 3840x2400          | 1         | 0.61%   |
| 3000x2000          | 1         | 0.61%   |
| 2160x1200          | 1         | 0.61%   |
| 1920x1280          | 1         | 0.61%   |
| 1600x900 (HD+)     | 1         | 0.61%   |
| 1440x900 (WXGA+)   | 1         | 0.61%   |
| 1280x720 (HD)      | 1         | 0.61%   |
| 1024x600           | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 18.13%  |
| 14      | 25        | 14.62%  |
| 13      | 20        | 11.7%   |
| 27      | 18        | 10.53%  |
| 24      | 16        | 9.36%   |
| 23      | 12        | 7.02%   |
| 17      | 8         | 4.68%   |
| 12      | 7         | 4.09%   |
| 34      | 6         | 3.51%   |
| 31      | 6         | 3.51%   |
| 16      | 4         | 2.34%   |
| 21      | 3         | 1.75%   |
| 25      | 2         | 1.17%   |
| 22      | 2         | 1.17%   |
| 19      | 2         | 1.17%   |
| 84      | 1         | 0.58%   |
| 49      | 1         | 0.58%   |
| 46      | 1         | 0.58%   |
| 38      | 1         | 0.58%   |
| 28      | 1         | 0.58%   |
| 20      | 1         | 0.58%   |
| 11      | 1         | 0.58%   |
| 10      | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 64        | 38.55%  |
| 501-600     | 43        | 25.9%   |
| 201-300     | 27        | 16.27%  |
| 601-700     | 8         | 4.82%   |
| 351-400     | 7         | 4.22%   |
| 701-800     | 6         | 3.61%   |
| 401-500     | 6         | 3.61%   |
| 1001-1500   | 2         | 1.2%    |
| 801-900     | 1         | 0.6%    |
| 1501-2000   | 1         | 0.6%    |
| Unknown     | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 104       | 69.33%  |
| 16/10 | 29        | 19.33%  |
| 21/9  | 6         | 4%      |
| 5/4   | 5         | 3.33%   |
| 3/2   | 5         | 3.33%   |
| 1.00  | 1         | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 32        | 18.71%  |
| 101-110        | 32        | 18.71%  |
| 201-250        | 25        | 14.62%  |
| 301-350        | 18        | 10.53%  |
| 351-500        | 13        | 7.6%    |
| 71-80          | 12        | 7.02%   |
| 251-300        | 8         | 4.68%   |
| 61-70          | 7         | 4.09%   |
| 151-200        | 5         | 2.92%   |
| 121-130        | 4         | 2.34%   |
| 111-120        | 4         | 2.34%   |
| 141-150        | 3         | 1.75%   |
| More than 1000 | 2         | 1.17%   |
| 501-1000       | 2         | 1.17%   |
| 51-60          | 1         | 0.58%   |
| 41-50          | 1         | 0.58%   |
| 131-140        | 1         | 0.58%   |
| Unknown        | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 43        | 26.88%  |
| 121-160       | 39        | 24.38%  |
| 161-240       | 38        | 23.75%  |
| 101-120       | 21        | 13.13%  |
| More than 240 | 16        | 10%     |
| 1-50          | 2         | 1.25%   |
| Unknown       | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 111       | 64.91%  |
| 2     | 32        | 18.71%  |
| 0     | 23        | 13.45%  |
| 3     | 5         | 2.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 108       | 45.19%  |
| Realtek Semiconductor             | 84        | 35.15%  |
| Qualcomm Atheros                  | 9         | 3.77%   |
| MediaTek                          | 7         | 2.93%   |
| Broadcom                          | 5         | 2.09%   |
| Aquantia                          | 4         | 1.67%   |
| TP-Link                           | 2         | 0.84%   |
| Qualcomm                          | 2         | 0.84%   |
| Microsoft                         | 2         | 0.84%   |
| Lenovo                            | 2         | 0.84%   |
| Xiaomi                            | 1         | 0.42%   |
| Texas Instruments                 | 1         | 0.42%   |
| Standard Microsystems             | 1         | 0.42%   |
| Ralink Technology                 | 1         | 0.42%   |
| Ralink                            | 1         | 0.42%   |
| QinHeng Electronics               | 1         | 0.42%   |
| Pulse-Eight                       | 1         | 0.42%   |
| Oculus VR                         | 1         | 0.42%   |
| ICS Advent                        | 1         | 0.42%   |
| Google                            | 1         | 0.42%   |
| Fibocom                           | 1         | 0.42%   |
| Ericsson Business Mobile Networks | 1         | 0.42%   |
| D-Link System                     | 1         | 0.42%   |
| D-Link                            | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 53        | 19.2%   |
| Intel Wi-Fi 6 AX200                                               | 21        | 7.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 6.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 3.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 8         | 2.9%    |
| Intel Wireless 8260                                               | 6         | 2.17%   |
| Intel Wireless 7265                                               | 6         | 2.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 2.17%   |
| Intel I211 Gigabit Network Connection                             | 6         | 2.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5         | 1.81%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.81%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.81%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 4         | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.45%   |
| Intel Wireless-AC 9260                                            | 3         | 1.09%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.09%   |
| Intel Wireless 7260                                               | 3         | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.09%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 3         | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.72%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 0.72%   |
| Intel Wireless 3165                                               | 2         | 0.72%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.72%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 87        | 69.6%   |
| Realtek Semiconductor | 8         | 6.4%    |
| Qualcomm Atheros      | 8         | 6.4%    |
| MediaTek              | 7         | 5.6%    |
| Broadcom              | 4         | 3.2%    |
| TP-Link               | 2         | 1.6%    |
| Qualcomm              | 2         | 1.6%    |
| Microsoft             | 2         | 1.6%    |
| Ralink Technology     | 1         | 0.8%    |
| Ralink                | 1         | 0.8%    |
| Fibocom               | 1         | 0.8%    |
| D-Link System         | 1         | 0.8%    |
| D-Link                | 1         | 0.8%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 21        | 16.8%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 8         | 6.4%    |
| Intel Wireless 8260                                            | 6         | 4.8%    |
| Intel Wireless 7265                                            | 6         | 4.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 4.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5         | 4%      |
| Intel Wi-Fi 6 AX201                                            | 5         | 4%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 4%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 4         | 3.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 3.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 3.2%    |
| Intel Wireless-AC 9260                                         | 3         | 2.4%    |
| Intel Wireless 8265 / 8275                                     | 3         | 2.4%    |
| Intel Wireless 7260                                            | 3         | 2.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 2.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.4%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 2.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.6%    |
| Microsoft Xbox 360 Wireless Adapter                            | 2         | 1.6%    |
| Intel Wireless 3165                                            | 2         | 1.6%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.8%    |
| TP-Link 802.11ac NIC                                           | 1         | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.8%    |
| Realtek 802.11ac NIC                                           | 1         | 0.8%    |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.8%    |
| Ralink RT2800 802.11n PCI                                      | 1         | 0.8%    |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.8%    |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.8%    |
| Intel Wireless 3160                                            | 1         | 0.8%    |
| Intel 700 Series Chipset Family Wi-Fi                          | 1         | 0.8%    |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 78        | 56.52%  |
| Intel                 | 46        | 33.33%  |
| Aquantia              | 4         | 2.9%    |
| Qualcomm Atheros      | 2         | 1.45%   |
| Lenovo                | 2         | 1.45%   |
| Broadcom              | 2         | 1.45%   |
| Xiaomi                | 1         | 0.72%   |
| Standard Microsystems | 1         | 0.72%   |
| ICS Advent            | 1         | 0.72%   |
| Google                | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 53        | 36.3%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 12.33%  |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 7.53%   |
| Intel I211 Gigabit Network Connection                             | 6         | 4.11%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.42%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 3.42%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.74%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 2.05%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.37%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.37%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.37%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.37%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.37%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.68%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.68%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.68%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.68%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.68%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.68%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.68%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.68%   |
| ICS Advent 10/100M LAN                                            | 1         | 0.68%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.68%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.68%   |
| Aquantia AQC100 10G Ethernet MAC controller [AQtion]              | 1         | 0.68%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 124       | 49.6%   |
| WiFi     | 121       | 48.4%   |
| Modem    | 5         | 2%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 61.05%  |
| Ethernet | 67        | 38.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 83        | 49.7%   |
| 2     | 73        | 43.71%  |
| 0     | 6         | 3.59%   |
| 3     | 4         | 2.4%    |
| 4     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 121       | 71.6%   |
| Yes  | 48        | 28.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 79        | 66.95%  |
| Realtek Semiconductor           | 9         | 7.63%   |
| MediaTek                        | 5         | 4.24%   |
| Qualcomm Atheros Communications | 4         | 3.39%   |
| Cambridge Silicon Radio         | 4         | 3.39%   |
| ASUSTek Computer                | 4         | 3.39%   |
| Apple                           | 4         | 3.39%   |
| Broadcom                        | 3         | 2.54%   |
| Foxconn / Hon Hai               | 2         | 1.69%   |
| USI                             | 1         | 0.85%   |
| Lite-On Technology              | 1         | 0.85%   |
| IMC Networks                    | 1         | 0.85%   |
| HTC (High Tech Computer)        | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 19        | 16.1%   |
| Intel Bluetooth wireless interface                                   | 17        | 14.41%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 11        | 9.32%   |
| Intel AX201 Bluetooth                                                | 11        | 9.32%   |
| Realtek Bluetooth Radio                                              | 9         | 7.63%   |
| Intel Bluetooth Device                                               | 9         | 7.63%   |
| Intel AX210 Bluetooth                                                | 6         | 5.08%   |
| MediaTek Wireless_Device                                             | 5         | 4.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 4         | 3.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 2.54%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 2.54%   |
| Apple Bluetooth Host Controller                                      | 3         | 2.54%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2         | 1.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 1.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 1.69%   |
| USI Bluetooth Device                                                 | 1         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 0.85%   |
| IMC Networks Bluetooth Device                                        | 1         | 0.85%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.85%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1         | 0.85%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 1         | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 0.85%   |
| ASUS Broadcom Bluetooth 2.1                                          | 1         | 0.85%   |
| ASUS ASUS USB-BT500                                                  | 1         | 0.85%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 98        | 37.69%  |
| AMD                                  | 68        | 26.15%  |
| Nvidia                               | 42        | 16.15%  |
| C-Media Electronics                  | 7         | 2.69%   |
| Lenovo                               | 4         | 1.54%   |
| Creative Technology                  | 4         | 1.54%   |
| Texas Instruments                    | 3         | 1.15%   |
| Sennheiser Communications            | 3         | 1.15%   |
| Kingston Technology                  | 3         | 1.15%   |
| Synaptics                            | 2         | 0.77%   |
| Realtek Semiconductor                | 2         | 0.77%   |
| Razer USA                            | 2         | 0.77%   |
| Focusrite-Novation                   | 2         | 0.77%   |
| Trust                                | 1         | 0.38%   |
| Thomann                              | 1         | 0.38%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.38%   |
| Sony                                 | 1         | 0.38%   |
| Shure                                | 1         | 0.38%   |
| Schiit Audio                         | 1         | 0.38%   |
| Scarlett                             | 1         | 0.38%   |
| Satechi                              | 1         | 0.38%   |
| PreSonus Audio Electronics           | 1         | 0.38%   |
| Logitech                             | 1         | 0.38%   |
| GYROCOM C&C                          | 1         | 0.38%   |
| Edifier Technology                   | 1         | 0.38%   |
| Creative Labs                        | 1         | 0.38%   |
| Corsair                              | 1         | 0.38%   |
| Conexant Systems                     | 1         | 0.38%   |
| ASUSTek Computer                     | 1         | 0.38%   |
| ASRock                               | 1         | 0.38%   |
| Apogee Electronics                   | 1         | 0.38%   |
| Antlion Audio                        | 1         | 0.38%   |
| (LCS) USB Audio Device               | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 30        | 9.49%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 23        | 7.28%   |
| AMD Starship/Matisse HD Audio Controller                                | 20        | 6.33%   |
| Intel Sunrise Point-LP HD Audio                                         | 16        | 5.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 9         | 2.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 9         | 2.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 8         | 2.53%   |
| Intel Cannon Lake PCH cAVS                                              | 7         | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 7         | 2.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 6         | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 6         | 1.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 6         | 1.9%    |
| AMD Navi 10 HDMI Audio                                                  | 6         | 1.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 6         | 1.9%    |
| Nvidia TU106 High Definition Audio Controller                           | 5         | 1.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 5         | 1.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 5         | 1.58%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 5         | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                         | 4         | 1.27%   |
| Nvidia GK104 HDMI Audio Controller                                      | 4         | 1.27%   |
| Nvidia GA106 High Definition Audio Controller                           | 4         | 1.27%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 1.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 4         | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                           | 3         | 0.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 3         | 0.95%   |
| Nvidia GA104 High Definition Audio Controller                           | 3         | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 3         | 0.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 3         | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                            | 3         | 0.95%   |
| Intel Comet Lake PCH cAVS                                               | 3         | 0.95%   |
| Intel Broadwell-U Audio Controller                                      | 3         | 0.95%   |
| Intel 200 Series PCH HD Audio                                           | 3         | 0.95%   |
| Creative Technology SoundBlaster Live! 24-bit External SB0490           | 3         | 0.95%   |
| Texas Instruments PCM2902 Audio Codec                                   | 2         | 0.63%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 0.63%   |
| Sennheiser Communications Headset [PC 8]                                | 2         | 0.63%   |
| Realtek Semiconductor USB Audio                                         | 2         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                           | 2         | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                           | 2         | 0.63%   |
| Nvidia GM204 High Definition Audio Controller                           | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 40        | 21.74%  |
| SK hynix                     | 23        | 12.5%   |
| Kingston                     | 23        | 12.5%   |
| Micron Technology            | 22        | 11.96%  |
| Corsair                      | 19        | 10.33%  |
| G.Skill                      | 13        | 7.07%   |
| Crucial                      | 13        | 7.07%   |
| Team                         | 6         | 3.26%   |
| Unknown (ABCD)               | 5         | 2.72%   |
| Unknown                      | 5         | 2.72%   |
| A-DATA Technology            | 4         | 2.17%   |
| Ramaxel Technology           | 2         | 1.09%   |
| GOODRAM                      | 2         | 1.09%   |
| AMD                          | 2         | 1.09%   |
| Strontium                    | 1         | 0.54%   |
| Patriot Memory (PDP Systems) | 1         | 0.54%   |
| Patriot                      | 1         | 0.54%   |
| Avant                        | 1         | 0.54%   |
| Unknown                      | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 2.01%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 3         | 1.51%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.51%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 3         | 1.51%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 3         | 1.51%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.01%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.01%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.01%   |
| Samsung RAM M471A2K43BB1-CPB 16384MB SODIMM DDR4 2133MT/s        | 2         | 1.01%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.01%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.01%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 2         | 1.01%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.01%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.01%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 1.01%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 1.01%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 1.01%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 2         | 1.01%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s           | 2         | 1.01%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.5%    |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.5%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.5%    |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                    | 1         | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s               | 1         | 0.5%    |
| Team RAM TEAMGROUP-UD4-2666 16384MB DIMM DDR4 2933MT/s           | 1         | 0.5%    |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.5%    |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s               | 1         | 0.5%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.5%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                     | 1         | 0.5%    |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.5%    |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.5%    |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.5%    |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.5%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.5%    |
| SK hynix RAM HMA851S6CJR6N-XN 4096MB SODIMM DDR4 3200MT/s        | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 97        | 61.39%  |
| DDR3   | 26        | 16.46%  |
| LPDDR4 | 14        | 8.86%   |
| LPDDR5 | 10        | 6.33%   |
| LPDDR3 | 6         | 3.8%    |
| DDR5   | 4         | 2.53%   |
| SDRAM  | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 47.83%  |
| DIMM         | 54        | 33.54%  |
| Row Of Chips | 26        | 16.15%  |
| Chip         | 2         | 1.24%   |
| RIMM         | 1         | 0.62%   |
| Unknown      | 1         | 0.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 74        | 42.05%  |
| 16384 | 51        | 28.98%  |
| 4096  | 23        | 13.07%  |
| 32768 | 22        | 12.5%   |
| 2048  | 5         | 2.84%   |
| 1024  | 1         | 0.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 43        | 25%     |
| 1600    | 19        | 11.05%  |
| 2667    | 18        | 10.47%  |
| 2400    | 14        | 8.14%   |
| 2133    | 13        | 7.56%   |
| 6400    | 10        | 5.81%   |
| 3600    | 9         | 5.23%   |
| 4267    | 7         | 4.07%   |
| 3000    | 5         | 2.91%   |
| 1867    | 5         | 2.91%   |
| 3733    | 4         | 2.33%   |
| 1333    | 3         | 1.74%   |
| 4800    | 2         | 1.16%   |
| 4266    | 2         | 1.16%   |
| 3400    | 2         | 1.16%   |
| 3334    | 2         | 1.16%   |
| 3266    | 2         | 1.16%   |
| 2933    | 2         | 1.16%   |
| 6000    | 1         | 0.58%   |
| 5600    | 1         | 0.58%   |
| 3866    | 1         | 0.58%   |
| 3666    | 1         | 0.58%   |
| 3534    | 1         | 0.58%   |
| 2800    | 1         | 0.58%   |
| 2134    | 1         | 0.58%   |
| 2132    | 1         | 0.58%   |
| 1066    | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Xerox  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Xerox Phaser 6125N | 1         | 100%    |

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
| Chicony Electronics           | 19        | 18.1%   |
| Microdia                      | 13        | 12.38%  |
| Logitech                      | 13        | 12.38%  |
| IMC Networks                  | 13        | 12.38%  |
| Realtek Semiconductor         | 11        | 10.48%  |
| Acer                          | 9         | 8.57%   |
| Bison Electronics             | 6         | 5.71%   |
| Sunplus Innovation Technology | 4         | 3.81%   |
| Quanta                        | 3         | 2.86%   |
| MacroSilicon                  | 3         | 2.86%   |
| Lite-On Technology            | 3         | 2.86%   |
| Apple                         | 2         | 1.9%    |
| Syntek                        | 1         | 0.95%   |
| SunplusIT                     | 1         | 0.95%   |
| Microsoft                     | 1         | 0.95%   |
| Luxvisions Innotech Limited   | 1         | 0.95%   |
| Alcor Micro                   | 1         | 0.95%   |
| 2M UVC CAMERA                 | 1         | 0.95%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 12        | 11.32%  |
| Microdia Integrated_Webcam_HD                     | 6         | 5.66%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 6         | 5.66%   |
| Realtek Integrated_Webcam_HD                      | 5         | 4.72%   |
| IMC Networks Integrated Camera                    | 5         | 4.72%   |
| Chicony HP HD Camera                              | 4         | 3.77%   |
| Acer Integrated Camera                            | 4         | 3.77%   |
| MacroSilicon USB Video                            | 3         | 2.83%   |
| Logitech HD Pro Webcam C920                       | 3         | 2.83%   |
| Bison Integrated Camera                           | 3         | 2.83%   |
| Sunplus Integrated_Webcam_FHD                     | 2         | 1.89%   |
| Realtek Laptop Camera                             | 2         | 1.89%   |
| Quanta VGA WebCam                                 | 2         | 1.89%   |
| Microdia Webcam Vitade AF                         | 2         | 1.89%   |
| Logitech Webcam C270                              | 2         | 1.89%   |
| Lite-On Integrated Camera                         | 2         | 1.89%   |
| Acer Integrated IR Camera                         | 2         | 1.89%   |
| Acer HD Webcam                                    | 2         | 1.89%   |
| Syntek Integrated Camera                          | 1         | 0.94%   |
| SunplusIT HP TrueVision HD Camera                 | 1         | 0.94%   |
| Sunplus Integrated_Webcam_HD                      | 1         | 0.94%   |
| Sunplus HD WebCam                                 | 1         | 0.94%   |
| Realtek TV Camera                                 | 1         | 0.94%   |
| Realtek Realtek USB MIC                           | 1         | 0.94%   |
| Realtek Lenovo EasyCamera                         | 1         | 0.94%   |
| Realtek Integrated Webcam                         | 1         | 0.94%   |
| Realtek EasyCamera                                | 1         | 0.94%   |
| Quanta HP True Vision HD Camera                   | 1         | 0.94%   |
| Microsoft LifeCam HD-3000                         | 1         | 0.94%   |
| Microdia USB 2.0 Camera                           | 1         | 0.94%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 0.94%   |
| Microdia Integrated Webcam                        | 1         | 0.94%   |
| Microdia HP Integrated Webcam                     | 1         | 0.94%   |
| Microdia Camera                                   | 1         | 0.94%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 0.94%   |
| Logitech Webcam Pro 9000                          | 1         | 0.94%   |
| Logitech Webcam C930e                             | 1         | 0.94%   |
| Logitech Webcam C310                              | 1         | 0.94%   |
| Logitech Webcam C120                              | 1         | 0.94%   |
| Logitech StreamCam                                | 1         | 0.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 44%     |
| Validity Sensors           | 7         | 28%     |
| Shenzhen Goodix Technology | 5         | 20%     |
| Gingytech                  | 1         | 4%      |
| Focal-systems.Corp         | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 5         | 20%     |
| Shenzhen Goodix Fingerprint Reader                       | 4         | 16%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 12%     |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 8%      |
| Synaptics UWP WBDI Device                                | 2         | 8%      |
| Synaptics UWP WBDI                                       | 2         | 8%      |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 4%      |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 4%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4%      |
| Shenzhen Goodix  Fingerprint Device                      | 1         | 4%      |
| Gingytech Fingerprint sensor                             | 1         | 4%      |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 10        | 62.5%   |
| Broadcom    | 3         | 18.75%  |
| Yubico.com  | 2         | 12.5%   |
| Upek        | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 98        | 56.98%  |
| 1     | 47        | 27.33%  |
| 2     | 24        | 13.95%  |
| 4     | 2         | 1.16%   |
| 3     | 1         | 0.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 23        | 22.77%  |
| Multimedia controller    | 21        | 20.79%  |
| Graphics card            | 18        | 17.82%  |
| Chipcard                 | 12        | 11.88%  |
| Net/wireless             | 8         | 7.92%   |
| Bluetooth                | 5         | 4.95%   |
| Unassigned class         | 3         | 2.97%   |
| Camera                   | 3         | 2.97%   |
| Modem                    | 2         | 1.98%   |
| Card reader              | 2         | 1.98%   |
| Storage/ata              | 1         | 0.99%   |
| Network                  | 1         | 0.99%   |
| Dvb card                 | 1         | 0.99%   |
| Communication controller | 1         | 0.99%   |

