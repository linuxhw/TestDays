Linux in Slovenia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovenia.

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

Total: 215

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Nvidia     | MCP79                       | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| AZW        | EQ                          | [98e574abed](https://linux-hardware.org/?probe=98e574abed) | Jun 07, 2023 |
| Nvidia     | MCP79                       | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| ASRock     | H170M Pro4                  | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| HP         | 2AF7                        | [b459ce46cb](https://linux-hardware.org/?probe=b459ce46cb) | May 27, 2023 |
| ASRock     | B550 Steel Legend           | [35534cbfba](https://linux-hardware.org/?probe=35534cbfba) | Apr 19, 2023 |
| MSI        | B450 GAMING PLUS MAX        | [c279e7b8fe](https://linux-hardware.org/?probe=c279e7b8fe) | Apr 11, 2023 |
| Gigabyte   | M61SME-S2                   | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| ASRock     | Q1900M                      | [dfae44d3f6](https://linux-hardware.org/?probe=dfae44d3f6) | Apr 02, 2023 |
| Gigabyte   | GA-880GM-UD2H               | [f46913bb86](https://linux-hardware.org/?probe=f46913bb86) | Apr 02, 2023 |
| HP         | 1998                        | [d88ffd3db4](https://linux-hardware.org/?probe=d88ffd3db4) | Apr 01, 2023 |
| HP         | 8053                        | [6c887800bb](https://linux-hardware.org/?probe=6c887800bb) | Apr 01, 2023 |
| ASUSTek    | PRIME H610I-PLUS D4         | [7b984afb2c](https://linux-hardware.org/?probe=7b984afb2c) | Mar 29, 2023 |
| ASUSTek    | SABERTOOTH Z77              | [43113791e9](https://linux-hardware.org/?probe=43113791e9) | Mar 23, 2023 |
| HP         | 1589                        | [5c483a16fc](https://linux-hardware.org/?probe=5c483a16fc) | Mar 18, 2023 |
| ASUSTek    | M5A88-M                     | [4b1712febb](https://linux-hardware.org/?probe=4b1712febb) | Mar 15, 2023 |
| MSI        | B450 GAMING PLUS MAX        | [6735fc94ae](https://linux-hardware.org/?probe=6735fc94ae) | Mar 06, 2023 |
| Gigabyte   | EX58-UD5                    | [eaec9511de](https://linux-hardware.org/?probe=eaec9511de) | Feb 27, 2023 |
| Gigabyte   | EX58-UD5                    | [85ed1d43c7](https://linux-hardware.org/?probe=85ed1d43c7) | Feb 26, 2023 |
| ASUSTek    | ROG STRIX Z370-G GAMING     | [84fb689a7e](https://linux-hardware.org/?probe=84fb689a7e) | Feb 06, 2023 |
| ASUSTek    | Z97-PRO                     | [0e241538c1](https://linux-hardware.org/?probe=0e241538c1) | Jan 29, 2023 |
| ASUSTek    | Z170-K                      | [2cf59bd38d](https://linux-hardware.org/?probe=2cf59bd38d) | Jan 26, 2023 |
| Lenovo     | MAHOBAY NOK                 | [6bd02bf2c0](https://linux-hardware.org/?probe=6bd02bf2c0) | Jan 24, 2023 |
| ASUSTek    | ROG STRIX Z370-G GAMING     | [405641895c](https://linux-hardware.org/?probe=405641895c) | Jan 18, 2023 |
| Medion     | MS-7621                     | [67b535d88f](https://linux-hardware.org/?probe=67b535d88f) | Jan 18, 2023 |
| Lenovo     | 31900058 STD or WIN         | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| ASUSTek    | TUF B450-PLUS GAMING        | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| MSI        | Z170-A PRO                  | [3948dcc7ef](https://linux-hardware.org/?probe=3948dcc7ef) | Dec 23, 2022 |
| HP         | 8594                        | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Gigabyte   | B650M GAMING X AX           | [01b7250cea](https://linux-hardware.org/?probe=01b7250cea) | Dec 19, 2022 |
| Gigabyte   | B650M GAMING X AX           | [999cbfe9f7](https://linux-hardware.org/?probe=999cbfe9f7) | Dec 19, 2022 |
| ASUSTek    | SABERTOOTH Z77              | [3892b54ac4](https://linux-hardware.org/?probe=3892b54ac4) | Dec 08, 2022 |
| ASUSTek    | SABERTOOTH Z77              | [eced972f80](https://linux-hardware.org/?probe=eced972f80) | Dec 05, 2022 |
| ASUSTek    | SABERTOOTH Z77              | [d37c93af89](https://linux-hardware.org/?probe=d37c93af89) | Dec 05, 2022 |
| ASRock     | H55M-LE                     | [9d2066a479](https://linux-hardware.org/?probe=9d2066a479) | Dec 03, 2022 |
| HP         | 8591                        | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
| Gigabyte   | H61M-S2V-B3                 | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| Gigabyte   | H81M-S2PV                   | [90661c40a3](https://linux-hardware.org/?probe=90661c40a3) | Oct 12, 2022 |
| ASRock     | H61M-HVS                    | [5348794267](https://linux-hardware.org/?probe=5348794267) | Oct 09, 2022 |
| HP         | 18E4                        | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| ASRock     | H61M-HVS                    | [660419ed49](https://linux-hardware.org/?probe=660419ed49) | Sep 27, 2022 |
| MSI        | X570-A PRO                  | [0306edc8ba](https://linux-hardware.org/?probe=0306edc8ba) | Sep 22, 2022 |
| MSI        | X570-A PRO                  | [56d6df17b5](https://linux-hardware.org/?probe=56d6df17b5) | Sep 22, 2022 |
| ASUSTek    | PRIME B550M-K               | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| Gigabyte   | B450M DS3H-CF               | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| ASUSTek    | TUF Gaming B550M-E          | [600ef31484](https://linux-hardware.org/?probe=600ef31484) | Sep 15, 2022 |
| MSI        | MPG B550 GAMING EDGE WIF... | [4c7f501c2b](https://linux-hardware.org/?probe=4c7f501c2b) | Sep 02, 2022 |
| HP         | 8053                        | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| ASRock     | B450 Gaming-ITX/ac          | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| ASRock     | H110M-DVS R2.0              | [adae304d62](https://linux-hardware.org/?probe=adae304d62) | Aug 24, 2022 |
| Supermicro | X7SBi-LN4                   | [ec37ffcc15](https://linux-hardware.org/?probe=ec37ffcc15) | Aug 23, 2022 |
| ASUSTek    | PRIME B450M-A               | [230d7247c0](https://linux-hardware.org/?probe=230d7247c0) | Aug 11, 2022 |
| MSI        | B450 TOMAHAWK MAX           | [17954b8ac5](https://linux-hardware.org/?probe=17954b8ac5) | Jul 26, 2022 |
| ASUSTek    | PRIME X470-PRO              | [0e195b05bf](https://linux-hardware.org/?probe=0e195b05bf) | Jul 13, 2022 |
| ASUSTek    | CROSSHAIR V FORMULA-Z       | [d59692d648](https://linux-hardware.org/?probe=d59692d648) | Jun 29, 2022 |
| ASRock     | H61M-ITX                    | [4afafc5b76](https://linux-hardware.org/?probe=4afafc5b76) | Jun 29, 2022 |
| HP         | 212B                        | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| ASRock     | X570M Pro4                  | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [cc2e6a1605](https://linux-hardware.org/?probe=cc2e6a1605) | Jun 17, 2022 |
| ASRock     | X570M Pro4                  | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| Intel      | CM-iAM/SBC-FITPC2i          | [cbfe433386](https://linux-hardware.org/?probe=cbfe433386) | May 20, 2022 |
| ASUSTek    | ROG STRIX Z370-F GAMING     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| Gigabyte   | GA-MA770T-UD3               | [934d403a31](https://linux-hardware.org/?probe=934d403a31) | May 04, 2022 |
| ASUSTek    | ROG STRIX Z370-F GAMING     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [f727388ac8](https://linux-hardware.org/?probe=f727388ac8) | Apr 17, 2022 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [c1102c77ec](https://linux-hardware.org/?probe=c1102c77ec) | Apr 17, 2022 |
| ASUSTek    | STRIX Z270G GAMING          | [76a5225b83](https://linux-hardware.org/?probe=76a5225b83) | Apr 16, 2022 |
| ASRock     | H170M Pro4                  | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| ASUSTek    | TUF Gaming B560-PLUS WIF... | [222189213d](https://linux-hardware.org/?probe=222189213d) | Apr 11, 2022 |
| MSI        | X570-A PRO                  | [0813d4bc9e](https://linux-hardware.org/?probe=0813d4bc9e) | Mar 31, 2022 |
| MSI        | X570-A PRO                  | [defac75126](https://linux-hardware.org/?probe=defac75126) | Mar 31, 2022 |
| ASUSTek    | PRIME B250M-A               | [1260b540e7](https://linux-hardware.org/?probe=1260b540e7) | Mar 27, 2022 |
| ASUSTek    | PRIME A320M-K               | [9d5d5c0ffb](https://linux-hardware.org/?probe=9d5d5c0ffb) | Feb 26, 2022 |
| ASUSTek    | ROG STRIX B450-F GAMING ... | [1c8a37fb2f](https://linux-hardware.org/?probe=1c8a37fb2f) | Feb 24, 2022 |
| Dell       | 09M8Y8 A02                  | [202fc1f0b9](https://linux-hardware.org/?probe=202fc1f0b9) | Feb 22, 2022 |
| ASUSTek    | PRIME H410M-A               | [cad9a70c49](https://linux-hardware.org/?probe=cad9a70c49) | Feb 16, 2022 |
| ASUSTek    | PRIME H410M-A               | [676d121bda](https://linux-hardware.org/?probe=676d121bda) | Feb 13, 2022 |
| Gigabyte   | EP45-UD3LR                  | [239eb94a17](https://linux-hardware.org/?probe=239eb94a17) | Feb 07, 2022 |
| Gigabyte   | Z170-HD3P-CF                | [901d568e70](https://linux-hardware.org/?probe=901d568e70) | Jan 31, 2022 |
| Gigabyte   | Z170-HD3P-CF                | [621d099786](https://linux-hardware.org/?probe=621d099786) | Jan 31, 2022 |
| HP         | 1589                        | [41dbcb78cb](https://linux-hardware.org/?probe=41dbcb78cb) | Jan 30, 2022 |
| Pegatron   | EVE                         | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron   | EVE                         | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| ASRock     | B85M-HDS                    | [77cb3218a8](https://linux-hardware.org/?probe=77cb3218a8) | Jan 12, 2022 |
| Lenovo     | ThinkCentre M57e 9439WHV    | [a9b2163945](https://linux-hardware.org/?probe=a9b2163945) | Dec 25, 2021 |
| Gigabyte   | H57M-USB3                   | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| ASUSTek    | ROG STRIX Z370-F GAMING     | [6aee0ff442](https://linux-hardware.org/?probe=6aee0ff442) | Dec 15, 2021 |
| ASUSTek    | TUF B450-PLUS GAMING        | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek    | TUF B450-PLUS GAMING        | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASUSTek    | M4A78T-E                    | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek    | ROG STRIX X570-F GAMING     | [6016236fad](https://linux-hardware.org/?probe=6016236fad) | Nov 24, 2021 |
| Gigabyte   | H57M-USB3                   | [97409a8d1c](https://linux-hardware.org/?probe=97409a8d1c) | Nov 22, 2021 |
| Gigabyte   | H57M-USB3                   | [e0e4ee802a](https://linux-hardware.org/?probe=e0e4ee802a) | Nov 22, 2021 |
| Gigabyte   | H61M-S2PV                   | [163092e4b9](https://linux-hardware.org/?probe=163092e4b9) | Nov 18, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Fujitsu    | D3417-B2 S26361-D3417-B2    | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| ASUSTek    | PRIME Z270-A                | [a11d4b7c50](https://linux-hardware.org/?probe=a11d4b7c50) | Oct 20, 2021 |
| ASRock     | X300M-STX                   | [cd738f5036](https://linux-hardware.org/?probe=cd738f5036) | Oct 11, 2021 |
| ASRock     | X300M-STX                   | [bc1fd03a63](https://linux-hardware.org/?probe=bc1fd03a63) | Oct 10, 2021 |
| ASRock     | X300M-STX                   | [6ec6ce5c81](https://linux-hardware.org/?probe=6ec6ce5c81) | Oct 10, 2021 |
| MSI        | X570-A PRO                  | [9813ead17b](https://linux-hardware.org/?probe=9813ead17b) | Sep 23, 2021 |
| Medion     | Akoya E7226                 | [9367472acb](https://linux-hardware.org/?probe=9367472acb) | Sep 18, 2021 |
| MSI        | X570-A PRO                  | [934d0576e0](https://linux-hardware.org/?probe=934d0576e0) | Aug 27, 2021 |
| ASRock     | H310CM-HDV                  | [0fccd48745](https://linux-hardware.org/?probe=0fccd48745) | Aug 13, 2021 |
| MSI        | X570-A PRO                  | [8cc7d05010](https://linux-hardware.org/?probe=8cc7d05010) | Aug 12, 2021 |
| ASUSTek    | PRIME A320M-K               | [e6e223209a](https://linux-hardware.org/?probe=e6e223209a) | Jul 20, 2021 |
| MSI        | H61M-P31                    | [ccd9d80d59](https://linux-hardware.org/?probe=ccd9d80d59) | Jul 18, 2021 |
| Pegatron   | 2A73                        | [2bff425af7](https://linux-hardware.org/?probe=2bff425af7) | Jul 14, 2021 |
| Pegatron   | 2A73                        | [44ea7169ef](https://linux-hardware.org/?probe=44ea7169ef) | Jul 14, 2021 |
| MSI        | B450 TOMAHAWK MAX II        | [bc18a23953](https://linux-hardware.org/?probe=bc18a23953) | Jun 28, 2021 |
| ASUSTek    | ROG STRIX Z370-G GAMING     | [181bd83bdd](https://linux-hardware.org/?probe=181bd83bdd) | Jun 02, 2021 |
| Gigabyte   | F2A88XM-D3HP                | [02bf919368](https://linux-hardware.org/?probe=02bf919368) | Jun 02, 2021 |
| Lenovo     | ThinkStation S20 4157ZSK    | [3e6d98fe9c](https://linux-hardware.org/?probe=3e6d98fe9c) | Apr 27, 2021 |
| ASRock     | B560 Pro4                   | [ddd384c6cb](https://linux-hardware.org/?probe=ddd384c6cb) | Apr 26, 2021 |
| Lenovo     | ThinkCentre M55e 9389WEG    | [66c2003859](https://linux-hardware.org/?probe=66c2003859) | Apr 20, 2021 |
| HP         | 1905                        | [e0fc243f47](https://linux-hardware.org/?probe=e0fc243f47) | Apr 19, 2021 |
| ASUSTek    | ROG STRIX Z370-G GAMING     | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| ASUSTek    | ROG STRIX Z370-G GAMING     | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| ASUSTek    | P5Q SE                      | [325f4ca461](https://linux-hardware.org/?probe=325f4ca461) | Apr 05, 2021 |
| ASUSTek    | P5Q SE                      | [1c3958d998](https://linux-hardware.org/?probe=1c3958d998) | Apr 05, 2021 |
| ASUSTek    | ROG STRIX Z370-G GAMING     | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| Lenovo     | ThinkStation S20 4157ZSK    | [1038d58fea](https://linux-hardware.org/?probe=1038d58fea) | Mar 25, 2021 |
| Lenovo     | ThinkStation S20 4157ZSK    | [8b28b318fd](https://linux-hardware.org/?probe=8b28b318fd) | Mar 19, 2021 |
| Gigabyte   | H61M-D2-B3                  | [453120855b](https://linux-hardware.org/?probe=453120855b) | Mar 18, 2021 |
| Apple      | Mac-F4208DA9 PVT            | [4ab255096c](https://linux-hardware.org/?probe=4ab255096c) | Feb 28, 2021 |
| Dell       | 0C27VV A02                  | [49cd056ca4](https://linux-hardware.org/?probe=49cd056ca4) | Feb 24, 2021 |
| Gigabyte   | P35C-DS3R                   | [bd76fdbde8](https://linux-hardware.org/?probe=bd76fdbde8) | Feb 20, 2021 |
| ASUSTek    | PRIME B350-PLUS             | [153bb12a6a](https://linux-hardware.org/?probe=153bb12a6a) | Feb 19, 2021 |
| MSI        | H61M-P31                    | [a0192f9d6e](https://linux-hardware.org/?probe=a0192f9d6e) | Feb 17, 2021 |
| ASUSTek    | SABERTOOTH 990FX R2.0       | [106c66da60](https://linux-hardware.org/?probe=106c66da60) | Feb 14, 2021 |
| Lenovo     | ThinkCentre M90p 5498PK8    | [df39a8847b](https://linux-hardware.org/?probe=df39a8847b) | Feb 14, 2021 |
| ASUSTek    | P7H55-M SI                  | [e40fe3768d](https://linux-hardware.org/?probe=e40fe3768d) | Feb 09, 2021 |
| Gigabyte   | P35C-DS3R                   | [a31754db23](https://linux-hardware.org/?probe=a31754db23) | Feb 08, 2021 |
| Pegatron   | 2A73                        | [4c2042c088](https://linux-hardware.org/?probe=4c2042c088) | Jan 18, 2021 |
| Pegatron   | 2A73                        | [c6cf8a7efe](https://linux-hardware.org/?probe=c6cf8a7efe) | Jan 18, 2021 |
| MSI        | H55M-P31                    | [3313a8aba5](https://linux-hardware.org/?probe=3313a8aba5) | Jan 12, 2021 |
| ASUSTek    | PRIME B350-PLUS             | [0265add193](https://linux-hardware.org/?probe=0265add193) | Jan 10, 2021 |
| Gigabyte   | B450M DS3H-CF               | [8b0a9a71b3](https://linux-hardware.org/?probe=8b0a9a71b3) | Jan 10, 2021 |
| ASUSTek    | PRIME B350-PLUS             | [497bf4005e](https://linux-hardware.org/?probe=497bf4005e) | Jan 10, 2021 |
| Gigabyte   | H61M-D2-B3                  | [60d8b9344b](https://linux-hardware.org/?probe=60d8b9344b) | Jan 09, 2021 |
| ASUSTek    | TUF Z370-PLUS GAMING        | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| Gigabyte   | H270-HD3-CF                 | [b6c93666ee](https://linux-hardware.org/?probe=b6c93666ee) | Dec 29, 2020 |
| Gigabyte   | H270-HD3-CF                 | [7905034ba5](https://linux-hardware.org/?probe=7905034ba5) | Dec 29, 2020 |
| Gigabyte   | H270-HD3-CF                 | [71370e1dd8](https://linux-hardware.org/?probe=71370e1dd8) | Dec 19, 2020 |
| Gigabyte   | B450M GAMING                | [def1b6fff4](https://linux-hardware.org/?probe=def1b6fff4) | Dec 13, 2020 |
| Pegatron   | EVE                         | [08ced52205](https://linux-hardware.org/?probe=08ced52205) | Nov 29, 2020 |
| ASRock     | H110M-HDV R3.0              | [c3df499de1](https://linux-hardware.org/?probe=c3df499de1) | Nov 12, 2020 |
| ASRock     | H110M-HDV R3.0              | [e05c144d2f](https://linux-hardware.org/?probe=e05c144d2f) | Nov 12, 2020 |
| Lenovo     | ThinkCentre M55e 9389WEG    | [2462c80a14](https://linux-hardware.org/?probe=2462c80a14) | Nov 10, 2020 |
| ASUSTek    | Z97-K                       | [e8f7b6ef7e](https://linux-hardware.org/?probe=e8f7b6ef7e) | Nov 07, 2020 |
| ASUSTek    | Z97-K                       | [7e9d52855a](https://linux-hardware.org/?probe=7e9d52855a) | Nov 07, 2020 |
| MSI        | B450 TOMAHAWK               | [1e6ba50614](https://linux-hardware.org/?probe=1e6ba50614) | Nov 04, 2020 |
| Intel      | DH87RL AAG74240-403         | [caa0e9c93b](https://linux-hardware.org/?probe=caa0e9c93b) | Nov 02, 2020 |
| Gigabyte   | H270-HD3-CF                 | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| MSI        | B360M PRO-VDH               | [d336eeaa8d](https://linux-hardware.org/?probe=d336eeaa8d) | Oct 21, 2020 |
| Lenovo     | 3098 NOK                    | [2c592ebb94](https://linux-hardware.org/?probe=2c592ebb94) | Oct 19, 2020 |
| Lenovo     | 3098 NOK                    | [92a22bd753](https://linux-hardware.org/?probe=92a22bd753) | Oct 19, 2020 |
| Gigabyte   | Z68P-DS3                    | [2e8b092dbc](https://linux-hardware.org/?probe=2e8b092dbc) | Oct 12, 2020 |
| Gigabyte   | Z97X-Gaming 3               | [da4740881e](https://linux-hardware.org/?probe=da4740881e) | Oct 04, 2020 |
| Pegatron   | 2A94h                       | [3a1ede6188](https://linux-hardware.org/?probe=3a1ede6188) | Oct 03, 2020 |
| Gigabyte   | F2A88XM-D3HP                | [1d3401ff46](https://linux-hardware.org/?probe=1d3401ff46) | Oct 02, 2020 |
| Intel      | DQ35JO AAD82085-801         | [51c42a0f25](https://linux-hardware.org/?probe=51c42a0f25) | Sep 17, 2020 |
| Pegatron   | 2A73                        | [a4607af679](https://linux-hardware.org/?probe=a4607af679) | Aug 25, 2020 |
| Pegatron   | 2A73                        | [f2c225880d](https://linux-hardware.org/?probe=f2c225880d) | Aug 25, 2020 |
| HP         | 3048h                       | [0bc2b9bafc](https://linux-hardware.org/?probe=0bc2b9bafc) | Aug 17, 2020 |
| ASUSTek    | P7H55-M SI                  | [c323481902](https://linux-hardware.org/?probe=c323481902) | Jun 14, 2020 |
| ASUSTek    | P7H55-M SI                  | [6889f53e3b](https://linux-hardware.org/?probe=6889f53e3b) | Jun 13, 2020 |
| ASRock     | X570 Extreme4               | [add6daf97a](https://linux-hardware.org/?probe=add6daf97a) | Jun 07, 2020 |
| ASUSTek    | PRIME H370-PLUS             | [d7dee77bfc](https://linux-hardware.org/?probe=d7dee77bfc) | Jun 04, 2020 |
| Gigabyte   | B85M-HD3                    | [03b36ff9c1](https://linux-hardware.org/?probe=03b36ff9c1) | May 28, 2020 |
| ASRock     | Z390 Pro4                   | [e1c0c74ca6](https://linux-hardware.org/?probe=e1c0c74ca6) | May 25, 2020 |
| MSI        | H61M-P31                    | [870b2534d7](https://linux-hardware.org/?probe=870b2534d7) | May 22, 2020 |
| MSI        | H110M ECO                   | [fe6009a465](https://linux-hardware.org/?probe=fe6009a465) | May 15, 2020 |
| Lenovo     | ThinkCentre M55e 9389W11    | [f148017266](https://linux-hardware.org/?probe=f148017266) | Apr 12, 2020 |
| ASUSTek    | H170 PRO GAMING             | [f9c3afb706](https://linux-hardware.org/?probe=f9c3afb706) | Apr 08, 2020 |
| Gigabyte   | B360M DS3H                  | [17dd7e6ddb](https://linux-hardware.org/?probe=17dd7e6ddb) | Apr 05, 2020 |
| Lenovo     | ThinkCentre M57e 9356W2K    | [663d112138](https://linux-hardware.org/?probe=663d112138) | Apr 02, 2020 |
| HP         | 0A58h                       | [0734e4224d](https://linux-hardware.org/?probe=0734e4224d) | Mar 16, 2020 |
| ASUSTek    | H110M-A                     | [9a43e8f82a](https://linux-hardware.org/?probe=9a43e8f82a) | Feb 26, 2020 |
| ASUSTek    | H110M-A                     | [0722f7ccf8](https://linux-hardware.org/?probe=0722f7ccf8) | Feb 22, 2020 |
| ASUSTek    | P8Z77-M PRO                 | [44e0ce8fc8](https://linux-hardware.org/?probe=44e0ce8fc8) | Jan 24, 2020 |
| Medion     | MS-7707                     | [3feacd8f08](https://linux-hardware.org/?probe=3feacd8f08) | Jan 19, 2020 |
| Medion     | MS-7707                     | [5d5096c9a8](https://linux-hardware.org/?probe=5d5096c9a8) | Jan 18, 2020 |
| Biostar    | TH55B HD                    | [3f28da0706](https://linux-hardware.org/?probe=3f28da0706) | Jan 17, 2020 |
| Biostar    | TH55B HD                    | [980b5da590](https://linux-hardware.org/?probe=980b5da590) | Jan 02, 2020 |
| Biostar    | TH55B HD                    | [e13730f188](https://linux-hardware.org/?probe=e13730f188) | Dec 25, 2019 |
| HP         | 1495                        | [d56240bfb5](https://linux-hardware.org/?probe=d56240bfb5) | Dec 07, 2019 |
| Gigabyte   | F2A88XM-D3HP                | [de68096cdc](https://linux-hardware.org/?probe=de68096cdc) | Nov 27, 2019 |
| ASRock     | H61M-DGS R2.0               | [7ad66ff018](https://linux-hardware.org/?probe=7ad66ff018) | Nov 23, 2019 |
| ASRock     | H61M-DGS R2.0               | [837d7c2621](https://linux-hardware.org/?probe=837d7c2621) | Nov 23, 2019 |
| HP         | 1495                        | [7517e7c74d](https://linux-hardware.org/?probe=7517e7c74d) | Nov 20, 2019 |
| HP         | 1495                        | [b4598c0e73](https://linux-hardware.org/?probe=b4598c0e73) | Nov 19, 2019 |
| HP         | 1495                        | [ab3f7ddb42](https://linux-hardware.org/?probe=ab3f7ddb42) | Nov 05, 2019 |
| HP         | 1495                        | [75e4e80f87](https://linux-hardware.org/?probe=75e4e80f87) | Oct 04, 2019 |
| HP         | 1495                        | [470c7daaaa](https://linux-hardware.org/?probe=470c7daaaa) | Sep 20, 2019 |
| HP         | 1495                        | [4f34ee60db](https://linux-hardware.org/?probe=4f34ee60db) | Sep 17, 2019 |
| Medion     | MS-7707                     | [9b50675efd](https://linux-hardware.org/?probe=9b50675efd) | Aug 03, 2019 |
| ASUSTek    | PRIME X470-PRO              | [4a2455eae6](https://linux-hardware.org/?probe=4a2455eae6) | Jul 28, 2019 |
| ASUSTek    | PRIME X470-PRO              | [8d117b8f35](https://linux-hardware.org/?probe=8d117b8f35) | Jul 28, 2019 |
| Gigabyte   | F2A88XM-D3HP                | [ab7980dba3](https://linux-hardware.org/?probe=ab7980dba3) | Jul 01, 2019 |
| Medion     | MS-7707                     | [b843e52e30](https://linux-hardware.org/?probe=b843e52e30) | Jun 03, 2019 |
| Lenovo     | ThinkCentre M57 6072VAM     | [c399cbb5f3](https://linux-hardware.org/?probe=c399cbb5f3) | May 04, 2019 |
| ASUSTek    | PRIME X370-PRO              | [8ad90844e8](https://linux-hardware.org/?probe=8ad90844e8) | Apr 16, 2019 |
| Medion     | MS-7707                     | [71684dcee4](https://linux-hardware.org/?probe=71684dcee4) | Apr 12, 2019 |
| HP         | 0A68h                       | [fa9c3d044f](https://linux-hardware.org/?probe=fa9c3d044f) | Mar 13, 2019 |
| Intel      | DQ67SW AAG12527-310         | [d304d79466](https://linux-hardware.org/?probe=d304d79466) | Mar 10, 2019 |
| ASUSTek    | PRIME X470-PRO              | [8348d3c21e](https://linux-hardware.org/?probe=8348d3c21e) | Feb 23, 2019 |
| HP         | 82A2                        | [0f9aa13b55](https://linux-hardware.org/?probe=0f9aa13b55) | Feb 21, 2019 |
| ASUSTek    | PRIME X470-PRO              | [0407ee67e9](https://linux-hardware.org/?probe=0407ee67e9) | Feb 11, 2019 |
| HP         | 0A68h                       | [7b0d921779](https://linux-hardware.org/?probe=7b0d921779) | Dec 15, 2018 |
| HP         | 0A68h                       | [b773c3a27d](https://linux-hardware.org/?probe=b773c3a27d) | Dec 15, 2018 |
| HP         | 0A68h                       | [11bcd6f218](https://linux-hardware.org/?probe=11bcd6f218) | Dec 15, 2018 |
| Gigabyte   | 970A-UD3P                   | [d48dca3ee3](https://linux-hardware.org/?probe=d48dca3ee3) | Feb 18, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 27       | 17.88%  |
| Ubuntu 22.04                 | 9        | 5.96%   |
| Ubuntu 18.04                 | 9        | 5.96%   |
| OpenMandriva 4.3             | 8        | 5.3%    |
| Zorin 16                     | 6        | 3.97%   |
| OpenMandriva 23.03           | 4        | 2.65%   |
| Kubuntu 22.04                | 4        | 2.65%   |
| KDE neon 20.04               | 4        | 2.65%   |
| Xubuntu 20.04                | 3        | 1.99%   |
| Ubuntu 19.10                 | 3        | 1.99%   |
| Pop!_OS 20.04                | 3        | 1.99%   |
| Linux Mint 19.3              | 3        | 1.99%   |
| ArcoLinux Rolling            | 3        | 1.99%   |
| Ubuntu 20.10                 | 2        | 1.32%   |
| Ubuntu 18.10                 | 2        | 1.32%   |
| Pop!_OS 21.10                | 2        | 1.32%   |
| OpenMandriva 4.2             | 2        | 1.32%   |
| Kubuntu 20.04                | 2        | 1.32%   |
| KDE neon 22.04               | 2        | 1.32%   |
| Fedora 37                    | 2        | 1.32%   |
| Fedora 35                    | 2        | 1.32%   |
| EndeavourOS Rolling          | 2        | 1.32%   |
| Debian 11                    | 2        | 1.32%   |
| Arch Rolling                 | 2        | 1.32%   |
| Zorin 15                     | 1        | 0.66%   |
| Xubuntu 22.04                | 1        | 0.66%   |
| Xubuntu 21.10                | 1        | 0.66%   |
| Ubuntu Unity 18.04           | 1        | 0.66%   |
| Ubuntu Unity 16.04           | 1        | 0.66%   |
| Ubuntu MATE 23.04            | 1        | 0.66%   |
| Ubuntu MATE 18.04            | 1        | 0.66%   |
| Ubuntu Kylin 20.04           | 1        | 0.66%   |
| Ubuntu Budgie 22.04          | 1        | 0.66%   |
| Ubuntu 21.10                 | 1        | 0.66%   |
| ROSA R8                      | 1        | 0.66%   |
| RHEL 8                       | 1        | 0.66%   |
| Pop!_OS 22.04                | 1        | 0.66%   |
| openSUSE Tumbleweed-XXXXXXXX | 1        | 0.66%   |
| OpenMandriva 4.50            | 1        | 0.66%   |
| OpenMandriva 23.01           | 1        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 52       | 36.11%  |
| OpenMandriva  | 14       | 9.72%   |
| Linux Mint    | 7        | 4.86%   |
| Kubuntu       | 7        | 4.86%   |
| Zorin         | 6        | 4.17%   |
| Pop!_OS       | 6        | 4.17%   |
| Manjaro       | 6        | 4.17%   |
| KDE neon      | 6        | 4.17%   |
| Xubuntu       | 5        | 3.47%   |
| Fedora        | 4        | 2.78%   |
| Gentoo        | 3        | 2.08%   |
| EndeavourOS   | 3        | 2.08%   |
| ArcoLinux     | 3        | 2.08%   |
| Arch          | 3        | 2.08%   |
| Ubuntu Unity  | 2        | 1.39%   |
| Ubuntu MATE   | 2        | 1.39%   |
| Endless       | 2        | 1.39%   |
| Debian        | 2        | 1.39%   |
| Ubuntu Kylin  | 1        | 0.69%   |
| Ubuntu Budgie | 1        | 0.69%   |
| ROSA          | 1        | 0.69%   |
| RHEL          | 1        | 0.69%   |
| openSUSE      | 1        | 0.69%   |
| Mageia        | 1        | 0.69%   |
| Lubuntu       | 1        | 0.69%   |
| Elementary    | 1        | 0.69%   |
| CentOS        | 1        | 0.69%   |
| BlackPanther  | 1        | 0.69%   |
| Artix         | 1        | 0.69%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 8        | 4.73%   |
| 5.4.0-48-generic         | 5        | 2.96%   |
| 6.2.6-desktop-1omv2390   | 3        | 1.78%   |
| 5.8.0-43-generic         | 3        | 1.78%   |
| 5.4.0-31-generic         | 3        | 1.78%   |
| 5.15.0-56-generic        | 3        | 1.78%   |
| 5.15.0-25-generic        | 3        | 1.78%   |
| 5.8.0-36-generic         | 2        | 1.18%   |
| 5.4.0-7642-generic       | 2        | 1.18%   |
| 5.4.0-66-generic         | 2        | 1.18%   |
| 5.4.0-60-generic         | 2        | 1.18%   |
| 5.4.0-52-generic         | 2        | 1.18%   |
| 5.4.0-29-generic         | 2        | 1.18%   |
| 5.4.0-104-generic        | 2        | 1.18%   |
| 5.3.0-40-generic         | 2        | 1.18%   |
| 5.3.0-26-generic         | 2        | 1.18%   |
| 5.3.0-23-generic         | 2        | 1.18%   |
| 5.16.15-76051615-generic | 2        | 1.18%   |
| 5.15.0-58-generic        | 2        | 1.18%   |
| 5.15.0-47-generic        | 2        | 1.18%   |
| 5.15.0-46-generic        | 2        | 1.18%   |
| 5.15.0-43-generic        | 2        | 1.18%   |
| 5.13.0-30-generic        | 2        | 1.18%   |
| 5.13.0-27-generic        | 2        | 1.18%   |
| 5.11.0-40-generic        | 2        | 1.18%   |
| 5.10.14-desktop-1omv4002 | 2        | 1.18%   |
| 4.18.0-17-generic        | 2        | 1.18%   |
| 4.18.0-15-generic        | 2        | 1.18%   |
| 4.15.0-45-generic        | 2        | 1.18%   |
| 6.4.0-060400rc5-generic  | 1        | 0.59%   |
| 6.3.4-zen1-1-zen         | 1        | 0.59%   |
| 6.2.8-arch1-1            | 1        | 0.59%   |
| 6.2.10-cb2.0.fc37.x86_64 | 1        | 0.59%   |
| 6.1.8-artix1-1           | 1        | 0.59%   |
| 6.1.4-artix1-1           | 1        | 0.59%   |
| 6.1.3-x64v1-xanmod1-1    | 1        | 0.59%   |
| 6.1.14-200.fc37.x86_64   | 1        | 0.59%   |
| 6.1.1-desktop-1omv2290   | 1        | 0.59%   |
| 6.0.13-300.fc37.x86_64   | 1        | 0.59%   |
| 6.0.12-arch1-1           | 1        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 31       | 19.5%   |
| 5.15.0  | 19       | 11.95%  |
| 5.8.0   | 11       | 6.92%   |
| 5.16.7  | 9        | 5.66%   |
| 5.13.0  | 8        | 5.03%   |
| 4.18.0  | 8        | 5.03%   |
| 5.3.0   | 7        | 4.4%    |
| 5.11.0  | 6        | 3.77%   |
| 4.15.0  | 6        | 3.77%   |
| 6.2.6   | 3        | 1.89%   |
| 5.10.14 | 3        | 1.89%   |
| 5.19.0  | 2        | 1.26%   |
| 5.16.15 | 2        | 1.26%   |
| 5.10.30 | 2        | 1.26%   |
| 5.0.0   | 2        | 1.26%   |
| 6.4.0   | 1        | 0.63%   |
| 6.3.4   | 1        | 0.63%   |
| 6.2.8   | 1        | 0.63%   |
| 6.2.10  | 1        | 0.63%   |
| 6.1.8   | 1        | 0.63%   |
| 6.1.4   | 1        | 0.63%   |
| 6.1.3   | 1        | 0.63%   |
| 6.1.14  | 1        | 0.63%   |
| 6.1.1   | 1        | 0.63%   |
| 6.0.13  | 1        | 0.63%   |
| 6.0.12  | 1        | 0.63%   |
| 5.9.2   | 1        | 0.63%   |
| 5.9.15  | 1        | 0.63%   |
| 5.7.0   | 1        | 0.63%   |
| 5.6.14  | 1        | 0.63%   |
| 5.6.0   | 1        | 0.63%   |
| 5.4.14  | 1        | 0.63%   |
| 5.19.13 | 1        | 0.63%   |
| 5.18.10 | 1        | 0.63%   |
| 5.17.5  | 1        | 0.63%   |
| 5.16.18 | 1        | 0.63%   |
| 5.16.13 | 1        | 0.63%   |
| 5.15.85 | 1        | 0.63%   |
| 5.15.74 | 1        | 0.63%   |
| 5.15.6  | 1        | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 32       | 20.65%  |
| 5.15    | 24       | 15.48%  |
| 5.16    | 12       | 7.74%   |
| 5.8     | 11       | 7.1%    |
| 5.13    | 9        | 5.81%   |
| 4.18    | 9        | 5.81%   |
| 5.3     | 7        | 4.52%   |
| 5.11    | 7        | 4.52%   |
| 5.10    | 6        | 3.87%   |
| 4.15    | 6        | 3.87%   |
| 6.2     | 5        | 3.23%   |
| 6.1     | 4        | 2.58%   |
| 5.19    | 3        | 1.94%   |
| 5.14    | 3        | 1.94%   |
| 5.12    | 3        | 1.94%   |
| 6.0     | 2        | 1.29%   |
| 5.6     | 2        | 1.29%   |
| 5.0     | 2        | 1.29%   |
| 6.4     | 1        | 0.65%   |
| 6.3     | 1        | 0.65%   |
| 5.9     | 1        | 0.65%   |
| 5.7     | 1        | 0.65%   |
| 5.18    | 1        | 0.65%   |
| 5.17    | 1        | 0.65%   |
| 4.20    | 1        | 0.65%   |
| 4.1     | 1        | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 135      | 97.83%  |
| i686   | 3        | 2.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 61       | 40.94%  |
| KDE5       | 34       | 22.82%  |
| Unknown    | 15       | 10.07%  |
| XFCE       | 13       | 8.72%   |
| KDE        | 6        | 4.03%   |
| X-Cinnamon | 5        | 3.36%   |
| Cinnamon   | 4        | 2.68%   |
| Unity      | 2        | 1.34%   |
| MATE       | 2        | 1.34%   |
| UKUI       | 1        | 0.67%   |
| Pantheon   | 1        | 0.67%   |
| NsCDE      | 1        | 0.67%   |
| LXQt       | 1        | 0.67%   |
| KDE4       | 1        | 0.67%   |
| DWM        | 1        | 0.67%   |
| Budgie     | 1        | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 115      | 81.56%  |
| Wayland | 10       | 7.09%   |
| Unknown | 10       | 7.09%   |
| Tty     | 6        | 4.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 63       | 43.45%  |
| SDDM    | 31       | 21.38%  |
| LightDM | 16       | 11.03%  |
| GDM     | 15       | 10.34%  |
| GDM3    | 13       | 8.97%   |
| TDM     | 5        | 3.45%   |
| XDM     | 1        | 0.69%   |
| KDM     | 1        | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 71       | 49.31%  |
| sl_SI   | 46       | 31.94%  |
| Unknown | 15       | 10.42%  |
| en_GB   | 5        | 3.47%   |
| C       | 3        | 2.08%   |
| de_AT   | 2        | 1.39%   |
| it_IT   | 1        | 0.69%   |
| de_DE   | 1        | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 78       | 54.55%  |
| EFI  | 65       | 45.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 101      | 71.63%  |
| Overlay | 19       | 13.48%  |
| Btrfs   | 8        | 5.67%   |
| Unknown | 6        | 4.26%   |
| Zfs     | 4        | 2.84%   |
| Xfs     | 3        | 2.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 64       | 46.38%  |
| GPT     | 56       | 40.58%  |
| MBR     | 18       | 13.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 76.92%  |
| Yes       | 33       | 23.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 69.29%  |
| Yes       | 43       | 30.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 41       | 29.71%  |
| Gigabyte Technology | 24       | 17.39%  |
| ASRock              | 17       | 12.32%  |
| Hewlett-Packard     | 14       | 10.14%  |
| MSI                 | 13       | 9.42%   |
| Lenovo              | 10       | 7.25%   |
| Pegatron            | 4        | 2.9%    |
| Intel               | 4        | 2.9%    |
| Medion              | 3        | 2.17%   |
| Dell                | 2        | 1.45%   |
| Supermicro          | 1        | 0.72%   |
| Nvidia              | 1        | 0.72%   |
| Fujitsu             | 1        | 0.72%   |
| Biostar             | 1        | 0.72%   |
| AZW                 | 1        | 0.72%   |
| Apple               | 1        | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| MSI MS-7C02                       | 3        | 2.17%   |
| Pegatron FL308AA-ABD IQ512de      | 2        | 1.45%   |
| MSI MS-7C37                       | 2        | 1.45%   |
| MSI MS-7788                       | 2        | 1.45%   |
| Gigabyte F2A88XM-D3HP             | 2        | 1.45%   |
| Gigabyte B450M DS3H               | 2        | 1.45%   |
| ASUS TUF B450-PLUS GAMING         | 2        | 1.45%   |
| ASUS ROG STRIX Z370-F GAMING      | 2        | 1.45%   |
| ASUS ROG STRIX X570-E GAMING      | 2        | 1.45%   |
| ASUS PRIME B350-PLUS              | 2        | 1.45%   |
| ASUS PRIME A320M-K                | 2        | 1.45%   |
| ASUS P7H55-M SI                   | 2        | 1.45%   |
| ASUS All Series                   | 2        | 1.45%   |
| Supermicro X7SBi-LN4              | 1        | 0.72%   |
| Pegatron Pro 3010 Microtower PC   | 1        | 0.72%   |
| Pegatron 2A73                     | 1        | 0.72%   |
| Nvidia MCP79                      | 1        | 0.72%   |
| MSI MS-7C91                       | 1        | 0.72%   |
| MSI MS-7B86                       | 1        | 0.72%   |
| MSI MS-7B24                       | 1        | 0.72%   |
| MSI MS-7994                       | 1        | 0.72%   |
| MSI MS-7971                       | 1        | 0.72%   |
| MSI MS-7636                       | 1        | 0.72%   |
| Medion MS-7707                    | 1        | 0.72%   |
| Medion MS-7621                    | 1        | 0.72%   |
| Medion Akoya E7226                | 1        | 0.72%   |
| Lenovo ThinkStation S20 4157ZSK   | 1        | 0.72%   |
| Lenovo ThinkCentre M92p 32384B0   | 1        | 0.72%   |
| Lenovo ThinkCentre M90p 5498PK8   | 1        | 0.72%   |
| Lenovo ThinkCentre M73 10B4S0NN00 | 1        | 0.72%   |
| Lenovo ThinkCentre M57e 9439WHV   | 1        | 0.72%   |
| Lenovo ThinkCentre M57e 9356W2K   | 1        | 0.72%   |
| Lenovo ThinkCentre M57 6072VAM    | 1        | 0.72%   |
| Lenovo ThinkCentre M55e 9389WEG   | 1        | 0.72%   |
| Lenovo ThinkCentre M55e 9389W11   | 1        | 0.72%   |
| Lenovo H535s 10119                | 1        | 0.72%   |
| Intel DQ67SW AAG12527-310         | 1        | 0.72%   |
| Intel DQ35JO AAD82085-801         | 1        | 0.72%   |
| Intel DH87RL AAG74240-403         | 1        | 0.72%   |
| Intel CM-iAM/SBC-FITPC2i          | 1        | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 13       | 9.42%   |
| Lenovo ThinkCentre    | 8        | 5.8%    |
| ASUS ROG              | 8        | 5.8%    |
| ASUS TUF              | 5        | 3.62%   |
| HP EliteDesk          | 4        | 2.9%    |
| MSI MS-7C02           | 3        | 2.17%   |
| HP Compaq             | 3        | 2.17%   |
| Gigabyte B450M        | 3        | 2.17%   |
| Pegatron FL308AA-ABD  | 2        | 1.45%   |
| MSI MS-7C37           | 2        | 1.45%   |
| MSI MS-7788           | 2        | 1.45%   |
| Gigabyte F2A88XM-D3HP | 2        | 1.45%   |
| ASUS SABERTOOTH       | 2        | 1.45%   |
| ASUS P7H55-M          | 2        | 1.45%   |
| ASUS All              | 2        | 1.45%   |
| Supermicro X7SBi-LN4  | 1        | 0.72%   |
| Pegatron Pro          | 1        | 0.72%   |
| Pegatron 2A73         | 1        | 0.72%   |
| Nvidia MCP79          | 1        | 0.72%   |
| MSI MS-7C91           | 1        | 0.72%   |
| MSI MS-7B86           | 1        | 0.72%   |
| MSI MS-7B24           | 1        | 0.72%   |
| MSI MS-7994           | 1        | 0.72%   |
| MSI MS-7971           | 1        | 0.72%   |
| MSI MS-7636           | 1        | 0.72%   |
| Medion MS-7707        | 1        | 0.72%   |
| Medion MS-7621        | 1        | 0.72%   |
| Medion Akoya          | 1        | 0.72%   |
| Lenovo ThinkStation   | 1        | 0.72%   |
| Lenovo H535s          | 1        | 0.72%   |
| Intel DQ67SW          | 1        | 0.72%   |
| Intel DQ35JO          | 1        | 0.72%   |
| Intel DH87RL          | 1        | 0.72%   |
| Intel CM-iAM          | 1        | 0.72%   |
| HP Z440               | 1        | 0.72%   |
| HP Z420               | 1        | 0.72%   |
| HP Z230               | 1        | 0.72%   |
| HP Z1                 | 1        | 0.72%   |
| HP xw4400             | 1        | 0.72%   |
| HP Rfrb               | 1        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 14       | 10.14%  |
| 2009 | 14       | 10.14%  |
| 2019 | 12       | 8.7%    |
| 2017 | 12       | 8.7%    |
| 2015 | 11       | 7.97%   |
| 2013 | 11       | 7.97%   |
| 2011 | 11       | 7.97%   |
| 2020 | 9        | 6.52%   |
| 2010 | 7        | 5.07%   |
| 2016 | 6        | 4.35%   |
| 2014 | 6        | 4.35%   |
| 2012 | 5        | 3.62%   |
| 2008 | 5        | 3.62%   |
| 2007 | 5        | 3.62%   |
| 2006 | 4        | 2.9%    |
| 2021 | 3        | 2.17%   |
| 2022 | 2        | 1.45%   |
| 2023 | 1        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 138      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 134      | 97.1%   |
| Enabled  | 4        | 2.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 138      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 37       | 26.43%  |
| 8.01-16.0   | 32       | 22.86%  |
| 3.01-4.0    | 23       | 16.43%  |
| 32.01-64.0  | 17       | 12.14%  |
| 4.01-8.0    | 15       | 10.71%  |
| 2.01-3.0    | 5        | 3.57%   |
| 64.01-256.0 | 5        | 3.57%   |
| 24.01-32.0  | 4        | 2.86%   |
| 1.01-2.0    | 2        | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 53       | 33.76%  |
| 2.01-3.0   | 33       | 21.02%  |
| 4.01-8.0   | 30       | 19.11%  |
| 3.01-4.0   | 18       | 11.46%  |
| 8.01-16.0  | 9        | 5.73%   |
| 0.51-1.0   | 6        | 3.82%   |
| 0.01-0.5   | 4        | 2.55%   |
| 16.01-24.0 | 3        | 1.91%   |
| 24.01-32.0 | 1        | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 54       | 37.5%   |
| 2      | 42       | 29.17%  |
| 3      | 20       | 13.89%  |
| 4      | 11       | 7.64%   |
| 5      | 6        | 4.17%   |
| 6      | 4        | 2.78%   |
| 8      | 3        | 2.08%   |
| 7      | 2        | 1.39%   |
| 11     | 1        | 0.69%   |
| 0      | 1        | 0.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 54.29%  |
| Yes       | 64       | 45.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 136      | 98.55%  |
| No        | 2        | 1.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 69.06%  |
| Yes       | 43       | 30.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 76.81%  |
| Yes       | 32       | 23.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Slovenia | 138      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Ljubljana           | 51       | 34.23%  |
| Vrhnika             | 5        | 3.36%   |
| Maribor             | 4        | 2.68%   |
| Koper               | 4        | 2.68%   |
| Kamnik              | 4        | 2.68%   |
| Sempeter pri Gorici | 3        | 2.01%   |
| Rence               | 3        | 2.01%   |
| Radovljica          | 3        | 2.01%   |
| Novo Mesto          | 3        | 2.01%   |
| Kranj               | 3        | 2.01%   |
| Grosuplje           | 3        | 2.01%   |
| Žalec              | 2        | 1.34%   |
| Škofja Loka        | 2        | 1.34%   |
| Ptuj                | 2        | 1.34%   |
| Pragersko           | 2        | 1.34%   |
| Logatec             | 2        | 1.34%   |
| Crensovci           | 2        | 1.34%   |
| Celje               | 2        | 1.34%   |
| Zirovnica           | 1        | 0.67%   |
| Ziri                | 1        | 0.67%   |
| Zgornja Besnica     | 1        | 0.67%   |
| Vuzenica            | 1        | 0.67%   |
| Volcja Draga        | 1        | 0.67%   |
| Velenje             | 1        | 0.67%   |
| Trzin               | 1        | 0.67%   |
| Štore              | 1        | 0.67%   |
| Stari Trg pri Lozu  | 1        | 0.67%   |
| Sostanj             | 1        | 0.67%   |
| Slovenske Konjice   | 1        | 0.67%   |
| Slovenska Bistrica  | 1        | 0.67%   |
| Selnica ob Dravi    | 1        | 0.67%   |
| Radomlje            | 1        | 0.67%   |
| Race                | 1        | 0.67%   |
| Postojna            | 1        | 0.67%   |
| Portorož           | 1        | 0.67%   |
| Podvelka            | 1        | 0.67%   |
| Petrovce            | 1        | 0.67%   |
| Oplotnica           | 1        | 0.67%   |
| Nova Gorica         | 1        | 0.67%   |
| Muta                | 1        | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 68       | 131    | 27.09%  |
| Samsung Electronics         | 31       | 59     | 12.35%  |
| Seagate                     | 29       | 53     | 11.55%  |
| Kingston                    | 21       | 28     | 8.37%   |
| Toshiba                     | 19       | 25     | 7.57%   |
| Crucial                     | 15       | 21     | 5.98%   |
| SanDisk                     | 10       | 12     | 3.98%   |
| Intel                       | 5        | 6      | 1.99%   |
| Corsair                     | 5        | 6      | 1.99%   |
| Intenso                     | 4        | 6      | 1.59%   |
| Hitachi                     | 4        | 4      | 1.59%   |
| OCZ                         | 3        | 7      | 1.2%    |
| Silicon Motion              | 2        | 2      | 0.8%    |
| PNY                         | 2        | 2      | 0.8%    |
| Patriot                     | 2        | 3      | 0.8%    |
| JMicron Technology          | 2        | 2      | 0.8%    |
| HGST                        | 2        | 2      | 0.8%    |
| Hewlett-Packard             | 2        | 2      | 0.8%    |
| China                       | 2        | 2      | 0.8%    |
| Apacer                      | 2        | 3      | 0.8%    |
| Unknown                     | 1        | 1      | 0.4%    |
| TS512GMT                    | 1        | 5      | 0.4%    |
| Transcend                   | 1        | 2      | 0.4%    |
| SPCC                        | 1        | 2      | 0.4%    |
| SK hynix                    | 1        | 1      | 0.4%    |
| Realtek                     | 1        | 1      | 0.4%    |
| Phison Electronics          | 1        | 1      | 0.4%    |
| Phison                      | 1        | 1      | 0.4%    |
| Netac                       | 1        | 1      | 0.4%    |
| Maxtor                      | 1        | 1      | 0.4%    |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.4%    |
| LITEONIT                    | 1        | 1      | 0.4%    |
| Leven                       | 1        | 1      | 0.4%    |
| KIOXIA                      | 1        | 1      | 0.4%    |
| KingDian                    | 1        | 1      | 0.4%    |
| Integral                    | 1        | 1      | 0.4%    |
| GOODRAM                     | 1        | 1      | 0.4%    |
| Gigabyte Technology         | 1        | 2      | 0.4%    |
| Fujitsu                     | 1        | 1      | 0.4%    |
| ASMT109x                    | 1        | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 7        | 2.3%    |
| Toshiba DT01ACA100 1TB           | 6        | 1.97%   |
| Crucial CT240BX500SSD1 240GB     | 6        | 1.97%   |
| WDC WD10EARS-00Y5B1 1TB          | 4        | 1.31%   |
| Toshiba HDWD120 2TB              | 4        | 1.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 3        | 0.98%   |
| WDC WD5000AADS-00S9B0 500GB      | 3        | 0.98%   |
| Toshiba DT01ACA200 2TB           | 3        | 0.98%   |
| SanDisk SSD PLUS 1000GB          | 3        | 0.98%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.98%   |
| Samsung SSD 860 EVO 1TB          | 3        | 0.98%   |
| Samsung SSD 850 EVO 250GB        | 3        | 0.98%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2        | 0.66%   |
| WDC WDS500G2B0A 500GB SSD        | 2        | 0.66%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 2        | 0.66%   |
| WDC WD5000AAKX-001CA0 500GB      | 2        | 0.66%   |
| WDC WD5000AACS-00G8B1 500GB      | 2        | 0.66%   |
| WDC WD40PURZ-85TTDY0 4TB         | 2        | 0.66%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 2        | 0.66%   |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 0.66%   |
| WDC WD20PURZ-85GU6Y0 2TB         | 2        | 0.66%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 0.66%   |
| WDC WD15EARS-00MVWB0 1TB         | 2        | 0.66%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 0.66%   |
| WDC WD10EADS-00L5B1 1TB          | 2        | 0.66%   |
| WDC WD1002FAEX-00Y9A0 1TB        | 2        | 0.66%   |
| Toshiba DT01ACA050 500GB         | 2        | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.66%   |
| Seagate Portable 2TB             | 2        | 0.66%   |
| SanDisk SSD PLUS 240GB           | 2        | 0.66%   |
| SanDisk NVMe SSD Drive 500GB     | 2        | 0.66%   |
| Samsung SSD 980 PRO 500GB        | 2        | 0.66%   |
| Samsung SSD 980 PRO 250GB        | 2        | 0.66%   |
| Samsung SSD 980 1TB              | 2        | 0.66%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.66%   |
| Samsung SSD 850 EVO 120GB        | 2        | 0.66%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 0.66%   |
| Kingston SUV400S37240G 240GB SSD | 2        | 0.66%   |
| Kingston SA400S37480G 480GB SSD  | 2        | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 60       | 114    | 51.72%  |
| Seagate             | 27       | 49     | 23.28%  |
| Toshiba             | 17       | 23     | 14.66%  |
| Hitachi             | 4        | 4      | 3.45%   |
| Samsung Electronics | 2        | 2      | 1.72%   |
| HGST                | 2        | 2      | 1.72%   |
| Maxtor              | 1        | 1      | 0.86%   |
| Intenso             | 1        | 1      | 0.86%   |
| Fujitsu             | 1        | 1      | 0.86%   |
| ASMT109x            | 1        | 1      | 0.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 18       | 21     | 18.75%  |
| Samsung Electronics | 15       | 27     | 15.63%  |
| Crucial             | 14       | 20     | 14.58%  |
| WDC                 | 12       | 14     | 12.5%   |
| SanDisk             | 6        | 7      | 6.25%   |
| Intel               | 5        | 6      | 5.21%   |
| OCZ                 | 3        | 7      | 3.13%   |
| Corsair             | 3        | 4      | 3.13%   |
| PNY                 | 2        | 2      | 2.08%   |
| Patriot             | 2        | 3      | 2.08%   |
| JMicron Technology  | 2        | 2      | 2.08%   |
| China               | 2        | 2      | 2.08%   |
| Apacer              | 2        | 3      | 2.08%   |
| Transcend           | 1        | 2      | 1.04%   |
| Toshiba             | 1        | 1      | 1.04%   |
| Netac               | 1        | 1      | 1.04%   |
| LITEONIT            | 1        | 1      | 1.04%   |
| Leven               | 1        | 1      | 1.04%   |
| KingDian            | 1        | 1      | 1.04%   |
| Intenso             | 1        | 1      | 1.04%   |
| Integral            | 1        | 1      | 1.04%   |
| GOODRAM             | 1        | 1      | 1.04%   |
| A-DATA Technology   | 1        | 2      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 93       | 198    | 42.27%  |
| SSD     | 77       | 130    | 35%     |
| NVMe    | 44       | 64     | 20%     |
| Unknown | 6        | 13     | 2.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 124      | 323    | 68.89%  |
| NVMe | 44       | 63     | 24.44%  |
| SAS  | 12       | 19     | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 96       | 174    | 51.34%  |
| 0.51-1.0   | 54       | 97     | 28.88%  |
| 1.01-2.0   | 19       | 27     | 10.16%  |
| 3.01-4.0   | 9        | 16     | 4.81%   |
| 4.01-10.0  | 5        | 9      | 2.67%   |
| 2.01-3.0   | 3        | 4      | 1.6%    |
| 10.01-20.0 | 1        | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 32       | 21.33%  |
| 251-500        | 24       | 16%     |
| 1001-2000      | 20       | 13.33%  |
| 501-1000       | 19       | 12.67%  |
| 1-20           | 16       | 10.67%  |
| More than 3000 | 10       | 6.67%   |
| 2001-3000      | 10       | 6.67%   |
| 51-100         | 9        | 6%      |
| Unknown        | 6        | 4%      |
| 21-50          | 4        | 2.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 52       | 34.9%   |
| 21-50          | 21       | 14.09%  |
| 51-100         | 19       | 12.75%  |
| 101-250        | 16       | 10.74%  |
| 251-500        | 10       | 6.71%   |
| 1001-2000      | 10       | 6.71%   |
| 501-1000       | 7        | 4.7%    |
| 2001-3000      | 6        | 4.03%   |
| Unknown        | 6        | 4.03%   |
| More than 3000 | 2        | 1.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB                 | 2        | 3      | 7.69%   |
| WDC WDS480G2G0A-00JH30 480GB SSD         | 1        | 1      | 3.85%   |
| WDC WD800BD-22LRA0 80GB                  | 1        | 1      | 3.85%   |
| WDC WD5000AADS-00S9B0 500GB              | 1        | 1      | 3.85%   |
| WDC WD40EFRX-68N32N0 4TB                 | 1        | 1      | 3.85%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1        | 1      | 3.85%   |
| Toshiba Q300. 240GB SSD                  | 1        | 1      | 3.85%   |
| Toshiba DT01ACA300 3TB                   | 1        | 1      | 3.85%   |
| Seagate ST3500514NS 500GB                | 1        | 1      | 3.85%   |
| Seagate ST3500320NS 500GB                | 1        | 1      | 3.85%   |
| Seagate ST3320620AS 320GB                | 1        | 1      | 3.85%   |
| Seagate ST3200822AS 200GB                | 1        | 1      | 3.85%   |
| Seagate ST2000DM001-1CH164 2TB           | 1        | 1      | 3.85%   |
| Seagate ST1000DM003-1CH162 1TB           | 1        | 2      | 3.85%   |
| SanDisk SSD PLUS 240GB                   | 1        | 1      | 3.85%   |
| SanDisk SSD PLUS 1000GB                  | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 970 EVO 1TB      | 1        | 1      | 3.85%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 3.85%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 2      | 3.85%   |
| Kingston SA400S37240G 240GB SSD          | 1        | 1      | 3.85%   |
| Intel SSDSCKKW240H6 240GB                | 1        | 1      | 3.85%   |
| Intel SSDSA2M160G2GC 160GB               | 1        | 1      | 3.85%   |
| HGST HTS541075A9E680 752GB               | 1        | 1      | 3.85%   |
| Hewlett-Packard SSD EX900 500GB          | 1        | 1      | 3.85%   |
| Crucial M4-CT128M4SSD2 128GB             | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 8      | 26.09%  |
| Seagate             | 4        | 7      | 17.39%  |
| Toshiba             | 2        | 2      | 8.7%    |
| SanDisk             | 2        | 2      | 8.7%    |
| Samsung Electronics | 2        | 2      | 8.7%    |
| Intel               | 2        | 2      | 8.7%    |
| OCZ                 | 1        | 2      | 4.35%   |
| Kingston            | 1        | 1      | 4.35%   |
| HGST                | 1        | 1      | 4.35%   |
| Hewlett-Packard     | 1        | 1      | 4.35%   |
| Crucial             | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 7      | 45.45%  |
| Seagate | 4        | 7      | 36.36%  |
| Toshiba | 1        | 1      | 9.09%   |
| HGST    | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 9        | 11     | 45%     |
| HDD  | 9        | 16     | 45%     |
| NVMe | 2        | 2      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| SPCC M.2 PCIe SSD 2TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| SPCC   | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 79       | 184    | 48.47%  |
| Works    | 64       | 191    | 39.26%  |
| Malfunc  | 19       | 29     | 11.66%  |
| Failed   | 1        | 1      | 0.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 93       | 45.59%  |
| AMD                           | 42       | 20.59%  |
| Samsung Electronics           | 19       | 9.31%   |
| SanDisk                       | 7        | 3.43%   |
| JMicron Technology            | 6        | 2.94%   |
| ASMedia Technology            | 6        | 2.94%   |
| Silicon Motion                | 5        | 2.45%   |
| Phison Electronics            | 5        | 2.45%   |
| Kingston Technology Company   | 5        | 2.45%   |
| Marvell Technology Group      | 4        | 1.96%   |
| Nvidia                        | 3        | 1.47%   |
| Toshiba America Info Systems  | 1        | 0.49%   |
| SK hynix                      | 1        | 0.49%   |
| Silicon Image                 | 1        | 0.49%   |
| Seagate Technology            | 1        | 0.49%   |
| OCZ Technology Group          | 1        | 0.49%   |
| Micron/Crucial Technology     | 1        | 0.49%   |
| MAXIO Technology (Hangzhou)   | 1        | 0.49%   |
| KIOXIA                        | 1        | 0.49%   |
| Integrated Technology Express | 1        | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28       | 10.65%  |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 4.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 4.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 3.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 3.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 2.66%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 2.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 1.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.9%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 1.9%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 1.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5        | 1.9%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5        | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 1.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 1.52%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 1.14%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 1.14%   |
| JMicron JMB368 IDE controller                                                           | 3        | 1.14%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 1.14%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.14%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.14%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.76%   |
| Phison E12 NVMe Controller                                                              | 2        | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                            | 2        | 0.76%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.76%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 2        | 0.76%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 0.76%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 2        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.76%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 105      | 53.3%   |
| NVMe | 44       | 22.34%  |
| IDE  | 39       | 19.8%   |
| RAID | 7        | 3.55%   |
| SAS  | 1        | 0.51%   |
| SCSI | 1        | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 95       | 68.84%  |
| AMD    | 43       | 31.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor         | 4        | 2.9%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3        | 2.17%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 2.17%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.17%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 2.17%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 3        | 2.17%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.45%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.45%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.45%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.45%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 2        | 1.45%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 2        | 1.45%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.45%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 2        | 1.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.45%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2        | 1.45%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 2        | 1.45%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.45%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.45%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.45%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 1.45%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.45%   |
| AMD Phenom II X6 1055T Processor            | 2        | 1.45%   |
| Intel Xeon CPU X5365 @ 3.00GHz              | 1        | 0.72%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.72%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.72%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz          | 1        | 0.72%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz         | 1        | 0.72%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz         | 1        | 0.72%   |
| Intel Xeon CPU E3-1225 v6 @ 3.30GHz         | 1        | 0.72%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.72%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1        | 0.72%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 0.72%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1        | 0.72%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.72%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.72%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.72%   |
| Intel N100                                  | 1        | 0.72%   |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1        | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 34       | 24.64%  |
| AMD Ryzen 5             | 15       | 10.87%  |
| Intel Core i7           | 12       | 8.7%    |
| Intel Core 2 Duo        | 10       | 7.25%   |
| Intel Core i3           | 9        | 6.52%   |
| Intel Xeon              | 8        | 5.8%    |
| AMD Ryzen 7             | 7        | 5.07%   |
| AMD Ryzen 9             | 6        | 4.35%   |
| Other                   | 4        | 2.9%    |
| Intel Pentium           | 4        | 2.9%    |
| Intel Core 2 Quad       | 3        | 2.17%   |
| Intel Core 2            | 3        | 2.17%   |
| Intel Celeron           | 3        | 2.17%   |
| AMD Ryzen 3             | 3        | 2.17%   |
| Intel Atom              | 2        | 1.45%   |
| AMD Phenom II X6        | 2        | 1.45%   |
| AMD FX                  | 2        | 1.45%   |
| AMD A10                 | 2        | 1.45%   |
| Intel Pentium Dual-Core | 1        | 0.72%   |
| Intel Pentium D         | 1        | 0.72%   |
| Intel Core i9           | 1        | 0.72%   |
| AMD Ryzen 3 PRO         | 1        | 0.72%   |
| AMD Phenom II X4        | 1        | 0.72%   |
| AMD Athlon X4           | 1        | 0.72%   |
| AMD Athlon II X4        | 1        | 0.72%   |
| AMD Athlon II X2        | 1        | 0.72%   |
| AMD Athlon 64 X2        | 1        | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 58       | 42.03%  |
| 2      | 35       | 25.36%  |
| 6      | 27       | 19.57%  |
| 8      | 10       | 7.25%   |
| 12     | 5        | 3.62%   |
| 1      | 2        | 1.45%   |
| 16     | 1        | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 137      | 99.28%  |
| 2      | 1        | 0.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 70       | 50.72%  |
| 2      | 68       | 49.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 135      | 97.12%  |
| Unknown        | 3        | 2.16%   |
| 32-bit         | 1        | 0.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 32       | 21.92%  |
| 0x506e3    | 9        | 6.16%   |
| 0x906ea    | 7        | 4.79%   |
| 0x306c3    | 7        | 4.79%   |
| 0x906e9    | 6        | 4.11%   |
| 0x306a9    | 6        | 4.11%   |
| 0x206a7    | 6        | 4.11%   |
| 0x1067a    | 5        | 3.42%   |
| 0x0a201016 | 5        | 3.42%   |
| 0x106e5    | 4        | 2.74%   |
| 0x10676    | 4        | 2.74%   |
| 0x0800820d | 4        | 2.74%   |
| 0x6fb      | 3        | 2.05%   |
| 0x0a201009 | 3        | 2.05%   |
| 0x08108109 | 3        | 2.05%   |
| 0x08001138 | 3        | 2.05%   |
| 0xa0671    | 2        | 1.37%   |
| 0x906ed    | 2        | 1.37%   |
| 0x20655    | 2        | 1.37%   |
| 0x106c2    | 2        | 1.37%   |
| 0x08701021 | 2        | 1.37%   |
| 0x08001137 | 2        | 1.37%   |
| 0x010000dc | 2        | 1.37%   |
| 0xf47      | 1        | 0.68%   |
| 0xa0655    | 1        | 0.68%   |
| 0x906eb    | 1        | 0.68%   |
| 0x6fd      | 1        | 0.68%   |
| 0x6f7      | 1        | 0.68%   |
| 0x6f6      | 1        | 0.68%   |
| 0x6f2      | 1        | 0.68%   |
| 0x406f1    | 1        | 0.68%   |
| 0x306e4    | 1        | 0.68%   |
| 0x30678    | 1        | 0.68%   |
| 0x206d7    | 1        | 0.68%   |
| 0x20652    | 1        | 0.68%   |
| 0x106a5    | 1        | 0.68%   |
| 0x0a50000c | 1        | 0.68%   |
| 0x0a20120a | 1        | 0.68%   |
| 0x0a201205 | 1        | 0.68%   |
| 0x08701013 | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 17       | 12.32%  |
| Zen 3       | 12       | 8.7%    |
| Haswell     | 12       | 8.7%    |
| Skylake     | 10       | 7.25%   |
| Penryn      | 10       | 7.25%   |
| SandyBridge | 9        | 6.52%   |
| Core        | 9        | 6.52%   |
| Zen+        | 8        | 5.8%    |
| IvyBridge   | 8        | 5.8%    |
| Zen         | 7        | 5.07%   |
| Nehalem     | 6        | 4.35%   |
| K10         | 5        | 3.62%   |
| Zen 2       | 4        | 2.9%    |
| Westmere    | 3        | 2.17%   |
| Piledriver  | 3        | 2.17%   |
| Unknown     | 3        | 2.17%   |
| Silvermont  | 2        | 1.45%   |
| Bonnell     | 2        | 1.45%   |
| Steamroller | 1        | 0.72%   |
| NetBurst    | 1        | 0.72%   |
| K8 Hammer   | 1        | 0.72%   |
| Icelake     | 1        | 0.72%   |
| Gracemont   | 1        | 0.72%   |
| Excavator   | 1        | 0.72%   |
| CometLake   | 1        | 0.72%   |
| Broadwell   | 1        | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 63       | 42%     |
| AMD    | 45       | 30%     |
| Intel  | 42       | 28%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 5.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 3.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.29%   |
| Intel HD Graphics 630                                                       | 4        | 2.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 2.63%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 4        | 2.63%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 4        | 2.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.97%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.97%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 1.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.97%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.32%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.32%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.32%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.32%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.32%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.32%   |
| Nvidia G98M [GeForce 9300M GS]                                              | 2        | 1.32%   |
| Intel HD Graphics 530                                                       | 2        | 1.32%   |
| Intel HD Graphics 510                                                       | 2        | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 1.32%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.32%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 2        | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.32%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 1.32%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 2        | 1.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.32%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.32%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.66%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.66%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.66%   |
| Nvidia GP104GL [Quadro P4000]                                               | 1        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.66%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 56       | 40%     |
| 1 x AMD        | 39       | 27.86%  |
| 1 x Intel      | 36       | 25.71%  |
| AMD + Nvidia   | 4        | 2.86%   |
| Intel + Nvidia | 3        | 2.14%   |
| 2 x AMD        | 2        | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 102      | 71.83%  |
| Proprietary | 31       | 21.83%  |
| Unknown     | 9        | 6.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 62       | 42.76%  |
| 1.01-2.0   | 21       | 14.48%  |
| 7.01-8.0   | 14       | 9.66%   |
| 0.01-0.5   | 13       | 8.97%   |
| 0.51-1.0   | 12       | 8.28%   |
| 3.01-4.0   | 9        | 6.21%   |
| 5.01-6.0   | 6        | 4.14%   |
| 8.01-16.0  | 5        | 3.45%   |
| 2.01-3.0   | 2        | 1.38%   |
| 4.01-5.0   | 1        | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 34       | 22.22%  |
| Dell                 | 28       | 18.3%   |
| AOC                  | 21       | 13.73%  |
| Goldstar             | 16       | 10.46%  |
| Philips              | 14       | 9.15%   |
| Hewlett-Packard      | 9        | 5.88%   |
| Ancor Communications | 4        | 2.61%   |
| Acer                 | 4        | 2.61%   |
| Lenovo               | 3        | 1.96%   |
| Iiyama               | 3        | 1.96%   |
| ViewSonic            | 2        | 1.31%   |
| Sony                 | 2        | 1.31%   |
| Vestel Elektronik    | 1        | 0.65%   |
| Unknown              | 1        | 0.65%   |
| RS                   | 1        | 0.65%   |
| LG Display           | 1        | 0.65%   |
| HannStar             | 1        | 0.65%   |
| Grundig              | 1        | 0.65%   |
| FUN                  | 1        | 0.65%   |
| Eizo                 | 1        | 0.65%   |
| DIF                  | 1        | 0.65%   |
| DENON                | 1        | 0.65%   |
| BenQ                 | 1        | 0.65%   |
| ASUSTek Computer     | 1        | 0.65%   |
| Arnos Instruments    | 1        | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Philips LCD Monitor FTV 1920x1080                                       | 3        | 1.81%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 3        | 1.81%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 3        | 1.81%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 3        | 1.81%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 376x301mm 19.0-inch    | 2        | 1.2%    |
| Samsung Electronics LCD Monitor SAM04FD 1280x720                        | 2        | 1.2%    |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 2        | 1.2%    |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                       | 2        | 1.2%    |
| Dell U2515H DELD06E 2560x1440 553x311mm 25.0-inch                       | 2        | 1.2%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                     | 2        | 1.2%    |
| AOC LCD Monitor AG251FWG2 1920x1080                                     | 2        | 1.2%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                         | 2        | 1.2%    |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1        | 0.6%    |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                  | 1        | 0.6%    |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch    | 1        | 0.6%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 0.6%    |
| Sony TV SNYAB03 1920x1080                                               | 1        | 0.6%    |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                      | 1        | 0.6%    |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch       | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM05EC 1920x1080 597x336mm 27.0-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM04DE 1920x1080 477x268mm 21.5-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM044C 1680x1050 474x296mm 22.0-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0423 1920x1080                        | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0303 1680x1050 494x320mm 23.2-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0288 1680x1050 474x296mm 22.0-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM0214 1680x1050 408x306mm 20.1-inch    | 1        | 0.6%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch    | 1        | 0.6%    |
| Samsung Electronics SMS24A450/460 SAM0838 1920x1080 531x299mm 24.0-inch | 1        | 0.6%    |
| Samsung Electronics SMBX2231 SAM076C 1920x1080 477x268mm 21.5-inch      | 1        | 0.6%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.6%    |
| Samsung Electronics S24E450 SAM0C82 1920x1080 531x299mm 24.0-inch       | 1        | 0.6%    |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch       | 1        | 0.6%    |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch       | 1        | 0.6%    |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch       | 1        | 0.6%    |
| Samsung Electronics S22C200 SAM09B7 1920x1080 477x268mm 21.5-inch       | 1        | 0.6%    |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1        | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 61       | 40.94%  |
| 3840x2160 (4K)     | 17       | 11.41%  |
| 2560x1440 (QHD)    | 15       | 10.07%  |
| 1280x1024 (SXGA)   | 12       | 8.05%   |
| 1680x1050 (WSXGA+) | 11       | 7.38%   |
| 1920x1200 (WUXGA)  | 8        | 5.37%   |
| 3440x1440          | 4        | 2.68%   |
| 2560x1080          | 4        | 2.68%   |
| 1600x900 (HD+)     | 3        | 2.01%   |
| 1440x900 (WXGA+)   | 2        | 1.34%   |
| 1366x768 (WXGA)    | 2        | 1.34%   |
| 1024x768 (XGA)     | 2        | 1.34%   |
| 3840x1600          | 1        | 0.67%   |
| 3840x1080          | 1        | 0.67%   |
| 2560x1600          | 1        | 0.67%   |
| 2560x1024          | 1        | 0.67%   |
| 2288x1287          | 1        | 0.67%   |
| 1280x960           | 1        | 0.67%   |
| 1280x720 (HD)      | 1        | 0.67%   |
| Unknown            | 1        | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 22       | 14.19%  |
| 23      | 18       | 11.61%  |
| 27      | 17       | 10.97%  |
| 21      | 16       | 10.32%  |
| Unknown | 15       | 9.68%   |
| 19      | 11       | 7.1%    |
| 34      | 8        | 5.16%   |
| 22      | 7        | 4.52%   |
| 31      | 6        | 3.87%   |
| 20      | 5        | 3.23%   |
| 65      | 4        | 2.58%   |
| 17      | 4        | 2.58%   |
| 84      | 3        | 1.94%   |
| 72      | 2        | 1.29%   |
| 33      | 2        | 1.29%   |
| 32      | 2        | 1.29%   |
| 25      | 2        | 1.29%   |
| 18      | 2        | 1.29%   |
| 15      | 2        | 1.29%   |
| 142     | 1        | 0.65%   |
| 55      | 1        | 0.65%   |
| 54      | 1        | 0.65%   |
| 49      | 1        | 0.65%   |
| 37      | 1        | 0.65%   |
| 29      | 1        | 0.65%   |
| 28      | 1        | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 51       | 33.77%  |
| 401-500        | 30       | 19.87%  |
| Unknown        | 15       | 9.93%   |
| 701-800        | 12       | 7.95%   |
| 601-700        | 12       | 7.95%   |
| 351-400        | 12       | 7.95%   |
| 1001-1500      | 7        | 4.64%   |
| 301-350        | 5        | 3.31%   |
| 1501-2000      | 5        | 3.31%   |
| More than 2000 | 1        | 0.66%   |
| 801-900        | 1        | 0.66%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 82       | 57.34%  |
| 16/10   | 20       | 13.99%  |
| 5/4     | 14       | 9.79%   |
| Unknown | 12       | 8.39%   |
| 21/9    | 9        | 6.29%   |
| 4/3     | 3        | 2.1%    |
| 32/9    | 1        | 0.7%    |
| 3/2     | 1        | 0.7%    |
| 1.00    | 1        | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 46       | 30.07%  |
| 151-200        | 21       | 13.73%  |
| 351-500        | 20       | 13.07%  |
| 301-350        | 17       | 11.11%  |
| Unknown        | 15       | 9.8%    |
| 251-300        | 13       | 8.5%    |
| More than 1000 | 12       | 7.84%   |
| 141-150        | 4        | 2.61%   |
| 101-110        | 2        | 1.31%   |
| 501-1000       | 2        | 1.31%   |
| 121-130        | 1        | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 77       | 54.61%  |
| 101-120 | 29       | 20.57%  |
| Unknown | 15       | 10.64%  |
| 1-50    | 9        | 6.38%   |
| 121-160 | 9        | 6.38%   |
| 161-240 | 2        | 1.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 106      | 74.65%  |
| 2     | 28       | 19.72%  |
| 0     | 7        | 4.93%   |
| 6     | 1        | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 81       | 45%     |
| Intel                           | 57       | 31.67%  |
| Qualcomm Atheros                | 7        | 3.89%   |
| Broadcom                        | 6        | 3.33%   |
| Ralink Technology               | 4        | 2.22%   |
| Ralink                          | 4        | 2.22%   |
| ASUSTek Computer                | 3        | 1.67%   |
| Nvidia                          | 2        | 1.11%   |
| Marvell Technology Group        | 2        | 1.11%   |
| Linksys                         | 2        | 1.11%   |
| ZyDAS Technology                | 1        | 0.56%   |
| ZyDAS                           | 1        | 0.56%   |
| VIA Technologies                | 1        | 0.56%   |
| TP-Link                         | 1        | 0.56%   |
| Samsung Electronics             | 1        | 0.56%   |
| Qualcomm Atheros Communications | 1        | 0.56%   |
| IMC Networks                    | 1        | 0.56%   |
| Edimax Technology               | 1        | 0.56%   |
| D-Link System                   | 1        | 0.56%   |
| D-Link                          | 1        | 0.56%   |
| Compal Electronics              | 1        | 0.56%   |
| Belkin Components               | 1        | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69       | 35.75%  |
| Intel Ethernet Connection (2) I219-V                              | 10       | 5.18%   |
| Intel I211 Gigabit Network Connection                             | 9        | 4.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 3.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 2.59%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 1.55%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 1.04%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.04%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 1.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 1.04%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 1.04%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.04%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.04%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.04%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.04%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 2        | 1.04%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2        | 1.04%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 2        | 1.04%   |
| ZyDAS ZD1211 802.11g                                              | 1        | 0.52%   |
| ZyDAS ZD1212B Wireless Adapter                                    | 1        | 0.52%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.52%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.52%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.52%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.52%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1        | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.52%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 0.52%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 1        | 0.52%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 23.26%  |
| Realtek Semiconductor           | 7        | 16.28%  |
| Ralink Technology               | 4        | 9.3%    |
| Ralink                          | 4        | 9.3%    |
| Qualcomm Atheros                | 4        | 9.3%    |
| ASUSTek Computer                | 3        | 6.98%   |
| Broadcom                        | 2        | 4.65%   |
| ZyDAS Technology                | 1        | 2.33%   |
| ZyDAS                           | 1        | 2.33%   |
| Qualcomm Atheros Communications | 1        | 2.33%   |
| Linksys                         | 1        | 2.33%   |
| IMC Networks                    | 1        | 2.33%   |
| Edimax Technology               | 1        | 2.33%   |
| D-Link System                   | 1        | 2.33%   |
| D-Link                          | 1        | 2.33%   |
| Belkin Components               | 1        | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 3        | 6.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                                             | 2        | 4.55%   |
| Ralink MT7601U Wireless Adapter                                                   | 2        | 4.55%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                         | 2        | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 2        | 4.55%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2        | 4.55%   |
| ZyDAS ZD1211 802.11g                                                              | 1        | 2.27%   |
| ZyDAS ZD1212B Wireless Adapter                                                    | 1        | 2.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                   | 1        | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 1        | 2.27%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 1        | 2.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 1        | 2.27%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                   | 1        | 2.27%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                       | 1        | 2.27%   |
| Realtek RTL8188EE Wireless Network Adapter                                        | 1        | 2.27%   |
| Realtek RTL8187 Wireless Adapter                                                  | 1        | 2.27%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                              | 1        | 2.27%   |
| Ralink RT2561/RT61 802.11g PCI                                                    | 1        | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                        | 1        | 2.27%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 2.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1        | 2.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 1        | 2.27%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]            | 1        | 2.27%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]                     | 1        | 2.27%   |
| Intel Wireless 7260                                                               | 1        | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 1        | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 1        | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 1        | 2.27%   |
| Intel Alder Lake-N Wireless-AC                                                    | 1        | 2.27%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                              | 1        | 2.27%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]                 | 1        | 2.27%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1        | 2.27%   |
| D-Link 802.11 n WLAN                                                              | 1        | 2.27%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B]                | 1        | 2.27%   |
| ASUS WL-167G v1 802.11g Adapter [Ralink RT2571]                                   | 1        | 2.27%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]                | 1        | 2.27%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                         | 1        | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 78       | 53.79%  |
| Intel                    | 52       | 35.86%  |
| Broadcom                 | 4        | 2.76%   |
| Qualcomm Atheros         | 3        | 2.07%   |
| Nvidia                   | 2        | 1.38%   |
| Marvell Technology Group | 2        | 1.38%   |
| VIA Technologies         | 1        | 0.69%   |
| TP-Link                  | 1        | 0.69%   |
| Linksys                  | 1        | 0.69%   |
| Compal Electronics       | 1        | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 69       | 46.62%  |
| Intel Ethernet Connection (2) I219-V                                          | 10       | 6.76%   |
| Intel I211 Gigabit Network Connection                                         | 9        | 6.08%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 3.38%   |
| Intel Ethernet Connection I217-LM                                             | 3        | 2.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2        | 1.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2        | 1.35%   |
| Intel Ethernet Controller I225-V                                              | 2        | 1.35%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 1.35%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.35%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.35%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.35%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 1.35%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 2        | 1.35%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                         | 2        | 1.35%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 0.68%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1        | 0.68%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.68%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 0.68%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.68%   |
| Linksys Gigabit Network Adapter                                               | 1        | 0.68%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 0.68%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.68%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 0.68%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.68%   |
| Intel 82583V Gigabit Network Connection                                       | 1        | 0.68%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.68%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 0.68%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1        | 0.68%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 1        | 0.68%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.68%   |
| Intel 82566DM Gigabit Network Connection                                      | 1        | 0.68%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                        | 1        | 0.68%   |
| Compal Android                                                                | 1        | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 136      | 75.56%  |
| WiFi     | 43       | 23.89%  |
| Modem    | 1        | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 116      | 82.27%  |
| WiFi     | 25       | 17.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 101      | 72.66%  |
| 2     | 30       | 21.58%  |
| 3     | 4        | 2.88%   |
| 0     | 2        | 1.44%   |
| 5     | 1        | 0.72%   |
| 4     | 1        | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 125      | 86.81%  |
| Yes  | 19       | 13.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 10       | 30.3%   |
| Cambridge Silicon Radio    | 7        | 21.21%  |
| ASUSTek Computer           | 6        | 18.18%  |
| Realtek Semiconductor      | 2        | 6.06%   |
| Hewlett-Packard            | 2        | 6.06%   |
| Edimax Technology          | 2        | 6.06%   |
| Lite-On Technology         | 1        | 3.03%   |
| Integrated System Solution | 1        | 3.03%   |
| IMC Networks               | 1        | 3.03%   |
| Apple                      | 1        | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 21.21%  |
| Intel AX200 Bluetooth                               | 3        | 9.09%   |
| Realtek Bluetooth Radio                             | 2        | 6.06%   |
| Intel AX210 Bluetooth                               | 2        | 6.06%   |
| Intel AX201 Bluetooth                               | 2        | 6.06%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2        | 6.06%   |
| Edimax Bluetooth Adapter                            | 2        | 6.06%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2        | 6.06%   |
| Lite-On Bluetooth Device                            | 1        | 3.03%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.03%   |
| Intel Bluetooth wireless interface                  | 1        | 3.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.03%   |
| Integrated System Solution Bluetooth Device         | 1        | 3.03%   |
| IMC Networks Bluetooth Radio                        | 1        | 3.03%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 3.03%   |
| ASUS Bluetooth Radio                                | 1        | 3.03%   |
| ASUS BCM20702A0                                     | 1        | 3.03%   |
| ASUS ASUS USB-BT500                                 | 1        | 3.03%   |
| Apple Bluetooth HCI                                 | 1        | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 88       | 37.45%  |
| AMD                        | 60       | 25.53%  |
| Nvidia                     | 57       | 24.26%  |
| C-Media Electronics        | 4        | 1.7%    |
| Logitech                   | 3        | 1.28%   |
| ASUSTek Computer           | 3        | 1.28%   |
| JMTek                      | 2        | 0.85%   |
| BEHRINGER International    | 2        | 0.85%   |
| Yamaha                     | 1        | 0.43%   |
| Textech International      | 1        | 0.43%   |
| Texas Instruments          | 1        | 0.43%   |
| Syntek                     | 1        | 0.43%   |
| Sony                       | 1        | 0.43%   |
| SAVITECH                   | 1        | 0.43%   |
| PreSonus Audio Electronics | 1        | 0.43%   |
| Nam Tai E&E Products       | 1        | 0.43%   |
| Mackie Designs             | 1        | 0.43%   |
| Kingston Technology        | 1        | 0.43%   |
| iCreate Technologies       | 1        | 0.43%   |
| Guangzhou FiiO Electronics | 1        | 0.43%   |
| DCMT Technology            | 1        | 0.43%   |
| Creative Technology        | 1        | 0.43%   |
| Creative Labs              | 1        | 0.43%   |
| AKAI Professional M.I.     | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 13       | 4.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11       | 4.14%   |
| Intel 200 Series PCH HD Audio                                                     | 10       | 3.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10       | 3.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 3.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9        | 3.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 9        | 3.38%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8        | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 7        | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 7        | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                        | 6        | 2.26%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5        | 1.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 5        | 1.88%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5        | 1.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 1.88%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 1.88%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 1.5%    |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4        | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.5%    |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 4        | 1.5%    |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 1.13%   |
| Nvidia TU104 HD Audio Controller                                                  | 3        | 1.13%   |
| Nvidia GP102 HDMI Audio Controller                                                | 3        | 1.13%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3        | 1.13%   |
| Nvidia GK106 HDMI Audio Controller                                                | 3        | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 1.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 1.13%   |
| AMD FCH Azalia Controller                                                         | 3        | 1.13%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.13%   |
| Nvidia MCP79 High Definition Audio                                                | 2        | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 0.75%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.75%   |
| Nvidia GF106 High Definition Audio Controller                                     | 2        | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 16       | 17.39%  |
| G.Skill             | 14       | 15.22%  |
| Crucial             | 14       | 15.22%  |
| Unknown             | 9        | 9.78%   |
| SK hynix            | 8        | 8.7%    |
| Samsung Electronics | 8        | 8.7%    |
| Corsair             | 6        | 6.52%   |
| Team                | 2        | 2.17%   |
| TakeMS              | 2        | 2.17%   |
| Patriot             | 2        | 2.17%   |
| Nanya Technology    | 2        | 2.17%   |
| Micron Technology   | 2        | 2.17%   |
| Transcend           | 1        | 1.09%   |
| Swissbit            | 1        | 1.09%   |
| Silicon Power       | 1        | 1.09%   |
| Ramaxel Technology  | 1        | 1.09%   |
| GOODRAM             | 1        | 1.09%   |
| Elpida              | 1        | 1.09%   |
| A-DATA Technology   | 1        | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 1333MT/s                                       | 2        | 2.06%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                          | 2        | 2.06%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s                     | 2        | 2.06%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                  | 1        | 1.03%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s                                | 1        | 1.03%   |
| Unknown RAM Module 2GB SODIMM DDR2                                         | 1        | 1.03%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                        | 1        | 1.03%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                        | 1        | 1.03%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                                | 1        | 1.03%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                      | 1        | 1.03%   |
| Transcend RAM JM800QLU-2G 1GB DIMM DDR2 2048MT/s                           | 1        | 1.03%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s                         | 1        | 1.03%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s                         | 1        | 1.03%   |
| TakeMS RAM TMS4GB364F081139EM 4096MB DIMM DDR3 1333MT/s                    | 1        | 1.03%   |
| TakeMS RAM TMS4GB364E081139PP 4GB DIMM DDR3 1333MT/s                       | 1        | 1.03%   |
| TakeMS RAM TMS2GB264D081805EV 2048MB DIMM DDR2 800MT/s                     | 1        | 1.03%   |
| Swissbit RAM MEN02G64D2BF2EP-2A 2GB DIMM SDRAM 2048MT/s                    | 1        | 1.03%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                               | 1        | 1.03%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                                 | 1        | 1.03%   |
| SK hynix RAM Module 4096MB FB-DIMM DDR2 667MT/s                            | 1        | 1.03%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8GB DIMM DDR3 1600MT/s                       | 1        | 1.03%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                       | 1        | 1.03%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s                       | 1        | 1.03%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s                       | 1        | 1.03%   |
| SK hynix RAM 48594D503131325536344350382D53362020 1024MB DIMM DDR2 800MT/s | 1        | 1.03%   |
| Silicon Power RAM SP004GBLFU240W02 4GB DIMM DDR4 2400MT/s                  | 1        | 1.03%   |
| Samsung RAM Module 4096MB DIMM DDR4 2400MT/s                               | 1        | 1.03%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s                     | 1        | 1.03%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1867MT/s                        | 1        | 1.03%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s                        | 1        | 1.03%   |
| Samsung RAM M391A2K43BB1-CRC 16GB DIMM DDR4 2866MT/s                       | 1        | 1.03%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s                        | 1        | 1.03%   |
| Samsung RAM M378B5673FH0-CF8 2GB DIMM DDR3 1067MT/s                        | 1        | 1.03%   |
| Samsung RAM M3 78T5663QZ3-CF7 2048MB DIMM DDR2 800MT/s                     | 1        | 1.03%   |
| Samsung RAM M3 78T5663QZ3-CE6 2GB DIMM DDR 667MT/s                         | 1        | 1.03%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s                      | 1        | 1.03%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s                        | 1        | 1.03%   |
| Patriot RAM 3000 C16 Series 16GB DIMM DDR4 3200MT/s                        | 1        | 1.03%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s                         | 1        | 1.03%   |
| Nanya RAM NT1GT64U88D0BY-AD 1GB DIMM DDR2 49926MT/s                        | 1        | 1.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 46       | 56.1%   |
| DDR3    | 18       | 21.95%  |
| DDR2    | 8        | 9.76%   |
| SDRAM   | 4        | 4.88%   |
| Unknown | 4        | 4.88%   |
| DDR5    | 1        | 1.22%   |
| DDR     | 1        | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 75       | 92.59%  |
| SODIMM  | 5        | 6.17%   |
| FB-DIMM | 1        | 1.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 39.02%  |
| 4096  | 16       | 19.51%  |
| 16384 | 13       | 15.85%  |
| 2048  | 13       | 15.85%  |
| 32768 | 4        | 4.88%   |
| 1024  | 4        | 4.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 11       | 11.96%  |
| 2400    | 8        | 8.7%    |
| 1600    | 8        | 8.7%    |
| 1333    | 7        | 7.61%   |
| 3600    | 6        | 6.52%   |
| 2667    | 6        | 6.52%   |
| 2133    | 6        | 6.52%   |
| 800     | 4        | 4.35%   |
| 667     | 4        | 4.35%   |
| 3733    | 3        | 3.26%   |
| 2048    | 3        | 3.26%   |
| 1867    | 3        | 3.26%   |
| 1800    | 3        | 3.26%   |
| 3800    | 2        | 2.17%   |
| 3000    | 2        | 2.17%   |
| 2800    | 2        | 2.17%   |
| 49926   | 1        | 1.09%   |
| 4800    | 1        | 1.09%   |
| 4133    | 1        | 1.09%   |
| 3866    | 1        | 1.09%   |
| 3534    | 1        | 1.09%   |
| 3466    | 1        | 1.09%   |
| 3333    | 1        | 1.09%   |
| 3266    | 1        | 1.09%   |
| 2866    | 1        | 1.09%   |
| 1866    | 1        | 1.09%   |
| 1639    | 1        | 1.09%   |
| 1067    | 1        | 1.09%   |
| 400     | 1        | 1.09%   |
| Unknown | 1        | 1.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 3        | 30%     |
| Xerox                 | 1        | 10%     |
| Seiko Epson           | 1        | 10%     |
| Samsung Electronics   | 1        | 10%     |
| Lexmark International | 1        | 10%     |
| Datamax-O'Neil        | 1        | 10%     |
| Canon                 | 1        | 10%     |
| Brother Industries    | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Xerox Phaser 3140 and 3155               | 1        | 10%     |
| Seiko Epson ET-2720 Series               | 1        | 10%     |
| Samsung M2070 Series                     | 1        | 10%     |
| Lexmark International Laser Printer E232 | 1        | 10%     |
| HP DeskJet 4530 series                   | 1        | 10%     |
| HP DeskJet 2600 series                   | 1        | 10%     |
| HP Color LaserJet 2605dn                 | 1        | 10%     |
| Datamax-O'Neil Datamax E-4304            | 1        | 10%     |
| Canon PIXMA MX390 Series                 | 1        | 10%     |
| Brother DCP-L2530DW series               | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 3        | 75%     |
| Acer Peripherals (now BenQ) | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20       | 1        | 25%     |
| Canon CanoScan LiDE 700F                 | 1        | 25%     |
| Canon CanoScan LiDE 220                  | 1        | 25%     |
| Acer Peripherals (now BenQ) Prisa 1240UT | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 33.33%  |
| Chicony Electronics           | 4        | 22.22%  |
| Z-Star Microelectronics       | 1        | 5.56%   |
| Sunplus Innovation Technology | 1        | 5.56%   |
| Sony                          | 1        | 5.56%   |
| Samsung Electronics           | 1        | 5.56%   |
| Pixart Imaging                | 1        | 5.56%   |
| Microdia                      | 1        | 5.56%   |
| MacroSilicon                  | 1        | 5.56%   |
| Cubeternet                    | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Chicony CNF7042                               | 2        | 11.11%  |
| Z-Star Venus USB2.0 Camera                    | 1        | 5.56%   |
| Sunplus HD 720P webcam                        | 1        | 5.56%   |
| Sony CEVCECM                                  | 1        | 5.56%   |
| Samsung Galaxy series, misc. (MTP mode)       | 1        | 5.56%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro          | 1        | 5.56%   |
| Microdia Camera                               | 1        | 5.56%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 5.56%   |
| Logitech Webcam C310                          | 1        | 5.56%   |
| Logitech Webcam C210                          | 1        | 5.56%   |
| Logitech Webcam C170                          | 1        | 5.56%   |
| Logitech HD Webcam C910                       | 1        | 5.56%   |
| Logitech HD Pro Webcam C920                   | 1        | 5.56%   |
| Logitech BRIO Ultra HD Webcam                 | 1        | 5.56%   |
| Cubeternet GL-UPC822 UVC WebCam               | 1        | 5.56%   |
| Chicony WebCam                                | 1        | 5.56%   |
| Chicony USB2.0 HD UVC WebCam                  | 1        | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| SCM Microsystems uTrust 3512 SAM slot Token | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 115      | 81.56%  |
| 1     | 26       | 18.44%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 15       | 57.69%  |
| Multimedia controller | 5        | 19.23%  |
| Net/wireless          | 2        | 7.69%   |
| Unassigned class      | 1        | 3.85%   |
| Fingerprint reader    | 1        | 3.85%   |
| Chipcard              | 1        | 3.85%   |
| Card reader           | 1        | 3.85%   |

