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

Total: 222

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| NixOS 22.11                      | 50        | 29.24%  |
| NixOS 22.05                      | 37        | 21.64%  |
| NixOS 23.05                      | 29        | 16.96%  |
| NixOS 21.11                      | 18        | 10.53%  |
| NixOS                            | 5         | 2.92%   |
| NixOS 23.11                      | 2         | 1.17%   |
| NixOS 21.05pre-git               | 2         | 1.17%   |
| NixOS 20.09pre-git               | 2         | 1.17%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.58%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.58%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.58%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.58%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.58%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.58%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.58%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.58%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.58%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.58%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.58%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.58%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.58%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.58%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.58%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.58%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.58%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.58%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.58%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.58%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.58%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.58%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.58%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.58%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.58%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 153       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version     | Computers | Percent |
|-------------|-----------|---------|
| 5.15.74     | 5         | 2.73%   |
| 6.3.3       | 4         | 2.19%   |
| 5.15.86     | 4         | 2.19%   |
| 5.15.43     | 4         | 2.19%   |
| 6.3.1       | 3         | 1.64%   |
| 6.2.0-rc6   | 3         | 1.64%   |
| 6.1.0       | 3         | 1.64%   |
| 6.0.11      | 3         | 1.64%   |
| 6.0.10      | 3         | 1.64%   |
| 5.15.82     | 3         | 1.64%   |
| 5.15.72     | 3         | 1.64%   |
| 5.15.68     | 3         | 1.64%   |
| 5.15.47     | 3         | 1.64%   |
| 5.15.26     | 3         | 1.64%   |
| 6.1.27      | 2         | 1.09%   |
| 6.1.24      | 2         | 1.09%   |
| 6.1.1       | 2         | 1.09%   |
| 5.8.1-zen1  | 2         | 1.09%   |
| 5.19.14     | 2         | 1.09%   |
| 5.18.19     | 2         | 1.09%   |
| 5.17.1      | 2         | 1.09%   |
| 5.16.8-zen1 | 2         | 1.09%   |
| 5.16.15     | 2         | 1.09%   |
| 5.15.96     | 2         | 1.09%   |
| 5.15.92     | 2         | 1.09%   |
| 5.15.90     | 2         | 1.09%   |
| 5.15.85     | 2         | 1.09%   |
| 5.15.64     | 2         | 1.09%   |
| 5.15.32     | 2         | 1.09%   |
| 5.15.25     | 2         | 1.09%   |
| 5.15.109    | 2         | 1.09%   |
| 5.15.107    | 2         | 1.09%   |
| 5.13.7      | 2         | 1.09%   |
| 5.13.2      | 2         | 1.09%   |
| 5.12.15     | 2         | 1.09%   |
| 5.10.102    | 2         | 1.09%   |
| 6.2.9-lqx1  | 1         | 0.55%   |
| 6.2.9       | 1         | 0.55%   |
| 6.2.8       | 1         | 0.55%   |
| 6.2.7       | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.74  | 5         | 2.73%   |
| 6.3.3    | 4         | 2.19%   |
| 6.2.0    | 4         | 2.19%   |
| 6.1.0    | 4         | 2.19%   |
| 6.0.10   | 4         | 2.19%   |
| 5.15.86  | 4         | 2.19%   |
| 5.15.43  | 4         | 2.19%   |
| 6.3.1    | 3         | 1.64%   |
| 6.0.11   | 3         | 1.64%   |
| 5.15.82  | 3         | 1.64%   |
| 5.15.72  | 3         | 1.64%   |
| 5.15.68  | 3         | 1.64%   |
| 5.15.47  | 3         | 1.64%   |
| 5.15.26  | 3         | 1.64%   |
| 6.2.9    | 2         | 1.09%   |
| 6.2.11   | 2         | 1.09%   |
| 6.1.27   | 2         | 1.09%   |
| 6.1.24   | 2         | 1.09%   |
| 6.1.1    | 2         | 1.09%   |
| 6.0.2    | 2         | 1.09%   |
| 5.8.1    | 2         | 1.09%   |
| 5.19.14  | 2         | 1.09%   |
| 5.18.19  | 2         | 1.09%   |
| 5.17.1   | 2         | 1.09%   |
| 5.16.8   | 2         | 1.09%   |
| 5.16.15  | 2         | 1.09%   |
| 5.15.96  | 2         | 1.09%   |
| 5.15.92  | 2         | 1.09%   |
| 5.15.90  | 2         | 1.09%   |
| 5.15.85  | 2         | 1.09%   |
| 5.15.83  | 2         | 1.09%   |
| 5.15.64  | 2         | 1.09%   |
| 5.15.32  | 2         | 1.09%   |
| 5.15.25  | 2         | 1.09%   |
| 5.15.109 | 2         | 1.09%   |
| 5.15.107 | 2         | 1.09%   |
| 5.13.7   | 2         | 1.09%   |
| 5.13.2   | 2         | 1.09%   |
| 5.12.15  | 2         | 1.09%   |
| 5.11.16  | 2         | 1.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 59        | 33.71%  |
| 6.1     | 17        | 9.71%   |
| 5.10    | 14        | 8%      |
| 6.2     | 13        | 7.43%   |
| 6.0     | 13        | 7.43%   |
| 5.16    | 8         | 4.57%   |
| 6.3     | 7         | 4%      |
| 5.4     | 7         | 4%      |
| 5.19    | 7         | 4%      |
| 5.8     | 6         | 3.43%   |
| 5.18    | 5         | 2.86%   |
| 5.13    | 4         | 2.29%   |
| 5.7     | 3         | 1.71%   |
| 5.17    | 3         | 1.71%   |
| 5.12    | 3         | 1.71%   |
| 5.14    | 2         | 1.14%   |
| 5.11    | 2         | 1.14%   |
| 4.19    | 2         | 1.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 148       | 96.73%  |
| aarch64 | 4         | 2.61%   |
| i686    | 1         | 0.65%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 88        | 55%     |
| sway         | 16        | 10%     |
| KDE5         | 13        | 8.13%   |
| GNOME        | 13        | 8.13%   |
| XFCE         | 7         | 4.38%   |
| none+i3      | 6         | 3.75%   |
| KDE          | 5         | 3.13%   |
| Hyprland     | 5         | 3.13%   |
| none+xmonad  | 2         | 1.25%   |
| none+awesome | 2         | 1.25%   |
| X-Generic    | 1         | 0.63%   |
| none+bspwm   | 1         | 0.63%   |
| MATE         | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 51.25%  |
| X11     | 33        | 20.63%  |
| Wayland | 32        | 20%     |
| Tty     | 13        | 8.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 98        | 63.23%  |
| LightDM | 23        | 14.84%  |
| SDDM    | 19        | 12.26%  |
| GDM     | 15        | 9.68%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 68        | 43.87%  |
| Unknown    | 56        | 36.13%  |
| en_GB      | 7         | 4.52%   |
| en_DK      | 4         | 2.58%   |
| ru_RU      | 3         | 1.94%   |
| fr_FR      | 3         | 1.94%   |
| en_AU      | 3         | 1.94%   |
| de_DE      | 3         | 1.94%   |
| de_CH      | 2         | 1.29%   |
| ro_RO      | 1         | 0.65%   |
| pt_BR      | 1         | 0.65%   |
| lv_LV      | 1         | 0.65%   |
| it_IT      | 1         | 0.65%   |
| en_IE.UTF8 | 1         | 0.65%   |
| en_CA      | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 133       | 85.81%  |
| BIOS | 22        | 14.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 81        | 51.59%  |
| Btrfs   | 25        | 15.92%  |
| Xfs     | 17        | 10.83%  |
| Zfs     | 16        | 10.19%  |
| Tmpfs   | 11        | 7.01%   |
| Unknown | 6         | 3.82%   |
| Ext2    | 1         | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 144       | 92.31%  |
| Unknown | 8         | 5.13%   |
| MBR     | 4         | 2.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 76.43%  |
| Yes       | 37        | 23.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 67.97%  |
| Yes       | 49        | 32.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 33        | 21.57%  |
| ASUSTek Computer                     | 30        | 19.61%  |
| Dell                                 | 19        | 12.42%  |
| MSI                                  | 13        | 8.5%    |
| Gigabyte Technology                  | 11        | 7.19%   |
| Hewlett-Packard                      | 8         | 5.23%   |
| ASRock                               | 6         | 3.92%   |
| Acer                                 | 6         | 3.92%   |
| Apple                                | 4         | 2.61%   |
| GPD                                  | 3         | 1.96%   |
| Supermicro                           | 2         | 1.31%   |
| Raspberry Pi Foundation              | 2         | 1.31%   |
| Pine Microsystems                    | 2         | 1.31%   |
| Intel                                | 2         | 1.31%   |
| Framework                            | 2         | 1.31%   |
| Toshiba                              | 1         | 0.65%   |
| Teclast                              | 1         | 0.65%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.65%   |
| OBSIDIAN-PC                          | 1         | 0.65%   |
| MECHREVO                             | 1         | 0.65%   |
| MACHENIKE                            | 1         | 0.65%   |
| Hardkernel                           | 1         | 0.65%   |
| EVGA                                 | 1         | 0.65%   |
| Blackview                            | 1         | 0.65%   |
| Avell High Performance               | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo 13w Yoga 82S1                       | 3         | 1.96%   |
| Pine Microsystems Pine64 PinePhone (1.2)   | 2         | 1.31%   |
| MSI MS-7C56                                | 2         | 1.31%   |
| MSI MS-7C37                                | 2         | 1.31%   |
| Gigabyte B550I AORUS PRO AX                | 2         | 1.31%   |
| Gigabyte B450M DS3H                        | 2         | 1.31%   |
| Dell Latitude 7420                         | 2         | 1.31%   |
| ASUS Zenbook UX3402ZA_UX3402ZA             | 2         | 1.31%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 1.31%   |
| ASUS All Series                            | 2         | 1.31%   |
| Apple MacBookPro11,5                       | 2         | 1.31%   |
| Toshiba Satellite L50-B                    | 1         | 0.65%   |
| Teclast F5                                 | 1         | 0.65%   |
| Supermicro X8DT6                           | 1         | 0.65%   |
| Supermicro X10SLL-F                        | 1         | 0.65%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.65%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 1         | 0.65%   |
| RPi Raspberry Pi 3 Model B+                | 1         | 0.65%   |
| OBSIDIAN-PC N13_N140ZU                     | 1         | 0.65%   |
| MSI MS-7C95                                | 1         | 0.65%   |
| MSI MS-7C91                                | 1         | 0.65%   |
| MSI MS-7C84                                | 1         | 0.65%   |
| MSI MS-7C35                                | 1         | 0.65%   |
| MSI MS-7B89                                | 1         | 0.65%   |
| MSI MS-7B09                                | 1         | 0.65%   |
| MSI MS-7758                                | 1         | 0.65%   |
| MSI Bravo 15 B5DD                          | 1         | 0.65%   |
| MSI Alpha 15 B5EEK                         | 1         | 0.65%   |
| MECHREVO Code01 Ver2.0                     | 1         | 0.65%   |
| MACHENIKE F117-7P                          | 1         | 0.65%   |
| Lenovo Yoga Slim 7 13ACN5 82CY             | 1         | 0.65%   |
| Lenovo Yoga 520-14IKB 81C8                 | 1         | 0.65%   |
| Lenovo ThinkPad X390 20Q0CTO1WW            | 1         | 0.65%   |
| Lenovo ThinkPad X260 20F5S6MF02            | 1         | 0.65%   |
| Lenovo ThinkPad X260 20F5S4BY00            | 1         | 0.65%   |
| Lenovo ThinkPad X250 20CLS18S0T            | 1         | 0.65%   |
| Lenovo ThinkPad X230 2333AZ2               | 1         | 0.65%   |
| Lenovo ThinkPad X230 23243E9               | 1         | 0.65%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW      | 1         | 0.65%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBCT01WW   | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 21        | 13.73%  |
| ASUS ROG                                   | 9         | 5.88%   |
| ASUS PRIME                                 | 7         | 4.58%   |
| Dell XPS                                   | 6         | 3.92%   |
| Dell Inspiron                              | 5         | 3.27%   |
| Dell Latitude                              | 4         | 2.61%   |
| Lenovo Legion                              | 3         | 1.96%   |
| Lenovo 13w                                 | 3         | 1.96%   |
| Gigabyte B450M                             | 3         | 1.96%   |
| Dell Precision                             | 3         | 1.96%   |
| ASUS Zenbook                               | 3         | 1.96%   |
| Apple MacBookPro11                         | 3         | 1.96%   |
| Acer Aspire                                | 3         | 1.96%   |
| RPi Raspberry                              | 2         | 1.31%   |
| Pine Microsystems Pine64                   | 2         | 1.31%   |
| MSI MS-7C56                                | 2         | 1.31%   |
| MSI MS-7C37                                | 2         | 1.31%   |
| Lenovo Yoga                                | 2         | 1.31%   |
| HP Spectre                                 | 2         | 1.31%   |
| HP ProBook                                 | 2         | 1.31%   |
| Gigabyte X570                              | 2         | 1.31%   |
| Gigabyte B550I                             | 2         | 1.31%   |
| Framework Laptop                           | 2         | 1.31%   |
| ASUS All                                   | 2         | 1.31%   |
| Toshiba Satellite                          | 1         | 0.65%   |
| Teclast F5                                 | 1         | 0.65%   |
| Supermicro X8DT6                           | 1         | 0.65%   |
| Supermicro X10SLL-F                        | 1         | 0.65%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.65%   |
| OBSIDIAN-PC N13                            | 1         | 0.65%   |
| MSI MS-7C95                                | 1         | 0.65%   |
| MSI MS-7C91                                | 1         | 0.65%   |
| MSI MS-7C84                                | 1         | 0.65%   |
| MSI MS-7C35                                | 1         | 0.65%   |
| MSI MS-7B89                                | 1         | 0.65%   |
| MSI MS-7B09                                | 1         | 0.65%   |
| MSI MS-7758                                | 1         | 0.65%   |
| MSI Bravo                                  | 1         | 0.65%   |
| MSI Alpha                                  | 1         | 0.65%   |
| MECHREVO Code01                            | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 29        | 18.95%  |
| 2019    | 21        | 13.73%  |
| 2021    | 18        | 11.76%  |
| 2022    | 17        | 11.11%  |
| 2018    | 17        | 11.11%  |
| 2016    | 12        | 7.84%   |
| 2017    | 8         | 5.23%   |
| 2015    | 7         | 4.58%   |
| 2013    | 6         | 3.92%   |
| 2012    | 6         | 3.92%   |
| 2014    | 4         | 2.61%   |
| Unknown | 4         | 2.61%   |
| 2023    | 1         | 0.65%   |
| 2011    | 1         | 0.65%   |
| 2010    | 1         | 0.65%   |
| 2009    | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 72        | 47.06%  |
| Desktop        | 55        | 35.95%  |
| Convertible    | 14        | 9.15%   |
| Server         | 3         | 1.96%   |
| Phone          | 2         | 1.31%   |
| System on chip | 2         | 1.31%   |
| Mini pc        | 2         | 1.31%   |
| All in one     | 2         | 1.31%   |
| Tablet         | 1         | 0.65%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 153       | 99.35%  |
| Enabled  | 1         | 0.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 152       | 99.35%  |
| Yes  | 1         | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 41        | 26.28%  |
| 16.01-24.0  | 39        | 25%     |
| 8.01-16.0   | 23        | 14.74%  |
| 64.01-256.0 | 20        | 12.82%  |
| 4.01-8.0    | 15        | 9.62%   |
| 24.01-32.0  | 9         | 5.77%   |
| 3.01-4.0    | 6         | 3.85%   |
| 0.51-1.0    | 2         | 1.28%   |
| 1.01-2.0    | 1         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 47        | 27.81%  |
| 8.01-16.0   | 28        | 16.57%  |
| 3.01-4.0    | 25        | 14.79%  |
| 2.01-3.0    | 19        | 11.24%  |
| 1.01-2.0    | 18        | 10.65%  |
| 32.01-64.0  | 8         | 4.73%   |
| 24.01-32.0  | 7         | 4.14%   |
| 16.01-24.0  | 7         | 4.14%   |
| 0.51-1.0    | 7         | 4.14%   |
| 0.01-0.5    | 2         | 1.18%   |
| 64.01-256.0 | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 87        | 55.06%  |
| 2      | 40        | 25.32%  |
| 3      | 12        | 7.59%   |
| 5      | 5         | 3.16%   |
| 6      | 4         | 2.53%   |
| 4      | 3         | 1.9%    |
| 7      | 2         | 1.27%   |
| 23     | 1         | 0.63%   |
| 17     | 1         | 0.63%   |
| 11     | 1         | 0.63%   |
| 8      | 1         | 0.63%   |
| 0      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 90.85%  |
| Yes       | 14        | 9.15%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 76.28%  |
| No        | 37        | 23.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 73.2%   |
| No        | 41        | 26.8%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 68.39%  |
| No        | 49        | 31.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 26        | 16.99%  |
| Germany     | 17        | 11.11%  |
| UK          | 12        | 7.84%   |
| France      | 11        | 7.19%   |
| Russia      | 10        | 6.54%   |
| Italy       | 9         | 5.88%   |
| Poland      | 8         | 5.23%   |
| Ukraine     | 7         | 4.58%   |
| Canada      | 7         | 4.58%   |
| Austria     | 5         | 3.27%   |
| Switzerland | 4         | 2.61%   |
| Netherlands | 4         | 2.61%   |
| Denmark     | 3         | 1.96%   |
| Czechia     | 3         | 1.96%   |
| Brazil      | 3         | 1.96%   |
| Australia   | 3         | 1.96%   |
| India       | 2         | 1.31%   |
| Belgium     | 2         | 1.31%   |
| Uruguay     | 1         | 0.65%   |
| Sweden      | 1         | 0.65%   |
| Spain       | 1         | 0.65%   |
| Slovenia    | 1         | 0.65%   |
| Serbia      | 1         | 0.65%   |
| Romania     | 1         | 0.65%   |
| Portugal    | 1         | 0.65%   |
| Peru        | 1         | 0.65%   |
| New Zealand | 1         | 0.65%   |
| Latvia      | 1         | 0.65%   |
| Kyrgyzstan  | 1         | 0.65%   |
| Japan       | 1         | 0.65%   |
| Iraq        | 1         | 0.65%   |
| Iran        | 1         | 0.65%   |
| Hungary     | 1         | 0.65%   |
| Colombia    | 1         | 0.65%   |
| China       | 1         | 0.65%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Kharkiv            | 5         | 3.03%   |
| Vienna             | 4         | 2.42%   |
| Marki              | 4         | 2.42%   |
| Frankfurt am Main  | 4         | 2.42%   |
| Plymouth           | 3         | 1.82%   |
| Milwaukee          | 3         | 1.82%   |
| Lyon               | 3         | 1.82%   |
| Cerami             | 3         | 1.82%   |
| Southampton        | 2         | 1.21%   |
| South Deerfield    | 2         | 1.21%   |
| Schaafheim         | 2         | 1.21%   |
| Richardson         | 2         | 1.21%   |
| Prague             | 2         | 1.21%   |
| Ottawa             | 2         | 1.21%   |
| Melbourne          | 2         | 1.21%   |
| London             | 2         | 1.21%   |
| Krasnodar          | 2         | 1.21%   |
| Halifax            | 2         | 1.21%   |
| Gdansk             | 2         | 1.21%   |
| Darmstadt          | 2         | 1.21%   |
| Chelyabinsk        | 2         | 1.21%   |
| Catania            | 2         | 1.21%   |
| Austin             | 2         | 1.21%   |
| Amsterdam          | 2         | 1.21%   |
| Zurich             | 1         | 0.61%   |
| Yangzhou           | 1         | 0.61%   |
| Woodford           | 1         | 0.61%   |
| Wellington         | 1         | 0.61%   |
| Warsaw             | 1         | 0.61%   |
| Villeurbanne       | 1         | 0.61%   |
| Verneuil-sur-Seine | 1         | 0.61%   |
| Valpacos           | 1         | 0.61%   |
| Trento             | 1         | 0.61%   |
| Tremestieri Etneo  | 1         | 0.61%   |
| Tottenham          | 1         | 0.61%   |
| Tolyatti           | 1         | 0.61%   |
| Tehran             | 1         | 0.61%   |
| Talas              | 1         | 0.61%   |
| Székesfehérvár  | 1         | 0.61%   |
| Stockholm          | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 62        | 123    | 26.61%  |
| SanDisk                     | 21        | 27     | 9.01%   |
| WDC                         | 19        | 41     | 8.15%   |
| Seagate                     | 18        | 51     | 7.73%   |
| Toshiba                     | 15        | 31     | 6.44%   |
| Kingston                    | 11        | 11     | 4.72%   |
| Crucial                     | 11        | 18     | 4.72%   |
| Micron Technology           | 9         | 10     | 3.86%   |
| Intel                       | 8         | 14     | 3.43%   |
| SK hynix                    | 7         | 10     | 3%      |
| Unknown                     | 5         | 8      | 2.15%   |
| HGST                        | 5         | 15     | 2.15%   |
| Apple                       | 4         | 7      | 1.72%   |
| Phison Electronics          | 3         | 6      | 1.29%   |
| Hitachi                     | 3         | 5      | 1.29%   |
| Transcend                   | 2         | 2      | 0.86%   |
| Realtek Semiconductor       | 2         | 2      | 0.86%   |
| Plextor                     | 2         | 2      | 0.86%   |
| KIOXIA                      | 2         | 3      | 0.86%   |
| Kingston Technology Company | 2         | 2      | 0.86%   |
| China                       | 2         | 2      | 0.86%   |
| ADATA Technology            | 2         | 4      | 0.86%   |
| Yangtze Memory Technologies | 1         | 1      | 0.43%   |
| Teclast                     | 1         | 2      | 0.43%   |
| SPCC                        | 1         | 1      | 0.43%   |
| Silicon Motion              | 1         | 1      | 0.43%   |
| Phison                      | 1         | 1      | 0.43%   |
| OCZ                         | 1         | 1      | 0.43%   |
| Micron/Crucial Technology   | 1         | 1      | 0.43%   |
| LITEON                      | 1         | 1      | 0.43%   |
| Lexar                       | 1         | 1      | 0.43%   |
| INNOVATION IT               | 1         | 1      | 0.43%   |
| Dogfish                     | 1         | 1      | 0.43%   |
| Corsair                     | 1         | 1      | 0.43%   |
| Biwin Storage Technology    | 1         | 1      | 0.43%   |
| BIWIN                       | 1         | 1      | 0.43%   |
| ASMT                        | 1         | 1      | 0.43%   |
| ASMedia                     | 1         | 1      | 0.43%   |
| A-DATA Technology           | 1         | 1      | 0.43%   |
| Unknown                     | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 6         | 2.14%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 1.79%   |
| SanDisk SSD PLUS 240GB                              | 4         | 1.43%   |
| Samsung SSD 860 QVO 1TB                             | 4         | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 4         | 1.43%   |
| Unknown MMC Card  32GB                              | 3         | 1.07%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3         | 1.07%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3         | 1.07%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 1.07%   |
| Samsung SSD 970 EVO 500GB                           | 3         | 1.07%   |
| Samsung SSD 860 EVO 500GB                           | 3         | 1.07%   |
| Micron MTFDKCD512TFK 512GB                          | 3         | 1.07%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 1.07%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB             | 2         | 0.71%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.71%   |
| Seagate ST3000DM001-1CH166 3TB                      | 2         | 0.71%   |
| Sandisk WD Black SN850 500GB                        | 2         | 0.71%   |
| SanDisk Ultra II 240GB SSD                          | 2         | 0.71%   |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.71%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.71%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 0.71%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.71%   |
| Samsung SSD 860 EVO 2TB                             | 2         | 0.71%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.71%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.71%   |
| Samsung SSD 840 EVO 250GB                           | 2         | 0.71%   |
| Samsung PM9A1 NVMe 1024GB                           | 2         | 0.71%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 0.71%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.71%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 0.71%   |
| HGST HTS721010A9E630 1TB                            | 2         | 0.71%   |
| Crucial CT250MX500SSD1 250GB                        | 2         | 0.71%   |
| Apple SSD SM0512G 500GB                             | 2         | 0.71%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                | 1         | 0.36%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                    | 1         | 0.36%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.36%   |
| WDC WDS200T1X0E-00AFY0 2TB                          | 1         | 0.36%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.36%   |
| WDC WD80EDAZ-11TA3A0 8TB                            | 1         | 0.36%   |
| WDC WD50EZRX-00MVLB1 5TB                            | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 51     | 33.33%  |
| WDC                 | 13        | 33     | 24.07%  |
| Toshiba             | 11        | 24     | 20.37%  |
| HGST                | 5         | 15     | 9.26%   |
| Hitachi             | 3         | 5      | 5.56%   |
| Samsung Electronics | 2         | 2      | 3.7%    |
| ASMedia             | 1         | 1      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 64     | 34.52%  |
| SanDisk             | 10        | 15     | 11.9%   |
| Crucial             | 10        | 17     | 11.9%   |
| Kingston            | 7         | 7      | 8.33%   |
| Intel               | 5         | 7      | 5.95%   |
| Apple               | 4         | 6      | 4.76%   |
| WDC                 | 2         | 3      | 2.38%   |
| Transcend           | 2         | 2      | 2.38%   |
| China               | 2         | 2      | 2.38%   |
| Toshiba             | 1         | 1      | 1.19%   |
| Teclast             | 1         | 2      | 1.19%   |
| SPCC                | 1         | 1      | 1.19%   |
| SK hynix            | 1         | 1      | 1.19%   |
| Plextor             | 1         | 1      | 1.19%   |
| OCZ                 | 1         | 1      | 1.19%   |
| Micron Technology   | 1         | 1      | 1.19%   |
| LITEON              | 1         | 1      | 1.19%   |
| INNOVATION IT       | 1         | 1      | 1.19%   |
| Dogfish             | 1         | 1      | 1.19%   |
| Corsair             | 1         | 1      | 1.19%   |
| BIWIN               | 1         | 1      | 1.19%   |
| ASMT                | 1         | 1      | 1.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 95        | 135    | 45.45%  |
| SSD  | 72        | 137    | 34.45%  |
| HDD  | 37        | 132    | 17.7%   |
| MMC  | 5         | 9      | 2.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 95        | 135    | 51.08%  |
| SATA | 81        | 261    | 43.55%  |
| SAS  | 5         | 8      | 2.69%   |
| MMC  | 5         | 9      | 2.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 59        | 109    | 48.76%  |
| 0.51-1.0   | 33        | 59     | 27.27%  |
| 1.01-2.0   | 11        | 16     | 9.09%   |
| 4.01-10.0  | 8         | 52     | 6.61%   |
| 2.01-3.0   | 6         | 12     | 4.96%   |
| 3.01-4.0   | 3         | 15     | 2.48%   |
| 10.01-20.0 | 1         | 6      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 63        | 39.87%  |
| 1-20           | 32        | 20.25%  |
| 251-500        | 15        | 9.49%   |
| 501-1000       | 12        | 7.59%   |
| 101-250        | 11        | 6.96%   |
| 1001-2000      | 10        | 6.33%   |
| More than 3000 | 7         | 4.43%   |
| 2001-3000      | 6         | 3.8%    |
| 21-50          | 2         | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 63        | 39.13%  |
| 1-20           | 42        | 26.09%  |
| 101-250        | 14        | 8.7%    |
| 501-1000       | 9         | 5.59%   |
| 51-100         | 9         | 5.59%   |
| 251-500        | 8         | 4.97%   |
| 21-50          | 8         | 4.97%   |
| 1001-2000      | 4         | 2.48%   |
| More than 3000 | 2         | 1.24%   |
| 2001-3000      | 2         | 1.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| SanDisk SSD PLUS 240GB                         | 2         | 4      | 11.76%  |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1         | 1      | 5.88%   |
| WDC WD20EARX-008FB0 2TB                        | 1         | 1      | 5.88%   |
| WDC WD10EZEX-60ZF5A0 1TB                       | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 5.88%   |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 5.88%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 5.88%   |
| Seagate ST8000VN004-2M2101 8TB                 | 1         | 3      | 5.88%   |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 870 EVO 1TB            | 1         | 1      | 5.88%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 5.88%   |
| Intel SSDSC2BW240A4 240GB                      | 1         | 1      | 5.88%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 5.88%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 5.88%   |
| ASMT 2115 160GB                                | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 17.65%  |
| Toshiba             | 2         | 2      | 11.76%  |
| Seagate             | 2         | 4      | 11.76%  |
| SanDisk             | 2         | 4      | 11.76%  |
| Samsung Electronics | 2         | 2      | 11.76%  |
| SK hynix            | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |
| Intel               | 1         | 1      | 5.88%   |
| Hitachi             | 1         | 1      | 5.88%   |
| HGST                | 1         | 1      | 5.88%   |
| ASMT                | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 33.33%  |
| Toshiba | 2         | 2      | 22.22%  |
| Seagate | 2         | 4      | 22.22%  |
| Hitachi | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 11     | 50%     |
| SSD  | 6         | 8      | 37.5%   |
| NVMe | 2         | 2      | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MG03ACA300 3TB                           | 1         | 1      | 33.33%  |
| Toshiba HDWG180 8TB                              | 1         | 4      | 33.33%  |
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 5      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 145       | 354    | 81.92%  |
| Detected | 16        | 32     | 9.04%   |
| Malfunc  | 13        | 21     | 7.34%   |
| Failed   | 3         | 6      | 1.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 70        | 31.39%  |
| Samsung Electronics          | 43        | 19.28%  |
| AMD                          | 39        | 17.49%  |
| SanDisk                      | 16        | 7.17%   |
| Micron Technology            | 8         | 3.59%   |
| Kingston Technology Company  | 7         | 3.14%   |
| SK hynix                     | 6         | 2.69%   |
| ASMedia Technology           | 5         | 2.24%   |
| Toshiba America Info Systems | 4         | 1.79%   |
| Phison Electronics           | 4         | 1.79%   |
| LSI Logic / Symbios Logic    | 3         | 1.35%   |
| Broadcom / LSI               | 3         | 1.35%   |
| ADATA Technology             | 3         | 1.35%   |
| Realtek Semiconductor        | 2         | 0.9%    |
| Micron/Crucial Technology    | 2         | 0.9%    |
| KIOXIA                       | 2         | 0.9%    |
| Yangtze Memory Technologies  | 1         | 0.45%   |
| Silicon Motion               | 1         | 0.45%   |
| Shenzhen Longsys Electronics | 1         | 0.45%   |
| Marvell Technology Group     | 1         | 0.45%   |
| Lite-On Technology           | 1         | 0.45%   |
| Biwin Storage Technology     | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 25        | 10.55%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 10.55%  |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 5.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 3.38%   |
| Micron NVMe Storage Controller                                                 | 8         | 3.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 3.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 2.53%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 2.11%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 2.11%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 2.11%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 4         | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.27%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.27%   |
| Samsung Electronics SATA controller                                            | 3         | 1.27%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.27%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.27%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.27%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.84%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.84%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.84%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.84%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 0.84%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.84%   |
| Intel Comet Lake PCH-H RAID                                                    | 2         | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.84%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 96        | 45.07%  |
| SATA | 96        | 45.07%  |
| RAID | 12        | 5.63%   |
| SAS  | 6         | 2.82%   |
| IDE  | 3         | 1.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 92        | 60.13%  |
| AMD    | 57        | 37.25%  |
| ARM    | 4         | 2.61%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 3.27%   |
| AMD Ryzen 5 3600 6-Core Processor          | 5         | 3.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 2.61%   |
| ARM Processor                              | 4         | 2.61%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 4         | 2.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 3         | 1.96%   |
| Intel 12th Gen Core i7-1260P               | 3         | 1.96%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 1.96%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 1.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 3         | 1.96%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 3         | 1.96%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 1.96%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 3         | 1.96%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 3         | 1.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 1.31%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 1.31%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 1.31%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 1.31%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 1.31%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 2         | 1.31%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 1.31%   |
| Intel 12th Gen Core i5-1240P               | 2         | 1.31%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 2         | 1.31%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 1.31%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 1.31%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 2         | 1.31%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 2         | 1.31%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 2         | 1.31%   |
| Intel Xeon W-1290P CPU @ 3.70GHz           | 1         | 0.65%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 0.65%   |
| Intel Xeon CPU L5640 @ 2.27GHz             | 1         | 0.65%   |
| Intel Xeon CPU E5606 @ 2.13GHz             | 1         | 0.65%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz        | 1         | 0.65%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz       | 1         | 0.65%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 0.65%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 0.65%   |
| Intel Core i9-9900X CPU @ 3.50GHz          | 1         | 0.65%   |
| Intel Core i7-8700 CPU @ 3.20GHz           | 1         | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 0.65%   |
| Intel Core i7-6850K CPU @ 3.60GHz          | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 35        | 22.88%  |
| Other                  | 25        | 16.34%  |
| AMD Ryzen 7            | 20        | 13.07%  |
| AMD Ryzen 5            | 20        | 13.07%  |
| Intel Core i5          | 19        | 12.42%  |
| AMD Ryzen 9            | 10        | 6.54%   |
| Intel Xeon             | 6         | 3.92%   |
| Intel Celeron          | 4         | 2.61%   |
| AMD Ryzen 7 PRO        | 4         | 2.61%   |
| Intel Core i3          | 3         | 1.96%   |
| Intel Core i9          | 2         | 1.31%   |
| AMD Ryzen Threadripper | 2         | 1.31%   |
| Intel Core m3          | 1         | 0.65%   |
| Intel Atom             | 1         | 0.65%   |
| AMD FX                 | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 48        | 31.37%  |
| 8       | 33        | 21.57%  |
| 6       | 27        | 17.65%  |
| 2       | 19        | 12.42%  |
| 12      | 11        | 7.19%   |
| Unknown | 4         | 2.61%   |
| 16      | 3         | 1.96%   |
| 10      | 3         | 1.96%   |
| 24      | 2         | 1.31%   |
| 32      | 1         | 0.65%   |
| 14      | 1         | 0.65%   |
| 1       | 1         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 147       | 96.08%  |
| Unknown | 4         | 2.61%   |
| 2       | 2         | 1.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 136       | 88.89%  |
| 1       | 13        | 8.5%    |
| Unknown | 4         | 2.61%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 152       | 98.7%   |
| 32-bit         | 1         | 0.65%   |
| Unknown        | 1         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 23.42%  |
| 0x0a50000c | 10        | 6.33%   |
| 0x306c3    | 7         | 4.43%   |
| 0x0a50000d | 7         | 4.43%   |
| 0x08701021 | 7         | 4.43%   |
| 0x806ea    | 6         | 3.8%    |
| 0x806c1    | 6         | 3.8%    |
| 0x906ea    | 5         | 3.16%   |
| 0x306a9    | 5         | 3.16%   |
| 0x806ec    | 4         | 2.53%   |
| 0x506e3    | 4         | 2.53%   |
| 0x08701013 | 4         | 2.53%   |
| 0x906a3    | 3         | 1.9%    |
| 0x806eb    | 3         | 1.9%    |
| 0x306d4    | 3         | 1.9%    |
| 0x0a404102 | 3         | 1.9%    |
| 0x08600106 | 3         | 1.9%    |
| 0x906e9    | 2         | 1.27%   |
| 0x806e9    | 2         | 1.27%   |
| 0x706a1    | 2         | 1.27%   |
| 0x406e3    | 2         | 1.27%   |
| 0x40661    | 2         | 1.27%   |
| 0x40651    | 2         | 1.27%   |
| 0x0a201204 | 2         | 1.27%   |
| 0x0a201016 | 2         | 1.27%   |
| 0x0a201009 | 2         | 1.27%   |
| 0x08600104 | 2         | 1.27%   |
| 0x08001138 | 2         | 1.27%   |
| 0xa0653    | 1         | 0.63%   |
| 0xa0652    | 1         | 0.63%   |
| 0x906ed    | 1         | 0.63%   |
| 0x806d1    | 1         | 0.63%   |
| 0x706a8    | 1         | 0.63%   |
| 0x406f1    | 1         | 0.63%   |
| 0x306f2    | 1         | 0.63%   |
| 0x206c2    | 1         | 0.63%   |
| 0x0a601203 | 1         | 0.63%   |
| 0x0a50000b | 1         | 0.63%   |
| 0x0a404101 | 1         | 0.63%   |
| 0x0a20120a | 1         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 27        | 17.65%  |
| Zen 3            | 26        | 16.99%  |
| Zen 2            | 18        | 11.76%  |
| Haswell          | 13        | 8.5%    |
| Unknown          | 13        | 8.5%    |
| Skylake          | 11        | 7.19%   |
| TigerLake        | 8         | 5.23%   |
| Alderlake Hybrid | 7         | 4.58%   |
| IvyBridge        | 6         | 3.92%   |
| Zen              | 4         | 2.61%   |
| Goldmont plus    | 4         | 2.61%   |
| Broadwell        | 4         | 2.61%   |
| Zen+             | 3         | 1.96%   |
| CometLake        | 3         | 1.96%   |
| Westmere         | 2         | 1.31%   |
| Icelake          | 2         | 1.31%   |
| Piledriver       | 1         | 0.65%   |
| Bonnell          | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 73        | 39.04%  |
| Nvidia                     | 57        | 30.48%  |
| AMD                        | 54        | 28.88%  |
| Matrox Electronics Systems | 2         | 1.07%   |
| ASPEED Technology          | 1         | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 13        | 6.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 8         | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 3.65%   |
| Intel UHD Graphics 620                                                                | 6         | 3.13%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 6         | 3.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 2.6%    |
| Intel HD Graphics 530                                                                 | 5         | 2.6%    |
| AMD Renoir                                                                            | 5         | 2.6%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 5         | 2.6%    |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 2.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 2.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 2.08%   |
| AMD Rembrandt [Radeon 680M]                                                           | 4         | 2.08%   |
| AMD Barcelo                                                                           | 4         | 2.08%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 3         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 1.56%   |
| Nvidia GK104 [GeForce GTX 760]                                                        | 3         | 1.56%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 3         | 1.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 1.56%   |
| Intel HD Graphics 620                                                                 | 3         | 1.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 1.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 1.04%   |
| Nvidia GM204 [GeForce GTX 970]                                                        | 2         | 1.04%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.04%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                         | 2         | 1.04%   |
| Intel HD Graphics 630                                                                 | 2         | 1.04%   |
| Intel HD Graphics 5500                                                                | 2         | 1.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 1.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 1.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 1.04%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 2         | 1.04%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                              | 2         | 1.04%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.04%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                            | 2         | 1.04%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                         | 2         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.52%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 29.22%  |
| 1 x AMD        | 35        | 22.73%  |
| 1 x Nvidia     | 23        | 14.94%  |
| Intel + Nvidia | 23        | 14.94%  |
| AMD + Nvidia   | 11        | 7.14%   |
| Other          | 5         | 3.25%   |
| 2 x AMD        | 4         | 2.6%    |
| Intel + AMD    | 3         | 1.95%   |
| 1 x Matrox     | 2         | 1.3%    |
| 2 x Intel      | 1         | 0.65%   |
| 1 x ASPEED     | 1         | 0.65%   |
| AMD + ASPEED   | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 108       | 70.13%  |
| Proprietary | 37        | 24.03%  |
| Unknown     | 9         | 5.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 60.76%  |
| 0.01-0.5   | 17        | 10.76%  |
| 7.01-8.0   | 15        | 9.49%   |
| 3.01-4.0   | 11        | 6.96%   |
| 1.01-2.0   | 11        | 6.96%   |
| 8.01-16.0  | 4         | 2.53%   |
| 0.51-1.0   | 3         | 1.9%    |
| 16.01-24.0 | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 24        | 14.81%  |
| AU Optronics         | 18        | 11.11%  |
| Samsung Electronics  | 16        | 9.88%   |
| BOE                  | 13        | 8.02%   |
| Goldstar             | 11        | 6.79%   |
| LG Display           | 10        | 6.17%   |
| Chimei Innolux       | 8         | 4.94%   |
| Acer                 | 7         | 4.32%   |
| PANDA                | 6         | 3.7%    |
| Sharp                | 5         | 3.09%   |
| CSO                  | 5         | 3.09%   |
| Hewlett-Packard      | 4         | 2.47%   |
| Apple                | 4         | 2.47%   |
| Ancor Communications | 4         | 2.47%   |
| AOC                  | 3         | 1.85%   |
| Panasonic            | 2         | 1.23%   |
| InfoVision           | 2         | 1.23%   |
| Iiyama               | 2         | 1.23%   |
| Eizo                 | 2         | 1.23%   |
| WST                  | 1         | 0.62%   |
| Vizio                | 1         | 0.62%   |
| ViewSonic            | 1         | 0.62%   |
| Unknown (AAA)        | 1         | 0.62%   |
| RTK                  | 1         | 0.62%   |
| Philips              | 1         | 0.62%   |
| NEC Computers        | 1         | 0.62%   |
| MSI                  | 1         | 0.62%   |
| MPI                  | 1         | 0.62%   |
| Lenovo               | 1         | 0.62%   |
| JDI                  | 1         | 0.62%   |
| HVR                  | 1         | 0.62%   |
| HannStar             | 1         | 0.62%   |
| Gigabyte Technology  | 1         | 0.62%   |
| BenQ                 | 1         | 0.62%   |
| ASUSTek Computer     | 1         | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO019C 1920x1200 286x178mm 13.3-inch        | 3         | 1.82%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 1.21%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch          | 2         | 1.21%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 1.21%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2         | 1.21%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 1.21%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                   | 2         | 1.21%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 1.21%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 1.21%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2         | 1.21%   |
| WST KL.1350W.003 WST2C34 2256x1504 285x190mm 13.5-inch                | 1         | 0.61%   |
| Vizio D50-D1 VIZ1004 1920x1080 1100x620mm 49.7-inch                   | 1         | 0.61%   |
| ViewSonic VX2758-Series VSCA738 2560x1440 598x336mm 27.0-inch         | 1         | 0.61%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1         | 0.61%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch  | 1         | 0.61%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.61%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 0.61%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4160 3000x2000 285x190mm 13.5-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.61%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 600x340mm 27.2-inch    | 1         | 0.61%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 0.61%   |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch     | 1         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.61%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                     | 1         | 0.61%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1         | 0.61%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch               | 1         | 0.61%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch               | 1         | 0.61%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 0.61%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 36.36%  |
| 3840x2160 (4K)     | 27        | 17.53%  |
| 2560x1440 (QHD)    | 18        | 11.69%  |
| 1366x768 (WXGA)    | 9         | 5.84%   |
| 1920x1200 (WUXGA)  | 8         | 5.19%   |
| 2560x1600          | 7         | 4.55%   |
| 2880x1800          | 5         | 3.25%   |
| 1280x1024 (SXGA)   | 5         | 3.25%   |
| 2560x1080          | 4         | 2.6%    |
| 2256x1504          | 3         | 1.95%   |
| 3440x1440          | 2         | 1.3%    |
| 1680x1050 (WSXGA+) | 2         | 1.3%    |
| 3840x2400          | 1         | 0.65%   |
| 3000x2000          | 1         | 0.65%   |
| 2160x1200          | 1         | 0.65%   |
| 1920x1280          | 1         | 0.65%   |
| 1600x900 (HD+)     | 1         | 0.65%   |
| 1440x900 (WXGA+)   | 1         | 0.65%   |
| 1280x720 (HD)      | 1         | 0.65%   |
| 1024x600           | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 16.98%  |
| 13      | 20        | 12.58%  |
| 14      | 19        | 11.95%  |
| 27      | 18        | 11.32%  |
| 24      | 16        | 10.06%  |
| 23      | 11        | 6.92%   |
| 17      | 8         | 5.03%   |
| 34      | 6         | 3.77%   |
| 31      | 6         | 3.77%   |
| 12      | 6         | 3.77%   |
| 16      | 4         | 2.52%   |
| 21      | 3         | 1.89%   |
| 25      | 2         | 1.26%   |
| 22      | 2         | 1.26%   |
| 19      | 2         | 1.26%   |
| 84      | 1         | 0.63%   |
| 49      | 1         | 0.63%   |
| 46      | 1         | 0.63%   |
| 38      | 1         | 0.63%   |
| 28      | 1         | 0.63%   |
| 20      | 1         | 0.63%   |
| 11      | 1         | 0.63%   |
| 10      | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 35.71%  |
| 501-600     | 42        | 27.27%  |
| 201-300     | 25        | 16.23%  |
| 601-700     | 8         | 5.19%   |
| 351-400     | 7         | 4.55%   |
| 701-800     | 6         | 3.9%    |
| 401-500     | 6         | 3.9%    |
| 1001-1500   | 2         | 1.3%    |
| 801-900     | 1         | 0.65%   |
| 1501-2000   | 1         | 0.65%   |
| Unknown     | 1         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 96        | 69.06%  |
| 16/10 | 26        | 18.71%  |
| 21/9  | 6         | 4.32%   |
| 5/4   | 5         | 3.6%    |
| 3/2   | 5         | 3.6%    |
| 1.00  | 1         | 0.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 17.61%  |
| 81-90          | 26        | 16.35%  |
| 201-250        | 24        | 15.09%  |
| 301-350        | 18        | 11.32%  |
| 351-500        | 13        | 8.18%   |
| 71-80          | 12        | 7.55%   |
| 251-300        | 8         | 5.03%   |
| 61-70          | 6         | 3.77%   |
| 151-200        | 5         | 3.14%   |
| 121-130        | 4         | 2.52%   |
| 111-120        | 4         | 2.52%   |
| 141-150        | 3         | 1.89%   |
| More than 1000 | 2         | 1.26%   |
| 501-1000       | 2         | 1.26%   |
| 51-60          | 1         | 0.63%   |
| 41-50          | 1         | 0.63%   |
| 131-140        | 1         | 0.63%   |
| Unknown        | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 28.38%  |
| 161-240       | 38        | 25.68%  |
| 121-160       | 32        | 21.62%  |
| 101-120       | 20        | 13.51%  |
| More than 240 | 13        | 8.78%   |
| 1-50          | 2         | 1.35%   |
| Unknown       | 1         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 101       | 63.52%  |
| 2     | 31        | 19.5%   |
| 0     | 22        | 13.84%  |
| 3     | 5         | 3.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 99        | 43.81%  |
| Realtek Semiconductor             | 82        | 36.28%  |
| Qualcomm Atheros                  | 8         | 3.54%   |
| MediaTek                          | 6         | 2.65%   |
| Broadcom                          | 5         | 2.21%   |
| Aquantia                          | 4         | 1.77%   |
| TP-Link                           | 2         | 0.88%   |
| Qualcomm                          | 2         | 0.88%   |
| Microsoft                         | 2         | 0.88%   |
| Lenovo                            | 2         | 0.88%   |
| Xiaomi                            | 1         | 0.44%   |
| Texas Instruments                 | 1         | 0.44%   |
| Standard Microsystems             | 1         | 0.44%   |
| Ralink Technology                 | 1         | 0.44%   |
| Ralink                            | 1         | 0.44%   |
| QinHeng Electronics               | 1         | 0.44%   |
| Pulse-Eight                       | 1         | 0.44%   |
| Oculus VR                         | 1         | 0.44%   |
| ICS Advent                        | 1         | 0.44%   |
| Google                            | 1         | 0.44%   |
| Fibocom                           | 1         | 0.44%   |
| Ericsson Business Mobile Networks | 1         | 0.44%   |
| D-Link System                     | 1         | 0.44%   |
| D-Link                            | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 19.54%  |
| Intel Wi-Fi 6 AX200                                               | 19        | 7.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 6.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 4.21%   |
| Intel Wireless 7265                                               | 6         | 2.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 2.3%    |
| Intel I211 Gigabit Network Connection                             | 6         | 2.3%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 2.3%    |
| Intel Ethernet Controller I225-V                                  | 5         | 1.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 4         | 1.53%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 1.53%   |
| Intel Wireless 8260                                               | 4         | 1.53%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 1.53%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.15%   |
| Intel Wireless-AC 9260                                            | 3         | 1.15%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.15%   |
| Intel Wireless 7260                                               | 3         | 1.15%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.15%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.15%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 3         | 1.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.77%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 0.77%   |
| Intel Wireless 3165                                               | 2         | 0.77%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.77%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.77%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.77%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.77%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 78        | 68.42%  |
| Realtek Semiconductor | 8         | 7.02%   |
| Qualcomm Atheros      | 7         | 6.14%   |
| MediaTek              | 6         | 5.26%   |
| Broadcom              | 4         | 3.51%   |
| TP-Link               | 2         | 1.75%   |
| Qualcomm              | 2         | 1.75%   |
| Microsoft             | 2         | 1.75%   |
| Ralink Technology     | 1         | 0.88%   |
| Ralink                | 1         | 0.88%   |
| Fibocom               | 1         | 0.88%   |
| D-Link System         | 1         | 0.88%   |
| D-Link                | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 19        | 16.67%  |
| Intel Wireless 7265                                            | 6         | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 5.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 5.26%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 4         | 3.51%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 3.51%   |
| Intel Wireless 8260                                            | 4         | 3.51%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 3.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 3.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.63%   |
| Intel Wireless-AC 9260                                         | 3         | 2.63%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.63%   |
| Intel Wireless 7260                                            | 3         | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.63%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.75%   |
| Microsoft Xbox 360 Wireless Adapter                            | 2         | 1.75%   |
| Intel Wireless 3165                                            | 2         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.88%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.88%   |
| Realtek 802.11ac NIC                                           | 1         | 0.88%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.88%   |
| Ralink RT2800 802.11n PCI                                      | 1         | 0.88%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.88%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.88%   |
| Intel Wireless 3160                                            | 1         | 0.88%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 1         | 0.88%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 76        | 56.72%  |
| Intel                 | 44        | 32.84%  |
| Aquantia              | 4         | 2.99%   |
| Qualcomm Atheros      | 2         | 1.49%   |
| Lenovo                | 2         | 1.49%   |
| Broadcom              | 2         | 1.49%   |
| Xiaomi                | 1         | 0.75%   |
| Standard Microsystems | 1         | 0.75%   |
| ICS Advent            | 1         | 0.75%   |
| Google                | 1         | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 35.92%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 12.68%  |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 7.75%   |
| Intel I211 Gigabit Network Connection                             | 6         | 4.23%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.52%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.82%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.11%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 2.11%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.41%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.41%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.41%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.41%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.41%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.7%    |
| Standard Microsystems Ethernet controller                         | 1         | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.7%    |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.7%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.7%    |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 1         | 0.7%    |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.7%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.7%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.7%    |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.7%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.7%    |
| ICS Advent USB 10/100 LAN                                         | 1         | 0.7%    |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.7%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.7%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.7%    |
| Aquantia AQC100 10G Ethernet MAC controller [AQtion]              | 1         | 0.7%    |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 0.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 120       | 51.06%  |
| WiFi     | 110       | 46.81%  |
| Modem    | 5         | 2.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 94        | 58.75%  |
| Ethernet | 66        | 41.25%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 75        | 48.7%   |
| 2     | 70        | 45.45%  |
| 0     | 5         | 3.25%   |
| 3     | 3         | 1.95%   |
| 4     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 114       | 72.61%  |
| Yes  | 43        | 27.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 65.42%  |
| Realtek Semiconductor           | 9         | 8.41%   |
| Qualcomm Atheros Communications | 4         | 3.74%   |
| MediaTek                        | 4         | 3.74%   |
| Cambridge Silicon Radio         | 4         | 3.74%   |
| ASUSTek Computer                | 4         | 3.74%   |
| Apple                           | 4         | 3.74%   |
| Broadcom                        | 3         | 2.8%    |
| Foxconn / Hon Hai               | 2         | 1.87%   |
| USI                             | 1         | 0.93%   |
| Lite-On Technology              | 1         | 0.93%   |
| HTC (High Tech Computer)        | 1         | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 17        | 15.89%  |
| Intel Bluetooth wireless interface                                   | 15        | 14.02%  |
| Intel AX201 Bluetooth                                                | 10        | 9.35%   |
| Realtek Bluetooth Radio                                              | 9         | 8.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 9         | 8.41%   |
| Intel Bluetooth Device                                               | 7         | 6.54%   |
| Intel AX210 Bluetooth                                                | 6         | 5.61%   |
| MediaTek Wireless_Device                                             | 4         | 3.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 4         | 3.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 2.8%    |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 2.8%    |
| Apple Bluetooth Host Controller                                      | 3         | 2.8%    |
| Qualcomm Atheros  Bluetooth Device                                   | 2         | 1.87%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 1.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 1.87%   |
| USI Bluetooth Device                                                 | 1         | 0.93%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 0.93%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.93%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1         | 0.93%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 1         | 0.93%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 0.93%   |
| ASUS Broadcom Bluetooth 2.1                                          | 1         | 0.93%   |
| ASUS ASUS USB-BT500                                                  | 1         | 0.93%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 90        | 36.73%  |
| AMD                                  | 65        | 26.53%  |
| Nvidia                               | 41        | 16.73%  |
| C-Media Electronics                  | 6         | 2.45%   |
| Creative Technology                  | 4         | 1.63%   |
| Texas Instruments                    | 3         | 1.22%   |
| Lenovo                               | 3         | 1.22%   |
| Kingston Technology                  | 3         | 1.22%   |
| Focusrite-Novation                   | 3         | 1.22%   |
| Synaptics                            | 2         | 0.82%   |
| Realtek Semiconductor                | 2         | 0.82%   |
| Razer USA                            | 2         | 0.82%   |
| DSEA A/S                             | 2         | 0.82%   |
| Trust                                | 1         | 0.41%   |
| Thomann                              | 1         | 0.41%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.41%   |
| Sony                                 | 1         | 0.41%   |
| Shure                                | 1         | 0.41%   |
| Sennheiser Communications            | 1         | 0.41%   |
| Schiit Audio                         | 1         | 0.41%   |
| Satechi                              | 1         | 0.41%   |
| PreSonus Audio Electronics           | 1         | 0.41%   |
| Logitech                             | 1         | 0.41%   |
| GYROCOM C&C                          | 1         | 0.41%   |
| Edifier Technology                   | 1         | 0.41%   |
| Creative Labs                        | 1         | 0.41%   |
| Corsair                              | 1         | 0.41%   |
| ASUSTek Computer                     | 1         | 0.41%   |
| ASRock                               | 1         | 0.41%   |
| Apogee Electronics                   | 1         | 0.41%   |
| Antlion Audio                        | 1         | 0.41%   |
| (LCS) USB Audio Device               | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 27        | 9.06%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 21        | 7.05%   |
| AMD Starship/Matisse HD Audio Controller                                | 20        | 6.71%   |
| Intel Sunrise Point-LP HD Audio                                         | 14        | 4.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 8         | 2.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 8         | 2.68%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 7         | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 7         | 2.35%   |
| Intel Cannon Lake PCH cAVS                                              | 6         | 2.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 6         | 2.01%   |
| AMD Navi 10 HDMI Audio                                                  | 6         | 2.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 6         | 2.01%   |
| Nvidia TU106 High Definition Audio Controller                           | 5         | 1.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 5         | 1.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 5         | 1.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 5         | 1.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 5         | 1.68%   |
| Nvidia GP107GL High Definition Audio Controller                         | 4         | 1.34%   |
| Nvidia GK104 HDMI Audio Controller                                      | 4         | 1.34%   |
| Nvidia GA106 High Definition Audio Controller                           | 4         | 1.34%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 4         | 1.34%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 4         | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                           | 3         | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                           | 3         | 1.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 3         | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 3         | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                            | 3         | 1.01%   |
| Intel Comet Lake PCH cAVS                                               | 3         | 1.01%   |
| Intel Broadwell-U Audio Controller                                      | 3         | 1.01%   |
| Intel 200 Series PCH HD Audio                                           | 3         | 1.01%   |
| Creative Technology SoundBlaster Live! 24-bit External SB0490           | 3         | 1.01%   |
| Texas Instruments PCM2902 Audio Codec                                   | 2         | 0.67%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 0.67%   |
| Realtek Semiconductor USB Audio                                         | 2         | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 2         | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                           | 2         | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                           | 2         | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                           | 2         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 37        | 21.64%  |
| Kingston                     | 23        | 13.45%  |
| SK hynix                     | 20        | 11.7%   |
| Corsair                      | 19        | 11.11%  |
| Micron Technology            | 18        | 10.53%  |
| G.Skill                      | 13        | 7.6%    |
| Crucial                      | 13        | 7.6%    |
| Team                         | 6         | 3.51%   |
| Unknown                      | 5         | 2.92%   |
| Unknown (ABCD)               | 4         | 2.34%   |
| A-DATA Technology            | 4         | 2.34%   |
| Goodram                      | 2         | 1.17%   |
| AMD                          | 2         | 1.17%   |
| Strontium                    | 1         | 0.58%   |
| Ramaxel Technology           | 1         | 0.58%   |
| Patriot Memory (PDP Systems) | 1         | 0.58%   |
| Avant                        | 1         | 0.58%   |
| Unknown                      | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.62%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 3         | 1.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s  | 3         | 1.62%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s          | 3         | 1.62%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 3         | 1.62%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.08%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.08%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.08%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.08%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.08%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.08%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 1.08%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 1.08%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 1.08%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 2         | 1.08%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s           | 2         | 1.08%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.54%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.54%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.54%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.54%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                    | 1         | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.54%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 1         | 0.54%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s               | 1         | 0.54%   |
| Team RAM TEAMGROUP-UD4-2666 16384MB DIMM DDR4 2933MT/s           | 1         | 0.54%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.54%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s               | 1         | 0.54%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                     | 1         | 0.54%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.54%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.54%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.54%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.54%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.54%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.54%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.54%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 1         | 0.54%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 91        | 61.9%   |
| DDR3   | 26        | 17.69%  |
| LPDDR4 | 12        | 8.16%   |
| LPDDR5 | 7         | 4.76%   |
| LPDDR3 | 6         | 4.08%   |
| DDR5   | 4         | 2.72%   |
| SDRAM  | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 46%     |
| DIMM         | 54        | 36%     |
| Row Of Chips | 23        | 15.33%  |
| Chip         | 2         | 1.33%   |
| RIMM         | 1         | 0.67%   |
| Unknown      | 1         | 0.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 67        | 40.85%  |
| 16384 | 51        | 31.1%   |
| 32768 | 21        | 12.8%   |
| 4096  | 20        | 12.2%   |
| 2048  | 4         | 2.44%   |
| 1024  | 1         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 41        | 25.47%  |
| 1600    | 19        | 11.8%   |
| 2667    | 17        | 10.56%  |
| 2400    | 12        | 7.45%   |
| 2133    | 12        | 7.45%   |
| 3600    | 9         | 5.59%   |
| 6400    | 7         | 4.35%   |
| 4267    | 6         | 3.73%   |
| 3000    | 5         | 3.11%   |
| 1867    | 5         | 3.11%   |
| 3733    | 4         | 2.48%   |
| 1333    | 3         | 1.86%   |
| 4800    | 2         | 1.24%   |
| 4266    | 2         | 1.24%   |
| 3400    | 2         | 1.24%   |
| 3334    | 2         | 1.24%   |
| 2933    | 2         | 1.24%   |
| 6000    | 1         | 0.62%   |
| 5600    | 1         | 0.62%   |
| 3866    | 1         | 0.62%   |
| 3666    | 1         | 0.62%   |
| 3534    | 1         | 0.62%   |
| 3266    | 1         | 0.62%   |
| 2800    | 1         | 0.62%   |
| 2134    | 1         | 0.62%   |
| 2132    | 1         | 0.62%   |
| 1066    | 1         | 0.62%   |
| Unknown | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Xerox  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Xerox Phaser 6125N | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 17        | 17.89%  |
| Logitech                      | 13        | 13.68%  |
| Microdia                      | 11        | 11.58%  |
| IMC Networks                  | 10        | 10.53%  |
| Acer                          | 10        | 10.53%  |
| Realtek Semiconductor         | 9         | 9.47%   |
| Bison Electronics             | 5         | 5.26%   |
| Sunplus Innovation Technology | 4         | 4.21%   |
| Quanta                        | 3         | 3.16%   |
| MacroSilicon                  | 3         | 3.16%   |
| Lite-On Technology            | 2         | 2.11%   |
| Apple                         | 2         | 2.11%   |
| webcam                        | 1         | 1.05%   |
| Syntek                        | 1         | 1.05%   |
| SunplusIT                     | 1         | 1.05%   |
| Microsoft                     | 1         | 1.05%   |
| Luxvisions Innotech Limited   | 1         | 1.05%   |
| Alcor Micro                   | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 11        | 11.46%  |
| Microdia Integrated_Webcam_HD                     | 6         | 6.25%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 5         | 5.21%   |
| Acer Integrated Camera                            | 4         | 4.17%   |
| Realtek Integrated_Webcam_HD                      | 3         | 3.13%   |
| MacroSilicon usb video                            | 3         | 3.13%   |
| Logitech HD Pro Webcam C920                       | 3         | 3.13%   |
| IMC Networks Integrated Camera                    | 3         | 3.13%   |
| Chicony HP HD Camera                              | 3         | 3.13%   |
| Bison Integrated Camera                           | 3         | 3.13%   |
| Sunplus Integrated_Webcam_FHD                     | 2         | 2.08%   |
| Realtek Laptop Camera                             | 2         | 2.08%   |
| Quanta VGA WebCam                                 | 2         | 2.08%   |
| Logitech Webcam C270                              | 2         | 2.08%   |
| Acer Integrated IR Camera                         | 2         | 2.08%   |
| Acer HD Webcam                                    | 2         | 2.08%   |
| webcam webcam                                     | 1         | 1.04%   |
| Syntek Integrated Camera                          | 1         | 1.04%   |
| SunplusIT HP TrueVision HD Camera                 | 1         | 1.04%   |
| Sunplus Integrated_Webcam_HD                      | 1         | 1.04%   |
| Sunplus HD WebCam                                 | 1         | 1.04%   |
| Realtek TV Camera                                 | 1         | 1.04%   |
| Realtek Realtek USB MIC                           | 1         | 1.04%   |
| Realtek Lenovo EasyCamera                         | 1         | 1.04%   |
| Realtek Integrated Webcam                         | 1         | 1.04%   |
| Realtek EasyCamera                                | 1         | 1.04%   |
| Quanta HP True Vision HD Camera                   | 1         | 1.04%   |
| Microsoft LifeCam HD-3000                         | 1         | 1.04%   |
| Microdia Webcam Vitade AF                         | 1         | 1.04%   |
| Microdia USB 2.0 Camera                           | 1         | 1.04%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 1.04%   |
| Microdia Integrated Webcam                        | 1         | 1.04%   |
| Microdia Camera                                   | 1         | 1.04%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1.04%   |
| Logitech Webcam Pro 9000                          | 1         | 1.04%   |
| Logitech Webcam C930e                             | 1         | 1.04%   |
| Logitech Webcam C310                              | 1         | 1.04%   |
| Logitech Webcam C120                              | 1         | 1.04%   |
| Logitech StreamCam                                | 1         | 1.04%   |
| Logitech HD Webcam C615                           | 1         | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 45.45%  |
| Validity Sensors           | 7         | 31.82%  |
| Shenzhen Goodix Technology | 4         | 18.18%  |
| Gingytech                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 4         | 18.18%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 13.64%  |
| Shenzhen Goodix Fingerprint Reader                       | 3         | 13.64%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 9.09%   |
| Synaptics UWP WBDI Device                                | 2         | 9.09%   |
| Synaptics UWP WBDI                                       | 2         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 4.55%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 4.55%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.55%   |
| Shenzhen Goodix  Fingerprint Device                      | 1         | 4.55%   |
| Gingytech Fingerprint sensor                             | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 10        | 66.67%  |
| Yubico.com  | 2         | 13.33%  |
| Broadcom    | 2         | 13.33%  |
| Upek        | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 10        | 66.67%  |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 6.67%   |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 1         | 6.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 6.67%   |
| Broadcom 5880                                              | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 90        | 56.6%   |
| 1     | 43        | 27.04%  |
| 2     | 23        | 14.47%  |
| 4     | 2         | 1.26%   |
| 3     | 1         | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Multimedia controller    | 20        | 21.05%  |
| Fingerprint reader       | 20        | 21.05%  |
| Graphics card            | 18        | 18.95%  |
| Chipcard                 | 11        | 11.58%  |
| Net/wireless             | 8         | 8.42%   |
| Bluetooth                | 5         | 5.26%   |
| Unassigned class         | 3         | 3.16%   |
| Camera                   | 3         | 3.16%   |
| Modem                    | 2         | 2.11%   |
| Storage/ata              | 1         | 1.05%   |
| Network                  | 1         | 1.05%   |
| Dvb card                 | 1         | 1.05%   |
| Communication controller | 1         | 1.05%   |
| Card reader              | 1         | 1.05%   |

