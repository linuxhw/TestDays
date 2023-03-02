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

Total: 510

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 60        | 16.85%  |
| Ubuntu 18.04                 | 24        | 6.74%   |
| Ubuntu 22.04                 | 17        | 4.78%   |
| OpenMandriva 4.3             | 12        | 3.37%   |
| Debian 11                    | 11        | 3.09%   |
| KDE neon 20.04               | 10        | 2.81%   |
| Zorin 16                     | 9         | 2.53%   |
| Ubuntu 20.10                 | 8         | 2.25%   |
| Xubuntu 20.04                | 7         | 1.97%   |
| ArcoLinux Rolling            | 7         | 1.97%   |
| Ubuntu 19.10                 | 6         | 1.69%   |
| Zorin 15                     | 5         | 1.4%    |
| Linux Mint 19.3              | 5         | 1.4%    |
| Kubuntu 22.04                | 5         | 1.4%    |
| Kubuntu 20.04                | 5         | 1.4%    |
| Fedora 34                    | 5         | 1.4%    |
| Arch                         | 5         | 1.4%    |
| Pop!_OS 20.04                | 4         | 1.12%   |
| OpenMandriva 4.2             | 4         | 1.12%   |
| Manjaro                      | 4         | 1.12%   |
| Linux Mint 19.1              | 4         | 1.12%   |
| Fedora 37                    | 4         | 1.12%   |
| Fedora 33                    | 4         | 1.12%   |
| Ubuntu Unity 16.04           | 3         | 0.84%   |
| Ubuntu 21.10                 | 3         | 0.84%   |
| Pop!_OS 21.10                | 3         | 0.84%   |
| Kubuntu 21.10                | 3         | 0.84%   |
| Gentoo 2.6                   | 3         | 0.84%   |
| Fedora 35                    | 3         | 0.84%   |
| EndeavourOS                  | 3         | 0.84%   |
| Debian Testing               | 3         | 0.84%   |
| Xubuntu 22.04                | 2         | 0.56%   |
| Ubuntu Budgie 22.04          | 2         | 0.56%   |
| Ubuntu 21.04                 | 2         | 0.56%   |
| Ubuntu 18.10                 | 2         | 0.56%   |
| ROSA R8                      | 2         | 0.56%   |
| Pop!_OS 22.04                | 2         | 0.56%   |
| Pop!_OS 21.04                | 2         | 0.56%   |
| Pop!_OS 20.10                | 2         | 0.56%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 119       | 35%     |
| OpenMandriva  | 18        | 5.29%   |
| Linux Mint    | 18        | 5.29%   |
| Kubuntu       | 18        | 5.29%   |
| Fedora        | 18        | 5.29%   |
| Debian        | 16        | 4.71%   |
| Manjaro       | 15        | 4.41%   |
| Zorin         | 13        | 3.82%   |
| Pop!_OS       | 13        | 3.82%   |
| KDE neon      | 13        | 3.82%   |
| Xubuntu       | 11        | 3.24%   |
| Endless       | 10        | 2.94%   |
| ArcoLinux     | 7         | 2.06%   |
| Arch          | 7         | 2.06%   |
| Gentoo        | 5         | 1.47%   |
| EndeavourOS   | 5         | 1.47%   |
| Ubuntu Unity  | 4         | 1.18%   |
| Ubuntu Budgie | 3         | 0.88%   |
| Lubuntu       | 3         | 0.88%   |
| Elementary    | 3         | 0.88%   |
| Ubuntu MATE   | 2         | 0.59%   |
| ROSA          | 2         | 0.59%   |
| openSUSE      | 2         | 0.59%   |
| BlackPanther  | 2         | 0.59%   |
| Android       | 2         | 0.59%   |
| Ubuntu Kylin  | 1         | 0.29%   |
| RHEL          | 1         | 0.29%   |
| Q4OS          | 1         | 0.29%   |
| Mageia        | 1         | 0.29%   |
| LMDE          | 1         | 0.29%   |
| Kali          | 1         | 0.29%   |
| Garuda Linux  | 1         | 0.29%   |
| Clear Linux   | 1         | 0.29%   |
| Chrome OS     | 1         | 0.29%   |
| CentOS        | 1         | 0.29%   |
| Artix         | 1         | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 12        | 3.08%   |
| 5.4.0-48-generic         | 7         | 1.8%    |
| 5.15.0-56-generic        | 6         | 1.54%   |
| 4.18.0-15-generic        | 6         | 1.54%   |
| 5.4.0-42-generic         | 5         | 1.29%   |
| 5.3.0-40-generic         | 5         | 1.29%   |
| 5.13.0-30-generic        | 5         | 1.29%   |
| 5.8.0-41-generic         | 4         | 1.03%   |
| 5.15.0-47-generic        | 4         | 1.03%   |
| 5.15.0-46-generic        | 4         | 1.03%   |
| 5.15.0-43-generic        | 4         | 1.03%   |
| 5.15.0-25-generic        | 4         | 1.03%   |
| 5.13.0-41-generic        | 4         | 1.03%   |
| 5.13.0-28-generic        | 4         | 1.03%   |
| 5.11.0-43-generic        | 4         | 1.03%   |
| 5.11.0-40-generic        | 4         | 1.03%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.03%   |
| 5.8.0-43-generic         | 3         | 0.77%   |
| 5.8.0-36-generic         | 3         | 0.77%   |
| 5.8.0-14-generic         | 3         | 0.77%   |
| 5.4.0-70-generic         | 3         | 0.77%   |
| 5.4.0-60-generic         | 3         | 0.77%   |
| 5.4.0-54-generic         | 3         | 0.77%   |
| 5.4.0-52-generic         | 3         | 0.77%   |
| 5.4.0-31-generic         | 3         | 0.77%   |
| 5.4.0-29-generic         | 3         | 0.77%   |
| 5.4.0-26-generic         | 3         | 0.77%   |
| 5.3.0-26-generic         | 3         | 0.77%   |
| 5.15.0-57-generic        | 3         | 0.77%   |
| 5.13.0-21-generic        | 3         | 0.77%   |
| 4.18.0-17-generic        | 3         | 0.77%   |
| 5.9.2-arch1-1            | 2         | 0.51%   |
| 5.8.0-7630-generic       | 2         | 0.51%   |
| 5.8.0-53-generic         | 2         | 0.51%   |
| 5.8.0-44-generic         | 2         | 0.51%   |
| 5.6.14-desktop-2bP       | 2         | 0.51%   |
| 5.6.0-1-amd64            | 2         | 0.51%   |
| 5.4.0-90-generic         | 2         | 0.51%   |
| 5.4.0-89-generic         | 2         | 0.51%   |
| 5.4.0-7642-generic       | 2         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 69        | 18.7%   |
| 5.15.0  | 35        | 9.49%   |
| 5.8.0   | 28        | 7.59%   |
| 5.13.0  | 26        | 7.05%   |
| 5.11.0  | 20        | 5.42%   |
| 4.15.0  | 17        | 4.61%   |
| 5.3.0   | 16        | 4.34%   |
| 4.18.0  | 16        | 4.34%   |
| 5.16.7  | 13        | 3.52%   |
| 5.10.0  | 11        | 2.98%   |
| 5.0.0   | 7         | 1.9%    |
| 5.10.14 | 6         | 1.63%   |
| 5.6.0   | 4         | 1.08%   |
| 6.0.11  | 2         | 0.54%   |
| 5.9.2   | 2         | 0.54%   |
| 5.9.15  | 2         | 0.54%   |
| 5.6.14  | 2         | 0.54%   |
| 5.19.0  | 2         | 0.54%   |
| 5.17.5  | 2         | 0.54%   |
| 5.17.1  | 2         | 0.54%   |
| 5.16.15 | 2         | 0.54%   |
| 5.15.2  | 2         | 0.54%   |
| 5.14.16 | 2         | 0.54%   |
| 5.14.0  | 2         | 0.54%   |
| 5.13.19 | 2         | 0.54%   |
| 5.12.8  | 2         | 0.54%   |
| 5.12.4  | 2         | 0.54%   |
| 5.10.30 | 2         | 0.54%   |
| 4.18.16 | 2         | 0.54%   |
| 6.1.9   | 1         | 0.27%   |
| 6.1.8   | 1         | 0.27%   |
| 6.1.5   | 1         | 0.27%   |
| 6.1.4   | 1         | 0.27%   |
| 6.1.3   | 1         | 0.27%   |
| 6.1.1   | 1         | 0.27%   |
| 6.0.7   | 1         | 0.27%   |
| 6.0.15  | 1         | 0.27%   |
| 6.0.13  | 1         | 0.27%   |
| 6.0.12  | 1         | 0.27%   |
| 5.9.8   | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 72        | 19.78%  |
| 5.15    | 44        | 12.09%  |
| 5.8     | 33        | 9.07%   |
| 5.13    | 30        | 8.24%   |
| 5.11    | 23        | 6.32%   |
| 5.16    | 20        | 5.49%   |
| 5.10    | 20        | 5.49%   |
| 4.18    | 18        | 4.95%   |
| 5.3     | 17        | 4.67%   |
| 4.15    | 17        | 4.67%   |
| 5.17    | 7         | 1.92%   |
| 5.12    | 7         | 1.92%   |
| 5.0     | 7         | 1.92%   |
| 6.0     | 6         | 1.65%   |
| 5.6     | 6         | 1.65%   |
| 5.19    | 6         | 1.65%   |
| 5.14    | 6         | 1.65%   |
| 6.1     | 5         | 1.37%   |
| 5.9     | 5         | 1.37%   |
| 5.7     | 2         | 0.55%   |
| 5.5     | 2         | 0.55%   |
| 5.18    | 2         | 0.55%   |
| 4.19    | 2         | 0.55%   |
| 4.1     | 2         | 0.55%   |
| 3.18    | 2         | 0.55%   |
| 4.9     | 1         | 0.27%   |
| 4.20    | 1         | 0.27%   |
| 4.14    | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 310       | 95.09%  |
| i686    | 9         | 2.76%   |
| aarch64 | 5         | 1.53%   |
| armv8l  | 2         | 0.61%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 142       | 41.28%  |
| KDE5            | 65        | 18.9%   |
| Unknown         | 47        | 13.66%  |
| XFCE            | 32        | 9.3%    |
| X-Cinnamon      | 13        | 3.78%   |
| KDE             | 9         | 2.62%   |
| Cinnamon        | 6         | 1.74%   |
| LXQt            | 5         | 1.45%   |
| Unity           | 4         | 1.16%   |
| MATE            | 4         | 1.16%   |
| Pantheon        | 3         | 0.87%   |
| Budgie          | 3         | 0.87%   |
| LXDE            | 2         | 0.58%   |
| DWM             | 2         | 0.58%   |
| UKUI            | 1         | 0.29%   |
| Trinity         | 1         | 0.29%   |
| Openbox         | 1         | 0.29%   |
| NsCDE           | 1         | 0.29%   |
| KDE4            | 1         | 0.29%   |
| i3              | 1         | 0.29%   |
| GNOME Flashback | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 256       | 75.96%  |
| Wayland | 40        | 11.87%  |
| Unknown | 32        | 9.5%    |
| Tty     | 9         | 2.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 166       | 48.54%  |
| SDDM    | 57        | 16.67%  |
| GDM     | 39        | 11.4%   |
| LightDM | 36        | 10.53%  |
| GDM3    | 28        | 8.19%   |
| TDM     | 14        | 4.09%   |
| XDM     | 1         | 0.29%   |
| KDM     | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 164       | 49.1%   |
| sl_SI   | 90        | 26.95%  |
| Unknown | 45        | 13.47%  |
| en_GB   | 15        | 4.49%   |
| C       | 6         | 1.8%    |
| it_IT   | 4         | 1.2%    |
| en_SI   | 4         | 1.2%    |
| de_AT   | 2         | 0.6%    |
| pt_PT   | 1         | 0.3%    |
| nl_NL   | 1         | 0.3%    |
| hr_HR   | 1         | 0.3%    |
| de_DE   | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 168       | 50.15%  |
| EFI  | 167       | 49.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 259       | 77.54%  |
| Overlay | 31        | 9.28%   |
| Btrfs   | 19        | 5.69%   |
| Unknown | 16        | 4.79%   |
| Zfs     | 5         | 1.5%    |
| Xfs     | 3         | 0.9%    |
| Ext2    | 1         | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 179       | 53.59%  |
| GPT     | 112       | 33.53%  |
| MBR     | 43        | 12.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 288       | 86.49%  |
| Yes       | 45        | 13.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 236       | 71.3%   |
| Yes       | 95        | 28.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 72        | 22.09%  |
| Lenovo                  | 62        | 19.02%  |
| ASUSTek Computer        | 61        | 18.71%  |
| Gigabyte Technology     | 23        | 7.06%   |
| Dell                    | 20        | 6.13%   |
| ASRock                  | 15        | 4.6%    |
| MSI                     | 14        | 4.29%   |
| Toshiba                 | 8         | 2.45%   |
| Intel                   | 7         | 2.15%   |
| Acer                    | 7         | 2.15%   |
| Raspberry Pi Foundation | 5         | 1.53%   |
| Pegatron                | 4         | 1.23%   |
| Medion                  | 4         | 1.23%   |
| Fujitsu                 | 4         | 1.23%   |
| Apple                   | 4         | 1.23%   |
| Supermicro              | 2         | 0.61%   |
| Fujitsu Siemens         | 2         | 0.61%   |
| Unknown                 | 2         | 0.61%   |
| TUXEDO                  | 1         | 0.31%   |
| Razer                   | 1         | 0.31%   |
| PC Specialist           | 1         | 0.31%   |
| Panasonic               | 1         | 0.31%   |
| Microsoft               | 1         | 0.31%   |
| IBM                     | 1         | 0.31%   |
| HUAWEI                  | 1         | 0.31%   |
| Framework               | 1         | 0.31%   |
| eMachines               | 1         | 0.31%   |
| Biostar                 | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 4         | 1.23%   |
| MSI MS-7C02                                | 3         | 0.92%   |
| HP 255 G7 Notebook PC                      | 3         | 0.92%   |
| Toshiba Satellite L750                     | 2         | 0.61%   |
| RPi Raspberry Pi 400 Rev 1.0               | 2         | 0.61%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 2         | 0.61%   |
| Pegatron FL308AA-ABD IQ512de               | 2         | 0.61%   |
| MSI MS-7C37                                | 2         | 0.61%   |
| MSI MS-7788                                | 2         | 0.61%   |
| Lenovo ThinkPad T410 2522A92               | 2         | 0.61%   |
| HP Spectre x360 Convertible 13-ae0xx       | 2         | 0.61%   |
| HP ProBook 4730s                           | 2         | 0.61%   |
| HP EliteBook 8760w                         | 2         | 0.61%   |
| Gigabyte F2A88XM-D3HP                      | 2         | 0.61%   |
| Gigabyte B450M DS3H                        | 2         | 0.61%   |
| Dell XPS 13 9310                           | 2         | 0.61%   |
| Dell Inspiron 5570                         | 2         | 0.61%   |
| Dell Inspiron 1501                         | 2         | 0.61%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 0.61%   |
| ASUS TUF B450-PLUS GAMING                  | 2         | 0.61%   |
| ASUS ROG STRIX Z370-F GAMING               | 2         | 0.61%   |
| ASUS ROG STRIX X570-E GAMING               | 2         | 0.61%   |
| ASUS PRIME B350-PLUS                       | 2         | 0.61%   |
| ASUS PRIME A320M-K                         | 2         | 0.61%   |
| ASUS P7H55-M SI                            | 2         | 0.61%   |
| ASUS All Series                            | 2         | 0.61%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.31%   |
| Toshiba TECRA S10                          | 1         | 0.31%   |
| Toshiba TECRA A11                          | 1         | 0.31%   |
| Toshiba Satellite R630                     | 1         | 0.31%   |
| Toshiba Satellite Pro U400                 | 1         | 0.31%   |
| Toshiba Satellite A100                     | 1         | 0.31%   |
| Toshiba QOSMIO X500                        | 1         | 0.31%   |
| Supermicro X7SBi-LN4                       | 1         | 0.31%   |
| Supermicro PCplus T600-C246                | 1         | 0.31%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 (DT)    | 1         | 0.31%   |
| Pegatron Pro 3010 Microtower PC            | 1         | 0.31%   |
| Pegatron 2A73                              | 1         | 0.31%   |
| PC Specialist Fusion IV                    | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 35        | 10.74%  |
| HP ProBook            | 12        | 3.68%   |
| HP EliteBook          | 12        | 3.68%   |
| ASUS PRIME            | 12        | 3.68%   |
| Lenovo ThinkCentre    | 8         | 2.45%   |
| Dell Inspiron         | 8         | 2.45%   |
| ASUS ROG              | 8         | 2.45%   |
| HP ZBook              | 6         | 1.84%   |
| HP Compaq             | 6         | 1.84%   |
| ASUS TUF              | 6         | 1.84%   |
| Toshiba Satellite     | 5         | 1.53%   |
| RPi Raspberry         | 5         | 1.53%   |
| Lenovo IdeaPad        | 5         | 1.53%   |
| Dell Latitude         | 5         | 1.53%   |
| HP Pavilion           | 4         | 1.23%   |
| HP 255                | 4         | 1.23%   |
| HP 250                | 4         | 1.23%   |
| ASUS VivoBook         | 4         | 1.23%   |
| Acer Aspire           | 4         | 1.23%   |
| Unknown               | 4         | 1.23%   |
| MSI MS-7C02           | 3         | 0.92%   |
| HP EliteDesk          | 3         | 0.92%   |
| Gigabyte B450M        | 3         | 0.92%   |
| Fujitsu LIFEBOOK      | 3         | 0.92%   |
| Dell XPS              | 3         | 0.92%   |
| ASUS ASUS             | 3         | 0.92%   |
| Toshiba TECRA         | 2         | 0.61%   |
| Pegatron FL308AA-ABD  | 2         | 0.61%   |
| MSI MS-7C37           | 2         | 0.61%   |
| MSI MS-7788           | 2         | 0.61%   |
| Lenovo Yoga           | 2         | 0.61%   |
| Lenovo ThinkStation   | 2         | 0.61%   |
| HP Spectre            | 2         | 0.61%   |
| HP Laptop             | 2         | 0.61%   |
| Gigabyte F2A88XM-D3HP | 2         | 0.61%   |
| Dell Precision        | 2         | 0.61%   |
| ASUS SABERTOOTH       | 2         | 0.61%   |
| ASUS P7H55-M          | 2         | 0.61%   |
| ASUS All              | 2         | 0.61%   |
| Acer Predator         | 2         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 34        | 10.43%  |
| 2020    | 29        | 8.9%    |
| 2018    | 29        | 8.9%    |
| 2017    | 29        | 8.9%    |
| 2011    | 27        | 8.28%   |
| 2009    | 22        | 6.75%   |
| 2013    | 21        | 6.44%   |
| 2015    | 20        | 6.13%   |
| 2014    | 18        | 5.52%   |
| 2010    | 18        | 5.52%   |
| 2012    | 15        | 4.6%    |
| 2008    | 15        | 4.6%    |
| 2021    | 13        | 3.99%   |
| 2016    | 10        | 3.07%   |
| 2006    | 9         | 2.76%   |
| 2007    | 8         | 2.45%   |
| Unknown | 7         | 2.15%   |
| 2022    | 2         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 172       | 52.76%  |
| Desktop        | 127       | 38.96%  |
| System on chip | 5         | 1.53%   |
| Mini pc        | 5         | 1.53%   |
| All in one     | 5         | 1.53%   |
| Convertible    | 4         | 1.23%   |
| Tablet         | 3         | 0.92%   |
| Server         | 3         | 0.92%   |
| Phone          | 2         | 0.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 305       | 92.71%  |
| Enabled  | 24        | 7.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 325       | 99.69%  |
| Yes  | 1         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 73        | 22.26%  |
| 16.01-24.0      | 70        | 21.34%  |
| 8.01-16.0       | 67        | 20.43%  |
| 4.01-8.0        | 53        | 16.16%  |
| 32.01-64.0      | 32        | 9.76%   |
| 1.01-2.0        | 10        | 3.05%   |
| 2.01-3.0        | 8         | 2.44%   |
| 64.01-256.0     | 6         | 1.83%   |
| 24.01-32.0      | 5         | 1.52%   |
| 0.51-1.0        | 3         | 0.91%   |
| More than 256.0 | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 121       | 33.24%  |
| 2.01-3.0   | 89        | 24.45%  |
| 4.01-8.0   | 56        | 15.38%  |
| 3.01-4.0   | 42        | 11.54%  |
| 0.51-1.0   | 26        | 7.14%   |
| 8.01-16.0  | 18        | 4.95%   |
| 0.01-0.5   | 7         | 1.92%   |
| 16.01-24.0 | 4         | 1.1%    |
| 24.01-32.0 | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 202       | 60.3%   |
| 2      | 78        | 23.28%  |
| 3      | 25        | 7.46%   |
| 4      | 10        | 2.99%   |
| 5      | 5         | 1.49%   |
| 0      | 5         | 1.49%   |
| 6      | 4         | 1.19%   |
| 8      | 3         | 0.9%    |
| 7      | 2         | 0.6%    |
| 11     | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 55.96%  |
| Yes       | 144       | 44.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 293       | 89.6%   |
| No        | 34        | 10.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 68.6%   |
| No        | 103       | 31.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 55.18%  |
| No        | 147       | 44.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Slovenia | 326       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 121       | 34.38%  |
| Maribor                 | 9         | 2.56%   |
| Kranj                   | 9         | 2.56%   |
| Celje                   | 9         | 2.56%   |
| Vrhnika                 | 8         | 2.27%   |
| Koper                   | 8         | 2.27%   |
| Novo Mesto              | 6         | 1.7%    |
| Kamnik                  | 6         | 1.7%    |
| Trzin                   | 5         | 1.42%   |
| Grosuplje               | 5         | 1.42%   |
| Žalec                  | 4         | 1.14%   |
| Slovenske Konjice       | 4         | 1.14%   |
| Rence                   | 4         | 1.14%   |
| Portorož               | 4         | 1.14%   |
| Poljane nad Skofjo Loko | 4         | 1.14%   |
| Nova Gorica             | 4         | 1.14%   |
| Ajdovščina            | 4         | 1.14%   |
| Škofja Loka            | 3         | 0.85%   |
| Radovljica              | 3         | 0.85%   |
| Ptuj                    | 3         | 0.85%   |
| Pragersko               | 3         | 0.85%   |
| Petrovce                | 3         | 0.85%   |
| Murska Sobota           | 3         | 0.85%   |
| Logatec                 | 3         | 0.85%   |
| Ziri                    | 2         | 0.57%   |
| Zgornja Besnica         | 2         | 0.57%   |
| Velike Lašče          | 2         | 0.57%   |
| Velenje                 | 2         | 0.57%   |
| Trzic                   | 2         | 0.57%   |
| Smarje pri Jelsah       | 2         | 0.57%   |
| Slovenj Gradec          | 2         | 0.57%   |
| Sežana                 | 2         | 0.57%   |
| Šentjur pri Celju      | 2         | 0.57%   |
| Sempeter pri Gorici     | 2         | 0.57%   |
| Puconci                 | 2         | 0.57%   |
| Postojna                | 2         | 0.57%   |
| Oplotnica               | 2         | 0.57%   |
| Muta                    | 2         | 0.57%   |
| Loski Potok             | 2         | 0.57%   |
| Ljutomer                | 2         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 84        | 142    | 17.83%  |
| Samsung Electronics     | 70        | 109    | 14.86%  |
| Seagate                 | 49        | 75     | 10.4%   |
| Toshiba                 | 37        | 51     | 7.86%   |
| Kingston                | 35        | 46     | 7.43%   |
| Crucial                 | 32        | 44     | 6.79%   |
| SanDisk                 | 21        | 25     | 4.46%   |
| Unknown                 | 18        | 21     | 3.82%   |
| SK hynix                | 13        | 17     | 2.76%   |
| Hitachi                 | 13        | 16     | 2.76%   |
| HGST                    | 11        | 12     | 2.34%   |
| Intel                   | 9         | 10     | 1.91%   |
| Intenso                 | 7         | 9      | 1.49%   |
| Corsair                 | 6         | 9      | 1.27%   |
| OCZ                     | 4         | 7      | 0.85%   |
| KIOXIA                  | 4         | 4      | 0.85%   |
| JMicron Technology      | 4         | 4      | 0.85%   |
| Transcend               | 3         | 4      | 0.64%   |
| Silicon Motion          | 3         | 4      | 0.64%   |
| PNY                     | 3         | 3      | 0.64%   |
| Patriot                 | 3         | 5      | 0.64%   |
| Micron Technology       | 3         | 3      | 0.64%   |
| Fujitsu                 | 3         | 4      | 0.64%   |
| Apacer                  | 3         | 5      | 0.64%   |
| Team                    | 2         | 2      | 0.42%   |
| LITEONIT                | 2         | 3      | 0.42%   |
| LITEON                  | 2         | 2      | 0.42%   |
| Leven                   | 2         | 2      | 0.42%   |
| Lenovo                  | 2         | 2      | 0.42%   |
| Hewlett-Packard         | 2         | 2      | 0.42%   |
| Gigabyte Technology     | 2         | 4      | 0.42%   |
| China                   | 2         | 2      | 0.42%   |
| Apple                   | 2         | 3      | 0.42%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.21%   |
| TS512GMT                | 1         | 5      | 0.21%   |
| SPCC                    | 1         | 2      | 0.21%   |
| SABRENT                 | 1         | 1      | 0.21%   |
| Realtek                 | 1         | 1      | 0.21%   |
| Phison Electronics      | 1         | 1      | 0.21%   |
| Phison                  | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 10        | 1.89%   |
| Crucial CT240BX500SSD1 240GB                        | 9         | 1.7%    |
| Toshiba DT01ACA100 1TB                              | 6         | 1.13%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 6         | 1.13%   |
| Samsung SSD 850 EVO 250GB                           | 5         | 0.94%   |
| Samsung NVMe SSD Drive 512GB                        | 5         | 0.94%   |
| HGST HTS721010A9E630 1TB                            | 5         | 0.94%   |
| WDC WD10EARS-00Y5B1 1TB                             | 4         | 0.75%   |
| Unknown MMC Card  16GB                              | 4         | 0.75%   |
| Toshiba HDWD120 2TB                                 | 4         | 0.75%   |
| SanDisk SSD PLUS 1000GB                             | 4         | 0.75%   |
| Kingston SUV400S37240G 240GB SSD                    | 4         | 0.75%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 0.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 3         | 0.57%   |
| Unknown MMC Card  32GB                              | 3         | 0.57%   |
| Toshiba DT01ACA200 2TB                              | 3         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.57%   |
| SanDisk NVMe SSD Drive 512GB                        | 3         | 0.57%   |
| SanDisk NVMe SSD Drive 500GB                        | 3         | 0.57%   |
| Samsung SSD 980 1TB                                 | 3         | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB                      | 3         | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.57%   |
| Samsung SSD 860 EVO 1TB                             | 3         | 0.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 0.57%   |
| JMicron Generic 200GB                               | 3         | 0.57%   |
| Intenso 128GB                                       | 3         | 0.57%   |
| Hitachi HTS547575A9E384 752GB                       | 3         | 0.57%   |
| HGST HTS545050A7E680 500GB                          | 3         | 0.57%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.57%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.57%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 2         | 0.38%   |
| WDC WDS500G2B0A 500GB SSD                           | 2         | 0.38%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 2         | 0.38%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 2         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2         | 0.38%   |
| WDC WD5000AAKX-001CA0 500GB                         | 2         | 0.38%   |
| WDC WD5000AADS-00S9B0 500GB                         | 2         | 0.38%   |
| WDC WD5000AACS-00G8B1 500GB                         | 2         | 0.38%   |
| WDC WD40PURZ-85TTDY0 4TB                            | 2         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 65        | 114    | 36.31%  |
| Seagate             | 47        | 71     | 26.26%  |
| Toshiba             | 27        | 38     | 15.08%  |
| Hitachi             | 13        | 16     | 7.26%   |
| HGST                | 11        | 12     | 6.15%   |
| JMicron Technology  | 3         | 3      | 1.68%   |
| Fujitsu             | 3         | 4      | 1.68%   |
| Samsung Electronics | 2         | 2      | 1.12%   |
| Unknown             | 1         | 1      | 0.56%   |
| SABRENT             | 1         | 1      | 0.56%   |
| Maxtor              | 1         | 1      | 0.56%   |
| Intenso             | 1         | 1      | 0.56%   |
| IBM-ESXS            | 1         | 1      | 0.56%   |
| HGST HTS            | 1         | 1      | 0.56%   |
| ASMT109x            | 1         | 1      | 0.56%   |
| Apple               | 1         | 2      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 45     | 18.13%  |
| Kingston            | 30        | 37     | 17.54%  |
| Crucial             | 30        | 42     | 17.54%  |
| WDC                 | 18        | 20     | 10.53%  |
| SanDisk             | 13        | 16     | 7.6%    |
| Intel               | 6         | 7      | 3.51%   |
| SK hynix            | 4         | 4      | 2.34%   |
| OCZ                 | 4         | 7      | 2.34%   |
| Corsair             | 4         | 7      | 2.34%   |
| Transcend           | 3         | 4      | 1.75%   |
| PNY                 | 3         | 3      | 1.75%   |
| Patriot             | 3         | 5      | 1.75%   |
| Intenso             | 3         | 3      | 1.75%   |
| Toshiba             | 2         | 2      | 1.17%   |
| LITEONIT            | 2         | 3      | 1.17%   |
| LITEON              | 2         | 2      | 1.17%   |
| Leven               | 2         | 2      | 1.17%   |
| China               | 2         | 2      | 1.17%   |
| Apacer              | 2         | 3      | 1.17%   |
| Team                | 1         | 1      | 0.58%   |
| Micron Technology   | 1         | 1      | 0.58%   |
| KingDian            | 1         | 1      | 0.58%   |
| Integral            | 1         | 1      | 0.58%   |
| GOODRAM             | 1         | 1      | 0.58%   |
| Gigabyte Technology | 1         | 2      | 0.58%   |
| A-DATA Technology   | 1         | 1      | 0.58%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 154       | 269    | 35.81%  |
| SSD     | 148       | 222    | 34.42%  |
| NVMe    | 105       | 147    | 24.42%  |
| MMC     | 15        | 18     | 3.49%   |
| Unknown | 8         | 15     | 1.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 242       | 477    | 63.19%  |
| NVMe | 105       | 146    | 27.42%  |
| SAS  | 21        | 30     | 5.48%   |
| MMC  | 15        | 18     | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 188       | 291    | 59.12%  |
| 0.51-1.0   | 87        | 138    | 27.36%  |
| 1.01-2.0   | 23        | 30     | 7.23%   |
| 3.01-4.0   | 9         | 16     | 2.83%   |
| 4.01-10.0  | 6         | 10     | 1.89%   |
| 2.01-3.0   | 3         | 4      | 0.94%   |
| 10.01-20.0 | 2         | 2      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 88        | 25.29%  |
| 251-500        | 76        | 21.84%  |
| 501-1000       | 47        | 13.51%  |
| 1-20           | 32        | 9.2%    |
| 1001-2000      | 31        | 8.91%   |
| 51-100         | 22        | 6.32%   |
| 21-50          | 15        | 4.31%   |
| 2001-3000      | 15        | 4.31%   |
| More than 3000 | 11        | 3.16%   |
| Unknown        | 11        | 3.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 141       | 39.94%  |
| 21-50          | 49        | 13.88%  |
| 101-250        | 46        | 13.03%  |
| 51-100         | 46        | 13.03%  |
| 251-500        | 25        | 7.08%   |
| 1001-2000      | 13        | 3.68%   |
| 501-1000       | 13        | 3.68%   |
| Unknown        | 11        | 3.12%   |
| 2001-3000      | 7         | 1.98%   |
| More than 3000 | 2         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB               | 2         | 2      | 5.26%   |
| WDC WDS480G2G0A-00JH30 480GB SSD         | 1         | 1      | 2.63%   |
| WDC WD5000AADS-00S9B0 500GB              | 1         | 1      | 2.63%   |
| WDC WD40EFRX-68N32N0 4TB                 | 1         | 1      | 2.63%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 2.63%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1         | 1      | 2.63%   |
| Toshiba Q300. 240GB SSD                  | 1         | 1      | 2.63%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 5      | 2.63%   |
| Toshiba DT01ACA300 3TB                   | 1         | 1      | 2.63%   |
| SK hynix HFS256G32MND-2200A 256GB SSD    | 1         | 1      | 2.63%   |
| Seagate ST98823AS 80GB                   | 1         | 1      | 2.63%   |
| Seagate ST9750420AS 752GB                | 1         | 1      | 2.63%   |
| Seagate ST9500423AS 500GB                | 1         | 1      | 2.63%   |
| Seagate ST9500325AS 500GB                | 1         | 2      | 2.63%   |
| Seagate ST3500514NS 500GB                | 1         | 1      | 2.63%   |
| Seagate ST3500320NS 500GB                | 1         | 1      | 2.63%   |
| Seagate ST3320620AS 320GB                | 1         | 1      | 2.63%   |
| Seagate ST3200822AS 200GB                | 1         | 1      | 2.63%   |
| Seagate ST2000DM001-1CH164 2TB           | 1         | 1      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 2.63%   |
| Seagate ST1000DM003-1CH162 1TB           | 1         | 1      | 2.63%   |
| SanDisk SSD PLUS 240GB                   | 1         | 1      | 2.63%   |
| SanDisk SSD PLUS 1000GB                  | 1         | 1      | 2.63%   |
| SanDisk SD7SB2Q512G1001 512GB SSD        | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 970 EVO 1TB      | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 840 Series 120GB | 1         | 1      | 2.63%   |
| OCZ VERTEX3 120GB SSD                    | 1         | 1      | 2.63%   |
| Kingston SV300S37A120G 120GB SSD         | 1         | 1      | 2.63%   |
| Kingston SA400S37240G 240GB SSD          | 1         | 1      | 2.63%   |
| Intel SSDSCKKW240H6 240GB                | 1         | 1      | 2.63%   |
| Intel SSDSA2M160G2GC 160GB               | 1         | 1      | 2.63%   |
| Hitachi HTS727550A9E364 500GB            | 1         | 1      | 2.63%   |
| Hitachi HTS543280L9SA00 80GB             | 1         | 1      | 2.63%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 2.63%   |
| Hewlett-Packard SSD EX900 500GB          | 1         | 1      | 2.63%   |
| Crucial M4-CT128M4SSD2 128GB             | 1         | 1      | 2.63%   |
| Crucial CT120M500SSD1 120GB              | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 12     | 25.71%  |
| WDC                 | 4         | 5      | 11.43%  |
| Toshiba             | 3         | 7      | 8.57%   |
| SanDisk             | 3         | 3      | 8.57%   |
| HGST                | 3         | 3      | 8.57%   |
| Samsung Electronics | 2         | 2      | 5.71%   |
| Kingston            | 2         | 2      | 5.71%   |
| Intel               | 2         | 2      | 5.71%   |
| Hitachi             | 2         | 2      | 5.71%   |
| Crucial             | 2         | 2      | 5.71%   |
| SK hynix            | 1         | 1      | 2.86%   |
| OCZ                 | 1         | 1      | 2.86%   |
| Hewlett-Packard     | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 12     | 47.37%  |
| WDC     | 3         | 4      | 15.79%  |
| HGST    | 3         | 3      | 15.79%  |
| Toshiba | 2         | 6      | 10.53%  |
| Hitachi | 2         | 2      | 10.53%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 27     | 53.13%  |
| SSD  | 13        | 14     | 40.63%  |
| NVMe | 2         | 2      | 6.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK6465GSX 640GB | 1         | 2      | 50%     |
| SPCC M.2 PCIe SSD 2TB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 50%     |
| SPCC    | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 199       | 360    | 55.59%  |
| Works    | 125       | 265    | 34.92%  |
| Malfunc  | 32        | 43     | 8.94%   |
| Failed   | 2         | 3      | 0.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 221       | 52.62%  |
| AMD                              | 60        | 14.29%  |
| Samsung Electronics              | 47        | 11.19%  |
| SanDisk                          | 16        | 3.81%   |
| Toshiba America Info Systems     | 10        | 2.38%   |
| SK hynix                         | 9         | 2.14%   |
| Kingston Technology Company      | 7         | 1.67%   |
| Silicon Motion                   | 6         | 1.43%   |
| Phison Electronics               | 6         | 1.43%   |
| JMicron Technology               | 6         | 1.43%   |
| ASMedia Technology               | 6         | 1.43%   |
| Marvell Technology Group         | 5         | 1.19%   |
| KIOXIA                           | 3         | 0.71%   |
| Nvidia                           | 2         | 0.48%   |
| Micron/Crucial Technology        | 2         | 0.48%   |
| Micron Technology                | 2         | 0.48%   |
| Lenovo                           | 2         | 0.48%   |
| Union Memory (Shenzhen)          | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Silicon Image                    | 1         | 0.24%   |
| Shenzhen Longsys Electronics     | 1         | 0.24%   |
| Seagate Technology               | 1         | 0.24%   |
| OCZ Technology Group             | 1         | 0.24%   |
| LSI Logic / Symbios Logic        | 1         | 0.24%   |
| Integrated Technology Express    | 1         | 0.24%   |
| Hewlett-Packard                  | 1         | 0.24%   |
| Broadcom / LSI                   | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 42        | 8.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 27        | 5.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 2.66%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12        | 2.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11        | 2.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 2.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 2.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8         | 1.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 7         | 1.43%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 1.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 7         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 7         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 7         | 1.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 1.23%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5         | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 1.02%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5         | 1.02%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5         | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5         | 1.02%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 4         | 0.82%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 4         | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 0.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 0.82%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 4         | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 227       | 54.7%   |
| NVMe | 109       | 26.27%  |
| IDE  | 56        | 13.49%  |
| RAID | 20        | 4.82%   |
| SAS  | 2         | 0.48%   |
| SCSI | 1         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 252       | 77.3%   |
| AMD    | 67        | 20.55%  |
| ARM    | 7         | 2.15%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.53%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.53%   |
| ARM Processor                                 | 5         | 1.53%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 1.23%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 4         | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.92%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 3         | 0.92%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 0.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.92%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 0.92%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.92%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 0.92%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 0.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.92%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.92%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 3         | 0.92%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.61%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.61%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.61%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.61%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.61%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.61%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.61%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.61%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.61%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.61%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2         | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.61%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.61%   |
| Intel Core i5-3550 CPU @ 3.30GHz              | 2         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 79        | 24.23%  |
| Intel Core i7           | 66        | 20.25%  |
| Intel Core 2 Duo        | 27        | 8.28%   |
| Intel Core i3           | 22        | 6.75%   |
| AMD Ryzen 5             | 20        | 6.13%   |
| Other                   | 15        | 4.6%    |
| Intel Celeron           | 12        | 3.68%   |
| Intel Xeon              | 11        | 3.37%   |
| AMD Ryzen 7             | 11        | 3.37%   |
| Intel Pentium           | 9         | 2.76%   |
| AMD Ryzen 9             | 9         | 2.76%   |
| AMD Ryzen 3             | 8         | 2.45%   |
| Intel Core 2            | 4         | 1.23%   |
| Intel Core 2 Quad       | 3         | 0.92%   |
| Intel Atom              | 3         | 0.92%   |
| Intel Genuine           | 2         | 0.61%   |
| AMD FX                  | 2         | 0.61%   |
| AMD A10                 | 2         | 0.61%   |
| Intel Pentium Silver    | 1         | 0.31%   |
| Intel Pentium Dual-Core | 1         | 0.31%   |
| Intel Pentium Dual      | 1         | 0.31%   |
| Intel Pentium D         | 1         | 0.31%   |
| Intel Core i9           | 1         | 0.31%   |
| ARM AArch64             | 1         | 0.31%   |
| AMD Turion II Dual-Core | 1         | 0.31%   |
| AMD Turion II           | 1         | 0.31%   |
| AMD Ryzen 3 PRO         | 1         | 0.31%   |
| AMD Phenom II X6        | 1         | 0.31%   |
| AMD Phenom II X4        | 1         | 0.31%   |
| AMD Mobile Sempron      | 1         | 0.31%   |
| AMD E1                  | 1         | 0.31%   |
| AMD E                   | 1         | 0.31%   |
| AMD C-60                | 1         | 0.31%   |
| AMD Athlon X4           | 1         | 0.31%   |
| AMD Athlon Neo          | 1         | 0.31%   |
| AMD Athlon II X2        | 1         | 0.31%   |
| AMD Athlon 64 X2        | 1         | 0.31%   |
| AMD A8                  | 1         | 0.31%   |
| AMD A6                  | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 131       | 40.18%  |
| 2      | 127       | 38.96%  |
| 6      | 37        | 11.35%  |
| 8      | 19        | 5.83%   |
| 12     | 7         | 2.15%   |
| 1      | 4         | 1.23%   |
| 16     | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 321       | 98.47%  |
| 2      | 5         | 1.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 202       | 61.96%  |
| 1      | 124       | 38.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 311       | 94.82%  |
| Unknown        | 14        | 4.27%   |
| 32-bit         | 3         | 0.91%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 20.35%  |
| 0x206a7    | 18        | 5.31%   |
| 0x306a9    | 16        | 4.72%   |
| 0x306c3    | 14        | 4.13%   |
| 0x906ea    | 11        | 3.24%   |
| 0x906e9    | 11        | 3.24%   |
| 0x806ec    | 10        | 2.95%   |
| 0x1067a    | 10        | 2.95%   |
| 0x806ea    | 9         | 2.65%   |
| 0x506e3    | 9         | 2.65%   |
| 0x40651    | 9         | 2.65%   |
| 0x20655    | 9         | 2.65%   |
| 0x10676    | 9         | 2.65%   |
| 0x30678    | 8         | 2.36%   |
| 0x806c1    | 7         | 2.06%   |
| 0x6fd      | 7         | 2.06%   |
| 0x106e5    | 7         | 2.06%   |
| 0x906ed    | 5         | 1.47%   |
| 0x08108102 | 5         | 1.47%   |
| 0x6fb      | 4         | 1.18%   |
| 0x306d4    | 4         | 1.18%   |
| 0x20652    | 4         | 1.18%   |
| 0x0a201016 | 4         | 1.18%   |
| 0x0800820d | 4         | 1.18%   |
| 0xa0652    | 3         | 0.88%   |
| 0x706e5    | 3         | 0.88%   |
| 0x406e3    | 3         | 0.88%   |
| 0x0a201009 | 3         | 0.88%   |
| 0x08600106 | 3         | 0.88%   |
| 0x08108109 | 3         | 0.88%   |
| 0x0810100b | 3         | 0.88%   |
| 0x08001138 | 3         | 0.88%   |
| 0xa0671    | 2         | 0.59%   |
| 0x906eb    | 2         | 0.59%   |
| 0x806eb    | 2         | 0.59%   |
| 0x706a1    | 2         | 0.59%   |
| 0x6e8      | 2         | 0.59%   |
| 0x506c9    | 2         | 0.59%   |
| 0x206d7    | 2         | 0.59%   |
| 0x08701021 | 2         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 60        | 18.4%   |
| Haswell       | 28        | 8.59%   |
| SandyBridge   | 24        | 7.36%   |
| Penryn        | 21        | 6.44%   |
| IvyBridge     | 20        | 6.13%   |
| Core          | 17        | 5.21%   |
| Westmere      | 14        | 4.29%   |
| Skylake       | 14        | 4.29%   |
| Unknown       | 14        | 4.29%   |
| Zen+          | 13        | 3.99%   |
| Zen 3         | 12        | 3.68%   |
| Silvermont    | 10        | 3.07%   |
| Zen 2         | 9         | 2.76%   |
| Zen           | 9         | 2.76%   |
| Nehalem       | 9         | 2.76%   |
| Broadwell     | 8         | 2.45%   |
| TigerLake     | 7         | 2.15%   |
| Piledriver    | 5         | 1.53%   |
| K10           | 5         | 1.53%   |
| IceLake       | 5         | 1.53%   |
| CometLake     | 5         | 1.53%   |
| K8 Hammer     | 3         | 0.92%   |
| Goldmont plus | 3         | 0.92%   |
| P6            | 2         | 0.61%   |
| Goldmont      | 2         | 0.61%   |
| Bobcat        | 2         | 0.61%   |
| Steamroller   | 1         | 0.31%   |
| NetBurst      | 1         | 0.31%   |
| Jaguar        | 1         | 0.31%   |
| Excavator     | 1         | 0.31%   |
| Bonnell       | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 175       | 45.69%  |
| Nvidia                           | 107       | 27.94%  |
| AMD                              | 98        | 25.59%  |
| Matrox Electronics Systems       | 2         | 0.52%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 16        | 4.07%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 11        | 2.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 10        | 2.54%   |
| Intel UHD Graphics 620                                                                | 10        | 2.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 2.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 9         | 2.29%   |
| Intel Core Processor Integrated Graphics Controller                                   | 8         | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 2.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 8         | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 1.78%   |
| Intel HD Graphics 630                                                                 | 7         | 1.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 6         | 1.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 6         | 1.53%   |
| AMD Renoir                                                                            | 6         | 1.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 5         | 1.27%   |
| Intel HD Graphics 5500                                                                | 5         | 1.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 5         | 1.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 1.27%   |
| AMD Lucienne                                                                          | 5         | 1.27%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 1.02%   |
| AMD Juniper XT [Radeon HD 5770]                                                       | 4         | 1.02%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                    | 4         | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 3         | 0.76%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                    | 3         | 0.76%   |
| Nvidia GM206 [GeForce GTX 960]                                                        | 3         | 0.76%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 3         | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 3         | 0.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 0.76%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 3         | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 3         | 0.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 0.76%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                 | 2         | 0.51%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 2         | 0.51%   |
| Nvidia GP107M [GeForce MX350]                                                         | 2         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.51%   |
| Nvidia GP107 [GeForce GTX 1050]                                                       | 2         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 122       | 37.2%   |
| 1 x AMD        | 68        | 20.73%  |
| 1 x Nvidia     | 66        | 20.12%  |
| Intel + Nvidia | 32        | 9.76%   |
| Intel + AMD    | 17        | 5.18%   |
| AMD + Nvidia   | 9         | 2.74%   |
| Other          | 7         | 2.13%   |
| 2 x AMD        | 4         | 1.22%   |
| 1 x Matrox     | 2         | 0.61%   |
| 1 x SiS        | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 253       | 76.44%  |
| Proprietary | 56        | 16.92%  |
| Unknown     | 22        | 6.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 187       | 55.33%  |
| 1.01-2.0   | 50        | 14.79%  |
| 0.01-0.5   | 30        | 8.88%   |
| 0.51-1.0   | 24        | 7.1%    |
| 3.01-4.0   | 16        | 4.73%   |
| 7.01-8.0   | 15        | 4.44%   |
| 5.01-6.0   | 8         | 2.37%   |
| 8.01-16.0  | 4         | 1.18%   |
| 2.01-3.0   | 3         | 0.89%   |
| 4.01-5.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 52        | 14.53%  |
| AU Optronics            | 48        | 13.41%  |
| Dell                    | 37        | 10.34%  |
| LG Display              | 27        | 7.54%   |
| AOC                     | 24        | 6.7%    |
| Chimei Innolux          | 21        | 5.87%   |
| BOE                     | 19        | 5.31%   |
| Goldstar                | 18        | 5.03%   |
| Lenovo                  | 17        | 4.75%   |
| Philips                 | 15        | 4.19%   |
| Hewlett-Packard         | 11        | 3.07%   |
| Chi Mei Optoelectronics | 7         | 1.96%   |
| Acer                    | 5         | 1.4%    |
| Sony                    | 4         | 1.12%   |
| Ancor Communications    | 4         | 1.12%   |
| ViewSonic               | 3         | 0.84%   |
| Unknown                 | 3         | 0.84%   |
| Sharp                   | 3         | 0.84%   |
| LG Philips              | 3         | 0.84%   |
| Iiyama                  | 3         | 0.84%   |
| HannStar                | 3         | 0.84%   |
| BenQ                    | 3         | 0.84%   |
| Apple                   | 3         | 0.84%   |
| TMX                     | 2         | 0.56%   |
| PANDA                   | 2         | 0.56%   |
| CSO                     | 2         | 0.56%   |
| CPT                     | 2         | 0.56%   |
| ASUSTek Computer        | 2         | 0.56%   |
| Vestel Elektronik       | 1         | 0.28%   |
| Unknown (XXX)           | 1         | 0.28%   |
| RS                      | 1         | 0.28%   |
| NEC Computers           | 1         | 0.28%   |
| Medion                  | 1         | 0.28%   |
| LGD                     | 1         | 0.28%   |
| InfoVision              | 1         | 0.28%   |
| IBM                     | 1         | 0.28%   |
| Grundig                 | 1         | 0.28%   |
| Gericom                 | 1         | 0.28%   |
| FUN                     | 1         | 0.28%   |
| Eizo                    | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 1.87%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 4         | 1.07%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 4         | 1.07%   |
| Philips LCD Monitor FTV 1920x1080                                         | 3         | 0.8%    |
| Philips FTV PHL01EA 1920x1080 640x360mm 28.9-inch                         | 3         | 0.8%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                  | 3         | 0.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 3         | 0.8%    |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 0.8%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 3         | 0.8%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 2         | 0.53%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch      | 2         | 0.53%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 2         | 0.53%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch      | 2         | 0.53%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 376x301mm 19.0-inch      | 2         | 0.53%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 2         | 0.53%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                       | 2         | 0.53%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 2         | 0.53%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 2         | 0.53%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch                  | 2         | 0.53%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 2         | 0.53%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                   | 2         | 0.53%   |
| Goldstar ULTRAWIDE GSM5AE2 3440x1440 800x335mm 34.1-inch                  | 2         | 0.53%   |
| Dell U2515H DELD06E 2560x1440 553x311mm 25.0-inch                         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1376 1920x1080 293x165mm 13.2-inch          | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 0.53%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 0.53%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 0.53%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 2         | 0.53%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO479D 1920x1080 382x215mm 17.3-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 2         | 0.53%   |
| AOC LCD Monitor AG251FWG2 1920x1080                                       | 2         | 0.53%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                           | 2         | 0.53%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch                 | 1         | 0.27%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                    | 1         | 0.27%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 146       | 42.82%  |
| 1366x768 (WXGA)    | 40        | 11.73%  |
| 3840x2160 (4K)     | 23        | 6.74%   |
| 2560x1440 (QHD)    | 21        | 6.16%   |
| 1600x900 (HD+)     | 21        | 6.16%   |
| 1680x1050 (WSXGA+) | 15        | 4.4%    |
| 1920x1200 (WUXGA)  | 14        | 4.11%   |
| 1280x1024 (SXGA)   | 13        | 3.81%   |
| 3440x1440          | 9         | 2.64%   |
| 1280x800 (WXGA)    | 8         | 2.35%   |
| 1440x900 (WXGA+)   | 7         | 2.05%   |
| 2560x1080          | 4         | 1.17%   |
| 2560x1600          | 3         | 0.88%   |
| 2288x1287          | 2         | 0.59%   |
| Unknown            | 2         | 0.59%   |
| 3840x1600          | 1         | 0.29%   |
| 3840x1200          | 1         | 0.29%   |
| 3840x1080          | 1         | 0.29%   |
| 3456x2160          | 1         | 0.29%   |
| 2736x1824          | 1         | 0.29%   |
| 2560x1024          | 1         | 0.29%   |
| 2520x1680          | 1         | 0.29%   |
| 2256x1504          | 1         | 0.29%   |
| 2048x1152          | 1         | 0.29%   |
| 1400x1050          | 1         | 0.29%   |
| 1280x960           | 1         | 0.29%   |
| 1280x720 (HD)      | 1         | 0.29%   |
| 1024x768 (XGA)     | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 88        | 24.44%  |
| 24      | 34        | 9.44%   |
| 17      | 30        | 8.33%   |
| 23      | 26        | 7.22%   |
| 27      | 22        | 6.11%   |
| 21      | 21        | 5.83%   |
| 13      | 21        | 5.83%   |
| 14      | 18        | 5%      |
| Unknown | 16        | 4.44%   |
| 34      | 13        | 3.61%   |
| 22      | 9         | 2.5%    |
| 19      | 9         | 2.5%    |
| 31      | 7         | 1.94%   |
| 18      | 6         | 1.67%   |
| 20      | 5         | 1.39%   |
| 12      | 5         | 1.39%   |
| 65      | 4         | 1.11%   |
| 54      | 3         | 0.83%   |
| 33      | 3         | 0.83%   |
| 142     | 2         | 0.56%   |
| 84      | 2         | 0.56%   |
| 72      | 2         | 0.56%   |
| 32      | 2         | 0.56%   |
| 25      | 2         | 0.56%   |
| 55      | 1         | 0.28%   |
| 49      | 1         | 0.28%   |
| 40      | 1         | 0.28%   |
| 39      | 1         | 0.28%   |
| 37      | 1         | 0.28%   |
| 29      | 1         | 0.28%   |
| 28      | 1         | 0.28%   |
| 16      | 1         | 0.28%   |
| 11      | 1         | 0.28%   |
| 10      | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 116       | 32.86%  |
| 501-600        | 75        | 21.25%  |
| 401-500        | 39        | 11.05%  |
| 351-400        | 38        | 10.76%  |
| 201-300        | 21        | 5.95%   |
| 701-800        | 18        | 5.1%    |
| Unknown        | 16        | 4.53%   |
| 601-700        | 12        | 3.4%    |
| 1001-1500      | 9         | 2.55%   |
| 1501-2000      | 4         | 1.13%   |
| 801-900        | 3         | 0.85%   |
| More than 2000 | 2         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 231       | 70.64%  |
| 16/10   | 46        | 14.07%  |
| 21/9    | 14        | 4.28%   |
| 5/4     | 13        | 3.98%   |
| Unknown | 13        | 3.98%   |
| 3/2     | 4         | 1.22%   |
| 4/3     | 3         | 0.92%   |
| 1.00    | 2         | 0.61%   |
| 32/9    | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 24.37%  |
| 201-250        | 67        | 18.77%  |
| 351-500        | 27        | 7.56%   |
| 81-90          | 26        | 7.28%   |
| 121-130        | 24        | 6.72%   |
| 151-200        | 23        | 6.44%   |
| 301-350        | 22        | 6.16%   |
| 251-300        | 16        | 4.48%   |
| Unknown        | 16        | 4.48%   |
| More than 1000 | 14        | 3.92%   |
| 71-80          | 12        | 3.36%   |
| 141-150        | 6         | 1.68%   |
| 61-70          | 5         | 1.4%    |
| 501-1000       | 4         | 1.12%   |
| 131-140        | 3         | 0.84%   |
| 91-100         | 2         | 0.56%   |
| 51-60          | 1         | 0.28%   |
| 41-50          | 1         | 0.28%   |
| 111-120        | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 116       | 33.82%  |
| 121-160       | 88        | 25.66%  |
| 101-120       | 85        | 24.78%  |
| 161-240       | 19        | 5.54%   |
| Unknown       | 16        | 4.66%   |
| 1-50          | 13        | 3.79%   |
| More than 240 | 6         | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 260       | 76.92%  |
| 2     | 57        | 16.86%  |
| 0     | 17        | 5.03%   |
| 3     | 3         | 0.89%   |
| 6     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 165       | 35.41%  |
| Intel                             | 163       | 34.98%  |
| Qualcomm Atheros                  | 44        | 9.44%   |
| Broadcom                          | 31        | 6.65%   |
| Ralink                            | 8         | 1.72%   |
| Ralink Technology                 | 6         | 1.29%   |
| Marvell Technology Group          | 6         | 1.29%   |
| ASUSTek Computer                  | 5         | 1.07%   |
| Sierra Wireless                   | 3         | 0.64%   |
| Samsung Electronics               | 3         | 0.64%   |
| Huawei Technologies               | 3         | 0.64%   |
| Hewlett-Packard                   | 3         | 0.64%   |
| Ericsson Business Mobile Networks | 3         | 0.64%   |
| MediaTek                          | 2         | 0.43%   |
| Linksys                           | 2         | 0.43%   |
| Broadcom Limited                  | 2         | 0.43%   |
| ZyDAS Technology                  | 1         | 0.21%   |
| VIA Technologies                  | 1         | 0.21%   |
| TP-Link                           | 1         | 0.21%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.21%   |
| Qualcomm Atheros Communications   | 1         | 0.21%   |
| Nvidia                            | 1         | 0.21%   |
| Microsoft                         | 1         | 0.21%   |
| Lenovo                            | 1         | 0.21%   |
| JMicron Technology                | 1         | 0.21%   |
| IMC Networks                      | 1         | 0.21%   |
| IBM                               | 1         | 0.21%   |
| Dell                              | 1         | 0.21%   |
| D-Link System                     | 1         | 0.21%   |
| D-Link                            | 1         | 0.21%   |
| Compal Electronics                | 1         | 0.21%   |
| Belkin Components                 | 1         | 0.21%   |
| ASIX Electronics                  | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 123       | 22.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 3.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.69%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.33%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 1.79%   |
| Intel Wireless 7260                                               | 9         | 1.61%   |
| Intel I211 Gigabit Network Connection                             | 9         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.08%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.08%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.9%    |
| Intel Wireless 7265                                               | 5         | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 4         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.54%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 3         | 0.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 0.54%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 108       | 45.57%  |
| Qualcomm Atheros                  | 36        | 15.19%  |
| Realtek Semiconductor             | 32        | 13.5%   |
| Broadcom                          | 22        | 9.28%   |
| Ralink                            | 8         | 3.38%   |
| Ralink Technology                 | 6         | 2.53%   |
| ASUSTek Computer                  | 5         | 2.11%   |
| Sierra Wireless                   | 3         | 1.27%   |
| MediaTek                          | 2         | 0.84%   |
| Hewlett-Packard                   | 2         | 0.84%   |
| Broadcom Limited                  | 2         | 0.84%   |
| ZyDAS Technology                  | 1         | 0.42%   |
| TP-Link                           | 1         | 0.42%   |
| Qualcomm Atheros Communications   | 1         | 0.42%   |
| Marvell Technology Group          | 1         | 0.42%   |
| Linksys                           | 1         | 0.42%   |
| IMC Networks                      | 1         | 0.42%   |
| Ericsson Business Mobile Networks | 1         | 0.42%   |
| Dell                              | 1         | 0.42%   |
| D-Link System                     | 1         | 0.42%   |
| D-Link                            | 1         | 0.42%   |
| Belkin Components                 | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 13        | 5.46%   |
| Intel Wireless 8265 / 8275                                              | 11        | 4.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 4.2%    |
| Intel Wireless 7260                                                     | 9         | 3.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 2.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.52%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 2.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.1%    |
| Intel Wireless 7265                                                     | 5         | 2.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.1%    |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.68%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.26%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 1.26%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 1.26%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.26%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.26%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.26%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 2         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.84%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.84%   |
| Intel Wireless 8260                                                     | 2         | 0.84%   |
| Intel Wireless 3165                                                     | 2         | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 155       | 49.52%  |
| Intel                            | 110       | 35.14%  |
| Broadcom                         | 14        | 4.47%   |
| Qualcomm Atheros                 | 13        | 4.15%   |
| Marvell Technology Group         | 5         | 1.6%    |
| Samsung Electronics              | 3         | 0.96%   |
| Huawei Technologies              | 3         | 0.96%   |
| VIA Technologies                 | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Nvidia                           | 1         | 0.32%   |
| Microsoft                        | 1         | 0.32%   |
| Linksys                          | 1         | 0.32%   |
| Lenovo                           | 1         | 0.32%   |
| JMicron Technology               | 1         | 0.32%   |
| IBM                              | 1         | 0.32%   |
| Compal Electronics               | 1         | 0.32%   |
| ASIX Electronics                 | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 123       | 38.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 5.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 4.73%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 3.15%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.89%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.58%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.58%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.26%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.26%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.26%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.26%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.95%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.95%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.95%   |
| Intel 82562GT 10/100 Network Connection                           | 3         | 0.95%   |
| Huawei MLA-L11                                                    | 3         | 0.95%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.63%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 2         | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.63%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.63%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.63%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.63%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.63%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 2         | 0.63%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2         | 0.63%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.63%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 293       | 56.24%  |
| WiFi     | 225       | 43.19%  |
| Modem    | 3         | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 169       | 51.52%  |
| WiFi     | 159       | 48.48%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 187       | 57.01%  |
| 1     | 124       | 37.8%   |
| 0     | 11        | 3.35%   |
| 3     | 3         | 0.91%   |
| 4     | 2         | 0.61%   |
| 5     | 1         | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 308       | 92.77%  |
| Yes  | 24        | 7.23%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 42.39%  |
| IMC Networks                    | 15        | 8.15%   |
| Realtek Semiconductor           | 14        | 7.61%   |
| Qualcomm Atheros Communications | 14        | 7.61%   |
| Broadcom                        | 14        | 7.61%   |
| Cambridge Silicon Radio         | 10        | 5.43%   |
| ASUSTek Computer                | 8         | 4.35%   |
| Hewlett-Packard                 | 7         | 3.8%    |
| Lite-On Technology              | 4         | 2.17%   |
| Toshiba                         | 3         | 1.63%   |
| Ralink                          | 3         | 1.63%   |
| Apple                           | 3         | 1.63%   |
| Foxconn International           | 2         | 1.09%   |
| Edimax Technology               | 2         | 1.09%   |
| Ralink Technology               | 1         | 0.54%   |
| Qcom                            | 1         | 0.54%   |
| Marvell Semiconductor           | 1         | 0.54%   |
| Integrated System Solution      | 1         | 0.54%   |
| Foxconn / Hon Hai               | 1         | 0.54%   |
| Chicony Electronics             | 1         | 0.54%   |
| Askey Computer                  | 1         | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 27        | 14.67%  |
| Intel AX201 Bluetooth                               | 18        | 9.78%   |
| Intel AX200 Bluetooth                               | 13        | 7.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 5.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 5.43%   |
| IMC Networks Bluetooth Radio                        | 7         | 3.8%    |
| Realtek Bluetooth Radio                             | 6         | 3.26%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 2.72%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.17%   |
| Intel AX210 Bluetooth                               | 4         | 2.17%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 2.17%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.63%   |
| IMC Networks Bluetooth Device                       | 3         | 1.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.63%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 1.09%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.09%   |
| Lite-On Bluetooth Device                            | 2         | 1.09%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.09%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.09%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.09%   |
| Edimax Bluetooth Adapter                            | 2         | 1.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.09%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.09%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.09%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.09%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 1.09%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.09%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 1.09%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.54%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.54%   |
| Realtek CSR BS8510                                  | 1         | 0.54%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.54%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.54%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 240       | 53.69%  |
| AMD                              | 91        | 20.36%  |
| Nvidia                           | 78        | 17.45%  |
| C-Media Electronics              | 5         | 1.12%   |
| Logitech                         | 4         | 0.89%   |
| JMTek                            | 3         | 0.67%   |
| ASUSTek Computer                 | 3         | 0.67%   |
| Texas Instruments                | 2         | 0.45%   |
| BEHRINGER International          | 2         | 0.45%   |
| Yamaha                           | 1         | 0.22%   |
| Textech International            | 1         | 0.22%   |
| Syntek                           | 1         | 0.22%   |
| Sony                             | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| SAVITECH                         | 1         | 0.22%   |
| PreSonus Audio Electronics       | 1         | 0.22%   |
| Nam Tai E&E Products             | 1         | 0.22%   |
| Mackie Designs                   | 1         | 0.22%   |
| Lenovo                           | 1         | 0.22%   |
| Kingston Technology              | 1         | 0.22%   |
| iCreate Technologies             | 1         | 0.22%   |
| Hewlett-Packard                  | 1         | 0.22%   |
| Generalplus Technology           | 1         | 0.22%   |
| FiiO Electronics Technology      | 1         | 0.22%   |
| DSEA A/S                         | 1         | 0.22%   |
| Dell                             | 1         | 0.22%   |
| Creative Labs                    | 1         | 0.22%   |
| AKAI Professional M.I.           | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 26        | 4.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 24        | 4.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 20        | 3.84%   |
| Intel Sunrise Point-LP HD Audio                                                   | 16        | 3.07%   |
| Intel Cannon Lake PCH cAVS                                                        | 15        | 2.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 15        | 2.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 15        | 2.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12        | 2.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 12        | 2.3%    |
| AMD Starship/Matisse HD Audio Controller                                          | 12        | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 12        | 2.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                            | 11        | 2.11%   |
| Intel 200 Series PCH HD Audio                                                     | 11        | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11        | 2.11%   |
| Intel Haswell-ULT HD Audio Controller                                             | 10        | 1.92%   |
| Intel 8 Series HD Audio Controller                                                | 10        | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 10        | 1.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10        | 1.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 9         | 1.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 9         | 1.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8         | 1.54%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 8         | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7         | 1.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 7         | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 7         | 1.34%   |
| Intel Broadwell-U Audio Controller                                                | 7         | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 7         | 1.34%   |
| AMD FCH Azalia Controller                                                         | 7         | 1.34%   |
| Nvidia GP106 High Definition Audio Controller                                     | 6         | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6         | 1.15%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 6         | 1.15%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5         | 0.96%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5         | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 0.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 0.77%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4         | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4         | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 4         | 0.77%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 43        | 20%     |
| Samsung Electronics | 38        | 17.67%  |
| Kingston            | 23        | 10.7%   |
| Crucial             | 23        | 10.7%   |
| Micron Technology   | 22        | 10.23%  |
| Unknown             | 16        | 7.44%   |
| G.Skill             | 13        | 6.05%   |
| Corsair             | 6         | 2.79%   |
| Ramaxel Technology  | 5         | 2.33%   |
| Elpida              | 5         | 2.33%   |
| Nanya Technology    | 4         | 1.86%   |
| Team                | 3         | 1.4%    |
| Patriot             | 3         | 1.4%    |
| A-DATA Technology   | 3         | 1.4%    |
| TakeMS              | 2         | 0.93%   |
| Transcend           | 1         | 0.47%   |
| Swissbit            | 1         | 0.47%   |
| Silicon Power       | 1         | 0.47%   |
| Qimonda             | 1         | 0.47%   |
| GOODRAM             | 1         | 0.47%   |
| ChangXin Memory     | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                        | 3         | 1.27%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.27%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.27%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 1.27%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.27%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s           | 2         | 0.85%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s             | 2         | 0.85%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 2         | 0.85%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 2         | 0.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 0.85%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 2         | 0.85%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s  | 2         | 0.85%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.85%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s    | 2         | 0.85%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1867MT/s       | 2         | 0.85%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4096MB SODIMM DDR3 1334MT/s   | 2         | 0.85%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 2         | 0.85%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s    | 2         | 0.85%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 2         | 0.85%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 2         | 0.85%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s | 2         | 0.85%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 1         | 0.42%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                 | 1         | 0.42%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.42%   |
| Unknown RAM Module 512MB SODIMM DDR2                      | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s               | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.42%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DRAM                     | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 1         | 0.42%   |
| Unknown RAM Module 2048MB Chip DDR3 1066MT/s              | 1         | 0.42%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 1         | 0.42%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 1         | 0.42%   |
| Transcend RAM JM800QLU-2G 2048MB DIMM DDR 2048MT/s        | 1         | 0.42%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s        | 1         | 0.42%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s        | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 93        | 50.27%  |
| DDR3    | 56        | 30.27%  |
| DDR2    | 17        | 9.19%   |
| SDRAM   | 8         | 4.32%   |
| LPDDR3  | 4         | 2.16%   |
| LPDDR4  | 3         | 1.62%   |
| Unknown | 2         | 1.08%   |
| DRAM    | 1         | 0.54%   |
| DDR     | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 54.35%  |
| DIMM         | 72        | 39.13%  |
| Row Of Chips | 9         | 4.89%   |
| Chip         | 2         | 1.09%   |
| FB-DIMM      | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 68        | 35.98%  |
| 4096  | 48        | 25.4%   |
| 16384 | 33        | 17.46%  |
| 2048  | 25        | 13.23%  |
| 1024  | 8         | 4.23%   |
| 32768 | 5         | 2.65%   |
| 512   | 2         | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 35        | 17.07%  |
| 2667    | 29        | 14.15%  |
| 3200    | 24        | 11.71%  |
| 2400    | 17        | 8.29%   |
| 2133    | 12        | 5.85%   |
| 1333    | 11        | 5.37%   |
| 1334    | 9         | 4.39%   |
| 667     | 9         | 4.39%   |
| 3600    | 6         | 2.93%   |
| 1867    | 5         | 2.44%   |
| 800     | 5         | 2.44%   |
| Unknown | 5         | 2.44%   |
| 3733    | 4         | 1.95%   |
| 2048    | 4         | 1.95%   |
| 1067    | 3         | 1.46%   |
| 4267    | 2         | 0.98%   |
| 4199    | 2         | 0.98%   |
| 3800    | 2         | 0.98%   |
| 3000    | 2         | 0.98%   |
| 2800    | 2         | 0.98%   |
| 1800    | 2         | 0.98%   |
| 49926   | 1         | 0.49%   |
| 8400    | 1         | 0.49%   |
| 4133    | 1         | 0.49%   |
| 3866    | 1         | 0.49%   |
| 3534    | 1         | 0.49%   |
| 3466    | 1         | 0.49%   |
| 3333    | 1         | 0.49%   |
| 3266    | 1         | 0.49%   |
| 2933    | 1         | 0.49%   |
| 2866    | 1         | 0.49%   |
| 1866    | 1         | 0.49%   |
| 1639    | 1         | 0.49%   |
| 1066    | 1         | 0.49%   |
| 975     | 1         | 0.49%   |
| 533     | 1         | 0.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 33.33%  |
| Xerox               | 2         | 16.67%  |
| Canon               | 2         | 16.67%  |
| Seiko Epson         | 1         | 8.33%   |
| Samsung Electronics | 1         | 8.33%   |
| Datamax-O'Neil      | 1         | 8.33%   |
| Brother Industries  | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Xerox Phaser 3140 and 3155         | 1         | 8.33%   |
| Xerox Phaser 3010                  | 1         | 8.33%   |
| Seiko Epson ET-2720 Series         | 1         | 8.33%   |
| Samsung M2070 Series               | 1         | 8.33%   |
| HP DeskJet F4200 series            | 1         | 8.33%   |
| HP DeskJet 4530 series             | 1         | 8.33%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 8.33%   |
| HP Color LaserJet 2605dn           | 1         | 8.33%   |
| Datamax-O'Neil Datamax E-4304      | 1         | 8.33%   |
| Canon PIXMA MX390 Series           | 1         | 8.33%   |
| Canon PIXMA MP250                  | 1         | 8.33%   |
| Brother DCP-L2530DW series         | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 4         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 25%     |
| Canon CanoScan LiDE 700F           | 1         | 25%     |
| Canon CanoScan LiDE 220            | 1         | 25%     |
| Canon CanoScan 4200F               | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 50        | 28.9%   |
| IMC Networks                           | 20        | 11.56%  |
| Sunplus Innovation Technology          | 11        | 6.36%   |
| Realtek Semiconductor                  | 11        | 6.36%   |
| Quanta                                 | 11        | 6.36%   |
| Microdia                               | 10        | 5.78%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.2%    |
| Acer                                   | 9         | 5.2%    |
| Logitech                               | 8         | 4.62%   |
| Lite-On Technology                     | 6         | 3.47%   |
| Apple                                  | 4         | 2.31%   |
| Suyin                                  | 3         | 1.73%   |
| Primax Electronics                     | 3         | 1.73%   |
| Lenovo                                 | 3         | 1.73%   |
| Syntek                                 | 2         | 1.16%   |
| Samsung Electronics                    | 2         | 1.16%   |
| Generalplus Technology                 | 2         | 1.16%   |
| Z-Star Microelectronics                | 1         | 0.58%   |
| Unknown (3730304231443631474643)       | 1         | 0.58%   |
| Sony                                   | 1         | 0.58%   |
| Silicon Motion                         | 1         | 0.58%   |
| Ricoh                                  | 1         | 0.58%   |
| Pixart Imaging                         | 1         | 0.58%   |
| MacroSilicon                           | 1         | 0.58%   |
| Luxvisions Innotech Limited            | 1         | 0.58%   |
| Cubeternet                             | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                        | 10        | 5.68%   |
| Microdia Integrated_Webcam_HD                                    | 8         | 4.55%   |
| IMC Networks Integrated Camera                                   | 8         | 4.55%   |
| Sunplus HP HD Webcam [Fixed]                                     | 4         | 2.27%   |
| IMC Networks USB2.0 HD UVC WebCam                                | 4         | 2.27%   |
| Acer Integrated Camera                                           | 4         | 2.27%   |
| Quanta HP HD Camera                                              | 3         | 1.7%    |
| Primax HP HD Webcam [Fixed]                                      | 3         | 1.7%    |
| Lite-On HP HD Webcam                                             | 3         | 1.7%    |
| Chicony USB2.0 HD UVC WebCam                                     | 3         | 1.7%    |
| Chicony HP HD Webcam                                             | 3         | 1.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                 | 3         | 1.7%    |
| Syntek Lenovo EasyCamera                                         | 2         | 1.14%   |
| Sunplus HD WebCam                                                | 2         | 1.14%   |
| Samsung Galaxy A5 (MTP)                                          | 2         | 1.14%   |
| Realtek USB Camera                                               | 2         | 1.14%   |
| Realtek Integrated_Webcam_HD                                     | 2         | 1.14%   |
| Realtek Asus laptop camera                                       | 2         | 1.14%   |
| Quanta HP Webcam                                                 | 2         | 1.14%   |
| Quanta HP TrueVision HD Camera                                   | 2         | 1.14%   |
| Logitech Webcam C310                                             | 2         | 1.14%   |
| Lite-On HP HD Camera                                             | 2         | 1.14%   |
| Lenovo Integrated Webcam [R5U877]                                | 2         | 1.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                               | 2         | 1.14%   |
| IMC Networks Integrated Webcam                                   | 2         | 1.14%   |
| Generalplus GENERAL WEBCAM                                       | 2         | 1.14%   |
| Chicony USB2.0 VGA UVC WebCam                                    | 2         | 1.14%   |
| Chicony USB2.0 UVC WebCam                                        | 2         | 1.14%   |
| Chicony Lenovo EasyCamera                                        | 2         | 1.14%   |
| Chicony Integrated Camera [ThinkPad]                             | 2         | 1.14%   |
| Chicony Integrated Camera (1280x720@30)                          | 2         | 1.14%   |
| Chicony HP Wide Vision HD Camera                                 | 2         | 1.14%   |
| Chicony HP Webcam                                                | 2         | 1.14%   |
| Chicony HP TrueVision HD Camera                                  | 2         | 1.14%   |
| Chicony HP HD Camera                                             | 2         | 1.14%   |
| Chicony FJ Camera                                                | 2         | 1.14%   |
| Chicony CNF7042                                                  | 2         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision FHD Camera | 2         | 1.14%   |
| Apple FaceTime HD Camera (Built-in)                              | 2         | 1.14%   |
| Acer Integrated IR Camera                                        | 2         | 1.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 33.96%  |
| Validity Sensors           | 17        | 32.08%  |
| AuthenTec                  | 6         | 11.32%  |
| Shenzhen Goodix Technology | 5         | 9.43%   |
| Upek                       | 4         | 7.55%   |
| Elan Microelectronics      | 2         | 3.77%   |
| STMicroelectronics         | 1         | 1.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 11.32%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 11.32%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 7.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 7.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 5.66%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 5.66%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 5.66%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.77%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.77%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 3.77%   |
| AuthenTec AES2810                                                          | 2         | 3.77%   |
| Unknown                                                                    | 2         | 3.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.89%   |
| Validity Sensors VFS491                                                    | 1         | 1.89%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.89%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.89%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.89%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.89%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.89%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 1.89%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.89%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.89%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.89%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.89%   |
| AuthenTec AES1600                                                          | 1         | 1.89%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 7         | 46.67%  |
| Broadcom         | 4         | 26.67%  |
| O2 Micro         | 2         | 13.33%  |
| Upek             | 1         | 6.67%   |
| SCM Microsystems | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 46.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 13.33%  |
| Broadcom 58200                                                               | 2         | 13.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.67%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 219       | 66.16%  |
| 1     | 85        | 25.68%  |
| 2     | 24        | 7.25%   |
| 3     | 3         | 0.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 37.86%  |
| Graphics card            | 31        | 22.14%  |
| Chipcard                 | 15        | 10.71%  |
| Net/wireless             | 12        | 8.57%   |
| Multimedia controller    | 9         | 6.43%   |
| Bluetooth                | 5         | 3.57%   |
| Communication controller | 4         | 2.86%   |
| Storage                  | 3         | 2.14%   |
| Unassigned class         | 1         | 0.71%   |
| Sound                    | 1         | 0.71%   |
| Network                  | 1         | 0.71%   |
| Net/ethernet             | 1         | 0.71%   |
| Flash memory             | 1         | 0.71%   |
| Dvb card                 | 1         | 0.71%   |
| Card reader              | 1         | 0.71%   |
| Camera                   | 1         | 0.71%   |

