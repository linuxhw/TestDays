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

Total: 104

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | M68MT-S2P                   | [93adad7445](https://linux-hardware.org/?probe=93adad7445) | Dec 30, 2022 |
| Dell          | 00V62H A01                  | [296edfbde5](https://linux-hardware.org/?probe=296edfbde5) | Dec 22, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| Gigabyte      | H410M H                     | [71a25274d7](https://linux-hardware.org/?probe=71a25274d7) | Oct 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [32d74cab14](https://linux-hardware.org/?probe=32d74cab14) | Oct 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [abbdbe7e68](https://linux-hardware.org/?probe=abbdbe7e68) | Oct 10, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [ea7b836323](https://linux-hardware.org/?probe=ea7b836323) | Oct 08, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| ASUSTek       | PRIME A520M-K               | [6b528465e2](https://linux-hardware.org/?probe=6b528465e2) | Sep 20, 2022 |
| HP            | 8768 A                      | [dd63bfb225](https://linux-hardware.org/?probe=dd63bfb225) | Sep 16, 2022 |
| ASUSTek       | Z170-P                      | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | H97-Gaming 3                | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Biostar       | H61MGV3                     | [bb42e29bbb](https://linux-hardware.org/?probe=bb42e29bbb) | Jun 28, 2022 |
| ASRock        | B450 Gaming K4              | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ff0b730eed](https://linux-hardware.org/?probe=ff0b730eed) | Jun 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [edb1f4bda1](https://linux-hardware.org/?probe=edb1f4bda1) | Jun 14, 2022 |
| ASUSTek       | H81M-A                      | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| Intel         | DH61BF AAG81311-101         | [9c54929196](https://linux-hardware.org/?probe=9c54929196) | May 11, 2022 |
| Gigabyte      | X58A-UD3R                   | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Gigabyte      | H97-Gaming 3                | [150f5a4bd0](https://linux-hardware.org/?probe=150f5a4bd0) | Apr 30, 2022 |
| Biostar       | G41D3C                      | [a6db6a2cdf](https://linux-hardware.org/?probe=a6db6a2cdf) | Apr 27, 2022 |
| Biostar       | G41D3C                      | [ac5c2d8b54](https://linux-hardware.org/?probe=ac5c2d8b54) | Apr 23, 2022 |
| Biostar       | G41D3C                      | [6fdf919c55](https://linux-hardware.org/?probe=6fdf919c55) | Apr 23, 2022 |
| ASUSTek       | H81M-A                      | [01c63fa622](https://linux-hardware.org/?probe=01c63fa622) | Apr 22, 2022 |
| Foxconn       | Cinema Series FAB           | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | H81M-A                      | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Gigabyte      | H97-Gaming 3                | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| Google        | Panther                     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| ASUSTek       | H81M-A                      | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| TPV-INVENT... | 2AF2 A01                    | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| Biostar       | G31-M7 TE                   | [f08be29479](https://linux-hardware.org/?probe=f08be29479) | Mar 12, 2022 |
| Intel         | H81                         | [a62759e3c8](https://linux-hardware.org/?probe=a62759e3c8) | Feb 27, 2022 |
| Intel         | H81                         | [d1f816774f](https://linux-hardware.org/?probe=d1f816774f) | Feb 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [14f2fcb8be](https://linux-hardware.org/?probe=14f2fcb8be) | Feb 16, 2022 |
| Gigabyte      | H97-Gaming 3                | [b5ee6e292d](https://linux-hardware.org/?probe=b5ee6e292d) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [4cabeb69e3](https://linux-hardware.org/?probe=4cabeb69e3) | Feb 04, 2022 |
| Biostar       | H61MGV3                     | [2f9b9ff8ee](https://linux-hardware.org/?probe=2f9b9ff8ee) | Jan 13, 2022 |
| Biostar       | H61MGV3                     | [332b6e1f8a](https://linux-hardware.org/?probe=332b6e1f8a) | Jan 12, 2022 |
| Biostar       | A68N-2100                   | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Intel         | DG41RQ AAE54511-205         | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205         | [d84eb83569](https://linux-hardware.org/?probe=d84eb83569) | Dec 08, 2021 |
| ASUSTek       | H81M-A                      | [c7762271da](https://linux-hardware.org/?probe=c7762271da) | Nov 18, 2021 |
| Gigabyte      | H310M H x.x                 | [419e0c7eb2](https://linux-hardware.org/?probe=419e0c7eb2) | Oct 21, 2021 |
| ASUSTek       | PRIME H410M-E               | [b5d6c0ae9c](https://linux-hardware.org/?probe=b5d6c0ae9c) | Oct 20, 2021 |
| Gigabyte      | H310M H x.x                 | [3fe7cdd0f9](https://linux-hardware.org/?probe=3fe7cdd0f9) | Oct 14, 2021 |
| ASRock        | B450 Gaming K4              | [0de7c95a46](https://linux-hardware.org/?probe=0de7c95a46) | Oct 12, 2021 |
| Foxconn       | H61MXL-K                    | [e776e3f647](https://linux-hardware.org/?probe=e776e3f647) | Sep 08, 2021 |
| ASUSTek       | P7P55D-E                    | [5e208c3927](https://linux-hardware.org/?probe=5e208c3927) | Sep 02, 2021 |
| ASUSTek       | PRIME H410M-E               | [f667f32489](https://linux-hardware.org/?probe=f667f32489) | Aug 31, 2021 |
| MSI           | Z390-A PRO                  | [72cddcc75c](https://linux-hardware.org/?probe=72cddcc75c) | Aug 29, 2021 |
| Gigabyte      | H410M H V2                  | [84faf4af12](https://linux-hardware.org/?probe=84faf4af12) | Aug 22, 2021 |
| Gigabyte      | H410M H V2                  | [5e4047a59c](https://linux-hardware.org/?probe=5e4047a59c) | Aug 22, 2021 |
| Gigabyte      | H97M-DS3P                   | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | PRIME A520M-K               | [33c83a65d8](https://linux-hardware.org/?probe=33c83a65d8) | Jul 24, 2021 |
| Biostar       | A68N-2100                   | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Pegatron      | 2ACC                        | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| ASUSTek       | PRIME A520M-K               | [0f90b91804](https://linux-hardware.org/?probe=0f90b91804) | Jun 25, 2021 |
| ASUSTek       | H81M-K                      | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | PRIME J4005I-C              | [d8be675a5d](https://linux-hardware.org/?probe=d8be675a5d) | May 19, 2021 |
| ASRock        | B550M-HDV                   | [aaee9d166a](https://linux-hardware.org/?probe=aaee9d166a) | Apr 26, 2021 |
| Gigabyte      | H81M-H                      | [e34aa83281](https://linux-hardware.org/?probe=e34aa83281) | Apr 16, 2021 |
| Intel         | DB75EN AAG39650-302         | [02f80c53ea](https://linux-hardware.org/?probe=02f80c53ea) | Mar 05, 2021 |
| ASUSTek       | PRIME A520M-K               | [d5ef689e13](https://linux-hardware.org/?probe=d5ef689e13) | Feb 27, 2021 |
| Shuttle       | SFM27 V20                   | [14a841b718](https://linux-hardware.org/?probe=14a841b718) | Feb 21, 2021 |
| Biostar       | G31-M7 TE                   | [c30b6ae115](https://linux-hardware.org/?probe=c30b6ae115) | Jan 24, 2021 |
| Intel         | DG33BU AAD79951-407         | [c0e2f63e04](https://linux-hardware.org/?probe=c0e2f63e04) | Dec 20, 2020 |
| Intel         | DP55KG AAE47218-404         | [5604be0f67](https://linux-hardware.org/?probe=5604be0f67) | Nov 25, 2020 |
| ASUSTek       | PRIME A320M-A               | [cffed87fd7](https://linux-hardware.org/?probe=cffed87fd7) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | [1505bb0505](https://linux-hardware.org/?probe=1505bb0505) | Nov 21, 2020 |
| MSI           | B75A-G43                    | [fd4f003fa9](https://linux-hardware.org/?probe=fd4f003fa9) | Sep 28, 2020 |
| MSI           | B75A-G43                    | [148c1711fe](https://linux-hardware.org/?probe=148c1711fe) | Sep 28, 2020 |
| ECS           | H61H2-MV                    | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| HP            | 1497                        | [02645aa87a](https://linux-hardware.org/?probe=02645aa87a) | Sep 15, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | [cb7ecd71b1](https://linux-hardware.org/?probe=cb7ecd71b1) | Sep 07, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | [917f5d9bd0](https://linux-hardware.org/?probe=917f5d9bd0) | Sep 07, 2020 |
| Biostar       | A68N-2100                   | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| Gigabyte      | H81M-H                      | [ca4fa8777d](https://linux-hardware.org/?probe=ca4fa8777d) | Aug 10, 2020 |
| HP            | ProLiant MicroServer        | [87be3f63a0](https://linux-hardware.org/?probe=87be3f63a0) | Jul 09, 2020 |
| HP            | ProLiant MicroServer        | [82f2a3732c](https://linux-hardware.org/?probe=82f2a3732c) | Jul 09, 2020 |
| Biostar       | A68N-2100                   | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| ASUSTek       | H81M-K                      | [0a4363a1ba](https://linux-hardware.org/?probe=0a4363a1ba) | Jun 28, 2020 |
| Biostar       | G31-M7 TE                   | [56a67b5ddc](https://linux-hardware.org/?probe=56a67b5ddc) | Jun 22, 2020 |
| ASRock        | H61M-VS                     | [87788ef1c8](https://linux-hardware.org/?probe=87788ef1c8) | Jun 11, 2020 |
| Biostar       | H81MLV3                     | [d912bc8bdc](https://linux-hardware.org/?probe=d912bc8bdc) | May 12, 2020 |
| Biostar       | G31-M7 TE                   | [21283d29b3](https://linux-hardware.org/?probe=21283d29b3) | May 10, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | [f43cc5765b](https://linux-hardware.org/?probe=f43cc5765b) | Apr 25, 2020 |
| Intel         | DH61WW AAG23116-203         | [ca1baf42c2](https://linux-hardware.org/?probe=ca1baf42c2) | Dec 18, 2019 |
| Intel         | DH61WW AAG23116-203         | [b3270b7077](https://linux-hardware.org/?probe=b3270b7077) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | [5097027e46](https://linux-hardware.org/?probe=5097027e46) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | [3fc475bd40](https://linux-hardware.org/?probe=3fc475bd40) | Dec 05, 2019 |
| HP            | 18E7                        | [2d2bb51f61](https://linux-hardware.org/?probe=2d2bb51f61) | Aug 27, 2019 |
| ASUSTek       | PRIME A320M-A               | [29c5995612](https://linux-hardware.org/?probe=29c5995612) | Jul 29, 2019 |
| Dell          | 0CRH6C A02                  | [9bfbd0c2f6](https://linux-hardware.org/?probe=9bfbd0c2f6) | May 16, 2019 |
| Intel         | DZ68DB AAG27985-101         | [ebe6dcff50](https://linux-hardware.org/?probe=ebe6dcff50) | May 05, 2019 |
| Intel         | DZ68DB AAG27985-101         | [2d6ea0b597](https://linux-hardware.org/?probe=2d6ea0b597) | May 05, 2019 |
| Cartimex      | H61H2-MV                    | [aa36029d7f](https://linux-hardware.org/?probe=aa36029d7f) | Apr 09, 2019 |
| ASUSTek       | PRIME A320M-A               | [d857fd97fd](https://linux-hardware.org/?probe=d857fd97fd) | Mar 11, 2019 |
| ASUSTek       | PRIME A320M-A               | [4b50a9d6a2](https://linux-hardware.org/?probe=4b50a9d6a2) | Jan 08, 2019 |
| ASUSTek       | PRIME A320M-A               | [91f58fec26](https://linux-hardware.org/?probe=91f58fec26) | Jan 08, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 15       | 21.43%  |
| Ubuntu 18.04       | 10       | 14.29%  |
| Ubuntu 22.04       | 3        | 4.29%   |
| OpenMandriva 4.3   | 3        | 4.29%   |
| OpenMandriva 4.2   | 3        | 4.29%   |
| Debian 11          | 3        | 4.29%   |
| Zorin 16           | 2        | 2.86%   |
| Linux Mint 19.1    | 2        | 2.86%   |
| Fedora 36          | 2        | 2.86%   |
| Fedora 34          | 2        | 2.86%   |
| Xubuntu 18.04      | 1        | 1.43%   |
| Ubuntu 21.10       | 1        | 1.43%   |
| Ubuntu 16.04       | 1        | 1.43%   |
| Pop!_OS 21.04      | 1        | 1.43%   |
| Pop!_OS 20.04      | 1        | 1.43%   |
| Peppermint 10      | 1        | 1.43%   |
| openSUSE Leap-15.2 | 1        | 1.43%   |
| Nobara 36          | 1        | 1.43%   |
| Manjaro 21.3.7     | 1        | 1.43%   |
| Manjaro 21.2.5     | 1        | 1.43%   |
| Manjaro            | 1        | 1.43%   |
| Lubuntu 16.04      | 1        | 1.43%   |
| LMDE 4             | 1        | 1.43%   |
| Linux Mint 21      | 1        | 1.43%   |
| Linux Mint 20.3    | 1        | 1.43%   |
| Linux Mint 20.1    | 1        | 1.43%   |
| Kubuntu 22.04      | 1        | 1.43%   |
| KDE neon 22.04     | 1        | 1.43%   |
| Kali 2022.2        | 1        | 1.43%   |
| Fedora 35          | 1        | 1.43%   |
| Elementary 5.1.7   | 1        | 1.43%   |
| Debian 10          | 1        | 1.43%   |
| Clear Linux 35810  | 1        | 1.43%   |
| CentOS 7           | 1        | 1.43%   |
| Arch               | 1        | 1.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 30       | 42.86%  |
| OpenMandriva | 6        | 8.57%   |
| Linux Mint   | 5        | 7.14%   |
| Fedora       | 5        | 7.14%   |
| Debian       | 4        | 5.71%   |
| Manjaro      | 3        | 4.29%   |
| Zorin        | 2        | 2.86%   |
| Pop!_OS      | 2        | 2.86%   |
| Xubuntu      | 1        | 1.43%   |
| Peppermint   | 1        | 1.43%   |
| openSUSE     | 1        | 1.43%   |
| Nobara       | 1        | 1.43%   |
| Lubuntu      | 1        | 1.43%   |
| LMDE         | 1        | 1.43%   |
| Kubuntu      | 1        | 1.43%   |
| KDE neon     | 1        | 1.43%   |
| Kali         | 1        | 1.43%   |
| Elementary   | 1        | 1.43%   |
| Clear Linux  | 1        | 1.43%   |
| CentOS       | 1        | 1.43%   |
| Arch         | 1        | 1.43%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003      | 3        | 3.95%   |
| 5.10.14-desktop-1omv4002     | 3        | 3.95%   |
| 5.8.0-50-generic             | 2        | 2.63%   |
| 5.4.0-73-generic             | 2        | 2.63%   |
| 5.4.0-54-generic             | 2        | 2.63%   |
| 5.4.0-29-generic             | 2        | 2.63%   |
| 5.15.0-56-generic            | 2        | 2.63%   |
| 4.15.0-20-generic            | 2        | 2.63%   |
| 5.8.0-63-generic             | 1        | 1.32%   |
| 5.8.0-41-generic             | 1        | 1.32%   |
| 5.8.0-40-generic             | 1        | 1.32%   |
| 5.7.0-0.bpo.2-amd64          | 1        | 1.32%   |
| 5.4.0-91-generic             | 1        | 1.32%   |
| 5.4.0-81-generic             | 1        | 1.32%   |
| 5.4.0-7634-generic           | 1        | 1.32%   |
| 5.4.0-45-generic             | 1        | 1.32%   |
| 5.4.0-42-generic             | 1        | 1.32%   |
| 5.4.0-37-generic             | 1        | 1.32%   |
| 5.4.0-126-generic            | 1        | 1.32%   |
| 5.3.18-lp152.87-default      | 1        | 1.32%   |
| 5.3.0-46-generic             | 1        | 1.32%   |
| 5.19.9-201.fsync.fc36.x86_64 | 1        | 1.32%   |
| 5.18.5-200.fc36.x86_64       | 1        | 1.32%   |
| 5.17.9-602.inttf.fc36.x86_64 | 1        | 1.32%   |
| 5.17.5-76051705-generic      | 1        | 1.32%   |
| 5.17.4-200.fc35.x86_64       | 1        | 1.32%   |
| 5.17.0-kali3-amd64           | 1        | 1.32%   |
| 5.16.7-1122.native           | 1        | 1.32%   |
| 5.16.0-arch1-1               | 1        | 1.32%   |
| 5.15.60-1-MANJARO            | 1        | 1.32%   |
| 5.15.28-1-MANJARO            | 1        | 1.32%   |
| 5.15.0-50-generic            | 1        | 1.32%   |
| 5.15.0-47-generic            | 1        | 1.32%   |
| 5.15.0-46-lowlatency         | 1        | 1.32%   |
| 5.15.0-41-generic            | 1        | 1.32%   |
| 5.15.0-30-generic            | 1        | 1.32%   |
| 5.13.4-200.fc34.x86_64       | 1        | 1.32%   |
| 5.13.0-39-generic            | 1        | 1.32%   |
| 5.13.0-35-generic            | 1        | 1.32%   |
| 5.13.0-30-generic            | 1        | 1.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 12       | 16.67%  |
| 4.15.0  | 9        | 12.5%   |
| 5.15.0  | 7        | 9.72%   |
| 5.8.0   | 5        | 6.94%   |
| 5.16.7  | 4        | 5.56%   |
| 5.11.0  | 4        | 5.56%   |
| 5.13.0  | 3        | 4.17%   |
| 5.10.14 | 3        | 4.17%   |
| 5.10.0  | 3        | 4.17%   |
| 5.0.0   | 2        | 2.78%   |
| 4.19.0  | 2        | 2.78%   |
| 5.7.0   | 1        | 1.39%   |
| 5.3.18  | 1        | 1.39%   |
| 5.3.0   | 1        | 1.39%   |
| 5.19.9  | 1        | 1.39%   |
| 5.18.5  | 1        | 1.39%   |
| 5.17.9  | 1        | 1.39%   |
| 5.17.5  | 1        | 1.39%   |
| 5.17.4  | 1        | 1.39%   |
| 5.17.0  | 1        | 1.39%   |
| 5.16.0  | 1        | 1.39%   |
| 5.15.60 | 1        | 1.39%   |
| 5.15.28 | 1        | 1.39%   |
| 5.13.4  | 1        | 1.39%   |
| 5.11.16 | 1        | 1.39%   |
| 5.10.59 | 1        | 1.39%   |
| 5.0.10  | 1        | 1.39%   |
| 4.18.0  | 1        | 1.39%   |
| 3.10.0  | 1        | 1.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 16.67%  |
| 5.15    | 9        | 12.5%   |
| 4.15    | 9        | 12.5%   |
| 5.10    | 7        | 9.72%   |
| 5.8     | 5        | 6.94%   |
| 5.16    | 5        | 6.94%   |
| 5.11    | 5        | 6.94%   |
| 5.17    | 4        | 5.56%   |
| 5.13    | 4        | 5.56%   |
| 5.0     | 3        | 4.17%   |
| 5.3     | 2        | 2.78%   |
| 4.19    | 2        | 2.78%   |
| 5.7     | 1        | 1.39%   |
| 5.19    | 1        | 1.39%   |
| 5.18    | 1        | 1.39%   |
| 4.18    | 1        | 1.39%   |
| 3.10    | 1        | 1.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 64       | 96.97%  |
| i686   | 2        | 3.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 32       | 47.06%  |
| KDE5       | 12       | 17.65%  |
| Unknown    | 9        | 13.24%  |
| X-Cinnamon | 6        | 8.82%   |
| XFCE       | 3        | 4.41%   |
| MATE       | 2        | 2.94%   |
| LXDE       | 2        | 2.94%   |
| qtile      | 1        | 1.47%   |
| Pantheon   | 1        | 1.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 52       | 76.47%  |
| Wayland | 12       | 17.65%  |
| Unknown | 3        | 4.41%   |
| Tty     | 1        | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 52.78%  |
| SDDM    | 11       | 15.28%  |
| GDM3    | 10       | 13.89%  |
| GDM     | 8        | 11.11%  |
| LightDM | 3        | 4.17%   |
| TDM     | 2        | 2.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_EC   | 34       | 50%     |
| en_US   | 19       | 27.94%  |
| Unknown | 6        | 8.82%   |
| es_ES   | 5        | 7.35%   |
| ru_RU   | 1        | 1.47%   |
| es_PE   | 1        | 1.47%   |
| en_AG   | 1        | 1.47%   |
| C       | 1        | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 44       | 66.67%  |
| EFI  | 22       | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 51       | 75%     |
| Overlay | 7        | 10.29%  |
| Btrfs   | 4        | 5.88%   |
| Xfs     | 3        | 4.41%   |
| Unknown | 3        | 4.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 45       | 67.16%  |
| GPT     | 13       | 19.4%   |
| MBR     | 9        | 13.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 84.06%  |
| Yes       | 11       | 15.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 64.18%  |
| Yes       | 24       | 35.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 19       | 28.79%  |
| Gigabyte Technology | 11       | 16.67%  |
| Intel               | 8        | 12.12%  |
| Biostar             | 8        | 12.12%  |
| Hewlett-Packard     | 4        | 6.06%   |
| Foxconn             | 3        | 4.55%   |
| ASRock              | 3        | 4.55%   |
| MSI                 | 2        | 3.03%   |
| Dell                | 2        | 3.03%   |
| TPV-INVENTA         | 1        | 1.52%   |
| Shuttle             | 1        | 1.52%   |
| Pegatron            | 1        | 1.52%   |
| Google              | 1        | 1.52%   |
| ECS                 | 1        | 1.52%   |
| Cartimex            | 1        | 1.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 4        | 6.06%   |
| ASUS PRIME A320M-A               | 3        | 4.55%   |
| Gigabyte H81M-H                  | 2        | 3.03%   |
| Biostar H61MGV3                  | 2        | 3.03%   |
| Biostar G31-M7 TE                | 2        | 3.03%   |
| TPV-INVENTA 2AF2 A01             | 1        | 1.52%   |
| Shuttle SFM27                    | 1        | 1.52%   |
| Pegatron CQ1506LA                | 1        | 1.52%   |
| MSI MS-7B98                      | 1        | 1.52%   |
| MSI MS-7758                      | 1        | 1.52%   |
| Intel H81                        | 1        | 1.52%   |
| Intel DZ68DB AAG27985-101        | 1        | 1.52%   |
| Intel DP55KG AAE47218-404        | 1        | 1.52%   |
| Intel DH61WW AAG23116-203        | 1        | 1.52%   |
| Intel DH61BF AAG81311-101        | 1        | 1.52%   |
| Intel DG41RQ AAE54511-205        | 1        | 1.52%   |
| Intel DG33BU AAD79951-407        | 1        | 1.52%   |
| Intel DB75EN AAG39650-302        | 1        | 1.52%   |
| HP Slim Desktop S01-pF1xxx       | 1        | 1.52%   |
| HP ProLiant MicroServer          | 1        | 1.52%   |
| HP ProDesk 600 G1 SFF            | 1        | 1.52%   |
| HP Compaq 6200 Pro MT PC         | 1        | 1.52%   |
| Google Panther                   | 1        | 1.52%   |
| Gigabyte X58A-UD3R               | 1        | 1.52%   |
| Gigabyte M68MT-S2P               | 1        | 1.52%   |
| Gigabyte H97M-DS3P               | 1        | 1.52%   |
| Gigabyte H97-Gaming 3            | 1        | 1.52%   |
| Gigabyte H410M H V2              | 1        | 1.52%   |
| Gigabyte H410M H                 | 1        | 1.52%   |
| Gigabyte H310M H 2.0             | 1        | 1.52%   |
| Gigabyte B550 AORUS ELITE V2     | 1        | 1.52%   |
| Gigabyte B450M DS3H              | 1        | 1.52%   |
| Foxconn H61MXL-K                 | 1        | 1.52%   |
| Foxconn H61MXE/-S/-V/-K          | 1        | 1.52%   |
| Foxconn Cinema Series            | 1        | 1.52%   |
| ECS H61H2-MV                     | 1        | 1.52%   |
| Dell Precision WorkStation T5500 | 1        | 1.52%   |
| Dell OptiPlex 9020               | 1        | 1.52%   |
| Cartimex H61H2-MV                | 1        | 1.52%   |
| Biostar P4M90-M7                 | 1        | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 9        | 13.64%  |
| ASUS All            | 4        | 6.06%   |
| Gigabyte H81M-H     | 2        | 3.03%   |
| Gigabyte H410M      | 2        | 3.03%   |
| Biostar H61MGV3     | 2        | 3.03%   |
| Biostar G31-M7      | 2        | 3.03%   |
| TPV-INVENTA 2AF2    | 1        | 1.52%   |
| Shuttle SFM27       | 1        | 1.52%   |
| Pegatron CQ1506LA   | 1        | 1.52%   |
| MSI MS-7B98         | 1        | 1.52%   |
| MSI MS-7758         | 1        | 1.52%   |
| Intel H81           | 1        | 1.52%   |
| Intel DZ68DB        | 1        | 1.52%   |
| Intel DP55KG        | 1        | 1.52%   |
| Intel DH61WW        | 1        | 1.52%   |
| Intel DH61BF        | 1        | 1.52%   |
| Intel DG41RQ        | 1        | 1.52%   |
| Intel DG33BU        | 1        | 1.52%   |
| Intel DB75EN        | 1        | 1.52%   |
| HP Slim             | 1        | 1.52%   |
| HP ProLiant         | 1        | 1.52%   |
| HP ProDesk          | 1        | 1.52%   |
| HP Compaq           | 1        | 1.52%   |
| Google Panther      | 1        | 1.52%   |
| Gigabyte X58A-UD3R  | 1        | 1.52%   |
| Gigabyte M68MT-S2P  | 1        | 1.52%   |
| Gigabyte H97M-DS3P  | 1        | 1.52%   |
| Gigabyte H97-Gaming | 1        | 1.52%   |
| Gigabyte H310M      | 1        | 1.52%   |
| Gigabyte B550       | 1        | 1.52%   |
| Gigabyte B450M      | 1        | 1.52%   |
| Foxconn H61MXL-K    | 1        | 1.52%   |
| Foxconn H61MXE      | 1        | 1.52%   |
| Foxconn Cinema      | 1        | 1.52%   |
| ECS H61H2-MV        | 1        | 1.52%   |
| Dell Precision      | 1        | 1.52%   |
| Dell OptiPlex       | 1        | 1.52%   |
| Cartimex H61H2-MV   | 1        | 1.52%   |
| Biostar P4M90-M7    | 1        | 1.52%   |
| Biostar H81MLV3     | 1        | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 10       | 15.15%  |
| 2012 | 7        | 10.61%  |
| 2011 | 7        | 10.61%  |
| 2020 | 6        | 9.09%   |
| 2018 | 6        | 9.09%   |
| 2009 | 5        | 7.58%   |
| 2017 | 4        | 6.06%   |
| 2014 | 4        | 6.06%   |
| 2021 | 3        | 4.55%   |
| 2019 | 3        | 4.55%   |
| 2010 | 3        | 4.55%   |
| 2008 | 3        | 4.55%   |
| 2015 | 2        | 3.03%   |
| 2007 | 2        | 3.03%   |
| 2016 | 1        | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 66       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 65       | 97.01%  |
| Enabled  | 2        | 2.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 98.48%  |
| Yes  | 1        | 1.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 19       | 27.54%  |
| 4.01-8.0   | 15       | 21.74%  |
| 3.01-4.0   | 12       | 17.39%  |
| 16.01-24.0 | 10       | 14.49%  |
| 32.01-64.0 | 5        | 7.25%   |
| 1.01-2.0   | 5        | 7.25%   |
| 24.01-32.0 | 3        | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 25       | 32.05%  |
| 2.01-3.0  | 22       | 28.21%  |
| 4.01-8.0  | 12       | 15.38%  |
| 3.01-4.0  | 12       | 15.38%  |
| 0.51-1.0  | 3        | 3.85%   |
| 8.01-16.0 | 2        | 2.56%   |
| 0.01-0.5  | 2        | 2.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 40       | 57.97%  |
| 2      | 17       | 24.64%  |
| 3      | 11       | 15.94%  |
| 5      | 1        | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 36       | 52.94%  |
| No        | 32       | 47.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 66       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 64.18%  |
| Yes       | 24       | 35.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 81.82%  |
| Yes       | 12       | 18.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ecuador | 66       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Quito                          | 27       | 40.91%  |
| Guayaquil                      | 20       | 30.3%   |
| Manta                          | 3        | 4.55%   |
| Cuenca                         | 3        | 4.55%   |
| Riobamba                       | 2        | 3.03%   |
| Cotacachi                      | 2        | 3.03%   |
| Santo Domingo de los Colorados | 1        | 1.52%   |
| Quevedo                        | 1        | 1.52%   |
| Loja                           | 1        | 1.52%   |
| Latacunga                      | 1        | 1.52%   |
| Las Pinas                      | 1        | 1.52%   |
| Guanujo                        | 1        | 1.52%   |
| Cariamanga                     | 1        | 1.52%   |
| Azogues                        | 1        | 1.52%   |
| Ambato                         | 1        | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 40     | 24.74%  |
| Seagate             | 20       | 29     | 20.62%  |
| Samsung Electronics | 11       | 13     | 11.34%  |
| Toshiba             | 10       | 14     | 10.31%  |
| Kingston            | 10       | 16     | 10.31%  |
| Hitachi             | 6        | 6      | 6.19%   |
| Hewlett-Packard     | 3        | 3      | 3.09%   |
| A-DATA Technology   | 3        | 4      | 3.09%   |
| SPCC                | 2        | 2      | 2.06%   |
| PNY                 | 2        | 2      | 2.06%   |
| Micro Center        | 1        | 1      | 1.03%   |
| Intel               | 1        | 1      | 1.03%   |
| Imation             | 1        | 1      | 1.03%   |
| HPE                 | 1        | 1      | 1.03%   |
| Gigabyte Technology | 1        | 1      | 1.03%   |
| Fujitsu             | 1        | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB   | 6        | 5.56%   |
| Kingston SA400S37240G 240GB SSD   | 6        | 5.56%   |
| Toshiba DT01ACA100 1TB            | 5        | 4.63%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 4        | 3.7%    |
| Seagate ST1000DM010-2EP102 1TB    | 3        | 2.78%   |
| Samsung HD502HJ 500GB             | 3        | 2.78%   |
| WDC WDS480G2G0A-00JH30 480GB SSD  | 2        | 1.85%   |
| Toshiba DT01ACA200 2TB            | 2        | 1.85%   |
| Kingston SV300S37A60G 64GB SSD    | 2        | 1.85%   |
| Hitachi HDS721050CLA660 500GB     | 2        | 1.85%   |
| HP SSD S700 500GB                 | 2        | 1.85%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 0.93%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 0.93%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 0.93%   |
| WDC WDBNCE5000PNC 500GB SSD       | 1        | 0.93%   |
| WDC WD7500BPVX-22JC3T0 752GB      | 1        | 0.93%   |
| WDC WD5000AVVS-63M8B0 500GB       | 1        | 0.93%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 1        | 0.93%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 0.93%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1        | 0.93%   |
| WDC WD5000AAKS-00V2B0 500GB       | 1        | 0.93%   |
| WDC WD40EFAX-68JH4N1 4TB          | 1        | 0.93%   |
| WDC WD3200AVVS-63L2B0 320GB       | 1        | 0.93%   |
| WDC WD3200AAJS-60M0A0 320GB       | 1        | 0.93%   |
| WDC WD30EZRS-00J99B0 3TB          | 1        | 0.93%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 0.93%   |
| WDC WD1600HLHX-60JJPV1 160GB      | 1        | 0.93%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 0.93%   |
| WDC WD1200BEVS-22UST0 120GB       | 1        | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB          | 1        | 0.93%   |
| WDC WD10EZEX-00WN4A0 1TB          | 1        | 0.93%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 0.93%   |
| WDC WD10EURX-63UY4Y0 1TB          | 1        | 0.93%   |
| WDC WD1002FBYS-18W8B0 1TB         | 1        | 0.93%   |
| Toshiba THNSFJ256GDNU A 256GB SSD | 1        | 0.93%   |
| Toshiba MK7559GSXP 752GB          | 1        | 0.93%   |
| Toshiba MK5055GSX 500GB           | 1        | 0.93%   |
| Toshiba MK3276GSX 320GB           | 1        | 0.93%   |
| SPCC Solid State Disk 512GB       | 1        | 0.93%   |
| SPCC M.2 SSD 256GB                | 1        | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 33     | 29.85%  |
| Seagate             | 20       | 29     | 29.85%  |
| Samsung Electronics | 10       | 12     | 14.93%  |
| Toshiba             | 9        | 13     | 13.43%  |
| Hitachi             | 6        | 6      | 8.96%   |
| HPE                 | 1        | 1      | 1.49%   |
| Fujitsu             | 1        | 1      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 10       | 14     | 34.48%  |
| WDC                 | 6        | 7      | 20.69%  |
| Hewlett-Packard     | 3        | 3      | 10.34%  |
| SPCC                | 2        | 2      | 6.9%    |
| PNY                 | 2        | 2      | 6.9%    |
| A-DATA Technology   | 2        | 2      | 6.9%    |
| Toshiba             | 1        | 1      | 3.45%   |
| Micro Center        | 1        | 1      | 3.45%   |
| Intel               | 1        | 1      | 3.45%   |
| Gigabyte Technology | 1        | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 55       | 95     | 64.71%  |
| SSD     | 26       | 34     | 30.59%  |
| NVMe    | 3        | 5      | 3.53%   |
| Unknown | 1        | 1      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 66       | 130    | 95.65%  |
| NVMe | 3        | 5      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 74     | 55.81%  |
| 0.51-1.0   | 27       | 38     | 31.4%   |
| 1.01-2.0   | 9        | 15     | 10.47%  |
| 3.01-4.0   | 1        | 1      | 1.16%   |
| 2.01-3.0   | 1        | 1      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 20       | 27.78%  |
| 101-250        | 14       | 19.44%  |
| 501-1000       | 12       | 16.67%  |
| 1001-2000      | 11       | 15.28%  |
| 1-20           | 7        | 9.72%   |
| More than 3000 | 4        | 5.56%   |
| 51-100         | 2        | 2.78%   |
| Unknown        | 2        | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 25       | 33.78%  |
| 21-50          | 14       | 18.92%  |
| 251-500        | 10       | 13.51%  |
| 101-250        | 6        | 8.11%   |
| 51-100         | 6        | 8.11%   |
| 1001-2000      | 5        | 6.76%   |
| 501-1000       | 4        | 5.41%   |
| More than 3000 | 2        | 2.7%    |
| Unknown        | 2        | 2.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2        | 3      | 15.38%  |
| Hitachi HDS721050CLA660 500GB     | 2        | 2      | 15.38%  |
| WDC WD1200BEVS-22UST0 120GB       | 1        | 1      | 7.69%   |
| Seagate ST3750330AS 752GB         | 1        | 1      | 7.69%   |
| Seagate ST31000333AS 1TB          | 1        | 1      | 7.69%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 2      | 7.69%   |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 7.69%   |
| Samsung Electronics HD322HJ 320GB | 1        | 1      | 7.69%   |
| Kingston SNS4151S316GD 16GB SSD   | 1        | 1      | 7.69%   |
| HPE MB0500EAMZD 500GB             | 1        | 1      | 7.69%   |
| Fujitsu MHZ2160BH G1 160GB        | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 7      | 38.46%  |
| Samsung Electronics | 2        | 2      | 15.38%  |
| Hitachi             | 2        | 2      | 15.38%  |
| WDC                 | 1        | 1      | 7.69%   |
| Kingston            | 1        | 1      | 7.69%   |
| HPE                 | 1        | 1      | 7.69%   |
| Fujitsu             | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 7      | 41.67%  |
| Samsung Electronics | 2        | 2      | 16.67%  |
| Hitachi             | 2        | 2      | 16.67%  |
| WDC                 | 1        | 1      | 8.33%   |
| HPE                 | 1        | 1      | 8.33%   |
| Fujitsu             | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 14     | 90%     |
| SSD  | 1        | 1      | 10%     |

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
| Detected | 46       | 101    | 63.89%  |
| Works    | 16       | 19     | 22.22%  |
| Malfunc  | 10       | 15     | 13.89%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 48       | 61.54%  |
| AMD                         | 16       | 20.51%  |
| Marvell Technology Group    | 4        | 5.13%   |
| VIA Technologies            | 2        | 2.56%   |
| JMicron Technology          | 2        | 2.56%   |
| ASMedia Technology          | 2        | 2.56%   |
| Samsung Electronics         | 1        | 1.28%   |
| Nvidia                      | 1        | 1.28%   |
| Kingston Technology Company | 1        | 1.28%   |
| ADATA Technology            | 1        | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 8.82%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 7.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 5.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 4.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 3.92%   |
| AMD FCH SATA Controller D                                                               | 4        | 3.92%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 2.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 2.94%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.96%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.98%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 0.98%   |
| VIA Serial ATA Controller                                                               | 1        | 0.98%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.98%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.98%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.98%   |
| Marvell Group 88SE914D SATA-600 Controller                                              | 1        | 0.98%   |
| Marvell Group 88SE6145 SATA II PCI-E controller                                         | 1        | 0.98%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.98%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 0.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.98%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.98%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.98%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 47       | 63.51%  |
| IDE  | 20       | 27.03%  |
| RAID | 4        | 5.41%   |
| NVMe | 3        | 4.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 49       | 74.24%  |
| AMD    | 17       | 25.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4440 CPU @ 3.10GHz            | 4        | 6.06%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 4.55%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 3.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 3.03%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 3.03%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 2        | 3.03%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 3.03%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 3.03%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 3.03%   |
| AMD Athlon II X2 270 Processor              | 2        | 3.03%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 1.52%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.52%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.52%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 1.52%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.52%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.52%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.52%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.52%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 1.52%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.52%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.52%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.52%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.52%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.52%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.52%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.52%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.52%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.52%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.52%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.52%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.52%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.52%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.52%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.52%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 1.52%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1.52%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 1.52%   |
| Intel Celeron J4005 CPU @ 2.00GHz           | 1        | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 27.27%  |
| AMD Ryzen 5             | 9        | 13.64%  |
| Intel Core i7           | 8        | 12.12%  |
| Intel Core i3           | 6        | 9.09%   |
| Intel Pentium           | 5        | 7.58%   |
| Intel Celeron           | 4        | 6.06%   |
| Intel Core 2 Quad       | 2        | 3.03%   |
| Intel Core 2 Duo        | 2        | 3.03%   |
| Intel Atom              | 2        | 3.03%   |
| AMD E1                  | 2        | 3.03%   |
| AMD Athlon II X2        | 2        | 3.03%   |
| Intel Xeon              | 1        | 1.52%   |
| Intel Pentium Dual-Core | 1        | 1.52%   |
| AMD Ryzen 7             | 1        | 1.52%   |
| AMD Phenom II X6        | 1        | 1.52%   |
| AMD Phenom II X2        | 1        | 1.52%   |
| AMD Athlon II Neo       | 1        | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 30       | 45.45%  |
| 2      | 23       | 34.85%  |
| 6      | 11       | 16.67%  |
| 8      | 2        | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 42       | 63.64%  |
| 2      | 24       | 36.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 65       | 98.48%  |
| Unknown        | 1        | 1.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 10       | 14.71%  |
| Unknown    | 10       | 14.71%  |
| 0x306a9    | 8        | 11.76%  |
| 0x206a7    | 5        | 7.35%   |
| 0xa0653    | 4        | 5.88%   |
| 0x1067a    | 4        | 5.88%   |
| 0x906ed    | 2        | 2.94%   |
| 0x106e5    | 2        | 2.94%   |
| 0x0a201005 | 2        | 2.94%   |
| 0x0810100b | 2        | 2.94%   |
| 0x010000c8 | 2        | 2.94%   |
| 0x906ec    | 1        | 1.47%   |
| 0x906ea    | 1        | 1.47%   |
| 0x706a1    | 1        | 1.47%   |
| 0x6fd      | 1        | 1.47%   |
| 0x40651    | 1        | 1.47%   |
| 0x206c2    | 1        | 1.47%   |
| 0x106ca    | 1        | 1.47%   |
| 0x106c2    | 1        | 1.47%   |
| 0x106a5    | 1        | 1.47%   |
| 0x10676    | 1        | 1.47%   |
| 0x0a201204 | 1        | 1.47%   |
| 0x08701021 | 1        | 1.47%   |
| 0x08701013 | 1        | 1.47%   |
| 0x08101016 | 1        | 1.47%   |
| 0x08101004 | 1        | 1.47%   |
| 0x0700010f | 1        | 1.47%   |
| 0x010000bf | 1        | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 13       | 19.7%   |
| IvyBridge     | 8        | 12.12%  |
| SandyBridge   | 5        | 7.58%   |
| Penryn        | 5        | 7.58%   |
| K10           | 5        | 7.58%   |
| CometLake     | 5        | 7.58%   |
| KabyLake      | 4        | 6.06%   |
| Zen 3         | 3        | 4.55%   |
| Zen 2         | 3        | 4.55%   |
| Zen           | 3        | 4.55%   |
| Nehalem       | 3        | 4.55%   |
| Bonnell       | 2        | 3.03%   |
| Zen+          | 1        | 1.52%   |
| Westmere      | 1        | 1.52%   |
| Skylake       | 1        | 1.52%   |
| Jaguar        | 1        | 1.52%   |
| Goldmont plus | 1        | 1.52%   |
| Core          | 1        | 1.52%   |
| Bobcat        | 1        | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 35       | 48.61%  |
| Nvidia           | 20       | 27.78%  |
| AMD              | 16       | 22.22%  |
| VIA Technologies | 1        | 1.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 12.5%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 9.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 5.56%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 4.17%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 4.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 4.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 4.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 4.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 2.78%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 2.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.78%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 1.39%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.39%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.39%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 1.39%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.39%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.39%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.39%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 1.39%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 1.39%   |
| Nvidia G98 [Quadro NVS 420]                                                 | 1        | 1.39%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.39%   |
| Intel HD Graphics 530                                                       | 1        | 1.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.39%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 1        | 1.39%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 1.39%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.39%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.39%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.39%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.39%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 1.39%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.39%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 1.39%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.39%   |
| AMD Kabini [Radeon HD 8210]                                                 | 1        | 1.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 31       | 45.59%  |
| 1 x Nvidia               | 17       | 25%     |
| 1 x AMD                  | 14       | 20.59%  |
| Intel + Nvidia           | 2        | 2.94%   |
| Intel + AMD              | 2        | 2.94%   |
| 1 x VIA                  | 1        | 1.47%   |
| Intel + AMD + 1 x Nvidia | 1        | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 53       | 76.81%  |
| Proprietary | 11       | 15.94%  |
| Unknown     | 5        | 7.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 42       | 57.53%  |
| 1.01-2.0   | 15       | 20.55%  |
| 0.51-1.0   | 6        | 8.22%   |
| 0.01-0.5   | 5        | 6.85%   |
| 5.01-6.0   | 2        | 2.74%   |
| 7.01-8.0   | 1        | 1.37%   |
| 3.01-4.0   | 1        | 1.37%   |
| 8.01-16.0  | 1        | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 23       | 37.1%   |
| BenQ                | 9        | 14.52%  |
| Hewlett-Packard     | 6        | 9.68%   |
| AOC                 | 6        | 9.68%   |
| Samsung Electronics | 5        | 8.06%   |
| LG Electronics      | 4        | 6.45%   |
| Dell                | 3        | 4.84%   |
| Acer                | 2        | 3.23%   |
| Unknown (XXX)       | 1        | 1.61%   |
| NEC Computers       | 1        | 1.61%   |
| KTC                 | 1        | 1.61%   |
| DMT                 | 1        | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 4        | 5.88%   |
| BenQ G2420HDBL BNQ785E 1920x1080 477x268mm 21.5-inch                 | 3        | 4.41%   |
| LG Electronics LCD Monitor LG TV 1360x768                            | 2        | 2.94%   |
| Goldstar W2243 GSM56FE 1920x1080 480x270mm 21.7-inch                 | 2        | 2.94%   |
| Goldstar LG HD GSM5ACD 1366x768 410x230mm 18.5-inch                  | 2        | 2.94%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 2        | 2.94%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 2        | 2.94%   |
| BenQ GL930A BNQ7870 1366x768 410x230mm 18.5-inch                     | 2        | 2.94%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 1.47%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 1.47%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 304x228mm 15.0-inch  | 1        | 1.47%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 1.47%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 1        | 1.47%   |
| Samsung Electronics LCD Monitor SMB1930N 1366x768                    | 1        | 1.47%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                 | 1        | 1.47%   |
| NEC Computers LCD1850E NEC65D1 1280x1024 359x287mm 18.1-inch         | 1        | 1.47%   |
| LG Electronics LCD Monitor W2043 3520x1080                           | 1        | 1.47%   |
| LG Electronics LCD Monitor 2D HD LG TV                               | 1        | 1.47%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 1.47%   |
| KTC 32T72-H-AN KTC3200 1360x768 698x392mm 31.5-inch                  | 1        | 1.47%   |
| Hewlett-Packard w1858 HWP2835 1366x768 413x234mm 18.7-inch           | 1        | 1.47%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch            | 1        | 1.47%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch           | 1        | 1.47%   |
| Hewlett-Packard Omni/Pro HWP410E 1366x768 410x230mm 18.5-inch        | 1        | 1.47%   |
| Hewlett-Packard LCD Monitor L1710 2646x1024                          | 1        | 1.47%   |
| Hewlett-Packard E241i HWP3124 1920x1200 518x324mm 24.1-inch          | 1        | 1.47%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch          | 1        | 1.47%   |
| Goldstar T1910 GSM4BD8 1280x1024 376x301mm 19.0-inch                 | 1        | 1.47%   |
| Goldstar M237WA GSM5724 1920x1080 509x286mm 23.0-inch                | 1        | 1.47%   |
| Goldstar L177WSB GSM448D 1440x900 370x232mm 17.2-inch                | 1        | 1.47%   |
| Goldstar L1530S GSM3B95 1024x768 304x228mm 15.0-inch                 | 1        | 1.47%   |
| Goldstar IPS WSXGA GSM5B20 1440x900 419x262mm 19.5-inch              | 1        | 1.47%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 1        | 1.47%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                 | 1        | 1.47%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 1        | 1.47%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1        | 1.47%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                  | 1        | 1.47%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 1.47%   |
| DMT CHHWJT* DMT0030 1440x900 708x398mm 32.0-inch                     | 1        | 1.47%   |
| Dell E2311H DELF035 1920x1080 510x287mm 23.0-inch                    | 1        | 1.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 16       | 25.81%  |
| 1366x768 (WXGA)  | 16       | 25.81%  |
| 1360x768         | 7        | 11.29%  |
| 1600x900 (HD+)   | 6        | 9.68%   |
| 1440x900 (WXGA+) | 5        | 8.06%   |
| 1024x768 (XGA)   | 4        | 6.45%   |
| 1280x1024 (SXGA) | 3        | 4.84%   |
| Unknown          | 2        | 3.23%   |
| 3520x1080        | 1        | 1.61%   |
| 2646x1024        | 1        | 1.61%   |
| 2560x1440 (QHD)  | 1        | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 20       | 31.75%  |
| 19      | 8        | 12.7%   |
| Unknown | 8        | 12.7%   |
| 23      | 7        | 11.11%  |
| 21      | 5        | 7.94%   |
| 20      | 4        | 6.35%   |
| 15      | 4        | 6.35%   |
| 24      | 3        | 4.76%   |
| 32      | 2        | 3.17%   |
| 54      | 1        | 1.59%   |
| 17      | 1        | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 33       | 53.23%  |
| 501-600     | 10       | 16.13%  |
| Unknown     | 8        | 12.9%   |
| 351-400     | 4        | 6.45%   |
| 301-350     | 4        | 6.45%   |
| 701-800     | 2        | 3.23%   |
| 1001-1500   | 1        | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 38       | 64.41%  |
| Unknown | 8        | 13.56%  |
| 16/10   | 6        | 10.17%  |
| 4/3     | 4        | 6.78%   |
| 5/4     | 3        | 5.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 19       | 30.16%  |
| 151-200        | 14       | 22.22%  |
| 201-250        | 13       | 20.63%  |
| Unknown        | 8        | 12.7%   |
| 101-110        | 4        | 6.35%   |
| 351-500        | 2        | 3.17%   |
| More than 1000 | 1        | 1.59%   |
| 251-300        | 1        | 1.59%   |
| 131-140        | 1        | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 46       | 75.41%  |
| Unknown | 8        | 13.11%  |
| 101-120 | 5        | 8.2%    |
| 1-50    | 2        | 3.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 58       | 84.06%  |
| 2     | 8        | 11.59%  |
| 0     | 3        | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 48       | 53.93%  |
| Intel                           | 12       | 13.48%  |
| Qualcomm Atheros                | 8        | 8.99%   |
| Ralink Technology               | 5        | 5.62%   |
| TP-Link                         | 4        | 4.49%   |
| Ralink                          | 2        | 2.25%   |
| D-Link System                   | 2        | 2.25%   |
| Broadcom                        | 2        | 2.25%   |
| VIA Technologies                | 1        | 1.12%   |
| TRENDnet                        | 1        | 1.12%   |
| Samsung Electronics             | 1        | 1.12%   |
| Qualcomm Atheros Communications | 1        | 1.12%   |
| Nvidia                          | 1        | 1.12%   |
| Arduino SA                      | 1        | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 38       | 39.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 5        | 5.21%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2        | 2.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 2.08%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2        | 2.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 2        | 2.08%   |
| Intel Ethernet Connection I217-LM                                                             | 2        | 2.08%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 2.08%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                               | 2        | 2.08%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1        | 1.04%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS]             | 1        | 1.04%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.04%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 1.04%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 1.04%   |
| TP-Link 802.11n NIC                                                                           | 1        | 1.04%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                                   | 1        | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.04%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 1.04%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 1.04%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 1.04%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.04%   |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                                                        | 1        | 1.04%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 1.04%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.04%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 1.04%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1        | 1.04%   |
| Nvidia MCP61 Ethernet                                                                         | 1        | 1.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 1.04%   |
| Intel I211 Gigabit Network Connection                                                         | 1        | 1.04%   |
| Intel Ethernet Connection I217-V                                                              | 1        | 1.04%   |
| Intel Ethernet Connection (7) I219-V                                                          | 1        | 1.04%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1        | 1.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 9        | 34.62%  |
| Ralink Technology               | 5        | 19.23%  |
| TP-Link                         | 4        | 15.38%  |
| Qualcomm Atheros                | 3        | 11.54%  |
| Ralink                          | 2        | 7.69%   |
| TRENDnet                        | 1        | 3.85%   |
| Qualcomm Atheros Communications | 1        | 3.85%   |
| Intel                           | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 11.54%  |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 7.69%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2        | 7.69%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS]             | 1        | 3.85%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 3.85%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]                           | 1        | 3.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 3.85%   |
| TP-Link 802.11n NIC                                                                           | 1        | 3.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 3.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 3.85%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 3.85%   |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                                                        | 1        | 3.85%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 3.85%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 3.85%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 3.85%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 3.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 3.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 3.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 46       | 66.67%  |
| Intel                 | 11       | 15.94%  |
| Qualcomm Atheros      | 5        | 7.25%   |
| D-Link System         | 2        | 2.9%    |
| Broadcom              | 2        | 2.9%    |
| VIA Technologies      | 1        | 1.45%   |
| Samsung Electronics   | 1        | 1.45%   |
| Nvidia                | 1        | 1.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38       | 55.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 7.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 2.9%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.9%    |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.9%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 2.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.45%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.45%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.45%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.45%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.45%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.45%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.45%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.45%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 1.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 66       | 72.53%  |
| WiFi     | 24       | 26.37%  |
| Modem    | 1        | 1.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 53       | 80.3%   |
| WiFi     | 13       | 19.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 82.09%  |
| 2     | 11       | 16.42%  |
| 3     | 1        | 1.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 85.29%  |
| Yes  | 10       | 14.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 8        | 66.67%  |
| Realtek Semiconductor   | 1        | 8.33%   |
| Intel                   | 1        | 8.33%   |
| IMC Networks            | 1        | 8.33%   |
| D-Link System           | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 66.67%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 8.33%   |
| Intel AX201 Bluetooth                               | 1        | 8.33%   |
| IMC Networks Bluetooth Device                       | 1        | 8.33%   |
| D-Link System DBT-122 Bluetooth                     | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 49       | 55.06%  |
| AMD              | 21       | 23.6%   |
| Nvidia           | 18       | 20.22%  |
| VIA Technologies | 1        | 1.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 10.19%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 9.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9        | 8.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 5.56%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 5.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 3.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 3.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 3.7%    |
| Nvidia High Definition Audio Controller                                    | 3        | 2.78%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 2.78%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 2.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 2.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.85%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.85%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.85%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.93%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia GF100 High Definition Audio Controller                              | 1        | 0.93%   |
| Intel USB PnP Sound Device                                                 | 1        | 0.93%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 0.93%   |
| Intel Audio device                                                         | 1        | 0.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 0.93%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 0.93%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 0.93%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 30%     |
| Unknown             | 8        | 26.67%  |
| Corsair             | 4        | 13.33%  |
| Samsung Electronics | 2        | 6.67%   |
| Micron Technology   | 2        | 6.67%   |
| PNY                 | 1        | 3.33%   |
| Hewlett-Packard     | 1        | 3.33%   |
| Crucial             | 1        | 3.33%   |
| Avant               | 1        | 3.33%   |
| A-DATA Technology   | 1        | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 2.78%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 2.78%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 2.78%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 1        | 2.78%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 2.78%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s            | 1        | 2.78%   |
| Unknown RAM Module 2048MB DIMM DDR2                       | 1        | 2.78%   |
| Unknown RAM Module 1GB DIMM DDR2                          | 1        | 2.78%   |
| Unknown RAM Module 1024MB DIMM 1333MT/s                   | 1        | 2.78%   |
| Samsung RAM Module 4GB DIMM DDR4 3200MT/s                 | 1        | 2.78%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 2.78%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 2.78%   |
| PNY RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1        | 2.78%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s               | 1        | 2.78%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 2.78%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 1        | 2.78%   |
| Kingston RAM KHX3000C16D4/16GX 16384MB DIMM DDR4 2400MT/s | 1        | 2.78%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 1        | 2.78%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 1        | 2.78%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s      | 1        | 2.78%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 1        | 2.78%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 2.78%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 2.78%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 2.78%   |
| Kingston RAM 99U5471-038.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 2.78%   |
| Kingston RAM 99U5471-030.A00LF 8192MB DIMM DDR3 1333MT/s  | 1        | 2.78%   |
| Kingston RAM 9905471-017.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 2.78%   |
| Kingston RAM 9905402-171.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 2.78%   |
| HP RAM 7EH55AA# 8GB DIMM DDR4 2666MT/s                    | 1        | 2.78%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s     | 1        | 2.78%   |
| Corsair RAM CMV16GX4M1A2666C18 16GB DIMM DDR4 2667MT/s    | 1        | 2.78%   |
| Corsair RAM CMK32GX4M2E3200C16 16384MB DIMM DDR4 3200MT/s | 1        | 2.78%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 2.78%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s     | 1        | 2.78%   |
| Avant RAM W641GU49J9266N6 8GB DIMM DDR4 2666MT/s          | 1        | 2.78%   |
| A-DATA RAM Module 8GB DIMM DDR3 1333MT/s                  | 1        | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 11       | 42.31%  |
| DDR4    | 9        | 34.62%  |
| DDR2    | 3        | 11.54%  |
| Unknown | 2        | 7.69%   |
| SDRAM   | 1        | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 25       | 96.15%  |
| SODIMM | 1        | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 9        | 30%     |
| 8192  | 8        | 26.67%  |
| 2048  | 7        | 23.33%  |
| 16384 | 4        | 13.33%  |
| 1024  | 2        | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 9        | 29.03%  |
| 1600    | 5        | 16.13%  |
| 3200    | 3        | 9.68%   |
| Unknown | 3        | 9.68%   |
| 3600    | 2        | 6.45%   |
| 3466    | 2        | 6.45%   |
| 3400    | 1        | 3.23%   |
| 2667    | 1        | 3.23%   |
| 2666    | 1        | 3.23%   |
| 2400    | 1        | 3.23%   |
| 2133    | 1        | 3.23%   |
| 1866    | 1        | 3.23%   |
| 800     | 1        | 3.23%   |

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
| Generalplus GENERAL WEBCAM                 | 1        | 5.88%   |
| Generalplus 808 Camera #9 (web-cam mode)   | 1        | 5.88%   |
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
| 0     | 57       | 82.61%  |
| 1     | 10       | 14.49%  |
| 2     | 2        | 2.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 50%     |
| Net/wireless             | 4        | 28.57%  |
| Communication controller | 2        | 14.29%  |
| Chipcard                 | 1        | 7.14%   |

