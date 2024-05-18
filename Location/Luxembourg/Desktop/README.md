Linux in Luxembourg - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Luxembourg.

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

Total: 73

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MAG B650 TOMAHAWK WIFI      | [692f458014](https://linux-hardware.org/?probe=692f458014) | May 01, 2024 |
| JWIPC         | A320I S1                    | [eea8091ffa](https://linux-hardware.org/?probe=eea8091ffa) | Apr 22, 2024 |
| JWIPC         | A320I S1                    | [c8bb6cd872](https://linux-hardware.org/?probe=c8bb6cd872) | Apr 21, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [89107c7d88](https://linux-hardware.org/?probe=89107c7d88) | Apr 18, 2024 |
| ASUSTek       | PRIME B460M-A               | [63a643c790](https://linux-hardware.org/?probe=63a643c790) | Mar 26, 2024 |
| ASUSTek       | P6X58D PREMIUM              | [3e42f1f6bb](https://linux-hardware.org/?probe=3e42f1f6bb) | Mar 24, 2024 |
| Dell          | 0KC9NP A01                  | [ee6bd4e717](https://linux-hardware.org/?probe=ee6bd4e717) | Mar 07, 2024 |
| Gigabyte      | Z77X-D3H                    | [aa69326408](https://linux-hardware.org/?probe=aa69326408) | Jan 29, 2024 |
| HP            | 198E                        | [30e0f75eee](https://linux-hardware.org/?probe=30e0f75eee) | Dec 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e1e496f1a9](https://linux-hardware.org/?probe=e1e496f1a9) | Dec 15, 2023 |
| Dell          | 02K9CR A02                  | [47ca1834f0](https://linux-hardware.org/?probe=47ca1834f0) | Oct 15, 2023 |
| MSI           | PRO Z790-P WIFI             | [5b9aef438f](https://linux-hardware.org/?probe=5b9aef438f) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | [1f3f8a869b](https://linux-hardware.org/?probe=1f3f8a869b) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [50ee937fb2](https://linux-hardware.org/?probe=50ee937fb2) | Aug 02, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | [93c8724c91](https://linux-hardware.org/?probe=93c8724c91) | Jul 31, 2023 |
| Unknown       | T3 MRD                      | [5539799efa](https://linux-hardware.org/?probe=5539799efa) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a179c222ea](https://linux-hardware.org/?probe=a179c222ea) | Jul 23, 2023 |
| MACHINIST     | E5-D8-MAX V1.1              | [ea68d9762b](https://linux-hardware.org/?probe=ea68d9762b) | Jul 21, 2023 |
| Win Elemen... | M9                          | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | [53f395d7fa](https://linux-hardware.org/?probe=53f395d7fa) | May 15, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | [5d12a9965b](https://linux-hardware.org/?probe=5d12a9965b) | May 06, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [c8bf9d49d4](https://linux-hardware.org/?probe=c8bf9d49d4) | Apr 15, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [5fe0f2c1fe](https://linux-hardware.org/?probe=5fe0f2c1fe) | Feb 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [f91712ea02](https://linux-hardware.org/?probe=f91712ea02) | Feb 15, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [6666a9b8ca](https://linux-hardware.org/?probe=6666a9b8ca) | Jan 09, 2023 |
| MSI           | B85-G43                     | [a8f28d3f69](https://linux-hardware.org/?probe=a8f28d3f69) | Nov 23, 2022 |
| Intel         | DP35DP AAD81073-207         | [c597415419](https://linux-hardware.org/?probe=c597415419) | Nov 11, 2022 |
| JWIPC         | A320I S1                    | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | [dbfdcae895](https://linux-hardware.org/?probe=dbfdcae895) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | [4167167e38](https://linux-hardware.org/?probe=4167167e38) | Sep 08, 2022 |
| Gigabyte      | X99-UD3-CF                  | [75dbdd1681](https://linux-hardware.org/?probe=75dbdd1681) | Jul 26, 2022 |
| Gigabyte      | X99-UD3-CF                  | [7eaa9fa16b](https://linux-hardware.org/?probe=7eaa9fa16b) | Jul 26, 2022 |
| HP            | 2820h                       | [7303ad365d](https://linux-hardware.org/?probe=7303ad365d) | Jul 11, 2022 |
| Intel         | DG41WV AAE90316-104         | [b6dc38eb16](https://linux-hardware.org/?probe=b6dc38eb16) | Feb 25, 2022 |
| ASRock        | H110M-STX                   | [e5876258c7](https://linux-hardware.org/?probe=e5876258c7) | Feb 19, 2022 |
| ASUSTek       | Z97-A                       | [19d74bd6f0](https://linux-hardware.org/?probe=19d74bd6f0) | Jan 31, 2022 |
| ASUSTek       | PRIME X470-PRO              | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Medion        | Cattle24 1M                 | [05747b9a42](https://linux-hardware.org/?probe=05747b9a42) | Nov 10, 2021 |
| Medion        | Cattle24 1M                 | [9763c21680](https://linux-hardware.org/?probe=9763c21680) | Nov 10, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [b2f196476a](https://linux-hardware.org/?probe=b2f196476a) | Nov 04, 2021 |
| ASUSTek       | UN62                        | [0702f80222](https://linux-hardware.org/?probe=0702f80222) | Sep 09, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ce97f26d1d](https://linux-hardware.org/?probe=ce97f26d1d) | Sep 09, 2021 |
| Intel         | DG41WV AAE90316-104         | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [80a7298343](https://linux-hardware.org/?probe=80a7298343) | Jul 27, 2021 |
| ASRock        | B450M-HDV R4.0              | [b5b8d7a195](https://linux-hardware.org/?probe=b5b8d7a195) | Jun 13, 2021 |
| Intel         | DG965SS AAD41678-308        | [d76e4b9ec3](https://linux-hardware.org/?probe=d76e4b9ec3) | May 04, 2021 |
| ASUSTek       | M5A78L-M LX3                | [565be765f5](https://linux-hardware.org/?probe=565be765f5) | Apr 29, 2021 |
| Intel         | DG41WV AAE90316-104         | [af606a347f](https://linux-hardware.org/?probe=af606a347f) | Mar 15, 2021 |
| Gigabyte      | H81M-DS2                    | [439d425d4b](https://linux-hardware.org/?probe=439d425d4b) | Mar 01, 2021 |
| Gigabyte      | H81M-DS2                    | [3500ce2480](https://linux-hardware.org/?probe=3500ce2480) | Feb 09, 2021 |
| ASUSTek       | Z87-DELUXE                  | [e160eea25a](https://linux-hardware.org/?probe=e160eea25a) | Dec 28, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [ae14c03ffc](https://linux-hardware.org/?probe=ae14c03ffc) | Dec 19, 2020 |
| Gigabyte      | X570 AORUS PRO              | [9ec2d84b9b](https://linux-hardware.org/?probe=9ec2d84b9b) | Dec 10, 2020 |
| ASUSTek       | PRIME H470M-PLUS            | [1d77b8496d](https://linux-hardware.org/?probe=1d77b8496d) | Nov 28, 2020 |
| Gigabyte      | H81M-DS2                    | [e6be700463](https://linux-hardware.org/?probe=e6be700463) | Oct 28, 2020 |
| ASUSTek       | Z87-A                       | [bbe1190702](https://linux-hardware.org/?probe=bbe1190702) | Oct 01, 2020 |
| MSI           | MAG Z490 TOMAHAWK           | [ffd532c8d8](https://linux-hardware.org/?probe=ffd532c8d8) | Aug 16, 2020 |
| Gigabyte      | Z97X-Gaming 5               | [e1c1c22a7b](https://linux-hardware.org/?probe=e1c1c22a7b) | Aug 11, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [3f740083f9](https://linux-hardware.org/?probe=3f740083f9) | Jul 19, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [f1c586d370](https://linux-hardware.org/?probe=f1c586d370) | Jul 19, 2020 |
| Medion        | MS-7848                     | [6c60cef00e](https://linux-hardware.org/?probe=6c60cef00e) | May 06, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [33665c7f49](https://linux-hardware.org/?probe=33665c7f49) | May 04, 2020 |
| MSI           | H310M PRO-M2 PLUS           | [6e21e82c58](https://linux-hardware.org/?probe=6e21e82c58) | Mar 26, 2020 |
| ASUSTek       | PRIME B250M-A               | [68e88028d6](https://linux-hardware.org/?probe=68e88028d6) | Jan 09, 2020 |
| ASUSTek       | PRIME B250M-A               | [453044841e](https://linux-hardware.org/?probe=453044841e) | Jan 09, 2020 |
| Foxconn       | 2AA9                        | [2b2a941903](https://linux-hardware.org/?probe=2b2a941903) | Jan 07, 2020 |
| Foxconn       | 2AA9                        | [ed7e0428fb](https://linux-hardware.org/?probe=ed7e0428fb) | Jan 07, 2020 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [c1c91fe558](https://linux-hardware.org/?probe=c1c91fe558) | Nov 18, 2019 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [9ee20bcfcb](https://linux-hardware.org/?probe=9ee20bcfcb) | Nov 18, 2019 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [3b96b0c40d](https://linux-hardware.org/?probe=3b96b0c40d) | Nov 17, 2019 |
| Gigabyte      | Z270M-D3H-CF                | [3bcd649400](https://linux-hardware.org/?probe=3bcd649400) | Jul 14, 2019 |
| HP            | 3048h                       | [ab8f89fdcc](https://linux-hardware.org/?probe=ab8f89fdcc) | Oct 07, 2018 |
| MSI           | NF750-G55                   | [d1b2ddb193](https://linux-hardware.org/?probe=d1b2ddb193) | May 22, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 7        | 12.28%  |
| Ubuntu 22.04        | 5        | 8.77%   |
| Ubuntu 18.04        | 4        | 7.02%   |
| openSUSE Leap-15.2  | 2        | 3.51%   |
| Linux Mint 20.1     | 2        | 3.51%   |
| Fedora 38           | 2        | 3.51%   |
| Arch Rolling        | 2        | 3.51%   |
| Zorin 16            | 1        | 1.75%   |
| Xubuntu 16.04       | 1        | 1.75%   |
| UbuntuDDE 20.04     | 1        | 1.75%   |
| Ubuntu Studio 20.04 | 1        | 1.75%   |
| Ubuntu 22.10        | 1        | 1.75%   |
| Ubuntu 20.10        | 1        | 1.75%   |
| Ubuntu 19.10        | 1        | 1.75%   |
| Pop!_OS 22.04       | 1        | 1.75%   |
| openSUSE Leap-15.3  | 1        | 1.75%   |
| OpenMandriva 4.90   | 1        | 1.75%   |
| Manjaro 21.1.0      | 1        | 1.75%   |
| Mageia 7            | 1        | 1.75%   |
| Lubuntu 22.04       | 1        | 1.75%   |
| Lubuntu 20.10       | 1        | 1.75%   |
| LMDE 4              | 1        | 1.75%   |
| Kubuntu 23.10       | 1        | 1.75%   |
| Kubuntu 22.04       | 1        | 1.75%   |
| Kubuntu 20.04       | 1        | 1.75%   |
| KDE neon 20.04      | 1        | 1.75%   |
| Kali 2021.3         | 1        | 1.75%   |
| Gentoo 2.14         | 1        | 1.75%   |
| Gentoo 2.13         | 1        | 1.75%   |
| Fedora 40           | 1        | 1.75%   |
| Fedora 37           | 1        | 1.75%   |
| Fedora 34           | 1        | 1.75%   |
| Fedora 33           | 1        | 1.75%   |
| Fedora 32           | 1        | 1.75%   |
| EndeavourOS Rolling | 1        | 1.75%   |
| Elementary 5.1.7    | 1        | 1.75%   |
| Debian 10           | 1        | 1.75%   |
| CentOS 8            | 1        | 1.75%   |
| ArcoLinux Rolling   | 1        | 1.75%   |
| Arch                | 1        | 1.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 19       | 34.55%  |
| Fedora        | 7        | 12.73%  |
| Arch          | 3        | 5.45%   |
| openSUSE      | 2        | 3.64%   |
| Lubuntu       | 2        | 3.64%   |
| Linux Mint    | 2        | 3.64%   |
| Kubuntu       | 2        | 3.64%   |
| Gentoo        | 2        | 3.64%   |
| Zorin         | 1        | 1.82%   |
| Xubuntu       | 1        | 1.82%   |
| UbuntuDDE     | 1        | 1.82%   |
| Ubuntu Studio | 1        | 1.82%   |
| Pop!_OS       | 1        | 1.82%   |
| OpenMandriva  | 1        | 1.82%   |
| Manjaro       | 1        | 1.82%   |
| Mageia        | 1        | 1.82%   |
| LMDE          | 1        | 1.82%   |
| KDE neon      | 1        | 1.82%   |
| Kali          | 1        | 1.82%   |
| EndeavourOS   | 1        | 1.82%   |
| Elementary    | 1        | 1.82%   |
| Debian        | 1        | 1.82%   |
| CentOS        | 1        | 1.82%   |
| ArcoLinux     | 1        | 1.82%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.4.0-90-generic            | 2        | 3.28%   |
| 6.8.6-300.fc40.x86_64       | 1        | 1.64%   |
| 6.6.7-arch1-1               | 1        | 1.64%   |
| 6.6.29-1-lts                | 1        | 1.64%   |
| 6.6.22-gentoo-dist-hardened | 1        | 1.64%   |
| 6.5.0-28-generic            | 1        | 1.64%   |
| 6.5.0-21-generic            | 1        | 1.64%   |
| 6.5.0-15-generic            | 1        | 1.64%   |
| 6.4.7-arch1-1               | 1        | 1.64%   |
| 6.4.4-zen1-1-zen            | 1        | 1.64%   |
| 6.3.12-200.fc38.x86_64      | 1        | 1.64%   |
| 6.3.1-arch2-1               | 1        | 1.64%   |
| 6.2.9-300.fc38.x86_64       | 1        | 1.64%   |
| 6.1.22-gentoo-dist          | 1        | 1.64%   |
| 6.1.10-200.fc37.x86_64      | 1        | 1.64%   |
| 5.9.13-zen1-1-zen           | 1        | 1.64%   |
| 5.9.10-200.fc33.x86_64      | 1        | 1.64%   |
| 5.8.0-44-generic            | 1        | 1.64%   |
| 5.8.0-43-generic            | 1        | 1.64%   |
| 5.8.0-26-generic            | 1        | 1.64%   |
| 5.7.19-desktop-3.mga7       | 1        | 1.64%   |
| 5.4.0-91-generic            | 1        | 1.64%   |
| 5.4.0-72-generic            | 1        | 1.64%   |
| 5.4.0-58-generic            | 1        | 1.64%   |
| 5.4.0-47-generic            | 1        | 1.64%   |
| 5.4.0-42-generic            | 1        | 1.64%   |
| 5.4.0-40-generic            | 1        | 1.64%   |
| 5.4.0-21-generic            | 1        | 1.64%   |
| 5.4.0-169-generic           | 1        | 1.64%   |
| 5.4.0-155-lowlatency        | 1        | 1.64%   |
| 5.3.18-lp152.66-default     | 1        | 1.64%   |
| 5.3.18-lp152.33-default     | 1        | 1.64%   |
| 5.3.18-59.19-preempt        | 1        | 1.64%   |
| 5.3.18-150300.59.49-preempt | 1        | 1.64%   |
| 5.3.0-46-generic            | 1        | 1.64%   |
| 5.3.0-42-generic            | 1        | 1.64%   |
| 5.3.0-26-generic            | 1        | 1.64%   |
| 5.3.0-0.bpo.2-686-pae       | 1        | 1.64%   |
| 5.19.0-76051900-generic     | 1        | 1.64%   |
| 5.19.0-50-generic           | 1        | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 11       | 19.64%  |
| 5.15.0  | 8        | 14.29%  |
| 6.5.0   | 3        | 5.36%   |
| 5.3.0   | 3        | 5.36%   |
| 5.3.18  | 2        | 3.57%   |
| 5.19.0  | 2        | 3.57%   |
| 4.18.0  | 2        | 3.57%   |
| 6.8.6   | 1        | 1.79%   |
| 6.6.7   | 1        | 1.79%   |
| 6.6.29  | 1        | 1.79%   |
| 6.6.22  | 1        | 1.79%   |
| 6.4.7   | 1        | 1.79%   |
| 6.4.4   | 1        | 1.79%   |
| 6.3.12  | 1        | 1.79%   |
| 6.3.1   | 1        | 1.79%   |
| 6.2.9   | 1        | 1.79%   |
| 6.1.22  | 1        | 1.79%   |
| 6.1.10  | 1        | 1.79%   |
| 5.9.13  | 1        | 1.79%   |
| 5.9.10  | 1        | 1.79%   |
| 5.8.0   | 1        | 1.79%   |
| 5.7.19  | 1        | 1.79%   |
| 5.18.12 | 1        | 1.79%   |
| 5.13.4  | 1        | 1.79%   |
| 5.12.7  | 1        | 1.79%   |
| 5.11.0  | 1        | 1.79%   |
| 5.10.7  | 1        | 1.79%   |
| 5.10.0  | 1        | 1.79%   |
| 5.0.0   | 1        | 1.79%   |
| 4.4.0   | 1        | 1.79%   |
| 4.19.0  | 1        | 1.79%   |
| 4.15.0  | 1        | 1.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 11       | 19.64%  |
| 5.15    | 8        | 14.29%  |
| 5.3     | 5        | 8.93%   |
| 6.6     | 3        | 5.36%   |
| 6.5     | 3        | 5.36%   |
| 6.4     | 2        | 3.57%   |
| 6.3     | 2        | 3.57%   |
| 6.1     | 2        | 3.57%   |
| 5.9     | 2        | 3.57%   |
| 5.19    | 2        | 3.57%   |
| 5.10    | 2        | 3.57%   |
| 4.18    | 2        | 3.57%   |
| 6.8     | 1        | 1.79%   |
| 6.2     | 1        | 1.79%   |
| 5.8     | 1        | 1.79%   |
| 5.7     | 1        | 1.79%   |
| 5.18    | 1        | 1.79%   |
| 5.13    | 1        | 1.79%   |
| 5.12    | 1        | 1.79%   |
| 5.11    | 1        | 1.79%   |
| 5.0     | 1        | 1.79%   |
| 4.4     | 1        | 1.79%   |
| 4.19    | 1        | 1.79%   |
| 4.15    | 1        | 1.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 52       | 98.11%  |
| i686   | 1        | 1.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 26       | 46.43%  |
| KDE5       | 9        | 16.07%  |
| Unknown    | 6        | 10.71%  |
| XFCE       | 3        | 5.36%   |
| X-Cinnamon | 2        | 3.57%   |
| LXQt       | 2        | 3.57%   |
| KDE        | 2        | 3.57%   |
| Deepin     | 2        | 3.57%   |
| Cinnamon   | 2        | 3.57%   |
| Pantheon   | 1        | 1.79%   |
| KDE6       | 1        | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 36       | 65.45%  |
| Wayland | 13       | 23.64%  |
| Tty     | 3        | 5.45%   |
| Unknown | 3        | 5.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 42.59%  |
| SDDM    | 10       | 18.52%  |
| GDM3    | 9        | 16.67%  |
| LightDM | 6        | 11.11%  |
| GDM     | 5        | 9.26%   |
| TDM     | 1        | 1.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 24       | 44.44%  |
| fr_FR   | 8        | 14.81%  |
| de_LU   | 5        | 9.26%   |
| en_GB   | 4        | 7.41%   |
| C       | 4        | 7.41%   |
| es_ES   | 2        | 3.7%    |
| de_DE   | 2        | 3.7%    |
| Unknown | 2        | 3.7%    |
| lb_LU   | 1        | 1.85%   |
| de_CH   | 1        | 1.85%   |
| C.UTF8  | 1        | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 28       | 52.83%  |
| EFI  | 25       | 47.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 35       | 66.04%  |
| Btrfs   | 9        | 16.98%  |
| Xfs     | 3        | 5.66%   |
| Tmpfs   | 3        | 5.66%   |
| Overlay | 2        | 3.77%   |
| Zfs     | 1        | 1.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 26       | 49.06%  |
| Unknown | 24       | 45.28%  |
| MBR     | 3        | 5.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 83.33%  |
| Yes       | 9        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 66.67%  |
| Yes       | 18       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 30.19%  |
| Gigabyte Technology | 9        | 16.98%  |
| MSI                 | 6        | 11.32%  |
| ASRock              | 4        | 7.55%   |
| Intel               | 3        | 5.66%   |
| Hewlett-Packard     | 3        | 5.66%   |
| Medion              | 2        | 3.77%   |
| Dell                | 2        | 3.77%   |
| Win Element         | 1        | 1.89%   |
| MACHINIST           | 1        | 1.89%   |
| Lenovo              | 1        | 1.89%   |
| LattePanda          | 1        | 1.89%   |
| JWIPC               | 1        | 1.89%   |
| Foxconn             | 1        | 1.89%   |
| BESSTAR Tech        | 1        | 1.89%   |
| Unknown             | 1        | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 5.66%   |
| Win Element M9                      | 1        | 1.89%   |
| MSI MS-7E06                         | 1        | 1.89%   |
| MSI MS-7D75                         | 1        | 1.89%   |
| MSI MS-7C91                         | 1        | 1.89%   |
| MSI MS-7C80                         | 1        | 1.89%   |
| MSI MS-7C08                         | 1        | 1.89%   |
| MSI MS-7816                         | 1        | 1.89%   |
| Medion P961x                        | 1        | 1.89%   |
| Medion MS-7848                      | 1        | 1.89%   |
| MACHINIST E5-D8-MAX V1.1            | 1        | 1.89%   |
| Lenovo ThinkCentre M910s 10MKS02N04 | 1        | 1.89%   |
| LattePanda 3 Delta                  | 1        | 1.89%   |
| JWIPC BF24                          | 1        | 1.89%   |
| Intel DP35DP AAD81073-207           | 1        | 1.89%   |
| Intel DG965SS AAD41678-308          | 1        | 1.89%   |
| Intel DG41WV AAE90316-104           | 1        | 1.89%   |
| HP ProDesk 400 G2 MT (TPM DP)       | 1        | 1.89%   |
| HP Compaq dc5800 Small Form Factor  | 1        | 1.89%   |
| HP Compaq 6000 Pro SFF PC           | 1        | 1.89%   |
| Gigabyte Z97X-Gaming 5              | 1        | 1.89%   |
| Gigabyte Z77X-D3H                   | 1        | 1.89%   |
| Gigabyte Z370 AORUS Ultra Gaming    | 1        | 1.89%   |
| Gigabyte Z270M-D3H                  | 1        | 1.89%   |
| Gigabyte X99-UD3-CF                 | 1        | 1.89%   |
| Gigabyte X670E AORUS MASTER         | 1        | 1.89%   |
| Gigabyte X570 AORUS PRO             | 1        | 1.89%   |
| Gigabyte H81M-DS2                   | 1        | 1.89%   |
| Gigabyte B550M AORUS PRO-P          | 1        | 1.89%   |
| Foxconn p6601fr-m                   | 1        | 1.89%   |
| Dell Precision Tower 3420           | 1        | 1.89%   |
| Dell OptiPlex 9020                  | 1        | 1.89%   |
| BESSTAR Tech DMAF5                  | 1        | 1.89%   |
| ASUS UN62                           | 1        | 1.89%   |
| ASUS TUF Gaming Z590-PLUS WIFI      | 1        | 1.89%   |
| ASUS TUF Gaming X570-PLUS           | 1        | 1.89%   |
| ASUS ROG STRIX X570-E GAMING        | 1        | 1.89%   |
| ASUS ROG STRIX B550-F GAMING        | 1        | 1.89%   |
| ASUS ROG CROSSHAIR VIII DARK HERO   | 1        | 1.89%   |
| ASUS PRIME X470-PRO                 | 1        | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 4        | 7.55%   |
| ASUS ROG             | 3        | 5.66%   |
| ASUS All             | 3        | 5.66%   |
| HP Compaq            | 2        | 3.77%   |
| ASUS TUF             | 2        | 3.77%   |
| Win Element M9       | 1        | 1.89%   |
| MSI MS-7E06          | 1        | 1.89%   |
| MSI MS-7D75          | 1        | 1.89%   |
| MSI MS-7C91          | 1        | 1.89%   |
| MSI MS-7C80          | 1        | 1.89%   |
| MSI MS-7C08          | 1        | 1.89%   |
| MSI MS-7816          | 1        | 1.89%   |
| Medion P961x         | 1        | 1.89%   |
| Medion MS-7848       | 1        | 1.89%   |
| MACHINIST E5-D8-MAX  | 1        | 1.89%   |
| Lenovo ThinkCentre   | 1        | 1.89%   |
| LattePanda 3         | 1        | 1.89%   |
| JWIPC BF24           | 1        | 1.89%   |
| Intel DP35DP         | 1        | 1.89%   |
| Intel DG965SS        | 1        | 1.89%   |
| Intel DG41WV         | 1        | 1.89%   |
| HP ProDesk           | 1        | 1.89%   |
| Gigabyte Z97X-Gaming | 1        | 1.89%   |
| Gigabyte Z77X-D3H    | 1        | 1.89%   |
| Gigabyte Z370        | 1        | 1.89%   |
| Gigabyte Z270M-D3H   | 1        | 1.89%   |
| Gigabyte X99-UD3-CF  | 1        | 1.89%   |
| Gigabyte X670E       | 1        | 1.89%   |
| Gigabyte X570        | 1        | 1.89%   |
| Gigabyte H81M-DS2    | 1        | 1.89%   |
| Gigabyte B550M       | 1        | 1.89%   |
| Foxconn p6601fr-m    | 1        | 1.89%   |
| Dell Precision       | 1        | 1.89%   |
| Dell OptiPlex        | 1        | 1.89%   |
| BESSTAR Tech DMAF5   | 1        | 1.89%   |
| ASUS UN62            | 1        | 1.89%   |
| ASUS P6X58D          | 1        | 1.89%   |
| ASUS M5A78L-M        | 1        | 1.89%   |
| ASUS CH1001297       | 1        | 1.89%   |
| ASRock X570          | 1        | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 7        | 13.21%  |
| 2018 | 6        | 11.32%  |
| 2014 | 6        | 11.32%  |
| 2019 | 5        | 9.43%   |
| 2013 | 5        | 9.43%   |
| 2010 | 4        | 7.55%   |
| 2023 | 3        | 5.66%   |
| 2022 | 3        | 5.66%   |
| 2021 | 3        | 5.66%   |
| 2016 | 3        | 5.66%   |
| 2017 | 2        | 3.77%   |
| 2012 | 2        | 3.77%   |
| 2007 | 2        | 3.77%   |
| 2009 | 1        | 1.89%   |
| 2008 | 1        | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 53       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 49       | 92.45%  |
| Enabled  | 4        | 7.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 20       | 37.04%  |
| 32.01-64.0  | 11       | 20.37%  |
| 4.01-8.0    | 7        | 12.96%  |
| 8.01-16.0   | 7        | 12.96%  |
| 3.01-4.0    | 5        | 9.26%   |
| 64.01-256.0 | 3        | 5.56%   |
| 24.01-32.0  | 1        | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 15       | 26.32%  |
| 2.01-3.0  | 13       | 22.81%  |
| 1.01-2.0  | 13       | 22.81%  |
| 3.01-4.0  | 8        | 14.04%  |
| 8.01-16.0 | 6        | 10.53%  |
| 0.51-1.0  | 2        | 3.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 36.36%  |
| 1      | 13       | 23.64%  |
| 3      | 9        | 16.36%  |
| 4      | 7        | 12.73%  |
| 5      | 3        | 5.45%   |
| 7      | 2        | 3.64%   |
| 6      | 1        | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 62.26%  |
| Yes       | 20       | 37.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 53       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 53.7%   |
| Yes       | 25       | 46.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 64.15%  |
| Yes       | 19       | 35.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Luxembourg | 53       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Luxembourg        | 33       | 58.93%  |
| Sanem             | 2        | 3.57%   |
| Esch-sur-Alzette  | 2        | 3.57%   |
| Differdange       | 2        | 3.57%   |
| Wormeldange       | 1        | 1.79%   |
| Wasserbillig      | 1        | 1.79%   |
| Useldange         | 1        | 1.79%   |
| Strassen          | 1        | 1.79%   |
| Schieren          | 1        | 1.79%   |
| Roeser            | 1        | 1.79%   |
| Pontpierre        | 1        | 1.79%   |
| Pétange          | 1        | 1.79%   |
| Junglinster       | 1        | 1.79%   |
| Itzig             | 1        | 1.79%   |
| Hosingen          | 1        | 1.79%   |
| Ehnen             | 1        | 1.79%   |
| Dudelange         | 1        | 1.79%   |
| Contern           | 1        | 1.79%   |
| Brouch            | 1        | 1.79%   |
| Bettange-sur-Mess | 1        | 1.79%   |
| Belvaux           | 1        | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Samsung Electronics          | 29       | 46     | 27.62%  |
| Seagate                      | 17       | 27     | 16.19%  |
| WDC                          | 14       | 23     | 13.33%  |
| Crucial                      | 8        | 12     | 7.62%   |
| SanDisk                      | 4        | 7      | 3.81%   |
| Kingston                     | 4        | 7      | 3.81%   |
| Hitachi                      | 3        | 5      | 2.86%   |
| Toshiba                      | 2        | 4      | 1.9%    |
| Shenzhen Longsys Electronics | 2        | 2      | 1.9%    |
| Phison                       | 2        | 2      | 1.9%    |
| HGST                         | 2        | 4      | 1.9%    |
| Unknown                      | 1        | 2      | 0.95%   |
| Transcend                    | 1        | 1      | 0.95%   |
| TCSUNBOW                     | 1        | 1      | 0.95%   |
| StarTech                     | 1        | 2      | 0.95%   |
| SABRENT                      | 1        | 1      | 0.95%   |
| PNY                          | 1        | 1      | 0.95%   |
| OCZ                          | 1        | 1      | 0.95%   |
| Micron/Crucial Technology    | 1        | 1      | 0.95%   |
| Maxtor                       | 1        | 2      | 0.95%   |
| MAXIO Technology (Hangzhou)  | 1        | 2      | 0.95%   |
| KingSpec                     | 1        | 1      | 0.95%   |
| JMicron Technology           | 1        | 1      | 0.95%   |
| Intenso                      | 1        | 1      | 0.95%   |
| Intel                        | 1        | 1      | 0.95%   |
| Inateck                      | 1        | 1      | 0.95%   |
| Gigabyte Technology          | 1        | 1      | 0.95%   |
| ASMT                         | 1        | 4      | 0.95%   |
| A-DATA Technology            | 1        | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung SSD 840 EVO 250GB                          | 3        | 2.27%   |
| Samsung SSD 750 EVO 500GB                          | 3        | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3        | 2.27%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 2        | 1.52%   |
| Seagate ST4000DM004-2CV104 4TB                     | 2        | 1.52%   |
| SanDisk SDSSDH3512G 512GB                          | 2        | 1.52%   |
| Samsung SSD 860 QVO 2TB                            | 2        | 1.52%   |
| Samsung SSD 860 EVO 250GB                          | 2        | 1.52%   |
| Samsung SSD 850 EVO 250GB                          | 2        | 1.52%   |
| Samsung SP2504C 250GB                              | 2        | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2        | 1.52%   |
| Kingston SA400S37240G 240GB SSD                    | 2        | 1.52%   |
| Crucial CT1000P2SSD8 1TB                           | 2        | 1.52%   |
| WDC WDS500G3X0C-00SJG0 500GB                       | 1        | 0.76%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                   | 1        | 0.76%   |
| WDC WD5000AAVS-00ZTB0 500GB                        | 1        | 0.76%   |
| WDC WD5000AAKS-60Z1A0 500GB                        | 1        | 0.76%   |
| WDC WD40EZRZ-75GXCB0 4TB                           | 1        | 0.76%   |
| WDC WD4000FYYZ-01UL1B2 4TB                         | 1        | 0.76%   |
| WDC WD3001FFSX-68JNUN0 3TB                         | 1        | 0.76%   |
| WDC WD3000GLFS-01F8U0 304GB                        | 1        | 0.76%   |
| WDC WD20EFAX-68FB5N0 2TB                           | 1        | 0.76%   |
| WDC WD141KRYZ-01C66B0 14TB                         | 1        | 0.76%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1        | 0.76%   |
| WDC WD10EZRX-00A8LB0 1TB                           | 1        | 0.76%   |
| WDC WD10EZEX-60ZF5A0 1TB                           | 1        | 0.76%   |
| WDC WD10EARX-00N0YB0 1TB                           | 1        | 0.76%   |
| WDC WD10EARS-00Y5B1 1TB                            | 1        | 0.76%   |
| WDC WD10EADS-00M2B0 1TB                            | 1        | 0.76%   |
| WDC WD10EACS-00D6B1 1TB                            | 1        | 0.76%   |
| WDC WD1001FALS-00J7B0 1TB                          | 1        | 0.76%   |
| Unknown MMC Card  64GB                             | 1        | 0.76%   |
| Unknown DA4064  64GB                               | 1        | 0.76%   |
| Transcend TS512GSSD370 512GB                       | 1        | 0.76%   |
| Toshiba MG03ACA100 1TB                             | 1        | 0.76%   |
| Toshiba DT01ACA050 500GB                           | 1        | 0.76%   |
| TCSUNBOW X3 240GB                                  | 1        | 0.76%   |
| StarTech M2E1BRU31C 2TB                            | 1        | 0.76%   |
| Shenzhen Longsys Lexar SSD ARES 1TB                | 1        | 0.76%   |
| Shenzhen Longsys Emtec X300 500GB                  | 1        | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 25     | 37.5%   |
| WDC                 | 12       | 21     | 30%     |
| Hitachi             | 3        | 5      | 7.5%    |
| Toshiba             | 2        | 4      | 5%      |
| Samsung Electronics | 2        | 2      | 5%      |
| HGST                | 2        | 4      | 5%      |
| SABRENT             | 1        | 1      | 2.5%    |
| Intenso             | 1        | 1      | 2.5%    |
| Inateck             | 1        | 1      | 2.5%    |
| ASMT                | 1        | 4      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 20       | 25     | 50%     |
| Crucial             | 5        | 9      | 12.5%   |
| SanDisk             | 3        | 5      | 7.5%    |
| Kingston            | 3        | 5      | 7.5%    |
| WDC                 | 1        | 1      | 2.5%    |
| Transcend           | 1        | 1      | 2.5%    |
| TCSUNBOW            | 1        | 1      | 2.5%    |
| PNY                 | 1        | 1      | 2.5%    |
| OCZ                 | 1        | 1      | 2.5%    |
| Maxtor              | 1        | 2      | 2.5%    |
| KingSpec            | 1        | 1      | 2.5%    |
| Intel               | 1        | 1      | 2.5%    |
| A-DATA Technology   | 1        | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 31       | 54     | 34.07%  |
| HDD     | 31       | 68     | 34.07%  |
| NVMe    | 24       | 35     | 26.37%  |
| Unknown | 3        | 4      | 3.3%    |
| MMC     | 2        | 3      | 2.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 44       | 113    | 57.89%  |
| NVMe | 24       | 35     | 31.58%  |
| SAS  | 6        | 13     | 7.89%   |
| MMC  | 2        | 3      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 64     | 43.24%  |
| 0.51-1.0   | 21       | 33     | 28.38%  |
| 1.01-2.0   | 9        | 12     | 12.16%  |
| 3.01-4.0   | 7        | 7      | 9.46%   |
| 2.01-3.0   | 2        | 3      | 2.7%    |
| 4.01-10.0  | 2        | 2      | 2.7%    |
| 10.01-20.0 | 1        | 1      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 11       | 20.37%  |
| 101-250        | 10       | 18.52%  |
| 251-500        | 9        | 16.67%  |
| 1001-2000      | 5        | 9.26%   |
| 501-1000       | 5        | 9.26%   |
| Unknown        | 5        | 9.26%   |
| 2001-3000      | 4        | 7.41%   |
| 51-100         | 3        | 5.56%   |
| 1-20           | 2        | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 15       | 27.78%  |
| 101-250        | 8        | 14.81%  |
| 21-50          | 7        | 12.96%  |
| 1001-2000      | 5        | 9.26%   |
| Unknown        | 5        | 9.26%   |
| 251-500        | 4        | 7.41%   |
| More than 3000 | 3        | 5.56%   |
| 2001-3000      | 3        | 5.56%   |
| 501-1000       | 2        | 3.7%    |
| 51-100         | 2        | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Desktops | Drives | Percent |
|-----------------------------------------------|----------|--------|---------|
| Samsung Electronics MZVLQ1T0HBLB-00B00 1024GB | 1        | 1      | 33.33%  |
| Hitachi HTS543232A7A384 320GB                 | 1        | 1      | 33.33%  |
| Crucial CT128MX100SSD1 128GB                  | 1        | 2      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 33.33%  |
| Hitachi             | 1        | 1      | 33.33%  |
| Crucial             | 1        | 2      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 1        | 1      | 33.33%  |
| SSD  | 1        | 2      | 33.33%  |
| HDD  | 1        | 1      | 33.33%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 34       | 92     | 54.84%  |
| Works    | 25       | 68     | 40.32%  |
| Malfunc  | 3        | 4      | 4.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 33       | 39.29%  |
| AMD                          | 18       | 21.43%  |
| Samsung Electronics          | 13       | 15.48%  |
| Micron/Crucial Technology    | 4        | 4.76%   |
| Marvell Technology Group     | 4        | 4.76%   |
| Phison Electronics           | 3        | 3.57%   |
| Shenzhen Longsys Electronics | 2        | 2.38%   |
| SanDisk                      | 2        | 2.38%   |
| ASMedia Technology           | 2        | 2.38%   |
| Seagate Technology           | 1        | 1.19%   |
| MAXIO Technology (Hangzhou)  | 1        | 1.19%   |
| Kingston Technology Company  | 1        | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 11       | 11.34%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 6        | 6.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 5        | 5.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 5        | 5.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                                                   | 5        | 5.15%   |
| AMD 400 Series Chipset SATA Controller                                                                             | 4        | 4.12%   |
| Phison E12 NVMe Controller                                                                                         | 3        | 3.09%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                                               | 3        | 3.09%   |
| Intel SATA Controller [RAID mode]                                                                                  | 3        | 3.09%   |
| AMD 500 Series Chipset SATA Controller                                                                             | 3        | 3.09%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 2        | 2.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 2        | 2.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 2        | 2.06%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                                                          | 2        | 2.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                                                          | 2        | 2.06%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                                                       | 2        | 2.06%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                                                      | 2        | 2.06%   |
| AMD 600 Series Chipset SATA Controller                                                                             | 2        | 2.06%   |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                                                                  | 1        | 1.03%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1        | 1.03%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                                                              | 1        | 1.03%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                                                        | 1        | 1.03%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                                                          | 1        | 1.03%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 1        | 1.03%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                                                       | 1        | 1.03%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                                            | 1        | 1.03%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                                           | 1        | 1.03%   |
| Intel SATA controller                                                                                              | 1        | 1.03%   |
| Intel Raptor Lake SATA AHCI Controller                                                                             | 1        | 1.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                                      | 1        | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                                                  | 1        | 1.03%   |
| Intel Jasper Lake SATA AHCI Controller                                                                             | 1        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                                                              | 1        | 1.03%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                                                         | 1        | 1.03%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                                                  | 1        | 1.03%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                                               | 1        | 1.03%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                                                | 1        | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 1        | 1.03%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                                             | 1        | 1.03%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                                                | 1        | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 44       | 56.41%  |
| NVMe | 24       | 30.77%  |
| IDE  | 7        | 8.97%   |
| RAID | 3        | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 66.04%  |
| AMD    | 18       | 33.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 5.66%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 2        | 3.77%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 3.77%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 3.77%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1        | 1.89%   |
| Intel Xeon CPU E5-2698 v3 @ 2.30GHz         | 1        | 1.89%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1        | 1.89%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 1.89%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 1.89%   |
| Intel N100                                  | 1        | 1.89%   |
| Intel Core i7-9700KF CPU @ 3.60GHz          | 1        | 1.89%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.89%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.89%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1        | 1.89%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.89%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.89%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.89%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 1.89%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 1.89%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.89%   |
| Intel Core i5-6600T CPU @ 2.70GHz           | 1        | 1.89%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 1.89%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.89%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.89%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 1        | 1.89%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.89%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 1.89%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 1.89%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.89%   |
| Intel Core 2 CPU 6420 @ 2.13GHz             | 1        | 1.89%   |
| Intel Celeron N5105 @ 2.00GHz               | 1        | 1.89%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1        | 1.89%   |
| Intel 13th Gen Core i7-13700                | 1        | 1.89%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 1        | 1.89%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 1        | 1.89%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 1.89%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 1.89%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics  | 1        | 1.89%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 1        | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 10       | 18.87%  |
| AMD Ryzen 5             | 9        | 16.98%  |
| Intel Core i5           | 8        | 15.09%  |
| Other                   | 3        | 5.66%   |
| Intel Core 2 Quad       | 3        | 5.66%   |
| AMD Ryzen 9             | 3        | 5.66%   |
| AMD Ryzen 7             | 3        | 5.66%   |
| Intel Xeon              | 2        | 3.77%   |
| Intel Pentium           | 2        | 3.77%   |
| Intel Core i3           | 2        | 3.77%   |
| Intel Pentium Dual-Core | 1        | 1.89%   |
| Intel Core 2 Duo        | 1        | 1.89%   |
| Intel Core 2            | 1        | 1.89%   |
| Intel Celeron           | 1        | 1.89%   |
| Intel Atom              | 1        | 1.89%   |
| AMD Ryzen 7 PRO         | 1        | 1.89%   |
| AMD Phenom II X4        | 1        | 1.89%   |
| AMD FX                  | 1        | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 39.62%  |
| 6      | 12       | 22.64%  |
| 2      | 8        | 15.09%  |
| 8      | 7        | 13.21%  |
| 12     | 3        | 5.66%   |
| 32     | 1        | 1.89%   |
| 16     | 1        | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 52       | 98.11%  |
| 2      | 1        | 1.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 34       | 64.15%  |
| 1      | 19       | 35.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 53       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 18.87%  |
| 0x306c3    | 6        | 11.32%  |
| 0x906e9    | 3        | 5.66%   |
| 0x08701013 | 3        | 5.66%   |
| 0xa0655    | 2        | 3.77%   |
| 0x506e3    | 2        | 3.77%   |
| 0x1067a    | 2        | 3.77%   |
| 0x10677    | 2        | 3.77%   |
| 0x0a20120a | 2        | 3.77%   |
| 0x08701021 | 2        | 3.77%   |
| 0xb06e0    | 1        | 1.89%   |
| 0xa0671    | 1        | 1.89%   |
| 0xa0653    | 1        | 1.89%   |
| 0x906ed    | 1        | 1.89%   |
| 0x906ea    | 1        | 1.89%   |
| 0x906c0    | 1        | 1.89%   |
| 0x6fb      | 1        | 1.89%   |
| 0x6f6      | 1        | 1.89%   |
| 0x406f1    | 1        | 1.89%   |
| 0x406c4    | 1        | 1.89%   |
| 0x40651    | 1        | 1.89%   |
| 0x0a601206 | 1        | 1.89%   |
| 0x0a601203 | 1        | 1.89%   |
| 0x0a201009 | 1        | 1.89%   |
| 0x08600103 | 1        | 1.89%   |
| 0x08108102 | 1        | 1.89%   |
| 0x0810100b | 1        | 1.89%   |
| 0x0800820d | 1        | 1.89%   |
| 0x010000db | 1        | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 11       | 20.75%  |
| Zen 2            | 8        | 15.09%  |
| KabyLake         | 5        | 9.43%   |
| Penryn           | 4        | 7.55%   |
| Unknown          | 4        | 7.55%   |
| Zen 3            | 3        | 5.66%   |
| CometLake        | 3        | 5.66%   |
| Zen+             | 2        | 3.77%   |
| Skylake          | 2        | 3.77%   |
| Core             | 2        | 3.77%   |
| Zen              | 1        | 1.89%   |
| Westmere         | 1        | 1.89%   |
| Silvermont       | 1        | 1.89%   |
| Piledriver       | 1        | 1.89%   |
| K10              | 1        | 1.89%   |
| IvyBridge        | 1        | 1.89%   |
| Icelake          | 1        | 1.89%   |
| Broadwell        | 1        | 1.89%   |
| Alderlake Hybrid | 1        | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 22       | 39.29%  |
| Intel  | 21       | 37.5%   |
| AMD    | 13       | 23.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 6.78%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3        | 5.08%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 3.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 3.39%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2        | 3.39%   |
| Intel HD Graphics 530                                                                    | 2        | 3.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 3.39%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 1.69%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1        | 1.69%   |
| Nvidia GT218 [NVS 300]                                                                   | 1        | 1.69%   |
| Nvidia GT218 [GeForce G210]                                                              | 1        | 1.69%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1        | 1.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 1.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 1.69%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.69%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 1.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.69%   |
| Nvidia GK110GL [Quadro K6000]                                                            | 1        | 1.69%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1        | 1.69%   |
| Nvidia GF119 [GeForce GT 705]                                                            | 1        | 1.69%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                                       | 1        | 1.69%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 1        | 1.69%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 1.69%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                               | 1        | 1.69%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 1.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.69%   |
| Intel HD Graphics 630                                                                    | 1        | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 1.69%   |
| Intel DG2 [Arc A380]                                                                     | 1        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.69%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 1        | 1.69%   |
| Intel 82Q33 Express Integrated Graphics Controller                                       | 1        | 1.69%   |
| Intel 82G965 Integrated Graphics Controller                                              | 1        | 1.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.69%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 1        | 1.69%   |
| AMD RV620 PRO [Radeon HD 3470]                                                           | 1        | 1.69%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 1        | 1.69%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                                | 1        | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 22       | 40.74%  |
| 1 x Intel   | 18       | 33.33%  |
| 1 x AMD     | 10       | 18.52%  |
| 2 x AMD     | 3        | 5.56%   |
| Intel + AMD | 1        | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 60.38%  |
| Proprietary | 17       | 32.08%  |
| Unknown     | 4        | 7.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 50.94%  |
| 8.01-16.0  | 6        | 11.32%  |
| 1.01-2.0   | 5        | 9.43%   |
| 0.01-0.5   | 5        | 9.43%   |
| 3.01-4.0   | 4        | 7.55%   |
| 0.51-1.0   | 4        | 7.55%   |
| 5.01-6.0   | 2        | 3.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 17.46%  |
| Dell                 | 9        | 14.29%  |
| Goldstar             | 7        | 11.11%  |
| Iiyama               | 5        | 7.94%   |
| Hewlett-Packard      | 5        | 7.94%   |
| Philips              | 4        | 6.35%   |
| Medion               | 3        | 4.76%   |
| BenQ                 | 3        | 4.76%   |
| AOC                  | 3        | 4.76%   |
| Ancor Communications | 3        | 4.76%   |
| Eizo                 | 2        | 3.17%   |
| Acer                 | 2        | 3.17%   |
| ViewSonic            | 1        | 1.59%   |
| UGD                  | 1        | 1.59%   |
| PAR                  | 1        | 1.59%   |
| MSI                  | 1        | 1.59%   |
| Fujitsu Siemens      | 1        | 1.59%   |
| Belinea              | 1        | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch              | 2        | 3.13%   |
| ViewSonic VX2458 series VSC0437 1920x1080 521x293mm 23.5-inch         | 1        | 1.56%   |
| UGD Artist13.3pro UGD1302 1920x1080 294x165mm 13.3-inch               | 1        | 1.56%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1        | 1.56%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 600x340mm 27.2-inch  | 1        | 1.56%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1        | 1.56%   |
| Samsung Electronics SMT27A950 SAM080F 1920x1080 598x336mm 27.0-inch   | 1        | 1.56%   |
| Samsung Electronics SMS27A650 SAM082E 1920x1080 598x336mm 27.0-inch   | 1        | 1.56%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch     | 1        | 1.56%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 1.56%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1        | 1.56%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1        | 1.56%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1196x336mm 48.9-inch    | 1        | 1.56%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch    | 1        | 1.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 1.56%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1        | 1.56%   |
| Philips PHL 275C5 PHLC0E4 1920x1080 598x336mm 27.0-inch               | 1        | 1.56%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch             | 1        | 1.56%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1        | 1.56%   |
| PAR LED1920X1080 PAR9C63 1920x1080 710x400mm 32.1-inch                | 1        | 1.56%   |
| MSI MPG27CQ MSI3FA3 2560x1440 600x340mm 27.2-inch                     | 1        | 1.56%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch            | 1        | 1.56%   |
| Medion MD20434 MED36C8 1920x1080 521x293mm 23.5-inch                  | 1        | 1.56%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                 | 1        | 1.56%   |
| Iiyama X2485 IVM610F 1920x1200 518x324mm 24.1-inch                    | 1        | 1.56%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 1        | 1.56%   |
| Iiyama PL2796HS IVM6669 1920x1080 598x336mm 27.0-inch                 | 1        | 1.56%   |
| Iiyama PL2783Q IVM661F 2560x1440 597x336mm 27.0-inch                  | 1        | 1.56%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                  | 1        | 1.56%   |
| Hewlett-Packard S2331 HWP2907 1920x1080 509x286mm 23.0-inch           | 1        | 1.56%   |
| Hewlett-Packard L1950 HWP26E8 1280x1024 380x300mm 19.1-inch           | 1        | 1.56%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1        | 1.56%   |
| Hewlett-Packard 24y HPN3506 1920x1080 528x297mm 23.9-inch             | 1        | 1.56%   |
| Hewlett-Packard 23xi HWP3032 1920x1080 509x286mm 23.0-inch            | 1        | 1.56%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 1        | 1.56%   |
| Goldstar LG TV GSMC0A0 3840x2160                                      | 1        | 1.56%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 1        | 1.56%   |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                  | 1        | 1.56%   |
| Goldstar 24EA53 GSM59AC 1920x1080 510x290mm 23.1-inch                 | 1        | 1.56%   |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 509x286mm 23.0-inch      | 1        | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 33       | 55.93%  |
| 3840x2160 (4K)     | 8        | 13.56%  |
| 2560x1440 (QHD)    | 7        | 11.86%  |
| 1920x1200 (WUXGA)  | 3        | 5.08%   |
| 3840x1080          | 2        | 3.39%   |
| 1680x1050 (WSXGA+) | 1        | 1.69%   |
| 1600x1200          | 1        | 1.69%   |
| 1360x768           | 1        | 1.69%   |
| 1280x1024 (SXGA)   | 1        | 1.69%   |
| 1024x768 (XGA)     | 1        | 1.69%   |
| Unknown            | 1        | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 16       | 26.23%  |
| 23      | 12       | 19.67%  |
| 24      | 10       | 16.39%  |
| Unknown | 4        | 6.56%   |
| 31      | 3        | 4.92%   |
| 21      | 3        | 4.92%   |
| 72      | 2        | 3.28%   |
| 32      | 2        | 3.28%   |
| 49      | 1        | 1.64%   |
| 46      | 1        | 1.64%   |
| 25      | 1        | 1.64%   |
| 22      | 1        | 1.64%   |
| 20      | 1        | 1.64%   |
| 19      | 1        | 1.64%   |
| 18      | 1        | 1.64%   |
| 15      | 1        | 1.64%   |
| 13      | 1        | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 33       | 57.89%  |
| 401-500     | 6        | 10.53%  |
| 601-700     | 5        | 8.77%   |
| Unknown     | 4        | 7.02%   |
| 701-800     | 2        | 3.51%   |
| 1501-2000   | 2        | 3.51%   |
| 1001-1500   | 2        | 3.51%   |
| 351-400     | 1        | 1.75%   |
| 301-350     | 1        | 1.75%   |
| 201-300     | 1        | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 43       | 79.63%  |
| 16/10   | 4        | 7.41%   |
| Unknown | 3        | 5.56%   |
| 4/3     | 2        | 3.7%    |
| 5/4     | 1        | 1.85%   |
| 32/9    | 1        | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 22       | 36.67%  |
| 301-350        | 16       | 26.67%  |
| 351-500        | 5        | 8.33%   |
| 251-300        | 4        | 6.67%   |
| Unknown        | 4        | 6.67%   |
| More than 1000 | 2        | 3.33%   |
| 151-200        | 2        | 3.33%   |
| 501-1000       | 2        | 3.33%   |
| 71-80          | 1        | 1.67%   |
| 141-150        | 1        | 1.67%   |
| 101-110        | 1        | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 42       | 73.68%  |
| 101-120 | 6        | 10.53%  |
| Unknown | 4        | 7.02%   |
| 161-240 | 3        | 5.26%   |
| 1-50    | 2        | 3.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 70.37%  |
| 2     | 12       | 22.22%  |
| 0     | 3        | 5.56%   |
| 3     | 1        | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 33       | 45.83%  |
| Realtek Semiconductor    | 25       | 34.72%  |
| Qualcomm Atheros         | 5        | 6.94%   |
| Broadcom                 | 3        | 4.17%   |
| TP-Link                  | 1        | 1.39%   |
| Ralink Technology        | 1        | 1.39%   |
| MediaTek                 | 1        | 1.39%   |
| Marvell Technology Group | 1        | 1.39%   |
| D-Link                   | 1        | 1.39%   |
| Unknown                  | 1        | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19       | 22.35%  |
| Intel Wi-Fi 6 AX200                                                    | 7        | 8.24%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6        | 7.06%   |
| Intel I211 Gigabit Network Connection                                  | 6        | 7.06%   |
| Intel Ethernet Controller I225-V                                       | 5        | 5.88%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 4.71%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 2.35%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 2.35%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 2        | 2.35%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.18%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 1.18%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1        | 1.18%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 1.18%   |
| Realtek 802.11ac NIC                                                   | 1        | 1.18%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 1.18%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 1.18%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.18%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1        | 1.18%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 1.18%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 1.18%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1        | 1.18%   |
| Intel Wi-Fi 6 AX201 160MHz                                             | 1        | 1.18%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 1        | 1.18%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 1.18%   |
| Intel Ethernet controller                                              | 1        | 1.18%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.18%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 1.18%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.18%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 1.18%   |
| Intel CNVi: Wi-Fi                                                      | 1        | 1.18%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 1.18%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 1.18%   |
| Intel 82566DC Gigabit Network Connection                               | 1        | 1.18%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]   | 1        | 1.18%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter           | 1        | 1.18%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 46.15%  |
| Realtek Semiconductor | 5        | 19.23%  |
| Broadcom              | 3        | 11.54%  |
| Qualcomm Atheros      | 2        | 7.69%   |
| TP-Link               | 1        | 3.85%   |
| Ralink Technology     | 1        | 3.85%   |
| MediaTek              | 1        | 3.85%   |
| D-Link                | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 7        | 26.92%  |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 2        | 7.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1        | 3.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1        | 3.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1        | 3.85%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1        | 3.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 3.85%   |
| Realtek 802.11ac NIC                                                 | 1        | 3.85%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 3.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 1        | 3.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1        | 3.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1        | 3.85%   |
| Intel Wi-Fi 6 AX201 160MHz                                           | 1        | 3.85%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 1        | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 3.85%   |
| Intel CNVi: Wi-Fi                                                    | 1        | 3.85%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1        | 3.85%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter         | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 28       | 49.12%  |
| Realtek Semiconductor    | 25       | 43.86%  |
| Qualcomm Atheros         | 3        | 5.26%   |
| Marvell Technology Group | 1        | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19       | 32.76%  |
| Realtek RTL8125 2.5GbE Controller                                      | 6        | 10.34%  |
| Intel I211 Gigabit Network Connection                                  | 6        | 10.34%  |
| Intel Ethernet Controller I225-V                                       | 5        | 8.62%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 6.9%    |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 3.45%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 3.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 1.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 1.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 1.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 1.72%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 1.72%   |
| Intel Ethernet controller                                              | 1        | 1.72%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.72%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 1.72%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.72%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.72%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 1.72%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 1.72%   |
| Intel 82566DC Gigabit Network Connection                               | 1        | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 53       | 67.09%  |
| WiFi     | 25       | 31.65%  |
| Modem    | 1        | 1.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 45       | 81.82%  |
| WiFi     | 10       | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 49.06%  |
| 2     | 22       | 41.51%  |
| 3     | 4        | 7.55%   |
| 5     | 1        | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 39       | 73.58%  |
| Yes  | 14       | 26.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 55%     |
| Cambridge Silicon Radio | 4        | 20%     |
| IMC Networks            | 2        | 10%     |
| MediaTek                | 1        | 5%      |
| Broadcom                | 1        | 5%      |
| ASUSTek Computer        | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 6        | 30%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 20%     |
| Intel AX201 Bluetooth                               | 2        | 10%     |
| MediaTek Wireless_Device                            | 1        | 5%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5%      |
| Intel AX211 Bluetooth                               | 1        | 5%      |
| Intel AX210 Bluetooth                               | 1        | 5%      |
| IMC Networks Bluetooth Radio                        | 1        | 5%      |
| IMC Networks Bluetooth Module                       | 1        | 5%      |
| Broadcom Bluetooth 3.0 Device                       | 1        | 5%      |
| ASUS BCM20702A0                                     | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 34       | 37.36%  |
| Nvidia                                       | 21       | 23.08%  |
| AMD                                          | 21       | 23.08%  |
| Logitech                                     | 4        | 4.4%    |
| C-Media Electronics                          | 3        | 3.3%    |
| SteelSeries ApS                              | 2        | 2.2%    |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 1.1%    |
| www.hirestech.com 2012 REV 1.8               | 1        | 1.1%    |
| Sony                                         | 1        | 1.1%    |
| Micro Star International                     | 1        | 1.1%    |
| Kingston Technology                          | 1        | 1.1%    |
| Generalplus Technology                       | 1        | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                | 10       | 9.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 7        | 6.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 5        | 4.59%   |
| Intel 200 Series PCH HD Audio                                           | 5        | 4.59%   |
| AMD Family 17h/19h HD Audio Controller                                  | 5        | 4.59%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 4        | 3.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                          | 3        | 2.75%   |
| Nvidia High Definition Audio Controller                                 | 2        | 1.83%   |
| Nvidia GP108 High Definition Audio Controller                           | 2        | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                         | 2        | 1.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 2        | 1.83%   |
| Nvidia GA106 High Definition Audio Controller                           | 2        | 1.83%   |
| Logitech Blue Microphones                                               | 2        | 1.83%   |
| Intel Comet Lake PCH cAVS                                               | 2        | 1.83%   |
| Intel C610/X99 series chipset HD Audio Controller                       | 2        | 1.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                       | 2        | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 2        | 1.83%   |
| AMD SBx00 Azalia (Intel HDA)                                            | 2        | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 2        | 1.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2        | 1.83%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID          | 1        | 0.92%   |
| www.hirestech.com 2012 REV 1.8 Music Streamer II                        | 1        | 0.92%   |
| SteelSeries ApS SteelSeries Arctis 7                                    | 1        | 0.92%   |
| SteelSeries ApS Arctis Nova 3                                           | 1        | 0.92%   |
| Sony DualShock 4 [CUH-ZCT2x]                                            | 1        | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                           | 1        | 0.92%   |
| Nvidia GT216 HDMI Audio Controller                                      | 1        | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                           | 1        | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                           | 1        | 0.92%   |
| Nvidia GM204 High Definition Audio Controller                           | 1        | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 1        | 0.92%   |
| Nvidia GK110 High Definition Audio Controller                           | 1        | 0.92%   |
| Nvidia GK106 HDMI Audio Controller                                      | 1        | 0.92%   |
| Nvidia GF119 HDMI Audio Controller                                      | 1        | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                           | 1        | 0.92%   |
| Nvidia GA102 High Definition Audio Controller                           | 1        | 0.92%   |
| Micro Star International USB Audio                                      | 1        | 0.92%   |
| Logitech QuickCam Fusion                                                | 1        | 0.92%   |
| Logitech Premium Stereo USB Headset 350                                 | 1        | 0.92%   |
| Kingston Technology HyperX 7.1 Audio                                    | 1        | 0.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 6        | 19.35%  |
| Samsung Electronics          | 5        | 16.13%  |
| G.Skill                      | 5        | 16.13%  |
| Corsair                      | 5        | 16.13%  |
| Qimonda                      | 2        | 6.45%   |
| Crucial                      | 2        | 6.45%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 3.23%   |
| Unknown                      | 1        | 3.23%   |
| SK hynix                     | 1        | 3.23%   |
| Patriot                      | 1        | 3.23%   |
| Dane-Elec                    | 1        | 3.23%   |
| A-DATA Technology            | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1        | 3.13%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 1GB DIMM DDR2 667MT/s | 1        | 3.13%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                    | 1        | 3.13%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR4 2933MT/s           | 1        | 3.13%   |
| Samsung RAM M378B5773CH0-CH9 2048MB DIMM DDR3 1867MT/s        | 1        | 3.13%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s           | 1        | 3.13%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s           | 1        | 3.13%   |
| Samsung RAM M378A1G44AB0-CWE 8192MB DIMM DDR4 3200MT/s        | 1        | 3.13%   |
| Samsung RAM 99U5429-007.A00LF 2GB DIMM DDR2 800MT/s           | 1        | 3.13%   |
| Qimonda RAM Module 2GB DIMM DDR2 667MT/s                      | 1        | 3.13%   |
| Qimonda RAM 64T256020EU2.5C2 2048MB DIMM SDRAM                | 1        | 3.13%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s            | 1        | 3.13%   |
| Kingston RAM KHX4000C19D4/8GX 8GB DIMM DDR4 3600MT/s          | 1        | 3.13%   |
| Kingston RAM KHX2400C15S4/16G 16GB SODIMM DDR4 2400MT/s       | 1        | 3.13%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s           | 1        | 3.13%   |
| Kingston RAM 99U5700-028.A00G 8GB SODIMM DDR4 2400MT/s        | 1        | 3.13%   |
| Kingston RAM 9905734-082.A00G 16384MB DIMM DDR4 3200MT/s      | 1        | 3.13%   |
| Kingston RAM 9905625-074.A00G 16GB DIMM DDR4 2400MT/s         | 1        | 3.13%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s          | 1        | 3.13%   |
| G.Skill RAM F5-6000J3040F16G 16GB DIMM DDR5 6000MT/s          | 1        | 3.13%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s          | 1        | 3.13%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s          | 1        | 3.13%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s        | 1        | 3.13%   |
| Dane-Elec RAM Module 1GB DIMM DDR2 667MT/s                    | 1        | 3.13%   |
| Crucial RAM CT8G4DFS8266.C8FE 8GB DIMM DDR4 2667MT/s          | 1        | 3.13%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 1        | 3.13%   |
| Corsair RAM Module 2GB DIMM DDR2 800MT/s                      | 1        | 3.13%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s        | 1        | 3.13%   |
| Corsair RAM CMW16GX4M2A2666C16 8GB DIMM DDR4 2667MT/s         | 1        | 3.13%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s        | 1        | 3.13%   |
| Corsair RAM CMK16GX4M1B3000C15 16GB DIMM DDR4 3400MT/s        | 1        | 3.13%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                   | 1        | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 17       | 58.62%  |
| DDR3   | 4        | 13.79%  |
| DDR2   | 3        | 10.34%  |
| SDRAM  | 2        | 6.9%    |
| DDR5   | 2        | 6.9%    |
| LPDDR4 | 1        | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 24       | 85.71%  |
| SODIMM       | 3        | 10.71%  |
| Row Of Chips | 1        | 3.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 34.48%  |
| 16384 | 9        | 31.03%  |
| 2048  | 4        | 13.79%  |
| 32768 | 3        | 10.34%  |
| 4096  | 2        | 6.9%    |
| 1024  | 1        | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 5        | 17.24%  |
| 3200  | 4        | 13.79%  |
| 2400  | 3        | 10.34%  |
| 2667  | 2        | 6.9%    |
| 1867  | 2        | 6.9%    |
| 1600  | 2        | 6.9%    |
| 800   | 2        | 6.9%    |
| 6400  | 1        | 3.45%   |
| 6000  | 1        | 3.45%   |
| 3534  | 1        | 3.45%   |
| 3500  | 1        | 3.45%   |
| 3400  | 1        | 3.45%   |
| 2933  | 1        | 3.45%   |
| 1333  | 1        | 3.45%   |
| 1066  | 1        | 3.45%   |
| 667   | 1        | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| HP OfficeJet 6950        | 1        | 33.33%  |
| HP Officejet 6600        | 1        | 33.33%  |
| HP OfficeJet 5200 series | 1        | 33.33%  |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 4        | 40%     |
| Microdia            | 2        | 20%     |
| YGTek               | 1        | 10%     |
| Huawei Technologies | 1        | 10%     |
| Cubeternet          | 1        | 10%     |
| Alcor Micro         | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech B525 HD Webcam         | 2        | 20%     |
| YGTek Webcam                    | 1        | 10%     |
| Microdia USB 2.0 Camera         | 1        | 10%     |
| Microdia Camera                 | 1        | 10%     |
| Logitech Webcam C270            | 1        | 10%     |
| Logitech HD Webcam C910         | 1        | 10%     |
| Huawei HiCamera                 | 1        | 10%     |
| Cubeternet GL-UPC822 UVC WebCam | 1        | 10%     |
| Alcor Micro USB 2.0 PC Camera   | 1        | 10%     |

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


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 42       | 79.25%  |
| 1     | 10       | 18.87%  |
| 3     | 1        | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 3        | 27.27%  |
| Unassigned class         | 2        | 18.18%  |
| Network                  | 1        | 9.09%   |
| Net/wireless             | 1        | 9.09%   |
| Net/ethernet             | 1        | 9.09%   |
| Multimedia controller    | 1        | 9.09%   |
| Communication controller | 1        | 9.09%   |
| Chipcard                 | 1        | 9.09%   |

