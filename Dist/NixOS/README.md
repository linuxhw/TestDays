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

Total: 189

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| NixOS 22.11                      | 39        | 26.9%   |
| NixOS 22.05                      | 37        | 25.52%  |
| NixOS 21.11                      | 18        | 12.41%  |
| NixOS 23.05                      | 16        | 11.03%  |
| NixOS                            | 5         | 3.45%   |
| NixOS 21.05pre-git               | 2         | 1.38%   |
| NixOS 20.09pre-git               | 2         | 1.38%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.69%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.69%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.69%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.69%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.69%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.69%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.69%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.69%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.69%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.69%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.69%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.69%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.69%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.69%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.69%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.69%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.69%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.69%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.69%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.69%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.69%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.69%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.69%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.69%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.69%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 127       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 5.15.74          | 5         | 3.27%   |
| 5.15.43          | 4         | 2.61%   |
| 6.2.0-rc6        | 3         | 1.96%   |
| 6.1.0            | 3         | 1.96%   |
| 6.0.11           | 3         | 1.96%   |
| 6.0.10           | 3         | 1.96%   |
| 5.15.86          | 3         | 1.96%   |
| 5.15.82          | 3         | 1.96%   |
| 5.15.72          | 3         | 1.96%   |
| 5.15.68          | 3         | 1.96%   |
| 5.15.47          | 3         | 1.96%   |
| 5.15.26          | 3         | 1.96%   |
| 6.1.1            | 2         | 1.31%   |
| 5.8.1-zen1       | 2         | 1.31%   |
| 5.19.14          | 2         | 1.31%   |
| 5.18.19          | 2         | 1.31%   |
| 5.17.1           | 2         | 1.31%   |
| 5.16.8-zen1      | 2         | 1.31%   |
| 5.16.15          | 2         | 1.31%   |
| 5.15.92          | 2         | 1.31%   |
| 5.15.85          | 2         | 1.31%   |
| 5.15.64          | 2         | 1.31%   |
| 5.15.32          | 2         | 1.31%   |
| 5.15.25          | 2         | 1.31%   |
| 5.13.7           | 2         | 1.31%   |
| 5.13.2           | 2         | 1.31%   |
| 5.12.15          | 2         | 1.31%   |
| 5.10.102         | 2         | 1.31%   |
| 6.2.7            | 1         | 0.65%   |
| 6.2.1            | 1         | 0.65%   |
| 6.2.0            | 1         | 0.65%   |
| 6.1.9            | 1         | 0.65%   |
| 6.1.7-xanmod1    | 1         | 0.65%   |
| 6.1.14           | 1         | 0.65%   |
| 6.1.10           | 1         | 0.65%   |
| 6.1.0-zen1       | 1         | 0.65%   |
| 6.0.8-zen1       | 1         | 0.65%   |
| 6.0.6            | 1         | 0.65%   |
| 6.0.2-xanmod1-tt | 1         | 0.65%   |
| 6.0.2            | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.74  | 5         | 3.27%   |
| 6.2.0    | 4         | 2.61%   |
| 6.1.0    | 4         | 2.61%   |
| 6.0.10   | 4         | 2.61%   |
| 5.15.43  | 4         | 2.61%   |
| 6.0.11   | 3         | 1.96%   |
| 5.15.86  | 3         | 1.96%   |
| 5.15.82  | 3         | 1.96%   |
| 5.15.72  | 3         | 1.96%   |
| 5.15.68  | 3         | 1.96%   |
| 5.15.47  | 3         | 1.96%   |
| 5.15.26  | 3         | 1.96%   |
| 6.1.1    | 2         | 1.31%   |
| 6.0.2    | 2         | 1.31%   |
| 5.8.1    | 2         | 1.31%   |
| 5.19.14  | 2         | 1.31%   |
| 5.18.19  | 2         | 1.31%   |
| 5.17.1   | 2         | 1.31%   |
| 5.16.8   | 2         | 1.31%   |
| 5.16.15  | 2         | 1.31%   |
| 5.15.92  | 2         | 1.31%   |
| 5.15.85  | 2         | 1.31%   |
| 5.15.83  | 2         | 1.31%   |
| 5.15.64  | 2         | 1.31%   |
| 5.15.32  | 2         | 1.31%   |
| 5.15.25  | 2         | 1.31%   |
| 5.13.7   | 2         | 1.31%   |
| 5.13.2   | 2         | 1.31%   |
| 5.12.15  | 2         | 1.31%   |
| 5.11.16  | 2         | 1.31%   |
| 5.10.102 | 2         | 1.31%   |
| 6.2.7    | 1         | 0.65%   |
| 6.2.1    | 1         | 0.65%   |
| 6.1.9    | 1         | 0.65%   |
| 6.1.7    | 1         | 0.65%   |
| 6.1.14   | 1         | 0.65%   |
| 6.1.10   | 1         | 0.65%   |
| 6.0.8    | 1         | 0.65%   |
| 6.0.6    | 1         | 0.65%   |
| 6.0.12   | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 52        | 35.37%  |
| 5.10    | 14        | 9.52%   |
| 6.0     | 13        | 8.84%   |
| 6.1     | 10        | 6.8%    |
| 5.16    | 8         | 5.44%   |
| 5.4     | 7         | 4.76%   |
| 5.19    | 7         | 4.76%   |
| 6.2     | 6         | 4.08%   |
| 5.8     | 6         | 4.08%   |
| 5.18    | 5         | 3.4%    |
| 5.13    | 4         | 2.72%   |
| 5.7     | 3         | 2.04%   |
| 5.17    | 3         | 2.04%   |
| 5.12    | 3         | 2.04%   |
| 5.14    | 2         | 1.36%   |
| 5.11    | 2         | 1.36%   |
| 4.19    | 2         | 1.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 122       | 96.06%  |
| aarch64 | 4         | 3.15%   |
| i686    | 1         | 0.79%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 85        | 63.43%  |
| sway         | 11        | 8.21%   |
| KDE5         | 9         | 6.72%   |
| GNOME        | 9         | 6.72%   |
| XFCE         | 6         | 4.48%   |
| none+i3      | 4         | 2.99%   |
| KDE          | 4         | 2.99%   |
| none+xmonad  | 2         | 1.49%   |
| X-Generic    | 1         | 0.75%   |
| none+bspwm   | 1         | 0.75%   |
| none+awesome | 1         | 0.75%   |
| Hyprland     | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 76        | 56.72%  |
| X11     | 26        | 19.4%   |
| Wayland | 19        | 14.18%  |
| Tty     | 13        | 9.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 88        | 68.75%  |
| LightDM | 17        | 13.28%  |
| SDDM    | 14        | 10.94%  |
| GDM     | 9         | 7.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 55        | 42.64%  |
| Unknown | 54        | 41.86%  |
| en_GB   | 3         | 2.33%   |
| ru_RU   | 2         | 1.55%   |
| fr_FR   | 2         | 1.55%   |
| en_DK   | 2         | 1.55%   |
| en_AU   | 2         | 1.55%   |
| de_DE   | 2         | 1.55%   |
| de_CH   | 2         | 1.55%   |
| ro_RO   | 1         | 0.78%   |
| pt_BR   | 1         | 0.78%   |
| lv_LV   | 1         | 0.78%   |
| it_IT   | 1         | 0.78%   |
| en_CA   | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 109       | 84.5%   |
| BIOS | 20        | 15.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 65        | 49.62%  |
| Btrfs   | 22        | 16.79%  |
| Xfs     | 14        | 10.69%  |
| Zfs     | 13        | 9.92%   |
| Tmpfs   | 10        | 7.63%   |
| Unknown | 6         | 4.58%   |
| Ext2    | 1         | 0.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 120       | 92.31%  |
| Unknown | 8         | 6.15%   |
| MBR     | 2         | 1.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 74.81%  |
| Yes       | 33        | 25.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 68.5%   |
| Yes       | 40        | 31.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 28        | 22.05%  |
| ASUSTek Computer                     | 25        | 19.69%  |
| Dell                                 | 16        | 12.6%   |
| MSI                                  | 12        | 9.45%   |
| Hewlett-Packard                      | 8         | 6.3%    |
| Gigabyte Technology                  | 6         | 4.72%   |
| ASRock                               | 6         | 4.72%   |
| Acer                                 | 4         | 3.15%   |
| GPD                                  | 3         | 2.36%   |
| Supermicro                           | 2         | 1.57%   |
| Raspberry Pi Foundation              | 2         | 1.57%   |
| Pine Microsystems                    | 2         | 1.57%   |
| Framework                            | 2         | 1.57%   |
| Apple                                | 2         | 1.57%   |
| Toshiba                              | 1         | 0.79%   |
| Teclast                              | 1         | 0.79%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.79%   |
| OBSIDIAN-PC                          | 1         | 0.79%   |
| MECHREVO                             | 1         | 0.79%   |
| Intel                                | 1         | 0.79%   |
| Hardkernel                           | 1         | 0.79%   |
| EVGA                                 | 1         | 0.79%   |
| Blackview                            | 1         | 0.79%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo 13w Yoga 82S1                       | 3         | 2.36%   |
| Pine Microsystems Pine64 PinePhone (1.2)   | 2         | 1.57%   |
| MSI MS-7C56                                | 2         | 1.57%   |
| MSI MS-7C37                                | 2         | 1.57%   |
| Dell Latitude 7420                         | 2         | 1.57%   |
| ASUS Zenbook UX3402ZA_UX3402ZA             | 2         | 1.57%   |
| ASUS All Series                            | 2         | 1.57%   |
| Toshiba Satellite L50-B                    | 1         | 0.79%   |
| Teclast F5                                 | 1         | 0.79%   |
| Supermicro X8DT6                           | 1         | 0.79%   |
| Supermicro X10SLL-F                        | 1         | 0.79%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.79%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 1         | 0.79%   |
| RPi Raspberry Pi 3 Model B+                | 1         | 0.79%   |
| OBSIDIAN-PC N13_N140ZU                     | 1         | 0.79%   |
| MSI MS-7C95                                | 1         | 0.79%   |
| MSI MS-7C91                                | 1         | 0.79%   |
| MSI MS-7C84                                | 1         | 0.79%   |
| MSI MS-7C35                                | 1         | 0.79%   |
| MSI MS-7B89                                | 1         | 0.79%   |
| MSI MS-7B09                                | 1         | 0.79%   |
| MSI MS-7758                                | 1         | 0.79%   |
| MSI Bravo 15 B5DD                          | 1         | 0.79%   |
| MECHREVO Code01 Ver2.0                     | 1         | 0.79%   |
| Lenovo Yoga Slim 7 13ACN5 82CY             | 1         | 0.79%   |
| Lenovo Yoga 520-14IKB 81C8                 | 1         | 0.79%   |
| Lenovo ThinkPad X390 20Q0CTO1WW            | 1         | 0.79%   |
| Lenovo ThinkPad X260 20F5S6MF02            | 1         | 0.79%   |
| Lenovo ThinkPad X260 20F5S4BY00            | 1         | 0.79%   |
| Lenovo ThinkPad X250 20CLS18S0T            | 1         | 0.79%   |
| Lenovo ThinkPad X230 2333AZ2               | 1         | 0.79%   |
| Lenovo ThinkPad X230 23243E9               | 1         | 0.79%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW      | 1         | 0.79%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBCT01WW   | 1         | 0.79%   |
| Lenovo ThinkPad T580 20L90024PB            | 1         | 0.79%   |
| Lenovo ThinkPad T540p 20BE005YMH           | 1         | 0.79%   |
| Lenovo ThinkPad T490 20N2000LUK            | 1         | 0.79%   |
| Lenovo ThinkPad T480 20L5CTO1WW            | 1         | 0.79%   |
| Lenovo ThinkPad T460p 20FWCTO1WW           | 1         | 0.79%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW       | 1         | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 19        | 14.96%  |
| ASUS ROG                                   | 6         | 4.72%   |
| Dell XPS                                   | 5         | 3.94%   |
| ASUS PRIME                                 | 5         | 3.94%   |
| Dell Inspiron                              | 4         | 3.15%   |
| Lenovo 13w                                 | 3         | 2.36%   |
| Dell Precision                             | 3         | 2.36%   |
| Dell Latitude                              | 3         | 2.36%   |
| ASUS Zenbook                               | 3         | 2.36%   |
| RPi Raspberry                              | 2         | 1.57%   |
| Pine Microsystems Pine64                   | 2         | 1.57%   |
| MSI MS-7C56                                | 2         | 1.57%   |
| MSI MS-7C37                                | 2         | 1.57%   |
| Lenovo Yoga                                | 2         | 1.57%   |
| Lenovo Legion                              | 2         | 1.57%   |
| HP Spectre                                 | 2         | 1.57%   |
| HP ProBook                                 | 2         | 1.57%   |
| Framework Laptop                           | 2         | 1.57%   |
| ASUS All                                   | 2         | 1.57%   |
| Acer Aspire                                | 2         | 1.57%   |
| Toshiba Satellite                          | 1         | 0.79%   |
| Teclast F5                                 | 1         | 0.79%   |
| Supermicro X8DT6                           | 1         | 0.79%   |
| Supermicro X10SLL-F                        | 1         | 0.79%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.79%   |
| OBSIDIAN-PC N13                            | 1         | 0.79%   |
| MSI MS-7C95                                | 1         | 0.79%   |
| MSI MS-7C91                                | 1         | 0.79%   |
| MSI MS-7C84                                | 1         | 0.79%   |
| MSI MS-7C35                                | 1         | 0.79%   |
| MSI MS-7B89                                | 1         | 0.79%   |
| MSI MS-7B09                                | 1         | 0.79%   |
| MSI MS-7758                                | 1         | 0.79%   |
| MSI Bravo                                  | 1         | 0.79%   |
| MECHREVO Code01                            | 1         | 0.79%   |
| Lenovo IdeaPadFlex                         | 1         | 0.79%   |
| Lenovo IdeaPad                             | 1         | 0.79%   |
| Intel NUC11PAHi7                           | 1         | 0.79%   |
| HP ZBook                                   | 1         | 0.79%   |
| HP ENVY                                    | 1         | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 26        | 20.47%  |
| 2019    | 20        | 15.75%  |
| 2021    | 15        | 11.81%  |
| 2018    | 13        | 10.24%  |
| 2022    | 11        | 8.66%   |
| 2016    | 11        | 8.66%   |
| 2017    | 6         | 4.72%   |
| 2015    | 5         | 3.94%   |
| 2013    | 5         | 3.94%   |
| 2012    | 5         | 3.94%   |
| 2014    | 4         | 3.15%   |
| Unknown | 4         | 3.15%   |
| 2010    | 1         | 0.79%   |
| 2009    | 1         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 59        | 46.46%  |
| Desktop        | 45        | 35.43%  |
| Convertible    | 13        | 10.24%  |
| Server         | 3         | 2.36%   |
| Phone          | 2         | 1.57%   |
| System on chip | 2         | 1.57%   |
| Tablet         | 1         | 0.79%   |
| Mini pc        | 1         | 0.79%   |
| All in one     | 1         | 0.79%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 127       | 99.22%  |
| Enabled  | 1         | 0.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 126       | 99.21%  |
| Yes  | 1         | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 36        | 27.69%  |
| 16.01-24.0  | 30        | 23.08%  |
| 8.01-16.0   | 21        | 16.15%  |
| 64.01-256.0 | 15        | 11.54%  |
| 4.01-8.0    | 13        | 10%     |
| 24.01-32.0  | 7         | 5.38%   |
| 3.01-4.0    | 5         | 3.85%   |
| 0.51-1.0    | 2         | 1.54%   |
| 1.01-2.0    | 1         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 39        | 27.46%  |
| 8.01-16.0   | 25        | 17.61%  |
| 3.01-4.0    | 19        | 13.38%  |
| 2.01-3.0    | 17        | 11.97%  |
| 1.01-2.0    | 15        | 10.56%  |
| 32.01-64.0  | 6         | 4.23%   |
| 24.01-32.0  | 6         | 4.23%   |
| 16.01-24.0  | 6         | 4.23%   |
| 0.51-1.0    | 6         | 4.23%   |
| 0.01-0.5    | 2         | 1.41%   |
| 64.01-256.0 | 1         | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 54.96%  |
| 2      | 33        | 25.19%  |
| 3      | 10        | 7.63%   |
| 5      | 5         | 3.82%   |
| 6      | 4         | 3.05%   |
| 4      | 2         | 1.53%   |
| 23     | 1         | 0.76%   |
| 17     | 1         | 0.76%   |
| 11     | 1         | 0.76%   |
| 8      | 1         | 0.76%   |
| 0      | 1         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 90.55%  |
| Yes       | 12        | 9.45%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 74.62%  |
| No        | 33        | 25.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 71.65%  |
| No        | 36        | 28.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 67.44%  |
| No        | 42        | 32.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 23        | 18.11%  |
| Germany     | 14        | 11.02%  |
| UK          | 10        | 7.87%   |
| France      | 9         | 7.09%   |
| Russia      | 8         | 6.3%    |
| Poland      | 8         | 6.3%    |
| Italy       | 7         | 5.51%   |
| Canada      | 7         | 5.51%   |
| Ukraine     | 6         | 4.72%   |
| Switzerland | 4         | 3.15%   |
| Austria     | 4         | 3.15%   |
| Czechia     | 3         | 2.36%   |
| Netherlands | 2         | 1.57%   |
| Denmark     | 2         | 1.57%   |
| Belgium     | 2         | 1.57%   |
| Australia   | 2         | 1.57%   |
| Uruguay     | 1         | 0.79%   |
| Sweden      | 1         | 0.79%   |
| Spain       | 1         | 0.79%   |
| Serbia      | 1         | 0.79%   |
| Romania     | 1         | 0.79%   |
| Portugal    | 1         | 0.79%   |
| New Zealand | 1         | 0.79%   |
| Latvia      | 1         | 0.79%   |
| Kyrgyzstan  | 1         | 0.79%   |
| Iraq        | 1         | 0.79%   |
| Iran        | 1         | 0.79%   |
| India       | 1         | 0.79%   |
| Hungary     | 1         | 0.79%   |
| Colombia    | 1         | 0.79%   |
| China       | 1         | 0.79%   |
| Brazil      | 1         | 0.79%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Vienna             | 4         | 2.88%   |
| Marki              | 4         | 2.88%   |
| Kharkiv            | 4         | 2.88%   |
| Frankfurt am Main  | 4         | 2.88%   |
| Plymouth           | 3         | 2.16%   |
| Milwaukee          | 3         | 2.16%   |
| Capo d'Orlando     | 3         | 2.16%   |
| South Deerfield    | 2         | 1.44%   |
| Schaafheim         | 2         | 1.44%   |
| Richardson         | 2         | 1.44%   |
| Prague             | 2         | 1.44%   |
| Ottawa             | 2         | 1.44%   |
| Melbourne          | 2         | 1.44%   |
| Lyon               | 2         | 1.44%   |
| London             | 2         | 1.44%   |
| Krasnodar          | 2         | 1.44%   |
| Halifax            | 2         | 1.44%   |
| Gdansk             | 2         | 1.44%   |
| Darmstadt          | 2         | 1.44%   |
| Chelyabinsk        | 2         | 1.44%   |
| Austin             | 2         | 1.44%   |
| Zurich             | 1         | 0.72%   |
| Yangzhou           | 1         | 0.72%   |
| Woodford           | 1         | 0.72%   |
| Wellington         | 1         | 0.72%   |
| Warsaw             | 1         | 0.72%   |
| Villeurbanne       | 1         | 0.72%   |
| Verneuil-sur-Seine | 1         | 0.72%   |
| Valpacos           | 1         | 0.72%   |
| Trento             | 1         | 0.72%   |
| Tottenham          | 1         | 0.72%   |
| Tolyatti           | 1         | 0.72%   |
| Tehran             | 1         | 0.72%   |
| Talas              | 1         | 0.72%   |
| Székesfehérvár  | 1         | 0.72%   |
| Stockholm          | 1         | 0.72%   |
| Southampton        | 1         | 0.72%   |
| Sindelfingen       | 1         | 0.72%   |
| Saratov            | 1         | 0.72%   |
| San Gabriel        | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 50        | 106    | 25.51%  |
| WDC                         | 18        | 40     | 9.18%   |
| SanDisk                     | 17        | 23     | 8.67%   |
| Seagate                     | 15        | 44     | 7.65%   |
| Toshiba                     | 13        | 26     | 6.63%   |
| Crucial                     | 11        | 16     | 5.61%   |
| Kingston                    | 8         | 8      | 4.08%   |
| Intel                       | 8         | 13     | 4.08%   |
| Micron Technology           | 7         | 7      | 3.57%   |
| SK hynix                    | 6         | 9      | 3.06%   |
| Unknown                     | 5         | 8      | 2.55%   |
| HGST                        | 4         | 14     | 2.04%   |
| Transcend                   | 2         | 2      | 1.02%   |
| Plextor                     | 2         | 2      | 1.02%   |
| Phison Electronics          | 2         | 4      | 1.02%   |
| KIOXIA                      | 2         | 3      | 1.02%   |
| Kingston Technology Company | 2         | 2      | 1.02%   |
| Hitachi                     | 2         | 4      | 1.02%   |
| China                       | 2         | 2      | 1.02%   |
| Apple                       | 2         | 5      | 1.02%   |
| Yangtze Memory Technologies | 1         | 1      | 0.51%   |
| Teclast                     | 1         | 2      | 0.51%   |
| SPCC                        | 1         | 1      | 0.51%   |
| Silicon Motion              | 1         | 1      | 0.51%   |
| Realtek Semiconductor       | 1         | 1      | 0.51%   |
| Phison                      | 1         | 1      | 0.51%   |
| OCZ                         | 1         | 1      | 0.51%   |
| LITEON                      | 1         | 1      | 0.51%   |
| Lexar                       | 1         | 1      | 0.51%   |
| INNOVATION IT               | 1         | 1      | 0.51%   |
| Dogfish                     | 1         | 1      | 0.51%   |
| Corsair                     | 1         | 1      | 0.51%   |
| Biwin Storage Technology    | 1         | 1      | 0.51%   |
| BIWIN                       | 1         | 1      | 0.51%   |
| ASMT                        | 1         | 1      | 0.51%   |
| ASMedia                     | 1         | 1      | 0.51%   |
| ADATA Technology            | 1         | 2      | 0.51%   |
| Unknown                     | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB                             | 5         | 2.1%    |
| Unknown MMC Card  32GB                              | 3         | 1.26%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3         | 1.26%   |
| SanDisk SSD PLUS 240GB                              | 3         | 1.26%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3         | 1.26%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 1.26%   |
| Samsung SSD 970 EVO 500GB                           | 3         | 1.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 1.26%   |
| Micron MTFDKCD512TFK 512GB                          | 3         | 1.26%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 1.26%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 2         | 0.84%   |
| Seagate ST3000DM001-1CH166 3TB                      | 2         | 0.84%   |
| Sandisk WD Black SN850 1TB                          | 2         | 0.84%   |
| SanDisk Ultra II 240GB SSD                          | 2         | 0.84%   |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.84%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.84%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 0.84%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.84%   |
| Samsung SSD 860 QVO 1TB                             | 2         | 0.84%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.84%   |
| Samsung SSD 860 EVO 2TB                             | 2         | 0.84%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.84%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.84%   |
| Samsung PM9A1 NVMe 1024GB                           | 2         | 0.84%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 0.84%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.84%   |
| HGST HTS721010A9E630 1TB                            | 2         | 0.84%   |
| Crucial CT250MX500SSD1 250GB                        | 2         | 0.84%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                | 1         | 0.42%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                    | 1         | 0.42%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.42%   |
| WDC WDS200T1X0E-00AFY0 2TB                          | 1         | 0.42%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.42%   |
| WDC WD80EDAZ-11TA3A0 8TB                            | 1         | 0.42%   |
| WDC WD50EZRX-00MVLB1 5TB                            | 1         | 0.42%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1         | 0.42%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 0.42%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1         | 0.42%   |
| WDC WD20EARX-008FB0 2TB                             | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 44     | 33.33%  |
| WDC                 | 12        | 32     | 26.67%  |
| Toshiba             | 9         | 19     | 20%     |
| HGST                | 4         | 14     | 8.89%   |
| Hitachi             | 2         | 4      | 4.44%   |
| Samsung Electronics | 1         | 1      | 2.22%   |
| ASMT                | 1         | 1      | 2.22%   |
| Apple               | 1         | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 56     | 31.51%  |
| Crucial             | 10        | 15     | 13.7%   |
| SanDisk             | 9         | 14     | 12.33%  |
| Kingston            | 5         | 5      | 6.85%   |
| Intel               | 5         | 7      | 6.85%   |
| WDC                 | 2         | 3      | 2.74%   |
| Transcend           | 2         | 2      | 2.74%   |
| China               | 2         | 2      | 2.74%   |
| Apple               | 2         | 4      | 2.74%   |
| Toshiba             | 1         | 1      | 1.37%   |
| Teclast             | 1         | 2      | 1.37%   |
| SPCC                | 1         | 1      | 1.37%   |
| SK hynix            | 1         | 1      | 1.37%   |
| Plextor             | 1         | 1      | 1.37%   |
| OCZ                 | 1         | 1      | 1.37%   |
| Micron Technology   | 1         | 1      | 1.37%   |
| LITEON              | 1         | 1      | 1.37%   |
| INNOVATION IT       | 1         | 1      | 1.37%   |
| Dogfish             | 1         | 1      | 1.37%   |
| Corsair             | 1         | 1      | 1.37%   |
| BIWIN               | 1         | 1      | 1.37%   |
| ASMedia             | 1         | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 77        | 111    | 44.25%  |
| SSD  | 61        | 122    | 35.06%  |
| HDD  | 31        | 116    | 17.82%  |
| MMC  | 5         | 9      | 2.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 77        | 111    | 49.68%  |
| SATA | 68        | 230    | 43.87%  |
| SAS  | 5         | 8      | 3.23%   |
| MMC  | 5         | 9      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 93     | 46.23%  |
| 0.51-1.0   | 30        | 55     | 28.3%   |
| 1.01-2.0   | 10        | 15     | 9.43%   |
| 4.01-10.0  | 7         | 47     | 6.6%    |
| 2.01-3.0   | 6         | 12     | 5.66%   |
| 3.01-4.0   | 3         | 10     | 2.83%   |
| 10.01-20.0 | 1         | 6      | 0.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 60        | 45.45%  |
| 1-20           | 24        | 18.18%  |
| 501-1000       | 11        | 8.33%   |
| 251-500        | 10        | 7.58%   |
| 101-250        | 8         | 6.06%   |
| 2001-3000      | 6         | 4.55%   |
| 1001-2000      | 6         | 4.55%   |
| More than 3000 | 5         | 3.79%   |
| 21-50          | 2         | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 60        | 44.78%  |
| 1-20           | 32        | 23.88%  |
| 101-250        | 12        | 8.96%   |
| 251-500        | 7         | 5.22%   |
| 501-1000       | 6         | 4.48%   |
| 51-100         | 6         | 4.48%   |
| 21-50          | 5         | 3.73%   |
| 1001-2000      | 3         | 2.24%   |
| 2001-3000      | 2         | 1.49%   |
| More than 3000 | 1         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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
| ASMT 2115 500GB                                | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 22.22%  |
| Toshiba | 2         | 2      | 22.22%  |
| Seagate | 2         | 4      | 22.22%  |
| Hitachi | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |
| ASMT    | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 11     | 57.14%  |
| SSD  | 4         | 6      | 28.57%  |
| NVMe | 2         | 2      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| Toshiba MG03ACA300 3TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 119       | 306    | 80.41%  |
| Detected | 16        | 32     | 10.81%  |
| Malfunc  | 12        | 19     | 8.11%   |
| Failed   | 1         | 1      | 0.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 61        | 33.33%  |
| Samsung Electronics          | 34        | 18.58%  |
| AMD                          | 30        | 16.39%  |
| SanDisk                      | 13        | 7.1%    |
| Micron Technology            | 6         | 3.28%   |
| Kingston Technology Company  | 6         | 3.28%   |
| SK hynix                     | 5         | 2.73%   |
| ASMedia Technology           | 5         | 2.73%   |
| Toshiba America Info Systems | 4         | 2.19%   |
| Phison Electronics           | 3         | 1.64%   |
| LSI Logic / Symbios Logic    | 3         | 1.64%   |
| Broadcom / LSI               | 3         | 1.64%   |
| KIOXIA                       | 2         | 1.09%   |
| Yangtze Memory Technologies  | 1         | 0.55%   |
| Silicon Motion               | 1         | 0.55%   |
| Shenzhen Longsys Electronics | 1         | 0.55%   |
| Realtek Semiconductor        | 1         | 0.55%   |
| Micron/Crucial Technology    | 1         | 0.55%   |
| Lite-On Technology           | 1         | 0.55%   |
| Biwin Storage Technology     | 1         | 0.55%   |
| ADATA Technology             | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 21        | 10.82%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 9.79%   |
| AMD 500 Series Chipset SATA Controller                                         | 10        | 5.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 4.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 3.09%   |
| Micron NVMe Storage Controller                                                 | 6         | 3.09%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 2.58%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 2.58%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 2.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 2.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.06%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.06%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.55%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.55%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.55%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.03%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.03%   |
| SanDisk NVMe Controller                                                        | 2         | 1.03%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.03%   |
| Samsung Electronics SATA controller                                            | 2         | 1.03%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2         | 1.03%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.03%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.03%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.03%   |
| Intel Comet Lake PCH-H RAID                                                    | 2         | 1.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.03%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 1.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.03%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 2         | 1.03%   |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 78        | 44.57%  |
| SATA | 77        | 44%     |
| RAID | 11        | 6.29%   |
| SAS  | 6         | 3.43%   |
| IDE  | 3         | 1.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 78        | 61.42%  |
| AMD    | 45        | 35.43%  |
| ARM    | 4         | 3.15%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 3.94%   |
| AMD Ryzen 5 3600 6-Core Processor          | 5         | 3.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 3.15%   |
| ARM Processor                              | 4         | 3.15%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 3         | 2.36%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 2.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 3         | 2.36%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 2.36%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 2.36%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 3         | 2.36%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 1.57%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 1.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 1.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 1.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 2         | 1.57%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 1.57%   |
| Intel 12th Gen Core i5-1240P               | 2         | 1.57%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 2         | 1.57%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 1.57%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 2         | 1.57%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 2         | 1.57%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 2         | 1.57%   |
| Intel Xeon W-1290P CPU @ 3.70GHz           | 1         | 0.79%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 0.79%   |
| Intel Xeon CPU L5640 @ 2.27GHz             | 1         | 0.79%   |
| Intel Xeon CPU E5606 @ 2.13GHz             | 1         | 0.79%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz        | 1         | 0.79%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz       | 1         | 0.79%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 0.79%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 0.79%   |
| Intel Core i9-9900X CPU @ 3.50GHz          | 1         | 0.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 0.79%   |
| Intel Core i7-6850K CPU @ 3.60GHz          | 1         | 0.79%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 0.79%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 1         | 0.79%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 0.79%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 0.79%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 0.79%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 30        | 23.62%  |
| Other                  | 19        | 14.96%  |
| Intel Core i5          | 16        | 12.6%   |
| AMD Ryzen 5            | 16        | 12.6%   |
| AMD Ryzen 7            | 15        | 11.81%  |
| AMD Ryzen 9            | 7         | 5.51%   |
| Intel Xeon             | 6         | 4.72%   |
| Intel Celeron          | 4         | 3.15%   |
| AMD Ryzen 7 PRO        | 4         | 3.15%   |
| Intel Core i3          | 3         | 2.36%   |
| Intel Core i9          | 2         | 1.57%   |
| AMD Ryzen Threadripper | 2         | 1.57%   |
| Intel Core m3          | 1         | 0.79%   |
| Intel Atom             | 1         | 0.79%   |
| AMD FX                 | 1         | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 41        | 32.28%  |
| 8       | 25        | 19.69%  |
| 6       | 24        | 18.9%   |
| 2       | 17        | 13.39%  |
| 12      | 8         | 6.3%    |
| Unknown | 4         | 3.15%   |
| 10      | 3         | 2.36%   |
| 16      | 2         | 1.57%   |
| 32      | 1         | 0.79%   |
| 24      | 1         | 0.79%   |
| 1       | 1         | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 121       | 95.28%  |
| Unknown | 4         | 3.15%   |
| 2       | 2         | 1.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 110       | 86.61%  |
| 1       | 13        | 10.24%  |
| Unknown | 4         | 3.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 126       | 98.44%  |
| 32-bit         | 1         | 0.78%   |
| Unknown        | 1         | 0.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 20.61%  |
| 0x306c3    | 7         | 5.34%   |
| 0x0a50000d | 7         | 5.34%   |
| 0x0a50000c | 7         | 5.34%   |
| 0x08701021 | 7         | 5.34%   |
| 0x806ea    | 6         | 4.58%   |
| 0x806c1    | 6         | 4.58%   |
| 0x906ea    | 4         | 3.05%   |
| 0x806ec    | 4         | 3.05%   |
| 0x506e3    | 4         | 3.05%   |
| 0x306a9    | 4         | 3.05%   |
| 0x08701013 | 4         | 3.05%   |
| 0x906a3    | 3         | 2.29%   |
| 0x806eb    | 3         | 2.29%   |
| 0x0a404102 | 3         | 2.29%   |
| 0x08600106 | 3         | 2.29%   |
| 0x906e9    | 2         | 1.53%   |
| 0x806e9    | 2         | 1.53%   |
| 0x706a1    | 2         | 1.53%   |
| 0x406e3    | 2         | 1.53%   |
| 0x306d4    | 2         | 1.53%   |
| 0x0a201204 | 2         | 1.53%   |
| 0x0a201009 | 2         | 1.53%   |
| 0xa0653    | 1         | 0.76%   |
| 0xa0652    | 1         | 0.76%   |
| 0x906ed    | 1         | 0.76%   |
| 0x806d1    | 1         | 0.76%   |
| 0x706a8    | 1         | 0.76%   |
| 0x406f1    | 1         | 0.76%   |
| 0x40661    | 1         | 0.76%   |
| 0x40651    | 1         | 0.76%   |
| 0x306f2    | 1         | 0.76%   |
| 0x206c2    | 1         | 0.76%   |
| 0x0a50000b | 1         | 0.76%   |
| 0x0a201016 | 1         | 0.76%   |
| 0x08600104 | 1         | 0.76%   |
| 0x08301025 | 1         | 0.76%   |
| 0x0800820d | 1         | 0.76%   |
| 0x08001138 | 1         | 0.76%   |
| 0x08001137 | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 25        | 19.69%  |
| Zen 3            | 20        | 15.75%  |
| Zen 2            | 17        | 13.39%  |
| Skylake          | 10        | 7.87%   |
| Haswell          | 10        | 7.87%   |
| Unknown          | 9         | 7.09%   |
| TigerLake        | 8         | 6.3%    |
| IvyBridge        | 5         | 3.94%   |
| Goldmont plus    | 4         | 3.15%   |
| Alderlake Hybrid | 4         | 3.15%   |
| CometLake        | 3         | 2.36%   |
| Broadwell        | 3         | 2.36%   |
| Zen+             | 2         | 1.57%   |
| Zen              | 2         | 1.57%   |
| Westmere         | 2         | 1.57%   |
| Piledriver       | 1         | 0.79%   |
| Icelake          | 1         | 0.79%   |
| Bonnell          | 1         | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 62        | 40.52%  |
| Nvidia                     | 48        | 31.37%  |
| AMD                        | 40        | 26.14%  |
| Matrox Electronics Systems | 2         | 1.31%   |
| ASPEED Technology          | 1         | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 12        | 7.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 4.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 6         | 3.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 3.18%   |
| Intel UHD Graphics 620                                                                | 5         | 3.18%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 5         | 3.18%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 2.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 2.55%   |
| Intel HD Graphics 530                                                                 | 4         | 2.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 2.55%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 4         | 2.55%   |
| AMD Renoir                                                                            | 4         | 2.55%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 3         | 1.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 1.91%   |
| Nvidia GK104 [GeForce GTX 760]                                                        | 3         | 1.91%   |
| Intel HD Graphics 620                                                                 | 3         | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 1.91%   |
| AMD Rembrandt [Radeon 680M]                                                           | 3         | 1.91%   |
| AMD Barcelo                                                                           | 3         | 1.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 1.27%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.27%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 1.27%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 1.27%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                         | 2         | 1.27%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 1.27%   |
| Intel HD Graphics 630                                                                 | 2         | 1.27%   |
| Intel HD Graphics 5500                                                                | 2         | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 1.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 1.27%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                              | 2         | 1.27%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                    | 1         | 0.64%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                 | 1         | 0.64%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                 | 1         | 0.64%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                 | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 30.71%  |
| 1 x AMD        | 26        | 20.47%  |
| 1 x Nvidia     | 20        | 15.75%  |
| Intel + Nvidia | 19        | 14.96%  |
| AMD + Nvidia   | 9         | 7.09%   |
| Other          | 5         | 3.94%   |
| 2 x AMD        | 3         | 2.36%   |
| 1 x Matrox     | 2         | 1.57%   |
| Intel + AMD    | 2         | 1.57%   |
| 2 x Intel      | 1         | 0.79%   |
| 1 x ASPEED     | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 90        | 70.31%  |
| Proprietary | 29        | 22.66%  |
| Unknown     | 9         | 7.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 63.36%  |
| 0.01-0.5   | 16        | 12.21%  |
| 7.01-8.0   | 11        | 8.4%    |
| 1.01-2.0   | 10        | 7.63%   |
| 3.01-4.0   | 8         | 6.11%   |
| 0.51-1.0   | 2         | 1.53%   |
| 8.01-16.0  | 1         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 22        | 16.67%  |
| AU Optronics         | 16        | 12.12%  |
| Samsung Electronics  | 12        | 9.09%   |
| Goldstar             | 10        | 7.58%   |
| LG Display           | 9         | 6.82%   |
| BOE                  | 9         | 6.82%   |
| Chimei Innolux       | 7         | 5.3%    |
| Acer                 | 6         | 4.55%   |
| PANDA                | 5         | 3.79%   |
| Sharp                | 4         | 3.03%   |
| CSO                  | 4         | 3.03%   |
| Hewlett-Packard      | 3         | 2.27%   |
| Panasonic            | 2         | 1.52%   |
| InfoVision           | 2         | 1.52%   |
| Apple                | 2         | 1.52%   |
| AOC                  | 2         | 1.52%   |
| Ancor Communications | 2         | 1.52%   |
| WST                  | 1         | 0.76%   |
| Vizio                | 1         | 0.76%   |
| Unknown (AAA)        | 1         | 0.76%   |
| RTK                  | 1         | 0.76%   |
| Philips              | 1         | 0.76%   |
| NEC Computers        | 1         | 0.76%   |
| MPI                  | 1         | 0.76%   |
| Lenovo               | 1         | 0.76%   |
| JDI                  | 1         | 0.76%   |
| Iiyama               | 1         | 0.76%   |
| HVR                  | 1         | 0.76%   |
| HannStar             | 1         | 0.76%   |
| Eizo                 | 1         | 0.76%   |
| BenQ                 | 1         | 0.76%   |
| ASUSTek Computer     | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO019C 1920x1200 286x178mm 13.3-inch         | 3         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 2         | 1.48%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch           | 2         | 1.48%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 2         | 1.48%   |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                       | 2         | 1.48%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                      | 2         | 1.48%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                    | 2         | 1.48%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                      | 2         | 1.48%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch         | 2         | 1.48%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                   | 2         | 1.48%   |
| WST KL.1350W.003 WST2C34 2256x1504 285x190mm 13.5-inch                 | 1         | 0.74%   |
| Vizio D43-D2 VIZ1004 1920x1080 477x268mm 21.5-inch                     | 1         | 0.74%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch            | 1         | 0.74%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 1         | 0.74%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 1         | 0.74%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.74%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                | 1         | 0.74%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch   | 1         | 0.74%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch      | 1         | 0.74%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch      | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4160 3000x2000 285x190mm 13.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch  | 1         | 0.74%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch      | 1         | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1         | 0.74%   |
| RTK FHD HDR RTKBC32 1920x1080 332x186mm 15.0-inch                      | 1         | 0.74%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1         | 0.74%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                | 1         | 0.74%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch                | 1         | 0.74%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch                | 1         | 0.74%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                | 1         | 0.74%   |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                | 1         | 0.74%   |
| NEC Computers 90GX2 NEC6692 1280x1024 376x301mm 19.0-inch              | 1         | 0.74%   |
| MPI MPI7002 MPI7002 1280x1024 255x255mm 14.2-inch                      | 1         | 0.74%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 45        | 35.71%  |
| 3840x2160 (4K)     | 22        | 17.46%  |
| 2560x1440 (QHD)    | 15        | 11.9%   |
| 1366x768 (WXGA)    | 8         | 6.35%   |
| 1920x1200 (WUXGA)  | 7         | 5.56%   |
| 1280x1024 (SXGA)   | 5         | 3.97%   |
| 2560x1600          | 4         | 3.17%   |
| 2560x1080          | 4         | 3.17%   |
| 2880x1800          | 3         | 2.38%   |
| 2256x1504          | 3         | 2.38%   |
| 3440x1440          | 2         | 1.59%   |
| 1680x1050 (WSXGA+) | 2         | 1.59%   |
| 3840x2400          | 1         | 0.79%   |
| 3000x2000          | 1         | 0.79%   |
| 2160x1200          | 1         | 0.79%   |
| 1440x900 (WXGA+)   | 1         | 0.79%   |
| 1280x720 (HD)      | 1         | 0.79%   |
| 1024x600           | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 16.15%  |
| 13      | 19        | 14.62%  |
| 27      | 16        | 12.31%  |
| 14      | 16        | 12.31%  |
| 24      | 11        | 8.46%   |
| 23      | 8         | 6.15%   |
| 17      | 7         | 5.38%   |
| 34      | 6         | 4.62%   |
| 31      | 5         | 3.85%   |
| 12      | 5         | 3.85%   |
| 25      | 2         | 1.54%   |
| 22      | 2         | 1.54%   |
| 21      | 2         | 1.54%   |
| 19      | 2         | 1.54%   |
| 16      | 2         | 1.54%   |
| 84      | 1         | 0.77%   |
| 49      | 1         | 0.77%   |
| 46      | 1         | 0.77%   |
| 11      | 1         | 0.77%   |
| 10      | 1         | 0.77%   |
| Unknown | 1         | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 34.92%  |
| 501-600     | 33        | 26.19%  |
| 201-300     | 23        | 18.25%  |
| 701-800     | 6         | 4.76%   |
| 601-700     | 6         | 4.76%   |
| 351-400     | 6         | 4.76%   |
| 401-500     | 4         | 3.17%   |
| 1001-1500   | 2         | 1.59%   |
| 1501-2000   | 1         | 0.79%   |
| Unknown     | 1         | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 76        | 67.86%  |
| 16/10 | 20        | 17.86%  |
| 21/9  | 6         | 5.36%   |
| 5/4   | 5         | 4.46%   |
| 3/2   | 4         | 3.57%   |
| 1.00  | 1         | 0.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 23        | 17.56%  |
| 101-110        | 22        | 16.79%  |
| 201-250        | 18        | 13.74%  |
| 301-350        | 16        | 12.21%  |
| 71-80          | 11        | 8.4%    |
| 351-500        | 11        | 8.4%    |
| 251-300        | 6         | 4.58%   |
| 61-70          | 5         | 3.82%   |
| 151-200        | 4         | 3.05%   |
| 141-150        | 3         | 2.29%   |
| 121-130        | 3         | 2.29%   |
| More than 1000 | 2         | 1.53%   |
| 111-120        | 2         | 1.53%   |
| 51-60          | 1         | 0.76%   |
| 41-50          | 1         | 0.76%   |
| 131-140        | 1         | 0.76%   |
| 501-1000       | 1         | 0.76%   |
| Unknown        | 1         | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 34        | 28.1%   |
| 161-240       | 29        | 23.97%  |
| 121-160       | 27        | 22.31%  |
| 101-120       | 15        | 12.4%   |
| More than 240 | 13        | 10.74%  |
| 1-50          | 2         | 1.65%   |
| Unknown       | 1         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 79        | 59.4%   |
| 2     | 26        | 19.55%  |
| 0     | 23        | 17.29%  |
| 3     | 5         | 3.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 83        | 45.6%   |
| Realtek Semiconductor             | 66        | 36.26%  |
| Qualcomm Atheros                  | 6         | 3.3%    |
| MediaTek                          | 4         | 2.2%    |
| Broadcom                          | 3         | 1.65%   |
| Qualcomm                          | 2         | 1.1%    |
| Microsoft                         | 2         | 1.1%    |
| Lenovo                            | 2         | 1.1%    |
| Aquantia                          | 2         | 1.1%    |
| Xiaomi                            | 1         | 0.55%   |
| TP-Link                           | 1         | 0.55%   |
| Texas Instruments                 | 1         | 0.55%   |
| Standard Microsystems             | 1         | 0.55%   |
| Ralink Technology                 | 1         | 0.55%   |
| Ralink                            | 1         | 0.55%   |
| Pulse-Eight                       | 1         | 0.55%   |
| Oculus VR                         | 1         | 0.55%   |
| ICS Advent                        | 1         | 0.55%   |
| Google                            | 1         | 0.55%   |
| Fibocom                           | 1         | 0.55%   |
| Ericsson Business Mobile Networks | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 19.43%  |
| Intel Wi-Fi 6 AX200                                               | 16        | 7.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 6.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 3.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 2.37%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.37%   |
| Intel Wireless 7265                                               | 4         | 1.9%    |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 1.9%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 3         | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.42%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 1.42%   |
| Intel Wireless-AC 9260                                            | 3         | 1.42%   |
| Intel Wireless 8260                                               | 3         | 1.42%   |
| Intel Wireless 7260                                               | 3         | 1.42%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.42%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.42%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.42%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 0.95%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.95%   |
| Intel Wireless 3165                                               | 2         | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.95%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.95%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.95%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.95%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.95%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.47%   |
| Texas Instruments CC2538 USB CDC                                  | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 71.43%  |
| Realtek Semiconductor | 7         | 7.69%   |
| Qualcomm Atheros      | 5         | 5.49%   |
| MediaTek              | 4         | 4.4%    |
| Qualcomm              | 2         | 2.2%    |
| Microsoft             | 2         | 2.2%    |
| Broadcom              | 2         | 2.2%    |
| TP-Link               | 1         | 1.1%    |
| Ralink Technology     | 1         | 1.1%    |
| Ralink                | 1         | 1.1%    |
| Fibocom               | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 16        | 17.58%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 5.49%   |
| Intel Wireless 7265                                            | 4         | 4.4%    |
| Intel Wi-Fi 6 AX201                                            | 4         | 4.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 4.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 4.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 3.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 3.3%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 3.3%    |
| Intel Wireless-AC 9260                                         | 3         | 3.3%    |
| Intel Wireless 8260                                            | 3         | 3.3%    |
| Intel Wireless 7260                                            | 3         | 3.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 3.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 3.3%    |
| Microsoft Xbox 360 Wireless Adapter                            | 2         | 2.2%    |
| Intel Wireless 8265 / 8275                                     | 2         | 2.2%    |
| Intel Wireless 3165                                            | 2         | 2.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 2.2%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.2%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 2.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.1%    |
| Realtek 802.11ac NIC                                           | 1         | 1.1%    |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.1%    |
| Ralink RT2800 802.11n PCI                                      | 1         | 1.1%    |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.1%    |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.1%    |
| Intel Wireless 3160                                            | 1         | 1.1%    |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 60        | 54.55%  |
| Intel                 | 38        | 34.55%  |
| Qualcomm Atheros      | 2         | 1.82%   |
| Lenovo                | 2         | 1.82%   |
| Broadcom              | 2         | 1.82%   |
| Aquantia              | 2         | 1.82%   |
| Xiaomi                | 1         | 0.91%   |
| Standard Microsystems | 1         | 0.91%   |
| ICS Advent            | 1         | 0.91%   |
| Google                | 1         | 0.91%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 35.34%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 12.07%  |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 6.9%    |
| Intel I211 Gigabit Network Connection                             | 5         | 4.31%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.45%   |
| Intel Ethernet Controller I225-V                                  | 3         | 2.59%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.59%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.59%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.72%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.72%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.72%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.72%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.86%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.86%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.86%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.86%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.86%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.86%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.86%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.86%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.86%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 0.86%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.86%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.86%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.86%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 98        | 51.31%  |
| WiFi     | 89        | 46.6%   |
| Modem    | 4         | 2.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 56.06%  |
| Ethernet | 58        | 43.94%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 65        | 50.78%  |
| 2     | 54        | 42.19%  |
| 0     | 5         | 3.91%   |
| 3     | 3         | 2.34%   |
| 4     | 1         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 98        | 74.81%  |
| Yes  | 33        | 25.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 67.05%  |
| Realtek Semiconductor           | 8         | 9.09%   |
| ASUSTek Computer                | 4         | 4.55%   |
| Qualcomm Atheros Communications | 3         | 3.41%   |
| MediaTek                        | 3         | 3.41%   |
| Broadcom                        | 3         | 3.41%   |
| Cambridge Silicon Radio         | 2         | 2.27%   |
| Apple                           | 2         | 2.27%   |
| USI                             | 1         | 1.14%   |
| Lite-On Technology              | 1         | 1.14%   |
| HTC (High Tech Computer)        | 1         | 1.14%   |
| Foxconn / Hon Hai               | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 14        | 15.91%  |
| Intel Bluetooth wireless interface                                   | 13        | 14.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 9         | 10.23%  |
| Realtek Bluetooth Radio                                              | 8         | 9.09%   |
| Intel AX201 Bluetooth                                                | 8         | 9.09%   |
| Intel AX210 Bluetooth                                                | 5         | 5.68%   |
| Intel Bluetooth Device                                               | 4         | 4.55%   |
| MediaTek Wireless_Device                                             | 3         | 3.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 3.41%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 3.41%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2         | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 2.27%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 2.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 2.27%   |
| USI Bluetooth Device                                                 | 1         | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 1.14%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.14%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1         | 1.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 1.14%   |
| ASUS Broadcom Bluetooth 2.1                                          | 1         | 1.14%   |
| ASUS ASUS USB-BT500                                                  | 1         | 1.14%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 1.14%   |
| Apple Bluetooth Host Controller                                      | 1         | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 75        | 37.88%  |
| AMD                                  | 49        | 24.75%  |
| Nvidia                               | 32        | 16.16%  |
| C-Media Electronics                  | 6         | 3.03%   |
| Creative Technology                  | 4         | 2.02%   |
| Texas Instruments                    | 3         | 1.52%   |
| Sennheiser Communications            | 3         | 1.52%   |
| Lenovo                               | 3         | 1.52%   |
| Synaptics                            | 2         | 1.01%   |
| Realtek Semiconductor                | 2         | 1.01%   |
| Razer USA                            | 2         | 1.01%   |
| Kingston Technology                  | 2         | 1.01%   |
| Trust                                | 1         | 0.51%   |
| Thomann                              | 1         | 0.51%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.51%   |
| Sony                                 | 1         | 0.51%   |
| Schiit Audio                         | 1         | 0.51%   |
| Satechi                              | 1         | 0.51%   |
| PreSonus Audio Electronics           | 1         | 0.51%   |
| GYROCOM C&C                          | 1         | 0.51%   |
| Focusrite-Novation                   | 1         | 0.51%   |
| Edifier Technology                   | 1         | 0.51%   |
| Creative Labs                        | 1         | 0.51%   |
| Corsair                              | 1         | 0.51%   |
| ASRock                               | 1         | 0.51%   |
| Antlion Audio                        | 1         | 0.51%   |
| (LCS) USB Audio Device               | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 21        | 8.86%   |
| AMD Starship/Matisse HD Audio Controller                            | 17        | 7.17%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 17        | 7.17%   |
| Intel Sunrise Point-LP HD Audio                                     | 13        | 5.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 8         | 3.38%   |
| Intel Cannon Lake PCH cAVS                                          | 6         | 2.53%   |
| AMD Navi 10 HDMI Audio                                              | 6         | 2.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 6         | 2.53%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 5         | 2.11%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 5         | 2.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 5         | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 5         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 5         | 2.11%   |
| Nvidia TU106 High Definition Audio Controller                       | 4         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                     | 4         | 1.69%   |
| Nvidia GK104 HDMI Audio Controller                                  | 4         | 1.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 4         | 1.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 4         | 1.69%   |
| Nvidia GA106 High Definition Audio Controller                       | 3         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 1.27%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 1.27%   |
| Creative Technology SoundBlaster Live! 24-bit External SB0490       | 3         | 1.27%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 3         | 1.27%   |
| Texas Instruments PCM2902 Audio Codec                               | 2         | 0.84%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                 | 2         | 0.84%   |
| Sennheiser Communications Headset [PC 8]                            | 2         | 0.84%   |
| Realtek Semiconductor USB Audio                                     | 2         | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 0.84%   |
| Nvidia GP106 High Definition Audio Controller                       | 2         | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                       | 2         | 0.84%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 0.84%   |
| Kingston Technology HyperX 7.1 Audio                                | 2         | 0.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 0.84%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2         | 0.84%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 0.84%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2         | 0.84%   |
| Intel 200 Series PCH HD Audio                                       | 2         | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 24.82%  |
| Kingston            | 20        | 14.18%  |
| SK hynix            | 17        | 12.06%  |
| Corsair             | 15        | 10.64%  |
| Micron Technology   | 14        | 9.93%   |
| Crucial             | 11        | 7.8%    |
| G.Skill             | 10        | 7.09%   |
| Unknown (ABCD)      | 4         | 2.84%   |
| Unknown             | 4         | 2.84%   |
| Team                | 3         | 2.13%   |
| Goodram             | 2         | 1.42%   |
| AMD                 | 2         | 1.42%   |
| A-DATA Technology   | 2         | 1.42%   |
| Strontium           | 1         | 0.71%   |
| Avant               | 1         | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.95%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.95%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 3         | 1.95%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 2         | 1.3%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.3%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.3%    |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.3%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 1.3%    |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 1.3%    |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 1.3%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 2         | 1.3%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 2         | 1.3%    |
| Corsair RAM CMK16GX4M1D3000C16 16384MB DIMM DDR4 3000MT/s        | 2         | 1.3%    |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.65%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.65%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                    | 1         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 1         | 0.65%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2933MT/s            | 1         | 0.65%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s               | 1         | 0.65%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                     | 1         | 0.65%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.65%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.65%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.65%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.65%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 1         | 0.65%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.65%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.65%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.65%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.65%   |
| SK hynix RAM H5ANAG6NCJR-XN 8GB SODIMM DDR4 3200MT/s             | 1         | 0.65%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.65%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.65%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.65%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 76        | 62.81%  |
| DDR3   | 21        | 17.36%  |
| LPDDR4 | 12        | 9.92%   |
| LPDDR3 | 5         | 4.13%   |
| LPDDR5 | 4         | 3.31%   |
| DDR5   | 2         | 1.65%   |
| SDRAM  | 1         | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 57        | 45.97%  |
| DIMM         | 44        | 35.48%  |
| Row Of Chips | 19        | 15.32%  |
| Chip         | 2         | 1.61%   |
| RIMM         | 1         | 0.81%   |
| Unknown      | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 54        | 40.6%   |
| 16384 | 44        | 33.08%  |
| 4096  | 17        | 12.78%  |
| 32768 | 13        | 9.77%   |
| 2048  | 4         | 3.01%   |
| 1024  | 1         | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 34        | 25.56%  |
| 2667    | 15        | 11.28%  |
| 1600    | 15        | 11.28%  |
| 2400    | 11        | 8.27%   |
| 2133    | 10        | 7.52%   |
| 4267    | 6         | 4.51%   |
| 3600    | 6         | 4.51%   |
| 6400    | 4         | 3.01%   |
| 3000    | 4         | 3.01%   |
| 1867    | 4         | 3.01%   |
| 3733    | 3         | 2.26%   |
| 1333    | 3         | 2.26%   |
| 4800    | 2         | 1.5%    |
| 4266    | 2         | 1.5%    |
| 3400    | 2         | 1.5%    |
| 3334    | 2         | 1.5%    |
| 2933    | 2         | 1.5%    |
| 3866    | 1         | 0.75%   |
| 3666    | 1         | 0.75%   |
| 3534    | 1         | 0.75%   |
| 3266    | 1         | 0.75%   |
| 2134    | 1         | 0.75%   |
| 2132    | 1         | 0.75%   |
| 1066    | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

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
| Chicony Electronics           | 14        | 18.18%  |
| Microdia                      | 11        | 14.29%  |
| IMC Networks                  | 10        | 12.99%  |
| Logitech                      | 9         | 11.69%  |
| Acer                          | 9         | 11.69%  |
| Realtek Semiconductor         | 6         | 7.79%   |
| Sunplus Innovation Technology | 4         | 5.19%   |
| Quanta                        | 3         | 3.9%    |
| MacroSilicon                  | 2         | 2.6%    |
| Bison Electronics             | 2         | 2.6%    |
| Apple                         | 2         | 2.6%    |
| webcam                        | 1         | 1.3%    |
| Syntek                        | 1         | 1.3%    |
| SunplusIT                     | 1         | 1.3%    |
| Lite-On Technology            | 1         | 1.3%    |
| Alcor Micro                   | 1         | 1.3%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 9         | 11.39%  |
| Microdia Integrated_Webcam_HD        | 6         | 7.59%   |
| Acer Integrated Camera               | 6         | 7.59%   |
| IMC Networks USB2.0 HD UVC WebCam    | 5         | 6.33%   |
| IMC Networks Integrated Camera       | 3         | 3.8%    |
| Chicony HP HD Camera                 | 3         | 3.8%    |
| Sunplus Integrated_Webcam_FHD        | 2         | 2.53%   |
| Realtek Laptop Camera                | 2         | 2.53%   |
| Realtek Integrated_Webcam_HD         | 2         | 2.53%   |
| Quanta VGA WebCam                    | 2         | 2.53%   |
| MacroSilicon USB Video               | 2         | 2.53%   |
| Logitech Webcam C270                 | 2         | 2.53%   |
| Logitech HD Pro Webcam C920          | 2         | 2.53%   |
| Acer Integrated IR Camera            | 2         | 2.53%   |
| webcam webcam                        | 1         | 1.27%   |
| Syntek Integrated Camera             | 1         | 1.27%   |
| SunplusIT HP TrueVision HD Camera    | 1         | 1.27%   |
| Sunplus Integrated_Webcam_HD         | 1         | 1.27%   |
| Sunplus HD WebCam                    | 1         | 1.27%   |
| Realtek Integrated Webcam            | 1         | 1.27%   |
| Realtek EasyCamera                   | 1         | 1.27%   |
| Quanta HP True Vision HD Camera      | 1         | 1.27%   |
| Microdia Webcam Vitade AF            | 1         | 1.27%   |
| Microdia USB 2.0 Camera              | 1         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_HD | 1         | 1.27%   |
| Microdia Integrated Webcam           | 1         | 1.27%   |
| Microdia Camera                      | 1         | 1.27%   |
| Logitech Webcam C930e                | 1         | 1.27%   |
| Logitech Webcam C310                 | 1         | 1.27%   |
| Logitech Webcam C120                 | 1         | 1.27%   |
| Logitech StreamCam                   | 1         | 1.27%   |
| Logitech C930c                       | 1         | 1.27%   |
| Lite-On HP HD Camera                 | 1         | 1.27%   |
| IMC Networks XHC Camera              | 1         | 1.27%   |
| IMC Networks USB2.0 UVC 1.3M WebCam  | 1         | 1.27%   |
| Chicony USB2.0 Camera                | 1         | 1.27%   |
| Chicony Integrated Camera [ThinkPad] | 1         | 1.27%   |
| Bison Integrated RGB Camera          | 1         | 1.27%   |
| Bison Integrated Camera              | 1         | 1.27%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X      | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 47.62%  |
| Validity Sensors           | 6         | 28.57%  |
| Shenzhen Goodix Technology | 4         | 19.05%  |
| Gingytech                  | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 4         | 19.05%  |
| Shenzhen Goodix Fingerprint Reader                       | 3         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 2         | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 9.52%   |
| Synaptics UWP WBDI Device                                | 2         | 9.52%   |
| Synaptics UWP WBDI                                       | 2         | 9.52%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 4.76%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 4.76%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Shenzhen Goodix  Fingerprint Device                      | 1         | 4.76%   |
| Gingytech Fingerprint sensor                             | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 9         | 69.23%  |
| Yubico.com  | 2         | 15.38%  |
| Upek        | 1         | 7.69%   |
| Broadcom    | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 73        | 55.73%  |
| 1     | 37        | 28.24%  |
| 2     | 18        | 13.74%  |
| 4     | 2         | 1.53%   |
| 3     | 1         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 23.17%  |
| Graphics card            | 16        | 19.51%  |
| Multimedia controller    | 15        | 18.29%  |
| Chipcard                 | 10        | 12.2%   |
| Net/wireless             | 6         | 7.32%   |
| Unassigned class         | 3         | 3.66%   |
| Camera                   | 3         | 3.66%   |
| Bluetooth                | 3         | 3.66%   |
| Modem                    | 2         | 2.44%   |
| Storage/ata              | 1         | 1.22%   |
| Network                  | 1         | 1.22%   |
| Dvb card                 | 1         | 1.22%   |
| Communication controller | 1         | 1.22%   |
| Card reader              | 1         | 1.22%   |

