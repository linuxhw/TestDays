Linux in Slovenia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovenia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Slovenia/Desktop/README.md) and [notebooks](/Location/Slovenia/Notebook/README.md).

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

Total: 575

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d387c8fec5](https://linux-hardware.org/?probe=d387c8fec5) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [cf0d6729b4](https://linux-hardware.org/?probe=cf0d6729b4) | Aug 11, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [5510e9c316](https://linux-hardware.org/?probe=5510e9c316) | Aug 06, 2023 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [0f3d20a423](https://linux-hardware.org/?probe=0f3d20a423) | Aug 06, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [12948b89f6](https://linux-hardware.org/?probe=12948b89f6) | Aug 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a14f4895b0](https://linux-hardware.org/?probe=a14f4895b0) | Jul 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e462c362aa](https://linux-hardware.org/?probe=e462c362aa) | Jul 14, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [b62328e801](https://linux-hardware.org/?probe=b62328e801) | Jun 28, 2023 |
| TUXEDO        | Polaris AMD Gen2 (REN)      | Notebook    | [18847b167a](https://linux-hardware.org/?probe=18847b167a) | Jun 28, 2023 |
| ASUSTek       | GL503VS                     | Notebook    | [767317b527](https://linux-hardware.org/?probe=767317b527) | Jun 20, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [73720c6437](https://linux-hardware.org/?probe=73720c6437) | Jun 12, 2023 |
| Nvidia        | MCP79                       | Desktop     | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| AZW           | EQ                          | Desktop     | [98e574abed](https://linux-hardware.org/?probe=98e574abed) | Jun 07, 2023 |
| Nvidia        | MCP79                       | Desktop     | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| HP            | 2AF7                        | Desktop     | [b459ce46cb](https://linux-hardware.org/?probe=b459ce46cb) | May 27, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [50b19fc413](https://linux-hardware.org/?probe=50b19fc413) | May 20, 2023 |
| Dell          | Latitude D630               | Notebook    | [d5d56f7183](https://linux-hardware.org/?probe=d5d56f7183) | May 20, 2023 |
| Dell          | Latitude D630               | Notebook    | [af41a1c303](https://linux-hardware.org/?probe=af41a1c303) | May 20, 2023 |
| ASUSTek       | Z11PG-D16 Series            | Server      | [6d9e4fc47b](https://linux-hardware.org/?probe=6d9e4fc47b) | May 16, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5402CBA... | Notebook    | [170341ae00](https://linux-hardware.org/?probe=170341ae00) | May 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [ed72b68c39](https://linux-hardware.org/?probe=ed72b68c39) | May 13, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [fbd91068d3](https://linux-hardware.org/?probe=fbd91068d3) | May 05, 2023 |
| Medion        | E6232                       | Notebook    | [38b433b485](https://linux-hardware.org/?probe=38b433b485) | May 04, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [2ab4f57ff6](https://linux-hardware.org/?probe=2ab4f57ff6) | May 04, 2023 |
| HP            | ProBook 4730s               | Notebook    | [c4f4cf46cf](https://linux-hardware.org/?probe=c4f4cf46cf) | May 01, 2023 |
| HP            | ProBook 4730s               | Notebook    | [bd90580b35](https://linux-hardware.org/?probe=bd90580b35) | May 01, 2023 |
| Acer          | Nitro AN517-42              | Notebook    | [5e54d08f91](https://linux-hardware.org/?probe=5e54d08f91) | Apr 25, 2023 |
| HP            | ZBook 17 G5                 | Notebook    | [c1d71592a4](https://linux-hardware.org/?probe=c1d71592a4) | Apr 24, 2023 |
| HP            | ZBook 17 G5                 | Notebook    | [ce9fd79431](https://linux-hardware.org/?probe=ce9fd79431) | Apr 23, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [5c9b8fef2e](https://linux-hardware.org/?probe=5c9b8fef2e) | Apr 21, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [35534cbfba](https://linux-hardware.org/?probe=35534cbfba) | Apr 19, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [d8ed935b86](https://linux-hardware.org/?probe=d8ed935b86) | Apr 19, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [ac404082b4](https://linux-hardware.org/?probe=ac404082b4) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | 2B3E                        | All in one  | [70f8ce05b6](https://linux-hardware.org/?probe=70f8ce05b6) | Apr 12, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | Notebook    | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c279e7b8fe](https://linux-hardware.org/?probe=c279e7b8fe) | Apr 11, 2023 |
| Lenovo        | ThinkPad 10 20C10025SC      | Tablet      | [780500d158](https://linux-hardware.org/?probe=780500d158) | Apr 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [4c46d2ae80](https://linux-hardware.org/?probe=4c46d2ae80) | Apr 04, 2023 |
| ASRock        | Q1900M                      | Desktop     | [dfae44d3f6](https://linux-hardware.org/?probe=dfae44d3f6) | Apr 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f46913bb86](https://linux-hardware.org/?probe=f46913bb86) | Apr 02, 2023 |
| HP            | 1998                        | Desktop     | [d88ffd3db4](https://linux-hardware.org/?probe=d88ffd3db4) | Apr 01, 2023 |
| HP            | 8053                        | Desktop     | [6c887800bb](https://linux-hardware.org/?probe=6c887800bb) | Apr 01, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [a316144991](https://linux-hardware.org/?probe=a316144991) | Mar 29, 2023 |
| ASUSTek       | PRIME H610I-PLUS D4         | Desktop     | [7b984afb2c](https://linux-hardware.org/?probe=7b984afb2c) | Mar 29, 2023 |
| HP            | Compaq 6730s                | Notebook    | [8d4cea5a81](https://linux-hardware.org/?probe=8d4cea5a81) | Mar 28, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [43113791e9](https://linux-hardware.org/?probe=43113791e9) | Mar 23, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [acbfa27478](https://linux-hardware.org/?probe=acbfa27478) | Mar 20, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [d8c39b84d1](https://linux-hardware.org/?probe=d8c39b84d1) | Mar 20, 2023 |
| HP            | 1589                        | Desktop     | [5c483a16fc](https://linux-hardware.org/?probe=5c483a16fc) | Mar 18, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [92d818d184](https://linux-hardware.org/?probe=92d818d184) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [60114cc9c8](https://linux-hardware.org/?probe=60114cc9c8) | Mar 16, 2023 |
| Dell          | Latitude 5530               | Notebook    | [aac966a8af](https://linux-hardware.org/?probe=aac966a8af) | Mar 15, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [4b1712febb](https://linux-hardware.org/?probe=4b1712febb) | Mar 15, 2023 |
| Lenovo        | IdeaPad U300s 20111         | Notebook    | [aaaee5fcf5](https://linux-hardware.org/?probe=aaaee5fcf5) | Mar 12, 2023 |
| Lenovo        | IdeaPad U300s 20111         | Notebook    | [3f3945f7e3](https://linux-hardware.org/?probe=3f3945f7e3) | Mar 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6735fc94ae](https://linux-hardware.org/?probe=6735fc94ae) | Mar 06, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Toshiba       | Satellite Pro R50-E         | Notebook    | [b039ed22c6](https://linux-hardware.org/?probe=b039ed22c6) | Mar 01, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | Notebook    | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [eaec9511de](https://linux-hardware.org/?probe=eaec9511de) | Feb 27, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [85ed1d43c7](https://linux-hardware.org/?probe=85ed1d43c7) | Feb 26, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| HP            | ProBook 4730s               | Notebook    | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Supermicro    | X11SCAA                     | Server      | [f445829317](https://linux-hardware.org/?probe=f445829317) | Feb 15, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [0461c55b4a](https://linux-hardware.org/?probe=0461c55b4a) | Feb 10, 2023 |
| HP            | ProBook 4530s               | Notebook    | [c081fdc9be](https://linux-hardware.org/?probe=c081fdc9be) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [84fb689a7e](https://linux-hardware.org/?probe=84fb689a7e) | Feb 06, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [475265e1f8](https://linux-hardware.org/?probe=475265e1f8) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [0698054de0](https://linux-hardware.org/?probe=0698054de0) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [122005ade3](https://linux-hardware.org/?probe=122005ade3) | Jan 30, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [0e241538c1](https://linux-hardware.org/?probe=0e241538c1) | Jan 29, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [2cf59bd38d](https://linux-hardware.org/?probe=2cf59bd38d) | Jan 26, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [6bd02bf2c0](https://linux-hardware.org/?probe=6bd02bf2c0) | Jan 24, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [405641895c](https://linux-hardware.org/?probe=405641895c) | Jan 18, 2023 |
| Medion        | MS-7621                     | Desktop     | [67b535d88f](https://linux-hardware.org/?probe=67b535d88f) | Jan 18, 2023 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [74bf687e30](https://linux-hardware.org/?probe=74bf687e30) | Jan 15, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [436a4fc2a0](https://linux-hardware.org/?probe=436a4fc2a0) | Jan 15, 2023 |
| Lenovo        | ThinkPad E590 20NCS00800    | Notebook    | [8751d5b445](https://linux-hardware.org/?probe=8751d5b445) | Jan 15, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [b3c2be78b3](https://linux-hardware.org/?probe=b3c2be78b3) | Jan 14, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [6a11a77a53](https://linux-hardware.org/?probe=6a11a77a53) | Jan 12, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [09f51f5cd3](https://linux-hardware.org/?probe=09f51f5cd3) | Jan 12, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [82ca2971d9](https://linux-hardware.org/?probe=82ca2971d9) | Jan 12, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [7c432a386b](https://linux-hardware.org/?probe=7c432a386b) | Jan 11, 2023 |
| Lenovo        | 31900058 STD or WIN         | Desktop     | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [496bc9b9cd](https://linux-hardware.org/?probe=496bc9b9cd) | Jan 03, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [501b47c258](https://linux-hardware.org/?probe=501b47c258) | Jan 02, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [3948dcc7ef](https://linux-hardware.org/?probe=3948dcc7ef) | Dec 23, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [01b7250cea](https://linux-hardware.org/?probe=01b7250cea) | Dec 19, 2022 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [999cbfe9f7](https://linux-hardware.org/?probe=999cbfe9f7) | Dec 19, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [1bb0000755](https://linux-hardware.org/?probe=1bb0000755) | Dec 16, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [3892b54ac4](https://linux-hardware.org/?probe=3892b54ac4) | Dec 08, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [a7b446df37](https://linux-hardware.org/?probe=a7b446df37) | Dec 08, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [59118a0638](https://linux-hardware.org/?probe=59118a0638) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [a214979767](https://linux-hardware.org/?probe=a214979767) | Dec 07, 2022 |
| Toshiba       | Satellite R630              | Notebook    | [3826be6846](https://linux-hardware.org/?probe=3826be6846) | Dec 06, 2022 |
| Toshiba       | Satellite R630              | Notebook    | [eebafcab9e](https://linux-hardware.org/?probe=eebafcab9e) | Dec 06, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [eced972f80](https://linux-hardware.org/?probe=eced972f80) | Dec 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [d37c93af89](https://linux-hardware.org/?probe=d37c93af89) | Dec 05, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [9d2066a479](https://linux-hardware.org/?probe=9d2066a479) | Dec 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [f19b2c0b81](https://linux-hardware.org/?probe=f19b2c0b81) | Dec 03, 2022 |
| ASUSTek       | 1225B                       | Notebook    | [87f1b143de](https://linux-hardware.org/?probe=87f1b143de) | Nov 27, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [5271fa9ef9](https://linux-hardware.org/?probe=5271fa9ef9) | Nov 26, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [673c961915](https://linux-hardware.org/?probe=673c961915) | Nov 09, 2022 |
| Lenovo        | B50-80 80LT                 | Notebook    | [c16106686d](https://linux-hardware.org/?probe=c16106686d) | Nov 08, 2022 |
| HP            | 8591                        | Desktop     | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [10d2346f7c](https://linux-hardware.org/?probe=10d2346f7c) | Oct 30, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [1af8ca0ac9](https://linux-hardware.org/?probe=1af8ca0ac9) | Oct 27, 2022 |
| ASUSTek       | X510UQR                     | Notebook    | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [de0b3e96fa](https://linux-hardware.org/?probe=de0b3e96fa) | Oct 23, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [b91eedb26a](https://linux-hardware.org/?probe=b91eedb26a) | Oct 23, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a2e0ee2043](https://linux-hardware.org/?probe=a2e0ee2043) | Oct 15, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [90661c40a3](https://linux-hardware.org/?probe=90661c40a3) | Oct 12, 2022 |
| Toshiba       | Satellite A100              | Notebook    | [f280857c1c](https://linux-hardware.org/?probe=f280857c1c) | Oct 09, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [5348794267](https://linux-hardware.org/?probe=5348794267) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [487fd1959f](https://linux-hardware.org/?probe=487fd1959f) | Oct 08, 2022 |
| HP            | 18E4                        | Desktop     | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [660419ed49](https://linux-hardware.org/?probe=660419ed49) | Sep 27, 2022 |
| HP            | Pavilion g7                 | Notebook    | [19b206ba2f](https://linux-hardware.org/?probe=19b206ba2f) | Sep 25, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [0306edc8ba](https://linux-hardware.org/?probe=0306edc8ba) | Sep 22, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [56d6df17b5](https://linux-hardware.org/?probe=56d6df17b5) | Sep 22, 2022 |
| HP            | ProBook 4340s               | Notebook    | [668ffa05ea](https://linux-hardware.org/?probe=668ffa05ea) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| HP            | ProBook 4340s               | Notebook    | [1abbd84e9c](https://linux-hardware.org/?probe=1abbd84e9c) | Sep 18, 2022 |
| Toshiba       | TECRA S10                   | Notebook    | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [600ef31484](https://linux-hardware.org/?probe=600ef31484) | Sep 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6ff152e455](https://linux-hardware.org/?probe=6ff152e455) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | Notebook    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| HP            | Unknown                     | Notebook    | [692825c1eb](https://linux-hardware.org/?probe=692825c1eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | Notebook    | [c55fef18c3](https://linux-hardware.org/?probe=c55fef18c3) | Sep 11, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [4c7f501c2b](https://linux-hardware.org/?probe=4c7f501c2b) | Sep 02, 2022 |
| HP            | 8053                        | Desktop     | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | Notebook    | [273e5229a4](https://linux-hardware.org/?probe=273e5229a4) | Aug 30, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [adae304d62](https://linux-hardware.org/?probe=adae304d62) | Aug 24, 2022 |
| Supermicro    | X7SBi-LN4                   | Desktop     | [ec37ffcc15](https://linux-hardware.org/?probe=ec37ffcc15) | Aug 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [230d7247c0](https://linux-hardware.org/?probe=230d7247c0) | Aug 11, 2022 |
| Framework     | Laptop                      | Notebook    | [c52019fe10](https://linux-hardware.org/?probe=c52019fe10) | Aug 07, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | Notebook    | [b9c35e80d2](https://linux-hardware.org/?probe=b9c35e80d2) | Aug 06, 2022 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [c301219c25](https://linux-hardware.org/?probe=c301219c25) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [17954b8ac5](https://linux-hardware.org/?probe=17954b8ac5) | Jul 26, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [6ab4942a20](https://linux-hardware.org/?probe=6ab4942a20) | Jul 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [0e195b05bf](https://linux-hardware.org/?probe=0e195b05bf) | Jul 13, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [d9573dc3e6](https://linux-hardware.org/?probe=d9573dc3e6) | Jul 08, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [f6efa72c1f](https://linux-hardware.org/?probe=f6efa72c1f) | Jul 01, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d59692d648](https://linux-hardware.org/?probe=d59692d648) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [4afafc5b76](https://linux-hardware.org/?probe=4afafc5b76) | Jun 29, 2022 |
| IBM           | 00AM527                     | Server      | [8af3a08c43](https://linux-hardware.org/?probe=8af3a08c43) | Jun 26, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [cae0332804](https://linux-hardware.org/?probe=cae0332804) | Jun 17, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [e65ead281f](https://linux-hardware.org/?probe=e65ead281f) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [cc2e6a1605](https://linux-hardware.org/?probe=cc2e6a1605) | Jun 17, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [28c5fad176](https://linux-hardware.org/?probe=28c5fad176) | Jun 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [f4c9e8f3f2](https://linux-hardware.org/?probe=f4c9e8f3f2) | May 30, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [14ebca03fe](https://linux-hardware.org/?probe=14ebca03fe) | May 30, 2022 |
| Toshiba       | Satellite Pro U400          | Notebook    | [4aeeca648d](https://linux-hardware.org/?probe=4aeeca648d) | May 24, 2022 |
| Intel         | CM-iAM/SBC-FITPC2i          | Desktop     | [cbfe433386](https://linux-hardware.org/?probe=cbfe433386) | May 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ddadf86375](https://linux-hardware.org/?probe=ddadf86375) | May 15, 2022 |
| ASUSTek       | N71Vg                       | Notebook    | [33a6047c0b](https://linux-hardware.org/?probe=33a6047c0b) | May 14, 2022 |
| ASUSTek       | N71Vg                       | Notebook    | [86d9e911f1](https://linux-hardware.org/?probe=86d9e911f1) | May 13, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [934d403a31](https://linux-hardware.org/?probe=934d403a31) | May 04, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [ce528c379a](https://linux-hardware.org/?probe=ce528c379a) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [81409450dc](https://linux-hardware.org/?probe=81409450dc) | Apr 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f727388ac8](https://linux-hardware.org/?probe=f727388ac8) | Apr 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c1102c77ec](https://linux-hardware.org/?probe=c1102c77ec) | Apr 17, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d7b7a81cbb](https://linux-hardware.org/?probe=d7b7a81cbb) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [7e7136d915](https://linux-hardware.org/?probe=7e7136d915) | Apr 16, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [76a5225b83](https://linux-hardware.org/?probe=76a5225b83) | Apr 16, 2022 |
| ASRock        | H170M Pro4                  | Desktop     | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [8570b5ab84](https://linux-hardware.org/?probe=8570b5ab84) | Apr 12, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [222189213d](https://linux-hardware.org/?probe=222189213d) | Apr 11, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | Notebook    | [4864fcdfa0](https://linux-hardware.org/?probe=4864fcdfa0) | Apr 07, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [0813d4bc9e](https://linux-hardware.org/?probe=0813d4bc9e) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [defac75126](https://linux-hardware.org/?probe=defac75126) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d13496f68a](https://linux-hardware.org/?probe=d13496f68a) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [da62c7238d](https://linux-hardware.org/?probe=da62c7238d) | Mar 28, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [1260b540e7](https://linux-hardware.org/?probe=1260b540e7) | Mar 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1eebe899b0](https://linux-hardware.org/?probe=1eebe899b0) | Mar 27, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [f0efa22aa2](https://linux-hardware.org/?probe=f0efa22aa2) | Mar 27, 2022 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [0bf3028253](https://linux-hardware.org/?probe=0bf3028253) | Mar 27, 2022 |
| Dell          | Precision 5540              | Notebook    | [38d9bed727](https://linux-hardware.org/?probe=38d9bed727) | Mar 21, 2022 |
| Fujitsu       | LIFEBOOK S792               | Notebook    | [55da3ab4e0](https://linux-hardware.org/?probe=55da3ab4e0) | Mar 09, 2022 |
| Supermicro    | X11SCAA                     | Server      | [b850cd60f6](https://linux-hardware.org/?probe=b850cd60f6) | Mar 08, 2022 |
| HP            | Compaq nw8440 (RH415EA#A... | Notebook    | [55a6d982b3](https://linux-hardware.org/?probe=55a6d982b3) | Mar 07, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| HP            | kip                         | Notebook    | [4d6e1264c7](https://linux-hardware.org/?probe=4d6e1264c7) | Mar 02, 2022 |
| HP            | kip                         | Notebook    | [a6ab5d4d8a](https://linux-hardware.org/?probe=a6ab5d4d8a) | Mar 01, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [d5c0be1b13](https://linux-hardware.org/?probe=d5c0be1b13) | Feb 27, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9d5d5c0ffb](https://linux-hardware.org/?probe=9d5d5c0ffb) | Feb 26, 2022 |
| HP            | Pavilion dv7                | Notebook    | [46280b758c](https://linux-hardware.org/?probe=46280b758c) | Feb 25, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1c8a37fb2f](https://linux-hardware.org/?probe=1c8a37fb2f) | Feb 24, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [ec93ded12b](https://linux-hardware.org/?probe=ec93ded12b) | Feb 23, 2022 |
| Dell          | 09M8Y8 A02                  | Desktop     | [202fc1f0b9](https://linux-hardware.org/?probe=202fc1f0b9) | Feb 22, 2022 |
| HP            | Pavilion dv7                | Notebook    | [fd1bbe1769](https://linux-hardware.org/?probe=fd1bbe1769) | Feb 21, 2022 |
| HP            | Pavilion dv7                | Notebook    | [da9449422c](https://linux-hardware.org/?probe=da9449422c) | Feb 21, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [0ee9dcd568](https://linux-hardware.org/?probe=0ee9dcd568) | Feb 20, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5ffa4bce13](https://linux-hardware.org/?probe=5ffa4bce13) | Feb 19, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [5ee5668ab1](https://linux-hardware.org/?probe=5ee5668ab1) | Feb 19, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [5323885713](https://linux-hardware.org/?probe=5323885713) | Feb 17, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cad9a70c49](https://linux-hardware.org/?probe=cad9a70c49) | Feb 16, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [676d121bda](https://linux-hardware.org/?probe=676d121bda) | Feb 13, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [df5a829402](https://linux-hardware.org/?probe=df5a829402) | Feb 09, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [239eb94a17](https://linux-hardware.org/?probe=239eb94a17) | Feb 07, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [ec43c5baa2](https://linux-hardware.org/?probe=ec43c5baa2) | Feb 07, 2022 |
| ASUSTek       | X750LN                      | Notebook    | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Inspiron 5748               | Notebook    | [07c8076d3e](https://linux-hardware.org/?probe=07c8076d3e) | Feb 01, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [901d568e70](https://linux-hardware.org/?probe=901d568e70) | Jan 31, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [621d099786](https://linux-hardware.org/?probe=621d099786) | Jan 31, 2022 |
| HP            | 1589                        | Desktop     | [41dbcb78cb](https://linux-hardware.org/?probe=41dbcb78cb) | Jan 30, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [81e03a6b48](https://linux-hardware.org/?probe=81e03a6b48) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [faba7de732](https://linux-hardware.org/?probe=faba7de732) | Jan 17, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [f2bae7651d](https://linux-hardware.org/?probe=f2bae7651d) | Jan 16, 2022 |
| ASRock        | B85M-HDS                    | Desktop     | [77cb3218a8](https://linux-hardware.org/?probe=77cb3218a8) | Jan 12, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [b9b69a73a3](https://linux-hardware.org/?probe=b9b69a73a3) | Jan 09, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [22e51b8b41](https://linux-hardware.org/?probe=22e51b8b41) | Jan 06, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [52db8d0bbf](https://linux-hardware.org/?probe=52db8d0bbf) | Jan 06, 2022 |
| Lenovo        | ThinkPad T590 20N5S0MR00    | Notebook    | [29040ecce5](https://linux-hardware.org/?probe=29040ecce5) | Jan 01, 2022 |
| MSI           | U210                        | Notebook    | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [be79b3cd82](https://linux-hardware.org/?probe=be79b3cd82) | Dec 26, 2021 |
| Lenovo        | ThinkCentre M57e 9439WHV    | Desktop     | [a9b2163945](https://linux-hardware.org/?probe=a9b2163945) | Dec 25, 2021 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [97ec4e3d99](https://linux-hardware.org/?probe=97ec4e3d99) | Dec 25, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [8887022aa7](https://linux-hardware.org/?probe=8887022aa7) | Dec 23, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6b40a0f2c5](https://linux-hardware.org/?probe=6b40a0f2c5) | Dec 21, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [31c2b40e84](https://linux-hardware.org/?probe=31c2b40e84) | Dec 21, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [6238c622ad](https://linux-hardware.org/?probe=6238c622ad) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [6aee0ff442](https://linux-hardware.org/?probe=6aee0ff442) | Dec 15, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [45ac665485](https://linux-hardware.org/?probe=45ac665485) | Dec 10, 2021 |
| Dell          | Inspiron 5748               | Notebook    | [77f278682e](https://linux-hardware.org/?probe=77f278682e) | Dec 06, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [6d9c31a411](https://linux-hardware.org/?probe=6d9c31a411) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [e005ddb405](https://linux-hardware.org/?probe=e005ddb405) | Nov 28, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | EliteBook 8760w             | Notebook    | [febc9d2faa](https://linux-hardware.org/?probe=febc9d2faa) | Nov 28, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6016236fad](https://linux-hardware.org/?probe=6016236fad) | Nov 24, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [97409a8d1c](https://linux-hardware.org/?probe=97409a8d1c) | Nov 22, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [e0e4ee802a](https://linux-hardware.org/?probe=e0e4ee802a) | Nov 22, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [e898d8c017](https://linux-hardware.org/?probe=e898d8c017) | Nov 20, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [e37febb0b3](https://linux-hardware.org/?probe=e37febb0b3) | Nov 18, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [163092e4b9](https://linux-hardware.org/?probe=163092e4b9) | Nov 18, 2021 |
| HP            | 250 G3                      | Notebook    | [8d370cbb27](https://linux-hardware.org/?probe=8d370cbb27) | Nov 16, 2021 |
| HP            | 250 G3                      | Notebook    | [fb9fe2f3fb](https://linux-hardware.org/?probe=fb9fe2f3fb) | Nov 16, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [c4e6de1315](https://linux-hardware.org/?probe=c4e6de1315) | Nov 15, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [0f6c2b21cf](https://linux-hardware.org/?probe=0f6c2b21cf) | Nov 14, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [01c20231f2](https://linux-hardware.org/?probe=01c20231f2) | Nov 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [3c3e5bc872](https://linux-hardware.org/?probe=3c3e5bc872) | Nov 08, 2021 |
| HP            | EliteBook 8760w             | Notebook    | [99fb47dc2b](https://linux-hardware.org/?probe=99fb47dc2b) | Oct 28, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [4e5da9e4d3](https://linux-hardware.org/?probe=4e5da9e4d3) | Oct 24, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [f66ba65dc8](https://linux-hardware.org/?probe=f66ba65dc8) | Oct 22, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [1d50915627](https://linux-hardware.org/?probe=1d50915627) | Oct 21, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [a11d4b7c50](https://linux-hardware.org/?probe=a11d4b7c50) | Oct 20, 2021 |
| Lenovo        | ThinkPad 10 20C10025SC      | Tablet      | [7d6ab19f8d](https://linux-hardware.org/?probe=7d6ab19f8d) | Oct 20, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [f18e793687](https://linux-hardware.org/?probe=f18e793687) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [065ee91163](https://linux-hardware.org/?probe=065ee91163) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [2cbf85194c](https://linux-hardware.org/?probe=2cbf85194c) | Oct 14, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [cd738f5036](https://linux-hardware.org/?probe=cd738f5036) | Oct 11, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [bc1fd03a63](https://linux-hardware.org/?probe=bc1fd03a63) | Oct 10, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [6ec6ce5c81](https://linux-hardware.org/?probe=6ec6ce5c81) | Oct 10, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [f424437bd1](https://linux-hardware.org/?probe=f424437bd1) | Oct 01, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [c85622ebee](https://linux-hardware.org/?probe=c85622ebee) | Sep 29, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [9813ead17b](https://linux-hardware.org/?probe=9813ead17b) | Sep 23, 2021 |
| Medion        | Akoya E7226                 | Desktop     | [9367472acb](https://linux-hardware.org/?probe=9367472acb) | Sep 18, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [934d0576e0](https://linux-hardware.org/?probe=934d0576e0) | Aug 27, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | Notebook    | [b2de2ea1ab](https://linux-hardware.org/?probe=b2de2ea1ab) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | Notebook    | [9da6a33d24](https://linux-hardware.org/?probe=9da6a33d24) | Aug 22, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [8c7e729202](https://linux-hardware.org/?probe=8c7e729202) | Aug 19, 2021 |
| ASRock        | H310CM-HDV                  | Desktop     | [0fccd48745](https://linux-hardware.org/?probe=0fccd48745) | Aug 13, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [8cc7d05010](https://linux-hardware.org/?probe=8cc7d05010) | Aug 12, 2021 |
| HP            | 2000                        | Notebook    | [2909375db3](https://linux-hardware.org/?probe=2909375db3) | Aug 06, 2021 |
| HP            | 2000                        | Notebook    | [df5d5e05c6](https://linux-hardware.org/?probe=df5d5e05c6) | Aug 06, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| HP            | 2000                        | Notebook    | [9fbfcf95d2](https://linux-hardware.org/?probe=9fbfcf95d2) | Jul 29, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [13aaafccdb](https://linux-hardware.org/?probe=13aaafccdb) | Jul 22, 2021 |
| HP            | 2000                        | Notebook    | [f3c7f85988](https://linux-hardware.org/?probe=f3c7f85988) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e6e223209a](https://linux-hardware.org/?probe=e6e223209a) | Jul 20, 2021 |
| MSI           | H61M-P31                    | Desktop     | [ccd9d80d59](https://linux-hardware.org/?probe=ccd9d80d59) | Jul 18, 2021 |
| Pegatron      | 2A73                        | Desktop     | [2bff425af7](https://linux-hardware.org/?probe=2bff425af7) | Jul 14, 2021 |
| Pegatron      | 2A73                        | Desktop     | [44ea7169ef](https://linux-hardware.org/?probe=44ea7169ef) | Jul 14, 2021 |
| HP            | 2000                        | Notebook    | [e6019f1bd3](https://linux-hardware.org/?probe=e6019f1bd3) | Jul 12, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [bc18a23953](https://linux-hardware.org/?probe=bc18a23953) | Jun 28, 2021 |
| HP            | 2000                        | Notebook    | [6a169f2d87](https://linux-hardware.org/?probe=6a169f2d87) | Jun 22, 2021 |
| HP            | 2000                        | Notebook    | [b2e5075aaf](https://linux-hardware.org/?probe=b2e5075aaf) | Jun 17, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [330d2214c6](https://linux-hardware.org/?probe=330d2214c6) | Jun 10, 2021 |
| HP            | 2000                        | Notebook    | [6a1c91ae8d](https://linux-hardware.org/?probe=6a1c91ae8d) | Jun 07, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [c79b400454](https://linux-hardware.org/?probe=c79b400454) | Jun 06, 2021 |
| Lenovo        | ThinkPad T61 8897CTO        | Notebook    | [6cfc0271ba](https://linux-hardware.org/?probe=6cfc0271ba) | Jun 03, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [181bd83bdd](https://linux-hardware.org/?probe=181bd83bdd) | Jun 02, 2021 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [02bf919368](https://linux-hardware.org/?probe=02bf919368) | Jun 02, 2021 |
| Acer          | Aspire Z5610                | All in one  | [b24fdb7446](https://linux-hardware.org/?probe=b24fdb7446) | May 28, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [92d97521bc](https://linux-hardware.org/?probe=92d97521bc) | May 21, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [32951a000f](https://linux-hardware.org/?probe=32951a000f) | May 21, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [76598a468f](https://linux-hardware.org/?probe=76598a468f) | May 20, 2021 |
| HP            | 2000                        | Notebook    | [1469c94a5f](https://linux-hardware.org/?probe=1469c94a5f) | May 17, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [a4b9bc232a](https://linux-hardware.org/?probe=a4b9bc232a) | May 15, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [8fcf99f057](https://linux-hardware.org/?probe=8fcf99f057) | May 12, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | Desktop     | [3e6d98fe9c](https://linux-hardware.org/?probe=3e6d98fe9c) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [f67c550f8e](https://linux-hardware.org/?probe=f67c550f8e) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [0876a200b7](https://linux-hardware.org/?probe=0876a200b7) | Apr 27, 2021 |
| ASRock        | B560 Pro4                   | Desktop     | [ddd384c6cb](https://linux-hardware.org/?probe=ddd384c6cb) | Apr 26, 2021 |
| Lenovo        | ThinkCentre M55e 9389WEG    | Desktop     | [66c2003859](https://linux-hardware.org/?probe=66c2003859) | Apr 20, 2021 |
| HP            | 1905                        | Desktop     | [e0fc243f47](https://linux-hardware.org/?probe=e0fc243f47) | Apr 19, 2021 |
| Panasonic     | CF-53SWWZ5MG                | Notebook    | [c59fd76192](https://linux-hardware.org/?probe=c59fd76192) | Apr 14, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [d0a4124a2a](https://linux-hardware.org/?probe=d0a4124a2a) | Apr 10, 2021 |
| HP            | ProBook 4515s (VC377ES#A... | Notebook    | [2c84f60b0d](https://linux-hardware.org/?probe=2c84f60b0d) | Apr 09, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| HP            | ProBook 4740s               | Notebook    | [cf941af09e](https://linux-hardware.org/?probe=cf941af09e) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| ASUSTek       | P5Q SE                      | Desktop     | [325f4ca461](https://linux-hardware.org/?probe=325f4ca461) | Apr 05, 2021 |
| ASUSTek       | P5Q SE                      | Desktop     | [1c3958d998](https://linux-hardware.org/?probe=1c3958d998) | Apr 05, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | Desktop     | [1038d58fea](https://linux-hardware.org/?probe=1038d58fea) | Mar 25, 2021 |
| Dell          | Latitude 5501               | Notebook    | [474510883b](https://linux-hardware.org/?probe=474510883b) | Mar 22, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | Desktop     | [8b28b318fd](https://linux-hardware.org/?probe=8b28b318fd) | Mar 19, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [453120855b](https://linux-hardware.org/?probe=453120855b) | Mar 18, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [49b951896d](https://linux-hardware.org/?probe=49b951896d) | Mar 17, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [2d9ae8527d](https://linux-hardware.org/?probe=2d9ae8527d) | Mar 11, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [e434a21940](https://linux-hardware.org/?probe=e434a21940) | Mar 04, 2021 |
| Panasonic     | CF-53SWWZ5MG                | Notebook    | [6fdf12c20c](https://linux-hardware.org/?probe=6fdf12c20c) | Feb 28, 2021 |
| Apple         | Mac-F4208DA9 PVT            | Desktop     | [4ab255096c](https://linux-hardware.org/?probe=4ab255096c) | Feb 28, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [9dc547fceb](https://linux-hardware.org/?probe=9dc547fceb) | Feb 26, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [49cd056ca4](https://linux-hardware.org/?probe=49cd056ca4) | Feb 24, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [8e84f252bc](https://linux-hardware.org/?probe=8e84f252bc) | Feb 20, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [bd76fdbde8](https://linux-hardware.org/?probe=bd76fdbde8) | Feb 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [153bb12a6a](https://linux-hardware.org/?probe=153bb12a6a) | Feb 19, 2021 |
| MSI           | H61M-P31                    | Desktop     | [a0192f9d6e](https://linux-hardware.org/?probe=a0192f9d6e) | Feb 17, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [106c66da60](https://linux-hardware.org/?probe=106c66da60) | Feb 14, 2021 |
| Lenovo        | ThinkCentre M90p 5498PK8    | Desktop     | [df39a8847b](https://linux-hardware.org/?probe=df39a8847b) | Feb 14, 2021 |
| Lenovo        | ThinkPad L520 785958G       | Notebook    | [45025e2399](https://linux-hardware.org/?probe=45025e2399) | Feb 13, 2021 |
| Lenovo        | ThinkPad L520 785958G       | Notebook    | [be03f382e6](https://linux-hardware.org/?probe=be03f382e6) | Feb 09, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [e40fe3768d](https://linux-hardware.org/?probe=e40fe3768d) | Feb 09, 2021 |
| Panasonic     | CF-53SWWZ5MG                | Notebook    | [d1ade3e39d](https://linux-hardware.org/?probe=d1ade3e39d) | Feb 08, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [a31754db23](https://linux-hardware.org/?probe=a31754db23) | Feb 08, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [95958aa225](https://linux-hardware.org/?probe=95958aa225) | Feb 08, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [0e552a01e6](https://linux-hardware.org/?probe=0e552a01e6) | Feb 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [1f3dc6c825](https://linux-hardware.org/?probe=1f3dc6c825) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | Notebook    | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [7e828e295f](https://linux-hardware.org/?probe=7e828e295f) | Jan 20, 2021 |
| Pegatron      | 2A73                        | Desktop     | [4c2042c088](https://linux-hardware.org/?probe=4c2042c088) | Jan 18, 2021 |
| Pegatron      | 2A73                        | Desktop     | [c6cf8a7efe](https://linux-hardware.org/?probe=c6cf8a7efe) | Jan 18, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [812e100310](https://linux-hardware.org/?probe=812e100310) | Jan 12, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [30332e1d71](https://linux-hardware.org/?probe=30332e1d71) | Jan 12, 2021 |
| MSI           | H55M-P31                    | Desktop     | [3313a8aba5](https://linux-hardware.org/?probe=3313a8aba5) | Jan 12, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0265add193](https://linux-hardware.org/?probe=0265add193) | Jan 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8b0a9a71b3](https://linux-hardware.org/?probe=8b0a9a71b3) | Jan 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [497bf4005e](https://linux-hardware.org/?probe=497bf4005e) | Jan 10, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [8227f44e5c](https://linux-hardware.org/?probe=8227f44e5c) | Jan 10, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [60d8b9344b](https://linux-hardware.org/?probe=60d8b9344b) | Jan 09, 2021 |
| HP            | ProBook 4730s               | Notebook    | [e7ab1bcd89](https://linux-hardware.org/?probe=e7ab1bcd89) | Jan 06, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [e9c1683321](https://linux-hardware.org/?probe=e9c1683321) | Jan 04, 2021 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [b6c93666ee](https://linux-hardware.org/?probe=b6c93666ee) | Dec 29, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [7905034ba5](https://linux-hardware.org/?probe=7905034ba5) | Dec 29, 2020 |
| ASUSTek       | UX31E                       | Notebook    | [912f3fe702](https://linux-hardware.org/?probe=912f3fe702) | Dec 25, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [d759211bb6](https://linux-hardware.org/?probe=d759211bb6) | Dec 24, 2020 |
| Lenovo        | ThinkPad T420 4236A78       | Notebook    | [f98c371e7f](https://linux-hardware.org/?probe=f98c371e7f) | Dec 24, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [71370e1dd8](https://linux-hardware.org/?probe=71370e1dd8) | Dec 19, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [6c3965a41f](https://linux-hardware.org/?probe=6c3965a41f) | Dec 18, 2020 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [87bd14894c](https://linux-hardware.org/?probe=87bd14894c) | Dec 18, 2020 |
| ASUSTek       | G771JW                      | Notebook    | [b103133d69](https://linux-hardware.org/?probe=b103133d69) | Dec 16, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [def1b6fff4](https://linux-hardware.org/?probe=def1b6fff4) | Dec 13, 2020 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [edd5100ec5](https://linux-hardware.org/?probe=edd5100ec5) | Dec 13, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [4260174285](https://linux-hardware.org/?probe=4260174285) | Dec 11, 2020 |
| Lenovo        | ThinkPad T500 2055WYX       | Notebook    | [6f04a45e2e](https://linux-hardware.org/?probe=6f04a45e2e) | Dec 11, 2020 |
| Lenovo        | 3135                        | Mini pc     | [b16b2d9bd5](https://linux-hardware.org/?probe=b16b2d9bd5) | Dec 11, 2020 |
| Lenovo        | ThinkPad T410 2522A92       | Notebook    | [dd93682c3c](https://linux-hardware.org/?probe=dd93682c3c) | Dec 09, 2020 |
| Dell          | Latitude D630               | Notebook    | [92ccc6100c](https://linux-hardware.org/?probe=92ccc6100c) | Dec 05, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [e2ffbd65b4](https://linux-hardware.org/?probe=e2ffbd65b4) | Dec 04, 2020 |
| Pegatron      | EVE                         | Desktop     | [08ced52205](https://linux-hardware.org/?probe=08ced52205) | Nov 29, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [44642a5ed8](https://linux-hardware.org/?probe=44642a5ed8) | Nov 27, 2020 |
| Apple         | Mac-F2218EA9                | All in one  | [201739da91](https://linux-hardware.org/?probe=201739da91) | Nov 25, 2020 |
| Apple         | Mac-F2218EA9                | All in one  | [abd1a36454](https://linux-hardware.org/?probe=abd1a36454) | Nov 23, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [1b5583ba18](https://linux-hardware.org/?probe=1b5583ba18) | Nov 23, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1bc0a5a430](https://linux-hardware.org/?probe=1bc0a5a430) | Nov 23, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bc3c7d8910](https://linux-hardware.org/?probe=bc3c7d8910) | Nov 22, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [db1f0e1247](https://linux-hardware.org/?probe=db1f0e1247) | Nov 22, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [5978ba6a13](https://linux-hardware.org/?probe=5978ba6a13) | Nov 22, 2020 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [505fb108f7](https://linux-hardware.org/?probe=505fb108f7) | Nov 21, 2020 |
| HP            | 470 G7 Notebook PC          | Notebook    | [f0d3574818](https://linux-hardware.org/?probe=f0d3574818) | Nov 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8783481f8a](https://linux-hardware.org/?probe=8783481f8a) | Nov 15, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [1298138505](https://linux-hardware.org/?probe=1298138505) | Nov 13, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [c3df499de1](https://linux-hardware.org/?probe=c3df499de1) | Nov 12, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e05c144d2f](https://linux-hardware.org/?probe=e05c144d2f) | Nov 12, 2020 |
| HP            | ProBook 4720s               | Notebook    | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| Lenovo        | ThinkCentre M55e 9389WEG    | Desktop     | [2462c80a14](https://linux-hardware.org/?probe=2462c80a14) | Nov 10, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e8f7b6ef7e](https://linux-hardware.org/?probe=e8f7b6ef7e) | Nov 07, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [7e9d52855a](https://linux-hardware.org/?probe=7e9d52855a) | Nov 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3ecd75648c](https://linux-hardware.org/?probe=3ecd75648c) | Nov 06, 2020 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [b9007f3b4f](https://linux-hardware.org/?probe=b9007f3b4f) | Nov 05, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1e6ba50614](https://linux-hardware.org/?probe=1e6ba50614) | Nov 04, 2020 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [caa0e9c93b](https://linux-hardware.org/?probe=caa0e9c93b) | Nov 02, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0b3fe9a6f2](https://linux-hardware.org/?probe=0b3fe9a6f2) | Nov 01, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [49bc5032be](https://linux-hardware.org/?probe=49bc5032be) | Nov 01, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [9c9e8ac41c](https://linux-hardware.org/?probe=9c9e8ac41c) | Oct 24, 2020 |
| MSI           | B360M PRO-VDH               | Desktop     | [d336eeaa8d](https://linux-hardware.org/?probe=d336eeaa8d) | Oct 21, 2020 |
| Lenovo        | 3098 NOK                    | Desktop     | [2c592ebb94](https://linux-hardware.org/?probe=2c592ebb94) | Oct 19, 2020 |
| Lenovo        | 3098 NOK                    | Desktop     | [92a22bd753](https://linux-hardware.org/?probe=92a22bd753) | Oct 19, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [2e8b092dbc](https://linux-hardware.org/?probe=2e8b092dbc) | Oct 12, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [3ad72de5c7](https://linux-hardware.org/?probe=3ad72de5c7) | Oct 09, 2020 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [da4740881e](https://linux-hardware.org/?probe=da4740881e) | Oct 04, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2c625d510e](https://linux-hardware.org/?probe=2c625d510e) | Oct 03, 2020 |
| Pegatron      | 2A94h                       | Desktop     | [3a1ede6188](https://linux-hardware.org/?probe=3a1ede6188) | Oct 03, 2020 |
| Unknown       | Unknown                     | Phone       | [f4bd5779b6](https://linux-hardware.org/?probe=f4bd5779b6) | Oct 02, 2020 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [1d3401ff46](https://linux-hardware.org/?probe=1d3401ff46) | Oct 02, 2020 |
| Intel         | NUC7i3BNB J22859-302        | Mini pc     | [afa81d3409](https://linux-hardware.org/?probe=afa81d3409) | Oct 01, 2020 |
| Lenovo        | ThinkPad P53 20QN000DGE     | Notebook    | [3a0bc546cc](https://linux-hardware.org/?probe=3a0bc546cc) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [1a20b51c58](https://linux-hardware.org/?probe=1a20b51c58) | Sep 24, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [ca8c660b91](https://linux-hardware.org/?probe=ca8c660b91) | Sep 24, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8bba4f976e](https://linux-hardware.org/?probe=8bba4f976e) | Sep 20, 2020 |
| Intel         | DQ35JO AAD82085-801         | Desktop     | [51c42a0f25](https://linux-hardware.org/?probe=51c42a0f25) | Sep 17, 2020 |
| Dell          | Vostro 3550                 | Notebook    | [ef71fe525d](https://linux-hardware.org/?probe=ef71fe525d) | Sep 17, 2020 |
| Unknown       | Unknown                     | Phone       | [e49d4429f4](https://linux-hardware.org/?probe=e49d4429f4) | Sep 15, 2020 |
| Unknown       | Unknown                     | Phone       | [6354f593f4](https://linux-hardware.org/?probe=6354f593f4) | Sep 15, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [85ab9de98f](https://linux-hardware.org/?probe=85ab9de98f) | Sep 03, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [94e860aade](https://linux-hardware.org/?probe=94e860aade) | Sep 03, 2020 |
| PC Special... | Fusion IV                   | Notebook    | [55da1618ab](https://linux-hardware.org/?probe=55da1618ab) | Aug 30, 2020 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | Notebook    | [a87567fe16](https://linux-hardware.org/?probe=a87567fe16) | Aug 27, 2020 |
| HP            | ProBook 4540s               | Notebook    | [32346e7861](https://linux-hardware.org/?probe=32346e7861) | Aug 26, 2020 |
| Pegatron      | 2A73                        | Desktop     | [a4607af679](https://linux-hardware.org/?probe=a4607af679) | Aug 25, 2020 |
| Pegatron      | 2A73                        | Desktop     | [f2c225880d](https://linux-hardware.org/?probe=f2c225880d) | Aug 25, 2020 |
| HP            | 3048h                       | Desktop     | [0bc2b9bafc](https://linux-hardware.org/?probe=0bc2b9bafc) | Aug 17, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [438b0df832](https://linux-hardware.org/?probe=438b0df832) | Jul 21, 2020 |
| HP            | 2000                        | Notebook    | [1facf761c9](https://linux-hardware.org/?probe=1facf761c9) | Jul 19, 2020 |
| Lenovo        | ThinkPad T420 423662G       | Notebook    | [f0e52bdb36](https://linux-hardware.org/?probe=f0e52bdb36) | Jul 10, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [b78049616e](https://linux-hardware.org/?probe=b78049616e) | Jul 09, 2020 |
| Lenovo        | ThinkPad T480 20L6S01W00    | Notebook    | [758a8710d7](https://linux-hardware.org/?probe=758a8710d7) | Jun 29, 2020 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [c323481902](https://linux-hardware.org/?probe=c323481902) | Jun 14, 2020 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [6889f53e3b](https://linux-hardware.org/?probe=6889f53e3b) | Jun 13, 2020 |
| HP            | ProBook 4540s               | Notebook    | [98a9e4902b](https://linux-hardware.org/?probe=98a9e4902b) | Jun 08, 2020 |
| ASRock        | X570 Extreme4               | Desktop     | [add6daf97a](https://linux-hardware.org/?probe=add6daf97a) | Jun 07, 2020 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [d7dee77bfc](https://linux-hardware.org/?probe=d7dee77bfc) | Jun 04, 2020 |
| HP            | ProBook 4540s               | Notebook    | [2b515ca642](https://linux-hardware.org/?probe=2b515ca642) | May 31, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [a8e5567ca8](https://linux-hardware.org/?probe=a8e5567ca8) | May 30, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [03b36ff9c1](https://linux-hardware.org/?probe=03b36ff9c1) | May 28, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [bea6687b8b](https://linux-hardware.org/?probe=bea6687b8b) | May 27, 2020 |
| ASRock        | Z390 Pro4                   | Desktop     | [e1c0c74ca6](https://linux-hardware.org/?probe=e1c0c74ca6) | May 25, 2020 |
| Acer          | Aspire V3-771               | Notebook    | [910279b054](https://linux-hardware.org/?probe=910279b054) | May 25, 2020 |
| Lenovo        | ThinkPad X250 20CM004ESC    | Notebook    | [793c164825](https://linux-hardware.org/?probe=793c164825) | May 25, 2020 |
| MSI           | H61M-P31                    | Desktop     | [870b2534d7](https://linux-hardware.org/?probe=870b2534d7) | May 22, 2020 |
| HP            | ProBook 470 G2              | Notebook    | [d39ca7c5fa](https://linux-hardware.org/?probe=d39ca7c5fa) | May 15, 2020 |
| MSI           | H110M ECO                   | Desktop     | [fe6009a465](https://linux-hardware.org/?probe=fe6009a465) | May 15, 2020 |
| HP            | 15                          | Notebook    | [fa65501be6](https://linux-hardware.org/?probe=fa65501be6) | May 10, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [91d3944426](https://linux-hardware.org/?probe=91d3944426) | May 10, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [ee92e64256](https://linux-hardware.org/?probe=ee92e64256) | May 07, 2020 |
| HP            | ProBook 4515s (VC377ES#A... | Notebook    | [3ec25a2e7a](https://linux-hardware.org/?probe=3ec25a2e7a) | May 01, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [a1de2f2fe9](https://linux-hardware.org/?probe=a1de2f2fe9) | Apr 18, 2020 |
| Lenovo        | ThinkCentre M55e 9389W11    | Desktop     | [f148017266](https://linux-hardware.org/?probe=f148017266) | Apr 12, 2020 |
| Lenovo        | ThinkPad T590 20N5S0YN00    | Notebook    | [0efab1d69f](https://linux-hardware.org/?probe=0efab1d69f) | Apr 08, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [f9c3afb706](https://linux-hardware.org/?probe=f9c3afb706) | Apr 08, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [17dd7e6ddb](https://linux-hardware.org/?probe=17dd7e6ddb) | Apr 05, 2020 |
| Lenovo        | ThinkCentre M57e 9356W2K    | Desktop     | [663d112138](https://linux-hardware.org/?probe=663d112138) | Apr 02, 2020 |
| ASUSTek       | X750LB                      | Notebook    | [a7c5fb20f8](https://linux-hardware.org/?probe=a7c5fb20f8) | Mar 28, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [9130b68bf4](https://linux-hardware.org/?probe=9130b68bf4) | Mar 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [ff84ae40b8](https://linux-hardware.org/?probe=ff84ae40b8) | Mar 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [0877aa97e7](https://linux-hardware.org/?probe=0877aa97e7) | Mar 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [677f41b346](https://linux-hardware.org/?probe=677f41b346) | Mar 21, 2020 |
| HP            | 0A58h                       | Desktop     | [0734e4224d](https://linux-hardware.org/?probe=0734e4224d) | Mar 16, 2020 |
| Lenovo        | ThinkPad P52 20MAS5XN00     | Notebook    | [48cd703e5b](https://linux-hardware.org/?probe=48cd703e5b) | Mar 05, 2020 |
| Lenovo        | ThinkPad P52 20MAS5XN00     | Notebook    | [e6a4ad2c61](https://linux-hardware.org/?probe=e6a4ad2c61) | Mar 04, 2020 |
| HP            | EliteBook 8760w             | Notebook    | [624fd6f7fa](https://linux-hardware.org/?probe=624fd6f7fa) | Mar 01, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [9a43e8f82a](https://linux-hardware.org/?probe=9a43e8f82a) | Feb 26, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [0722f7ccf8](https://linux-hardware.org/?probe=0722f7ccf8) | Feb 22, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | Notebook    | [608fef5510](https://linux-hardware.org/?probe=608fef5510) | Feb 03, 2020 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [44e0ce8fc8](https://linux-hardware.org/?probe=44e0ce8fc8) | Jan 24, 2020 |
| Medion        | MS-7707                     | Desktop     | [3feacd8f08](https://linux-hardware.org/?probe=3feacd8f08) | Jan 19, 2020 |
| Medion        | MS-7707                     | Desktop     | [5d5096c9a8](https://linux-hardware.org/?probe=5d5096c9a8) | Jan 18, 2020 |
| Biostar       | TH55B HD                    | Desktop     | [3f28da0706](https://linux-hardware.org/?probe=3f28da0706) | Jan 17, 2020 |
| HP            | 829B                        | All in one  | [d626be0762](https://linux-hardware.org/?probe=d626be0762) | Jan 09, 2020 |
| Lenovo        | ThinkPad E590 20NB002BSC    | Notebook    | [b20e37d478](https://linux-hardware.org/?probe=b20e37d478) | Jan 06, 2020 |
| Dell          | Latitude 5500               | Notebook    | [84e2b9bc59](https://linux-hardware.org/?probe=84e2b9bc59) | Jan 03, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [0d7f336b82](https://linux-hardware.org/?probe=0d7f336b82) | Jan 03, 2020 |
| Dell          | Latitude 5500               | Notebook    | [0d946e75f9](https://linux-hardware.org/?probe=0d946e75f9) | Jan 03, 2020 |
| Dell          | Latitude 5500               | Notebook    | [be70af9da7](https://linux-hardware.org/?probe=be70af9da7) | Jan 03, 2020 |
| Biostar       | TH55B HD                    | Desktop     | [980b5da590](https://linux-hardware.org/?probe=980b5da590) | Jan 02, 2020 |
| Biostar       | TH55B HD                    | Desktop     | [e13730f188](https://linux-hardware.org/?probe=e13730f188) | Dec 25, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [d853ff31e4](https://linux-hardware.org/?probe=d853ff31e4) | Dec 08, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [25e0799d44](https://linux-hardware.org/?probe=25e0799d44) | Dec 08, 2019 |
| HP            | 1495                        | Desktop     | [d56240bfb5](https://linux-hardware.org/?probe=d56240bfb5) | Dec 07, 2019 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [de68096cdc](https://linux-hardware.org/?probe=de68096cdc) | Nov 27, 2019 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [7ad66ff018](https://linux-hardware.org/?probe=7ad66ff018) | Nov 23, 2019 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [837d7c2621](https://linux-hardware.org/?probe=837d7c2621) | Nov 23, 2019 |
| HP            | 1495                        | Desktop     | [7517e7c74d](https://linux-hardware.org/?probe=7517e7c74d) | Nov 20, 2019 |
| HP            | 1495                        | Desktop     | [b4598c0e73](https://linux-hardware.org/?probe=b4598c0e73) | Nov 19, 2019 |
| HP            | 1495                        | Desktop     | [ab3f7ddb42](https://linux-hardware.org/?probe=ab3f7ddb42) | Nov 05, 2019 |
| MSI           | GP60 2OD                    | Notebook    | [f450b0d5d4](https://linux-hardware.org/?probe=f450b0d5d4) | Oct 20, 2019 |
| HP            | 1495                        | Desktop     | [75e4e80f87](https://linux-hardware.org/?probe=75e4e80f87) | Oct 04, 2019 |
| HP            | EliteBook 6930p             | Notebook    | [b11cbf51cb](https://linux-hardware.org/?probe=b11cbf51cb) | Sep 28, 2019 |
| HP            | 1495                        | Desktop     | [470c7daaaa](https://linux-hardware.org/?probe=470c7daaaa) | Sep 20, 2019 |
| HP            | 1495                        | Desktop     | [4f34ee60db](https://linux-hardware.org/?probe=4f34ee60db) | Sep 17, 2019 |
| Lenovo        | G585 20137                  | Notebook    | [084d318c5c](https://linux-hardware.org/?probe=084d318c5c) | Sep 16, 2019 |
| Acer          | Aspire E5-573G              | Notebook    | [d2242a3cd4](https://linux-hardware.org/?probe=d2242a3cd4) | Sep 02, 2019 |
| eMachines     | G730                        | Notebook    | [af8b954f82](https://linux-hardware.org/?probe=af8b954f82) | Aug 29, 2019 |
| ASUSTek       | G751JT                      | Notebook    | [a5f96019bd](https://linux-hardware.org/?probe=a5f96019bd) | Aug 04, 2019 |
| Medion        | MS-7707                     | Desktop     | [9b50675efd](https://linux-hardware.org/?probe=9b50675efd) | Aug 03, 2019 |
| eMachines     | G730                        | Notebook    | [5073ea0163](https://linux-hardware.org/?probe=5073ea0163) | Aug 02, 2019 |
| eMachines     | G730                        | Notebook    | [4f0fa60c8d](https://linux-hardware.org/?probe=4f0fa60c8d) | Jul 31, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [4a2455eae6](https://linux-hardware.org/?probe=4a2455eae6) | Jul 28, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8d117b8f35](https://linux-hardware.org/?probe=8d117b8f35) | Jul 28, 2019 |
| HP            | Pavilion 15                 | Notebook    | [edf229fa5e](https://linux-hardware.org/?probe=edf229fa5e) | Jul 22, 2019 |
| Toshiba       | QOSMIO X500                 | Notebook    | [34905cb301](https://linux-hardware.org/?probe=34905cb301) | Jul 15, 2019 |
| ASUSTek       | G751JT                      | Notebook    | [3a17d38bdd](https://linux-hardware.org/?probe=3a17d38bdd) | Jul 09, 2019 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [ab7980dba3](https://linux-hardware.org/?probe=ab7980dba3) | Jul 01, 2019 |
| Lenovo        | ThinkPad T410 2522A92       | Notebook    | [68640c00d9](https://linux-hardware.org/?probe=68640c00d9) | Jun 09, 2019 |
| Medion        | MS-7707                     | Desktop     | [b843e52e30](https://linux-hardware.org/?probe=b843e52e30) | Jun 03, 2019 |
| HP            | Compaq 325                  | Notebook    | [4161a93030](https://linux-hardware.org/?probe=4161a93030) | May 16, 2019 |
| HP            | ProBook 4710s               | Notebook    | [54ed79f58d](https://linux-hardware.org/?probe=54ed79f58d) | May 15, 2019 |
| HP            | Compaq 325                  | Notebook    | [b9dadeece3](https://linux-hardware.org/?probe=b9dadeece3) | May 12, 2019 |
| HP            | Compaq 6720s                | Notebook    | [0e2550055b](https://linux-hardware.org/?probe=0e2550055b) | May 07, 2019 |
| Gigabyte      | P65                         | Notebook    | [6dfb59f508](https://linux-hardware.org/?probe=6dfb59f508) | May 07, 2019 |
| Lenovo        | ThinkCentre M57 6072VAM     | Desktop     | [c399cbb5f3](https://linux-hardware.org/?probe=c399cbb5f3) | May 04, 2019 |
| HP            | ZBook 14 G2                 | Notebook    | [e1463c9ca8](https://linux-hardware.org/?probe=e1463c9ca8) | Apr 23, 2019 |
| Lenovo        | ThinkPad W530 24479K4       | Notebook    | [7d56ca80ca](https://linux-hardware.org/?probe=7d56ca80ca) | Apr 22, 2019 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8ad90844e8](https://linux-hardware.org/?probe=8ad90844e8) | Apr 16, 2019 |
| Medion        | MS-7707                     | Desktop     | [71684dcee4](https://linux-hardware.org/?probe=71684dcee4) | Apr 12, 2019 |
| ASUSTek       | X751NV                      | Notebook    | [a189d47b9a](https://linux-hardware.org/?probe=a189d47b9a) | Apr 09, 2019 |
| HP            | 82C0                        | Mini pc     | [1ecda8c9db](https://linux-hardware.org/?probe=1ecda8c9db) | Apr 06, 2019 |
| HP            | 82C0                        | Mini pc     | [134dd6a268](https://linux-hardware.org/?probe=134dd6a268) | Apr 06, 2019 |
| HP            | 0A68h                       | Desktop     | [fa9c3d044f](https://linux-hardware.org/?probe=fa9c3d044f) | Mar 13, 2019 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [d304d79466](https://linux-hardware.org/?probe=d304d79466) | Mar 10, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8348d3c21e](https://linux-hardware.org/?probe=8348d3c21e) | Feb 23, 2019 |
| Dell          | Latitude E6500              | Notebook    | [abdbb02998](https://linux-hardware.org/?probe=abdbb02998) | Feb 23, 2019 |
| HP            | 82A2                        | Desktop     | [0f9aa13b55](https://linux-hardware.org/?probe=0f9aa13b55) | Feb 21, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [0407ee67e9](https://linux-hardware.org/?probe=0407ee67e9) | Feb 11, 2019 |
| Medion        | E7218                       | Notebook    | [5d97b97758](https://linux-hardware.org/?probe=5d97b97758) | Dec 16, 2018 |
| HP            | 0A68h                       | Desktop     | [7b0d921779](https://linux-hardware.org/?probe=7b0d921779) | Dec 15, 2018 |
| HP            | 0A68h                       | Desktop     | [b773c3a27d](https://linux-hardware.org/?probe=b773c3a27d) | Dec 15, 2018 |
| HP            | 0A68h                       | Desktop     | [11bcd6f218](https://linux-hardware.org/?probe=11bcd6f218) | Dec 15, 2018 |
| HP            | Unknown                     | Notebook    | [696e11ac42](https://linux-hardware.org/?probe=696e11ac42) | Nov 29, 2018 |
| HP            | Unknown                     | Notebook    | [121bf767df](https://linux-hardware.org/?probe=121bf767df) | Nov 29, 2018 |
| Lenovo        | ThinkPad Edge 326054G       | Notebook    | [6754682a3b](https://linux-hardware.org/?probe=6754682a3b) | Sep 16, 2017 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [d48dca3ee3](https://linux-hardware.org/?probe=d48dca3ee3) | Feb 18, 2017 |
| Lenovo        | ThinkPad Edge 326054G       | Notebook    | [c208f4b144](https://linux-hardware.org/?probe=c208f4b144) | Nov 24, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Slovenia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 62        | 15.35%  |
| Ubuntu 18.04        | 24        | 5.94%   |
| Ubuntu 22.04        | 23        | 5.69%   |
| OpenMandriva 4.3    | 13        | 3.22%   |
| Debian 11           | 11        | 2.72%   |
| Zorin 16            | 10        | 2.48%   |
| KDE neon 20.04      | 10        | 2.48%   |
| Ubuntu 20.10        | 8         | 1.98%   |
| Kubuntu 22.04       | 8         | 1.98%   |
| Fedora 37           | 8         | 1.98%   |
| ArcoLinux Rolling   | 8         | 1.98%   |
| Arch Rolling        | 8         | 1.98%   |
| Xubuntu 20.04       | 7         | 1.73%   |
| Ubuntu 19.10        | 6         | 1.49%   |
| Zorin 15            | 5         | 1.24%   |
| OpenMandriva 23.03  | 5         | 1.24%   |
| Linux Mint 19.3     | 5         | 1.24%   |
| Kubuntu 20.04       | 5         | 1.24%   |
| Fedora 34           | 5         | 1.24%   |
| Arch                | 5         | 1.24%   |
| Pop!_OS 22.04       | 4         | 0.99%   |
| Pop!_OS 20.04       | 4         | 0.99%   |
| OpenMandriva 4.2    | 4         | 0.99%   |
| Manjaro             | 4         | 0.99%   |
| Linux Mint 19.1     | 4         | 0.99%   |
| KDE neon 22.04      | 4         | 0.99%   |
| Fedora 33           | 4         | 0.99%   |
| Ubuntu Unity 16.04  | 3         | 0.74%   |
| Ubuntu 21.10        | 3         | 0.74%   |
| Pop!_OS 21.10       | 3         | 0.74%   |
| OpenMandriva 23.01  | 3         | 0.74%   |
| Linux Mint 20.3     | 3         | 0.74%   |
| Kubuntu 21.10       | 3         | 0.74%   |
| Gentoo 2.6          | 3         | 0.74%   |
| Fedora 35           | 3         | 0.74%   |
| EndeavourOS         | 3         | 0.74%   |
| Debian Testing      | 3         | 0.74%   |
| Xubuntu 22.04       | 2         | 0.5%    |
| Ubuntu Budgie 22.04 | 2         | 0.5%    |
| Ubuntu 21.04        | 2         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 128       | 33.33%  |
| OpenMandriva  | 24        | 6.25%   |
| Fedora        | 23        | 5.99%   |
| Kubuntu       | 21        | 5.47%   |
| Linux Mint    | 18        | 4.69%   |
| Debian        | 17        | 4.43%   |
| Pop!_OS       | 15        | 3.91%   |
| Manjaro       | 15        | 3.91%   |
| KDE neon      | 15        | 3.91%   |
| Zorin         | 14        | 3.65%   |
| Arch          | 13        | 3.39%   |
| Xubuntu       | 11        | 2.86%   |
| Endless       | 10        | 2.6%    |
| ArcoLinux     | 8         | 2.08%   |
| Gentoo        | 5         | 1.3%    |
| EndeavourOS   | 5         | 1.3%    |
| Ubuntu Unity  | 4         | 1.04%   |
| openSUSE      | 4         | 1.04%   |
| Ubuntu MATE   | 3         | 0.78%   |
| Ubuntu Budgie | 3         | 0.78%   |
| Lubuntu       | 3         | 0.78%   |
| Elementary    | 3         | 0.78%   |
| ROSA          | 2         | 0.52%   |
| LMDE          | 2         | 0.52%   |
| Kali          | 2         | 0.52%   |
| BlackPanther  | 2         | 0.52%   |
| Android       | 2         | 0.52%   |
| Ubuntu Kylin  | 1         | 0.26%   |
| RHEL          | 1         | 0.26%   |
| Q4OS          | 1         | 0.26%   |
| Nobara        | 1         | 0.26%   |
| NixOS         | 1         | 0.26%   |
| Mageia        | 1         | 0.26%   |
| Garuda Linux  | 1         | 0.26%   |
| Clear Linux   | 1         | 0.26%   |
| Chrome OS     | 1         | 0.26%   |
| CentOS        | 1         | 0.26%   |
| CachyOS       | 1         | 0.26%   |
| Artix         | 1         | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 12        | 2.71%   |
| 5.4.0-48-generic         | 7         | 1.58%   |
| 5.15.0-56-generic        | 6         | 1.36%   |
| 4.18.0-15-generic        | 6         | 1.36%   |
| 5.4.0-42-generic         | 5         | 1.13%   |
| 5.3.0-40-generic         | 5         | 1.13%   |
| 5.15.0-43-generic        | 5         | 1.13%   |
| 5.13.0-30-generic        | 5         | 1.13%   |
| 6.2.6-desktop-1omv2390   | 4         | 0.9%    |
| 5.8.0-41-generic         | 4         | 0.9%    |
| 5.15.0-47-generic        | 4         | 0.9%    |
| 5.15.0-46-generic        | 4         | 0.9%    |
| 5.15.0-25-generic        | 4         | 0.9%    |
| 5.13.0-41-generic        | 4         | 0.9%    |
| 5.13.0-28-generic        | 4         | 0.9%    |
| 5.11.0-43-generic        | 4         | 0.9%    |
| 5.11.0-40-generic        | 4         | 0.9%    |
| 5.10.14-desktop-1omv4002 | 4         | 0.9%    |
| 5.8.0-43-generic         | 3         | 0.68%   |
| 5.8.0-36-generic         | 3         | 0.68%   |
| 5.8.0-14-generic         | 3         | 0.68%   |
| 5.4.0-70-generic         | 3         | 0.68%   |
| 5.4.0-60-generic         | 3         | 0.68%   |
| 5.4.0-54-generic         | 3         | 0.68%   |
| 5.4.0-52-generic         | 3         | 0.68%   |
| 5.4.0-31-generic         | 3         | 0.68%   |
| 5.4.0-29-generic         | 3         | 0.68%   |
| 5.4.0-26-generic         | 3         | 0.68%   |
| 5.3.0-26-generic         | 3         | 0.68%   |
| 5.15.0-57-generic        | 3         | 0.68%   |
| 5.13.0-21-generic        | 3         | 0.68%   |
| 4.18.0-17-generic        | 3         | 0.68%   |
| 6.3.9-arch1-1            | 2         | 0.45%   |
| 6.2.6-76060206-generic   | 2         | 0.45%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.45%   |
| 5.9.2-arch1-1            | 2         | 0.45%   |
| 5.8.0-7630-generic       | 2         | 0.45%   |
| 5.8.0-53-generic         | 2         | 0.45%   |
| 5.8.0-44-generic         | 2         | 0.45%   |
| 5.6.14-desktop-2bP       | 2         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 70        | 16.71%  |
| 5.15.0  | 40        | 9.55%   |
| 5.8.0   | 28        | 6.68%   |
| 5.13.0  | 26        | 6.21%   |
| 5.11.0  | 20        | 4.77%   |
| 4.15.0  | 17        | 4.06%   |
| 5.3.0   | 16        | 3.82%   |
| 4.18.0  | 16        | 3.82%   |
| 5.16.7  | 13        | 3.1%    |
| 5.10.0  | 12        | 2.86%   |
| 5.19.0  | 9         | 2.15%   |
| 5.0.0   | 7         | 1.67%   |
| 6.2.6   | 6         | 1.43%   |
| 5.10.14 | 6         | 1.43%   |
| 5.6.0   | 4         | 0.95%   |
| 6.4.7   | 2         | 0.48%   |
| 6.4.3   | 2         | 0.48%   |
| 6.3.9   | 2         | 0.48%   |
| 6.2.8   | 2         | 0.48%   |
| 6.2.10  | 2         | 0.48%   |
| 6.1.1   | 2         | 0.48%   |
| 6.1.0   | 2         | 0.48%   |
| 6.0.11  | 2         | 0.48%   |
| 5.9.2   | 2         | 0.48%   |
| 5.9.15  | 2         | 0.48%   |
| 5.6.14  | 2         | 0.48%   |
| 5.17.5  | 2         | 0.48%   |
| 5.17.1  | 2         | 0.48%   |
| 5.16.15 | 2         | 0.48%   |
| 5.16.13 | 2         | 0.48%   |
| 5.15.2  | 2         | 0.48%   |
| 5.14.16 | 2         | 0.48%   |
| 5.14.0  | 2         | 0.48%   |
| 5.13.19 | 2         | 0.48%   |
| 5.12.8  | 2         | 0.48%   |
| 5.12.4  | 2         | 0.48%   |
| 5.10.30 | 2         | 0.48%   |
| 4.18.16 | 2         | 0.48%   |
| 6.4.9   | 1         | 0.24%   |
| 6.4.0   | 1         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 73        | 17.68%  |
| 5.15    | 50        | 12.11%  |
| 5.8     | 33        | 7.99%   |
| 5.13    | 30        | 7.26%   |
| 5.11    | 23        | 5.57%   |
| 5.16    | 21        | 5.08%   |
| 5.10    | 21        | 5.08%   |
| 4.18    | 18        | 4.36%   |
| 5.3     | 17        | 4.12%   |
| 4.15    | 17        | 4.12%   |
| 6.2     | 14        | 3.39%   |
| 6.1     | 13        | 3.15%   |
| 5.19    | 13        | 3.15%   |
| 5.17    | 7         | 1.69%   |
| 5.14    | 7         | 1.69%   |
| 5.12    | 7         | 1.69%   |
| 5.0     | 7         | 1.69%   |
| 6.4     | 6         | 1.45%   |
| 6.0     | 6         | 1.45%   |
| 5.6     | 6         | 1.45%   |
| 5.9     | 5         | 1.21%   |
| 6.3     | 4         | 0.97%   |
| 5.7     | 2         | 0.48%   |
| 5.5     | 2         | 0.48%   |
| 5.18    | 2         | 0.48%   |
| 4.19    | 2         | 0.48%   |
| 4.1     | 2         | 0.48%   |
| 3.18    | 2         | 0.48%   |
| 4.9     | 1         | 0.24%   |
| 4.20    | 1         | 0.24%   |
| 4.14    | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 348       | 95.6%   |
| i686    | 9         | 2.47%   |
| aarch64 | 5         | 1.37%   |
| armv8l  | 2         | 0.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 157       | 40.67%  |
| KDE5            | 83        | 21.5%   |
| Unknown         | 50        | 12.95%  |
| XFCE            | 32        | 8.29%   |
| X-Cinnamon      | 15        | 3.89%   |
| KDE             | 9         | 2.33%   |
| Cinnamon        | 6         | 1.55%   |
| MATE            | 5         | 1.3%    |
| LXQt            | 5         | 1.3%    |
| Unity           | 4         | 1.04%   |
| Pantheon        | 3         | 0.78%   |
| i3              | 3         | 0.78%   |
| Budgie          | 3         | 0.78%   |
| LXDE            | 2         | 0.52%   |
| DWM             | 2         | 0.52%   |
| UKUI            | 1         | 0.26%   |
| Trinity         | 1         | 0.26%   |
| Openbox         | 1         | 0.26%   |
| NsCDE           | 1         | 0.26%   |
| none+awesome    | 1         | 0.26%   |
| KDE4            | 1         | 0.26%   |
| GNOME Flashback | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 280       | 74.07%  |
| Wayland | 54        | 14.29%  |
| Unknown | 32        | 8.47%   |
| Tty     | 12        | 3.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 174       | 45.43%  |
| SDDM    | 73        | 19.06%  |
| LightDM | 41        | 10.7%   |
| GDM     | 41        | 10.7%   |
| GDM3    | 38        | 9.92%   |
| TDM     | 14        | 3.66%   |
| XDM     | 1         | 0.26%   |
| KDM     | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 194       | 52.01%  |
| sl_SI   | 93        | 24.93%  |
| Unknown | 46        | 12.33%  |
| en_GB   | 17        | 4.56%   |
| C       | 8         | 2.14%   |
| it_IT   | 4         | 1.07%   |
| en_SI   | 4         | 1.07%   |
| de_AT   | 2         | 0.54%   |
| pt_PT   | 1         | 0.27%   |
| nl_NL   | 1         | 0.27%   |
| hr_HR   | 1         | 0.27%   |
| en_BW   | 1         | 0.27%   |
| de_DE   | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 193       | 51.33%  |
| BIOS | 183       | 48.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 286       | 76.27%  |
| Overlay | 34        | 9.07%   |
| Btrfs   | 28        | 7.47%   |
| Unknown | 16        | 4.27%   |
| Zfs     | 5         | 1.33%   |
| Xfs     | 4         | 1.07%   |
| Tmpfs   | 1         | 0.27%   |
| Ext2    | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 185       | 49.47%  |
| GPT     | 138       | 36.9%   |
| MBR     | 51        | 13.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 321       | 86.06%  |
| Yes       | 52        | 13.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 261       | 70.54%  |
| Yes       | 109       | 29.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 80        | 21.98%  |
| ASUSTek Computer        | 69        | 18.96%  |
| Lenovo                  | 66        | 18.13%  |
| Gigabyte Technology     | 25        | 6.87%   |
| Dell                    | 23        | 6.32%   |
| ASRock                  | 17        | 4.67%   |
| MSI                     | 16        | 4.4%    |
| Toshiba                 | 9         | 2.47%   |
| Acer                    | 8         | 2.2%    |
| Intel                   | 7         | 1.92%   |
| Raspberry Pi Foundation | 5         | 1.37%   |
| Medion                  | 5         | 1.37%   |
| Fujitsu                 | 5         | 1.37%   |
| Pegatron                | 4         | 1.1%    |
| Apple                   | 4         | 1.1%    |
| Unknown                 | 3         | 0.82%   |
| TUXEDO                  | 2         | 0.55%   |
| Supermicro              | 2         | 0.55%   |
| Fujitsu Siemens         | 2         | 0.55%   |
| Schenker                | 1         | 0.27%   |
| Razer                   | 1         | 0.27%   |
| PC Specialist           | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| Nvidia                  | 1         | 0.27%   |
| Microsoft               | 1         | 0.27%   |
| IBM                     | 1         | 0.27%   |
| HUAWEI                  | 1         | 0.27%   |
| Framework               | 1         | 0.27%   |
| eMachines               | 1         | 0.27%   |
| Biostar                 | 1         | 0.27%   |
| AZW                     | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 5         | 1.37%   |
| MSI MS-7C02                                | 4         | 1.1%    |
| HP 255 G7 Notebook PC                      | 3         | 0.82%   |
| Toshiba Satellite L750                     | 2         | 0.55%   |
| RPi Raspberry Pi 400 Rev 1.0               | 2         | 0.55%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 2         | 0.55%   |
| Pegatron FL308AA-ABD IQ512de               | 2         | 0.55%   |
| MSI MS-7C37                                | 2         | 0.55%   |
| MSI MS-7788                                | 2         | 0.55%   |
| Lenovo ThinkPad T410 2522A92               | 2         | 0.55%   |
| HP Spectre x360 Convertible 13-ae0xx       | 2         | 0.55%   |
| HP ProBook 4730s                           | 2         | 0.55%   |
| HP EliteBook 8760w                         | 2         | 0.55%   |
| HP 255 G8 Notebook PC                      | 2         | 0.55%   |
| Gigabyte F2A88XM-D3HP                      | 2         | 0.55%   |
| Gigabyte B450M DS3H                        | 2         | 0.55%   |
| Dell XPS 13 9310                           | 2         | 0.55%   |
| Dell Latitude D630                         | 2         | 0.55%   |
| Dell Inspiron 5570                         | 2         | 0.55%   |
| Dell Inspiron 1501                         | 2         | 0.55%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 0.55%   |
| ASUS TUF B450-PLUS GAMING                  | 2         | 0.55%   |
| ASUS ROG STRIX Z370-F GAMING               | 2         | 0.55%   |
| ASUS ROG STRIX X570-E GAMING               | 2         | 0.55%   |
| ASUS PRIME B350-PLUS                       | 2         | 0.55%   |
| ASUS PRIME A320M-K                         | 2         | 0.55%   |
| ASUS P7H55-M SI                            | 2         | 0.55%   |
| ASUS All Series                            | 2         | 0.55%   |
| TUXEDO Polaris AMD Gen2 (REN)              | 1         | 0.27%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.27%   |
| Toshiba TECRA S10                          | 1         | 0.27%   |
| Toshiba TECRA A11                          | 1         | 0.27%   |
| Toshiba Satellite R630                     | 1         | 0.27%   |
| Toshiba Satellite Pro U400                 | 1         | 0.27%   |
| Toshiba Satellite Pro R50-E                | 1         | 0.27%   |
| Toshiba Satellite A100                     | 1         | 0.27%   |
| Toshiba QOSMIO X500                        | 1         | 0.27%   |
| Supermicro X7SBi-LN4                       | 1         | 0.27%   |
| Supermicro PCplus T600-C246                | 1         | 0.27%   |
| Schenker XMG FUSION 15 (XFU15M22)          | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 36        | 9.89%   |
| HP ProBook            | 13        | 3.57%   |
| ASUS PRIME            | 13        | 3.57%   |
| HP EliteBook          | 12        | 3.3%    |
| Lenovo ThinkCentre    | 8         | 2.2%    |
| Dell Inspiron         | 8         | 2.2%    |
| ASUS ROG              | 8         | 2.2%    |
| Lenovo IdeaPad        | 7         | 1.92%   |
| HP ZBook              | 7         | 1.92%   |
| HP Compaq             | 7         | 1.92%   |
| Dell Latitude         | 7         | 1.92%   |
| ASUS TUF              | 7         | 1.92%   |
| Toshiba Satellite     | 6         | 1.65%   |
| RPi Raspberry         | 5         | 1.37%   |
| HP Pavilion           | 5         | 1.37%   |
| HP 255                | 5         | 1.37%   |
| Unknown               | 5         | 1.37%   |
| MSI MS-7C02           | 4         | 1.1%    |
| HP EliteDesk          | 4         | 1.1%    |
| HP 250                | 4         | 1.1%    |
| Fujitsu LIFEBOOK      | 4         | 1.1%    |
| Dell XPS              | 4         | 1.1%    |
| ASUS VivoBook         | 4         | 1.1%    |
| ASUS ASUS             | 4         | 1.1%    |
| Acer Aspire           | 4         | 1.1%    |
| Gigabyte B450M        | 3         | 0.82%   |
| Toshiba TECRA         | 2         | 0.55%   |
| Pegatron FL308AA-ABD  | 2         | 0.55%   |
| MSI MS-7C37           | 2         | 0.55%   |
| MSI MS-7788           | 2         | 0.55%   |
| Lenovo Yoga           | 2         | 0.55%   |
| Lenovo ThinkStation   | 2         | 0.55%   |
| Lenovo Legion         | 2         | 0.55%   |
| HP Spectre            | 2         | 0.55%   |
| HP Laptop             | 2         | 0.55%   |
| Gigabyte F2A88XM-D3HP | 2         | 0.55%   |
| Dell Precision        | 2         | 0.55%   |
| ASUS SABERTOOTH       | 2         | 0.55%   |
| ASUS P7H55-M          | 2         | 0.55%   |
| ASUS All              | 2         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 39        | 10.71%  |
| 2020    | 33        | 9.07%   |
| 2018    | 31        | 8.52%   |
| 2017    | 29        | 7.97%   |
| 2011    | 29        | 7.97%   |
| 2009    | 24        | 6.59%   |
| 2015    | 23        | 6.32%   |
| 2013    | 23        | 6.32%   |
| 2014    | 19        | 5.22%   |
| 2010    | 19        | 5.22%   |
| 2021    | 16        | 4.4%    |
| 2012    | 16        | 4.4%    |
| 2008    | 16        | 4.4%    |
| 2016    | 11        | 3.02%   |
| 2007    | 10        | 2.75%   |
| 2006    | 9         | 2.47%   |
| Unknown | 7         | 1.92%   |
| 2022    | 6         | 1.65%   |
| 2023    | 4         | 1.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 193       | 53.02%  |
| Desktop        | 141       | 38.74%  |
| All in one     | 6         | 1.65%   |
| System on chip | 5         | 1.37%   |
| Convertible    | 5         | 1.37%   |
| Mini pc        | 5         | 1.37%   |
| Server         | 4         | 1.1%    |
| Tablet         | 3         | 0.82%   |
| Phone          | 2         | 0.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 339       | 92.37%  |
| Enabled  | 28        | 7.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 363       | 99.73%  |
| Yes  | 1         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 81        | 22.01%  |
| 16.01-24.0      | 78        | 21.2%   |
| 8.01-16.0       | 74        | 20.11%  |
| 4.01-8.0        | 57        | 15.49%  |
| 32.01-64.0      | 39        | 10.6%   |
| 2.01-3.0        | 10        | 2.72%   |
| 1.01-2.0        | 10        | 2.72%   |
| 64.01-256.0     | 8         | 2.17%   |
| 24.01-32.0      | 6         | 1.63%   |
| 0.51-1.0        | 3         | 0.82%   |
| More than 256.0 | 2         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 133       | 32.2%   |
| 2.01-3.0   | 98        | 23.73%  |
| 4.01-8.0   | 65        | 15.74%  |
| 3.01-4.0   | 53        | 12.83%  |
| 0.51-1.0   | 28        | 6.78%   |
| 8.01-16.0  | 22        | 5.33%   |
| 0.01-0.5   | 7         | 1.69%   |
| 16.01-24.0 | 5         | 1.21%   |
| 24.01-32.0 | 2         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 227       | 60.05%  |
| 2      | 88        | 23.28%  |
| 3      | 27        | 7.14%   |
| 4      | 12        | 3.17%   |
| 5      | 7         | 1.85%   |
| 0      | 6         | 1.59%   |
| 6      | 5         | 1.32%   |
| 8      | 3         | 0.79%   |
| 7      | 2         | 0.53%   |
| 11     | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 213       | 58.2%   |
| Yes       | 153       | 41.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 327       | 89.34%  |
| No        | 39        | 10.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 253       | 69.13%  |
| No        | 113       | 30.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 56.28%  |
| No        | 160       | 43.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Slovenia | 364       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 133       | 33.17%  |
| Kranj                   | 14        | 3.49%   |
| Maribor                 | 12        | 2.99%   |
| Celje                   | 10        | 2.49%   |
| Vrhnika                 | 9         | 2.24%   |
| Koper                   | 9         | 2.24%   |
| Trzin                   | 8         | 2%      |
| Novo Mesto              | 7         | 1.75%   |
| Kamnik                  | 6         | 1.5%    |
| Žalec                  | 5         | 1.25%   |
| Sempeter pri Gorici     | 5         | 1.25%   |
| Poljane nad Skofjo Loko | 5         | 1.25%   |
| Grosuplje               | 5         | 1.25%   |
| Slovenske Konjice       | 4         | 1%      |
| Škofja Loka            | 4         | 1%      |
| Rence                   | 4         | 1%      |
| Portorož               | 4         | 1%      |
| Nova Gorica             | 4         | 1%      |
| Domžale                | 4         | 1%      |
| Ajdovščina            | 4         | 1%      |
| Radovljica              | 3         | 0.75%   |
| Ptuj                    | 3         | 0.75%   |
| Pragersko               | 3         | 0.75%   |
| Petrovce                | 3         | 0.75%   |
| Murska Sobota           | 3         | 0.75%   |
| Logatec                 | 3         | 0.75%   |
| Crensovci               | 3         | 0.75%   |
| Ziri                    | 2         | 0.5%    |
| Zgornja Besnica         | 2         | 0.5%    |
| Velike Lašče          | 2         | 0.5%    |
| Velenje                 | 2         | 0.5%    |
| Trzic                   | 2         | 0.5%    |
| Sostanj                 | 2         | 0.5%    |
| Smarje pri Jelsah       | 2         | 0.5%    |
| Slovenj Gradec          | 2         | 0.5%    |
| Sežana                 | 2         | 0.5%    |
| Šentjur pri Celju      | 2         | 0.5%    |
| Puconci                 | 2         | 0.5%    |
| Postojna                | 2         | 0.5%    |
| Oplotnica               | 2         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 91        | 157    | 17.27%  |
| Samsung Electronics     | 79        | 126    | 14.99%  |
| Seagate                 | 54        | 82     | 10.25%  |
| Kingston                | 39        | 52     | 7.4%    |
| Toshiba                 | 38        | 54     | 7.21%   |
| Crucial                 | 35        | 49     | 6.64%   |
| SanDisk                 | 24        | 29     | 4.55%   |
| Unknown                 | 20        | 24     | 3.8%    |
| SK hynix                | 14        | 19     | 2.66%   |
| Hitachi                 | 14        | 17     | 2.66%   |
| HGST                    | 13        | 14     | 2.47%   |
| Intel                   | 10        | 11     | 1.9%    |
| Micron Technology       | 8         | 9      | 1.52%   |
| Intenso                 | 7         | 9      | 1.33%   |
| KIOXIA                  | 6         | 6      | 1.14%   |
| Corsair                 | 6         | 9      | 1.14%   |
| OCZ                     | 5         | 9      | 0.95%   |
| JMicron Technology      | 5         | 5      | 0.95%   |
| PNY                     | 4         | 4      | 0.76%   |
| Fujitsu                 | 4         | 5      | 0.76%   |
| Transcend               | 3         | 4      | 0.57%   |
| Silicon Motion          | 3         | 4      | 0.57%   |
| Patriot                 | 3         | 5      | 0.57%   |
| Apacer                  | 3         | 5      | 0.57%   |
| Team                    | 2         | 2      | 0.38%   |
| SPCC                    | 2         | 3      | 0.38%   |
| LITEONIT                | 2         | 3      | 0.38%   |
| LITEON                  | 2         | 2      | 0.38%   |
| Leven                   | 2         | 2      | 0.38%   |
| Lenovo                  | 2         | 2      | 0.38%   |
| KingDian                | 2         | 2      | 0.38%   |
| Hewlett-Packard         | 2         | 2      | 0.38%   |
| Gigabyte Technology     | 2         | 4      | 0.38%   |
| China                   | 2         | 2      | 0.38%   |
| Apple                   | 2         | 3      | 0.38%   |
| A-DATA Technology       | 2         | 3      | 0.38%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.19%   |
| TS512GMT                | 1         | 5      | 0.19%   |
| SABRENT                 | 1         | 1      | 0.19%   |
| Realtek                 | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 10        | 1.69%   |
| Crucial CT240BX500SSD1 240GB                        | 9         | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 7         | 1.18%   |
| Toshiba DT01ACA100 1TB                              | 6         | 1.01%   |
| Samsung SSD 850 EVO 250GB                           | 6         | 1.01%   |
| Samsung NVMe SSD Drive 256GB                        | 6         | 1.01%   |
| Samsung NVMe SSD Drive 512GB                        | 5         | 0.84%   |
| Kingston SA400S37120G 120GB SSD                     | 5         | 0.84%   |
| HGST HTS721010A9E630 1TB                            | 5         | 0.84%   |
| WDC WD10EARS-00Y5B1 1TB                             | 4         | 0.67%   |
| Unknown MMC Card  16GB                              | 4         | 0.67%   |
| Toshiba HDWD120 2TB                                 | 4         | 0.67%   |
| SanDisk SSD PLUS 1000GB                             | 4         | 0.67%   |
| Samsung SSD 980 1TB                                 | 4         | 0.67%   |
| Kingston SUV400S37240G 240GB SSD                    | 4         | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 3         | 0.51%   |
| WDC WD5000AADS-00S9B0 500GB                         | 3         | 0.51%   |
| Unknown MMC Card  32GB                              | 3         | 0.51%   |
| Toshiba DT01ACA200 2TB                              | 3         | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.51%   |
| SanDisk NVMe SSD Drive 512GB                        | 3         | 0.51%   |
| SanDisk NVMe SSD Drive 500GB                        | 3         | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB                      | 3         | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.51%   |
| Samsung SSD 860 EVO 1TB                             | 3         | 0.51%   |
| Samsung SSD 850 EVO 500GB                           | 3         | 0.51%   |
| PNY CS900 120GB SSD                                 | 3         | 0.51%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 0.51%   |
| JMicron Generic 512GB                               | 3         | 0.51%   |
| Intenso 128GB                                       | 3         | 0.51%   |
| Hitachi HTS547575A9E384 752GB                       | 3         | 0.51%   |
| HGST HTS545050A7E680 500GB                          | 3         | 0.51%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.51%   |
| Crucial CT2000MX500SSD1 2TB                         | 3         | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.51%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 2         | 0.34%   |
| WDC WDS500G2B0A 500GB SSD                           | 2         | 0.34%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 2         | 0.34%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 2         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 70        | 125    | 36.08%  |
| Seagate             | 52        | 78     | 26.8%   |
| Toshiba             | 28        | 41     | 14.43%  |
| Hitachi             | 14        | 17     | 7.22%   |
| HGST                | 13        | 14     | 6.7%    |
| Fujitsu             | 4         | 5      | 2.06%   |
| JMicron Technology  | 3         | 3      | 1.55%   |
| Samsung Electronics | 2         | 2      | 1.03%   |
| Unknown             | 1         | 1      | 0.52%   |
| SABRENT             | 1         | 1      | 0.52%   |
| Maxtor              | 1         | 1      | 0.52%   |
| Intenso             | 1         | 1      | 0.52%   |
| IBM-ESXS            | 1         | 1      | 0.52%   |
| HGST HTS            | 1         | 1      | 0.52%   |
| ASMT109x            | 1         | 1      | 0.52%   |
| Apple               | 1         | 2      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 53     | 18.32%  |
| Kingston            | 33        | 41     | 17.28%  |
| Crucial             | 33        | 47     | 17.28%  |
| WDC                 | 18        | 21     | 9.42%   |
| SanDisk             | 14        | 17     | 7.33%   |
| Intel               | 6         | 7      | 3.14%   |
| OCZ                 | 5         | 9      | 2.62%   |
| SK hynix            | 4         | 4      | 2.09%   |
| PNY                 | 4         | 4      | 2.09%   |
| Corsair             | 4         | 7      | 2.09%   |
| Transcend           | 3         | 4      | 1.57%   |
| Patriot             | 3         | 5      | 1.57%   |
| Micron Technology   | 3         | 3      | 1.57%   |
| Intenso             | 3         | 3      | 1.57%   |
| Toshiba             | 2         | 2      | 1.05%   |
| LITEONIT            | 2         | 3      | 1.05%   |
| LITEON              | 2         | 2      | 1.05%   |
| Leven               | 2         | 2      | 1.05%   |
| KingDian            | 2         | 2      | 1.05%   |
| China               | 2         | 2      | 1.05%   |
| Apacer              | 2         | 3      | 1.05%   |
| A-DATA Technology   | 2         | 3      | 1.05%   |
| Team                | 1         | 1      | 0.52%   |
| SPCC                | 1         | 1      | 0.52%   |
| Netac               | 1         | 1      | 0.52%   |
| JMicron Technology  | 1         | 1      | 0.52%   |
| Integral            | 1         | 1      | 0.52%   |
| GOODRAM             | 1         | 1      | 0.52%   |
| Gigabyte Technology | 1         | 2      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 165       | 294    | 34.52%  |
| SSD     | 163       | 252    | 34.1%   |
| NVMe    | 124       | 174    | 25.94%  |
| MMC     | 17        | 21     | 3.56%   |
| Unknown | 9         | 16     | 1.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 265       | 533    | 62.06%  |
| NVMe | 124       | 173    | 29.04%  |
| SAS  | 21        | 30     | 4.92%   |
| MMC  | 17        | 21     | 3.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 202       | 320    | 58.38%  |
| 0.51-1.0   | 98        | 154    | 28.32%  |
| 1.01-2.0   | 26        | 39     | 7.51%   |
| 3.01-4.0   | 9         | 17     | 2.6%    |
| 4.01-10.0  | 6         | 10     | 1.73%   |
| 2.01-3.0   | 3         | 4      | 0.87%   |
| 10.01-20.0 | 2         | 2      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 99        | 25.26%  |
| 251-500        | 82        | 20.92%  |
| 501-1000       | 51        | 13.01%  |
| 1001-2000      | 36        | 9.18%   |
| 1-20           | 36        | 9.18%   |
| 51-100         | 25        | 6.38%   |
| More than 3000 | 17        | 4.34%   |
| 21-50          | 16        | 4.08%   |
| 2001-3000      | 16        | 4.08%   |
| Unknown        | 14        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 154       | 38.5%   |
| 21-50          | 59        | 14.75%  |
| 51-100         | 54        | 13.5%   |
| 101-250        | 52        | 13%     |
| 251-500        | 27        | 6.75%   |
| 501-1000       | 15        | 3.75%   |
| 1001-2000      | 14        | 3.5%    |
| Unknown        | 14        | 3.5%    |
| 2001-3000      | 8         | 2%      |
| More than 3000 | 3         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB                       | 2         | 3      | 4.17%   |
| HGST HTS545050A7E680 500GB                     | 2         | 2      | 4.17%   |
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 2.08%   |
| WDC WD800BD-22LRA0 80GB                        | 1         | 1      | 2.08%   |
| WDC WD5000AADS-00S9B0 500GB                    | 1         | 2      | 2.08%   |
| WDC WD40EZRX-00SPEB0 4TB                       | 1         | 1      | 2.08%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 1      | 2.08%   |
| WDC WD3200AAKS-22B3A0 320GB                    | 1         | 1      | 2.08%   |
| WDC WD2500AAJS-08L7A0 250GB                    | 1         | 1      | 2.08%   |
| Toshiba Q300. 240GB SSD                        | 1         | 1      | 2.08%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 5      | 2.08%   |
| Toshiba DT01ACA300 3TB                         | 1         | 1      | 2.08%   |
| SK hynix HFS256G32MND-2200A 256GB SSD          | 1         | 1      | 2.08%   |
| Seagate ST98823AS 80GB                         | 1         | 2      | 2.08%   |
| Seagate ST9750420AS 752GB                      | 1         | 1      | 2.08%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 2.08%   |
| Seagate ST9500325AS 500GB                      | 1         | 2      | 2.08%   |
| Seagate ST9160314AS 160GB                      | 1         | 1      | 2.08%   |
| Seagate ST3500514NS 500GB                      | 1         | 1      | 2.08%   |
| Seagate ST3500320NS 500GB                      | 1         | 1      | 2.08%   |
| Seagate ST3320620AS 320GB                      | 1         | 1      | 2.08%   |
| Seagate ST3200822AS 200GB                      | 1         | 1      | 2.08%   |
| Seagate ST2000DM001-1CH164 2TB                 | 1         | 1      | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 2.08%   |
| Seagate ST1000DM003-1CH162 1TB                 | 1         | 2      | 2.08%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 2.08%   |
| SanDisk SSD PLUS 1000GB                        | 1         | 1      | 2.08%   |
| SanDisk SD7SB2Q512G1001 512GB SSD              | 1         | 1      | 2.08%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 2.08%   |
| Samsung Electronics SSD 850 EVO 250GB          | 1         | 1      | 2.08%   |
| Samsung Electronics SSD 840 Series 120GB       | 1         | 1      | 2.08%   |
| OCZ VERTEX3 120GB SSD                          | 1         | 2      | 2.08%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 2.08%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 2.08%   |
| Kingston SA400S37240G 240GB SSD                | 1         | 1      | 2.08%   |
| Intel SSDSCKKW240H6 240GB                      | 1         | 1      | 2.08%   |
| Intel SSDSA2M160G2GC 160GB                     | 1         | 1      | 2.08%   |
| Hitachi HTS727550A9E364 500GB                  | 1         | 1      | 2.08%   |
| Hitachi HTS543280L9SA00 80GB                   | 1         | 1      | 2.08%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 15     | 22.22%  |
| WDC                 | 8         | 11     | 17.78%  |
| HGST                | 5         | 5      | 11.11%  |
| Toshiba             | 3         | 7      | 6.67%   |
| SanDisk             | 3         | 3      | 6.67%   |
| Samsung Electronics | 3         | 3      | 6.67%   |
| Crucial             | 3         | 3      | 6.67%   |
| Kingston            | 2         | 2      | 4.44%   |
| Intel               | 2         | 2      | 4.44%   |
| Hitachi             | 2         | 2      | 4.44%   |
| SK hynix            | 1         | 1      | 2.22%   |
| OCZ                 | 1         | 2      | 2.22%   |
| Micron Technology   | 1         | 1      | 2.22%   |
| Hewlett-Packard     | 1         | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 15     | 38.46%  |
| WDC     | 7         | 10     | 26.92%  |
| HGST    | 5         | 5      | 19.23%  |
| Toshiba | 2         | 6      | 7.69%   |
| Hitachi | 2         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 38     | 56.1%   |
| SSD  | 16        | 18     | 39.02%  |
| NVMe | 2         | 2      | 4.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MK6465GSX 640GB                          | 1         | 2      | 33.33%  |
| SPCC M.2 PCIe SSD 2TB                            | 1         | 1      | 33.33%  |
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 2      | 33.33%  |
| SPCC                | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 211       | 382    | 52.36%  |
| Works    | 150       | 313    | 37.22%  |
| Malfunc  | 39        | 58     | 9.68%   |
| Failed   | 3         | 4      | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 243       | 51.59%  |
| AMD                              | 67        | 14.23%  |
| Samsung Electronics              | 55        | 11.68%  |
| SanDisk                          | 20        | 4.25%   |
| Toshiba America Info Systems     | 11        | 2.34%   |
| SK hynix                         | 10        | 2.12%   |
| Kingston Technology Company      | 8         | 1.7%    |
| Silicon Motion                   | 6         | 1.27%   |
| Phison Electronics               | 6         | 1.27%   |
| JMicron Technology               | 6         | 1.27%   |
| ASMedia Technology               | 6         | 1.27%   |
| Micron Technology                | 5         | 1.06%   |
| Marvell Technology Group         | 5         | 1.06%   |
| Nvidia                           | 4         | 0.85%   |
| KIOXIA                           | 4         | 0.85%   |
| Micron/Crucial Technology        | 2         | 0.42%   |
| Lenovo                           | 2         | 0.42%   |
| Union Memory (Shenzhen)          | 1         | 0.21%   |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |
| Silicon Image                    | 1         | 0.21%   |
| Shenzhen Longsys Electronics     | 1         | 0.21%   |
| Seagate Technology               | 1         | 0.21%   |
| OCZ Technology Group             | 1         | 0.21%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.21%   |
| LSI Logic / Symbios Logic        | 1         | 0.21%   |
| Integrated Technology Express    | 1         | 0.21%   |
| Hewlett-Packard                  | 1         | 0.21%   |
| Broadcom / LSI                   | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 46        | 8.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 31        | 5.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16        | 2.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 14        | 2.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14        | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 2.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 12        | 2.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 1.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 9         | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.65%   |
| Samsung NVMe SSD Controller 980                                                         | 8         | 1.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 8         | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 1.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 1.46%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 7         | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7         | 1.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 6         | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 1.1%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 5         | 0.91%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 5         | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 0.91%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5         | 0.91%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5         | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5         | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 0.91%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5         | 0.91%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 4         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 254       | 54.27%  |
| NVMe | 128       | 27.35%  |
| IDE  | 60        | 12.82%  |
| RAID | 23        | 4.91%   |
| SAS  | 2         | 0.43%   |
| SCSI | 1         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 279       | 76.65%  |
| AMD    | 78        | 21.43%  |
| ARM    | 7         | 1.92%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.37%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.37%   |
| ARM Processor                                 | 5         | 1.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.1%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 1.1%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 4         | 1.1%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 4         | 1.1%    |
| AMD Ryzen 3 5300U with Radeon Graphics        | 4         | 1.1%    |
| Intel Pentium CPU P6100 @ 2.00GHz             | 3         | 0.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.82%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 3         | 0.82%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 0.82%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.82%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 0.82%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 3         | 0.82%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 0.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.82%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.82%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.55%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.55%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.55%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.55%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.55%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.55%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.55%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.55%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 0.55%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.55%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2         | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 81        | 22.25%  |
| Intel Core i7           | 73        | 20.05%  |
| Intel Core 2 Duo        | 29        | 7.97%   |
| Intel Core i3           | 25        | 6.87%   |
| Other                   | 23        | 6.32%   |
| AMD Ryzen 5             | 23        | 6.32%   |
| AMD Ryzen 7             | 15        | 4.12%   |
| Intel Celeron           | 14        | 3.85%   |
| Intel Xeon              | 11        | 3.02%   |
| Intel Pentium           | 10        | 2.75%   |
| AMD Ryzen 9             | 9         | 2.47%   |
| AMD Ryzen 3             | 9         | 2.47%   |
| Intel Core 2            | 4         | 1.1%    |
| Intel Atom              | 4         | 1.1%    |
| Intel Core 2 Quad       | 3         | 0.82%   |
| Intel Genuine           | 2         | 0.55%   |
| AMD Phenom II X6        | 2         | 0.55%   |
| AMD FX                  | 2         | 0.55%   |
| AMD Athlon 64 X2        | 2         | 0.55%   |
| AMD A10                 | 2         | 0.55%   |
| Intel Xeon Gold         | 1         | 0.27%   |
| Intel Pentium Silver    | 1         | 0.27%   |
| Intel Pentium Dual-Core | 1         | 0.27%   |
| Intel Pentium Dual      | 1         | 0.27%   |
| Intel Pentium D         | 1         | 0.27%   |
| Intel Core i9           | 1         | 0.27%   |
| ARM AArch64             | 1         | 0.27%   |
| AMD Turion II Dual-Core | 1         | 0.27%   |
| AMD Turion II           | 1         | 0.27%   |
| AMD Ryzen 3 PRO         | 1         | 0.27%   |
| AMD Phenom II X4        | 1         | 0.27%   |
| AMD Mobile Sempron      | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |
| AMD E                   | 1         | 0.27%   |
| AMD C-60                | 1         | 0.27%   |
| AMD Athlon X4           | 1         | 0.27%   |
| AMD Athlon Neo          | 1         | 0.27%   |
| AMD Athlon II X4        | 1         | 0.27%   |
| AMD Athlon II X2        | 1         | 0.27%   |
| AMD A8                  | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 145       | 39.84%  |
| 2      | 135       | 37.09%  |
| 6      | 42        | 11.54%  |
| 8      | 25        | 6.87%   |
| 12     | 8         | 2.2%    |
| 1      | 5         | 1.37%   |
| 16     | 2         | 0.55%   |
| 32     | 1         | 0.27%   |
| 10     | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 358       | 98.35%  |
| 2      | 6         | 1.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 231       | 63.46%  |
| 1      | 133       | 36.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 349       | 95.36%  |
| Unknown        | 14        | 3.83%   |
| 32-bit         | 3         | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 23.76%  |
| 0x206a7    | 19        | 4.96%   |
| 0x306a9    | 16        | 4.18%   |
| 0x306c3    | 15        | 3.92%   |
| 0x906e9    | 12        | 3.13%   |
| 0x906ea    | 11        | 2.87%   |
| 0x806ec    | 11        | 2.87%   |
| 0x1067a    | 11        | 2.87%   |
| 0x506e3    | 10        | 2.61%   |
| 0x20655    | 10        | 2.61%   |
| 0x806ea    | 9         | 2.35%   |
| 0x40651    | 9         | 2.35%   |
| 0x10676    | 9         | 2.35%   |
| 0x6fd      | 8         | 2.09%   |
| 0x30678    | 8         | 2.09%   |
| 0x806c1    | 7         | 1.83%   |
| 0x106e5    | 7         | 1.83%   |
| 0x906ed    | 5         | 1.31%   |
| 0x0a201016 | 5         | 1.31%   |
| 0x08108102 | 5         | 1.31%   |
| 0x6fb      | 4         | 1.04%   |
| 0x306d4    | 4         | 1.04%   |
| 0x20652    | 4         | 1.04%   |
| 0x08600106 | 4         | 1.04%   |
| 0x0800820d | 4         | 1.04%   |
| 0xa0652    | 3         | 0.78%   |
| 0x706e5    | 3         | 0.78%   |
| 0x406e3    | 3         | 0.78%   |
| 0x0a50000c | 3         | 0.78%   |
| 0x0a201009 | 3         | 0.78%   |
| 0x08608103 | 3         | 0.78%   |
| 0x08108109 | 3         | 0.78%   |
| 0x0810100b | 3         | 0.78%   |
| 0x08001138 | 3         | 0.78%   |
| 0xa0671    | 2         | 0.52%   |
| 0x906eb    | 2         | 0.52%   |
| 0x806eb    | 2         | 0.52%   |
| 0x706a1    | 2         | 0.52%   |
| 0x6e8      | 2         | 0.52%   |
| 0x506c9    | 2         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 65        | 17.86%  |
| Haswell          | 30        | 8.24%   |
| SandyBridge      | 25        | 6.87%   |
| Penryn           | 22        | 6.04%   |
| IvyBridge        | 21        | 5.77%   |
| Unknown          | 19        | 5.22%   |
| Skylake          | 18        | 4.95%   |
| Core             | 18        | 4.95%   |
| Zen 3            | 16        | 4.4%    |
| Westmere         | 15        | 4.12%   |
| Zen+             | 13        | 3.57%   |
| Zen 2            | 11        | 3.02%   |
| Silvermont       | 11        | 3.02%   |
| Zen              | 9         | 2.47%   |
| Nehalem          | 9         | 2.47%   |
| TigerLake        | 8         | 2.2%    |
| Broadwell        | 8         | 2.2%    |
| K10              | 7         | 1.92%   |
| IceLake          | 7         | 1.92%   |
| Piledriver       | 5         | 1.37%   |
| CometLake        | 5         | 1.37%   |
| K8 Hammer        | 4         | 1.1%    |
| Goldmont plus    | 3         | 0.82%   |
| P6               | 2         | 0.55%   |
| Goldmont         | 2         | 0.55%   |
| Bonnell          | 2         | 0.55%   |
| Bobcat           | 2         | 0.55%   |
| Alderlake Hybrid | 2         | 0.55%   |
| Steamroller      | 1         | 0.27%   |
| NetBurst         | 1         | 0.27%   |
| Jaguar           | 1         | 0.27%   |
| Gracemont        | 1         | 0.27%   |
| Excavator        | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 196       | 45.37%  |
| Nvidia                           | 123       | 28.47%  |
| AMD                              | 109       | 25.23%  |
| Matrox Electronics Systems       | 2         | 0.46%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| ASPEED Technology                | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 17        | 3.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 12        | 2.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 11        | 2.48%   |
| Intel UHD Graphics 620                                                                | 11        | 2.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 2.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 10        | 2.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 10        | 2.26%   |
| Intel Core Processor Integrated Graphics Controller                                   | 9         | 2.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 8         | 1.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 1.81%   |
| Intel HD Graphics 630                                                                 | 7         | 1.58%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 1.58%   |
| AMD Renoir                                                                            | 7         | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 6         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 6         | 1.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 1.35%   |
| AMD Lucienne                                                                          | 6         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 5         | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 5         | 1.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 5         | 1.13%   |
| Intel HD Graphics 5500                                                                | 5         | 1.13%   |
| Intel HD Graphics 530                                                                 | 5         | 1.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 5         | 1.13%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 0.9%    |
| AMD Juniper XT [Radeon HD 5770]                                                       | 4         | 0.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 4         | 0.9%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                    | 4         | 0.9%    |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 3         | 0.68%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                    | 3         | 0.68%   |
| Nvidia GM206 [GeForce GTX 960]                                                        | 3         | 0.68%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 3         | 0.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 0.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 3         | 0.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 0.68%   |
| Intel HD Graphics 620                                                                 | 3         | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 0.68%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 3         | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 3         | 0.68%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                 | 2         | 0.45%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 2         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 135       | 36.78%  |
| 1 x AMD         | 76        | 20.71%  |
| 1 x Nvidia      | 72        | 19.62%  |
| Intel + Nvidia  | 39        | 10.63%  |
| Intel + AMD     | 18        | 4.9%    |
| AMD + Nvidia    | 11        | 3%      |
| Other           | 7         | 1.91%   |
| 2 x AMD         | 4         | 1.09%   |
| 1 x Matrox      | 2         | 0.54%   |
| 2 x Intel       | 1         | 0.27%   |
| 1 x SiS         | 1         | 0.27%   |
| Nvidia + ASPEED | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 281       | 75.74%  |
| Proprietary | 66        | 17.79%  |
| Unknown     | 24        | 6.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 210       | 55.41%  |
| 1.01-2.0   | 51        | 13.46%  |
| 0.01-0.5   | 36        | 9.5%    |
| 0.51-1.0   | 25        | 6.6%    |
| 3.01-4.0   | 20        | 5.28%   |
| 7.01-8.0   | 17        | 4.49%   |
| 5.01-6.0   | 10        | 2.64%   |
| 8.01-16.0  | 6         | 1.58%   |
| 2.01-3.0   | 3         | 0.79%   |
| 4.01-5.0   | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 62        | 15.38%  |
| AU Optronics            | 52        | 12.9%   |
| Dell                    | 41        | 10.17%  |
| LG Display              | 30        | 7.44%   |
| AOC                     | 27        | 6.7%    |
| Chimei Innolux          | 24        | 5.96%   |
| BOE                     | 22        | 5.46%   |
| Goldstar                | 21        | 5.21%   |
| Philips                 | 18        | 4.47%   |
| Lenovo                  | 17        | 4.22%   |
| Hewlett-Packard         | 14        | 3.47%   |
| Chi Mei Optoelectronics | 9         | 2.23%   |
| Acer                    | 5         | 1.24%   |
| Sony                    | 4         | 0.99%   |
| Sharp                   | 4         | 0.99%   |
| LG Philips              | 4         | 0.99%   |
| Iiyama                  | 4         | 0.99%   |
| Ancor Communications    | 4         | 0.99%   |
| ViewSonic               | 3         | 0.74%   |
| Unknown                 | 3         | 0.74%   |
| HannStar                | 3         | 0.74%   |
| CSO                     | 3         | 0.74%   |
| BenQ                    | 3         | 0.74%   |
| Apple                   | 3         | 0.74%   |
| TMX                     | 2         | 0.5%    |
| PANDA                   | 2         | 0.5%    |
| CPT                     | 2         | 0.5%    |
| ASUSTek Computer        | 2         | 0.5%    |
| Vestel Elektronik       | 1         | 0.25%   |
| Unknown (XXX)           | 1         | 0.25%   |
| RS                      | 1         | 0.25%   |
| NEC Computers           | 1         | 0.25%   |
| Medion                  | 1         | 0.25%   |
| LGD                     | 1         | 0.25%   |
| InfoVision              | 1         | 0.25%   |
| IBM                     | 1         | 0.25%   |
| Grundig                 | 1         | 0.25%   |
| Gericom                 | 1         | 0.25%   |
| FUN                     | 1         | 0.25%   |
| Eizo                    | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 1.67%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                        | 4         | 0.95%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 4         | 0.95%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 4         | 0.95%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 4         | 0.95%   |
| Philips LCD Monitor FTV 1920x1080                                         | 3         | 0.71%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 3         | 0.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 3         | 0.71%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 0.71%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 2         | 0.48%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch      | 2         | 0.48%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 2         | 0.48%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch      | 2         | 0.48%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch      | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SAM04FD 1280x720                          | 2         | 0.48%   |
| Samsung Electronics LC27RG50 SAM1009 1920x1080 530x300mm 24.0-inch        | 2         | 0.48%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 2         | 0.48%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 2         | 0.48%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                       | 2         | 0.48%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 2         | 0.48%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 2         | 0.48%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 2         | 0.48%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 597x336mm 27.0-inch                  | 2         | 0.48%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                   | 2         | 0.48%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                   | 2         | 0.48%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch               | 2         | 0.48%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                         | 2         | 0.48%   |
| Dell U2515H DELD06E 2560x1440 553x311mm 25.0-inch                         | 2         | 0.48%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                         | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1376 1920x1080 293x165mm 13.2-inch          | 2         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 0.48%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 0.48%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 0.48%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 2         | 0.48%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO479D 1920x1080 382x215mm 17.3-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 161       | 42.04%  |
| 1366x768 (WXGA)    | 44        | 11.49%  |
| 3840x2160 (4K)     | 29        | 7.57%   |
| 2560x1440 (QHD)    | 28        | 7.31%   |
| 1600x900 (HD+)     | 21        | 5.48%   |
| 1680x1050 (WSXGA+) | 18        | 4.7%    |
| 1920x1200 (WUXGA)  | 16        | 4.18%   |
| 1280x1024 (SXGA)   | 14        | 3.66%   |
| 3440x1440          | 9         | 2.35%   |
| 1440x900 (WXGA+)   | 8         | 2.09%   |
| 1280x800 (WXGA)    | 8         | 2.09%   |
| 2560x1600          | 4         | 1.04%   |
| 2560x1080          | 4         | 1.04%   |
| 2288x1287          | 2         | 0.52%   |
| 1024x768 (XGA)     | 2         | 0.52%   |
| Unknown            | 2         | 0.52%   |
| 3840x1600          | 1         | 0.26%   |
| 3840x1200          | 1         | 0.26%   |
| 3840x1080          | 1         | 0.26%   |
| 3456x2160          | 1         | 0.26%   |
| 2880x1800          | 1         | 0.26%   |
| 2736x1824          | 1         | 0.26%   |
| 2560x1024          | 1         | 0.26%   |
| 2520x1680          | 1         | 0.26%   |
| 2256x1504          | 1         | 0.26%   |
| 2048x1152          | 1         | 0.26%   |
| 1400x1050          | 1         | 0.26%   |
| 1280x960           | 1         | 0.26%   |
| 1280x720 (HD)      | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 100       | 24.63%  |
| 24      | 37        | 9.11%   |
| 17      | 32        | 7.88%   |
| 23      | 28        | 6.9%    |
| 27      | 25        | 6.16%   |
| 13      | 24        | 5.91%   |
| 21      | 22        | 5.42%   |
| 14      | 21        | 5.17%   |
| Unknown | 18        | 4.43%   |
| 34      | 13        | 3.2%    |
| 19      | 12        | 2.96%   |
| 22      | 11        | 2.71%   |
| 31      | 10        | 2.46%   |
| 20      | 6         | 1.48%   |
| 18      | 6         | 1.48%   |
| 65      | 5         | 1.23%   |
| 12      | 5         | 1.23%   |
| 33      | 4         | 0.99%   |
| 84      | 3         | 0.74%   |
| 54      | 3         | 0.74%   |
| 142     | 2         | 0.49%   |
| 72      | 2         | 0.49%   |
| 40      | 2         | 0.49%   |
| 32      | 2         | 0.49%   |
| 25      | 2         | 0.49%   |
| 16      | 2         | 0.49%   |
| 55      | 1         | 0.25%   |
| 49      | 1         | 0.25%   |
| 39      | 1         | 0.25%   |
| 38      | 1         | 0.25%   |
| 37      | 1         | 0.25%   |
| 29      | 1         | 0.25%   |
| 28      | 1         | 0.25%   |
| 11      | 1         | 0.25%   |
| 10      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 134       | 33.58%  |
| 501-600        | 82        | 20.55%  |
| 401-500        | 43        | 10.78%  |
| 351-400        | 43        | 10.78%  |
| 201-300        | 22        | 5.51%   |
| 701-800        | 19        | 4.76%   |
| Unknown        | 18        | 4.51%   |
| 601-700        | 16        | 4.01%   |
| 1001-1500      | 10        | 2.51%   |
| 801-900        | 5         | 1.25%   |
| 1501-2000      | 5         | 1.25%   |
| More than 2000 | 2         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 258       | 70.11%  |
| 16/10   | 54        | 14.67%  |
| 5/4     | 16        | 4.35%   |
| Unknown | 15        | 4.08%   |
| 21/9    | 14        | 3.8%    |
| 4/3     | 4         | 1.09%   |
| 3/2     | 4         | 1.09%   |
| 1.00    | 2         | 0.54%   |
| 32/9    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 99        | 24.57%  |
| 201-250        | 72        | 17.87%  |
| 81-90          | 31        | 7.69%   |
| 351-500        | 31        | 7.69%   |
| 151-200        | 28        | 6.95%   |
| 121-130        | 26        | 6.45%   |
| 301-350        | 25        | 6.2%    |
| 251-300        | 18        | 4.47%   |
| Unknown        | 18        | 4.47%   |
| More than 1000 | 16        | 3.97%   |
| 71-80          | 13        | 3.23%   |
| 141-150        | 6         | 1.49%   |
| 501-1000       | 6         | 1.49%   |
| 61-70          | 5         | 1.24%   |
| 131-140        | 3         | 0.74%   |
| 111-120        | 2         | 0.5%    |
| 91-100         | 2         | 0.5%    |
| 51-60          | 1         | 0.25%   |
| 41-50          | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 133       | 34.28%  |
| 121-160       | 102       | 26.29%  |
| 101-120       | 93        | 23.97%  |
| 161-240       | 22        | 5.67%   |
| Unknown       | 18        | 4.64%   |
| 1-50          | 13        | 3.35%   |
| More than 240 | 7         | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 290       | 77.13%  |
| 2     | 66        | 17.55%  |
| 0     | 16        | 4.26%   |
| 3     | 3         | 0.8%    |
| 6     | 1         | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 186       | 35.7%   |
| Intel                             | 186       | 35.7%   |
| Qualcomm Atheros                  | 45        | 8.64%   |
| Broadcom                          | 32        | 6.14%   |
| Ralink                            | 8         | 1.54%   |
| Marvell Technology Group          | 7         | 1.34%   |
| Ralink Technology                 | 6         | 1.15%   |
| ASUSTek Computer                  | 6         | 1.15%   |
| MediaTek                          | 4         | 0.77%   |
| Sierra Wireless                   | 3         | 0.58%   |
| Samsung Electronics               | 3         | 0.58%   |
| Nvidia                            | 3         | 0.58%   |
| Huawei Technologies               | 3         | 0.58%   |
| Hewlett-Packard                   | 3         | 0.58%   |
| Ericsson Business Mobile Networks | 3         | 0.58%   |
| Linksys                           | 2         | 0.38%   |
| Broadcom Limited                  | 2         | 0.38%   |
| ASIX Electronics                  | 2         | 0.38%   |
| ZyDAS Technology                  | 1         | 0.19%   |
| ZyDAS                             | 1         | 0.19%   |
| VIA Technologies                  | 1         | 0.19%   |
| TP-Link                           | 1         | 0.19%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.19%   |
| Qualcomm Atheros Communications   | 1         | 0.19%   |
| Microsoft                         | 1         | 0.19%   |
| Lenovo                            | 1         | 0.19%   |
| JMicron Technology                | 1         | 0.19%   |
| IMC Networks                      | 1         | 0.19%   |
| IBM                               | 1         | 0.19%   |
| Edimax Technology                 | 1         | 0.19%   |
| Dell                              | 1         | 0.19%   |
| D-Link System                     | 1         | 0.19%   |
| D-Link                            | 1         | 0.19%   |
| Compal Electronics                | 1         | 0.19%   |
| Belkin Components                 | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 139       | 22.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.41%   |
| Intel Wireless 8265 / 8275                                        | 14        | 2.25%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 2.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.77%   |
| Intel Ethernet Connection (2) I219-V                              | 11        | 1.77%   |
| Intel Wireless 7260                                               | 10        | 1.61%   |
| Intel I211 Gigabit Network Connection                             | 9         | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 0.96%   |
| Intel Wireless 7265                                               | 6         | 0.96%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.96%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 5         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.64%   |
| Intel Wireless 8260                                               | 4         | 0.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.64%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.48%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 3         | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 128       | 48.12%  |
| Qualcomm Atheros                  | 37        | 13.91%  |
| Realtek Semiconductor             | 35        | 13.16%  |
| Broadcom                          | 22        | 8.27%   |
| Ralink                            | 8         | 3.01%   |
| Ralink Technology                 | 6         | 2.26%   |
| ASUSTek Computer                  | 6         | 2.26%   |
| MediaTek                          | 4         | 1.5%    |
| Sierra Wireless                   | 3         | 1.13%   |
| Hewlett-Packard                   | 2         | 0.75%   |
| Broadcom Limited                  | 2         | 0.75%   |
| ZyDAS Technology                  | 1         | 0.38%   |
| ZyDAS                             | 1         | 0.38%   |
| TP-Link                           | 1         | 0.38%   |
| Qualcomm Atheros Communications   | 1         | 0.38%   |
| Marvell Technology Group          | 1         | 0.38%   |
| Linksys                           | 1         | 0.38%   |
| IMC Networks                      | 1         | 0.38%   |
| Ericsson Business Mobile Networks | 1         | 0.38%   |
| Edimax Technology                 | 1         | 0.38%   |
| Dell                              | 1         | 0.38%   |
| D-Link System                     | 1         | 0.38%   |
| D-Link                            | 1         | 0.38%   |
| Belkin Components                 | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 14        | 5.24%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 5.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 4.12%   |
| Intel Wireless 7260                                                     | 10        | 3.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.25%   |
| Intel Wireless 7265                                                     | 6         | 2.25%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 2.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 1.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.5%    |
| Intel Wireless 8260                                                     | 4         | 1.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 1.12%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 1.12%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.12%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.75%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 2         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.75%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 175       | 50.43%  |
| Intel                            | 120       | 34.58%  |
| Broadcom                         | 15        | 4.32%   |
| Qualcomm Atheros                 | 13        | 3.75%   |
| Marvell Technology Group         | 6         | 1.73%   |
| Nvidia                           | 3         | 0.86%   |
| Huawei Technologies              | 3         | 0.86%   |
| Samsung Electronics              | 2         | 0.58%   |
| ASIX Electronics                 | 2         | 0.58%   |
| VIA Technologies                 | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Microsoft                        | 1         | 0.29%   |
| Linksys                          | 1         | 0.29%   |
| Lenovo                           | 1         | 0.29%   |
| JMicron Technology               | 1         | 0.29%   |
| IBM                              | 1         | 0.29%   |
| Compal Electronics               | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 139       | 39.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 4.26%   |
| Intel Ethernet Connection (2) I219-V                              | 11        | 3.13%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.99%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 1.7%    |
| Intel Ethernet Connection (6) I219-V                              | 6         | 1.7%    |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.42%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.14%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.14%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.14%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.85%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 3         | 0.85%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.85%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.85%   |
| Intel 82562GT 10/100 Network Connection                           | 3         | 0.85%   |
| Huawei WLZ-AN00                                                   | 3         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.57%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.57%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.57%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.57%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.57%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.57%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.57%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 2         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 327       | 55.99%  |
| WiFi     | 253       | 43.32%  |
| Modem    | 4         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 188       | 50.81%  |
| WiFi     | 182       | 49.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 206       | 56.28%  |
| 1     | 140       | 38.25%  |
| 0     | 11        | 3.01%   |
| 4     | 4         | 1.09%   |
| 3     | 4         | 1.09%   |
| 5     | 1         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 342       | 91.94%  |
| Yes  | 30        | 8.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 95        | 45.45%  |
| Realtek Semiconductor           | 17        | 8.13%   |
| IMC Networks                    | 16        | 7.66%   |
| Qualcomm Atheros Communications | 14        | 6.7%    |
| Broadcom                        | 14        | 6.7%    |
| Cambridge Silicon Radio         | 10        | 4.78%   |
| Hewlett-Packard                 | 8         | 3.83%   |
| ASUSTek Computer                | 8         | 3.83%   |
| Lite-On Technology              | 4         | 1.91%   |
| Toshiba                         | 3         | 1.44%   |
| Ralink                          | 3         | 1.44%   |
| Apple                           | 3         | 1.44%   |
| Foxconn International           | 2         | 0.96%   |
| Foxconn / Hon Hai               | 2         | 0.96%   |
| Edimax Technology               | 2         | 0.96%   |
| Askey Computer                  | 2         | 0.96%   |
| Ralink Technology               | 1         | 0.48%   |
| Qcom                            | 1         | 0.48%   |
| Marvell Semiconductor           | 1         | 0.48%   |
| Integrated System Solution      | 1         | 0.48%   |
| Dell                            | 1         | 0.48%   |
| Chicony Electronics             | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 33        | 15.79%  |
| Intel AX201 Bluetooth                               | 21        | 10.05%  |
| Intel AX200 Bluetooth                               | 14        | 6.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 13        | 6.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 4.78%   |
| Realtek Bluetooth Radio                             | 9         | 4.31%   |
| IMC Networks Bluetooth Radio                        | 7         | 3.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 2.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 2.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 1.91%   |
| Intel AX210 Bluetooth                               | 4         | 1.91%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.44%   |
| Intel Bluetooth Device                              | 3         | 1.44%   |
| IMC Networks Bluetooth Device                       | 3         | 1.44%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.44%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.96%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.96%   |
| Lite-On Bluetooth Device                            | 2         | 0.96%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.96%   |
| IMC Networks Wireless_Device                        | 2         | 0.96%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.96%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.96%   |
| Edimax Bluetooth Adapter                            | 2         | 0.96%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.96%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.96%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.96%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.96%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.96%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 0.96%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.96%   |
| Askey Bluetooth Device                              | 2         | 0.96%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.48%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.48%   |
| Realtek CSR BS8510                                  | 1         | 0.48%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 265       | 53%     |
| AMD                              | 103       | 20.6%   |
| Nvidia                           | 90        | 18%     |
| C-Media Electronics              | 5         | 1%      |
| Logitech                         | 4         | 0.8%    |
| JMTek                            | 3         | 0.6%    |
| ASUSTek Computer                 | 3         | 0.6%    |
| Texas Instruments                | 2         | 0.4%    |
| FUXIN                            | 2         | 0.4%    |
| BEHRINGER International          | 2         | 0.4%    |
| Yamaha                           | 1         | 0.2%    |
| Textech International            | 1         | 0.2%    |
| Syntek                           | 1         | 0.2%    |
| SteelSeries ApS                  | 1         | 0.2%    |
| Sony                             | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Sennheiser Communications        | 1         | 0.2%    |
| SAVITECH                         | 1         | 0.2%    |
| PreSonus Audio Electronics       | 1         | 0.2%    |
| Nam Tai E&E Products             | 1         | 0.2%    |
| Mackie Designs                   | 1         | 0.2%    |
| Lenovo                           | 1         | 0.2%    |
| Kingston Technology              | 1         | 0.2%    |
| iCreate Technologies             | 1         | 0.2%    |
| Hewlett-Packard                  | 1         | 0.2%    |
| Generalplus Technology           | 1         | 0.2%    |
| FiiO Electronics Technology      | 1         | 0.2%    |
| Dell                             | 1         | 0.2%    |
| Creative Technology              | 1         | 0.2%    |
| Creative Labs                    | 1         | 0.2%    |
| AKAI Professional M.I.           | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 31        | 5.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 25        | 4.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 21        | 3.61%   |
| Intel Sunrise Point-LP HD Audio                                                   | 18        | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 17        | 2.92%   |
| Intel Cannon Lake PCH cAVS                                                        | 16        | 2.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 16        | 2.75%   |
| AMD Starship/Matisse HD Audio Controller                                          | 15        | 2.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 15        | 2.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 14        | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 13        | 2.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 13        | 2.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 12        | 2.06%   |
| Intel 200 Series PCH HD Audio                                                     | 11        | 1.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 11        | 1.89%   |
| Intel Haswell-ULT HD Audio Controller                                             | 10        | 1.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 10        | 1.72%   |
| Intel 8 Series HD Audio Controller                                                | 10        | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 10        | 1.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10        | 1.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10        | 1.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 8         | 1.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 8         | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7         | 1.2%    |
| Nvidia GP104 High Definition Audio Controller                                     | 7         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                                      | 7         | 1.2%    |
| Intel Broadwell-U Audio Controller                                                | 7         | 1.2%    |
| AMD FCH Azalia Controller                                                         | 7         | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                                     | 6         | 1.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6         | 1.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 6         | 1.03%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5         | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 0.69%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4         | 0.69%   |
| Nvidia GA106 High Definition Audio Controller                                     | 4         | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 50        | 20%     |
| Samsung Electronics | 49        | 19.6%   |
| Micron Technology   | 25        | 10%     |
| Crucial             | 25        | 10%     |
| Kingston            | 23        | 9.2%    |
| Unknown             | 20        | 8%      |
| G.Skill             | 14        | 5.6%    |
| Nanya Technology    | 7         | 2.8%    |
| Corsair             | 6         | 2.4%    |
| Ramaxel Technology  | 5         | 2%      |
| Elpida              | 5         | 2%      |
| Team                | 4         | 1.6%    |
| A-DATA Technology   | 4         | 1.6%    |
| Patriot             | 3         | 1.2%    |
| TakeMS              | 2         | 0.8%    |
| Qimonda             | 2         | 0.8%    |
| Transcend           | 1         | 0.4%    |
| Swissbit            | 1         | 0.4%    |
| Silicon Power       | 1         | 0.4%    |
| GOODRAM             | 1         | 0.4%    |
| GLOWAY              | 1         | 0.4%    |
| ChangXin Memory     | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                        | 3         | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.1%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 1.1%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.1%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 3         | 1.1%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.74%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 2         | 0.74%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s           | 2         | 0.74%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s             | 2         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.74%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 2         | 0.74%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 2         | 0.74%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 2         | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 0.74%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 2         | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.74%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.74%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.74%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s     | 2         | 0.74%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1867MT/s       | 2         | 0.74%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s      | 2         | 0.74%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s      | 2         | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 2         | 0.74%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s    | 2         | 0.74%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 2         | 0.74%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 2         | 0.74%   |
| Crucial RAM CT8G4SFD824A.M16FF 8GB SODIMM DDR4 2400MT/s   | 2         | 0.74%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s | 2         | 0.74%   |
| A-DATA RAM DDR4 3600 16GB DIMM DDR4 3800MT/s              | 2         | 0.74%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 1         | 0.37%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                 | 1         | 0.37%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.37%   |
| Unknown RAM Module 512MB SODIMM DDR2                      | 1         | 0.37%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s               | 1         | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM 400MT/s                       | 1         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DRAM                     | 1         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 106       | 49.3%   |
| DDR3    | 61        | 28.37%  |
| DDR2    | 18        | 8.37%   |
| SDRAM   | 9         | 4.19%   |
| LPDDR4  | 5         | 2.33%   |
| LPDDR3  | 5         | 2.33%   |
| Unknown | 5         | 2.33%   |
| DDR5    | 4         | 1.86%   |
| DRAM    | 1         | 0.47%   |
| DDR     | 1         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 119       | 55.61%  |
| DIMM         | 81        | 37.85%  |
| Row Of Chips | 11        | 5.14%   |
| Chip         | 2         | 0.93%   |
| FB-DIMM      | 1         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 79        | 35.43%  |
| 4096  | 48        | 21.52%  |
| 16384 | 43        | 19.28%  |
| 2048  | 34        | 15.25%  |
| 1024  | 9         | 4.04%   |
| 32768 | 7         | 3.14%   |
| 512   | 2         | 0.9%    |
| 65536 | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 37        | 15.48%  |
| 2667    | 33        | 13.81%  |
| 3200    | 31        | 12.97%  |
| 2400    | 18        | 7.53%   |
| 1333    | 15        | 6.28%   |
| 2133    | 14        | 5.86%   |
| 1334    | 11        | 4.6%    |
| 667     | 10        | 4.18%   |
| 3600    | 6         | 2.51%   |
| 2048    | 5         | 2.09%   |
| 1867    | 5         | 2.09%   |
| 800     | 5         | 2.09%   |
| Unknown | 5         | 2.09%   |
| 3733    | 4         | 1.67%   |
| 4800    | 3         | 1.26%   |
| 4267    | 3         | 1.26%   |
| 3800    | 3         | 1.26%   |
| 3000    | 3         | 1.26%   |
| 1800    | 3         | 1.26%   |
| 1067    | 3         | 1.26%   |
| 4199    | 2         | 0.84%   |
| 2800    | 2         | 0.84%   |
| 49926   | 1         | 0.42%   |
| 8400    | 1         | 0.42%   |
| 5600    | 1         | 0.42%   |
| 4266    | 1         | 0.42%   |
| 4133    | 1         | 0.42%   |
| 3866    | 1         | 0.42%   |
| 3534    | 1         | 0.42%   |
| 3466    | 1         | 0.42%   |
| 3333    | 1         | 0.42%   |
| 3266    | 1         | 0.42%   |
| 2933    | 1         | 0.42%   |
| 2866    | 1         | 0.42%   |
| 1866    | 1         | 0.42%   |
| 1639    | 1         | 0.42%   |
| 1066    | 1         | 0.42%   |
| 975     | 1         | 0.42%   |
| 533     | 1         | 0.42%   |
| 400     | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 4         | 30.77%  |
| Xerox                 | 2         | 15.38%  |
| Canon                 | 2         | 15.38%  |
| Seiko Epson           | 1         | 7.69%   |
| Samsung Electronics   | 1         | 7.69%   |
| Lexmark International | 1         | 7.69%   |
| Datamax-O'Neil        | 1         | 7.69%   |
| Brother Industries    | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Xerox Phaser 3140 and 3155               | 1         | 7.69%   |
| Xerox Phaser 3010                        | 1         | 7.69%   |
| Seiko Epson ET-2720 Series               | 1         | 7.69%   |
| Samsung M2070 Series                     | 1         | 7.69%   |
| Lexmark International Laser Printer E232 | 1         | 7.69%   |
| HP DeskJet F4200 series                  | 1         | 7.69%   |
| HP DeskJet 4530 series                   | 1         | 7.69%   |
| HP DeskJet 2620 All-in-One Printer       | 1         | 7.69%   |
| HP Color LaserJet 2605dn                 | 1         | 7.69%   |
| Datamax-O'Neil Datamax E-4304            | 1         | 7.69%   |
| Canon PIXMA MX390 Series                 | 1         | 7.69%   |
| Canon PIXMA MP250                        | 1         | 7.69%   |
| Brother DCP-L2530DW series               | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 5         | 83.33%  |
| Acer Peripherals (now BenQ) | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20       | 2         | 33.33%  |
| Canon CanoScan LiDE 700F                 | 1         | 16.67%  |
| Canon CanoScan LiDE 220                  | 1         | 16.67%  |
| Canon CanoScan 4200F                     | 1         | 16.67%  |
| Acer Peripherals (now BenQ) Prisa 1240UT | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 58        | 30.05%  |
| IMC Networks                           | 22        | 11.4%   |
| Quanta                                 | 15        | 7.77%   |
| Realtek Semiconductor                  | 12        | 6.22%   |
| Sunplus Innovation Technology          | 11        | 5.7%    |
| Microdia                               | 11        | 5.7%    |
| Cheng Uei Precision Industry (Foxlink) | 9         | 4.66%   |
| Logitech                               | 8         | 4.15%   |
| Lite-On Technology                     | 7         | 3.63%   |
| Bison Electronics                      | 5         | 2.59%   |
| Apple                                  | 4         | 2.07%   |
| Acer                                   | 4         | 2.07%   |
| Syntek                                 | 3         | 1.55%   |
| Suyin                                  | 3         | 1.55%   |
| Primax Electronics                     | 3         | 1.55%   |
| Lenovo                                 | 3         | 1.55%   |
| Samsung Electronics                    | 2         | 1.04%   |
| Luxvisions Innotech Limited            | 2         | 1.04%   |
| Generalplus Technology                 | 2         | 1.04%   |
| Z-Star Microelectronics                | 1         | 0.52%   |
| Unknown (3730304231385031345945)       | 1         | 0.52%   |
| Sony                                   | 1         | 0.52%   |
| Sonix Technology                       | 1         | 0.52%   |
| Silicon Motion                         | 1         | 0.52%   |
| Ricoh                                  | 1         | 0.52%   |
| Pixart Imaging                         | 1         | 0.52%   |
| MacroSilicon                           | 1         | 0.52%   |
| Cubeternet                             | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                        | 11        | 5.61%   |
| Microdia Integrated_Webcam_HD                                    | 8         | 4.08%   |
| IMC Networks Integrated Camera                                   | 8         | 4.08%   |
| IMC Networks USB2.0 HD UVC WebCam                                | 6         | 3.06%   |
| Sunplus HP HD Webcam [Fixed]                                     | 4         | 2.04%   |
| Quanta HP HD Camera                                              | 4         | 2.04%   |
| Syntek Lenovo EasyCamera                                         | 3         | 1.53%   |
| Quanta HP TrueVision HD Camera                                   | 3         | 1.53%   |
| Primax HP HD Webcam [Fixed]                                      | 3         | 1.53%   |
| Lite-On HP HD Webcam                                             | 3         | 1.53%   |
| Chicony USB2.0 HD UVC WebCam                                     | 3         | 1.53%   |
| Chicony HP HD Webcam                                             | 3         | 1.53%   |
| Chicony HP HD Camera                                             | 3         | 1.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                 | 3         | 1.53%   |
| Acer Integrated Camera                                           | 3         | 1.53%   |
| Sunplus HD WebCam                                                | 2         | 1.02%   |
| Samsung Galaxy series, misc. (MTP mode)                          | 2         | 1.02%   |
| Realtek USB Camera                                               | 2         | 1.02%   |
| Realtek Integrated_Webcam_HD                                     | 2         | 1.02%   |
| Realtek Asus laptop camera                                       | 2         | 1.02%   |
| Quanta HP Webcam                                                 | 2         | 1.02%   |
| Logitech Webcam C310                                             | 2         | 1.02%   |
| Lite-On Integrated Camera                                        | 2         | 1.02%   |
| Lite-On HP HD Camera                                             | 2         | 1.02%   |
| Lenovo Integrated Webcam [R5U877]                                | 2         | 1.02%   |
| IMC Networks USB2.0 VGA UVC WebCam                               | 2         | 1.02%   |
| IMC Networks Integrated Webcam                                   | 2         | 1.02%   |
| Generalplus GENERAL WEBCAM                                       | 2         | 1.02%   |
| Chicony USB2.0 VGA UVC WebCam                                    | 2         | 1.02%   |
| Chicony USB2.0 UVC WebCam                                        | 2         | 1.02%   |
| Chicony Lenovo EasyCamera                                        | 2         | 1.02%   |
| Chicony Integrated IR Camera                                     | 2         | 1.02%   |
| Chicony Integrated Camera [ThinkPad]                             | 2         | 1.02%   |
| Chicony Integrated Camera (1280x720@30)                          | 2         | 1.02%   |
| Chicony HP Wide Vision HD Camera                                 | 2         | 1.02%   |
| Chicony HP Webcam                                                | 2         | 1.02%   |
| Chicony HP TrueVision HD Camera                                  | 2         | 1.02%   |
| Chicony FJ Camera                                                | 2         | 1.02%   |
| Chicony CNF7042                                                  | 2         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision FHD Camera | 2         | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 19        | 32.76%  |
| Validity Sensors           | 18        | 31.03%  |
| AuthenTec                  | 6         | 10.34%  |
| Shenzhen Goodix Technology | 5         | 8.62%   |
| Upek                       | 4         | 6.9%    |
| Elan Microelectronics      | 4         | 6.9%    |
| STMicroelectronics         | 2         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 10.34%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 10.34%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 6.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 6.9%    |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 6.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 5.17%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 5.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.45%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.45%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 3.45%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.45%   |
| AuthenTec AES2810                                                          | 2         | 3.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.72%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.72%   |
| Validity Sensors VFS491                                                    | 1         | 1.72%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.72%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.72%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.72%   |
| Synaptics UWP WBDI                                                         | 1         | 1.72%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.72%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.72%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 1.72%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.72%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.72%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.72%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.72%   |
| AuthenTec AES1600                                                          | 1         | 1.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 8         | 44.44%  |
| Broadcom         | 5         | 27.78%  |
| O2 Micro         | 3         | 16.67%  |
| Upek             | 1         | 5.56%   |
| SCM Microsystems | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 44.44%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 16.67%  |
| Broadcom 58200                                                               | 3         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.56%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 244       | 65.77%  |
| 1     | 97        | 26.15%  |
| 2     | 26        | 7.01%   |
| 3     | 3         | 0.81%   |
| 10    | 1         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 35.58%  |
| Graphics card            | 35        | 21.47%  |
| Chipcard                 | 16        | 9.82%   |
| Net/wireless             | 15        | 9.2%    |
| Multimedia controller    | 9         | 5.52%   |
| Communication controller | 6         | 3.68%   |
| Bluetooth                | 6         | 3.68%   |
| Camera                   | 4         | 2.45%   |
| Storage                  | 3         | 1.84%   |
| Unassigned class         | 2         | 1.23%   |
| Sound                    | 2         | 1.23%   |
| Network                  | 2         | 1.23%   |
| Card reader              | 2         | 1.23%   |
| Net/ethernet             | 1         | 0.61%   |
| Flash memory             | 1         | 0.61%   |
| Dvb card                 | 1         | 0.61%   |

