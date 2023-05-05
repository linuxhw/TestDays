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

Total: 201

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| NixOS 22.11                      | 44        | 28.21%  |
| NixOS 22.05                      | 37        | 23.72%  |
| NixOS 23.05                      | 22        | 14.1%   |
| NixOS 21.11                      | 18        | 11.54%  |
| NixOS                            | 5         | 3.21%   |
| NixOS 21.05pre-git               | 2         | 1.28%   |
| NixOS 20.09pre-git               | 2         | 1.28%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.64%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.64%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.64%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.64%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.64%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.64%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.64%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.64%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.64%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.64%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.64%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.64%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.64%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.64%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.64%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.64%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.64%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.64%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.64%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.64%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.64%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.64%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.64%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.64%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.64%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 138       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version       | Computers | Percent |
|---------------|-----------|---------|
| 5.15.74       | 5         | 3.03%   |
| 5.15.86       | 4         | 2.42%   |
| 5.15.43       | 4         | 2.42%   |
| 6.2.0-rc6     | 3         | 1.82%   |
| 6.1.0         | 3         | 1.82%   |
| 6.0.11        | 3         | 1.82%   |
| 6.0.10        | 3         | 1.82%   |
| 5.15.82       | 3         | 1.82%   |
| 5.15.72       | 3         | 1.82%   |
| 5.15.68       | 3         | 1.82%   |
| 5.15.47       | 3         | 1.82%   |
| 5.15.26       | 3         | 1.82%   |
| 6.1.1         | 2         | 1.21%   |
| 5.8.1-zen1    | 2         | 1.21%   |
| 5.19.14       | 2         | 1.21%   |
| 5.18.19       | 2         | 1.21%   |
| 5.17.1        | 2         | 1.21%   |
| 5.16.8-zen1   | 2         | 1.21%   |
| 5.16.15       | 2         | 1.21%   |
| 5.15.96       | 2         | 1.21%   |
| 5.15.92       | 2         | 1.21%   |
| 5.15.90       | 2         | 1.21%   |
| 5.15.85       | 2         | 1.21%   |
| 5.15.64       | 2         | 1.21%   |
| 5.15.32       | 2         | 1.21%   |
| 5.15.25       | 2         | 1.21%   |
| 5.13.7        | 2         | 1.21%   |
| 5.13.2        | 2         | 1.21%   |
| 5.12.15       | 2         | 1.21%   |
| 5.10.102      | 2         | 1.21%   |
| 6.2.9-lqx1    | 1         | 0.61%   |
| 6.2.8         | 1         | 0.61%   |
| 6.2.7         | 1         | 0.61%   |
| 6.2.11-lqx3   | 1         | 0.61%   |
| 6.2.11        | 1         | 0.61%   |
| 6.2.1         | 1         | 0.61%   |
| 6.2.0         | 1         | 0.61%   |
| 6.1.9         | 1         | 0.61%   |
| 6.1.7-xanmod1 | 1         | 0.61%   |
| 6.1.25        | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.74  | 5         | 3.03%   |
| 6.2.0    | 4         | 2.42%   |
| 6.1.0    | 4         | 2.42%   |
| 6.0.10   | 4         | 2.42%   |
| 5.15.86  | 4         | 2.42%   |
| 5.15.43  | 4         | 2.42%   |
| 6.0.11   | 3         | 1.82%   |
| 5.15.82  | 3         | 1.82%   |
| 5.15.72  | 3         | 1.82%   |
| 5.15.68  | 3         | 1.82%   |
| 5.15.47  | 3         | 1.82%   |
| 5.15.26  | 3         | 1.82%   |
| 6.2.11   | 2         | 1.21%   |
| 6.1.1    | 2         | 1.21%   |
| 6.0.2    | 2         | 1.21%   |
| 5.8.1    | 2         | 1.21%   |
| 5.19.14  | 2         | 1.21%   |
| 5.18.19  | 2         | 1.21%   |
| 5.17.1   | 2         | 1.21%   |
| 5.16.8   | 2         | 1.21%   |
| 5.16.15  | 2         | 1.21%   |
| 5.15.96  | 2         | 1.21%   |
| 5.15.92  | 2         | 1.21%   |
| 5.15.90  | 2         | 1.21%   |
| 5.15.85  | 2         | 1.21%   |
| 5.15.83  | 2         | 1.21%   |
| 5.15.64  | 2         | 1.21%   |
| 5.15.32  | 2         | 1.21%   |
| 5.15.25  | 2         | 1.21%   |
| 5.13.7   | 2         | 1.21%   |
| 5.13.2   | 2         | 1.21%   |
| 5.12.15  | 2         | 1.21%   |
| 5.11.16  | 2         | 1.21%   |
| 5.10.102 | 2         | 1.21%   |
| 6.2.9    | 1         | 0.61%   |
| 6.2.8    | 1         | 0.61%   |
| 6.2.7    | 1         | 0.61%   |
| 6.2.1    | 1         | 0.61%   |
| 6.1.9    | 1         | 0.61%   |
| 6.1.7    | 1         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 56        | 35.44%  |
| 5.10    | 14        | 8.86%   |
| 6.1     | 13        | 8.23%   |
| 6.0     | 13        | 8.23%   |
| 6.2     | 10        | 6.33%   |
| 5.16    | 8         | 5.06%   |
| 5.4     | 7         | 4.43%   |
| 5.19    | 7         | 4.43%   |
| 5.8     | 6         | 3.8%    |
| 5.18    | 5         | 3.16%   |
| 5.13    | 4         | 2.53%   |
| 5.7     | 3         | 1.9%    |
| 5.17    | 3         | 1.9%    |
| 5.12    | 3         | 1.9%    |
| 5.14    | 2         | 1.27%   |
| 5.11    | 2         | 1.27%   |
| 4.19    | 2         | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 133       | 96.38%  |
| aarch64 | 4         | 2.9%    |
| i686    | 1         | 0.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 85        | 58.62%  |
| sway         | 14        | 9.66%   |
| KDE5         | 10        | 6.9%    |
| GNOME        | 10        | 6.9%    |
| XFCE         | 7         | 4.83%   |
| none+i3      | 5         | 3.45%   |
| KDE          | 4         | 2.76%   |
| Hyprland     | 4         | 2.76%   |
| none+xmonad  | 2         | 1.38%   |
| none+awesome | 2         | 1.38%   |
| X-Generic    | 1         | 0.69%   |
| none+bspwm   | 1         | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 78        | 53.79%  |
| X11     | 29        | 20%     |
| Wayland | 25        | 17.24%  |
| Tty     | 13        | 8.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 93        | 66.91%  |
| LightDM | 20        | 14.39%  |
| SDDM    | 15        | 10.79%  |
| GDM     | 11        | 7.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 61        | 43.57%  |
| Unknown    | 54        | 38.57%  |
| en_GB      | 4         | 2.86%   |
| fr_FR      | 3         | 2.14%   |
| en_AU      | 3         | 2.14%   |
| de_DE      | 3         | 2.14%   |
| ru_RU      | 2         | 1.43%   |
| en_DK      | 2         | 1.43%   |
| de_CH      | 2         | 1.43%   |
| ro_RO      | 1         | 0.71%   |
| pt_BR      | 1         | 0.71%   |
| lv_LV      | 1         | 0.71%   |
| it_IT      | 1         | 0.71%   |
| en_IE.UTF8 | 1         | 0.71%   |
| en_CA      | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 119       | 85%     |
| BIOS | 21        | 15%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 72        | 50.7%   |
| Btrfs   | 22        | 15.49%  |
| Xfs     | 16        | 11.27%  |
| Zfs     | 15        | 10.56%  |
| Tmpfs   | 10        | 7.04%   |
| Unknown | 6         | 4.23%   |
| Ext2    | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 130       | 92.2%   |
| Unknown | 8         | 5.67%   |
| MBR     | 3         | 2.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 108       | 76.06%  |
| Yes       | 34        | 23.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 93        | 67.39%  |
| Yes       | 45        | 32.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 31        | 22.46%  |
| ASUSTek Computer                     | 28        | 20.29%  |
| Dell                                 | 18        | 13.04%  |
| MSI                                  | 12        | 8.7%    |
| Hewlett-Packard                      | 8         | 5.8%    |
| Gigabyte Technology                  | 7         | 5.07%   |
| ASRock                               | 6         | 4.35%   |
| Acer                                 | 4         | 2.9%    |
| GPD                                  | 3         | 2.17%   |
| Apple                                | 3         | 2.17%   |
| Supermicro                           | 2         | 1.45%   |
| Raspberry Pi Foundation              | 2         | 1.45%   |
| Pine Microsystems                    | 2         | 1.45%   |
| Framework                            | 2         | 1.45%   |
| Toshiba                              | 1         | 0.72%   |
| Teclast                              | 1         | 0.72%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.72%   |
| OBSIDIAN-PC                          | 1         | 0.72%   |
| MECHREVO                             | 1         | 0.72%   |
| Intel                                | 1         | 0.72%   |
| Hardkernel                           | 1         | 0.72%   |
| EVGA                                 | 1         | 0.72%   |
| Blackview                            | 1         | 0.72%   |
| Avell High Performance               | 1         | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo 13w Yoga 82S1                       | 3         | 2.17%   |
| Pine Microsystems Pine64 PinePhone (1.2)   | 2         | 1.45%   |
| MSI MS-7C56                                | 2         | 1.45%   |
| MSI MS-7C37                                | 2         | 1.45%   |
| Gigabyte B550I AORUS PRO AX                | 2         | 1.45%   |
| Dell Latitude 7420                         | 2         | 1.45%   |
| ASUS Zenbook UX3402ZA_UX3402ZA             | 2         | 1.45%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 1.45%   |
| ASUS All Series                            | 2         | 1.45%   |
| Toshiba Satellite L50-B                    | 1         | 0.72%   |
| Teclast F5                                 | 1         | 0.72%   |
| Supermicro X8DT6                           | 1         | 0.72%   |
| Supermicro X10SLL-F                        | 1         | 0.72%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.72%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 1         | 0.72%   |
| RPi Raspberry Pi 3 Model B+                | 1         | 0.72%   |
| OBSIDIAN-PC N13_N140ZU                     | 1         | 0.72%   |
| MSI MS-7C95                                | 1         | 0.72%   |
| MSI MS-7C91                                | 1         | 0.72%   |
| MSI MS-7C84                                | 1         | 0.72%   |
| MSI MS-7C35                                | 1         | 0.72%   |
| MSI MS-7B89                                | 1         | 0.72%   |
| MSI MS-7B09                                | 1         | 0.72%   |
| MSI MS-7758                                | 1         | 0.72%   |
| MSI Bravo 15 B5DD                          | 1         | 0.72%   |
| MECHREVO Code01 Ver2.0                     | 1         | 0.72%   |
| Lenovo Yoga Slim 7 13ACN5 82CY             | 1         | 0.72%   |
| Lenovo Yoga 520-14IKB 81C8                 | 1         | 0.72%   |
| Lenovo ThinkPad X390 20Q0CTO1WW            | 1         | 0.72%   |
| Lenovo ThinkPad X260 20F5S6MF02            | 1         | 0.72%   |
| Lenovo ThinkPad X260 20F5S4BY00            | 1         | 0.72%   |
| Lenovo ThinkPad X250 20CLS18S0T            | 1         | 0.72%   |
| Lenovo ThinkPad X230 2333AZ2               | 1         | 0.72%   |
| Lenovo ThinkPad X230 23243E9               | 1         | 0.72%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW      | 1         | 0.72%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBCT01WW   | 1         | 0.72%   |
| Lenovo ThinkPad T580 20L90024PB            | 1         | 0.72%   |
| Lenovo ThinkPad T540p 20BE005YMH           | 1         | 0.72%   |
| Lenovo ThinkPad T490 20N2000LUK            | 1         | 0.72%   |
| Lenovo ThinkPad T480 20L5CTO1WW            | 1         | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 21        | 15.22%  |
| ASUS ROG                                   | 8         | 5.8%    |
| Dell XPS                                   | 6         | 4.35%   |
| ASUS PRIME                                 | 6         | 4.35%   |
| Dell Inspiron                              | 5         | 3.62%   |
| Lenovo 13w                                 | 3         | 2.17%   |
| Dell Precision                             | 3         | 2.17%   |
| Dell Latitude                              | 3         | 2.17%   |
| ASUS Zenbook                               | 3         | 2.17%   |
| RPi Raspberry                              | 2         | 1.45%   |
| Pine Microsystems Pine64                   | 2         | 1.45%   |
| MSI MS-7C56                                | 2         | 1.45%   |
| MSI MS-7C37                                | 2         | 1.45%   |
| Lenovo Yoga                                | 2         | 1.45%   |
| Lenovo Legion                              | 2         | 1.45%   |
| HP Spectre                                 | 2         | 1.45%   |
| HP ProBook                                 | 2         | 1.45%   |
| Gigabyte B550I                             | 2         | 1.45%   |
| Framework Laptop                           | 2         | 1.45%   |
| ASUS All                                   | 2         | 1.45%   |
| Apple MacBookPro11                         | 2         | 1.45%   |
| Acer Aspire                                | 2         | 1.45%   |
| Toshiba Satellite                          | 1         | 0.72%   |
| Teclast F5                                 | 1         | 0.72%   |
| Supermicro X8DT6                           | 1         | 0.72%   |
| Supermicro X10SLL-F                        | 1         | 0.72%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.72%   |
| OBSIDIAN-PC N13                            | 1         | 0.72%   |
| MSI MS-7C95                                | 1         | 0.72%   |
| MSI MS-7C91                                | 1         | 0.72%   |
| MSI MS-7C84                                | 1         | 0.72%   |
| MSI MS-7C35                                | 1         | 0.72%   |
| MSI MS-7B89                                | 1         | 0.72%   |
| MSI MS-7B09                                | 1         | 0.72%   |
| MSI MS-7758                                | 1         | 0.72%   |
| MSI Bravo                                  | 1         | 0.72%   |
| MECHREVO Code01                            | 1         | 0.72%   |
| Lenovo IdeaPadFlex                         | 1         | 0.72%   |
| Lenovo IdeaPad                             | 1         | 0.72%   |
| Lenovo G50-70                              | 1         | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 29        | 21.01%  |
| 2019    | 20        | 14.49%  |
| 2021    | 16        | 11.59%  |
| 2022    | 13        | 9.42%   |
| 2018    | 13        | 9.42%   |
| 2016    | 11        | 7.97%   |
| 2017    | 8         | 5.8%    |
| 2013    | 7         | 5.07%   |
| 2015    | 6         | 4.35%   |
| 2012    | 5         | 3.62%   |
| 2014    | 4         | 2.9%    |
| Unknown | 4         | 2.9%    |
| 2010    | 1         | 0.72%   |
| 2009    | 1         | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 66        | 47.83%  |
| Desktop        | 48        | 34.78%  |
| Convertible    | 13        | 9.42%   |
| Server         | 3         | 2.17%   |
| Phone          | 2         | 1.45%   |
| System on chip | 2         | 1.45%   |
| All in one     | 2         | 1.45%   |
| Tablet         | 1         | 0.72%   |
| Mini pc        | 1         | 0.72%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 138       | 99.28%  |
| Enabled  | 1         | 0.72%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 137       | 99.28%  |
| Yes  | 1         | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 39        | 27.66%  |
| 16.01-24.0  | 33        | 23.4%   |
| 8.01-16.0   | 22        | 15.6%   |
| 64.01-256.0 | 18        | 12.77%  |
| 4.01-8.0    | 13        | 9.22%   |
| 24.01-32.0  | 7         | 4.96%   |
| 3.01-4.0    | 6         | 4.26%   |
| 0.51-1.0    | 2         | 1.42%   |
| 1.01-2.0    | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 41        | 26.8%   |
| 8.01-16.0   | 26        | 16.99%  |
| 3.01-4.0    | 21        | 13.73%  |
| 2.01-3.0    | 18        | 11.76%  |
| 1.01-2.0    | 18        | 11.76%  |
| 24.01-32.0  | 7         | 4.58%   |
| 16.01-24.0  | 7         | 4.58%   |
| 32.01-64.0  | 6         | 3.92%   |
| 0.51-1.0    | 6         | 3.92%   |
| 0.01-0.5    | 2         | 1.31%   |
| 64.01-256.0 | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 78        | 54.55%  |
| 2      | 37        | 25.87%  |
| 3      | 11        | 7.69%   |
| 5      | 5         | 3.5%    |
| 6      | 4         | 2.8%    |
| 4      | 2         | 1.4%    |
| 23     | 1         | 0.7%    |
| 17     | 1         | 0.7%    |
| 11     | 1         | 0.7%    |
| 8      | 1         | 0.7%    |
| 7      | 1         | 0.7%    |
| 0      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 124       | 89.86%  |
| Yes       | 14        | 10.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 75.89%  |
| No        | 34        | 24.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 73.19%  |
| No        | 37        | 26.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 68.57%  |
| No        | 44        | 31.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 26        | 18.84%  |
| Germany     | 15        | 10.87%  |
| UK          | 10        | 7.25%   |
| France      | 10        | 7.25%   |
| Russia      | 8         | 5.8%    |
| Poland      | 8         | 5.8%    |
| Italy       | 7         | 5.07%   |
| Canada      | 7         | 5.07%   |
| Ukraine     | 6         | 4.35%   |
| Switzerland | 4         | 2.9%    |
| Austria     | 4         | 2.9%    |
| Netherlands | 3         | 2.17%   |
| Czechia     | 3         | 2.17%   |
| Brazil      | 3         | 2.17%   |
| Australia   | 3         | 2.17%   |
| Denmark     | 2         | 1.45%   |
| Belgium     | 2         | 1.45%   |
| Uruguay     | 1         | 0.72%   |
| Sweden      | 1         | 0.72%   |
| Spain       | 1         | 0.72%   |
| Slovenia    | 1         | 0.72%   |
| Serbia      | 1         | 0.72%   |
| Romania     | 1         | 0.72%   |
| Portugal    | 1         | 0.72%   |
| New Zealand | 1         | 0.72%   |
| Latvia      | 1         | 0.72%   |
| Kyrgyzstan  | 1         | 0.72%   |
| Japan       | 1         | 0.72%   |
| Iraq        | 1         | 0.72%   |
| Iran        | 1         | 0.72%   |
| India       | 1         | 0.72%   |
| Hungary     | 1         | 0.72%   |
| Colombia    | 1         | 0.72%   |
| China       | 1         | 0.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Vienna             | 4         | 2.67%   |
| Marki              | 4         | 2.67%   |
| Kharkiv            | 4         | 2.67%   |
| Frankfurt am Main  | 4         | 2.67%   |
| Plymouth           | 3         | 2%      |
| Milwaukee          | 3         | 2%      |
| Lyon               | 3         | 2%      |
| Capo d'Orlando     | 3         | 2%      |
| South Deerfield    | 2         | 1.33%   |
| Schaafheim         | 2         | 1.33%   |
| Richardson         | 2         | 1.33%   |
| Prague             | 2         | 1.33%   |
| Ottawa             | 2         | 1.33%   |
| Melbourne          | 2         | 1.33%   |
| London             | 2         | 1.33%   |
| Krasnodar          | 2         | 1.33%   |
| Halifax            | 2         | 1.33%   |
| Gdansk             | 2         | 1.33%   |
| Darmstadt          | 2         | 1.33%   |
| Chelyabinsk        | 2         | 1.33%   |
| Austin             | 2         | 1.33%   |
| Zurich             | 1         | 0.67%   |
| Yangzhou           | 1         | 0.67%   |
| Woodford           | 1         | 0.67%   |
| Wellington         | 1         | 0.67%   |
| Warsaw             | 1         | 0.67%   |
| Villeurbanne       | 1         | 0.67%   |
| Verneuil-sur-Seine | 1         | 0.67%   |
| Valpacos           | 1         | 0.67%   |
| Trento             | 1         | 0.67%   |
| Tottenham          | 1         | 0.67%   |
| Tolyatti           | 1         | 0.67%   |
| Tokyo              | 1         | 0.67%   |
| Tehran             | 1         | 0.67%   |
| Talas              | 1         | 0.67%   |
| Székesfehérvár  | 1         | 0.67%   |
| Stockholm          | 1         | 0.67%   |
| Southampton        | 1         | 0.67%   |
| Sorocaba           | 1         | 0.67%   |
| Sindelfingen       | 1         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 54        | 111    | 25.47%  |
| Sandisk                     | 20        | 26     | 9.43%   |
| WDC                         | 18        | 40     | 8.49%   |
| Seagate                     | 15        | 48     | 7.08%   |
| Toshiba                     | 14        | 27     | 6.6%    |
| Crucial                     | 11        | 18     | 5.19%   |
| Kingston                    | 9         | 9      | 4.25%   |
| Micron Technology           | 8         | 8      | 3.77%   |
| Intel                       | 8         | 13     | 3.77%   |
| SK hynix                    | 7         | 10     | 3.3%    |
| Unknown                     | 5         | 8      | 2.36%   |
| HGST                        | 5         | 15     | 2.36%   |
| Apple                       | 3         | 6      | 1.42%   |
| Transcend                   | 2         | 2      | 0.94%   |
| Realtek Semiconductor       | 2         | 2      | 0.94%   |
| Plextor                     | 2         | 2      | 0.94%   |
| Phison Electronics          | 2         | 4      | 0.94%   |
| KIOXIA                      | 2         | 3      | 0.94%   |
| Kingston Technology Company | 2         | 2      | 0.94%   |
| Hitachi                     | 2         | 4      | 0.94%   |
| China                       | 2         | 2      | 0.94%   |
| Yangtze Memory Technologies | 1         | 1      | 0.47%   |
| Teclast                     | 1         | 2      | 0.47%   |
| SPCC                        | 1         | 1      | 0.47%   |
| Silicon Motion              | 1         | 1      | 0.47%   |
| Phison                      | 1         | 1      | 0.47%   |
| OCZ                         | 1         | 1      | 0.47%   |
| Micron/Crucial Technology   | 1         | 1      | 0.47%   |
| LITEON                      | 1         | 1      | 0.47%   |
| Lexar                       | 1         | 1      | 0.47%   |
| INNOVATION IT               | 1         | 1      | 0.47%   |
| Dogfish                     | 1         | 1      | 0.47%   |
| Corsair                     | 1         | 1      | 0.47%   |
| Biwin Storage Technology    | 1         | 1      | 0.47%   |
| BIWIN                       | 1         | 1      | 0.47%   |
| ASMT                        | 1         | 1      | 0.47%   |
| ASMedia                     | 1         | 1      | 0.47%   |
| ADATA Technology            | 1         | 2      | 0.47%   |
| A-DATA Technology           | 1         | 1      | 0.47%   |
| Unknown                     | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB                            | 5         | 1.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4         | 1.56%   |
| Unknown MMC Card  32GB                             | 3         | 1.17%   |
| Seagate ST3000DM001-1ER166 3TB                     | 3         | 1.17%   |
| SanDisk SSD PLUS 240GB                             | 3         | 1.17%   |
| Samsung SSD 970 EVO Plus 2TB                       | 3         | 1.17%   |
| Samsung SSD 970 EVO Plus 1TB                       | 3         | 1.17%   |
| Samsung SSD 970 EVO 500GB                          | 3         | 1.17%   |
| Samsung SSD 860 QVO 1TB                            | 3         | 1.17%   |
| Micron MTFDKCD512TFK 512GB                         | 3         | 1.17%   |
| Crucial CT1000MX500SSD1 1TB                        | 3         | 1.17%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB            | 2         | 0.78%   |
| Seagate ST4000DM004-2CV104 4TB                     | 2         | 0.78%   |
| Seagate ST3000DM001-1CH166 3TB                     | 2         | 0.78%   |
| Sandisk WD Black SN850 1TB                         | 2         | 0.78%   |
| SanDisk Ultra II 240GB SSD                         | 2         | 0.78%   |
| SanDisk NVMe SSD Drive 1TB                         | 2         | 0.78%   |
| Samsung SSD 980 PRO 1TB                            | 2         | 0.78%   |
| Samsung SSD 970 EVO 1TB                            | 2         | 0.78%   |
| Samsung SSD 870 EVO 1TB                            | 2         | 0.78%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 0.78%   |
| Samsung SSD 860 EVO 2TB                            | 2         | 0.78%   |
| Samsung SSD 860 EVO 250GB                          | 2         | 0.78%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 0.78%   |
| Samsung SSD 840 EVO 250GB                          | 2         | 0.78%   |
| Samsung PM9A1 NVMe 1024GB                          | 2         | 0.78%   |
| Samsung NVMe SSD Drive 1TB                         | 2         | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 0.78%   |
| Kingston SA400S37960G 960GB SSD                    | 2         | 0.78%   |
| HGST HTS721010A9E630 1TB                           | 2         | 0.78%   |
| Crucial CT250MX500SSD1 250GB                       | 2         | 0.78%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB               | 1         | 0.39%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                   | 1         | 0.39%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1         | 0.39%   |
| WDC WDS200T1X0E-00AFY0 2TB                         | 1         | 0.39%   |
| WDC WD80EMAZ-00WJTA0 8TB                           | 1         | 0.39%   |
| WDC WD80EDAZ-11TA3A0 8TB                           | 1         | 0.39%   |
| WDC WD50EZRX-00MVLB1 5TB                           | 1         | 0.39%   |
| WDC WD40EFRX-68N32N0 4TB                           | 1         | 0.39%   |
| WDC WD3200BPVT-22JJ5T0 320GB                       | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 48     | 31.91%  |
| WDC                 | 12        | 32     | 25.53%  |
| Toshiba             | 10        | 20     | 21.28%  |
| HGST                | 5         | 15     | 10.64%  |
| Hitachi             | 2         | 4      | 4.26%   |
| Samsung Electronics | 1         | 1      | 2.13%   |
| ASMedia             | 1         | 1      | 2.13%   |
| Apple               | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 59     | 33.33%  |
| Crucial             | 10        | 17     | 12.82%  |
| SanDisk             | 9         | 14     | 11.54%  |
| Kingston            | 6         | 6      | 7.69%   |
| Intel               | 5         | 7      | 6.41%   |
| Apple               | 3         | 5      | 3.85%   |
| WDC                 | 2         | 3      | 2.56%   |
| Transcend           | 2         | 2      | 2.56%   |
| China               | 2         | 2      | 2.56%   |
| Toshiba             | 1         | 1      | 1.28%   |
| Teclast             | 1         | 2      | 1.28%   |
| SPCC                | 1         | 1      | 1.28%   |
| SK hynix            | 1         | 1      | 1.28%   |
| Plextor             | 1         | 1      | 1.28%   |
| OCZ                 | 1         | 1      | 1.28%   |
| Micron Technology   | 1         | 1      | 1.28%   |
| LITEON              | 1         | 1      | 1.28%   |
| INNOVATION IT       | 1         | 1      | 1.28%   |
| Dogfish             | 1         | 1      | 1.28%   |
| Corsair             | 1         | 1      | 1.28%   |
| BIWIN               | 1         | 1      | 1.28%   |
| ASMT                | 1         | 1      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 85        | 121    | 44.97%  |
| SSD  | 66        | 129    | 34.92%  |
| HDD  | 33        | 122    | 17.46%  |
| MMC  | 5         | 9      | 2.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 85        | 121    | 50.6%   |
| SATA | 73        | 243    | 43.45%  |
| SAS  | 5         | 8      | 2.98%   |
| MMC  | 5         | 9      | 2.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 99     | 47.32%  |
| 0.51-1.0   | 30        | 55     | 26.79%  |
| 1.01-2.0   | 12        | 17     | 10.71%  |
| 2.01-3.0   | 6         | 12     | 5.36%   |
| 4.01-10.0  | 6         | 46     | 5.36%   |
| 3.01-4.0   | 3         | 15     | 2.68%   |
| 10.01-20.0 | 2         | 7      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 60        | 41.96%  |
| 1-20           | 29        | 20.28%  |
| 251-500        | 11        | 7.69%   |
| 501-1000       | 11        | 7.69%   |
| 101-250        | 10        | 6.99%   |
| 1001-2000      | 9         | 6.29%   |
| 2001-3000      | 6         | 4.2%    |
| More than 3000 | 5         | 3.5%    |
| 21-50          | 2         | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 60        | 41.38%  |
| 1-20           | 38        | 26.21%  |
| 101-250        | 13        | 8.97%   |
| 501-1000       | 8         | 5.52%   |
| 251-500        | 7         | 4.83%   |
| 21-50          | 7         | 4.83%   |
| 51-100         | 6         | 4.14%   |
| 1001-2000      | 3         | 2.07%   |
| 2001-3000      | 2         | 1.38%   |
| More than 3000 | 1         | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD20EARX-008FB0 2TB                        | 1         | 1      | 6.67%   |
| WDC WD10EZEX-60ZF5A0 1TB                       | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 6.67%   |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 6.67%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 6.67%   |
| Seagate ST8000VN004-2M2101 8TB                 | 1         | 3      | 6.67%   |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 6.67%   |
| SanDisk SSD PLUS 240GB                         | 1         | 3      | 6.67%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 870 EVO 1TB            | 1         | 1      | 6.67%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 6.67%   |
| Intel SSDSC2BW240A4 240GB                      | 1         | 1      | 6.67%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 6.67%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 6.67%   |
| ASMT 2115 2TB                                  | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 13.33%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Seagate             | 2         | 4      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| SK hynix            | 1         | 1      | 6.67%   |
| SanDisk             | 1         | 3      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |
| ASMT                | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 25%     |
| Toshiba | 2         | 2      | 25%     |
| Seagate | 2         | 4      | 25%     |
| Hitachi | 1         | 1      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 10     | 50%     |
| SSD  | 5         | 7      | 35.71%  |
| NVMe | 2         | 2      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MG03ACA300 3TB                           | 1         | 1      | 50%     |
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 130       | 328    | 81.25%  |
| Detected | 16        | 32     | 10%     |
| Malfunc  | 12        | 19     | 7.5%    |
| Failed   | 2         | 2      | 1.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 64        | 31.68%  |
| Samsung Electronics          | 36        | 17.82%  |
| AMD                          | 35        | 17.33%  |
| SanDisk                      | 16        | 7.92%   |
| Micron Technology            | 7         | 3.47%   |
| SK hynix                     | 6         | 2.97%   |
| Kingston Technology Company  | 6         | 2.97%   |
| ASMedia Technology           | 5         | 2.48%   |
| Toshiba America Info Systems | 4         | 1.98%   |
| Phison Electronics           | 3         | 1.49%   |
| LSI Logic / Symbios Logic    | 3         | 1.49%   |
| Broadcom / LSI               | 3         | 1.49%   |
| Realtek Semiconductor        | 2         | 0.99%   |
| Micron/Crucial Technology    | 2         | 0.99%   |
| KIOXIA                       | 2         | 0.99%   |
| ADATA Technology             | 2         | 0.99%   |
| Yangtze Memory Technologies  | 1         | 0.5%    |
| Silicon Motion               | 1         | 0.5%    |
| Shenzhen Longsys Electronics | 1         | 0.5%    |
| Marvell Technology Group     | 1         | 0.5%    |
| Lite-On Technology           | 1         | 0.5%    |
| Biwin Storage Technology     | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 10.23%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 22        | 10.23%  |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 5.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 3.72%   |
| Micron NVMe Storage Controller                                                 | 7         | 3.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.79%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 2.33%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 2.33%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 4         | 1.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.86%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.4%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.4%    |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.4%    |
| Phison E12 NVMe Controller                                                     | 3         | 1.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.4%    |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.4%    |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.4%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.93%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.93%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.93%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.93%   |
| Samsung Electronics SATA controller                                            | 2         | 0.93%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.93%   |
| Intel Comet Lake PCH-H RAID                                                    | 2         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.93%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 0.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 86        | 44.79%  |
| SATA | 86        | 44.79%  |
| RAID | 11        | 5.73%   |
| SAS  | 6         | 3.13%   |
| IDE  | 3         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 83        | 60.14%  |
| AMD    | 51        | 36.96%  |
| ARM    | 4         | 2.9%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 3.62%   |
| AMD Ryzen 5 3600 6-Core Processor          | 5         | 3.62%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 2.9%    |
| ARM Processor                              | 4         | 2.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz          | 3         | 2.17%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 3         | 2.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 2.17%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 2.17%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 3         | 2.17%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 3         | 2.17%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 1.45%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 1.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 1.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 1.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 1.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 2         | 1.45%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 1.45%   |
| Intel 12th Gen Core i7-1260P               | 2         | 1.45%   |
| Intel 12th Gen Core i5-1240P               | 2         | 1.45%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 2         | 1.45%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 2         | 1.45%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 2         | 1.45%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 1.45%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 2         | 1.45%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 2         | 1.45%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 2         | 1.45%   |
| Intel Xeon W-1290P CPU @ 3.70GHz           | 1         | 0.72%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 0.72%   |
| Intel Xeon CPU L5640 @ 2.27GHz             | 1         | 0.72%   |
| Intel Xeon CPU E5606 @ 2.13GHz             | 1         | 0.72%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz        | 1         | 0.72%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz       | 1         | 0.72%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 0.72%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 0.72%   |
| Intel Core i9-9900X CPU @ 3.50GHz          | 1         | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 0.72%   |
| Intel Core i7-6850K CPU @ 3.60GHz          | 1         | 0.72%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 32        | 23.19%  |
| Other                  | 21        | 15.22%  |
| AMD Ryzen 5            | 19        | 13.77%  |
| Intel Core i5          | 17        | 12.32%  |
| AMD Ryzen 7            | 16        | 11.59%  |
| AMD Ryzen 9            | 9         | 6.52%   |
| Intel Xeon             | 6         | 4.35%   |
| Intel Celeron          | 4         | 2.9%    |
| AMD Ryzen 7 PRO        | 4         | 2.9%    |
| Intel Core i3          | 3         | 2.17%   |
| Intel Core i9          | 2         | 1.45%   |
| AMD Ryzen Threadripper | 2         | 1.45%   |
| Intel Core m3          | 1         | 0.72%   |
| Intel Atom             | 1         | 0.72%   |
| AMD FX                 | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 44        | 31.88%  |
| 8       | 28        | 20.29%  |
| 6       | 26        | 18.84%  |
| 2       | 18        | 13.04%  |
| 12      | 10        | 7.25%   |
| Unknown | 4         | 2.9%    |
| 10      | 3         | 2.17%   |
| 16      | 2         | 1.45%   |
| 32      | 1         | 0.72%   |
| 24      | 1         | 0.72%   |
| 1       | 1         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 132       | 95.65%  |
| Unknown | 4         | 2.9%    |
| 2       | 2         | 1.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 121       | 87.68%  |
| 1       | 13        | 9.42%   |
| Unknown | 4         | 2.9%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 137       | 98.56%  |
| 32-bit         | 1         | 0.72%   |
| Unknown        | 1         | 0.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 21.13%  |
| 0x0a50000c | 9         | 6.34%   |
| 0x306c3    | 7         | 4.93%   |
| 0x0a50000d | 7         | 4.93%   |
| 0x08701021 | 7         | 4.93%   |
| 0x806ea    | 6         | 4.23%   |
| 0x806c1    | 6         | 4.23%   |
| 0x906ea    | 4         | 2.82%   |
| 0x806ec    | 4         | 2.82%   |
| 0x506e3    | 4         | 2.82%   |
| 0x306a9    | 4         | 2.82%   |
| 0x08701013 | 4         | 2.82%   |
| 0x906a3    | 3         | 2.11%   |
| 0x806eb    | 3         | 2.11%   |
| 0x0a404102 | 3         | 2.11%   |
| 0x08600106 | 3         | 2.11%   |
| 0x906e9    | 2         | 1.41%   |
| 0x806e9    | 2         | 1.41%   |
| 0x706a1    | 2         | 1.41%   |
| 0x406e3    | 2         | 1.41%   |
| 0x40661    | 2         | 1.41%   |
| 0x40651    | 2         | 1.41%   |
| 0x306d4    | 2         | 1.41%   |
| 0x0a201204 | 2         | 1.41%   |
| 0x0a201009 | 2         | 1.41%   |
| 0x08600104 | 2         | 1.41%   |
| 0x08001138 | 2         | 1.41%   |
| 0xa0653    | 1         | 0.7%    |
| 0xa0652    | 1         | 0.7%    |
| 0x906ed    | 1         | 0.7%    |
| 0x806d1    | 1         | 0.7%    |
| 0x706a8    | 1         | 0.7%    |
| 0x406f1    | 1         | 0.7%    |
| 0x306f2    | 1         | 0.7%    |
| 0x206c2    | 1         | 0.7%    |
| 0x0a50000b | 1         | 0.7%    |
| 0x0a201025 | 1         | 0.7%    |
| 0x0a201016 | 1         | 0.7%    |
| 0x08301025 | 1         | 0.7%    |
| 0x0800820d | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 25        | 18.12%  |
| Zen 3            | 23        | 16.67%  |
| Zen 2            | 18        | 13.04%  |
| Haswell          | 12        | 8.7%    |
| Skylake          | 11        | 7.97%   |
| Unknown          | 9         | 6.52%   |
| TigerLake        | 8         | 5.8%    |
| IvyBridge        | 5         | 3.62%   |
| Alderlake Hybrid | 5         | 3.62%   |
| Zen              | 4         | 2.9%    |
| Goldmont plus    | 4         | 2.9%    |
| CometLake        | 3         | 2.17%   |
| Broadwell        | 3         | 2.17%   |
| Zen+             | 2         | 1.45%   |
| Westmere         | 2         | 1.45%   |
| Icelake          | 2         | 1.45%   |
| Piledriver       | 1         | 0.72%   |
| Bonnell          | 1         | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 66        | 39.29%  |
| Nvidia                     | 53        | 31.55%  |
| AMD                        | 46        | 27.38%  |
| Matrox Electronics Systems | 2         | 1.19%   |
| ASPEED Technology          | 1         | 0.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 12        | 6.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 8         | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 4.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 2.91%   |
| Intel UHD Graphics 620                                                                | 5         | 2.91%   |
| Intel HD Graphics 530                                                                 | 5         | 2.91%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 5         | 2.91%   |
| AMD Renoir                                                                            | 5         | 2.91%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 5         | 2.91%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 2.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 2.33%   |
| AMD Barcelo                                                                           | 4         | 2.33%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 3         | 1.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 1.74%   |
| Nvidia GK104 [GeForce GTX 760]                                                        | 3         | 1.74%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 3         | 1.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 1.74%   |
| Intel HD Graphics 620                                                                 | 3         | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 1.74%   |
| AMD Rembrandt [Radeon 680M]                                                           | 3         | 1.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 1.16%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 1.16%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                         | 2         | 1.16%   |
| Intel HD Graphics 630                                                                 | 2         | 1.16%   |
| Intel HD Graphics 5500                                                                | 2         | 1.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 1.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 1.16%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                              | 2         | 1.16%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.58%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 0.58%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.58%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                    | 1         | 0.58%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                 | 1         | 0.58%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 41        | 29.5%   |
| 1 x AMD        | 30        | 21.58%  |
| 1 x Nvidia     | 22        | 15.83%  |
| Intel + Nvidia | 21        | 15.11%  |
| AMD + Nvidia   | 10        | 7.19%   |
| Other          | 5         | 3.6%    |
| 2 x AMD        | 3         | 2.16%   |
| 1 x Matrox     | 2         | 1.44%   |
| Intel + AMD    | 2         | 1.44%   |
| 2 x Intel      | 1         | 0.72%   |
| 1 x ASPEED     | 1         | 0.72%   |
| AMD + ASPEED   | 1         | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 97        | 69.78%  |
| Proprietary | 33        | 23.74%  |
| Unknown     | 9         | 6.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 61.54%  |
| 0.01-0.5   | 17        | 11.89%  |
| 7.01-8.0   | 14        | 9.79%   |
| 1.01-2.0   | 10        | 6.99%   |
| 3.01-4.0   | 9         | 6.29%   |
| 0.51-1.0   | 3         | 2.1%    |
| 8.01-16.0  | 2         | 1.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 24        | 16.67%  |
| AU Optronics         | 16        | 11.11%  |
| Samsung Electronics  | 15        | 10.42%  |
| BOE                  | 11        | 7.64%   |
| LG Display           | 10        | 6.94%   |
| Goldstar             | 10        | 6.94%   |
| Chimei Innolux       | 8         | 5.56%   |
| PANDA                | 6         | 4.17%   |
| Acer                 | 6         | 4.17%   |
| Sharp                | 4         | 2.78%   |
| CSO                  | 4         | 2.78%   |
| Hewlett-Packard      | 3         | 2.08%   |
| Apple                | 3         | 2.08%   |
| Panasonic            | 2         | 1.39%   |
| InfoVision           | 2         | 1.39%   |
| AOC                  | 2         | 1.39%   |
| Ancor Communications | 2         | 1.39%   |
| WST                  | 1         | 0.69%   |
| Vizio                | 1         | 0.69%   |
| ViewSonic            | 1         | 0.69%   |
| Unknown (AAA)        | 1         | 0.69%   |
| RTK                  | 1         | 0.69%   |
| Philips              | 1         | 0.69%   |
| NEC Computers        | 1         | 0.69%   |
| MPI                  | 1         | 0.69%   |
| Lenovo               | 1         | 0.69%   |
| JDI                  | 1         | 0.69%   |
| Iiyama               | 1         | 0.69%   |
| HVR                  | 1         | 0.69%   |
| HannStar             | 1         | 0.69%   |
| Eizo                 | 1         | 0.69%   |
| BenQ                 | 1         | 0.69%   |
| ASUSTek Computer     | 1         | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO019C 1920x1200 286x178mm 13.3-inch         | 3         | 2.04%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 2         | 1.36%   |
| Panasonic VVY13F001G10 MEI96A2 1920x1080 344x193mm 15.5-inch           | 2         | 1.36%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 2         | 1.36%   |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                       | 2         | 1.36%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                      | 2         | 1.36%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                    | 2         | 1.36%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                      | 2         | 1.36%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 2         | 1.36%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch         | 2         | 1.36%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                   | 2         | 1.36%   |
| WST KL.1350W.003 WST2C34 2256x1504 285x190mm 13.5-inch                 | 1         | 0.68%   |
| Vizio D43-D2 VIZ1004 1920x1080 477x268mm 21.5-inch                     | 1         | 0.68%   |
| ViewSonic VX2758-Series VSCA738 2560x1440 598x336mm 27.0-inch          | 1         | 0.68%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch            | 1         | 0.68%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 1         | 0.68%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 1         | 0.68%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.68%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch   | 1         | 0.68%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch      | 1         | 0.68%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch      | 1         | 0.68%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch      | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4160 3000x2000 285x190mm 13.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch  | 1         | 0.68%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch      | 1         | 0.68%   |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch      | 1         | 0.68%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1         | 0.68%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                      | 1         | 0.68%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1         | 0.68%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                | 1         | 0.68%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch                | 1         | 0.68%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch                | 1         | 0.68%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                | 1         | 0.68%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                | 1         | 0.68%   |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 49        | 35.51%  |
| 3840x2160 (4K)     | 26        | 18.84%  |
| 2560x1440 (QHD)    | 16        | 11.59%  |
| 1366x768 (WXGA)    | 9         | 6.52%   |
| 1920x1200 (WUXGA)  | 8         | 5.8%    |
| 1280x1024 (SXGA)   | 5         | 3.62%   |
| 2880x1800          | 4         | 2.9%    |
| 2560x1600          | 4         | 2.9%    |
| 2560x1080          | 4         | 2.9%    |
| 2256x1504          | 3         | 2.17%   |
| 3440x1440          | 2         | 1.45%   |
| 1680x1050 (WSXGA+) | 2         | 1.45%   |
| 3840x2400          | 1         | 0.72%   |
| 3000x2000          | 1         | 0.72%   |
| 2160x1200          | 1         | 0.72%   |
| 1440x900 (WXGA+)   | 1         | 0.72%   |
| 1280x720 (HD)      | 1         | 0.72%   |
| 1024x600           | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 25        | 17.61%  |
| 13      | 20        | 14.08%  |
| 14      | 18        | 12.68%  |
| 27      | 17        | 11.97%  |
| 24      | 13        | 9.15%   |
| 23      | 8         | 5.63%   |
| 17      | 7         | 4.93%   |
| 34      | 6         | 4.23%   |
| 31      | 5         | 3.52%   |
| 12      | 5         | 3.52%   |
| 25      | 2         | 1.41%   |
| 22      | 2         | 1.41%   |
| 21      | 2         | 1.41%   |
| 19      | 2         | 1.41%   |
| 16      | 2         | 1.41%   |
| 84      | 1         | 0.7%    |
| 49      | 1         | 0.7%    |
| 46      | 1         | 0.7%    |
| 38      | 1         | 0.7%    |
| 28      | 1         | 0.7%    |
| 11      | 1         | 0.7%    |
| 10      | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 36.23%  |
| 501-600     | 36        | 26.09%  |
| 201-300     | 24        | 17.39%  |
| 601-700     | 7         | 5.07%   |
| 701-800     | 6         | 4.35%   |
| 351-400     | 6         | 4.35%   |
| 401-500     | 4         | 2.9%    |
| 1001-1500   | 2         | 1.45%   |
| 801-900     | 1         | 0.72%   |
| 1501-2000   | 1         | 0.72%   |
| Unknown     | 1         | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 86        | 69.35%  |
| 16/10 | 22        | 17.74%  |
| 21/9  | 6         | 4.84%   |
| 5/4   | 5         | 4.03%   |
| 3/2   | 4         | 3.23%   |
| 1.00  | 1         | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 18.18%  |
| 81-90          | 25        | 17.48%  |
| 201-250        | 18        | 12.59%  |
| 301-350        | 17        | 11.89%  |
| 71-80          | 12        | 8.39%   |
| 351-500        | 12        | 8.39%   |
| 251-300        | 8         | 5.59%   |
| 61-70          | 5         | 3.5%    |
| 151-200        | 4         | 2.8%    |
| 141-150        | 3         | 2.1%    |
| 121-130        | 3         | 2.1%    |
| More than 1000 | 2         | 1.4%    |
| 111-120        | 2         | 1.4%    |
| 501-1000       | 2         | 1.4%    |
| 51-60          | 1         | 0.7%    |
| 41-50          | 1         | 0.7%    |
| 131-140        | 1         | 0.7%    |
| Unknown        | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 35        | 26.32%  |
| 161-240       | 32        | 24.06%  |
| 121-160       | 31        | 23.31%  |
| 101-120       | 19        | 14.29%  |
| More than 240 | 13        | 9.77%   |
| 1-50          | 2         | 1.5%    |
| Unknown       | 1         | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 89        | 61.81%  |
| 2     | 27        | 18.75%  |
| 0     | 23        | 15.97%  |
| 3     | 5         | 3.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 90        | 45%     |
| Realtek Semiconductor             | 74        | 37%     |
| Qualcomm Atheros                  | 8         | 4%      |
| MediaTek                          | 4         | 2%      |
| Broadcom                          | 4         | 2%      |
| Qualcomm                          | 2         | 1%      |
| Microsoft                         | 2         | 1%      |
| Lenovo                            | 2         | 1%      |
| Aquantia                          | 2         | 1%      |
| Xiaomi                            | 1         | 0.5%    |
| TP-Link                           | 1         | 0.5%    |
| Texas Instruments                 | 1         | 0.5%    |
| Standard Microsystems             | 1         | 0.5%    |
| Ralink Technology                 | 1         | 0.5%    |
| Ralink                            | 1         | 0.5%    |
| Pulse-Eight                       | 1         | 0.5%    |
| Oculus VR                         | 1         | 0.5%    |
| ICS Advent                        | 1         | 0.5%    |
| Google                            | 1         | 0.5%    |
| Fibocom                           | 1         | 0.5%    |
| Ericsson Business Mobile Networks | 1         | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 19.05%  |
| Intel Wi-Fi 6 AX200                                               | 19        | 8.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 6.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 4.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 2.6%    |
| Intel I211 Gigabit Network Connection                             | 5         | 2.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 2.16%   |
| Intel Wireless 8260                                               | 4         | 1.73%   |
| Intel Wireless 7265                                               | 4         | 1.73%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.73%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.73%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 3         | 1.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.3%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 1.3%    |
| Intel Wireless-AC 9260                                            | 3         | 1.3%    |
| Intel Wireless 7260                                               | 3         | 1.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 1.3%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.3%    |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.87%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 0.87%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.87%   |
| Intel Wireless 3165                                               | 2         | 0.87%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.87%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.87%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.87%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.87%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 72        | 71.29%  |
| Realtek Semiconductor | 7         | 6.93%   |
| Qualcomm Atheros      | 7         | 6.93%   |
| MediaTek              | 4         | 3.96%   |
| Broadcom              | 3         | 2.97%   |
| Qualcomm              | 2         | 1.98%   |
| Microsoft             | 2         | 1.98%   |
| TP-Link               | 1         | 0.99%   |
| Ralink Technology     | 1         | 0.99%   |
| Ralink                | 1         | 0.99%   |
| Fibocom               | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 19        | 18.81%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 5.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 4.95%   |
| Intel Wireless 8260                                            | 4         | 3.96%   |
| Intel Wireless 7265                                            | 4         | 3.96%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 3.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 3.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 2.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.97%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 2.97%   |
| Intel Wireless-AC 9260                                         | 3         | 2.97%   |
| Intel Wireless 7260                                            | 3         | 2.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 2.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 2.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.98%   |
| Microsoft Xbox 360 Wireless Adapter                            | 2         | 1.98%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.98%   |
| Intel Wireless 3165                                            | 2         | 1.98%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.98%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 1.98%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.99%   |
| Realtek 802.11ac NIC                                           | 1         | 0.99%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.99%   |
| Ralink RT2800 802.11n PCI                                      | 1         | 0.99%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.99%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.99%   |
| Intel Wireless 3160                                            | 1         | 0.99%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 0.99%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 68        | 56.67%  |
| Intel                 | 40        | 33.33%  |
| Qualcomm Atheros      | 2         | 1.67%   |
| Lenovo                | 2         | 1.67%   |
| Broadcom              | 2         | 1.67%   |
| Aquantia              | 2         | 1.67%   |
| Xiaomi                | 1         | 0.83%   |
| Standard Microsystems | 1         | 0.83%   |
| ICS Advent            | 1         | 0.83%   |
| Google                | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 34.92%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 12.7%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 7.94%   |
| Intel I211 Gigabit Network Connection                             | 5         | 3.97%   |
| Intel Ethernet Controller I225-V                                  | 4         | 3.17%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.17%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.38%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 2.38%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.59%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.59%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.59%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.59%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.79%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.79%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.79%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.79%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.79%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.79%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.79%   |
| ICS Advent 10/100M LAN                                            | 1         | 0.79%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.79%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.79%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.79%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.79%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 108       | 51.18%  |
| WiFi     | 99        | 46.92%  |
| Modem    | 4         | 1.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 58.04%  |
| Ethernet | 60        | 41.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 69        | 49.64%  |
| 2     | 61        | 43.88%  |
| 0     | 5         | 3.6%    |
| 3     | 3         | 2.16%   |
| 4     | 1         | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 104       | 73.24%  |
| Yes  | 38        | 26.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 67.01%  |
| Realtek Semiconductor           | 8         | 8.25%   |
| Qualcomm Atheros Communications | 4         | 4.12%   |
| ASUSTek Computer                | 4         | 4.12%   |
| MediaTek                        | 3         | 3.09%   |
| Cambridge Silicon Radio         | 3         | 3.09%   |
| Broadcom                        | 3         | 3.09%   |
| Apple                           | 3         | 3.09%   |
| USI                             | 1         | 1.03%   |
| Lite-On Technology              | 1         | 1.03%   |
| HTC (High Tech Computer)        | 1         | 1.03%   |
| Foxconn / Hon Hai               | 1         | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 17        | 17.53%  |
| Intel Bluetooth wireless interface                                   | 13        | 13.4%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 9         | 9.28%   |
| Intel AX201 Bluetooth                                                | 9         | 9.28%   |
| Realtek Bluetooth Radio                                              | 8         | 8.25%   |
| Intel AX210 Bluetooth                                                | 6         | 6.19%   |
| Intel Bluetooth Device                                               | 5         | 5.15%   |
| Qualcomm Atheros  Bluetooth Device                                   | 3         | 3.09%   |
| MediaTek Wireless_Device                                             | 3         | 3.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 3.09%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 3.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 3         | 3.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 2.06%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 2.06%   |
| Apple Bluetooth Host Controller                                      | 2         | 2.06%   |
| USI Bluetooth Device                                                 | 1         | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 1.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 1.03%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.03%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1         | 1.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 1.03%   |
| ASUS Broadcom Bluetooth 2.1                                          | 1         | 1.03%   |
| ASUS ASUS USB-BT500                                                  | 1         | 1.03%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 81        | 37.16%  |
| AMD                                  | 56        | 25.69%  |
| Nvidia                               | 37        | 16.97%  |
| C-Media Electronics                  | 6         | 2.75%   |
| Creative Technology                  | 4         | 1.83%   |
| Texas Instruments                    | 3         | 1.38%   |
| Sennheiser Communications            | 3         | 1.38%   |
| Lenovo                               | 3         | 1.38%   |
| Synaptics                            | 2         | 0.92%   |
| Realtek Semiconductor                | 2         | 0.92%   |
| Razer USA                            | 2         | 0.92%   |
| Kingston Technology                  | 2         | 0.92%   |
| Focusrite-Novation                   | 2         | 0.92%   |
| Trust                                | 1         | 0.46%   |
| Thomann                              | 1         | 0.46%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.46%   |
| Sony                                 | 1         | 0.46%   |
| Schiit Audio                         | 1         | 0.46%   |
| Satechi                              | 1         | 0.46%   |
| PreSonus Audio Electronics           | 1         | 0.46%   |
| Logitech                             | 1         | 0.46%   |
| GYROCOM C&C                          | 1         | 0.46%   |
| Edifier Technology                   | 1         | 0.46%   |
| Creative Labs                        | 1         | 0.46%   |
| Corsair                              | 1         | 0.46%   |
| ASRock                               | 1         | 0.46%   |
| Antlion Audio                        | 1         | 0.46%   |
| (LCS) USB Audio Device               | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 24        | 9.09%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 20        | 7.58%   |
| AMD Starship/Matisse HD Audio Controller                                | 18        | 6.82%   |
| Intel Sunrise Point-LP HD Audio                                         | 13        | 4.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 8         | 3.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 8         | 3.03%   |
| Intel Cannon Lake PCH cAVS                                              | 6         | 2.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 6         | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 6         | 2.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 6         | 2.27%   |
| AMD Navi 10 HDMI Audio                                                  | 6         | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 6         | 2.27%   |
| Nvidia TU106 High Definition Audio Controller                           | 5         | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 5         | 1.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 5         | 1.89%   |
| Nvidia GP107GL High Definition Audio Controller                         | 4         | 1.52%   |
| Nvidia GK104 HDMI Audio Controller                                      | 4         | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 4         | 1.52%   |
| Nvidia GA106 High Definition Audio Controller                           | 3         | 1.14%   |
| Nvidia GA104 High Definition Audio Controller                           | 3         | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 3         | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 3         | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                            | 3         | 1.14%   |
| Intel Comet Lake PCH cAVS                                               | 3         | 1.14%   |
| Creative Technology SoundBlaster Live! 24-bit External SB0490           | 3         | 1.14%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 3         | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 3         | 1.14%   |
| Texas Instruments PCM2902 Audio Codec                                   | 2         | 0.76%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 0.76%   |
| Sennheiser Communications Headset [PC 8]                                | 2         | 0.76%   |
| Realtek Semiconductor USB Audio                                         | 2         | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                           | 2         | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 2         | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                           | 2         | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                           | 2         | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 0.76%   |
| Kingston Technology HyperX 7.1 Audio                                    | 2         | 0.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 2         | 0.76%   |
| Intel Haswell-ULT HD Audio Controller                                   | 2         | 0.76%   |
| Intel C610/X99 series chipset HD Audio Controller                       | 2         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 37        | 23.87%  |
| Kingston            | 20        | 12.9%   |
| SK hynix            | 18        | 11.61%  |
| Corsair             | 16        | 10.32%  |
| Micron Technology   | 15        | 9.68%   |
| Crucial             | 13        | 8.39%   |
| G.Skill             | 11        | 7.1%    |
| Team                | 6         | 3.87%   |
| Unknown (ABCD)      | 4         | 2.58%   |
| Unknown             | 4         | 2.58%   |
| A-DATA Technology   | 3         | 1.94%   |
| GOODRAM             | 2         | 1.29%   |
| AMD                 | 2         | 1.29%   |
| Strontium           | 1         | 0.65%   |
| Ramaxel Technology  | 1         | 0.65%   |
| Avant               | 1         | 0.65%   |
| Unknown             | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 1.78%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 3         | 1.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.78%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 3         | 1.78%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 3         | 1.78%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.18%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.18%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.18%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.18%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.18%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.18%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 1.18%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 1.18%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 1.18%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 2         | 1.18%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s           | 2         | 1.18%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.59%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.59%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.59%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                    | 1         | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.59%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 1         | 0.59%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s               | 1         | 0.59%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s              | 1         | 0.59%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.59%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s               | 1         | 0.59%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                     | 1         | 0.59%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.59%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.59%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.59%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.59%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.59%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.59%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 1         | 0.59%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.59%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.59%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.59%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 84        | 63.64%  |
| DDR3   | 23        | 17.42%  |
| LPDDR4 | 12        | 9.09%   |
| LPDDR5 | 5         | 3.79%   |
| LPDDR3 | 5         | 3.79%   |
| DDR5   | 2         | 1.52%   |
| SDRAM  | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 47.41%  |
| DIMM         | 47        | 34.81%  |
| Row Of Chips | 20        | 14.81%  |
| Chip         | 2         | 1.48%   |
| RIMM         | 1         | 0.74%   |
| Unknown      | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 59        | 39.86%  |
| 16384 | 47        | 31.76%  |
| 32768 | 19        | 12.84%  |
| 4096  | 19        | 12.84%  |
| 2048  | 3         | 2.03%   |
| 1024  | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 38        | 26.03%  |
| 1600    | 17        | 11.64%  |
| 2667    | 16        | 10.96%  |
| 2400    | 12        | 8.22%   |
| 2133    | 11        | 7.53%   |
| 3600    | 7         | 4.79%   |
| 4267    | 6         | 4.11%   |
| 6400    | 5         | 3.42%   |
| 3000    | 5         | 3.42%   |
| 3733    | 4         | 2.74%   |
| 1867    | 4         | 2.74%   |
| 1333    | 3         | 2.05%   |
| 4800    | 2         | 1.37%   |
| 4266    | 2         | 1.37%   |
| 3400    | 2         | 1.37%   |
| 3334    | 2         | 1.37%   |
| 2933    | 2         | 1.37%   |
| 3866    | 1         | 0.68%   |
| 3666    | 1         | 0.68%   |
| 3534    | 1         | 0.68%   |
| 3266    | 1         | 0.68%   |
| 2134    | 1         | 0.68%   |
| 2132    | 1         | 0.68%   |
| 1066    | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

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
| Chicony Electronics           | 16        | 18.18%  |
| Logitech                      | 12        | 13.64%  |
| Microdia                      | 11        | 12.5%   |
| IMC Networks                  | 10        | 11.36%  |
| Realtek Semiconductor         | 8         | 9.09%   |
| Acer                          | 7         | 7.95%   |
| Bison Electronics             | 6         | 6.82%   |
| Sunplus Innovation Technology | 4         | 4.55%   |
| Quanta                        | 3         | 3.41%   |
| MacroSilicon                  | 2         | 2.27%   |
| Lite-On Technology            | 2         | 2.27%   |
| Apple                         | 2         | 2.27%   |
| Syntek                        | 1         | 1.14%   |
| SunplusIT                     | 1         | 1.14%   |
| Microsoft                     | 1         | 1.14%   |
| Alcor Micro                   | 1         | 1.14%   |
| 2M UVC CAMERA                 | 1         | 1.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 10        | 11.24%  |
| Microdia Integrated_Webcam_HD        | 6         | 6.74%   |
| IMC Networks USB2.0 HD UVC WebCam    | 5         | 5.62%   |
| Acer Integrated Camera               | 4         | 4.49%   |
| Logitech HD Pro Webcam C920          | 3         | 3.37%   |
| IMC Networks Integrated Camera       | 3         | 3.37%   |
| Chicony HP HD Camera                 | 3         | 3.37%   |
| Bison Integrated Camera              | 3         | 3.37%   |
| Sunplus Integrated_Webcam_FHD        | 2         | 2.25%   |
| Realtek Laptop Camera                | 2         | 2.25%   |
| Realtek Integrated_Webcam_HD         | 2         | 2.25%   |
| MacroSilicon USB Video               | 2         | 2.25%   |
| Logitech Webcam C270                 | 2         | 2.25%   |
| Acer Integrated IR Camera            | 2         | 2.25%   |
| Syntek Integrated Camera             | 1         | 1.12%   |
| SunplusIT HP TrueVision HD Camera    | 1         | 1.12%   |
| Sunplus Integrated_Webcam_HD         | 1         | 1.12%   |
| Sunplus HD WebCam                    | 1         | 1.12%   |
| Realtek TV Camera                    | 1         | 1.12%   |
| Realtek Realtek USB MIC              | 1         | 1.12%   |
| Realtek Lenovo EasyCamera            | 1         | 1.12%   |
| Realtek Integrated Webcam            | 1         | 1.12%   |
| Realtek EasyCamera                   | 1         | 1.12%   |
| Quanta VGA WebCam                    | 1         | 1.12%   |
| Quanta HP True Vision HD Camera      | 1         | 1.12%   |
| Quanta HD WebCam                     | 1         | 1.12%   |
| Microsoft LifeCam HD-3000            | 1         | 1.12%   |
| Microdia Webcam Vitade AF            | 1         | 1.12%   |
| Microdia USB 2.0 Camera              | 1         | 1.12%   |
| Microdia Laptop_Integrated_Webcam_HD | 1         | 1.12%   |
| Microdia Integrated Webcam           | 1         | 1.12%   |
| Microdia Camera                      | 1         | 1.12%   |
| Logitech Webcam C930e                | 1         | 1.12%   |
| Logitech Webcam C310                 | 1         | 1.12%   |
| Logitech Webcam C120                 | 1         | 1.12%   |
| Logitech StreamCam                   | 1         | 1.12%   |
| Logitech HD Webcam C615              | 1         | 1.12%   |
| Logitech C930c                       | 1         | 1.12%   |
| Logitech C922 Pro Stream Webcam      | 1         | 1.12%   |
| Lite-On Integrated Camera            | 1         | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 45.45%  |
| Validity Sensors           | 7         | 31.82%  |
| Shenzhen Goodix Technology | 4         | 18.18%  |
| Gingytech                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 10        | 71.43%  |
| Yubico.com  | 2         | 14.29%  |
| Upek        | 1         | 7.14%   |
| Broadcom    | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 80        | 55.94%  |
| 1     | 42        | 29.37%  |
| 2     | 18        | 12.59%  |
| 4     | 2         | 1.4%    |
| 3     | 1         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 20        | 22.99%  |
| Multimedia controller    | 17        | 19.54%  |
| Graphics card            | 17        | 19.54%  |
| Chipcard                 | 10        | 11.49%  |
| Net/wireless             | 6         | 6.9%    |
| Bluetooth                | 4         | 4.6%    |
| Unassigned class         | 3         | 3.45%   |
| Camera                   | 3         | 3.45%   |
| Modem                    | 2         | 2.3%    |
| Storage/ata              | 1         | 1.15%   |
| Network                  | 1         | 1.15%   |
| Dvb card                 | 1         | 1.15%   |
| Communication controller | 1         | 1.15%   |
| Card reader              | 1         | 1.15%   |

