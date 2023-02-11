Lubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_22.04/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 235

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | Notebook    | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| MSI           | MS-7032                     | Desktop     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | Desktop     | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | Desktop     | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | Notebook    | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [6ef8fba020](https://linux-hardware.org/?probe=6ef8fba020) | Jan 06, 2023 |
| ASUSTek       | F50SV                       | Notebook    | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | Notebook    | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Google        | Candy                       | Notebook    | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fd1cdfc132](https://linux-hardware.org/?probe=fd1cdfc132) | Dec 28, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Intel         | BTC-T37                     | Desktop     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [2574454ebe](https://linux-hardware.org/?probe=2574454ebe) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3b7077c5ab](https://linux-hardware.org/?probe=3b7077c5ab) | Nov 19, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a922f68180](https://linux-hardware.org/?probe=a922f68180) | Nov 03, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | Desktop     | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Dell          | 0R849J A00                  | Desktop     | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| ASUSTek       | UX360CAK                    | Convertible | [015df11bc4](https://linux-hardware.org/?probe=015df11bc4) | Sep 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c45724d6d3](https://linux-hardware.org/?probe=c45724d6d3) | Sep 20, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2f9ab4273a](https://linux-hardware.org/?probe=2f9ab4273a) | Sep 20, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | Notebook    | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Dell          | 0J584C A00                  | Desktop     | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | Notebook    | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 8768 A                      | Desktop     | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | Desktop     | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | Desktop     | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.0-43-generic           | 31        | 16.4%   |
| 5.15.0-56-generic           | 16        | 8.47%   |
| 5.15.0-25-generic           | 13        | 6.88%   |
| 5.15.0-47-generic           | 12        | 6.35%   |
| 5.15.0-30-generic           | 10        | 5.29%   |
| 5.15.0-46-generic           | 9         | 4.76%   |
| 5.15.0-41-generic           | 9         | 4.76%   |
| 5.15.0-27-generic           | 9         | 4.76%   |
| 5.15.0-53-generic           | 8         | 4.23%   |
| 5.15.0-52-generic           | 8         | 4.23%   |
| 5.15.0-58-generic           | 7         | 3.7%    |
| 5.15.0-50-generic           | 6         | 3.17%   |
| 5.15.0-48-generic           | 6         | 3.17%   |
| 5.15.0-40-generic           | 6         | 3.17%   |
| 5.15.0-57-generic           | 5         | 2.65%   |
| 5.15.0-39-generic           | 4         | 2.12%   |
| 5.15.0-35-generic           | 4         | 2.12%   |
| 5.15.0-33-generic           | 4         | 2.12%   |
| 5.15.0-37-generic           | 2         | 1.06%   |
| 5.15.0-23-generic           | 2         | 1.06%   |
| 5.15.0-18-generic           | 2         | 1.06%   |
| 6.1.0-custom                | 1         | 0.53%   |
| 6.0.8-060008-generic        | 1         | 0.53%   |
| 6.0.12-x64v2-xanmod1        | 1         | 0.53%   |
| 6.0.10-rockchip64           | 1         | 0.53%   |
| 5.19.8-xanmod1              | 1         | 0.53%   |
| 5.19.11-ux360cak            | 1         | 0.53%   |
| 5.19.0-16.2-liquorix-amd64  | 1         | 0.53%   |
| 5.19.0-051900-generic       | 1         | 0.53%   |
| 5.18.0-051800-generic       | 1         | 0.53%   |
| 5.15.0-59-lowlatency        | 1         | 0.53%   |
| 5.15.0-54-generic           | 1         | 0.53%   |
| 5.15.0-41-lowlatency        | 1         | 0.53%   |
| 5.15.0-362206031516-generic | 1         | 0.53%   |
| 5.15.0-28-generic           | 1         | 0.53%   |
| 5.15.0-1017-raspi           | 1         | 0.53%   |
| 5.14.0-1040-oem             | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 168       | 94.38%  |
| 5.19.0  | 2         | 1.12%   |
| 6.1.0   | 1         | 0.56%   |
| 6.0.8   | 1         | 0.56%   |
| 6.0.12  | 1         | 0.56%   |
| 6.0.10  | 1         | 0.56%   |
| 5.19.8  | 1         | 0.56%   |
| 5.19.11 | 1         | 0.56%   |
| 5.18.0  | 1         | 0.56%   |
| 5.14.0  | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 168       | 94.38%  |
| 5.19    | 4         | 2.25%   |
| 6.0     | 3         | 1.69%   |
| 6.1     | 1         | 0.56%   |
| 5.18    | 1         | 0.56%   |
| 5.14    | 1         | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 172       | 98.85%  |
| aarch64 | 2         | 1.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 167       | 95.43%  |
| LXDE       | 4         | 2.29%   |
| X-Cinnamon | 2         | 1.14%   |
| XFCE       | 1         | 0.57%   |
| GNOME      | 1         | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 168       | 95.45%  |
| Tty         | 6         | 3.41%   |
| Wayland     | 1         | 0.57%   |
| Unspecified | 1         | 0.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 151       | 85.8%   |
| Unknown | 10        | 5.68%   |
| LightDM | 9         | 5.11%   |
| GDM3    | 3         | 1.7%    |
| XDM     | 1         | 0.57%   |
| SLiM    | 1         | 0.57%   |
| LXDM    | 1         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 45        | 25.71%  |
| fr_FR  | 17        | 9.71%   |
| it_IT  | 13        | 7.43%   |
| de_DE  | 13        | 7.43%   |
| en_GB  | 10        | 5.71%   |
| C      | 9         | 5.14%   |
| pt_BR  | 7         | 4%      |
| pl_PL  | 7         | 4%      |
| en_AG  | 7         | 4%      |
| es_ES  | 6         | 3.43%   |
| nl_BE  | 4         | 2.29%   |
| es_CR  | 4         | 2.29%   |
| es_AR  | 4         | 2.29%   |
| ru_RU  | 3         | 1.71%   |
| es_MX  | 3         | 1.71%   |
| en_AU  | 3         | 1.71%   |
| en_CA  | 2         | 1.14%   |
| el_GR  | 2         | 1.14%   |
| tr_TR  | 1         | 0.57%   |
| sv_SE  | 1         | 0.57%   |
| ru_UA  | 1         | 0.57%   |
| lzh_TW | 1         | 0.57%   |
| ja_JP  | 1         | 0.57%   |
| hu_HU  | 1         | 0.57%   |
| fr_CA  | 1         | 0.57%   |
| fi_FI  | 1         | 0.57%   |
| es_EC  | 1         | 0.57%   |
| es_CO  | 1         | 0.57%   |
| es_CL  | 1         | 0.57%   |
| en_ZA  | 1         | 0.57%   |
| en_PH  | 1         | 0.57%   |
| en_DE  | 1         | 0.57%   |
| cv_RU  | 1         | 0.57%   |
| aa_DJ  | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 116       | 66.29%  |
| EFI  | 59        | 33.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 162       | 92.05%  |
| Overlay | 10        | 5.68%   |
| Btrfs   | 3         | 1.7%    |
| Ext2    | 1         | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 78        | 44.07%  |
| MBR     | 52        | 29.38%  |
| Unknown | 47        | 26.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 153       | 87.43%  |
| Yes       | 22        | 12.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 124       | 70.86%  |
| Yes       | 51        | 29.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 25        | 14.37%  |
| Dell                    | 22        | 12.64%  |
| ASUSTek Computer        | 21        | 12.07%  |
| Hewlett-Packard         | 18        | 10.34%  |
| Acer                    | 11        | 6.32%   |
| MSI                     | 9         | 5.17%   |
| Google                  | 6         | 3.45%   |
| Apple                   | 6         | 3.45%   |
| Unknown                 | 6         | 3.45%   |
| Fujitsu                 | 5         | 2.87%   |
| ASRock                  | 5         | 2.87%   |
| AMI                     | 4         | 2.3%    |
| Sony                    | 3         | 1.72%   |
| Intel                   | 3         | 1.72%   |
| Gigabyte Technology     | 3         | 1.72%   |
| Toshiba                 | 2         | 1.15%   |
| Positivo                | 2         | 1.15%   |
| OEM                     | 2         | 1.15%   |
| Mediacom                | 2         | 1.15%   |
| Gateway                 | 2         | 1.15%   |
| ZOTAC                   | 1         | 0.57%   |
| Thomson                 | 1         | 0.57%   |
| SGIN                    | 1         | 0.57%   |
| Samsung Electronics     | 1         | 0.57%   |
| Rockchip                | 1         | 0.57%   |
| Raspberry Pi Foundation | 1         | 0.57%   |
| Pretech                 | 1         | 0.57%   |
| Prestigio               | 1         | 0.57%   |
| Pegatron                | 1         | 0.57%   |
| Packard Bell            | 1         | 0.57%   |
| NEC Computers           | 1         | 0.57%   |
| Kiano                   | 1         | 0.57%   |
| IFSA                    | 1         | 0.57%   |
| GPU Company             | 1         | 0.57%   |
| Fujitsu Siemens         | 1         | 0.57%   |
| Chuwi                   | 1         | 0.57%   |
| Alienware               | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 4.02%   |
| Apple MacBookPro8,1                        | 3         | 1.72%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 1.15%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 1.15%   |
| Lenovo G50-30 80G0                         | 2         | 1.15%   |
| HP Pavilion g6                             | 2         | 1.15%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 1.15%   |
| Dell Dimension 9100                        | 2         | 1.15%   |
| ZOTAC NM10                                 | 1         | 0.57%   |
| Toshiba Satellite Pro S500                 | 1         | 0.57%   |
| Toshiba Satellite L40                      | 1         | 0.57%   |
| Thomson N14C4WH64                          | 1         | 0.57%   |
| Sony VPCEB15FM                             | 1         | 0.57%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.57%   |
| Sony SVE14A2V1EW                           | 1         | 0.57%   |
| SGIN laptop                                | 1         | 0.57%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.57%   |
| Rockchip RK3318 BOX                        | 1         | 0.57%   |
| RPi Raspberry Pi                           | 1         | 0.57%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.57%   |
| Prestigio PSB141C01BFH                     | 1         | 0.57%   |
| Positivo POS-AG31AP                        | 1         | 0.57%   |
| Positivo i500pro                           | 1         | 0.57%   |
| Pegatron AY748AA-ABA p6320y                | 1         | 0.57%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.57%   |
| OEM M882CWP                                | 1         | 0.57%   |
| NEC Computers ECS-945G                     | 1         | 0.57%   |
| MSI MS-7D09                                | 1         | 0.57%   |
| MSI MS-7C96                                | 1         | 0.57%   |
| MSI MS-7C51                                | 1         | 0.57%   |
| MSI MS-7C37                                | 1         | 0.57%   |
| MSI MS-7B86                                | 1         | 0.57%   |
| MSI MS-7978                                | 1         | 0.57%   |
| MSI MS-7641                                | 1         | 0.57%   |
| MSI MS-7501                                | 1         | 0.57%   |
| MSI MS-7032                                | 1         | 0.57%   |
| Lenovo Z70-80 80FG                         | 1         | 0.57%   |
| Lenovo Yoga C940-14IIL 81Q9                | 1         | 0.57%   |
| Lenovo ThinkPad X220 4291H82               | 1         | 0.57%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE02   | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 7         | 4.02%   |
| Dell Latitude          | 7         | 4.02%   |
| Acer Aspire            | 7         | 4.02%   |
| Unknown                | 7         | 4.02%   |
| Lenovo IdeaPad         | 6         | 3.45%   |
| HP Pavilion            | 4         | 2.3%    |
| Fujitsu LIFEBOOK       | 4         | 2.3%    |
| HP ProBook             | 3         | 1.72%   |
| Dell OptiPlex          | 3         | 1.72%   |
| Apple MacBookPro8      | 3         | 1.72%   |
| Toshiba Satellite      | 2         | 1.15%   |
| Mediacom WinPad        | 2         | 1.15%   |
| Lenovo ThinkCentre     | 2         | 1.15%   |
| Lenovo G50-30          | 2         | 1.15%   |
| HP Compaq              | 2         | 1.15%   |
| Dell XPS               | 2         | 1.15%   |
| Dell Vostro            | 2         | 1.15%   |
| Dell Studio            | 2         | 1.15%   |
| Dell Precision         | 2         | 1.15%   |
| Dell Dimension         | 2         | 1.15%   |
| ASUS PRIME             | 2         | 1.15%   |
| ZOTAC NM10             | 1         | 0.57%   |
| Thomson N14C4WH64      | 1         | 0.57%   |
| Sony VPCEB15FM         | 1         | 0.57%   |
| Sony VGN-SZ71WN        | 1         | 0.57%   |
| Sony SVE14A2V1EW       | 1         | 0.57%   |
| SGIN laptop            | 1         | 0.57%   |
| Samsung 300V3A         | 1         | 0.57%   |
| Rockchip RK3318        | 1         | 0.57%   |
| RPi Raspberry          | 1         | 0.57%   |
| Pretech EVE            | 1         | 0.57%   |
| Prestigio PSB141C01BFH | 1         | 0.57%   |
| Positivo POS-AG31AP    | 1         | 0.57%   |
| Positivo i500pro       | 1         | 0.57%   |
| Pegatron AY748AA-ABA   | 1         | 0.57%   |
| Packard Bell EasyNote  | 1         | 0.57%   |
| OEM M882CWP            | 1         | 0.57%   |
| NEC Computers ECS-945G | 1         | 0.57%   |
| MSI MS-7D09            | 1         | 0.57%   |
| MSI MS-7C96            | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 20        | 11.49%  |
| 2014    | 13        | 7.47%   |
| 2008    | 13        | 7.47%   |
| 2020    | 12        | 6.9%    |
| 2019    | 12        | 6.9%    |
| 2013    | 12        | 6.9%    |
| 2021    | 11        | 6.32%   |
| 2015    | 11        | 6.32%   |
| 2010    | 11        | 6.32%   |
| 2009    | 11        | 6.32%   |
| 2016    | 10        | 5.75%   |
| 2012    | 9         | 5.17%   |
| 2017    | 8         | 4.6%    |
| 2007    | 7         | 4.02%   |
| 2022    | 6         | 3.45%   |
| 2018    | 3         | 1.72%   |
| 2006    | 2         | 1.15%   |
| Unknown | 2         | 1.15%   |
| 2001    | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 107       | 61.49%  |
| Desktop        | 55        | 31.61%  |
| Convertible    | 4         | 2.3%    |
| Tablet         | 3         | 1.72%   |
| System on chip | 2         | 1.15%   |
| Mini pc        | 2         | 1.15%   |
| All in one     | 1         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 169       | 97.13%  |
| Enabled  | 5         | 2.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 167       | 95.98%  |
| Yes  | 7         | 4.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 62        | 35.43%  |
| 4.01-8.0    | 38        | 21.71%  |
| 8.01-16.0   | 21        | 12%     |
| 1.01-2.0    | 20        | 11.43%  |
| 16.01-24.0  | 17        | 9.71%   |
| 32.01-64.0  | 7         | 4%      |
| 2.01-3.0    | 6         | 3.43%   |
| 0.51-1.0    | 3         | 1.71%   |
| 64.01-256.0 | 1         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 87        | 47.8%   |
| 0.51-1.0  | 46        | 25.27%  |
| 2.01-3.0  | 32        | 17.58%  |
| 4.01-8.0  | 8         | 4.4%    |
| 3.01-4.0  | 7         | 3.85%   |
| 8.01-16.0 | 1         | 0.55%   |
| 0.01-0.5  | 1         | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 124       | 70.45%  |
| 2      | 38        | 21.59%  |
| 3      | 5         | 2.84%   |
| 0      | 3         | 1.7%    |
| 5      | 2         | 1.14%   |
| 4      | 2         | 1.14%   |
| 7      | 1         | 0.57%   |
| 6      | 1         | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 58.05%  |
| Yes       | 73        | 41.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 79.89%  |
| No        | 35        | 20.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 74.71%  |
| No        | 44        | 25.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 50.29%  |
| Yes       | 87        | 49.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 27        | 15.52%  |
| Germany      | 19        | 10.92%  |
| France       | 17        | 9.77%   |
| Italy        | 15        | 8.62%   |
| Poland       | 10        | 5.75%   |
| Brazil       | 8         | 4.6%    |
| UK           | 7         | 4.02%   |
| Spain        | 7         | 4.02%   |
| Belgium      | 6         | 3.45%   |
| Ukraine      | 4         | 2.3%    |
| Russia       | 4         | 2.3%    |
| Costa Rica   | 4         | 2.3%    |
| Canada       | 4         | 2.3%    |
| Argentina    | 4         | 2.3%    |
| Mexico       | 3         | 1.72%   |
| Indonesia    | 3         | 1.72%   |
| Australia    | 3         | 1.72%   |
| Vietnam      | 2         | 1.15%   |
| Turkey       | 2         | 1.15%   |
| Sweden       | 2         | 1.15%   |
| Latvia       | 2         | 1.15%   |
| Hungary      | 2         | 1.15%   |
| Greece       | 2         | 1.15%   |
| Taiwan       | 1         | 0.57%   |
| South Africa | 1         | 0.57%   |
| Saudi Arabia | 1         | 0.57%   |
| Romania      | 1         | 0.57%   |
| Portugal     | 1         | 0.57%   |
| Philippines  | 1         | 0.57%   |
| Netherlands  | 1         | 0.57%   |
| Kenya        | 1         | 0.57%   |
| Japan        | 1         | 0.57%   |
| Ireland      | 1         | 0.57%   |
| Finland      | 1         | 0.57%   |
| Ecuador      | 1         | 0.57%   |
| Colombia     | 1         | 0.57%   |
| Chile        | 1         | 0.57%   |
| Bulgaria     | 1         | 0.57%   |
| Belarus      | 1         | 0.57%   |
| Armenia      | 1         | 0.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 5         | 2.78%   |
| Heredia          | 4         | 2.22%   |
| Melbourne        | 3         | 1.67%   |
| Kyiv             | 3         | 1.67%   |
| Ghent            | 3         | 1.67%   |
| Warsaw           | 2         | 1.11%   |
| Sarospatak       | 2         | 1.11%   |
| Porto Alegre     | 2         | 1.11%   |
| Novo Gama        | 2         | 1.11%   |
| Milan            | 2         | 1.11%   |
| Largo            | 2         | 1.11%   |
| Jakarta          | 2         | 1.11%   |
| Zizur Mayor      | 1         | 0.56%   |
| Zawiercie        | 1         | 0.56%   |
| Yoshkar-Ola      | 1         | 0.56%   |
| Yorkville        | 1         | 0.56%   |
| Yerevan          | 1         | 0.56%   |
| Wolfhagen        | 1         | 0.56%   |
| Wetteren         | 1         | 0.56%   |
| West Stockbridge | 1         | 0.56%   |
| Washington       | 1         | 0.56%   |
| Warendorf        | 1         | 0.56%   |
| Volzhskiy        | 1         | 0.56%   |
| Versailles       | 1         | 0.56%   |
| Verona           | 1         | 0.56%   |
| Varna            | 1         | 0.56%   |
| Valentigney      | 1         | 0.56%   |
| Valencia         | 1         | 0.56%   |
| Tychy            | 1         | 0.56%   |
| Thornton Heath   | 1         | 0.56%   |
| Thessaloniki     | 1         | 0.56%   |
| Texas City       | 1         | 0.56%   |
| Taylorsville     | 1         | 0.56%   |
| Tandil           | 1         | 0.56%   |
| Taipei           | 1         | 0.56%   |
| Surabaya         | 1         | 0.56%   |
| Stuttgart        | 1         | 0.56%   |
| Strzyzow         | 1         | 0.56%   |
| Stockholm        | 1         | 0.56%   |
| Southampton      | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 35        | 42     | 16.06%  |
| WDC                       | 25        | 33     | 11.47%  |
| Unknown                   | 22        | 32     | 10.09%  |
| Samsung Electronics       | 20        | 27     | 9.17%   |
| Toshiba                   | 14        | 15     | 6.42%   |
| Hitachi                   | 12        | 15     | 5.5%    |
| Kingston                  | 11        | 12     | 5.05%   |
| SanDisk                   | 10        | 10     | 4.59%   |
| Crucial                   | 5         | 5      | 2.29%   |
| Micron Technology         | 4         | 4      | 1.83%   |
| HGST                      | 4         | 4      | 1.83%   |
| GOODRAM                   | 4         | 4      | 1.83%   |
| A-DATA Technology         | 4         | 4      | 1.83%   |
| Intel                     | 3         | 4      | 1.38%   |
| Apacer                    | 3         | 3      | 1.38%   |
| Transcend                 | 2         | 2      | 0.92%   |
| SPCC                      | 2         | 3      | 0.92%   |
| SK hynix                  | 2         | 2      | 0.92%   |
| Maxtor                    | 2         | 2      | 0.92%   |
| Unknown                   | 2         | 2      | 0.92%   |
| WD MediaMax               | 1         | 1      | 0.46%   |
| W800S                     | 1         | 1      | 0.46%   |
| UMIS                      | 1         | 1      | 0.46%   |
| TO Exter                  | 1         | 1      | 0.46%   |
| Teclast                   | 1         | 1      | 0.46%   |
| Team                      | 1         | 1      | 0.46%   |
| T-FORCE                   | 1         | 1      | 0.46%   |
| RSH-319                   | 1         | 1      | 0.46%   |
| Rogueware                 | 1         | 1      | 0.46%   |
| PNY                       | 1         | 1      | 0.46%   |
| Patriot                   | 1         | 1      | 0.46%   |
| NGFF                      | 1         | 1      | 0.46%   |
| Micron/Crucial Technology | 1         | 1      | 0.46%   |
| LITEONIT                  | 1         | 1      | 0.46%   |
| Lexar                     | 1         | 1      | 0.46%   |
| Leqixiang                 | 1         | 1      | 0.46%   |
| Lenovo                    | 1         | 1      | 0.46%   |
| Kston                     | 1         | 3      | 0.46%   |
| KIOXIA                    | 1         | 1      | 0.46%   |
| KINGPOWER                 | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB          | 5         | 2.1%    |
| Seagate ST500DM002-1BD142 500GB    | 5         | 2.1%    |
| Unknown MMC Card  64GB             | 4         | 1.68%   |
| Kingston SA400S37240G 240GB SSD    | 4         | 1.68%   |
| SanDisk DF4032  32GB               | 3         | 1.26%   |
| Unknown SD/MMC/MS PRO 2GB          | 2         | 0.84%   |
| Unknown SC64G  64GB                | 2         | 0.84%   |
| Unknown NCard  32GB                | 2         | 0.84%   |
| Unknown MMC64G  64GB               | 2         | 0.84%   |
| Unknown MMC Card  32GB             | 2         | 0.84%   |
| Unknown DA4032  32GB               | 2         | 0.84%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.84%   |
| Toshiba MQ01ABD050 500GB           | 2         | 0.84%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.84%   |
| SPCC Solid State Disk 120GB        | 2         | 0.84%   |
| Seagate ST3120213AS 120GB          | 2         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.84%   |
| SanDisk DF4064  64GB               | 2         | 0.84%   |
| Samsung HD502HJ 500GB              | 2         | 0.84%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 0.84%   |
| Apacer 16GB SATA Flash Drive SSD   | 2         | 0.84%   |
| Unknown                            | 2         | 0.84%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.42%   |
| WDC WDS500G2B0A 500GB SSD          | 1         | 0.42%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 0.42%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1         | 0.42%   |
| WDC WD800BB-00CAA1 80GB            | 1         | 0.42%   |
| WDC WD5000LUCT-63RC2Y0 500GB       | 1         | 0.42%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.42%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 0.42%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 1         | 0.42%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1         | 0.42%   |
| WDC WD3200BPVT-80JJ5T0 320GB       | 1         | 0.42%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 0.42%   |
| WDC WD3200BPVT-00HXZT3 320GB       | 1         | 0.42%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 1         | 0.42%   |
| WDC WD30EZRZ-00GXCB0 3TB           | 1         | 0.42%   |
| WDC WD2500KS-00MJB0 250GB          | 1         | 0.42%   |
| WDC WD2500BEVS-22UST0 250GB        | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 41     | 35%     |
| WDC                 | 21        | 24     | 21%     |
| Toshiba             | 12        | 13     | 12%     |
| Hitachi             | 12        | 15     | 12%     |
| Samsung Electronics | 7         | 11     | 7%      |
| HGST                | 4         | 4      | 4%      |
| Unknown             | 2         | 2      | 2%      |
| Maxtor              | 2         | 2      | 2%      |
| WD MediaMax         | 1         | 1      | 1%      |
| RSH-319             | 1         | 1      | 1%      |
| Fujitsu             | 1         | 1      | 1%      |
| External            | 1         | 1      | 1%      |
| Apricorn            | 1         | 1      | 1%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 16.9%   |
| Kingston            | 9         | 10     | 12.68%  |
| SanDisk             | 4         | 4      | 5.63%   |
| GOODRAM             | 4         | 4      | 5.63%   |
| Crucial             | 4         | 4      | 5.63%   |
| A-DATA Technology   | 4         | 4      | 5.63%   |
| WDC                 | 3         | 4      | 4.23%   |
| Apacer              | 3         | 3      | 4.23%   |
| Transcend           | 2         | 2      | 2.82%   |
| Toshiba             | 2         | 2      | 2.82%   |
| SPCC                | 2         | 3      | 2.82%   |
| Micron Technology   | 2         | 2      | 2.82%   |
| Intel               | 2         | 2      | 2.82%   |
| W800S               | 1         | 1      | 1.41%   |
| TO Exter            | 1         | 1      | 1.41%   |
| Teclast             | 1         | 1      | 1.41%   |
| Team                | 1         | 1      | 1.41%   |
| Rogueware           | 1         | 1      | 1.41%   |
| PNY                 | 1         | 1      | 1.41%   |
| Patriot             | 1         | 1      | 1.41%   |
| NGFF                | 1         | 1      | 1.41%   |
| LITEONIT            | 1         | 1      | 1.41%   |
| Lexar               | 1         | 1      | 1.41%   |
| Leqixiang           | 1         | 1      | 1.41%   |
| Lenovo              | 1         | 1      | 1.41%   |
| Kston               | 1         | 3      | 1.41%   |
| KINGPOWER           | 1         | 1      | 1.41%   |
| HUSKY               | 1         | 1      | 1.41%   |
| Gigabyte Technology | 1         | 1      | 1.41%   |
| Emtec               | 1         | 1      | 1.41%   |
| 2.5"                | 1         | 2      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 84        | 117    | 41.58%  |
| SSD     | 68        | 78     | 33.66%  |
| MMC     | 27        | 38     | 13.37%  |
| NVMe    | 20        | 24     | 9.9%    |
| Unknown | 3         | 5      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 132       | 188    | 70.21%  |
| MMC  | 27        | 38     | 14.36%  |
| NVMe | 20        | 24     | 10.64%  |
| SAS  | 9         | 12     | 4.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 110       | 140    | 70.97%  |
| 0.51-1.0   | 31        | 37     | 20%     |
| 1.01-2.0   | 8         | 10     | 5.16%   |
| 2.01-3.0   | 3         | 4      | 1.94%   |
| 4.01-10.0  | 2         | 3      | 1.29%   |
| 3.01-4.0   | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 53        | 29.94%  |
| 251-500        | 41        | 23.16%  |
| 51-100         | 20        | 11.3%   |
| 1-20           | 16        | 9.04%   |
| 21-50          | 15        | 8.47%   |
| 501-1000       | 15        | 8.47%   |
| 1001-2000      | 6         | 3.39%   |
| More than 3000 | 5         | 2.82%   |
| 2001-3000      | 5         | 2.82%   |
| Unknown        | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 96        | 53.63%  |
| 21-50          | 32        | 17.88%  |
| 101-250        | 15        | 8.38%   |
| 51-100         | 14        | 7.82%   |
| 251-500        | 7         | 3.91%   |
| 501-1000       | 6         | 3.35%   |
| More than 3000 | 4         | 2.23%   |
| 1001-2000      | 3         | 1.68%   |
| 2001-3000      | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                 | 2         | 2      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 2      | 7.14%   |
| Apacer 16GB SATA Flash Drive SSD          | 2         | 2      | 7.14%   |
| WDC WD10SPZX-24Z10T0 1TB                  | 1         | 1      | 3.57%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 3.57%   |
| WDC WD10EACS-00D6B1 1TB                   | 1         | 1      | 3.57%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 1      | 3.57%   |
| Toshiba MK6465GSX 640GB                   | 1         | 1      | 3.57%   |
| Seagate ST9320325AS 320GB                 | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 3.57%   |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 1      | 3.57%   |
| Seagate ST320LT020-9YG142 320GB           | 1         | 1      | 3.57%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 3.57%   |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 1      | 3.57%   |
| Samsung Electronics HM121HI 120GB         | 1         | 4      | 3.57%   |
| Samsung Electronics HD161HJ 160GB         | 1         | 1      | 3.57%   |
| NGFF 2280 512GB SSD                       | 1         | 1      | 3.57%   |
| Micron Technology MTFDDAV256TBN 256GB SSD | 1         | 1      | 3.57%   |
| Maxtor 6L200M0 208GB                      | 1         | 1      | 3.57%   |
| Hitachi HTS722080K9SA00 80GB              | 1         | 1      | 3.57%   |
| Hitachi HTS545050A7E380 500GB             | 1         | 1      | 3.57%   |
| Fujitsu MHY2120BH 120GB                   | 1         | 1      | 3.57%   |
| A-DATA Technology SP920SS 256GB SSD       | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 39.29%  |
| WDC                 | 3         | 3      | 10.71%  |
| Toshiba             | 3         | 3      | 10.71%  |
| Samsung Electronics | 2         | 5      | 7.14%   |
| Hitachi             | 2         | 2      | 7.14%   |
| Apacer              | 2         | 2      | 7.14%   |
| NGFF                | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 1      | 3.57%   |
| Maxtor              | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |
| A-DATA Technology   | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 47.83%  |
| WDC                 | 3         | 3      | 13.04%  |
| Toshiba             | 3         | 3      | 13.04%  |
| Samsung Electronics | 2         | 5      | 8.7%    |
| Hitachi             | 2         | 2      | 8.7%    |
| Maxtor              | 1         | 1      | 4.35%   |
| Fujitsu             | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 26     | 82.14%  |
| SSD  | 5         | 5      | 17.86%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 1         | 1      | 50%     |
| HGST HTS725025A7 250GB    | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 95        | 146    | 51.63%  |
| Works    | 59        | 83     | 32.07%  |
| Malfunc  | 28        | 31     | 15.22%  |
| Failed   | 2         | 2      | 1.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 110       | 63.58%  |
| AMD                              | 31        | 17.92%  |
| Nvidia                           | 6         | 3.47%   |
| SanDisk                          | 4         | 2.31%   |
| Samsung Electronics              | 3         | 1.73%   |
| JMicron Technology               | 3         | 1.73%   |
| SK hynix                         | 2         | 1.16%   |
| Micron/Crucial Technology        | 2         | 1.16%   |
| Micron Technology                | 2         | 1.16%   |
| Kingston Technology Company      | 2         | 1.16%   |
| VIA Technologies                 | 1         | 0.58%   |
| Union Memory (Shenzhen)          | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| Silicon Image                    | 1         | 0.58%   |
| Seagate Technology               | 1         | 0.58%   |
| Marvell Technology Group         | 1         | 0.58%   |
| KIOXIA                           | 1         | 0.58%   |
| ASMedia Technology               | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 7.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 5.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 4.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 9         | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 4.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 8         | 3.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 3.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 3.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 2.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 2.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 2.34%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 2.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 1.87%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 1.4%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.93%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.93%   |
| Micron Non-Volatile memory controller                                            | 2         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 0.93%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 0.93%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 0.93%   |
| AMD FCH SATA Controller [IDE mode]                                               | 2         | 0.93%   |
| AMD FCH IDE Controller                                                           | 2         | 0.93%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.47%   |
| VIA VIA VT6420 SATA RAID Controller                                              | 1         | 0.47%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.47%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.47%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 122       | 64.89%  |
| IDE  | 38        | 20.21%  |
| NVMe | 19        | 10.11%  |
| RAID | 9         | 4.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 137       | 78.74%  |
| AMD    | 35        | 20.11%  |
| ARM    | 2         | 1.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 2.87%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 2.3%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 4         | 2.3%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.72%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.72%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 3         | 1.72%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 3         | 1.72%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 1.15%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.15%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.15%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.15%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.15%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.15%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.15%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 1.15%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.15%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.15%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 1.15%   |
| ARM Processor                                 | 2         | 1.15%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.15%   |
| AMD E-450 APU with Radeon HD Graphics         | 2         | 1.15%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.15%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.57%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz           | 1         | 0.57%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.57%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.57%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 0.57%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.57%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.57%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.57%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.57%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.57%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.57%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 27        | 15.52%  |
| Intel Celeron      | 27        | 15.52%  |
| Intel Core 2 Duo   | 18        | 10.34%  |
| Intel Atom         | 18        | 10.34%  |
| Intel Core i3      | 15        | 8.62%   |
| Intel Core i7      | 14        | 8.05%   |
| AMD Ryzen 5        | 6         | 3.45%   |
| Intel Pentium      | 5         | 2.87%   |
| Other              | 3         | 1.72%   |
| Intel Pentium Dual | 3         | 1.72%   |
| AMD FX             | 3         | 1.72%   |
| AMD A6             | 3         | 1.72%   |
| Intel Xeon         | 2         | 1.15%   |
| Intel Pentium D    | 2         | 1.15%   |
| Intel Core 2 Quad  | 2         | 1.15%   |
| Intel Core 2       | 2         | 1.15%   |
| AMD Ryzen 7        | 2         | 1.15%   |
| AMD Phenom II X4   | 2         | 1.15%   |
| AMD E1             | 2         | 1.15%   |
| AMD E              | 2         | 1.15%   |
| AMD Athlon 64 X2   | 2         | 1.15%   |
| AMD A8             | 2         | 1.15%   |
| Intel Core m3      | 1         | 0.57%   |
| Intel Core i9      | 1         | 0.57%   |
| AMD Ryzen 9        | 1         | 0.57%   |
| AMD Ryzen 7 PRO    | 1         | 0.57%   |
| AMD Ryzen 5 PRO    | 1         | 0.57%   |
| AMD Phenom II X6   | 1         | 0.57%   |
| AMD GX             | 1         | 0.57%   |
| AMD G              | 1         | 0.57%   |
| AMD C-60           | 1         | 0.57%   |
| AMD Athlon II X2   | 1         | 0.57%   |
| AMD A4             | 1         | 0.57%   |
| AMD A10            | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 100       | 57.47%  |
| 4       | 54        | 31.03%  |
| 6       | 6         | 3.45%   |
| 1       | 6         | 3.45%   |
| 8       | 4         | 2.3%    |
| 3       | 2         | 1.15%   |
| 10      | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 173       | 99.43%  |
| Unknown | 1         | 0.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 100       | 57.47%  |
| 2       | 73        | 41.95%  |
| Unknown | 1         | 0.57%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 173       | 99.43%  |
| 64-bit         | 1         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 40.57%  |
| 0x406c4    | 9         | 5.14%   |
| 0x206a7    | 9         | 5.14%   |
| 0x306a9    | 6         | 3.43%   |
| 0x1067a    | 6         | 3.43%   |
| 0x706e5    | 4         | 2.29%   |
| 0x6fd      | 4         | 2.29%   |
| 0x406c3    | 4         | 2.29%   |
| 0x806ec    | 3         | 1.71%   |
| 0x706a8    | 3         | 1.71%   |
| 0x40651    | 3         | 1.71%   |
| 0x306c3    | 3         | 1.71%   |
| 0x20655    | 3         | 1.71%   |
| 0x106ca    | 3         | 1.71%   |
| 0x0a50000c | 3         | 1.71%   |
| 0x05000119 | 3         | 1.71%   |
| 0x906c0    | 2         | 1.14%   |
| 0x806ea    | 2         | 1.14%   |
| 0x806e9    | 2         | 1.14%   |
| 0x6fb      | 2         | 1.14%   |
| 0x506e3    | 2         | 1.14%   |
| 0x30678    | 2         | 1.14%   |
| 0x0700010f | 2         | 1.14%   |
| 0x06006705 | 2         | 1.14%   |
| 0x06001119 | 2         | 1.14%   |
| 0xa0653    | 1         | 0.57%   |
| 0x906ed    | 1         | 0.57%   |
| 0x806eb    | 1         | 0.57%   |
| 0x706a1    | 1         | 0.57%   |
| 0x6fa      | 1         | 0.57%   |
| 0x6f6      | 1         | 0.57%   |
| 0x506c9    | 1         | 0.57%   |
| 0x406e3    | 1         | 0.57%   |
| 0x30679    | 1         | 0.57%   |
| 0x106a5    | 1         | 0.57%   |
| 0x10676    | 1         | 0.57%   |
| 0x0a50000b | 1         | 0.57%   |
| 0x0a201009 | 1         | 0.57%   |
| 0x08701021 | 1         | 0.57%   |
| 0x08001138 | 1         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 27        | 15.52%  |
| SandyBridge   | 16        | 9.2%    |
| Penryn        | 14        | 8.05%   |
| Core          | 12        | 6.9%    |
| KabyLake      | 10        | 5.75%   |
| IvyBridge     | 10        | 5.75%   |
| Haswell       | 10        | 5.75%   |
| Goldmont plus | 8         | 4.6%    |
| Zen 3         | 5         | 2.87%   |
| Westmere      | 5         | 2.87%   |
| Piledriver    | 5         | 2.87%   |
| Bonnell       | 5         | 2.87%   |
| Skylake       | 4         | 2.3%    |
| K10           | 4         | 2.3%    |
| IceLake       | 4         | 2.3%    |
| Bobcat        | 4         | 2.3%    |
| Zen+          | 3         | 1.72%   |
| K8 Hammer     | 3         | 1.72%   |
| Zen           | 2         | 1.15%   |
| Tremont       | 2         | 1.15%   |
| NetBurst      | 2         | 1.15%   |
| Nehalem       | 2         | 1.15%   |
| Jaguar        | 2         | 1.15%   |
| Goldmont      | 2         | 1.15%   |
| Excavator     | 2         | 1.15%   |
| CometLake     | 2         | 1.15%   |
| Broadwell     | 2         | 1.15%   |
| Unknown       | 2         | 1.15%   |
| Zen 2         | 1         | 0.57%   |
| Steamroller   | 1         | 0.57%   |
| Puma          | 1         | 0.57%   |
| K10 Llano     | 1         | 0.57%   |
| Bulldozer     | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 109       | 58.92%  |
| AMD    | 43        | 23.24%  |
| Nvidia | 33        | 17.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 8.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 7.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 4.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 3.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 3.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 3.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 3.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.99%   |
| Nvidia GT218 [ION]                                                                       | 3         | 1.49%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.49%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.49%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 1.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.49%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 1%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1%      |
| Intel UHD Graphics 620                                                                   | 2         | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1%      |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1%      |
| Intel Iris Plus Graphics G7                                                              | 2         | 1%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1%      |
| Intel HD Graphics 5500                                                                   | 2         | 1%      |
| Intel HD Graphics 500                                                                    | 2         | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1%      |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 1%      |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 1%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1%      |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1%      |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 1%      |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2         | 1%      |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2         | 1%      |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1         | 0.5%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.5%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.5%    |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.5%    |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.5%    |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 95        | 54.6%   |
| 1 x AMD            | 30        | 17.24%  |
| 1 x Nvidia         | 27        | 15.52%  |
| 2 x AMD            | 6         | 3.45%   |
| Intel + AMD        | 5         | 2.87%   |
| Other              | 4         | 2.3%    |
| Intel + Nvidia     | 4         | 2.3%    |
| Intel + 2 x Nvidia | 1         | 0.57%   |
| Intel + 2 x AMD    | 1         | 0.57%   |
| AMD + Nvidia       | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 158       | 90.8%   |
| Proprietary | 9         | 5.17%   |
| Unknown     | 7         | 4.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 135       | 77.14%  |
| 0.01-0.5   | 17        | 9.71%   |
| 1.01-2.0   | 6         | 3.43%   |
| 0.51-1.0   | 6         | 3.43%   |
| 7.01-8.0   | 4         | 2.29%   |
| 3.01-4.0   | 2         | 1.14%   |
| 2.01-3.0   | 2         | 1.14%   |
| 8.01-16.0  | 2         | 1.14%   |
| 5.01-6.0   | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 13.77%  |
| LG Display              | 22        | 13.17%  |
| Samsung Electronics     | 20        | 11.98%  |
| Chimei Innolux          | 15        | 8.98%   |
| BOE                     | 11        | 6.59%   |
| Hewlett-Packard         | 8         | 4.79%   |
| Goldstar                | 8         | 4.79%   |
| Dell                    | 7         | 4.19%   |
| Apple                   | 6         | 3.59%   |
| CPT                     | 5         | 2.99%   |
| Philips                 | 4         | 2.4%    |
| Lenovo                  | 3         | 1.8%    |
| Chi Mei Optoelectronics | 3         | 1.8%    |
| Ancor Communications    | 3         | 1.8%    |
| Acer                    | 3         | 1.8%    |
| Sharp                   | 2         | 1.2%    |
| LG Philips              | 2         | 1.2%    |
| Eizo                    | 2         | 1.2%    |
| BenQ                    | 2         | 1.2%    |
| Vizio                   | 1         | 0.6%    |
| ViewSonic               | 1         | 0.6%    |
| VHT                     | 1         | 0.6%    |
| Unknown                 | 1         | 0.6%    |
| Toshiba                 | 1         | 0.6%    |
| Sony                    | 1         | 0.6%    |
| SNC                     | 1         | 0.6%    |
| Sampo                   | 1         | 0.6%    |
| Positivo                | 1         | 0.6%    |
| MSI                     | 1         | 0.6%    |
| LG Electronics          | 1         | 0.6%    |
| JVC                     | 1         | 0.6%    |
| JDI                     | 1         | 0.6%    |
| InfoVision              | 1         | 0.6%    |
| HannStar                | 1         | 0.6%    |
| Daewoo                  | 1         | 0.6%    |
| CS_                     | 1         | 0.6%    |
| AOC                     | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 4         | 2.38%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 2         | 1.19%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.19%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.19%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.19%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1         | 0.6%    |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 0.6%    |
| VHT Monitor VHTDDDD 1024x768                                          | 1         | 0.6%    |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1         | 0.6%    |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 0.6%    |
| Sony TV SNY9C01 1360x768                                              | 1         | 0.6%    |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 1         | 0.6%    |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.6%    |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch              | 1         | 0.6%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch  | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch  | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch   | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.6%    |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch    | 1         | 0.6%    |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch  | 1         | 0.6%    |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch    | 1         | 0.6%    |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                         | 1         | 0.6%    |
| Positivo SMILE4XX NON1400 1360x768 309x174mm 14.0-inch                | 1         | 0.6%    |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 1         | 0.6%    |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch             | 1         | 0.6%    |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                  | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 56        | 34.36%  |
| 1920x1080 (FHD)    | 42        | 25.77%  |
| 1280x800 (WXGA)    | 15        | 9.2%    |
| 1600x900 (HD+)     | 12        | 7.36%   |
| 1680x1050 (WSXGA+) | 7         | 4.29%   |
| 2560x1440 (QHD)    | 5         | 3.07%   |
| 1440x900 (WXGA+)   | 5         | 3.07%   |
| 1280x1024 (SXGA)   | 5         | 3.07%   |
| 1360x768           | 3         | 1.84%   |
| 3840x2160 (4K)     | 2         | 1.23%   |
| 800x600            | 1         | 0.61%   |
| 3200x1800 (QHD+)   | 1         | 0.61%   |
| 3000x2000          | 1         | 0.61%   |
| 2560x1600          | 1         | 0.61%   |
| 2560x1080          | 1         | 0.61%   |
| 2160x1440          | 1         | 0.61%   |
| 1920x1200 (WUXGA)  | 1         | 0.61%   |
| 1528x1222          | 1         | 0.61%   |
| 1280x768           | 1         | 0.61%   |
| 1280x720 (HD)      | 1         | 0.61%   |
| 1024x768 (XGA)     | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 36        | 21.69%  |
| 14      | 22        | 13.25%  |
| 13      | 20        | 12.05%  |
| 11      | 11        | 6.63%   |
| 17      | 9         | 5.42%   |
| 23      | 8         | 4.82%   |
| 18      | 7         | 4.22%   |
| 24      | 6         | 3.61%   |
| 22      | 6         | 3.61%   |
| 21      | 6         | 3.61%   |
| 19      | 6         | 3.61%   |
| Unknown | 6         | 3.61%   |
| 27      | 5         | 3.01%   |
| 20      | 4         | 2.41%   |
| 12      | 3         | 1.81%   |
| 10      | 2         | 1.2%    |
| 72      | 1         | 0.6%    |
| 49      | 1         | 0.6%    |
| 47      | 1         | 0.6%    |
| 43      | 1         | 0.6%    |
| 34      | 1         | 0.6%    |
| 28      | 1         | 0.6%    |
| 16      | 1         | 0.6%    |
| 9       | 1         | 0.6%    |
| 8       | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 67        | 40.36%  |
| 201-300     | 29        | 17.47%  |
| 401-500     | 28        | 16.87%  |
| 501-600     | 18        | 10.84%  |
| 351-400     | 9         | 5.42%   |
| Unknown     | 6         | 3.61%   |
| 601-700     | 2         | 1.2%    |
| 101-200     | 2         | 1.2%    |
| 1001-1500   | 2         | 1.2%    |
| 701-800     | 1         | 0.6%    |
| 1501-2000   | 1         | 0.6%    |
| 901-1000    | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 113       | 71.97%  |
| 16/10   | 30        | 19.11%  |
| 4/3     | 4         | 2.55%   |
| Unknown | 4         | 2.55%   |
| 5/4     | 3         | 1.91%   |
| 3/2     | 2         | 1.27%   |
| 21/9    | 1         | 0.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 36        | 21.82%  |
| 101-110        | 35        | 21.21%  |
| 201-250        | 22        | 13.33%  |
| 151-200        | 12        | 7.27%   |
| 51-60          | 11        | 6.67%   |
| 141-150        | 8         | 4.85%   |
| 121-130        | 7         | 4.24%   |
| 71-80          | 6         | 3.64%   |
| Unknown        | 6         | 3.64%   |
| 301-350        | 5         | 3.03%   |
| 61-70          | 3         | 1.82%   |
| 41-50          | 3         | 1.82%   |
| 251-300        | 3         | 1.82%   |
| 501-1000       | 3         | 1.82%   |
| More than 1000 | 2         | 1.21%   |
| 1-40           | 1         | 0.61%   |
| 131-140        | 1         | 0.61%   |
| 111-120        | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 60        | 36.81%  |
| 51-100        | 48        | 29.45%  |
| 121-160       | 33        | 20.25%  |
| 161-240       | 9         | 5.52%   |
| Unknown       | 6         | 3.68%   |
| 1-50          | 5         | 3.07%   |
| More than 240 | 2         | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 156       | 89.66%  |
| 2     | 12        | 6.9%    |
| 0     | 5         | 2.87%   |
| 3     | 1         | 0.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 85        | 34.27%  |
| Intel                           | 64        | 25.81%  |
| Qualcomm Atheros                | 37        | 14.92%  |
| Broadcom                        | 15        | 6.05%   |
| TP-Link                         | 6         | 2.42%   |
| Marvell Technology Group        | 6         | 2.42%   |
| Samsung Electronics             | 5         | 2.02%   |
| Qualcomm Atheros Communications | 4         | 1.61%   |
| Nvidia                          | 4         | 1.61%   |
| Broadcom Limited                | 4         | 1.61%   |
| Qualcomm                        | 2         | 0.81%   |
| NetGear                         | 2         | 0.81%   |
| MediaTek                        | 2         | 0.81%   |
| ASIX Electronics                | 2         | 0.81%   |
| VIA Technologies                | 1         | 0.4%    |
| Trident Microsystems            | 1         | 0.4%    |
| Sierra Wireless                 | 1         | 0.4%    |
| Ralink Technology               | 1         | 0.4%    |
| Ralink                          | 1         | 0.4%    |
| Microsoft                       | 1         | 0.4%    |
| JMicron Technology              | 1         | 0.4%    |
| ICS Advent                      | 1         | 0.4%    |
| Belkin Components               | 1         | 0.4%    |
| ASUSTek Computer                | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 18.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 3.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 2.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 2.06%   |
| Intel Wireless 7265                                               | 6         | 2.06%   |
| Intel Wireless 7260                                               | 6         | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 1.37%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.03%   |
| Realtek 802.11n WLAN Adapter                                      | 3         | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.03%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.03%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.03%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 1.03%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.03%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.69%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.69%   |
| NetGear A6210                                                     | 2         | 0.69%   |
| Intel Wireless 8260                                               | 2         | 0.69%   |
| Intel Wireless 3160                                               | 2         | 0.69%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2         | 0.69%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 35.46%  |
| Qualcomm Atheros                | 33        | 23.4%   |
| Realtek Semiconductor           | 28        | 19.86%  |
| Broadcom                        | 9         | 6.38%   |
| TP-Link                         | 5         | 3.55%   |
| Qualcomm Atheros Communications | 4         | 2.84%   |
| NetGear                         | 2         | 1.42%   |
| MediaTek                        | 2         | 1.42%   |
| Broadcom Limited                | 2         | 1.42%   |
| Sierra Wireless                 | 1         | 0.71%   |
| Ralink Technology               | 1         | 0.71%   |
| Ralink                          | 1         | 0.71%   |
| Microsoft                       | 1         | 0.71%   |
| Belkin Components               | 1         | 0.71%   |
| ASUSTek Computer                | 1         | 0.71%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 6         | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 6         | 4.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 6         | 4.26%   |
| Intel Wireless 7265                                                 | 6         | 4.26%   |
| Intel Wireless 7260                                                 | 6         | 4.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 5         | 3.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 4         | 2.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 4         | 2.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 4         | 2.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 4         | 2.84%   |
| Realtek 802.11n WLAN Adapter                                        | 3         | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                     | 3         | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 3         | 2.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection       | 3         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 3         | 2.13%   |
| Intel Centrino Wireless-N 2230                                      | 3         | 2.13%   |
| Intel Centrino Advanced-N 6235                                      | 3         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 3         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 1.42%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2         | 1.42%   |
| NetGear A6210                                                       | 2         | 1.42%   |
| Intel Wireless 8260                                                 | 2         | 1.42%   |
| Intel Wireless 3160                                                 | 2         | 1.42%   |
| Intel Centrino Advanced-N 6200                                      | 2         | 1.42%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 1.42%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 2         | 1.42%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2         | 1.42%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1         | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1         | 0.71%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1         | 0.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1         | 0.71%   |
| TP-Link 802.11ac NIC                                                | 1         | 0.71%   |
| Sierra Wireless EM7305 Modem                                        | 1         | 0.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1         | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1         | 0.71%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 1         | 0.71%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1         | 0.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 1         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1         | 0.71%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 73        | 48.99%  |
| Intel                    | 29        | 19.46%  |
| Qualcomm Atheros         | 12        | 8.05%   |
| Broadcom                 | 9         | 6.04%   |
| Marvell Technology Group | 6         | 4.03%   |
| Samsung Electronics      | 5         | 3.36%   |
| Nvidia                   | 4         | 2.68%   |
| Qualcomm                 | 2         | 1.34%   |
| Broadcom Limited         | 2         | 1.34%   |
| ASIX Electronics         | 2         | 1.34%   |
| VIA Technologies         | 1         | 0.67%   |
| Trident Microsystems     | 1         | 0.67%   |
| TP-Link                  | 1         | 0.67%   |
| JMicron Technology       | 1         | 0.67%   |
| ICS Advent               | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 55        | 36.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 5.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.67%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 2%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 2%      |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 2%      |
| Intel Ethernet Controller I225-V                                               | 3         | 2%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 2%      |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.33%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 1.33%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 2         | 1.33%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.33%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.67%   |
| Trident Microsystems 4DWave DX                                                 | 1         | 0.67%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.67%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 0.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.67%   |
| Qualcomm FP3                                                                   | 1         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.67%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.67%   |
| Qualcomm Android                                                               | 1         | 0.67%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.67%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.67%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.67%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.67%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 139       | 51.67%  |
| WiFi     | 130       | 48.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 57.31%  |
| Ethernet | 73        | 42.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 84        | 48.28%  |
| 1     | 69        | 39.66%  |
| 0     | 17        | 9.77%   |
| 3     | 3         | 1.72%   |
| 4     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 138       | 78.86%  |
| Yes  | 37        | 21.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 37.93%  |
| Realtek Semiconductor           | 14        | 16.09%  |
| Qualcomm Atheros Communications | 9         | 10.34%  |
| Broadcom                        | 5         | 5.75%   |
| Apple                           | 5         | 5.75%   |
| IMC Networks                    | 3         | 3.45%   |
| Foxconn / Hon Hai               | 3         | 3.45%   |
| Dell                            | 3         | 3.45%   |
| MediaTek                        | 2         | 2.3%    |
| Lite-On Technology              | 2         | 2.3%    |
| Cambridge Silicon Radio         | 2         | 2.3%    |
| Toshiba                         | 1         | 1.15%   |
| Syntek                          | 1         | 1.15%   |
| Logitech                        | 1         | 1.15%   |
| Hewlett-Packard                 | 1         | 1.15%   |
| ASUSTek Computer                | 1         | 1.15%   |
| Alps Electric                   | 1         | 1.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 20.69%  |
| Realtek Bluetooth Radio                                                             | 9         | 10.34%  |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 5.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 5.75%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 4.6%    |
| Realtek RTL8723B Bluetooth                                                          | 3         | 3.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 3.45%   |
| Intel Bluetooth Device                                                              | 3         | 3.45%   |
| Apple Bluetooth Host Controller                                                     | 3         | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.3%    |
| MediaTek Wireless_Device                                                            | 2         | 2.3%    |
| IMC Networks Bluetooth Device                                                       | 2         | 2.3%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 2.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.3%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 2.3%    |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.15%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 1.15%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 1.15%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.15%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 1.15%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.15%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.15%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.15%   |
| Intel AX200 Bluetooth                                                               | 1         | 1.15%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 1.15%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.15%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.15%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 1.15%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 1.15%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.15%   |
| Broadcom HP Portable Valentine                                                      | 1         | 1.15%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.15%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.15%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 1.15%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.15%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.15%   |
| Alps Electric Bluetooth Adapter                                                     | 1         | 1.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 120       | 60.3%   |
| AMD                                          | 39        | 19.6%   |
| Nvidia                                       | 26        | 13.07%  |
| C-Media Electronics                          | 3         | 1.51%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.5%    |
| VIA Technologies                             | 1         | 0.5%    |
| Sony                                         | 1         | 0.5%    |
| Razer USA                                    | 1         | 0.5%    |
| MosArt Semiconductor                         | 1         | 0.5%    |
| Logitech                                     | 1         | 0.5%    |
| JMTek                                        | 1         | 0.5%    |
| Ensoniq                                      | 1         | 0.5%    |
| EGO SYStems                                  | 1         | 0.5%    |
| Creative Labs                                | 1         | 0.5%    |
| ASUSTek Computer                             | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 15        | 6.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 5.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 4.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 4.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 3.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 3.83%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 3.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 3.4%    |
| AMD FCH Azalia Controller                                                                         | 8         | 3.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.55%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.55%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 2.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.7%    |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.28%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.28%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.28%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.28%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.28%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.85%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.85%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.85%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.85%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.85%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.85%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 20.66%  |
| Unknown             | 21        | 17.36%  |
| SK hynix            | 19        | 15.7%   |
| Micron Technology   | 17        | 14.05%  |
| Kingston            | 8         | 6.61%   |
| Nanya Technology    | 5         | 4.13%   |
| Elpida              | 4         | 3.31%   |
| Corsair             | 4         | 3.31%   |
| G.Skill             | 3         | 2.48%   |
| Unknown             | 3         | 2.48%   |
| Unknown (ABCD)      | 2         | 1.65%   |
| Smart               | 2         | 1.65%   |
| Transcend           | 1         | 0.83%   |
| Ramaxel Technology  | 1         | 0.83%   |
| Novatech            | 1         | 0.83%   |
| Kllisre             | 1         | 0.83%   |
| HMD                 | 1         | 0.83%   |
| GOODRAM             | 1         | 0.83%   |
| AMD                 | 1         | 0.83%   |
| A-DATA Technology   | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 2.27%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 2.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.27%   |
| Unknown                                                          | 3         | 2.27%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 1.52%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.52%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1.52%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.52%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 1.52%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1.52%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.76%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.76%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 1         | 0.76%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.76%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.76%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.76%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s         | 1         | 0.76%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                | 1         | 0.76%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.76%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.76%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 0.76%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.76%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 0.76%   |
| SK hynix RAM HT5SMRAP 2GB SODIMM DDR3 1600MT/s                   | 1         | 0.76%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.76%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 1         | 0.76%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 53        | 48.62%  |
| DDR4    | 28        | 25.69%  |
| DDR2    | 11        | 10.09%  |
| LPDDR4  | 7         | 6.42%   |
| SDRAM   | 5         | 4.59%   |
| LPDDR3  | 3         | 2.75%   |
| Unknown | 2         | 1.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 69.72%  |
| DIMM         | 22        | 20.18%  |
| Row Of Chips | 8         | 7.34%   |
| Unknown      | 3         | 2.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 39        | 31.45%  |
| 2048  | 38        | 30.65%  |
| 8192  | 30        | 24.19%  |
| 16384 | 7         | 5.65%   |
| 1024  | 7         | 5.65%   |
| 32768 | 2         | 1.61%   |
| 512   | 1         | 0.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 34        | 30.09%  |
| 3200    | 13        | 11.5%   |
| 1333    | 11        | 9.73%   |
| 667     | 7         | 6.19%   |
| 2667    | 6         | 5.31%   |
| 1334    | 5         | 4.42%   |
| 2400    | 4         | 3.54%   |
| 1066    | 4         | 3.54%   |
| 1067    | 3         | 2.65%   |
| Unknown | 3         | 2.65%   |
| 4267    | 2         | 1.77%   |
| 3266    | 2         | 1.77%   |
| 2133    | 2         | 1.77%   |
| 2048    | 2         | 1.77%   |
| 1867    | 2         | 1.77%   |
| 1866    | 2         | 1.77%   |
| 975     | 2         | 1.77%   |
| 800     | 2         | 1.77%   |
| 4199    | 1         | 0.88%   |
| 3733    | 1         | 0.88%   |
| 3666    | 1         | 0.88%   |
| 3400    | 1         | 0.88%   |
| 3066    | 1         | 0.88%   |
| 2800    | 1         | 0.88%   |
| 333     | 1         | 0.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 3         | 60%     |
| Hewlett-Packard    | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP LaserJet P1102       | 1         | 20%     |
| Canon PIXMA MP250       | 1         | 20%     |
| Canon MF3110            | 1         | 20%     |
| Canon CanoScan LiDE 300 | 1         | 20%     |
| Brother DCP-7055W       | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 26.73%  |
| Microdia                               | 11        | 10.89%  |
| Sunplus Innovation Technology          | 8         | 7.92%   |
| Realtek Semiconductor                  | 8         | 7.92%   |
| Syntek                                 | 5         | 4.95%   |
| Apple                                  | 5         | 4.95%   |
| Logitech                               | 4         | 3.96%   |
| IMC Networks                           | 4         | 3.96%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.97%   |
| Alcor Micro                            | 3         | 2.97%   |
| Acer                                   | 3         | 2.97%   |
| Suyin                                  | 2         | 1.98%   |
| Silicon Motion                         | 2         | 1.98%   |
| Quanta                                 | 2         | 1.98%   |
| Lenovo                                 | 2         | 1.98%   |
| ALi                                    | 2         | 1.98%   |
| Y Media                                | 1         | 0.99%   |
| WaveRider Communications               | 1         | 0.99%   |
| USB Camera CS                          | 1         | 0.99%   |
| SunplusIT                              | 1         | 0.99%   |
| Ricoh                                  | 1         | 0.99%   |
| Pixart Imaging                         | 1         | 0.99%   |
| Microsoft                              | 1         | 0.99%   |
| Lite-On Technology                     | 1         | 0.99%   |
| Cubeternet                             | 1         | 0.99%   |
| AVerMedia Technologies                 | 1         | 0.99%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 7         | 6.86%   |
| Sunplus HD WebCam                                   | 3         | 2.94%   |
| Chicony HD WebCam                                   | 3         | 2.94%   |
| Realtek Lenovo EasyCamera                           | 2         | 1.96%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.96%   |
| Realtek Integrated Webcam HD                        | 2         | 1.96%   |
| Microdia Lenovo EasyCamera                          | 2         | 1.96%   |
| Microdia Integrated_Webcam_HD                       | 2         | 1.96%   |
| Microdia Integrated Webcam                          | 2         | 1.96%   |
| Microdia HP Webcam-50                               | 2         | 1.96%   |
| Logitech Webcam C270                                | 2         | 1.96%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.96%   |
| Chicony FJ Camera                                   | 2         | 1.96%   |
| Chicony EasyCamera                                  | 2         | 1.96%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 2         | 1.96%   |
| Apple FaceTime HD Camera                            | 2         | 1.96%   |
| ALi WebCam                                          | 2         | 1.96%   |
| Alcor Micro HD Webcam                               | 2         | 1.96%   |
| Y Media USB Camera                                  | 1         | 0.98%   |
| WaveRider USB 2.0 Camera                            | 1         | 0.98%   |
| USB Camera CS USB Camera CS                         | 1         | 0.98%   |
| Syntek USB2.0 Camera                                | 1         | 0.98%   |
| Syntek USB Camera Device                            | 1         | 0.98%   |
| Syntek Sonix USB 2.0 Camera                         | 1         | 0.98%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.98%   |
| Syntek HD WebCam                                    | 1         | 0.98%   |
| Suyin Intel Webcam                                  | 1         | 0.98%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.98%   |
| SunplusIT USB 2.0 Camera                            | 1         | 0.98%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.98%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.98%   |
| Sunplus HD User Facing                              | 1         | 0.98%   |
| Sunplus Dell Integrated HD Webcam                   | 1         | 0.98%   |
| Sunplus Asus Webcam                                 | 1         | 0.98%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.98%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 0.98%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 0.98%   |
| Realtek USB Camera                                  | 1         | 0.98%   |
| Realtek EasyCamera                                  | 1         | 0.98%   |
| Quanta HP Webcam                                    | 1         | 0.98%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 26.32%  |
| Upek                  | 4         | 21.05%  |
| AuthenTec             | 4         | 21.05%  |
| Synaptics             | 2         | 10.53%  |
| STMicroelectronics    | 2         | 10.53%  |
| LighTuning Technology | 1         | 5.26%   |
| Elan Microelectronics | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 21.05%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 10.53%  |
| Unknown                                                | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5.26%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.26%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.26%   |
| Elan ELAN:Fingerprint                                  | 1         | 5.26%   |
| AuthenTec Fingerprint Sensor                           | 1         | 5.26%   |
| AuthenTec AES2810                                      | 1         | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 5.26%   |
| AuthenTec AES1600                                      | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 62.5%   |
| O2 Micro    | 1         | 12.5%   |
| Cherry      | 1         | 12.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 37.5%   |
| Broadcom BCM5880 Secure Applications Processor | 2         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 12.5%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC    | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 135       | 77.14%  |
| 1     | 37        | 21.14%  |
| 2     | 3         | 1.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 19        | 44.19%  |
| Graphics card      | 7         | 16.28%  |
| Chipcard           | 7         | 16.28%  |
| Net/wireless       | 3         | 6.98%   |
| Camera             | 3         | 6.98%   |
| Storage            | 1         | 2.33%   |
| Network            | 1         | 2.33%   |
| Dvb card           | 1         | 2.33%   |
| Bluetooth          | 1         | 2.33%   |

