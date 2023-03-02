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

Total: 179

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| NixOS 22.05                      | 37        | 27.01%  |
| NixOS 22.11                      | 35        | 25.55%  |
| NixOS 21.11                      | 18        | 13.14%  |
| NixOS 23.05                      | 12        | 8.76%   |
| NixOS                            | 5         | 3.65%   |
| NixOS 21.05pre-git               | 2         | 1.46%   |
| NixOS 20.09pre-git               | 2         | 1.46%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.73%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.73%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.73%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.73%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.73%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.73%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.73%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.73%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.73%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.73%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.73%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.73%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.73%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.73%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.73%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.73%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.73%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.73%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.73%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.73%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.73%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.73%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.73%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.73%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.73%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 121       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 5.15.74          | 5         | 3.47%   |
| 5.15.43          | 4         | 2.78%   |
| 6.2.0-rc6        | 3         | 2.08%   |
| 6.1.0            | 3         | 2.08%   |
| 6.0.11           | 3         | 2.08%   |
| 6.0.10           | 3         | 2.08%   |
| 5.15.86          | 3         | 2.08%   |
| 5.15.82          | 3         | 2.08%   |
| 5.15.72          | 3         | 2.08%   |
| 5.15.68          | 3         | 2.08%   |
| 5.15.47          | 3         | 2.08%   |
| 5.15.26          | 3         | 2.08%   |
| 6.1.1            | 2         | 1.39%   |
| 5.8.1-zen1       | 2         | 1.39%   |
| 5.19.14          | 2         | 1.39%   |
| 5.18.19          | 2         | 1.39%   |
| 5.17.1           | 2         | 1.39%   |
| 5.16.8-zen1      | 2         | 1.39%   |
| 5.16.15          | 2         | 1.39%   |
| 5.15.85          | 2         | 1.39%   |
| 5.15.64          | 2         | 1.39%   |
| 5.15.32          | 2         | 1.39%   |
| 5.15.25          | 2         | 1.39%   |
| 5.13.7           | 2         | 1.39%   |
| 5.13.2           | 2         | 1.39%   |
| 5.12.15          | 2         | 1.39%   |
| 5.10.102         | 2         | 1.39%   |
| 6.1.9            | 1         | 0.69%   |
| 6.1.10           | 1         | 0.69%   |
| 6.1.0-zen1       | 1         | 0.69%   |
| 6.0.8-zen1       | 1         | 0.69%   |
| 6.0.6            | 1         | 0.69%   |
| 6.0.2-xanmod1-tt | 1         | 0.69%   |
| 6.0.2            | 1         | 0.69%   |
| 6.0.12           | 1         | 0.69%   |
| 6.0.10-zen2      | 1         | 0.69%   |
| 6.0.0-xanmod1    | 1         | 0.69%   |
| 5.8.4            | 1         | 0.69%   |
| 5.8.16-hardened  | 1         | 0.69%   |
| 5.8.11           | 1         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.74  | 5         | 3.47%   |
| 6.1.0    | 4         | 2.78%   |
| 6.0.10   | 4         | 2.78%   |
| 5.15.43  | 4         | 2.78%   |
| 6.2.0    | 3         | 2.08%   |
| 6.0.11   | 3         | 2.08%   |
| 5.15.86  | 3         | 2.08%   |
| 5.15.82  | 3         | 2.08%   |
| 5.15.72  | 3         | 2.08%   |
| 5.15.68  | 3         | 2.08%   |
| 5.15.47  | 3         | 2.08%   |
| 5.15.26  | 3         | 2.08%   |
| 6.1.1    | 2         | 1.39%   |
| 6.0.2    | 2         | 1.39%   |
| 5.8.1    | 2         | 1.39%   |
| 5.19.14  | 2         | 1.39%   |
| 5.18.19  | 2         | 1.39%   |
| 5.17.1   | 2         | 1.39%   |
| 5.16.8   | 2         | 1.39%   |
| 5.16.15  | 2         | 1.39%   |
| 5.15.85  | 2         | 1.39%   |
| 5.15.64  | 2         | 1.39%   |
| 5.15.32  | 2         | 1.39%   |
| 5.15.25  | 2         | 1.39%   |
| 5.13.7   | 2         | 1.39%   |
| 5.13.2   | 2         | 1.39%   |
| 5.12.15  | 2         | 1.39%   |
| 5.11.16  | 2         | 1.39%   |
| 5.10.102 | 2         | 1.39%   |
| 6.1.9    | 1         | 0.69%   |
| 6.1.10   | 1         | 0.69%   |
| 6.0.8    | 1         | 0.69%   |
| 6.0.6    | 1         | 0.69%   |
| 6.0.12   | 1         | 0.69%   |
| 6.0.0    | 1         | 0.69%   |
| 5.8.4    | 1         | 0.69%   |
| 5.8.16   | 1         | 0.69%   |
| 5.8.11   | 1         | 0.69%   |
| 5.8.10   | 1         | 0.69%   |
| 5.7.4    | 1         | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 49        | 35.25%  |
| 5.10    | 14        | 10.07%  |
| 6.0     | 13        | 9.35%   |
| 6.1     | 8         | 5.76%   |
| 5.16    | 8         | 5.76%   |
| 5.4     | 7         | 5.04%   |
| 5.19    | 7         | 5.04%   |
| 5.8     | 6         | 4.32%   |
| 5.18    | 5         | 3.6%    |
| 5.13    | 4         | 2.88%   |
| 6.2     | 3         | 2.16%   |
| 5.7     | 3         | 2.16%   |
| 5.17    | 3         | 2.16%   |
| 5.12    | 3         | 2.16%   |
| 5.14    | 2         | 1.44%   |
| 5.11    | 2         | 1.44%   |
| 4.19    | 2         | 1.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 117       | 96.69%  |
| aarch64 | 4         | 3.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 83        | 65.35%  |
| sway         | 11        | 8.66%   |
| GNOME        | 8         | 6.3%    |
| XFCE         | 6         | 4.72%   |
| KDE5         | 6         | 4.72%   |
| none+i3      | 4         | 3.15%   |
| KDE          | 4         | 3.15%   |
| none+xmonad  | 2         | 1.57%   |
| X-Generic    | 1         | 0.79%   |
| none+bspwm   | 1         | 0.79%   |
| none+awesome | 1         | 0.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 75        | 58.59%  |
| X11     | 24        | 18.75%  |
| Wayland | 17        | 13.28%  |
| Tty     | 12        | 9.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 88        | 72.13%  |
| LightDM | 15        | 12.3%   |
| SDDM    | 11        | 9.02%   |
| GDM     | 8         | 6.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 54        | 44.26%  |
| en_US   | 48        | 39.34%  |
| en_GB   | 3         | 2.46%   |
| ru_RU   | 2         | 1.64%   |
| fr_FR   | 2         | 1.64%   |
| en_DK   | 2         | 1.64%   |
| en_AU   | 2         | 1.64%   |
| de_DE   | 2         | 1.64%   |
| de_CH   | 2         | 1.64%   |
| ro_RO   | 1         | 0.82%   |
| pt_BR   | 1         | 0.82%   |
| lv_LV   | 1         | 0.82%   |
| it_IT   | 1         | 0.82%   |
| en_CA   | 1         | 0.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 104       | 84.55%  |
| BIOS | 19        | 15.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 61        | 49.19%  |
| Btrfs   | 20        | 16.13%  |
| Zfs     | 13        | 10.48%  |
| Xfs     | 13        | 10.48%  |
| Tmpfs   | 10        | 8.06%   |
| Unknown | 6         | 4.84%   |
| Ext2    | 1         | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 115       | 92.74%  |
| Unknown | 8         | 6.45%   |
| MBR     | 1         | 0.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 73.6%   |
| Yes       | 33        | 26.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 66.94%  |
| Yes       | 40        | 33.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 27        | 22.31%  |
| ASUSTek Computer                     | 24        | 19.83%  |
| Dell                                 | 16        | 13.22%  |
| MSI                                  | 10        | 8.26%   |
| Hewlett-Packard                      | 7         | 5.79%   |
| Gigabyte Technology                  | 6         | 4.96%   |
| ASRock                               | 6         | 4.96%   |
| Acer                                 | 4         | 3.31%   |
| Supermicro                           | 2         | 1.65%   |
| Raspberry Pi Foundation              | 2         | 1.65%   |
| Pine Microsystems                    | 2         | 1.65%   |
| GPD                                  | 2         | 1.65%   |
| Framework                            | 2         | 1.65%   |
| Apple                                | 2         | 1.65%   |
| Toshiba                              | 1         | 0.83%   |
| Teclast                              | 1         | 0.83%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.83%   |
| OBSIDIAN-PC                          | 1         | 0.83%   |
| MECHREVO                             | 1         | 0.83%   |
| Intel                                | 1         | 0.83%   |
| Hardkernel                           | 1         | 0.83%   |
| EVGA                                 | 1         | 0.83%   |
| Blackview                            | 1         | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo 13w Yoga 82S1                       | 3         | 2.48%   |
| Pine Microsystems Pine64 PinePhone (1.2)   | 2         | 1.65%   |
| MSI MS-7C37                                | 2         | 1.65%   |
| Dell Latitude 7420                         | 2         | 1.65%   |
| ASUS Zenbook UX3402ZA_UX3402ZA             | 2         | 1.65%   |
| ASUS All Series                            | 2         | 1.65%   |
| Toshiba Satellite L50-B                    | 1         | 0.83%   |
| Teclast F5                                 | 1         | 0.83%   |
| Supermicro X8DT6                           | 1         | 0.83%   |
| Supermicro X10SLL-F                        | 1         | 0.83%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.83%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 1         | 0.83%   |
| RPi Raspberry Pi 3 Model B+                | 1         | 0.83%   |
| OBSIDIAN-PC N13_N140ZU                     | 1         | 0.83%   |
| MSI MS-7C95                                | 1         | 0.83%   |
| MSI MS-7C84                                | 1         | 0.83%   |
| MSI MS-7C56                                | 1         | 0.83%   |
| MSI MS-7C35                                | 1         | 0.83%   |
| MSI MS-7B89                                | 1         | 0.83%   |
| MSI MS-7B09                                | 1         | 0.83%   |
| MSI MS-7758                                | 1         | 0.83%   |
| MSI Bravo 15 B5DD                          | 1         | 0.83%   |
| MECHREVO Code01 Ver2.0                     | 1         | 0.83%   |
| Lenovo Yoga Slim 7 13ACN5 82CY             | 1         | 0.83%   |
| Lenovo Yoga 520-14IKB 81C8                 | 1         | 0.83%   |
| Lenovo ThinkPad X390 20Q0CTO1WW            | 1         | 0.83%   |
| Lenovo ThinkPad X260 20F5S6MF02            | 1         | 0.83%   |
| Lenovo ThinkPad X260 20F5S4BY00            | 1         | 0.83%   |
| Lenovo ThinkPad X250 20CLS18S0T            | 1         | 0.83%   |
| Lenovo ThinkPad X230 2333AZ2               | 1         | 0.83%   |
| Lenovo ThinkPad X230 23243E9               | 1         | 0.83%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW      | 1         | 0.83%   |
| Lenovo ThinkPad T580 20L90024PB            | 1         | 0.83%   |
| Lenovo ThinkPad T540p 20BE005YMH           | 1         | 0.83%   |
| Lenovo ThinkPad T490 20N2000LUK            | 1         | 0.83%   |
| Lenovo ThinkPad T480 20L5CTO1WW            | 1         | 0.83%   |
| Lenovo ThinkPad T460p 20FWCTO1WW           | 1         | 0.83%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW       | 1         | 0.83%   |
| Lenovo ThinkPad T14s Gen 3 21BR000MUS      | 1         | 0.83%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK      | 1         | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 18        | 14.88%  |
| ASUS ROG                                   | 6         | 4.96%   |
| Dell XPS                                   | 5         | 4.13%   |
| ASUS PRIME                                 | 5         | 4.13%   |
| Dell Inspiron                              | 4         | 3.31%   |
| Lenovo 13w                                 | 3         | 2.48%   |
| Dell Precision                             | 3         | 2.48%   |
| Dell Latitude                              | 3         | 2.48%   |
| ASUS Zenbook                               | 3         | 2.48%   |
| RPi Raspberry                              | 2         | 1.65%   |
| Pine Microsystems Pine64                   | 2         | 1.65%   |
| MSI MS-7C37                                | 2         | 1.65%   |
| Lenovo Yoga                                | 2         | 1.65%   |
| Lenovo Legion                              | 2         | 1.65%   |
| HP ProBook                                 | 2         | 1.65%   |
| Framework Laptop                           | 2         | 1.65%   |
| ASUS All                                   | 2         | 1.65%   |
| Acer Aspire                                | 2         | 1.65%   |
| Toshiba Satellite                          | 1         | 0.83%   |
| Teclast F5                                 | 1         | 0.83%   |
| Supermicro X8DT6                           | 1         | 0.83%   |
| Supermicro X10SLL-F                        | 1         | 0.83%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.83%   |
| OBSIDIAN-PC N13                            | 1         | 0.83%   |
| MSI MS-7C95                                | 1         | 0.83%   |
| MSI MS-7C84                                | 1         | 0.83%   |
| MSI MS-7C56                                | 1         | 0.83%   |
| MSI MS-7C35                                | 1         | 0.83%   |
| MSI MS-7B89                                | 1         | 0.83%   |
| MSI MS-7B09                                | 1         | 0.83%   |
| MSI MS-7758                                | 1         | 0.83%   |
| MSI Bravo                                  | 1         | 0.83%   |
| MECHREVO Code01                            | 1         | 0.83%   |
| Lenovo IdeaPadFlex                         | 1         | 0.83%   |
| Lenovo IdeaPad                             | 1         | 0.83%   |
| Intel NUC11PAHi7                           | 1         | 0.83%   |
| HP ZBook                                   | 1         | 0.83%   |
| HP Spectre                                 | 1         | 0.83%   |
| HP ENVY                                    | 1         | 0.83%   |
| HP EliteDesk                               | 1         | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 24        | 19.83%  |
| 2019    | 20        | 16.53%  |
| 2021    | 14        | 11.57%  |
| 2018    | 13        | 10.74%  |
| 2022    | 10        | 8.26%   |
| 2016    | 10        | 8.26%   |
| 2017    | 6         | 4.96%   |
| 2015    | 5         | 4.13%   |
| 2013    | 5         | 4.13%   |
| 2012    | 5         | 4.13%   |
| 2014    | 4         | 3.31%   |
| Unknown | 4         | 3.31%   |
| 2010    | 1         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 56        | 46.28%  |
| Desktop        | 43        | 35.54%  |
| Convertible    | 12        | 9.92%   |
| Server         | 3         | 2.48%   |
| Phone          | 2         | 1.65%   |
| System on chip | 2         | 1.65%   |
| Tablet         | 1         | 0.83%   |
| Mini pc        | 1         | 0.83%   |
| All in one     | 1         | 0.83%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 121       | 99.18%  |
| Enabled  | 1         | 0.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 120       | 99.17%  |
| Yes  | 1         | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 34        | 27.64%  |
| 16.01-24.0  | 27        | 21.95%  |
| 8.01-16.0   | 21        | 17.07%  |
| 64.01-256.0 | 15        | 12.2%   |
| 4.01-8.0    | 13        | 10.57%  |
| 24.01-32.0  | 6         | 4.88%   |
| 3.01-4.0    | 5         | 4.07%   |
| 1.01-2.0    | 1         | 0.81%   |
| 0.51-1.0    | 1         | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 37        | 27.82%  |
| 8.01-16.0   | 24        | 18.05%  |
| 3.01-4.0    | 17        | 12.78%  |
| 2.01-3.0    | 16        | 12.03%  |
| 1.01-2.0    | 15        | 11.28%  |
| 32.01-64.0  | 6         | 4.51%   |
| 16.01-24.0  | 6         | 4.51%   |
| 24.01-32.0  | 5         | 3.76%   |
| 0.51-1.0    | 5         | 3.76%   |
| 64.01-256.0 | 1         | 0.75%   |
| 0.01-0.5    | 1         | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 66        | 52.8%   |
| 2      | 33        | 26.4%   |
| 3      | 10        | 8%      |
| 5      | 5         | 4%      |
| 6      | 4         | 3.2%    |
| 4      | 2         | 1.6%    |
| 23     | 1         | 0.8%    |
| 17     | 1         | 0.8%    |
| 11     | 1         | 0.8%    |
| 8      | 1         | 0.8%    |
| 0      | 1         | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 90.08%  |
| Yes       | 12        | 9.92%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 75%     |
| No        | 31        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 70.25%  |
| No        | 36        | 29.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 67.48%  |
| No        | 40        | 32.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 20        | 16.53%  |
| Germany     | 14        | 11.57%  |
| UK          | 9         | 7.44%   |
| France      | 9         | 7.44%   |
| Russia      | 8         | 6.61%   |
| Poland      | 7         | 5.79%   |
| Italy       | 7         | 5.79%   |
| Canada      | 7         | 5.79%   |
| Ukraine     | 6         | 4.96%   |
| Austria     | 4         | 3.31%   |
| Switzerland | 3         | 2.48%   |
| Czechia     | 3         | 2.48%   |
| Netherlands | 2         | 1.65%   |
| Denmark     | 2         | 1.65%   |
| Belgium     | 2         | 1.65%   |
| Australia   | 2         | 1.65%   |
| Uruguay     | 1         | 0.83%   |
| Sweden      | 1         | 0.83%   |
| Spain       | 1         | 0.83%   |
| Serbia      | 1         | 0.83%   |
| Romania     | 1         | 0.83%   |
| Portugal    | 1         | 0.83%   |
| New Zealand | 1         | 0.83%   |
| Latvia      | 1         | 0.83%   |
| Kyrgyzstan  | 1         | 0.83%   |
| Iraq        | 1         | 0.83%   |
| Iran        | 1         | 0.83%   |
| India       | 1         | 0.83%   |
| Hungary     | 1         | 0.83%   |
| Colombia    | 1         | 0.83%   |
| China       | 1         | 0.83%   |
| Brazil      | 1         | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Vienna             | 4         | 3.03%   |
| Marki              | 4         | 3.03%   |
| Kharkiv            | 4         | 3.03%   |
| Frankfurt am Main  | 4         | 3.03%   |
| Plymouth           | 3         | 2.27%   |
| Milwaukee          | 3         | 2.27%   |
| Capo d'Orlando     | 3         | 2.27%   |
| South Deerfield    | 2         | 1.52%   |
| Schaafheim         | 2         | 1.52%   |
| Richardson         | 2         | 1.52%   |
| Prague             | 2         | 1.52%   |
| Ottawa             | 2         | 1.52%   |
| Melbourne          | 2         | 1.52%   |
| Lyon               | 2         | 1.52%   |
| London             | 2         | 1.52%   |
| Krasnodar          | 2         | 1.52%   |
| Halifax            | 2         | 1.52%   |
| Gdansk             | 2         | 1.52%   |
| Darmstadt          | 2         | 1.52%   |
| Chelyabinsk        | 2         | 1.52%   |
| Yangzhou           | 1         | 0.76%   |
| Woodford           | 1         | 0.76%   |
| Wellington         | 1         | 0.76%   |
| Villeurbanne       | 1         | 0.76%   |
| Verneuil-sur-Seine | 1         | 0.76%   |
| Valpacos           | 1         | 0.76%   |
| Trento             | 1         | 0.76%   |
| Tottenham          | 1         | 0.76%   |
| Tolyatti           | 1         | 0.76%   |
| Tehran             | 1         | 0.76%   |
| Talas              | 1         | 0.76%   |
| Székesfehérvár  | 1         | 0.76%   |
| Stockholm          | 1         | 0.76%   |
| Southampton        | 1         | 0.76%   |
| Sindelfingen       | 1         | 0.76%   |
| Saratov            | 1         | 0.76%   |
| San Gabriel        | 1         | 0.76%   |
| Saarlouis          | 1         | 0.76%   |
| Saarbrücken       | 1         | 0.76%   |
| Riga               | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 48        | 102    | 25.26%  |
| WDC                         | 18        | 40     | 9.47%   |
| Sandisk                     | 16        | 22     | 8.42%   |
| Seagate                     | 15        | 41     | 7.89%   |
| Toshiba                     | 13        | 26     | 6.84%   |
| Crucial                     | 11        | 14     | 5.79%   |
| Kingston                    | 8         | 8      | 4.21%   |
| Intel                       | 8         | 13     | 4.21%   |
| Micron Technology           | 7         | 7      | 3.68%   |
| SK hynix                    | 6         | 9      | 3.16%   |
| Unknown                     | 5         | 8      | 2.63%   |
| HGST                        | 4         | 14     | 2.11%   |
| Transcend                   | 2         | 2      | 1.05%   |
| Plextor                     | 2         | 2      | 1.05%   |
| Phison Electronics          | 2         | 4      | 1.05%   |
| KIOXIA                      | 2         | 3      | 1.05%   |
| Kingston Technology Company | 2         | 2      | 1.05%   |
| China                       | 2         | 2      | 1.05%   |
| Apple                       | 2         | 5      | 1.05%   |
| Yangtze Memory Technologies | 1         | 1      | 0.53%   |
| Teclast                     | 1         | 2      | 0.53%   |
| SPCC                        | 1         | 1      | 0.53%   |
| Realtek Semiconductor       | 1         | 1      | 0.53%   |
| Phison                      | 1         | 1      | 0.53%   |
| OCZ                         | 1         | 1      | 0.53%   |
| LITEON                      | 1         | 1      | 0.53%   |
| Lexar                       | 1         | 1      | 0.53%   |
| INNOVATION IT               | 1         | 1      | 0.53%   |
| Hitachi                     | 1         | 3      | 0.53%   |
| Dogfish                     | 1         | 1      | 0.53%   |
| Corsair                     | 1         | 1      | 0.53%   |
| BIWIN                       | 1         | 1      | 0.53%   |
| ASMT                        | 1         | 1      | 0.53%   |
| ASMedia                     | 1         | 1      | 0.53%   |
| ADATA Technology            | 1         | 2      | 0.53%   |
| Unknown                     | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB                              | 5         | 2.16%   |
| Unknown MMC Card  32GB                               | 3         | 1.3%    |
| Seagate ST3000DM001-1ER166 3TB                       | 3         | 1.3%    |
| SanDisk SSD PLUS 240GB                               | 3         | 1.3%    |
| Samsung SSD 970 EVO Plus 2TB                         | 3         | 1.3%    |
| Samsung SSD 970 EVO Plus 1TB                         | 3         | 1.3%    |
| Samsung SSD 970 EVO 500GB                            | 3         | 1.3%    |
| Micron MTFDKCD512TFK 512GB                           | 3         | 1.3%    |
| Crucial CT1000MX500SSD1 1TB                          | 3         | 1.3%    |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                 | 2         | 0.87%   |
| Seagate ST3000DM001-1CH166 3TB                       | 2         | 0.87%   |
| SanDisk Ultra II 240GB SSD                           | 2         | 0.87%   |
| SanDisk NVMe SSD Drive 1TB                           | 2         | 0.87%   |
| Samsung SSD 980 PRO 1TB                              | 2         | 0.87%   |
| Samsung SSD 970 EVO 1TB                              | 2         | 0.87%   |
| Samsung SSD 870 EVO 1TB                              | 2         | 0.87%   |
| Samsung SSD 860 QVO 1TB                              | 2         | 0.87%   |
| Samsung SSD 860 EVO 500GB                            | 2         | 0.87%   |
| Samsung SSD 860 EVO 2TB                              | 2         | 0.87%   |
| Samsung SSD 860 EVO 250GB                            | 2         | 0.87%   |
| Samsung SSD 850 EVO 500GB                            | 2         | 0.87%   |
| Samsung PM9A1 NVMe 1024GB                            | 2         | 0.87%   |
| Samsung NVMe SSD Drive 1TB                           | 2         | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 2         | 0.87%   |
| Kingston SA400S37960G 960GB SSD                      | 2         | 0.87%   |
| HGST HTS721010A9E630 1TB                             | 2         | 0.87%   |
| Crucial CT250MX500SSD1 250GB                         | 2         | 0.87%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                 | 1         | 0.43%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                     | 1         | 0.43%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 1         | 0.43%   |
| WDC WDS200T1X0E-00AFY0 2TB                           | 1         | 0.43%   |
| WDC WD80EMAZ-00WJTA0 8TB                             | 1         | 0.43%   |
| WDC WD80EDAZ-11TA3A0 8TB                             | 1         | 0.43%   |
| WDC WD50EZRX-00MVLB1 5TB                             | 1         | 0.43%   |
| WDC WD40EFRX-68N32N0 4TB                             | 1         | 0.43%   |
| WDC WD3200BPVT-22JJ5T0 320GB                         | 1         | 0.43%   |
| WDC WD20EZRX-00D8PB0 2TB                             | 1         | 0.43%   |
| WDC WD20EARX-008FB0 2TB                              | 1         | 0.43%   |
| WDC WD1600AAJS-62B4A0 160GB                          | 1         | 0.43%   |
| WDC WD120EMFZ-11A6JA0 12TB                           | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 41     | 34.88%  |
| WDC                 | 12        | 32     | 27.91%  |
| Toshiba             | 9         | 19     | 20.93%  |
| HGST                | 4         | 14     | 9.3%    |
| Samsung Electronics | 1         | 1      | 2.33%   |
| Hitachi             | 1         | 3      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 55     | 31.08%  |
| Crucial             | 10        | 13     | 13.51%  |
| SanDisk             | 9         | 14     | 12.16%  |
| Kingston            | 5         | 5      | 6.76%   |
| Intel               | 5         | 7      | 6.76%   |
| WDC                 | 2         | 3      | 2.7%    |
| Transcend           | 2         | 2      | 2.7%    |
| China               | 2         | 2      | 2.7%    |
| Apple               | 2         | 4      | 2.7%    |
| Toshiba             | 1         | 1      | 1.35%   |
| Teclast             | 1         | 2      | 1.35%   |
| SPCC                | 1         | 1      | 1.35%   |
| SK hynix            | 1         | 1      | 1.35%   |
| Plextor             | 1         | 1      | 1.35%   |
| OCZ                 | 1         | 1      | 1.35%   |
| Micron Technology   | 1         | 1      | 1.35%   |
| LITEON              | 1         | 1      | 1.35%   |
| INNOVATION IT       | 1         | 1      | 1.35%   |
| Dogfish             | 1         | 1      | 1.35%   |
| Corsair             | 1         | 1      | 1.35%   |
| BIWIN               | 1         | 1      | 1.35%   |
| ASMT                | 1         | 1      | 1.35%   |
| ASMedia             | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 72        | 105    | 42.86%  |
| SSD  | 61        | 120    | 36.31%  |
| HDD  | 30        | 111    | 17.86%  |
| MMC  | 5         | 9      | 2.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 72        | 105    | 48.32%  |
| SATA | 67        | 223    | 44.97%  |
| SAS  | 5         | 8      | 3.36%   |
| MMC  | 5         | 9      | 3.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 90     | 46.15%  |
| 0.51-1.0   | 29        | 54     | 27.88%  |
| 1.01-2.0   | 10        | 15     | 9.62%   |
| 4.01-10.0  | 7         | 47     | 6.73%   |
| 2.01-3.0   | 6         | 12     | 5.77%   |
| 3.01-4.0   | 3         | 7      | 2.88%   |
| 10.01-20.0 | 1         | 6      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 60        | 48%     |
| 1-20           | 21        | 16.8%   |
| 251-500        | 10        | 8%      |
| 501-1000       | 10        | 8%      |
| 101-250        | 7         | 5.6%    |
| 2001-3000      | 6         | 4.8%    |
| 1001-2000      | 5         | 4%      |
| More than 3000 | 4         | 3.2%    |
| 21-50          | 2         | 1.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 60        | 47.24%  |
| 1-20           | 29        | 22.83%  |
| 101-250        | 10        | 7.87%   |
| 251-500        | 7         | 5.51%   |
| 21-50          | 5         | 3.94%   |
| 501-1000       | 5         | 3.94%   |
| 51-100         | 5         | 3.94%   |
| 1001-2000      | 3         | 2.36%   |
| 2001-3000      | 2         | 1.57%   |
| More than 3000 | 1         | 0.79%   |

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
| ASMT 2115 128GB                                | 1         | 1      | 6.67%   |

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


| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| Toshiba MG03ACA300 3TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 113       | 293    | 79.58%  |
| Detected | 16        | 32     | 11.27%  |
| Malfunc  | 12        | 19     | 8.45%   |
| Failed   | 1         | 1      | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 60        | 34.29%  |
| Samsung Electronics          | 32        | 18.29%  |
| AMD                          | 28        | 16%     |
| SanDisk                      | 12        | 6.86%   |
| Micron Technology            | 6         | 3.43%   |
| Kingston Technology Company  | 6         | 3.43%   |
| SK hynix                     | 5         | 2.86%   |
| ASMedia Technology           | 5         | 2.86%   |
| Toshiba America Info Systems | 4         | 2.29%   |
| Phison Electronics           | 3         | 1.71%   |
| LSI Logic / Symbios Logic    | 3         | 1.71%   |
| Broadcom / LSI               | 3         | 1.71%   |
| KIOXIA                       | 2         | 1.14%   |
| Yangtze Memory Technologies  | 1         | 0.57%   |
| Shenzhen Longsys Electronics | 1         | 0.57%   |
| Realtek Semiconductor        | 1         | 0.57%   |
| Micron/Crucial Technology    | 1         | 0.57%   |
| Lite-On Technology           | 1         | 0.57%   |
| ADATA Technology             | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 20        | 10.81%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 9.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 4.32%   |
| AMD 500 Series Chipset SATA Controller                                         | 8         | 4.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 3.24%   |
| Micron Non-Volatile memory controller                                          | 6         | 3.24%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 2.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 2.7%    |
| Sandisk Non-Volatile memory controller                                         | 4         | 2.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 2.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 2.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.16%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.16%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.62%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.62%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.62%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.62%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.08%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.08%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.08%   |
| Samsung Electronics SATA controller                                            | 2         | 1.08%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2         | 1.08%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.08%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.08%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.08%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.08%   |
| Intel Comet Lake PCH-H RAID                                                    | 2         | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.08%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 1.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.08%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 2         | 1.08%   |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 74        | 44.31%  |
| NVMe | 73        | 43.71%  |
| RAID | 11        | 6.59%   |
| SAS  | 6         | 3.59%   |
| IDE  | 3         | 1.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 74        | 61.16%  |
| AMD    | 43        | 35.54%  |
| ARM    | 4         | 3.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 4.13%   |
| AMD Ryzen 5 3600 6-Core Processor          | 5         | 4.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 3.31%   |
| ARM Processor                              | 4         | 3.31%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 3         | 2.48%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 2.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 3         | 2.48%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 2.48%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 2.48%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 3         | 2.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 1.65%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 1.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 1.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 1.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 2         | 1.65%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 1.65%   |
| Intel 12th Gen Core i5-1240P               | 2         | 1.65%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 2         | 1.65%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 1.65%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 2         | 1.65%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 2         | 1.65%   |
| Intel Xeon W-1290P CPU @ 3.70GHz           | 1         | 0.83%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 0.83%   |
| Intel Xeon CPU L5640 @ 2.27GHz             | 1         | 0.83%   |
| Intel Xeon CPU E5606 @ 2.13GHz             | 1         | 0.83%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz        | 1         | 0.83%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz       | 1         | 0.83%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 0.83%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 0.83%   |
| Intel Core i9-9900X CPU @ 3.50GHz          | 1         | 0.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 0.83%   |
| Intel Core i7-6850K CPU @ 3.60GHz          | 1         | 0.83%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 0.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 0.83%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 0.83%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 0.83%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 0.83%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 0.83%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 1         | 0.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 1         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 29        | 23.97%  |
| Other                  | 17        | 14.05%  |
| Intel Core i5          | 16        | 13.22%  |
| AMD Ryzen 7            | 15        | 12.4%   |
| AMD Ryzen 5            | 14        | 11.57%  |
| AMD Ryzen 9            | 7         | 5.79%   |
| Intel Xeon             | 6         | 4.96%   |
| Intel Celeron          | 4         | 3.31%   |
| AMD Ryzen 7 PRO        | 4         | 3.31%   |
| Intel Core i3          | 3         | 2.48%   |
| Intel Core i9          | 2         | 1.65%   |
| AMD Ryzen Threadripper | 2         | 1.65%   |
| Intel Core m3          | 1         | 0.83%   |
| AMD FX                 | 1         | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 40        | 33.06%  |
| 8       | 25        | 20.66%  |
| 6       | 22        | 18.18%  |
| 2       | 16        | 13.22%  |
| 12      | 8         | 6.61%   |
| Unknown | 4         | 3.31%   |
| 16      | 2         | 1.65%   |
| 10      | 2         | 1.65%   |
| 32      | 1         | 0.83%   |
| 24      | 1         | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 115       | 95.04%  |
| Unknown | 4         | 3.31%   |
| 2       | 2         | 1.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 104       | 85.95%  |
| 1       | 13        | 10.74%  |
| Unknown | 4         | 3.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 121       | 99.18%  |
| Unknown        | 1         | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 17.74%  |
| 0x306c3    | 7         | 5.65%   |
| 0x0a50000c | 7         | 5.65%   |
| 0x08701021 | 7         | 5.65%   |
| 0x806ea    | 6         | 4.84%   |
| 0x806c1    | 6         | 4.84%   |
| 0x0a50000d | 6         | 4.84%   |
| 0x906ea    | 4         | 3.23%   |
| 0x806ec    | 4         | 3.23%   |
| 0x506e3    | 4         | 3.23%   |
| 0x306a9    | 4         | 3.23%   |
| 0x08701013 | 4         | 3.23%   |
| 0x906a3    | 3         | 2.42%   |
| 0x806eb    | 3         | 2.42%   |
| 0x0a404102 | 3         | 2.42%   |
| 0x08600106 | 3         | 2.42%   |
| 0x906e9    | 2         | 1.61%   |
| 0x806e9    | 2         | 1.61%   |
| 0x706a1    | 2         | 1.61%   |
| 0x406e3    | 2         | 1.61%   |
| 0x306d4    | 2         | 1.61%   |
| 0x0a201204 | 2         | 1.61%   |
| 0x0a201009 | 2         | 1.61%   |
| 0xa0653    | 1         | 0.81%   |
| 0xa0652    | 1         | 0.81%   |
| 0x906ed    | 1         | 0.81%   |
| 0x806d1    | 1         | 0.81%   |
| 0x706a8    | 1         | 0.81%   |
| 0x406f1    | 1         | 0.81%   |
| 0x40661    | 1         | 0.81%   |
| 0x40651    | 1         | 0.81%   |
| 0x306f2    | 1         | 0.81%   |
| 0x206c2    | 1         | 0.81%   |
| 0x0a50000b | 1         | 0.81%   |
| 0x0a201016 | 1         | 0.81%   |
| 0x08600104 | 1         | 0.81%   |
| 0x08301025 | 1         | 0.81%   |
| 0x0800820d | 1         | 0.81%   |
| 0x08001137 | 1         | 0.81%   |
| 0x06000852 | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 25        | 20.66%  |
| Zen 3            | 19        | 15.7%   |
| Zen 2            | 17        | 14.05%  |
| Haswell          | 10        | 8.26%   |
| Skylake          | 9         | 7.44%   |
| Unknown          | 9         | 7.44%   |
| TigerLake        | 7         | 5.79%   |
| IvyBridge        | 5         | 4.13%   |
| Goldmont plus    | 4         | 3.31%   |
| CometLake        | 3         | 2.48%   |
| Broadwell        | 3         | 2.48%   |
| Alderlake Hybrid | 3         | 2.48%   |
| Zen+             | 2         | 1.65%   |
| Westmere         | 2         | 1.65%   |
| Zen              | 1         | 0.83%   |
| Piledriver       | 1         | 0.83%   |
| Icelake          | 1         | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 58        | 39.46%  |
| Nvidia                     | 47        | 31.97%  |
| AMD                        | 39        | 26.53%  |
| Matrox Electronics Systems | 2         | 1.36%   |
| ASPEED Technology          | 1         | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 11        | 7.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 4.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 6         | 4.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 3.36%   |
| Intel UHD Graphics 620                                                                | 5         | 3.36%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 5         | 3.36%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 2.68%   |
| Intel HD Graphics 530                                                                 | 4         | 2.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 2.68%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 4         | 2.68%   |
| AMD Renoir                                                                            | 4         | 2.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 2.01%   |
| Nvidia GK104 [GeForce GTX 760]                                                        | 3         | 2.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 2.01%   |
| Intel HD Graphics 620                                                                 | 3         | 2.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 2.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 2.01%   |
| AMD Rembrandt [Radeon 680M]                                                           | 3         | 2.01%   |
| AMD Barcelo                                                                           | 3         | 2.01%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 2         | 1.34%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 1.34%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.34%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 1.34%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 1.34%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                         | 2         | 1.34%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 1.34%   |
| Intel HD Graphics 630                                                                 | 2         | 1.34%   |
| Intel HD Graphics 5500                                                                | 2         | 1.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 1.34%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 1.34%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                              | 2         | 1.34%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.34%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.67%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 0.67%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                    | 1         | 0.67%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                 | 1         | 0.67%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                 | 1         | 0.67%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                 | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 29.75%  |
| 1 x AMD        | 26        | 21.49%  |
| 1 x Nvidia     | 19        | 15.7%   |
| Intel + Nvidia | 19        | 15.7%   |
| AMD + Nvidia   | 9         | 7.44%   |
| Other          | 5         | 4.13%   |
| 2 x AMD        | 2         | 1.65%   |
| 1 x Matrox     | 2         | 1.65%   |
| Intel + AMD    | 2         | 1.65%   |
| 1 x ASPEED     | 1         | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 85        | 69.67%  |
| Proprietary | 28        | 22.95%  |
| Unknown     | 9         | 7.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 62.9%   |
| 0.01-0.5   | 15        | 12.1%   |
| 7.01-8.0   | 10        | 8.06%   |
| 1.01-2.0   | 10        | 8.06%   |
| 3.01-4.0   | 8         | 6.45%   |
| 0.51-1.0   | 2         | 1.61%   |
| 8.01-16.0  | 1         | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 22        | 16.92%  |
| AU Optronics         | 16        | 12.31%  |
| Samsung Electronics  | 11        | 8.46%   |
| Goldstar             | 11        | 8.46%   |
| LG Display           | 9         | 6.92%   |
| BOE                  | 9         | 6.92%   |
| Chimei Innolux       | 7         | 5.38%   |
| Acer                 | 6         | 4.62%   |
| PANDA                | 5         | 3.85%   |
| Sharp                | 4         | 3.08%   |
| Hewlett-Packard      | 3         | 2.31%   |
| CSO                  | 3         | 2.31%   |
| Ancor Communications | 3         | 2.31%   |
| InfoVision           | 2         | 1.54%   |
| Apple                | 2         | 1.54%   |
| AOC                  | 2         | 1.54%   |
| WST                  | 1         | 0.77%   |
| Vizio                | 1         | 0.77%   |
| Unknown (AAA)        | 1         | 0.77%   |
| RTK                  | 1         | 0.77%   |
| Philips              | 1         | 0.77%   |
| Panasonic            | 1         | 0.77%   |
| NEC Computers        | 1         | 0.77%   |
| MPI                  | 1         | 0.77%   |
| Lenovo               | 1         | 0.77%   |
| JDI                  | 1         | 0.77%   |
| Iiyama               | 1         | 0.77%   |
| HVR                  | 1         | 0.77%   |
| Eizo                 | 1         | 0.77%   |
| BenQ                 | 1         | 0.77%   |
| ASUSTek Computer     | 1         | 0.77%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO019C 1920x1200 286x178mm 13.3-inch          | 3         | 2.24%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 2         | 1.49%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 2         | 1.49%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                       | 2         | 1.49%   |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                        | 2         | 1.49%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                       | 2         | 1.49%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                     | 2         | 1.49%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                       | 2         | 1.49%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                   | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch          | 2         | 1.49%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                    | 2         | 1.49%   |
| WST KL.1350W.003 WST2C34 2256x1504 285x190mm 13.5-inch                  | 1         | 0.75%   |
| Vizio D43-D2 VIZ1004 1920x1080 477x268mm 21.5-inch                      | 1         | 0.75%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch             | 1         | 0.75%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                 | 1         | 0.75%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                 | 1         | 0.75%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                 | 1         | 0.75%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch                 | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch    | 1         | 0.75%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 1         | 0.75%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch       | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch   | 1         | 0.75%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch       | 1         | 0.75%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 0.75%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                       | 1         | 0.75%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                | 1         | 0.75%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                 | 1         | 0.75%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch                 | 1         | 0.75%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch                 | 1         | 0.75%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                 | 1         | 0.75%   |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                 | 1         | 0.75%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch            | 1         | 0.75%   |
| NEC Computers 90GX2 NEC6692 1280x1024 376x301mm 19.0-inch               | 1         | 0.75%   |
| MPI MPI7002 MPI7002 1280x1024 255x255mm 14.2-inch                       | 1         | 0.75%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 36.51%  |
| 3840x2160 (4K)     | 22        | 17.46%  |
| 2560x1440 (QHD)    | 15        | 11.9%   |
| 1920x1200 (WUXGA)  | 8         | 6.35%   |
| 1366x768 (WXGA)    | 8         | 6.35%   |
| 1280x1024 (SXGA)   | 5         | 3.97%   |
| 2560x1600          | 4         | 3.17%   |
| 2560x1080          | 4         | 3.17%   |
| 2880x1800          | 3         | 2.38%   |
| 2256x1504          | 3         | 2.38%   |
| 3440x1440          | 2         | 1.59%   |
| 1680x1050 (WSXGA+) | 2         | 1.59%   |
| 3840x2400          | 1         | 0.79%   |
| 2160x1200          | 1         | 0.79%   |
| 1440x900 (WXGA+)   | 1         | 0.79%   |
| 1280x720 (HD)      | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 16.28%  |
| 13      | 18        | 13.95%  |
| 27      | 17        | 13.18%  |
| 14      | 16        | 12.4%   |
| 24      | 11        | 8.53%   |
| 23      | 9         | 6.98%   |
| 34      | 6         | 4.65%   |
| 17      | 6         | 4.65%   |
| 31      | 5         | 3.88%   |
| 12      | 5         | 3.88%   |
| 25      | 2         | 1.55%   |
| 22      | 2         | 1.55%   |
| 21      | 2         | 1.55%   |
| 19      | 2         | 1.55%   |
| 16      | 2         | 1.55%   |
| 84      | 1         | 0.78%   |
| 49      | 1         | 0.78%   |
| 46      | 1         | 0.78%   |
| 11      | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 35.2%   |
| 501-600     | 35        | 28%     |
| 201-300     | 21        | 16.8%   |
| 701-800     | 6         | 4.8%    |
| 601-700     | 6         | 4.8%    |
| 351-400     | 5         | 4%      |
| 401-500     | 4         | 3.2%    |
| 1001-1500   | 2         | 1.6%    |
| 1501-2000   | 1         | 0.8%    |
| Unknown     | 1         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 76        | 68.47%  |
| 16/10 | 20        | 18.02%  |
| 21/9  | 6         | 5.41%   |
| 5/4   | 5         | 4.5%    |
| 3/2   | 3         | 2.7%    |
| 1.00  | 1         | 0.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 22        | 16.92%  |
| 101-110        | 22        | 16.92%  |
| 201-250        | 19        | 14.62%  |
| 301-350        | 17        | 13.08%  |
| 71-80          | 11        | 8.46%   |
| 351-500        | 11        | 8.46%   |
| 251-300        | 6         | 4.62%   |
| 61-70          | 5         | 3.85%   |
| 151-200        | 4         | 3.08%   |
| 141-150        | 3         | 2.31%   |
| More than 1000 | 2         | 1.54%   |
| 121-130        | 2         | 1.54%   |
| 111-120        | 2         | 1.54%   |
| 51-60          | 1         | 0.77%   |
| 131-140        | 1         | 0.77%   |
| 501-1000       | 1         | 0.77%   |
| Unknown        | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 35        | 29.17%  |
| 161-240       | 30        | 25%     |
| 121-160       | 27        | 22.5%   |
| 101-120       | 14        | 11.67%  |
| More than 240 | 11        | 9.17%   |
| 1-50          | 2         | 1.67%   |
| Unknown       | 1         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 74        | 58.73%  |
| 2     | 26        | 20.63%  |
| 0     | 21        | 16.67%  |
| 3     | 5         | 3.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 80        | 45.98%  |
| Realtek Semiconductor             | 63        | 36.21%  |
| Qualcomm Atheros                  | 5         | 2.87%   |
| MediaTek                          | 4         | 2.3%    |
| Broadcom                          | 3         | 1.72%   |
| Qualcomm                          | 2         | 1.15%   |
| Microsoft                         | 2         | 1.15%   |
| Lenovo                            | 2         | 1.15%   |
| Aquantia                          | 2         | 1.15%   |
| Xiaomi                            | 1         | 0.57%   |
| TP-Link                           | 1         | 0.57%   |
| Texas Instruments                 | 1         | 0.57%   |
| Standard Microsystems             | 1         | 0.57%   |
| Ralink Technology                 | 1         | 0.57%   |
| Ralink                            | 1         | 0.57%   |
| Pulse-Eight                       | 1         | 0.57%   |
| Oculus VR                         | 1         | 0.57%   |
| ICS Advent                        | 1         | 0.57%   |
| Fibocom                           | 1         | 0.57%   |
| Ericsson Business Mobile Networks | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 19.6%   |
| Intel Wi-Fi 6 AX200                                               | 16        | 8.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 7.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 3.02%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.51%   |
| Intel Wireless 7265                                               | 4         | 2.01%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 2.01%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.01%   |
| Realtek Realtek Network controller                                | 3         | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.51%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 1.51%   |
| Intel Wireless-AC 9260                                            | 3         | 1.51%   |
| Intel Wireless 8260                                               | 3         | 1.51%   |
| Intel Wireless 7260                                               | 3         | 1.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 1.51%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.51%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.51%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 1.01%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.01%   |
| Intel Wireless 3165                                               | 2         | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.01%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.01%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.01%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.01%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.01%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.5%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.5%    |
| Texas Instruments CC2538 USB CDC                                  | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 62        | 72.09%  |
| Realtek Semiconductor             | 6         | 6.98%   |
| Qualcomm Atheros                  | 4         | 4.65%   |
| MediaTek                          | 3         | 3.49%   |
| Qualcomm                          | 2         | 2.33%   |
| Microsoft                         | 2         | 2.33%   |
| Broadcom                          | 2         | 2.33%   |
| TP-Link                           | 1         | 1.16%   |
| Ralink Technology                 | 1         | 1.16%   |
| Ralink                            | 1         | 1.16%   |
| Fibocom                           | 1         | 1.16%   |
| Ericsson Business Mobile Networks | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 16        | 18.6%   |
| Intel Wireless 7265                                        | 4         | 4.65%   |
| Intel Wi-Fi 6 AX201                                        | 4         | 4.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 4         | 4.65%   |
| Realtek Realtek Network controller                         | 3         | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 3.49%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 3         | 3.49%   |
| Intel Wireless-AC 9260                                     | 3         | 3.49%   |
| Intel Wireless 8260                                        | 3         | 3.49%   |
| Intel Wireless 7260                                        | 3         | 3.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 3         | 3.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3         | 3.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 3.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                           | 3         | 3.49%   |
| Microsoft Xbox 360 Wireless Adapter                        | 2         | 2.33%   |
| Intel Wireless 8265 / 8275                                 | 2         | 2.33%   |
| Intel Wireless 3165                                        | 2         | 2.33%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 2         | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 2         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2         | 2.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 2         | 2.33%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 1.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.16%   |
| Ralink RT5370 Wireless Adapter                             | 1         | 1.16%   |
| Ralink RT2800 802.11n PCI                                  | 1         | 1.16%   |
| Qualcomm QCNFA765 Wireless Network Adapter                 | 1         | 1.16%   |
| Qualcomm QCA6390 Wireless Network Adapter                  | 1         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 1.16%   |
| Intel Wireless 3160                                        | 1         | 1.16%   |
| Fibocom L830-EB-00 LTE WWAN Modem                          | 1         | 1.16%   |
| Ericsson Business Mobile Networks N5321 gw                 | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 57        | 54.29%  |
| Intel                 | 37        | 35.24%  |
| Lenovo                | 2         | 1.9%    |
| Broadcom              | 2         | 1.9%    |
| Aquantia              | 2         | 1.9%    |
| Xiaomi                | 1         | 0.95%   |
| Standard Microsystems | 1         | 0.95%   |
| Qualcomm Atheros      | 1         | 0.95%   |
| MediaTek              | 1         | 0.95%   |
| ICS Advent            | 1         | 0.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 35.45%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 12.73%  |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 5.45%   |
| Intel I211 Gigabit Network Connection                             | 5         | 4.55%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.64%   |
| Intel Ethernet Controller I225-V                                  | 3         | 2.73%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.73%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.82%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.82%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.82%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.82%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.82%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.91%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.91%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.91%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.91%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.91%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.91%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.91%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.91%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.91%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.91%   |
| ICS Advent 10/100M LAN                                            | 1         | 0.91%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.91%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.91%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.91%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 0.91%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 94        | 52.22%  |
| WiFi     | 83        | 46.11%  |
| Modem    | 3         | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 67        | 53.6%   |
| Ethernet | 58        | 46.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 63        | 51.64%  |
| 2     | 50        | 40.98%  |
| 0     | 5         | 4.1%    |
| 3     | 3         | 2.46%   |
| 4     | 1         | 0.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 94        | 75.2%   |
| Yes  | 31        | 24.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 66.67%  |
| Realtek Semiconductor           | 8         | 9.52%   |
| Qualcomm Atheros Communications | 3         | 3.57%   |
| MediaTek                        | 3         | 3.57%   |
| Broadcom                        | 3         | 3.57%   |
| ASUSTek Computer                | 3         | 3.57%   |
| Cambridge Silicon Radio         | 2         | 2.38%   |
| Apple                           | 2         | 2.38%   |
| USI                             | 1         | 1.19%   |
| Lite-On Technology              | 1         | 1.19%   |
| HTC (High Tech Computer)        | 1         | 1.19%   |
| Foxconn / Hon Hai               | 1         | 1.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 14        | 16.67%  |
| Intel Bluetooth wireless interface                                   | 13        | 15.48%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 9         | 10.71%  |
| Realtek Bluetooth Radio                                              | 8         | 9.52%   |
| Intel AX201 Bluetooth                                                | 8         | 9.52%   |
| MediaTek Wireless_Device                                             | 3         | 3.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 3.57%   |
| Intel Bluetooth Device                                               | 3         | 3.57%   |
| Intel AX210 Bluetooth                                                | 3         | 3.57%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2         | 2.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 2.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 2.38%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 2.38%   |
| USI Bluetooth Device                                                 | 1         | 1.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 1.19%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 1.19%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.19%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1         | 1.19%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 1.19%   |
| ASUS ASUS USB-BT500                                                  | 1         | 1.19%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 1.19%   |
| Apple Bluetooth Host Controller                                      | 1         | 1.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 71        | 37.37%  |
| AMD                                  | 47        | 24.74%  |
| Nvidia                               | 31        | 16.32%  |
| C-Media Electronics                  | 6         | 3.16%   |
| Creative Technology                  | 4         | 2.11%   |
| Texas Instruments                    | 3         | 1.58%   |
| Lenovo                               | 3         | 1.58%   |
| Synaptics                            | 2         | 1.05%   |
| Realtek Semiconductor                | 2         | 1.05%   |
| Kingston Technology                  | 2         | 1.05%   |
| DSEA A/S                             | 2         | 1.05%   |
| Unknown                              | 1         | 0.53%   |
| Trust                                | 1         | 0.53%   |
| Thomann                              | 1         | 0.53%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.53%   |
| Sony                                 | 1         | 0.53%   |
| Sennheiser Communications            | 1         | 0.53%   |
| Schiit Audio                         | 1         | 0.53%   |
| Satechi                              | 1         | 0.53%   |
| Razer USA                            | 1         | 0.53%   |
| PreSonus Audio Electronics           | 1         | 0.53%   |
| GYROCOM C&C                          | 1         | 0.53%   |
| Focusrite-Novation                   | 1         | 0.53%   |
| Edifier Technology                   | 1         | 0.53%   |
| Creative Labs                        | 1         | 0.53%   |
| Corsair                              | 1         | 0.53%   |
| Antlion Audio                        | 1         | 0.53%   |
| (LCS) USB Audio Device               | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 20        | 8.81%   |
| AMD Starship/Matisse HD Audio Controller                            | 17        | 7.49%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 16        | 7.05%   |
| Intel Sunrise Point-LP HD Audio                                     | 12        | 5.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 7         | 3.08%   |
| Intel Cannon Lake PCH cAVS                                          | 6         | 2.64%   |
| AMD Navi 10 HDMI Audio                                              | 6         | 2.64%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 6         | 2.64%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 5         | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 5         | 2.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 5         | 2.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 5         | 2.2%    |
| Nvidia GP107GL High Definition Audio Controller                     | 4         | 1.76%   |
| Nvidia GK104 HDMI Audio Controller                                  | 4         | 1.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 4         | 1.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 4         | 1.76%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 1.32%   |
| Nvidia GA106 High Definition Audio Controller                       | 3         | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3         | 1.32%   |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 1.32%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 1.32%   |
| Creative Technology SoundBlaster Live! 24-bit External SB0490       | 3         | 1.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 3         | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 3         | 1.32%   |
| Texas Instruments PCM2902 Audio Codec                               | 2         | 0.88%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                 | 2         | 0.88%   |
| Realtek Semiconductor USB Audio                                     | 2         | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                       | 2         | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                       | 2         | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 0.88%   |
| Kingston Technology HyperX 7.1 Audio                                | 2         | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 0.88%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2         | 0.88%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2         | 0.88%   |
| Intel 200 Series PCH HD Audio                                       | 2         | 0.88%   |
| DSEA A/S Headset [PC 8]                                             | 2         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 24.63%  |
| Kingston            | 20        | 14.93%  |
| SK hynix            | 16        | 11.94%  |
| Corsair             | 15        | 11.19%  |
| Micron Technology   | 14        | 10.45%  |
| Crucial             | 11        | 8.21%   |
| G.Skill             | 8         | 5.97%   |
| Unknown (ABCD)      | 4         | 2.99%   |
| Unknown             | 3         | 2.24%   |
| Team                | 3         | 2.24%   |
| Goodram             | 2         | 1.49%   |
| AMD                 | 2         | 1.49%   |
| Strontium           | 1         | 0.75%   |
| Avant               | 1         | 0.75%   |
| A-DATA Technology   | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 2.05%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 2.05%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 3         | 2.05%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 1.37%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.37%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.37%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.37%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 1.37%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 1.37%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 1.37%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 2         | 1.37%   |
| Corsair RAM CMK16GX4M1D3000C16 16384MB DIMM DDR4 3000MT/s        | 2         | 1.37%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.68%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.68%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                    | 1         | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.68%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s               | 1         | 0.68%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s               | 1         | 0.68%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                     | 1         | 0.68%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.68%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.68%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.68%   |
| SK hynix RAM HMT41GU7MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.68%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.68%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.68%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 1         | 0.68%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.68%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.68%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.68%   |
| SK hynix RAM H5ANAG6NCJR-XN 8GB SODIMM DDR4 3200MT/s             | 1         | 0.68%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.68%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.68%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.68%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.68%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 0.68%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 74        | 64.35%  |
| DDR3   | 21        | 18.26%  |
| LPDDR4 | 10        | 8.7%    |
| LPDDR5 | 4         | 3.48%   |
| LPDDR3 | 4         | 3.48%   |
| DDR5   | 2         | 1.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 47.01%  |
| DIMM         | 42        | 35.9%   |
| Row Of Chips | 17        | 14.53%  |
| RIMM         | 1         | 0.85%   |
| Chip         | 1         | 0.85%   |
| Unknown      | 1         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 51        | 40.48%  |
| 16384 | 42        | 33.33%  |
| 4096  | 17        | 13.49%  |
| 32768 | 13        | 10.32%  |
| 2048  | 3         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 35        | 27.78%  |
| 2667  | 15        | 11.9%   |
| 1600  | 15        | 11.9%   |
| 2400  | 10        | 7.94%   |
| 2133  | 10        | 7.94%   |
| 3600  | 5         | 3.97%   |
| 6400  | 4         | 3.17%   |
| 4267  | 4         | 3.17%   |
| 3733  | 3         | 2.38%   |
| 3000  | 3         | 2.38%   |
| 1867  | 3         | 2.38%   |
| 1333  | 3         | 2.38%   |
| 4800  | 2         | 1.59%   |
| 4266  | 2         | 1.59%   |
| 3334  | 2         | 1.59%   |
| 2933  | 2         | 1.59%   |
| 3866  | 1         | 0.79%   |
| 3666  | 1         | 0.79%   |
| 3534  | 1         | 0.79%   |
| 3400  | 1         | 0.79%   |
| 3266  | 1         | 0.79%   |
| 2134  | 1         | 0.79%   |
| 2132  | 1         | 0.79%   |
| 1066  | 1         | 0.79%   |

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
| Chicony Electronics           | 13        | 17.57%  |
| Microdia                      | 11        | 14.86%  |
| Acer                          | 11        | 14.86%  |
| Logitech                      | 9         | 12.16%  |
| IMC Networks                  | 9         | 12.16%  |
| Realtek Semiconductor         | 6         | 8.11%   |
| Sunplus Innovation Technology | 4         | 5.41%   |
| Quanta                        | 3         | 4.05%   |
| MacroSilicon                  | 2         | 2.7%    |
| Apple                         | 2         | 2.7%    |
| Syntek                        | 1         | 1.35%   |
| SunplusIT                     | 1         | 1.35%   |
| Lite-On Technology            | 1         | 1.35%   |
| 2M UVC CAMERA                 | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 8         | 10.53%  |
| Acer Integrated Camera               | 7         | 9.21%   |
| Microdia Integrated_Webcam_HD        | 6         | 7.89%   |
| IMC Networks USB2.0 HD UVC WebCam    | 5         | 6.58%   |
| IMC Networks Integrated Camera       | 3         | 3.95%   |
| Chicony HP HD Camera                 | 3         | 3.95%   |
| Sunplus Integrated_Webcam_FHD        | 2         | 2.63%   |
| Realtek Laptop Camera                | 2         | 2.63%   |
| Realtek Integrated_Webcam_HD         | 2         | 2.63%   |
| MacroSilicon USB Video               | 2         | 2.63%   |
| Logitech Webcam C270                 | 2         | 2.63%   |
| Logitech HD Pro Webcam C920          | 2         | 2.63%   |
| Acer Integrated IR Camera            | 2         | 2.63%   |
| Syntek Integrated Camera             | 1         | 1.32%   |
| SunplusIT MTD camera                 | 1         | 1.32%   |
| Sunplus Integrated_Webcam_HD         | 1         | 1.32%   |
| Sunplus HD WebCam                    | 1         | 1.32%   |
| Realtek Integrated Webcam            | 1         | 1.32%   |
| Realtek EasyCamera                   | 1         | 1.32%   |
| Quanta VGA WebCam                    | 1         | 1.32%   |
| Quanta HP True Vision HD Camera      | 1         | 1.32%   |
| Quanta HD WebCam                     | 1         | 1.32%   |
| Microdia Webcam Vitade AF            | 1         | 1.32%   |
| Microdia USB 2.0 Camera              | 1         | 1.32%   |
| Microdia Laptop_Integrated_Webcam_HD | 1         | 1.32%   |
| Microdia Integrated Webcam           | 1         | 1.32%   |
| Microdia Camera                      | 1         | 1.32%   |
| Logitech Webcam C930e                | 1         | 1.32%   |
| Logitech Webcam C310                 | 1         | 1.32%   |
| Logitech Webcam C120                 | 1         | 1.32%   |
| Logitech StreamCam                   | 1         | 1.32%   |
| Logitech C930c                       | 1         | 1.32%   |
| Lite-On HP HD Camera                 | 1         | 1.32%   |
| IMC Networks XHC Camera              | 1         | 1.32%   |
| Chicony USB2.0 Camera                | 1         | 1.32%   |
| Chicony Integrated Camera [ThinkPad] | 1         | 1.32%   |
| Apple iPhone 5/5C/5S/6/SE            | 1         | 1.32%   |
| Apple FaceTime HD Camera (Built-in)  | 1         | 1.32%   |
| Acer ThinkPad P50 Integrated Camera  | 1         | 1.32%   |
| Acer SunplusIT Integrated Camera     | 1         | 1.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 50%     |
| Validity Sensors           | 5         | 25%     |
| Shenzhen Goodix Technology | 4         | 20%     |
| Gingytech                  | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 5         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 4         | 20%     |
| Shenzhen Goodix Fingerprint Reader                | 3         | 15%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 5%      |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5%      |
| Shenzhen Goodix  Fingerprint Device               | 1         | 5%      |
| Gingytech Fingerprint sensor                      | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 9         | 75%     |
| Yubico.com  | 1         | 8.33%   |
| Upek        | 1         | 8.33%   |
| Broadcom    | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 9         | 75%     |
| Yubico.com Yubikey 4 U2F+CCID                              | 1         | 8.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 70        | 56%     |
| 1     | 34        | 27.2%   |
| 2     | 18        | 14.4%   |
| 4     | 2         | 1.6%    |
| 3     | 1         | 0.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 22.78%  |
| Graphics card            | 15        | 18.99%  |
| Multimedia controller    | 14        | 17.72%  |
| Chipcard                 | 10        | 12.66%  |
| Net/wireless             | 6         | 7.59%   |
| Unassigned class         | 3         | 3.8%    |
| Camera                   | 3         | 3.8%    |
| Bluetooth                | 3         | 3.8%    |
| Modem                    | 2         | 2.53%   |
| Storage/ata              | 1         | 1.27%   |
| Network                  | 1         | 1.27%   |
| Dvb card                 | 1         | 1.27%   |
| Communication controller | 1         | 1.27%   |
| Card reader              | 1         | 1.27%   |

