CentOS - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for CentOS.

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

Total: 456

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0K068D A00                  | [a73170db03](https://linux-hardware.org/?probe=a73170db03) | Apr 30, 2022 |
| Unknown       | G41 Series                  | [c6040e6638](https://linux-hardware.org/?probe=c6040e6638) | Apr 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Gigabyte      | EP45-DS3L                   | [4727ba6ee4](https://linux-hardware.org/?probe=4727ba6ee4) | Apr 14, 2022 |
| Gigabyte      | H410M H V3                  | [5b5118db5d](https://linux-hardware.org/?probe=5b5118db5d) | Apr 06, 2022 |
| Unknown       | G41 Series                  | [e5276074c9](https://linux-hardware.org/?probe=e5276074c9) | Apr 01, 2022 |
| Dell          | 0Y2YM6 A01                  | [4578be5a1e](https://linux-hardware.org/?probe=4578be5a1e) | Mar 30, 2022 |
| Unknown       | G41 Series                  | [4dbde5e06f](https://linux-hardware.org/?probe=4dbde5e06f) | Mar 28, 2022 |
| Unknown       | G41 Series                  | [e11644e5c8](https://linux-hardware.org/?probe=e11644e5c8) | Mar 27, 2022 |
| Unknown       | G41 Series                  | [5064d12f0b](https://linux-hardware.org/?probe=5064d12f0b) | Mar 27, 2022 |
| Dell          | 00V62H A01                  | [309ea240bd](https://linux-hardware.org/?probe=309ea240bd) | Mar 25, 2022 |
| HP            | 0AECh D                     | [2fa93f9b4e](https://linux-hardware.org/?probe=2fa93f9b4e) | Mar 22, 2022 |
| MiTAC         | UltraPoint                  | [5199d92feb](https://linux-hardware.org/?probe=5199d92feb) | Mar 21, 2022 |
| ASUSTek       | PRIME X570-PRO              | [beda807e51](https://linux-hardware.org/?probe=beda807e51) | Mar 20, 2022 |
| Gigabyte      | EP45-DS3L                   | [03d7fe99c6](https://linux-hardware.org/?probe=03d7fe99c6) | Mar 05, 2022 |
| HP            | 0A9Ch                       | [0403520776](https://linux-hardware.org/?probe=0403520776) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | [6d961af923](https://linux-hardware.org/?probe=6d961af923) | Mar 03, 2022 |
| ASUSTek       | X99-DELUXE                  | [27513a5e2d](https://linux-hardware.org/?probe=27513a5e2d) | Feb 28, 2022 |
| Intel         | X99                         | [9cc44f0705](https://linux-hardware.org/?probe=9cc44f0705) | Feb 26, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | [746ddfc621](https://linux-hardware.org/?probe=746ddfc621) | Feb 09, 2022 |
| Gigabyte      | EP45-DS3L                   | [294d18eb2b](https://linux-hardware.org/?probe=294d18eb2b) | Jan 30, 2022 |
| ASUSTek       | F1A55-M LX PLUS             | [706b5f2fab](https://linux-hardware.org/?probe=706b5f2fab) | Jan 27, 2022 |
| Unknown       | G41 Series                  | [28502ce22e](https://linux-hardware.org/?probe=28502ce22e) | Jan 27, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c7f152495b](https://linux-hardware.org/?probe=c7f152495b) | Jan 21, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [6d015ef040](https://linux-hardware.org/?probe=6d015ef040) | Jan 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [010543afde](https://linux-hardware.org/?probe=010543afde) | Jan 13, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [a355e13859](https://linux-hardware.org/?probe=a355e13859) | Jan 11, 2022 |
| ASUSTek       | V-P7H55E                    | [7fc2d44a4a](https://linux-hardware.org/?probe=7fc2d44a4a) | Jan 11, 2022 |
| Gigabyte      | G41M-ES2L                   | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| MSI           | Z270 GAMING PLUS            | [bd96b37321](https://linux-hardware.org/?probe=bd96b37321) | Jan 07, 2022 |
| HP            | 3397                        | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [cbb5305dc7](https://linux-hardware.org/?probe=cbb5305dc7) | Dec 30, 2021 |
| ASUSTek       | PRIME X370-PRO              | [a810f7c0fb](https://linux-hardware.org/?probe=a810f7c0fb) | Dec 28, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [aad21a9d66](https://linux-hardware.org/?probe=aad21a9d66) | Dec 21, 2021 |
| Supermicro    | X10SDV-6C-TLN4F             | [07aa1e6365](https://linux-hardware.org/?probe=07aa1e6365) | Dec 17, 2021 |
| ASUSTek       | Pro Q570M-C                 | [d868c52b5a](https://linux-hardware.org/?probe=d868c52b5a) | Dec 15, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [fe889c0a84](https://linux-hardware.org/?probe=fe889c0a84) | Dec 15, 2021 |
| Unknown       | G41 Series                  | [45a2524e2b](https://linux-hardware.org/?probe=45a2524e2b) | Dec 11, 2021 |
| Gigabyte      | EP45-DS3L                   | [8354035770](https://linux-hardware.org/?probe=8354035770) | Dec 11, 2021 |
| Unknown       | G41 Series                  | [77c738bc15](https://linux-hardware.org/?probe=77c738bc15) | Dec 09, 2021 |
| Unknown       | G41 Series                  | [8f861614bc](https://linux-hardware.org/?probe=8f861614bc) | Dec 06, 2021 |
| Unknown       | G41 Series                  | [e9846d4aa5](https://linux-hardware.org/?probe=e9846d4aa5) | Dec 05, 2021 |
| Gigabyte      | H97N-WIFI                   | [646eb8cd7d](https://linux-hardware.org/?probe=646eb8cd7d) | Dec 04, 2021 |
| ASRock        | X570 Steel Legend           | [e5e357405c](https://linux-hardware.org/?probe=e5e357405c) | Nov 29, 2021 |
| Dell          | 0KC9NP A01                  | [cdc7bbd885](https://linux-hardware.org/?probe=cdc7bbd885) | Nov 29, 2021 |
| ASUSTek       | P5QL PRO                    | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| HP            | 8717                        | [a00d17d8c4](https://linux-hardware.org/?probe=a00d17d8c4) | Nov 25, 2021 |
| Dell          | 02K9CR A01                  | [36c6a137fb](https://linux-hardware.org/?probe=36c6a137fb) | Nov 23, 2021 |
| Gigabyte      | B360HD3                     | [71a92047fb](https://linux-hardware.org/?probe=71a92047fb) | Nov 23, 2021 |
| Dell          | 0C2KJT A00                  | [b4fb255866](https://linux-hardware.org/?probe=b4fb255866) | Nov 23, 2021 |
| Gigabyte      | F2A55M-DS2                  | [c40447abe8](https://linux-hardware.org/?probe=c40447abe8) | Nov 20, 2021 |
| Dell          | 02K9CR A01                  | [7d558b813e](https://linux-hardware.org/?probe=7d558b813e) | Nov 17, 2021 |
| MSI           | A88X-G43                    | [c546efdb47](https://linux-hardware.org/?probe=c546efdb47) | Nov 16, 2021 |
| MSI           | A88X-G43                    | [3cb4a9134c](https://linux-hardware.org/?probe=3cb4a9134c) | Nov 16, 2021 |
| HP            | 0A9Ch                       | [7fef9e130e](https://linux-hardware.org/?probe=7fef9e130e) | Nov 13, 2021 |
| Dell          | 04YP6J A02                  | [6c41e1551e](https://linux-hardware.org/?probe=6c41e1551e) | Nov 09, 2021 |
| Dell          | 04YP6J A02                  | [736e182a15](https://linux-hardware.org/?probe=736e182a15) | Nov 09, 2021 |
| Dell          | 0R038D A00                  | [6b0833e390](https://linux-hardware.org/?probe=6b0833e390) | Nov 05, 2021 |
| HP            | 0A9Ch                       | [e3e06f5858](https://linux-hardware.org/?probe=e3e06f5858) | Nov 04, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [4e1b94d5c2](https://linux-hardware.org/?probe=4e1b94d5c2) | Nov 03, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [97ece593e1](https://linux-hardware.org/?probe=97ece593e1) | Nov 01, 2021 |
| ASRock        | Z77 Extreme4                | [bf66e1d281](https://linux-hardware.org/?probe=bf66e1d281) | Oct 29, 2021 |
| eMachines     | EMCP73VT-PM                 | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| eMachines     | EMCP73VT-PM                 | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| Gigabyte      | 970-GAMING                  | [9a9b258736](https://linux-hardware.org/?probe=9a9b258736) | Oct 22, 2021 |
| Gigabyte      | EP45-DS3L                   | [b4a30d2562](https://linux-hardware.org/?probe=b4a30d2562) | Oct 22, 2021 |
| Gigabyte      | 970-GAMING                  | [264e021ecb](https://linux-hardware.org/?probe=264e021ecb) | Oct 22, 2021 |
| ASRock        | Z77 Extreme4                | [862513b9f6](https://linux-hardware.org/?probe=862513b9f6) | Oct 21, 2021 |
| ASUSTek       | KGPE-D16                    | [b5d2358b76](https://linux-hardware.org/?probe=b5d2358b76) | Oct 21, 2021 |
| Dell          | 0GTK4K A02                  | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| ASUSTek       | P5BV-M/RS100-E5             | [13134022df](https://linux-hardware.org/?probe=13134022df) | Oct 19, 2021 |
| ASRock        | Z77 Extreme4                | [53b29edc51](https://linux-hardware.org/?probe=53b29edc51) | Oct 14, 2021 |
| ASRock        | Z77 Extreme4                | [0d69ee2560](https://linux-hardware.org/?probe=0d69ee2560) | Oct 10, 2021 |
| Huanan        | X79                         | [3532bbed3d](https://linux-hardware.org/?probe=3532bbed3d) | Oct 08, 2021 |
| Huanan        | X79                         | [6638a35363](https://linux-hardware.org/?probe=6638a35363) | Oct 08, 2021 |
| Gigabyte      | 970-GAMING                  | [9a4c250f63](https://linux-hardware.org/?probe=9a4c250f63) | Oct 06, 2021 |
| MSI           | FM2-A55M-E33                | [2ff5df695f](https://linux-hardware.org/?probe=2ff5df695f) | Oct 05, 2021 |
| MSI           | FM2-A55M-E33                | [f6ff6eebb3](https://linux-hardware.org/?probe=f6ff6eebb3) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | [21d49c2826](https://linux-hardware.org/?probe=21d49c2826) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | [cb940b924d](https://linux-hardware.org/?probe=cb940b924d) | Sep 30, 2021 |
| HP            | 0AACh                       | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [1c1bca9399](https://linux-hardware.org/?probe=1c1bca9399) | Sep 28, 2021 |
| Unknown       | Unknown                     | [7baf2629b9](https://linux-hardware.org/?probe=7baf2629b9) | Sep 26, 2021 |
| ASRock        | Z77 Extreme4                | [b603b360a4](https://linux-hardware.org/?probe=b603b360a4) | Sep 25, 2021 |
| Dell          | 0FM586                      | [5ec44ec202](https://linux-hardware.org/?probe=5ec44ec202) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [b04783b7e1](https://linux-hardware.org/?probe=b04783b7e1) | Sep 20, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [976ca14e35](https://linux-hardware.org/?probe=976ca14e35) | Sep 19, 2021 |
| ASRock        | Z77 Extreme4                | [36129a77bf](https://linux-hardware.org/?probe=36129a77bf) | Sep 18, 2021 |
| ASRock        | Z77 Extreme4                | [b59cb8f7f5](https://linux-hardware.org/?probe=b59cb8f7f5) | Sep 17, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [4720c56d37](https://linux-hardware.org/?probe=4720c56d37) | Sep 15, 2021 |
| Dell          | 0Y7WYT A00                  | [e4278d3243](https://linux-hardware.org/?probe=e4278d3243) | Sep 15, 2021 |
| HP            | 8750                        | [b5bbf3502f](https://linux-hardware.org/?probe=b5bbf3502f) | Sep 08, 2021 |
| ASRock        | Z77 Extreme4                | [5cda73f744](https://linux-hardware.org/?probe=5cda73f744) | Sep 05, 2021 |
| Intel         | DH55TC AAE70932-302         | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [5d701efa3e](https://linux-hardware.org/?probe=5d701efa3e) | Sep 03, 2021 |
| ASRock        | Z77 Extreme4                | [f754b0f478](https://linux-hardware.org/?probe=f754b0f478) | Sep 03, 2021 |
| ASUSTek       | P5L8L-SE                    | [32e39bbd4f](https://linux-hardware.org/?probe=32e39bbd4f) | Sep 02, 2021 |
| MSI           | MAG B550M MORTAR            | [5ae94fc78a](https://linux-hardware.org/?probe=5ae94fc78a) | Aug 28, 2021 |
| Supermicro    | X8SAX                       | [3795e4ab95](https://linux-hardware.org/?probe=3795e4ab95) | Aug 28, 2021 |
| Gigabyte      | B85M-D3PH                   | [01d87985dd](https://linux-hardware.org/?probe=01d87985dd) | Aug 28, 2021 |
| Gigabyte      | H97N-WIFI                   | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| HP            | 8751                        | [cdaf5a0ed8](https://linux-hardware.org/?probe=cdaf5a0ed8) | Aug 24, 2021 |
| Gigabyte      | Z170MX-Gaming 5             | [461d550db6](https://linux-hardware.org/?probe=461d550db6) | Aug 19, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| HP            | 2B3C                        | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | [cabe0be4fc](https://linux-hardware.org/?probe=cabe0be4fc) | Aug 17, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [3501d4479e](https://linux-hardware.org/?probe=3501d4479e) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | [cf348cec5f](https://linux-hardware.org/?probe=cf348cec5f) | Aug 16, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [0cecab8e81](https://linux-hardware.org/?probe=0cecab8e81) | Aug 11, 2021 |
| ASRock        | A320M-HD                    | [d1e968eadd](https://linux-hardware.org/?probe=d1e968eadd) | Aug 11, 2021 |
| ASRock        | A320M-HD                    | [13bd66cba7](https://linux-hardware.org/?probe=13bd66cba7) | Aug 11, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [92336b575c](https://linux-hardware.org/?probe=92336b575c) | Aug 10, 2021 |
| ASRock        | A320M-HD                    | [775b415921](https://linux-hardware.org/?probe=775b415921) | Aug 08, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [8ddb489f03](https://linux-hardware.org/?probe=8ddb489f03) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [d19976dabe](https://linux-hardware.org/?probe=d19976dabe) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [d56fdac07b](https://linux-hardware.org/?probe=d56fdac07b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [3eb59a276c](https://linux-hardware.org/?probe=3eb59a276c) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [3d0db6b81f](https://linux-hardware.org/?probe=3d0db6b81f) | Aug 05, 2021 |
| Dell          | 0YNVJG A01                  | [7952948421](https://linux-hardware.org/?probe=7952948421) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [1fc2375e54](https://linux-hardware.org/?probe=1fc2375e54) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [9a5d8276bf](https://linux-hardware.org/?probe=9a5d8276bf) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [a653e9beb2](https://linux-hardware.org/?probe=a653e9beb2) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [2165980dd3](https://linux-hardware.org/?probe=2165980dd3) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [4a2adade2a](https://linux-hardware.org/?probe=4a2adade2a) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [78c5e3532b](https://linux-hardware.org/?probe=78c5e3532b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [10bdaec1ef](https://linux-hardware.org/?probe=10bdaec1ef) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | [80244f2809](https://linux-hardware.org/?probe=80244f2809) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [70fc6a65ef](https://linux-hardware.org/?probe=70fc6a65ef) | Aug 05, 2021 |
| HP            | 8591                        | [6794bdb00e](https://linux-hardware.org/?probe=6794bdb00e) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | [f209feb9c8](https://linux-hardware.org/?probe=f209feb9c8) | Aug 05, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [40b8d28af0](https://linux-hardware.org/?probe=40b8d28af0) | Aug 04, 2021 |
| ASRock        | A320M-HD                    | [d68ac72e1d](https://linux-hardware.org/?probe=d68ac72e1d) | Aug 03, 2021 |
| Gigabyte      | EP45-DS3L                   | [597de4e10b](https://linux-hardware.org/?probe=597de4e10b) | Aug 01, 2021 |
| HP            | 0AECh D                     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| Gigabyte      | H57M-USB3                   | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| MSI           | MAG B550M MORTAR            | [59a63323ed](https://linux-hardware.org/?probe=59a63323ed) | Jul 23, 2021 |
| ASUSTek       | SABERTOOTH X79              | [1232705d62](https://linux-hardware.org/?probe=1232705d62) | Jul 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ec0e7ce341](https://linux-hardware.org/?probe=ec0e7ce341) | Jul 19, 2021 |
| MSI           | B460M-A PRO                 | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| MSI           | MAG B550M MORTAR            | [4ac62bb08e](https://linux-hardware.org/?probe=4ac62bb08e) | Jul 13, 2021 |
| ASRock        | A320M-HD                    | [ff76aecb8e](https://linux-hardware.org/?probe=ff76aecb8e) | Jul 12, 2021 |
| HP            | 2B34                        | [0de82dabad](https://linux-hardware.org/?probe=0de82dabad) | Jul 10, 2021 |
| HP            | 0A9Ch                       | [e3159a6511](https://linux-hardware.org/?probe=e3159a6511) | Jul 07, 2021 |
| Dell          | 09KPNV A01                  | [a3f3f1e1c0](https://linux-hardware.org/?probe=a3f3f1e1c0) | Jul 02, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [f4606d038d](https://linux-hardware.org/?probe=f4606d038d) | Jun 29, 2021 |
| Gigabyte      | EP45-DS3L                   | [6beb9f6867](https://linux-hardware.org/?probe=6beb9f6867) | Jun 19, 2021 |
| ASRock        | A320M-HD                    | [e09e4e329c](https://linux-hardware.org/?probe=e09e4e329c) | Jun 14, 2021 |
| HP            | 1494                        | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| Dell          | 0M5DCD A00                  | [00ce09b473](https://linux-hardware.org/?probe=00ce09b473) | May 31, 2021 |
| Intel         | E98683-353                  | [2f0ae62282](https://linux-hardware.org/?probe=2f0ae62282) | May 29, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [de14f99534](https://linux-hardware.org/?probe=de14f99534) | May 24, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [8ecaed3eb2](https://linux-hardware.org/?probe=8ecaed3eb2) | May 24, 2021 |
| HP            | 1589                        | [a4b0ebbee2](https://linux-hardware.org/?probe=a4b0ebbee2) | May 23, 2021 |
| Dell          | 0200DY A02                  | [340184fb36](https://linux-hardware.org/?probe=340184fb36) | May 23, 2021 |
| ASRock        | J3710M                      | [6f289497fc](https://linux-hardware.org/?probe=6f289497fc) | May 23, 2021 |
| HP            | 18E7                        | [3045530e64](https://linux-hardware.org/?probe=3045530e64) | May 17, 2021 |
| HP            | 8594                        | [991250b6a8](https://linux-hardware.org/?probe=991250b6a8) | May 14, 2021 |
| HP            | 1825                        | [13110a2081](https://linux-hardware.org/?probe=13110a2081) | May 14, 2021 |
| MSI           | MAG B550M MORTAR            | [640c5adfc3](https://linux-hardware.org/?probe=640c5adfc3) | May 10, 2021 |
| Gigabyte      | EP45-DS3L                   | [33c13bfcf0](https://linux-hardware.org/?probe=33c13bfcf0) | May 01, 2021 |
| ASUSTek       | PRIME X570-PRO              | [88b8ca6dbe](https://linux-hardware.org/?probe=88b8ca6dbe) | Apr 30, 2021 |
| ASUSTek       | PRIME X570-PRO              | [be1a846088](https://linux-hardware.org/?probe=be1a846088) | Apr 30, 2021 |
| HP            | 8591                        | [149576417f](https://linux-hardware.org/?probe=149576417f) | Apr 27, 2021 |
| HP            | 8591                        | [03b17d692d](https://linux-hardware.org/?probe=03b17d692d) | Apr 26, 2021 |
| HP            | 213D A01                    | [72e7e27309](https://linux-hardware.org/?probe=72e7e27309) | Apr 26, 2021 |
| ASUSTek       | Z97-E/USB                   | [8524f8f381](https://linux-hardware.org/?probe=8524f8f381) | Apr 16, 2021 |
| Gigabyte      | EP43-DS3                    | [3eaab1a9d9](https://linux-hardware.org/?probe=3eaab1a9d9) | Apr 05, 2021 |
| HP            | 8591                        | [d3dd8e0a2b](https://linux-hardware.org/?probe=d3dd8e0a2b) | Apr 02, 2021 |
| ASUSTek       | Z97-E/USB                   | [561d33760f](https://linux-hardware.org/?probe=561d33760f) | Mar 31, 2021 |
| Dell          | 0MWYPT A02                  | [e2e2e6f179](https://linux-hardware.org/?probe=e2e2e6f179) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| Unknown       | Unknown                     | [b672c68361](https://linux-hardware.org/?probe=b672c68361) | Mar 30, 2021 |
| HP            | 8591                        | [3c4d055665](https://linux-hardware.org/?probe=3c4d055665) | Mar 30, 2021 |
| HP            | 8591                        | [b436577a94](https://linux-hardware.org/?probe=b436577a94) | Mar 30, 2021 |
| ASRock        | X570 Steel Legend           | [f8b36f6373](https://linux-hardware.org/?probe=f8b36f6373) | Mar 29, 2021 |
| ASRock        | X570 Steel Legend           | [60fa73286f](https://linux-hardware.org/?probe=60fa73286f) | Mar 29, 2021 |
| Gigabyte      | Z490 GAMING X               | [f37546f14b](https://linux-hardware.org/?probe=f37546f14b) | Mar 26, 2021 |
| Dell          | 0XHGV1 A00                  | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| Lenovo        | MAHOBAY                     | [3bce30311a](https://linux-hardware.org/?probe=3bce30311a) | Mar 23, 2021 |
| Gigabyte      | EP45-DS3L                   | [c724df2a1a](https://linux-hardware.org/?probe=c724df2a1a) | Mar 23, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | [c46179b0b2](https://linux-hardware.org/?probe=c46179b0b2) | Mar 22, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | [0473f156a3](https://linux-hardware.org/?probe=0473f156a3) | Mar 22, 2021 |
| ASUSTek       | PRIME X370-PRO              | [ccdc5f822c](https://linux-hardware.org/?probe=ccdc5f822c) | Mar 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9fdca2136a](https://linux-hardware.org/?probe=9fdca2136a) | Mar 19, 2021 |
| MiTAC         | PD10BI PD10BI-702           | [63335e1b88](https://linux-hardware.org/?probe=63335e1b88) | Mar 18, 2021 |
| MiTAC         | PD10BI PD10BI-702           | [5d23375dcd](https://linux-hardware.org/?probe=5d23375dcd) | Mar 18, 2021 |
| Unknown       | Unknown                     | [234c991949](https://linux-hardware.org/?probe=234c991949) | Mar 17, 2021 |
| MSI           | H170A GAMING PRO            | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| Dell          | 0NC2VH A01                  | [cc8791aaa6](https://linux-hardware.org/?probe=cc8791aaa6) | Mar 17, 2021 |
| ASUSTek       | PRIME A320M-R               | [adac87af3d](https://linux-hardware.org/?probe=adac87af3d) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [0190551f1e](https://linux-hardware.org/?probe=0190551f1e) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [1184f695c1](https://linux-hardware.org/?probe=1184f695c1) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [b5658ed87e](https://linux-hardware.org/?probe=b5658ed87e) | Mar 12, 2021 |
| ASUSTek       | Z97-E/USB                   | [b979ba17d1](https://linux-hardware.org/?probe=b979ba17d1) | Mar 07, 2021 |
| ASUSTek       | Z97-E/USB                   | [47a56b26e5](https://linux-hardware.org/?probe=47a56b26e5) | Mar 07, 2021 |
| Gigabyte      | EP45-DS3L                   | [6663605d82](https://linux-hardware.org/?probe=6663605d82) | Feb 27, 2021 |
| Gigabyte      | B75M-D3H                    | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| AMI           | PCHK-Z83 Poslab_ECO         | [5dd25822e3](https://linux-hardware.org/?probe=5dd25822e3) | Feb 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | [1314989a9a](https://linux-hardware.org/?probe=1314989a9a) | Feb 21, 2021 |
| Dell          | 0WR7PY A01                  | [ad06439414](https://linux-hardware.org/?probe=ad06439414) | Feb 19, 2021 |
| Gigabyte      | D525TUD                     | [59b1050f5f](https://linux-hardware.org/?probe=59b1050f5f) | Feb 19, 2021 |
| Supermicro    | X9SCI/X9SCA                 | [28940aaa42](https://linux-hardware.org/?probe=28940aaa42) | Feb 16, 2021 |
| Dell          | 07T4MC A06                  | [ae053aa0ed](https://linux-hardware.org/?probe=ae053aa0ed) | Feb 15, 2021 |
| ASUSTek       | Z97-E/USB                   | [0cf9401181](https://linux-hardware.org/?probe=0cf9401181) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-D               | [aab84fafeb](https://linux-hardware.org/?probe=aab84fafeb) | Feb 10, 2021 |
| Gigabyte      | MZBSWMP-00                  | [754ea78372](https://linux-hardware.org/?probe=754ea78372) | Feb 09, 2021 |
| Gigabyte      | MZBSWMP-00                  | [5e6e46d3b1](https://linux-hardware.org/?probe=5e6e46d3b1) | Feb 09, 2021 |
| Gigabyte      | H77N-WIFI                   | [8469853bc1](https://linux-hardware.org/?probe=8469853bc1) | Feb 08, 2021 |
| Gigabyte      | H77N-WIFI                   | [7b44703f86](https://linux-hardware.org/?probe=7b44703f86) | Feb 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | [9fc9b672d0](https://linux-hardware.org/?probe=9fc9b672d0) | Feb 07, 2021 |
| HP            | 3397                        | [aba05551cb](https://linux-hardware.org/?probe=aba05551cb) | Feb 05, 2021 |
| ASUSTek       | Z97-E/USB                   | [494eafb565](https://linux-hardware.org/?probe=494eafb565) | Feb 03, 2021 |
| ASUSTek       | Z97-E/USB                   | [59f3594f3d](https://linux-hardware.org/?probe=59f3594f3d) | Jan 28, 2021 |
| ASUSTek       | Z97-E/USB                   | [17fef649e3](https://linux-hardware.org/?probe=17fef649e3) | Jan 25, 2021 |
| ASRock        | X570 Steel Legend           | [59145ca9e6](https://linux-hardware.org/?probe=59145ca9e6) | Jan 24, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [996727413b](https://linux-hardware.org/?probe=996727413b) | Jan 17, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [20c1a73c0e](https://linux-hardware.org/?probe=20c1a73c0e) | Jan 14, 2021 |
| ASUSTek       | GD30CI                      | [201c54f6b8](https://linux-hardware.org/?probe=201c54f6b8) | Jan 12, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [d798d76c9a](https://linux-hardware.org/?probe=d798d76c9a) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [6de78c3913](https://linux-hardware.org/?probe=6de78c3913) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [e2cd4bfc82](https://linux-hardware.org/?probe=e2cd4bfc82) | Jan 11, 2021 |
| Dell          | 0HHV7N A00                  | [7b55587c5a](https://linux-hardware.org/?probe=7b55587c5a) | Jan 10, 2021 |
| MSI           | H97 GAMING 3                | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| ASUSTek       | GD30CI                      | [4f2d51ec4b](https://linux-hardware.org/?probe=4f2d51ec4b) | Jan 09, 2021 |
| ASRock        | X570 Steel Legend           | [6371149c87](https://linux-hardware.org/?probe=6371149c87) | Jan 08, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| HP            | 806A                        | [f02a4a5e93](https://linux-hardware.org/?probe=f02a4a5e93) | Jan 05, 2021 |
| ASRock        | X570 Steel Legend           | [dcd24f778c](https://linux-hardware.org/?probe=dcd24f778c) | Jan 03, 2021 |
| Gigabyte      | D525TUD                     | [e9f1445d02](https://linux-hardware.org/?probe=e9f1445d02) | Jan 03, 2021 |
| HP            | ProLiant MicroServer        | [edbd95264a](https://linux-hardware.org/?probe=edbd95264a) | Jan 02, 2021 |
| ASRock        | X570 Steel Legend           | [16fc91341e](https://linux-hardware.org/?probe=16fc91341e) | Dec 31, 2020 |
| ASRock        | X570 Steel Legend           | [91ed18105e](https://linux-hardware.org/?probe=91ed18105e) | Dec 31, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [34a96782e3](https://linux-hardware.org/?probe=34a96782e3) | Dec 28, 2020 |
| ASRock        | X570 Steel Legend           | [384c4a8068](https://linux-hardware.org/?probe=384c4a8068) | Dec 27, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ac785c27e5](https://linux-hardware.org/?probe=ac785c27e5) | Dec 27, 2020 |
| Dell          | 0VD5HY A00                  | [470703f4af](https://linux-hardware.org/?probe=470703f4af) | Dec 27, 2020 |
| Intel         | DQ67OW AAG12528-309         | [5f42b365ae](https://linux-hardware.org/?probe=5f42b365ae) | Dec 26, 2020 |
| ASRock        | X570 Steel Legend           | [c96512d726](https://linux-hardware.org/?probe=c96512d726) | Dec 25, 2020 |
| Gigabyte      | EP45-DS3L                   | [aad57f82cd](https://linux-hardware.org/?probe=aad57f82cd) | Dec 24, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [2b7bb243da](https://linux-hardware.org/?probe=2b7bb243da) | Dec 23, 2020 |
| ASUSTek       | X99-DELUXE                  | [46613a5ce9](https://linux-hardware.org/?probe=46613a5ce9) | Dec 20, 2020 |
| Gigabyte      | Z370 AORUS Gaming WIFI-C... | [5438d83866](https://linux-hardware.org/?probe=5438d83866) | Dec 14, 2020 |
| Gigabyte      | Z77-D3H                     | [b7c033babd](https://linux-hardware.org/?probe=b7c033babd) | Dec 10, 2020 |
| Gigabyte      | D525TUD                     | [0c13d73ba0](https://linux-hardware.org/?probe=0c13d73ba0) | Nov 27, 2020 |
| ASUSTek       | Z170-A                      | [b4e9865791](https://linux-hardware.org/?probe=b4e9865791) | Nov 25, 2020 |
| ASUSTek       | H87M-PLUS                   | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bc3bd4ea10](https://linux-hardware.org/?probe=bc3bd4ea10) | Nov 24, 2020 |
| ASRock        | Z390M-ITX/ac                | [3d5c6b679d](https://linux-hardware.org/?probe=3d5c6b679d) | Nov 22, 2020 |
| ASRock        | Z390M-ITX/ac                | [b3f3cd1511](https://linux-hardware.org/?probe=b3f3cd1511) | Nov 22, 2020 |
| HP            | 81C9                        | [ea900ff5b1](https://linux-hardware.org/?probe=ea900ff5b1) | Nov 19, 2020 |
| Rockwell A... | 6177R A1                    | [a12a2989fd](https://linux-hardware.org/?probe=a12a2989fd) | Nov 16, 2020 |
| ASUSTek       | PRIME X370-PRO              | [70fc4e5649](https://linux-hardware.org/?probe=70fc4e5649) | Nov 16, 2020 |
| HP            | 1587h                       | [4b1f2221ee](https://linux-hardware.org/?probe=4b1f2221ee) | Nov 16, 2020 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| HP            | 1495                        | [931bc038c8](https://linux-hardware.org/?probe=931bc038c8) | Nov 07, 2020 |
| HP            | 1495                        | [a2c50ab08e](https://linux-hardware.org/?probe=a2c50ab08e) | Nov 07, 2020 |
| Supermicro    | X8SIL                       | [10b7c06f49](https://linux-hardware.org/?probe=10b7c06f49) | Nov 02, 2020 |
| Supermicro    | X8SIL                       | [e40055e7ca](https://linux-hardware.org/?probe=e40055e7ca) | Nov 01, 2020 |
| ASRock        | G31M-S                      | [1741a29fd6](https://linux-hardware.org/?probe=1741a29fd6) | Nov 01, 2020 |
| ASRock        | G31M-S                      | [e579695cc9](https://linux-hardware.org/?probe=e579695cc9) | Nov 01, 2020 |
| ASUSTek       | PRIME X570-P                | [4e9d94747a](https://linux-hardware.org/?probe=4e9d94747a) | Oct 30, 2020 |
| Supermicro    | X8SIL                       | [ff3a4a93df](https://linux-hardware.org/?probe=ff3a4a93df) | Oct 28, 2020 |
| Supermicro    | X8SIL                       | [c6d306f861](https://linux-hardware.org/?probe=c6d306f861) | Oct 27, 2020 |
| MSI           | A320M PRO-VD/S V2           | [56d1218104](https://linux-hardware.org/?probe=56d1218104) | Oct 25, 2020 |
| ASUSTek       | Z170-A                      | [e5b6274c3e](https://linux-hardware.org/?probe=e5b6274c3e) | Oct 22, 2020 |
| ASUSTek       | P9X79                       | [e0a6bc45ee](https://linux-hardware.org/?probe=e0a6bc45ee) | Oct 17, 2020 |
| ASUSTek       | P9X79                       | [d14403a73b](https://linux-hardware.org/?probe=d14403a73b) | Oct 17, 2020 |
| HP            | 1495                        | [a678a5caf0](https://linux-hardware.org/?probe=a678a5caf0) | Oct 13, 2020 |
| Dell          | 01NP3N A00                  | [1f5b92d91b](https://linux-hardware.org/?probe=1f5b92d91b) | Oct 12, 2020 |
| ASRock        | X99 Taichi                  | [fabde85a5a](https://linux-hardware.org/?probe=fabde85a5a) | Oct 11, 2020 |
| ASUSTek       | F2A55-M LE                  | [1fc864e04c](https://linux-hardware.org/?probe=1fc864e04c) | Oct 10, 2020 |
| MSI           | B450I GAMING PLUS AC        | [ff2176937d](https://linux-hardware.org/?probe=ff2176937d) | Oct 03, 2020 |
| ASUSTek       | Berkeley                    | [8ead41d349](https://linux-hardware.org/?probe=8ead41d349) | Sep 28, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [29fdcb6b00](https://linux-hardware.org/?probe=29fdcb6b00) | Sep 28, 2020 |
| ECS           | H61H2-MV                    | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| Gigabyte      | A320M-S2H-CF                | [bcf59e135b](https://linux-hardware.org/?probe=bcf59e135b) | Sep 19, 2020 |
| Gigabyte      | A320M-S2H-CF                | [43d38ed1be](https://linux-hardware.org/?probe=43d38ed1be) | Sep 19, 2020 |
| HP            | 0AECh D                     | [d80079cb33](https://linux-hardware.org/?probe=d80079cb33) | Sep 18, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [b363aea94a](https://linux-hardware.org/?probe=b363aea94a) | Sep 17, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [1896a5c345](https://linux-hardware.org/?probe=1896a5c345) | Sep 17, 2020 |
| Intel         | DH61WW AAG23116-204         | [5788667247](https://linux-hardware.org/?probe=5788667247) | Sep 12, 2020 |
| AEWIN         | SCB-1711A                   | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| HP            | 8053                        | [b00f600647](https://linux-hardware.org/?probe=b00f600647) | Sep 09, 2020 |
| Intel         | D54250WYK H13922-303        | [219e110c70](https://linux-hardware.org/?probe=219e110c70) | Sep 03, 2020 |
| Zenith        | Orion                       | [9de5e32b25](https://linux-hardware.org/?probe=9de5e32b25) | Sep 02, 2020 |
| Gigabyte      | EP45-DS3L                   | [599830e150](https://linux-hardware.org/?probe=599830e150) | Aug 29, 2020 |
| HP            | 0B54h D                     | [b39f47faf8](https://linux-hardware.org/?probe=b39f47faf8) | Aug 26, 2020 |
| ASUSTek       | P7P55D                      | [4a55c3588b](https://linux-hardware.org/?probe=4a55c3588b) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | [81f3fe5ce0](https://linux-hardware.org/?probe=81f3fe5ce0) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | [09fb692364](https://linux-hardware.org/?probe=09fb692364) | Aug 26, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [1c28fb67ab](https://linux-hardware.org/?probe=1c28fb67ab) | Aug 20, 2020 |
| ASUSTek       | Z97-E/USB                   | [2377cf4d5e](https://linux-hardware.org/?probe=2377cf4d5e) | Aug 19, 2020 |
| ASUSTek       | Z97-E/USB                   | [2da17db4c1](https://linux-hardware.org/?probe=2da17db4c1) | Aug 19, 2020 |
| Gigabyte      | B450 AORUS M                | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [eeaeff9e52](https://linux-hardware.org/?probe=eeaeff9e52) | Aug 12, 2020 |
| Lenovo        | ThinkServer TS140           | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| MSI           | B350M PRO-VDH               | [301fe36ff7](https://linux-hardware.org/?probe=301fe36ff7) | Aug 06, 2020 |
| Gigabyte      | A320M-S2H-CF                | [cbcae43afd](https://linux-hardware.org/?probe=cbcae43afd) | Aug 02, 2020 |
| Dell          | 08HPGT A02                  | [fa6826d636](https://linux-hardware.org/?probe=fa6826d636) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | [d9b3b9a12e](https://linux-hardware.org/?probe=d9b3b9a12e) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | [3a33cfc73c](https://linux-hardware.org/?probe=3a33cfc73c) | Aug 02, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Gigabyte      | A320M-S2H-CF                | [08325f77c1](https://linux-hardware.org/?probe=08325f77c1) | Aug 01, 2020 |
| Gigabyte      | H97-HD3                     | [06c68b698e](https://linux-hardware.org/?probe=06c68b698e) | Jul 24, 2020 |
| Gigabyte      | B360M DS3H                  | [be78e318ef](https://linux-hardware.org/?probe=be78e318ef) | Jul 23, 2020 |
| HP            | 0AECh D                     | [c6310b9606](https://linux-hardware.org/?probe=c6310b9606) | Jul 14, 2020 |
| ASUSTek       | Z97-E/USB                   | [f6f4d985ea](https://linux-hardware.org/?probe=f6f4d985ea) | Jul 13, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [2244646450](https://linux-hardware.org/?probe=2244646450) | Jul 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [80c07a542a](https://linux-hardware.org/?probe=80c07a542a) | Jul 11, 2020 |
| HP            | 1589                        | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| Dell          | 0YXT71 A02                  | [0d249e4d90](https://linux-hardware.org/?probe=0d249e4d90) | Jul 08, 2020 |
| ASRockRack    | EP2C612 WS                  | [4392ed1437](https://linux-hardware.org/?probe=4392ed1437) | Jul 08, 2020 |
| Dell          | 073MMW A00                  | [115d71c055](https://linux-hardware.org/?probe=115d71c055) | Jul 06, 2020 |
| Intel         | H81C                        | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| Gigabyte      | EP45-DS3R                   | [cfad3da667](https://linux-hardware.org/?probe=cfad3da667) | Jul 03, 2020 |
| ASUSTek       | SABERTOOTH X99              | [d014e3ba24](https://linux-hardware.org/?probe=d014e3ba24) | Jul 03, 2020 |
| Unknown       | IPM31-AK                    | [acd334c9b0](https://linux-hardware.org/?probe=acd334c9b0) | Jun 28, 2020 |
| Gigabyte      | P85-D3                      | [3be565ccfd](https://linux-hardware.org/?probe=3be565ccfd) | Jun 23, 2020 |
| ASUSTek       | P8Z77-V                     | [f94256b581](https://linux-hardware.org/?probe=f94256b581) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [f9990a3c91](https://linux-hardware.org/?probe=f9990a3c91) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [6d4908178c](https://linux-hardware.org/?probe=6d4908178c) | Jun 22, 2020 |
| ASUSTek       | Crosshair IV Formula        | [51b8e4300b](https://linux-hardware.org/?probe=51b8e4300b) | Jun 20, 2020 |
| ASUSTek       | Crosshair IV Formula        | [e1184552d0](https://linux-hardware.org/?probe=e1184552d0) | Jun 20, 2020 |
| ASRock        | Z170 Extreme7+              | [56fa210d0c](https://linux-hardware.org/?probe=56fa210d0c) | Jun 20, 2020 |
| ASRock        | Z170 Extreme7+              | [b2d975c2e7](https://linux-hardware.org/?probe=b2d975c2e7) | Jun 20, 2020 |
| MSI           | 2A9C                        | [9af3bb0a4e](https://linux-hardware.org/?probe=9af3bb0a4e) | Jun 17, 2020 |
| Packard Be... | MCP73VT-PM                  | [8cba2e7fa8](https://linux-hardware.org/?probe=8cba2e7fa8) | Jun 14, 2020 |
| Packard Be... | MCP73VT-PM                  | [26f700fbc5](https://linux-hardware.org/?probe=26f700fbc5) | Jun 14, 2020 |
| Supermicro    | X10DRG-H                    | [3bd676846b](https://linux-hardware.org/?probe=3bd676846b) | Jun 12, 2020 |
| ASRock        | X399 Professional Gaming    | [d313005743](https://linux-hardware.org/?probe=d313005743) | Jun 10, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9020f6e51c](https://linux-hardware.org/?probe=9020f6e51c) | Jun 07, 2020 |
| MSI           | B450M MORTAR MAX            | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [edbd2a746d](https://linux-hardware.org/?probe=edbd2a746d) | Jun 06, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [0436cc9607](https://linux-hardware.org/?probe=0436cc9607) | Jun 03, 2020 |
| Intel         | DP45SG AAE27733-405         | [f195015cf8](https://linux-hardware.org/?probe=f195015cf8) | Jun 02, 2020 |
| Dell          | 0VRWRC A00                  | [dd7e20baec](https://linux-hardware.org/?probe=dd7e20baec) | May 29, 2020 |
| Dell          | 0VRWRC A00                  | [c27987482d](https://linux-hardware.org/?probe=c27987482d) | May 29, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [6d648c7448](https://linux-hardware.org/?probe=6d648c7448) | May 27, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [22c1a49189](https://linux-hardware.org/?probe=22c1a49189) | May 27, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [d4cbe90b0f](https://linux-hardware.org/?probe=d4cbe90b0f) | May 27, 2020 |
| Dell          | 0YXT71 A02                  | [e3f86df812](https://linux-hardware.org/?probe=e3f86df812) | May 25, 2020 |
| ASRock        | AM1B-ITX                    | [d0b6f8f474](https://linux-hardware.org/?probe=d0b6f8f474) | May 25, 2020 |
| Supermicro    | X10DAI                      | [c2d45e8975](https://linux-hardware.org/?probe=c2d45e8975) | May 21, 2020 |
| Gigabyte      | Z68P-DS3                    | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [3f253aecbb](https://linux-hardware.org/?probe=3f253aecbb) | May 15, 2020 |
| ASUSTek       | CM1740                      | [65921c1a5e](https://linux-hardware.org/?probe=65921c1a5e) | May 14, 2020 |
| Lenovo        | MAHOBAY                     | [3ad583ff3d](https://linux-hardware.org/?probe=3ad583ff3d) | May 14, 2020 |
| Gigabyte      | EP45-DS3L                   | [6a3f0afa07](https://linux-hardware.org/?probe=6a3f0afa07) | May 07, 2020 |
| HP            | 1495                        | [a38478daa1](https://linux-hardware.org/?probe=a38478daa1) | May 05, 2020 |
| HP            | 1495                        | [c3d3f31b83](https://linux-hardware.org/?probe=c3d3f31b83) | May 05, 2020 |
| HP            | 1495                        | [6fed1750c3](https://linux-hardware.org/?probe=6fed1750c3) | May 05, 2020 |
| Foxconn       | 17A0                        | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| Supermicro    | X10SDE-DF                   | [54cbea6bb1](https://linux-hardware.org/?probe=54cbea6bb1) | Apr 26, 2020 |
| Supermicro    | X10SDE-DF                   | [3c55fe3c77](https://linux-hardware.org/?probe=3c55fe3c77) | Apr 26, 2020 |
| Biostar       | A320MH                      | [bc6b5804c2](https://linux-hardware.org/?probe=bc6b5804c2) | Apr 24, 2020 |
| Foxconn       | 2A8C                        | [64941f8ea2](https://linux-hardware.org/?probe=64941f8ea2) | Apr 21, 2020 |
| ASRockRack    | EP2C612 WS                  | [22419b4efe](https://linux-hardware.org/?probe=22419b4efe) | Apr 20, 2020 |
| Dell          | 0C3YXR A01                  | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [cfed23f08f](https://linux-hardware.org/?probe=cfed23f08f) | Apr 18, 2020 |
| ASUSTek       | Rampage V EXTREME           | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| Dell          | 0YXT71 A02                  | [f454033e1f](https://linux-hardware.org/?probe=f454033e1f) | Apr 13, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | [17ba5a84d9](https://linux-hardware.org/?probe=17ba5a84d9) | Apr 12, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c670b78e38](https://linux-hardware.org/?probe=c670b78e38) | Apr 11, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [5d17d05d00](https://linux-hardware.org/?probe=5d17d05d00) | Apr 11, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [bb9f29477a](https://linux-hardware.org/?probe=bb9f29477a) | Apr 07, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [95a4ea12d4](https://linux-hardware.org/?probe=95a4ea12d4) | Apr 05, 2020 |
| Unknown       | LakePort                    | [85bfbe1e35](https://linux-hardware.org/?probe=85bfbe1e35) | Apr 02, 2020 |
| Gigabyte      | EP45-DS3L                   | [942f7d3c3c](https://linux-hardware.org/?probe=942f7d3c3c) | Apr 01, 2020 |
| Gigabyte      | EP45-DS3L                   | [fc9be427f5](https://linux-hardware.org/?probe=fc9be427f5) | Apr 01, 2020 |
| ASUSTek       | PRIME A320M-K               | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASRock        | X399 Professional Gaming    | [efe1215f69](https://linux-hardware.org/?probe=efe1215f69) | Mar 19, 2020 |
| Gigabyte      | EP45-DS3L                   | [c20d28a563](https://linux-hardware.org/?probe=c20d28a563) | Mar 15, 2020 |
| Gigabyte      | EP45-DS3L                   | [3086c3b9f5](https://linux-hardware.org/?probe=3086c3b9f5) | Mar 15, 2020 |
| HP            | 843F                        | [f76a18754d](https://linux-hardware.org/?probe=f76a18754d) | Mar 12, 2020 |
| Gigabyte      | EP45-DS3L                   | [1345dd63eb](https://linux-hardware.org/?probe=1345dd63eb) | Mar 11, 2020 |
| Dell          | 040DDP A01                  | [1e1a7753ca](https://linux-hardware.org/?probe=1e1a7753ca) | Mar 10, 2020 |
| Gigabyte      | EP45-DS3L                   | [6fc52e234a](https://linux-hardware.org/?probe=6fc52e234a) | Mar 09, 2020 |
| Gigabyte      | EP45-DS3L                   | [add6bd96c8](https://linux-hardware.org/?probe=add6bd96c8) | Mar 09, 2020 |
| Gigabyte      | EP45-DS3L                   | [906db6cad1](https://linux-hardware.org/?probe=906db6cad1) | Mar 09, 2020 |
| Gigabyte      | EX58-EXTREME                | [29d31a8603](https://linux-hardware.org/?probe=29d31a8603) | Mar 08, 2020 |
| Dell          | 0X8DXD A01                  | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Gigabyte      | Z170X-UD3-CF                | [ed0506aa18](https://linux-hardware.org/?probe=ed0506aa18) | Feb 25, 2020 |
| Gigabyte      | EX58-EXTREME                | [d2b19a4a0f](https://linux-hardware.org/?probe=d2b19a4a0f) | Feb 24, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [54d3d863ad](https://linux-hardware.org/?probe=54d3d863ad) | Feb 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [72895d5cc3](https://linux-hardware.org/?probe=72895d5cc3) | Feb 23, 2020 |
| Gigabyte      | EX58-EXTREME                | [2ce62d5ef2](https://linux-hardware.org/?probe=2ce62d5ef2) | Feb 23, 2020 |
| Supermicro    | X10DAI                      | [8bb87102a9](https://linux-hardware.org/?probe=8bb87102a9) | Feb 20, 2020 |
| Foxconn       | 2ABF                        | [d45674e336](https://linux-hardware.org/?probe=d45674e336) | Feb 06, 2020 |
| ASUSTek       | H87M-PLUS                   | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| ASUSTek       | AT4NM10T-I                  | [a0fa3c7ca0](https://linux-hardware.org/?probe=a0fa3c7ca0) | Jan 28, 2020 |
| Gigabyte      | Z77X-UD5H                   | [2c5e967e3a](https://linux-hardware.org/?probe=2c5e967e3a) | Jan 25, 2020 |
| HP            | 18E4                        | [f6f6dfd341](https://linux-hardware.org/?probe=f6f6dfd341) | Jan 25, 2020 |
| MSI           | H77MA-G43                   | [5a0c6d2f14](https://linux-hardware.org/?probe=5a0c6d2f14) | Jan 24, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [917bf2b4cf](https://linux-hardware.org/?probe=917bf2b4cf) | Jan 24, 2020 |
| Dell          | 0C27VV A01                  | [01545ea8b0](https://linux-hardware.org/?probe=01545ea8b0) | Jan 24, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [9d92e8ed9d](https://linux-hardware.org/?probe=9d92e8ed9d) | Jan 24, 2020 |
| Dell          | 0M5DCD A00                  | [21e230fb02](https://linux-hardware.org/?probe=21e230fb02) | Jan 24, 2020 |
| Gigabyte      | Z77N-WIFI                   | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Foxconn       | 2AA9                        | [2b2a941903](https://linux-hardware.org/?probe=2b2a941903) | Jan 07, 2020 |
| Foxconn       | 2AA9                        | [ed7e0428fb](https://linux-hardware.org/?probe=ed7e0428fb) | Jan 07, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [3c407e606c](https://linux-hardware.org/?probe=3c407e606c) | Dec 31, 2019 |
| Gigabyte      | EP45-DS4                    | [13acec4985](https://linux-hardware.org/?probe=13acec4985) | Dec 25, 2019 |
| ASUSTek       | PRIME Z390-P                | [0b771c098e](https://linux-hardware.org/?probe=0b771c098e) | Dec 20, 2019 |
| HP            | 0A98h                       | [e68759aa8e](https://linux-hardware.org/?probe=e68759aa8e) | Dec 12, 2019 |
| MSI           | H55M-E33                    | [48d4121155](https://linux-hardware.org/?probe=48d4121155) | Dec 10, 2019 |
| ASRock        | X79 Extreme11               | [1b28cc994f](https://linux-hardware.org/?probe=1b28cc994f) | Dec 07, 2019 |
| Dell          | 0PC5F7 A01                  | [ba442e31fa](https://linux-hardware.org/?probe=ba442e31fa) | Nov 24, 2019 |
| ASUSTek       | Benicia                     | [5d4f2621ec](https://linux-hardware.org/?probe=5d4f2621ec) | Nov 22, 2019 |
| Dell          | 09KPNV A01                  | [0c44bfb480](https://linux-hardware.org/?probe=0c44bfb480) | Nov 22, 2019 |
| Dell          | 0XR1GT A00                  | [76dba7bb94](https://linux-hardware.org/?probe=76dba7bb94) | Nov 22, 2019 |
| HP            | ProLiant MicroServer        | [fdfa4ab709](https://linux-hardware.org/?probe=fdfa4ab709) | Nov 14, 2019 |
| Dell          | 07T4MC A06                  | [8fba67a719](https://linux-hardware.org/?probe=8fba67a719) | Nov 14, 2019 |
| Lenovo        | MAHOBAY                     | [652157e27c](https://linux-hardware.org/?probe=652157e27c) | Nov 03, 2019 |
| Lenovo        | MAHOBAY                     | [fd672567d1](https://linux-hardware.org/?probe=fd672567d1) | Nov 03, 2019 |
| Gigabyte      | B150M-D3H-CF                | [0c5c6bd0d1](https://linux-hardware.org/?probe=0c5c6bd0d1) | Oct 31, 2019 |
| ASUSTek       | Benicia                     | [764ecc00c4](https://linux-hardware.org/?probe=764ecc00c4) | Oct 30, 2019 |
| ASUSTek       | Benicia                     | [c604466168](https://linux-hardware.org/?probe=c604466168) | Oct 26, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [17d03076df](https://linux-hardware.org/?probe=17d03076df) | Oct 16, 2019 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [11a89e3f6f](https://linux-hardware.org/?probe=11a89e3f6f) | Oct 13, 2019 |
| ECS           | H55H-M                      | [970477516c](https://linux-hardware.org/?probe=970477516c) | Oct 12, 2019 |
| ECS           | H55H-M                      | [dab03eeec5](https://linux-hardware.org/?probe=dab03eeec5) | Oct 12, 2019 |
| ASUSTek       | P8H67-M                     | [a3522aac75](https://linux-hardware.org/?probe=a3522aac75) | Oct 09, 2019 |
| ASUSTek       | P8H67-M                     | [1c6a686559](https://linux-hardware.org/?probe=1c6a686559) | Oct 08, 2019 |
| ASUSTek       | P8H67-M                     | [8c40634de7](https://linux-hardware.org/?probe=8c40634de7) | Oct 08, 2019 |
| Supermicro    | X7DVL                       | [e4951bb84b](https://linux-hardware.org/?probe=e4951bb84b) | Oct 05, 2019 |
| Gigabyte      | X58A-UD5                    | [c1cd5017a5](https://linux-hardware.org/?probe=c1cd5017a5) | Oct 05, 2019 |
| Gigabyte      | B360HD3PLM-CF               | [05d00cc5d7](https://linux-hardware.org/?probe=05d00cc5d7) | Sep 09, 2019 |
| Gigabyte      | 970A-D3P                    | [6e3666d8c9](https://linux-hardware.org/?probe=6e3666d8c9) | Sep 04, 2019 |
| AMI           | Cherry Trail CR             | [fe652a02c9](https://linux-hardware.org/?probe=fe652a02c9) | Jul 25, 2019 |
| Dell          | 09KPNV A00                  | [a72c60b73b](https://linux-hardware.org/?probe=a72c60b73b) | Jul 24, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [b2fac79afd](https://linux-hardware.org/?probe=b2fac79afd) | Jun 27, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [44eb4c1fed](https://linux-hardware.org/?probe=44eb4c1fed) | Jun 25, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [4bb11d6dc0](https://linux-hardware.org/?probe=4bb11d6dc0) | Jun 07, 2019 |
| ASRockRack    | E3C242D4U2-2T               | [3fb7cc0574](https://linux-hardware.org/?probe=3fb7cc0574) | Jun 07, 2019 |
| AAEON         | MF-001 V1.0                 | [19f89f5d4e](https://linux-hardware.org/?probe=19f89f5d4e) | Jun 05, 2019 |
| HP            | 8054                        | [8409fbc1c6](https://linux-hardware.org/?probe=8409fbc1c6) | May 28, 2019 |
| Intel         | SHARKBAY                    | [8418bef88a](https://linux-hardware.org/?probe=8418bef88a) | May 15, 2019 |
| ASUSTek       | P5G41T-M LX                 | [16ecb5a13f](https://linux-hardware.org/?probe=16ecb5a13f) | Apr 19, 2019 |
| Intel         | SHARKBAY                    | [58607accae](https://linux-hardware.org/?probe=58607accae) | Apr 08, 2019 |
| Intel         | SHARKBAY                    | [d8c89a633e](https://linux-hardware.org/?probe=d8c89a633e) | Apr 08, 2019 |
| Intel         | SHARKBAY                    | [5e5b4e25a0](https://linux-hardware.org/?probe=5e5b4e25a0) | Apr 08, 2019 |
| ASUSTek       | F1A75-M LE                  | [f8301ffe57](https://linux-hardware.org/?probe=f8301ffe57) | Mar 26, 2019 |
| ASRock        | Z87 Extreme6                | [96aaa39135](https://linux-hardware.org/?probe=96aaa39135) | Mar 18, 2019 |
| HP            | 81C5 MVB                    | [46ea2e591e](https://linux-hardware.org/?probe=46ea2e591e) | Mar 18, 2019 |
| MSI           | X299 RAIDER                 | [f06f57dde9](https://linux-hardware.org/?probe=f06f57dde9) | Mar 07, 2019 |
| Lenovo        | 4030                        | [10455104fd](https://linux-hardware.org/?probe=10455104fd) | Mar 01, 2019 |
| Gigabyte      | 970A-DS3P                   | [9c8b01fc94](https://linux-hardware.org/?probe=9c8b01fc94) | Dec 22, 2018 |
| Gigabyte      | 970A-DS3P                   | [3b0d00f6c9](https://linux-hardware.org/?probe=3b0d00f6c9) | Dec 22, 2018 |
| Dell          | 0CD6TV A01                  | [7f702ee88f](https://linux-hardware.org/?probe=7f702ee88f) | Oct 29, 2018 |
| Dell          | 0CD6TV A01                  | [46e3d4f4d9](https://linux-hardware.org/?probe=46e3d4f4d9) | Oct 29, 2018 |
| TYAN Compu... | S5512                       | [67bfe1b221](https://linux-hardware.org/?probe=67bfe1b221) | Jun 30, 2018 |
| ASRock        | H77 Pro4/MVP                | [a5918b30a1](https://linux-hardware.org/?probe=a5918b30a1) | May 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| CentOS 8      | 146      | 50.87%  |
| CentOS 7      | 132      | 45.99%  |
| CentOS 6      | 6        | 2.09%   |
| CentOS Stream | 2        | 0.7%    |
| CentOS 9      | 1        | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| CentOS | 285      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-147.8.1.el8_1.x86_64  | 13       | 3.98%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 12       | 3.67%   |
| 4.18.0-193.14.2.el8_2.x86_64 | 12       | 3.67%   |
| 3.10.0-1160.31.1.el7.x86_64  | 12       | 3.67%   |
| 3.10.0-1160.25.1.el7.x86_64  | 10       | 3.06%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 9        | 2.75%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 9        | 2.75%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 9        | 2.75%   |
| 3.10.0-1160.45.1.el7.x86_64  | 8        | 2.45%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 7        | 2.14%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 7        | 2.14%   |
| 3.10.0-1160.15.2.el7.x86_64  | 7        | 2.14%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 6        | 1.83%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 6        | 1.83%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 6        | 1.83%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 6        | 1.83%   |
| 3.10.0-1062.12.1.el7.x86_64  | 6        | 1.83%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 5        | 1.53%   |
| 3.10.0-957.10.1.el7.x86_64   | 5        | 1.53%   |
| 3.10.0-1160.6.1.el7.x86_64   | 5        | 1.53%   |
| 3.10.0-1160.59.1.el7.x86_64  | 5        | 1.53%   |
| 3.10.0-1160.36.2.el7.x86_64  | 5        | 1.53%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 4        | 1.22%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 4        | 1.22%   |
| 4.18.0-301.1.el8.x86_64      | 4        | 1.22%   |
| 4.18.0-147.el8.x86_64        | 4        | 1.22%   |
| 3.10.0-957.27.2.el7.x86_64   | 4        | 1.22%   |
| 3.10.0-1127.el7.x86_64       | 4        | 1.22%   |
| 3.10.0-1127.19.1.el7.x86_64  | 4        | 1.22%   |
| 4.18.0-315.el8.x86_64        | 3        | 0.92%   |
| 3.10.0-957.5.1.el7.x86_64    | 3        | 0.92%   |
| 3.10.0-957.1.3.el7.x86_64    | 3        | 0.92%   |
| 3.10.0-1160.49.1.el7.x86_64  | 3        | 0.92%   |
| 3.10.0-1160.21.1.el7.x86_64  | 3        | 0.92%   |
| 3.10.0-1160.11.1.el7.x86_64  | 3        | 0.92%   |
| 3.10.0-1127.13.1.el7.x86_64  | 3        | 0.92%   |
| 3.10.0-1062.el7.x86_64       | 3        | 0.92%   |
| 3.10.0-1062.9.1.el7.x86_64   | 3        | 0.92%   |
| 3.10.0-1062.18.1.el7.x86_64  | 3        | 0.92%   |
| 4.18.0-80.el8.x86_64         | 2        | 0.61%   |
| 4.18.0-358.el8.x86_64        | 2        | 0.61%   |
| 4.18.0-338.el8.x86_64        | 2        | 0.61%   |
| 4.18.0-326.el8.x86_64        | 2        | 0.61%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 2        | 0.61%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 0.61%   |
| 4.18.0-305.0.1.el8.x86_64    | 2        | 0.61%   |
| 4.18.0-294.el8.x86_64        | 2        | 0.61%   |
| 4.18.0-277.el8.x86_64        | 2        | 0.61%   |
| 4.18.0-257.el8.x86_64        | 2        | 0.61%   |
| 4.18.0-240.el8.x86_64        | 2        | 0.61%   |
| 4.18.0-193.10.el8.x86_64     | 2        | 0.61%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 2        | 0.61%   |
| 3.10.0-957.el7.x86_64        | 2        | 0.61%   |
| 3.10.0-957.12.2.el7.x86_64   | 2        | 0.61%   |
| 3.10.0-693.21.1.el7.x86_64   | 2        | 0.61%   |
| 3.10.0-1160.el7.x86_64       | 2        | 0.61%   |
| 3.10.0-1160.53.1.el7.x86_64  | 2        | 0.61%   |
| 3.10.0-1160.24.1.el7.x86_64  | 2        | 0.61%   |
| 3.10.0-1127.10.1.el7.x86_64  | 2        | 0.61%   |
| 3.10.0-1062.4.1.el7.x86_64   | 2        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 144      | 50.17%  |
| 3.10.0  | 116      | 40.42%  |
| 2.6.32  | 6        | 2.09%   |
| 5.8.0   | 1        | 0.35%   |
| 5.7.7   | 1        | 0.35%   |
| 5.7.10  | 1        | 0.35%   |
| 5.6.10  | 1        | 0.35%   |
| 5.5.0   | 1        | 0.35%   |
| 5.4.96  | 1        | 0.35%   |
| 5.4.188 | 1        | 0.35%   |
| 5.4.142 | 1        | 0.35%   |
| 5.4.119 | 1        | 0.35%   |
| 5.4.118 | 1        | 0.35%   |
| 5.4.113 | 1        | 0.35%   |
| 5.3.11  | 1        | 0.35%   |
| 5.17.2  | 1        | 0.35%   |
| 5.13.11 | 1        | 0.35%   |
| 5.10.3  | 1        | 0.35%   |
| 5.1.19  | 1        | 0.35%   |
| 4.9.188 | 1        | 0.35%   |
| 4.9.182 | 1        | 0.35%   |
| 4.9.180 | 1        | 0.35%   |
| 4.9.179 | 1        | 0.35%   |
| 4.20.4  | 1        | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 144      | 50.17%  |
| 3.10    | 116      | 40.42%  |
| 5.4     | 6        | 2.09%   |
| 2.6     | 6        | 2.09%   |
| 4.9     | 4        | 1.39%   |
| 5.7     | 2        | 0.7%    |
| 5.8     | 1        | 0.35%   |
| 5.6     | 1        | 0.35%   |
| 5.5     | 1        | 0.35%   |
| 5.3     | 1        | 0.35%   |
| 5.17    | 1        | 0.35%   |
| 5.13    | 1        | 0.35%   |
| 5.10    | 1        | 0.35%   |
| 5.1     | 1        | 0.35%   |
| 4.20    | 1        | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 283      | 99.3%   |
| i686   | 2        | 0.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 159      | 55.02%  |
| Unknown       | 79       | 27.34%  |
| GNOME Classic | 22       | 7.61%   |
| KDE4          | 14       | 4.84%   |
| XFCE          | 5        | 1.73%   |
| MATE          | 4        | 1.38%   |
| KDE5          | 3        | 1.04%   |
| Cinnamon      | 2        | 0.69%   |
| Xpra          | 1        | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 175      | 59.73%  |
| Wayland | 71       | 24.23%  |
| Unknown | 46       | 15.7%   |
| Web     | 1        | 0.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 165      | 57.29%  |
| GDM     | 116      | 40.28%  |
| LightDM | 5        | 1.74%   |
| SDDM    | 1        | 0.35%   |
| KDM     | 1        | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 139      | 47.77%  |
| Unknown     | 48       | 16.49%  |
| C           | 16       | 5.5%    |
| en_GB       | 13       | 4.47%   |
| de_DE       | 9        | 3.09%   |
| ru_RU       | 8        | 2.75%   |
| en_CA       | 7        | 2.41%   |
| pt_BR       | 6        | 2.06%   |
| pl_PL       | 6        | 2.06%   |
| en_AU       | 6        | 2.06%   |
| fr_FR       | 5        | 1.72%   |
| en_IN       | 4        | 1.37%   |
| de_AT       | 3        | 1.03%   |
| zh_CN       | 2        | 0.69%   |
| ko_KR       | 2        | 0.69%   |
| fr_CA       | 2        | 0.69%   |
| es_PE       | 2        | 0.69%   |
| en_US.utf-8 | 2        | 0.69%   |
| uk_UA       | 1        | 0.34%   |
| tr_TR       | 1        | 0.34%   |
| sl_SI       | 1        | 0.34%   |
| it_IT       | 1        | 0.34%   |
| hu_HU       | 1        | 0.34%   |
| fi_FI       | 1        | 0.34%   |
| es_US       | 1        | 0.34%   |
| en_SG       | 1        | 0.34%   |
| de_LU       | 1        | 0.34%   |
| de_CH       | 1        | 0.34%   |
| cs_CZ       | 1        | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 153      | 53.5%   |
| EFI  | 133      | 46.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 228      | 79.44%  |
| Ext4 | 58       | 20.21%  |
| Ext3 | 1        | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 115      | 39.66%  |
| Unknown | 110      | 37.93%  |
| MBR     | 65       | 22.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 253      | 88.46%  |
| Yes       | 33       | 11.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 255      | 89.16%  |
| Yes       | 31       | 10.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 61       | 21.4%   |
| Gigabyte Technology | 52       | 18.25%  |
| Dell                | 51       | 17.89%  |
| Hewlett-Packard     | 35       | 12.28%  |
| MSI                 | 18       | 6.32%   |
| ASRock              | 12       | 4.21%   |
| Supermicro          | 9        | 3.16%   |
| Intel               | 9        | 3.16%   |
| Unknown             | 6        | 2.11%   |
| Lenovo              | 4        | 1.4%    |
| Fujitsu             | 4        | 1.4%    |
| Foxconn             | 4        | 1.4%    |
| ASRockRack          | 4        | 1.4%    |
| MiTAC               | 2        | 0.7%    |
| ECS                 | 2        | 0.7%    |
| AMI                 | 2        | 0.7%    |
| Zenith              | 1        | 0.35%   |
| TYAN Computer       | 1        | 0.35%   |
| Packard Bell        | 1        | 0.35%   |
| Huanan              | 1        | 0.35%   |
| eMachines           | 1        | 0.35%   |
| Cisco Systems       | 1        | 0.35%   |
| Biostar             | 1        | 0.35%   |
| Apple               | 1        | 0.35%   |
| AEWIN               | 1        | 0.35%   |
| AAEON               | 1        | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Dell OptiPlex 9020                 | 9        | 3.16%   |
| Dell OptiPlex 7040                 | 8        | 2.81%   |
| ASUS All Series                    | 6        | 2.11%   |
| Unknown                            | 6        | 2.11%   |
| HP Z800 Workstation                | 3        | 1.05%   |
| HP Compaq 8200 Elite SFF PC        | 3        | 1.05%   |
| Dell Precision WorkStation T3500   | 3        | 1.05%   |
| Dell OptiPlex 7010                 | 3        | 1.05%   |
| ASRockRack E3C242D4U2-2T           | 3        | 1.05%   |
| Supermicro SYS-7048A-T             | 2        | 0.7%    |
| HP Z420 Workstation                | 2        | 0.7%    |
| HP Z2 Tower G5 Workstation         | 2        | 0.7%    |
| HP ProLiant MicroServer            | 2        | 0.7%    |
| HP Compaq Elite 8300 SFF           | 2        | 0.7%    |
| Gigabyte X470 AORUS ULTRA GAMING   | 2        | 0.7%    |
| Gigabyte H97N-WIFI                 | 2        | 0.7%    |
| Gigabyte A320M-S2H                 | 2        | 0.7%    |
| Fujitsu D3401-H1                   | 2        | 0.7%    |
| Dell PowerEdge T40                 | 2        | 0.7%    |
| Dell OptiPlex 780                  | 2        | 0.7%    |
| Dell OptiPlex 390                  | 2        | 0.7%    |
| Dell OptiPlex 3020                 | 2        | 0.7%    |
| ASUS TUF B450M-PRO GAMING          | 2        | 0.7%    |
| ASUS PRIME X570-PRO                | 2        | 0.7%    |
| ASUS PRIME X570-P                  | 2        | 0.7%    |
| ASUS PRIME X370-PRO                | 2        | 0.7%    |
| ASUS M5A99FX PRO R2.0              | 2        | 0.7%    |
| ASUS M5A78L-M/USB3                 | 2        | 0.7%    |
| ASRock X399 Professional Gaming    | 2        | 0.7%    |
| Zenith Orion                       | 1        | 0.35%   |
| TYAN S5512                         | 1        | 0.35%   |
| Supermicro X9SCI/X9SCA             | 1        | 0.35%   |
| Supermicro X8SIL                   | 1        | 0.35%   |
| Supermicro X8SAX                   | 1        | 0.35%   |
| Supermicro X7DVL                   | 1        | 0.35%   |
| Supermicro SYS-E200-8D             | 1        | 0.35%   |
| Supermicro SYS-5038MD-H24TRF-OS012 | 1        | 0.35%   |
| Supermicro SYS-1028GR-TR           | 1        | 0.35%   |
| Packard Bell IMEDIA D3610 FR       | 1        | 0.35%   |
| MSI MS-7C94                        | 1        | 0.35%   |
| MSI MS-7C88                        | 1        | 0.35%   |
| MSI MS-7C84                        | 1        | 0.35%   |
| MSI MS-7C83                        | 1        | 0.35%   |
| MSI MS-7C37                        | 1        | 0.35%   |
| MSI MS-7C02                        | 1        | 0.35%   |
| MSI MS-7B89                        | 1        | 0.35%   |
| MSI MS-7A94                        | 1        | 0.35%   |
| MSI MS-7A75                        | 1        | 0.35%   |
| MSI MS-7A40                        | 1        | 0.35%   |
| MSI MS-7A38                        | 1        | 0.35%   |
| MSI MS-7A36                        | 1        | 0.35%   |
| MSI MS-7978                        | 1        | 0.35%   |
| MSI MS-7918                        | 1        | 0.35%   |
| MSI MS-7793                        | 1        | 0.35%   |
| MSI MS-7756                        | 1        | 0.35%   |
| MSI MS-7636                        | 1        | 0.35%   |
| MSI HPE-421f                       | 1        | 0.35%   |
| MiTAC UltraPoint                   | 1        | 0.35%   |
| MiTAC PD10BI                       | 1        | 0.35%   |
| Lenovo ThinkCentre M92p 3238AZ8    | 1        | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Dell OptiPlex                      | 30       | 10.53%  |
| ASUS PRIME                         | 12       | 4.21%   |
| Dell Precision                     | 11       | 3.86%   |
| HP Compaq                          | 7        | 2.46%   |
| ASUS All                           | 6        | 2.11%   |
| Unknown                            | 6        | 2.11%   |
| HP EliteDesk                       | 5        | 1.75%   |
| ASUS TUF                           | 5        | 1.75%   |
| ASUS ROG                           | 5        | 1.75%   |
| Dell PowerEdge                     | 4        | 1.4%    |
| Dell Inspiron                      | 4        | 1.4%    |
| HP Z800                            | 3        | 1.05%   |
| HP ProDesk                         | 3        | 1.05%   |
| ASUS M5A78L-M                      | 3        | 1.05%   |
| ASRockRack E3C242D4U2-2T           | 3        | 1.05%   |
| Supermicro SYS-7048A-T             | 2        | 0.7%    |
| HP Z420                            | 2        | 0.7%    |
| HP Z2                              | 2        | 0.7%    |
| HP ProLiant                        | 2        | 0.7%    |
| Gigabyte Z370                      | 2        | 0.7%    |
| Gigabyte X570                      | 2        | 0.7%    |
| Gigabyte X470                      | 2        | 0.7%    |
| Gigabyte H97N-WIFI                 | 2        | 0.7%    |
| Gigabyte GA-78LMT-USB3             | 2        | 0.7%    |
| Gigabyte B360                      | 2        | 0.7%    |
| Gigabyte A320M-S2H                 | 2        | 0.7%    |
| Fujitsu D3401-H1                   | 2        | 0.7%    |
| Foxconn Pro                        | 2        | 0.7%    |
| Dell Vostro                        | 2        | 0.7%    |
| ASUS Pro                           | 2        | 0.7%    |
| ASUS P8Z77-V                       | 2        | 0.7%    |
| ASUS M5A99FX                       | 2        | 0.7%    |
| ASRock X399                        | 2        | 0.7%    |
| Zenith Orion                       | 1        | 0.35%   |
| TYAN S5512                         | 1        | 0.35%   |
| Supermicro X9SCI                   | 1        | 0.35%   |
| Supermicro X8SIL                   | 1        | 0.35%   |
| Supermicro X8SAX                   | 1        | 0.35%   |
| Supermicro X7DVL                   | 1        | 0.35%   |
| Supermicro SYS-E200-8D             | 1        | 0.35%   |
| Supermicro SYS-5038MD-H24TRF-OS012 | 1        | 0.35%   |
| Supermicro SYS-1028GR-TR           | 1        | 0.35%   |
| Packard Bell IMEDIA                | 1        | 0.35%   |
| MSI MS-7C94                        | 1        | 0.35%   |
| MSI MS-7C88                        | 1        | 0.35%   |
| MSI MS-7C84                        | 1        | 0.35%   |
| MSI MS-7C83                        | 1        | 0.35%   |
| MSI MS-7C37                        | 1        | 0.35%   |
| MSI MS-7C02                        | 1        | 0.35%   |
| MSI MS-7B89                        | 1        | 0.35%   |
| MSI MS-7A94                        | 1        | 0.35%   |
| MSI MS-7A75                        | 1        | 0.35%   |
| MSI MS-7A40                        | 1        | 0.35%   |
| MSI MS-7A38                        | 1        | 0.35%   |
| MSI MS-7A36                        | 1        | 0.35%   |
| MSI MS-7978                        | 1        | 0.35%   |
| MSI MS-7918                        | 1        | 0.35%   |
| MSI MS-7793                        | 1        | 0.35%   |
| MSI MS-7756                        | 1        | 0.35%   |
| MSI MS-7636                        | 1        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 31       | 10.88%  |
| 2012    | 31       | 10.88%  |
| 2018    | 30       | 10.53%  |
| 2014    | 24       | 8.42%   |
| 2013    | 24       | 8.42%   |
| 2016    | 22       | 7.72%   |
| 2017    | 20       | 7.02%   |
| 2011    | 20       | 7.02%   |
| 2010    | 20       | 7.02%   |
| 2015    | 15       | 5.26%   |
| 2020    | 14       | 4.91%   |
| 2008    | 12       | 4.21%   |
| 2009    | 10       | 3.51%   |
| 2021    | 6        | 2.11%   |
| 2007    | 5        | 1.75%   |
| Unknown | 1        | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 285      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 281      | 98.6%   |
| Enabled  | 4        | 1.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 284      | 99.65%  |
| Yes  | 1        | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 64       | 22.3%   |
| 32.01-64.0      | 57       | 19.86%  |
| 16.01-24.0      | 57       | 19.86%  |
| 64.01-256.0     | 30       | 10.45%  |
| 3.01-4.0        | 29       | 10.1%   |
| 8.01-16.0       | 29       | 10.1%   |
| 1.01-2.0        | 10       | 3.48%   |
| 24.01-32.0      | 7        | 2.44%   |
| More than 256.0 | 2        | 0.7%    |
| 2.01-3.0        | 2        | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 63       | 20.32%  |
| 1.01-2.0   | 60       | 19.35%  |
| 4.01-8.0   | 52       | 16.77%  |
| 3.01-4.0   | 47       | 15.16%  |
| 0.51-1.0   | 33       | 10.65%  |
| 8.01-16.0  | 29       | 9.35%   |
| 0.01-0.5   | 11       | 3.55%   |
| 16.01-24.0 | 6        | 1.94%   |
| Unknown    | 6        | 1.94%   |
| 24.01-32.0 | 2        | 0.65%   |
| 32.01-64.0 | 1        | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 114      | 39.31%  |
| 2       | 65       | 22.41%  |
| 3       | 48       | 16.55%  |
| 4       | 21       | 7.24%   |
| 6       | 10       | 3.45%   |
| 5       | 9        | 3.1%    |
| 7       | 5        | 1.72%   |
| 19      | 2        | 0.69%   |
| 15      | 2        | 0.69%   |
| 10      | 2        | 0.69%   |
| 9       | 2        | 0.69%   |
| 8       | 2        | 0.69%   |
| 0       | 2        | 0.69%   |
| Unknown | 2        | 0.69%   |
| 71      | 1        | 0.34%   |
| 68      | 1        | 0.34%   |
| 13      | 1        | 0.34%   |
| 12      | 1        | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 166      | 58.04%  |
| Yes       | 120      | 41.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 284      | 99.65%  |
| No        | 1        | 0.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 213      | 74.22%  |
| Yes       | 74       | 25.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 220      | 77.19%  |
| Yes       | 65       | 22.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| USA                | 77       | 26.92%  |
| Germany            | 21       | 7.34%   |
| Russia             | 20       | 6.99%   |
| Canada             | 15       | 5.24%   |
| Brazil             | 15       | 5.24%   |
| India              | 14       | 4.9%    |
| UK                 | 12       | 4.2%    |
| France             | 10       | 3.5%    |
| Australia          | 8        | 2.8%    |
| Poland             | 7        | 2.45%   |
| Switzerland        | 5        | 1.75%   |
| Finland            | 5        | 1.75%   |
| Czechia            | 5        | 1.75%   |
| China              | 5        | 1.75%   |
| Ukraine            | 4        | 1.4%    |
| Sweden             | 4        | 1.4%    |
| South Korea        | 4        | 1.4%    |
| Belgium            | 4        | 1.4%    |
| Turkey             | 3        | 1.05%   |
| Romania            | 3        | 1.05%   |
| Netherlands        | 3        | 1.05%   |
| Hong Kong          | 3        | 1.05%   |
| Bulgaria           | 3        | 1.05%   |
| Taiwan             | 2        | 0.7%    |
| South Africa       | 2        | 0.7%    |
| Portugal           | 2        | 0.7%    |
| Peru               | 2        | 0.7%    |
| Norway             | 2        | 0.7%    |
| Italy              | 2        | 0.7%    |
| Indonesia          | 2        | 0.7%    |
| Thailand           | 1        | 0.35%   |
| Spain              | 1        | 0.35%   |
| Slovenia           | 1        | 0.35%   |
| Slovakia           | 1        | 0.35%   |
| Singapore          | 1        | 0.35%   |
| Serbia             | 1        | 0.35%   |
| Saudi Arabia       | 1        | 0.35%   |
| Pakistan           | 1        | 0.35%   |
| Mexico             | 1        | 0.35%   |
| Malaysia           | 1        | 0.35%   |
| Luxembourg         | 1        | 0.35%   |
| Lithuania          | 1        | 0.35%   |
| Japan              | 1        | 0.35%   |
| Israel             | 1        | 0.35%   |
| Iran               | 1        | 0.35%   |
| Hungary            | 1        | 0.35%   |
| Greece             | 1        | 0.35%   |
| Ecuador            | 1        | 0.35%   |
| Dominican Republic | 1        | 0.35%   |
| Colombia           | 1        | 0.35%   |
| Belarus            | 1        | 0.35%   |
| Bangladesh         | 1        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Rochester                   | 15       | 5.17%   |
| Moscow                      | 6        | 2.07%   |
| Sydney                      | 5        | 1.72%   |
| Alexandria                  | 5        | 1.72%   |
| London                      | 4        | 1.38%   |
| Frankfurt am Main           | 4        | 1.38%   |
| Brno                        | 4        | 1.38%   |
| Berlin                      | 4        | 1.38%   |
| Victoria                    | 3        | 1.03%   |
| St Petersburg               | 3        | 1.03%   |
| Sao Paulo                   | 3        | 1.03%   |
| Munich                      | 3        | 1.03%   |
| Montreal                    | 3        | 1.03%   |
| Istanbul                    | 3        | 1.03%   |
| Helsinki                    | 3        | 1.03%   |
| Central                     | 3        | 1.03%   |
| Waxhaw                      | 2        | 0.69%   |
| Warsaw                      | 2        | 0.69%   |
| Vancouver                   | 2        | 0.69%   |
| Tampa                       | 2        | 0.69%   |
| Sundbyberg                  | 2        | 0.69%   |
| Seattle                     | 2        | 0.69%   |
| Portland                    | 2        | 0.69%   |
| Paris                       | 2        | 0.69%   |
| New Taipei                  | 2        | 0.69%   |
| Mumbai                      | 2        | 0.69%   |
| Lima                        | 2        | 0.69%   |
| Kyiv                        | 2        | 0.69%   |
| Hyderabad                   | 2        | 0.69%   |
| Hornsby                     | 2        | 0.69%   |
| Gdansk                      | 2        | 0.69%   |
| Ernakulam                   | 2        | 0.69%   |
| Chicago                     | 2        | 0.69%   |
| Brandon                     | 2        | 0.69%   |
| Brampton                    | 2        | 0.69%   |
| Bengaluru                   | 2        | 0.69%   |
| Zaporizhzhia                | 1        | 0.34%   |
| Zapopan                     | 1        | 0.34%   |
| Yel'tsovka                  | 1        | 0.34%   |
| Yekaterinburg               | 1        | 0.34%   |
| Yangquan                    | 1        | 0.34%   |
| Wuxi                        | 1        | 0.34%   |
| WodzisÅ‚aw ÅšlÄ…ski | 1        | 0.34%   |
| Wheeling                    | 1        | 0.34%   |
| West Valley City            | 1        | 0.34%   |
| West Henrietta              | 1        | 0.34%   |
| West Bromwich               | 1        | 0.34%   |
| Wayne                       | 1        | 0.34%   |
| Vitebsk                     | 1        | 0.34%   |
| Villa Bisono                | 1        | 0.34%   |
| Vaugneray                   | 1        | 0.34%   |
| Valaparla                   | 1        | 0.34%   |
| Val-des-Monts               | 1        | 0.34%   |
| Untersiemau                 | 1        | 0.34%   |
| UniversitГЎrio            | 1        | 0.34%   |
| Tyumen                      | 1        | 0.34%   |
| Tuusula                     | 1        | 0.34%   |
| Tucson                      | 1        | 0.34%   |
| Tremembe                    | 1        | 0.34%   |
| Tours                       | 1        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 111      | 278    | 22.65%  |
| Seagate                   | 98       | 319    | 20%     |
| Samsung Electronics       | 72       | 179    | 14.69%  |
| Kingston                  | 35       | 41     | 7.14%   |
| Toshiba                   | 26       | 40     | 5.31%   |
| Hitachi                   | 22       | 32     | 4.49%   |
| SanDisk                   | 18       | 22     | 3.67%   |
| Intel                     | 14       | 36     | 2.86%   |
| HGST                      | 10       | 96     | 2.04%   |
| Unknown                   | 8        | 26     | 1.63%   |
| Crucial                   | 6        | 7      | 1.22%   |
| A-DATA Technology         | 6        | 8      | 1.22%   |
| SK Hynix                  | 5        | 5      | 1.02%   |
| Silicon Motion            | 5        | 5      | 1.02%   |
| SPCC                      | 3        | 3      | 0.61%   |
| Phison                    | 3        | 4      | 0.61%   |
| OCZ                       | 3        | 4      | 0.61%   |
| Micron/Crucial Technology | 3        | 4      | 0.61%   |
| Micron Technology         | 3        | 5      | 0.61%   |
| Hewlett-Packard           | 3        | 3      | 0.61%   |
| Gigabyte Technology       | 3        | 4      | 0.61%   |
| XPG                       | 2        | 2      | 0.41%   |
| PNY                       | 2        | 3      | 0.41%   |
| Apacer                    | 2        | 2      | 0.41%   |
| Verbatim                  | 1        | 1      | 0.2%    |
| V-GeN                     | 1        | 1      | 0.2%    |
| Transcend                 | 1        | 1      | 0.2%    |
| Team                      | 1        | 1      | 0.2%    |
| SUN                       | 1        | 3      | 0.2%    |
| SSSTC                     | 1        | 1      | 0.2%    |
| SATADOM-SL                | 1        | 1      | 0.2%    |
| ROG                       | 1        | 1      | 0.2%    |
| Realtek Semiconductor     | 1        | 1      | 0.2%    |
| PLEXTOR                   | 1        | 1      | 0.2%    |
| Patriot                   | 1        | 3      | 0.2%    |
| OWC                       | 1        | 1      | 0.2%    |
| NVMe                      | 1        | 1      | 0.2%    |
| MAXTOR                    | 1        | 1      | 0.2%    |
| LITEONIT                  | 1        | 1      | 0.2%    |
| Lexar                     | 1        | 1      | 0.2%    |
| Lenovo                    | 1        | 2      | 0.2%    |
| KIOXIA-EXCERIA            | 1        | 2      | 0.2%    |
| Kingston Technologies     | 1        | 1      | 0.2%    |
| KingSpec                  | 1        | 1      | 0.2%    |
| KingDian                  | 1        | 4      | 0.2%    |
| GLOWAY                    | 1        | 1      | 0.2%    |
| Dell                      | 1        | 1      | 0.2%    |
| Corsair                   | 1        | 1      | 0.2%    |
| China                     | 1        | 4      | 0.2%    |
| ASMT                      | 1        | 1      | 0.2%    |
| Apple                     | 1        | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 8        | 1.32%   |
| WDC WD20EARX-00PASB0 2TB            | 7        | 1.15%   |
| Toshiba DT01ACA100 1TB              | 7        | 1.15%   |
| Toshiba DT01ACA050 500GB            | 7        | 1.15%   |
| Seagate ST500DM002-1SB10A 500GB     | 7        | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB      | 6        | 0.99%   |
| Seagate ST1000DM003-1CH162 1TB      | 6        | 0.99%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5        | 0.82%   |
| Kingston SA400S37240G 240GB SSD     | 5        | 0.82%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 4        | 0.66%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 4        | 0.66%   |
| WDC WD20EZRX-00D8PB0 2TB            | 4        | 0.66%   |
| Seagate ST31000528AS 1TB            | 4        | 0.66%   |
| Seagate ST2000DM006-2DM164 2TB      | 4        | 0.66%   |
| Samsung SSD 860 EVO 250GB           | 4        | 0.66%   |
| Kingston SA400S37480G 480GB SSD     | 4        | 0.66%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 3        | 0.49%   |
| WDC WD40EZAZ-00SF3B0 4TB            | 3        | 0.49%   |
| WDC WD3200AAKS-75L9A0 320GB         | 3        | 0.49%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 3        | 0.49%   |
| WDC WD2002FAEX-007BA0 2TB           | 3        | 0.49%   |
| Unknown HUH728080ALE601 8TB         | 3        | 0.49%   |
| Seagate ST6000NM0095 6TB            | 3        | 0.49%   |
| Seagate ST6000NM0034 6TB            | 3        | 0.49%   |
| Seagate ST6000NM0014 6TB            | 3        | 0.49%   |
| Seagate ST4000NXCLAR4000 4TB        | 3        | 0.49%   |
| Seagate ST4000NM0023 4TB            | 3        | 0.49%   |
| Seagate ST31000524AS 1TB            | 3        | 0.49%   |
| Seagate ST2000DM001-9YN164 2TB      | 3        | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB      | 3        | 0.49%   |
| Seagate Expansion Desk 4TB          | 3        | 0.49%   |
| Samsung SSD 970 PRO 512GB           | 3        | 0.49%   |
| Samsung SSD 860 EVO 500GB           | 3        | 0.49%   |
| Samsung SSD 860 EVO 1TB             | 3        | 0.49%   |
| Samsung SSD 850 EVO 250GB           | 3        | 0.49%   |
| Samsung SSD 840 EVO 250GB           | 3        | 0.49%   |
| Samsung NVMe SSD Drive 512GB        | 3        | 0.49%   |
| Samsung NVMe SSD Drive 500GB        | 3        | 0.49%   |
| Samsung HD103SJ 1TB                 | 3        | 0.49%   |
| Kingston SA400S37120G 120GB SSD     | 3        | 0.49%   |
| WDC WDS250G2B0A-00SM50 250GB SSD    | 2        | 0.33%   |
| WDC WD40EZRZ-00GXCB0 4TB            | 2        | 0.33%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 0.33%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2        | 0.33%   |
| WDC WD30PURX-64P6ZY0 3TB            | 2        | 0.33%   |
| WDC WD2500AAJS-75M0A0 250GB         | 2        | 0.33%   |
| WDC WD20EZRX-00DC0B0 2TB            | 2        | 0.33%   |
| WDC WD20EFRX-68EUZN0 2TB            | 2        | 0.33%   |
| WDC WD180EDFZ-11AFWA0 18TB          | 2        | 0.33%   |
| WDC WD10EZEX-22MFCA0 1TB            | 2        | 0.33%   |
| WDC WD10EZEX-00WN4A0 1TB            | 2        | 0.33%   |
| WDC WD10EZEX-00BN5A0 1TB            | 2        | 0.33%   |
| WDC WD1003FBYX-01Y7B1 1TB           | 2        | 0.33%   |
| Toshiba HDWD120 2TB                 | 2        | 0.33%   |
| Toshiba DT01ACA200 2TB              | 2        | 0.33%   |
| SPCC Solid State Disk 64GB          | 2        | 0.33%   |
| SK Hynix SHGS31-500GS-2 500GB SSD   | 2        | 0.33%   |
| Silicon Motion NVMe SSD Drive 512GB | 2        | 0.33%   |
| Seagate ST8000AS0002-1NA17Z 8TB     | 2        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 106      | 257    | 36.81%  |
| Seagate             | 97       | 317    | 33.68%  |
| Toshiba             | 26       | 40     | 9.03%   |
| Hitachi             | 22       | 32     | 7.64%   |
| Samsung Electronics | 15       | 91     | 5.21%   |
| HGST                | 10       | 49     | 3.47%   |
| Unknown             | 4        | 22     | 1.39%   |
| Hewlett-Packard     | 2        | 2      | 0.69%   |
| SUN                 | 1        | 3      | 0.35%   |
| MAXTOR              | 1        | 1      | 0.35%   |
| Lenovo              | 1        | 2      | 0.35%   |
| Dell                | 1        | 1      | 0.35%   |
| ASMT                | 1        | 1      | 0.35%   |
| Apple               | 1        | 1      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 39       | 58     | 25.83%  |
| Kingston            | 34       | 40     | 22.52%  |
| Intel               | 13       | 33     | 8.61%   |
| WDC                 | 12       | 21     | 7.95%   |
| SanDisk             | 9        | 10     | 5.96%   |
| SK Hynix            | 5        | 5      | 3.31%   |
| Crucial             | 5        | 6      | 3.31%   |
| A-DATA Technology   | 4        | 5      | 2.65%   |
| SPCC                | 3        | 3      | 1.99%   |
| OCZ                 | 3        | 4      | 1.99%   |
| Seagate             | 2        | 2      | 1.32%   |
| PNY                 | 2        | 3      | 1.32%   |
| Micron Technology   | 2        | 3      | 1.32%   |
| Apacer              | 2        | 2      | 1.32%   |
| Verbatim            | 1        | 1      | 0.66%   |
| V-GeN               | 1        | 1      | 0.66%   |
| Transcend           | 1        | 1      | 0.66%   |
| Team                | 1        | 1      | 0.66%   |
| SATADOM-SL          | 1        | 1      | 0.66%   |
| PLEXTOR             | 1        | 1      | 0.66%   |
| Patriot             | 1        | 3      | 0.66%   |
| OWC                 | 1        | 1      | 0.66%   |
| LITEONIT            | 1        | 1      | 0.66%   |
| Lexar               | 1        | 1      | 0.66%   |
| KingDian            | 1        | 4      | 0.66%   |
| Hewlett-Packard     | 1        | 1      | 0.66%   |
| GLOWAY              | 1        | 1      | 0.66%   |
| Gigabyte Technology | 1        | 2      | 0.66%   |
| Corsair             | 1        | 1      | 0.66%   |
| China               | 1        | 4      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 210      | 819    | 52.76%  |
| SSD     | 126      | 220    | 31.66%  |
| NVMe    | 54       | 75     | 13.57%  |
| MMC     | 4        | 4      | 1.01%   |
| Unknown | 4        | 49     | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 256      | 881    | 77.11%  |
| NVMe | 54       | 75     | 16.27%  |
| SAS  | 18       | 207    | 5.42%   |
| MMC  | 4        | 4      | 1.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 180      | 403    | 44.67%  |
| 0.51-1.0   | 107      | 165    | 26.55%  |
| 1.01-2.0   | 53       | 123    | 13.15%  |
| 3.01-4.0   | 24       | 143    | 5.96%   |
| 4.01-10.0  | 18       | 109    | 4.47%   |
| 2.01-3.0   | 14       | 43     | 3.47%   |
| 10.01-20.0 | 7        | 53     | 1.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 61       | 20.75%  |
| 501-1000       | 53       | 18.03%  |
| More than 3000 | 46       | 15.65%  |
| 101-250        | 46       | 15.65%  |
| 1001-2000      | 35       | 11.9%   |
| Unknown        | 14       | 4.76%   |
| 21-50          | 11       | 3.74%   |
| 51-100         | 10       | 3.4%    |
| 2001-3000      | 9        | 3.06%   |
| 1-20           | 9        | 3.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 101      | 33.78%  |
| 21-50          | 40       | 13.38%  |
| 101-250        | 37       | 12.37%  |
| More than 3000 | 25       | 8.36%   |
| 251-500        | 24       | 8.03%   |
| 51-100         | 21       | 7.02%   |
| 501-1000       | 20       | 6.69%   |
| Unknown        | 14       | 4.68%   |
| 1001-2000      | 11       | 3.68%   |
| 2001-3000      | 5        | 1.67%   |
| 0              | 1        | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB             | 3        | 3      | 5.17%   |
| Seagate ST2000DM001-9YN164 2TB              | 3        | 3      | 5.17%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD            | 1        | 1      | 1.72%   |
| WDC WD6400AADS-00M2B0 640GB                 | 1        | 1      | 1.72%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1        | 1      | 1.72%   |
| WDC WD5000AVCS-632DY1 500GB                 | 1        | 1      | 1.72%   |
| WDC WD5000AACS-00G8B0 500GB                 | 1        | 1      | 1.72%   |
| WDC WD3200AVVS-63L2B0 320GB                 | 1        | 1      | 1.72%   |
| WDC WD3200AAKS-75L9A0 320GB                 | 1        | 1      | 1.72%   |
| WDC WD2500HHTZ-04N21V0 250GB                | 1        | 1      | 1.72%   |
| WDC WD20EZRZ-00Z5HB0 2TB                    | 1        | 1      | 1.72%   |
| WDC WD20EFRX-68EUZN0 2TB                    | 1        | 4      | 1.72%   |
| WDC WD20EARX-00PASB0 2TB                    | 1        | 1      | 1.72%   |
| WDC WD20EARS-00MVWB0 2TB                    | 1        | 2      | 1.72%   |
| WDC WD10EZEX-60WN4A1 1TB                    | 1        | 1      | 1.72%   |
| WDC WD10EADS-00L5B1 1TB                     | 1        | 1      | 1.72%   |
| WDC WD1003FBYX-01Y7B0 1TB                   | 1        | 1      | 1.72%   |
| WDC WD1002FBYS-18A6B0 1TB                   | 1        | 1      | 1.72%   |
| WDC WD1001FALS-00J7B1 1TB                   | 1        | 1      | 1.72%   |
| WDC RFT030VQFF-KRM5P7 3TB                   | 1        | 1      | 1.72%   |
| Toshiba MK2552GSX 250GB                     | 1        | 1      | 1.72%   |
| SK Hynix HFS128G32TND-N210A 128GB SSD       | 1        | 1      | 1.72%   |
| Seagate ST500LT012-1DG142 500GB             | 1        | 1      | 1.72%   |
| Seagate ST380211AS 80GB                     | 1        | 1      | 1.72%   |
| Seagate ST380013AS 80GB                     | 1        | 1      | 1.72%   |
| Seagate ST3400820AS 400GB                   | 1        | 1      | 1.72%   |
| Seagate ST3250620NS 250GB                   | 1        | 2      | 1.72%   |
| Seagate ST31000524NS 1TB                    | 1        | 1      | 1.72%   |
| Seagate ST31000340AS 1TB                    | 1        | 1      | 1.72%   |
| Seagate ST3000VM002-1ET166 3TB              | 1        | 1      | 1.72%   |
| Seagate ST1000NX0313 1TB                    | 1        | 1      | 1.72%   |
| Seagate ST1000DM003-1ER162 1TB              | 1        | 1      | 1.72%   |
| Seagate ST1000DM003-1CH162 1TB              | 1        | 1      | 1.72%   |
| SanDisk SDSSDX240GG25 240GB                 | 1        | 1      | 1.72%   |
| Samsung Electronics SSD SM871 2.5 7mm 512GB | 1        | 1      | 1.72%   |
| Samsung Electronics SSD 840 EVO 250GB       | 1        | 1      | 1.72%   |
| Samsung Electronics HD154UI 1TB             | 1        | 1      | 1.72%   |
| Samsung Electronics HD103UI 1TB             | 1        | 1      | 1.72%   |
| MAXTOR 6Y080L0 82GB                         | 1        | 1      | 1.72%   |
| LITEONIT LCT-256M3S 256GB SSD               | 1        | 1      | 1.72%   |
| Kingston SV100S264G 64GB SSD                | 1        | 1      | 1.72%   |
| Kingston SNS4151S316G 16GB SSD              | 1        | 1      | 1.72%   |
| Kingston SHFS37A120G 120GB SSD              | 1        | 1      | 1.72%   |
| Intel SSDSCKKW256G8 256GB                   | 1        | 1      | 1.72%   |
| Intel SSDSA2M120G2GC 120GB                  | 1        | 1      | 1.72%   |
| Intel SSDSA2M080G2LE 80GB                   | 1        | 15     | 1.72%   |
| Intel SSDSA2M040G2GC 40GB                   | 1        | 1      | 1.72%   |
| Hitachi HTS723232A7A364 320GB               | 1        | 1      | 1.72%   |
| Hitachi HTS542512K9A300 120GB               | 1        | 1      | 1.72%   |
| Hitachi HDT721010SLA360 1TB                 | 1        | 1      | 1.72%   |
| Hitachi HDS728080PLA380 80GB                | 1        | 1      | 1.72%   |
| Hitachi HDS721050CLA660 500GB               | 1        | 1      | 1.72%   |
| HGST HDS724040ALE640 4TB                    | 1        | 2      | 1.72%   |
| HGST HDN726060ALE610 6TB                    | 1        | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 18     | 30.36%  |
| WDC                 | 16       | 22     | 28.57%  |
| Hitachi             | 5        | 5      | 8.93%   |
| Samsung Electronics | 4        | 4      | 7.14%   |
| Intel               | 4        | 18     | 7.14%   |
| Kingston            | 3        | 3      | 5.36%   |
| HGST                | 2        | 3      | 3.57%   |
| Toshiba             | 1        | 1      | 1.79%   |
| SK Hynix            | 1        | 1      | 1.79%   |
| SanDisk             | 1        | 1      | 1.79%   |
| MAXTOR              | 1        | 1      | 1.79%   |
| LITEONIT            | 1        | 1      | 1.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 18     | 39.53%  |
| WDC                 | 15       | 21     | 34.88%  |
| Hitachi             | 5        | 5      | 11.63%  |
| Samsung Electronics | 2        | 2      | 4.65%   |
| HGST                | 2        | 3      | 4.65%   |
| Toshiba             | 1        | 1      | 2.33%   |
| MAXTOR              | 1        | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 37       | 51     | 74%     |
| SSD  | 13       | 27     | 26%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 162      | 553    | 48.94%  |
| Detected | 121      | 534    | 36.56%  |
| Malfunc  | 47       | 78     | 14.2%   |
| Failed   | 1        | 2      | 0.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 209      | 52.38%  |
| AMD                            | 66       | 16.54%  |
| Samsung Electronics            | 26       | 6.52%   |
| ASMedia Technology             | 19       | 4.76%   |
| LSI Logic / Symbios Logic      | 11       | 2.76%   |
| Marvell Technology Group       | 10       | 2.51%   |
| JMicron Technology             | 10       | 2.51%   |
| Sandisk                        | 8        | 2.01%   |
| Silicon Motion                 | 6        | 1.5%    |
| Broadcom / LSI                 | 6        | 1.5%    |
| Phison Electronics             | 5        | 1.25%   |
| Micron/Crucial Technology      | 3        | 0.75%   |
| ADATA Technology               | 3        | 0.75%   |
| Adaptec                        | 3        | 0.75%   |
| Nvidia                         | 2        | 0.5%    |
| Micron Technology              | 2        | 0.5%    |
| Kingston Technology Company    | 2        | 0.5%    |
| VIA Technologies               | 1        | 0.25%   |
| Solid State Storage Technology | 1        | 0.25%   |
| SK Hynix                       | 1        | 0.25%   |
| Silicon Image                  | 1        | 0.25%   |
| Realtek Semiconductor          | 1        | 0.25%   |
| KIOXIA                         | 1        | 0.25%   |
| Integrated Technology Express  | 1        | 0.25%   |
| 3ware                          | 1        | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 42       | 8.47%   |
| Intel SATA Controller [RAID mode]                                                       | 32       | 6.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 5.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 17       | 3.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16       | 3.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16       | 3.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15       | 3.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 2.22%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 2.22%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 1.81%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 8        | 1.61%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 1.61%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                 | 7        | 1.41%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 1.41%   |
| AMD FCH SATA Controller D                                                               | 7        | 1.41%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 6        | 1.21%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5        | 1.01%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 1.01%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 1.01%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 1.01%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5        | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.81%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 0.81%   |
| AMD X399 Series Chipset SATA Controller                                                 | 4        | 0.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 0.6%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3        | 0.6%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 3        | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 0.6%    |
| Samsung NVMe SSD Controller 980                                                         | 3        | 0.6%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.6%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 3        | 0.6%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.6%    |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                           | 3        | 0.6%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 0.6%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3        | 0.6%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 3        | 0.6%    |
| Intel 631xESB/632xESB IDE Controller                                                    | 3        | 0.6%    |
| ASMedia SATA controller                                                                 | 3        | 0.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [Non-RAID5 mode]                                  | 3        | 0.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 0.6%    |
| AMD FCH IDE Controller                                                                  | 3        | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.6%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.4%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2        | 0.4%    |
| Nvidia MCP73 IDE Controller                                                             | 2        | 0.4%    |
| Micron Non-Volatile memory controller                                                   | 2        | 0.4%    |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                        | 2        | 0.4%    |
| JMicron JMB368 IDE controller                                                           | 2        | 0.4%    |
| Intel SSD 660P Series                                                                   | 2        | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 198      | 51.83%  |
| IDE  | 59       | 15.45%  |
| NVMe | 55       | 14.4%   |
| RAID | 54       | 14.14%  |
| SAS  | 11       | 2.88%   |
| SCSI | 5        | 1.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 219      | 76.84%  |
| AMD    | 66       | 23.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-6700 CPU @ 3.40GHz               | 13       | 4.55%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 7        | 2.45%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 5        | 1.75%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 5        | 1.75%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 5        | 1.75%   |
| AMD Ryzen 5 3600 6-Core Processor              | 5        | 1.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz               | 4        | 1.4%    |
| Intel Core i5-3470 CPU @ 3.20GHz               | 4        | 1.4%    |
| Intel Core i5-2400 CPU @ 3.10GHz               | 4        | 1.4%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 4        | 1.4%    |
| Intel Xeon E-2136 CPU @ 3.30GHz                | 3        | 1.05%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 3        | 1.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 3        | 1.05%   |
| Intel Core i5-9500 CPU @ 3.00GHz               | 3        | 1.05%   |
| Intel Core i5-3570K CPU @ 3.40GHz              | 3        | 1.05%   |
| Intel Core i5 CPU 760 @ 2.80GHz                | 3        | 1.05%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz          | 3        | 1.05%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz           | 3        | 1.05%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 3        | 1.05%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 3        | 1.05%   |
| AMD FX-8350 Eight-Core Processor               | 3        | 1.05%   |
| AMD FX-6300 Six-Core Processor                 | 3        | 1.05%   |
| Intel Xeon E-2224G CPU @ 3.50GHz               | 2        | 0.7%    |
| Intel Xeon CPU X5680 @ 3.33GHz                 | 2        | 0.7%    |
| Intel Xeon CPU X5450 @ 3.00GHz                 | 2        | 0.7%    |
| Intel Xeon CPU W3530 @ 2.80GHz                 | 2        | 0.7%    |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 2        | 0.7%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz            | 2        | 0.7%    |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz             | 2        | 0.7%    |
| Intel Xeon CPU E31270 @ 3.40GHz                | 2        | 0.7%    |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 2        | 0.7%    |
| Intel Core i9-9900K CPU @ 3.60GHz              | 2        | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 0.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz              | 2        | 0.7%    |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 0.7%    |
| Intel Core i7-5930K CPU @ 3.50GHz              | 2        | 0.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz              | 2        | 0.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 0.7%    |
| Intel Core i7-2600K CPU @ 3.40GHz              | 2        | 0.7%    |
| Intel Core i7-10700F CPU @ 2.90GHz             | 2        | 0.7%    |
| Intel Core i7-10700 CPU @ 2.90GHz              | 2        | 0.7%    |
| Intel Core i7 CPU 950 @ 3.07GHz                | 2        | 0.7%    |
| Intel Core i5-4590S CPU @ 3.00GHz              | 2        | 0.7%    |
| Intel Core i5-3570 CPU @ 3.40GHz               | 2        | 0.7%    |
| Intel Core i5-3470S CPU @ 2.90GHz              | 2        | 0.7%    |
| Intel Core i5-10400 CPU @ 2.90GHz              | 2        | 0.7%    |
| Intel Core i3-4330 CPU @ 3.50GHz               | 2        | 0.7%    |
| Intel Core i3-4160 CPU @ 3.60GHz               | 2        | 0.7%    |
| Intel Core i3-3220 CPU @ 3.30GHz               | 2        | 0.7%    |
| Intel Core i3-2120 CPU @ 3.30GHz               | 2        | 0.7%    |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz          | 2        | 0.7%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 2        | 0.7%    |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 2        | 0.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 2        | 0.7%    |
| Intel Atom CPU D525 @ 1.80GHz                  | 2        | 0.7%    |
| AMD Turion II Neo N54L Dual-Core Processor     | 2        | 0.7%    |
| AMD Ryzen Threadripper 2950X 16-Core Processor | 2        | 0.7%    |
| AMD Ryzen 7 2700X Eight-Core Processor         | 2        | 0.7%    |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 0.7%    |
| AMD Ryzen 5 3500X 6-Core Processor             | 2        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 61       | 21.33%  |
| Intel Core i5           | 49       | 17.13%  |
| Intel Xeon              | 45       | 15.73%  |
| Intel Core i3           | 16       | 5.59%   |
| AMD Ryzen 5             | 15       | 5.24%   |
| AMD FX                  | 12       | 4.2%    |
| Intel Core 2 Quad       | 10       | 3.5%    |
| Intel Core 2 Duo        | 8        | 2.8%    |
| AMD Ryzen 9             | 8        | 2.8%    |
| AMD Ryzen 7             | 8        | 2.8%    |
| Intel Pentium           | 7        | 2.45%   |
| Intel Atom              | 7        | 2.45%   |
| AMD Ryzen 3             | 5        | 1.75%   |
| Intel Pentium Dual-Core | 4        | 1.4%    |
| Intel Core i9           | 4        | 1.4%    |
| AMD Ryzen Threadripper  | 4        | 1.4%    |
| Intel Celeron           | 3        | 1.05%   |
| Intel Pentium Dual      | 2        | 0.7%    |
| AMD Turion II Neo       | 2        | 0.7%    |
| AMD Ryzen 7 PRO         | 2        | 0.7%    |
| AMD A8                  | 2        | 0.7%    |
| AMD A10                 | 2        | 0.7%    |
| Other                   | 1        | 0.35%   |
| Intel Pentium Gold      | 1        | 0.35%   |
| Intel Genuine           | 1        | 0.35%   |
| AMD Phenom II X6        | 1        | 0.35%   |
| AMD Phenom II X4        | 1        | 0.35%   |
| AMD Opteron             | 1        | 0.35%   |
| AMD GX                  | 1        | 0.35%   |
| AMD E2                  | 1        | 0.35%   |
| AMD Athlon              | 1        | 0.35%   |
| AMD A4                  | 1        | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 136      | 47.55%  |
| 2      | 49       | 17.13%  |
| 6      | 43       | 15.03%  |
| 8      | 23       | 8.04%   |
| 12     | 13       | 4.55%   |
| 16     | 8        | 2.8%    |
| 3      | 5        | 1.75%   |
| 10     | 3        | 1.05%   |
| 1      | 3        | 1.05%   |
| 28     | 1        | 0.35%   |
| 20     | 1        | 0.35%   |
| 14     | 1        | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 271      | 95.09%  |
| 2      | 13       | 4.56%   |
| 0      | 1        | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 170      | 59.23%  |
| 1      | 117      | 40.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 273      | 95.79%  |
| Unknown        | 12       | 4.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 32       | 11.07%  |
| 0x306a9    | 20       | 6.92%   |
| Unknown    | 20       | 6.92%   |
| 0x506e3    | 19       | 6.57%   |
| 0x206a7    | 19       | 6.57%   |
| 0x906ea    | 15       | 5.19%   |
| 0x06000852 | 12       | 4.15%   |
| 0x1067a    | 11       | 3.81%   |
| 0x08701021 | 11       | 3.81%   |
| 0x306f2    | 10       | 3.46%   |
| 0xa0655    | 8        | 2.77%   |
| 0x906e9    | 8        | 2.77%   |
| 0x0800820d | 8        | 2.77%   |
| 0x106e5    | 7        | 2.42%   |
| 0x08701013 | 7        | 2.42%   |
| 0x206c2    | 6        | 2.08%   |
| 0x6fb      | 5        | 1.73%   |
| 0x206d7    | 5        | 1.73%   |
| 0x6fd      | 4        | 1.38%   |
| 0x406c4    | 4        | 1.38%   |
| 0x106a5    | 4        | 1.38%   |
| 0x08001137 | 4        | 1.38%   |
| 0x906ed    | 3        | 1.04%   |
| 0x50654    | 3        | 1.04%   |
| 0x106ca    | 3        | 1.04%   |
| 0x10676    | 3        | 1.04%   |
| 0x08101016 | 3        | 1.04%   |
| 0x03000027 | 3        | 1.04%   |
| 0xa0653    | 2        | 0.69%   |
| 0x40651    | 2        | 0.69%   |
| 0x10677    | 2        | 0.69%   |
| 0x0a201009 | 2        | 0.69%   |
| 0x06001119 | 2        | 0.69%   |
| 0x010000c8 | 2        | 0.69%   |
| 0xa0671    | 1        | 0.35%   |
| 0x906eb    | 1        | 0.35%   |
| 0x506ca    | 1        | 0.35%   |
| 0x50663    | 1        | 0.35%   |
| 0x406f1    | 1        | 0.35%   |
| 0x406e3    | 1        | 0.35%   |
| 0x406c3    | 1        | 0.35%   |
| 0x30678    | 1        | 0.35%   |
| 0x20655    | 1        | 0.35%   |
| 0x20652    | 1        | 0.35%   |
| 0x106c2    | 1        | 0.35%   |
| 0x08701011 | 1        | 0.35%   |
| 0x08600106 | 1        | 0.35%   |
| 0x0800820b | 1        | 0.35%   |
| 0x08001138 | 1        | 0.35%   |
| 0x08001129 | 1        | 0.35%   |
| 0x0700010f | 1        | 0.35%   |
| 0x0600084f | 1        | 0.35%   |
| 0x010000dc | 1        | 0.35%   |
| 0x010000db | 1        | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 44       | 15.38%  |
| KabyLake    | 28       | 9.79%   |
| Skylake     | 26       | 9.09%   |
| SandyBridge | 26       | 9.09%   |
| Zen 2       | 21       | 7.34%   |
| IvyBridge   | 20       | 6.99%   |
| Penryn      | 19       | 6.64%   |
| Piledriver  | 16       | 5.59%   |
| Nehalem     | 11       | 3.85%   |
| Zen         | 10       | 3.5%    |
| Westmere    | 10       | 3.5%    |
| CometLake   | 10       | 3.5%    |
| Zen+        | 9        | 3.15%   |
| Core        | 9        | 3.15%   |
| Silvermont  | 6        | 2.1%    |
| K10         | 4        | 1.4%    |
| Broadwell   | 4        | 1.4%    |
| Bonnell     | 4        | 1.4%    |
| K10 Llano   | 3        | 1.05%   |
| Zen 3       | 2        | 0.7%    |
| Jaguar      | 2        | 0.7%    |
| Goldmont    | 1        | 0.35%   |
| Unknown     | 1        | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 113      | 37.05%  |
| Nvidia                                       | 99       | 32.46%  |
| AMD                                          | 78       | 25.57%  |
| ASPEED Technology                            | 9        | 2.95%   |
| S3 Graphics                                  | 2        | 0.66%   |
| Matrox Electronics Systems                   | 2        | 0.66%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.33%   |
| Silicon Motion                               | 1        | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18       | 5.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14       | 4.53%   |
| Intel HD Graphics 530                                                                    | 13       | 4.21%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 12       | 3.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12       | 3.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11       | 3.56%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 9        | 2.91%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 8        | 2.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7        | 2.27%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 7        | 2.27%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 7        | 2.27%   |
| Nvidia GT218 [GeForce 210]                                                               | 6        | 1.94%   |
| Intel HD Graphics 630                                                                    | 5        | 1.62%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5        | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 1.62%   |
| Nvidia GP107GL [Quadro P400]                                                             | 4        | 1.29%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 1.29%   |
| AMD RS780L [Radeon 3000]                                                                 | 4        | 1.29%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 0.97%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 3        | 0.97%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3        | 0.97%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 3        | 0.97%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3        | 0.97%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 0.97%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 0.97%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 2        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 2        | 0.65%   |
| Nvidia GT218 [GeForce G210]                                                              | 2        | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2        | 0.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2        | 0.65%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2        | 0.65%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 2        | 0.65%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 2        | 0.65%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 2        | 0.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2        | 0.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 0.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 2        | 0.65%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2        | 0.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 0.65%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2        | 0.65%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 0.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 0.65%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 2        | 0.65%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)                           | 1        | 0.32%   |
| Silicon Motion SM712 LynxEM+                                                             | 1        | 0.32%   |
| S3 Graphics Savage 4                                                                     | 1        | 0.32%   |
| S3 Graphics 86c375 [ViRGE/DX] or 86c385 [ViRGE/GX]                                       | 1        | 0.32%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.32%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.32%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 0.32%   |
| Nvidia TU104GL [Quadro RTX 5000]                                                         | 1        | 0.32%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.32%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.32%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 0.32%   |
| Nvidia TU102 [TITAN RTX]                                                                 | 1        | 0.32%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 1        | 0.32%   |
| Nvidia GT218 [NVS 300]                                                                   | 1        | 0.32%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.32%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Intel            | 99       | 34.49%  |
| 1 x Nvidia           | 90       | 31.36%  |
| 1 x AMD              | 70       | 24.39%  |
| 1 x ASPEED           | 6        | 2.09%   |
| Intel + AMD          | 4        | 1.39%   |
| 2 x Nvidia           | 2        | 0.7%    |
| 2 x AMD              | 2        | 0.7%    |
| 1 x S3 Graphics      | 2        | 0.7%    |
| Nvidia + ASPEED      | 2        | 0.7%    |
| 1 x Matrox           | 2        | 0.7%    |
| Intel + Nvidia       | 2        | 0.7%    |
| Other                | 1        | 0.35%   |
| 2 x AMD + 1 x ASPEED | 1        | 0.35%   |
| 1 x XGI              | 1        | 0.35%   |
| 1 x Silicon Motion   | 1        | 0.35%   |
| Intel + 2 x Nvidia   | 1        | 0.35%   |
| AMD + Nvidia         | 1        | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 206      | 71.53%  |
| Proprietary | 49       | 17.01%  |
| Unknown     | 33       | 11.46%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 128      | 43.54%  |
| 1.01-2.0   | 49       | 16.67%  |
| 0.51-1.0   | 38       | 12.93%  |
| 0.01-0.5   | 26       | 8.84%   |
| 7.01-8.0   | 23       | 7.82%   |
| 3.01-4.0   | 15       | 5.1%    |
| 5.01-6.0   | 4        | 1.36%   |
| 4.01-5.0   | 4        | 1.36%   |
| 2.01-3.0   | 3        | 1.02%   |
| 8.01-16.0  | 3        | 1.02%   |
| 16.01-24.0 | 1        | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Dell                    | 59       | 22.18%  |
| Samsung Electronics     | 40       | 15.04%  |
| Hewlett-Packard         | 29       | 10.9%   |
| Goldstar                | 27       | 10.15%  |
| Acer                    | 17       | 6.39%   |
| BenQ                    | 12       | 4.51%   |
| Ancor Communications    | 10       | 3.76%   |
| Philips                 | 9        | 3.38%   |
| AOC                     | 9        | 3.38%   |
| ViewSonic               | 7        | 2.63%   |
| Eizo                    | 5        | 1.88%   |
| LG Electronics          | 4        | 1.5%    |
| Iiyama                  | 4        | 1.5%    |
| Unknown                 | 3        | 1.13%   |
| Sony                    | 3        | 1.13%   |
| NEC Computers           | 3        | 1.13%   |
| Xiaomi                  | 2        | 0.75%   |
| Sceptre Tech            | 2        | 0.75%   |
| MStar                   | 2        | 0.75%   |
| Lenovo                  | 2        | 0.75%   |
| HPN                     | 2        | 0.75%   |
| ___                     | 1        | 0.38%   |
| Xerox                   | 1        | 0.38%   |
| Sun                     | 1        | 0.38%   |
| Packard Bell            | 1        | 0.38%   |
| NME                     | 1        | 0.38%   |
| Insignia                | 1        | 0.38%   |
| HannStar Display        | 1        | 0.38%   |
| HannStar                | 1        | 0.38%   |
| GVV                     | 1        | 0.38%   |
| Founder                 | 1        | 0.38%   |
| Chi Mei Optoelectronics | 1        | 0.38%   |
| AUS                     | 1        | 0.38%   |
| ASUSTek Computer        | 1        | 0.38%   |
| Apple                   | 1        | 0.38%   |
| AMW                     | 1        | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Dell P2414H DELA09A 1920x1080 527x297mm 23.8-inch                    | 7        | 2.3%    |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                    | 6        | 1.97%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                       | 4        | 1.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch             | 3        | 0.99%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 3        | 0.99%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3        | 0.99%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                    | 3        | 0.99%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                   | 2        | 0.66%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch | 2        | 0.66%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch  | 2        | 0.66%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch  | 2        | 0.66%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2        | 0.66%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                     | 2        | 0.66%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch        | 2        | 0.66%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 519x324mm 24.1-inch         | 2        | 0.66%   |
| Goldstar Ultra HD GSM5B09 3780x2160 600x340mm 27.2-inch              | 2        | 0.66%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch            | 2        | 0.66%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch               | 2        | 0.66%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                | 2        | 0.66%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 0.66%   |
| Dell ST2410 DELA05D 1920x1080 531x299mm 24.0-inch                    | 2        | 0.66%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                | 2        | 0.66%   |
| Dell P2417H DELA0DA 1920x1080 527x296mm 23.8-inch                    | 2        | 0.66%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                    | 2        | 0.66%   |
| BenQ LCD Monitor GW2283 3840x1080                                    | 2        | 0.66%   |
| BenQ LCD Monitor GW2283                                              | 2        | 0.66%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                    | 2        | 0.66%   |
| ___ LCDTV16 ___9000 1360x768                                         | 1        | 0.33%   |
| Xerox XM7-22w XER08E8 1680x1050 474x296mm 22.0-inch                  | 1        | 0.33%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch            | 1        | 0.33%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 0.33%   |
| ViewSonic VA2759 Series VSC6832 1920x1080 598x336mm 27.0-inch        | 1        | 0.33%   |
| ViewSonic VA2342 SERIES VSCFA2B 1920x1080 509x286mm 23.0-inch        | 1        | 0.33%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch            | 1        | 0.33%   |
| ViewSonic VA2210-FHD VSCC536 1920x1080 476x268mm 21.5-inch           | 1        | 0.33%   |
| ViewSonic VA1601W-LED VSC1A25 1366x768 344x193mm 15.5-inch           | 1        | 0.33%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1        | 0.33%   |
| Unknown LCD Monitor XXX AAA 1366x768                                 | 1        | 0.33%   |
| Unknown LCD Monitor BENQ G2200W 5520x2160                            | 1        | 0.33%   |
| Sun 21" Premium Color Monitor SUN0567 1600x1200 388x291mm 19.1-inch  | 1        | 0.33%   |
| Sony TV *00 SNY8404 3840x2160 1218x685mm 55.0-inch                   | 1        | 0.33%   |
| Sony TV *00 SNY7C04 3840x2160 952x535mm 43.0-inch                    | 1        | 0.33%   |
| Sony SDM-E96D SNYB400 1280x1024 376x301mm 19.0-inch                  | 1        | 0.33%   |
| Sceptre Tech U435CV-UMC SPT1109 3840x2160 575x323mm 26.0-inch        | 1        | 0.33%   |
| Sceptre Tech F27 SPT0ABF 1920x1080 409x230mm 18.5-inch               | 1        | 0.33%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch    | 1        | 0.33%   |
| Samsung Electronics U28E850 SAM0CCD 3840x2160 608x345mm 27.5-inch    | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM05C7 1920x1080 521x293mm 23.5-inch | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM04DD 1920x1080 477x268mm 21.5-inch | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1        | 0.33%   |
| Samsung Electronics SyncMaster SAM0094 1280x1024 338x270mm 17.0-inch | 1        | 0.33%   |
| Samsung Electronics SMEX2220 SAM0685 1920x1080 477x268mm 21.5-inch   | 1        | 0.33%   |
| Samsung Electronics SMBX2350 SAM071E 1920x1080 510x290mm 23.1-inch   | 1        | 0.33%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 477x268mm 21.5-inch   | 1        | 0.33%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch    | 1        | 0.33%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch    | 1        | 0.33%   |
| Samsung Electronics S27E391 SAM0C16 1920x1080 598x336mm 27.0-inch    | 1        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 120      | 44.94%  |
| 3840x2160 (4K)     | 23       | 8.61%   |
| 1920x1200 (WUXGA)  | 16       | 5.99%   |
| Unknown            | 16       | 5.99%   |
| 1680x1050 (WSXGA+) | 15       | 5.62%   |
| 2560x1440 (QHD)    | 14       | 5.24%   |
| 1366x768 (WXGA)    | 9        | 3.37%   |
| 1280x1024 (SXGA)   | 9        | 3.37%   |
| 1600x900 (HD+)     | 7        | 2.62%   |
| 3840x1080          | 6        | 2.25%   |
| 1440x900 (WXGA+)   | 6        | 2.25%   |
| 1600x1200          | 5        | 1.87%   |
| 1024x768 (XGA)     | 4        | 1.5%    |
| 3840x1200          | 3        | 1.12%   |
| 2560x1080          | 3        | 1.12%   |
| 2880x1800          | 2        | 0.75%   |
| 7680x1080          | 1        | 0.37%   |
| 7280x2160          | 1        | 0.37%   |
| 5760x1080          | 1        | 0.37%   |
| 5520x2160          | 1        | 0.37%   |
| 3640x1920          | 1        | 0.37%   |
| 2560x1600          | 1        | 0.37%   |
| 1400x1050          | 1        | 0.37%   |
| 1360x768           | 1        | 0.37%   |
| 1280x960           | 1        | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 51       | 19.03%  |
| 27      | 39       | 14.55%  |
| 21      | 37       | 13.81%  |
| 23      | 34       | 12.69%  |
| Unknown | 32       | 11.94%  |
| 20      | 12       | 4.48%   |
| 19      | 11       | 4.1%    |
| 22      | 9        | 3.36%   |
| 15      | 7        | 2.61%   |
| 18      | 6        | 2.24%   |
| 31      | 4        | 1.49%   |
| 34      | 3        | 1.12%   |
| 32      | 3        | 1.12%   |
| 25      | 3        | 1.12%   |
| 17      | 3        | 1.12%   |
| 84      | 2        | 0.75%   |
| 65      | 2        | 0.75%   |
| 52      | 2        | 0.75%   |
| 40      | 2        | 0.75%   |
| 72      | 1        | 0.37%   |
| 54      | 1        | 0.37%   |
| 49      | 1        | 0.37%   |
| 42      | 1        | 0.37%   |
| 29      | 1        | 0.37%   |
| 26      | 1        | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 115      | 45.1%   |
| 401-500     | 64       | 25.1%   |
| Unknown     | 32       | 12.55%  |
| 301-350     | 10       | 3.92%   |
| 601-700     | 9        | 3.53%   |
| 351-400     | 7        | 2.75%   |
| 701-800     | 6        | 2.35%   |
| 1001-1500   | 6        | 2.35%   |
| 1501-2000   | 3        | 1.18%   |
| 801-900     | 2        | 0.78%   |
| 901-1000    | 1        | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 152      | 62.55%  |
| 16/10   | 38       | 15.64%  |
| Unknown | 29       | 11.93%  |
| 4/3     | 11       | 4.53%   |
| 5/4     | 9        | 3.7%    |
| 21/9    | 3        | 1.23%   |
| 3/2     | 1        | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 99       | 37.79%  |
| 301-350        | 39       | 14.89%  |
| 151-200        | 32       | 12.21%  |
| Unknown        | 32       | 12.21%  |
| 251-300        | 22       | 8.4%    |
| 351-500        | 11       | 4.2%    |
| More than 1000 | 9        | 3.44%   |
| 141-150        | 8        | 3.05%   |
| 101-110        | 7        | 2.67%   |
| 501-1000       | 3        | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 148      | 60.41%  |
| 101-120 | 47       | 19.18%  |
| Unknown | 32       | 13.06%  |
| 121-160 | 8        | 3.27%   |
| 1-50    | 5        | 2.04%   |
| 161-240 | 5        | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 169      | 58.48%  |
| 0     | 63       | 21.8%   |
| 2     | 48       | 16.61%  |
| 3     | 5        | 1.73%   |
| 4     | 3        | 1.04%   |
| 6     | 1        | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 159      | 40.66%  |
| Realtek Semiconductor       | 135      | 34.53%  |
| Broadcom                    | 24       | 6.14%   |
| Qualcomm Atheros            | 17       | 4.35%   |
| Ralink Technology           | 12       | 3.07%   |
| TP-Link                     | 7        | 1.79%   |
| D-Link System               | 5        | 1.28%   |
| Mellanox Technologies       | 4        | 1.02%   |
| Broadcom Limited            | 3        | 0.77%   |
| Aquantia                    | 3        | 0.77%   |
| D-Link                      | 2        | 0.51%   |
| ASIX Electronics            | 2        | 0.51%   |
| Xilinx                      | 1        | 0.26%   |
| Xiaomi                      | 1        | 0.26%   |
| VIA Technologies            | 1        | 0.26%   |
| Spreadtrum Communications   | 1        | 0.26%   |
| Sierra Wireless             | 1        | 0.26%   |
| Samsung Electronics         | 1        | 0.26%   |
| Ralink                      | 1        | 0.26%   |
| MediaTek                    | 1        | 0.26%   |
| Marvell Technology Group    | 1        | 0.26%   |
| Linux 2.6.31.6 with s3c-udc | 1        | 0.26%   |
| Linksys                     | 1        | 0.26%   |
| ICS Advent                  | 1        | 0.26%   |
| Dresden Elektronik          | 1        | 0.26%   |
| DisplayLink                 | 1        | 0.26%   |
| Cisco Systems               | 1        | 0.26%   |
| Apple                       | 1        | 0.26%   |
| Accton Technology           | 1        | 0.26%   |
| 3Com                        | 1        | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 112      | 25.51%  |
| Intel I211 Gigabit Network Connection                                         | 23       | 5.24%   |
| Intel Ethernet Connection I217-LM                                             | 17       | 3.87%   |
| Intel Ethernet Connection (2) I219-LM                                         | 17       | 3.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 17       | 3.87%   |
| Intel 82574L Gigabit Network Connection                                       | 13       | 2.96%   |
| Intel Ethernet Connection (2) I219-V                                          | 10       | 2.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 8        | 1.82%   |
| Intel Wi-Fi 6 AX200                                                           | 8        | 1.82%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 1.59%   |
| Intel Ethernet Connection (7) I219-LM                                         | 7        | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 7        | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 1.37%   |
| Intel Ethernet Connection (2) I218-V                                          | 6        | 1.37%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 1.37%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 5        | 1.14%   |
| Ralink RT5370 Wireless Adapter                                                | 4        | 0.91%   |
| Ralink MT7601U Wireless Adapter                                               | 4        | 0.91%   |
| Intel Ethernet Connection (11) I219-LM                                        | 4        | 0.91%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 4        | 0.91%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 4        | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.68%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 3        | 0.68%   |
| Intel Wireless-AC 9260                                                        | 3        | 0.68%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 0.68%   |
| Intel Ethernet Controller 10G X550T                                           | 3        | 0.68%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 0.68%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 0.46%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2        | 0.46%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 2        | 0.46%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 2        | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 2        | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 2        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 0.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 0.46%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2        | 0.46%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 0.46%   |
| Intel Wireless 7260                                                           | 2        | 0.46%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2        | 0.46%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.46%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.46%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.46%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 2        | 0.46%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2        | 0.46%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express               | 2        | 0.46%   |
| Xilinx Network controller                                                     | 1        | 0.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.23%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 0.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.23%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.23%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1        | 0.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.23%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 0.23%   |
| Spreadtrum Spreadtrum Phone                                                   | 1        | 0.23%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                               | 1        | 0.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 28       | 33.73%  |
| Realtek Semiconductor | 14       | 16.87%  |
| Ralink Technology     | 12       | 14.46%  |
| Qualcomm Atheros      | 8        | 9.64%   |
| TP-Link               | 7        | 8.43%   |
| Broadcom              | 7        | 8.43%   |
| D-Link                | 2        | 2.41%   |
| Sierra Wireless       | 1        | 1.2%    |
| Ralink                | 1        | 1.2%    |
| MediaTek              | 1        | 1.2%    |
| Linksys               | 1        | 1.2%    |
| D-Link System         | 1        | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 8        | 9.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 7        | 8.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 5        | 5.95%   |
| Ralink RT5370 Wireless Adapter                                                                | 4        | 4.76%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 4.76%   |
| Intel Wireless-AC 9260                                                                        | 3        | 3.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 2.38%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 2        | 2.38%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 2        | 2.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 2        | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 2.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2        | 2.38%   |
| Intel Wireless 8265 / 8275                                                                    | 2        | 2.38%   |
| Intel Wireless 7260                                                                           | 2        | 2.38%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.19%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 1.19%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 1.19%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 1.19%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.19%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                                               | 1        | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1        | 1.19%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 1.19%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 1.19%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.19%   |
| Realtek 802.11ac NIC                                                                          | 1        | 1.19%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 1.19%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 1.19%   |
| Ralink RT2770 Wireless Adapter                                                                | 1        | 1.19%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.19%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 1.19%   |
| MediaTek Wireless                                                                             | 1        | 1.19%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 1.19%   |
| Intel Wireless 7265                                                                           | 1        | 1.19%   |
| Intel Wireless 3165                                                                           | 1        | 1.19%   |
| Intel Wireless 3160                                                                           | 1        | 1.19%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 1.19%   |
| Intel Centrino Advanced-N 6235                                                                | 1        | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.19%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]                             | 1        | 1.19%   |
| D-Link DWA-160 Xtreme N Dual Band USB Adapter(rev.C1)                                         | 1        | 1.19%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                          | 1        | 1.19%   |
| D-Link 802.11 n WLAN                                                                          | 1        | 1.19%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1        | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 1        | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 145      | 44.62%  |
| Realtek Semiconductor     | 131      | 40.31%  |
| Broadcom                  | 17       | 5.23%   |
| Qualcomm Atheros          | 9        | 2.77%   |
| D-Link System             | 4        | 1.23%   |
| Broadcom Limited          | 3        | 0.92%   |
| Aquantia                  | 3        | 0.92%   |
| ASIX Electronics          | 2        | 0.62%   |
| Xiaomi                    | 1        | 0.31%   |
| VIA Technologies          | 1        | 0.31%   |
| Spreadtrum Communications | 1        | 0.31%   |
| Samsung Electronics       | 1        | 0.31%   |
| Marvell Technology Group  | 1        | 0.31%   |
| ICS Advent                | 1        | 0.31%   |
| DisplayLink               | 1        | 0.31%   |
| Cisco Systems             | 1        | 0.31%   |
| Apple                     | 1        | 0.31%   |
| Accton Technology         | 1        | 0.31%   |
| 3Com                      | 1        | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 112      | 32.18%  |
| Intel I211 Gigabit Network Connection                                          | 23       | 6.61%   |
| Intel Ethernet Connection I217-LM                                              | 17       | 4.89%   |
| Intel Ethernet Connection (2) I219-LM                                          | 17       | 4.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 17       | 4.89%   |
| Intel 82574L Gigabit Network Connection                                        | 13       | 3.74%   |
| Intel Ethernet Connection (2) I219-V                                           | 10       | 2.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8        | 2.3%    |
| Intel I210 Gigabit Network Connection                                          | 7        | 2.01%   |
| Intel Ethernet Connection (7) I219-LM                                          | 7        | 2.01%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6        | 1.72%   |
| Intel Ethernet Connection (2) I218-V                                           | 6        | 1.72%   |
| Intel 82579V Gigabit Network Connection                                        | 6        | 1.72%   |
| Intel Ethernet Connection (11) I219-LM                                         | 4        | 1.15%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4        | 1.15%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 4        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 0.86%   |
| Intel I350 Gigabit Network Connection                                          | 3        | 0.86%   |
| Intel Ethernet Controller 10G X550T                                            | 3        | 0.86%   |
| Intel 82580 Gigabit Network Connection                                         | 3        | 0.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 3        | 0.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2        | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2        | 0.57%   |
| Intel Ethernet Connection I217-V                                               | 2        | 0.57%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2        | 0.57%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 2        | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2        | 0.57%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 2        | 0.57%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 2        | 0.57%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                               | 2        | 0.57%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express                | 2        | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.29%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 1        | 0.29%   |
| Spreadtrum Spreadtrum Phone                                                    | 1        | 0.29%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1        | 0.29%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.29%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 0.29%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 0.29%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                               | 1        | 0.29%   |
| Intel Ethernet Controller I225-V                                               | 1        | 0.29%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 0.29%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                               | 1        | 0.29%   |
| Intel Ethernet Connection I219-V                                               | 1        | 0.29%   |
| Intel Ethernet Connection I218-V                                               | 1        | 0.29%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1        | 0.29%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.29%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 1        | 0.29%   |
| Intel 82578DC Gigabit Network Connection                                       | 1        | 0.29%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 1        | 0.29%   |
| Intel 82567LF-2 Gigabit Network Connection                                     | 1        | 0.29%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1        | 0.29%   |
| Intel 82566DC-2 Gigabit Network Connection                                     | 1        | 0.29%   |
| Intel 82562V-2 10/100 Network Connection                                       | 1        | 0.29%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                           | 1        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 284      | 77.6%   |
| WiFi     | 75       | 20.49%  |
| Unknown  | 5        | 1.37%   |
| Modem    | 2        | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 270      | 84.91%  |
| WiFi     | 47       | 14.78%  |
| Unknown  | 1        | 0.31%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 167      | 58.19%  |
| 2     | 84       | 29.27%  |
| 3     | 22       | 7.67%   |
| 4     | 5        | 1.74%   |
| 5     | 4        | 1.39%   |
| 0     | 2        | 0.7%    |
| 8     | 1        | 0.35%   |
| 7     | 1        | 0.35%   |
| 6     | 1        | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 269      | 93.73%  |
| Yes  | 18       | 6.27%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 26       | 39.39%  |
| Cambridge Silicon Radio         | 17       | 25.76%  |
| Broadcom                        | 9        | 13.64%  |
| ASUSTek Computer                | 6        | 9.09%   |
| Realtek Semiconductor           | 3        | 4.55%   |
| Qualcomm Atheros Communications | 2        | 3.03%   |
| IMC Networks                    | 1        | 1.52%   |
| Dynex                           | 1        | 1.52%   |
| Apple                           | 1        | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 17       | 25.76%  |
| Intel AX200 Bluetooth                                    | 8        | 12.12%  |
| Intel Wireless-AC 3168 Bluetooth                         | 6        | 9.09%   |
| Intel Bluetooth wireless interface                       | 6        | 9.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 6        | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 3        | 4.55%   |
| Realtek Bluetooth Radio                                  | 2        | 3.03%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2        | 3.03%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 2        | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1        | 1.52%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1        | 1.52%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 1.52%   |
| Intel Bluetooth Device                                   | 1        | 1.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 1.52%   |
| IMC Networks Bluetooth Device                            | 1        | 1.52%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.52%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 1.52%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 1        | 1.52%   |
| Broadcom ANYCOM Blue USB-200/250                         | 1        | 1.52%   |
| ASUS Bluetooth Radio                                     | 1        | 1.52%   |
| ASUS BCM20702A0                                          | 1        | 1.52%   |
| Apple Bluetooth USB Host Controller                      | 1        | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 183      | 44.74%  |
| AMD                 | 104      | 25.43%  |
| Nvidia              | 89       | 21.76%  |
| C-Media Electronics | 6        | 1.47%   |
| Logitech            | 5        | 1.22%   |
| Texas Instruments   | 4        | 0.98%   |
| Creative Labs       | 4        | 0.98%   |
| Plantronics         | 2        | 0.49%   |
| Creative Technology | 2        | 0.49%   |
| SteelSeries ApS     | 1        | 0.24%   |
| NEC Computers       | 1        | 0.24%   |
| Lynx                | 1        | 0.24%   |
| JMTek               | 1        | 0.24%   |
| GN Netcom           | 1        | 0.24%   |
| Fry's Electronics   | 1        | 0.24%   |
| Ensoniq             | 1        | 0.24%   |
| Corsair             | 1        | 0.24%   |
| AVID Technology     | 1        | 0.24%   |
| ASUSTek Computer    | 1        | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25       | 5.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 23       | 4.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 23       | 4.91%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 22       | 4.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 19       | 4.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19       | 4.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17       | 3.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 16       | 3.42%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 15       | 3.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15       | 3.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 14       | 2.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 13       | 2.78%   |
| Nvidia High Definition Audio Controller                                                           | 11       | 2.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11       | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11       | 2.35%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 10       | 2.14%   |
| Intel 200 Series PCH HD Audio                                                                     | 9        | 1.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8        | 1.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7        | 1.5%    |
| AMD FCH Azalia Controller                                                                         | 7        | 1.5%    |
| Nvidia TU104 HD Audio Controller                                                                  | 6        | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6        | 1.28%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 6        | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6        | 1.28%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 5        | 1.07%   |
| Intel Comet Lake PCH cAVS                                                                         | 5        | 1.07%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 5        | 1.07%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5        | 1.07%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4        | 0.85%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 4        | 0.85%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 4        | 0.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4        | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3        | 0.64%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 3        | 0.64%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3        | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 0.64%   |
| Intel Audio device                                                                                | 3        | 0.64%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 3        | 0.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 0.64%   |
| AMD Navi 10 HDMI Audio                                                                            | 3        | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2        | 0.43%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 2        | 0.43%   |
| Nvidia MCP73 High Definition Audio                                                                | 2        | 0.43%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2        | 0.43%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2        | 0.43%   |
| Nvidia GM200 High Definition Audio                                                                | 2        | 0.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.43%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2        | 0.43%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2        | 0.43%   |
| Logitech USB Headset                                                                              | 2        | 0.43%   |
| Logitech Headset H390                                                                             | 2        | 0.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2        | 0.43%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2        | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 0.43%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 0.43%   |
| Intel 8 Series HD Audio Controller                                                                | 2        | 0.43%   |
| Creative Technology Sound Blaster Play! 3                                                         | 2        | 0.43%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2        | 0.43%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2        | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 38       | 17.59%  |
| Unknown             | 35       | 16.2%   |
| SK Hynix            | 30       | 13.89%  |
| Samsung Electronics | 30       | 13.89%  |
| Crucial             | 21       | 9.72%   |
| Micron Technology   | 20       | 9.26%   |
| Corsair             | 14       | 6.48%   |
| G.Skill             | 8        | 3.7%    |
| Team                | 4        | 1.85%   |
| A-DATA Technology   | 4        | 1.85%   |
| Patriot             | 3        | 1.39%   |
| Transcend           | 2        | 0.93%   |
| Nanya Technology    | 2        | 0.93%   |
| Unknown (9B0D)      | 1        | 0.46%   |
| TwinMOS             | 1        | 0.46%   |
| Ramaxel Technology  | 1        | 0.46%   |
| Elpida              | 1        | 0.46%   |
| Apacer              | 1        | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s       | 6        | 2.51%   |
| Micron RAM 4ATF51264AZ-2G3B1 4GB DIMM DDR4 2800MT/s       | 4        | 1.67%   |
| Crucial RAM CT16G4DFD824A.C16FDD 16GB DIMM DDR4 2400MT/s  | 4        | 1.67%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 3        | 1.26%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 3        | 1.26%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                      | 2        | 0.84%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2        | 0.84%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 2        | 0.84%   |
| Unknown RAM Module 2048MB DIMM DDR2                       | 2        | 0.84%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1600MT/s             | 2        | 0.84%   |
| SK Hynix RAM Module 16GB DIMM DDR4 3200MT/s               | 2        | 0.84%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2        | 0.84%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 2        | 0.84%   |
| Samsung RAM Module 8192MB DIMM DDR4 3200MT/s              | 2        | 0.84%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1333MT/s        | 2        | 0.84%   |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s        | 2        | 0.84%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s      | 2        | 0.84%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 2        | 0.84%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 2        | 0.84%   |
| Kingston RAM 99U5471-012.A00LF 4096MB DIMM DDR3 1600MT/s  | 2        | 0.84%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s   | 2        | 0.84%   |
| Crucial RAM BLS16G4D26BFSE.16FD 16GB DIMM DDR4 2666MT/s   | 2        | 0.84%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s     | 2        | 0.84%   |
| A-DATA RAM DDR4 2666 2OZ 4GB DIMM DDR4 2667MT/s           | 2        | 0.84%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1        | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 1        | 0.42%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 1        | 0.42%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 0.42%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                   | 1        | 0.42%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                   | 1        | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                  | 1        | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1        | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s               | 1        | 0.42%   |
| Unknown RAM Module 4096MB DIMM 800MT/s                    | 1        | 0.42%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                    | 1        | 0.42%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 1        | 0.42%   |
| Unknown RAM Module 4096MB DIMM                            | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                   | 1        | 0.42%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3 800MT/s             | 1        | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s             | 1        | 0.42%   |
| Unknown RAM Module 2048MB DIMM LPDDR4 1600MT/s            | 1        | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 1        | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 1        | 0.42%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 1        | 0.42%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                    | 1        | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 1        | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1067MT/s                   | 1        | 0.42%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s             | 1        | 0.42%   |
| Unknown RAM Module 16384MB DIMM 1067MT/s                  | 1        | 0.42%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s               | 1        | 0.42%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 1        | 0.42%   |
| Unknown (9B0D) RAM Module 2048MB DIMM DDR2 667MT/s        | 1        | 0.42%   |
| TwinMOS RAM 9DEPBMZ8-TATP 2048MB DIMM DDR3 1333MT/s       | 1        | 0.42%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s          | 1        | 0.42%   |
| Transcend RAM JM800QLU-2G 2048MB DIMM DDR2 2048MT/s       | 1        | 0.42%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s       | 1        | 0.42%   |
| Team RAM TEAMGROUP-UD4-2666 4GB DIMM DDR4 2667MT/s        | 1        | 0.42%   |
| Team RAM TEAMGROUP-UD4-2400 16384MB DIMM DDR4 2400MT/s    | 1        | 0.42%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                | 1        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 77       | 40.74%  |
| DDR3    | 77       | 40.74%  |
| Unknown | 19       | 10.05%  |
| DDR2    | 9        | 4.76%   |
| SDRAM   | 3        | 1.59%   |
| DDR     | 3        | 1.59%   |
| LPDDR4  | 1        | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 176      | 93.12%  |
| SODIMM | 12       | 6.35%   |
| RIMM   | 1        | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 65       | 31.55%  |
| 8192  | 61       | 29.61%  |
| 16384 | 36       | 17.48%  |
| 2048  | 31       | 15.05%  |
| 32768 | 7        | 3.4%    |
| 1024  | 5        | 2.43%   |
| 512   | 1        | 0.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 47       | 23.15%  |
| 1333    | 36       | 17.73%  |
| 2400    | 23       | 11.33%  |
| 2667    | 16       | 7.88%   |
| 2133    | 11       | 5.42%   |
| 3200    | 9        | 4.43%   |
| 800     | 8        | 3.94%   |
| 667     | 8        | 3.94%   |
| 3600    | 6        | 2.96%   |
| 2666    | 6        | 2.96%   |
| 2800    | 5        | 2.46%   |
| Unknown | 5        | 2.46%   |
| 3466    | 3        | 1.48%   |
| 1800    | 3        | 1.48%   |
| 2134    | 2        | 0.99%   |
| 2000    | 2        | 0.99%   |
| 1867    | 2        | 0.99%   |
| 400     | 2        | 0.99%   |
| 4333    | 1        | 0.49%   |
| 3733    | 1        | 0.49%   |
| 3500    | 1        | 0.49%   |
| 3100    | 1        | 0.49%   |
| 3000    | 1        | 0.49%   |
| 2733    | 1        | 0.49%   |
| 2465    | 1        | 0.49%   |
| 2048    | 1        | 0.49%   |
| 1067    | 1        | 0.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 5        | 50%     |
| Brother Industries | 3        | 30%     |
| Kyocera            | 1        | 10%     |
| Canon              | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| HP DeskJet 2130 series   | 2        | 20%     |
| Kyocera FS-1030D printer | 1        | 10%     |
| HP LaserJet 400 M401dne  | 1        | 10%     |
| HP LaserJet 3030         | 1        | 10%     |
| HP LaserJet 1020         | 1        | 10%     |
| Canon MF210 Series       | 1        | 10%     |
| Brother MFC-J450DW       | 1        | 10%     |
| Brother MFC-9130CW       | 1        | 10%     |
| Brother HL-L2390DW       | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 11       | 42.31%  |
| Microdia               | 4        | 15.38%  |
| Samsung Electronics    | 2        | 7.69%   |
| Realtek Semiconductor  | 2        | 7.69%   |
| Lenovo                 | 2        | 7.69%   |
| Microsoft              | 1        | 3.85%   |
| Generalplus Technology | 1        | 3.85%   |
| Cubeternet             | 1        | 3.85%   |
| Creative Technology    | 1        | 3.85%   |
| Chicony Electronics    | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech HD Webcam C615                     | 3        | 11.54%  |
| Logitech HD Pro Webcam C920                 | 3        | 11.54%  |
| Samsung Galaxy A5 (MTP)                     | 2        | 7.69%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 2        | 7.69%   |
| Microdia Camera                             | 2        | 7.69%   |
| Logitech Webcam C270                        | 2        | 7.69%   |
| Lenovo FHD Webcam                           | 2        | 7.69%   |
| Realtek Web Camera                          | 1        | 3.85%   |
| Realtek Laptop_Integrated_Webcam_FHD        | 1        | 3.85%   |
| Microsoft LifeCam HD-5000                   | 1        | 3.85%   |
| Logitech Webcam C930e                       | 1        | 3.85%   |
| Logitech Webcam C310                        | 1        | 3.85%   |
| Logitech StreamCam                          | 1        | 3.85%   |
| Generalplus 808 Camera #9 (web-cam mode)    | 1        | 3.85%   |
| Cubeternet USB2.0 Camera                    | 1        | 3.85%   |
| Creative Live! Cam Chat HD [VF0700]         | 1        | 3.85%   |
| Chicony HP Integrated Webcam                | 1        | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SCM Microsystems    | 2        | 40%     |
| Giesecke & Devrient | 2        | 40%     |
| Cherry              | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Giesecke & Devrient StarSign CUT S                         | 2        | 40%     |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader | 1        | 20%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1        | 20%     |
| Cherry SmartCard Reader Keyboard KC 1000 SC                | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 213      | 73.45%  |
| 1     | 59       | 20.34%  |
| 2     | 11       | 3.79%   |
| 4     | 4        | 1.38%   |
| 3     | 3        | 1.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 36       | 35.29%  |
| Communication controller | 17       | 16.67%  |
| Unassigned class         | 14       | 13.73%  |
| Net/wireless             | 14       | 13.73%  |
| Storage/ide              | 6        | 5.88%   |
| Net/ethernet             | 5        | 4.9%    |
| Sound                    | 4        | 3.92%   |
| Network                  | 3        | 2.94%   |
| Storage/raid             | 1        | 0.98%   |
| Multimedia controller    | 1        | 0.98%   |
| Card reader              | 1        | 0.98%   |

