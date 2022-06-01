Linux in Ecuador - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ecuador.

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

Total: 87

| Vendor        | Model                | Probe                                                      | Date         |
|---------------|----------------------|------------------------------------------------------------|--------------|
| ASUSTek       | H81M-A               | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| ASUSTek       | PRIME A320M-K        | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K        | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| Intel         | DH61BF AAG81311-101  | [9c54929196](https://linux-hardware.org/?probe=9c54929196) | May 11, 2022 |
| Gigabyte      | X58A-UD3R            | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Gigabyte      | H97-Gaming 3         | [150f5a4bd0](https://linux-hardware.org/?probe=150f5a4bd0) | Apr 30, 2022 |
| Biostar       | G41D3C               | [a6db6a2cdf](https://linux-hardware.org/?probe=a6db6a2cdf) | Apr 27, 2022 |
| Biostar       | G41D3C               | [ac5c2d8b54](https://linux-hardware.org/?probe=ac5c2d8b54) | Apr 23, 2022 |
| Biostar       | G41D3C               | [6fdf919c55](https://linux-hardware.org/?probe=6fdf919c55) | Apr 23, 2022 |
| ASUSTek       | H81M-A               | [01c63fa622](https://linux-hardware.org/?probe=01c63fa622) | Apr 22, 2022 |
| Foxconn       | Cinema Series FAB    | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | H81M-A               | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Gigabyte      | H97-Gaming 3         | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| Google        | Panther              | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther              | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| ASUSTek       | H81M-A               | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| TPV-INVENT... | 2AF2 A01             | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| Biostar       | G31-M7 TE            | [f08be29479](https://linux-hardware.org/?probe=f08be29479) | Mar 12, 2022 |
| Intel         | H81                  | [a62759e3c8](https://linux-hardware.org/?probe=a62759e3c8) | Feb 27, 2022 |
| Intel         | H81                  | [d1f816774f](https://linux-hardware.org/?probe=d1f816774f) | Feb 27, 2022 |
| Gigabyte      | B450M DS3H-CF        | [14f2fcb8be](https://linux-hardware.org/?probe=14f2fcb8be) | Feb 16, 2022 |
| Gigabyte      | H97-Gaming 3         | [b5ee6e292d](https://linux-hardware.org/?probe=b5ee6e292d) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H-CF        | [4cabeb69e3](https://linux-hardware.org/?probe=4cabeb69e3) | Feb 04, 2022 |
| Biostar       | H61MGV3              | [2f9b9ff8ee](https://linux-hardware.org/?probe=2f9b9ff8ee) | Jan 13, 2022 |
| Biostar       | H61MGV3              | [332b6e1f8a](https://linux-hardware.org/?probe=332b6e1f8a) | Jan 12, 2022 |
| Biostar       | A68N-2100            | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Intel         | DG41RQ AAE54511-205  | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205  | [d84eb83569](https://linux-hardware.org/?probe=d84eb83569) | Dec 08, 2021 |
| ASUSTek       | H81M-A               | [c7762271da](https://linux-hardware.org/?probe=c7762271da) | Nov 18, 2021 |
| Gigabyte      | H310M H x.x          | [419e0c7eb2](https://linux-hardware.org/?probe=419e0c7eb2) | Oct 21, 2021 |
| ASUSTek       | PRIME H410M-E        | [b5d6c0ae9c](https://linux-hardware.org/?probe=b5d6c0ae9c) | Oct 20, 2021 |
| Gigabyte      | H310M H x.x          | [3fe7cdd0f9](https://linux-hardware.org/?probe=3fe7cdd0f9) | Oct 14, 2021 |
| ASRock        | B450 Gaming K4       | [0de7c95a46](https://linux-hardware.org/?probe=0de7c95a46) | Oct 12, 2021 |
| Foxconn       | H61MXL-K             | [e776e3f647](https://linux-hardware.org/?probe=e776e3f647) | Sep 08, 2021 |
| ASUSTek       | P7P55D-E             | [5e208c3927](https://linux-hardware.org/?probe=5e208c3927) | Sep 02, 2021 |
| ASUSTek       | PRIME H410M-E        | [f667f32489](https://linux-hardware.org/?probe=f667f32489) | Aug 31, 2021 |
| MSI           | Z390-A PRO           | [72cddcc75c](https://linux-hardware.org/?probe=72cddcc75c) | Aug 29, 2021 |
| Gigabyte      | H410M H V2           | [84faf4af12](https://linux-hardware.org/?probe=84faf4af12) | Aug 22, 2021 |
| Gigabyte      | H410M H V2           | [5e4047a59c](https://linux-hardware.org/?probe=5e4047a59c) | Aug 22, 2021 |
| Gigabyte      | H97M-DS3P            | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A        | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | PRIME A520M-K        | [33c83a65d8](https://linux-hardware.org/?probe=33c83a65d8) | Jul 24, 2021 |
| Biostar       | A68N-2100            | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Pegatron      | 2ACC                 | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| ASUSTek       | PRIME A520M-K        | [0f90b91804](https://linux-hardware.org/?probe=0f90b91804) | Jun 25, 2021 |
| ASUSTek       | H81M-K               | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | PRIME J4005I-C       | [d8be675a5d](https://linux-hardware.org/?probe=d8be675a5d) | May 19, 2021 |
| ASRock        | B550M-HDV            | [aaee9d166a](https://linux-hardware.org/?probe=aaee9d166a) | Apr 26, 2021 |
| Gigabyte      | H81M-H               | [e34aa83281](https://linux-hardware.org/?probe=e34aa83281) | Apr 16, 2021 |
| Intel         | DB75EN AAG39650-302  | [02f80c53ea](https://linux-hardware.org/?probe=02f80c53ea) | Mar 05, 2021 |
| ASUSTek       | PRIME A520M-K        | [d5ef689e13](https://linux-hardware.org/?probe=d5ef689e13) | Feb 27, 2021 |
| Shuttle       | SFM27 V20            | [14a841b718](https://linux-hardware.org/?probe=14a841b718) | Feb 21, 2021 |
| Biostar       | G31-M7 TE            | [c30b6ae115](https://linux-hardware.org/?probe=c30b6ae115) | Jan 24, 2021 |
| Intel         | DG33BU AAD79951-407  | [c0e2f63e04](https://linux-hardware.org/?probe=c0e2f63e04) | Dec 20, 2020 |
| Intel         | DP55KG AAE47218-404  | [5604be0f67](https://linux-hardware.org/?probe=5604be0f67) | Nov 25, 2020 |
| ASUSTek       | PRIME A320M-A        | [cffed87fd7](https://linux-hardware.org/?probe=cffed87fd7) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A        | [1505bb0505](https://linux-hardware.org/?probe=1505bb0505) | Nov 21, 2020 |
| MSI           | B75A-G43             | [fd4f003fa9](https://linux-hardware.org/?probe=fd4f003fa9) | Sep 28, 2020 |
| MSI           | B75A-G43             | [148c1711fe](https://linux-hardware.org/?probe=148c1711fe) | Sep 28, 2020 |
| ECS           | H61H2-MV             | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| HP            | 1497                 | [02645aa87a](https://linux-hardware.org/?probe=02645aa87a) | Sep 15, 2020 |
| Biostar       | P4M90-M7 Ver:1.0     | [cb7ecd71b1](https://linux-hardware.org/?probe=cb7ecd71b1) | Sep 07, 2020 |
| Biostar       | P4M90-M7 Ver:1.0     | [917f5d9bd0](https://linux-hardware.org/?probe=917f5d9bd0) | Sep 07, 2020 |
| Biostar       | A68N-2100            | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| Gigabyte      | H81M-H               | [ca4fa8777d](https://linux-hardware.org/?probe=ca4fa8777d) | Aug 10, 2020 |
| HP            | ProLiant MicroServer | [87be3f63a0](https://linux-hardware.org/?probe=87be3f63a0) | Jul 09, 2020 |
| HP            | ProLiant MicroServer | [82f2a3732c](https://linux-hardware.org/?probe=82f2a3732c) | Jul 09, 2020 |
| Biostar       | A68N-2100            | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| ASUSTek       | H81M-K               | [0a4363a1ba](https://linux-hardware.org/?probe=0a4363a1ba) | Jun 28, 2020 |
| Biostar       | G31-M7 TE            | [56a67b5ddc](https://linux-hardware.org/?probe=56a67b5ddc) | Jun 22, 2020 |
| ASRock        | H61M-VS              | [87788ef1c8](https://linux-hardware.org/?probe=87788ef1c8) | Jun 11, 2020 |
| Biostar       | H81MLV3              | [d912bc8bdc](https://linux-hardware.org/?probe=d912bc8bdc) | May 12, 2020 |
| Biostar       | G31-M7 TE            | [21283d29b3](https://linux-hardware.org/?probe=21283d29b3) | May 10, 2020 |
| Foxconn       | H61MXE/-S/-V/-K      | [f43cc5765b](https://linux-hardware.org/?probe=f43cc5765b) | Apr 25, 2020 |
| Intel         | DH61WW AAG23116-203  | [ca1baf42c2](https://linux-hardware.org/?probe=ca1baf42c2) | Dec 18, 2019 |
| Intel         | DH61WW AAG23116-203  | [b3270b7077](https://linux-hardware.org/?probe=b3270b7077) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA  | [5097027e46](https://linux-hardware.org/?probe=5097027e46) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA  | [3fc475bd40](https://linux-hardware.org/?probe=3fc475bd40) | Dec 05, 2019 |
| HP            | 18E7                 | [2d2bb51f61](https://linux-hardware.org/?probe=2d2bb51f61) | Aug 27, 2019 |
| ASUSTek       | PRIME A320M-A        | [29c5995612](https://linux-hardware.org/?probe=29c5995612) | Jul 29, 2019 |
| Dell          | 0CRH6C A02           | [9bfbd0c2f6](https://linux-hardware.org/?probe=9bfbd0c2f6) | May 16, 2019 |
| Intel         | DZ68DB AAG27985-101  | [ebe6dcff50](https://linux-hardware.org/?probe=ebe6dcff50) | May 05, 2019 |
| Intel         | DZ68DB AAG27985-101  | [2d6ea0b597](https://linux-hardware.org/?probe=2d6ea0b597) | May 05, 2019 |
| Cartimex      | H61H2-MV             | [aa36029d7f](https://linux-hardware.org/?probe=aa36029d7f) | Apr 09, 2019 |
| ASUSTek       | PRIME A320M-A        | [d857fd97fd](https://linux-hardware.org/?probe=d857fd97fd) | Mar 11, 2019 |
| ASUSTek       | PRIME A320M-A        | [4b50a9d6a2](https://linux-hardware.org/?probe=4b50a9d6a2) | Jan 08, 2019 |
| ASUSTek       | PRIME A320M-A        | [91f58fec26](https://linux-hardware.org/?probe=91f58fec26) | Jan 08, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 13       | 22.81%  |
| Ubuntu 18.04       | 9        | 15.79%  |
| OpenMandriva 4.2   | 3        | 5.26%   |
| Debian 11          | 3        | 5.26%   |
| Zorin 16           | 2        | 3.51%   |
| OpenMandriva 4.3   | 2        | 3.51%   |
| Linux Mint 19.1    | 2        | 3.51%   |
| Fedora 34          | 2        | 3.51%   |
| Xubuntu 18.04      | 1        | 1.75%   |
| Ubuntu 22.04       | 1        | 1.75%   |
| Ubuntu 21.10       | 1        | 1.75%   |
| Ubuntu 16.04       | 1        | 1.75%   |
| Pop!_OS 21.04      | 1        | 1.75%   |
| Pop!_OS 20.04      | 1        | 1.75%   |
| Peppermint 10      | 1        | 1.75%   |
| openSUSE Leap-15.2 | 1        | 1.75%   |
| Manjaro 21.2.5     | 1        | 1.75%   |
| Manjaro            | 1        | 1.75%   |
| Lubuntu 16.04      | 1        | 1.75%   |
| LMDE 4             | 1        | 1.75%   |
| Linux Mint 20.3    | 1        | 1.75%   |
| Linux Mint 20.1    | 1        | 1.75%   |
| Fedora 36          | 1        | 1.75%   |
| Fedora 35          | 1        | 1.75%   |
| Elementary 5.1.7   | 1        | 1.75%   |
| Debian 10          | 1        | 1.75%   |
| Clear Linux 35810  | 1        | 1.75%   |
| CentOS 7           | 1        | 1.75%   |
| Arch               | 1        | 1.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 25       | 43.86%  |
| OpenMandriva | 5        | 8.77%   |
| Linux Mint   | 4        | 7.02%   |
| Fedora       | 4        | 7.02%   |
| Debian       | 4        | 7.02%   |
| Zorin        | 2        | 3.51%   |
| Pop!_OS      | 2        | 3.51%   |
| Manjaro      | 2        | 3.51%   |
| Xubuntu      | 1        | 1.75%   |
| Peppermint   | 1        | 1.75%   |
| openSUSE     | 1        | 1.75%   |
| Lubuntu      | 1        | 1.75%   |
| LMDE         | 1        | 1.75%   |
| Elementary   | 1        | 1.75%   |
| Clear Linux  | 1        | 1.75%   |
| CentOS       | 1        | 1.75%   |
| Arch         | 1        | 1.75%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002     | 3        | 4.76%   |
| 5.8.0-50-generic             | 2        | 3.17%   |
| 5.4.0-73-generic             | 2        | 3.17%   |
| 5.4.0-54-generic             | 2        | 3.17%   |
| 5.4.0-29-generic             | 2        | 3.17%   |
| 5.16.7-desktop-1omv4003      | 2        | 3.17%   |
| 4.15.0-20-generic            | 2        | 3.17%   |
| 5.8.0-63-generic             | 1        | 1.59%   |
| 5.8.0-41-generic             | 1        | 1.59%   |
| 5.8.0-40-generic             | 1        | 1.59%   |
| 5.7.0-0.bpo.2-amd64          | 1        | 1.59%   |
| 5.4.0-91-generic             | 1        | 1.59%   |
| 5.4.0-81-generic             | 1        | 1.59%   |
| 5.4.0-7634-generic           | 1        | 1.59%   |
| 5.4.0-45-generic             | 1        | 1.59%   |
| 5.4.0-42-generic             | 1        | 1.59%   |
| 5.4.0-37-generic             | 1        | 1.59%   |
| 5.3.18-lp152.87-default      | 1        | 1.59%   |
| 5.3.0-46-generic             | 1        | 1.59%   |
| 5.17.9-602.inttf.fc36.x86_64 | 1        | 1.59%   |
| 5.17.4-200.fc35.x86_64       | 1        | 1.59%   |
| 5.16.7-1122.native           | 1        | 1.59%   |
| 5.16.0-arch1-1               | 1        | 1.59%   |
| 5.15.28-1-MANJARO            | 1        | 1.59%   |
| 5.15.0-30-generic            | 1        | 1.59%   |
| 5.13.4-200.fc34.x86_64       | 1        | 1.59%   |
| 5.13.0-39-generic            | 1        | 1.59%   |
| 5.13.0-35-generic            | 1        | 1.59%   |
| 5.13.0-30-generic            | 1        | 1.59%   |
| 5.13.0-19-generic            | 1        | 1.59%   |
| 5.11.16-300.fc34.x86_64      | 1        | 1.59%   |
| 5.11.0-7633-generic          | 1        | 1.59%   |
| 5.11.0-46-generic            | 1        | 1.59%   |
| 5.11.0-34-generic            | 1        | 1.59%   |
| 5.11.0-27-generic            | 1        | 1.59%   |
| 5.10.59-1-MANJARO            | 1        | 1.59%   |
| 5.10.0-9-amd64               | 1        | 1.59%   |
| 5.10.0-8-amd64               | 1        | 1.59%   |
| 5.10.0-11-amd64              | 1        | 1.59%   |
| 5.0.10-050010-generic        | 1        | 1.59%   |
| 5.0.0-37-generic             | 1        | 1.59%   |
| 5.0.0-23-generic             | 1        | 1.59%   |
| 4.19.0-20-amd64              | 1        | 1.59%   |
| 4.19.0-041900-generic        | 1        | 1.59%   |
| 4.18.0-17-generic            | 1        | 1.59%   |
| 4.15.0-50-generic            | 1        | 1.59%   |
| 4.15.0-45-generic            | 1        | 1.59%   |
| 4.15.0-43-generic            | 1        | 1.59%   |
| 4.15.0-142-generic           | 1        | 1.59%   |
| 4.15.0-118-generic           | 1        | 1.59%   |
| 4.15.0-112-generic           | 1        | 1.59%   |
| 4.15.0-109-generic           | 1        | 1.59%   |
| 4.15.0-107-generic           | 1        | 1.59%   |
| 4.15.0-102-generic           | 1        | 1.59%   |
| 3.10.0-1127.19.1.el7.x86_64  | 1        | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 11       | 18.64%  |
| 4.15.0  | 9        | 15.25%  |
| 5.8.0   | 5        | 8.47%   |
| 5.11.0  | 4        | 6.78%   |
| 5.16.7  | 3        | 5.08%   |
| 5.13.0  | 3        | 5.08%   |
| 5.10.14 | 3        | 5.08%   |
| 5.10.0  | 3        | 5.08%   |
| 5.0.0   | 2        | 3.39%   |
| 4.19.0  | 2        | 3.39%   |
| 5.7.0   | 1        | 1.69%   |
| 5.3.18  | 1        | 1.69%   |
| 5.3.0   | 1        | 1.69%   |
| 5.17.9  | 1        | 1.69%   |
| 5.17.4  | 1        | 1.69%   |
| 5.16.0  | 1        | 1.69%   |
| 5.15.28 | 1        | 1.69%   |
| 5.15.0  | 1        | 1.69%   |
| 5.13.4  | 1        | 1.69%   |
| 5.11.16 | 1        | 1.69%   |
| 5.10.59 | 1        | 1.69%   |
| 5.0.10  | 1        | 1.69%   |
| 4.18.0  | 1        | 1.69%   |
| 3.10.0  | 1        | 1.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 11       | 18.64%  |
| 4.15    | 9        | 15.25%  |
| 5.10    | 7        | 11.86%  |
| 5.8     | 5        | 8.47%   |
| 5.11    | 5        | 8.47%   |
| 5.16    | 4        | 6.78%   |
| 5.13    | 4        | 6.78%   |
| 5.0     | 3        | 5.08%   |
| 5.3     | 2        | 3.39%   |
| 5.17    | 2        | 3.39%   |
| 5.15    | 2        | 3.39%   |
| 4.19    | 2        | 3.39%   |
| 5.7     | 1        | 1.69%   |
| 4.18    | 1        | 1.69%   |
| 3.10    | 1        | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 53       | 96.36%  |
| i686   | 2        | 3.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 26       | 46.43%  |
| KDE5       | 8        | 14.29%  |
| Unknown    | 8        | 14.29%  |
| X-Cinnamon | 5        | 8.93%   |
| XFCE       | 3        | 5.36%   |
| MATE       | 2        | 3.57%   |
| LXDE       | 2        | 3.57%   |
| qtile      | 1        | 1.79%   |
| Pantheon   | 1        | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 43       | 76.79%  |
| Wayland | 9        | 16.07%  |
| Unknown | 3        | 5.36%   |
| Tty     | 1        | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 58.33%  |
| SDDM    | 8        | 13.33%  |
| GDM     | 8        | 13.33%  |
| GDM3    | 5        | 8.33%   |
| TDM     | 2        | 3.33%   |
| LightDM | 2        | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_EC   | 28       | 50%     |
| en_US   | 15       | 26.79%  |
| Unknown | 6        | 10.71%  |
| es_ES   | 4        | 7.14%   |
| ru_RU   | 1        | 1.79%   |
| es_PE   | 1        | 1.79%   |
| C       | 1        | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 39       | 70.91%  |
| EFI  | 16       | 29.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 41       | 73.21%  |
| Overlay | 6        | 10.71%  |
| Xfs     | 3        | 5.36%   |
| Btrfs   | 3        | 5.36%   |
| Unknown | 3        | 5.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 40       | 71.43%  |
| GPT     | 9        | 16.07%  |
| MBR     | 7        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 82.76%  |
| Yes       | 10       | 17.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 62.5%   |
| Yes       | 21       | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 14       | 25.45%  |
| Intel               | 8        | 14.55%  |
| Gigabyte Technology | 8        | 14.55%  |
| Biostar             | 7        | 12.73%  |
| Hewlett-Packard     | 3        | 5.45%   |
| Foxconn             | 3        | 5.45%   |
| ASRock              | 3        | 5.45%   |
| MSI                 | 2        | 3.64%   |
| TPV-INVENTA         | 1        | 1.82%   |
| Shuttle             | 1        | 1.82%   |
| Pegatron            | 1        | 1.82%   |
| Google              | 1        | 1.82%   |
| ECS                 | 1        | 1.82%   |
| Dell                | 1        | 1.82%   |
| Cartimex            | 1        | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 4        | 7.27%   |
| ASUS PRIME A320M-A               | 3        | 5.45%   |
| Gigabyte H81M-H                  | 2        | 3.64%   |
| Biostar G31-M7 TE                | 2        | 3.64%   |
| TPV-INVENTA 2AF2 A01             | 1        | 1.82%   |
| Shuttle SFM27                    | 1        | 1.82%   |
| Pegatron CQ1506LA                | 1        | 1.82%   |
| MSI MS-7B98                      | 1        | 1.82%   |
| MSI MS-7758                      | 1        | 1.82%   |
| Intel H81                        | 1        | 1.82%   |
| Intel DZ68DB AAG27985-101        | 1        | 1.82%   |
| Intel DP55KG AAE47218-404        | 1        | 1.82%   |
| Intel DH61WW AAG23116-203        | 1        | 1.82%   |
| Intel DH61BF AAG81311-101        | 1        | 1.82%   |
| Intel DG41RQ AAE54511-205        | 1        | 1.82%   |
| Intel DG33BU AAD79951-407        | 1        | 1.82%   |
| Intel DB75EN AAG39650-302        | 1        | 1.82%   |
| HP ProLiant MicroServer          | 1        | 1.82%   |
| HP ProDesk 600 G1 SFF            | 1        | 1.82%   |
| HP Compaq 6200 Pro MT PC         | 1        | 1.82%   |
| Google Panther                   | 1        | 1.82%   |
| Gigabyte X58A-UD3R               | 1        | 1.82%   |
| Gigabyte H97M-DS3P               | 1        | 1.82%   |
| Gigabyte H97-Gaming 3            | 1        | 1.82%   |
| Gigabyte H410M H V2              | 1        | 1.82%   |
| Gigabyte H310M H 2.0             | 1        | 1.82%   |
| Gigabyte B450M DS3H              | 1        | 1.82%   |
| Foxconn H61MXL-K                 | 1        | 1.82%   |
| Foxconn H61MXE/-S/-V/-K          | 1        | 1.82%   |
| Foxconn Cinema Series            | 1        | 1.82%   |
| ECS H61H2-MV                     | 1        | 1.82%   |
| Dell Precision WorkStation T5500 | 1        | 1.82%   |
| Cartimex H61H2-MV                | 1        | 1.82%   |
| Biostar P4M90-M7                 | 1        | 1.82%   |
| Biostar H81MLV3                  | 1        | 1.82%   |
| Biostar H61MGV3                  | 1        | 1.82%   |
| Biostar G41D3C                   | 1        | 1.82%   |
| Biostar A68N-2100                | 1        | 1.82%   |
| ASUS PRIME J4005I-C              | 1        | 1.82%   |
| ASUS PRIME H410M-E               | 1        | 1.82%   |
| ASUS PRIME B450M-A               | 1        | 1.82%   |
| ASUS PRIME A520M-K               | 1        | 1.82%   |
| ASUS PRIME A320M-K               | 1        | 1.82%   |
| ASUS P7P55D-E                    | 1        | 1.82%   |
| ASUS 970 PRO GAMING/AURA         | 1        | 1.82%   |
| ASRock H61M-VS                   | 1        | 1.82%   |
| ASRock B550M-HDV                 | 1        | 1.82%   |
| ASRock B450 Gaming K4            | 1        | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 8        | 14.55%  |
| ASUS All            | 4        | 7.27%   |
| Gigabyte H81M-H     | 2        | 3.64%   |
| Biostar G31-M7      | 2        | 3.64%   |
| TPV-INVENTA 2AF2    | 1        | 1.82%   |
| Shuttle SFM27       | 1        | 1.82%   |
| Pegatron CQ1506LA   | 1        | 1.82%   |
| MSI MS-7B98         | 1        | 1.82%   |
| MSI MS-7758         | 1        | 1.82%   |
| Intel H81           | 1        | 1.82%   |
| Intel DZ68DB        | 1        | 1.82%   |
| Intel DP55KG        | 1        | 1.82%   |
| Intel DH61WW        | 1        | 1.82%   |
| Intel DH61BF        | 1        | 1.82%   |
| Intel DG41RQ        | 1        | 1.82%   |
| Intel DG33BU        | 1        | 1.82%   |
| Intel DB75EN        | 1        | 1.82%   |
| HP ProLiant         | 1        | 1.82%   |
| HP ProDesk          | 1        | 1.82%   |
| HP Compaq           | 1        | 1.82%   |
| Google Panther      | 1        | 1.82%   |
| Gigabyte X58A-UD3R  | 1        | 1.82%   |
| Gigabyte H97M-DS3P  | 1        | 1.82%   |
| Gigabyte H97-Gaming | 1        | 1.82%   |
| Gigabyte H410M      | 1        | 1.82%   |
| Gigabyte H310M      | 1        | 1.82%   |
| Gigabyte B450M      | 1        | 1.82%   |
| Foxconn H61MXL-K    | 1        | 1.82%   |
| Foxconn H61MXE      | 1        | 1.82%   |
| Foxconn Cinema      | 1        | 1.82%   |
| ECS H61H2-MV        | 1        | 1.82%   |
| Dell Precision      | 1        | 1.82%   |
| Cartimex H61H2-MV   | 1        | 1.82%   |
| Biostar P4M90-M7    | 1        | 1.82%   |
| Biostar H81MLV3     | 1        | 1.82%   |
| Biostar H61MGV3     | 1        | 1.82%   |
| Biostar G41D3C      | 1        | 1.82%   |
| Biostar A68N-2100   | 1        | 1.82%   |
| ASUS P7P55D-E       | 1        | 1.82%   |
| ASUS 970            | 1        | 1.82%   |
| ASRock H61M-VS      | 1        | 1.82%   |
| ASRock B550M-HDV    | 1        | 1.82%   |
| ASRock B450         | 1        | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 9        | 16.36%  |
| 2012 | 7        | 12.73%  |
| 2011 | 6        | 10.91%  |
| 2018 | 5        | 9.09%   |
| 2017 | 4        | 7.27%   |
| 2009 | 4        | 7.27%   |
| 2020 | 3        | 5.45%   |
| 2014 | 3        | 5.45%   |
| 2010 | 3        | 5.45%   |
| 2008 | 3        | 5.45%   |
| 2021 | 2        | 3.64%   |
| 2019 | 2        | 3.64%   |
| 2007 | 2        | 3.64%   |
| 2016 | 1        | 1.82%   |
| 2015 | 1        | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 55       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 55       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 54       | 98.18%  |
| Yes  | 1        | 1.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 17       | 29.82%  |
| 4.01-8.0   | 13       | 22.81%  |
| 3.01-4.0   | 11       | 19.3%   |
| 16.01-24.0 | 6        | 10.53%  |
| 1.01-2.0   | 4        | 7.02%   |
| 32.01-64.0 | 3        | 5.26%   |
| 24.01-32.0 | 3        | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 23       | 35.94%  |
| 2.01-3.0  | 17       | 26.56%  |
| 3.01-4.0  | 10       | 15.63%  |
| 4.01-8.0  | 8        | 12.5%   |
| 8.01-16.0 | 2        | 3.13%   |
| 0.51-1.0  | 2        | 3.13%   |
| 0.01-0.5  | 2        | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 56.14%  |
| 2      | 16       | 28.07%  |
| 3      | 8        | 14.04%  |
| 5      | 1        | 1.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 51.79%  |
| No        | 27       | 48.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 55       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 70.91%  |
| Yes       | 16       | 29.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 85.45%  |
| Yes       | 8        | 14.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ecuador | 55       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Quito                          | 20       | 36.36%  |
| Guayaquil                      | 18       | 32.73%  |
| Manta                          | 3        | 5.45%   |
| Riobamba                       | 2        | 3.64%   |
| Cuenca                         | 2        | 3.64%   |
| Cotacachi                      | 2        | 3.64%   |
| Santo Domingo de los Colorados | 1        | 1.82%   |
| Quevedo                        | 1        | 1.82%   |
| Loja                           | 1        | 1.82%   |
| Latacunga                      | 1        | 1.82%   |
| Las Pinas                      | 1        | 1.82%   |
| Guanujo                        | 1        | 1.82%   |
| Cariamanga                     | 1        | 1.82%   |
| Ambato                         | 1        | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 31     | 24.39%  |
| Seagate             | 16       | 23     | 19.51%  |
| Samsung Electronics | 9        | 10     | 10.98%  |
| Kingston            | 9        | 13     | 10.98%  |
| Toshiba             | 8        | 12     | 9.76%   |
| Hitachi             | 6        | 6      | 7.32%   |
| A-DATA Technology   | 3        | 3      | 3.66%   |
| SPCC                | 2        | 2      | 2.44%   |
| PNY                 | 2        | 2      | 2.44%   |
| Hewlett-Packard     | 2        | 2      | 2.44%   |
| Micro Center        | 1        | 1      | 1.22%   |
| Intel               | 1        | 1      | 1.22%   |
| IMATION             | 1        | 1      | 1.22%   |
| HPE                 | 1        | 1      | 1.22%   |
| Gigabyte Technology | 1        | 1      | 1.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 5        | 5.56%   |
| Kingston SA400S37240G 240GB SSD     | 5        | 5.56%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 4        | 4.44%   |
| Toshiba DT01ACA100 1TB              | 4        | 4.44%   |
| Samsung HD502HJ 500GB               | 3        | 3.33%   |
| Toshiba DT01ACA200 2TB              | 2        | 2.22%   |
| Seagate ST1000DM010-2EP102 1TB      | 2        | 2.22%   |
| Kingston SV300S37A60G 64GB SSD      | 2        | 2.22%   |
| Hitachi HDS721050CLA660 500GB       | 2        | 2.22%   |
| HP SSD S700 500GB                   | 2        | 2.22%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1        | 1.11%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1.11%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 1.11%   |
| WDC WDBNCE5000PNC 500GB SSD         | 1        | 1.11%   |
| WDC WD7500BPVX-22JC3T0 752GB        | 1        | 1.11%   |
| WDC WD5000AVVS-63M8B0 500GB         | 1        | 1.11%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1        | 1.11%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1.11%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1        | 1.11%   |
| WDC WD5000AAKS-00V2B0 500GB         | 1        | 1.11%   |
| WDC WD3200AVVS-63L2B0 320GB         | 1        | 1.11%   |
| WDC WD3200AAJS-60M0A0 320GB         | 1        | 1.11%   |
| WDC WD30EZRS-00J99B0 3TB            | 1        | 1.11%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1.11%   |
| WDC WD1600HLHX-60JJPV1 160GB        | 1        | 1.11%   |
| WDC WD1600AAJS-75M0A0 160GB         | 1        | 1.11%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 1.11%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 1.11%   |
| WDC WD10EURX-63UY4Y0 1TB            | 1        | 1.11%   |
| Toshiba MK7559GSXP 752GB            | 1        | 1.11%   |
| Toshiba MK5055GSX 500GB             | 1        | 1.11%   |
| Toshiba MK3276GSX 320GB             | 1        | 1.11%   |
| SPCC Solid State Disk 512GB         | 1        | 1.11%   |
| SPCC M.2 SSD 256GB                  | 1        | 1.11%   |
| Seagate ST3750640NS 752GB           | 1        | 1.11%   |
| Seagate ST3750330AS 752GB           | 1        | 1.11%   |
| Seagate ST3500312CS 500GB           | 1        | 1.11%   |
| Seagate ST3400833AS 400GB           | 1        | 1.11%   |
| Seagate ST320LT007-9ZV142 320GB     | 1        | 1.11%   |
| Seagate ST31000524AS 1TB            | 1        | 1.11%   |
| Seagate ST31000333AS 1TB            | 1        | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 1.11%   |
| Seagate ST1000DM003-9YN162 1TB      | 1        | 1.11%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1.11%   |
| Samsung SP0802N 80GB                | 1        | 1.11%   |
| Samsung HD503HI 500GB               | 1        | 1.11%   |
| Samsung HD501LJ 500GB               | 1        | 1.11%   |
| Samsung HD161HJ 160GB               | 1        | 1.11%   |
| Samsung HD160JJ 160GB               | 1        | 1.11%   |
| Samsung HD103SJ 1TB                 | 1        | 1.11%   |
| PNY SSD2SC240G1CS1754D117-488 240GB | 1        | 1.11%   |
| PNY CS900 240GB SSD                 | 1        | 1.11%   |
| Micro Center SSD G2 series 64GB     | 1        | 1.11%   |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1.11%   |
| Kingston SNS4151S316GD 16GB SSD     | 1        | 1.11%   |
| Kingston SM2280S3120G 120GB SSD     | 1        | 1.11%   |
| Kingston SA400S37480G 480GB SSD     | 1        | 1.11%   |
| Kingston NVMe SSD Drive 500GB       | 1        | 1.11%   |
| Intel SSDSC2KW240H6 240GB           | 1        | 1.11%   |
| IMATION S3025-032 32GB              | 1        | 1.11%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 26     | 29.82%  |
| Seagate             | 16       | 23     | 28.07%  |
| Samsung Electronics | 9        | 10     | 15.79%  |
| Toshiba             | 8        | 12     | 14.04%  |
| Hitachi             | 6        | 6      | 10.53%  |
| HPE                 | 1        | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 9        | 12     | 37.5%   |
| WDC                 | 4        | 5      | 16.67%  |
| SPCC                | 2        | 2      | 8.33%   |
| PNY                 | 2        | 2      | 8.33%   |
| Hewlett-Packard     | 2        | 2      | 8.33%   |
| A-DATA Technology   | 2        | 2      | 8.33%   |
| Micro Center        | 1        | 1      | 4.17%   |
| Intel               | 1        | 1      | 4.17%   |
| Gigabyte Technology | 1        | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 47       | 78     | 66.2%   |
| SSD     | 21       | 28     | 29.58%  |
| NVMe    | 2        | 2      | 2.82%   |
| Unknown | 1        | 1      | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 55       | 107    | 96.49%  |
| NVMe | 2        | 2      | 3.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 40       | 62     | 56.34%  |
| 0.51-1.0   | 22       | 31     | 30.99%  |
| 1.01-2.0   | 8        | 12     | 11.27%  |
| 2.01-3.0   | 1        | 1      | 1.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 16       | 26.67%  |
| 101-250        | 12       | 20%     |
| 1001-2000      | 10       | 16.67%  |
| 501-1000       | 9        | 15%     |
| 1-20           | 7        | 11.67%  |
| More than 3000 | 3        | 5%      |
| 51-100         | 2        | 3.33%   |
| Unknown        | 1        | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 20       | 32.79%  |
| 21-50          | 10       | 16.39%  |
| 251-500        | 9        | 14.75%  |
| 51-100         | 6        | 9.84%   |
| 1001-2000      | 5        | 8.2%    |
| 101-250        | 4        | 6.56%   |
| 501-1000       | 4        | 6.56%   |
| More than 3000 | 2        | 3.28%   |
| Unknown        | 1        | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2        | 3      | 20%     |
| Hitachi HDS721050CLA660 500GB     | 2        | 2      | 20%     |
| Seagate ST3750330AS 752GB         | 1        | 1      | 10%     |
| Seagate ST31000333AS 1TB          | 1        | 1      | 10%     |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 1      | 10%     |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 10%     |
| Kingston SNS4151S316GD 16GB SSD   | 1        | 1      | 10%     |
| HPE MB0500EAMZD 500GB             | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 50%     |
| Hitachi             | 2        | 2      | 20%     |
| Samsung Electronics | 1        | 1      | 10%     |
| Kingston            | 1        | 1      | 10%     |
| HPE                 | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 55.56%  |
| Hitachi             | 2        | 2      | 22.22%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| HPE                 | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 10     | 88.89%  |
| SSD  | 1        | 1      | 11.11%  |

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
| Detected | 39       | 84     | 65%     |
| Works    | 12       | 14     | 20%     |
| Malfunc  | 9        | 11     | 15%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 40       | 60.61%  |
| AMD                         | 14       | 21.21%  |
| Marvell Technology Group    | 4        | 6.06%   |
| VIA Technologies            | 2        | 3.03%   |
| JMicron Technology          | 2        | 3.03%   |
| ASMedia Technology          | 2        | 3.03%   |
| Kingston Technology Company | 1        | 1.52%   |
| ADATA Technology            | 1        | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 10.23%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 9.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 5.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 4.55%   |
| AMD FCH SATA Controller D                                                               | 4        | 4.55%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.41%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 2.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 2.27%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 2.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.27%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.27%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 1.14%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 1.14%   |
| VIA Serial ATA Controller                                                               | 1        | 1.14%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 1.14%   |
| Marvell Group 88SE914D SATA-600 Controller                                              | 1        | 1.14%   |
| Marvell Group 88SE6145 SATA II PCI-E controller                                         | 1        | 1.14%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 1.14%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 1.14%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.14%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.14%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.14%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 1.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.14%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.14%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 65.57%  |
| IDE  | 17       | 27.87%  |
| RAID | 2        | 3.28%   |
| NVMe | 2        | 3.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 41       | 74.55%  |
| AMD    | 14       | 25.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4440 CPU @ 3.10GHz            | 4        | 7.27%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 5.45%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 3.64%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 2        | 3.64%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 3.64%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 3.64%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 3.64%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 1.82%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.82%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.82%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 1.82%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1.82%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.82%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.82%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.82%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.82%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 1.82%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.82%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.82%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.82%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.82%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.82%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.82%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.82%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.82%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.82%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.82%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1.82%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 1.82%   |
| Intel Celeron J4005 CPU @ 2.00GHz           | 1        | 1.82%   |
| Intel Celeron CPU E3300 @ 2.50GHz           | 1        | 1.82%   |
| Intel Celeron 2955U @ 1.40GHz               | 1        | 1.82%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 1.82%   |
| Intel Atom CPU 330 @ 1.60GHz                | 1        | 1.82%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 1        | 1.82%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 1.82%   |
| AMD Phenom II X6 1055T Processor            | 1        | 1.82%   |
| AMD Phenom II X2 555 Processor              | 1        | 1.82%   |
| AMD E1-2100 APU with Radeon HD Graphics     | 1        | 1.82%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 1        | 1.82%   |
| AMD Athlon II Neo N36L Dual-Core Processor  | 1        | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 14       | 25.45%  |
| AMD Ryzen 5             | 9        | 16.36%  |
| Intel Core i7           | 7        | 12.73%  |
| Intel Core i3           | 5        | 9.09%   |
| Intel Pentium           | 4        | 7.27%   |
| Intel Celeron           | 3        | 5.45%   |
| Intel Core 2 Quad       | 2        | 3.64%   |
| Intel Core 2 Duo        | 2        | 3.64%   |
| Intel Atom              | 2        | 3.64%   |
| AMD E1                  | 2        | 3.64%   |
| Intel Xeon              | 1        | 1.82%   |
| Intel Pentium Dual-Core | 1        | 1.82%   |
| AMD Phenom II X6        | 1        | 1.82%   |
| AMD Phenom II X2        | 1        | 1.82%   |
| AMD Athlon II Neo       | 1        | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 27       | 49.09%  |
| 2      | 19       | 34.55%  |
| 6      | 8        | 14.55%  |
| 8      | 1        | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 55       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 63.64%  |
| 2      | 20       | 36.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 54       | 98.18%  |
| Unknown        | 1        | 1.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 9        | 15.79%  |
| Unknown    | 8        | 14.04%  |
| 0x306a9    | 7        | 12.28%  |
| 0x206a7    | 5        | 8.77%   |
| 0x1067a    | 4        | 7.02%   |
| 0x106e5    | 2        | 3.51%   |
| 0x0a201005 | 2        | 3.51%   |
| 0x0810100b | 2        | 3.51%   |
| 0xa0653    | 1        | 1.75%   |
| 0x906ed    | 1        | 1.75%   |
| 0x906ec    | 1        | 1.75%   |
| 0x706a1    | 1        | 1.75%   |
| 0x6fd      | 1        | 1.75%   |
| 0x40651    | 1        | 1.75%   |
| 0x206c2    | 1        | 1.75%   |
| 0x106ca    | 1        | 1.75%   |
| 0x106c2    | 1        | 1.75%   |
| 0x106a5    | 1        | 1.75%   |
| 0x10676    | 1        | 1.75%   |
| 0x08701021 | 1        | 1.75%   |
| 0x08701013 | 1        | 1.75%   |
| 0x08101016 | 1        | 1.75%   |
| 0x08101004 | 1        | 1.75%   |
| 0x0700010f | 1        | 1.75%   |
| 0x010000c8 | 1        | 1.75%   |
| 0x010000bf | 1        | 1.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 12       | 21.82%  |
| IvyBridge     | 7        | 12.73%  |
| SandyBridge   | 5        | 9.09%   |
| Penryn        | 5        | 9.09%   |
| Zen 2         | 3        | 5.45%   |
| Zen           | 3        | 5.45%   |
| Nehalem       | 3        | 5.45%   |
| K10           | 3        | 5.45%   |
| Zen 3         | 2        | 3.64%   |
| KabyLake      | 2        | 3.64%   |
| CometLake     | 2        | 3.64%   |
| Bonnell       | 2        | 3.64%   |
| Zen+          | 1        | 1.82%   |
| Westmere      | 1        | 1.82%   |
| Jaguar        | 1        | 1.82%   |
| Goldmont plus | 1        | 1.82%   |
| Core          | 1        | 1.82%   |
| Bobcat        | 1        | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 29       | 48.33%  |
| Nvidia           | 15       | 25%     |
| AMD              | 15       | 25%     |
| VIA Technologies | 1        | 1.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 13.33%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 10%     |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 6.67%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 5%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 5%      |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 5%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 3.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.33%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 3.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.33%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 3.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 3.33%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 1.67%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.67%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 1.67%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 1.67%   |
| Nvidia G98 [Quadro NVS 420]                                                 | 1        | 1.67%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.67%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 1.67%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.67%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.67%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.67%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.67%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 1.67%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.67%   |
| AMD Kabini [Radeon HD 8210]                                                 | 1        | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.67%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 1        | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 25       | 44.64%  |
| 1 x Nvidia     | 13       | 23.21%  |
| 1 x AMD        | 13       | 23.21%  |
| Intel + Nvidia | 2        | 3.57%   |
| Intel + AMD    | 2        | 3.57%   |
| 1 x VIA        | 1        | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 44       | 78.57%  |
| Proprietary | 8        | 14.29%  |
| Unknown     | 4        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 55%     |
| 1.01-2.0   | 14       | 23.33%  |
| 0.51-1.0   | 6        | 10%     |
| 0.01-0.5   | 4        | 6.67%   |
| 5.01-6.0   | 2        | 3.33%   |
| 3.01-4.0   | 1        | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 20       | 37.74%  |
| BenQ                | 8        | 15.09%  |
| Hewlett-Packard     | 6        | 11.32%  |
| AOC                 | 6        | 11.32%  |
| Samsung Electronics | 4        | 7.55%   |
| LG Electronics      | 4        | 7.55%   |
| Unknown (XXX)       | 1        | 1.89%   |
| NEC Computers       | 1        | 1.89%   |
| DMT                 | 1        | 1.89%   |
| Dell                | 1        | 1.89%   |
| Acer                | 1        | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 3        | 5.17%   |
| BenQ G2420HDBL BNQ785E 1920x1080 477x268mm 21.5-inch                 | 3        | 5.17%   |
| LG Electronics LCD Monitor LG TV 1360x768                            | 2        | 3.45%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                 | 2        | 3.45%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 2        | 3.45%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 1.72%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 304x228mm 15.0-inch  | 1        | 1.72%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 1.72%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 1        | 1.72%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                 | 1        | 1.72%   |
| NEC Computers LCD1850E NEC65D1 1280x1024 359x287mm 18.1-inch         | 1        | 1.72%   |
| LG Electronics LCD Monitor W2043 3520x1080                           | 1        | 1.72%   |
| LG Electronics LCD Monitor 2D HD LG TV                               | 1        | 1.72%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 1.72%   |
| Hewlett-Packard w1858 HWP2835 1366x768 413x234mm 18.7-inch           | 1        | 1.72%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch            | 1        | 1.72%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch           | 1        | 1.72%   |
| Hewlett-Packard LCD Monitor L1710 2646x1024                          | 1        | 1.72%   |
| Hewlett-Packard E241i HWP3124 1920x1200 518x324mm 24.1-inch          | 1        | 1.72%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch          | 1        | 1.72%   |
| Hewlett-Packard All in One HWP410E 1366x768 410x230mm 18.5-inch      | 1        | 1.72%   |
| Goldstar T1910 GSM4BD8 1280x1024 376x301mm 19.0-inch                 | 1        | 1.72%   |
| Goldstar M237WA GSM5724 1920x1080 509x286mm 23.0-inch                | 1        | 1.72%   |
| Goldstar L177WSB GSM448D 1440x900 370x232mm 17.2-inch                | 1        | 1.72%   |
| Goldstar L1530S GSM3B95 1024x768 304x228mm 15.0-inch                 | 1        | 1.72%   |
| Goldstar IPS WSXGA GSM5B20 1440x900 419x262mm 19.5-inch              | 1        | 1.72%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 1        | 1.72%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 1        | 1.72%   |
| Goldstar E2242 GSM58BE 1920x1080 480x270mm 21.7-inch                 | 1        | 1.72%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 1        | 1.72%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1        | 1.72%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                  | 1        | 1.72%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 1        | 1.72%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 1.72%   |
| DMT CHHWJT* DMT0030 1440x900 708x398mm 32.0-inch                     | 1        | 1.72%   |
| Dell E2311H DELF035 1920x1080 510x287mm 23.0-inch                    | 1        | 1.72%   |
| Dell E2213H DELA090 1920x1080 480x270mm 21.7-inch                    | 1        | 1.72%   |
| BenQ LCD Monitor GL2480 1920x1080                                    | 1        | 1.72%   |
| BenQ LCD Monitor G2420HDBL 1920x1080                                 | 1        | 1.72%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 1        | 1.72%   |
| BenQ GL930A BNQ7870 1366x768 410x230mm 18.5-inch                     | 1        | 1.72%   |
| BenQ G922HDA BNQ783C 1366x768 410x230mm 18.5-inch                    | 1        | 1.72%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                 | 1        | 1.72%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 1        | 1.72%   |
| AOC 2251w AOC2251 1920x1080 477x268mm 21.5-inch                      | 1        | 1.72%   |
| AOC 2080W AOC2080 1440x900 419x262mm 19.5-inch                       | 1        | 1.72%   |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                        | 1        | 1.72%   |
| AOC 197S-1 AOCC944 1280x1024 376x301mm 19.0-inch                     | 1        | 1.72%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                       | 1        | 1.72%   |
| Acer V206HQL ACR032C 1600x900 432x240mm 19.5-inch                    | 1        | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 15       | 28.3%   |
| 1366x768 (WXGA)  | 12       | 22.64%  |
| 1360x768         | 6        | 11.32%  |
| 1600x900 (HD+)   | 5        | 9.43%   |
| 1440x900 (WXGA+) | 5        | 9.43%   |
| 1280x1024 (SXGA) | 3        | 5.66%   |
| 1024x768 (XGA)   | 3        | 5.66%   |
| Unknown          | 2        | 3.77%   |
| 3520x1080        | 1        | 1.89%   |
| 2646x1024        | 1        | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 16       | 29.63%  |
| 19      | 8        | 14.81%  |
| 23      | 7        | 12.96%  |
| Unknown | 7        | 12.96%  |
| 21      | 5        | 9.26%   |
| 20      | 3        | 5.56%   |
| 15      | 3        | 5.56%   |
| 24      | 2        | 3.7%    |
| 54      | 1        | 1.85%   |
| 32      | 1        | 1.85%   |
| 17      | 1        | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 28       | 52.83%  |
| 501-600     | 9        | 16.98%  |
| Unknown     | 7        | 13.21%  |
| 351-400     | 4        | 7.55%   |
| 301-350     | 3        | 5.66%   |
| 701-800     | 1        | 1.89%   |
| 1001-1500   | 1        | 1.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 31       | 62%     |
| Unknown | 7        | 14%     |
| 16/10   | 6        | 12%     |
| 5/4     | 3        | 6%      |
| 4/3     | 3        | 6%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 15       | 27.78%  |
| 151-200        | 13       | 24.07%  |
| 201-250        | 12       | 22.22%  |
| Unknown        | 7        | 12.96%  |
| 101-110        | 3        | 5.56%   |
| More than 1000 | 1        | 1.85%   |
| 351-500        | 1        | 1.85%   |
| 251-300        | 1        | 1.85%   |
| 131-140        | 1        | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 38       | 73.08%  |
| Unknown | 7        | 13.46%  |
| 101-120 | 5        | 9.62%   |
| 1-50    | 2        | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 80.7%   |
| 2     | 8        | 14.04%  |
| 0     | 3        | 5.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 39       | 54.17%  |
| Intel                           | 10       | 13.89%  |
| Qualcomm Atheros                | 7        | 9.72%   |
| Ralink Technology               | 5        | 6.94%   |
| Ralink                          | 2        | 2.78%   |
| D-Link System                   | 2        | 2.78%   |
| Broadcom                        | 2        | 2.78%   |
| VIA Technologies                | 1        | 1.39%   |
| TP-Link                         | 1        | 1.39%   |
| Samsung Electronics             | 1        | 1.39%   |
| Qualcomm Atheros Communications | 1        | 1.39%   |
| Arduino SA                      | 1        | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 31       | 40.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 5        | 6.49%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 3.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 2.6%    |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2        | 2.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 2        | 2.6%    |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 2.6%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                               | 2        | 2.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1        | 1.3%    |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 1.3%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                                   | 1        | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.3%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 1.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 1.3%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.3%    |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 1.3%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.3%    |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 1.3%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 1.3%    |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 1.3%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1        | 1.3%    |
| Intel I211 Gigabit Network Connection                                                         | 1        | 1.3%    |
| Intel Ethernet Connection I217-V                                                              | 1        | 1.3%    |
| Intel Ethernet Connection I217-LM                                                             | 1        | 1.3%    |
| Intel Ethernet Connection (7) I219-V                                                          | 1        | 1.3%    |
| Intel Ethernet Connection (11) I219-V                                                         | 1        | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 1        | 1.3%    |
| Intel 82578DC Gigabit Network Connection                                                      | 1        | 1.3%    |
| Intel 82566DC-2 Gigabit Network Connection                                                    | 1        | 1.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                              | 1        | 1.3%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                                              | 1        | 1.3%    |
| Arduino SA Mega 2560 R3 (CDC ACM)                                                             | 1        | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 7        | 38.89%  |
| Ralink Technology               | 5        | 27.78%  |
| Ralink                          | 2        | 11.11%  |
| Qualcomm Atheros                | 2        | 11.11%  |
| TP-Link                         | 1        | 5.56%   |
| Qualcomm Atheros Communications | 1        | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 16.67%  |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 11.11%  |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2        | 11.11%  |
| TP-Link 802.11ac WLAN Adapter                                                                 | 1        | 5.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 5.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 5.56%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 5.56%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 5.56%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 5.56%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 5.56%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 5.56%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 5.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 5.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 37       | 63.79%  |
| Intel                 | 10       | 17.24%  |
| Qualcomm Atheros      | 5        | 8.62%   |
| D-Link System         | 2        | 3.45%   |
| Broadcom              | 2        | 3.45%   |
| VIA Technologies      | 1        | 1.72%   |
| Samsung Electronics   | 1        | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31       | 53.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 8.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 3.45%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 3.45%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 3.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.72%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.72%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.72%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.72%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.72%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.72%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.72%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 55       | 76.39%  |
| WiFi     | 16       | 22.22%  |
| Modem    | 1        | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 80%     |
| WiFi     | 11       | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 46       | 83.64%  |
| 2     | 8        | 14.55%  |
| 3     | 1        | 1.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 85.71%  |
| Yes  | 8        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 6        | 75%     |
| IMC Networks            | 1        | 12.5%   |
| D-Link System           | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 75%     |
| IMC Networks Bluetooth Device                       | 1        | 12.5%   |
| D-Link System DBT-122 Bluetooth                     | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 41       | 55.41%  |
| AMD              | 19       | 25.68%  |
| Nvidia           | 13       | 17.57%  |
| VIA Technologies | 1        | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 10.99%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 9.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 8.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 6.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 5.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 4.4%    |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 4.4%    |
| Nvidia High Definition Audio Controller                                    | 3        | 3.3%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 3.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.2%    |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 2.2%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 2.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 2.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 2.2%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.2%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.2%    |
| AMD FCH Azalia Controller                                                  | 2        | 2.2%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.1%    |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 1.1%    |
| Nvidia GF100 High Definition Audio Controller                              | 1        | 1.1%    |
| Intel USB PnP Sound Device                                                 | 1        | 1.1%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.1%    |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.1%    |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.1%    |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.1%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.1%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 1.1%    |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.1%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 40.91%  |
| Unknown             | 6        | 27.27%  |
| Corsair             | 2        | 9.09%   |
| Samsung Electronics | 1        | 4.55%   |
| PNY                 | 1        | 4.55%   |
| Micron Technology   | 1        | 4.55%   |
| Crucial             | 1        | 4.55%   |
| A-DATA Technology   | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 3.57%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 3.57%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 3.57%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s            | 1        | 3.57%   |
| Unknown RAM Module 2048MB DIMM DDR2                       | 1        | 3.57%   |
| Unknown RAM Module 1GB DIMM DDR2                          | 1        | 3.57%   |
| Unknown RAM Module 1024MB DIMM 1333MT/s                   | 1        | 3.57%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s       | 1        | 3.57%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 3.57%   |
| PNY RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1        | 3.57%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s               | 1        | 3.57%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s   | 1        | 3.57%   |
| Kingston RAM KHX3000C16D4/16GX 16384MB DIMM DDR4 2400MT/s | 1        | 3.57%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 1        | 3.57%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 1        | 3.57%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 2933MT/s      | 1        | 3.57%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s       | 1        | 3.57%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 3.57%   |
| Kingston RAM 99U5474-016.A00LF 4096MB DIMM DDR3 1333MT/s  | 1        | 3.57%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 3.57%   |
| Kingston RAM 99U5471-038.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 3.57%   |
| Kingston RAM 99U5471-030.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 3.57%   |
| Kingston RAM 9905471-017.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 3.57%   |
| Kingston RAM 9905402-171.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 3.57%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 3.57%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 1        | 3.57%   |
| A-DATA RAM Module 8GB DIMM DDR3 1333MT/s                  | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 9        | 47.37%  |
| DDR4    | 5        | 26.32%  |
| DDR2    | 3        | 15.79%  |
| SDRAM   | 1        | 5.26%   |
| Unknown | 1        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 18       | 94.74%  |
| SODIMM | 1        | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 30.43%  |
| 4096  | 6        | 26.09%  |
| 2048  | 6        | 26.09%  |
| 16384 | 2        | 8.7%    |
| 1024  | 2        | 8.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 7        | 30.43%  |
| 1600    | 3        | 13.04%  |
| Unknown | 3        | 13.04%  |
| 3466    | 2        | 8.7%    |
| 3600    | 1        | 4.35%   |
| 3533    | 1        | 4.35%   |
| 3200    | 1        | 4.35%   |
| 2933    | 1        | 4.35%   |
| 2400    | 1        | 4.35%   |
| 2133    | 1        | 4.35%   |
| 1866    | 1        | 4.35%   |
| 800     | 1        | 4.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 50%     |
| Hewlett-Packard     | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1        | 50%     |
| HP Deskjet 2050 J510               | 1        | 50%     |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Microdia                    | 3        | 17.65%  |
| Pixart Imaging              | 2        | 11.76%  |
| Logitech                    | 2        | 11.76%  |
| KYE Systems (Mouse Systems) | 2        | 11.76%  |
| Generalplus Technology      | 2        | 11.76%  |
| Jieli Technology            | 1        | 5.88%   |
| IMC Networks                | 1        | 5.88%   |
| Genesys Logic               | 1        | 5.88%   |
| GEMBIRD                     | 1        | 5.88%   |
| Chicony Electronics         | 1        | 5.88%   |
| Arkmicro Technologies       | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Microdia Camera                            | 2        | 11.76%  |
| Logitech Webcam C270                       | 2        | 11.76%  |
| Pixart Imaging Webcam Genius iLook 300     | 1        | 5.88%   |
| Pixart Imaging Multimedia audio controller | 1        | 5.88%   |
| Microdia Webcam Vitade AF                  | 1        | 5.88%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 5.88%   |
| KYE Systems (Mouse Systems) FaceCam 310    | 1        | 5.88%   |
| Jieli USB PHY 2.0                          | 1        | 5.88%   |
| IMC Networks XHC Camera                    | 1        | 5.88%   |
| Genesys Logic USB2.0 UVC PC Camera         | 1        | 5.88%   |
| Generalplus CAMERA - UVC                   | 1        | 5.88%   |
| Generalplus 808 Camera                     | 1        | 5.88%   |
| GEMBIRD USB2.0 PC CAMERA                   | 1        | 5.88%   |
| Chicony HP High Definition 1MP Webcam      | 1        | 5.88%   |
| Arkmicro USB2.0 PC CAMERA                  | 1        | 5.88%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 49       | 85.96%  |
| 1     | 8        | 14.04%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 75%     |
| Net/wireless             | 1        | 12.5%   |
| Communication controller | 1        | 12.5%   |

