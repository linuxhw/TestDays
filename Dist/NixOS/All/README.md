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

Total: 156

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| NixOS 22.05                      | 37        | 30.83%  |
| NixOS 22.11                      | 26        | 21.67%  |
| NixOS 21.11                      | 18        | 15%     |
| NixOS                            | 5         | 4.17%   |
| NixOS 23.05                      | 4         | 3.33%   |
| NixOS 21.05pre-git               | 2         | 1.67%   |
| NixOS 20.09pre-git               | 2         | 1.67%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.83%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.83%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.83%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.83%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.83%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.83%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.83%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.83%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.83%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.83%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.83%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.83%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.83%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.83%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.83%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.83%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.83%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.83%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.83%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.83%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.83%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.83%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.83%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.83%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.83%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 107       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 5.15.74          | 5         | 3.97%   |
| 5.15.43          | 4         | 3.17%   |
| 6.1.0            | 3         | 2.38%   |
| 6.0.11           | 3         | 2.38%   |
| 6.0.10           | 3         | 2.38%   |
| 5.15.72          | 3         | 2.38%   |
| 5.15.68          | 3         | 2.38%   |
| 5.15.47          | 3         | 2.38%   |
| 5.15.26          | 3         | 2.38%   |
| 5.8.1-zen1       | 2         | 1.59%   |
| 5.19.14          | 2         | 1.59%   |
| 5.18.19          | 2         | 1.59%   |
| 5.17.1           | 2         | 1.59%   |
| 5.16.8-zen1      | 2         | 1.59%   |
| 5.16.15          | 2         | 1.59%   |
| 5.15.64          | 2         | 1.59%   |
| 5.15.32          | 2         | 1.59%   |
| 5.15.25          | 2         | 1.59%   |
| 5.13.7           | 2         | 1.59%   |
| 5.13.2           | 2         | 1.59%   |
| 5.12.15          | 2         | 1.59%   |
| 5.10.102         | 2         | 1.59%   |
| 6.1.0-zen1       | 1         | 0.79%   |
| 6.0.8-zen1       | 1         | 0.79%   |
| 6.0.6            | 1         | 0.79%   |
| 6.0.2-xanmod1-tt | 1         | 0.79%   |
| 6.0.2            | 1         | 0.79%   |
| 6.0.12           | 1         | 0.79%   |
| 6.0.10-zen2      | 1         | 0.79%   |
| 6.0.0-xanmod1    | 1         | 0.79%   |
| 5.8.4            | 1         | 0.79%   |
| 5.8.16-hardened  | 1         | 0.79%   |
| 5.8.11           | 1         | 0.79%   |
| 5.8.10           | 1         | 0.79%   |
| 5.7.4            | 1         | 0.79%   |
| 5.7.19           | 1         | 0.79%   |
| 5.7.17           | 1         | 0.79%   |
| 5.4.94           | 1         | 0.79%   |
| 5.4.72           | 1         | 0.79%   |
| 5.4.69           | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.74  | 5         | 3.97%   |
| 6.1.0    | 4         | 3.17%   |
| 6.0.10   | 4         | 3.17%   |
| 5.15.43  | 4         | 3.17%   |
| 6.0.11   | 3         | 2.38%   |
| 5.15.72  | 3         | 2.38%   |
| 5.15.68  | 3         | 2.38%   |
| 5.15.47  | 3         | 2.38%   |
| 5.15.26  | 3         | 2.38%   |
| 6.0.2    | 2         | 1.59%   |
| 5.8.1    | 2         | 1.59%   |
| 5.19.14  | 2         | 1.59%   |
| 5.18.19  | 2         | 1.59%   |
| 5.17.1   | 2         | 1.59%   |
| 5.16.8   | 2         | 1.59%   |
| 5.16.15  | 2         | 1.59%   |
| 5.15.64  | 2         | 1.59%   |
| 5.15.32  | 2         | 1.59%   |
| 5.15.25  | 2         | 1.59%   |
| 5.13.7   | 2         | 1.59%   |
| 5.13.2   | 2         | 1.59%   |
| 5.12.15  | 2         | 1.59%   |
| 5.11.16  | 2         | 1.59%   |
| 5.10.102 | 2         | 1.59%   |
| 6.0.8    | 1         | 0.79%   |
| 6.0.6    | 1         | 0.79%   |
| 6.0.12   | 1         | 0.79%   |
| 6.0.0    | 1         | 0.79%   |
| 5.8.4    | 1         | 0.79%   |
| 5.8.16   | 1         | 0.79%   |
| 5.8.11   | 1         | 0.79%   |
| 5.8.10   | 1         | 0.79%   |
| 5.7.4    | 1         | 0.79%   |
| 5.7.19   | 1         | 0.79%   |
| 5.7.17   | 1         | 0.79%   |
| 5.4.94   | 1         | 0.79%   |
| 5.4.72   | 1         | 0.79%   |
| 5.4.69   | 1         | 0.79%   |
| 5.4.50   | 1         | 0.79%   |
| 5.4.47   | 1         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 40        | 32.52%  |
| 5.10    | 14        | 11.38%  |
| 6.0     | 13        | 10.57%  |
| 5.16    | 8         | 6.5%    |
| 5.4     | 7         | 5.69%   |
| 5.19    | 7         | 5.69%   |
| 5.8     | 6         | 4.88%   |
| 5.18    | 5         | 4.07%   |
| 6.1     | 4         | 3.25%   |
| 5.13    | 4         | 3.25%   |
| 5.7     | 3         | 2.44%   |
| 5.17    | 3         | 2.44%   |
| 5.12    | 3         | 2.44%   |
| 5.14    | 2         | 1.63%   |
| 5.11    | 2         | 1.63%   |
| 4.19    | 2         | 1.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 103       | 96.26%  |
| aarch64 | 4         | 3.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 78        | 70.91%  |
| GNOME        | 7         | 6.36%   |
| XFCE         | 6         | 5.45%   |
| sway         | 6         | 5.45%   |
| KDE5         | 4         | 3.64%   |
| KDE          | 4         | 3.64%   |
| none+xmonad  | 2         | 1.82%   |
| none+i3      | 1         | 0.91%   |
| none+bspwm   | 1         | 0.91%   |
| none+awesome | 1         | 0.91%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 71        | 62.83%  |
| X11     | 20        | 17.7%   |
| Wayland | 12        | 10.62%  |
| Tty     | 10        | 8.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 81        | 75%     |
| LightDM | 11        | 10.19%  |
| SDDM    | 9         | 8.33%   |
| GDM     | 7         | 6.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 53        | 49.53%  |
| en_US   | 37        | 34.58%  |
| en_GB   | 3         | 2.8%    |
| ru_RU   | 2         | 1.87%   |
| fr_FR   | 2         | 1.87%   |
| en_DK   | 2         | 1.87%   |
| en_AU   | 2         | 1.87%   |
| de_CH   | 2         | 1.87%   |
| ro_RO   | 1         | 0.93%   |
| pt_BR   | 1         | 0.93%   |
| it_IT   | 1         | 0.93%   |
| de_DE   | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 92        | 84.4%   |
| BIOS | 17        | 15.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 52        | 47.27%  |
| Btrfs   | 20        | 18.18%  |
| Zfs     | 11        | 10%     |
| Xfs     | 10        | 9.09%   |
| Tmpfs   | 10        | 9.09%   |
| Unknown | 6         | 5.45%   |
| Ext2    | 1         | 0.91%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 100       | 91.74%  |
| Unknown | 8         | 7.34%   |
| MBR     | 1         | 0.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 71.82%  |
| Yes       | 31        | 28.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 64.49%  |
| Yes       | 38        | 35.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 23        | 21.5%   |
| Lenovo                  | 22        | 20.56%  |
| Dell                    | 16        | 14.95%  |
| MSI                     | 9         | 8.41%   |
| Hewlett-Packard         | 7         | 6.54%   |
| Gigabyte Technology     | 5         | 4.67%   |
| ASRock                  | 4         | 3.74%   |
| Acer                    | 3         | 2.8%    |
| Raspberry Pi Foundation | 2         | 1.87%   |
| Pine Microsystems       | 2         | 1.87%   |
| GPD                     | 2         | 1.87%   |
| Framework               | 2         | 1.87%   |
| Apple                   | 2         | 1.87%   |
| Toshiba                 | 1         | 0.93%   |
| Teclast                 | 1         | 0.93%   |
| Supermicro              | 1         | 0.93%   |
| OBSIDIAN-PC             | 1         | 0.93%   |
| MECHREVO                | 1         | 0.93%   |
| Intel                   | 1         | 0.93%   |
| Hardkernel              | 1         | 0.93%   |
| EVGA                    | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Pine Microsystems Pine64 PinePhone (1.2) | 2         | 1.87%   |
| MSI MS-7C37                              | 2         | 1.87%   |
| Dell Latitude 7420                       | 2         | 1.87%   |
| ASUS All Series                          | 2         | 1.87%   |
| Toshiba Satellite L50-B                  | 1         | 0.93%   |
| Teclast F5                               | 1         | 0.93%   |
| Supermicro X8DT6                         | 1         | 0.93%   |
| RPi Raspberry Pi 4 Model B Rev 1.2       | 1         | 0.93%   |
| RPi Raspberry Pi 3 Model B+              | 1         | 0.93%   |
| OBSIDIAN-PC N13_N140ZU                   | 1         | 0.93%   |
| MSI MS-7C95                              | 1         | 0.93%   |
| MSI MS-7C84                              | 1         | 0.93%   |
| MSI MS-7C56                              | 1         | 0.93%   |
| MSI MS-7C35                              | 1         | 0.93%   |
| MSI MS-7B89                              | 1         | 0.93%   |
| MSI MS-7B09                              | 1         | 0.93%   |
| MSI Bravo 15 B5DD                        | 1         | 0.93%   |
| MECHREVO Code01 Ver2.0                   | 1         | 0.93%   |
| Lenovo Yoga Slim 7 13ACN5 82CY           | 1         | 0.93%   |
| Lenovo Yoga 520-14IKB 81C8               | 1         | 0.93%   |
| Lenovo ThinkPad X390 20Q0CTO1WW          | 1         | 0.93%   |
| Lenovo ThinkPad X260 20F5S6MF02          | 1         | 0.93%   |
| Lenovo ThinkPad X260 20F5S4BY00          | 1         | 0.93%   |
| Lenovo ThinkPad X250 20CLS18S0T          | 1         | 0.93%   |
| Lenovo ThinkPad X230 23243E9             | 1         | 0.93%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 0.93%   |
| Lenovo ThinkPad T580 20L90024PB          | 1         | 0.93%   |
| Lenovo ThinkPad T540p 20BE005YMH         | 1         | 0.93%   |
| Lenovo ThinkPad T490 20N2000LUK          | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L5CTO1WW          | 1         | 0.93%   |
| Lenovo ThinkPad T460p 20FWCTO1WW         | 1         | 0.93%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW     | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 3 21BR000MUS    | 1         | 0.93%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK    | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT     | 1         | 0.93%   |
| Lenovo ThinkPad E470 20H1006JIX          | 1         | 0.93%   |
| Lenovo Legion S7 15ACH6 82K8             | 1         | 0.93%   |
| Lenovo Legion 5 17ARH05H 82GN            | 1         | 0.93%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS        | 1         | 0.93%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 16        | 14.95%  |
| ASUS ROG                 | 6         | 5.61%   |
| Dell XPS                 | 5         | 4.67%   |
| ASUS PRIME               | 5         | 4.67%   |
| Dell Inspiron            | 4         | 3.74%   |
| Dell Precision           | 3         | 2.8%    |
| Dell Latitude            | 3         | 2.8%    |
| RPi Raspberry            | 2         | 1.87%   |
| Pine Microsystems Pine64 | 2         | 1.87%   |
| MSI MS-7C37              | 2         | 1.87%   |
| Lenovo Yoga              | 2         | 1.87%   |
| Lenovo Legion            | 2         | 1.87%   |
| HP ProBook               | 2         | 1.87%   |
| Framework Laptop         | 2         | 1.87%   |
| ASUS Zenbook             | 2         | 1.87%   |
| ASUS All                 | 2         | 1.87%   |
| Acer Aspire              | 2         | 1.87%   |
| Toshiba Satellite        | 1         | 0.93%   |
| Teclast F5               | 1         | 0.93%   |
| Supermicro X8DT6         | 1         | 0.93%   |
| OBSIDIAN-PC N13          | 1         | 0.93%   |
| MSI MS-7C95              | 1         | 0.93%   |
| MSI MS-7C84              | 1         | 0.93%   |
| MSI MS-7C56              | 1         | 0.93%   |
| MSI MS-7C35              | 1         | 0.93%   |
| MSI MS-7B89              | 1         | 0.93%   |
| MSI MS-7B09              | 1         | 0.93%   |
| MSI Bravo                | 1         | 0.93%   |
| MECHREVO Code01          | 1         | 0.93%   |
| Lenovo IdeaPadFlex       | 1         | 0.93%   |
| Lenovo IdeaPad           | 1         | 0.93%   |
| Intel NUC11PAHi7         | 1         | 0.93%   |
| HP ZBook                 | 1         | 0.93%   |
| HP Spectre               | 1         | 0.93%   |
| HP ENVY                  | 1         | 0.93%   |
| HP EliteDesk             | 1         | 0.93%   |
| HP EliteBook             | 1         | 0.93%   |
| Hardkernel ODROID-H2     | 1         | 0.93%   |
| GPD WIN2                 | 1         | 0.93%   |
| GPD MicroPC              | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 22        | 20.56%  |
| 2019    | 20        | 18.69%  |
| 2021    | 13        | 12.15%  |
| 2018    | 12        | 11.21%  |
| 2016    | 10        | 9.35%   |
| 2017    | 6         | 5.61%   |
| 2022    | 4         | 3.74%   |
| 2015    | 4         | 3.74%   |
| 2014    | 4         | 3.74%   |
| 2013    | 4         | 3.74%   |
| Unknown | 4         | 3.74%   |
| 2012    | 3         | 2.8%    |
| 2010    | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 53        | 49.53%  |
| Desktop        | 38        | 35.51%  |
| Convertible    | 8         | 7.48%   |
| Phone          | 2         | 1.87%   |
| System on chip | 2         | 1.87%   |
| Server         | 2         | 1.87%   |
| Mini pc        | 1         | 0.93%   |
| All in one     | 1         | 0.93%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 107       | 99.07%  |
| Enabled  | 1         | 0.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 106       | 99.07%  |
| Yes  | 1         | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 31        | 28.44%  |
| 16.01-24.0  | 24        | 22.02%  |
| 8.01-16.0   | 18        | 16.51%  |
| 64.01-256.0 | 15        | 13.76%  |
| 4.01-8.0    | 8         | 7.34%   |
| 24.01-32.0  | 6         | 5.5%    |
| 3.01-4.0    | 5         | 4.59%   |
| 1.01-2.0    | 1         | 0.92%   |
| 0.51-1.0    | 1         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 26.27%  |
| 8.01-16.0   | 22        | 18.64%  |
| 2.01-3.0    | 16        | 13.56%  |
| 3.01-4.0    | 15        | 12.71%  |
| 1.01-2.0    | 11        | 9.32%   |
| 32.01-64.0  | 6         | 5.08%   |
| 24.01-32.0  | 5         | 4.24%   |
| 16.01-24.0  | 5         | 4.24%   |
| 0.51-1.0    | 5         | 4.24%   |
| 64.01-256.0 | 1         | 0.85%   |
| 0.01-0.5    | 1         | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 57        | 51.35%  |
| 2      | 32        | 28.83%  |
| 3      | 9         | 8.11%   |
| 6      | 4         | 3.6%    |
| 5      | 3         | 2.7%    |
| 23     | 1         | 0.9%    |
| 17     | 1         | 0.9%    |
| 11     | 1         | 0.9%    |
| 8      | 1         | 0.9%    |
| 4      | 1         | 0.9%    |
| 0      | 1         | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 96        | 89.72%  |
| Yes       | 11        | 10.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 77.06%  |
| No        | 25        | 22.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 70.09%  |
| No        | 32        | 29.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 67.89%  |
| No        | 35        | 32.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 17        | 15.89%  |
| Germany     | 13        | 12.15%  |
| France      | 9         | 8.41%   |
| UK          | 8         | 7.48%   |
| Poland      | 7         | 6.54%   |
| Canada      | 7         | 6.54%   |
| Russia      | 6         | 5.61%   |
| Ukraine     | 5         | 4.67%   |
| Italy       | 4         | 3.74%   |
| Switzerland | 3         | 2.8%    |
| Czechia     | 3         | 2.8%    |
| Austria     | 3         | 2.8%    |
| Netherlands | 2         | 1.87%   |
| Denmark     | 2         | 1.87%   |
| Belgium     | 2         | 1.87%   |
| Australia   | 2         | 1.87%   |
| Uruguay     | 1         | 0.93%   |
| Sweden      | 1         | 0.93%   |
| Spain       | 1         | 0.93%   |
| Serbia      | 1         | 0.93%   |
| Romania     | 1         | 0.93%   |
| Portugal    | 1         | 0.93%   |
| New Zealand | 1         | 0.93%   |
| Iraq        | 1         | 0.93%   |
| Iran        | 1         | 0.93%   |
| India       | 1         | 0.93%   |
| Hungary     | 1         | 0.93%   |
| Colombia    | 1         | 0.93%   |
| China       | 1         | 0.93%   |
| Brazil      | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Marki              | 4         | 3.45%   |
| Frankfurt am Main  | 4         | 3.45%   |
| Vienna             | 3         | 2.59%   |
| Plymouth           | 3         | 2.59%   |
| Kharkiv            | 3         | 2.59%   |
| South Deerfield    | 2         | 1.72%   |
| Schaafheim         | 2         | 1.72%   |
| Richardson         | 2         | 1.72%   |
| Prague             | 2         | 1.72%   |
| Ottawa             | 2         | 1.72%   |
| Milwaukee          | 2         | 1.72%   |
| Melbourne          | 2         | 1.72%   |
| Lyon               | 2         | 1.72%   |
| London             | 2         | 1.72%   |
| Halifax            | 2         | 1.72%   |
| Gdansk             | 2         | 1.72%   |
| Darmstadt          | 2         | 1.72%   |
| Chelyabinsk        | 2         | 1.72%   |
| Yangzhou           | 1         | 0.86%   |
| Woodford           | 1         | 0.86%   |
| Wellington         | 1         | 0.86%   |
| Villeurbanne       | 1         | 0.86%   |
| Verneuil-sur-Seine | 1         | 0.86%   |
| Valpacos           | 1         | 0.86%   |
| Trento             | 1         | 0.86%   |
| Tottenham          | 1         | 0.86%   |
| Tolyatti           | 1         | 0.86%   |
| Tehran             | 1         | 0.86%   |
| Székesfehérvár  | 1         | 0.86%   |
| Stockholm          | 1         | 0.86%   |
| Southampton        | 1         | 0.86%   |
| Sindelfingen       | 1         | 0.86%   |
| Saratov            | 1         | 0.86%   |
| San Gabriel        | 1         | 0.86%   |
| Saarlouis          | 1         | 0.86%   |
| Saarbrücken       | 1         | 0.86%   |
| Riegelsberg        | 1         | 0.86%   |
| Rho                | 1         | 0.86%   |
| Redwood City       | 1         | 0.86%   |
| Ramenskoye         | 1         | 0.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 46        | 99     | 27.38%  |
| WDC                         | 14        | 33     | 8.33%   |
| SanDisk                     | 14        | 20     | 8.33%   |
| Toshiba                     | 13        | 26     | 7.74%   |
| Seagate                     | 13        | 37     | 7.74%   |
| Crucial                     | 9         | 11     | 5.36%   |
| Kingston                    | 8         | 8      | 4.76%   |
| Intel                       | 8         | 11     | 4.76%   |
| SK hynix                    | 6         | 9      | 3.57%   |
| Unknown                     | 5         | 8      | 2.98%   |
| HGST                        | 3         | 13     | 1.79%   |
| Transcend                   | 2         | 2      | 1.19%   |
| Plextor                     | 2         | 2      | 1.19%   |
| Phison Electronics          | 2         | 4      | 1.19%   |
| Micron Technology           | 2         | 2      | 1.19%   |
| KIOXIA                      | 2         | 3      | 1.19%   |
| Kingston Technology Company | 2         | 2      | 1.19%   |
| Apple                       | 2         | 5      | 1.19%   |
| Yangtze Memory Technologies | 1         | 1      | 0.6%    |
| Teclast                     | 1         | 1      | 0.6%    |
| SPCC                        | 1         | 1      | 0.6%    |
| Phison                      | 1         | 1      | 0.6%    |
| OCZ                         | 1         | 1      | 0.6%    |
| Lexar                       | 1         | 1      | 0.6%    |
| INNOVATION IT               | 1         | 1      | 0.6%    |
| Hitachi                     | 1         | 3      | 0.6%    |
| Dogfish                     | 1         | 1      | 0.6%    |
| China                       | 1         | 1      | 0.6%    |
| BIWIN                       | 1         | 1      | 0.6%    |
| ASMT                        | 1         | 1      | 0.6%    |
| ASMedia                     | 1         | 1      | 0.6%    |
| ADATA Technology            | 1         | 2      | 0.6%    |
| Unknown                     | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB                 | 5         | 2.4%    |
| Unknown MMC Card  32GB                  | 3         | 1.44%   |
| Seagate ST3000DM001-1ER166 3TB          | 3         | 1.44%   |
| SanDisk SSD PLUS 240GB                  | 3         | 1.44%   |
| Samsung SSD 970 EVO Plus 2TB            | 3         | 1.44%   |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 1.44%   |
| Samsung SSD 970 EVO 500GB               | 3         | 1.44%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 1.44%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB | 2         | 0.96%   |
| Seagate ST3000DM001-1CH166 3TB          | 2         | 0.96%   |
| SanDisk Ultra II 240GB SSD              | 2         | 0.96%   |
| SanDisk NVMe SSD Drive 1TB              | 2         | 0.96%   |
| Samsung SSD 980 PRO 1TB                 | 2         | 0.96%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.96%   |
| Samsung SSD 870 EVO 1TB                 | 2         | 0.96%   |
| Samsung SSD 860 QVO 1TB                 | 2         | 0.96%   |
| Samsung SSD 860 EVO 500GB               | 2         | 0.96%   |
| Samsung SSD 860 EVO 2TB                 | 2         | 0.96%   |
| Samsung SSD 850 EVO 500GB               | 2         | 0.96%   |
| Samsung PM9A1 NVMe 1024GB               | 2         | 0.96%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.96%   |
| Kingston SA400S37960G 960GB SSD         | 2         | 0.96%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.96%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB    | 1         | 0.48%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD        | 1         | 0.48%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.48%   |
| WDC WDS200T1X0E-00AFY0 2TB              | 1         | 0.48%   |
| WDC WD80EDAZ-11TA3A0 8TB                | 1         | 0.48%   |
| WDC WD50EZRX-00MVLB1 5TB                | 1         | 0.48%   |
| WDC WD40EFRX-68N32N0 4TB                | 1         | 0.48%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.48%   |
| WDC WD20EZRX-00D8PB0 2TB                | 1         | 0.48%   |
| WDC WD120EMFZ-11A6JA0 12TB              | 1         | 0.48%   |
| WDC WD10EZEX-21WN4A0 1TB                | 1         | 0.48%   |
| WDC WD10EZEX-00RKKA0 1TB                | 1         | 0.48%   |
| WDC WD10EZEX-00KUWA0 1TB                | 1         | 0.48%   |
| WDC WD10EAVS-32D7B1 1TB                 | 1         | 0.48%   |
| WDC WD10EAVS-00D7B0 1TB                 | 1         | 0.48%   |
| WDC WD10EARS-00Y5B1 1TB                 | 1         | 0.48%   |
| WDC WD10EADS-00M2B0 1TB                 | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 37     | 35.14%  |
| Toshiba             | 9         | 19     | 24.32%  |
| WDC                 | 8         | 25     | 21.62%  |
| HGST                | 3         | 13     | 8.11%   |
| Samsung Electronics | 1         | 1      | 2.7%    |
| Hitachi             | 1         | 3      | 2.7%    |
| ASMT                | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 54     | 33.33%  |
| SanDisk             | 8         | 13     | 12.12%  |
| Crucial             | 8         | 10     | 12.12%  |
| Kingston            | 5         | 5      | 7.58%   |
| Intel               | 5         | 7      | 7.58%   |
| WDC                 | 2         | 3      | 3.03%   |
| Transcend           | 2         | 2      | 3.03%   |
| Apple               | 2         | 4      | 3.03%   |
| Toshiba             | 1         | 1      | 1.52%   |
| Teclast             | 1         | 1      | 1.52%   |
| SPCC                | 1         | 1      | 1.52%   |
| SK hynix            | 1         | 1      | 1.52%   |
| Plextor             | 1         | 1      | 1.52%   |
| OCZ                 | 1         | 1      | 1.52%   |
| Micron Technology   | 1         | 1      | 1.52%   |
| INNOVATION IT       | 1         | 1      | 1.52%   |
| Dogfish             | 1         | 1      | 1.52%   |
| China               | 1         | 1      | 1.52%   |
| BIWIN               | 1         | 1      | 1.52%   |
| ASMedia             | 1         | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 64        | 94     | 43.24%  |
| SSD  | 54        | 110    | 36.49%  |
| HDD  | 25        | 100    | 16.89%  |
| MMC  | 5         | 9      | 3.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 64        | 94     | 48.12%  |
| SATA | 59        | 202    | 44.36%  |
| SAS  | 5         | 8      | 3.76%   |
| MMC  | 5         | 9      | 3.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 79     | 45.16%  |
| 0.51-1.0   | 27        | 52     | 29.03%  |
| 1.01-2.0   | 9         | 14     | 9.68%   |
| 2.01-3.0   | 6         | 12     | 6.45%   |
| 4.01-10.0  | 6         | 43     | 6.45%   |
| 3.01-4.0   | 2         | 4      | 2.15%   |
| 10.01-20.0 | 1         | 6      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 59        | 53.64%  |
| 1-20           | 18        | 16.36%  |
| 501-1000       | 7         | 6.36%   |
| 2001-3000      | 6         | 5.45%   |
| 101-250        | 6         | 5.45%   |
| 251-500        | 5         | 4.55%   |
| 1001-2000      | 4         | 3.64%   |
| More than 3000 | 3         | 2.73%   |
| 21-50          | 2         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 59        | 53.64%  |
| 1-20           | 26        | 23.64%  |
| 101-250        | 9         | 8.18%   |
| 251-500        | 6         | 5.45%   |
| 1001-2000      | 3         | 2.73%   |
| 501-1000       | 3         | 2.73%   |
| More than 3000 | 1         | 0.91%   |
| 21-50          | 1         | 0.91%   |
| 2001-3000      | 1         | 0.91%   |
| 51-100         | 1         | 0.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 9.09%   |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 9.09%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 9.09%   |
| Seagate ST8000VN004-2M2101 8TB                 | 1         | 3      | 9.09%   |
| SanDisk SSD PLUS 240GB                         | 1         | 3      | 9.09%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 870 EVO 1TB            | 1         | 1      | 9.09%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 9.09%   |
| Intel SSDSC2BW240A4 240GB                      | 1         | 1      | 9.09%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 9.09%   |
| ASMT 2115 320GB                                | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 18.18%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| SK hynix            | 1         | 1      | 9.09%   |
| Seagate             | 1         | 3      | 9.09%   |
| SanDisk             | 1         | 3      | 9.09%   |
| Micron Technology   | 1         | 1      | 9.09%   |
| Intel               | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |
| ASMT                | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 40%     |
| Seagate | 1         | 3      | 20%     |
| Hitachi | 1         | 1      | 20%     |
| ASMT    | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 7      | 45.45%  |
| SSD  | 4         | 6      | 36.36%  |
| NVMe | 2         | 2      | 18.18%  |

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
| Works    | 98        | 264    | 78.4%   |
| Detected | 17        | 33     | 13.6%   |
| Malfunc  | 9         | 15     | 7.2%    |
| Failed   | 1         | 1      | 0.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 53        | 33.97%  |
| Samsung Electronics          | 31        | 19.87%  |
| AMD                          | 26        | 16.67%  |
| SanDisk                      | 11        | 7.05%   |
| Kingston Technology Company  | 6         | 3.85%   |
| SK hynix                     | 5         | 3.21%   |
| Toshiba America Info Systems | 4         | 2.56%   |
| ASMedia Technology           | 4         | 2.56%   |
| Phison Electronics           | 3         | 1.92%   |
| Broadcom / LSI               | 3         | 1.92%   |
| LSI Logic / Symbios Logic    | 2         | 1.28%   |
| KIOXIA                       | 2         | 1.28%   |
| Yangtze Memory Technologies  | 1         | 0.64%   |
| Shenzhen Longsys Electronics | 1         | 0.64%   |
| Micron/Crucial Technology    | 1         | 0.64%   |
| Micron Technology            | 1         | 0.64%   |
| Lite-On Technology           | 1         | 0.64%   |
| ADATA Technology             | 1         | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 20        | 12.12%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 10.3%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 4.24%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 4.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 3.64%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 3.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.42%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 2.42%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.82%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.82%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.82%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.82%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.21%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.21%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 1.21%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.21%   |
| Samsung Electronics SATA controller                                            | 2         | 1.21%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.21%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.21%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.21%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.21%   |
| Intel Comet Lake PCH-H RAID                                                    | 2         | 1.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.21%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.21%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 1.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.21%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 2         | 1.21%   |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 0.61%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.61%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.61%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                    | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 66        | 44.3%   |
| NVMe | 65        | 43.62%  |
| RAID | 10        | 6.71%   |
| SAS  | 5         | 3.36%   |
| IDE  | 3         | 2.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 67        | 62.62%  |
| AMD    | 36        | 33.64%  |
| ARM    | 4         | 3.74%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor          | 5         | 4.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 3.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 3.74%   |
| ARM Processor                              | 4         | 3.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 3         | 2.8%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 3         | 2.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 3         | 2.8%    |
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 2.8%    |
| AMD Ryzen 7 3800X 8-Core Processor         | 3         | 2.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 1.87%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 1.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 1.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 1.87%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 2         | 1.87%   |
| Intel 12th Gen Core i5-1240P               | 2         | 1.87%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 2         | 1.87%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 1.87%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 2         | 1.87%   |
| Intel Xeon W-1290P CPU @ 3.70GHz           | 1         | 0.93%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 0.93%   |
| Intel Xeon CPU L5640 @ 2.27GHz             | 1         | 0.93%   |
| Intel Xeon CPU E5606 @ 2.13GHz             | 1         | 0.93%   |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz        | 1         | 0.93%   |
| Intel Core m3-8100Y CPU @ 1.10GHz          | 1         | 0.93%   |
| Intel Core i9-9980HK CPU @ 2.40GHz         | 1         | 0.93%   |
| Intel Core i9-9900X CPU @ 3.50GHz          | 1         | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 0.93%   |
| Intel Core i7-6850K CPU @ 3.60GHz          | 1         | 0.93%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 0.93%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 0.93%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 0.93%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 0.93%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz         | 1         | 0.93%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 0.93%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 1         | 0.93%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 1         | 0.93%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 1         | 0.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 1         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 0.93%   |
| Intel Core i5-7600K CPU @ 3.80GHz          | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 28        | 26.17%  |
| Other                  | 16        | 14.95%  |
| AMD Ryzen 7            | 15        | 14.02%  |
| Intel Core i5          | 13        | 12.15%  |
| AMD Ryzen 5            | 9         | 8.41%   |
| AMD Ryzen 9            | 6         | 5.61%   |
| Intel Xeon             | 5         | 4.67%   |
| Intel Core i3          | 3         | 2.8%    |
| Intel Celeron          | 3         | 2.8%    |
| AMD Ryzen 7 PRO        | 3         | 2.8%    |
| Intel Core i9          | 2         | 1.87%   |
| AMD Ryzen Threadripper | 2         | 1.87%   |
| Intel Core m3          | 1         | 0.93%   |
| AMD FX                 | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 35        | 32.71%  |
| 8       | 23        | 21.5%   |
| 6       | 17        | 15.89%  |
| 2       | 15        | 14.02%  |
| 12      | 7         | 6.54%   |
| Unknown | 4         | 3.74%   |
| 16      | 2         | 1.87%   |
| 10      | 2         | 1.87%   |
| 32      | 1         | 0.93%   |
| 24      | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 101       | 94.39%  |
| Unknown | 4         | 3.74%   |
| 2       | 2         | 1.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 93        | 86.92%  |
| 1       | 10        | 9.35%   |
| Unknown | 4         | 3.74%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 107       | 99.07%  |
| Unknown        | 1         | 0.93%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 17.43%  |
| 0x0a50000c | 7         | 6.42%   |
| 0x08701021 | 7         | 6.42%   |
| 0x806c1    | 6         | 5.5%    |
| 0x806ea    | 5         | 4.59%   |
| 0x306c3    | 5         | 4.59%   |
| 0x906ea    | 4         | 3.67%   |
| 0x806ec    | 4         | 3.67%   |
| 0x506e3    | 4         | 3.67%   |
| 0x08701013 | 4         | 3.67%   |
| 0x906a3    | 3         | 2.75%   |
| 0x806eb    | 3         | 2.75%   |
| 0x306a9    | 3         | 2.75%   |
| 0x08600106 | 3         | 2.75%   |
| 0x906e9    | 2         | 1.83%   |
| 0x806e9    | 2         | 1.83%   |
| 0x706a1    | 2         | 1.83%   |
| 0x406e3    | 2         | 1.83%   |
| 0x306d4    | 2         | 1.83%   |
| 0x0a50000d | 2         | 1.83%   |
| 0x0a201204 | 2         | 1.83%   |
| 0x0a201009 | 2         | 1.83%   |
| 0xa0653    | 1         | 0.92%   |
| 0xa0652    | 1         | 0.92%   |
| 0x906ed    | 1         | 0.92%   |
| 0x806d1    | 1         | 0.92%   |
| 0x406f1    | 1         | 0.92%   |
| 0x40661    | 1         | 0.92%   |
| 0x40651    | 1         | 0.92%   |
| 0x306f2    | 1         | 0.92%   |
| 0x206c2    | 1         | 0.92%   |
| 0x0a50000b | 1         | 0.92%   |
| 0x0a404102 | 1         | 0.92%   |
| 0x08600104 | 1         | 0.92%   |
| 0x08301025 | 1         | 0.92%   |
| 0x0800820d | 1         | 0.92%   |
| 0x08001137 | 1         | 0.92%   |
| 0x06000852 | 1         | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 24        | 22.43%  |
| Zen 2            | 17        | 15.89%  |
| Zen 3            | 14        | 13.08%  |
| Skylake          | 9         | 8.41%   |
| Haswell          | 8         | 7.48%   |
| TigerLake        | 7         | 6.54%   |
| Unknown          | 6         | 5.61%   |
| IvyBridge        | 3         | 2.8%    |
| Goldmont plus    | 3         | 2.8%    |
| CometLake        | 3         | 2.8%    |
| Broadwell        | 3         | 2.8%    |
| Alderlake Hybrid | 3         | 2.8%    |
| Zen+             | 2         | 1.87%   |
| Westmere         | 2         | 1.87%   |
| Zen              | 1         | 0.93%   |
| Piledriver       | 1         | 0.93%   |
| Icelake          | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 54        | 40.91%  |
| Nvidia                     | 44        | 33.33%  |
| AMD                        | 32        | 24.24%  |
| Matrox Electronics Systems | 2         | 1.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 10        | 7.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 4.51%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 6         | 4.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 3.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 5         | 3.76%   |
| Intel UHD Graphics 620                                                                | 4         | 3.01%   |
| Intel HD Graphics 530                                                                 | 4         | 3.01%   |
| AMD Renoir                                                                            | 4         | 3.01%   |
| Nvidia GP108M [GeForce MX150]                                                         | 3         | 2.26%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 2.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 2.26%   |
| Intel HD Graphics 620                                                                 | 3         | 2.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 2.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 2.26%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 3         | 2.26%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 2         | 1.5%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 1.5%    |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.5%    |
| Nvidia GK104 [GeForce GTX 760]                                                        | 2         | 1.5%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 1.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 1.5%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                         | 2         | 1.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 1.5%    |
| Intel HD Graphics 630                                                                 | 2         | 1.5%    |
| Intel HD Graphics 5500                                                                | 2         | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 1.5%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                              | 2         | 1.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                    | 1         | 0.75%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                 | 1         | 0.75%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                 | 1         | 0.75%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                 | 1         | 0.75%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                                       | 1         | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 1         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 30.84%  |
| 1 x AMD        | 20        | 18.69%  |
| Intel + Nvidia | 18        | 16.82%  |
| 1 x Nvidia     | 17        | 15.89%  |
| AMD + Nvidia   | 9         | 8.41%   |
| Other          | 5         | 4.67%   |
| 1 x Matrox     | 2         | 1.87%   |
| Intel + AMD    | 2         | 1.87%   |
| 2 x AMD        | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 74        | 68.52%  |
| Proprietary | 25        | 23.15%  |
| Unknown     | 9         | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 64.55%  |
| 7.01-8.0   | 10        | 9.09%   |
| 0.01-0.5   | 10        | 9.09%   |
| 1.01-2.0   | 9         | 8.18%   |
| 3.01-4.0   | 8         | 7.27%   |
| 8.01-16.0  | 1         | 0.91%   |
| 0.51-1.0   | 1         | 0.91%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Dell                 | 20        | 17.39%  |
| AU Optronics         | 13        | 11.3%   |
| Goldstar             | 10        | 8.7%    |
| Samsung Electronics  | 9         | 7.83%   |
| BOE                  | 9         | 7.83%   |
| LG Display           | 8         | 6.96%   |
| Chimei Innolux       | 6         | 5.22%   |
| Acer                 | 5         | 4.35%   |
| Sharp                | 4         | 3.48%   |
| PANDA                | 4         | 3.48%   |
| Hewlett-Packard      | 3         | 2.61%   |
| CSO                  | 3         | 2.61%   |
| Ancor Communications | 3         | 2.61%   |
| InfoVision           | 2         | 1.74%   |
| Apple                | 2         | 1.74%   |
| AOC                  | 2         | 1.74%   |
| Vizio                | 1         | 0.87%   |
| Unknown (AAA)        | 1         | 0.87%   |
| Philips              | 1         | 0.87%   |
| Panasonic            | 1         | 0.87%   |
| MPI                  | 1         | 0.87%   |
| Lenovo               | 1         | 0.87%   |
| JDI                  | 1         | 0.87%   |
| Iiyama               | 1         | 0.87%   |
| HVR                  | 1         | 0.87%   |
| Eizo                 | 1         | 0.87%   |
| BenQ                 | 1         | 0.87%   |
| ASUSTek Computer     | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2         | 1.68%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 1.68%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                      | 2         | 1.68%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 1.68%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 1.68%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 2         | 1.68%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 1.68%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2         | 1.68%   |
| Vizio E50-C1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 1         | 0.84%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1         | 0.84%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.84%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.84%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.84%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.84%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.84%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.84%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 0.84%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.84%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 1         | 0.84%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.84%   |
| PANDA LM116LF3L01 NCP000A 1920x1080 256x144mm 11.6-inch               | 1         | 0.84%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch               | 1         | 0.84%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch               | 1         | 0.84%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 0.84%   |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                      | 1         | 0.84%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.84%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.84%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch                 | 1         | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 45        | 40.54%  |
| 3840x2160 (4K)     | 22        | 19.82%  |
| 2560x1440 (QHD)    | 12        | 10.81%  |
| 1366x768 (WXGA)    | 7         | 6.31%   |
| 2560x1080          | 4         | 3.6%    |
| 1920x1200 (WUXGA)  | 4         | 3.6%    |
| 2560x1600          | 3         | 2.7%    |
| 1280x1024 (SXGA)   | 3         | 2.7%    |
| 3440x1440          | 2         | 1.8%    |
| 2880x1800          | 2         | 1.8%    |
| 2256x1504          | 2         | 1.8%    |
| 3840x2400          | 1         | 0.9%    |
| 2160x1200          | 1         | 0.9%    |
| 1680x1050 (WSXGA+) | 1         | 0.9%    |
| 1440x900 (WXGA+)   | 1         | 0.9%    |
| 1280x720 (HD)      | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 18.42%  |
| 27      | 15        | 13.16%  |
| 13      | 14        | 12.28%  |
| 14      | 12        | 10.53%  |
| 24      | 11        | 9.65%   |
| 23      | 9         | 7.89%   |
| 34      | 6         | 5.26%   |
| 17      | 6         | 5.26%   |
| 12      | 4         | 3.51%   |
| 31      | 3         | 2.63%   |
| 25      | 2         | 1.75%   |
| 21      | 2         | 1.75%   |
| 16      | 2         | 1.75%   |
| 84      | 1         | 0.88%   |
| 49      | 1         | 0.88%   |
| 46      | 1         | 0.88%   |
| 22      | 1         | 0.88%   |
| 11      | 1         | 0.88%   |
| 8       | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 37.27%  |
| 501-600     | 33        | 30%     |
| 201-300     | 15        | 13.64%  |
| 701-800     | 6         | 5.45%   |
| 601-700     | 4         | 3.64%   |
| 401-500     | 3         | 2.73%   |
| 351-400     | 3         | 2.73%   |
| 1001-1500   | 2         | 1.82%   |
| 1501-2000   | 1         | 0.91%   |
| 101-200     | 1         | 0.91%   |
| Unknown     | 1         | 0.91%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 70        | 72.92%  |
| 16/10 | 14        | 14.58%  |
| 21/9  | 6         | 6.25%   |
| 5/4   | 3         | 3.13%   |
| 3/2   | 2         | 2.08%   |
| 4/3   | 1         | 1.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 18.26%  |
| 81-90          | 18        | 15.65%  |
| 201-250        | 18        | 15.65%  |
| 301-350        | 15        | 13.04%  |
| 351-500        | 9         | 7.83%   |
| 71-80          | 8         | 6.96%   |
| 251-300        | 6         | 5.22%   |
| 61-70          | 4         | 3.48%   |
| 141-150        | 3         | 2.61%   |
| More than 1000 | 2         | 1.74%   |
| 151-200        | 2         | 1.74%   |
| 121-130        | 2         | 1.74%   |
| 111-120        | 2         | 1.74%   |
| 51-60          | 1         | 0.87%   |
| 1-40           | 1         | 0.87%   |
| 131-140        | 1         | 0.87%   |
| 501-1000       | 1         | 0.87%   |
| Unknown        | 1         | 0.87%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 29        | 27.62%  |
| 161-240       | 26        | 24.76%  |
| 121-160       | 25        | 23.81%  |
| 101-120       | 12        | 11.43%  |
| More than 240 | 10        | 9.52%   |
| 1-50          | 2         | 1.9%    |
| Unknown       | 1         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 64        | 57.66%  |
| 2     | 23        | 20.72%  |
| 0     | 19        | 17.12%  |
| 3     | 5         | 4.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 73        | 46.79%  |
| Realtek Semiconductor             | 56        | 35.9%   |
| Qualcomm Atheros                  | 5         | 3.21%   |
| MediaTek                          | 3         | 1.92%   |
| Broadcom                          | 3         | 1.92%   |
| Microsoft                         | 2         | 1.28%   |
| Lenovo                            | 2         | 1.28%   |
| Aquantia                          | 2         | 1.28%   |
| Xiaomi                            | 1         | 0.64%   |
| TP-Link                           | 1         | 0.64%   |
| Texas Instruments                 | 1         | 0.64%   |
| Standard Microsystems             | 1         | 0.64%   |
| Qualcomm                          | 1         | 0.64%   |
| Pulse-Eight                       | 1         | 0.64%   |
| Oculus VR                         | 1         | 0.64%   |
| ICS Advent                        | 1         | 0.64%   |
| Fibocom                           | 1         | 0.64%   |
| Ericsson Business Mobile Networks | 1         | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 19.55%  |
| Intel Wi-Fi 6 AX200                                               | 16        | 8.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 7.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 3.35%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.79%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 2.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.68%   |
| Intel Wireless-AC 9260                                            | 3         | 1.68%   |
| Intel Wireless 8260                                               | 3         | 1.68%   |
| Intel Wireless 7265                                               | 3         | 1.68%   |
| Intel Wireless 7260                                               | 3         | 1.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.68%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.68%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2         | 1.12%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 1.12%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.12%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.12%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.12%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.12%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.12%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.12%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.12%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.56%   |
| Texas Instruments CC2538 USB CDC                                  | 1         | 0.56%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 77.33%  |
| Qualcomm Atheros      | 4         | 5.33%   |
| Realtek Semiconductor | 3         | 4%      |
| MediaTek              | 3         | 4%      |
| Microsoft             | 2         | 2.67%   |
| Broadcom              | 2         | 2.67%   |
| TP-Link               | 1         | 1.33%   |
| Qualcomm              | 1         | 1.33%   |
| Fibocom               | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 16        | 21.33%  |
| Intel Wi-Fi 6 AX201                                           | 4         | 5.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 4         | 5.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 4%      |
| Intel Wireless-AC 9260                                        | 3         | 4%      |
| Intel Wireless 8260                                           | 3         | 4%      |
| Intel Wireless 7265                                           | 3         | 4%      |
| Intel Wireless 7260                                           | 3         | 4%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3         | 4%      |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 3         | 4%      |
| Microsoft Xbox 360 Wireless Adapter                           | 2         | 2.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2         | 2.67%   |
| Intel Wireless 8265 / 8275                                    | 2         | 2.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 2.67%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 2.67%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 2.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 2.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 2         | 2.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 1         | 1.33%   |
| Qualcomm QCA6390 Wireless Network Adapter                     | 1         | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 1.33%   |
| Intel Wireless 3165                                           | 1         | 1.33%   |
| Intel Wireless 3160                                           | 1         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 1         | 1.33%   |
| Fibocom L830-EB-00 LTE WWAN Modem                             | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 53        | 55.21%  |
| Intel                 | 33        | 34.38%  |
| Lenovo                | 2         | 2.08%   |
| Broadcom              | 2         | 2.08%   |
| Aquantia              | 2         | 2.08%   |
| Xiaomi                | 1         | 1.04%   |
| Standard Microsystems | 1         | 1.04%   |
| Qualcomm Atheros      | 1         | 1.04%   |
| ICS Advent            | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 35%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 14%     |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 6%      |
| Intel I211 Gigabit Network Connection                             | 5         | 5%      |
| Intel Ethernet Connection I217-LM                                 | 3         | 3%      |
| Intel Ethernet Connection (7) I219-V                              | 3         | 3%      |
| Intel Ethernet Controller I225-V                                  | 2         | 2%      |
| Intel Ethernet Connection I219-LM                                 | 2         | 2%      |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2%      |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2%      |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2%      |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2%      |
| Intel Ethernet Connection (2) I218-V                              | 2         | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1%      |
| Standard Microsystems Ethernet controller                         | 1         | 1%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1%      |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1%      |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1%      |
| Intel I210 Gigabit Network Connection                             | 1         | 1%      |
| Intel Ethernet Controller I225-LM                                 | 1         | 1%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 1%      |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1%      |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1%      |
| Intel 82576 Gigabit Network Connection                            | 1         | 1%      |
| Intel 82574L Gigabit Network Connection                           | 1         | 1%      |
| ICS Advent USB 10/100 LAN                                         | 1         | 1%      |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1%      |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1%      |
| Aquantia 5G USB Ethernet Adapter                                  | 1         | 1%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 85        | 52.47%  |
| WiFi     | 73        | 45.06%  |
| Modem    | 4         | 2.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 54.05%  |
| Ethernet | 51        | 45.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 54        | 50.47%  |
| 2     | 44        | 41.12%  |
| 0     | 5         | 4.67%   |
| 3     | 3         | 2.8%    |
| 4     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 77.06%  |
| Yes  | 25        | 22.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 70.67%  |
| Realtek Semiconductor           | 5         | 6.67%   |
| Qualcomm Atheros Communications | 3         | 4%      |
| ASUSTek Computer                | 3         | 4%      |
| MediaTek                        | 2         | 2.67%   |
| Cambridge Silicon Radio         | 2         | 2.67%   |
| Broadcom                        | 2         | 2.67%   |
| Apple                           | 2         | 2.67%   |
| Lite-On Technology              | 1         | 1.33%   |
| HTC (High Tech Computer)        | 1         | 1.33%   |
| Foxconn / Hon Hai               | 1         | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                | 14        | 18.67%  |
| Intel Bluetooth wireless interface                                   | 11        | 14.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 9         | 12%     |
| Intel AX201 Bluetooth                                                | 8         | 10.67%  |
| Realtek Bluetooth Radio                                              | 5         | 6.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 4%      |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 4%      |
| Intel AX210 Bluetooth                                                | 3         | 4%      |
| Qualcomm Atheros  Bluetooth Device                                   | 2         | 2.67%   |
| MediaTek Wireless_Device                                             | 2         | 2.67%   |
| Intel Bluetooth Device                                               | 2         | 2.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2         | 2.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 2.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 2.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 1.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 1.33%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.33%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1         | 1.33%   |
| ASUS Bluetooth Device                                                | 1         | 1.33%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 1.33%   |
| Apple Bluetooth Host Controller                                      | 1         | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 65        | 38.01%  |
| AMD                                  | 39        | 22.81%  |
| Nvidia                               | 29        | 16.96%  |
| C-Media Electronics                  | 6         | 3.51%   |
| Texas Instruments                    | 3         | 1.75%   |
| Lenovo                               | 3         | 1.75%   |
| Synaptics                            | 2         | 1.17%   |
| Realtek Semiconductor                | 2         | 1.17%   |
| Kingston Technology                  | 2         | 1.17%   |
| DSEA A/S                             | 2         | 1.17%   |
| Creative Technology                  | 2         | 1.17%   |
| Unknown                              | 1         | 0.58%   |
| Trust                                | 1         | 0.58%   |
| Thomann                              | 1         | 0.58%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.58%   |
| Sony                                 | 1         | 0.58%   |
| Sennheiser Communications            | 1         | 0.58%   |
| Schiit Audio                         | 1         | 0.58%   |
| Satechi                              | 1         | 0.58%   |
| Razer USA                            | 1         | 0.58%   |
| PreSonus Audio Electronics           | 1         | 0.58%   |
| GYROCOM C&C                          | 1         | 0.58%   |
| Focusrite-Novation                   | 1         | 0.58%   |
| Creative Labs                        | 1         | 0.58%   |
| Corsair                              | 1         | 0.58%   |
| Antlion Audio                        | 1         | 0.58%   |
| (LCS) USB Audio Device               | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 16        | 7.96%   |
| AMD Family 17h/19h HD Audio Controller                              | 14        | 6.97%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 12        | 5.97%   |
| Intel Sunrise Point-LP HD Audio                                     | 11        | 5.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 7         | 3.48%   |
| Intel Cannon Lake PCH cAVS                                          | 6         | 2.99%   |
| AMD Navi 10 HDMI Audio                                              | 6         | 2.99%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 6         | 2.99%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 5         | 2.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 5         | 2.49%   |
| Nvidia GP107GL High Definition Audio Controller                     | 4         | 1.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 4         | 1.99%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 1.49%   |
| Nvidia GK104 HDMI Audio Controller                                  | 3         | 1.49%   |
| Nvidia GA106 High Definition Audio Controller                       | 3         | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3         | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 1.49%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 3         | 1.49%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 3         | 1.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 3         | 1.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 3         | 1.49%   |
| Texas Instruments PCM2902 Audio Codec                               | 2         | 1%      |
| Synaptics KM-HIFI-384KHZ                                            | 2         | 1%      |
| Realtek Semiconductor USB Audio                                     | 2         | 1%      |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 1%      |
| Nvidia GP106 High Definition Audio Controller                       | 2         | 1%      |
| Nvidia GP104 High Definition Audio Controller                       | 2         | 1%      |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 1%      |
| Kingston Technology HyperX 7.1 Audio                                | 2         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 1%      |
| Intel C610/X99 series chipset HD Audio Controller                   | 2         | 1%      |
| Intel Broadwell-U Audio Controller                                  | 2         | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                   | 2         | 1%      |
| Intel 200 Series PCH HD Audio                                       | 2         | 1%      |
| DSEA A/S Headset [PC 8]                                             | 2         | 1%      |
| C-Media Electronics USB Advanced Audio Device                       | 2         | 1%      |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 2         | 1%      |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                          | 2         | 1%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 26.89%  |
| Kingston            | 17        | 14.29%  |
| Micron Technology   | 14        | 11.76%  |
| Corsair             | 14        | 11.76%  |
| Crucial             | 11        | 9.24%   |
| SK hynix            | 9         | 7.56%   |
| G.Skill             | 8         | 6.72%   |
| Unknown (ABCD)      | 3         | 2.52%   |
| Unknown             | 3         | 2.52%   |
| Team                | 2         | 1.68%   |
| Goodram             | 2         | 1.68%   |
| Strontium           | 1         | 0.84%   |
| Avant               | 1         | 0.84%   |
| AMD                 | 1         | 0.84%   |
| A-DATA Technology   | 1         | 0.84%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 3         | 2.31%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.54%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 1.54%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.54%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.54%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.54%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 1.54%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 1.54%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 1.54%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 2         | 1.54%   |
| Corsair RAM CMK16GX4M1D3000C16 16384MB DIMM DDR4 3000MT/s        | 2         | 1.54%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.77%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.77%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s                    | 1         | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.77%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s               | 1         | 0.77%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                     | 1         | 0.77%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.77%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.77%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.77%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.77%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips 6400MT/s        | 1         | 0.77%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.77%   |
| SK hynix RAM H5ANAG6NCJR-XN 8GB SODIMM DDR4 3200MT/s             | 1         | 0.77%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.77%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.77%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.77%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.77%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 0.77%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.77%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1600MT/s                   | 1         | 0.77%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.77%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 0.77%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.77%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 69        | 68.32%  |
| DDR3   | 17        | 16.83%  |
| LPDDR4 | 9         | 8.91%   |
| LPDDR3 | 3         | 2.97%   |
| LPDDR5 | 2         | 1.98%   |
| DDR5   | 1         | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 49.51%  |
| DIMM         | 37        | 35.92%  |
| Row Of Chips | 12        | 11.65%  |
| RIMM         | 1         | 0.97%   |
| Chip         | 1         | 0.97%   |
| Unknown      | 1         | 0.97%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 44        | 39.29%  |
| 16384 | 39        | 34.82%  |
| 4096  | 14        | 12.5%   |
| 32768 | 13        | 11.61%  |
| 2048  | 2         | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 32        | 28.57%  |
| 2667  | 15        | 13.39%  |
| 1600  | 11        | 9.82%   |
| 2133  | 10        | 8.93%   |
| 2400  | 9         | 8.04%   |
| 3600  | 6         | 5.36%   |
| 4267  | 4         | 3.57%   |
| 3733  | 3         | 2.68%   |
| 3000  | 3         | 2.68%   |
| 1333  | 3         | 2.68%   |
| 6400  | 2         | 1.79%   |
| 4266  | 2         | 1.79%   |
| 3334  | 2         | 1.79%   |
| 1867  | 2         | 1.79%   |
| 4800  | 1         | 0.89%   |
| 3866  | 1         | 0.89%   |
| 3400  | 1         | 0.89%   |
| 3266  | 1         | 0.89%   |
| 2933  | 1         | 0.89%   |
| 2134  | 1         | 0.89%   |
| 2132  | 1         | 0.89%   |
| 1066  | 1         | 0.89%   |

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
| Chicony Electronics           | 12        | 18.46%  |
| Microdia                      | 10        | 15.38%  |
| Logitech                      | 8         | 12.31%  |
| IMC Networks                  | 8         | 12.31%  |
| Acer                          | 7         | 10.77%  |
| Realtek Semiconductor         | 6         | 9.23%   |
| Sunplus Innovation Technology | 3         | 4.62%   |
| Quanta                        | 3         | 4.62%   |
| MacroSilicon                  | 2         | 3.08%   |
| Apple                         | 2         | 3.08%   |
| Syntek                        | 1         | 1.54%   |
| SunplusIT                     | 1         | 1.54%   |
| Lite-On Technology            | 1         | 1.54%   |
| HD 2MP WEBCAM                 | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 8         | 11.94%  |
| Microdia Integrated_Webcam_HD        | 6         | 8.96%   |
| IMC Networks USB2.0 HD UVC WebCam    | 4         | 5.97%   |
| Acer Integrated Camera               | 4         | 5.97%   |
| IMC Networks Integrated Camera       | 3         | 4.48%   |
| Chicony HP HD Camera                 | 3         | 4.48%   |
| Sunplus Integrated_Webcam_FHD        | 2         | 2.99%   |
| Realtek Laptop Camera                | 2         | 2.99%   |
| Realtek Integrated_Webcam_HD         | 2         | 2.99%   |
| MacroSilicon USB Video               | 2         | 2.99%   |
| Logitech HD Pro Webcam C920          | 2         | 2.99%   |
| Acer Integrated IR Camera            | 2         | 2.99%   |
| Syntek Integrated Camera             | 1         | 1.49%   |
| SunplusIT HP TrueVision HD Camera    | 1         | 1.49%   |
| Sunplus Integrated_Webcam_HD         | 1         | 1.49%   |
| Realtek Integrated Webcam            | 1         | 1.49%   |
| Realtek EasyCamera                   | 1         | 1.49%   |
| Quanta VGA WebCam                    | 1         | 1.49%   |
| Quanta HP True Vision HD Camera      | 1         | 1.49%   |
| Quanta HD WebCam                     | 1         | 1.49%   |
| Microdia USB 2.0 Camera              | 1         | 1.49%   |
| Microdia Laptop_Integrated_Webcam_HD | 1         | 1.49%   |
| Microdia Integrated Webcam           | 1         | 1.49%   |
| Microdia Camera                      | 1         | 1.49%   |
| Logitech Webcam C930e                | 1         | 1.49%   |
| Logitech Webcam C310                 | 1         | 1.49%   |
| Logitech Webcam C270                 | 1         | 1.49%   |
| Logitech Webcam C120                 | 1         | 1.49%   |
| Logitech StreamCam                   | 1         | 1.49%   |
| Logitech C930c                       | 1         | 1.49%   |
| Lite-On HP HD Camera                 | 1         | 1.49%   |
| IMC Networks XHC Camera              | 1         | 1.49%   |
| HD 2MP WEBCAM HD 2MP WEBCAM          | 1         | 1.49%   |
| Chicony USB2.0 Camera                | 1         | 1.49%   |
| Apple iPhone5/5C/5S/6                | 1         | 1.49%   |
| Apple FaceTime HD Camera (Built-in)  | 1         | 1.49%   |
| Acer ThinkPad P50 Integrated Camera  | 1         | 1.49%   |
| Acer SunplusIT Integrated Camera     | 1         | 1.49%   |
| Acer HD Webcam                       | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 47.06%  |
| Validity Sensors           | 5         | 29.41%  |
| Shenzhen Goodix Technology | 4         | 23.53%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 4         | 23.53%  |
| Shenzhen Goodix Fingerprint Reader                | 3         | 17.65%  |
| Unknown                                           | 3         | 17.65%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 11.76%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 5.88%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5.88%   |
| Shenzhen Goodix  Fingerprint Device               | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 8         | 80%     |
| Yubico.com  | 1         | 10%     |
| Broadcom    | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 8         | 80%     |
| Yubico.com Yubikey 4/5 U2F+CCID                | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 63        | 56.76%  |
| 1     | 30        | 27.03%  |
| 2     | 17        | 15.32%  |
| 4     | 1         | 0.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 15        | 22.73%  |
| Fingerprint reader       | 15        | 22.73%  |
| Multimedia controller    | 8         | 12.12%  |
| Chipcard                 | 8         | 12.12%  |
| Net/wireless             | 4         | 6.06%   |
| Unassigned class         | 3         | 4.55%   |
| Camera                   | 3         | 4.55%   |
| Bluetooth                | 3         | 4.55%   |
| Modem                    | 2         | 3.03%   |
| Storage/ata              | 1         | 1.52%   |
| Network                  | 1         | 1.52%   |
| Dvb card                 | 1         | 1.52%   |
| Communication controller | 1         | 1.52%   |
| Card reader              | 1         | 1.52%   |

