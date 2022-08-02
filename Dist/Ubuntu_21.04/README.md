Ubuntu 21.04 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_21.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_21.04/Notebook/README.md).

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

Total: 2534

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ProLiant DL360 G5           | Server      | [bc1ce319a3](https://linux-hardware.org/?probe=bc1ce319a3) | Jul 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [662b422bcd](https://linux-hardware.org/?probe=662b422bcd) | Jul 17, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [0a4fd044e4](https://linux-hardware.org/?probe=0a4fd044e4) | Jul 10, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [289b6912d0](https://linux-hardware.org/?probe=289b6912d0) | Jul 10, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [a03b01d3b5](https://linux-hardware.org/?probe=a03b01d3b5) | Jul 10, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [7065eb875e](https://linux-hardware.org/?probe=7065eb875e) | Jun 15, 2022 |
| Dell          | Latitude 5511               | Notebook    | [93210ee531](https://linux-hardware.org/?probe=93210ee531) | Jun 12, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [53c2e38d14](https://linux-hardware.org/?probe=53c2e38d14) | Jun 10, 2022 |
| Medion        | MS-7501                     | Desktop     | [e5bf3cfdc2](https://linux-hardware.org/?probe=e5bf3cfdc2) | Jun 07, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [b7e4b7a2ec](https://linux-hardware.org/?probe=b7e4b7a2ec) | Jun 03, 2022 |
| Alienware     | M11x R2                     | Notebook    | [0b6837debb](https://linux-hardware.org/?probe=0b6837debb) | Jun 01, 2022 |
| Supermicro    | C7Z270-CG-M                 | Server      | [dbbe7457ff](https://linux-hardware.org/?probe=dbbe7457ff) | May 31, 2022 |
| Supermicro    | C7Z270-CG-M                 | Server      | [a9c593dd0b](https://linux-hardware.org/?probe=a9c593dd0b) | May 31, 2022 |
| Alienware     | M11x R2                     | Notebook    | [4a364390a6](https://linux-hardware.org/?probe=4a364390a6) | May 31, 2022 |
| Alienware     | M11x R2                     | Notebook    | [87e8835eba](https://linux-hardware.org/?probe=87e8835eba) | May 30, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [69e61d13d7](https://linux-hardware.org/?probe=69e61d13d7) | May 30, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [97fc69a492](https://linux-hardware.org/?probe=97fc69a492) | May 22, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a5cd1ea7e4](https://linux-hardware.org/?probe=a5cd1ea7e4) | May 22, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [4932c3cd73](https://linux-hardware.org/?probe=4932c3cd73) | May 10, 2022 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [43afa2936d](https://linux-hardware.org/?probe=43afa2936d) | May 01, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [88c6676e7b](https://linux-hardware.org/?probe=88c6676e7b) | Apr 29, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [f2bdbd2a4a](https://linux-hardware.org/?probe=f2bdbd2a4a) | Apr 29, 2022 |
| Dell          | 0590KW A01                  | Server      | [e86a005fd7](https://linux-hardware.org/?probe=e86a005fd7) | Apr 21, 2022 |
| Unknown       | Unknown                     | Soc         | [478b3488e7](https://linux-hardware.org/?probe=478b3488e7) | Apr 16, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a89ca51e1b](https://linux-hardware.org/?probe=a89ca51e1b) | Apr 15, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [930c18b320](https://linux-hardware.org/?probe=930c18b320) | Apr 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [8570b5ab84](https://linux-hardware.org/?probe=8570b5ab84) | Apr 12, 2022 |
| TongFang      | GM5TG8W                     | Notebook    | [a37f30bc86](https://linux-hardware.org/?probe=a37f30bc86) | Apr 12, 2022 |
| TongFang      | GM5TG8W                     | Notebook    | [b4004b859e](https://linux-hardware.org/?probe=b4004b859e) | Apr 10, 2022 |
| Gigabyte      | H97M-HD3                    | Desktop     | [fc7b16c289](https://linux-hardware.org/?probe=fc7b16c289) | Apr 05, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [53ca8415e0](https://linux-hardware.org/?probe=53ca8415e0) | Apr 03, 2022 |
| Dell          | 0FPP7F A00                  | Desktop     | [8e8bee474f](https://linux-hardware.org/?probe=8e8bee474f) | Apr 03, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [112e437f5d](https://linux-hardware.org/?probe=112e437f5d) | Mar 31, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [293958c009](https://linux-hardware.org/?probe=293958c009) | Mar 31, 2022 |
| Dell          | 0F642F A00                  | Desktop     | [b3ae697cd6](https://linux-hardware.org/?probe=b3ae697cd6) | Mar 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7c0d1ce382](https://linux-hardware.org/?probe=7c0d1ce382) | Mar 29, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [8696148b4a](https://linux-hardware.org/?probe=8696148b4a) | Mar 29, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [bfc20224d0](https://linux-hardware.org/?probe=bfc20224d0) | Mar 28, 2022 |
| HP            | 0A98h                       | Desktop     | [4b9c0556af](https://linux-hardware.org/?probe=4b9c0556af) | Mar 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [0d58e4449b](https://linux-hardware.org/?probe=0d58e4449b) | Mar 26, 2022 |
| Lenovo        | ThinkPad X230 2325BN8       | Notebook    | [3ad2d0f3ee](https://linux-hardware.org/?probe=3ad2d0f3ee) | Mar 25, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [794139f740](https://linux-hardware.org/?probe=794139f740) | Mar 24, 2022 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [2e70de8c8d](https://linux-hardware.org/?probe=2e70de8c8d) | Mar 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [67e6e7097c](https://linux-hardware.org/?probe=67e6e7097c) | Mar 16, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [30f82f9c0a](https://linux-hardware.org/?probe=30f82f9c0a) | Mar 12, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [eaa5b0f454](https://linux-hardware.org/?probe=eaa5b0f454) | Mar 08, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [e207d2bf0a](https://linux-hardware.org/?probe=e207d2bf0a) | Mar 08, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4edc1d31b5](https://linux-hardware.org/?probe=4edc1d31b5) | Mar 06, 2022 |
| Positivo      | H14BT58                     | Notebook    | [5bcf783e8d](https://linux-hardware.org/?probe=5bcf783e8d) | Mar 02, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [feb1d977ea](https://linux-hardware.org/?probe=feb1d977ea) | Feb 26, 2022 |
| Dell          | Latitude E4300              | Notebook    | [ff42bce998](https://linux-hardware.org/?probe=ff42bce998) | Feb 23, 2022 |
| Dell          | Latitude E4300              | Notebook    | [ce00b44454](https://linux-hardware.org/?probe=ce00b44454) | Feb 23, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [9e1f07c164](https://linux-hardware.org/?probe=9e1f07c164) | Feb 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [10d9500000](https://linux-hardware.org/?probe=10d9500000) | Feb 22, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [747899db53](https://linux-hardware.org/?probe=747899db53) | Feb 20, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [6b77f8012b](https://linux-hardware.org/?probe=6b77f8012b) | Feb 18, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [74e488319b](https://linux-hardware.org/?probe=74e488319b) | Feb 18, 2022 |
| Dell          | Precision 5530              | Notebook    | [5650039a15](https://linux-hardware.org/?probe=5650039a15) | Feb 18, 2022 |
| ASUSTek       | X540UA                      | Notebook    | [681b4aca6f](https://linux-hardware.org/?probe=681b4aca6f) | Feb 16, 2022 |
| Dell          | Precision 7760              | Notebook    | [c40cc0206c](https://linux-hardware.org/?probe=c40cc0206c) | Feb 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [832c433c19](https://linux-hardware.org/?probe=832c433c19) | Feb 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bd1fb80901](https://linux-hardware.org/?probe=bd1fb80901) | Feb 15, 2022 |
| ASRock        | 880GMH/USB3                 | Desktop     | [2789041a4d](https://linux-hardware.org/?probe=2789041a4d) | Feb 15, 2022 |
| Acer          | TravelMate 6592             | Notebook    | [a12fc5be70](https://linux-hardware.org/?probe=a12fc5be70) | Feb 13, 2022 |
| ASUSTek       | TAICHI31                    | Notebook    | [760fdd8fdd](https://linux-hardware.org/?probe=760fdd8fdd) | Feb 12, 2022 |
| Acer          | TravelMate X349-G2-M        | Notebook    | [99296fdd45](https://linux-hardware.org/?probe=99296fdd45) | Feb 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [82d892f3e5](https://linux-hardware.org/?probe=82d892f3e5) | Feb 07, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [fbea64f951](https://linux-hardware.org/?probe=fbea64f951) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [e21a51339e](https://linux-hardware.org/?probe=e21a51339e) | Feb 06, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [52a7fb252a](https://linux-hardware.org/?probe=52a7fb252a) | Feb 06, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cb34c3126d](https://linux-hardware.org/?probe=cb34c3126d) | Feb 05, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [0bd2b97304](https://linux-hardware.org/?probe=0bd2b97304) | Feb 03, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [23987146db](https://linux-hardware.org/?probe=23987146db) | Feb 02, 2022 |
| Lenovo        | ThinkPad X280 20KF001GGE    | Notebook    | [f076061f22](https://linux-hardware.org/?probe=f076061f22) | Feb 02, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [df3c56c53c](https://linux-hardware.org/?probe=df3c56c53c) | Feb 02, 2022 |
| Lenovo        | 3176 NOK                    | Desktop     | [d3a3d5276b](https://linux-hardware.org/?probe=d3a3d5276b) | Feb 02, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [4ea07fe50a](https://linux-hardware.org/?probe=4ea07fe50a) | Jan 31, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [26005d669e](https://linux-hardware.org/?probe=26005d669e) | Jan 29, 2022 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [efc653778b](https://linux-hardware.org/?probe=efc653778b) | Jan 29, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [8b138118b8](https://linux-hardware.org/?probe=8b138118b8) | Jan 28, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [3c241e8e7f](https://linux-hardware.org/?probe=3c241e8e7f) | Jan 27, 2022 |
| Samsung       | 730QDA                      | Convertible | [81697fc34e](https://linux-hardware.org/?probe=81697fc34e) | Jan 26, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [a31ae712c0](https://linux-hardware.org/?probe=a31ae712c0) | Jan 26, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [82a45a6067](https://linux-hardware.org/?probe=82a45a6067) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470 20HES50400    | Notebook    | [4ebbaf952f](https://linux-hardware.org/?probe=4ebbaf952f) | Jan 26, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [9e892d9ea3](https://linux-hardware.org/?probe=9e892d9ea3) | Jan 26, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [3770e775f9](https://linux-hardware.org/?probe=3770e775f9) | Jan 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [591bedf88f](https://linux-hardware.org/?probe=591bedf88f) | Jan 24, 2022 |
| HP            | 1998                        | Desktop     | [7bbd98aafa](https://linux-hardware.org/?probe=7bbd98aafa) | Jan 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7986235186](https://linux-hardware.org/?probe=7986235186) | Jan 23, 2022 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [8003b9ec29](https://linux-hardware.org/?probe=8003b9ec29) | Jan 20, 2022 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [046d8a907a](https://linux-hardware.org/?probe=046d8a907a) | Jan 20, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [f1c61e2a1b](https://linux-hardware.org/?probe=f1c61e2a1b) | Jan 19, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [49d5581480](https://linux-hardware.org/?probe=49d5581480) | Jan 19, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [90b4523b21](https://linux-hardware.org/?probe=90b4523b21) | Jan 19, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5d1c8ba7f2](https://linux-hardware.org/?probe=5d1c8ba7f2) | Jan 18, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ff42ca8248](https://linux-hardware.org/?probe=ff42ca8248) | Jan 17, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [c28502d4bb](https://linux-hardware.org/?probe=c28502d4bb) | Jan 17, 2022 |
| HC            | HCAR357-MI V1.0             | Desktop     | [a610cc37dc](https://linux-hardware.org/?probe=a610cc37dc) | Jan 16, 2022 |
| MSI           | X58 Pro-E                   | Desktop     | [32b53a700a](https://linux-hardware.org/?probe=32b53a700a) | Jan 15, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [2e8135c20d](https://linux-hardware.org/?probe=2e8135c20d) | Jan 15, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [6eff31c620](https://linux-hardware.org/?probe=6eff31c620) | Jan 14, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [c6dc2d8971](https://linux-hardware.org/?probe=c6dc2d8971) | Jan 14, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [2bc7b76882](https://linux-hardware.org/?probe=2bc7b76882) | Jan 13, 2022 |
| HP            | 82F2                        | Desktop     | [708ffd7bb5](https://linux-hardware.org/?probe=708ffd7bb5) | Jan 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [b2621747db](https://linux-hardware.org/?probe=b2621747db) | Jan 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [71cf155467](https://linux-hardware.org/?probe=71cf155467) | Jan 12, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [e82feb71d2](https://linux-hardware.org/?probe=e82feb71d2) | Jan 12, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0529614510](https://linux-hardware.org/?probe=0529614510) | Jan 12, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [118b411a8c](https://linux-hardware.org/?probe=118b411a8c) | Jan 12, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [aaf1227ec4](https://linux-hardware.org/?probe=aaf1227ec4) | Jan 11, 2022 |
| sunxi         | Unknown                     | Soc         | [6c1b0df48a](https://linux-hardware.org/?probe=6c1b0df48a) | Jan 10, 2022 |
| sunxi         | Unknown                     | Soc         | [4e57abaa0a](https://linux-hardware.org/?probe=4e57abaa0a) | Jan 10, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [7e4fe3d952](https://linux-hardware.org/?probe=7e4fe3d952) | Jan 10, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [efa90d55cb](https://linux-hardware.org/?probe=efa90d55cb) | Jan 09, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [2fa8f23cb9](https://linux-hardware.org/?probe=2fa8f23cb9) | Jan 09, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [a0b1a9f1d3](https://linux-hardware.org/?probe=a0b1a9f1d3) | Jan 09, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [b2e4fe050c](https://linux-hardware.org/?probe=b2e4fe050c) | Jan 09, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [91c54ce00a](https://linux-hardware.org/?probe=91c54ce00a) | Jan 08, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [faffa9ba50](https://linux-hardware.org/?probe=faffa9ba50) | Jan 07, 2022 |
| Supermicro    | X9DRW                       | Server      | [31684ad7e4](https://linux-hardware.org/?probe=31684ad7e4) | Jan 06, 2022 |
| Lenovo        | ThinkPad T61 6463WCH        | Notebook    | [b0936c6830](https://linux-hardware.org/?probe=b0936c6830) | Jan 05, 2022 |
| ASUSTek       | UX490UA                     | Notebook    | [d8024aef8a](https://linux-hardware.org/?probe=d8024aef8a) | Jan 05, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [446ac9b29a](https://linux-hardware.org/?probe=446ac9b29a) | Jan 04, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [031670d0da](https://linux-hardware.org/?probe=031670d0da) | Jan 04, 2022 |
| Raspberry ... | rpi                         | Soc         | [7772c86e18](https://linux-hardware.org/?probe=7772c86e18) | Jan 03, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [4e1ebc00ff](https://linux-hardware.org/?probe=4e1ebc00ff) | Jan 02, 2022 |
| Dell          | Latitude E6510              | Notebook    | [7a6c58b609](https://linux-hardware.org/?probe=7a6c58b609) | Jan 02, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [73ec029d3d](https://linux-hardware.org/?probe=73ec029d3d) | Dec 31, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [1f6fddb4f0](https://linux-hardware.org/?probe=1f6fddb4f0) | Dec 31, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4ee18a044c](https://linux-hardware.org/?probe=4ee18a044c) | Dec 30, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [9be23e2b2d](https://linux-hardware.org/?probe=9be23e2b2d) | Dec 30, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [9406d941f5](https://linux-hardware.org/?probe=9406d941f5) | Dec 29, 2021 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [195c9a8567](https://linux-hardware.org/?probe=195c9a8567) | Dec 29, 2021 |
| Lenovo        | ThinkPad T440 20B7S06M00    | Notebook    | [be06952436](https://linux-hardware.org/?probe=be06952436) | Dec 29, 2021 |
| HP            | 15                          | Notebook    | [e0d79905e2](https://linux-hardware.org/?probe=e0d79905e2) | Dec 29, 2021 |
| Acer          | Aspire A315-22              | Notebook    | [69b22953b2](https://linux-hardware.org/?probe=69b22953b2) | Dec 29, 2021 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [3edd9950f9](https://linux-hardware.org/?probe=3edd9950f9) | Dec 28, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [0fc6dd4a3f](https://linux-hardware.org/?probe=0fc6dd4a3f) | Dec 28, 2021 |
| Biostar       | H55A+                       | Desktop     | [0a4141bcc2](https://linux-hardware.org/?probe=0a4141bcc2) | Dec 28, 2021 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [b4a19932e1](https://linux-hardware.org/?probe=b4a19932e1) | Dec 27, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [712f1bf709](https://linux-hardware.org/?probe=712f1bf709) | Dec 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [17cc2bca69](https://linux-hardware.org/?probe=17cc2bca69) | Dec 26, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [588620e35b](https://linux-hardware.org/?probe=588620e35b) | Dec 26, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [8891bd5101](https://linux-hardware.org/?probe=8891bd5101) | Dec 26, 2021 |
| Dell          | Inspiron 1501               | Notebook    | [69ea9bcec2](https://linux-hardware.org/?probe=69ea9bcec2) | Dec 25, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [44089c6854](https://linux-hardware.org/?probe=44089c6854) | Dec 25, 2021 |
| Shuttle       | FZ87                        | Desktop     | [e26f5a10e8](https://linux-hardware.org/?probe=e26f5a10e8) | Dec 24, 2021 |
| Shuttle       | FZ87                        | Desktop     | [62a0a858a6](https://linux-hardware.org/?probe=62a0a858a6) | Dec 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [80a1a1a3f2](https://linux-hardware.org/?probe=80a1a1a3f2) | Dec 24, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [04bcdd10e9](https://linux-hardware.org/?probe=04bcdd10e9) | Dec 24, 2021 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [d76ed454c1](https://linux-hardware.org/?probe=d76ed454c1) | Dec 24, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [09799e1378](https://linux-hardware.org/?probe=09799e1378) | Dec 23, 2021 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [91dfb2417e](https://linux-hardware.org/?probe=91dfb2417e) | Dec 23, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7e520450ed](https://linux-hardware.org/?probe=7e520450ed) | Dec 22, 2021 |
| Acer          | Aspire ES1-331              | Notebook    | [229ffb6197](https://linux-hardware.org/?probe=229ffb6197) | Dec 21, 2021 |
| Medion        | P2212T                      | Tablet      | [c61a96d514](https://linux-hardware.org/?probe=c61a96d514) | Dec 21, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4466b5357f](https://linux-hardware.org/?probe=4466b5357f) | Dec 21, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [041e50f6a8](https://linux-hardware.org/?probe=041e50f6a8) | Dec 20, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [91efbf7a41](https://linux-hardware.org/?probe=91efbf7a41) | Dec 20, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [cb7b24735e](https://linux-hardware.org/?probe=cb7b24735e) | Dec 18, 2021 |
| Acer          | Aspire ES1-331              | Notebook    | [f1d39480bb](https://linux-hardware.org/?probe=f1d39480bb) | Dec 17, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7aeb73d109](https://linux-hardware.org/?probe=7aeb73d109) | Dec 17, 2021 |
| Acer          | Aspire ES1-331              | Notebook    | [4d373ac2a3](https://linux-hardware.org/?probe=4d373ac2a3) | Dec 17, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [e12da201c3](https://linux-hardware.org/?probe=e12da201c3) | Dec 16, 2021 |
| ASUSTek       | K54L                        | Notebook    | [335a4179a6](https://linux-hardware.org/?probe=335a4179a6) | Dec 16, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [f8e1e0ea63](https://linux-hardware.org/?probe=f8e1e0ea63) | Dec 16, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [0eee85762e](https://linux-hardware.org/?probe=0eee85762e) | Dec 14, 2021 |
| ASUSTek       | B85M-F                      | Desktop     | [04b3b165f6](https://linux-hardware.org/?probe=04b3b165f6) | Dec 14, 2021 |
| Dell          | Precision 7510              | Notebook    | [59a0d1a314](https://linux-hardware.org/?probe=59a0d1a314) | Dec 13, 2021 |
| Acer          | Aspire A315-22              | Notebook    | [c7dec3c83d](https://linux-hardware.org/?probe=c7dec3c83d) | Dec 12, 2021 |
| HP            | Pavilion dv6                | Notebook    | [24e1124f28](https://linux-hardware.org/?probe=24e1124f28) | Dec 12, 2021 |
| HP            | ProBook 6470b               | Notebook    | [a950763fdb](https://linux-hardware.org/?probe=a950763fdb) | Dec 12, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c33bc12a7a](https://linux-hardware.org/?probe=c33bc12a7a) | Dec 11, 2021 |
| Dell          | 0GM819                      | Desktop     | [2b84176135](https://linux-hardware.org/?probe=2b84176135) | Dec 11, 2021 |
| Acer          | Aspire A315-22              | Notebook    | [43938eb3c9](https://linux-hardware.org/?probe=43938eb3c9) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [fd5ad714f1](https://linux-hardware.org/?probe=fd5ad714f1) | Dec 10, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [412accf186](https://linux-hardware.org/?probe=412accf186) | Dec 09, 2021 |
| HP            | 8184 X4                     | Desktop     | [3a2d5e3c77](https://linux-hardware.org/?probe=3a2d5e3c77) | Dec 08, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [696dd578ab](https://linux-hardware.org/?probe=696dd578ab) | Dec 08, 2021 |
| HP            | 8184 X4                     | Desktop     | [e225665abc](https://linux-hardware.org/?probe=e225665abc) | Dec 08, 2021 |
| Dell          | Precision M6800             | Notebook    | [da95c95a07](https://linux-hardware.org/?probe=da95c95a07) | Dec 08, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ad04822d41](https://linux-hardware.org/?probe=ad04822d41) | Dec 07, 2021 |
| Medion        | Akoya P7818                 | Notebook    | [93ecb6c404](https://linux-hardware.org/?probe=93ecb6c404) | Dec 07, 2021 |
| Toshiba       | Satellite C850-19Z          | Notebook    | [4fdaf4108a](https://linux-hardware.org/?probe=4fdaf4108a) | Dec 07, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [594becb8c9](https://linux-hardware.org/?probe=594becb8c9) | Dec 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [211486de2c](https://linux-hardware.org/?probe=211486de2c) | Dec 05, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [7f6abaf57b](https://linux-hardware.org/?probe=7f6abaf57b) | Dec 05, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [3c693abd6e](https://linux-hardware.org/?probe=3c693abd6e) | Dec 04, 2021 |
| Dell          | 0WG261                      | Desktop     | [21617413f1](https://linux-hardware.org/?probe=21617413f1) | Dec 04, 2021 |
| Dell          | 0WG261                      | Desktop     | [95facf9dd4](https://linux-hardware.org/?probe=95facf9dd4) | Dec 04, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [b3c78d548b](https://linux-hardware.org/?probe=b3c78d548b) | Dec 03, 2021 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [c7b4e4cc3c](https://linux-hardware.org/?probe=c7b4e4cc3c) | Dec 02, 2021 |
| HP            | ProBook 4520s               | Notebook    | [a4d5e80bbc](https://linux-hardware.org/?probe=a4d5e80bbc) | Dec 02, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [095d666164](https://linux-hardware.org/?probe=095d666164) | Dec 01, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [d63f7874c8](https://linux-hardware.org/?probe=d63f7874c8) | Nov 29, 2021 |
| Unknown       | Unknown                     | Soc         | [3dbf93245c](https://linux-hardware.org/?probe=3dbf93245c) | Nov 28, 2021 |
| Unknown       | Unknown                     | Soc         | [f46696c32c](https://linux-hardware.org/?probe=f46696c32c) | Nov 28, 2021 |
| Lenovo        | V560                        | Notebook    | [83e5b46ba2](https://linux-hardware.org/?probe=83e5b46ba2) | Nov 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [08d43243b9](https://linux-hardware.org/?probe=08d43243b9) | Nov 28, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [8b68d87b85](https://linux-hardware.org/?probe=8b68d87b85) | Nov 28, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [b936f93d22](https://linux-hardware.org/?probe=b936f93d22) | Nov 28, 2021 |
| Dell          | 0F642F A00                  | Desktop     | [86a0053059](https://linux-hardware.org/?probe=86a0053059) | Nov 28, 2021 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [185831a6a6](https://linux-hardware.org/?probe=185831a6a6) | Nov 28, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [064efec6fb](https://linux-hardware.org/?probe=064efec6fb) | Nov 27, 2021 |
| FIRICH        | J1900                       | Desktop     | [65b936ff81](https://linux-hardware.org/?probe=65b936ff81) | Nov 27, 2021 |
| Dell          | 0RF703                      | Desktop     | [fafb09d7a7](https://linux-hardware.org/?probe=fafb09d7a7) | Nov 27, 2021 |
| Dell          | 0RF703                      | Desktop     | [a1c5f0a19e](https://linux-hardware.org/?probe=a1c5f0a19e) | Nov 27, 2021 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [b1147db572](https://linux-hardware.org/?probe=b1147db572) | Nov 27, 2021 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [0162ece16f](https://linux-hardware.org/?probe=0162ece16f) | Nov 25, 2021 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [e8a1a915a4](https://linux-hardware.org/?probe=e8a1a915a4) | Nov 25, 2021 |
| Dell          | Inspiron 5437               | Notebook    | [3c089ce814](https://linux-hardware.org/?probe=3c089ce814) | Nov 25, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3355d6fd50](https://linux-hardware.org/?probe=3355d6fd50) | Nov 24, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [56f55d6a20](https://linux-hardware.org/?probe=56f55d6a20) | Nov 24, 2021 |
| Dell          | Latitude E6430              | Notebook    | [f18bb8ac48](https://linux-hardware.org/?probe=f18bb8ac48) | Nov 24, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [9476bb5e05](https://linux-hardware.org/?probe=9476bb5e05) | Nov 24, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [d4bfc15ece](https://linux-hardware.org/?probe=d4bfc15ece) | Nov 24, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [dca6d021bb](https://linux-hardware.org/?probe=dca6d021bb) | Nov 23, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [667c9a87dc](https://linux-hardware.org/?probe=667c9a87dc) | Nov 23, 2021 |
| HP            | 3647h                       | Desktop     | [e3d0601f0b](https://linux-hardware.org/?probe=e3d0601f0b) | Nov 23, 2021 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [2b2b399b41](https://linux-hardware.org/?probe=2b2b399b41) | Nov 23, 2021 |
| Dell          | Latitude E6430              | Notebook    | [ce21d5f8d7](https://linux-hardware.org/?probe=ce21d5f8d7) | Nov 23, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [6cb99e6a5f](https://linux-hardware.org/?probe=6cb99e6a5f) | Nov 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [7640e31dd0](https://linux-hardware.org/?probe=7640e31dd0) | Nov 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [21a35c6975](https://linux-hardware.org/?probe=21a35c6975) | Nov 22, 2021 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [b2a2916a12](https://linux-hardware.org/?probe=b2a2916a12) | Nov 22, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [d46b86b5c0](https://linux-hardware.org/?probe=d46b86b5c0) | Nov 22, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [af9a5a76c3](https://linux-hardware.org/?probe=af9a5a76c3) | Nov 22, 2021 |
| ASUSTek       | N71Vg                       | Notebook    | [4657bca419](https://linux-hardware.org/?probe=4657bca419) | Nov 21, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [08b2395aa0](https://linux-hardware.org/?probe=08b2395aa0) | Nov 21, 2021 |
| Toshiba       | Satellite L875D             | Notebook    | [abf232b07d](https://linux-hardware.org/?probe=abf232b07d) | Nov 21, 2021 |
| Lenovo        | ThinkPad T430 2349DS1       | Notebook    | [cd04ef3811](https://linux-hardware.org/?probe=cd04ef3811) | Nov 21, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [e0f0471cee](https://linux-hardware.org/?probe=e0f0471cee) | Nov 20, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [4fe276b0c3](https://linux-hardware.org/?probe=4fe276b0c3) | Nov 20, 2021 |
| Toshiba       | Satellite C850-19Z          | Notebook    | [38b73bb691](https://linux-hardware.org/?probe=38b73bb691) | Nov 20, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [a73d04c7ba](https://linux-hardware.org/?probe=a73d04c7ba) | Nov 20, 2021 |
| Dell          | 07PR60 A00                  | Desktop     | [806800bb1f](https://linux-hardware.org/?probe=806800bb1f) | Nov 19, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [69a210799e](https://linux-hardware.org/?probe=69a210799e) | Nov 19, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [55554fa68d](https://linux-hardware.org/?probe=55554fa68d) | Nov 18, 2021 |
| Toshiba       | Satellite L875D             | Notebook    | [894d6602f9](https://linux-hardware.org/?probe=894d6602f9) | Nov 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [8fc5db0cd9](https://linux-hardware.org/?probe=8fc5db0cd9) | Nov 17, 2021 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [3cbee876cb](https://linux-hardware.org/?probe=3cbee876cb) | Nov 17, 2021 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [92f0b10f02](https://linux-hardware.org/?probe=92f0b10f02) | Nov 17, 2021 |
| Dell          | Latitude 7420               | Notebook    | [52bd94ce90](https://linux-hardware.org/?probe=52bd94ce90) | Nov 17, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [dac5f9f46b](https://linux-hardware.org/?probe=dac5f9f46b) | Nov 16, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [246e62e738](https://linux-hardware.org/?probe=246e62e738) | Nov 16, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [fc12beb786](https://linux-hardware.org/?probe=fc12beb786) | Nov 16, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [c5764c10dc](https://linux-hardware.org/?probe=c5764c10dc) | Nov 16, 2021 |
| Medion        | Akoya P7818                 | Notebook    | [273e1d36c0](https://linux-hardware.org/?probe=273e1d36c0) | Nov 15, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [bc424a9c53](https://linux-hardware.org/?probe=bc424a9c53) | Nov 15, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [c4e6de1315](https://linux-hardware.org/?probe=c4e6de1315) | Nov 15, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [877d892aae](https://linux-hardware.org/?probe=877d892aae) | Nov 15, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [3028a32b5d](https://linux-hardware.org/?probe=3028a32b5d) | Nov 15, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [c202664327](https://linux-hardware.org/?probe=c202664327) | Nov 15, 2021 |
| MSI           | Z370M MORTAR                | Desktop     | [003fc9518e](https://linux-hardware.org/?probe=003fc9518e) | Nov 14, 2021 |
| MSI           | Z370M MORTAR                | Desktop     | [66683db42d](https://linux-hardware.org/?probe=66683db42d) | Nov 14, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [5d283e7da8](https://linux-hardware.org/?probe=5d283e7da8) | Nov 13, 2021 |
| ASUSTek       | M4N78-AM                    | Desktop     | [33e5f6918d](https://linux-hardware.org/?probe=33e5f6918d) | Nov 11, 2021 |
| HP            | 0AECh D                     | Desktop     | [7d8a81315d](https://linux-hardware.org/?probe=7d8a81315d) | Nov 11, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3d5a6a79f2](https://linux-hardware.org/?probe=3d5a6a79f2) | Nov 10, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [049c9e4f07](https://linux-hardware.org/?probe=049c9e4f07) | Nov 10, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [f1d7eca0f3](https://linux-hardware.org/?probe=f1d7eca0f3) | Nov 10, 2021 |
| Acer          | Swift SF514-52T             | Notebook    | [020a93edbc](https://linux-hardware.org/?probe=020a93edbc) | Nov 10, 2021 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [4b0d19ecf1](https://linux-hardware.org/?probe=4b0d19ecf1) | Nov 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [cc507fc6de](https://linux-hardware.org/?probe=cc507fc6de) | Nov 08, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [c32869e5a8](https://linux-hardware.org/?probe=c32869e5a8) | Nov 08, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [0ef80f43bb](https://linux-hardware.org/?probe=0ef80f43bb) | Nov 08, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9048879465](https://linux-hardware.org/?probe=9048879465) | Nov 08, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [0c5902f5a8](https://linux-hardware.org/?probe=0c5902f5a8) | Nov 07, 2021 |
| Supermicro    | X11DPH-T                    | Server      | [1a73c74fbb](https://linux-hardware.org/?probe=1a73c74fbb) | Nov 07, 2021 |
| Lenovo        | ThinkPad E14 20RAS1M600     | Notebook    | [d1ca56887d](https://linux-hardware.org/?probe=d1ca56887d) | Nov 07, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [5d35bd9e4a](https://linux-hardware.org/?probe=5d35bd9e4a) | Nov 07, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [5d9f112e39](https://linux-hardware.org/?probe=5d9f112e39) | Nov 07, 2021 |
| Supermicro    | X11DPH-T                    | Server      | [8b3bcb66e0](https://linux-hardware.org/?probe=8b3bcb66e0) | Nov 07, 2021 |
| Lenovo        | ThinkPad T61 6463WCH        | Notebook    | [7b7a362cc1](https://linux-hardware.org/?probe=7b7a362cc1) | Nov 06, 2021 |
| HP            | 0A9Ch                       | Desktop     | [59703eca34](https://linux-hardware.org/?probe=59703eca34) | Nov 05, 2021 |
| HP            | 15                          | Notebook    | [0719e191d4](https://linux-hardware.org/?probe=0719e191d4) | Nov 04, 2021 |
| MSI           | IONA                        | Desktop     | [80a676d45e](https://linux-hardware.org/?probe=80a676d45e) | Nov 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d62808ad60](https://linux-hardware.org/?probe=d62808ad60) | Nov 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6321f2a677](https://linux-hardware.org/?probe=6321f2a677) | Nov 03, 2021 |
| Intel         | S1200SP H57532-260          | Server      | [2a41e48c27](https://linux-hardware.org/?probe=2a41e48c27) | Nov 03, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [b643635a41](https://linux-hardware.org/?probe=b643635a41) | Nov 02, 2021 |
| MSI           | 2A9C                        | Desktop     | [7c98a4adff](https://linux-hardware.org/?probe=7c98a4adff) | Nov 02, 2021 |
| Gigabyte      | H110M-D2P-WG-CF             | Desktop     | [82a1f8e51e](https://linux-hardware.org/?probe=82a1f8e51e) | Nov 01, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [dfc43940cc](https://linux-hardware.org/?probe=dfc43940cc) | Nov 01, 2021 |
| Acer          | Aspire E1-410               | Notebook    | [5d4401610d](https://linux-hardware.org/?probe=5d4401610d) | Nov 01, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [5fbff69f17](https://linux-hardware.org/?probe=5fbff69f17) | Nov 01, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [80627a5a8a](https://linux-hardware.org/?probe=80627a5a8a) | Nov 01, 2021 |
| HP            | 15                          | Notebook    | [ab5e53c9ed](https://linux-hardware.org/?probe=ab5e53c9ed) | Nov 01, 2021 |
| Gigabyte      | H110M-D2P-WG-CF             | Desktop     | [36bf6dab37](https://linux-hardware.org/?probe=36bf6dab37) | Oct 31, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [783d081b5a](https://linux-hardware.org/?probe=783d081b5a) | Oct 31, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [26adc81160](https://linux-hardware.org/?probe=26adc81160) | Oct 30, 2021 |
| Dell          | 0X9M3X A03                  | Desktop     | [bbf963580d](https://linux-hardware.org/?probe=bbf963580d) | Oct 30, 2021 |
| HP            | 0A98h                       | Desktop     | [4299904c4d](https://linux-hardware.org/?probe=4299904c4d) | Oct 30, 2021 |
| MSI           | Z97 PC Mate                 | Desktop     | [5ca8bbd80d](https://linux-hardware.org/?probe=5ca8bbd80d) | Oct 30, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [72617e5dd9](https://linux-hardware.org/?probe=72617e5dd9) | Oct 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [ff8c85568e](https://linux-hardware.org/?probe=ff8c85568e) | Oct 29, 2021 |
| HP            | 0AECh D                     | Desktop     | [cd2f6268cf](https://linux-hardware.org/?probe=cd2f6268cf) | Oct 28, 2021 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | Notebook    | [6ae3033841](https://linux-hardware.org/?probe=6ae3033841) | Oct 28, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [27f4b2412f](https://linux-hardware.org/?probe=27f4b2412f) | Oct 27, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [c62bb4adc9](https://linux-hardware.org/?probe=c62bb4adc9) | Oct 27, 2021 |
| Lenovo        | ThinkPad E490 20N80010RT    | Notebook    | [3fc424b8c6](https://linux-hardware.org/?probe=3fc424b8c6) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [cc4c888046](https://linux-hardware.org/?probe=cc4c888046) | Oct 27, 2021 |
| MSI           | MEG B550 UNIFY              | Desktop     | [6326601487](https://linux-hardware.org/?probe=6326601487) | Oct 27, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [8d74dd99c7](https://linux-hardware.org/?probe=8d74dd99c7) | Oct 26, 2021 |
| MSI           | B85-G41 PC Mate             | Desktop     | [90659e6a34](https://linux-hardware.org/?probe=90659e6a34) | Oct 26, 2021 |
| HP            | Laptop 15-bs2xx             | Notebook    | [d0f14fd899](https://linux-hardware.org/?probe=d0f14fd899) | Oct 26, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [9d4edc7252](https://linux-hardware.org/?probe=9d4edc7252) | Oct 25, 2021 |
| Acer          | AO722                       | Notebook    | [832ca83fcd](https://linux-hardware.org/?probe=832ca83fcd) | Oct 25, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [23c770232c](https://linux-hardware.org/?probe=23c770232c) | Oct 25, 2021 |
| MSI           | Trinergy                    | Desktop     | [f2f1ad0e41](https://linux-hardware.org/?probe=f2f1ad0e41) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [1f26867986](https://linux-hardware.org/?probe=1f26867986) | Oct 25, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [6ecbec2c49](https://linux-hardware.org/?probe=6ecbec2c49) | Oct 25, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [338ddd258e](https://linux-hardware.org/?probe=338ddd258e) | Oct 24, 2021 |
| HP            | ProBook 4540s               | Notebook    | [49ce392cd2](https://linux-hardware.org/?probe=49ce392cd2) | Oct 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [9b3e361eb7](https://linux-hardware.org/?probe=9b3e361eb7) | Oct 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e9991e486b](https://linux-hardware.org/?probe=e9991e486b) | Oct 23, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d66b719066](https://linux-hardware.org/?probe=d66b719066) | Oct 23, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [16268db25b](https://linux-hardware.org/?probe=16268db25b) | Oct 22, 2021 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [040d7f611e](https://linux-hardware.org/?probe=040d7f611e) | Oct 22, 2021 |
| Dell          | Latitude E7470              | Notebook    | [96ef0ee68c](https://linux-hardware.org/?probe=96ef0ee68c) | Oct 22, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [545b983e7c](https://linux-hardware.org/?probe=545b983e7c) | Oct 22, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [c7d518ca51](https://linux-hardware.org/?probe=c7d518ca51) | Oct 22, 2021 |
| HP            | Stream Laptop               | Notebook    | [95df1a4e45](https://linux-hardware.org/?probe=95df1a4e45) | Oct 22, 2021 |
| ASUSTek       | Q87M-E                      | Desktop     | [2253d95e90](https://linux-hardware.org/?probe=2253d95e90) | Oct 22, 2021 |
| HP            | 8053                        | Desktop     | [4f5c7dde74](https://linux-hardware.org/?probe=4f5c7dde74) | Oct 22, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [0278eaa13a](https://linux-hardware.org/?probe=0278eaa13a) | Oct 22, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [0be91c158b](https://linux-hardware.org/?probe=0be91c158b) | Oct 22, 2021 |
| Acer          | Aspire ES1-111              | Notebook    | [98323be6f8](https://linux-hardware.org/?probe=98323be6f8) | Oct 22, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b792457755](https://linux-hardware.org/?probe=b792457755) | Oct 21, 2021 |
| Acer          | NG-AN515-51-522Q            | Notebook    | [e4762b54f7](https://linux-hardware.org/?probe=e4762b54f7) | Oct 21, 2021 |
| Dell          | 0KFKMF A00                  | All in one  | [4c88b83358](https://linux-hardware.org/?probe=4c88b83358) | Oct 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [3fe556cde3](https://linux-hardware.org/?probe=3fe556cde3) | Oct 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [0413ebb72c](https://linux-hardware.org/?probe=0413ebb72c) | Oct 21, 2021 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [516c451ac1](https://linux-hardware.org/?probe=516c451ac1) | Oct 21, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [fe32d5538f](https://linux-hardware.org/?probe=fe32d5538f) | Oct 21, 2021 |
| Toshiba       | Satellite Pro C850-1G8      | Notebook    | [37b87b5c45](https://linux-hardware.org/?probe=37b87b5c45) | Oct 21, 2021 |
| Dell          | Latitude 5400               | Notebook    | [6a14ed2d5e](https://linux-hardware.org/?probe=6a14ed2d5e) | Oct 21, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [36e6c22cc6](https://linux-hardware.org/?probe=36e6c22cc6) | Oct 20, 2021 |
| Dell          | Latitude E6420              | Notebook    | [4c3c43daaa](https://linux-hardware.org/?probe=4c3c43daaa) | Oct 20, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [7775a20781](https://linux-hardware.org/?probe=7775a20781) | Oct 20, 2021 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [fb7beb9612](https://linux-hardware.org/?probe=fb7beb9612) | Oct 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [f1449188a9](https://linux-hardware.org/?probe=f1449188a9) | Oct 20, 2021 |
| ASUSTek       | U56E                        | Notebook    | [a610876405](https://linux-hardware.org/?probe=a610876405) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [2db5d6dc7c](https://linux-hardware.org/?probe=2db5d6dc7c) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [1faf3f28e5](https://linux-hardware.org/?probe=1faf3f28e5) | Oct 20, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [c8606a3a2a](https://linux-hardware.org/?probe=c8606a3a2a) | Oct 20, 2021 |
| ASUSTek       | K72F                        | Notebook    | [0eedfc8a67](https://linux-hardware.org/?probe=0eedfc8a67) | Oct 20, 2021 |
| Dell          | Latitude 9410               | Convertible | [ec6dbcd331](https://linux-hardware.org/?probe=ec6dbcd331) | Oct 19, 2021 |
| Lenovo        | ThinkPad E14 20RAS1M600     | Notebook    | [a14a745c3a](https://linux-hardware.org/?probe=a14a745c3a) | Oct 19, 2021 |
| HP            | Notebook                    | Notebook    | [ff690977bf](https://linux-hardware.org/?probe=ff690977bf) | Oct 19, 2021 |
| MSI           | 2A9C                        | Desktop     | [29628ccee7](https://linux-hardware.org/?probe=29628ccee7) | Oct 19, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [a174c1781d](https://linux-hardware.org/?probe=a174c1781d) | Oct 19, 2021 |
| Dell          | Latitude E4300              | Notebook    | [127b65224f](https://linux-hardware.org/?probe=127b65224f) | Oct 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [9f21330313](https://linux-hardware.org/?probe=9f21330313) | Oct 18, 2021 |
| Framework     | Laptop                      | Notebook    | [591c9d1d8f](https://linux-hardware.org/?probe=591c9d1d8f) | Oct 18, 2021 |
| Kiano         | IntelectX3HD                | Tablet      | [4459e77fcc](https://linux-hardware.org/?probe=4459e77fcc) | Oct 18, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [c61bb65266](https://linux-hardware.org/?probe=c61bb65266) | Oct 18, 2021 |
| HP            | 8053                        | Desktop     | [8f76510560](https://linux-hardware.org/?probe=8f76510560) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [4768b805ff](https://linux-hardware.org/?probe=4768b805ff) | Oct 17, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [d837406f2a](https://linux-hardware.org/?probe=d837406f2a) | Oct 16, 2021 |
| Dell          | Latitude E6400              | Notebook    | [fbc4bfa1b0](https://linux-hardware.org/?probe=fbc4bfa1b0) | Oct 16, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [214d892f21](https://linux-hardware.org/?probe=214d892f21) | Oct 16, 2021 |
| Kiano         | IntelectX3HD                | Tablet      | [0bba28b672](https://linux-hardware.org/?probe=0bba28b672) | Oct 16, 2021 |
| Kiano         | IntelectX3HD                | Tablet      | [2f391b7a23](https://linux-hardware.org/?probe=2f391b7a23) | Oct 16, 2021 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [aa8e220390](https://linux-hardware.org/?probe=aa8e220390) | Oct 16, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [a4d3e13675](https://linux-hardware.org/?probe=a4d3e13675) | Oct 16, 2021 |
| IBM           | 81Y7071 SVT-R               | Desktop     | [033203aade](https://linux-hardware.org/?probe=033203aade) | Oct 16, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [4ee6c35b8f](https://linux-hardware.org/?probe=4ee6c35b8f) | Oct 16, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [fb4d76caab](https://linux-hardware.org/?probe=fb4d76caab) | Oct 16, 2021 |
| ASRock        | B460M Pro4                  | Desktop     | [1a90b22456](https://linux-hardware.org/?probe=1a90b22456) | Oct 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ac8590ee92](https://linux-hardware.org/?probe=ac8590ee92) | Oct 16, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [19105d9255](https://linux-hardware.org/?probe=19105d9255) | Oct 16, 2021 |
| Acer          | Aspire 7715Z                | Notebook    | [d2b159ed70](https://linux-hardware.org/?probe=d2b159ed70) | Oct 16, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0180... | Notebook    | [da345e8de3](https://linux-hardware.org/?probe=da345e8de3) | Oct 15, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [338292d813](https://linux-hardware.org/?probe=338292d813) | Oct 15, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [98ad849feb](https://linux-hardware.org/?probe=98ad849feb) | Oct 15, 2021 |
| Dell          | Latitude E4300              | Notebook    | [81efc2581c](https://linux-hardware.org/?probe=81efc2581c) | Oct 15, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5c405f8cf2](https://linux-hardware.org/?probe=5c405f8cf2) | Oct 15, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [722ca22e90](https://linux-hardware.org/?probe=722ca22e90) | Oct 15, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [570b8131d1](https://linux-hardware.org/?probe=570b8131d1) | Oct 15, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [f04cc5e7a8](https://linux-hardware.org/?probe=f04cc5e7a8) | Oct 15, 2021 |
| MSI           | Z270 PC MATE                | Desktop     | [72cbd4e7cf](https://linux-hardware.org/?probe=72cbd4e7cf) | Oct 15, 2021 |
| Dell          | 06FW8P A00                  | Desktop     | [7db180dfdd](https://linux-hardware.org/?probe=7db180dfdd) | Oct 15, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [e2538800e5](https://linux-hardware.org/?probe=e2538800e5) | Oct 15, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [06223f6db9](https://linux-hardware.org/?probe=06223f6db9) | Oct 15, 2021 |
| HP            | 0A98h                       | Desktop     | [5cebaf2fa6](https://linux-hardware.org/?probe=5cebaf2fa6) | Oct 14, 2021 |
| HP            | ProBook 4540s               | Notebook    | [046acc5982](https://linux-hardware.org/?probe=046acc5982) | Oct 14, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [54b9ff49e4](https://linux-hardware.org/?probe=54b9ff49e4) | Oct 14, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3074d8f202](https://linux-hardware.org/?probe=3074d8f202) | Oct 14, 2021 |
| Google        | Treeya                      | Notebook    | [6c10b9bcb3](https://linux-hardware.org/?probe=6c10b9bcb3) | Oct 14, 2021 |
| Durabook      | S14AT                       | Notebook    | [60d38664ee](https://linux-hardware.org/?probe=60d38664ee) | Oct 14, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [a99608bc0c](https://linux-hardware.org/?probe=a99608bc0c) | Oct 13, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f2c892dcdc](https://linux-hardware.org/?probe=f2c892dcdc) | Oct 13, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [294d1f6a89](https://linux-hardware.org/?probe=294d1f6a89) | Oct 13, 2021 |
| Alienware     | 17 R3                       | Notebook    | [0f1a877034](https://linux-hardware.org/?probe=0f1a877034) | Oct 13, 2021 |
| HP            | G42                         | Notebook    | [52ade78428](https://linux-hardware.org/?probe=52ade78428) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [df32df0b62](https://linux-hardware.org/?probe=df32df0b62) | Oct 13, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [6b3505b5f2](https://linux-hardware.org/?probe=6b3505b5f2) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [c7239a1379](https://linux-hardware.org/?probe=c7239a1379) | Oct 13, 2021 |
| Sony          | SVE14126CXB                 | Notebook    | [acf29b49fd](https://linux-hardware.org/?probe=acf29b49fd) | Oct 13, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [20dc49f637](https://linux-hardware.org/?probe=20dc49f637) | Oct 13, 2021 |
| Wortmann      | TERRA_MOBILE_1541H          | Notebook    | [28dd4b8caf](https://linux-hardware.org/?probe=28dd4b8caf) | Oct 13, 2021 |
| Microsoft     | Surface Pro 2               | Tablet      | [28e43dd2f4](https://linux-hardware.org/?probe=28e43dd2f4) | Oct 13, 2021 |
| Toshiba       | Satellite C850-19Z          | Notebook    | [59617db66a](https://linux-hardware.org/?probe=59617db66a) | Oct 13, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0ca14eb2ea](https://linux-hardware.org/?probe=0ca14eb2ea) | Oct 12, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [69b1b6e13e](https://linux-hardware.org/?probe=69b1b6e13e) | Oct 12, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [138ad65457](https://linux-hardware.org/?probe=138ad65457) | Oct 12, 2021 |
| Lenovo        | ThinkPad X260 20F5S08N00    | Notebook    | [c8e9d8e7a9](https://linux-hardware.org/?probe=c8e9d8e7a9) | Oct 12, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [450992ab23](https://linux-hardware.org/?probe=450992ab23) | Oct 12, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [3a14292469](https://linux-hardware.org/?probe=3a14292469) | Oct 12, 2021 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [3968e39b0b](https://linux-hardware.org/?probe=3968e39b0b) | Oct 12, 2021 |
| MSI           | NF520T-C35                  | Desktop     | [277af949b6](https://linux-hardware.org/?probe=277af949b6) | Oct 12, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [d74fd1a5d9](https://linux-hardware.org/?probe=d74fd1a5d9) | Oct 12, 2021 |
| HP            | Laptop 15-bs2xx             | Notebook    | [cc04e66dc0](https://linux-hardware.org/?probe=cc04e66dc0) | Oct 12, 2021 |
| MSI           | NF520T-C35                  | Desktop     | [ed9520268a](https://linux-hardware.org/?probe=ed9520268a) | Oct 12, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [5e8e9aea62](https://linux-hardware.org/?probe=5e8e9aea62) | Oct 12, 2021 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [347d6df600](https://linux-hardware.org/?probe=347d6df600) | Oct 12, 2021 |
| HP            | Notebook                    | Notebook    | [0b5eb78634](https://linux-hardware.org/?probe=0b5eb78634) | Oct 12, 2021 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [80718210cc](https://linux-hardware.org/?probe=80718210cc) | Oct 12, 2021 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [64861e0fdd](https://linux-hardware.org/?probe=64861e0fdd) | Oct 11, 2021 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | Notebook    | [6047c37a95](https://linux-hardware.org/?probe=6047c37a95) | Oct 11, 2021 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [0813ceeeca](https://linux-hardware.org/?probe=0813ceeeca) | Oct 11, 2021 |
| Dell          | Inspiron One 2320           | All in one  | [81048aabf5](https://linux-hardware.org/?probe=81048aabf5) | Oct 11, 2021 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | Notebook    | [3a3c3e4ad6](https://linux-hardware.org/?probe=3a3c3e4ad6) | Oct 11, 2021 |
| Lenovo        | E50-80 80J2                 | Notebook    | [c3d31689ec](https://linux-hardware.org/?probe=c3d31689ec) | Oct 11, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [b59de957b3](https://linux-hardware.org/?probe=b59de957b3) | Oct 11, 2021 |
| ASRock        | J4005M                      | Desktop     | [dbef05ba27](https://linux-hardware.org/?probe=dbef05ba27) | Oct 11, 2021 |
| Sony          | SVE1713Y1EB                 | Notebook    | [a427a26f34](https://linux-hardware.org/?probe=a427a26f34) | Oct 11, 2021 |
| HP            | 0A98h                       | Desktop     | [ea96f19e99](https://linux-hardware.org/?probe=ea96f19e99) | Oct 11, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [a671b6ab07](https://linux-hardware.org/?probe=a671b6ab07) | Oct 11, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [9855c138d4](https://linux-hardware.org/?probe=9855c138d4) | Oct 11, 2021 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [26a075831a](https://linux-hardware.org/?probe=26a075831a) | Oct 11, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [a3f3c59edc](https://linux-hardware.org/?probe=a3f3c59edc) | Oct 11, 2021 |
| Lenovo        | ThinkPad T410 2522ED2       | Notebook    | [c8c010b75c](https://linux-hardware.org/?probe=c8c010b75c) | Oct 11, 2021 |
| HP            | 17E2                        | Mini pc     | [e1e74f57a7](https://linux-hardware.org/?probe=e1e74f57a7) | Oct 11, 2021 |
| Dell          | 0HHV7N A00                  | Desktop     | [8fddbf28a1](https://linux-hardware.org/?probe=8fddbf28a1) | Oct 11, 2021 |
| MSI           | 2AE0                        | Desktop     | [e5ede0905a](https://linux-hardware.org/?probe=e5ede0905a) | Oct 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [1fa4e26ee6](https://linux-hardware.org/?probe=1fa4e26ee6) | Oct 10, 2021 |
| Alienware     | M11x R2                     | Notebook    | [e45fcc146d](https://linux-hardware.org/?probe=e45fcc146d) | Oct 10, 2021 |
| Toshiba       | Satellite L830              | Notebook    | [e8652672c3](https://linux-hardware.org/?probe=e8652672c3) | Oct 10, 2021 |
| Dell          | 00FKMJ A00                  | Desktop     | [713d852597](https://linux-hardware.org/?probe=713d852597) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [ff477e5a71](https://linux-hardware.org/?probe=ff477e5a71) | Oct 10, 2021 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [e770d8dd7c](https://linux-hardware.org/?probe=e770d8dd7c) | Oct 10, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [f467bc83ef](https://linux-hardware.org/?probe=f467bc83ef) | Oct 10, 2021 |
| Toshiba       | Satellite M305D             | Notebook    | [1ef98af428](https://linux-hardware.org/?probe=1ef98af428) | Oct 10, 2021 |
| Toshiba       | Satellite M305D             | Notebook    | [1b61cfb354](https://linux-hardware.org/?probe=1b61cfb354) | Oct 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [032398c308](https://linux-hardware.org/?probe=032398c308) | Oct 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [1fe376939c](https://linux-hardware.org/?probe=1fe376939c) | Oct 10, 2021 |
| Dell          | 09KPNV A00                  | Desktop     | [d576cb2dd3](https://linux-hardware.org/?probe=d576cb2dd3) | Oct 10, 2021 |
| Lenovo        | ThinkPad X260 20F5S08N00    | Notebook    | [f8f9a09e2a](https://linux-hardware.org/?probe=f8f9a09e2a) | Oct 10, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [0ca3ca1067](https://linux-hardware.org/?probe=0ca3ca1067) | Oct 10, 2021 |
| Dell          | Vostro 3401                 | Notebook    | [5e53dc591c](https://linux-hardware.org/?probe=5e53dc591c) | Oct 10, 2021 |
| Dell          | Latitude E4300              | Notebook    | [89506f9460](https://linux-hardware.org/?probe=89506f9460) | Oct 10, 2021 |
| HP            | Pavilion g6                 | Notebook    | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ad1aaa06bc](https://linux-hardware.org/?probe=ad1aaa06bc) | Oct 09, 2021 |
| Acer          | Aspire E5-551               | Notebook    | [264e09233b](https://linux-hardware.org/?probe=264e09233b) | Oct 09, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [43d48e705c](https://linux-hardware.org/?probe=43d48e705c) | Oct 09, 2021 |
| ASUSTek       | X555DG                      | Notebook    | [a7e80c532d](https://linux-hardware.org/?probe=a7e80c532d) | Oct 09, 2021 |
| ASUSTek       | P8Z77-M                     | Desktop     | [e2837da9c2](https://linux-hardware.org/?probe=e2837da9c2) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [e5056b55dd](https://linux-hardware.org/?probe=e5056b55dd) | Oct 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [52a27483b1](https://linux-hardware.org/?probe=52a27483b1) | Oct 09, 2021 |
| Lenovo        | ThinkPad T440p 20AN00DJA... | Notebook    | [0797c0312e](https://linux-hardware.org/?probe=0797c0312e) | Oct 09, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a0bc3d8be0](https://linux-hardware.org/?probe=a0bc3d8be0) | Oct 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4fc1c292cb](https://linux-hardware.org/?probe=4fc1c292cb) | Oct 09, 2021 |
| Dell          | Latitude E7250              | Notebook    | [782a17c042](https://linux-hardware.org/?probe=782a17c042) | Oct 09, 2021 |
| ASUSTek       | M2N                         | Desktop     | [f319cddaf6](https://linux-hardware.org/?probe=f319cddaf6) | Oct 09, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [56e9375e76](https://linux-hardware.org/?probe=56e9375e76) | Oct 09, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f62701cf54](https://linux-hardware.org/?probe=f62701cf54) | Oct 09, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [64a98a63e8](https://linux-hardware.org/?probe=64a98a63e8) | Oct 09, 2021 |
| Alienware     | M11x R2                     | Notebook    | [a2bb09f85a](https://linux-hardware.org/?probe=a2bb09f85a) | Oct 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [ba21dd1dd0](https://linux-hardware.org/?probe=ba21dd1dd0) | Oct 08, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [2bb0e878da](https://linux-hardware.org/?probe=2bb0e878da) | Oct 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [d521223809](https://linux-hardware.org/?probe=d521223809) | Oct 08, 2021 |
| MSI           | B550M PRO-VDH               | Desktop     | [b806a146d2](https://linux-hardware.org/?probe=b806a146d2) | Oct 08, 2021 |
| Lenovo        | ThinkPad T420 4236AK9       | Notebook    | [2d3cccc2d0](https://linux-hardware.org/?probe=2d3cccc2d0) | Oct 08, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5cabb513b7](https://linux-hardware.org/?probe=5cabb513b7) | Oct 07, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [ed0af6256d](https://linux-hardware.org/?probe=ed0af6256d) | Oct 07, 2021 |
| Sony          | VGN-NW21MF_W                | Notebook    | [3a4e2269af](https://linux-hardware.org/?probe=3a4e2269af) | Oct 07, 2021 |
| MSI           | Z170M MORTAR                | Desktop     | [f0c8db4bdb](https://linux-hardware.org/?probe=f0c8db4bdb) | Oct 07, 2021 |
| MSI           | Z97-G45 GAMING              | Desktop     | [0d11725312](https://linux-hardware.org/?probe=0d11725312) | Oct 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [9b74440deb](https://linux-hardware.org/?probe=9b74440deb) | Oct 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [9e72075ce8](https://linux-hardware.org/?probe=9e72075ce8) | Oct 07, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [24efeaacb7](https://linux-hardware.org/?probe=24efeaacb7) | Oct 07, 2021 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [d2088e43b2](https://linux-hardware.org/?probe=d2088e43b2) | Oct 07, 2021 |
| Acer          | Aspire E5-573T              | Notebook    | [749a8c4ccc](https://linux-hardware.org/?probe=749a8c4ccc) | Oct 07, 2021 |
| Dell          | Inspiron 7586               | Notebook    | [2ecf794b47](https://linux-hardware.org/?probe=2ecf794b47) | Oct 07, 2021 |
| HP            | 0AECh D                     | Desktop     | [415146d6ec](https://linux-hardware.org/?probe=415146d6ec) | Oct 07, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [396ca17477](https://linux-hardware.org/?probe=396ca17477) | Oct 07, 2021 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [834aacd006](https://linux-hardware.org/?probe=834aacd006) | Oct 07, 2021 |
| ASUSTek       | Q325UAR                     | Convertible | [26ce6dc2b2](https://linux-hardware.org/?probe=26ce6dc2b2) | Oct 07, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [ae154711ac](https://linux-hardware.org/?probe=ae154711ac) | Oct 07, 2021 |
| MSI           | GL63 8RD                    | Notebook    | [9f55f25caf](https://linux-hardware.org/?probe=9f55f25caf) | Oct 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [abd011c6b2](https://linux-hardware.org/?probe=abd011c6b2) | Oct 06, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [018213b3d3](https://linux-hardware.org/?probe=018213b3d3) | Oct 06, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [6a49f40963](https://linux-hardware.org/?probe=6a49f40963) | Oct 06, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [ac4da0432d](https://linux-hardware.org/?probe=ac4da0432d) | Oct 06, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [372dc0e0aa](https://linux-hardware.org/?probe=372dc0e0aa) | Oct 06, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [ac5c6a0dd6](https://linux-hardware.org/?probe=ac5c6a0dd6) | Oct 06, 2021 |
| Unknown       | Intel X79                   | Desktop     | [e3d2bdbc3d](https://linux-hardware.org/?probe=e3d2bdbc3d) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a68932119c](https://linux-hardware.org/?probe=a68932119c) | Oct 05, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [843d9a14d4](https://linux-hardware.org/?probe=843d9a14d4) | Oct 05, 2021 |
| Dell          | Latitude 5501               | Notebook    | [633e0959bc](https://linux-hardware.org/?probe=633e0959bc) | Oct 05, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [dd1daa0074](https://linux-hardware.org/?probe=dd1daa0074) | Oct 05, 2021 |
| ASUSTek       | P7P55D LE                   | Desktop     | [21e7391f6a](https://linux-hardware.org/?probe=21e7391f6a) | Oct 05, 2021 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [4b6c9614d7](https://linux-hardware.org/?probe=4b6c9614d7) | Oct 05, 2021 |
| Acer          | Predator PH315-51           | Notebook    | [fb9a605481](https://linux-hardware.org/?probe=fb9a605481) | Oct 05, 2021 |
| Dell          | Inspiron 5775               | Notebook    | [1f37c7ca65](https://linux-hardware.org/?probe=1f37c7ca65) | Oct 05, 2021 |
| Dell          | Inspiron 5775               | Notebook    | [c42e665e24](https://linux-hardware.org/?probe=c42e665e24) | Oct 05, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [b00fc610cd](https://linux-hardware.org/?probe=b00fc610cd) | Oct 05, 2021 |
| Acer          | Aspire M1930                | Desktop     | [0f21c5864a](https://linux-hardware.org/?probe=0f21c5864a) | Oct 05, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [2fec67511e](https://linux-hardware.org/?probe=2fec67511e) | Oct 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c3cccd51c4](https://linux-hardware.org/?probe=c3cccd51c4) | Oct 05, 2021 |
| Dell          | 09KPNV A00                  | Desktop     | [d99107fc98](https://linux-hardware.org/?probe=d99107fc98) | Oct 04, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [a37e8d930c](https://linux-hardware.org/?probe=a37e8d930c) | Oct 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [9c58f85510](https://linux-hardware.org/?probe=9c58f85510) | Oct 04, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [aee062d6e5](https://linux-hardware.org/?probe=aee062d6e5) | Oct 04, 2021 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [bf6d27f32d](https://linux-hardware.org/?probe=bf6d27f32d) | Oct 04, 2021 |
| Dell          | Latitude 5290               | Notebook    | [e3afd1ef97](https://linux-hardware.org/?probe=e3afd1ef97) | Oct 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [d9dcb6b432](https://linux-hardware.org/?probe=d9dcb6b432) | Oct 04, 2021 |
| Dell          | 0KV62T A01                  | Desktop     | [fbf1a41e0e](https://linux-hardware.org/?probe=fbf1a41e0e) | Oct 04, 2021 |
| Dell          | 0T656F A02                  | Desktop     | [a5080391e9](https://linux-hardware.org/?probe=a5080391e9) | Oct 04, 2021 |
| ASUSTek       | P5Q SE2                     | Desktop     | [36c4b84f94](https://linux-hardware.org/?probe=36c4b84f94) | Oct 04, 2021 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [f34d1166a5](https://linux-hardware.org/?probe=f34d1166a5) | Oct 03, 2021 |
| Dell          | Latitude E4300              | Notebook    | [d6bb983804](https://linux-hardware.org/?probe=d6bb983804) | Oct 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [cf3c05aa68](https://linux-hardware.org/?probe=cf3c05aa68) | Oct 03, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [65388cbcfc](https://linux-hardware.org/?probe=65388cbcfc) | Oct 03, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [97dde270fa](https://linux-hardware.org/?probe=97dde270fa) | Oct 03, 2021 |
| Dell          | 0X8582                      | Desktop     | [ec2be1d168](https://linux-hardware.org/?probe=ec2be1d168) | Oct 03, 2021 |
| Haier         | Y11C                        | Notebook    | [74b9ee5509](https://linux-hardware.org/?probe=74b9ee5509) | Oct 03, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [b95391e679](https://linux-hardware.org/?probe=b95391e679) | Oct 03, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [61c4dc2ac2](https://linux-hardware.org/?probe=61c4dc2ac2) | Oct 03, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b5e9ab8f07](https://linux-hardware.org/?probe=b5e9ab8f07) | Oct 03, 2021 |
| Dell          | Inspiron 3541               | Notebook    | [43649f98a5](https://linux-hardware.org/?probe=43649f98a5) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [96264b5cde](https://linux-hardware.org/?probe=96264b5cde) | Oct 02, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [5e542184d8](https://linux-hardware.org/?probe=5e542184d8) | Oct 02, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [9923b250ea](https://linux-hardware.org/?probe=9923b250ea) | Oct 02, 2021 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [5a6c7b98c0](https://linux-hardware.org/?probe=5a6c7b98c0) | Oct 02, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a7876d8329](https://linux-hardware.org/?probe=a7876d8329) | Oct 02, 2021 |
| Acer          | Predator G3-571             | Notebook    | [de7f48c895](https://linux-hardware.org/?probe=de7f48c895) | Oct 02, 2021 |
| Dell          | Latitude E6430              | Notebook    | [470770630d](https://linux-hardware.org/?probe=470770630d) | Oct 01, 2021 |
| ASUSTek       | G72GX                       | Notebook    | [984966986d](https://linux-hardware.org/?probe=984966986d) | Oct 01, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [a6d1182c1c](https://linux-hardware.org/?probe=a6d1182c1c) | Oct 01, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [4a4f239e4d](https://linux-hardware.org/?probe=4a4f239e4d) | Oct 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5ac27f4e29](https://linux-hardware.org/?probe=5ac27f4e29) | Oct 01, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b1066885ba](https://linux-hardware.org/?probe=b1066885ba) | Oct 01, 2021 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [5913ce5951](https://linux-hardware.org/?probe=5913ce5951) | Oct 01, 2021 |
| Dell          | 0HHV7N A00                  | Desktop     | [601a9a3bec](https://linux-hardware.org/?probe=601a9a3bec) | Oct 01, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6268790a76](https://linux-hardware.org/?probe=6268790a76) | Oct 01, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dc7925e9ed](https://linux-hardware.org/?probe=dc7925e9ed) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [a7e79f067e](https://linux-hardware.org/?probe=a7e79f067e) | Sep 30, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [9c801b9bcf](https://linux-hardware.org/?probe=9c801b9bcf) | Sep 30, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [071fdd49c5](https://linux-hardware.org/?probe=071fdd49c5) | Sep 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6e2173f8b4](https://linux-hardware.org/?probe=6e2173f8b4) | Sep 30, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [af2c7a813d](https://linux-hardware.org/?probe=af2c7a813d) | Sep 30, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [e17f08bb61](https://linux-hardware.org/?probe=e17f08bb61) | Sep 30, 2021 |
| Fujitsu       | U9311                       | Notebook    | [a76f2fbbe3](https://linux-hardware.org/?probe=a76f2fbbe3) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [0b2f645654](https://linux-hardware.org/?probe=0b2f645654) | Sep 30, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [6876f0e86d](https://linux-hardware.org/?probe=6876f0e86d) | Sep 29, 2021 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [ae8aed0f28](https://linux-hardware.org/?probe=ae8aed0f28) | Sep 29, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [3977fe7bd2](https://linux-hardware.org/?probe=3977fe7bd2) | Sep 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1f16dc9356](https://linux-hardware.org/?probe=1f16dc9356) | Sep 29, 2021 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [c63b30f0df](https://linux-hardware.org/?probe=c63b30f0df) | Sep 29, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [cb6b5c443a](https://linux-hardware.org/?probe=cb6b5c443a) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [410a604bab](https://linux-hardware.org/?probe=410a604bab) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1f251e5ba2](https://linux-hardware.org/?probe=1f251e5ba2) | Sep 29, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [5a23abfa74](https://linux-hardware.org/?probe=5a23abfa74) | Sep 29, 2021 |
| Dell          | Latitude E6540              | Notebook    | [f0552909c1](https://linux-hardware.org/?probe=f0552909c1) | Sep 29, 2021 |
| Minix         | NEO Z83-4A                  | Notebook    | [2a5bd76571](https://linux-hardware.org/?probe=2a5bd76571) | Sep 28, 2021 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [c21eff0d32](https://linux-hardware.org/?probe=c21eff0d32) | Sep 28, 2021 |
| Dell          | Latitude E6430              | Notebook    | [178e06b47b](https://linux-hardware.org/?probe=178e06b47b) | Sep 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [9e073b9a8e](https://linux-hardware.org/?probe=9e073b9a8e) | Sep 28, 2021 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | Notebook    | [4a91c75662](https://linux-hardware.org/?probe=4a91c75662) | Sep 28, 2021 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [42c50ac49d](https://linux-hardware.org/?probe=42c50ac49d) | Sep 28, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [053ea52cd6](https://linux-hardware.org/?probe=053ea52cd6) | Sep 28, 2021 |
| ASRock        | Z97 Anniversary             | Desktop     | [c2e1c947ca](https://linux-hardware.org/?probe=c2e1c947ca) | Sep 28, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e9dd5491e8](https://linux-hardware.org/?probe=e9dd5491e8) | Sep 28, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [9fef1cf40f](https://linux-hardware.org/?probe=9fef1cf40f) | Sep 28, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [44d29122aa](https://linux-hardware.org/?probe=44d29122aa) | Sep 28, 2021 |
| Dell          | Latitude D620               | Notebook    | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| Linx          | LINX1010B                   | Notebook    | [5fd6a97443](https://linux-hardware.org/?probe=5fd6a97443) | Sep 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [feed153041](https://linux-hardware.org/?probe=feed153041) | Sep 28, 2021 |
| Dell          | 0D24M8 A01                  | Desktop     | [f1f58938d1](https://linux-hardware.org/?probe=f1f58938d1) | Sep 27, 2021 |
| Haier         | Y11C                        | Notebook    | [591740bf00](https://linux-hardware.org/?probe=591740bf00) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [38a7a4c1d4](https://linux-hardware.org/?probe=38a7a4c1d4) | Sep 27, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [1f148a0dc9](https://linux-hardware.org/?probe=1f148a0dc9) | Sep 27, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [691e7c2746](https://linux-hardware.org/?probe=691e7c2746) | Sep 27, 2021 |
| Dell          | Latitude E6430              | Notebook    | [b442a8bd08](https://linux-hardware.org/?probe=b442a8bd08) | Sep 27, 2021 |
| Dell          | Latitude E5470              | Notebook    | [e466f1b4d8](https://linux-hardware.org/?probe=e466f1b4d8) | Sep 27, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | Notebook    | [591896b2ee](https://linux-hardware.org/?probe=591896b2ee) | Sep 27, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [0646fc1739](https://linux-hardware.org/?probe=0646fc1739) | Sep 27, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [37d30a84ca](https://linux-hardware.org/?probe=37d30a84ca) | Sep 27, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [7af0b1b5dd](https://linux-hardware.org/?probe=7af0b1b5dd) | Sep 27, 2021 |
| Dell          | 0KV62T A01                  | Desktop     | [5792f11670](https://linux-hardware.org/?probe=5792f11670) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [07b1aa0f24](https://linux-hardware.org/?probe=07b1aa0f24) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [2cdb257de7](https://linux-hardware.org/?probe=2cdb257de7) | Sep 27, 2021 |
| Toshiba       | Satellite C50-A             | Notebook    | [b1ae9995d6](https://linux-hardware.org/?probe=b1ae9995d6) | Sep 27, 2021 |
| Acer          | Extensa 2509                | Notebook    | [8383547e0a](https://linux-hardware.org/?probe=8383547e0a) | Sep 27, 2021 |
| Fujitsu       | LIFEBOOK T900               | Notebook    | [b8d983bbb2](https://linux-hardware.org/?probe=b8d983bbb2) | Sep 27, 2021 |
| Positivo      | W940TU                      | Notebook    | [0153e89101](https://linux-hardware.org/?probe=0153e89101) | Sep 27, 2021 |
| Fujitsu       | LIFEBOOK T900               | Notebook    | [0ad5cc2ce2](https://linux-hardware.org/?probe=0ad5cc2ce2) | Sep 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6886cfc383](https://linux-hardware.org/?probe=6886cfc383) | Sep 26, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [4d6c77accb](https://linux-hardware.org/?probe=4d6c77accb) | Sep 26, 2021 |
| Positivo      | W940TU                      | Notebook    | [fc44f175b0](https://linux-hardware.org/?probe=fc44f175b0) | Sep 26, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [28a3e24d5a](https://linux-hardware.org/?probe=28a3e24d5a) | Sep 26, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [99ffc0752c](https://linux-hardware.org/?probe=99ffc0752c) | Sep 26, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [c5da6d90b3](https://linux-hardware.org/?probe=c5da6d90b3) | Sep 26, 2021 |
| ASUSTek       | GL702VSK                    | Notebook    | [bdc99c7ccb](https://linux-hardware.org/?probe=bdc99c7ccb) | Sep 26, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [4a373f1855](https://linux-hardware.org/?probe=4a373f1855) | Sep 26, 2021 |
| Dell          | Inspiron 15-3573            | Notebook    | [320d64d26e](https://linux-hardware.org/?probe=320d64d26e) | Sep 26, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [123113ddfd](https://linux-hardware.org/?probe=123113ddfd) | Sep 26, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [bb17541aae](https://linux-hardware.org/?probe=bb17541aae) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [58e81067e0](https://linux-hardware.org/?probe=58e81067e0) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [5e8a05628b](https://linux-hardware.org/?probe=5e8a05628b) | Sep 26, 2021 |
| Dell          | Latitude E5470              | Notebook    | [24f254f7e8](https://linux-hardware.org/?probe=24f254f7e8) | Sep 25, 2021 |
| Lenovo        | Yoga C640-13IML LTE 81XL    | Convertible | [527cc99b36](https://linux-hardware.org/?probe=527cc99b36) | Sep 25, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [2ae9eaaa44](https://linux-hardware.org/?probe=2ae9eaaa44) | Sep 25, 2021 |
| Dell          | Latitude 5420               | Notebook    | [63d0044154](https://linux-hardware.org/?probe=63d0044154) | Sep 25, 2021 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [be6ac18b04](https://linux-hardware.org/?probe=be6ac18b04) | Sep 25, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [b484f4f0cc](https://linux-hardware.org/?probe=b484f4f0cc) | Sep 25, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [d2aaa88c7a](https://linux-hardware.org/?probe=d2aaa88c7a) | Sep 25, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [8bb0307157](https://linux-hardware.org/?probe=8bb0307157) | Sep 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [0a11365d2c](https://linux-hardware.org/?probe=0a11365d2c) | Sep 25, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c68b87dd56](https://linux-hardware.org/?probe=c68b87dd56) | Sep 25, 2021 |
| ASRock        | Z390M Pro4                  | Desktop     | [7be02e74b3](https://linux-hardware.org/?probe=7be02e74b3) | Sep 25, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dd082afe88](https://linux-hardware.org/?probe=dd082afe88) | Sep 24, 2021 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [3aad736b24](https://linux-hardware.org/?probe=3aad736b24) | Sep 24, 2021 |
| ASRock        | Z390M Pro4                  | Desktop     | [449f4436f5](https://linux-hardware.org/?probe=449f4436f5) | Sep 24, 2021 |
| HP            | 843F                        | Desktop     | [2160393dde](https://linux-hardware.org/?probe=2160393dde) | Sep 24, 2021 |
| HP            | 843F                        | Desktop     | [be648e45cb](https://linux-hardware.org/?probe=be648e45cb) | Sep 24, 2021 |
| Toshiba       | Satellite C70D-A            | Notebook    | [936256d533](https://linux-hardware.org/?probe=936256d533) | Sep 24, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [7565c48d46](https://linux-hardware.org/?probe=7565c48d46) | Sep 24, 2021 |
| ASUSTek       | A55BM-K                     | Desktop     | [e06893df36](https://linux-hardware.org/?probe=e06893df36) | Sep 24, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [004998105d](https://linux-hardware.org/?probe=004998105d) | Sep 24, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [01362b36bf](https://linux-hardware.org/?probe=01362b36bf) | Sep 24, 2021 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [44e4e1004f](https://linux-hardware.org/?probe=44e4e1004f) | Sep 24, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9d304a5b9f](https://linux-hardware.org/?probe=9d304a5b9f) | Sep 24, 2021 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [adf32ca36b](https://linux-hardware.org/?probe=adf32ca36b) | Sep 24, 2021 |
| ASUSTek       | U47A                        | Notebook    | [226b519fcc](https://linux-hardware.org/?probe=226b519fcc) | Sep 23, 2021 |
| HP            | 18E4                        | Desktop     | [fbd08bc910](https://linux-hardware.org/?probe=fbd08bc910) | Sep 23, 2021 |
| Acer          | EG43M                       | Desktop     | [e355190768](https://linux-hardware.org/?probe=e355190768) | Sep 23, 2021 |
| Acer          | EG43M                       | Desktop     | [e9e005a181](https://linux-hardware.org/?probe=e9e005a181) | Sep 23, 2021 |
| HP            | 0AA8h                       | Desktop     | [b702f1c3a2](https://linux-hardware.org/?probe=b702f1c3a2) | Sep 23, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [d9d5a32bc0](https://linux-hardware.org/?probe=d9d5a32bc0) | Sep 23, 2021 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [9405707012](https://linux-hardware.org/?probe=9405707012) | Sep 23, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [01f37a66c7](https://linux-hardware.org/?probe=01f37a66c7) | Sep 23, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [b4bd76d198](https://linux-hardware.org/?probe=b4bd76d198) | Sep 23, 2021 |
| ASUSTek       | U36JC                       | Notebook    | [c6e87f1fb7](https://linux-hardware.org/?probe=c6e87f1fb7) | Sep 23, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [bc776de3a8](https://linux-hardware.org/?probe=bc776de3a8) | Sep 23, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [46af053a8e](https://linux-hardware.org/?probe=46af053a8e) | Sep 23, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [67338cd31a](https://linux-hardware.org/?probe=67338cd31a) | Sep 23, 2021 |
| HP            | 18E7                        | Desktop     | [4c52ebef48](https://linux-hardware.org/?probe=4c52ebef48) | Sep 22, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ab056c254d](https://linux-hardware.org/?probe=ab056c254d) | Sep 22, 2021 |
| Dell          | Latitude 5480               | Notebook    | [a62c0b3e81](https://linux-hardware.org/?probe=a62c0b3e81) | Sep 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b08cd2f11d](https://linux-hardware.org/?probe=b08cd2f11d) | Sep 22, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [b9fcdffa50](https://linux-hardware.org/?probe=b9fcdffa50) | Sep 22, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [710301deba](https://linux-hardware.org/?probe=710301deba) | Sep 22, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [9662887c26](https://linux-hardware.org/?probe=9662887c26) | Sep 22, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [fd1153a7da](https://linux-hardware.org/?probe=fd1153a7da) | Sep 22, 2021 |
| HP            | G42                         | Notebook    | [3f3e8bf19a](https://linux-hardware.org/?probe=3f3e8bf19a) | Sep 22, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [0860cc542c](https://linux-hardware.org/?probe=0860cc542c) | Sep 21, 2021 |
| Acer          | EG43M                       | Desktop     | [48c256116d](https://linux-hardware.org/?probe=48c256116d) | Sep 21, 2021 |
| Dell          | 0KV62T A01                  | Desktop     | [70b115b474](https://linux-hardware.org/?probe=70b115b474) | Sep 21, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [fce5a6bf2a](https://linux-hardware.org/?probe=fce5a6bf2a) | Sep 21, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [7e0c5640af](https://linux-hardware.org/?probe=7e0c5640af) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b44b19f051](https://linux-hardware.org/?probe=b44b19f051) | Sep 21, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [323169caf9](https://linux-hardware.org/?probe=323169caf9) | Sep 21, 2021 |
| Dell          | 00TD00 A00                  | All in one  | [8f04a0df98](https://linux-hardware.org/?probe=8f04a0df98) | Sep 21, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [17c3d61831](https://linux-hardware.org/?probe=17c3d61831) | Sep 21, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [ef22f8090a](https://linux-hardware.org/?probe=ef22f8090a) | Sep 20, 2021 |
| Acer          | Aspire 7740                 | Notebook    | [dda5431cbb](https://linux-hardware.org/?probe=dda5431cbb) | Sep 20, 2021 |
| Acer          | Spin SP314-54N              | Convertible | [2f463816d0](https://linux-hardware.org/?probe=2f463816d0) | Sep 20, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [c0334c463b](https://linux-hardware.org/?probe=c0334c463b) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | Desktop     | [feb9cf5a3f](https://linux-hardware.org/?probe=feb9cf5a3f) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | Desktop     | [0025ab8888](https://linux-hardware.org/?probe=0025ab8888) | Sep 20, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [0d4306fd72](https://linux-hardware.org/?probe=0d4306fd72) | Sep 20, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [ab2b72b7d5](https://linux-hardware.org/?probe=ab2b72b7d5) | Sep 20, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [d922af010d](https://linux-hardware.org/?probe=d922af010d) | Sep 19, 2021 |
| Dell          | Latitude 7424 Rugged Ext... | Notebook    | [362307c0b1](https://linux-hardware.org/?probe=362307c0b1) | Sep 19, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [fc7ea9d020](https://linux-hardware.org/?probe=fc7ea9d020) | Sep 19, 2021 |
| MSI           | MS-7058 100                 | Desktop     | [e8b0580c54](https://linux-hardware.org/?probe=e8b0580c54) | Sep 19, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [9f31d3090b](https://linux-hardware.org/?probe=9f31d3090b) | Sep 19, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [1d86899e9a](https://linux-hardware.org/?probe=1d86899e9a) | Sep 19, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b9c711e311](https://linux-hardware.org/?probe=b9c711e311) | Sep 19, 2021 |
| Notebook      | NL40_50CU                   | Notebook    | [9319323793](https://linux-hardware.org/?probe=9319323793) | Sep 19, 2021 |
| Toshiba       | Satellite C855-2J5          | Notebook    | [56c7260e38](https://linux-hardware.org/?probe=56c7260e38) | Sep 19, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d51e979887](https://linux-hardware.org/?probe=d51e979887) | Sep 19, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [c1d4799ecf](https://linux-hardware.org/?probe=c1d4799ecf) | Sep 18, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [e624a1c725](https://linux-hardware.org/?probe=e624a1c725) | Sep 18, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [2149dc459f](https://linux-hardware.org/?probe=2149dc459f) | Sep 18, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a3bffa63dd](https://linux-hardware.org/?probe=a3bffa63dd) | Sep 18, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [b079ec3bca](https://linux-hardware.org/?probe=b079ec3bca) | Sep 18, 2021 |
| Dell          | 0X8582                      | Desktop     | [e4ea4d8c3e](https://linux-hardware.org/?probe=e4ea4d8c3e) | Sep 18, 2021 |
| TUXEDO        | N130BU                      | Notebook    | [12a72404ea](https://linux-hardware.org/?probe=12a72404ea) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7fbc9198ca](https://linux-hardware.org/?probe=7fbc9198ca) | Sep 18, 2021 |
| Dell          | 0VRWRC A01                  | Desktop     | [c2a88904db](https://linux-hardware.org/?probe=c2a88904db) | Sep 18, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [3a0e961b45](https://linux-hardware.org/?probe=3a0e961b45) | Sep 18, 2021 |
| MSI           | A75MA-G55                   | Desktop     | [2e92160434](https://linux-hardware.org/?probe=2e92160434) | Sep 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [fe662b5b36](https://linux-hardware.org/?probe=fe662b5b36) | Sep 18, 2021 |
| Digma         | EVE 1806 ES1028EW           | Tablet      | [2126b68f8f](https://linux-hardware.org/?probe=2126b68f8f) | Sep 18, 2021 |
| Biostar       | A68MHE                      | Desktop     | [8a2cdafa86](https://linux-hardware.org/?probe=8a2cdafa86) | Sep 18, 2021 |
| Digma         | EVE 1806 ES1028EW           | Tablet      | [336c8f0d42](https://linux-hardware.org/?probe=336c8f0d42) | Sep 18, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [369e99699a](https://linux-hardware.org/?probe=369e99699a) | Sep 18, 2021 |
| Acer          | FIH57                       | Desktop     | [af740ea4c9](https://linux-hardware.org/?probe=af740ea4c9) | Sep 18, 2021 |
| Acer          | FIH57                       | Desktop     | [1f486783b8](https://linux-hardware.org/?probe=1f486783b8) | Sep 18, 2021 |
| MSI           | MS-7058 100                 | Desktop     | [87a56cdea2](https://linux-hardware.org/?probe=87a56cdea2) | Sep 18, 2021 |
| ASUSTek       | U50Vg                       | Notebook    | [8a8cd9fece](https://linux-hardware.org/?probe=8a8cd9fece) | Sep 18, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [89eb27bf06](https://linux-hardware.org/?probe=89eb27bf06) | Sep 18, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [e646bde765](https://linux-hardware.org/?probe=e646bde765) | Sep 17, 2021 |
| ASUSTek       | N71Vg                       | Notebook    | [8e1fd4910a](https://linux-hardware.org/?probe=8e1fd4910a) | Sep 17, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [d374535153](https://linux-hardware.org/?probe=d374535153) | Sep 17, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [4340e989f9](https://linux-hardware.org/?probe=4340e989f9) | Sep 17, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 1 ... | Convertible | [49dbad6fdb](https://linux-hardware.org/?probe=49dbad6fdb) | Sep 17, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [85cb48e026](https://linux-hardware.org/?probe=85cb48e026) | Sep 17, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [76f8472281](https://linux-hardware.org/?probe=76f8472281) | Sep 16, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [b0952519eb](https://linux-hardware.org/?probe=b0952519eb) | Sep 16, 2021 |
| HP            | 339A                        | Desktop     | [973b7c1b1f](https://linux-hardware.org/?probe=973b7c1b1f) | Sep 16, 2021 |
| Intel         | NUC8i7HVB J68196-602        | Mini pc     | [507fbfc464](https://linux-hardware.org/?probe=507fbfc464) | Sep 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [07bb7a41c1](https://linux-hardware.org/?probe=07bb7a41c1) | Sep 16, 2021 |
| HP            | Notebook                    | Notebook    | [f4ae81e712](https://linux-hardware.org/?probe=f4ae81e712) | Sep 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b2b889b773](https://linux-hardware.org/?probe=b2b889b773) | Sep 16, 2021 |
| HP            | 3048h                       | Desktop     | [b7b670e814](https://linux-hardware.org/?probe=b7b670e814) | Sep 16, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [1c61b20dd4](https://linux-hardware.org/?probe=1c61b20dd4) | Sep 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [0eb4a7ecb7](https://linux-hardware.org/?probe=0eb4a7ecb7) | Sep 16, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [134631220f](https://linux-hardware.org/?probe=134631220f) | Sep 16, 2021 |
| Dell          | Latitude 9520               | Convertible | [ce071bc833](https://linux-hardware.org/?probe=ce071bc833) | Sep 16, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [bf09dd7f40](https://linux-hardware.org/?probe=bf09dd7f40) | Sep 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4d4918a470](https://linux-hardware.org/?probe=4d4918a470) | Sep 15, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [8d085a9a13](https://linux-hardware.org/?probe=8d085a9a13) | Sep 15, 2021 |
| AMD           | ETHANOL_DEBUG_X             | Server      | [04144b327a](https://linux-hardware.org/?probe=04144b327a) | Sep 15, 2021 |
| Toshiba       | TECRA A50-C                 | Notebook    | [1a625d3feb](https://linux-hardware.org/?probe=1a625d3feb) | Sep 15, 2021 |
| Acer          | Aspire 8730                 | Notebook    | [6e53b2cfa9](https://linux-hardware.org/?probe=6e53b2cfa9) | Sep 15, 2021 |
| ASUSTek       | U50Vg                       | Notebook    | [7d12a66551](https://linux-hardware.org/?probe=7d12a66551) | Sep 15, 2021 |
| ASUSTek       | P8H77-M                     | Desktop     | [1efbf10e10](https://linux-hardware.org/?probe=1efbf10e10) | Sep 15, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [218d153444](https://linux-hardware.org/?probe=218d153444) | Sep 15, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [6209c3e2c2](https://linux-hardware.org/?probe=6209c3e2c2) | Sep 15, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [c5f600efd8](https://linux-hardware.org/?probe=c5f600efd8) | Sep 15, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [c51f5529e4](https://linux-hardware.org/?probe=c51f5529e4) | Sep 15, 2021 |
| ASUSTek       | N552VX                      | Notebook    | [ca7b7f7df9](https://linux-hardware.org/?probe=ca7b7f7df9) | Sep 15, 2021 |
| HP            | 212B                        | Desktop     | [9a7f2627a3](https://linux-hardware.org/?probe=9a7f2627a3) | Sep 15, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c9286413a5](https://linux-hardware.org/?probe=c9286413a5) | Sep 15, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6488a302af](https://linux-hardware.org/?probe=6488a302af) | Sep 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [5fb084ffa4](https://linux-hardware.org/?probe=5fb084ffa4) | Sep 15, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [d210c0aca3](https://linux-hardware.org/?probe=d210c0aca3) | Sep 15, 2021 |
| ASUSTek       | N751JK                      | Notebook    | [9d34ea25cd](https://linux-hardware.org/?probe=9d34ea25cd) | Sep 14, 2021 |
| Dell          | Latitude 5290               | Notebook    | [baae3812d5](https://linux-hardware.org/?probe=baae3812d5) | Sep 14, 2021 |
| Lenovo        | ThinkPad T450s 20BWZ0CKU... | Notebook    | [a9e206d41b](https://linux-hardware.org/?probe=a9e206d41b) | Sep 14, 2021 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [b193a554c5](https://linux-hardware.org/?probe=b193a554c5) | Sep 14, 2021 |
| HP            | 212B                        | Desktop     | [289f117cde](https://linux-hardware.org/?probe=289f117cde) | Sep 14, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [e5804af7f6](https://linux-hardware.org/?probe=e5804af7f6) | Sep 14, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [67361acb38](https://linux-hardware.org/?probe=67361acb38) | Sep 14, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [f7cc010076](https://linux-hardware.org/?probe=f7cc010076) | Sep 14, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d172a59c18](https://linux-hardware.org/?probe=d172a59c18) | Sep 14, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [9631d6f9e1](https://linux-hardware.org/?probe=9631d6f9e1) | Sep 14, 2021 |
| ASUSTek       | P5K-VM                      | Desktop     | [59fc10448f](https://linux-hardware.org/?probe=59fc10448f) | Sep 14, 2021 |
| Advance       | AN-5431                     | Notebook    | [d48465a943](https://linux-hardware.org/?probe=d48465a943) | Sep 14, 2021 |
| Dell          | Latitude E7270              | Notebook    | [479b6d4aa9](https://linux-hardware.org/?probe=479b6d4aa9) | Sep 14, 2021 |
| Toshiba       | Satellite C55-C             | Notebook    | [8966b3a7b5](https://linux-hardware.org/?probe=8966b3a7b5) | Sep 14, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [7e07383aa8](https://linux-hardware.org/?probe=7e07383aa8) | Sep 14, 2021 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [7d4ed6e466](https://linux-hardware.org/?probe=7d4ed6e466) | Sep 13, 2021 |
| Microsoft     | Surface Book                | Tablet      | [43b4359eff](https://linux-hardware.org/?probe=43b4359eff) | Sep 13, 2021 |
| Sony          | SVS1312G3EW                 | Notebook    | [0a315b4077](https://linux-hardware.org/?probe=0a315b4077) | Sep 13, 2021 |
| Sony          | SVS1312G3EW                 | Notebook    | [bee47d862e](https://linux-hardware.org/?probe=bee47d862e) | Sep 13, 2021 |
| Dell          | Latitude 7370               | Notebook    | [7b446e8905](https://linux-hardware.org/?probe=7b446e8905) | Sep 13, 2021 |
| Dell          | Latitude 7370               | Notebook    | [ec12323a7e](https://linux-hardware.org/?probe=ec12323a7e) | Sep 13, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [51a17a84a4](https://linux-hardware.org/?probe=51a17a84a4) | Sep 13, 2021 |
| Dell          | 0VRWRC A01                  | Desktop     | [a14cd2accb](https://linux-hardware.org/?probe=a14cd2accb) | Sep 13, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [9624b39eea](https://linux-hardware.org/?probe=9624b39eea) | Sep 13, 2021 |
| HP            | Notebook                    | Notebook    | [9082e7207c](https://linux-hardware.org/?probe=9082e7207c) | Sep 13, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [651fc72613](https://linux-hardware.org/?probe=651fc72613) | Sep 13, 2021 |
| ASUSTek       | U50Vg                       | Notebook    | [f5d7593025](https://linux-hardware.org/?probe=f5d7593025) | Sep 13, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [229830926d](https://linux-hardware.org/?probe=229830926d) | Sep 13, 2021 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [4f79120f74](https://linux-hardware.org/?probe=4f79120f74) | Sep 13, 2021 |
| Thomson       | WWNEO14A-2BK32              | Notebook    | [1423ee3d10](https://linux-hardware.org/?probe=1423ee3d10) | Sep 13, 2021 |
| Dell          | 0VRWRC A01                  | Desktop     | [442dd66231](https://linux-hardware.org/?probe=442dd66231) | Sep 13, 2021 |
| Schenker      | XMG CORE (TGL/M21)          | Notebook    | [d1f9d8c10c](https://linux-hardware.org/?probe=d1f9d8c10c) | Sep 13, 2021 |
| Dell          | Precision 5540              | Notebook    | [2888ae8d0a](https://linux-hardware.org/?probe=2888ae8d0a) | Sep 13, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | Notebook    | [c4f8c481e7](https://linux-hardware.org/?probe=c4f8c481e7) | Sep 13, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3534d3e5f1](https://linux-hardware.org/?probe=3534d3e5f1) | Sep 13, 2021 |
| Dell          | Latitude 5400               | Notebook    | [1fed0bdd29](https://linux-hardware.org/?probe=1fed0bdd29) | Sep 13, 2021 |
| ASUSTek       | U50Vg                       | Notebook    | [8013b7cbcf](https://linux-hardware.org/?probe=8013b7cbcf) | Sep 13, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [31ca803af1](https://linux-hardware.org/?probe=31ca803af1) | Sep 13, 2021 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [7433bea790](https://linux-hardware.org/?probe=7433bea790) | Sep 13, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f8ebf7eb90](https://linux-hardware.org/?probe=f8ebf7eb90) | Sep 13, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [d4ae821034](https://linux-hardware.org/?probe=d4ae821034) | Sep 12, 2021 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [3d3b3161f5](https://linux-hardware.org/?probe=3d3b3161f5) | Sep 12, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [edb5bc2cac](https://linux-hardware.org/?probe=edb5bc2cac) | Sep 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | Desktop     | [4404093ccf](https://linux-hardware.org/?probe=4404093ccf) | Sep 12, 2021 |
| ASUSTek       | Leonite2                    | Desktop     | [be99559571](https://linux-hardware.org/?probe=be99559571) | Sep 12, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [1124d5133b](https://linux-hardware.org/?probe=1124d5133b) | Sep 12, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [0bba3925b9](https://linux-hardware.org/?probe=0bba3925b9) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [675a3f37b7](https://linux-hardware.org/?probe=675a3f37b7) | Sep 12, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [ed7eccc83b](https://linux-hardware.org/?probe=ed7eccc83b) | Sep 12, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [edc7645bfe](https://linux-hardware.org/?probe=edc7645bfe) | Sep 12, 2021 |
| Acer          | Revo RN96                   | Desktop     | [1559422fd4](https://linux-hardware.org/?probe=1559422fd4) | Sep 12, 2021 |
| Dell          | 0X8582                      | Desktop     | [75d86d9235](https://linux-hardware.org/?probe=75d86d9235) | Sep 12, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4a621d71b7](https://linux-hardware.org/?probe=4a621d71b7) | Sep 12, 2021 |
| Unknown       | G41                         | Desktop     | [0ac983ecc1](https://linux-hardware.org/?probe=0ac983ecc1) | Sep 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a11f12a84a](https://linux-hardware.org/?probe=a11f12a84a) | Sep 12, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [5306165bd6](https://linux-hardware.org/?probe=5306165bd6) | Sep 12, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [8fe2203713](https://linux-hardware.org/?probe=8fe2203713) | Sep 12, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [395e1bc884](https://linux-hardware.org/?probe=395e1bc884) | Sep 12, 2021 |
| Acer          | Revo RN96                   | Desktop     | [9bfcad9af4](https://linux-hardware.org/?probe=9bfcad9af4) | Sep 11, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [800d54370e](https://linux-hardware.org/?probe=800d54370e) | Sep 11, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [3be61fa185](https://linux-hardware.org/?probe=3be61fa185) | Sep 11, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [76e1a2a3f6](https://linux-hardware.org/?probe=76e1a2a3f6) | Sep 11, 2021 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [5f2cc29efc](https://linux-hardware.org/?probe=5f2cc29efc) | Sep 11, 2021 |
| Toshiba       | Satellite C850-1MC          | Notebook    | [98127c6225](https://linux-hardware.org/?probe=98127c6225) | Sep 11, 2021 |
| ASUSTek       | H110M-C                     | Desktop     | [e73e96c866](https://linux-hardware.org/?probe=e73e96c866) | Sep 11, 2021 |
| Toshiba       | Satellite Z930              | Notebook    | [2768d5ccb6](https://linux-hardware.org/?probe=2768d5ccb6) | Sep 11, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [67285c1d5d](https://linux-hardware.org/?probe=67285c1d5d) | Sep 11, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [c8da3fea5a](https://linux-hardware.org/?probe=c8da3fea5a) | Sep 11, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [dd09fcf11e](https://linux-hardware.org/?probe=dd09fcf11e) | Sep 10, 2021 |
| Timi          | TM1613                      | Notebook    | [a79355ced3](https://linux-hardware.org/?probe=a79355ced3) | Sep 10, 2021 |
| Dell          | G5 5587                     | Notebook    | [943e12f3e8](https://linux-hardware.org/?probe=943e12f3e8) | Sep 10, 2021 |
| ASUSTek       | P8H77-M                     | Desktop     | [088a432984](https://linux-hardware.org/?probe=088a432984) | Sep 10, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [74817fdcb8](https://linux-hardware.org/?probe=74817fdcb8) | Sep 10, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [ddcedfc109](https://linux-hardware.org/?probe=ddcedfc109) | Sep 10, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [0a2430ae78](https://linux-hardware.org/?probe=0a2430ae78) | Sep 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ab69e5a8f1](https://linux-hardware.org/?probe=ab69e5a8f1) | Sep 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [20664604ad](https://linux-hardware.org/?probe=20664604ad) | Sep 10, 2021 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [6829dbdafc](https://linux-hardware.org/?probe=6829dbdafc) | Sep 10, 2021 |
| Dell          | Latitude E5400              | Notebook    | [191b8606ba](https://linux-hardware.org/?probe=191b8606ba) | Sep 09, 2021 |
| Quanta        | S3E-MB 31S3EMB0010          | Server      | [01858bfdb7](https://linux-hardware.org/?probe=01858bfdb7) | Sep 09, 2021 |
| Notebook      | NJ5x_NJ7xLU                 | Notebook    | [4d544fc5d5](https://linux-hardware.org/?probe=4d544fc5d5) | Sep 09, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5d7c3904aa](https://linux-hardware.org/?probe=5d7c3904aa) | Sep 09, 2021 |
| Lenovo        | ThinkPad T410 2522WZN       | Notebook    | [b6c19325a4](https://linux-hardware.org/?probe=b6c19325a4) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [0e6deb049c](https://linux-hardware.org/?probe=0e6deb049c) | Sep 09, 2021 |
| Thomson       | WWNEO14A-2BK32              | Notebook    | [752aa1b840](https://linux-hardware.org/?probe=752aa1b840) | Sep 09, 2021 |
| Dell          | Latitude 5520               | Notebook    | [7e327f4604](https://linux-hardware.org/?probe=7e327f4604) | Sep 09, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [443986835d](https://linux-hardware.org/?probe=443986835d) | Sep 09, 2021 |
| Dell          | Latitude 9520               | Convertible | [d66cb50bbc](https://linux-hardware.org/?probe=d66cb50bbc) | Sep 08, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f04053a978](https://linux-hardware.org/?probe=f04053a978) | Sep 08, 2021 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [1619cb6257](https://linux-hardware.org/?probe=1619cb6257) | Sep 08, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [588250b1be](https://linux-hardware.org/?probe=588250b1be) | Sep 08, 2021 |
| TUXEDO        | N130BU                      | Notebook    | [e81e4cc415](https://linux-hardware.org/?probe=e81e4cc415) | Sep 08, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [2d9e427f68](https://linux-hardware.org/?probe=2d9e427f68) | Sep 08, 2021 |
| ASUSTek       | P55VA                       | Notebook    | [b00df8e82a](https://linux-hardware.org/?probe=b00df8e82a) | Sep 08, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [930ad79fe0](https://linux-hardware.org/?probe=930ad79fe0) | Sep 08, 2021 |
| Lenovo        | IdeaPad Gaming3 15ARH05D... | Notebook    | [f1bdc44923](https://linux-hardware.org/?probe=f1bdc44923) | Sep 08, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [56f6e80ac3](https://linux-hardware.org/?probe=56f6e80ac3) | Sep 07, 2021 |
| Timi          | A35S                        | Notebook    | [0b22fc8994](https://linux-hardware.org/?probe=0b22fc8994) | Sep 07, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [46f2f68684](https://linux-hardware.org/?probe=46f2f68684) | Sep 07, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [4963032754](https://linux-hardware.org/?probe=4963032754) | Sep 07, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0C50... | Notebook    | [5ac7df1c1c](https://linux-hardware.org/?probe=5ac7df1c1c) | Sep 07, 2021 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [6add940021](https://linux-hardware.org/?probe=6add940021) | Sep 07, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [7ca1df084e](https://linux-hardware.org/?probe=7ca1df084e) | Sep 07, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [ddee404146](https://linux-hardware.org/?probe=ddee404146) | Sep 07, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [9e43cd58cd](https://linux-hardware.org/?probe=9e43cd58cd) | Sep 07, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [94a243f26a](https://linux-hardware.org/?probe=94a243f26a) | Sep 07, 2021 |
| Acer          | Aspire XC-830               | Desktop     | [859878d1b2](https://linux-hardware.org/?probe=859878d1b2) | Sep 06, 2021 |
| Acer          | Swift SF514-51              | Notebook    | [6ab5bc3174](https://linux-hardware.org/?probe=6ab5bc3174) | Sep 06, 2021 |
| Acer          | Swift SF514-51              | Notebook    | [1bf499eb80](https://linux-hardware.org/?probe=1bf499eb80) | Sep 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [2d70c02261](https://linux-hardware.org/?probe=2d70c02261) | Sep 06, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [463f501179](https://linux-hardware.org/?probe=463f501179) | Sep 06, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [ee58e16f17](https://linux-hardware.org/?probe=ee58e16f17) | Sep 06, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [c18c52cd70](https://linux-hardware.org/?probe=c18c52cd70) | Sep 06, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [d45a82c3c9](https://linux-hardware.org/?probe=d45a82c3c9) | Sep 06, 2021 |
| HP            | 870C                        | Desktop     | [f46fa4ba94](https://linux-hardware.org/?probe=f46fa4ba94) | Sep 06, 2021 |
| HP            | 870C                        | Desktop     | [fcd88590bc](https://linux-hardware.org/?probe=fcd88590bc) | Sep 06, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [d410366b57](https://linux-hardware.org/?probe=d410366b57) | Sep 06, 2021 |
| TUXEDO        | P65_P67RGRERA               | Notebook    | [342dd3e712](https://linux-hardware.org/?probe=342dd3e712) | Sep 06, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [129a34a37f](https://linux-hardware.org/?probe=129a34a37f) | Sep 06, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [e72963a1b5](https://linux-hardware.org/?probe=e72963a1b5) | Sep 06, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [28a20b5f72](https://linux-hardware.org/?probe=28a20b5f72) | Sep 06, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c6e769829b](https://linux-hardware.org/?probe=c6e769829b) | Sep 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [eb43b257f2](https://linux-hardware.org/?probe=eb43b257f2) | Sep 05, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [51e31a6fa5](https://linux-hardware.org/?probe=51e31a6fa5) | Sep 05, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [4bfe01463e](https://linux-hardware.org/?probe=4bfe01463e) | Sep 05, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [f1300c2d55](https://linux-hardware.org/?probe=f1300c2d55) | Sep 05, 2021 |
| AMI           | Intel                       | Convertible | [4534d06570](https://linux-hardware.org/?probe=4534d06570) | Sep 05, 2021 |
| ASRock        | B365M Pro4                  | Desktop     | [a244333b78](https://linux-hardware.org/?probe=a244333b78) | Sep 05, 2021 |
| HP            | 339A                        | Desktop     | [ceb91782c2](https://linux-hardware.org/?probe=ceb91782c2) | Sep 05, 2021 |
| Intel         | SharkBay Platform           | Notebook    | [a19a4b3125](https://linux-hardware.org/?probe=a19a4b3125) | Sep 05, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [69ca9e90ae](https://linux-hardware.org/?probe=69ca9e90ae) | Sep 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [06404619aa](https://linux-hardware.org/?probe=06404619aa) | Sep 04, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [22390a295d](https://linux-hardware.org/?probe=22390a295d) | Sep 04, 2021 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [d1705e50a2](https://linux-hardware.org/?probe=d1705e50a2) | Sep 04, 2021 |
| HP            | 1494                        | Desktop     | [064f4ff59f](https://linux-hardware.org/?probe=064f4ff59f) | Sep 04, 2021 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [9e63bc0888](https://linux-hardware.org/?probe=9e63bc0888) | Sep 04, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [f88ba2a8ea](https://linux-hardware.org/?probe=f88ba2a8ea) | Sep 04, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [f42fc0ef77](https://linux-hardware.org/?probe=f42fc0ef77) | Sep 04, 2021 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [b02379df11](https://linux-hardware.org/?probe=b02379df11) | Sep 04, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [4d7a9bb2cf](https://linux-hardware.org/?probe=4d7a9bb2cf) | Sep 04, 2021 |
| Dynabook      | PORTEGE X30W-J              | Convertible | [1cfe27d3d1](https://linux-hardware.org/?probe=1cfe27d3d1) | Sep 04, 2021 |
| Dynabook      | PORTEGE X30W-J              | Convertible | [32d0a89cc6](https://linux-hardware.org/?probe=32d0a89cc6) | Sep 04, 2021 |
| IP3 Tech      | AB3                         | Mini pc     | [60cd252284](https://linux-hardware.org/?probe=60cd252284) | Sep 04, 2021 |
| HP            | Pavilion 17                 | Notebook    | [ef065acdd0](https://linux-hardware.org/?probe=ef065acdd0) | Sep 04, 2021 |
| Lenovo        | ThinkPad L470 20J5S2CP00    | Notebook    | [9ba4ef1dc5](https://linux-hardware.org/?probe=9ba4ef1dc5) | Sep 04, 2021 |
| Pegatron      | Maureen                     | Desktop     | [c5ab105ead](https://linux-hardware.org/?probe=c5ab105ead) | Sep 04, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [811f366c65](https://linux-hardware.org/?probe=811f366c65) | Sep 03, 2021 |
| Lenovo        | U310                        | Notebook    | [0be64d0c02](https://linux-hardware.org/?probe=0be64d0c02) | Sep 03, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [ae8bd5e632](https://linux-hardware.org/?probe=ae8bd5e632) | Sep 03, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [df9db29c8e](https://linux-hardware.org/?probe=df9db29c8e) | Sep 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d26d6327b1](https://linux-hardware.org/?probe=d26d6327b1) | Sep 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7b86b0dee4](https://linux-hardware.org/?probe=7b86b0dee4) | Sep 03, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [54ddd1baea](https://linux-hardware.org/?probe=54ddd1baea) | Sep 03, 2021 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [611c3c0c19](https://linux-hardware.org/?probe=611c3c0c19) | Sep 03, 2021 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [7f07140410](https://linux-hardware.org/?probe=7f07140410) | Sep 03, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [a507f9835b](https://linux-hardware.org/?probe=a507f9835b) | Sep 03, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [6275aab341](https://linux-hardware.org/?probe=6275aab341) | Sep 03, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5377e486bc](https://linux-hardware.org/?probe=5377e486bc) | Sep 03, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [79fc56898c](https://linux-hardware.org/?probe=79fc56898c) | Sep 03, 2021 |
| HP            | ProBook 4730s               | Notebook    | [36834479ab](https://linux-hardware.org/?probe=36834479ab) | Sep 03, 2021 |
| Pegatron      | Maureen                     | Desktop     | [8591d54048](https://linux-hardware.org/?probe=8591d54048) | Sep 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [be1de37337](https://linux-hardware.org/?probe=be1de37337) | Sep 03, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [96642dc49d](https://linux-hardware.org/?probe=96642dc49d) | Sep 02, 2021 |
| ASUSTek       | P7P55D LE                   | Desktop     | [8bbe7e58ae](https://linux-hardware.org/?probe=8bbe7e58ae) | Sep 02, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [77a32d2048](https://linux-hardware.org/?probe=77a32d2048) | Sep 02, 2021 |
| ASUSTek       | P7P55D LE                   | Desktop     | [21fd5c096a](https://linux-hardware.org/?probe=21fd5c096a) | Sep 02, 2021 |
| Acer          | Aspire 8730                 | Notebook    | [23961f8f02](https://linux-hardware.org/?probe=23961f8f02) | Sep 02, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8d28a5779f](https://linux-hardware.org/?probe=8d28a5779f) | Sep 02, 2021 |
| Acer          | Aspire 8730                 | Notebook    | [a0f96eb144](https://linux-hardware.org/?probe=a0f96eb144) | Sep 02, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d20dda51f0](https://linux-hardware.org/?probe=d20dda51f0) | Sep 02, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [54825c8496](https://linux-hardware.org/?probe=54825c8496) | Sep 02, 2021 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [bd648f717b](https://linux-hardware.org/?probe=bd648f717b) | Sep 02, 2021 |
| MSI           | TRX40 PRO WIFI              | Desktop     | [d337b01cb3](https://linux-hardware.org/?probe=d337b01cb3) | Sep 02, 2021 |
| Biostar       | H77MU3                      | Desktop     | [82f367ec4b](https://linux-hardware.org/?probe=82f367ec4b) | Sep 02, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [66df3754b3](https://linux-hardware.org/?probe=66df3754b3) | Sep 02, 2021 |
| Dell          | Inspiron One 2320           | All in one  | [911c78a85d](https://linux-hardware.org/?probe=911c78a85d) | Sep 02, 2021 |
| Acer          | Aspire V3-571               | Notebook    | [6998aee6d0](https://linux-hardware.org/?probe=6998aee6d0) | Sep 02, 2021 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [f8846969fd](https://linux-hardware.org/?probe=f8846969fd) | Sep 02, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [25258c3e09](https://linux-hardware.org/?probe=25258c3e09) | Sep 02, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [70fc801295](https://linux-hardware.org/?probe=70fc801295) | Sep 01, 2021 |
| Dell          | Latitude 5580               | Notebook    | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [48b4af3338](https://linux-hardware.org/?probe=48b4af3338) | Sep 01, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [5de0135b30](https://linux-hardware.org/?probe=5de0135b30) | Sep 01, 2021 |
| HP            | 18E9                        | Desktop     | [22f86af485](https://linux-hardware.org/?probe=22f86af485) | Sep 01, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [0a0d13044d](https://linux-hardware.org/?probe=0a0d13044d) | Sep 01, 2021 |
| HP            | 1998                        | Desktop     | [585ff46bb3](https://linux-hardware.org/?probe=585ff46bb3) | Sep 01, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [cde0de2a3d](https://linux-hardware.org/?probe=cde0de2a3d) | Sep 01, 2021 |
| FIRICH        | J1900                       | Desktop     | [a682347a14](https://linux-hardware.org/?probe=a682347a14) | Sep 01, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9ba35e9b27](https://linux-hardware.org/?probe=9ba35e9b27) | Sep 01, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ad1fdaa4c8](https://linux-hardware.org/?probe=ad1fdaa4c8) | Sep 01, 2021 |
| Lenovo        | ThinkPad X201 3626FBU       | Notebook    | [2a1b838727](https://linux-hardware.org/?probe=2a1b838727) | Sep 01, 2021 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [0f8fe06e8f](https://linux-hardware.org/?probe=0f8fe06e8f) | Aug 31, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [301e2787bd](https://linux-hardware.org/?probe=301e2787bd) | Aug 31, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [8c8a4d9cdf](https://linux-hardware.org/?probe=8c8a4d9cdf) | Aug 31, 2021 |
| ASUSTek       | UX550VE                     | Notebook    | [cd80e1ebb2](https://linux-hardware.org/?probe=cd80e1ebb2) | Aug 31, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [bb2bba4301](https://linux-hardware.org/?probe=bb2bba4301) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [8f1f4a2c99](https://linux-hardware.org/?probe=8f1f4a2c99) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [d33400a4fe](https://linux-hardware.org/?probe=d33400a4fe) | Aug 31, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [2c57f8fa2f](https://linux-hardware.org/?probe=2c57f8fa2f) | Aug 31, 2021 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [e689b2de7a](https://linux-hardware.org/?probe=e689b2de7a) | Aug 31, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [0413b7b1e4](https://linux-hardware.org/?probe=0413b7b1e4) | Aug 31, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [e289576136](https://linux-hardware.org/?probe=e289576136) | Aug 31, 2021 |
| ASUSTek       | GL752VW                     | Notebook    | [1476b07c9d](https://linux-hardware.org/?probe=1476b07c9d) | Aug 31, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [078613f010](https://linux-hardware.org/?probe=078613f010) | Aug 31, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b86e557def](https://linux-hardware.org/?probe=b86e557def) | Aug 31, 2021 |
| ASUSTek       | GL752VW                     | Notebook    | [625ac8c8bc](https://linux-hardware.org/?probe=625ac8c8bc) | Aug 31, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [02cd32fbb4](https://linux-hardware.org/?probe=02cd32fbb4) | Aug 30, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [b5459f613b](https://linux-hardware.org/?probe=b5459f613b) | Aug 30, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e829df72a5](https://linux-hardware.org/?probe=e829df72a5) | Aug 30, 2021 |
| Dell          | 0KFKMF A00                  | All in one  | [7c3c22add4](https://linux-hardware.org/?probe=7c3c22add4) | Aug 30, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [628f8d49c7](https://linux-hardware.org/?probe=628f8d49c7) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [9eb666fd13](https://linux-hardware.org/?probe=9eb666fd13) | Aug 30, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [882678793f](https://linux-hardware.org/?probe=882678793f) | Aug 30, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [1fcdd4041b](https://linux-hardware.org/?probe=1fcdd4041b) | Aug 30, 2021 |
| Dell          | Latitude E6520              | Notebook    | [03f5b8cb05](https://linux-hardware.org/?probe=03f5b8cb05) | Aug 30, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [846b2e2a87](https://linux-hardware.org/?probe=846b2e2a87) | Aug 30, 2021 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [780244d79f](https://linux-hardware.org/?probe=780244d79f) | Aug 30, 2021 |
| Fujitsu       | D3313-F1 S26361-D3313-F1    | Desktop     | [47c72f21ae](https://linux-hardware.org/?probe=47c72f21ae) | Aug 30, 2021 |
| HP            | Pavilion 17                 | Notebook    | [ca125d2f3c](https://linux-hardware.org/?probe=ca125d2f3c) | Aug 30, 2021 |
| ASUSTek       | P55VA                       | Notebook    | [12266fad85](https://linux-hardware.org/?probe=12266fad85) | Aug 30, 2021 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [f4e788dce6](https://linux-hardware.org/?probe=f4e788dce6) | Aug 30, 2021 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [8f5b776bcb](https://linux-hardware.org/?probe=8f5b776bcb) | Aug 30, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [4771af382d](https://linux-hardware.org/?probe=4771af382d) | Aug 30, 2021 |
| MSI           | P67A-C45                    | Desktop     | [5f5d217d7b](https://linux-hardware.org/?probe=5f5d217d7b) | Aug 30, 2021 |
| MSI           | P67A-C45                    | Desktop     | [8f1d2c8ca0](https://linux-hardware.org/?probe=8f1d2c8ca0) | Aug 30, 2021 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [a52209c9f2](https://linux-hardware.org/?probe=a52209c9f2) | Aug 30, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [1b602738e7](https://linux-hardware.org/?probe=1b602738e7) | Aug 30, 2021 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [2ca1595715](https://linux-hardware.org/?probe=2ca1595715) | Aug 30, 2021 |
| HP            | 84EF 01100                  | All in one  | [94918ce530](https://linux-hardware.org/?probe=94918ce530) | Aug 30, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [a2c8bb417d](https://linux-hardware.org/?probe=a2c8bb417d) | Aug 29, 2021 |
| Gigabyte      | H55-USB3                    | Desktop     | [ae6cbc8dd8](https://linux-hardware.org/?probe=ae6cbc8dd8) | Aug 29, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [05e455f345](https://linux-hardware.org/?probe=05e455f345) | Aug 29, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [eec643e4e2](https://linux-hardware.org/?probe=eec643e4e2) | Aug 29, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [d700bad32f](https://linux-hardware.org/?probe=d700bad32f) | Aug 29, 2021 |
| Acer          | AOD260                      | Notebook    | [de4ce44515](https://linux-hardware.org/?probe=de4ce44515) | Aug 29, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [8a976ca31c](https://linux-hardware.org/?probe=8a976ca31c) | Aug 29, 2021 |
| MSI           | MS-16Y1                     | Notebook    | [a9801b616e](https://linux-hardware.org/?probe=a9801b616e) | Aug 29, 2021 |
| HP            | 18E9                        | Desktop     | [539f181954](https://linux-hardware.org/?probe=539f181954) | Aug 29, 2021 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [4581bb2d5b](https://linux-hardware.org/?probe=4581bb2d5b) | Aug 29, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [171462cc36](https://linux-hardware.org/?probe=171462cc36) | Aug 29, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [e7a572f322](https://linux-hardware.org/?probe=e7a572f322) | Aug 29, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a089d56f43](https://linux-hardware.org/?probe=a089d56f43) | Aug 29, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [5a1fa64f5d](https://linux-hardware.org/?probe=5a1fa64f5d) | Aug 29, 2021 |
| Lenovo        | ThinkPad X201 3626FBU       | Notebook    | [7fe9be041a](https://linux-hardware.org/?probe=7fe9be041a) | Aug 29, 2021 |
| Acer          | Extensa 2509                | Notebook    | [a185b2f23f](https://linux-hardware.org/?probe=a185b2f23f) | Aug 29, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e06775bbd6](https://linux-hardware.org/?probe=e06775bbd6) | Aug 29, 2021 |
| HP            | 3397                        | Desktop     | [abf1615138](https://linux-hardware.org/?probe=abf1615138) | Aug 29, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [19a30277a2](https://linux-hardware.org/?probe=19a30277a2) | Aug 28, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [2672ce2fe7](https://linux-hardware.org/?probe=2672ce2fe7) | Aug 28, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [6bcc1e1e33](https://linux-hardware.org/?probe=6bcc1e1e33) | Aug 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [99b7f572be](https://linux-hardware.org/?probe=99b7f572be) | Aug 28, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [593479bed8](https://linux-hardware.org/?probe=593479bed8) | Aug 28, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [9e81caf509](https://linux-hardware.org/?probe=9e81caf509) | Aug 28, 2021 |
| Lenovo        | IdeaPad Gaming3 15ARH05D... | Notebook    | [757d521e89](https://linux-hardware.org/?probe=757d521e89) | Aug 28, 2021 |
| ASUSTek       | K52Jr                       | Notebook    | [7ec475cdd0](https://linux-hardware.org/?probe=7ec475cdd0) | Aug 28, 2021 |
| Monster       | ABRA A7 V7.3                | Notebook    | [17d5cd11fa](https://linux-hardware.org/?probe=17d5cd11fa) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [04c8ccfac4](https://linux-hardware.org/?probe=04c8ccfac4) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2ad8401f8f](https://linux-hardware.org/?probe=2ad8401f8f) | Aug 28, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [97ed1ed910](https://linux-hardware.org/?probe=97ed1ed910) | Aug 28, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3c7b22938d](https://linux-hardware.org/?probe=3c7b22938d) | Aug 27, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [e035ede092](https://linux-hardware.org/?probe=e035ede092) | Aug 27, 2021 |
| Pegatron      | IPMSB-GS                    | Desktop     | [b17f032a44](https://linux-hardware.org/?probe=b17f032a44) | Aug 27, 2021 |
| HP            | 2B34                        | Desktop     | [9477a88acd](https://linux-hardware.org/?probe=9477a88acd) | Aug 27, 2021 |
| Gigabyte      | P41T-USB3L                  | Desktop     | [e234ec66f2](https://linux-hardware.org/?probe=e234ec66f2) | Aug 27, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [a7bca9bc08](https://linux-hardware.org/?probe=a7bca9bc08) | Aug 27, 2021 |
| Pegatron      | IPMSB-GS                    | Desktop     | [9d2bbbabf1](https://linux-hardware.org/?probe=9d2bbbabf1) | Aug 27, 2021 |
| Google        | Careena                     | Notebook    | [c71e6267cb](https://linux-hardware.org/?probe=c71e6267cb) | Aug 27, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [03b37f86b2](https://linux-hardware.org/?probe=03b37f86b2) | Aug 27, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [fe97c44f4f](https://linux-hardware.org/?probe=fe97c44f4f) | Aug 27, 2021 |
| Shuttle       | FH61V                       | Desktop     | [11b6744d1c](https://linux-hardware.org/?probe=11b6744d1c) | Aug 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [50477e1758](https://linux-hardware.org/?probe=50477e1758) | Aug 27, 2021 |
| Acer          | AOD260                      | Notebook    | [d8cf89df4e](https://linux-hardware.org/?probe=d8cf89df4e) | Aug 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [d51c8093ec](https://linux-hardware.org/?probe=d51c8093ec) | Aug 27, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [c4ec7d7706](https://linux-hardware.org/?probe=c4ec7d7706) | Aug 27, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [7e1625f75d](https://linux-hardware.org/?probe=7e1625f75d) | Aug 27, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [03a89677c0](https://linux-hardware.org/?probe=03a89677c0) | Aug 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [d76439fc39](https://linux-hardware.org/?probe=d76439fc39) | Aug 26, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bbb2db43b4](https://linux-hardware.org/?probe=bbb2db43b4) | Aug 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [41dce1e5d4](https://linux-hardware.org/?probe=41dce1e5d4) | Aug 26, 2021 |
| Dell          | Inspiron 15-3573            | Notebook    | [9ca63b6d40](https://linux-hardware.org/?probe=9ca63b6d40) | Aug 26, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [c8198b5d21](https://linux-hardware.org/?probe=c8198b5d21) | Aug 26, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [1fc077ad52](https://linux-hardware.org/?probe=1fc077ad52) | Aug 26, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b3185cd80d](https://linux-hardware.org/?probe=b3185cd80d) | Aug 26, 2021 |
| Samsung       | 950QDB                      | Convertible | [c0dedecfe1](https://linux-hardware.org/?probe=c0dedecfe1) | Aug 26, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [1e65812b03](https://linux-hardware.org/?probe=1e65812b03) | Aug 26, 2021 |
| HP            | 1494                        | Desktop     | [29bc1c62ad](https://linux-hardware.org/?probe=29bc1c62ad) | Aug 26, 2021 |
| Samsung       | 950QDB                      | Convertible | [21ac7cda75](https://linux-hardware.org/?probe=21ac7cda75) | Aug 26, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [cfeb92ade1](https://linux-hardware.org/?probe=cfeb92ade1) | Aug 26, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [2f9e0312b5](https://linux-hardware.org/?probe=2f9e0312b5) | Aug 26, 2021 |
| ASUSTek       | S400CA                      | Notebook    | [d1c2760711](https://linux-hardware.org/?probe=d1c2760711) | Aug 26, 2021 |
| System76      | Oryx Pro                    | Notebook    | [ed8769ce16](https://linux-hardware.org/?probe=ed8769ce16) | Aug 26, 2021 |
| System76      | Oryx Pro                    | Notebook    | [a4ba687465](https://linux-hardware.org/?probe=a4ba687465) | Aug 26, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [badc363516](https://linux-hardware.org/?probe=badc363516) | Aug 26, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [24bfc2b04a](https://linux-hardware.org/?probe=24bfc2b04a) | Aug 26, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [8b7983c6f4](https://linux-hardware.org/?probe=8b7983c6f4) | Aug 26, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [60ba1a6cf7](https://linux-hardware.org/?probe=60ba1a6cf7) | Aug 25, 2021 |
| BANGHO        | MOV                         | Notebook    | [9bacff92e1](https://linux-hardware.org/?probe=9bacff92e1) | Aug 25, 2021 |
| ONDA          | V919 AIR CH                 | Tablet      | [239d17bc4a](https://linux-hardware.org/?probe=239d17bc4a) | Aug 25, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [19f99141b9](https://linux-hardware.org/?probe=19f99141b9) | Aug 25, 2021 |
| Lenovo        | ThinkPad T420s 4176W27      | Notebook    | [b84d5c31e3](https://linux-hardware.org/?probe=b84d5c31e3) | Aug 25, 2021 |
| Dell          | Inspiron 13-7359            | Notebook    | [0d1a190ded](https://linux-hardware.org/?probe=0d1a190ded) | Aug 25, 2021 |
| Dell          | Inspiron 13-7359            | Notebook    | [347f0ad714](https://linux-hardware.org/?probe=347f0ad714) | Aug 25, 2021 |
| HP            | 8768 A                      | Desktop     | [40e82f4d4f](https://linux-hardware.org/?probe=40e82f4d4f) | Aug 25, 2021 |
| Google        | Akemi                       | Notebook    | [11b458a90a](https://linux-hardware.org/?probe=11b458a90a) | Aug 25, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [e5251674c0](https://linux-hardware.org/?probe=e5251674c0) | Aug 25, 2021 |
| Google        | Akemi                       | Notebook    | [ebd0d7d1f9](https://linux-hardware.org/?probe=ebd0d7d1f9) | Aug 25, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [fb90bc01bc](https://linux-hardware.org/?probe=fb90bc01bc) | Aug 25, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [86c5a4a3dd](https://linux-hardware.org/?probe=86c5a4a3dd) | Aug 25, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [01b1cadf52](https://linux-hardware.org/?probe=01b1cadf52) | Aug 25, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [870deaf9fd](https://linux-hardware.org/?probe=870deaf9fd) | Aug 25, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [4b952eb1ae](https://linux-hardware.org/?probe=4b952eb1ae) | Aug 25, 2021 |
| Shuttle       | FH61V                       | Desktop     | [1b74c0ad1d](https://linux-hardware.org/?probe=1b74c0ad1d) | Aug 25, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [75869e33b7](https://linux-hardware.org/?probe=75869e33b7) | Aug 25, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [f75424e1e1](https://linux-hardware.org/?probe=f75424e1e1) | Aug 25, 2021 |
| Medion        | MS-7501                     | Desktop     | [c84fb9217e](https://linux-hardware.org/?probe=c84fb9217e) | Aug 25, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [2a6bfff91f](https://linux-hardware.org/?probe=2a6bfff91f) | Aug 24, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [2ef66334f0](https://linux-hardware.org/?probe=2ef66334f0) | Aug 24, 2021 |
| Apple         | Mac-F2218FC8                | All in one  | [f1df07c7a1](https://linux-hardware.org/?probe=f1df07c7a1) | Aug 24, 2021 |
| Lenovo        | B580 4377A9G                | Notebook    | [4a7f165a2f](https://linux-hardware.org/?probe=4a7f165a2f) | Aug 24, 2021 |
| Sony          | VGN-SZ4MN_B                 | Notebook    | [9b51d6eff6](https://linux-hardware.org/?probe=9b51d6eff6) | Aug 24, 2021 |
| HP            | 8054                        | Desktop     | [d54cd14c63](https://linux-hardware.org/?probe=d54cd14c63) | Aug 24, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [e9e6b8b426](https://linux-hardware.org/?probe=e9e6b8b426) | Aug 24, 2021 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [adb16307d7](https://linux-hardware.org/?probe=adb16307d7) | Aug 24, 2021 |
| ASRock        | Q77M vPro                   | Desktop     | [f53a9f288f](https://linux-hardware.org/?probe=f53a9f288f) | Aug 24, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [ea7f22c125](https://linux-hardware.org/?probe=ea7f22c125) | Aug 24, 2021 |
| CyberPower... | Tracer V                    | Notebook    | [d32f6e01af](https://linux-hardware.org/?probe=d32f6e01af) | Aug 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [8a59fff598](https://linux-hardware.org/?probe=8a59fff598) | Aug 24, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [c10c8ceffe](https://linux-hardware.org/?probe=c10c8ceffe) | Aug 23, 2021 |
| Dell          | Inspiron One 2320           | All in one  | [dfb665983b](https://linux-hardware.org/?probe=dfb665983b) | Aug 23, 2021 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [410b6b854f](https://linux-hardware.org/?probe=410b6b854f) | Aug 23, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [c5414322d8](https://linux-hardware.org/?probe=c5414322d8) | Aug 23, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [fa55eabafd](https://linux-hardware.org/?probe=fa55eabafd) | Aug 23, 2021 |
| HP            | Notebook                    | Notebook    | [5edda59c62](https://linux-hardware.org/?probe=5edda59c62) | Aug 23, 2021 |
| Samsung       | 750XDA                      | Notebook    | [a93fe624c9](https://linux-hardware.org/?probe=a93fe624c9) | Aug 23, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [bf921c6ff6](https://linux-hardware.org/?probe=bf921c6ff6) | Aug 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1971415007](https://linux-hardware.org/?probe=1971415007) | Aug 23, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a0805b7ffd](https://linux-hardware.org/?probe=a0805b7ffd) | Aug 23, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [946f2bf799](https://linux-hardware.org/?probe=946f2bf799) | Aug 22, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [6a52dc6e12](https://linux-hardware.org/?probe=6a52dc6e12) | Aug 22, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [6f5d61dc20](https://linux-hardware.org/?probe=6f5d61dc20) | Aug 22, 2021 |
| Toshiba       | Satellite C655D             | Notebook    | [63dfa0ffd8](https://linux-hardware.org/?probe=63dfa0ffd8) | Aug 22, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [99dbadcdde](https://linux-hardware.org/?probe=99dbadcdde) | Aug 22, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [89bfd52b3d](https://linux-hardware.org/?probe=89bfd52b3d) | Aug 22, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a82576e8e2](https://linux-hardware.org/?probe=a82576e8e2) | Aug 22, 2021 |
| HP            | Notebook                    | Notebook    | [5ac3618644](https://linux-hardware.org/?probe=5ac3618644) | Aug 22, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [521e8315c2](https://linux-hardware.org/?probe=521e8315c2) | Aug 22, 2021 |
| HP            | ProLiant ML350 G6           | Desktop     | [d89bfcf1f9](https://linux-hardware.org/?probe=d89bfcf1f9) | Aug 22, 2021 |
| HP            | 1494                        | Desktop     | [414b1c48e7](https://linux-hardware.org/?probe=414b1c48e7) | Aug 22, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1c910aa761](https://linux-hardware.org/?probe=1c910aa761) | Aug 22, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c1434ce76](https://linux-hardware.org/?probe=1c1434ce76) | Aug 21, 2021 |
| Dell          | Latitude E5400              | Notebook    | [0e1ba1167e](https://linux-hardware.org/?probe=0e1ba1167e) | Aug 21, 2021 |
| Dell          | Latitude E5400              | Notebook    | [10eee4ecd9](https://linux-hardware.org/?probe=10eee4ecd9) | Aug 21, 2021 |
| Acer          | EG43M                       | Desktop     | [3c17aecee4](https://linux-hardware.org/?probe=3c17aecee4) | Aug 21, 2021 |
| ASUSTek       | ZenBook UX434FQ             | Notebook    | [e5778c606b](https://linux-hardware.org/?probe=e5778c606b) | Aug 21, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [0db32c3e7e](https://linux-hardware.org/?probe=0db32c3e7e) | Aug 21, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [e9b8721812](https://linux-hardware.org/?probe=e9b8721812) | Aug 21, 2021 |
| Dell          | Inspiron 5491 2n1           | Convertible | [e85575b823](https://linux-hardware.org/?probe=e85575b823) | Aug 21, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [875e2fe9eb](https://linux-hardware.org/?probe=875e2fe9eb) | Aug 20, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [bad0ffd0e2](https://linux-hardware.org/?probe=bad0ffd0e2) | Aug 20, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [353385ccb8](https://linux-hardware.org/?probe=353385ccb8) | Aug 20, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [0c8cadf01b](https://linux-hardware.org/?probe=0c8cadf01b) | Aug 20, 2021 |
| Lenovo        | G560 0679                   | Notebook    | [a5d3d1f80c](https://linux-hardware.org/?probe=a5d3d1f80c) | Aug 20, 2021 |
| Lenovo        | G560 0679                   | Notebook    | [ce91db6192](https://linux-hardware.org/?probe=ce91db6192) | Aug 20, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [149d762d08](https://linux-hardware.org/?probe=149d762d08) | Aug 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f4ec2b8446](https://linux-hardware.org/?probe=f4ec2b8446) | Aug 20, 2021 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [d1800db637](https://linux-hardware.org/?probe=d1800db637) | Aug 20, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [e5f9d8b06f](https://linux-hardware.org/?probe=e5f9d8b06f) | Aug 20, 2021 |
| HP            | Stream 8 Tablet             | Tablet      | [379e9a74c2](https://linux-hardware.org/?probe=379e9a74c2) | Aug 20, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [a7ce746e66](https://linux-hardware.org/?probe=a7ce746e66) | Aug 20, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [8426ef6261](https://linux-hardware.org/?probe=8426ef6261) | Aug 20, 2021 |
| Gigabyte      | H87M-HD3                    | Desktop     | [bdc2409477](https://linux-hardware.org/?probe=bdc2409477) | Aug 20, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b8f5afa2f7](https://linux-hardware.org/?probe=b8f5afa2f7) | Aug 20, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [7e1f4b1620](https://linux-hardware.org/?probe=7e1f4b1620) | Aug 20, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [ed6b51261d](https://linux-hardware.org/?probe=ed6b51261d) | Aug 20, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [c4800a930a](https://linux-hardware.org/?probe=c4800a930a) | Aug 20, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [bffc40c965](https://linux-hardware.org/?probe=bffc40c965) | Aug 19, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [0223d6864b](https://linux-hardware.org/?probe=0223d6864b) | Aug 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [0c1d976c3c](https://linux-hardware.org/?probe=0c1d976c3c) | Aug 19, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [5c98a0115b](https://linux-hardware.org/?probe=5c98a0115b) | Aug 19, 2021 |
| Gigabyte      | P41T-USB3L                  | Desktop     | [e983759ddc](https://linux-hardware.org/?probe=e983759ddc) | Aug 19, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [b1a8b95c66](https://linux-hardware.org/?probe=b1a8b95c66) | Aug 19, 2021 |
| SLIMBOOK      | TITAN                       | Notebook    | [1eb70ec6e6](https://linux-hardware.org/?probe=1eb70ec6e6) | Aug 19, 2021 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [e26140d6a5](https://linux-hardware.org/?probe=e26140d6a5) | Aug 19, 2021 |
| Medion        | E2228T MD61450              | Convertible | [4ba158f6d9](https://linux-hardware.org/?probe=4ba158f6d9) | Aug 19, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [40aa5bc719](https://linux-hardware.org/?probe=40aa5bc719) | Aug 19, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [7cf3758630](https://linux-hardware.org/?probe=7cf3758630) | Aug 19, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [743442952d](https://linux-hardware.org/?probe=743442952d) | Aug 19, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [a4e0272377](https://linux-hardware.org/?probe=a4e0272377) | Aug 19, 2021 |
| Dell          | Vostro 3360                 | Notebook    | [03074a36b2](https://linux-hardware.org/?probe=03074a36b2) | Aug 19, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [74f533e1b3](https://linux-hardware.org/?probe=74f533e1b3) | Aug 19, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [5b2b23ac97](https://linux-hardware.org/?probe=5b2b23ac97) | Aug 19, 2021 |
| HP            | 450                         | Notebook    | [9f5d03c478](https://linux-hardware.org/?probe=9f5d03c478) | Aug 19, 2021 |
| ASUSTek       | G55VW                       | Notebook    | [7daa09d3c3](https://linux-hardware.org/?probe=7daa09d3c3) | Aug 19, 2021 |
| Samsung       | 520U4C/520U4X               | Notebook    | [1863ae7d28](https://linux-hardware.org/?probe=1863ae7d28) | Aug 19, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [4c1a100ab1](https://linux-hardware.org/?probe=4c1a100ab1) | Aug 19, 2021 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [810f986c77](https://linux-hardware.org/?probe=810f986c77) | Aug 19, 2021 |
| ASUSTek       | K54C                        | Notebook    | [816e5c7efa](https://linux-hardware.org/?probe=816e5c7efa) | Aug 19, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [a20cebc67a](https://linux-hardware.org/?probe=a20cebc67a) | Aug 18, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [ad6c9051e0](https://linux-hardware.org/?probe=ad6c9051e0) | Aug 18, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [8e26bae3fc](https://linux-hardware.org/?probe=8e26bae3fc) | Aug 18, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [ea3fc1154c](https://linux-hardware.org/?probe=ea3fc1154c) | Aug 18, 2021 |
| ASUSTek       | P8P67                       | Desktop     | [9bed63f2f6](https://linux-hardware.org/?probe=9bed63f2f6) | Aug 18, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e1467bfa3e](https://linux-hardware.org/?probe=e1467bfa3e) | Aug 18, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [d9923e15e0](https://linux-hardware.org/?probe=d9923e15e0) | Aug 18, 2021 |
| ASUSTek       | P8P67                       | Desktop     | [8885a008e0](https://linux-hardware.org/?probe=8885a008e0) | Aug 18, 2021 |
| Toshiba       | Satellite Z930              | Notebook    | [3138585fd8](https://linux-hardware.org/?probe=3138585fd8) | Aug 18, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [996054b23c](https://linux-hardware.org/?probe=996054b23c) | Aug 18, 2021 |
| Toshiba       | PORTEGE Z930                | Notebook    | [a49ad7f306](https://linux-hardware.org/?probe=a49ad7f306) | Aug 18, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [38ce4c1114](https://linux-hardware.org/?probe=38ce4c1114) | Aug 18, 2021 |
| Toshiba       | Satellite Z930              | Notebook    | [dfb39f616a](https://linux-hardware.org/?probe=dfb39f616a) | Aug 18, 2021 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [8596bc4b0e](https://linux-hardware.org/?probe=8596bc4b0e) | Aug 18, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [251af23ff3](https://linux-hardware.org/?probe=251af23ff3) | Aug 18, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [eb1e9924f7](https://linux-hardware.org/?probe=eb1e9924f7) | Aug 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [035488628d](https://linux-hardware.org/?probe=035488628d) | Aug 17, 2021 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [3e3018cc57](https://linux-hardware.org/?probe=3e3018cc57) | Aug 17, 2021 |
| ASUSTek       | K52Je                       | Notebook    | [d35de28c56](https://linux-hardware.org/?probe=d35de28c56) | Aug 17, 2021 |
| HP            | ENVY 17                     | Notebook    | [339f78f408](https://linux-hardware.org/?probe=339f78f408) | Aug 17, 2021 |
| Acer          | Nitro AN515-57              | Notebook    | [3c18d3a700](https://linux-hardware.org/?probe=3c18d3a700) | Aug 17, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [bf692b9804](https://linux-hardware.org/?probe=bf692b9804) | Aug 17, 2021 |
| Lenovo        | ThinkPad W541 20EF0020GE    | Notebook    | [ea3fc647ce](https://linux-hardware.org/?probe=ea3fc647ce) | Aug 17, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [00bff94489](https://linux-hardware.org/?probe=00bff94489) | Aug 17, 2021 |
| HP            | 1494                        | Desktop     | [df10192c5b](https://linux-hardware.org/?probe=df10192c5b) | Aug 16, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [d238322295](https://linux-hardware.org/?probe=d238322295) | Aug 16, 2021 |
| ASUSTek       | B150M-C                     | Desktop     | [794387ddd6](https://linux-hardware.org/?probe=794387ddd6) | Aug 16, 2021 |
| Medion        | MS-7707                     | Desktop     | [66ace31297](https://linux-hardware.org/?probe=66ace31297) | Aug 16, 2021 |
| Medion        | P6640                       | Notebook    | [e83d5a51ac](https://linux-hardware.org/?probe=e83d5a51ac) | Aug 16, 2021 |
| Acer          | Aspire 5733                 | Notebook    | [7d63c49cee](https://linux-hardware.org/?probe=7d63c49cee) | Aug 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [65ebd0006e](https://linux-hardware.org/?probe=65ebd0006e) | Aug 16, 2021 |
| Dell          | 082WXT A01                  | Desktop     | [e6b9ac8959](https://linux-hardware.org/?probe=e6b9ac8959) | Aug 16, 2021 |
| Notebook      | W94_95_97JU                 | Notebook    | [816ddae34c](https://linux-hardware.org/?probe=816ddae34c) | Aug 16, 2021 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [537aee667d](https://linux-hardware.org/?probe=537aee667d) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [213934c1e0](https://linux-hardware.org/?probe=213934c1e0) | Aug 16, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7f633b5d5b](https://linux-hardware.org/?probe=7f633b5d5b) | Aug 16, 2021 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [100ee97108](https://linux-hardware.org/?probe=100ee97108) | Aug 16, 2021 |
| ASUSTek       | Basswood                    | Desktop     | [f42051fa02](https://linux-hardware.org/?probe=f42051fa02) | Aug 15, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| HP            | 2B3E                        | All in one  | [d2de88ef3c](https://linux-hardware.org/?probe=d2de88ef3c) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8e47965ba8](https://linux-hardware.org/?probe=8e47965ba8) | Aug 15, 2021 |
| Gigabyte      | X99-SLI-CF                  | Desktop     | [27f528f809](https://linux-hardware.org/?probe=27f528f809) | Aug 15, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [7c1b975d25](https://linux-hardware.org/?probe=7c1b975d25) | Aug 15, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [696380b374](https://linux-hardware.org/?probe=696380b374) | Aug 15, 2021 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [66ff9d7471](https://linux-hardware.org/?probe=66ff9d7471) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [f406892aa9](https://linux-hardware.org/?probe=f406892aa9) | Aug 15, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [5076334ae6](https://linux-hardware.org/?probe=5076334ae6) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b333da4703](https://linux-hardware.org/?probe=b333da4703) | Aug 14, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [3a83d976d0](https://linux-hardware.org/?probe=3a83d976d0) | Aug 14, 2021 |
| ECS           | H61H2-TI                    | All in one  | [dd57d8772a](https://linux-hardware.org/?probe=dd57d8772a) | Aug 14, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [7df7534dd9](https://linux-hardware.org/?probe=7df7534dd9) | Aug 14, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [676c2b2a79](https://linux-hardware.org/?probe=676c2b2a79) | Aug 14, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [977c948bad](https://linux-hardware.org/?probe=977c948bad) | Aug 14, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [e359985b75](https://linux-hardware.org/?probe=e359985b75) | Aug 14, 2021 |
| ASRock        | H97M Pro4                   | Desktop     | [5edf7e02c8](https://linux-hardware.org/?probe=5edf7e02c8) | Aug 14, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [d03439a8d0](https://linux-hardware.org/?probe=d03439a8d0) | Aug 14, 2021 |
| Lenovo        | 3729 SDK0J40700 WIN 3258... | All in one  | [19272ae8a6](https://linux-hardware.org/?probe=19272ae8a6) | Aug 14, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [aa85094441](https://linux-hardware.org/?probe=aa85094441) | Aug 14, 2021 |
| Medion        | E2213 MD60193               | Notebook    | [5bb52d1b1b](https://linux-hardware.org/?probe=5bb52d1b1b) | Aug 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1aa131a4fc](https://linux-hardware.org/?probe=1aa131a4fc) | Aug 13, 2021 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [e2d8270403](https://linux-hardware.org/?probe=e2d8270403) | Aug 13, 2021 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [e9e0bafaee](https://linux-hardware.org/?probe=e9e0bafaee) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [6346388737](https://linux-hardware.org/?probe=6346388737) | Aug 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [11f9ccb3ad](https://linux-hardware.org/?probe=11f9ccb3ad) | Aug 13, 2021 |
| Radxa         | ROCK Pi X v1.4              | Notebook    | [d5c46e7235](https://linux-hardware.org/?probe=d5c46e7235) | Aug 13, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [fec985ca69](https://linux-hardware.org/?probe=fec985ca69) | Aug 13, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [a96e5e7fff](https://linux-hardware.org/?probe=a96e5e7fff) | Aug 13, 2021 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [1174eec6c2](https://linux-hardware.org/?probe=1174eec6c2) | Aug 13, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d5ea181465](https://linux-hardware.org/?probe=d5ea181465) | Aug 13, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1742e1c6a9](https://linux-hardware.org/?probe=1742e1c6a9) | Aug 13, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [8bb8411127](https://linux-hardware.org/?probe=8bb8411127) | Aug 13, 2021 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [d0db0c37b0](https://linux-hardware.org/?probe=d0db0c37b0) | Aug 12, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [be84ceed7a](https://linux-hardware.org/?probe=be84ceed7a) | Aug 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [de1de1fa76](https://linux-hardware.org/?probe=de1de1fa76) | Aug 12, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [adde6ef882](https://linux-hardware.org/?probe=adde6ef882) | Aug 12, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [02f3303081](https://linux-hardware.org/?probe=02f3303081) | Aug 12, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [d6668ff825](https://linux-hardware.org/?probe=d6668ff825) | Aug 12, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [fbeb3986b3](https://linux-hardware.org/?probe=fbeb3986b3) | Aug 12, 2021 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [6d351fec42](https://linux-hardware.org/?probe=6d351fec42) | Aug 12, 2021 |
| Dell          | G5 5587                     | Notebook    | [204e0318ab](https://linux-hardware.org/?probe=204e0318ab) | Aug 12, 2021 |
| Razer         | Blade                       | Notebook    | [d04a50103d](https://linux-hardware.org/?probe=d04a50103d) | Aug 11, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [1f6745d6bb](https://linux-hardware.org/?probe=1f6745d6bb) | Aug 11, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | Notebook    | [d24254d911](https://linux-hardware.org/?probe=d24254d911) | Aug 11, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [9b490356cb](https://linux-hardware.org/?probe=9b490356cb) | Aug 11, 2021 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [5f87a353c8](https://linux-hardware.org/?probe=5f87a353c8) | Aug 11, 2021 |
| Dell          | Latitude 5400               | Notebook    | [4f804f2046](https://linux-hardware.org/?probe=4f804f2046) | Aug 11, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [19412614ef](https://linux-hardware.org/?probe=19412614ef) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [90ae378555](https://linux-hardware.org/?probe=90ae378555) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [268452e2ee](https://linux-hardware.org/?probe=268452e2ee) | Aug 11, 2021 |
| ASUSTek       | TP300LA                     | Notebook    | [f5dca95f99](https://linux-hardware.org/?probe=f5dca95f99) | Aug 11, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ab15fa7759](https://linux-hardware.org/?probe=ab15fa7759) | Aug 11, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [91ed6ecc84](https://linux-hardware.org/?probe=91ed6ecc84) | Aug 10, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [4b8bdfd1eb](https://linux-hardware.org/?probe=4b8bdfd1eb) | Aug 10, 2021 |
| ECS           | Asterope3                   | Desktop     | [9255f2e941](https://linux-hardware.org/?probe=9255f2e941) | Aug 10, 2021 |
| Dell          | Latitude E6330              | Notebook    | [cc6a9823e1](https://linux-hardware.org/?probe=cc6a9823e1) | Aug 10, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [2af094f75d](https://linux-hardware.org/?probe=2af094f75d) | Aug 10, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [eb1b7627ff](https://linux-hardware.org/?probe=eb1b7627ff) | Aug 10, 2021 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [8beee2f359](https://linux-hardware.org/?probe=8beee2f359) | Aug 10, 2021 |
| ASUSTek       | D642MF                      | Desktop     | [e50f269bc9](https://linux-hardware.org/?probe=e50f269bc9) | Aug 10, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [d01d6a6ab0](https://linux-hardware.org/?probe=d01d6a6ab0) | Aug 10, 2021 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [d2e35c6ccb](https://linux-hardware.org/?probe=d2e35c6ccb) | Aug 10, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [8b463c7abb](https://linux-hardware.org/?probe=8b463c7abb) | Aug 10, 2021 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [88dcb8813a](https://linux-hardware.org/?probe=88dcb8813a) | Aug 10, 2021 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [07fad2e81c](https://linux-hardware.org/?probe=07fad2e81c) | Aug 10, 2021 |
| Dell          | Latitude E5400              | Notebook    | [c54ea52d26](https://linux-hardware.org/?probe=c54ea52d26) | Aug 09, 2021 |
| HP            | 87D6 SMVB                   | Desktop     | [7e4cda26e2](https://linux-hardware.org/?probe=7e4cda26e2) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450 20BUS0G91F    | Notebook    | [8db659cf12](https://linux-hardware.org/?probe=8db659cf12) | Aug 09, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [33a532dde2](https://linux-hardware.org/?probe=33a532dde2) | Aug 09, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [8e62a52f33](https://linux-hardware.org/?probe=8e62a52f33) | Aug 09, 2021 |
| LG Electro... | 17Z90P-G.AD88B              | Notebook    | [d18eda768e](https://linux-hardware.org/?probe=d18eda768e) | Aug 09, 2021 |
| ASUSTek       | N552VW                      | Notebook    | [9cc9b3d62e](https://linux-hardware.org/?probe=9cc9b3d62e) | Aug 09, 2021 |
| Monster       | TULPAR T7 V20.4             | Notebook    | [f94dfc2fc6](https://linux-hardware.org/?probe=f94dfc2fc6) | Aug 09, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [a2c47444e8](https://linux-hardware.org/?probe=a2c47444e8) | Aug 09, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [aaf4f26a30](https://linux-hardware.org/?probe=aaf4f26a30) | Aug 09, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [22fa8558fa](https://linux-hardware.org/?probe=22fa8558fa) | Aug 09, 2021 |
| Dell          | Precision M6600             | Notebook    | [58b77bf05d](https://linux-hardware.org/?probe=58b77bf05d) | Aug 09, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c42793eeff](https://linux-hardware.org/?probe=c42793eeff) | Aug 08, 2021 |
| HP            | 212B                        | Desktop     | [ee483c7463](https://linux-hardware.org/?probe=ee483c7463) | Aug 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e88a377feb](https://linux-hardware.org/?probe=e88a377feb) | Aug 08, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [59783ba71d](https://linux-hardware.org/?probe=59783ba71d) | Aug 08, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [093f956e28](https://linux-hardware.org/?probe=093f956e28) | Aug 08, 2021 |
| AOpen         | D1009 A1A4                  | Desktop     | [a1ad011d2c](https://linux-hardware.org/?probe=a1ad011d2c) | Aug 08, 2021 |
| Foxconn       | 2A8C                        | Desktop     | [7123b6c779](https://linux-hardware.org/?probe=7123b6c779) | Aug 08, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [b4fe0907aa](https://linux-hardware.org/?probe=b4fe0907aa) | Aug 08, 2021 |
| ASUSTek       | PN51-E1                     | Mini pc     | [ce3a7ea50e](https://linux-hardware.org/?probe=ce3a7ea50e) | Aug 08, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [756d4b46ad](https://linux-hardware.org/?probe=756d4b46ad) | Aug 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [45d400c67b](https://linux-hardware.org/?probe=45d400c67b) | Aug 08, 2021 |
| HP            | 1998                        | Desktop     | [b0e8ef9aa2](https://linux-hardware.org/?probe=b0e8ef9aa2) | Aug 08, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [f36ecee8d1](https://linux-hardware.org/?probe=f36ecee8d1) | Aug 07, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [8c36ac6a56](https://linux-hardware.org/?probe=8c36ac6a56) | Aug 07, 2021 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [293b45eded](https://linux-hardware.org/?probe=293b45eded) | Aug 07, 2021 |
| MSI           | Z97 GAMING 9 AC             | Desktop     | [17ce8c5436](https://linux-hardware.org/?probe=17ce8c5436) | Aug 07, 2021 |
| Panasonic     | CF-19KDR78CE                | Notebook    | [29eee33555](https://linux-hardware.org/?probe=29eee33555) | Aug 07, 2021 |
| ASUSTek       | E402SA                      | Notebook    | [790033a704](https://linux-hardware.org/?probe=790033a704) | Aug 07, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [ffe68561cd](https://linux-hardware.org/?probe=ffe68561cd) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b3dfe4bfe4](https://linux-hardware.org/?probe=b3dfe4bfe4) | Aug 07, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [fd15e7b399](https://linux-hardware.org/?probe=fd15e7b399) | Aug 07, 2021 |
| Medion        | P6640                       | Notebook    | [ee12482cc7](https://linux-hardware.org/?probe=ee12482cc7) | Aug 07, 2021 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [3d2bc47483](https://linux-hardware.org/?probe=3d2bc47483) | Aug 07, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [32192f4588](https://linux-hardware.org/?probe=32192f4588) | Aug 07, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [0dd35a18fe](https://linux-hardware.org/?probe=0dd35a18fe) | Aug 07, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [9ffd679117](https://linux-hardware.org/?probe=9ffd679117) | Aug 07, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [e9e8cca53d](https://linux-hardware.org/?probe=e9e8cca53d) | Aug 07, 2021 |
| ASUSTek       | X550CA                      | Notebook    | [a1e7efd7c1](https://linux-hardware.org/?probe=a1e7efd7c1) | Aug 07, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [21e4e5c57d](https://linux-hardware.org/?probe=21e4e5c57d) | Aug 07, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [a053325efe](https://linux-hardware.org/?probe=a053325efe) | Aug 06, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [78bd17f4c4](https://linux-hardware.org/?probe=78bd17f4c4) | Aug 06, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [09fa4c99dc](https://linux-hardware.org/?probe=09fa4c99dc) | Aug 06, 2021 |
| HP            | ProBook 4540s               | Notebook    | [52b0186956](https://linux-hardware.org/?probe=52b0186956) | Aug 06, 2021 |
| eMachines     | E627                        | Notebook    | [b83fe7564f](https://linux-hardware.org/?probe=b83fe7564f) | Aug 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [0a387b2df0](https://linux-hardware.org/?probe=0a387b2df0) | Aug 06, 2021 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [2415e3e33f](https://linux-hardware.org/?probe=2415e3e33f) | Aug 06, 2021 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [da4fd46a9b](https://linux-hardware.org/?probe=da4fd46a9b) | Aug 06, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [6af058344f](https://linux-hardware.org/?probe=6af058344f) | Aug 06, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [975daf858c](https://linux-hardware.org/?probe=975daf858c) | Aug 06, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [c149c02018](https://linux-hardware.org/?probe=c149c02018) | Aug 06, 2021 |
| Acer          | Aspire ES1-511              | Notebook    | [d8963041b5](https://linux-hardware.org/?probe=d8963041b5) | Aug 06, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [4d0bb591af](https://linux-hardware.org/?probe=4d0bb591af) | Aug 06, 2021 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [7306d11e16](https://linux-hardware.org/?probe=7306d11e16) | Aug 06, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [e0b87e63a3](https://linux-hardware.org/?probe=e0b87e63a3) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [47fca1c82c](https://linux-hardware.org/?probe=47fca1c82c) | Aug 05, 2021 |
| HKC           | Y11CC                       | Notebook    | [a8e149ef22](https://linux-hardware.org/?probe=a8e149ef22) | Aug 05, 2021 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [3118d29bf0](https://linux-hardware.org/?probe=3118d29bf0) | Aug 05, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3e56e95f2f](https://linux-hardware.org/?probe=3e56e95f2f) | Aug 05, 2021 |
| Unknown       | Unknown                     | Notebook    | [d4db86e4ac](https://linux-hardware.org/?probe=d4db86e4ac) | Aug 05, 2021 |
| Unknown       | Unknown                     | Notebook    | [bcb72c9247](https://linux-hardware.org/?probe=bcb72c9247) | Aug 05, 2021 |
| Dell          | Latitude 7380               | Notebook    | [c83f32076d](https://linux-hardware.org/?probe=c83f32076d) | Aug 05, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [fc6a3dd16d](https://linux-hardware.org/?probe=fc6a3dd16d) | Aug 05, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [641c9a47eb](https://linux-hardware.org/?probe=641c9a47eb) | Aug 05, 2021 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [ef7f570d01](https://linux-hardware.org/?probe=ef7f570d01) | Aug 04, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a2a1574d81](https://linux-hardware.org/?probe=a2a1574d81) | Aug 04, 2021 |
| Acer          | Switch SW312-31             | Tablet      | [df56ae8dda](https://linux-hardware.org/?probe=df56ae8dda) | Aug 04, 2021 |
| MSI           | 2A9C                        | Desktop     | [3616ca63df](https://linux-hardware.org/?probe=3616ca63df) | Aug 04, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [e0bb448b0d](https://linux-hardware.org/?probe=e0bb448b0d) | Aug 04, 2021 |
| Biostar       | A68MHE                      | Desktop     | [160e00a244](https://linux-hardware.org/?probe=160e00a244) | Aug 04, 2021 |
| IP3 Tech      | X30                         | Notebook    | [700e39c30d](https://linux-hardware.org/?probe=700e39c30d) | Aug 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [a7feba2af0](https://linux-hardware.org/?probe=a7feba2af0) | Aug 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [eaa9723b34](https://linux-hardware.org/?probe=eaa9723b34) | Aug 03, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [fc2c2761bc](https://linux-hardware.org/?probe=fc2c2761bc) | Aug 03, 2021 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [e679a451ab](https://linux-hardware.org/?probe=e679a451ab) | Aug 03, 2021 |
| ASUSTek       | X542UQ                      | Notebook    | [63d2276d55](https://linux-hardware.org/?probe=63d2276d55) | Aug 03, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [32e0ae8af0](https://linux-hardware.org/?probe=32e0ae8af0) | Aug 03, 2021 |
| ASUSTek       | K73BY                       | Notebook    | [37b4b1362f](https://linux-hardware.org/?probe=37b4b1362f) | Aug 03, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3980... | Notebook    | [32507fdf80](https://linux-hardware.org/?probe=32507fdf80) | Aug 03, 2021 |
| Dell          | G3 3500                     | Notebook    | [3480d1f83d](https://linux-hardware.org/?probe=3480d1f83d) | Aug 03, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [282ecb40ca](https://linux-hardware.org/?probe=282ecb40ca) | Aug 03, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [ce156e88b0](https://linux-hardware.org/?probe=ce156e88b0) | Aug 03, 2021 |
| HP            | ENVY m6                     | Notebook    | [6d72ad672c](https://linux-hardware.org/?probe=6d72ad672c) | Aug 03, 2021 |
| ASUSTek       | M3N78 PRO                   | Desktop     | [dda6e493b7](https://linux-hardware.org/?probe=dda6e493b7) | Aug 03, 2021 |
| Lenovo        | ThinkPad T440p 20AW0002I... | Notebook    | [7f53bdba21](https://linux-hardware.org/?probe=7f53bdba21) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [d976766cee](https://linux-hardware.org/?probe=d976766cee) | Aug 03, 2021 |
| Dell          | Inspiron 5301               | Notebook    | [2387a6a66c](https://linux-hardware.org/?probe=2387a6a66c) | Aug 03, 2021 |
| HP            | ProBook 4540s               | Notebook    | [42b95781f5](https://linux-hardware.org/?probe=42b95781f5) | Aug 03, 2021 |
| Dell          | Inspiron 7590 2n1           | Convertible | [90e00a5174](https://linux-hardware.org/?probe=90e00a5174) | Aug 02, 2021 |
| Acer          | Swift SF314-54G             | Notebook    | [04a33a7d5c](https://linux-hardware.org/?probe=04a33a7d5c) | Aug 02, 2021 |
| Foxconn       | 2A8C                        | Desktop     | [67e965bb06](https://linux-hardware.org/?probe=67e965bb06) | Aug 02, 2021 |
| HP            | ZBook 15u G4                | Notebook    | [d77bb6209a](https://linux-hardware.org/?probe=d77bb6209a) | Aug 02, 2021 |
| ASUSTek       | K73BY                       | Notebook    | [8fb5845dd4](https://linux-hardware.org/?probe=8fb5845dd4) | Aug 02, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [5ac36e570a](https://linux-hardware.org/?probe=5ac36e570a) | Aug 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [7b564a6ba6](https://linux-hardware.org/?probe=7b564a6ba6) | Aug 02, 2021 |
| MSI           | G31M3-F V2                  | Desktop     | [8f821ac3a7](https://linux-hardware.org/?probe=8f821ac3a7) | Aug 02, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [cb617ee0fa](https://linux-hardware.org/?probe=cb617ee0fa) | Aug 02, 2021 |
| Lenovo        | 3729 SDK0J40700 WIN 3258... | All in one  | [238be84c8e](https://linux-hardware.org/?probe=238be84c8e) | Aug 02, 2021 |
| HP            | 250 G4                      | Notebook    | [bd80a8cdf0](https://linux-hardware.org/?probe=bd80a8cdf0) | Aug 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [e9e0269b1a](https://linux-hardware.org/?probe=e9e0269b1a) | Aug 01, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [5144862148](https://linux-hardware.org/?probe=5144862148) | Aug 01, 2021 |
| HP            | Pavilion dm1                | Notebook    | [ac0e534d86](https://linux-hardware.org/?probe=ac0e534d86) | Aug 01, 2021 |
| Advance       | AN-5431                     | Notebook    | [06409d8637](https://linux-hardware.org/?probe=06409d8637) | Aug 01, 2021 |
| HP            | Presario CQ61               | Notebook    | [3496f82684](https://linux-hardware.org/?probe=3496f82684) | Aug 01, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [fb4efe3736](https://linux-hardware.org/?probe=fb4efe3736) | Aug 01, 2021 |
| ASUSTek       | P7Q57-M DO                  | Desktop     | [e14cd31bf6](https://linux-hardware.org/?probe=e14cd31bf6) | Aug 01, 2021 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [39b2e07348](https://linux-hardware.org/?probe=39b2e07348) | Aug 01, 2021 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [22790f2a7e](https://linux-hardware.org/?probe=22790f2a7e) | Aug 01, 2021 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [aaece9a4d4](https://linux-hardware.org/?probe=aaece9a4d4) | Aug 01, 2021 |
| Alienware     | M17xR4                      | Notebook    | [940c3efccf](https://linux-hardware.org/?probe=940c3efccf) | Aug 01, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [ec65d6706f](https://linux-hardware.org/?probe=ec65d6706f) | Aug 01, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [91cc6c6711](https://linux-hardware.org/?probe=91cc6c6711) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [2c67644e4c](https://linux-hardware.org/?probe=2c67644e4c) | Aug 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [69c078f12b](https://linux-hardware.org/?probe=69c078f12b) | Aug 01, 2021 |
| MSI           | MS-16GF                     | Notebook    | [ba0b532d35](https://linux-hardware.org/?probe=ba0b532d35) | Aug 01, 2021 |
| Google        | Stout                       | Notebook    | [dcc159aacb](https://linux-hardware.org/?probe=dcc159aacb) | Aug 01, 2021 |
| Dell          | Latitude E5520              | Notebook    | [495c7ad655](https://linux-hardware.org/?probe=495c7ad655) | Jul 31, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [e2db581d0b](https://linux-hardware.org/?probe=e2db581d0b) | Jul 31, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [b893ad294a](https://linux-hardware.org/?probe=b893ad294a) | Jul 31, 2021 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [977edacab3](https://linux-hardware.org/?probe=977edacab3) | Jul 31, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3b4a485e30](https://linux-hardware.org/?probe=3b4a485e30) | Jul 31, 2021 |
| Dell          | Vostro 14-5459              | Notebook    | [1a120753db](https://linux-hardware.org/?probe=1a120753db) | Jul 31, 2021 |
| HP            | Pavilion g6                 | Notebook    | [147539a271](https://linux-hardware.org/?probe=147539a271) | Jul 31, 2021 |
| Dell          | Vostro 14-5459              | Notebook    | [affecdcdb7](https://linux-hardware.org/?probe=affecdcdb7) | Jul 31, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6b8e73456f](https://linux-hardware.org/?probe=6b8e73456f) | Jul 31, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [64e8f0e803](https://linux-hardware.org/?probe=64e8f0e803) | Jul 31, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [abb1e8ea82](https://linux-hardware.org/?probe=abb1e8ea82) | Jul 31, 2021 |
| Gigabyte      | G41M-ES2H                   | Desktop     | [ba0824b1c9](https://linux-hardware.org/?probe=ba0824b1c9) | Jul 30, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fda988dc8a](https://linux-hardware.org/?probe=fda988dc8a) | Jul 30, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7e7791cf42](https://linux-hardware.org/?probe=7e7791cf42) | Jul 30, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9ad32a6e81](https://linux-hardware.org/?probe=9ad32a6e81) | Jul 30, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [75228088e0](https://linux-hardware.org/?probe=75228088e0) | Jul 30, 2021 |
| Dell          | Inspiron 5720               | Notebook    | [08e504b4d9](https://linux-hardware.org/?probe=08e504b4d9) | Jul 30, 2021 |
| ASRock        | H470M-HVS                   | Desktop     | [97dbb1b8b9](https://linux-hardware.org/?probe=97dbb1b8b9) | Jul 30, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4a27442871](https://linux-hardware.org/?probe=4a27442871) | Jul 30, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [23399ffe42](https://linux-hardware.org/?probe=23399ffe42) | Jul 30, 2021 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [d3e4773f47](https://linux-hardware.org/?probe=d3e4773f47) | Jul 30, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [d7a0f68d0d](https://linux-hardware.org/?probe=d7a0f68d0d) | Jul 30, 2021 |
| ASRock        | Z170 OC Formula             | Desktop     | [0d1ca849b8](https://linux-hardware.org/?probe=0d1ca849b8) | Jul 29, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [64b0d25c3a](https://linux-hardware.org/?probe=64b0d25c3a) | Jul 29, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5c8b0fb32b](https://linux-hardware.org/?probe=5c8b0fb32b) | Jul 29, 2021 |
| Sony          | SVF1521H2EW                 | Notebook    | [025ae9003b](https://linux-hardware.org/?probe=025ae9003b) | Jul 29, 2021 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [ceac6ce540](https://linux-hardware.org/?probe=ceac6ce540) | Jul 29, 2021 |
| MSI           | H510M PRO                   | Desktop     | [6b204e25a9](https://linux-hardware.org/?probe=6b204e25a9) | Jul 29, 2021 |
| Dell          | 0JGM7F A00                  | Desktop     | [8eba192a2d](https://linux-hardware.org/?probe=8eba192a2d) | Jul 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [5cacc2c659](https://linux-hardware.org/?probe=5cacc2c659) | Jul 29, 2021 |
| Dell          | 0JGM7F A00                  | Desktop     | [d2cd2288c7](https://linux-hardware.org/?probe=d2cd2288c7) | Jul 29, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [e896a37f1d](https://linux-hardware.org/?probe=e896a37f1d) | Jul 29, 2021 |
| Toshiba       | TECRA Z40-B                 | Notebook    | [d353412a4f](https://linux-hardware.org/?probe=d353412a4f) | Jul 29, 2021 |
| MSI           | G31TM-P21                   | Desktop     | [024df6a0c1](https://linux-hardware.org/?probe=024df6a0c1) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [85f066488a](https://linux-hardware.org/?probe=85f066488a) | Jul 29, 2021 |
| Sony          | VPCEJ1L1E                   | Notebook    | [03e1c179a3](https://linux-hardware.org/?probe=03e1c179a3) | Jul 29, 2021 |
| Samsung       | 935XDB                      | Notebook    | [ebc69d8a77](https://linux-hardware.org/?probe=ebc69d8a77) | Jul 29, 2021 |
| Gigabyte      | G41M-ES2H                   | Desktop     | [04b060a090](https://linux-hardware.org/?probe=04b060a090) | Jul 29, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [55f86a29a2](https://linux-hardware.org/?probe=55f86a29a2) | Jul 29, 2021 |
| Sony          | VPCEJ1L1E                   | Notebook    | [a43c899910](https://linux-hardware.org/?probe=a43c899910) | Jul 29, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [41c1c2551d](https://linux-hardware.org/?probe=41c1c2551d) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [fd1285b7f2](https://linux-hardware.org/?probe=fd1285b7f2) | Jul 29, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [8242b46551](https://linux-hardware.org/?probe=8242b46551) | Jul 29, 2021 |
| Lenovo        | Unknown                     | Notebook    | [eef802c064](https://linux-hardware.org/?probe=eef802c064) | Jul 29, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [bdea6cca11](https://linux-hardware.org/?probe=bdea6cca11) | Jul 29, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [4769f95bad](https://linux-hardware.org/?probe=4769f95bad) | Jul 29, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [09419fd70a](https://linux-hardware.org/?probe=09419fd70a) | Jul 28, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [53bd733ffa](https://linux-hardware.org/?probe=53bd733ffa) | Jul 28, 2021 |
| Gigabyte      | i1520M                      | Notebook    | [5d0fb03190](https://linux-hardware.org/?probe=5d0fb03190) | Jul 28, 2021 |
| Gigabyte      | i1520M                      | Notebook    | [95de13078b](https://linux-hardware.org/?probe=95de13078b) | Jul 28, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [8fe5a59e53](https://linux-hardware.org/?probe=8fe5a59e53) | Jul 28, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [844de3ccbf](https://linux-hardware.org/?probe=844de3ccbf) | Jul 28, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [4b4496337a](https://linux-hardware.org/?probe=4b4496337a) | Jul 27, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [b6f42df92b](https://linux-hardware.org/?probe=b6f42df92b) | Jul 27, 2021 |
| AMI           | Intel                       | Convertible | [f57e799da4](https://linux-hardware.org/?probe=f57e799da4) | Jul 27, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [72e045b4da](https://linux-hardware.org/?probe=72e045b4da) | Jul 27, 2021 |
| Dell          | Latitude 7370               | Notebook    | [8844c61431](https://linux-hardware.org/?probe=8844c61431) | Jul 27, 2021 |
| Dell          | Latitude 7370               | Notebook    | [65b034f3f3](https://linux-hardware.org/?probe=65b034f3f3) | Jul 27, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [315f0fd290](https://linux-hardware.org/?probe=315f0fd290) | Jul 27, 2021 |
| Toshiba       | Satellite Pro L650          | Notebook    | [10e8624257](https://linux-hardware.org/?probe=10e8624257) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e2877b1692](https://linux-hardware.org/?probe=e2877b1692) | Jul 27, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [a4ecebc31b](https://linux-hardware.org/?probe=a4ecebc31b) | Jul 27, 2021 |
| AMI           | Intel                       | Convertible | [4902924370](https://linux-hardware.org/?probe=4902924370) | Jul 27, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [59e9b7398f](https://linux-hardware.org/?probe=59e9b7398f) | Jul 27, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6fcd0a6b24](https://linux-hardware.org/?probe=6fcd0a6b24) | Jul 27, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [98486b5f47](https://linux-hardware.org/?probe=98486b5f47) | Jul 27, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [67a1d9bcc9](https://linux-hardware.org/?probe=67a1d9bcc9) | Jul 27, 2021 |
| Dell          | Precision M6600             | Notebook    | [67a1d8b2e4](https://linux-hardware.org/?probe=67a1d8b2e4) | Jul 27, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [8a24dd720f](https://linux-hardware.org/?probe=8a24dd720f) | Jul 27, 2021 |
| ASUSTek       | N551JM                      | Notebook    | [4334fcb285](https://linux-hardware.org/?probe=4334fcb285) | Jul 27, 2021 |
| Intel         | BTC-T37                     | Desktop     | [758e5d4332](https://linux-hardware.org/?probe=758e5d4332) | Jul 27, 2021 |
| Intel         | BTC-T37                     | Desktop     | [000e132ac1](https://linux-hardware.org/?probe=000e132ac1) | Jul 26, 2021 |
| ASUSTek       | G73Jh                       | Notebook    | [e7af78fad2](https://linux-hardware.org/?probe=e7af78fad2) | Jul 26, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [588c5ca9f6](https://linux-hardware.org/?probe=588c5ca9f6) | Jul 26, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [d7369d7eb4](https://linux-hardware.org/?probe=d7369d7eb4) | Jul 26, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [ef88333344](https://linux-hardware.org/?probe=ef88333344) | Jul 26, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [b56b5cfff2](https://linux-hardware.org/?probe=b56b5cfff2) | Jul 26, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [87ca1f0bda](https://linux-hardware.org/?probe=87ca1f0bda) | Jul 26, 2021 |
| roda compu... | DS13                        | Notebook    | [be0c6525a4](https://linux-hardware.org/?probe=be0c6525a4) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [690b0d3adc](https://linux-hardware.org/?probe=690b0d3adc) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3185d49877](https://linux-hardware.org/?probe=3185d49877) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [3c2e8b0074](https://linux-hardware.org/?probe=3c2e8b0074) | Jul 26, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [474dfcb3e3](https://linux-hardware.org/?probe=474dfcb3e3) | Jul 26, 2021 |
| Dell          | 0RY007                      | Desktop     | [f2cd48444a](https://linux-hardware.org/?probe=f2cd48444a) | Jul 26, 2021 |
| Acer          | Aspire V5-531P              | Notebook    | [b236b9b9d9](https://linux-hardware.org/?probe=b236b9b9d9) | Jul 26, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [26ab6b470a](https://linux-hardware.org/?probe=26ab6b470a) | Jul 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bd817619dd](https://linux-hardware.org/?probe=bd817619dd) | Jul 25, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [f637e33171](https://linux-hardware.org/?probe=f637e33171) | Jul 25, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [074932b079](https://linux-hardware.org/?probe=074932b079) | Jul 25, 2021 |
| ASUSTek       | B150M-K                     | Desktop     | [34e2582dc2](https://linux-hardware.org/?probe=34e2582dc2) | Jul 25, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [acc53aae10](https://linux-hardware.org/?probe=acc53aae10) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fb1170efa6](https://linux-hardware.org/?probe=fb1170efa6) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [19f5976aa3](https://linux-hardware.org/?probe=19f5976aa3) | Jul 25, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [02dad54406](https://linux-hardware.org/?probe=02dad54406) | Jul 25, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [335bb2e92e](https://linux-hardware.org/?probe=335bb2e92e) | Jul 25, 2021 |
| HP            | ProBook 650 G5              | Notebook    | [6d3f09e9c2](https://linux-hardware.org/?probe=6d3f09e9c2) | Jul 25, 2021 |
| Acer          | Aspire V7-582P              | Notebook    | [308aee8cb1](https://linux-hardware.org/?probe=308aee8cb1) | Jul 25, 2021 |
| Acer          | Aspire V7-582P              | Notebook    | [6ce43ddc17](https://linux-hardware.org/?probe=6ce43ddc17) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [c466690f21](https://linux-hardware.org/?probe=c466690f21) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [bfbf5b3302](https://linux-hardware.org/?probe=bfbf5b3302) | Jul 25, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [740f322568](https://linux-hardware.org/?probe=740f322568) | Jul 25, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [7ed4e2945c](https://linux-hardware.org/?probe=7ed4e2945c) | Jul 24, 2021 |
| Dell          | Inspiron 7391 2n1           | Convertible | [40a7a1942f](https://linux-hardware.org/?probe=40a7a1942f) | Jul 24, 2021 |
| HP            | 212B                        | Desktop     | [2ae8fe394a](https://linux-hardware.org/?probe=2ae8fe394a) | Jul 24, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [7fa1d5f6ab](https://linux-hardware.org/?probe=7fa1d5f6ab) | Jul 24, 2021 |
| Dell          | 0D24M8 A01                  | Desktop     | [2080a71bc0](https://linux-hardware.org/?probe=2080a71bc0) | Jul 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [3d2cd06389](https://linux-hardware.org/?probe=3d2cd06389) | Jul 24, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [f938836ae3](https://linux-hardware.org/?probe=f938836ae3) | Jul 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7e6901b321](https://linux-hardware.org/?probe=7e6901b321) | Jul 24, 2021 |
| Sony          | VPCEJ1L1E                   | Notebook    | [ae5dc242e4](https://linux-hardware.org/?probe=ae5dc242e4) | Jul 24, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [d83e888f43](https://linux-hardware.org/?probe=d83e888f43) | Jul 24, 2021 |
| HP            | Elite x2 G4                 | Tablet      | [09f8c72d80](https://linux-hardware.org/?probe=09f8c72d80) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [aa0949f27f](https://linux-hardware.org/?probe=aa0949f27f) | Jul 24, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [61aa66455b](https://linux-hardware.org/?probe=61aa66455b) | Jul 23, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [df948c9a32](https://linux-hardware.org/?probe=df948c9a32) | Jul 23, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [80e7ec8f3f](https://linux-hardware.org/?probe=80e7ec8f3f) | Jul 23, 2021 |
| DNS           | Unknown                     | Notebook    | [fce7ca77f0](https://linux-hardware.org/?probe=fce7ca77f0) | Jul 23, 2021 |
| roda compu... | DS13                        | Notebook    | [ff3f6c2d6f](https://linux-hardware.org/?probe=ff3f6c2d6f) | Jul 23, 2021 |
| MSI           | H110M PRO-VH                | Desktop     | [42bd7fe7d2](https://linux-hardware.org/?probe=42bd7fe7d2) | Jul 23, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [d058df63d2](https://linux-hardware.org/?probe=d058df63d2) | Jul 23, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [cca8fb82b1](https://linux-hardware.org/?probe=cca8fb82b1) | Jul 23, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [0dc7d14a68](https://linux-hardware.org/?probe=0dc7d14a68) | Jul 23, 2021 |
| Supermicro    | X11DPH-T                    | Server      | [5e1947b31a](https://linux-hardware.org/?probe=5e1947b31a) | Jul 23, 2021 |
| MSI           | 3664h                       | Desktop     | [8141885507](https://linux-hardware.org/?probe=8141885507) | Jul 23, 2021 |
| HP            | 14                          | Notebook    | [29af89c91b](https://linux-hardware.org/?probe=29af89c91b) | Jul 23, 2021 |
| MSI           | B360M BAZOOKA               | Desktop     | [c0e89d7f2c](https://linux-hardware.org/?probe=c0e89d7f2c) | Jul 23, 2021 |
| MSI           | B360M BAZOOKA               | Desktop     | [53b9087fbb](https://linux-hardware.org/?probe=53b9087fbb) | Jul 23, 2021 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [c9d0df911e](https://linux-hardware.org/?probe=c9d0df911e) | Jul 23, 2021 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [6295127736](https://linux-hardware.org/?probe=6295127736) | Jul 22, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [bc81196561](https://linux-hardware.org/?probe=bc81196561) | Jul 22, 2021 |
| Medion        | E6226                       | Notebook    | [aee8a0be6f](https://linux-hardware.org/?probe=aee8a0be6f) | Jul 22, 2021 |
| Supermicro    | X11DPH-T                    | Server      | [0b9ed4af1a](https://linux-hardware.org/?probe=0b9ed4af1a) | Jul 22, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [81c950f0e4](https://linux-hardware.org/?probe=81c950f0e4) | Jul 22, 2021 |
| Acer          | WMCP78M                     | Desktop     | [591c077e28](https://linux-hardware.org/?probe=591c077e28) | Jul 22, 2021 |
| Lenovo        | Unknown                     | Notebook    | [425e6aa6da](https://linux-hardware.org/?probe=425e6aa6da) | Jul 22, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [4f3af1bdc2](https://linux-hardware.org/?probe=4f3af1bdc2) | Jul 22, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [f00892d38b](https://linux-hardware.org/?probe=f00892d38b) | Jul 22, 2021 |
| Intel         | X79 V2.4F                   | Desktop     | [62eca59ba3](https://linux-hardware.org/?probe=62eca59ba3) | Jul 22, 2021 |
| Intel         | X79 V2.4F                   | Desktop     | [c469ee9d35](https://linux-hardware.org/?probe=c469ee9d35) | Jul 22, 2021 |
| Acer          | WMCP78M                     | Desktop     | [4d35606ff5](https://linux-hardware.org/?probe=4d35606ff5) | Jul 22, 2021 |
| Dell          | Latitude 3410               | Notebook    | [4058065b38](https://linux-hardware.org/?probe=4058065b38) | Jul 21, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [cc39834e1d](https://linux-hardware.org/?probe=cc39834e1d) | Jul 21, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [900229235e](https://linux-hardware.org/?probe=900229235e) | Jul 21, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [2682c21b3a](https://linux-hardware.org/?probe=2682c21b3a) | Jul 21, 2021 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [29e4fc068f](https://linux-hardware.org/?probe=29e4fc068f) | Jul 21, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [c1dcbf95e4](https://linux-hardware.org/?probe=c1dcbf95e4) | Jul 21, 2021 |
| Dell          | 00FKMJ A00                  | Desktop     | [0b4299bc41](https://linux-hardware.org/?probe=0b4299bc41) | Jul 21, 2021 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [85533714a5](https://linux-hardware.org/?probe=85533714a5) | Jul 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [96d7245671](https://linux-hardware.org/?probe=96d7245671) | Jul 21, 2021 |
| Lenovo        | G485                        | Notebook    | [0810c75be3](https://linux-hardware.org/?probe=0810c75be3) | Jul 21, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [243cac5745](https://linux-hardware.org/?probe=243cac5745) | Jul 20, 2021 |
| HP            | 3397                        | Desktop     | [7626063783](https://linux-hardware.org/?probe=7626063783) | Jul 20, 2021 |
| HP            | 3397                        | Desktop     | [38dfe540f7](https://linux-hardware.org/?probe=38dfe540f7) | Jul 20, 2021 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [58b1c1aecf](https://linux-hardware.org/?probe=58b1c1aecf) | Jul 20, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [8e68827883](https://linux-hardware.org/?probe=8e68827883) | Jul 20, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [b7a612e4ec](https://linux-hardware.org/?probe=b7a612e4ec) | Jul 20, 2021 |
| HP            | ProBook 650 G5              | Notebook    | [0880c07a99](https://linux-hardware.org/?probe=0880c07a99) | Jul 20, 2021 |
| Lenovo        | G485                        | Notebook    | [aa805dfe8d](https://linux-hardware.org/?probe=aa805dfe8d) | Jul 20, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [20eed1cd12](https://linux-hardware.org/?probe=20eed1cd12) | Jul 20, 2021 |
| HP            | 14                          | Notebook    | [345be169ae](https://linux-hardware.org/?probe=345be169ae) | Jul 20, 2021 |
| PCWare        | IPMH61R1                    | Desktop     | [1212ad03e9](https://linux-hardware.org/?probe=1212ad03e9) | Jul 20, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [30a28565e9](https://linux-hardware.org/?probe=30a28565e9) | Jul 19, 2021 |
| MSI           | 890GXM-G65                  | Desktop     | [ae86741130](https://linux-hardware.org/?probe=ae86741130) | Jul 19, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fb9c551dd7](https://linux-hardware.org/?probe=fb9c551dd7) | Jul 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [5faacb9f0b](https://linux-hardware.org/?probe=5faacb9f0b) | Jul 19, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [1a9549039b](https://linux-hardware.org/?probe=1a9549039b) | Jul 19, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD           | Desktop     | [0f6b60cc29](https://linux-hardware.org/?probe=0f6b60cc29) | Jul 19, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD           | Desktop     | [704aa27146](https://linux-hardware.org/?probe=704aa27146) | Jul 19, 2021 |
| Dell          | OptiPlex 7020               | Desktop     | [653462ebfc](https://linux-hardware.org/?probe=653462ebfc) | Jul 19, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [576d7b9871](https://linux-hardware.org/?probe=576d7b9871) | Jul 19, 2021 |
| Dell          | OptiPlex 7020               | Desktop     | [221fc0def9](https://linux-hardware.org/?probe=221fc0def9) | Jul 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6136fa3477](https://linux-hardware.org/?probe=6136fa3477) | Jul 18, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [59a5d00285](https://linux-hardware.org/?probe=59a5d00285) | Jul 18, 2021 |
| Biostar       | NF520D3                     | Desktop     | [3c302b5285](https://linux-hardware.org/?probe=3c302b5285) | Jul 18, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [e9ecd52e2c](https://linux-hardware.org/?probe=e9ecd52e2c) | Jul 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [96144f8d28](https://linux-hardware.org/?probe=96144f8d28) | Jul 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [cdd331d9ab](https://linux-hardware.org/?probe=cdd331d9ab) | Jul 18, 2021 |
| Apple         | MacBook8,1                  | Notebook    | [f7cabbb5fe](https://linux-hardware.org/?probe=f7cabbb5fe) | Jul 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [3cc44e771e](https://linux-hardware.org/?probe=3cc44e771e) | Jul 17, 2021 |
| Dell          | Latitude E6520              | Notebook    | [67d96eeb17](https://linux-hardware.org/?probe=67d96eeb17) | Jul 17, 2021 |
| ASRock        | Z77 Extreme3                | Desktop     | [79dd398eff](https://linux-hardware.org/?probe=79dd398eff) | Jul 17, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [a44ab9f722](https://linux-hardware.org/?probe=a44ab9f722) | Jul 17, 2021 |
| ASUSTek       | K52Jr                       | Notebook    | [e8672d5819](https://linux-hardware.org/?probe=e8672d5819) | Jul 17, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [7988a9c084](https://linux-hardware.org/?probe=7988a9c084) | Jul 17, 2021 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [f7c2e4c1ff](https://linux-hardware.org/?probe=f7c2e4c1ff) | Jul 17, 2021 |
| Dell          | G3 3500                     | Notebook    | [12e1eb1ce7](https://linux-hardware.org/?probe=12e1eb1ce7) | Jul 17, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [2db57969aa](https://linux-hardware.org/?probe=2db57969aa) | Jul 17, 2021 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [279539af23](https://linux-hardware.org/?probe=279539af23) | Jul 17, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [4efc06b843](https://linux-hardware.org/?probe=4efc06b843) | Jul 17, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [1183f6f39b](https://linux-hardware.org/?probe=1183f6f39b) | Jul 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [4a64b763a8](https://linux-hardware.org/?probe=4a64b763a8) | Jul 16, 2021 |
| MSI           | H81M-P33                    | Desktop     | [4a187b22eb](https://linux-hardware.org/?probe=4a187b22eb) | Jul 16, 2021 |
| MSI           | H110M PRO-VH                | Desktop     | [c91d217ad5](https://linux-hardware.org/?probe=c91d217ad5) | Jul 16, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d1105aa53f](https://linux-hardware.org/?probe=d1105aa53f) | Jul 16, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [a776d1ea9c](https://linux-hardware.org/?probe=a776d1ea9c) | Jul 16, 2021 |
| ASUSTek       | M4A88T-M                    | Desktop     | [8a768d9d2e](https://linux-hardware.org/?probe=8a768d9d2e) | Jul 16, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f0241430cc](https://linux-hardware.org/?probe=f0241430cc) | Jul 16, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a87acc7896](https://linux-hardware.org/?probe=a87acc7896) | Jul 15, 2021 |
| ASUSTek       | X751LJ                      | Notebook    | [fcbeeff3a2](https://linux-hardware.org/?probe=fcbeeff3a2) | Jul 15, 2021 |
| ASUSTek       | X751SA                      | Notebook    | [8bde6f919c](https://linux-hardware.org/?probe=8bde6f919c) | Jul 15, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [00b0b9f630](https://linux-hardware.org/?probe=00b0b9f630) | Jul 15, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [15b36f53b7](https://linux-hardware.org/?probe=15b36f53b7) | Jul 15, 2021 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [b833818421](https://linux-hardware.org/?probe=b833818421) | Jul 15, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [1b1591901f](https://linux-hardware.org/?probe=1b1591901f) | Jul 15, 2021 |
| Samsung       | 800G5H/800G5S               | Notebook    | [43c5271ff4](https://linux-hardware.org/?probe=43c5271ff4) | Jul 15, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [20be8dbc44](https://linux-hardware.org/?probe=20be8dbc44) | Jul 15, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [3d1c92e425](https://linux-hardware.org/?probe=3d1c92e425) | Jul 15, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [7802550585](https://linux-hardware.org/?probe=7802550585) | Jul 15, 2021 |
| System76      | Serval WS                   | Notebook    | [9c6e77076c](https://linux-hardware.org/?probe=9c6e77076c) | Jul 15, 2021 |
| Dell          | Latitude 9510               | Convertible | [5f29a9b2c5](https://linux-hardware.org/?probe=5f29a9b2c5) | Jul 15, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [a27de08174](https://linux-hardware.org/?probe=a27de08174) | Jul 15, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [96ce85594c](https://linux-hardware.org/?probe=96ce85594c) | Jul 14, 2021 |
| Timi          | A35S                        | Notebook    | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [8e96e56dc3](https://linux-hardware.org/?probe=8e96e56dc3) | Jul 14, 2021 |
| Lenovo        | ThinkPad E14 20RBS7WC00     | Notebook    | [4d34393d9f](https://linux-hardware.org/?probe=4d34393d9f) | Jul 14, 2021 |
| Intel         | NUC8i7HVB J68196-602        | Mini pc     | [8834700cd9](https://linux-hardware.org/?probe=8834700cd9) | Jul 14, 2021 |
| Dell          | Latitude 9510               | Convertible | [4d37e1ab92](https://linux-hardware.org/?probe=4d37e1ab92) | Jul 14, 2021 |
| Dell          | Latitude 5300               | Notebook    | [c1bf5424e4](https://linux-hardware.org/?probe=c1bf5424e4) | Jul 14, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | Desktop     | [d84332d50b](https://linux-hardware.org/?probe=d84332d50b) | Jul 14, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | Desktop     | [f68b508049](https://linux-hardware.org/?probe=f68b508049) | Jul 14, 2021 |
| HP            | ProBook 4530s               | Notebook    | [603ec2d5c9](https://linux-hardware.org/?probe=603ec2d5c9) | Jul 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2b7c858e62](https://linux-hardware.org/?probe=2b7c858e62) | Jul 14, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9a7cff028c](https://linux-hardware.org/?probe=9a7cff028c) | Jul 14, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [eea8e3b740](https://linux-hardware.org/?probe=eea8e3b740) | Jul 14, 2021 |
| Biostar       | TZ68K+                      | Desktop     | [52ef8197ad](https://linux-hardware.org/?probe=52ef8197ad) | Jul 13, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [e363457394](https://linux-hardware.org/?probe=e363457394) | Jul 13, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5b9e8c2d22](https://linux-hardware.org/?probe=5b9e8c2d22) | Jul 13, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [41a7775b52](https://linux-hardware.org/?probe=41a7775b52) | Jul 13, 2021 |
| Dell          | 0D6H9T A00                  | Desktop     | [a989b9d184](https://linux-hardware.org/?probe=a989b9d184) | Jul 13, 2021 |
| Dell          | 0D6H9T A00                  | Desktop     | [19a34b1a62](https://linux-hardware.org/?probe=19a34b1a62) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [aa5fadb321](https://linux-hardware.org/?probe=aa5fadb321) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [dcc22fa273](https://linux-hardware.org/?probe=dcc22fa273) | Jul 13, 2021 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [4bf665fc54](https://linux-hardware.org/?probe=4bf665fc54) | Jul 13, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [2151a0b75d](https://linux-hardware.org/?probe=2151a0b75d) | Jul 13, 2021 |
| Dell          | Latitude E7440              | Notebook    | [e4d6f94ccb](https://linux-hardware.org/?probe=e4d6f94ccb) | Jul 13, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [870b9bdfca](https://linux-hardware.org/?probe=870b9bdfca) | Jul 13, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [f63afb571d](https://linux-hardware.org/?probe=f63afb571d) | Jul 13, 2021 |
| Acer          | AS5750G                     | Notebook    | [5059f64428](https://linux-hardware.org/?probe=5059f64428) | Jul 13, 2021 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [f44cd2127b](https://linux-hardware.org/?probe=f44cd2127b) | Jul 12, 2021 |
| MSI           | H61M-E22/W8                 | Desktop     | [6fff913666](https://linux-hardware.org/?probe=6fff913666) | Jul 12, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [4ad9830a25](https://linux-hardware.org/?probe=4ad9830a25) | Jul 12, 2021 |
| Lenovo        | ThinkPad W540 20BHS2LM02    | Notebook    | [6d00312e5e](https://linux-hardware.org/?probe=6d00312e5e) | Jul 12, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [a32287126e](https://linux-hardware.org/?probe=a32287126e) | Jul 12, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [393ed0c954](https://linux-hardware.org/?probe=393ed0c954) | Jul 12, 2021 |
| Chuwi         | HeroBook Pro+               | Notebook    | [ab9af242f2](https://linux-hardware.org/?probe=ab9af242f2) | Jul 12, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [3cf8675c2d](https://linux-hardware.org/?probe=3cf8675c2d) | Jul 12, 2021 |
| Dell          | 0WPG9H A00                  | All in one  | [c1fb12473c](https://linux-hardware.org/?probe=c1fb12473c) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [fe6c28a62e](https://linux-hardware.org/?probe=fe6c28a62e) | Jul 11, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [4bb7996ee5](https://linux-hardware.org/?probe=4bb7996ee5) | Jul 11, 2021 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [667aa68843](https://linux-hardware.org/?probe=667aa68843) | Jul 11, 2021 |
| Fujitsu       | LIFEBOOK A556               | Notebook    | [076bf0f706](https://linux-hardware.org/?probe=076bf0f706) | Jul 11, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b551baea7d](https://linux-hardware.org/?probe=b551baea7d) | Jul 11, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [62a4b43bb7](https://linux-hardware.org/?probe=62a4b43bb7) | Jul 11, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [729e09654e](https://linux-hardware.org/?probe=729e09654e) | Jul 11, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [76dc55b00e](https://linux-hardware.org/?probe=76dc55b00e) | Jul 11, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [f00c776e5d](https://linux-hardware.org/?probe=f00c776e5d) | Jul 11, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [e76377da85](https://linux-hardware.org/?probe=e76377da85) | Jul 11, 2021 |
| Lenovo        | 3000 N200 0769ESG           | Notebook    | [17edd23abd](https://linux-hardware.org/?probe=17edd23abd) | Jul 10, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [dc0cd1d174](https://linux-hardware.org/?probe=dc0cd1d174) | Jul 10, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [9371836e3e](https://linux-hardware.org/?probe=9371836e3e) | Jul 10, 2021 |
| Kogan         | KAL11D600PA                 | Tablet      | [7d5490c589](https://linux-hardware.org/?probe=7d5490c589) | Jul 10, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [395229874c](https://linux-hardware.org/?probe=395229874c) | Jul 10, 2021 |
| Acer          | Switch SW312-31             | Tablet      | [85ba39cbc6](https://linux-hardware.org/?probe=85ba39cbc6) | Jul 10, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3df3921e13](https://linux-hardware.org/?probe=3df3921e13) | Jul 10, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [064d13dec1](https://linux-hardware.org/?probe=064d13dec1) | Jul 10, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [21129fefc1](https://linux-hardware.org/?probe=21129fefc1) | Jul 10, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [f79af9ba9b](https://linux-hardware.org/?probe=f79af9ba9b) | Jul 10, 2021 |
| Medion        | Akoya E6416 MD99610         | Notebook    | [fa99920590](https://linux-hardware.org/?probe=fa99920590) | Jul 10, 2021 |
| Medion        | Akoya E6416 MD99610         | Notebook    | [a1a9ad6ac8](https://linux-hardware.org/?probe=a1a9ad6ac8) | Jul 10, 2021 |
| Pegatron      | Benicia                     | Desktop     | [ad6d42566b](https://linux-hardware.org/?probe=ad6d42566b) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [cd0155712e](https://linux-hardware.org/?probe=cd0155712e) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [9727587570](https://linux-hardware.org/?probe=9727587570) | Jul 10, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6C... | Notebook    | [516709833b](https://linux-hardware.org/?probe=516709833b) | Jul 10, 2021 |
| MSI           | H110M PRO-VH                | Desktop     | [39bbc7b6a9](https://linux-hardware.org/?probe=39bbc7b6a9) | Jul 09, 2021 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [ec4f4e1d9b](https://linux-hardware.org/?probe=ec4f4e1d9b) | Jul 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c006002427](https://linux-hardware.org/?probe=c006002427) | Jul 09, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [aff224171e](https://linux-hardware.org/?probe=aff224171e) | Jul 09, 2021 |
| Dell          | 0200DY A01                  | Desktop     | [28c56ed28e](https://linux-hardware.org/?probe=28c56ed28e) | Jul 09, 2021 |
| HP            | 872E                        | Mini pc     | [b1de952c4e](https://linux-hardware.org/?probe=b1de952c4e) | Jul 09, 2021 |
| Shuttle       | FH61V                       | Desktop     | [57e978bf7e](https://linux-hardware.org/?probe=57e978bf7e) | Jul 09, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [cda1d2d081](https://linux-hardware.org/?probe=cda1d2d081) | Jul 09, 2021 |
| Wiltronic     | IVIEW Maximus Pro           | Notebook    | [94e424774a](https://linux-hardware.org/?probe=94e424774a) | Jul 09, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [13ba44e5ee](https://linux-hardware.org/?probe=13ba44e5ee) | Jul 09, 2021 |
| ASRock        | H67M                        | Desktop     | [660e47da08](https://linux-hardware.org/?probe=660e47da08) | Jul 08, 2021 |
| HP            | ProLiant DL560 Gen8         | Server      | [5f7514110b](https://linux-hardware.org/?probe=5f7514110b) | Jul 08, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [950a407dff](https://linux-hardware.org/?probe=950a407dff) | Jul 08, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a03d8e33d2](https://linux-hardware.org/?probe=a03d8e33d2) | Jul 08, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [65dab5ea20](https://linux-hardware.org/?probe=65dab5ea20) | Jul 08, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [71f2a9ae1f](https://linux-hardware.org/?probe=71f2a9ae1f) | Jul 08, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [cdc6087931](https://linux-hardware.org/?probe=cdc6087931) | Jul 08, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [905b293afa](https://linux-hardware.org/?probe=905b293afa) | Jul 08, 2021 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [77513a0fe5](https://linux-hardware.org/?probe=77513a0fe5) | Jul 08, 2021 |
| MSI           | CSM-H81M-P32                | Desktop     | [dcac2bf6e1](https://linux-hardware.org/?probe=dcac2bf6e1) | Jul 08, 2021 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [8beba5ddf7](https://linux-hardware.org/?probe=8beba5ddf7) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [6aa95f6599](https://linux-hardware.org/?probe=6aa95f6599) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [2a2e03aaa8](https://linux-hardware.org/?probe=2a2e03aaa8) | Jul 08, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [76a98ccf8a](https://linux-hardware.org/?probe=76a98ccf8a) | Jul 08, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7ff048cc41](https://linux-hardware.org/?probe=7ff048cc41) | Jul 08, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [e1e7fa29fb](https://linux-hardware.org/?probe=e1e7fa29fb) | Jul 08, 2021 |
| Unknown       | 1.0                         | Notebook    | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [020cab13c8](https://linux-hardware.org/?probe=020cab13c8) | Jul 08, 2021 |
| Dell          | 0WR7PY A00                  | Desktop     | [174989025c](https://linux-hardware.org/?probe=174989025c) | Jul 07, 2021 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [f05a96bdac](https://linux-hardware.org/?probe=f05a96bdac) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3980... | Notebook    | [99729a0a68](https://linux-hardware.org/?probe=99729a0a68) | Jul 07, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [de0ab0b7c2](https://linux-hardware.org/?probe=de0ab0b7c2) | Jul 07, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [4c4f65a000](https://linux-hardware.org/?probe=4c4f65a000) | Jul 07, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [8f33247147](https://linux-hardware.org/?probe=8f33247147) | Jul 07, 2021 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [11cb60efc3](https://linux-hardware.org/?probe=11cb60efc3) | Jul 07, 2021 |
| Dell          | G7 7700                     | Notebook    | [6fc41408bf](https://linux-hardware.org/?probe=6fc41408bf) | Jul 07, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [d87f176b36](https://linux-hardware.org/?probe=d87f176b36) | Jul 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [29727eef05](https://linux-hardware.org/?probe=29727eef05) | Jul 07, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [64371c73a0](https://linux-hardware.org/?probe=64371c73a0) | Jul 07, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [bc8df07ff7](https://linux-hardware.org/?probe=bc8df07ff7) | Jul 06, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7b4d2e8580](https://linux-hardware.org/?probe=7b4d2e8580) | Jul 06, 2021 |
| Dell          | Inspiron 5482               | Notebook    | [0d8c9adb49](https://linux-hardware.org/?probe=0d8c9adb49) | Jul 06, 2021 |
| Dell          | Latitude 5511               | Notebook    | [cac1bff4a1](https://linux-hardware.org/?probe=cac1bff4a1) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G713QR_G713QR     | Notebook    | [0b10aaa23c](https://linux-hardware.org/?probe=0b10aaa23c) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G713QR_G713QR     | Notebook    | [6c81e98dd0](https://linux-hardware.org/?probe=6c81e98dd0) | Jul 06, 2021 |
| Lenovo        | ThinkStation D10 6493RT8    | Desktop     | [8adc2b3a82](https://linux-hardware.org/?probe=8adc2b3a82) | Jul 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1b38515a6a](https://linux-hardware.org/?probe=1b38515a6a) | Jul 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0033ea368f](https://linux-hardware.org/?probe=0033ea368f) | Jul 06, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [c3bed169fd](https://linux-hardware.org/?probe=c3bed169fd) | Jul 06, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [0345fe1b56](https://linux-hardware.org/?probe=0345fe1b56) | Jul 05, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [f2ab6f6a6f](https://linux-hardware.org/?probe=f2ab6f6a6f) | Jul 05, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [260f6cb321](https://linux-hardware.org/?probe=260f6cb321) | Jul 05, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [92cfe5edd3](https://linux-hardware.org/?probe=92cfe5edd3) | Jul 05, 2021 |
| HP            | 83E8                        | Desktop     | [dd469e94e9](https://linux-hardware.org/?probe=dd469e94e9) | Jul 05, 2021 |
| Dell          | Latitude E6320              | Notebook    | [dc31c90631](https://linux-hardware.org/?probe=dc31c90631) | Jul 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [621494a6e3](https://linux-hardware.org/?probe=621494a6e3) | Jul 05, 2021 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [09dbdc286a](https://linux-hardware.org/?probe=09dbdc286a) | Jul 05, 2021 |
| Dell          | Latitude E5520              | Notebook    | [11a20a01eb](https://linux-hardware.org/?probe=11a20a01eb) | Jul 05, 2021 |
| HP            | 8430 1000                   | All in one  | [2f519d5ae4](https://linux-hardware.org/?probe=2f519d5ae4) | Jul 05, 2021 |
| Gigabyte      | H110M-S2V DDR3-CF           | Desktop     | [9eac8917f1](https://linux-hardware.org/?probe=9eac8917f1) | Jul 04, 2021 |
| ASUSTek       | X751SA                      | Notebook    | [98d8d8a1ca](https://linux-hardware.org/?probe=98d8d8a1ca) | Jul 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [94e917d395](https://linux-hardware.org/?probe=94e917d395) | Jul 04, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [867e24050a](https://linux-hardware.org/?probe=867e24050a) | Jul 04, 2021 |
| HP            | Compaq 510                  | Notebook    | [cd27b78fea](https://linux-hardware.org/?probe=cd27b78fea) | Jul 04, 2021 |
| MSI           | H81M-P33                    | Desktop     | [5a289e338f](https://linux-hardware.org/?probe=5a289e338f) | Jul 04, 2021 |
| MSI           | G41M-P33                    | Desktop     | [8bc3bbf743](https://linux-hardware.org/?probe=8bc3bbf743) | Jul 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e807bd56bc](https://linux-hardware.org/?probe=e807bd56bc) | Jul 04, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [db93b6b390](https://linux-hardware.org/?probe=db93b6b390) | Jul 03, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [926e72bc56](https://linux-hardware.org/?probe=926e72bc56) | Jul 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [48a36ae4a4](https://linux-hardware.org/?probe=48a36ae4a4) | Jul 03, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [29dc877a37](https://linux-hardware.org/?probe=29dc877a37) | Jul 03, 2021 |
| Dell          | Latitude E6400              | Notebook    | [18d5b00f71](https://linux-hardware.org/?probe=18d5b00f71) | Jul 03, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c669795b35](https://linux-hardware.org/?probe=c669795b35) | Jul 03, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4298da2e03](https://linux-hardware.org/?probe=4298da2e03) | Jul 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f5ca9e190e](https://linux-hardware.org/?probe=f5ca9e190e) | Jul 02, 2021 |
| Dell          | Latitude E6430              | Notebook    | [43100da49e](https://linux-hardware.org/?probe=43100da49e) | Jul 02, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Biostar       | H61MLV2                     | Desktop     | [45f8d339a6](https://linux-hardware.org/?probe=45f8d339a6) | Jul 02, 2021 |
| Dell          | Inspiron 1750               | Notebook    | [2ff81df67a](https://linux-hardware.org/?probe=2ff81df67a) | Jul 02, 2021 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [dcec6c2c5f](https://linux-hardware.org/?probe=dcec6c2c5f) | Jul 02, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [cdcbc5460d](https://linux-hardware.org/?probe=cdcbc5460d) | Jul 02, 2021 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [f0de8a11c7](https://linux-hardware.org/?probe=f0de8a11c7) | Jul 02, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [c8a5a8c476](https://linux-hardware.org/?probe=c8a5a8c476) | Jul 02, 2021 |
| Sony          | VGN-FE880E                  | Notebook    | [920adf56ec](https://linux-hardware.org/?probe=920adf56ec) | Jul 02, 2021 |
| Sony          | VGN-FE880E                  | Notebook    | [6ae2ef9b19](https://linux-hardware.org/?probe=6ae2ef9b19) | Jul 02, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [36176e3082](https://linux-hardware.org/?probe=36176e3082) | Jul 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [0dd8596f55](https://linux-hardware.org/?probe=0dd8596f55) | Jul 01, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [4e808a5437](https://linux-hardware.org/?probe=4e808a5437) | Jul 01, 2021 |
| Timi          | TM1701                      | Notebook    | [fe9f90644b](https://linux-hardware.org/?probe=fe9f90644b) | Jul 01, 2021 |
| HP            | 620                         | Notebook    | [a1ca12ac2c](https://linux-hardware.org/?probe=a1ca12ac2c) | Jul 01, 2021 |
| Dell          | Studio 1735                 | Notebook    | [2ed92032e0](https://linux-hardware.org/?probe=2ed92032e0) | Jul 01, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [c7dfa113bc](https://linux-hardware.org/?probe=c7dfa113bc) | Jul 01, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [1c7ba3c173](https://linux-hardware.org/?probe=1c7ba3c173) | Jul 01, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f281017450](https://linux-hardware.org/?probe=f281017450) | Jun 30, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [57d8d9da44](https://linux-hardware.org/?probe=57d8d9da44) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [5530b28aa3](https://linux-hardware.org/?probe=5530b28aa3) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [582e4795cf](https://linux-hardware.org/?probe=582e4795cf) | Jun 30, 2021 |
| MSI           | 890GXM-G65                  | Desktop     | [f4e1c45ed2](https://linux-hardware.org/?probe=f4e1c45ed2) | Jun 30, 2021 |
| Pegatron      | 2AC2                        | Desktop     | [46df29e3a0](https://linux-hardware.org/?probe=46df29e3a0) | Jun 30, 2021 |
| Dell          | Inspiron 7472               | Notebook    | [0624b57fad](https://linux-hardware.org/?probe=0624b57fad) | Jun 30, 2021 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [75dfe18377](https://linux-hardware.org/?probe=75dfe18377) | Jun 30, 2021 |
| Medion        | E2228T MD61450              | Convertible | [474e42c2b5](https://linux-hardware.org/?probe=474e42c2b5) | Jun 30, 2021 |
| Dell          | Latitude 9420               | Convertible | [01fe04725b](https://linux-hardware.org/?probe=01fe04725b) | Jun 30, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [39ce85da03](https://linux-hardware.org/?probe=39ce85da03) | Jun 30, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [3ec309cb24](https://linux-hardware.org/?probe=3ec309cb24) | Jun 30, 2021 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [618305c432](https://linux-hardware.org/?probe=618305c432) | Jun 30, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [e9cd0640f7](https://linux-hardware.org/?probe=e9cd0640f7) | Jun 30, 2021 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [fa67031341](https://linux-hardware.org/?probe=fa67031341) | Jun 29, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [072048636a](https://linux-hardware.org/?probe=072048636a) | Jun 29, 2021 |
| HP            | Notebook                    | Notebook    | [3087e92283](https://linux-hardware.org/?probe=3087e92283) | Jun 29, 2021 |
| HP            | ENVY Laptop 17m-ch0xxx      | Notebook    | [a310f33226](https://linux-hardware.org/?probe=a310f33226) | Jun 29, 2021 |
| Timi          | Mi Laptop Pro 15 2020       | Notebook    | [6632675d89](https://linux-hardware.org/?probe=6632675d89) | Jun 29, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [44ea4016b6](https://linux-hardware.org/?probe=44ea4016b6) | Jun 29, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [3f2438194e](https://linux-hardware.org/?probe=3f2438194e) | Jun 29, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [e99b341cf4](https://linux-hardware.org/?probe=e99b341cf4) | Jun 29, 2021 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [a26ce90876](https://linux-hardware.org/?probe=a26ce90876) | Jun 29, 2021 |
| Wiltronic     | IVIEW Maximus Pro           | Notebook    | [92570b133c](https://linux-hardware.org/?probe=92570b133c) | Jun 29, 2021 |
| ASRock        | B85 Pro4                    | Desktop     | [f9a2e6f60c](https://linux-hardware.org/?probe=f9a2e6f60c) | Jun 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [63055a9c60](https://linux-hardware.org/?probe=63055a9c60) | Jun 29, 2021 |
| Lenovo        | ThinkCentre M57 6062A25     | Desktop     | [e5a404d35c](https://linux-hardware.org/?probe=e5a404d35c) | Jun 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d210f1fcac](https://linux-hardware.org/?probe=d210f1fcac) | Jun 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f31a585b5d](https://linux-hardware.org/?probe=f31a585b5d) | Jun 28, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [a68897f1b5](https://linux-hardware.org/?probe=a68897f1b5) | Jun 28, 2021 |
| Dell          | Inspiron 7706 2n1           | Convertible | [77d7cb06f4](https://linux-hardware.org/?probe=77d7cb06f4) | Jun 28, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [0a190b5aa4](https://linux-hardware.org/?probe=0a190b5aa4) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d6fb94e774](https://linux-hardware.org/?probe=d6fb94e774) | Jun 28, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [42238e9adc](https://linux-hardware.org/?probe=42238e9adc) | Jun 28, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [e86f5af473](https://linux-hardware.org/?probe=e86f5af473) | Jun 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [deedec89af](https://linux-hardware.org/?probe=deedec89af) | Jun 28, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ba899e1f03](https://linux-hardware.org/?probe=ba899e1f03) | Jun 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1894c1b871](https://linux-hardware.org/?probe=1894c1b871) | Jun 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b0e2de6bbe](https://linux-hardware.org/?probe=b0e2de6bbe) | Jun 27, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [15884a55b2](https://linux-hardware.org/?probe=15884a55b2) | Jun 27, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [921fcdf0c3](https://linux-hardware.org/?probe=921fcdf0c3) | Jun 27, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [d0fb4fb2ad](https://linux-hardware.org/?probe=d0fb4fb2ad) | Jun 27, 2021 |
| ASUSTek       | Basswood                    | Desktop     | [daf1b9da91](https://linux-hardware.org/?probe=daf1b9da91) | Jun 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [c0e15bcf06](https://linux-hardware.org/?probe=c0e15bcf06) | Jun 27, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [92244e3c98](https://linux-hardware.org/?probe=92244e3c98) | Jun 27, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [e56a7ee3c9](https://linux-hardware.org/?probe=e56a7ee3c9) | Jun 27, 2021 |
| Acer          | TravelMate P653-M           | Notebook    | [f8509314e3](https://linux-hardware.org/?probe=f8509314e3) | Jun 27, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [5c56f0fc2f](https://linux-hardware.org/?probe=5c56f0fc2f) | Jun 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [d96ffce12a](https://linux-hardware.org/?probe=d96ffce12a) | Jun 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [62ab2d4450](https://linux-hardware.org/?probe=62ab2d4450) | Jun 26, 2021 |
| HP            | ProBook 440 G5              | Notebook    | [d7bcf08f6a](https://linux-hardware.org/?probe=d7bcf08f6a) | Jun 26, 2021 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [fa17f630fc](https://linux-hardware.org/?probe=fa17f630fc) | Jun 26, 2021 |
| HP            | ProBook 440 G4              | Notebook    | [730c184b2b](https://linux-hardware.org/?probe=730c184b2b) | Jun 26, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [8fae33ceb8](https://linux-hardware.org/?probe=8fae33ceb8) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [c42e493962](https://linux-hardware.org/?probe=c42e493962) | Jun 26, 2021 |
| ASRock        | TRX40 Taichi                | Desktop     | [6a2d22eae8](https://linux-hardware.org/?probe=6a2d22eae8) | Jun 26, 2021 |
| ASRock        | TRX40 Taichi                | Desktop     | [5b1b696b98](https://linux-hardware.org/?probe=5b1b696b98) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [9834731c15](https://linux-hardware.org/?probe=9834731c15) | Jun 26, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [d1e5fbd176](https://linux-hardware.org/?probe=d1e5fbd176) | Jun 26, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [b28ac0c857](https://linux-hardware.org/?probe=b28ac0c857) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [048336bb59](https://linux-hardware.org/?probe=048336bb59) | Jun 26, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [6e52c0e48b](https://linux-hardware.org/?probe=6e52c0e48b) | Jun 26, 2021 |
| Dell          | 0FPP7F A00                  | Desktop     | [2e2e4ab599](https://linux-hardware.org/?probe=2e2e4ab599) | Jun 26, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [0d7b1e266d](https://linux-hardware.org/?probe=0d7b1e266d) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [b93fa99bf8](https://linux-hardware.org/?probe=b93fa99bf8) | Jun 26, 2021 |
| Dell          | G3 3590                     | Notebook    | [06d10d0717](https://linux-hardware.org/?probe=06d10d0717) | Jun 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f9070b6d21](https://linux-hardware.org/?probe=f9070b6d21) | Jun 26, 2021 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [3791b62c7e](https://linux-hardware.org/?probe=3791b62c7e) | Jun 25, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [d1d2e34e3c](https://linux-hardware.org/?probe=d1d2e34e3c) | Jun 25, 2021 |
| Dell          | 0TT6JF A02                  | Server      | [3cf16bb78b](https://linux-hardware.org/?probe=3cf16bb78b) | Jun 25, 2021 |
| Lenovo        | ThinkPad P73 20QR0024GE     | Notebook    | [16b2f5dcfc](https://linux-hardware.org/?probe=16b2f5dcfc) | Jun 25, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [598db879ae](https://linux-hardware.org/?probe=598db879ae) | Jun 25, 2021 |
| ASUSTek       | F1A55-M LX R2.0             | Desktop     | [dab6b0d848](https://linux-hardware.org/?probe=dab6b0d848) | Jun 25, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [71134cd640](https://linux-hardware.org/?probe=71134cd640) | Jun 25, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [7c679b05c3](https://linux-hardware.org/?probe=7c679b05c3) | Jun 25, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3804a38690](https://linux-hardware.org/?probe=3804a38690) | Jun 25, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [52bee2a54e](https://linux-hardware.org/?probe=52bee2a54e) | Jun 25, 2021 |
| Dell          | Latitude 9420               | Convertible | [8aeecb9e37](https://linux-hardware.org/?probe=8aeecb9e37) | Jun 25, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7013a95d0a](https://linux-hardware.org/?probe=7013a95d0a) | Jun 25, 2021 |
| Intel         | X79 V2.72B                  | Desktop     | [c78b66e96e](https://linux-hardware.org/?probe=c78b66e96e) | Jun 25, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [3da8487d5f](https://linux-hardware.org/?probe=3da8487d5f) | Jun 24, 2021 |
| Teclast       | F7 Plus                     | Notebook    | [a11823af5a](https://linux-hardware.org/?probe=a11823af5a) | Jun 24, 2021 |
| Dell          | Latitude E6420              | Notebook    | [68f21f9b57](https://linux-hardware.org/?probe=68f21f9b57) | Jun 24, 2021 |
| Medion        | E6429 MD60812               | Notebook    | [8f8daf18b9](https://linux-hardware.org/?probe=8f8daf18b9) | Jun 24, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [180890e9c8](https://linux-hardware.org/?probe=180890e9c8) | Jun 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [00ef418c43](https://linux-hardware.org/?probe=00ef418c43) | Jun 24, 2021 |
| HP            | 245 G6                      | Notebook    | [7f8e4b050a](https://linux-hardware.org/?probe=7f8e4b050a) | Jun 24, 2021 |
| ASUSTek       | E402SA                      | Notebook    | [6e79fb94aa](https://linux-hardware.org/?probe=6e79fb94aa) | Jun 24, 2021 |
| Dell          | Latitude 5511               | Notebook    | [10434415d8](https://linux-hardware.org/?probe=10434415d8) | Jun 24, 2021 |
| HP            | Notebook                    | Notebook    | [c3f23110da](https://linux-hardware.org/?probe=c3f23110da) | Jun 24, 2021 |
| ASUSTek       | P5KPL-AM IN/GB              | Desktop     | [24c93ed20a](https://linux-hardware.org/?probe=24c93ed20a) | Jun 24, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [1905557ab4](https://linux-hardware.org/?probe=1905557ab4) | Jun 24, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [fe7063735e](https://linux-hardware.org/?probe=fe7063735e) | Jun 24, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [7be7bba24f](https://linux-hardware.org/?probe=7be7bba24f) | Jun 24, 2021 |
| Dell          | Latitude E5540              | Notebook    | [a240b57157](https://linux-hardware.org/?probe=a240b57157) | Jun 24, 2021 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [39f96730d9](https://linux-hardware.org/?probe=39f96730d9) | Jun 23, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7804268ecf](https://linux-hardware.org/?probe=7804268ecf) | Jun 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [e24031d13d](https://linux-hardware.org/?probe=e24031d13d) | Jun 23, 2021 |
| MSI           | Z270I CORSAIR ONE           | Desktop     | [0609479af2](https://linux-hardware.org/?probe=0609479af2) | Jun 23, 2021 |
| MSI           | Z270I CORSAIR ONE           | Desktop     | [bbbed29691](https://linux-hardware.org/?probe=bbbed29691) | Jun 23, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [f1d9fcd165](https://linux-hardware.org/?probe=f1d9fcd165) | Jun 23, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [06e8d9bce7](https://linux-hardware.org/?probe=06e8d9bce7) | Jun 23, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [463c88f144](https://linux-hardware.org/?probe=463c88f144) | Jun 23, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [8c9260d570](https://linux-hardware.org/?probe=8c9260d570) | Jun 23, 2021 |
| Dell          | Vostro 5581                 | Notebook    | [5e0ea603d3](https://linux-hardware.org/?probe=5e0ea603d3) | Jun 23, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [c13a83286a](https://linux-hardware.org/?probe=c13a83286a) | Jun 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f817714db4](https://linux-hardware.org/?probe=f817714db4) | Jun 22, 2021 |
| OEM           | B250B                       | Desktop     | [76ea6ec5b6](https://linux-hardware.org/?probe=76ea6ec5b6) | Jun 22, 2021 |
| Packard Be... | MCP73                       | Desktop     | [949909da41](https://linux-hardware.org/?probe=949909da41) | Jun 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [8ed5dab80e](https://linux-hardware.org/?probe=8ed5dab80e) | Jun 22, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [51fd033b49](https://linux-hardware.org/?probe=51fd033b49) | Jun 22, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [f52276d111](https://linux-hardware.org/?probe=f52276d111) | Jun 22, 2021 |
| Maibenben     | MaiBook S                   | Notebook    | [a6e045f815](https://linux-hardware.org/?probe=a6e045f815) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| TYAN Compu... | Toledo i3210W/i3200R S52... | Desktop     | [cfacd9e7ce](https://linux-hardware.org/?probe=cfacd9e7ce) | Jun 21, 2021 |
| Dell          | Latitude 5511               | Notebook    | [6625368d80](https://linux-hardware.org/?probe=6625368d80) | Jun 21, 2021 |
| Positivo      | W940SU2                     | Notebook    | [7baff31673](https://linux-hardware.org/?probe=7baff31673) | Jun 21, 2021 |
| OEM           | B250B                       | Desktop     | [cadd03edf3](https://linux-hardware.org/?probe=cadd03edf3) | Jun 21, 2021 |
| HP            | Laptop 17-ak0xx             | Notebook    | [4ae96f3d68](https://linux-hardware.org/?probe=4ae96f3d68) | Jun 21, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [c40ed6f57e](https://linux-hardware.org/?probe=c40ed6f57e) | Jun 21, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [6c5f517ffe](https://linux-hardware.org/?probe=6c5f517ffe) | Jun 21, 2021 |
| Packard Be... | MCP73                       | Desktop     | [e1eb07cc34](https://linux-hardware.org/?probe=e1eb07cc34) | Jun 21, 2021 |
| ASUSTek       | P5KPL-AM IN/GB              | Desktop     | [b23297702d](https://linux-hardware.org/?probe=b23297702d) | Jun 21, 2021 |
| Medion        | E6429 MD60812               | Notebook    | [05db194f3f](https://linux-hardware.org/?probe=05db194f3f) | Jun 21, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [5fa67b7e7e](https://linux-hardware.org/?probe=5fa67b7e7e) | Jun 21, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [5573a86f4c](https://linux-hardware.org/?probe=5573a86f4c) | Jun 21, 2021 |
| Dell          | Vostro 5581                 | Notebook    | [bd7fdd93ec](https://linux-hardware.org/?probe=bd7fdd93ec) | Jun 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3886ce4f71](https://linux-hardware.org/?probe=3886ce4f71) | Jun 21, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [ba24de57b3](https://linux-hardware.org/?probe=ba24de57b3) | Jun 21, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [3e013acd03](https://linux-hardware.org/?probe=3e013acd03) | Jun 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [08c40500a8](https://linux-hardware.org/?probe=08c40500a8) | Jun 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [550a41e850](https://linux-hardware.org/?probe=550a41e850) | Jun 21, 2021 |
| ASUSTek       | X550LB                      | Notebook    | [81070e651b](https://linux-hardware.org/?probe=81070e651b) | Jun 21, 2021 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [e8196c8861](https://linux-hardware.org/?probe=e8196c8861) | Jun 21, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [ac12b3d63e](https://linux-hardware.org/?probe=ac12b3d63e) | Jun 21, 2021 |
| Pegatron      | Benicia                     | Desktop     | [40526a2b4c](https://linux-hardware.org/?probe=40526a2b4c) | Jun 20, 2021 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [3f07752a76](https://linux-hardware.org/?probe=3f07752a76) | Jun 20, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [a563fa0660](https://linux-hardware.org/?probe=a563fa0660) | Jun 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7ddb9a5ab7](https://linux-hardware.org/?probe=7ddb9a5ab7) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [14083d2e96](https://linux-hardware.org/?probe=14083d2e96) | Jun 20, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [a3b81cc44c](https://linux-hardware.org/?probe=a3b81cc44c) | Jun 20, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [6cd85599cd](https://linux-hardware.org/?probe=6cd85599cd) | Jun 20, 2021 |
| Pegatron      | H36Y                        | Notebook    | [9209a16c5c](https://linux-hardware.org/?probe=9209a16c5c) | Jun 20, 2021 |
| System76      | Serval WS serw8-17g         | Notebook    | [913f491e05](https://linux-hardware.org/?probe=913f491e05) | Jun 20, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [89683f356e](https://linux-hardware.org/?probe=89683f356e) | Jun 19, 2021 |
| Biostar       | TB250-BTC                   | Desktop     | [135a42fc66](https://linux-hardware.org/?probe=135a42fc66) | Jun 19, 2021 |
| Biostar       | TB250-BTC                   | Desktop     | [acdf9bed0d](https://linux-hardware.org/?probe=acdf9bed0d) | Jun 19, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [24e2ca432c](https://linux-hardware.org/?probe=24e2ca432c) | Jun 19, 2021 |
| Dell          | Latitude E5570              | Notebook    | [b4bd39cf38](https://linux-hardware.org/?probe=b4bd39cf38) | Jun 19, 2021 |
| HP            | Notebook                    | Notebook    | [daae35477b](https://linux-hardware.org/?probe=daae35477b) | Jun 19, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [c13134fc57](https://linux-hardware.org/?probe=c13134fc57) | Jun 19, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [a53fb9eb09](https://linux-hardware.org/?probe=a53fb9eb09) | Jun 19, 2021 |
| Nvidia        | Jetson Nano Developer Ki... | Soc         | [1ccd6eee0e](https://linux-hardware.org/?probe=1ccd6eee0e) | Jun 19, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [8337e476da](https://linux-hardware.org/?probe=8337e476da) | Jun 19, 2021 |
| ASRock        | B85M Pro4                   | Desktop     | [3400ad3eb1](https://linux-hardware.org/?probe=3400ad3eb1) | Jun 19, 2021 |
| HP            | 18-5600br                   | Notebook    | [d0583b92ed](https://linux-hardware.org/?probe=d0583b92ed) | Jun 19, 2021 |
| MSI           | Z77A-G43 GAMING             | Desktop     | [e5da744b7b](https://linux-hardware.org/?probe=e5da744b7b) | Jun 19, 2021 |
| ECS           | H61H2-TI                    | All in one  | [f8a9a819f3](https://linux-hardware.org/?probe=f8a9a819f3) | Jun 18, 2021 |
| ASRock        | B85M Pro4                   | Desktop     | [f1e7b8a65b](https://linux-hardware.org/?probe=f1e7b8a65b) | Jun 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [c9cefa3aea](https://linux-hardware.org/?probe=c9cefa3aea) | Jun 18, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [b2c184af4f](https://linux-hardware.org/?probe=b2c184af4f) | Jun 18, 2021 |
| Schenker      | XMG CORE 17(M20, GTX 165... | Notebook    | [9445d67978](https://linux-hardware.org/?probe=9445d67978) | Jun 18, 2021 |
| Lenovo        | ThinkPad L580 20LXS6NE02    | Notebook    | [d9a2077c08](https://linux-hardware.org/?probe=d9a2077c08) | Jun 18, 2021 |
| Dell          | Latitude XT3                | Notebook    | [1c523898cb](https://linux-hardware.org/?probe=1c523898cb) | Jun 18, 2021 |
| Dell          | Latitude XT3                | Notebook    | [80e1b1d818](https://linux-hardware.org/?probe=80e1b1d818) | Jun 18, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [33fce68a70](https://linux-hardware.org/?probe=33fce68a70) | Jun 18, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [11daeeac47](https://linux-hardware.org/?probe=11daeeac47) | Jun 18, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [c843908a01](https://linux-hardware.org/?probe=c843908a01) | Jun 18, 2021 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [b0d1052f9f](https://linux-hardware.org/?probe=b0d1052f9f) | Jun 17, 2021 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [542e64b8b1](https://linux-hardware.org/?probe=542e64b8b1) | Jun 17, 2021 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [7a60f78b32](https://linux-hardware.org/?probe=7a60f78b32) | Jun 17, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [32ef787520](https://linux-hardware.org/?probe=32ef787520) | Jun 17, 2021 |
| Dell          | G3 3590                     | Notebook    | [adf875d64d](https://linux-hardware.org/?probe=adf875d64d) | Jun 17, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [39e707392d](https://linux-hardware.org/?probe=39e707392d) | Jun 17, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [097a4a8f7c](https://linux-hardware.org/?probe=097a4a8f7c) | Jun 16, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [886132fd6a](https://linux-hardware.org/?probe=886132fd6a) | Jun 16, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [fff555363c](https://linux-hardware.org/?probe=fff555363c) | Jun 16, 2021 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [1b6fedfa86](https://linux-hardware.org/?probe=1b6fedfa86) | Jun 16, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [061955c2a0](https://linux-hardware.org/?probe=061955c2a0) | Jun 16, 2021 |
| ASUSTek       | M2N68-AM                    | Desktop     | [21b5888299](https://linux-hardware.org/?probe=21b5888299) | Jun 16, 2021 |
| HP            | EliteBook 725 G3            | Notebook    | [f57f7d1e53](https://linux-hardware.org/?probe=f57f7d1e53) | Jun 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [e8f056e976](https://linux-hardware.org/?probe=e8f056e976) | Jun 16, 2021 |
| MSI           | B250I PRO                   | Desktop     | [02087ebc8a](https://linux-hardware.org/?probe=02087ebc8a) | Jun 15, 2021 |
| MSI           | B250I PRO                   | Desktop     | [05b0b94ace](https://linux-hardware.org/?probe=05b0b94ace) | Jun 15, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9045745027](https://linux-hardware.org/?probe=9045745027) | Jun 15, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [e62dd54d79](https://linux-hardware.org/?probe=e62dd54d79) | Jun 15, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [0ccd0cdf44](https://linux-hardware.org/?probe=0ccd0cdf44) | Jun 15, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [ab0934d142](https://linux-hardware.org/?probe=ab0934d142) | Jun 15, 2021 |
| Lenovo        | BS145-15IIL 82HB            | Notebook    | [e1e37c4609](https://linux-hardware.org/?probe=e1e37c4609) | Jun 15, 2021 |
| Dell          | Inspiron 7590 2n1           | Convertible | [fab20d7724](https://linux-hardware.org/?probe=fab20d7724) | Jun 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [27be88c747](https://linux-hardware.org/?probe=27be88c747) | Jun 14, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3d0e9bc4aa](https://linux-hardware.org/?probe=3d0e9bc4aa) | Jun 14, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [6757c0e254](https://linux-hardware.org/?probe=6757c0e254) | Jun 14, 2021 |
| Dell          | Vostro 1220                 | Notebook    | [c951207d24](https://linux-hardware.org/?probe=c951207d24) | Jun 14, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | 82BG                        | Convertible | [37c092caaf](https://linux-hardware.org/?probe=37c092caaf) | Jun 14, 2021 |
| Lenovo        | ThinkPad E590 20NB0029UK    | Notebook    | [073912d946](https://linux-hardware.org/?probe=073912d946) | Jun 14, 2021 |
| ASRock        | B560M-ITX/ac                | Desktop     | [2284cea3c5](https://linux-hardware.org/?probe=2284cea3c5) | Jun 14, 2021 |
| Dell          | Latitude 3350               | Notebook    | [7fe0552d03](https://linux-hardware.org/?probe=7fe0552d03) | Jun 14, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [ad883d60a1](https://linux-hardware.org/?probe=ad883d60a1) | Jun 14, 2021 |
| Gigabyte      | B360M HD3                   | Desktop     | [666afe018d](https://linux-hardware.org/?probe=666afe018d) | Jun 14, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [c75be35c68](https://linux-hardware.org/?probe=c75be35c68) | Jun 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [cd400a52de](https://linux-hardware.org/?probe=cd400a52de) | Jun 14, 2021 |
| HP            | 18-5600br                   | Notebook    | [2fca89986a](https://linux-hardware.org/?probe=2fca89986a) | Jun 13, 2021 |
| Dell          | Studio 1735                 | Notebook    | [6cd1b25005](https://linux-hardware.org/?probe=6cd1b25005) | Jun 13, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [8ec235f1f1](https://linux-hardware.org/?probe=8ec235f1f1) | Jun 13, 2021 |
| VINGA         | Iron S140                   | Notebook    | [24d0a16acd](https://linux-hardware.org/?probe=24d0a16acd) | Jun 13, 2021 |
| ASUSTek       | P5WD2-Premium               | Desktop     | [35c95bde23](https://linux-hardware.org/?probe=35c95bde23) | Jun 13, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [0bc409e14c](https://linux-hardware.org/?probe=0bc409e14c) | Jun 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e73e3f7127](https://linux-hardware.org/?probe=e73e3f7127) | Jun 13, 2021 |
| HP            | Notebook                    | Notebook    | [f1263ec1fc](https://linux-hardware.org/?probe=f1263ec1fc) | Jun 13, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8b7af4e6fa](https://linux-hardware.org/?probe=8b7af4e6fa) | Jun 13, 2021 |
| MSI           | 970A-G46                    | Desktop     | [f7b1001ef1](https://linux-hardware.org/?probe=f7b1001ef1) | Jun 13, 2021 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [981954c88b](https://linux-hardware.org/?probe=981954c88b) | Jun 13, 2021 |
| ASUSTek       | M2A-VM                      | Desktop     | [e4fdaff878](https://linux-hardware.org/?probe=e4fdaff878) | Jun 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [2f73a02055](https://linux-hardware.org/?probe=2f73a02055) | Jun 12, 2021 |
| Gigabyte      | X99M-Gaming 5               | Desktop     | [10d40dc417](https://linux-hardware.org/?probe=10d40dc417) | Jun 12, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [611dfe93f6](https://linux-hardware.org/?probe=611dfe93f6) | Jun 12, 2021 |
| Dell          | 0020HJ A01                  | Server      | [decc1f46ba](https://linux-hardware.org/?probe=decc1f46ba) | Jun 12, 2021 |
| Timi          | TM1703                      | Notebook    | [61a3e61fd2](https://linux-hardware.org/?probe=61a3e61fd2) | Jun 12, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [6c64f10207](https://linux-hardware.org/?probe=6c64f10207) | Jun 12, 2021 |
| Gigabyte      | Z590 VISION G               | Desktop     | [c3b20ee137](https://linux-hardware.org/?probe=c3b20ee137) | Jun 12, 2021 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [805e3de988](https://linux-hardware.org/?probe=805e3de988) | Jun 11, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [bfb3ab2f44](https://linux-hardware.org/?probe=bfb3ab2f44) | Jun 11, 2021 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [df62a2a7e0](https://linux-hardware.org/?probe=df62a2a7e0) | Jun 11, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [5e9614f03e](https://linux-hardware.org/?probe=5e9614f03e) | Jun 11, 2021 |
| Chuwi         | HeroBook Pro+               | Notebook    | [978d937d24](https://linux-hardware.org/?probe=978d937d24) | Jun 11, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [e13e5ed99e](https://linux-hardware.org/?probe=e13e5ed99e) | Jun 11, 2021 |
| Dell          | Precision 5540              | Notebook    | [b21ffd09ff](https://linux-hardware.org/?probe=b21ffd09ff) | Jun 11, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [76a7098ea9](https://linux-hardware.org/?probe=76a7098ea9) | Jun 11, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [f5ba57634a](https://linux-hardware.org/?probe=f5ba57634a) | Jun 11, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ca868aa68c](https://linux-hardware.org/?probe=ca868aa68c) | Jun 11, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [aea5a6b230](https://linux-hardware.org/?probe=aea5a6b230) | Jun 10, 2021 |
| Acer          | AS5750G                     | Notebook    | [29a60b38c7](https://linux-hardware.org/?probe=29a60b38c7) | Jun 10, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [fa7bfd58f6](https://linux-hardware.org/?probe=fa7bfd58f6) | Jun 10, 2021 |
| Lenovo        | ThinkPad T480s 20L7001PF... | Notebook    | [b54604a23d](https://linux-hardware.org/?probe=b54604a23d) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [22e9ce0306](https://linux-hardware.org/?probe=22e9ce0306) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [4bc5bdf702](https://linux-hardware.org/?probe=4bc5bdf702) | Jun 10, 2021 |
| Apple         | Mac-F2268DAE                | All in one  | [85f2356b7b](https://linux-hardware.org/?probe=85f2356b7b) | Jun 10, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [5ac932248a](https://linux-hardware.org/?probe=5ac932248a) | Jun 10, 2021 |
| HP            | 158A                        | Desktop     | [1da50908cf](https://linux-hardware.org/?probe=1da50908cf) | Jun 10, 2021 |
| MSI           | MPG Z590 GAMING EDGE WIF... | Desktop     | [bab34a6951](https://linux-hardware.org/?probe=bab34a6951) | Jun 10, 2021 |
| Dell          | Inspiron One 2320           | All in one  | [49d911cdaa](https://linux-hardware.org/?probe=49d911cdaa) | Jun 10, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [301f84c1e8](https://linux-hardware.org/?probe=301f84c1e8) | Jun 09, 2021 |
| HP            | 843B                        | Desktop     | [95015678e1](https://linux-hardware.org/?probe=95015678e1) | Jun 09, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [ca026e3930](https://linux-hardware.org/?probe=ca026e3930) | Jun 09, 2021 |
| ASUSTek       | G11DF                       | Desktop     | [86408c43ff](https://linux-hardware.org/?probe=86408c43ff) | Jun 09, 2021 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [e8ea861c92](https://linux-hardware.org/?probe=e8ea861c92) | Jun 09, 2021 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [7607b3bb86](https://linux-hardware.org/?probe=7607b3bb86) | Jun 09, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [03514539b0](https://linux-hardware.org/?probe=03514539b0) | Jun 09, 2021 |
| MSI           | GS63 Stealth 8RE            | Notebook    | [a098121a4b](https://linux-hardware.org/?probe=a098121a4b) | Jun 09, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [54b62ad499](https://linux-hardware.org/?probe=54b62ad499) | Jun 08, 2021 |
| Acer          | Aspire A517-51P             | Notebook    | [0d9f4bfb3f](https://linux-hardware.org/?probe=0d9f4bfb3f) | Jun 08, 2021 |
| Acer          | Aspire V5-573G              | Notebook    | [4f2c1d3cf1](https://linux-hardware.org/?probe=4f2c1d3cf1) | Jun 08, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [89462c851a](https://linux-hardware.org/?probe=89462c851a) | Jun 08, 2021 |
| Gigabyte      | P43T-ES3G                   | Desktop     | [ab6924723a](https://linux-hardware.org/?probe=ab6924723a) | Jun 08, 2021 |
| HP            | Pavilion dv5                | Notebook    | [a3ec72db59](https://linux-hardware.org/?probe=a3ec72db59) | Jun 08, 2021 |
| ASUSTek       | F50Z                        | Notebook    | [cf099f4a72](https://linux-hardware.org/?probe=cf099f4a72) | Jun 08, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [c37379b181](https://linux-hardware.org/?probe=c37379b181) | Jun 08, 2021 |
| Acer          | EG43M                       | Desktop     | [4300da7d4b](https://linux-hardware.org/?probe=4300da7d4b) | Jun 08, 2021 |
| Acer          | EG43M                       | Desktop     | [c160d8848f](https://linux-hardware.org/?probe=c160d8848f) | Jun 08, 2021 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [cf5748e282](https://linux-hardware.org/?probe=cf5748e282) | Jun 07, 2021 |
| Dell          | Latitude E7440              | Notebook    | [5f0d57018e](https://linux-hardware.org/?probe=5f0d57018e) | Jun 07, 2021 |
| HP            | 0AA0h                       | Desktop     | [1231618175](https://linux-hardware.org/?probe=1231618175) | Jun 07, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [7c843291b5](https://linux-hardware.org/?probe=7c843291b5) | Jun 07, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [81034d3717](https://linux-hardware.org/?probe=81034d3717) | Jun 07, 2021 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [5ccbd0c9dc](https://linux-hardware.org/?probe=5ccbd0c9dc) | Jun 07, 2021 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [bf27f62c50](https://linux-hardware.org/?probe=bf27f62c50) | Jun 07, 2021 |
| Lenovo        | 100e 2nd Gen 82GJ           | Notebook    | [ce0d33750c](https://linux-hardware.org/?probe=ce0d33750c) | Jun 06, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [6f5aed374a](https://linux-hardware.org/?probe=6f5aed374a) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [8cf5dc5f75](https://linux-hardware.org/?probe=8cf5dc5f75) | Jun 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d243b289c3](https://linux-hardware.org/?probe=d243b289c3) | Jun 06, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [4081189cda](https://linux-hardware.org/?probe=4081189cda) | Jun 06, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [e192001666](https://linux-hardware.org/?probe=e192001666) | Jun 06, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f49f22766b](https://linux-hardware.org/?probe=f49f22766b) | Jun 05, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [1fe01a8a37](https://linux-hardware.org/?probe=1fe01a8a37) | Jun 05, 2021 |
| ASUSTek       | G72GX                       | Notebook    | [9445bda61c](https://linux-hardware.org/?probe=9445bda61c) | Jun 05, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [0f9baa3f5f](https://linux-hardware.org/?probe=0f9baa3f5f) | Jun 05, 2021 |
| ASUSTek       | P5WD2-Premium               | Desktop     | [3bf03e7263](https://linux-hardware.org/?probe=3bf03e7263) | Jun 05, 2021 |
| Acer          | Aspire 5742Z                | Notebook    | [89ae1206bb](https://linux-hardware.org/?probe=89ae1206bb) | Jun 05, 2021 |
| HP            | 1998                        | Desktop     | [68978259f3](https://linux-hardware.org/?probe=68978259f3) | Jun 05, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [f55a54325f](https://linux-hardware.org/?probe=f55a54325f) | Jun 05, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [24a4df74e1](https://linux-hardware.org/?probe=24a4df74e1) | Jun 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e7e821c4a7](https://linux-hardware.org/?probe=e7e821c4a7) | Jun 04, 2021 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [f8d06e3e17](https://linux-hardware.org/?probe=f8d06e3e17) | Jun 04, 2021 |
| HP            | 0AA0h                       | Desktop     | [ff231665d3](https://linux-hardware.org/?probe=ff231665d3) | Jun 04, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [62a56ec749](https://linux-hardware.org/?probe=62a56ec749) | Jun 04, 2021 |
| Medion        | MS-7621                     | Desktop     | [29ecaf9382](https://linux-hardware.org/?probe=29ecaf9382) | Jun 04, 2021 |
| MSI           | MS-7125                     | Desktop     | [66e6adf1ec](https://linux-hardware.org/?probe=66e6adf1ec) | Jun 04, 2021 |
| HP            | 1998                        | Desktop     | [617a033a6e](https://linux-hardware.org/?probe=617a033a6e) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f0133f78dc](https://linux-hardware.org/?probe=f0133f78dc) | Jun 04, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [fa65ebf8c6](https://linux-hardware.org/?probe=fa65ebf8c6) | Jun 04, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [c0e0de26cb](https://linux-hardware.org/?probe=c0e0de26cb) | Jun 04, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [cf9db1ce7a](https://linux-hardware.org/?probe=cf9db1ce7a) | Jun 04, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [99de24cb78](https://linux-hardware.org/?probe=99de24cb78) | Jun 04, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [fe512b6857](https://linux-hardware.org/?probe=fe512b6857) | Jun 04, 2021 |
| ASUSTek       | TUF H370-PRO GAMING         | Desktop     | [8f75ede232](https://linux-hardware.org/?probe=8f75ede232) | Jun 04, 2021 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [0126e8d357](https://linux-hardware.org/?probe=0126e8d357) | Jun 04, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [9237a7a68b](https://linux-hardware.org/?probe=9237a7a68b) | Jun 03, 2021 |
| HP            | ProBook 4430s               | Notebook    | [46588303b9](https://linux-hardware.org/?probe=46588303b9) | Jun 03, 2021 |
| HP            | ProBook 4430s               | Notebook    | [53188205ea](https://linux-hardware.org/?probe=53188205ea) | Jun 03, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d63b4a98c3](https://linux-hardware.org/?probe=d63b4a98c3) | Jun 03, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [7a364bc855](https://linux-hardware.org/?probe=7a364bc855) | Jun 03, 2021 |
| ECS           | H61H2-TI                    | All in one  | [35b729e93d](https://linux-hardware.org/?probe=35b729e93d) | Jun 03, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [6a9e537939](https://linux-hardware.org/?probe=6a9e537939) | Jun 03, 2021 |
| LG Electro... | 16Z90P-G.AA76G              | Notebook    | [7a64de799d](https://linux-hardware.org/?probe=7a64de799d) | Jun 03, 2021 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4a95259edd](https://linux-hardware.org/?probe=4a95259edd) | Jun 03, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [adeee24676](https://linux-hardware.org/?probe=adeee24676) | Jun 03, 2021 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [a434845c16](https://linux-hardware.org/?probe=a434845c16) | Jun 03, 2021 |
| HP            | 3397                        | Desktop     | [73e07145f4](https://linux-hardware.org/?probe=73e07145f4) | Jun 03, 2021 |
| HP            | Pavilion dv6                | Notebook    | [caa052636f](https://linux-hardware.org/?probe=caa052636f) | Jun 03, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [d53b1525ed](https://linux-hardware.org/?probe=d53b1525ed) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6b5f1170f9](https://linux-hardware.org/?probe=6b5f1170f9) | Jun 02, 2021 |
| ASUSTek       | M2N                         | Desktop     | [f5537f32f6](https://linux-hardware.org/?probe=f5537f32f6) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [e2389864db](https://linux-hardware.org/?probe=e2389864db) | Jun 02, 2021 |
| HP            | 3397                        | Desktop     | [1eba8aa1c1](https://linux-hardware.org/?probe=1eba8aa1c1) | Jun 02, 2021 |
| Dell          | Studio 1735                 | Notebook    | [b0485d3960](https://linux-hardware.org/?probe=b0485d3960) | Jun 02, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [8533dbc1de](https://linux-hardware.org/?probe=8533dbc1de) | Jun 02, 2021 |
| Dell          | Latitude 9520               | Notebook    | [10a4c770cf](https://linux-hardware.org/?probe=10a4c770cf) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [390085b056](https://linux-hardware.org/?probe=390085b056) | Jun 02, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [40545ef53f](https://linux-hardware.org/?probe=40545ef53f) | Jun 02, 2021 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [5cbd925314](https://linux-hardware.org/?probe=5cbd925314) | Jun 02, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [61b78ffc77](https://linux-hardware.org/?probe=61b78ffc77) | Jun 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [0271a8fd47](https://linux-hardware.org/?probe=0271a8fd47) | Jun 02, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [8daf7e0679](https://linux-hardware.org/?probe=8daf7e0679) | Jun 02, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [c31c1c69c6](https://linux-hardware.org/?probe=c31c1c69c6) | Jun 02, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [043730ad50](https://linux-hardware.org/?probe=043730ad50) | Jun 01, 2021 |
| HP            | ProBook 6560b               | Notebook    | [f9ee7c5367](https://linux-hardware.org/?probe=f9ee7c5367) | Jun 01, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [6c241e0b82](https://linux-hardware.org/?probe=6c241e0b82) | Jun 01, 2021 |
| Dell          | Inspiron 5370               | Notebook    | [51235b00db](https://linux-hardware.org/?probe=51235b00db) | Jun 01, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [75cd860063](https://linux-hardware.org/?probe=75cd860063) | Jun 01, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [36f36a1183](https://linux-hardware.org/?probe=36f36a1183) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [07aa0b9e2b](https://linux-hardware.org/?probe=07aa0b9e2b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [6b0fca64c4](https://linux-hardware.org/?probe=6b0fca64c4) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [4c650b1991](https://linux-hardware.org/?probe=4c650b1991) | Jun 01, 2021 |
| Fujitsu Si... | MS-7379VP                   | Desktop     | [e417b5e11e](https://linux-hardware.org/?probe=e417b5e11e) | Jun 01, 2021 |
| Fujitsu Si... | MS-7379VP                   | Desktop     | [ea4e7fc19e](https://linux-hardware.org/?probe=ea4e7fc19e) | Jun 01, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [09cc2aed35](https://linux-hardware.org/?probe=09cc2aed35) | May 31, 2021 |
| HP            | ProBook 6560b               | Notebook    | [523614fee6](https://linux-hardware.org/?probe=523614fee6) | May 31, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [a133667e3c](https://linux-hardware.org/?probe=a133667e3c) | May 31, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [2c283a99a8](https://linux-hardware.org/?probe=2c283a99a8) | May 31, 2021 |
| Acer          | Aspire XC-230               | Desktop     | [4594f040e1](https://linux-hardware.org/?probe=4594f040e1) | May 31, 2021 |
| HP            | Pavilion dv6                | Notebook    | [6ac306c0da](https://linux-hardware.org/?probe=6ac306c0da) | May 31, 2021 |
| Gigabyte      | Z590 VISION G               | Desktop     | [ea4492aeee](https://linux-hardware.org/?probe=ea4492aeee) | May 30, 2021 |
| Lenovo        | V560                        | Notebook    | [62053ae42b](https://linux-hardware.org/?probe=62053ae42b) | May 30, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | Notebook    | [d7f2524297](https://linux-hardware.org/?probe=d7f2524297) | May 30, 2021 |
| HCL Infosy... | HCL ME Laptop               | Notebook    | [5c17f36c61](https://linux-hardware.org/?probe=5c17f36c61) | May 30, 2021 |
| Lenovo        | ThinkPad T420 42366Y0       | Notebook    | [74547808d3](https://linux-hardware.org/?probe=74547808d3) | May 30, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [6dde896b4f](https://linux-hardware.org/?probe=6dde896b4f) | May 30, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [36ebf65d44](https://linux-hardware.org/?probe=36ebf65d44) | May 30, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5f8bfd5fbf](https://linux-hardware.org/?probe=5f8bfd5fbf) | May 30, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [44a0f0e4e2](https://linux-hardware.org/?probe=44a0f0e4e2) | May 30, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [d640900b8a](https://linux-hardware.org/?probe=d640900b8a) | May 29, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [f7942b9c3e](https://linux-hardware.org/?probe=f7942b9c3e) | May 29, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [9358c3afbf](https://linux-hardware.org/?probe=9358c3afbf) | May 29, 2021 |
| Lenovo        | ThinkPad T420 42366Y0       | Notebook    | [d36582d3d6](https://linux-hardware.org/?probe=d36582d3d6) | May 29, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [8fd027f078](https://linux-hardware.org/?probe=8fd027f078) | May 29, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [6e2fc02f05](https://linux-hardware.org/?probe=6e2fc02f05) | May 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [dfa6b5b067](https://linux-hardware.org/?probe=dfa6b5b067) | May 28, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [e2d1740f3a](https://linux-hardware.org/?probe=e2d1740f3a) | May 28, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [09499164b9](https://linux-hardware.org/?probe=09499164b9) | May 28, 2021 |
| ASUSTek       | X550LB                      | Notebook    | [21f1da73fd](https://linux-hardware.org/?probe=21f1da73fd) | May 28, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [654c105561](https://linux-hardware.org/?probe=654c105561) | May 28, 2021 |
| ASUSTek       | X550LB                      | Notebook    | [cc4245844a](https://linux-hardware.org/?probe=cc4245844a) | May 28, 2021 |
| Acer          | Aspire E5-553               | Notebook    | [70037bddcb](https://linux-hardware.org/?probe=70037bddcb) | May 27, 2021 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [ee109d9097](https://linux-hardware.org/?probe=ee109d9097) | May 27, 2021 |
| MSI           | 970A-G43                    | Desktop     | [07a86d218e](https://linux-hardware.org/?probe=07a86d218e) | May 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [4eac592912](https://linux-hardware.org/?probe=4eac592912) | May 27, 2021 |
| Dell          | Latitude 5520               | Notebook    | [f9327e8bb8](https://linux-hardware.org/?probe=f9327e8bb8) | May 27, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [f0450b570d](https://linux-hardware.org/?probe=f0450b570d) | May 27, 2021 |
| HP            | 81B4                        | Desktop     | [41311d3164](https://linux-hardware.org/?probe=41311d3164) | May 27, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [3cfa12f511](https://linux-hardware.org/?probe=3cfa12f511) | May 27, 2021 |
| Biostar       | A320MD PRO                  | Desktop     | [02e5d996c8](https://linux-hardware.org/?probe=02e5d996c8) | May 27, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [abd5d85c0e](https://linux-hardware.org/?probe=abd5d85c0e) | May 27, 2021 |
| Alienware     | M17xR4                      | Notebook    | [d3da4ef72c](https://linux-hardware.org/?probe=d3da4ef72c) | May 27, 2021 |
| Alienware     | M17xR4                      | Notebook    | [f534e321eb](https://linux-hardware.org/?probe=f534e321eb) | May 27, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [9f58a0f0bf](https://linux-hardware.org/?probe=9f58a0f0bf) | May 26, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [5c45dfb686](https://linux-hardware.org/?probe=5c45dfb686) | May 26, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [5177972753](https://linux-hardware.org/?probe=5177972753) | May 26, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [75eb0f8565](https://linux-hardware.org/?probe=75eb0f8565) | May 26, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [3b8ddca28e](https://linux-hardware.org/?probe=3b8ddca28e) | May 26, 2021 |
| MSI           | FM2-A85XMA-P33              | Desktop     | [0a01344d75](https://linux-hardware.org/?probe=0a01344d75) | May 26, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5ec38e0f3f](https://linux-hardware.org/?probe=5ec38e0f3f) | May 25, 2021 |
| MSI           | ZH77A-G41                   | Desktop     | [8755040ea2](https://linux-hardware.org/?probe=8755040ea2) | May 25, 2021 |
| MSI           | FM2-A85XMA-P33              | Desktop     | [0fabdb3aad](https://linux-hardware.org/?probe=0fabdb3aad) | May 25, 2021 |
| Lenovo        | ThinkPad T410 2537Z2J       | Notebook    | [d86d3e8984](https://linux-hardware.org/?probe=d86d3e8984) | May 25, 2021 |
| Apple         | MacBookPro8,3               | Notebook    | [c34278c355](https://linux-hardware.org/?probe=c34278c355) | May 25, 2021 |
| Dell          | G7 7500                     | Notebook    | [89f41d7487](https://linux-hardware.org/?probe=89f41d7487) | May 25, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [f9ed2cd1c9](https://linux-hardware.org/?probe=f9ed2cd1c9) | May 25, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [564ed5a39d](https://linux-hardware.org/?probe=564ed5a39d) | May 25, 2021 |
| MSI           | FM2-A85XMA-P33              | Desktop     | [40de3f5310](https://linux-hardware.org/?probe=40de3f5310) | May 25, 2021 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [d878c63fe4](https://linux-hardware.org/?probe=d878c63fe4) | May 24, 2021 |
| Apple         | MacBookAir5,2               | Notebook    | [ec1abd9485](https://linux-hardware.org/?probe=ec1abd9485) | May 24, 2021 |
| Sony          | VGN-AR850E                  | Notebook    | [e17fe551fb](https://linux-hardware.org/?probe=e17fe551fb) | May 24, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [2961088957](https://linux-hardware.org/?probe=2961088957) | May 24, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [f6856776e4](https://linux-hardware.org/?probe=f6856776e4) | May 24, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [08d0784b54](https://linux-hardware.org/?probe=08d0784b54) | May 24, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [91cf490677](https://linux-hardware.org/?probe=91cf490677) | May 24, 2021 |
| Dell          | G5 5587                     | Notebook    | [65c1600593](https://linux-hardware.org/?probe=65c1600593) | May 24, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [2bbea8f317](https://linux-hardware.org/?probe=2bbea8f317) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | Desktop     | [02a90f300e](https://linux-hardware.org/?probe=02a90f300e) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | Desktop     | [91bdc4a9a0](https://linux-hardware.org/?probe=91bdc4a9a0) | May 24, 2021 |
| Acer          | TravelMate P215-53          | Notebook    | [dc89b4797f](https://linux-hardware.org/?probe=dc89b4797f) | May 24, 2021 |
| Acer          | Aspire one 1-431            | Notebook    | [db306fa1f7](https://linux-hardware.org/?probe=db306fa1f7) | May 24, 2021 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [5f6f9a1c6c](https://linux-hardware.org/?probe=5f6f9a1c6c) | May 24, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [6fbef63c17](https://linux-hardware.org/?probe=6fbef63c17) | May 23, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [86060380c8](https://linux-hardware.org/?probe=86060380c8) | May 23, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [33ba80d2ae](https://linux-hardware.org/?probe=33ba80d2ae) | May 23, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [5be7a59bcd](https://linux-hardware.org/?probe=5be7a59bcd) | May 23, 2021 |
| Acer          | TravelMate P215-53          | Notebook    | [18ea2a888a](https://linux-hardware.org/?probe=18ea2a888a) | May 23, 2021 |
| System76      | Galago Pro                  | Notebook    | [7bc86eb366](https://linux-hardware.org/?probe=7bc86eb366) | May 23, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [da126fa410](https://linux-hardware.org/?probe=da126fa410) | May 23, 2021 |
| ASUSTek       | ET2700I                     | Desktop     | [a3edd93ada](https://linux-hardware.org/?probe=a3edd93ada) | May 23, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [97dbd7a2d0](https://linux-hardware.org/?probe=97dbd7a2d0) | May 23, 2021 |
| Microsoft     | Surface Book                | Tablet      | [0e1d0b8d70](https://linux-hardware.org/?probe=0e1d0b8d70) | May 23, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [8a8a2bded7](https://linux-hardware.org/?probe=8a8a2bded7) | May 23, 2021 |
| Dell          | Inspiron 7706 2n1           | Convertible | [5b40e331b3](https://linux-hardware.org/?probe=5b40e331b3) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [61934ee4fc](https://linux-hardware.org/?probe=61934ee4fc) | May 22, 2021 |
| HP            | Pavilion dv5                | Notebook    | [97c2972e03](https://linux-hardware.org/?probe=97c2972e03) | May 22, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [b3da27422d](https://linux-hardware.org/?probe=b3da27422d) | May 22, 2021 |
| Dell          | 0RK936                      | Desktop     | [27b342b50b](https://linux-hardware.org/?probe=27b342b50b) | May 22, 2021 |
| Dell          | 0RK936                      | Desktop     | [6c12a5edf2](https://linux-hardware.org/?probe=6c12a5edf2) | May 22, 2021 |
| ASRock        | X370 Gaming K4              | Desktop     | [4945bb80f6](https://linux-hardware.org/?probe=4945bb80f6) | May 22, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [c781b981de](https://linux-hardware.org/?probe=c781b981de) | May 22, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [c458b6d1ca](https://linux-hardware.org/?probe=c458b6d1ca) | May 21, 2021 |
| Unknown       | T3 MRD                      | Notebook    | [1c16d2db6c](https://linux-hardware.org/?probe=1c16d2db6c) | May 21, 2021 |
| Lenovo        | ThinkPad T61 6463WCH        | Notebook    | [e1b3b6e090](https://linux-hardware.org/?probe=e1b3b6e090) | May 21, 2021 |
| Sony          | VGN-NS21Z_S                 | Notebook    | [4c412bd16f](https://linux-hardware.org/?probe=4c412bd16f) | May 21, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [0e3415879f](https://linux-hardware.org/?probe=0e3415879f) | May 21, 2021 |
| Dell          | Latitude 5410               | Notebook    | [6b5502593e](https://linux-hardware.org/?probe=6b5502593e) | May 21, 2021 |
| HP            | Spectre Pro x360 G2         | Notebook    | [236efc033e](https://linux-hardware.org/?probe=236efc033e) | May 21, 2021 |
| Dell          | Precision 5530              | Notebook    | [a5c63380d6](https://linux-hardware.org/?probe=a5c63380d6) | May 21, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [eb4531374e](https://linux-hardware.org/?probe=eb4531374e) | May 21, 2021 |
| Razer         | Blade Stealth               | Notebook    | [274e57be67](https://linux-hardware.org/?probe=274e57be67) | May 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [bb56c72ca2](https://linux-hardware.org/?probe=bb56c72ca2) | May 20, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [d63952115c](https://linux-hardware.org/?probe=d63952115c) | May 20, 2021 |
| HP            | 15                          | Notebook    | [814d85cf91](https://linux-hardware.org/?probe=814d85cf91) | May 20, 2021 |
| HP            | 350 G1                      | Notebook    | [949ae1ce88](https://linux-hardware.org/?probe=949ae1ce88) | May 20, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [efdb159b87](https://linux-hardware.org/?probe=efdb159b87) | May 20, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [60450a65b2](https://linux-hardware.org/?probe=60450a65b2) | May 20, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [6d6ff7b4d8](https://linux-hardware.org/?probe=6d6ff7b4d8) | May 20, 2021 |
| Acer          | Spin SP314-54N              | Convertible | [898f69117c](https://linux-hardware.org/?probe=898f69117c) | May 20, 2021 |
| Acer          | Aspire XC-230               | Desktop     | [31e0dabfb9](https://linux-hardware.org/?probe=31e0dabfb9) | May 20, 2021 |
| Fujitsu       | LIFEBOOK T730               | Notebook    | [f220f9ac45](https://linux-hardware.org/?probe=f220f9ac45) | May 20, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [42d9ebb57e](https://linux-hardware.org/?probe=42d9ebb57e) | May 20, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [c973055db8](https://linux-hardware.org/?probe=c973055db8) | May 20, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [6331748487](https://linux-hardware.org/?probe=6331748487) | May 20, 2021 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [ed2a5f47c6](https://linux-hardware.org/?probe=ed2a5f47c6) | May 20, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [30a5ddc9a4](https://linux-hardware.org/?probe=30a5ddc9a4) | May 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [013af3c5de](https://linux-hardware.org/?probe=013af3c5de) | May 19, 2021 |
| ASUSTek       | GL502VSK                    | Notebook    | [577af42985](https://linux-hardware.org/?probe=577af42985) | May 19, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [99d22d0422](https://linux-hardware.org/?probe=99d22d0422) | May 19, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a42bee6110](https://linux-hardware.org/?probe=a42bee6110) | May 19, 2021 |
| HP            | 802F                        | Desktop     | [f01cdeed88](https://linux-hardware.org/?probe=f01cdeed88) | May 19, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [a1b3c9d405](https://linux-hardware.org/?probe=a1b3c9d405) | May 19, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [3814598db5](https://linux-hardware.org/?probe=3814598db5) | May 19, 2021 |
| HP            | Pavilion 15                 | Notebook    | [c689ad926b](https://linux-hardware.org/?probe=c689ad926b) | May 19, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [bb0d60af3d](https://linux-hardware.org/?probe=bb0d60af3d) | May 19, 2021 |
| Notebook      | PCX0DX                      | Notebook    | [4556010665](https://linux-hardware.org/?probe=4556010665) | May 18, 2021 |
| Toshiba       | PORTEGE Z930                | Notebook    | [e006b8bf83](https://linux-hardware.org/?probe=e006b8bf83) | May 18, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [0548f9650b](https://linux-hardware.org/?probe=0548f9650b) | May 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1beabcf9d0](https://linux-hardware.org/?probe=1beabcf9d0) | May 18, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [d44e900d30](https://linux-hardware.org/?probe=d44e900d30) | May 18, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [8ab1ba226d](https://linux-hardware.org/?probe=8ab1ba226d) | May 18, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [12ffaaefb1](https://linux-hardware.org/?probe=12ffaaefb1) | May 18, 2021 |
| Dell          | 0KR7G8 A00                  | All in one  | [20f6e2b8de](https://linux-hardware.org/?probe=20f6e2b8de) | May 18, 2021 |
| Dell          | 0RK936                      | Desktop     | [c3c620590f](https://linux-hardware.org/?probe=c3c620590f) | May 18, 2021 |
| Acer          | Spin SP314-54N              | Convertible | [c617717583](https://linux-hardware.org/?probe=c617717583) | May 18, 2021 |
| Acer          | Spin SP314-54N              | Convertible | [71fc5d4b23](https://linux-hardware.org/?probe=71fc5d4b23) | May 18, 2021 |
| ASRock        | B550 Extreme4               | Desktop     | [38fe00e843](https://linux-hardware.org/?probe=38fe00e843) | May 18, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [b646c2612a](https://linux-hardware.org/?probe=b646c2612a) | May 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [de0186f460](https://linux-hardware.org/?probe=de0186f460) | May 18, 2021 |
| ASUSTek       | X550LB                      | Notebook    | [3dc677388a](https://linux-hardware.org/?probe=3dc677388a) | May 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [4cb87906e4](https://linux-hardware.org/?probe=4cb87906e4) | May 18, 2021 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [b6812b6242](https://linux-hardware.org/?probe=b6812b6242) | May 17, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [1bfce84c69](https://linux-hardware.org/?probe=1bfce84c69) | May 17, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [deb906b69f](https://linux-hardware.org/?probe=deb906b69f) | May 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [7724221aba](https://linux-hardware.org/?probe=7724221aba) | May 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [0e9e4151e9](https://linux-hardware.org/?probe=0e9e4151e9) | May 17, 2021 |
| Dell          | 0VHRW1 A03                  | Desktop     | [1ac850d5b7](https://linux-hardware.org/?probe=1ac850d5b7) | May 17, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ed92840007](https://linux-hardware.org/?probe=ed92840007) | May 17, 2021 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [6af6b1aa99](https://linux-hardware.org/?probe=6af6b1aa99) | May 17, 2021 |
| Acer          | Aspire E3-112               | Notebook    | [fed9ba4c7d](https://linux-hardware.org/?probe=fed9ba4c7d) | May 16, 2021 |
| Lenovo        | 3701 SDK0R32862 WIN 3258... | All in one  | [3aab28e1e4](https://linux-hardware.org/?probe=3aab28e1e4) | May 16, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [65a3c1a830](https://linux-hardware.org/?probe=65a3c1a830) | May 16, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [0c0dec114b](https://linux-hardware.org/?probe=0c0dec114b) | May 16, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [5c67466a7e](https://linux-hardware.org/?probe=5c67466a7e) | May 16, 2021 |
| MSI           | G41M-P25                    | Desktop     | [57d1c4dafa](https://linux-hardware.org/?probe=57d1c4dafa) | May 16, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [7694ca4dfd](https://linux-hardware.org/?probe=7694ca4dfd) | May 16, 2021 |
| Dell          | 051FJ8 A02                  | Desktop     | [dd8dc2d85a](https://linux-hardware.org/?probe=dd8dc2d85a) | May 16, 2021 |
| Dell          | XPS M1530                   | Notebook    | [19be0f2492](https://linux-hardware.org/?probe=19be0f2492) | May 16, 2021 |
| Dell          | Precision 3551              | Notebook    | [a080388baa](https://linux-hardware.org/?probe=a080388baa) | May 16, 2021 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [b8e9ac2eb7](https://linux-hardware.org/?probe=b8e9ac2eb7) | May 16, 2021 |
| Dell          | Precision 3551              | Notebook    | [f9f9852b96](https://linux-hardware.org/?probe=f9f9852b96) | May 16, 2021 |
| Dell          | Latitude 5285               | Notebook    | [c5396b5734](https://linux-hardware.org/?probe=c5396b5734) | May 16, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [00a90e02e9](https://linux-hardware.org/?probe=00a90e02e9) | May 15, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [ef62ad9c4b](https://linux-hardware.org/?probe=ef62ad9c4b) | May 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00a8ed533c](https://linux-hardware.org/?probe=00a8ed533c) | May 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [14b8295348](https://linux-hardware.org/?probe=14b8295348) | May 15, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [30fa3fc2c7](https://linux-hardware.org/?probe=30fa3fc2c7) | May 15, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [637ea140ae](https://linux-hardware.org/?probe=637ea140ae) | May 15, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [0d737eab8c](https://linux-hardware.org/?probe=0d737eab8c) | May 15, 2021 |
| Medion        | MS-7621                     | Desktop     | [9d7d398cc1](https://linux-hardware.org/?probe=9d7d398cc1) | May 15, 2021 |
| Dell          | Latitude 3350               | Notebook    | [f4e6b7cf7f](https://linux-hardware.org/?probe=f4e6b7cf7f) | May 15, 2021 |
| Positivo      | C14CR21TV                   | Notebook    | [8af930f7e1](https://linux-hardware.org/?probe=8af930f7e1) | May 15, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [bc393b7046](https://linux-hardware.org/?probe=bc393b7046) | May 15, 2021 |
| Lenovo        | G40-70 80GA                 | Notebook    | [619b20ccfb](https://linux-hardware.org/?probe=619b20ccfb) | May 15, 2021 |
| Lenovo        | G40-70 80GA                 | Notebook    | [c674fa597f](https://linux-hardware.org/?probe=c674fa597f) | May 15, 2021 |
| HP            | 1000                        | Notebook    | [d23f6c89ad](https://linux-hardware.org/?probe=d23f6c89ad) | May 15, 2021 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [ef3422dd2d](https://linux-hardware.org/?probe=ef3422dd2d) | May 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [2c887c5d3f](https://linux-hardware.org/?probe=2c887c5d3f) | May 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [aca4c8c6cf](https://linux-hardware.org/?probe=aca4c8c6cf) | May 14, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [74ec4fcd5b](https://linux-hardware.org/?probe=74ec4fcd5b) | May 14, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [b3d306266e](https://linux-hardware.org/?probe=b3d306266e) | May 14, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [5310f8c130](https://linux-hardware.org/?probe=5310f8c130) | May 14, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [b39ddf3718](https://linux-hardware.org/?probe=b39ddf3718) | May 14, 2021 |
| HP            | G62                         | Notebook    | [aec231d673](https://linux-hardware.org/?probe=aec231d673) | May 14, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [df405076a1](https://linux-hardware.org/?probe=df405076a1) | May 14, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [fcbfa1c448](https://linux-hardware.org/?probe=fcbfa1c448) | May 14, 2021 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [a44fcb1c39](https://linux-hardware.org/?probe=a44fcb1c39) | May 13, 2021 |
| Sony          | VGN-AR51SU                  | Notebook    | [6d72715029](https://linux-hardware.org/?probe=6d72715029) | May 13, 2021 |
| Dell          | Latitude 3350               | Notebook    | [bb64b2df5c](https://linux-hardware.org/?probe=bb64b2df5c) | May 13, 2021 |
| ASUSTek       | PRIME X299-A                | Desktop     | [d5cdc97c3b](https://linux-hardware.org/?probe=d5cdc97c3b) | May 13, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [20a2c142bf](https://linux-hardware.org/?probe=20a2c142bf) | May 13, 2021 |
| Medion        | E631X Ver                   | Desktop     | [872b2a2dc9](https://linux-hardware.org/?probe=872b2a2dc9) | May 13, 2021 |
| Insignia      | NS-P11W7100                 | Notebook    | [6bb54d0349](https://linux-hardware.org/?probe=6bb54d0349) | May 13, 2021 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | Notebook    | [9f56d64c9d](https://linux-hardware.org/?probe=9f56d64c9d) | May 13, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [b8108b310a](https://linux-hardware.org/?probe=b8108b310a) | May 13, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [c596247722](https://linux-hardware.org/?probe=c596247722) | May 13, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [097abb2630](https://linux-hardware.org/?probe=097abb2630) | May 13, 2021 |
| HP            | 1000                        | Notebook    | [a1ff0a7b3d](https://linux-hardware.org/?probe=a1ff0a7b3d) | May 13, 2021 |
| HP            | 1000                        | Notebook    | [4bbe06ec7a](https://linux-hardware.org/?probe=4bbe06ec7a) | May 13, 2021 |
| MSI           | Prestige 15 A11SCS          | Notebook    | [f892f92e65](https://linux-hardware.org/?probe=f892f92e65) | May 12, 2021 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [2efd6e26e3](https://linux-hardware.org/?probe=2efd6e26e3) | May 12, 2021 |
| Dell          | Precision M4500             | Notebook    | [784b8e3db4](https://linux-hardware.org/?probe=784b8e3db4) | May 11, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [cf41b106cb](https://linux-hardware.org/?probe=cf41b106cb) | May 11, 2021 |
| HP            | EliteBook 850 G4            | Notebook    | [2502c3d7e7](https://linux-hardware.org/?probe=2502c3d7e7) | May 11, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [63c11ce610](https://linux-hardware.org/?probe=63c11ce610) | May 11, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | Notebook    | [2543210bfd](https://linux-hardware.org/?probe=2543210bfd) | May 11, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [09ca2a6a53](https://linux-hardware.org/?probe=09ca2a6a53) | May 10, 2021 |
| Apple         | MacBookPro8,3               | Notebook    | [0537199c9f](https://linux-hardware.org/?probe=0537199c9f) | May 10, 2021 |
| Sony          | VPCCW2S8E                   | Notebook    | [4398b323b3](https://linux-hardware.org/?probe=4398b323b3) | May 10, 2021 |
| Sony          | VPCCW2S8E                   | Notebook    | [eba79cc54f](https://linux-hardware.org/?probe=eba79cc54f) | May 10, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9cbaa26773](https://linux-hardware.org/?probe=9cbaa26773) | May 10, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5ca33ceca6](https://linux-hardware.org/?probe=5ca33ceca6) | May 10, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [fc4143b244](https://linux-hardware.org/?probe=fc4143b244) | May 10, 2021 |
| Acer          | Aspire XC-230               | Desktop     | [73c9019a57](https://linux-hardware.org/?probe=73c9019a57) | May 10, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [71b5e3c825](https://linux-hardware.org/?probe=71b5e3c825) | May 10, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8afdfe2827](https://linux-hardware.org/?probe=8afdfe2827) | May 10, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [3d2e6af706](https://linux-hardware.org/?probe=3d2e6af706) | May 10, 2021 |
| ASUSTek       | M2A-VM                      | Desktop     | [425df4a110](https://linux-hardware.org/?probe=425df4a110) | May 09, 2021 |
| Acer          | Aspire A315-33              | Notebook    | [b50018b47b](https://linux-hardware.org/?probe=b50018b47b) | May 09, 2021 |
| Dell          | Vostro 7500                 | Notebook    | [6041d49bff](https://linux-hardware.org/?probe=6041d49bff) | May 09, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [5da4e125b2](https://linux-hardware.org/?probe=5da4e125b2) | May 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [bdef07b464](https://linux-hardware.org/?probe=bdef07b464) | May 09, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [511e08ef09](https://linux-hardware.org/?probe=511e08ef09) | May 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [cf55e0e340](https://linux-hardware.org/?probe=cf55e0e340) | May 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [287b32a385](https://linux-hardware.org/?probe=287b32a385) | May 09, 2021 |
| HP            | Laptop 17-bs0xx             | Notebook    | [e6623d7b8e](https://linux-hardware.org/?probe=e6623d7b8e) | May 09, 2021 |
| Dell          | 0YXT71 A00                  | Desktop     | [0b1b291060](https://linux-hardware.org/?probe=0b1b291060) | May 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f829fcf4ae](https://linux-hardware.org/?probe=f829fcf4ae) | May 08, 2021 |
| MSI           | H61M-P20/W8                 | Desktop     | [ca302c374f](https://linux-hardware.org/?probe=ca302c374f) | May 08, 2021 |
| MSI           | H61M-P20/W8                 | Desktop     | [e68f90acd5](https://linux-hardware.org/?probe=e68f90acd5) | May 08, 2021 |
| HP            | 09F8h                       | Desktop     | [88de1576e5](https://linux-hardware.org/?probe=88de1576e5) | May 08, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [85058201a1](https://linux-hardware.org/?probe=85058201a1) | May 08, 2021 |
| Lenovo        | E41-25 81FS                 | Notebook    | [4ccf4659d4](https://linux-hardware.org/?probe=4ccf4659d4) | May 08, 2021 |
| Lenovo        | E41-25 81FS                 | Notebook    | [532af26481](https://linux-hardware.org/?probe=532af26481) | May 08, 2021 |
| Acer          | Veriton X490G               | Desktop     | [a729505133](https://linux-hardware.org/?probe=a729505133) | May 08, 2021 |
| ASRock        | X99 Extreme4                | Desktop     | [22b924723a](https://linux-hardware.org/?probe=22b924723a) | May 08, 2021 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [7d79c9afb9](https://linux-hardware.org/?probe=7d79c9afb9) | May 08, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | Notebook    | [adfdb43f0b](https://linux-hardware.org/?probe=adfdb43f0b) | May 08, 2021 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [2869638c1b](https://linux-hardware.org/?probe=2869638c1b) | May 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [b7e4895fd8](https://linux-hardware.org/?probe=b7e4895fd8) | May 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [9d937a5244](https://linux-hardware.org/?probe=9d937a5244) | May 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [089fa466bc](https://linux-hardware.org/?probe=089fa466bc) | May 07, 2021 |
| HP            | Laptop 17-bs0xx             | Notebook    | [86f4c24f8f](https://linux-hardware.org/?probe=86f4c24f8f) | May 07, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [a65a4354b9](https://linux-hardware.org/?probe=a65a4354b9) | May 07, 2021 |
| HP            | 09F8h                       | Desktop     | [9d6ad317f4](https://linux-hardware.org/?probe=9d6ad317f4) | May 07, 2021 |
| MSI           | H410M PRO                   | Desktop     | [68104520c5](https://linux-hardware.org/?probe=68104520c5) | May 06, 2021 |
| ASUSTek       | K52F                        | Notebook    | [871f4c23c5](https://linux-hardware.org/?probe=871f4c23c5) | May 06, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8219a4a9ac](https://linux-hardware.org/?probe=8219a4a9ac) | May 06, 2021 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [96ed551beb](https://linux-hardware.org/?probe=96ed551beb) | May 06, 2021 |
| MSI           | H270M BAZOOKA               | Desktop     | [c2fdd4a7da](https://linux-hardware.org/?probe=c2fdd4a7da) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [34b008d2a3](https://linux-hardware.org/?probe=34b008d2a3) | May 06, 2021 |
| Samsung       | RC530/RC730                 | Notebook    | [479ca4a221](https://linux-hardware.org/?probe=479ca4a221) | May 06, 2021 |
| Samsung       | RC530/RC730                 | Notebook    | [96541e6169](https://linux-hardware.org/?probe=96541e6169) | May 06, 2021 |
| HP            | ZBook 15                    | Notebook    | [ccdf2eebed](https://linux-hardware.org/?probe=ccdf2eebed) | May 06, 2021 |
| HP            | ZBook 15                    | Notebook    | [702b924ad3](https://linux-hardware.org/?probe=702b924ad3) | May 06, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [bf80de79c3](https://linux-hardware.org/?probe=bf80de79c3) | May 06, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [a0fec588d6](https://linux-hardware.org/?probe=a0fec588d6) | May 06, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| Gigabyte      | B75M-HD3                    | Desktop     | [cff51c85da](https://linux-hardware.org/?probe=cff51c85da) | May 06, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [ac97a78679](https://linux-hardware.org/?probe=ac97a78679) | May 06, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [7aa400cdbf](https://linux-hardware.org/?probe=7aa400cdbf) | May 06, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [a8ae42440e](https://linux-hardware.org/?probe=a8ae42440e) | May 06, 2021 |
| Intel         | NUC8i5INB K29935-404        | Mini pc     | [45b14891d4](https://linux-hardware.org/?probe=45b14891d4) | May 06, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [61c9e8ca48](https://linux-hardware.org/?probe=61c9e8ca48) | May 05, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [25ad87e22b](https://linux-hardware.org/?probe=25ad87e22b) | May 05, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [5a4f35e056](https://linux-hardware.org/?probe=5a4f35e056) | May 05, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [bbc8131c67](https://linux-hardware.org/?probe=bbc8131c67) | May 05, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [dc28c67e94](https://linux-hardware.org/?probe=dc28c67e94) | May 05, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [48d1110975](https://linux-hardware.org/?probe=48d1110975) | May 05, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [9b72abe5d8](https://linux-hardware.org/?probe=9b72abe5d8) | May 05, 2021 |
| Standard      | Unknown                     | Notebook    | [e9a891227f](https://linux-hardware.org/?probe=e9a891227f) | May 05, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [8c61d2500f](https://linux-hardware.org/?probe=8c61d2500f) | May 04, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [45f40c1d2b](https://linux-hardware.org/?probe=45f40c1d2b) | May 04, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [64221d8f8a](https://linux-hardware.org/?probe=64221d8f8a) | May 04, 2021 |
| HP            | 3647h                       | Desktop     | [bd39210291](https://linux-hardware.org/?probe=bd39210291) | May 04, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e3bb17dee5](https://linux-hardware.org/?probe=e3bb17dee5) | May 04, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [f42aef173c](https://linux-hardware.org/?probe=f42aef173c) | May 04, 2021 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [8b524de561](https://linux-hardware.org/?probe=8b524de561) | May 04, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [c89b28e2f3](https://linux-hardware.org/?probe=c89b28e2f3) | May 03, 2021 |
| Acer          | Predator G9-793             | Notebook    | [90b04b667a](https://linux-hardware.org/?probe=90b04b667a) | May 03, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [b852cc3b14](https://linux-hardware.org/?probe=b852cc3b14) | May 03, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [43ecd6539f](https://linux-hardware.org/?probe=43ecd6539f) | May 03, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6fbe833fac](https://linux-hardware.org/?probe=6fbe833fac) | May 02, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [dc246b5e6d](https://linux-hardware.org/?probe=dc246b5e6d) | May 02, 2021 |
| System76      | Galago Pro                  | Notebook    | [0081dd52a5](https://linux-hardware.org/?probe=0081dd52a5) | May 02, 2021 |
| Lenovo        | ThinkPad T470 20HES1HD01    | Notebook    | [4eb1086713](https://linux-hardware.org/?probe=4eb1086713) | May 02, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [aebf5d33a4](https://linux-hardware.org/?probe=aebf5d33a4) | May 02, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [9e7bc88973](https://linux-hardware.org/?probe=9e7bc88973) | May 02, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [6223ea92f1](https://linux-hardware.org/?probe=6223ea92f1) | May 02, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [8c78374db7](https://linux-hardware.org/?probe=8c78374db7) | May 02, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP            | ProBook 6460b               | Notebook    | [24fab4aa05](https://linux-hardware.org/?probe=24fab4aa05) | May 02, 2021 |
| HUAWEI        | WRTB-WXX9                   | Notebook    | [f9ceb7c523](https://linux-hardware.org/?probe=f9ceb7c523) | May 02, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [009abcd381](https://linux-hardware.org/?probe=009abcd381) | May 02, 2021 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [15c0f31b91](https://linux-hardware.org/?probe=15c0f31b91) | May 02, 2021 |
| SYWZ          | S210H Series                | Desktop     | [746808e2c5](https://linux-hardware.org/?probe=746808e2c5) | May 01, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [315bc839ec](https://linux-hardware.org/?probe=315bc839ec) | May 01, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [9eaacbadec](https://linux-hardware.org/?probe=9eaacbadec) | May 01, 2021 |
| Sony          | VGN-FZ11S                   | Notebook    | [bd472575f4](https://linux-hardware.org/?probe=bd472575f4) | May 01, 2021 |
| Lenovo        | ThinkPad E480 20KN0061RT    | Notebook    | [6d6d654a5a](https://linux-hardware.org/?probe=6d6d654a5a) | May 01, 2021 |
| Lenovo        | ThinkPad E470 20H2S00700    | Notebook    | [cc35722c1f](https://linux-hardware.org/?probe=cc35722c1f) | May 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [d0838b99d8](https://linux-hardware.org/?probe=d0838b99d8) | May 01, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [af5179a1f9](https://linux-hardware.org/?probe=af5179a1f9) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [1a9b2e458a](https://linux-hardware.org/?probe=1a9b2e458a) | Apr 30, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [5035e203bb](https://linux-hardware.org/?probe=5035e203bb) | Apr 30, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [7d6a70d93f](https://linux-hardware.org/?probe=7d6a70d93f) | Apr 30, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [29206c06a9](https://linux-hardware.org/?probe=29206c06a9) | Apr 30, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [0b4d7ca209](https://linux-hardware.org/?probe=0b4d7ca209) | Apr 30, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [62b7ee34f7](https://linux-hardware.org/?probe=62b7ee34f7) | Apr 30, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [c3243b55ef](https://linux-hardware.org/?probe=c3243b55ef) | Apr 29, 2021 |
| Alienware     | 0TYR0X A00                  | Desktop     | [9f3fe00e5c](https://linux-hardware.org/?probe=9f3fe00e5c) | Apr 29, 2021 |
| Alienware     | 0TYR0X A00                  | Desktop     | [41fd34d001](https://linux-hardware.org/?probe=41fd34d001) | Apr 29, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3d8d1682dd](https://linux-hardware.org/?probe=3d8d1682dd) | Apr 29, 2021 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [48c0082d7e](https://linux-hardware.org/?probe=48c0082d7e) | Apr 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ab676ac56d](https://linux-hardware.org/?probe=ab676ac56d) | Apr 29, 2021 |
| Dell          | Inspiron 7791 2n1           | Convertible | [247867f57e](https://linux-hardware.org/?probe=247867f57e) | Apr 29, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [34b91a88a8](https://linux-hardware.org/?probe=34b91a88a8) | Apr 28, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [61c335bd08](https://linux-hardware.org/?probe=61c335bd08) | Apr 28, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [2b9b5faf20](https://linux-hardware.org/?probe=2b9b5faf20) | Apr 28, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [febcf69966](https://linux-hardware.org/?probe=febcf69966) | Apr 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [8e8858711b](https://linux-hardware.org/?probe=8e8858711b) | Apr 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [2c4d248451](https://linux-hardware.org/?probe=2c4d248451) | Apr 28, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | Notebook    | [56406a43bd](https://linux-hardware.org/?probe=56406a43bd) | Apr 28, 2021 |
| MSI           | GL75 Leopard 10SDR          | Notebook    | [458deed3d3](https://linux-hardware.org/?probe=458deed3d3) | Apr 27, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [acd54357f7](https://linux-hardware.org/?probe=acd54357f7) | Apr 27, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [325c441d47](https://linux-hardware.org/?probe=325c441d47) | Apr 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [b3217892ed](https://linux-hardware.org/?probe=b3217892ed) | Apr 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [ec5b0541a2](https://linux-hardware.org/?probe=ec5b0541a2) | Apr 27, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [1fe4e3b8f2](https://linux-hardware.org/?probe=1fe4e3b8f2) | Apr 27, 2021 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [8638d59270](https://linux-hardware.org/?probe=8638d59270) | Apr 27, 2021 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [f729b14cca](https://linux-hardware.org/?probe=f729b14cca) | Apr 27, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [5a9b9278df](https://linux-hardware.org/?probe=5a9b9278df) | Apr 26, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [cd9f6f91af](https://linux-hardware.org/?probe=cd9f6f91af) | Apr 26, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [604a50766b](https://linux-hardware.org/?probe=604a50766b) | Apr 26, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [5ae67a0ac5](https://linux-hardware.org/?probe=5ae67a0ac5) | Apr 26, 2021 |
| ASUSTek       | M4N78 SE                    | Desktop     | [b4d731ce7b](https://linux-hardware.org/?probe=b4d731ce7b) | Apr 26, 2021 |
| ASUSTek       | M4N78 SE                    | Desktop     | [7a99053f1f](https://linux-hardware.org/?probe=7a99053f1f) | Apr 26, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [266fb405d7](https://linux-hardware.org/?probe=266fb405d7) | Apr 26, 2021 |
| Toshiba       | Satellite A350              | Notebook    | [5da06fd6b1](https://linux-hardware.org/?probe=5da06fd6b1) | Apr 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [bf2ec3a69c](https://linux-hardware.org/?probe=bf2ec3a69c) | Apr 26, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [0609ea696c](https://linux-hardware.org/?probe=0609ea696c) | Apr 26, 2021 |
| Biostar       | A880GU3                     | Desktop     | [7c3cadb886](https://linux-hardware.org/?probe=7c3cadb886) | Apr 26, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [511562a9df](https://linux-hardware.org/?probe=511562a9df) | Apr 26, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [2d81b38ea4](https://linux-hardware.org/?probe=2d81b38ea4) | Apr 26, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [9e090254cd](https://linux-hardware.org/?probe=9e090254cd) | Apr 26, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [c1b51f4738](https://linux-hardware.org/?probe=c1b51f4738) | Apr 25, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [c515859de4](https://linux-hardware.org/?probe=c515859de4) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [0bcc333251](https://linux-hardware.org/?probe=0bcc333251) | Apr 25, 2021 |
| MSI           | Z77A-GD55                   | Desktop     | [4ae20b53ca](https://linux-hardware.org/?probe=4ae20b53ca) | Apr 25, 2021 |
| Lenovo        | ThinkPad T410 2537FP3       | Notebook    | [ae38a32169](https://linux-hardware.org/?probe=ae38a32169) | Apr 25, 2021 |
| Lenovo        | ThinkPad T410 2537FP3       | Notebook    | [45559a492c](https://linux-hardware.org/?probe=45559a492c) | Apr 25, 2021 |
| Lenovo        | ThinkPad T420 4236EF4       | Notebook    | [4d07ea7b58](https://linux-hardware.org/?probe=4d07ea7b58) | Apr 24, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [45678e2907](https://linux-hardware.org/?probe=45678e2907) | Apr 24, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [f178c672cf](https://linux-hardware.org/?probe=f178c672cf) | Apr 24, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [6dc9bcb3f7](https://linux-hardware.org/?probe=6dc9bcb3f7) | Apr 24, 2021 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [15cbbda6f8](https://linux-hardware.org/?probe=15cbbda6f8) | Apr 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [80224285b6](https://linux-hardware.org/?probe=80224285b6) | Apr 24, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [203ccba0d8](https://linux-hardware.org/?probe=203ccba0d8) | Apr 24, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [b6b305b0bd](https://linux-hardware.org/?probe=b6b305b0bd) | Apr 24, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [f5bfb4f382](https://linux-hardware.org/?probe=f5bfb4f382) | Apr 24, 2021 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [15f9ee179c](https://linux-hardware.org/?probe=15f9ee179c) | Apr 24, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [af9117e999](https://linux-hardware.org/?probe=af9117e999) | Apr 24, 2021 |
| Lenovo        | 3701 SDK0R32862 WIN 3258... | All in one  | [6a8f470ab8](https://linux-hardware.org/?probe=6a8f470ab8) | Apr 24, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [638c4207ce](https://linux-hardware.org/?probe=638c4207ce) | Apr 24, 2021 |
| ASUSTek       | VC66                        | Desktop     | [6158b04856](https://linux-hardware.org/?probe=6158b04856) | Apr 24, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [a63e8e0aeb](https://linux-hardware.org/?probe=a63e8e0aeb) | Apr 23, 2021 |
| ASUSTek       | K50IN                       | Notebook    | [7a84f17bdb](https://linux-hardware.org/?probe=7a84f17bdb) | Apr 23, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [3423651b5d](https://linux-hardware.org/?probe=3423651b5d) | Apr 23, 2021 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [163211473a](https://linux-hardware.org/?probe=163211473a) | Apr 23, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9a9bc27310](https://linux-hardware.org/?probe=9a9bc27310) | Apr 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS55S00    | Notebook    | [5dc10377ab](https://linux-hardware.org/?probe=5dc10377ab) | Apr 23, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | Notebook    | [3120e73dca](https://linux-hardware.org/?probe=3120e73dca) | Apr 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [06b060c49c](https://linux-hardware.org/?probe=06b060c49c) | Apr 23, 2021 |
| Acer          | Spin SP314-21               | Convertible | [429ca1c90b](https://linux-hardware.org/?probe=429ca1c90b) | Apr 23, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [7963c5b064](https://linux-hardware.org/?probe=7963c5b064) | Apr 23, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [6dba735784](https://linux-hardware.org/?probe=6dba735784) | Apr 20, 2021 |
| Lenovo        | ThinkPad T420 4236EF4       | Notebook    | [015d11b9cb](https://linux-hardware.org/?probe=015d11b9cb) | Apr 19, 2021 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [9622491640](https://linux-hardware.org/?probe=9622491640) | Apr 19, 2021 |
| ASRock        | B550 Steel Legend           | Desktop     | [d8db6d8577](https://linux-hardware.org/?probe=d8db6d8577) | Apr 18, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1a10915a97](https://linux-hardware.org/?probe=1a10915a97) | Apr 17, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [eb63a6bb36](https://linux-hardware.org/?probe=eb63a6bb36) | Apr 17, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [e3bc507a07](https://linux-hardware.org/?probe=e3bc507a07) | Apr 17, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [4e23f3b6b5](https://linux-hardware.org/?probe=4e23f3b6b5) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [18ee0d2d64](https://linux-hardware.org/?probe=18ee0d2d64) | Apr 16, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [8e9d22ed4d](https://linux-hardware.org/?probe=8e9d22ed4d) | Apr 15, 2021 |
| ASRock        | X570 PG Velocita            | Desktop     | [20e91a55f2](https://linux-hardware.org/?probe=20e91a55f2) | Apr 15, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [3274addf89](https://linux-hardware.org/?probe=3274addf89) | Apr 14, 2021 |
| ASRock        | H570 Phantom Gaming 4       | Desktop     | [e89bff9fa4](https://linux-hardware.org/?probe=e89bff9fa4) | Apr 14, 2021 |
| Dell          | 0VD5HY A07                  | Desktop     | [28dda9b894](https://linux-hardware.org/?probe=28dda9b894) | Apr 12, 2021 |
| HP            | Spectre XT Ultrabook PC     | Notebook    | [adf30d3202](https://linux-hardware.org/?probe=adf30d3202) | Apr 09, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [519d1fea88](https://linux-hardware.org/?probe=519d1fea88) | Apr 09, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [b3110fa6fb](https://linux-hardware.org/?probe=b3110fa6fb) | Apr 09, 2021 |
| ASUSTek       | X542URR                     | Notebook    | [d49a5f2b6c](https://linux-hardware.org/?probe=d49a5f2b6c) | Apr 07, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [44eeda4c00](https://linux-hardware.org/?probe=44eeda4c00) | Apr 05, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [eb4cc7f2c2](https://linux-hardware.org/?probe=eb4cc7f2c2) | Apr 05, 2021 |
| Lenovo        | ThinkPad T430 2349DD5       | Notebook    | [3cf8173314](https://linux-hardware.org/?probe=3cf8173314) | Apr 05, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [3a69abb947](https://linux-hardware.org/?probe=3a69abb947) | Apr 05, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [6534232c53](https://linux-hardware.org/?probe=6534232c53) | Apr 04, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [63996f0452](https://linux-hardware.org/?probe=63996f0452) | Apr 04, 2021 |
| MSI           | MS-B9181                    | Desktop     | [7c467c7f2b](https://linux-hardware.org/?probe=7c467c7f2b) | Apr 02, 2021 |
| MSI           | MS-B9181                    | Desktop     | [5ed3225348](https://linux-hardware.org/?probe=5ed3225348) | Apr 02, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [806a28ffcb](https://linux-hardware.org/?probe=806a28ffcb) | Apr 02, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [2d30481374](https://linux-hardware.org/?probe=2d30481374) | Apr 01, 2021 |
| Acer          | Switch SW312-31             | Tablet      | [e8fb03a779](https://linux-hardware.org/?probe=e8fb03a779) | Mar 31, 2021 |
| MSI           | MS-1672 Ver                 | Desktop     | [c630018fea](https://linux-hardware.org/?probe=c630018fea) | Mar 31, 2021 |
| MSI           | MS-1672 Ver                 | Desktop     | [d72651aaf4](https://linux-hardware.org/?probe=d72651aaf4) | Mar 31, 2021 |
| Lenovo        | ThinkPad T430 2349UWT       | Notebook    | [d6edf7c2df](https://linux-hardware.org/?probe=d6edf7c2df) | Mar 28, 2021 |
| Dell          | G3 3500                     | Notebook    | [83f2a24875](https://linux-hardware.org/?probe=83f2a24875) | Mar 27, 2021 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [9a724f738f](https://linux-hardware.org/?probe=9a724f738f) | Mar 26, 2021 |
| HP            | 3646h                       | Desktop     | [f870632953](https://linux-hardware.org/?probe=f870632953) | Mar 26, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [b468496893](https://linux-hardware.org/?probe=b468496893) | Mar 25, 2021 |
| Dell          | 084XW4 A00                  | Server      | [55471d97f1](https://linux-hardware.org/?probe=55471d97f1) | Mar 24, 2021 |
| Google        | Edgar                       | Notebook    | [e31c334180](https://linux-hardware.org/?probe=e31c334180) | Mar 23, 2021 |
| Pegatron      | VIOLET                      | Desktop     | [97b60b69c9](https://linux-hardware.org/?probe=97b60b69c9) | Mar 19, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [50b82af935](https://linux-hardware.org/?probe=50b82af935) | Mar 18, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| Biostar       | A320MD PRO                  | Desktop     | [cc647d652a](https://linux-hardware.org/?probe=cc647d652a) | Mar 16, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [8e4ebb57eb](https://linux-hardware.org/?probe=8e4ebb57eb) | Mar 10, 2021 |
| HP            | 8430 1000                   | All in one  | [f40d786ac2](https://linux-hardware.org/?probe=f40d786ac2) | Mar 08, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [ee9f48a9d0](https://linux-hardware.org/?probe=ee9f48a9d0) | Mar 06, 2021 |
| ASRockRack    | X570D4U                     | Desktop     | [046e21b599](https://linux-hardware.org/?probe=046e21b599) | Mar 04, 2021 |
| Razer         | Blade                       | Notebook    | [638dd21f45](https://linux-hardware.org/?probe=638dd21f45) | Mar 03, 2021 |
| ASRockRack    | X570D4U                     | Desktop     | [250918faa7](https://linux-hardware.org/?probe=250918faa7) | Mar 03, 2021 |
| ASRock        | FM2A75M-DGS                 | Desktop     | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [237d8d39fb](https://linux-hardware.org/?probe=237d8d39fb) | Feb 27, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [986679aa93](https://linux-hardware.org/?probe=986679aa93) | Feb 25, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ec5eb37f90](https://linux-hardware.org/?probe=ec5eb37f90) | Feb 25, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [bded62870c](https://linux-hardware.org/?probe=bded62870c) | Feb 23, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [446f49d2d6](https://linux-hardware.org/?probe=446f49d2d6) | Feb 22, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [3555575966](https://linux-hardware.org/?probe=3555575966) | Feb 21, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [190805f976](https://linux-hardware.org/?probe=190805f976) | Feb 21, 2021 |
| Gigabyte      | AB350M-D3V-CF               | Desktop     | [38a9e8bdd4](https://linux-hardware.org/?probe=38a9e8bdd4) | Feb 05, 2021 |
| HUAWEI        | SP1PGUM M1020               | Desktop     | [bd05c84564](https://linux-hardware.org/?probe=bd05c84564) | Feb 04, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [449cccd96f](https://linux-hardware.org/?probe=449cccd96f) | Feb 04, 2021 |
| HUAWEI        | BC82AMDDA V200R002C00       | Server      | [3ca7825025](https://linux-hardware.org/?probe=3ca7825025) | Jan 30, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [d87649a1b4](https://linux-hardware.org/?probe=d87649a1b4) | Jan 27, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [ea1a9ef713](https://linux-hardware.org/?probe=ea1a9ef713) | Jan 27, 2021 |
| HP            | 3032h                       | Desktop     | [89ff3e8a36](https://linux-hardware.org/?probe=89ff3e8a36) | Jan 25, 2021 |
| HASEE Comp... | HINS                        | Notebook    | [2419cd659a](https://linux-hardware.org/?probe=2419cd659a) | Jan 24, 2021 |
| HP            | 630                         | Notebook    | [1e3eae8729](https://linux-hardware.org/?probe=1e3eae8729) | Jan 21, 2021 |
| Acer          | Aspire V5-552G              | Notebook    | [8e70dd07f9](https://linux-hardware.org/?probe=8e70dd07f9) | Jan 19, 2021 |
| ASRock        | B75M-GL R2.0                | Desktop     | [79848dc213](https://linux-hardware.org/?probe=79848dc213) | Jan 17, 2021 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [319ddce23d](https://linux-hardware.org/?probe=319ddce23d) | Jan 11, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e081c11999](https://linux-hardware.org/?probe=e081c11999) | Jan 11, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [b242ecc226](https://linux-hardware.org/?probe=b242ecc226) | Jan 11, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [57427da656](https://linux-hardware.org/?probe=57427da656) | Jan 02, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [772dc9d4d7](https://linux-hardware.org/?probe=772dc9d4d7) | Dec 27, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [b17ba4582e](https://linux-hardware.org/?probe=b17ba4582e) | Dec 22, 2020 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [f5c9028c6a](https://linux-hardware.org/?probe=f5c9028c6a) | Dec 21, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [1feb258908](https://linux-hardware.org/?probe=1feb258908) | Dec 20, 2020 |
| ASRock        | B75M-GL R2.0                | Desktop     | [91c33b15fe](https://linux-hardware.org/?probe=91c33b15fe) | Dec 18, 2020 |
| Gateway       | M290                        | Notebook    | [0b09493054](https://linux-hardware.org/?probe=0b09493054) | Dec 15, 2020 |
| Acer          | Aspire V5-552G              | Notebook    | [8f8a054e09](https://linux-hardware.org/?probe=8f8a054e09) | Dec 13, 2020 |
| Gateway       | M290                        | Notebook    | [361d599d08](https://linux-hardware.org/?probe=361d599d08) | Dec 11, 2020 |
| HP            | 3032h                       | Desktop     | [aca3ed50ac](https://linux-hardware.org/?probe=aca3ed50ac) | Dec 07, 2020 |
| HP            | 3032h                       | Desktop     | [b061d52e66](https://linux-hardware.org/?probe=b061d52e66) | Dec 07, 2020 |
| ASUSTek       | X556UQ                      | Notebook    | [06423fe399](https://linux-hardware.org/?probe=06423fe399) | Dec 02, 2020 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [bb2f68b014](https://linux-hardware.org/?probe=bb2f68b014) | Nov 27, 2020 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [5c18dade22](https://linux-hardware.org/?probe=5c18dade22) | Nov 27, 2020 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [bcc73e0b8d](https://linux-hardware.org/?probe=bcc73e0b8d) | Nov 25, 2020 |
| Alienware     | 13 R3                       | Notebook    | [b4b8471219](https://linux-hardware.org/?probe=b4b8471219) | Nov 22, 2020 |
| Colorful T... | C.H110M-K PRO V21           | Desktop     | [c8211ace73](https://linux-hardware.org/?probe=c8211ace73) | Nov 20, 2020 |
| ASUSTek       | X556UQ                      | Notebook    | [d55510c234](https://linux-hardware.org/?probe=d55510c234) | Nov 06, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_21.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.11.0-16-generic        | 224       | 11.42%  |
| 5.11.0-25-generic        | 208       | 10.6%   |
| 5.11.0-22-generic        | 189       | 9.63%   |
| 5.11.0-31-generic        | 180       | 9.17%   |
| 5.11.0-18-generic        | 159       | 8.1%    |
| 5.11.0-37-generic        | 155       | 7.9%    |
| 5.11.0-17-generic        | 124       | 6.32%   |
| 5.11.0-34-generic        | 122       | 6.22%   |
| 5.11.0-38-generic        | 59        | 3.01%   |
| 5.11.0-49-generic        | 50        | 2.55%   |
| 5.11.0-36-generic        | 42        | 2.14%   |
| 5.11.0-40-generic        | 37        | 1.89%   |
| 5.11.0-41-generic        | 36        | 1.83%   |
| 5.11.0-26-generic        | 22        | 1.12%   |
| 5.11.0-1012-raspi        | 17        | 0.87%   |
| 5.11.0-1007-raspi        | 17        | 0.87%   |
| 5.11.0-33-generic        | 14        | 0.71%   |
| 5.11.0-24-generic        | 14        | 0.71%   |
| 5.11.0-13-generic        | 13        | 0.66%   |
| 5.11.0-1015-raspi        | 13        | 0.66%   |
| 5.11.0-1016-raspi        | 11        | 0.56%   |
| 5.10.0-14-generic        | 11        | 0.56%   |
| 5.11.0-44-generic        | 10        | 0.51%   |
| 5.11.0-1008-raspi        | 10        | 0.51%   |
| 5.11.0-42-generic        | 9         | 0.46%   |
| 5.11.0-20-generic        | 8         | 0.41%   |
| 5.11.0-1017-raspi        | 7         | 0.36%   |
| 5.11.0-14-generic        | 6         | 0.31%   |
| 5.11.0-11-generic        | 6         | 0.31%   |
| 5.11.0-1009-raspi        | 6         | 0.31%   |
| 5.8.0-36-generic         | 5         | 0.25%   |
| 5.11.0-35-generic        | 5         | 0.25%   |
| 5.11.0-23-generic        | 5         | 0.25%   |
| 5.11.0-1019-raspi        | 5         | 0.25%   |
| 5.8.0-50-generic         | 4         | 0.2%    |
| 5.13.1-051301-generic    | 4         | 0.2%    |
| 5.13.0-051300-generic    | 4         | 0.2%    |
| 5.12.0-051200-generic    | 4         | 0.2%    |
| 5.11.0-46-generic        | 4         | 0.2%    |
| 5.8.0-55-generic         | 3         | 0.15%   |
| 5.8.0-32-generic         | 3         | 0.15%   |
| 5.14.0-051400-generic    | 3         | 0.15%   |
| 5.13.9-051309-generic    | 3         | 0.15%   |
| 5.11.0-43-generic        | 3         | 0.15%   |
| 5.11.0-19-generic        | 3         | 0.15%   |
| 5.11.0-051100-generic    | 3         | 0.15%   |
| 5.10.0-12-generic        | 3         | 0.15%   |
| 5.8.0-63-generic         | 2         | 0.1%    |
| 5.8.0-25-generic         | 2         | 0.1%    |
| 5.14.9-051409-generic    | 2         | 0.1%    |
| 5.13.12-051312-generic   | 2         | 0.1%    |
| 5.13.0-051300rc7-generic | 2         | 0.1%    |
| 5.12.12-051212-generic   | 2         | 0.1%    |
| 5.12.0-051200rc3-generic | 2         | 0.1%    |
| 5.11.12-051112-generic   | 2         | 0.1%    |
| 5.11.0-1024-raspi        | 2         | 0.1%    |
| 5.11.0-1023-raspi        | 2         | 0.1%    |
| 5.11.0-1021-raspi        | 2         | 0.1%    |
| 5.10.0-051000-generic    | 2         | 0.1%    |
| 5.9.8-xanmod1-cachy      | 1         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 1649      | 92.43%  |
| 5.8.0   | 31        | 1.74%   |
| 5.10.0  | 18        | 1.01%   |
| 5.13.0  | 16        | 0.9%    |
| 5.12.0  | 8         | 0.45%   |
| 5.14.0  | 7         | 0.39%   |
| 5.4.0   | 4         | 0.22%   |
| 5.13.9  | 4         | 0.22%   |
| 5.13.1  | 4         | 0.22%   |
| 5.14.9  | 3         | 0.17%   |
| 5.15.0  | 2         | 0.11%   |
| 5.13.7  | 2         | 0.11%   |
| 5.13.12 | 2         | 0.11%   |
| 5.12.9  | 2         | 0.11%   |
| 5.12.12 | 2         | 0.11%   |
| 5.11.12 | 2         | 0.11%   |
| 5.9.8   | 1         | 0.06%   |
| 5.9.10  | 1         | 0.06%   |
| 5.4.73  | 1         | 0.06%   |
| 5.16.18 | 1         | 0.06%   |
| 5.16.10 | 1         | 0.06%   |
| 5.16.1  | 1         | 0.06%   |
| 5.16.0  | 1         | 0.06%   |
| 5.15.8  | 1         | 0.06%   |
| 5.14.8  | 1         | 0.06%   |
| 5.14.6  | 1         | 0.06%   |
| 5.14.3  | 1         | 0.06%   |
| 5.14.2  | 1         | 0.06%   |
| 5.14.10 | 1         | 0.06%   |
| 5.14.1  | 1         | 0.06%   |
| 5.13.6  | 1         | 0.06%   |
| 5.13.4  | 1         | 0.06%   |
| 5.12.8  | 1         | 0.06%   |
| 5.12.6  | 1         | 0.06%   |
| 5.12.4  | 1         | 0.06%   |
| 5.12.10 | 1         | 0.06%   |
| 5.11.6  | 1         | 0.06%   |
| 5.11.20 | 1         | 0.06%   |
| 5.11.10 | 1         | 0.06%   |
| 5.11.1  | 1         | 0.06%   |
| 5.10.75 | 1         | 0.06%   |
| 5.10.69 | 1         | 0.06%   |
| 5.10.43 | 1         | 0.06%   |
| 4.9.253 | 1         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 1655      | 92.77%  |
| 5.8     | 31        | 1.74%   |
| 5.13    | 30        | 1.68%   |
| 5.10    | 21        | 1.18%   |
| 5.14    | 16        | 0.9%    |
| 5.12    | 16        | 0.9%    |
| 5.4     | 5         | 0.28%   |
| 5.16    | 4         | 0.22%   |
| 5.15    | 3         | 0.17%   |
| 5.9     | 2         | 0.11%   |
| 4.9     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1678      | 94.86%  |
| aarch64 | 91        | 5.14%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 1587      | 88.76%  |
| Unknown           | 154       | 8.61%   |
| X-Cinnamon        | 17        | 0.95%   |
| Unity             | 10        | 0.56%   |
| Cinnamon          | 8         | 0.45%   |
| Yaru:ubuntu:GNOME | 2         | 0.11%   |
| sway              | 2         | 0.11%   |
| i3                | 2         | 0.11%   |
| GNOME Flashback   | 2         | 0.11%   |
| Trinity           | 1         | 0.06%   |
| openbox           | 1         | 0.06%   |
| fvwm              | 1         | 0.06%   |
| awesome           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1106      | 61.07%  |
| X11     | 601       | 33.19%  |
| Unknown | 74        | 4.09%   |
| Tty     | 30        | 1.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 996       | 54.52%  |
| GDM     | 484       | 26.49%  |
| GDM3    | 318       | 17.41%  |
| LightDM | 15        | 0.82%   |
| TDM     | 11        | 0.6%    |
| SDDM    | 2         | 0.11%   |
| Ly      | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 744       | 41.96%  |
| de_DE   | 199       | 11.22%  |
| en_GB   | 97        | 5.47%   |
| fr_FR   | 96        | 5.41%   |
| it_IT   | 63        | 3.55%   |
| pt_BR   | 54        | 3.05%   |
| en_IN   | 49        | 2.76%   |
| en_CA   | 40        | 2.26%   |
| ru_RU   | 39        | 2.2%    |
| es_ES   | 37        | 2.09%   |
| en_AU   | 37        | 2.09%   |
| pl_PL   | 36        | 2.03%   |
| cs_CZ   | 21        | 1.18%   |
| C       | 18        | 1.02%   |
| en_ZA   | 16        | 0.9%    |
| zh_CN   | 15        | 0.85%   |
| nl_NL   | 15        | 0.85%   |
| ja_JP   | 15        | 0.85%   |
| de_AT   | 14        | 0.79%   |
| sv_SE   | 11        | 0.62%   |
| hu_HU   | 11        | 0.62%   |
| es_AR   | 10        | 0.56%   |
| Unknown | 9         | 0.51%   |
| ru_UA   | 8         | 0.45%   |
| en_NZ   | 8         | 0.45%   |
| es_CL   | 7         | 0.39%   |
| de_CH   | 7         | 0.39%   |
| fr_BE   | 6         | 0.34%   |
| es_MX   | 6         | 0.34%   |
| pt_PT   | 5         | 0.28%   |
| nb_NO   | 5         | 0.28%   |
| fi_FI   | 5         | 0.28%   |
| en_IL   | 5         | 0.28%   |
| zh_TW   | 4         | 0.23%   |
| tr_TR   | 4         | 0.23%   |
| ro_RO   | 4         | 0.23%   |
| el_GR   | 4         | 0.23%   |
| da_DK   | 4         | 0.23%   |
| ca_ES   | 4         | 0.23%   |
| bg_BG   | 4         | 0.23%   |
| en_SG   | 3         | 0.17%   |
| vi_VN   | 2         | 0.11%   |
| sk_SK   | 2         | 0.11%   |
| hr_HR   | 2         | 0.11%   |
| fr_CA   | 2         | 0.11%   |
| es_UY   | 2         | 0.11%   |
| es_EC   | 2         | 0.11%   |
| es_CO   | 2         | 0.11%   |
| zh_HK   | 1         | 0.06%   |
| uk_UA   | 1         | 0.06%   |
| nl_BE   | 1         | 0.06%   |
| my_MM   | 1         | 0.06%   |
| id_ID   | 1         | 0.06%   |
| fr_CH   | 1         | 0.06%   |
| et_EE   | 1         | 0.06%   |
| es_PY   | 1         | 0.06%   |
| es_PE   | 1         | 0.06%   |
| es_NI   | 1         | 0.06%   |
| es_HN   | 1         | 0.06%   |
| es_CU   | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1163      | 64.97%  |
| EFI  | 627       | 35.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1625      | 91.65%  |
| Zfs      | 58        | 3.27%   |
| Overlay  | 46        | 2.59%   |
| Btrfs    | 26        | 1.47%   |
| Xfs      | 9         | 0.51%   |
| Ext2     | 4         | 0.23%   |
| Ext3     | 2         | 0.11%   |
| Unknown  | 2         | 0.11%   |
| SquXshfs | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1248      | 70.23%  |
| GPT     | 487       | 27.41%  |
| MBR     | 42        | 2.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1538      | 86.07%  |
| Yes       | 249       | 13.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1108      | 62.14%  |
| Yes       | 675       | 37.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 278       | 15.72%  |
| Dell                    | 246       | 13.91%  |
| Hewlett-Packard         | 237       | 13.4%   |
| Lenovo                  | 231       | 13.06%  |
| Gigabyte Technology     | 120       | 6.78%   |
| Acer                    | 99        | 5.6%    |
| MSI                     | 95        | 5.37%   |
| Raspberry Pi Foundation | 84        | 4.75%   |
| ASRock                  | 55        | 3.11%   |
| Apple                   | 39        | 2.2%    |
| Toshiba                 | 22        | 1.24%   |
| Intel                   | 22        | 1.24%   |
| Samsung Electronics     | 19        | 1.07%   |
| HUAWEI                  | 19        | 1.07%   |
| Fujitsu                 | 16        | 0.9%    |
| Sony                    | 14        | 0.79%   |
| Medion                  | 13        | 0.73%   |
| Unknown                 | 12        | 0.68%   |
| Biostar                 | 9         | 0.51%   |
| Timi                    | 8         | 0.45%   |
| Notebook                | 8         | 0.45%   |
| Pegatron                | 7         | 0.4%    |
| Positivo                | 5         | 0.28%   |
| Packard Bell            | 5         | 0.28%   |
| Microsoft               | 5         | 0.28%   |
| Alienware               | 5         | 0.28%   |
| TUXEDO                  | 4         | 0.23%   |
| System76                | 4         | 0.23%   |
| Supermicro              | 4         | 0.23%   |
| Foxconn                 | 4         | 0.23%   |
| Shuttle                 | 3         | 0.17%   |
| Razer                   | 3         | 0.17%   |
| Google                  | 3         | 0.17%   |
| AMI                     | 3         | 0.17%   |
| Schenker                | 2         | 0.11%   |
| Nvidia                  | 2         | 0.11%   |
| Monster                 | 2         | 0.11%   |
| LG Electronics          | 2         | 0.11%   |
| IP3 Tech                | 2         | 0.11%   |
| HC                      | 2         | 0.11%   |
| ECS                     | 2         | 0.11%   |
| Chuwi                   | 2         | 0.11%   |
| Wortmann AG             | 1         | 0.06%   |
| Wiltronic               | 1         | 0.06%   |
| VINGA                   | 1         | 0.06%   |
| TYAN Computer           | 1         | 0.06%   |
| TrekStor                | 1         | 0.06%   |
| TongFang                | 1         | 0.06%   |
| Thomson                 | 1         | 0.06%   |
| Teclast                 | 1         | 0.06%   |
| SYWZ                    | 1         | 0.06%   |
| sunxi                   | 1         | 0.06%   |
| Standard                | 1         | 0.06%   |
| Soyo                    | 1         | 0.06%   |
| roda computer           | 1         | 0.06%   |
| Radxa                   | 1         | 0.06%   |
| Quanta                  | 1         | 0.06%   |
| Positivo Bahia - VAIO   | 1         | 0.06%   |
| PCWare                  | 1         | 0.06%   |
| Panasonic               | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| RPi Raspberry Pi                   | 72        | 4.07%   |
| Unknown                            | 18        | 1.02%   |
| ASUS All Series                    | 17        | 0.96%   |
| Dell XPS 15 7590                   | 9         | 0.51%   |
| HP Notebook                        | 8         | 0.45%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 6         | 0.34%   |
| HP EliteBook 820 G1                | 5         | 0.28%   |
| Dell XPS 13 9310                   | 5         | 0.28%   |
| MSI MS-7C37                        | 4         | 0.23%   |
| MSI MS-7B86                        | 4         | 0.23%   |
| Intel NUC10i7FNH                   | 4         | 0.23%   |
| HP ProBook 450 G7                  | 4         | 0.23%   |
| Gigabyte B450M DS3H                | 4         | 0.23%   |
| Dell XPS 15 9510                   | 4         | 0.23%   |
| Dell XPS 13 7390                   | 4         | 0.23%   |
| Dell OptiPlex 7010                 | 4         | 0.23%   |
| MSI MS-7A34                        | 3         | 0.17%   |
| MSI MS-7850                        | 3         | 0.17%   |
| MSI MS-7758                        | 3         | 0.17%   |
| MSI MS-7693                        | 3         | 0.17%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2  | 3         | 0.17%   |
| Lenovo IdeaPad 5 14ARE05 81YM      | 3         | 0.17%   |
| Lenovo G500 20236                  | 3         | 0.17%   |
| HUAWEI HLYL-WXX9                   | 3         | 0.17%   |
| HP Z440 Workstation                | 3         | 0.17%   |
| HP Pavilion Notebook               | 3         | 0.17%   |
| HP Pavilion dv6                    | 3         | 0.17%   |
| HP Laptop 15-da0xxx                | 3         | 0.17%   |
| HP EliteBook 845 G7 Notebook PC    | 3         | 0.17%   |
| HP EliteBook 840 G3                | 3         | 0.17%   |
| HP EliteBook 840 G2                | 3         | 0.17%   |
| HP 15                              | 3         | 0.17%   |
| Gigabyte Z77-DS3H                  | 3         | 0.17%   |
| Gigabyte X570 AORUS MASTER         | 3         | 0.17%   |
| Dell XPS 15 9570                   | 3         | 0.17%   |
| Dell XPS 15 9500                   | 3         | 0.17%   |
| Dell XPS 13 9360                   | 3         | 0.17%   |
| Dell OptiPlex 9010                 | 3         | 0.17%   |
| Dell Latitude E6430                | 3         | 0.17%   |
| Dell Latitude E4300                | 3         | 0.17%   |
| Dell Latitude 5511                 | 3         | 0.17%   |
| Dell Inspiron 5406 2n1             | 3         | 0.17%   |
| Dell G5 5587                       | 3         | 0.17%   |
| Dell G3 3500                       | 3         | 0.17%   |
| ASUS X551CAP                       | 3         | 0.17%   |
| ASUS U50Vg                         | 3         | 0.17%   |
| ASUS ROG STRIX X570-E GAMING       | 3         | 0.17%   |
| ASUS ROG Strix G513QY_G513QY       | 3         | 0.17%   |
| ASUS ROG STRIX B550-F GAMING       | 3         | 0.17%   |
| ASUS ROG STRIX B450-F GAMING       | 3         | 0.17%   |
| ASUS PRIME Z590-P                  | 3         | 0.17%   |
| ASUS PRIME A320M-K                 | 3         | 0.17%   |
| ASUS M5A97 R2.0                    | 3         | 0.17%   |
| Apple MacBookPro9,2                | 3         | 0.17%   |
| Acer Swift SF314-59                | 3         | 0.17%   |
| Acer Aspire A515-44                | 3         | 0.17%   |
| Toshiba PORTEGE Z930               | 2         | 0.11%   |
| Timi A35S                          | 2         | 0.11%   |
| System76 Serval WS                 | 2         | 0.11%   |
| Supermicro Super Server            | 2         | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 99        | 5.6%    |
| RPi Raspberry          | 84        | 4.75%   |
| Dell Inspiron          | 69        | 3.9%    |
| Acer Aspire            | 60        | 3.39%   |
| Dell Latitude          | 59        | 3.34%   |
| Lenovo IdeaPad         | 51        | 2.88%   |
| ASUS ROG               | 48        | 2.71%   |
| Dell XPS               | 45        | 2.54%   |
| HP EliteBook           | 38        | 2.15%   |
| ASUS PRIME             | 37        | 2.09%   |
| HP Pavilion            | 35        | 1.98%   |
| HP ProBook             | 28        | 1.58%   |
| Dell OptiPlex          | 23        | 1.3%    |
| HP Laptop              | 22        | 1.24%   |
| Unknown                | 18        | 1.02%   |
| Dell Precision         | 17        | 0.96%   |
| ASUS All               | 17        | 0.96%   |
| Dell Vostro            | 16        | 0.9%    |
| Toshiba Satellite      | 15        | 0.85%   |
| HP ENVY                | 14        | 0.79%   |
| ASUS TUF               | 13        | 0.73%   |
| Acer Swift             | 13        | 0.73%   |
| Lenovo ThinkCentre     | 12        | 0.68%   |
| HP Spectre             | 12        | 0.68%   |
| HP Compaq              | 12        | 0.68%   |
| ASUS VivoBook          | 12        | 0.68%   |
| Lenovo Yoga            | 11        | 0.62%   |
| Lenovo IdeaPadFlex     | 10        | 0.57%   |
| Gigabyte X570          | 9         | 0.51%   |
| HP Notebook            | 8         | 0.45%   |
| Lenovo ThinkBook       | 7         | 0.4%    |
| HP EliteDesk           | 7         | 0.4%    |
| Fujitsu LIFEBOOK       | 7         | 0.4%    |
| Gigabyte GA-78LMT-USB3 | 6         | 0.34%   |
| Gigabyte B450M         | 6         | 0.34%   |
| ASUS ZenBook           | 6         | 0.34%   |
| ASUS M5A97             | 6         | 0.34%   |
| Acer TravelMate        | 6         | 0.34%   |
| Microsoft Surface      | 5         | 0.28%   |
| Lenovo Legion          | 5         | 0.28%   |
| HP ProLiant            | 5         | 0.28%   |
| ASUS P8Z77-V           | 5         | 0.28%   |
| Packard Bell EasyNote  | 4         | 0.23%   |
| MSI MS-7C37            | 4         | 0.23%   |
| MSI MS-7B86            | 4         | 0.23%   |
| Lenovo IdeaCentre      | 4         | 0.23%   |
| Intel NUC10i7FNH       | 4         | 0.23%   |
| HP ZBook               | 4         | 0.23%   |
| HP Stream              | 4         | 0.23%   |
| HP 15                  | 4         | 0.23%   |
| Dell PowerEdge         | 4         | 0.23%   |
| Dell G3                | 4         | 0.23%   |
| ASUS P5Q               | 4         | 0.23%   |
| ASRock 970             | 4         | 0.23%   |
| Apple MacBookPro8      | 4         | 0.23%   |
| Apple iMac19           | 4         | 0.23%   |
| Acer Nitro             | 4         | 0.23%   |
| Toshiba PORTEGE        | 3         | 0.17%   |
| Razer Blade            | 3         | 0.17%   |
| MSI MS-7A34            | 3         | 0.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 261       | 14.75%  |
| 2019    | 168       | 9.5%    |
| 2018    | 165       | 9.33%   |
| 2021    | 149       | 8.42%   |
| 2012    | 140       | 7.91%   |
| 2013    | 118       | 6.67%   |
| 2017    | 115       | 6.5%    |
| 2011    | 97        | 5.48%   |
| 2015    | 92        | 5.2%    |
| Unknown | 88        | 4.97%   |
| 2016    | 75        | 4.24%   |
| 2014    | 74        | 4.18%   |
| 2010    | 71        | 4.01%   |
| 2009    | 64        | 3.62%   |
| 2008    | 57        | 3.22%   |
| 2007    | 19        | 1.07%   |
| 2006    | 10        | 0.57%   |
| 2005    | 5         | 0.28%   |
| 2022    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 912       | 51.55%  |
| Desktop        | 609       | 34.43%  |
| System on chip | 89        | 5.03%   |
| Convertible    | 78        | 4.41%   |
| All in one     | 26        | 1.47%   |
| Mini pc        | 25        | 1.41%   |
| Tablet         | 16        | 0.9%    |
| Server         | 14        | 0.79%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1618      | 91.26%  |
| Enabled  | 155       | 8.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1765      | 99.77%  |
| Yes  | 4         | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 426       | 24.04%  |
| 16.01-24.0      | 382       | 21.56%  |
| 3.01-4.0        | 321       | 18.12%  |
| 8.01-16.0       | 318       | 17.95%  |
| 32.01-64.0      | 176       | 9.93%   |
| 64.01-256.0     | 59        | 3.33%   |
| 1.01-2.0        | 53        | 2.99%   |
| 24.01-32.0      | 22        | 1.24%   |
| 2.01-3.0        | 8         | 0.45%   |
| More than 256.0 | 4         | 0.23%   |
| 0.51-1.0        | 3         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 701       | 37.49%  |
| 2.01-3.0    | 522       | 27.91%  |
| 4.01-8.0    | 286       | 15.29%  |
| 3.01-4.0    | 229       | 12.25%  |
| 8.01-16.0   | 65        | 3.48%   |
| 0.51-1.0    | 35        | 1.87%   |
| 16.01-24.0  | 15        | 0.8%    |
| 32.01-64.0  | 6         | 0.32%   |
| 0.01-0.5    | 5         | 0.27%   |
| 24.01-32.0  | 4         | 0.21%   |
| 64.01-256.0 | 2         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1089      | 60.6%   |
| 2      | 410       | 22.82%  |
| 3      | 129       | 7.18%   |
| 4      | 70        | 3.9%    |
| 5      | 35        | 1.95%   |
| 0      | 24        | 1.34%   |
| 6      | 18        | 1%      |
| 8      | 7         | 0.39%   |
| 7      | 6         | 0.33%   |
| 10     | 4         | 0.22%   |
| 9      | 4         | 0.22%   |
| 11     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1153      | 65.03%  |
| Yes       | 620       | 34.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1385      | 78.16%  |
| No        | 387       | 21.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1323      | 74.49%  |
| No        | 453       | 25.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1107      | 62.16%  |
| No        | 674       | 37.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 315       | 17.75%  |
| Germany      | 238       | 13.41%  |
| France       | 105       | 5.92%   |
| Italy        | 83        | 4.68%   |
| UK           | 80        | 4.51%   |
| Russia       | 68        | 3.83%   |
| Brazil       | 67        | 3.77%   |
| Spain        | 53        | 2.99%   |
| India        | 53        | 2.99%   |
| Canada       | 52        | 2.93%   |
| Poland       | 51        | 2.87%   |
| Netherlands  | 46        | 2.59%   |
| Australia    | 37        | 2.08%   |
| Sweden       | 29        | 1.63%   |
| Czechia      | 27        | 1.52%   |
| Austria      | 27        | 1.52%   |
| Ukraine      | 23        | 1.3%    |
| Switzerland  | 23        | 1.3%    |
| Finland      | 23        | 1.3%    |
| South Africa | 18        | 1.01%   |
| Japan        | 17        | 0.96%   |
| Hungary      | 17        | 0.96%   |
| Romania      | 16        | 0.9%    |
| Belgium      | 16        | 0.9%    |
| China        | 15        | 0.85%   |
| Portugal     | 14        | 0.79%   |
| Argentina    | 14        | 0.79%   |
| Turkey       | 12        | 0.68%   |
| Mexico       | 12        | 0.68%   |
| New Zealand  | 11        | 0.62%   |
| Israel       | 11        | 0.62%   |
| Greece       | 11        | 0.62%   |
| Chile        | 9         | 0.51%   |
| Indonesia    | 8         | 0.45%   |
| Serbia       | 7         | 0.39%   |
| Norway       | 7         | 0.39%   |
| Denmark      | 7         | 0.39%   |
| Croatia      | 7         | 0.39%   |
| Vietnam      | 6         | 0.34%   |
| Pakistan     | 6         | 0.34%   |
| Iran         | 6         | 0.34%   |
| Colombia     | 6         | 0.34%   |
| Taiwan       | 5         | 0.28%   |
| Singapore    | 5         | 0.28%   |
| Belarus      | 5         | 0.28%   |
| Slovakia     | 4         | 0.23%   |
| Saudi Arabia | 4         | 0.23%   |
| Peru         | 4         | 0.23%   |
| Malaysia     | 4         | 0.23%   |
| Luxembourg   | 4         | 0.23%   |
| Hong Kong    | 4         | 0.23%   |
| Bulgaria     | 4         | 0.23%   |
| Algeria      | 4         | 0.23%   |
| Nepal        | 3         | 0.17%   |
| Latvia       | 3         | 0.17%   |
| Kenya        | 3         | 0.17%   |
| Egypt        | 3         | 0.17%   |
| Uzbekistan   | 2         | 0.11%   |
| Uruguay      | 2         | 0.11%   |
| Tunisia      | 2         | 0.11%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 22        | 1.2%    |
| Berlin           | 21        | 1.15%   |
| Vienna           | 20        | 1.09%   |
| Paris            | 19        | 1.04%   |
| Warsaw           | 14        | 0.77%   |
| Prague           | 12        | 0.66%   |
| Milan            | 10        | 0.55%   |
| Melbourne        | 10        | 0.55%   |
| Cologne          | 10        | 0.55%   |
| Sydney           | 9         | 0.49%   |
| Sao Paulo        | 9         | 0.49%   |
| Helsinki         | 9         | 0.49%   |
| Hamburg          | 9         | 0.49%   |
| Munich           | 8         | 0.44%   |
| Montreal         | 8         | 0.44%   |
| Kyiv             | 8         | 0.44%   |
| Dallas           | 8         | 0.44%   |
| Budapest         | 8         | 0.44%   |
| Athens           | 8         | 0.44%   |
| Madrid           | 7         | 0.38%   |
| Los Angeles      | 7         | 0.38%   |
| Bologna          | 7         | 0.38%   |
| Toronto          | 6         | 0.33%   |
| London           | 6         | 0.33%   |
| Hyderabad        | 6         | 0.33%   |
| Bucharest        | 6         | 0.33%   |
| Zurich           | 5         | 0.27%   |
| Zagreb           | 5         | 0.27%   |
| Turin            | 5         | 0.27%   |
| Tel Aviv         | 5         | 0.27%   |
| Tehran           | 5         | 0.27%   |
| Singapore        | 5         | 0.27%   |
| San Antonio      | 5         | 0.27%   |
| Nuremberg        | 5         | 0.27%   |
| New York         | 5         | 0.27%   |
| New Delhi        | 5         | 0.27%   |
| Lisbon           | 5         | 0.27%   |
| Krakow           | 5         | 0.27%   |
| Johannesburg     | 5         | 0.27%   |
| Houston          | 5         | 0.27%   |
| Brisbane         | 5         | 0.27%   |
| Belo Horizonte   | 5         | 0.27%   |
| Beijing          | 5         | 0.27%   |
| Amsterdam        | 5         | 0.27%   |
| Tokyo            | 4         | 0.22%   |
| Tampere          | 4         | 0.22%   |
| St Petersburg    | 4         | 0.22%   |
| Seattle          | 4         | 0.22%   |
| San Jose         | 4         | 0.22%   |
| San Francisco    | 4         | 0.22%   |
| Rome             | 4         | 0.22%   |
| Portland         | 4         | 0.22%   |
| Kolkata          | 4         | 0.22%   |
| Karachi          | 4         | 0.22%   |
| Ho Chi Minh City | 4         | 0.22%   |
| Gdansk           | 4         | 0.22%   |
| Florence         | 4         | 0.22%   |
| Érd             | 4         | 0.22%   |
| Cape Town        | 4         | 0.22%   |
| Canoas           | 4         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 407       | 538    | 16%     |
| WDC                       | 378       | 534    | 14.86%  |
| Seagate                   | 348       | 515    | 13.68%  |
| Toshiba                   | 187       | 233    | 7.35%   |
| Unknown                   | 164       | 201    | 6.45%   |
| SanDisk                   | 133       | 160    | 5.23%   |
| Kingston                  | 116       | 141    | 4.56%   |
| Crucial                   | 82        | 101    | 3.22%   |
| SK hynix                  | 77        | 81     | 3.03%   |
| Intel                     | 74        | 99     | 2.91%   |
| Hitachi                   | 70        | 87     | 2.75%   |
| HGST                      | 41        | 51     | 1.61%   |
| Micron Technology         | 38        | 43     | 1.49%   |
| A-DATA Technology         | 38        | 46     | 1.49%   |
| Phison                    | 26        | 35     | 1.02%   |
| KIOXIA                    | 25        | 28     | 0.98%   |
| Silicon Motion            | 21        | 23     | 0.83%   |
| LITEON                    | 14        | 15     | 0.55%   |
| China                     | 14        | 17     | 0.55%   |
| SPCC                      | 13        | 16     | 0.51%   |
| Micron/Crucial Technology | 13        | 14     | 0.51%   |
| Apple                     | 13        | 18     | 0.51%   |
| JMicron Technology        | 12        | 18     | 0.47%   |
| ASMT                      | 11        | 16     | 0.43%   |
| Patriot                   | 10        | 12     | 0.39%   |
| Maxtor                    | 10        | 14     | 0.39%   |
| Intenso                   | 10        | 12     | 0.39%   |
| Corsair                   | 9         | 12     | 0.35%   |
| Transcend                 | 8         | 9      | 0.31%   |
| PNY                       | 8         | 9      | 0.31%   |
| OCZ                       | 7         | 8      | 0.28%   |
| LITEONIT                  | 7         | 9      | 0.28%   |
| Goodram                   | 7         | 8      | 0.28%   |
| Team                      | 6         | 7      | 0.24%   |
| Mushkin                   | 6         | 9      | 0.24%   |
| Hewlett-Packard           | 6         | 8      | 0.24%   |
| XPG                       | 5         | 5      | 0.2%    |
| Gigabyte Technology       | 5         | 6      | 0.2%    |
| Union Memory              | 4         | 4      | 0.16%   |
| Plextor                   | 4         | 4      | 0.16%   |
| Argon                     | 4         | 5      | 0.16%   |
| Vaseky                    | 3         | 3      | 0.12%   |
| SABRENT                   | 3         | 4      | 0.12%   |
| Lenovo                    | 3         | 4      | 0.12%   |
| KingSpec                  | 3         | 3      | 0.12%   |
| Indilinx                  | 3         | 3      | 0.12%   |
| ADATA Technology          | 3         | 3      | 0.12%   |
| Unknown                   | 3         | 3      | 0.12%   |
| UMIS                      | 2         | 2      | 0.08%   |
| Teclast                   | 2         | 2      | 0.08%   |
| StoreJet                  | 2         | 2      | 0.08%   |
| SSSTC                     | 2         | 2      | 0.08%   |
| Solid State Storage       | 2         | 2      | 0.08%   |
| RSH-339                   | 2         | 2      | 0.08%   |
| Realtek Semiconductor     | 2         | 3      | 0.08%   |
| OSCOO                     | 2         | 2      | 0.08%   |
| Netac                     | 2         | 2      | 0.08%   |
| LaCie                     | 2         | 2      | 0.08%   |
| KIOXIA-EXCERIA            | 2         | 2      | 0.08%   |
| KingFast                  | 2         | 2      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  32GB             | 40        | 1.42%   |
| Samsung NVMe SSD Drive 512GB       | 39        | 1.39%   |
| Unknown MMC Card  64GB             | 28        | 1%      |
| Toshiba MQ01ABD100 1TB             | 26        | 0.92%   |
| Samsung NVMe SSD Drive 500GB       | 26        | 0.92%   |
| Unknown MMC Card  128GB            | 23        | 0.82%   |
| Seagate ST1000LM035-1RK172 1TB     | 23        | 0.82%   |
| Kingston SA400S37240G 240GB SSD    | 22        | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB     | 19        | 0.68%   |
| Samsung SSD 860 EVO 500GB          | 19        | 0.68%   |
| Samsung NVMe SSD Drive 1TB         | 19        | 0.68%   |
| Toshiba DT01ACA100 1TB             | 16        | 0.57%   |
| Unknown SD/MMC/MS PRO 64GB         | 15        | 0.53%   |
| Samsung SSD 850 EVO 250GB          | 15        | 0.53%   |
| Seagate ST500LT012-1DG142 500GB    | 14        | 0.5%    |
| SanDisk NVMe SSD Drive 512GB       | 14        | 0.5%    |
| Samsung SSD 850 EVO 500GB          | 14        | 0.5%    |
| HGST HTS721010A9E630 1TB           | 14        | 0.5%    |
| Unknown MMC Card  16GB             | 13        | 0.46%   |
| Toshiba MQ01ABF050 500GB           | 13        | 0.46%   |
| Kingston SA400S37480G 480GB SSD    | 13        | 0.46%   |
| Intel NVMe SSD Drive 512GB         | 13        | 0.46%   |
| Toshiba MQ04ABF100 1TB             | 12        | 0.43%   |
| Seagate ST500DM002-1BD142 500GB    | 12        | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 12        | 0.43%   |
| Seagate Expansion 1TB              | 12        | 0.43%   |
| Samsung SSD 860 EVO 250GB          | 12        | 0.43%   |
| Kingston SA400S37120G 120GB SSD    | 12        | 0.43%   |
| SK hynix NVMe SSD Drive 512GB      | 11        | 0.39%   |
| Seagate ST2000DM001-1ER164 2TB     | 11        | 0.39%   |
| Seagate ST9500325AS 500GB          | 10        | 0.36%   |
| Seagate ST2000DM008-2FR102 2TB     | 10        | 0.36%   |
| SanDisk NVMe SSD Drive 1TB         | 10        | 0.36%   |
| Samsung SSD 860 EVO 1TB            | 10        | 0.36%   |
| Crucial CT1000MX500SSD1 1TB        | 10        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 9         | 0.32%   |
| Toshiba DT01ACA200 2TB             | 9         | 0.32%   |
| Seagate ST31000524AS 1TB           | 9         | 0.32%   |
| SanDisk SSD PLUS 240GB             | 9         | 0.32%   |
| Samsung SSD 840 EVO 250GB          | 9         | 0.32%   |
| Samsung NVMe SSD Drive 256GB       | 9         | 0.32%   |
| Samsung NVMe SSD Drive 250GB       | 9         | 0.32%   |
| HGST HTS545050A7E680 500GB         | 9         | 0.32%   |
| Crucial CT500MX500SSD1 500GB       | 9         | 0.32%   |
| Toshiba NVMe SSD Drive 512GB       | 8         | 0.28%   |
| Seagate ST4000DM004-2CV104 4TB     | 8         | 0.28%   |
| Seagate ST2000DM006-2DM164 2TB     | 8         | 0.28%   |
| SanDisk SSD PLUS 480GB             | 8         | 0.28%   |
| SanDisk NVMe SSD Drive 500GB       | 8         | 0.28%   |
| Kingston SV300S37A120G 120GB SSD   | 8         | 0.28%   |
| Intel NVMe SSD Drive 1024GB        | 8         | 0.28%   |
| WDC WD10EZEX-08WN4A0 1TB           | 7         | 0.25%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 7         | 0.25%   |
| Seagate ST3500418AS 500GB          | 7         | 0.25%   |
| Seagate ST1000DM003-1ER162 1TB     | 7         | 0.25%   |
| Samsung SSD 850 PRO 256GB          | 7         | 0.25%   |
| Micron/Crucial NVMe SSD Drive 1TB  | 7         | 0.25%   |
| JMicron Generic 2TB                | 7         | 0.25%   |
| Crucial CT120BX500SSD1 120GB       | 7         | 0.25%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 6         | 0.21%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 339       | 500    | 35.61%  |
| WDC                 | 277       | 415    | 29.1%   |
| Toshiba             | 125       | 155    | 13.13%  |
| Hitachi             | 70        | 87     | 7.35%   |
| Samsung Electronics | 43        | 56     | 4.52%   |
| HGST                | 41        | 51     | 4.31%   |
| Unknown             | 16        | 17     | 1.68%   |
| Maxtor              | 10        | 14     | 1.05%   |
| ASMT                | 9         | 11     | 0.95%   |
| Apple               | 4         | 6      | 0.42%   |
| SABRENT             | 3         | 4      | 0.32%   |
| RSH-339             | 2         | 2      | 0.21%   |
| Intenso             | 2         | 3      | 0.21%   |
| Fujitsu             | 2         | 2      | 0.21%   |
| USB3.0              | 1         | 1      | 0.11%   |
| Synology            | 1         | 8      | 0.11%   |
| StoreJet            | 1         | 1      | 0.11%   |
| JMicron Technology  | 1         | 3      | 0.11%   |
| Hewlett-Packard     | 1         | 1      | 0.11%   |
| Ext Hard            | 1         | 1      | 0.11%   |
| DELLBOSS            | 1         | 1      | 0.11%   |
| ASMT109x            | 1         | 1      | 0.11%   |
| ASMedia             | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 185       | 226    | 24.73%  |
| Kingston            | 89        | 107    | 11.9%   |
| SanDisk             | 85        | 100    | 11.36%  |
| Crucial             | 75        | 94     | 10.03%  |
| WDC                 | 42        | 43     | 5.61%   |
| A-DATA Technology   | 28        | 33     | 3.74%   |
| Intel               | 20        | 27     | 2.67%   |
| Micron Technology   | 18        | 21     | 2.41%   |
| Toshiba             | 16        | 18     | 2.14%   |
| LITEON              | 14        | 15     | 1.87%   |
| China               | 14        | 17     | 1.87%   |
| SPCC                | 13        | 16     | 1.74%   |
| Patriot             | 10        | 12     | 1.34%   |
| Transcend           | 8         | 9      | 1.07%   |
| SK hynix            | 7         | 7      | 0.94%   |
| PNY                 | 7         | 8      | 0.94%   |
| OCZ                 | 7         | 8      | 0.94%   |
| LITEONIT            | 7         | 9      | 0.94%   |
| Intenso             | 7         | 8      | 0.94%   |
| GOODRAM             | 7         | 8      | 0.94%   |
| Team                | 5         | 6      | 0.67%   |
| Mushkin             | 5         | 7      | 0.67%   |
| Hewlett-Packard     | 5         | 6      | 0.67%   |
| Apple               | 5         | 6      | 0.67%   |
| Plextor             | 4         | 4      | 0.53%   |
| Argon               | 4         | 5      | 0.53%   |
| Vaseky              | 3         | 3      | 0.4%    |
| Unknown             | 3         | 3      | 0.4%    |
| KingSpec            | 3         | 3      | 0.4%    |
| Gigabyte Technology | 3         | 3      | 0.4%    |
| Corsair             | 3         | 3      | 0.4%    |
| Teclast             | 2         | 2      | 0.27%   |
| OSCOO               | 2         | 2      | 0.27%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.27%   |
| KingDian            | 2         | 2      | 0.27%   |
| Indilinx            | 2         | 2      | 0.27%   |
| Dogfish             | 2         | 2      | 0.27%   |
| ASMT                | 2         | 5      | 0.27%   |
| Zozt                | 1         | 3      | 0.13%   |
| Zheino              | 1         | 2      | 0.13%   |
| Yeyian              | 1         | 1      | 0.13%   |
| Verbatim            | 1         | 1      | 0.13%   |
| Union Memory        | 1         | 1      | 0.13%   |
| TwinMOS             | 1         | 1      | 0.13%   |
| StoreJet            | 1         | 1      | 0.13%   |
| Smartbuy            | 1         | 1      | 0.13%   |
| Seagate             | 1         | 1      | 0.13%   |
| S3+                 | 1         | 1      | 0.13%   |
| Palit               | 1         | 1      | 0.13%   |
| OWC                 | 1         | 1      | 0.13%   |
| OCZ-VERTEX3         | 1         | 1      | 0.13%   |
| Netac               | 1         | 1      | 0.13%   |
| Lexar               | 1         | 1      | 0.13%   |
| Leven               | 1         | 1      | 0.13%   |
| Lenovo              | 1         | 2      | 0.13%   |
| LDLC                | 1         | 1      | 0.13%   |
| KLEVV               | 1         | 1      | 0.13%   |
| KINGBANK            | 1         | 1      | 0.13%   |
| KEEPDATA            | 1         | 2      | 0.13%   |
| JMicron Technology  | 1         | 2      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 790       | 1341   | 34.65%  |
| SSD     | 656       | 892    | 28.77%  |
| NVMe    | 647       | 842    | 28.38%  |
| MMC     | 142       | 177    | 6.23%   |
| Unknown | 45        | 60     | 1.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1173      | 2118   | 56.37%  |
| NVMe | 639       | 832    | 30.71%  |
| MMC  | 142       | 177    | 6.82%   |
| SAS  | 127       | 185    | 6.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 837       | 1244   | 54.6%   |
| 0.51-1.0   | 467       | 630    | 30.46%  |
| 1.01-2.0   | 136       | 212    | 8.87%   |
| 3.01-4.0   | 34        | 45     | 2.22%   |
| 4.01-10.0  | 28        | 44     | 1.83%   |
| 2.01-3.0   | 23        | 33     | 1.5%    |
| 10.01-20.0 | 8         | 25     | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 480       | 26.52%  |
| 251-500        | 441       | 24.36%  |
| 501-1000       | 279       | 15.41%  |
| 1001-2000      | 138       | 7.62%   |
| 51-100         | 138       | 7.62%   |
| 1-20           | 108       | 5.97%   |
| 21-50          | 88        | 4.86%   |
| More than 3000 | 82        | 4.53%   |
| 2001-3000      | 45        | 2.49%   |
| Unknown        | 11        | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 747       | 40.33%  |
| 21-50          | 346       | 18.68%  |
| 101-250        | 226       | 12.2%   |
| 51-100         | 224       | 12.1%   |
| 251-500        | 118       | 6.37%   |
| 501-1000       | 82        | 4.43%   |
| 1001-2000      | 47        | 2.54%   |
| More than 3000 | 36        | 1.94%   |
| 2001-3000      | 15        | 0.81%   |
| Unknown        | 11        | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB              | 3         | 3      | 3.16%   |
| WDC WD5000AAKX-001CA0 500GB                  | 2         | 2      | 2.11%   |
| Seagate ST500LM000-1EJ162 500GB              | 2         | 2      | 2.11%   |
| Seagate ST4000DM004-2CV104 4TB               | 2         | 3      | 2.11%   |
| SanDisk SSD PLUS 480GB                       | 2         | 2      | 2.11%   |
| Crucial CT240M500SSD1 240GB                  | 2         | 2      | 2.11%   |
| WDC WD7500BPKX-00HPJT0 752GB                 | 1         | 1      | 1.05%   |
| WDC WD7500AADS-00M2B0 752GB                  | 1         | 1      | 1.05%   |
| WDC WD6400AAKS-65A7B0 640GB                  | 1         | 1      | 1.05%   |
| WDC WD5000LPLX-60ZNTT1 500GB                 | 1         | 1      | 1.05%   |
| WDC WD5000AZRX-00A8LB0 500GB                 | 1         | 1      | 1.05%   |
| WDC WD5000AAKX-22ERMA0 500GB                 | 1         | 1      | 1.05%   |
| WDC WD5000AAKS-22A7B0 500GB                  | 1         | 1      | 1.05%   |
| WDC WD5000AAKS-00UU3A0 500GB                 | 1         | 1      | 1.05%   |
| WDC WD5000AADS-00S9B0 500GB                  | 1         | 1      | 1.05%   |
| WDC WD5000AADS-00L4B1 500GB                  | 1         | 1      | 1.05%   |
| WDC WD3200LPCX-24C6HT0 320GB                 | 1         | 1      | 1.05%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 1.05%   |
| WDC WD3200AAVS-00ZTB0 320GB                  | 1         | 1      | 1.05%   |
| WDC WD3200AAJS-60M0A0 320GB                  | 1         | 1      | 1.05%   |
| WDC WD20EZRZ-00Z5HB0 2TB                     | 1         | 1      | 1.05%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1         | 1      | 1.05%   |
| WDC WD15EARS-00S8B1 1TB                      | 1         | 1      | 1.05%   |
| WDC WD10SPZX-17Z10T0 1TB                     | 1         | 1      | 1.05%   |
| WDC WD10EZEX-60ZF5A0 1TB                     | 1         | 2      | 1.05%   |
| WDC WD10EZEX-08M2NA0 1TB                     | 1         | 1      | 1.05%   |
| WDC WD10EZEX-00WN4A0 1TB                     | 1         | 3      | 1.05%   |
| WDC WD10EADS-65M2B1 1TB                      | 1         | 1      | 1.05%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 1         | 1      | 1.05%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 1.05%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 1.05%   |
| Toshiba MK3263GSXN 320GB                     | 1         | 1      | 1.05%   |
| Toshiba MK3252GSX 320GB                      | 1         | 1      | 1.05%   |
| Toshiba DT01ACA100 1TB                       | 1         | 1      | 1.05%   |
| SK hynix HFS256G39TND-N210A 256GB SSD        | 1         | 1      | 1.05%   |
| Seagate ST9320423AS 320GB                    | 1         | 1      | 1.05%   |
| Seagate ST9250311CS 250GB                    | 1         | 1      | 1.05%   |
| Seagate ST500NM0011 39M4517 42C0468IBM 500GB | 1         | 1      | 1.05%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 1.05%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 1.05%   |
| Seagate ST3750640NS 752GB                    | 1         | 1      | 1.05%   |
| Seagate ST3750330NS 752GB                    | 1         | 1      | 1.05%   |
| Seagate ST3500830AS 500GB                    | 1         | 1      | 1.05%   |
| Seagate ST3500630AS 500GB                    | 1         | 1      | 1.05%   |
| Seagate ST3500414CS 500GB                    | 1         | 1      | 1.05%   |
| Seagate ST3320820AS 320GB                    | 1         | 1      | 1.05%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 1      | 1.05%   |
| Seagate ST2000DX002-2DV164 2TB               | 1         | 1      | 1.05%   |
| Seagate ST2000DM001-1CH164 2TB               | 1         | 1      | 1.05%   |
| Seagate ST2000DL003-9VT166 2TB               | 1         | 1      | 1.05%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 1.05%   |
| SanDisk SSD U100 128GB                       | 1         | 1      | 1.05%   |
| SanDisk SDSSDHII240G 240GB                   | 1         | 1      | 1.05%   |
| SanDisk SDSSDA240G 240GB                     | 1         | 1      | 1.05%   |
| SanDisk SD7SB3Q128G1002 128GB SSD            | 1         | 1      | 1.05%   |
| Samsung Electronics SSD 970 EVO 1TB          | 1         | 1      | 1.05%   |
| Samsung Electronics SSD 870 EVO 4TB          | 1         | 1      | 1.05%   |
| Samsung Electronics SSD 860 EVO 500GB        | 1         | 1      | 1.05%   |
| Samsung Electronics SSD 850 EVO 250GB        | 1         | 1      | 1.05%   |
| Samsung Electronics SSD 840 EVO 500GB        | 1         | 1      | 1.05%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 28     | 24.44%  |
| Seagate             | 21        | 24     | 23.33%  |
| Samsung Electronics | 7         | 7      | 7.78%   |
| SanDisk             | 6         | 6      | 6.67%   |
| Toshiba             | 5         | 5      | 5.56%   |
| Micron Technology   | 4         | 6      | 4.44%   |
| Kingston            | 4         | 4      | 4.44%   |
| Intel               | 4         | 4      | 4.44%   |
| Crucial             | 4         | 4      | 4.44%   |
| Hitachi             | 3         | 3      | 3.33%   |
| OCZ                 | 2         | 2      | 2.22%   |
| A-DATA Technology   | 2         | 2      | 2.22%   |
| SK hynix            | 1         | 1      | 1.11%   |
| Plextor             | 1         | 1      | 1.11%   |
| LITEONIT            | 1         | 1      | 1.11%   |
| HGST                | 1         | 1      | 1.11%   |
| Fujitsu             | 1         | 1      | 1.11%   |
| Anobit              | 1         | 1      | 1.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 28     | 40%     |
| Seagate             | 21        | 24     | 38.18%  |
| Toshiba             | 5         | 5      | 9.09%   |
| Hitachi             | 3         | 3      | 5.45%   |
| Samsung Electronics | 2         | 2      | 3.64%   |
| HGST                | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 54        | 64     | 61.36%  |
| SSD  | 30        | 33     | 34.09%  |
| NVMe | 4         | 4      | 4.55%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB     | 1         | 1      | 50%     |
| JMicron Technology Tech 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 1         | 1      | 50%     |
| JMicron Technology | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1250      | 2342   | 66.52%  |
| Works    | 542       | 867    | 28.85%  |
| Malfunc  | 85        | 101    | 4.52%   |
| Failed   | 2         | 2      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1118      | 51.1%   |
| AMD                            | 313       | 14.31%  |
| Samsung Electronics            | 203       | 9.28%   |
| SanDisk                        | 115       | 5.26%   |
| SK hynix                       | 67        | 3.06%   |
| Toshiba America Info Systems   | 50        | 2.29%   |
| Phison Electronics             | 36        | 1.65%   |
| Nvidia                         | 30        | 1.37%   |
| Kingston Technology Company    | 28        | 1.28%   |
| KIOXIA                         | 27        | 1.23%   |
| ASMedia Technology             | 26        | 1.19%   |
| Silicon Motion                 | 25        | 1.14%   |
| Marvell Technology Group       | 23        | 1.05%   |
| Micron/Crucial Technology      | 20        | 0.91%   |
| Micron Technology              | 20        | 0.91%   |
| JMicron Technology             | 17        | 0.78%   |
| ADATA Technology               | 17        | 0.78%   |
| Union Memory (Shenzhen)        | 6         | 0.27%   |
| Hewlett-Packard                | 6         | 0.27%   |
| LSI Logic / Symbios Logic      | 5         | 0.23%   |
| Broadcom / LSI                 | 5         | 0.23%   |
| Solid State Storage Technology | 4         | 0.18%   |
| Silicon Image                  | 4         | 0.18%   |
| Realtek Semiconductor          | 4         | 0.18%   |
| Unknown                        | 3         | 0.14%   |
| Apple                          | 3         | 0.14%   |
| VIA Technologies               | 2         | 0.09%   |
| Lenovo                         | 2         | 0.09%   |
| Huawei Technologies            | 2         | 0.09%   |
| Adaptec                        | 2         | 0.09%   |
| Shenzhen Longsys Electronics   | 1         | 0.05%   |
| Seagate Technology             | 1         | 0.05%   |
| Promise Technology             | 1         | 0.05%   |
| Lite-On Technology             | 1         | 0.05%   |
| Lite-On IT Corp. / Plextor     | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 202       | 8.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 103       | 4.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 78        | 3.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 75        | 2.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 64        | 2.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 61        | 2.43%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 60        | 2.39%   |
| Samsung NVMe SSD Controller 980                                                         | 53        | 2.11%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 43        | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 42        | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 39        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 39        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 39        | 1.55%   |
| AMD 400 Series Chipset SATA Controller                                                  | 37        | 1.47%   |
| Intel SATA Controller [RAID mode]                                                       | 33        | 1.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 33        | 1.31%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 33        | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 33        | 1.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 32        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 30        | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 30        | 1.19%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 28        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 26        | 1.03%   |
| Intel SSD 660P Series                                                                   | 26        | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 25        | 0.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 25        | 0.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 25        | 0.99%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 24        | 0.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 24        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 24        | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                                  | 24        | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 23        | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 23        | 0.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 22        | 0.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 22        | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 22        | 0.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 22        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 22        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 22        | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 21        | 0.84%   |
| SK hynix BC511                                                                          | 20        | 0.8%    |
| Phison E12 NVMe Controller                                                              | 20        | 0.8%    |
| Micron Non-Volatile memory controller                                                   | 20        | 0.8%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 19        | 0.76%   |
| SK hynix Gold P31 SSD                                                                   | 18        | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 18        | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 18        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 18        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18        | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 17        | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 17        | 0.68%   |
| Intel Non-Volatile memory controller                                                    | 16        | 0.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 16        | 0.64%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 16        | 0.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 15        | 0.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 0.56%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 13        | 0.52%   |
| Kingston Company A2000 NVMe SSD                                                         | 13        | 0.52%   |
| SK hynix Non-Volatile memory controller                                                 | 12        | 0.48%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 12        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1194      | 53.42%  |
| NVMe | 642       | 28.72%  |
| IDE  | 200       | 8.95%   |
| RAID | 184       | 8.23%   |
| SAS  | 10        | 0.45%   |
| SCSI | 5         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 1277      | 72.19%  |
| AMD       | 401       | 22.67%  |
| ARM       | 88        | 4.97%   |
| QUALCOMM  | 1         | 0.06%   |
| HiSilicon | 1         | 0.06%   |
| Unknown   | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 87        | 4.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 41        | 2.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 26        | 1.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 25        | 1.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 20        | 1.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 0.96%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 0.9%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 16        | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 15        | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 14        | 0.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 14        | 0.79%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 14        | 0.79%   |
| AMD Ryzen 5 3600 6-Core Processor             | 14        | 0.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 0.73%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 13        | 0.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 0.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 12        | 0.68%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 12        | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 10        | 0.56%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 10        | 0.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 9         | 0.51%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 9         | 0.51%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.51%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 9         | 0.51%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 9         | 0.51%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 0.51%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 0.51%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 9         | 0.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.51%   |
| AMD FX-8350 Eight-Core Processor              | 9         | 0.51%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.45%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 8         | 0.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.45%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 8         | 0.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 0.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 8         | 0.45%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 8         | 0.45%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 8         | 0.45%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 8         | 0.45%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 0.45%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 8         | 0.45%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 7         | 0.4%    |
| Intel Core i7-8700K CPU @ 3.70GHz             | 7         | 0.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 0.4%    |
| Intel Core i5-4570 CPU @ 3.20GHz              | 7         | 0.4%    |
| Intel Core i5-4460 CPU @ 3.20GHz              | 7         | 0.4%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 7         | 0.4%    |
| Intel Core i5-10400F CPU @ 2.90GHz            | 7         | 0.4%    |
| Intel Core i3-2100 CPU @ 3.10GHz              | 7         | 0.4%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 7         | 0.4%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 7         | 0.4%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.4%    |
| Intel Core i7-3770K CPU @ 3.50GHz             | 6         | 0.34%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 6         | 0.34%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 6         | 0.34%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 6         | 0.34%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 6         | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 375       | 21.19%  |
| Intel Core i7                        | 340       | 19.21%  |
| Other                                | 205       | 11.58%  |
| Intel Core i3                        | 124       | 7.01%   |
| AMD Ryzen 5                          | 92        | 5.2%    |
| AMD Ryzen 7                          | 81        | 4.58%   |
| Intel Celeron                        | 69        | 3.9%    |
| Intel Core 2 Duo                     | 66        | 3.73%   |
| Intel Xeon                           | 42        | 2.37%   |
| Intel Pentium                        | 38        | 2.15%   |
| AMD FX                               | 28        | 1.58%   |
| Intel Atom                           | 26        | 1.47%   |
| AMD Ryzen 9                          | 26        | 1.47%   |
| Intel Core i9                        | 23        | 1.3%    |
| AMD Ryzen 3                          | 23        | 1.3%    |
| Intel Pentium Dual-Core              | 18        | 1.02%   |
| AMD Ryzen 7 PRO                      | 13        | 0.73%   |
| Intel Core 2 Quad                    | 12        | 0.68%   |
| AMD A6                               | 12        | 0.68%   |
| AMD A10                              | 12        | 0.68%   |
| AMD A4                               | 11        | 0.62%   |
| AMD Phenom II X4                     | 8         | 0.45%   |
| AMD Athlon 64 X2                     | 8         | 0.45%   |
| AMD A8                               | 8         | 0.45%   |
| AMD Athlon II X2                     | 7         | 0.4%    |
| AMD Athlon                           | 7         | 0.4%    |
| Intel Pentium Silver                 | 6         | 0.34%   |
| Intel Core 2                         | 6         | 0.34%   |
| AMD Ryzen Threadripper               | 6         | 0.34%   |
| AMD E                                | 6         | 0.34%   |
| Intel Pentium Dual                   | 5         | 0.28%   |
| Intel Pentium 4                      | 4         | 0.23%   |
| AMD Phenom II X6                     | 4         | 0.23%   |
| AMD Phenom                           | 4         | 0.23%   |
| AMD E2                               | 4         | 0.23%   |
| AMD E1                               | 4         | 0.23%   |
| Intel Pentium D                      | 3         | 0.17%   |
| AMD Ryzen 5 PRO                      | 3         | 0.17%   |
| AMD Athlon II X4                     | 3         | 0.17%   |
| Intel Core m7                        | 2         | 0.11%   |
| Intel Core m3                        | 2         | 0.11%   |
| Intel Core 2 Extreme                 | 2         | 0.11%   |
| AMD Sempron                          | 2         | 0.11%   |
| AMD PRO A10                          | 2         | 0.11%   |
| AMD C-60                             | 2         | 0.11%   |
| AMD Athlon X4                        | 2         | 0.11%   |
| AMD Athlon X2                        | 2         | 0.11%   |
| AMD A12                              | 2         | 0.11%   |
| QUALCOMM AArch64                     | 1         | 0.06%   |
| Intel Pentium Gold                   | 1         | 0.06%   |
| Intel Genuine                        | 1         | 0.06%   |
| Intel Core M                         | 1         | 0.06%   |
| Intel Celeron D                      | 1         | 0.06%   |
| ARM AArch64                          | 1         | 0.06%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.06%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.06%   |
| AMD Turion II Neo                    | 1         | 0.06%   |
| AMD Turion 64 X2 Mobile              | 1         | 0.06%   |
| AMD Ryzen 3 PRO                      | 1         | 0.06%   |
| AMD Phenom II X3                     | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 744       | 42.03%  |
| 2       | 616       | 34.8%   |
| 6       | 179       | 10.11%  |
| 8       | 150       | 8.47%   |
| 1       | 20        | 1.13%   |
| 3       | 14        | 0.79%   |
| 12      | 12        | 0.68%   |
| 10      | 12        | 0.68%   |
| 16      | 8         | 0.45%   |
| 24      | 5         | 0.28%   |
| 32      | 3         | 0.17%   |
| 128     | 1         | 0.06%   |
| 96      | 1         | 0.06%   |
| 64      | 1         | 0.06%   |
| 40      | 1         | 0.06%   |
| 36      | 1         | 0.06%   |
| 14      | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1748      | 98.81%  |
| 2       | 17        | 0.96%   |
| 6       | 1         | 0.06%   |
| 4       | 1         | 0.06%   |
| 3       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1165      | 65.86%  |
| 1       | 603       | 34.09%  |
| Unknown | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1689      | 95.48%  |
| Unknown        | 78        | 4.41%   |
| 64-bit         | 2         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1083      | 59.93%  |
| 0x806c1    | 70        | 3.87%   |
| 0x306a9    | 41        | 2.27%   |
| 0x806ec    | 40        | 2.21%   |
| 0x306c3    | 35        | 1.94%   |
| 0x806ea    | 33        | 1.83%   |
| 0x906ea    | 28        | 1.55%   |
| 0x206a7    | 22        | 1.22%   |
| 0x906e9    | 21        | 1.16%   |
| 0x806e9    | 21        | 1.16%   |
| 0x08600104 | 20        | 1.11%   |
| 0xa0652    | 19        | 1.05%   |
| 0x706e5    | 19        | 1.05%   |
| 0x0a50000c | 17        | 0.94%   |
| 0x406e3    | 16        | 0.89%   |
| 0x08600106 | 16        | 0.89%   |
| 0x08108109 | 16        | 0.89%   |
| 0x506e3    | 14        | 0.77%   |
| 0x1067a    | 13        | 0.72%   |
| 0x08701021 | 13        | 0.72%   |
| 0x906ed    | 11        | 0.61%   |
| 0x806d1    | 11        | 0.61%   |
| 0x40651    | 10        | 0.55%   |
| 0x306d4    | 10        | 0.55%   |
| 0x08608103 | 10        | 0.55%   |
| 0xa0655    | 9         | 0.5%    |
| 0xa0653    | 9         | 0.5%    |
| 0x30678    | 9         | 0.5%    |
| 0x806eb    | 8         | 0.44%   |
| 0x20655    | 8         | 0.44%   |
| 0x406c4    | 7         | 0.39%   |
| 0x0a201016 | 7         | 0.39%   |
| 0x08600103 | 7         | 0.39%   |
| 0xa0671    | 6         | 0.33%   |
| 0x706a8    | 5         | 0.28%   |
| 0x20652    | 5         | 0.28%   |
| 0x106e5    | 5         | 0.28%   |
| 0x0a201009 | 5         | 0.28%   |
| 0x08108102 | 5         | 0.28%   |
| 0x0800820d | 5         | 0.28%   |
| 0x06000852 | 5         | 0.28%   |
| 0xa0660    | 4         | 0.22%   |
| 0x906eb    | 4         | 0.22%   |
| 0x706a1    | 4         | 0.22%   |
| 0x406c3    | 4         | 0.22%   |
| 0x0a50000b | 4         | 0.22%   |
| 0x08608102 | 4         | 0.22%   |
| 0x0810100b | 4         | 0.22%   |
| 0x06006705 | 4         | 0.22%   |
| 0x6fd      | 3         | 0.17%   |
| 0x206d7    | 3         | 0.17%   |
| 0x106a5    | 3         | 0.17%   |
| 0x08701013 | 3         | 0.17%   |
| 0x010000c8 | 3         | 0.17%   |
| 0x506c9    | 2         | 0.11%   |
| 0x0a201006 | 2         | 0.11%   |
| 0x08200103 | 2         | 0.11%   |
| 0x08001137 | 2         | 0.11%   |
| 0x07030105 | 2         | 0.11%   |
| 0x0600611a | 2         | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 311       | 17.57%  |
| Haswell         | 133       | 7.51%   |
| IvyBridge       | 130       | 7.34%   |
| Unknown         | 117       | 6.61%   |
| SandyBridge     | 107       | 6.05%   |
| Zen 2           | 99        | 5.59%   |
| TigerLake       | 89        | 5.03%   |
| Penryn          | 82        | 4.63%   |
| Skylake         | 81        | 4.58%   |
| CometLake       | 67        | 3.79%   |
| Silvermont      | 56        | 3.16%   |
| Zen+            | 53        | 2.99%   |
| Westmere        | 49        | 2.77%   |
| Zen 3           | 48        | 2.71%   |
| Icelake         | 45        | 2.54%   |
| Piledriver      | 42        | 2.37%   |
| Zen             | 34        | 1.92%   |
| K10             | 33        | 1.86%   |
| Core            | 33        | 1.86%   |
| Broadwell       | 32        | 1.81%   |
| Goldmont plus   | 19        | 1.07%   |
| Nehalem         | 18        | 1.02%   |
| Excavator       | 17        | 0.96%   |
| K8 Hammer       | 11        | 0.62%   |
| Puma            | 10        | 0.56%   |
| Bobcat          | 10        | 0.56%   |
| Goldmont        | 9         | 0.51%   |
| NetBurst        | 8         | 0.45%   |
| Steamroller     | 6         | 0.34%   |
| Jaguar          | 6         | 0.34%   |
| K10 Llano       | 5         | 0.28%   |
| K8 & K10 hybrid | 4         | 0.23%   |
| Bulldozer       | 4         | 0.23%   |
| Bonnell         | 2         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 969       | 49.14%  |
| Nvidia                                       | 548       | 27.79%  |
| AMD                                          | 440       | 22.31%  |
| Matrox Electronics Systems                   | 8         | 0.41%   |
| ASPEED Technology                            | 5         | 0.25%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.05%   |
| Huawei Technologies                          | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 82        | 4.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 74        | 3.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 65        | 3.23%   |
| AMD Renoir                                                                               | 53        | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 49        | 2.43%   |
| Intel UHD Graphics 620                                                                   | 46        | 2.28%   |
| Intel HD Graphics 620                                                                    | 42        | 2.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 39        | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 37        | 1.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 33        | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 32        | 1.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 31        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 30        | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 30        | 1.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 30        | 1.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 1.44%   |
| Intel HD Graphics 530                                                                    | 27        | 1.34%   |
| AMD Cezanne                                                                              | 26        | 1.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 25        | 1.24%   |
| Intel HD Graphics 5500                                                                   | 24        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 21        | 1.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 20        | 0.99%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 20        | 0.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 0.99%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 19        | 0.94%   |
| Intel HD Graphics 630                                                                    | 19        | 0.94%   |
| AMD Lucienne                                                                             | 19        | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 16        | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 12        | 0.6%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 12        | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 12        | 0.6%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 12        | 0.6%    |
| Nvidia GP108M [GeForce MX250]                                                            | 11        | 0.55%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 11        | 0.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 11        | 0.55%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 11        | 0.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 10        | 0.5%    |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 0.5%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 0.5%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 10        | 0.5%    |
| Intel Iris Plus Graphics G7                                                              | 10        | 0.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 10        | 0.5%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 9         | 0.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.45%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 9         | 0.45%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 9         | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.4%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 8         | 0.4%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 8         | 0.4%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 8         | 0.4%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8         | 0.4%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 7         | 0.35%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 712       | 40.18%  |
| 1 x AMD                 | 354       | 19.98%  |
| 1 x Nvidia              | 305       | 17.21%  |
| Intel + Nvidia          | 203       | 11.46%  |
| Other                   | 89        | 5.02%   |
| Intel + AMD             | 36        | 2.03%   |
| AMD + Nvidia            | 29        | 1.64%   |
| 2 x AMD                 | 17        | 0.96%   |
| 2 x Nvidia              | 9         | 0.51%   |
| 1 x Matrox              | 7         | 0.4%    |
| 1 x ASPEED              | 3         | 0.17%   |
| 2 x Intel               | 2         | 0.11%   |
| AMD + ASPEED            | 2         | 0.11%   |
| 1 x XGI                 | 1         | 0.06%   |
| Nvidia + Matrox         | 1         | 0.06%   |
| 1 x Intel + 4 x AMD     | 1         | 0.06%   |
| 1 x Huawei Technologies | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1365      | 76.39%  |
| Proprietary | 284       | 15.89%  |
| Unknown     | 138       | 7.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1341      | 75.08%  |
| 1.01-2.0   | 129       | 7.22%   |
| 3.01-4.0   | 78        | 4.37%   |
| 0.01-0.5   | 77        | 4.31%   |
| 0.51-1.0   | 58        | 3.25%   |
| 7.01-8.0   | 43        | 2.41%   |
| 5.01-6.0   | 33        | 1.85%   |
| 8.01-16.0  | 18        | 1.01%   |
| 2.01-3.0   | 8         | 0.45%   |
| 0          | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 247       | 12.81%  |
| AU Optronics            | 236       | 12.24%  |
| LG Display              | 164       | 8.51%   |
| BOE                     | 157       | 8.14%   |
| Chimei Innolux          | 141       | 7.31%   |
| Dell                    | 117       | 6.07%   |
| Goldstar                | 90        | 4.67%   |
| Acer                    | 79        | 4.1%    |
| Hewlett-Packard         | 68        | 3.53%   |
| Sharp                   | 53        | 2.75%   |
| Ancor Communications    | 46        | 2.39%   |
| Philips                 | 41        | 2.13%   |
| BenQ                    | 40        | 2.07%   |
| AOC                     | 35        | 1.82%   |
| Apple                   | 33        | 1.71%   |
| Lenovo                  | 27        | 1.4%    |
| Iiyama                  | 24        | 1.24%   |
| Unknown                 | 23        | 1.19%   |
| Chi Mei Optoelectronics | 21        | 1.09%   |
| LG Electronics          | 19        | 0.99%   |
| Sony                    | 18        | 0.93%   |
| PANDA                   | 18        | 0.93%   |
| ViewSonic               | 17        | 0.88%   |
| InfoVision              | 13        | 0.67%   |
| NEC Computers           | 10        | 0.52%   |
| ASUSTek Computer        | 10        | 0.52%   |
| Fujitsu Siemens         | 9         | 0.47%   |
| HannStar                | 8         | 0.41%   |
| Panasonic               | 7         | 0.36%   |
| Sceptre Tech            | 6         | 0.31%   |
| Medion                  | 6         | 0.31%   |
| Hitachi                 | 6         | 0.31%   |
| Vestel Elektronik       | 5         | 0.26%   |
| TMX                     | 5         | 0.26%   |
| RTK                     | 5         | 0.26%   |
| CSO                     | 5         | 0.26%   |
| Toshiba                 | 4         | 0.21%   |
| LGD                     | 4         | 0.21%   |
| LG Philips              | 4         | 0.21%   |
| Eizo                    | 4         | 0.21%   |
| Unknown (XXX)           | 3         | 0.16%   |
| MiTAC                   | 3         | 0.16%   |
| JDI                     | 3         | 0.16%   |
| Idek Iiyama             | 3         | 0.16%   |
| CHR                     | 3         | 0.16%   |
| Westinghouse            | 2         | 0.1%    |
| Vizio                   | 2         | 0.1%    |
| Viotek                  | 2         | 0.1%    |
| SKY                     | 2         | 0.1%    |
| Sceptre                 | 2         | 0.1%    |
| ONN                     | 2         | 0.1%    |
| MSI                     | 2         | 0.1%    |
| KDC                     | 2         | 0.1%    |
| IPS                     | 2         | 0.1%    |
| HPN                     | 2         | 0.1%    |
| Denver                  | 2         | 0.1%    |
| DENON                   | 2         | 0.1%    |
| CPT                     | 2         | 0.1%    |
| BOE Technology Group    | 2         | 0.1%    |
| AUS                     | 2         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.6%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 10        | 0.5%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 6         | 0.3%    |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 6         | 0.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 6         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 6         | 0.3%    |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 5         | 0.25%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                  | 5         | 0.25%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 5         | 0.25%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 5         | 0.25%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 5         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 5         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch         | 5         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.25%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                    | 5         | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 5         | 0.25%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 4         | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 4         | 0.2%    |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                  | 4         | 0.2%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.2%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 4         | 0.2%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.2%    |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 4         | 0.2%    |
| Dell P2417H DELA0DC 1920x1080 530x300mm 24.0-inch                        | 4         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch          | 4         | 0.2%    |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 4         | 0.2%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.2%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 4         | 0.2%    |
| AU Optronics LCD Monitor AUOA08B 1920x1080 344x193mm 15.5-inch           | 4         | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.2%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 4         | 0.2%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.2%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 3         | 0.15%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 3         | 0.15%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 3         | 0.15%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 3         | 0.15%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                        | 3         | 0.15%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 3         | 0.15%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 3         | 0.15%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch  | 3         | 0.15%   |
| Samsung Electronics EPSON PJ SECA603 1920x1080 1600x900mm 72.3-inch      | 3         | 0.15%   |
| RTK CX101 RTK1010 1920x1200 220x130mm 10.1-inch                          | 3         | 0.15%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                  | 3         | 0.15%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 3         | 0.15%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch             | 3         | 0.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.15%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch             | 3         | 0.15%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch             | 3         | 0.15%   |
| LG Display LCD Monitor LGD03EE 1366x768 277x156mm 12.5-inch              | 3         | 0.15%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.15%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 3         | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 862       | 46.72%  |
| 1366x768 (WXGA)    | 294       | 15.93%  |
| 3840x2160 (4K)     | 125       | 6.78%   |
| 2560x1440 (QHD)    | 76        | 4.12%   |
| 1600x900 (HD+)     | 70        | 3.79%   |
| 1280x1024 (SXGA)   | 56        | 3.04%   |
| 1680x1050 (WSXGA+) | 44        | 2.38%   |
| 1920x1200 (WUXGA)  | 40        | 2.17%   |
| 1440x900 (WXGA+)   | 38        | 2.06%   |
| Unknown            | 37        | 2.01%   |
| 1280x800 (WXGA)    | 33        | 1.79%   |
| 3440x1440          | 19        | 1.03%   |
| 2560x1080          | 15        | 0.81%   |
| 2560x1600          | 13        | 0.7%    |
| 1360x768           | 13        | 0.7%    |
| 1920x540           | 10        | 0.54%   |
| 3840x1080          | 9         | 0.49%   |
| 3000x2000          | 8         | 0.43%   |
| 3840x2400          | 7         | 0.38%   |
| 3200x2000          | 5         | 0.27%   |
| 2160x1440          | 5         | 0.27%   |
| 1600x1200          | 5         | 0.27%   |
| 1280x720 (HD)      | 5         | 0.27%   |
| 5760x2160          | 4         | 0.22%   |
| 4480x1440          | 4         | 0.22%   |
| 3200x1800 (QHD+)   | 4         | 0.22%   |
| 5120x1440          | 3         | 0.16%   |
| 3520x1080          | 3         | 0.16%   |
| 3456x2160          | 3         | 0.16%   |
| 2736x1824          | 3         | 0.16%   |
| 2256x1504          | 3         | 0.16%   |
| 5760x1080          | 2         | 0.11%   |
| 2304x1440          | 2         | 0.11%   |
| 2048x1152          | 2         | 0.11%   |
| 1920x1280          | 2         | 0.11%   |
| 1024x768 (XGA)     | 2         | 0.11%   |
| 6400x2160          | 1         | 0.05%   |
| 5760x1200          | 1         | 0.05%   |
| 4608x1440          | 1         | 0.05%   |
| 4480x1200          | 1         | 0.05%   |
| 4480x1080          | 1         | 0.05%   |
| 4240x1440          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 3640x1920          | 1         | 0.05%   |
| 3600x1080          | 1         | 0.05%   |
| 3280x1050          | 1         | 0.05%   |
| 2880x1800          | 1         | 0.05%   |
| 2880x1200          | 1         | 0.05%   |
| 2800x1752          | 1         | 0.05%   |
| 2560x2520          | 1         | 0.05%   |
| 2048x1536          | 1         | 0.05%   |
| 1826x1027          | 1         | 0.05%   |
| 1680x945           | 1         | 0.05%   |
| 1360x765           | 1         | 0.05%   |
| 1280x768           | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 451       | 23.56%  |
| 13      | 196       | 10.24%  |
| 14      | 153       | 7.99%   |
| 24      | 141       | 7.37%   |
| 27      | 136       | 7.11%   |
| Unknown | 133       | 6.95%   |
| 23      | 125       | 6.53%   |
| 21      | 103       | 5.38%   |
| 17      | 96        | 5.02%   |
| 19      | 63        | 3.29%   |
| 31      | 46        | 2.4%    |
| 12      | 30        | 1.57%   |
| 34      | 27        | 1.41%   |
| 18      | 27        | 1.41%   |
| 22      | 26        | 1.36%   |
| 20      | 22        | 1.15%   |
| 84      | 21        | 1.1%    |
| 11      | 21        | 1.1%    |
| 54      | 12        | 0.63%   |
| 32      | 12        | 0.63%   |
| 72      | 10        | 0.52%   |
| 40      | 9         | 0.47%   |
| 16      | 8         | 0.42%   |
| 48      | 5         | 0.26%   |
| 26      | 5         | 0.26%   |
| 25      | 5         | 0.26%   |
| 10      | 4         | 0.21%   |
| 65      | 3         | 0.16%   |
| 43      | 3         | 0.16%   |
| 49      | 2         | 0.1%    |
| 47      | 2         | 0.1%    |
| 28      | 2         | 0.1%    |
| 86      | 1         | 0.05%   |
| 75      | 1         | 0.05%   |
| 69      | 1         | 0.05%   |
| 66      | 1         | 0.05%   |
| 57      | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 52      | 1         | 0.05%   |
| 50      | 1         | 0.05%   |
| 46      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 39      | 1         | 0.05%   |
| 36      | 1         | 0.05%   |
| 35      | 1         | 0.05%   |
| 30      | 1         | 0.05%   |
| 29      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 689       | 36.51%  |
| 501-600     | 378       | 20.03%  |
| 401-500     | 203       | 10.76%  |
| 201-300     | 171       | 9.06%   |
| Unknown     | 133       | 7.05%   |
| 351-400     | 132       | 7%      |
| 601-700     | 64        | 3.39%   |
| 701-800     | 38        | 2.01%   |
| 1501-2000   | 34        | 1.8%    |
| 1001-1500   | 29        | 1.54%   |
| 801-900     | 13        | 0.69%   |
| 901-1000    | 3         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1296      | 75.13%  |
| 16/10   | 188       | 10.9%   |
| Unknown | 114       | 6.61%   |
| 5/4     | 50        | 2.9%    |
| 21/9    | 31        | 1.8%    |
| 3/2     | 27        | 1.57%   |
| 4/3     | 10        | 0.58%   |
| 32/9    | 4         | 0.23%   |
| 6/5     | 3         | 0.17%   |
| 1.96    | 1         | 0.06%   |
| 0.45    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 450       | 23.66%  |
| 201-250        | 317       | 16.67%  |
| 81-90          | 255       | 13.41%  |
| 301-350        | 141       | 7.41%   |
| Unknown        | 133       | 6.99%   |
| 151-200        | 117       | 6.15%   |
| 71-80          | 95        | 4.99%   |
| 351-500        | 84        | 4.42%   |
| 121-130        | 75        | 3.94%   |
| More than 1000 | 59        | 3.1%    |
| 251-300        | 50        | 2.63%   |
| 141-150        | 37        | 1.95%   |
| 61-70          | 27        | 1.42%   |
| 51-60          | 21        | 1.1%    |
| 501-1000       | 21        | 1.1%    |
| 111-120        | 8         | 0.42%   |
| 41-50          | 4         | 0.21%   |
| 131-140        | 4         | 0.21%   |
| 91-100         | 4         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 573       | 30.97%  |
| 121-160       | 476       | 25.73%  |
| 101-120       | 428       | 23.14%  |
| Unknown       | 133       | 7.19%   |
| 161-240       | 120       | 6.49%   |
| More than 240 | 66        | 3.57%   |
| 1-50          | 54        | 2.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1370      | 76.58%  |
| 2     | 298       | 16.66%  |
| 0     | 96        | 5.37%   |
| 3     | 23        | 1.29%   |
| 4     | 2         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 876       | 35.22%  |
| Intel                             | 873       | 35.1%   |
| Qualcomm Atheros                  | 277       | 11.14%  |
| Broadcom                          | 133       | 5.35%   |
| Marvell Technology Group          | 28        | 1.13%   |
| TP-Link                           | 27        | 1.09%   |
| Ralink Technology                 | 25        | 1.01%   |
| Broadcom Limited                  | 24        | 0.97%   |
| Ralink                            | 22        | 0.88%   |
| Nvidia                            | 21        | 0.84%   |
| MediaTek                          | 18        | 0.72%   |
| Lenovo                            | 11        | 0.44%   |
| Samsung Electronics               | 10        | 0.4%    |
| ASUSTek Computer                  | 9         | 0.36%   |
| Dell                              | 8         | 0.32%   |
| Hewlett-Packard                   | 7         | 0.28%   |
| Qualcomm Atheros Communications   | 6         | 0.24%   |
| JMicron Technology                | 6         | 0.24%   |
| DisplayLink                       | 6         | 0.24%   |
| D-Link                            | 6         | 0.24%   |
| ASIX Electronics                  | 6         | 0.24%   |
| Sierra Wireless                   | 5         | 0.2%    |
| NetGear                           | 5         | 0.2%    |
| Huawei Technologies               | 5         | 0.2%    |
| Ericsson Business Mobile Networks | 5         | 0.2%    |
| Edimax Technology                 | 5         | 0.2%    |
| D-Link System                     | 5         | 0.2%    |
| Xiaomi                            | 4         | 0.16%   |
| OnePlus Technology (Shenzhen)     | 3         | 0.12%   |
| Motorola PCS                      | 3         | 0.12%   |
| Microsoft                         | 3         | 0.12%   |
| Arduino SA                        | 3         | 0.12%   |
| Aquantia                          | 3         | 0.12%   |
| U-Blox                            | 2         | 0.08%   |
| Sitecom Europe                    | 2         | 0.08%   |
| Qualcomm                          | 2         | 0.08%   |
| Mellanox Technologies             | 2         | 0.08%   |
| IMC Networks                      | 2         | 0.08%   |
| Google                            | 2         | 0.08%   |
| Fibocom                           | 2         | 0.08%   |
| BUFFALO                           | 2         | 0.08%   |
| AVM                               | 2         | 0.08%   |
| Uniden                            | 1         | 0.04%   |
| Texas Instruments                 | 1         | 0.04%   |
| STMicroelectronics                | 1         | 0.04%   |
| Solarflare Communications         | 1         | 0.04%   |
| Sigma Designs                     | 1         | 0.04%   |
| Seeed Technology                  | 1         | 0.04%   |
| Microchip Technology              | 1         | 0.04%   |
| Linksys                           | 1         | 0.04%   |
| LG Electronics                    | 1         | 0.04%   |
| Leaflabs                          | 1         | 0.04%   |
| ICS Advent                        | 1         | 0.04%   |
| IBM                               | 1         | 0.04%   |
| Holtek Semiconductor              | 1         | 0.04%   |
| Guillemot                         | 1         | 0.04%   |
| Elecom                            | 1         | 0.04%   |
| Davicom Semiconductor             | 1         | 0.04%   |
| Belkin Components                 | 1         | 0.04%   |
| Belkin                            | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 603       | 20.69%  |
| Intel Wi-Fi 6 AX200                                               | 113       | 3.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 88        | 3.02%   |
| Intel Wi-Fi 6 AX201                                               | 75        | 2.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 57        | 1.96%   |
| Intel Wireless 8265 / 8275                                        | 48        | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 43        | 1.48%   |
| Intel Wireless 7265                                               | 43        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 43        | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 1.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 37        | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 37        | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 36        | 1.23%   |
| Intel I211 Gigabit Network Connection                             | 35        | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 34        | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.13%   |
| Intel Wireless 7260                                               | 33        | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 31        | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 30        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 1.03%   |
| Intel Wireless 8260                                               | 29        | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 27        | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 25        | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 24        | 0.82%   |
| Intel Wireless 3165                                               | 23        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 22        | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 21        | 0.72%   |
| Intel Wireless-AC 9260                                            | 18        | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 18        | 0.62%   |
| Intel Ethernet Controller I225-V                                  | 18        | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 18        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 17        | 0.58%   |
| Intel Centrino Advanced-N 6235                                    | 17        | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                     | 17        | 0.58%   |
| Intel Wireless 3160                                               | 16        | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 16        | 0.55%   |
| Intel 82579V Gigabit Network Connection                           | 16        | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 15        | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 14        | 0.48%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 14        | 0.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 13        | 0.45%   |
| Ralink MT7601U Wireless Adapter                                   | 13        | 0.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 13        | 0.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 12        | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 12        | 0.41%   |
| Intel WiFi Link 5100                                              | 12        | 0.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 12        | 0.41%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 12        | 0.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.41%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.41%   |
| Realtek 802.11ac NIC                                              | 11        | 0.38%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 10        | 0.34%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 10        | 0.34%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.34%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.34%   |
| Intel Ethernet Connection (10) I219-V                             | 10        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 689       | 50.22%  |
| Qualcomm Atheros                | 218       | 15.89%  |
| Realtek Semiconductor           | 205       | 14.94%  |
| Broadcom                        | 95        | 6.92%   |
| Ralink Technology               | 25        | 1.82%   |
| TP-Link                         | 23        | 1.68%   |
| Ralink                          | 21        | 1.53%   |
| Broadcom Limited                | 16        | 1.17%   |
| MediaTek                        | 15        | 1.09%   |
| ASUSTek Computer                | 8         | 0.58%   |
| Qualcomm Atheros Communications | 6         | 0.44%   |
| D-Link                          | 6         | 0.44%   |
| Sierra Wireless                 | 5         | 0.36%   |
| Edimax Technology               | 5         | 0.36%   |
| NetGear                         | 4         | 0.29%   |
| Dell                            | 4         | 0.29%   |
| Microsoft                       | 3         | 0.22%   |
| Marvell Technology Group        | 3         | 0.22%   |
| D-Link System                   | 3         | 0.22%   |
| Sitecom Europe                  | 2         | 0.15%   |
| Qualcomm                        | 2         | 0.15%   |
| IMC Networks                    | 2         | 0.15%   |
| Fibocom                         | 2         | 0.15%   |
| BUFFALO                         | 2         | 0.15%   |
| AVM                             | 2         | 0.15%   |
| Linksys                         | 1         | 0.07%   |
| Hewlett-Packard                 | 1         | 0.07%   |
| Guillemot                       | 1         | 0.07%   |
| Elecom                          | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |
| Belkin                          | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 113       | 8.18%   |
| Intel Wi-Fi 6 AX201                                            | 75        | 5.43%   |
| Intel Wireless 8265 / 8275                                     | 48        | 3.48%   |
| Intel Wireless 7265                                            | 43        | 3.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 43        | 3.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 39        | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 37        | 2.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 37        | 2.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 34        | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 33        | 2.39%   |
| Intel Wireless 7260                                            | 33        | 2.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 31        | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 30        | 2.17%   |
| Intel Wireless 8260                                            | 29        | 2.1%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 27        | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 25        | 1.81%   |
| Intel Wireless 3165                                            | 23        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 22        | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 1.52%   |
| Intel Wireless-AC 9260                                         | 18        | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 18        | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 18        | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 17        | 1.23%   |
| Intel Centrino Advanced-N 6235                                 | 17        | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                  | 17        | 1.23%   |
| Intel Wireless 3160                                            | 16        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 14        | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 13        | 0.94%   |
| Ralink MT7601U Wireless Adapter                                | 13        | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 13        | 0.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 12        | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 12        | 0.87%   |
| Intel WiFi Link 5100                                           | 12        | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 12        | 0.87%   |
| Realtek 802.11ac NIC                                           | 11        | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10        | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 10        | 0.72%   |
| Intel Centrino Wireless-N 2230                                 | 10        | 0.72%   |
| Intel Centrino Advanced-N 6200                                 | 10        | 0.72%   |
| TP-Link 802.11ac NIC                                           | 9         | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 9         | 0.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 9         | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 8         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 7         | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 7         | 0.51%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 7         | 0.51%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 7         | 0.51%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 7         | 0.51%   |
| Intel Centrino Ultimate-N 6300                                 | 6         | 0.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 5         | 0.36%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 0.36%   |
| Qualcomm Atheros AR9271 802.11n                                | 5         | 0.36%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 5         | 0.36%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 5         | 0.36%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter             | 5         | 0.36%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 5         | 0.36%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 785       | 53.11%  |
| Intel                         | 412       | 27.88%  |
| Qualcomm Atheros              | 82        | 5.55%   |
| Broadcom                      | 63        | 4.26%   |
| Marvell Technology Group      | 25        | 1.69%   |
| Nvidia                        | 21        | 1.42%   |
| Lenovo                        | 11        | 0.74%   |
| Samsung Electronics           | 10        | 0.68%   |
| Broadcom Limited              | 8         | 0.54%   |
| JMicron Technology            | 6         | 0.41%   |
| DisplayLink                   | 6         | 0.41%   |
| ASIX Electronics              | 6         | 0.41%   |
| Xiaomi                        | 4         | 0.27%   |
| TP-Link                       | 4         | 0.27%   |
| Huawei Technologies           | 4         | 0.27%   |
| Hewlett-Packard               | 4         | 0.27%   |
| Motorola PCS                  | 3         | 0.2%    |
| MediaTek                      | 3         | 0.2%    |
| Aquantia                      | 3         | 0.2%    |
| Mellanox Technologies         | 2         | 0.14%   |
| Google                        | 2         | 0.14%   |
| D-Link System                 | 2         | 0.14%   |
| Solarflare Communications     | 1         | 0.07%   |
| OnePlus Technology (Shenzhen) | 1         | 0.07%   |
| NetGear                       | 1         | 0.07%   |
| Microchip Technology          | 1         | 0.07%   |
| LG Electronics                | 1         | 0.07%   |
| ICS Advent                    | 1         | 0.07%   |
| IBM                           | 1         | 0.07%   |
| Davicom Semiconductor         | 1         | 0.07%   |
| ASUSTek Computer              | 1         | 0.07%   |
| Apple                         | 1         | 0.07%   |
| American Megatrends           | 1         | 0.07%   |
| ADMtek                        | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 603       | 40.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 88        | 5.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 57        | 3.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 43        | 2.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 36        | 2.39%   |
| Intel I211 Gigabit Network Connection                             | 35        | 2.32%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 1.99%   |
| Intel Ethernet Connection I217-LM                                 | 24        | 1.59%   |
| Intel Ethernet Controller I225-V                                  | 18        | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 1.13%   |
| Intel Ethernet Connection (7) I219-V                              | 16        | 1.06%   |
| Intel 82579V Gigabit Network Connection                           | 16        | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.8%    |
| Intel Ethernet Connection I217-V                                  | 12        | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.8%    |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.8%    |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.66%   |
| Intel Ethernet Connection (10) I219-V                             | 10        | 0.66%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 9         | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 9         | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 9         | 0.6%    |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 9         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 8         | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 8         | 0.53%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 8         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 0.46%   |
| Nvidia MCP79 Ethernet                                             | 7         | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.46%   |
| Nvidia MCP77 Ethernet                                             | 6         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.4%    |
| Lenovo USB-C Dock Ethernet                                        | 6         | 0.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 6         | 0.4%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.33%   |
| Intel Ethernet Connection (10) I219-LM                            | 5         | 0.33%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 4         | 0.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 0.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.27%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.27%   |
| Lenovo ThinkPad Lan                                               | 4         | 0.27%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.27%   |
| Intel Ethernet Connection (14) I219-V                             | 4         | 0.27%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.27%   |
| Intel Ethernet Connection (13) I219-LM                            | 4         | 0.27%   |
| Intel Ethernet Connection (12) I219-V                             | 4         | 0.27%   |
| Intel Ethernet Connection (11) I219-LM                            | 4         | 0.27%   |
| Intel 82567V-2 Gigabit Network Connection                         | 4         | 0.27%   |
| HP lt4120 Snapdragon X5 LTE                                       | 4         | 0.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1381      | 50.57%  |
| WiFi     | 1323      | 48.44%  |
| Modem    | 22        | 0.81%   |
| Unknown  | 5         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1070      | 61%     |
| Ethernet | 684       | 39%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 906       | 51.13%  |
| 1     | 702       | 39.62%  |
| 0     | 117       | 6.6%    |
| 3     | 36        | 2.03%   |
| 4     | 7         | 0.4%    |
| 6     | 2         | 0.11%   |
| 5     | 2         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1284      | 72.05%  |
| Yes  | 498       | 27.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 591       | 53.05%  |
| Realtek Semiconductor           | 107       | 9.61%   |
| Qualcomm Atheros Communications | 83        | 7.45%   |
| Cambridge Silicon Radio         | 71        | 6.37%   |
| Broadcom                        | 52        | 4.67%   |
| Apple                           | 35        | 3.14%   |
| IMC Networks                    | 34        | 3.05%   |
| Lite-On Technology              | 23        | 2.06%   |
| Foxconn / Hon Hai               | 23        | 2.06%   |
| ASUSTek Computer                | 20        | 1.8%    |
| Dell                            | 15        | 1.35%   |
| Realtek                         | 10        | 0.9%    |
| Hewlett-Packard                 | 9         | 0.81%   |
| Toshiba                         | 7         | 0.63%   |
| Ralink                          | 7         | 0.63%   |
| Belkin Components               | 4         | 0.36%   |
| Alps Electric                   | 4         | 0.36%   |
| Marvell Semiconductor           | 3         | 0.27%   |
| Dynex                           | 3         | 0.27%   |
| Ralink Technology               | 2         | 0.18%   |
| Foxconn International           | 2         | 0.18%   |
| Unknown                         | 1         | 0.09%   |
| Taiyo Yuden                     | 1         | 0.09%   |
| Qcom                            | 1         | 0.09%   |
| Primax Electronics              | 1         | 0.09%   |
| Logitech                        | 1         | 0.09%   |
| Integrated System Solution      | 1         | 0.09%   |
| Conwise Technology              | 1         | 0.09%   |
| Chicony Electronics             | 1         | 0.09%   |
| Askey Computer                  | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 187       | 16.79%  |
| Intel AX201 Bluetooth                                    | 140       | 12.57%  |
| Intel AX200 Bluetooth                                    | 104       | 9.34%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 84        | 7.54%   |
| Realtek Bluetooth Radio                                  | 77        | 6.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 71        | 6.37%   |
| Qualcomm Atheros  Bluetooth Device                       | 56        | 5.03%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 26        | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                           | 23        | 2.06%   |
| Intel Bluetooth Device                                   | 22        | 1.97%   |
| Intel Wireless-AC 3168 Bluetooth                         | 16        | 1.44%   |
| Apple Bluetooth USB Host Controller                      | 14        | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 13        | 1.17%   |
| Intel AX210 Bluetooth                                    | 12        | 1.08%   |
| IMC Networks Bluetooth Radio                             | 12        | 1.08%   |
| Apple Bluetooth Host Controller                          | 11        | 0.99%   |
| Realtek Bluetooth Radio                                  | 10        | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                        | 10        | 0.9%    |
| IMC Networks Wireless_Device                             | 10        | 0.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 10        | 0.9%    |
| Lite-On Bluetooth Device                                 | 9         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                       | 9         | 0.81%   |
| Broadcom BCM2045B (BDC-2.1)                              | 9         | 0.81%   |
| Ralink RT3290 Bluetooth                                  | 7         | 0.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 7         | 0.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 6         | 0.54%   |
| IMC Networks Bluetooth Device                            | 6         | 0.54%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 6         | 0.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 6         | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                         | 5         | 0.45%   |
| HP Broadcom 2070 Bluetooth Combo                         | 5         | 0.45%   |
| Foxconn / Hon Hai BCM20702A0                             | 5         | 0.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 5         | 0.45%   |
| Dell Wireless 365 Bluetooth                              | 4         | 0.36%   |
| Dell DW375 Bluetooth Module                              | 4         | 0.36%   |
| Broadcom HP Portable SoftSailing                         | 4         | 0.36%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 4         | 0.36%   |
| Broadcom BCM2045 Bluetooth                               | 4         | 0.36%   |
| ASUS BT-253 Bluetooth Adapter                            | 4         | 0.36%   |
| ASUS ASUS USB-BT500                                      | 4         | 0.36%   |
| Realtek RTL8821A Bluetooth                               | 3         | 0.27%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 3         | 0.27%   |
| Marvell Bluetooth and Wireless LAN Composite             | 3         | 0.27%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 3         | 0.27%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 3         | 0.27%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller          | 3         | 0.27%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 3         | 0.27%   |
| Dell BCM20702A0 Bluetooth Module                         | 3         | 0.27%   |
| Apple Bluetooth HCI                                      | 3         | 0.27%   |
| Toshiba RT Bluetooth Radio                               | 2         | 0.18%   |
| Toshiba Bluetooth Device                                 | 2         | 0.18%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 2         | 0.18%   |
| Lite-On Wireless_Device                                  | 2         | 0.18%   |
| Foxconn International BCM43142A0 Bluetooth module        | 2         | 0.18%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 2         | 0.18%   |
| ASUS BT-270 Bluetooth Adapter                            | 2         | 0.18%   |
| ASUS Bluetooth Radio                                     | 2         | 0.18%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)          | 2         | 0.18%   |
| Unknown Bluetooth Device                                 | 1         | 0.09%   |
| Toshiba BCM43142A0                                       | 1         | 0.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1211      | 53.28%  |
| AMD                                             | 474       | 20.85%  |
| Nvidia                                          | 394       | 17.33%  |
| C-Media Electronics                             | 31        | 1.36%   |
| Logitech                                        | 13        | 0.57%   |
| Texas Instruments                               | 10        | 0.44%   |
| Creative Labs                                   | 10        | 0.44%   |
| GN Netcom                                       | 9         | 0.4%    |
| Lenovo                                          | 8         | 0.35%   |
| Focusrite-Novation                              | 8         | 0.35%   |
| Realtek Semiconductor                           | 6         | 0.26%   |
| Creative Technology                             | 6         | 0.26%   |
| ASUSTek Computer                                | 6         | 0.26%   |
| SteelSeries ApS                                 | 5         | 0.22%   |
| Samson Technologies                             | 5         | 0.22%   |
| JMTek                                           | 5         | 0.22%   |
| Sennheiser Communications                       | 4         | 0.18%   |
| Kingston Technology                             | 4         | 0.18%   |
| RODE Microphones                                | 3         | 0.13%   |
| Razer USA                                       | 3         | 0.13%   |
| Plantronics                                     | 3         | 0.13%   |
| Licensed by Sony Computer Entertainment America | 3         | 0.13%   |
| Hewlett-Packard                                 | 3         | 0.13%   |
| Generalplus Technology                          | 3         | 0.13%   |
| VIA Technologies                                | 2         | 0.09%   |
| Microsoft                                       | 2         | 0.09%   |
| Micro Star International                        | 2         | 0.09%   |
| GYROCOM C&C                                     | 2         | 0.09%   |
| DEXP BK-20                                      | 2         | 0.09%   |
| Dell                                            | 2         | 0.09%   |
| Bose                                            | 2         | 0.09%   |
| Astro Gaming                                    | 2         | 0.09%   |
| ZOOM                                            | 1         | 0.04%   |
| Yealink Network Technology                      | 1         | 0.04%   |
| Yamaha                                          | 1         | 0.04%   |
| Unknown                                         | 1         | 0.04%   |
| Sony                                            | 1         | 0.04%   |
| Pixart Imaging                                  | 1         | 0.04%   |
| Numark                                          | 1         | 0.04%   |
| No brand                                        | 1         | 0.04%   |
| MAG Technology                                  | 1         | 0.04%   |
| Mad Catz                                        | 1         | 0.04%   |
| KYE Systems (Mouse Systems)                     | 1         | 0.04%   |
| IK Multimedia                                   | 1         | 0.04%   |
| iConnectivity                                   | 1         | 0.04%   |
| Holtek Semiconductor                            | 1         | 0.04%   |
| Fry's Electronics                               | 1         | 0.04%   |
| Elitegroup Computer Systems (ECS)               | 1         | 0.04%   |
| Elite Silicon                                   | 1         | 0.04%   |
| Earth Computer Technologies                     | 1         | 0.04%   |
| DCMT Technology                                 | 1         | 0.04%   |
| Datelink Technology                             | 1         | 0.04%   |
| Corsair                                         | 1         | 0.04%   |
| Cambridge Silicon Radio                         | 1         | 0.04%   |
| C&T                                             | 1         | 0.04%   |
| Blue Microphones                                | 1         | 0.04%   |
| BEHRINGER International                         | 1         | 0.04%   |
| Barco Display Systems                           | 1         | 0.04%   |
| Asahi Kasei Microsystems                        | 1         | 0.04%   |
| Apple                                           | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 160       | 5.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 132       | 4.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 126       | 4.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 96        | 3.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 89        | 3.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 87        | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 69        | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 65        | 2.41%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 63        | 2.34%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 63        | 2.34%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 56        | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 55        | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 53        | 1.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 52        | 1.93%   |
| AMD FCH Azalia Controller                                                                         | 46        | 1.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 43        | 1.6%    |
| Intel 8 Series HD Audio Controller                                                                | 40        | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 39        | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 38        | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 38        | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 35        | 1.3%    |
| Intel Comet Lake PCH cAVS                                                                         | 34        | 1.26%   |
| Intel 200 Series PCH HD Audio                                                                     | 32        | 1.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 30        | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 29        | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 29        | 1.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 29        | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 28        | 1.04%   |
| Intel Broadwell-U Audio Controller                                                                | 28        | 1.04%   |
| Nvidia High Definition Audio Controller                                                           | 27        | 1%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 26        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 25        | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 25        | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 24        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 24        | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 23        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 21        | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 20        | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 19        | 0.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 19        | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 18        | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 18        | 0.67%   |
| Intel CM238 HD Audio Controller                                                                   | 18        | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 17        | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 0.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 17        | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 16        | 0.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.59%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 16        | 0.59%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 15        | 0.56%   |
| Intel Audio device                                                                                | 15        | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 14        | 0.52%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 14        | 0.52%   |
| AMD Navi 10 HDMI Audio                                                                            | 14        | 0.52%   |
| Nvidia TU104 HD Audio Controller                                                                  | 13        | 0.48%   |
| AMD Trinity HDMI Audio Controller                                                                 | 13        | 0.48%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 13        | 0.48%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 12        | 0.45%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 12        | 0.45%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 12        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 218       | 23.98%  |
| SK hynix                     | 170       | 18.7%   |
| Micron Technology            | 120       | 13.2%   |
| Kingston                     | 110       | 12.1%   |
| Unknown                      | 62        | 6.82%   |
| Corsair                      | 51        | 5.61%   |
| Crucial                      | 49        | 5.39%   |
| G.Skill                      | 36        | 3.96%   |
| Ramaxel Technology           | 13        | 1.43%   |
| A-DATA Technology            | 12        | 1.32%   |
| Team                         | 9         | 0.99%   |
| Elpida                       | 9         | 0.99%   |
| Nanya Technology             | 8         | 0.88%   |
| Unknown (ABCD)               | 5         | 0.55%   |
| Smart                        | 5         | 0.55%   |
| Patriot                      | 3         | 0.33%   |
| Avant                        | 3         | 0.33%   |
| Unknown (09D5)               | 2         | 0.22%   |
| Transcend                    | 2         | 0.22%   |
| Neo Forza                    | 2         | 0.22%   |
| GOODRAM                      | 2         | 0.22%   |
| Apacer                       | 2         | 0.22%   |
| Wilk Elektronik              | 1         | 0.11%   |
| Vaseky                       | 1         | 0.11%   |
| Unknown (F785)               | 1         | 0.11%   |
| Unknown (0x0702)             | 1         | 0.11%   |
| Unknown (08AE)               | 1         | 0.11%   |
| Unifosa                      | 1         | 0.11%   |
| Teikon                       | 1         | 0.11%   |
| Spectek                      | 1         | 0.11%   |
| Smart Modular                | 1         | 0.11%   |
| SHARETRONIC                  | 1         | 0.11%   |
| Patriot Memory (PDP Systems) | 1         | 0.11%   |
| Mushkin                      | 1         | 0.11%   |
| J&A Information              | 1         | 0.11%   |
| High Bridge                  | 1         | 0.11%   |
| Golden Empire                | 1         | 0.11%   |
| Exceleram                    | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 13        | 1.34%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 11        | 1.13%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 11        | 1.13%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 11        | 1.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 10        | 1.03%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 9         | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 8         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 8         | 0.82%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 7         | 0.72%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 7         | 0.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 0.62%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.62%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 6         | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 6         | 0.62%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s               | 6         | 0.62%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 5         | 0.51%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.51%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s      | 5         | 0.51%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 0.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 5         | 0.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 5         | 0.51%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 5         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 5         | 0.51%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 4         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s    | 4         | 0.41%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 4         | 0.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 0.41%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 0.41%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 4         | 0.41%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 0.41%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s           | 4         | 0.41%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.41%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s               | 4         | 0.41%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s            | 4         | 0.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 4         | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 3         | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                           | 3         | 0.31%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 3         | 0.31%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 3         | 0.31%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                          | 3         | 0.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.31%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s          | 3         | 0.31%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 3         | 0.31%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 3         | 0.31%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 0.31%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 0.31%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 0.31%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 3         | 0.31%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 3         | 0.31%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.31%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                         | 3         | 0.31%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 3         | 0.31%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 3         | 0.31%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                         | 3         | 0.31%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 477       | 59.77%  |
| DDR3    | 198       | 24.81%  |
| LPDDR4  | 44        | 5.51%   |
| LPDDR3  | 42        | 5.26%   |
| DDR2    | 15        | 1.88%   |
| SDRAM   | 8         | 1%      |
| Unknown | 8         | 1%      |
| DDR     | 5         | 0.63%   |
| DRAM    | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 468       | 57.78%  |
| DIMM         | 225       | 27.78%  |
| Row Of Chips | 114       | 14.07%  |
| Chip         | 2         | 0.25%   |
| Unknown      | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 350       | 41.03%  |
| 4096  | 234       | 27.43%  |
| 16384 | 143       | 16.76%  |
| 2048  | 76        | 8.91%   |
| 32768 | 35        | 4.1%    |
| 1024  | 12        | 1.41%   |
| 512   | 2         | 0.23%   |
| 65536 | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 201       | 23.37%  |
| 2667    | 159       | 18.49%  |
| 1600    | 129       | 15%     |
| 2400    | 56        | 6.51%   |
| 2133    | 54        | 6.28%   |
| 1333    | 47        | 5.47%   |
| 4267    | 31        | 3.6%    |
| 3600    | 25        | 2.91%   |
| 1334    | 20        | 2.33%   |
| 1867    | 19        | 2.21%   |
| 3466    | 12        | 1.4%    |
| 800     | 12        | 1.4%    |
| 3000    | 9         | 1.05%   |
| 3266    | 8         | 0.93%   |
| Unknown | 7         | 0.81%   |
| 8400    | 6         | 0.7%    |
| 3733    | 6         | 0.7%    |
| 2933    | 6         | 0.7%    |
| 2800    | 6         | 0.7%    |
| 2666    | 5         | 0.58%   |
| 1066    | 5         | 0.58%   |
| 667     | 5         | 0.58%   |
| 1067    | 4         | 0.47%   |
| 2048    | 3         | 0.35%   |
| 4266    | 2         | 0.23%   |
| 4199    | 2         | 0.23%   |
| 3800    | 2         | 0.23%   |
| 3400    | 2         | 0.23%   |
| 3334    | 2         | 0.23%   |
| 975     | 2         | 0.23%   |
| 333     | 2         | 0.23%   |
| 3500    | 1         | 0.12%   |
| 3100    | 1         | 0.12%   |
| 3066    | 1         | 0.12%   |
| 2934    | 1         | 0.12%   |
| 1866    | 1         | 0.12%   |
| 1800    | 1         | 0.12%   |
| 1777    | 1         | 0.12%   |
| 1400    | 1         | 0.12%   |
| 533     | 1         | 0.12%   |
| 400     | 1         | 0.12%   |
| 266     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Hewlett-Packard                    | 19        | 36.54%  |
| Canon                              | 10        | 19.23%  |
| Brother Industries                 | 6         | 11.54%  |
| Seiko Epson                        | 4         | 7.69%   |
| Samsung Electronics                | 3         | 5.77%   |
| Lexmark International              | 2         | 3.85%   |
| Kyocera                            | 2         | 3.85%   |
| Dymo-CoStar                        | 2         | 3.85%   |
| Zhuhai Poskey Technology           | 1         | 1.92%   |
| Zebra                              | 1         | 1.92%   |
| Xerox                              | 1         | 1.92%   |
| BeiJing LanXum Computer Technology | 1         | 1.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP ENVY 5000 series                                     | 2         | 3.85%   |
| HP DeskJet 3700 series                                  | 2         | 3.85%   |
| Canon PIXMA MG3600 Series                               | 2         | 3.85%   |
| Brother HL-5250DN Printer                               | 2         | 3.85%   |
| Zhuhai Poskey Printer                                   | 1         | 1.92%   |
| Zebra LP2844 Printer                                    | 1         | 1.92%   |
| Xerox WorkCentre 3119 Series                            | 1         | 1.92%   |
| Seiko Epson XP-4100 Series                              | 1         | 1.92%   |
| Seiko Epson WF-2510 Series                              | 1         | 1.92%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F  | 1         | 1.92%   |
| Seiko Epson L395 Series                                 | 1         | 1.92%   |
| Samsung SCX-3400 Series                                 | 1         | 1.92%   |
| Samsung ML-1450                                         | 1         | 1.92%   |
| Samsung Composite Device                                | 1         | 1.92%   |
| Lexmark International Lexmark MC2425adw                 | 1         | 1.92%   |
| Lexmark International InkJet Color Printer              | 1         | 1.92%   |
| Kyocera FS-3920DN                                       | 1         | 1.92%   |
| Kyocera FS-1370DN                                       | 1         | 1.92%   |
| HP OfficeJet 6950                                       | 1         | 1.92%   |
| HP Officejet 4500 G510g-m                               | 1         | 1.92%   |
| HP LaserJet Professional P1102w                         | 1         | 1.92%   |
| HP LaserJet P1005                                       | 1         | 1.92%   |
| HP LaserJet M14-M17                                     | 1         | 1.92%   |
| HP LaserJet M101-M106                                   | 1         | 1.92%   |
| HP LaserJet 400 M401dne                                 | 1         | 1.92%   |
| HP LaserJet 3050                                        | 1         | 1.92%   |
| HP LaserJet 1020                                        | 1         | 1.92%   |
| HP LaserJet 1010                                        | 1         | 1.92%   |
| HP ENVY Photo 6200 series                               | 1         | 1.92%   |
| HP DeskJet Plus 4100 series                             | 1         | 1.92%   |
| HP Deskjet F4500 series                                 | 1         | 1.92%   |
| HP DeskJet 970c/970cse                                  | 1         | 1.92%   |
| HP Deskjet 3050 J610 series                             | 1         | 1.92%   |
| Dymo-CoStar LabelWriter 400                             | 1         | 1.92%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                  | 1         | 1.92%   |
| Canon TS8000 series                                     | 1         | 1.92%   |
| Canon TR4500 series                                     | 1         | 1.92%   |
| Canon PRO-100 series                                    | 1         | 1.92%   |
| Canon PIXMA TS6250                                      | 1         | 1.92%   |
| Canon PIXMA iP5300 Printer                              | 1         | 1.92%   |
| Canon LiDE 400                                          | 1         | 1.92%   |
| Canon LBP6030/6030B/6018L                               | 1         | 1.92%   |
| Canon iP8700 series                                     | 1         | 1.92%   |
| Brother QL-550 printer                                  | 1         | 1.92%   |
| Brother Printer                                         | 1         | 1.92%   |
| Brother MFC-J480DW                                      | 1         | 1.92%   |
| Brother DCP-L2540DW                                     | 1         | 1.92%   |
| BeiJing LanXum Technology Black and White Laser Printer | 1         | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 9         | 75%     |
| Ultima Electronics | 1         | 8.33%   |
| Seiko Epson        | 1         | 8.33%   |
| Mustek Systems     | 1         | 8.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30         | 3         | 25%     |
| Canon CanoScan LiDE 120               | 2         | 16.67%  |
| Ultima Artec Ultima 2000              | 1         | 8.33%   |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 8.33%   |
| Mustek Systems BearPaw 2448 CU Pro    | 1         | 8.33%   |
| Canon CanoScan N670U/N676U/LiDE 20    | 1         | 8.33%   |
| Canon CanoScan LiDE 700F              | 1         | 8.33%   |
| Canon CanoScan LiDE 600F              | 1         | 8.33%   |
| Canon CanoScan LiDE 210               | 1         | 8.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                            | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Electronics                               | 236       | 21.49%  |
| Microdia                                          | 112       | 10.2%   |
| Realtek Semiconductor                             | 100       | 9.11%   |
| IMC Networks                                      | 96        | 8.74%   |
| Acer                                              | 62        | 5.65%   |
| Logitech                                          | 61        | 5.56%   |
| Sunplus Innovation Technology                     | 58        | 5.28%   |
| Quanta                                            | 47        | 4.28%   |
| Cheng Uei Precision Industry (Foxlink)            | 42        | 3.83%   |
| Apple                                             | 39        | 3.55%   |
| Lite-On Technology                                | 32        | 2.91%   |
| Suyin                                             | 30        | 2.73%   |
| Syntek                                            | 23        | 2.09%   |
| Silicon Motion                                    | 16        | 1.46%   |
| Luxvisions Innotech Limited                       | 14        | 1.28%   |
| Samsung Electronics                               | 12        | 1.09%   |
| Alcor Micro                                       | 10        | 0.91%   |
| Microsoft                                         | 9         | 0.82%   |
| Ricoh                                             | 8         | 0.73%   |
| Generalplus Technology                            | 8         | 0.73%   |
| GEMBIRD                                           | 5         | 0.46%   |
| Unknown                                           | 4         | 0.36%   |
| Lenovo                                            | 4         | 0.36%   |
| Creative Technology                               | 4         | 0.36%   |
| 2M UVC CAMERA                                     | 4         | 0.36%   |
| Z-Star Microelectronics                           | 3         | 0.27%   |
| Primax Electronics                                | 3         | 0.27%   |
| OmniVision Technologies                           | 3         | 0.27%   |
| Importek                                          | 3         | 0.27%   |
| Guillemot                                         | 3         | 0.27%   |
| Cubeternet                                        | 3         | 0.27%   |
| ARC International                                 | 3         | 0.27%   |
| Trust                                             | 2         | 0.18%   |
| Sunplus Technology                                | 2         | 0.18%   |
| Razer USA                                         | 2         | 0.18%   |
| MacroSilicon                                      | 2         | 0.18%   |
| LG Electronics                                    | 2         | 0.18%   |
| Intel                                             | 2         | 0.18%   |
| Huawei Technologies                               | 2         | 0.18%   |
| Genesys Logic                                     | 2         | 0.18%   |
| AVerMedia Technologies                            | 2         | 0.18%   |
| Xiongmai                                          | 1         | 0.09%   |
| SunplusIT                                         | 1         | 0.09%   |
| STMicroelectronics Imaging Division (VLSI Vision) | 1         | 0.09%   |
| Sonix Technology                                  | 1         | 0.09%   |
| RYS                                               | 1         | 0.09%   |
| PrehKeyTec                                        | 1         | 0.09%   |
| Polycom                                           | 1         | 0.09%   |
| Pixart Imaging                                    | 1         | 0.09%   |
| Philips (or NXP)                                  | 1         | 0.09%   |
| OPPO Electronics                                  | 1         | 0.09%   |
| Motorola PCS                                      | 1         | 0.09%   |
| Magic Control Technology                          | 1         | 0.09%   |
| kingcome                                          | 1         | 0.09%   |
| Jieli Technology                                  | 1         | 0.09%   |
| IPEVO                                             | 1         | 0.09%   |
| Etron Technology                                  | 1         | 0.09%   |
| DJJHNA29IE70D3                                    | 1         | 0.09%   |
| CKCamera                                          | 1         | 0.09%   |
| Aveo Technology                                   | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 62        | 5.64%   |
| Realtek Integrated_Webcam_HD                        | 52        | 4.73%   |
| Chicony Integrated Camera                           | 51        | 4.64%   |
| IMC Networks Integrated Camera                      | 39        | 3.55%   |
| Chicony HD Webcam                                   | 26        | 2.37%   |
| Acer Integrated Camera                              | 24        | 2.18%   |
| Sunplus Integrated_Webcam_HD                        | 21        | 1.91%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 21        | 1.91%   |
| Syntek Integrated Camera                            | 15        | 1.36%   |
| Logitech Webcam C270                                | 14        | 1.27%   |
| Apple Built-in iSight                               | 14        | 1.27%   |
| Quanta HD User Facing                               | 13        | 1.18%   |
| Samsung Galaxy A5 (MTP)                             | 12        | 1.09%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 10        | 0.91%   |
| Chicony USB2.0 Camera                               | 10        | 0.91%   |
| Chicony TOSHIBA Web Camera - HD                     | 9         | 0.82%   |
| Chicony HP Wide Vision HD Camera                    | 9         | 0.82%   |
| Chicony HP HD Camera                                | 9         | 0.82%   |
| Apple iPhone 5/5C/5S/6/SE                           | 9         | 0.82%   |
| Realtek USB Camera                                  | 8         | 0.73%   |
| Quanta HP TrueVision HD Camera                      | 8         | 0.73%   |
| Logitech HD Pro Webcam C920                         | 8         | 0.73%   |
| Lite-On HP HD Camera                                | 8         | 0.73%   |
| Chicony USB 2.0 Camera                              | 8         | 0.73%   |
| Microdia Amcrest AWC2198 USB Webcam                 | 7         | 0.64%   |
| Logitech HD Webcam C525                             | 7         | 0.64%   |
| Chicony USB2.0 HD UVC WebCam                        | 7         | 0.64%   |
| Chicony Lenovo EasyCamera                           | 7         | 0.64%   |
| Chicony Integrated HP HD Webcam                     | 7         | 0.64%   |
| Chicony HP TrueVision HD                            | 7         | 0.64%   |
| Chicony HD User Facing                              | 7         | 0.64%   |
| Chicony EasyCamera                                  | 7         | 0.64%   |
| Apple FaceTime HD Camera (Built-in)                 | 7         | 0.64%   |
| Apple FaceTime HD Camera                            | 7         | 0.64%   |
| Acer Lenovo EasyCamera                              | 7         | 0.64%   |
| Sunplus HD WebCam                                   | 6         | 0.55%   |
| Quanta HP HD Camera                                 | 6         | 0.55%   |
| Lite-On Integrated Camera                           | 6         | 0.55%   |
| Generalplus WEB CAM                                 | 6         | 0.55%   |
| Chicony FJ Camera                                   | 6         | 0.55%   |
| Acer BisonCam, NB Pro                               | 6         | 0.55%   |
| Realtek Integrated Webcam                           | 5         | 0.45%   |
| Quanta HP Wide Vision HD Camera                     | 5         | 0.45%   |
| Microdia Laptop_Integrated_Webcam_HD                | 5         | 0.45%   |
| Microdia Integrated Webcam                          | 5         | 0.45%   |
| Microdia Camera                                     | 5         | 0.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 0.45%   |
| Logitech Webcam C310                                | 5         | 0.45%   |
| Lite-On HP Wide Vision HD Camera                    | 5         | 0.45%   |
| Lite-On HP HD Webcam                                | 5         | 0.45%   |
| IMC Networks ov9734_azurewave_camera                | 5         | 0.45%   |
| IMC Networks Integrated Webcam                      | 5         | 0.45%   |
| Chicony HP Webcam                                   | 5         | 0.45%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 5         | 0.45%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 5         | 0.45%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 5         | 0.45%   |
| Alcor Micro USB 2.0 PC cam                          | 5         | 0.45%   |
| Suyin 1.3M HD WebCam                                | 4         | 0.36%   |
| Realtek USB2.0 HD UVC WebCam                        | 4         | 0.36%   |
| Realtek Lenovo EasyCamera                           | 4         | 0.36%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 76        | 31.67%  |
| Validity Sensors           | 64        | 26.67%  |
| Shenzhen Goodix Technology | 48        | 20%     |
| Elan Microelectronics      | 20        | 8.33%   |
| LighTuning Technology      | 13        | 5.42%   |
| Upek                       | 8         | 3.33%   |
| AuthenTec                  | 6         | 2.5%    |
| STMicroelectronics         | 2         | 0.83%   |
| Samsung Electronics        | 1         | 0.42%   |
| HOLTEK                     | 1         | 0.42%   |
| Dell                       | 1         | 0.42%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 10.42%  |
| Unknown                                                                    | 24        | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 23        | 9.58%   |
| Shenzhen Goodix  FingerPrint Device                                        | 21        | 8.75%   |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 7.5%    |
| Elan ELAN:Fingerprint                                                      | 13        | 5.42%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 4.58%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 3.75%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 2.92%   |
| Synaptics  WBDI                                                            | 7         | 2.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.92%   |
| Elan ELAN:ARM-M4                                                           | 7         | 2.92%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.5%    |
| Validity Sensors VFS491                                                    | 6         | 2.5%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 2.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.25%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.83%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.83%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.83%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.83%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.83%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.83%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.83%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.42%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.42%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.42%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.42%   |
| Synaptics WBDI Device                                                      | 1         | 0.42%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.42%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.42%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 0.42%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.42%   |
| AuthenTec AES2810                                                          | 1         | 0.42%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 41        | 48.24%  |
| Alcor Micro                       | 28        | 32.94%  |
| O2 Micro                          | 4         | 4.71%   |
| Lenovo                            | 3         | 3.53%   |
| Gemalto (was Gemplus)             | 3         | 3.53%   |
| VASCO Data Security International | 1         | 1.18%   |
| Upek                              | 1         | 1.18%   |
| Clay Logic                        | 1         | 1.18%   |
| Cherry                            | 1         | 1.18%   |
| BIT4ID                            | 1         | 1.18%   |
| Advanced Card Systems             | 1         | 1.18%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 28        | 32.94%  |
| Broadcom 58200                                                               | 14        | 16.47%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 15.29%  |
| Broadcom 5880                                                                | 10        | 11.76%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 4.71%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.53%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.53%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 2.35%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 1.18%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.18%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.18%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 1.18%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.18%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 1.18%   |
| BIT4ID miniLector EVO                                                        | 1         | 1.18%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.18%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1251      | 70.08%  |
| 1     | 438       | 24.54%  |
| 2     | 79        | 4.43%   |
| 3     | 14        | 0.78%   |
| 5     | 2         | 0.11%   |
| 4     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 235       | 37.24%  |
| Graphics card            | 128       | 20.29%  |
| Net/wireless             | 83        | 13.15%  |
| Chipcard                 | 73        | 11.57%  |
| Multimedia controller    | 25        | 3.96%   |
| Unassigned class         | 16        | 2.54%   |
| Communication controller | 12        | 1.9%    |
| Storage                  | 11        | 1.74%   |
| Card reader              | 11        | 1.74%   |
| Bluetooth                | 11        | 1.74%   |
| Camera                   | 10        | 1.58%   |
| Sound                    | 7         | 1.11%   |
| Net/ethernet             | 3         | 0.48%   |
| Storage/raid             | 2         | 0.32%   |
| Storage/ata              | 1         | 0.16%   |
| Network                  | 1         | 0.16%   |
| Modem                    | 1         | 0.16%   |
| Dvb card                 | 1         | 0.16%   |

