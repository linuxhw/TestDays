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

Total: 94

| Vendor        | Model                | Probe                                                      | Date         |
|---------------|----------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Z170-P               | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | H97-Gaming 3         | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3         | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Biostar       | H61MGV3              | [bb42e29bbb](https://linux-hardware.org/?probe=bb42e29bbb) | Jun 28, 2022 |
| ASRock        | B450 Gaming K4       | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2  | [ff0b730eed](https://linux-hardware.org/?probe=ff0b730eed) | Jun 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2  | [edb1f4bda1](https://linux-hardware.org/?probe=edb1f4bda1) | Jun 14, 2022 |
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
| Ubuntu 20.04       | 14       | 22.58%  |
| Ubuntu 18.04       | 9        | 14.52%  |
| OpenMandriva 4.2   | 3        | 4.84%   |
| Debian 11          | 3        | 4.84%   |
| Zorin 16           | 2        | 3.23%   |
| OpenMandriva 4.3   | 2        | 3.23%   |
| Linux Mint 19.1    | 2        | 3.23%   |
| Fedora 36          | 2        | 3.23%   |
| Fedora 34          | 2        | 3.23%   |
| Xubuntu 18.04      | 1        | 1.61%   |
| Ubuntu 22.04       | 1        | 1.61%   |
| Ubuntu 21.10       | 1        | 1.61%   |
| Ubuntu 16.04       | 1        | 1.61%   |
| Pop!_OS 21.04      | 1        | 1.61%   |
| Pop!_OS 20.04      | 1        | 1.61%   |
| Peppermint 10      | 1        | 1.61%   |
| openSUSE Leap-15.2 | 1        | 1.61%   |
| Manjaro 21.3.7     | 1        | 1.61%   |
| Manjaro 21.2.5     | 1        | 1.61%   |
| Manjaro            | 1        | 1.61%   |
| Lubuntu 16.04      | 1        | 1.61%   |
| LMDE 4             | 1        | 1.61%   |
| Linux Mint 20.3    | 1        | 1.61%   |
| Linux Mint 20.1    | 1        | 1.61%   |
| Kubuntu 22.04      | 1        | 1.61%   |
| Kali 2022.2        | 1        | 1.61%   |
| Fedora 35          | 1        | 1.61%   |
| Elementary 5.1.7   | 1        | 1.61%   |
| Debian 10          | 1        | 1.61%   |
| Clear Linux 35810  | 1        | 1.61%   |
| CentOS 7           | 1        | 1.61%   |
| Arch               | 1        | 1.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 26       | 41.94%  |
| OpenMandriva | 5        | 8.06%   |
| Fedora       | 5        | 8.06%   |
| Linux Mint   | 4        | 6.45%   |
| Debian       | 4        | 6.45%   |
| Manjaro      | 3        | 4.84%   |
| Zorin        | 2        | 3.23%   |
| Pop!_OS      | 2        | 3.23%   |
| Xubuntu      | 1        | 1.61%   |
| Peppermint   | 1        | 1.61%   |
| openSUSE     | 1        | 1.61%   |
| Lubuntu      | 1        | 1.61%   |
| LMDE         | 1        | 1.61%   |
| Kubuntu      | 1        | 1.61%   |
| Kali         | 1        | 1.61%   |
| Elementary   | 1        | 1.61%   |
| Clear Linux  | 1        | 1.61%   |
| CentOS       | 1        | 1.61%   |
| Arch         | 1        | 1.61%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002     | 3        | 4.41%   |
| 5.8.0-50-generic             | 2        | 2.94%   |
| 5.4.0-73-generic             | 2        | 2.94%   |
| 5.4.0-54-generic             | 2        | 2.94%   |
| 5.4.0-29-generic             | 2        | 2.94%   |
| 5.16.7-desktop-1omv4003      | 2        | 2.94%   |
| 4.15.0-20-generic            | 2        | 2.94%   |
| 5.8.0-63-generic             | 1        | 1.47%   |
| 5.8.0-41-generic             | 1        | 1.47%   |
| 5.8.0-40-generic             | 1        | 1.47%   |
| 5.7.0-0.bpo.2-amd64          | 1        | 1.47%   |
| 5.4.0-91-generic             | 1        | 1.47%   |
| 5.4.0-81-generic             | 1        | 1.47%   |
| 5.4.0-7634-generic           | 1        | 1.47%   |
| 5.4.0-45-generic             | 1        | 1.47%   |
| 5.4.0-42-generic             | 1        | 1.47%   |
| 5.4.0-37-generic             | 1        | 1.47%   |
| 5.3.18-lp152.87-default      | 1        | 1.47%   |
| 5.3.0-46-generic             | 1        | 1.47%   |
| 5.18.5-200.fc36.x86_64       | 1        | 1.47%   |
| 5.17.9-602.inttf.fc36.x86_64 | 1        | 1.47%   |
| 5.17.5-76051705-generic      | 1        | 1.47%   |
| 5.17.4-200.fc35.x86_64       | 1        | 1.47%   |
| 5.17.0-kali3-amd64           | 1        | 1.47%   |
| 5.16.7-1122.native           | 1        | 1.47%   |
| 5.16.0-arch1-1               | 1        | 1.47%   |
| 5.15.60-1-MANJARO            | 1        | 1.47%   |
| 5.15.28-1-MANJARO            | 1        | 1.47%   |
| 5.15.0-46-lowlatency         | 1        | 1.47%   |
| 5.15.0-30-generic            | 1        | 1.47%   |
| 5.13.4-200.fc34.x86_64       | 1        | 1.47%   |
| 5.13.0-39-generic            | 1        | 1.47%   |
| 5.13.0-35-generic            | 1        | 1.47%   |
| 5.13.0-30-generic            | 1        | 1.47%   |
| 5.13.0-19-generic            | 1        | 1.47%   |
| 5.11.16-300.fc34.x86_64      | 1        | 1.47%   |
| 5.11.0-7633-generic          | 1        | 1.47%   |
| 5.11.0-46-generic            | 1        | 1.47%   |
| 5.11.0-34-generic            | 1        | 1.47%   |
| 5.11.0-27-generic            | 1        | 1.47%   |
| 5.10.59-1-MANJARO            | 1        | 1.47%   |
| 5.10.0-9-amd64               | 1        | 1.47%   |
| 5.10.0-8-amd64               | 1        | 1.47%   |
| 5.10.0-11-amd64              | 1        | 1.47%   |
| 5.0.10-050010-generic        | 1        | 1.47%   |
| 5.0.0-37-generic             | 1        | 1.47%   |
| 5.0.0-23-generic             | 1        | 1.47%   |
| 4.19.0-20-amd64              | 1        | 1.47%   |
| 4.19.0-041900-generic        | 1        | 1.47%   |
| 4.18.0-17-generic            | 1        | 1.47%   |
| 4.15.0-50-generic            | 1        | 1.47%   |
| 4.15.0-45-generic            | 1        | 1.47%   |
| 4.15.0-43-generic            | 1        | 1.47%   |
| 4.15.0-142-generic           | 1        | 1.47%   |
| 4.15.0-118-generic           | 1        | 1.47%   |
| 4.15.0-112-generic           | 1        | 1.47%   |
| 4.15.0-109-generic           | 1        | 1.47%   |
| 4.15.0-107-generic           | 1        | 1.47%   |
| 4.15.0-102-generic           | 1        | 1.47%   |
| 3.10.0-1127.19.1.el7.x86_64  | 1        | 1.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 11       | 17.19%  |
| 4.15.0  | 9        | 14.06%  |
| 5.8.0   | 5        | 7.81%   |
| 5.11.0  | 4        | 6.25%   |
| 5.16.7  | 3        | 4.69%   |
| 5.13.0  | 3        | 4.69%   |
| 5.10.14 | 3        | 4.69%   |
| 5.10.0  | 3        | 4.69%   |
| 5.15.0  | 2        | 3.13%   |
| 5.0.0   | 2        | 3.13%   |
| 4.19.0  | 2        | 3.13%   |
| 5.7.0   | 1        | 1.56%   |
| 5.3.18  | 1        | 1.56%   |
| 5.3.0   | 1        | 1.56%   |
| 5.18.5  | 1        | 1.56%   |
| 5.17.9  | 1        | 1.56%   |
| 5.17.5  | 1        | 1.56%   |
| 5.17.4  | 1        | 1.56%   |
| 5.17.0  | 1        | 1.56%   |
| 5.16.0  | 1        | 1.56%   |
| 5.15.60 | 1        | 1.56%   |
| 5.15.28 | 1        | 1.56%   |
| 5.13.4  | 1        | 1.56%   |
| 5.11.16 | 1        | 1.56%   |
| 5.10.59 | 1        | 1.56%   |
| 5.0.10  | 1        | 1.56%   |
| 4.18.0  | 1        | 1.56%   |
| 3.10.0  | 1        | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 11       | 17.19%  |
| 4.15    | 9        | 14.06%  |
| 5.10    | 7        | 10.94%  |
| 5.8     | 5        | 7.81%   |
| 5.11    | 5        | 7.81%   |
| 5.17    | 4        | 6.25%   |
| 5.16    | 4        | 6.25%   |
| 5.15    | 4        | 6.25%   |
| 5.13    | 4        | 6.25%   |
| 5.0     | 3        | 4.69%   |
| 5.3     | 2        | 3.13%   |
| 4.19    | 2        | 3.13%   |
| 5.7     | 1        | 1.56%   |
| 5.18    | 1        | 1.56%   |
| 4.18    | 1        | 1.56%   |
| 3.10    | 1        | 1.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 56       | 96.55%  |
| i686   | 2        | 3.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 28       | 46.67%  |
| KDE5       | 10       | 16.67%  |
| Unknown    | 8        | 13.33%  |
| X-Cinnamon | 5        | 8.33%   |
| XFCE       | 3        | 5%      |
| MATE       | 2        | 3.33%   |
| LXDE       | 2        | 3.33%   |
| qtile      | 1        | 1.67%   |
| Pantheon   | 1        | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 47       | 78.33%  |
| Wayland | 9        | 15%     |
| Unknown | 3        | 5%      |
| Tty     | 1        | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 54.69%  |
| SDDM    | 10       | 15.63%  |
| GDM     | 8        | 12.5%   |
| GDM3    | 6        | 9.38%   |
| LightDM | 3        | 4.69%   |
| TDM     | 2        | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_EC   | 30       | 50%     |
| en_US   | 16       | 26.67%  |
| Unknown | 6        | 10%     |
| es_ES   | 4        | 6.67%   |
| ru_RU   | 1        | 1.67%   |
| es_PE   | 1        | 1.67%   |
| en_AG   | 1        | 1.67%   |
| C       | 1        | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 41       | 70.69%  |
| EFI  | 17       | 29.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 44       | 73.33%  |
| Overlay | 6        | 10%     |
| Btrfs   | 4        | 6.67%   |
| Xfs     | 3        | 5%      |
| Unknown | 3        | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 41       | 69.49%  |
| GPT     | 10       | 16.95%  |
| MBR     | 8        | 13.56%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 83.61%  |
| Yes       | 10       | 16.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 62.71%  |
| Yes       | 22       | 37.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 25.86%  |
| Gigabyte Technology | 9        | 15.52%  |
| Intel               | 8        | 13.79%  |
| Biostar             | 8        | 13.79%  |
| Hewlett-Packard     | 3        | 5.17%   |
| Foxconn             | 3        | 5.17%   |
| ASRock              | 3        | 5.17%   |
| MSI                 | 2        | 3.45%   |
| TPV-INVENTA         | 1        | 1.72%   |
| Shuttle             | 1        | 1.72%   |
| Pegatron            | 1        | 1.72%   |
| Google              | 1        | 1.72%   |
| ECS                 | 1        | 1.72%   |
| Dell                | 1        | 1.72%   |
| Cartimex            | 1        | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 4        | 6.9%    |
| ASUS PRIME A320M-A               | 3        | 5.17%   |
| Gigabyte H81M-H                  | 2        | 3.45%   |
| Biostar H61MGV3                  | 2        | 3.45%   |
| Biostar G31-M7 TE                | 2        | 3.45%   |
| TPV-INVENTA 2AF2 A01             | 1        | 1.72%   |
| Shuttle SFM27                    | 1        | 1.72%   |
| Pegatron CQ1506LA                | 1        | 1.72%   |
| MSI MS-7B98                      | 1        | 1.72%   |
| MSI MS-7758                      | 1        | 1.72%   |
| Intel H81                        | 1        | 1.72%   |
| Intel DZ68DB AAG27985-101        | 1        | 1.72%   |
| Intel DP55KG AAE47218-404        | 1        | 1.72%   |
| Intel DH61WW AAG23116-203        | 1        | 1.72%   |
| Intel DH61BF AAG81311-101        | 1        | 1.72%   |
| Intel DG41RQ AAE54511-205        | 1        | 1.72%   |
| Intel DG33BU AAD79951-407        | 1        | 1.72%   |
| Intel DB75EN AAG39650-302        | 1        | 1.72%   |
| HP ProLiant MicroServer          | 1        | 1.72%   |
| HP ProDesk 600 G1 SFF            | 1        | 1.72%   |
| HP Compaq 6200 Pro MT PC         | 1        | 1.72%   |
| Google Panther                   | 1        | 1.72%   |
| Gigabyte X58A-UD3R               | 1        | 1.72%   |
| Gigabyte H97M-DS3P               | 1        | 1.72%   |
| Gigabyte H97-Gaming 3            | 1        | 1.72%   |
| Gigabyte H410M H V2              | 1        | 1.72%   |
| Gigabyte H310M H 2.0             | 1        | 1.72%   |
| Gigabyte B550 AORUS ELITE V2     | 1        | 1.72%   |
| Gigabyte B450M DS3H              | 1        | 1.72%   |
| Foxconn H61MXL-K                 | 1        | 1.72%   |
| Foxconn H61MXE/-S/-V/-K          | 1        | 1.72%   |
| Foxconn Cinema Series            | 1        | 1.72%   |
| ECS H61H2-MV                     | 1        | 1.72%   |
| Dell Precision WorkStation T5500 | 1        | 1.72%   |
| Cartimex H61H2-MV                | 1        | 1.72%   |
| Biostar P4M90-M7                 | 1        | 1.72%   |
| Biostar H81MLV3                  | 1        | 1.72%   |
| Biostar G41D3C                   | 1        | 1.72%   |
| Biostar A68N-2100                | 1        | 1.72%   |
| ASUS Z170-P                      | 1        | 1.72%   |
| ASUS PRIME J4005I-C              | 1        | 1.72%   |
| ASUS PRIME H410M-E               | 1        | 1.72%   |
| ASUS PRIME B450M-A               | 1        | 1.72%   |
| ASUS PRIME A520M-K               | 1        | 1.72%   |
| ASUS PRIME A320M-K               | 1        | 1.72%   |
| ASUS P7P55D-E                    | 1        | 1.72%   |
| ASUS 970 PRO GAMING/AURA         | 1        | 1.72%   |
| ASRock H61M-VS                   | 1        | 1.72%   |
| ASRock B550M-HDV                 | 1        | 1.72%   |
| ASRock B450 Gaming K4            | 1        | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 8        | 13.79%  |
| ASUS All            | 4        | 6.9%    |
| Gigabyte H81M-H     | 2        | 3.45%   |
| Biostar H61MGV3     | 2        | 3.45%   |
| Biostar G31-M7      | 2        | 3.45%   |
| TPV-INVENTA 2AF2    | 1        | 1.72%   |
| Shuttle SFM27       | 1        | 1.72%   |
| Pegatron CQ1506LA   | 1        | 1.72%   |
| MSI MS-7B98         | 1        | 1.72%   |
| MSI MS-7758         | 1        | 1.72%   |
| Intel H81           | 1        | 1.72%   |
| Intel DZ68DB        | 1        | 1.72%   |
| Intel DP55KG        | 1        | 1.72%   |
| Intel DH61WW        | 1        | 1.72%   |
| Intel DH61BF        | 1        | 1.72%   |
| Intel DG41RQ        | 1        | 1.72%   |
| Intel DG33BU        | 1        | 1.72%   |
| Intel DB75EN        | 1        | 1.72%   |
| HP ProLiant         | 1        | 1.72%   |
| HP ProDesk          | 1        | 1.72%   |
| HP Compaq           | 1        | 1.72%   |
| Google Panther      | 1        | 1.72%   |
| Gigabyte X58A-UD3R  | 1        | 1.72%   |
| Gigabyte H97M-DS3P  | 1        | 1.72%   |
| Gigabyte H97-Gaming | 1        | 1.72%   |
| Gigabyte H410M      | 1        | 1.72%   |
| Gigabyte H310M      | 1        | 1.72%   |
| Gigabyte B550       | 1        | 1.72%   |
| Gigabyte B450M      | 1        | 1.72%   |
| Foxconn H61MXL-K    | 1        | 1.72%   |
| Foxconn H61MXE      | 1        | 1.72%   |
| Foxconn Cinema      | 1        | 1.72%   |
| ECS H61H2-MV        | 1        | 1.72%   |
| Dell Precision      | 1        | 1.72%   |
| Cartimex H61H2-MV   | 1        | 1.72%   |
| Biostar P4M90-M7    | 1        | 1.72%   |
| Biostar H81MLV3     | 1        | 1.72%   |
| Biostar G41D3C      | 1        | 1.72%   |
| Biostar A68N-2100   | 1        | 1.72%   |
| ASUS Z170-P         | 1        | 1.72%   |
| ASUS P7P55D-E       | 1        | 1.72%   |
| ASUS 970            | 1        | 1.72%   |
| ASRock H61M-VS      | 1        | 1.72%   |
| ASRock B550M-HDV    | 1        | 1.72%   |
| ASRock B450         | 1        | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 10       | 17.24%  |
| 2012 | 7        | 12.07%  |
| 2011 | 6        | 10.34%  |
| 2018 | 5        | 8.62%   |
| 2020 | 4        | 6.9%    |
| 2017 | 4        | 6.9%    |
| 2009 | 4        | 6.9%    |
| 2014 | 3        | 5.17%   |
| 2010 | 3        | 5.17%   |
| 2008 | 3        | 5.17%   |
| 2021 | 2        | 3.45%   |
| 2019 | 2        | 3.45%   |
| 2015 | 2        | 3.45%   |
| 2007 | 2        | 3.45%   |
| 2016 | 1        | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 58       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 58       | 98.31%  |
| Enabled  | 1        | 1.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 57       | 98.28%  |
| Yes  | 1        | 1.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 18       | 29.51%  |
| 4.01-8.0   | 13       | 21.31%  |
| 3.01-4.0   | 11       | 18.03%  |
| 16.01-24.0 | 7        | 11.48%  |
| 1.01-2.0   | 5        | 8.2%    |
| 32.01-64.0 | 4        | 6.56%   |
| 24.01-32.0 | 3        | 4.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 24       | 34.78%  |
| 2.01-3.0  | 20       | 28.99%  |
| 3.01-4.0  | 11       | 15.94%  |
| 4.01-8.0  | 8        | 11.59%  |
| 8.01-16.0 | 2        | 2.9%    |
| 0.51-1.0  | 2        | 2.9%    |
| 0.01-0.5  | 2        | 2.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 34       | 55.74%  |
| 2      | 16       | 26.23%  |
| 3      | 10       | 16.39%  |
| 5      | 1        | 1.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 30       | 50%     |
| No        | 30       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 58       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 69.49%  |
| Yes       | 18       | 30.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 86.21%  |
| Yes       | 8        | 13.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Ecuador | 58       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Quito                          | 21       | 36.21%  |
| Guayaquil                      | 19       | 32.76%  |
| Manta                          | 3        | 5.17%   |
| Cuenca                         | 3        | 5.17%   |
| Riobamba                       | 2        | 3.45%   |
| Cotacachi                      | 2        | 3.45%   |
| Santo Domingo de los Colorados | 1        | 1.72%   |
| Quevedo                        | 1        | 1.72%   |
| Loja                           | 1        | 1.72%   |
| Latacunga                      | 1        | 1.72%   |
| Las Pinas                      | 1        | 1.72%   |
| Guanujo                        | 1        | 1.72%   |
| Cariamanga                     | 1        | 1.72%   |
| Ambato                         | 1        | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 36     | 25%     |
| Seagate             | 16       | 24     | 18.18%  |
| Samsung Electronics | 11       | 13     | 12.5%   |
| Toshiba             | 9        | 13     | 10.23%  |
| Kingston            | 9        | 15     | 10.23%  |
| Hitachi             | 6        | 6      | 6.82%   |
| A-DATA Technology   | 3        | 4      | 3.41%   |
| SPCC                | 2        | 2      | 2.27%   |
| PNY                 | 2        | 2      | 2.27%   |
| Hewlett-Packard     | 2        | 2      | 2.27%   |
| Micro Center        | 1        | 1      | 1.14%   |
| Intel               | 1        | 1      | 1.14%   |
| Imation             | 1        | 1      | 1.14%   |
| HPE                 | 1        | 1      | 1.14%   |
| Gigabyte Technology | 1        | 1      | 1.14%   |
| Fujitsu             | 1        | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 5        | 5.15%   |
| Kingston SA400S37240G 240GB SSD     | 5        | 5.15%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 4        | 4.12%   |
| Toshiba DT01ACA100 1TB              | 4        | 4.12%   |
| Samsung HD502HJ 500GB               | 3        | 3.09%   |
| Toshiba DT01ACA200 2TB              | 2        | 2.06%   |
| Seagate ST1000DM010-2EP102 1TB      | 2        | 2.06%   |
| Kingston SV300S37A60G 64GB SSD      | 2        | 2.06%   |
| Hitachi HDS721050CLA660 500GB       | 2        | 2.06%   |
| HP SSD S700 500GB                   | 2        | 2.06%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1        | 1.03%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1.03%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1        | 1.03%   |
| WDC WDBNCE5000PNC 500GB SSD         | 1        | 1.03%   |
| WDC WD7500BPVX-22JC3T0 752GB        | 1        | 1.03%   |
| WDC WD5000AVVS-63M8B0 500GB         | 1        | 1.03%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1        | 1.03%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1.03%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 1        | 1.03%   |
| WDC WD5000AAKS-00V2B0 500GB         | 1        | 1.03%   |
| WDC WD40EFAX-68JH4N1 4TB            | 1        | 1.03%   |
| WDC WD3200AVVS-63L2B0 320GB         | 1        | 1.03%   |
| WDC WD3200AAJS-60M0A0 320GB         | 1        | 1.03%   |
| WDC WD30EZRS-00J99B0 3TB            | 1        | 1.03%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1.03%   |
| WDC WD1600HLHX-60JJPV1 160GB        | 1        | 1.03%   |
| WDC WD1600AAJS-75M0A0 160GB         | 1        | 1.03%   |
| WDC WD1200BEVS-22UST0 120GB         | 1        | 1.03%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 1.03%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 1.03%   |
| WDC WD10EURX-63UY4Y0 1TB            | 1        | 1.03%   |
| WDC WD1002FBYS-18W8B0 1TB           | 1        | 1.03%   |
| Toshiba THNSFJ256GDNU A 256GB SSD   | 1        | 1.03%   |
| Toshiba MK7559GSXP 752GB            | 1        | 1.03%   |
| Toshiba MK5055GSX 500GB             | 1        | 1.03%   |
| Toshiba MK3276GSX 320GB             | 1        | 1.03%   |
| SPCC Solid State Disk 512GB         | 1        | 1.03%   |
| SPCC M.2 SSD 256GB                  | 1        | 1.03%   |
| Seagate ST3750640NS 752GB           | 1        | 1.03%   |
| Seagate ST3750330AS 752GB           | 1        | 1.03%   |
| Seagate ST3500312CS 500GB           | 1        | 1.03%   |
| Seagate ST3400833AS 400GB           | 1        | 1.03%   |
| Seagate ST320LT007-9ZV142 320GB     | 1        | 1.03%   |
| Seagate ST31000524AS 1TB            | 1        | 1.03%   |
| Seagate ST31000333AS 1TB            | 1        | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 1.03%   |
| Seagate ST1000DM003-9YN162 1TB      | 1        | 1.03%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1.03%   |
| Samsung SSD 980 500GB               | 1        | 1.03%   |
| Samsung SP0802N 80GB                | 1        | 1.03%   |
| Samsung HD503HI 500GB               | 1        | 1.03%   |
| Samsung HD501LJ 500GB               | 1        | 1.03%   |
| Samsung HD322HJ 320GB               | 1        | 1.03%   |
| Samsung HD161HJ 160GB               | 1        | 1.03%   |
| Samsung HD160JJ 160GB               | 1        | 1.03%   |
| Samsung HD103SJ 1TB                 | 1        | 1.03%   |
| PNY SSD2SC240G1CS1754D117-488 240GB | 1        | 1.03%   |
| PNY CS900 240GB SSD                 | 1        | 1.03%   |
| Micro Center SSD G2 series 64GB     | 1        | 1.03%   |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 19       | 31     | 31.15%  |
| Seagate             | 16       | 24     | 26.23%  |
| Samsung Electronics | 10       | 12     | 16.39%  |
| Toshiba             | 8        | 12     | 13.11%  |
| Hitachi             | 6        | 6      | 9.84%   |
| HPE                 | 1        | 1      | 1.64%   |
| Fujitsu             | 1        | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 9        | 13     | 36%     |
| WDC                 | 4        | 5      | 16%     |
| SPCC                | 2        | 2      | 8%      |
| PNY                 | 2        | 2      | 8%      |
| Hewlett-Packard     | 2        | 2      | 8%      |
| A-DATA Technology   | 2        | 2      | 8%      |
| Toshiba             | 1        | 1      | 4%      |
| Micro Center        | 1        | 1      | 4%      |
| Intel               | 1        | 1      | 4%      |
| Gigabyte Technology | 1        | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 49       | 87     | 65.33%  |
| SSD     | 22       | 30     | 29.33%  |
| NVMe    | 3        | 5      | 4%      |
| Unknown | 1        | 1      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 58       | 118    | 95.08%  |
| NVMe | 3        | 5      | 4.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 43       | 69     | 56.58%  |
| 0.51-1.0   | 23       | 34     | 30.26%  |
| 1.01-2.0   | 8        | 12     | 10.53%  |
| 3.01-4.0   | 1        | 1      | 1.32%   |
| 2.01-3.0   | 1        | 1      | 1.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 17       | 26.56%  |
| 101-250        | 13       | 20.31%  |
| 1001-2000      | 10       | 15.63%  |
| 501-1000       | 10       | 15.63%  |
| 1-20           | 7        | 10.94%  |
| More than 3000 | 4        | 6.25%   |
| 51-100         | 2        | 3.13%   |
| Unknown        | 1        | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 22       | 33.33%  |
| 21-50          | 11       | 16.67%  |
| 251-500        | 10       | 15.15%  |
| 51-100         | 6        | 9.09%   |
| 101-250        | 5        | 7.58%   |
| 1001-2000      | 5        | 7.58%   |
| 501-1000       | 4        | 6.06%   |
| More than 3000 | 2        | 3.03%   |
| Unknown        | 1        | 1.52%   |

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
| Detected | 40       | 91     | 62.5%   |
| Works    | 14       | 17     | 21.88%  |
| Malfunc  | 10       | 15     | 15.63%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 42       | 60%     |
| AMD                         | 15       | 21.43%  |
| Marvell Technology Group    | 4        | 5.71%   |
| VIA Technologies            | 2        | 2.86%   |
| JMicron Technology          | 2        | 2.86%   |
| ASMedia Technology          | 2        | 2.86%   |
| Samsung Electronics         | 1        | 1.43%   |
| Kingston Technology Company | 1        | 1.43%   |
| ADATA Technology            | 1        | 1.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 9.68%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 8.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 6.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 5.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 5.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 4.3%    |
| AMD FCH SATA Controller D                                                               | 4        | 4.3%    |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 3.23%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.23%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 2.15%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 2.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 2.15%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 2.15%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 2.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.15%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 1.08%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 1.08%   |
| VIA Serial ATA Controller                                                               | 1        | 1.08%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.08%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 1.08%   |
| Marvell Group 88SE914D SATA-600 Controller                                              | 1        | 1.08%   |
| Marvell Group 88SE6145 SATA II PCI-E controller                                         | 1        | 1.08%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 1.08%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 1.08%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.08%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.08%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.08%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 1.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.08%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.08%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 1.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 42       | 64.62%  |
| IDE  | 18       | 27.69%  |
| NVMe | 3        | 4.62%   |
| RAID | 2        | 3.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 43       | 74.14%  |
| AMD    | 15       | 25.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4440 CPU @ 3.10GHz            | 4        | 6.9%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 5.17%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 3.45%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 3.45%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 2        | 3.45%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 3.45%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 3.45%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 3.45%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1        | 1.72%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.72%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.72%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 1.72%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 1.72%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 1.72%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.72%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.72%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.72%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.72%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.72%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.72%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.72%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.72%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.72%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.72%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.72%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 1.72%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 1.72%   |
| Intel Celeron J4005 CPU @ 2.00GHz           | 1        | 1.72%   |
| Intel Celeron CPU E3300 @ 2.50GHz           | 1        | 1.72%   |
| Intel Celeron 2955U @ 1.40GHz               | 1        | 1.72%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 1.72%   |
| Intel Atom CPU 330 @ 1.60GHz                | 1        | 1.72%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 1        | 1.72%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 1        | 1.72%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 1.72%   |
| AMD Phenom II X6 1055T Processor            | 1        | 1.72%   |
| AMD Phenom II X2 555 Processor              | 1        | 1.72%   |
| AMD E1-2100 APU with Radeon HD Graphics     | 1        | 1.72%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 1        | 1.72%   |
| AMD Athlon II Neo N36L Dual-Core Processor  | 1        | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 25.86%  |
| AMD Ryzen 5             | 9        | 15.52%  |
| Intel Core i7           | 7        | 12.07%  |
| Intel Pentium           | 5        | 8.62%   |
| Intel Core i3           | 5        | 8.62%   |
| Intel Celeron           | 3        | 5.17%   |
| Intel Core 2 Quad       | 2        | 3.45%   |
| Intel Core 2 Duo        | 2        | 3.45%   |
| Intel Atom              | 2        | 3.45%   |
| AMD E1                  | 2        | 3.45%   |
| Intel Xeon              | 1        | 1.72%   |
| Intel Pentium Dual-Core | 1        | 1.72%   |
| AMD Ryzen 7             | 1        | 1.72%   |
| AMD Phenom II X6        | 1        | 1.72%   |
| AMD Phenom II X2        | 1        | 1.72%   |
| AMD Athlon II Neo       | 1        | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 28       | 48.28%  |
| 2      | 20       | 34.48%  |
| 6      | 8        | 13.79%  |
| 8      | 2        | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 58       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 37       | 63.79%  |
| 2      | 21       | 36.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 57       | 98.28%  |
| Unknown        | 1        | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 9        | 15%     |
| Unknown    | 9        | 15%     |
| 0x306a9    | 8        | 13.33%  |
| 0x206a7    | 5        | 8.33%   |
| 0x1067a    | 4        | 6.67%   |
| 0x106e5    | 2        | 3.33%   |
| 0x0a201005 | 2        | 3.33%   |
| 0x0810100b | 2        | 3.33%   |
| 0xa0653    | 1        | 1.67%   |
| 0x906ed    | 1        | 1.67%   |
| 0x906ec    | 1        | 1.67%   |
| 0x706a1    | 1        | 1.67%   |
| 0x6fd      | 1        | 1.67%   |
| 0x40651    | 1        | 1.67%   |
| 0x206c2    | 1        | 1.67%   |
| 0x106ca    | 1        | 1.67%   |
| 0x106c2    | 1        | 1.67%   |
| 0x106a5    | 1        | 1.67%   |
| 0x10676    | 1        | 1.67%   |
| 0x0a201204 | 1        | 1.67%   |
| 0x08701021 | 1        | 1.67%   |
| 0x08701013 | 1        | 1.67%   |
| 0x08101016 | 1        | 1.67%   |
| 0x08101004 | 1        | 1.67%   |
| 0x0700010f | 1        | 1.67%   |
| 0x010000c8 | 1        | 1.67%   |
| 0x010000bf | 1        | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 12       | 20.69%  |
| IvyBridge     | 8        | 13.79%  |
| SandyBridge   | 5        | 8.62%   |
| Penryn        | 5        | 8.62%   |
| Zen 3         | 3        | 5.17%   |
| Zen 2         | 3        | 5.17%   |
| Zen           | 3        | 5.17%   |
| Nehalem       | 3        | 5.17%   |
| K10           | 3        | 5.17%   |
| KabyLake      | 2        | 3.45%   |
| CometLake     | 2        | 3.45%   |
| Bonnell       | 2        | 3.45%   |
| Zen+          | 1        | 1.72%   |
| Westmere      | 1        | 1.72%   |
| Skylake       | 1        | 1.72%   |
| Jaguar        | 1        | 1.72%   |
| Goldmont plus | 1        | 1.72%   |
| Core          | 1        | 1.72%   |
| Bobcat        | 1        | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 31       | 48.44%  |
| Nvidia           | 17       | 26.56%  |
| AMD              | 15       | 23.44%  |
| VIA Technologies | 1        | 1.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 12.5%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 10.94%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 6.25%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 4.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 4.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 4.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 3.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.13%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 3.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 3.13%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 3.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 3.13%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                           | 1        | 1.56%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.56%   |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 1.56%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.56%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 1.56%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 1.56%   |
| Nvidia G98 [Quadro NVS 420]                                                 | 1        | 1.56%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 1.56%   |
| Intel HD Graphics 530                                                       | 1        | 1.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 1.56%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.56%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.56%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.56%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.56%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 1.56%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.56%   |
| AMD Kabini [Radeon HD 8210]                                                 | 1        | 1.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 1.56%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 1        | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 27       | 45%     |
| 1 x Nvidia               | 14       | 23.33%  |
| 1 x AMD                  | 13       | 21.67%  |
| Intel + Nvidia           | 2        | 3.33%   |
| Intel + AMD              | 2        | 3.33%   |
| 1 x VIA                  | 1        | 1.67%   |
| Intel + AMD + 1 x Nvidia | 1        | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 46       | 75.41%  |
| Proprietary | 10       | 16.39%  |
| Unknown     | 5        | 8.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 55.38%  |
| 1.01-2.0   | 14       | 21.54%  |
| 0.51-1.0   | 6        | 9.23%   |
| 0.01-0.5   | 4        | 6.15%   |
| 5.01-6.0   | 2        | 3.08%   |
| 7.01-8.0   | 1        | 1.54%   |
| 3.01-4.0   | 1        | 1.54%   |
| 8.01-16.0  | 1        | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 21       | 38.18%  |
| BenQ                | 8        | 14.55%  |
| Hewlett-Packard     | 6        | 10.91%  |
| AOC                 | 6        | 10.91%  |
| Samsung Electronics | 4        | 7.27%   |
| LG Electronics      | 4        | 7.27%   |
| Acer                | 2        | 3.64%   |
| Unknown (XXX)       | 1        | 1.82%   |
| NEC Computers       | 1        | 1.82%   |
| DMT                 | 1        | 1.82%   |
| Dell                | 1        | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 3        | 4.92%   |
| BenQ G2420HDBL BNQ785E 1920x1080 477x268mm 21.5-inch                 | 3        | 4.92%   |
| LG Electronics LCD Monitor LG TV 1360x768                            | 2        | 3.28%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                 | 2        | 3.28%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 2        | 3.28%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 2        | 3.28%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 1        | 1.64%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 304x228mm 15.0-inch  | 1        | 1.64%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 1        | 1.64%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 1        | 1.64%   |
| Samsung Electronics LCD Monitor SA300/SA350 1366x768                 | 1        | 1.64%   |
| NEC Computers LCD1850E NEC65D1 1280x1024 359x287mm 18.1-inch         | 1        | 1.64%   |
| LG Electronics LCD Monitor W2043 3520x1080                           | 1        | 1.64%   |
| LG Electronics LCD Monitor 2D HD LG TV                               | 1        | 1.64%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 1.64%   |
| Hewlett-Packard w1858 HWP2835 1366x768 413x234mm 18.7-inch           | 1        | 1.64%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch            | 1        | 1.64%   |
| Hewlett-Packard S2031 HWP2903 1600x900 443x249mm 20.0-inch           | 1        | 1.64%   |
| Hewlett-Packard LCD Monitor L1710 2646x1024                          | 1        | 1.64%   |
| Hewlett-Packard E241i HWP3124 1920x1200 518x324mm 24.1-inch          | 1        | 1.64%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch          | 1        | 1.64%   |
| Hewlett-Packard Compaq CQ-1 HWP410E 1366x768 410x230mm 18.5-inch     | 1        | 1.64%   |
| Goldstar T1910 GSM4BD8 1280x1024 376x301mm 19.0-inch                 | 1        | 1.64%   |
| Goldstar M237WA GSM5724 1920x1080 509x286mm 23.0-inch                | 1        | 1.64%   |
| Goldstar L177WSB GSM448D 1440x900 370x232mm 17.2-inch                | 1        | 1.64%   |
| Goldstar L1530S GSM3B95 1024x768 304x228mm 15.0-inch                 | 1        | 1.64%   |
| Goldstar IPS WSXGA GSM5B20 1440x900 419x262mm 19.5-inch              | 1        | 1.64%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 1        | 1.64%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 1        | 1.64%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                 | 1        | 1.64%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 1        | 1.64%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1        | 1.64%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                  | 1        | 1.64%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 1        | 1.64%   |
| DMT CHHWJT* DMT0030 1440x900 708x398mm 32.0-inch                     | 1        | 1.64%   |
| Dell E2311H DELF035 1920x1080 510x287mm 23.0-inch                    | 1        | 1.64%   |
| Dell E2213H DELA090 1920x1080 480x270mm 21.7-inch                    | 1        | 1.64%   |
| BenQ LCD Monitor GL2480 1920x1080                                    | 1        | 1.64%   |
| BenQ LCD Monitor G2420HDBL 1920x1080                                 | 1        | 1.64%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 1        | 1.64%   |
| BenQ GL930A BNQ7870 1366x768 410x230mm 18.5-inch                     | 1        | 1.64%   |
| BenQ G922HDA BNQ783C 1366x768 410x230mm 18.5-inch                    | 1        | 1.64%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                 | 1        | 1.64%   |
| AOC LCD Monitor 2251w 1920x1080                                      | 1        | 1.64%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 1        | 1.64%   |
| AOC 2251w AOC2251 1920x1080 477x268mm 21.5-inch                      | 1        | 1.64%   |
| AOC 2080W AOC2080 1440x900 419x262mm 19.5-inch                       | 1        | 1.64%   |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                        | 1        | 1.64%   |
| AOC 197S-1 AOCC944 1280x1024 376x301mm 19.0-inch                     | 1        | 1.64%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                       | 1        | 1.64%   |
| Acer V206HQL ACR032C 1600x900 432x240mm 19.5-inch                    | 1        | 1.64%   |
| Acer EI242QR P ACR0958 1920x1080 530x300mm 24.0-inch                 | 1        | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 16       | 29.09%  |
| 1366x768 (WXGA)  | 12       | 21.82%  |
| 1600x900 (HD+)   | 6        | 10.91%  |
| 1360x768         | 6        | 10.91%  |
| 1440x900 (WXGA+) | 5        | 9.09%   |
| 1280x1024 (SXGA) | 3        | 5.45%   |
| 1024x768 (XGA)   | 3        | 5.45%   |
| Unknown          | 2        | 3.64%   |
| 3520x1080        | 1        | 1.82%   |
| 2646x1024        | 1        | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 16       | 28.07%  |
| 19      | 8        | 14.04%  |
| Unknown | 8        | 14.04%  |
| 23      | 7        | 12.28%  |
| 21      | 5        | 8.77%   |
| 20      | 4        | 7.02%   |
| 24      | 3        | 5.26%   |
| 15      | 3        | 5.26%   |
| 54      | 1        | 1.75%   |
| 32      | 1        | 1.75%   |
| 17      | 1        | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 29       | 51.79%  |
| 501-600     | 10       | 17.86%  |
| Unknown     | 8        | 14.29%  |
| 351-400     | 4        | 7.14%   |
| 301-350     | 3        | 5.36%   |
| 701-800     | 1        | 1.79%   |
| 1001-1500   | 1        | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 33       | 62.26%  |
| Unknown | 8        | 15.09%  |
| 16/10   | 6        | 11.32%  |
| 5/4     | 3        | 5.66%   |
| 4/3     | 3        | 5.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 15       | 26.32%  |
| 151-200        | 14       | 24.56%  |
| 201-250        | 13       | 22.81%  |
| Unknown        | 8        | 14.04%  |
| 101-110        | 3        | 5.26%   |
| More than 1000 | 1        | 1.75%   |
| 351-500        | 1        | 1.75%   |
| 251-300        | 1        | 1.75%   |
| 131-140        | 1        | 1.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 40       | 72.73%  |
| Unknown | 8        | 14.55%  |
| 101-120 | 5        | 9.09%   |
| 1-50    | 2        | 3.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 81.97%  |
| 2     | 8        | 13.11%  |
| 0     | 3        | 4.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 42       | 55.26%  |
| Intel                           | 10       | 13.16%  |
| Qualcomm Atheros                | 7        | 9.21%   |
| Ralink Technology               | 5        | 6.58%   |
| TP-Link                         | 2        | 2.63%   |
| Ralink                          | 2        | 2.63%   |
| D-Link System                   | 2        | 2.63%   |
| Broadcom                        | 2        | 2.63%   |
| VIA Technologies                | 1        | 1.32%   |
| Samsung Electronics             | 1        | 1.32%   |
| Qualcomm Atheros Communications | 1        | 1.32%   |
| Arduino SA                      | 1        | 1.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 33       | 40.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 5        | 6.1%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 3.66%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 2.44%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2        | 2.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                    | 2        | 2.44%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 2.44%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                               | 2        | 2.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1        | 1.22%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 1.22%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 1.22%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                                   | 1        | 1.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 1.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1        | 1.22%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.22%   |
| Realtek 802.11ac NIC                                                                          | 1        | 1.22%   |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 1.22%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.22%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 1        | 1.22%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 1.22%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                         | 1        | 1.22%   |
| Intel I211 Gigabit Network Connection                                                         | 1        | 1.22%   |
| Intel Ethernet Connection I217-V                                                              | 1        | 1.22%   |
| Intel Ethernet Connection I217-LM                                                             | 1        | 1.22%   |
| Intel Ethernet Connection (7) I219-V                                                          | 1        | 1.22%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1        | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 1        | 1.22%   |
| Intel 82578DC Gigabit Network Connection                                                      | 1        | 1.22%   |
| Intel 82566DC-2 Gigabit Network Connection                                                    | 1        | 1.22%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                              | 1        | 1.22%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                                              | 1        | 1.22%   |
| Arduino SA Mega 2560 R3 (CDC ACM)                                                             | 1        | 1.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 8        | 40%     |
| Ralink Technology               | 5        | 25%     |
| TP-Link                         | 2        | 10%     |
| Ralink                          | 2        | 10%     |
| Qualcomm Atheros                | 2        | 10%     |
| Qualcomm Atheros Communications | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 3        | 15%     |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2        | 10%     |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                          | 2        | 10%     |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1        | 5%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 5%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 5%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 5%      |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 5%      |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 5%      |
| Realtek 802.11ac NIC                                                                          | 1        | 5%      |
| Ralink RT5572 Wireless Adapter                                                                | 1        | 5%      |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 5%      |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 5%      |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 5%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 5%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 40       | 65.57%  |
| Intel                 | 10       | 16.39%  |
| Qualcomm Atheros      | 5        | 8.2%    |
| D-Link System         | 2        | 3.28%   |
| Broadcom              | 2        | 3.28%   |
| VIA Technologies      | 1        | 1.64%   |
| Samsung Electronics   | 1        | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33       | 54.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 8.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2        | 3.28%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 3.28%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 3.28%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.64%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.64%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.64%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.64%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.64%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.64%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.64%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.64%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 1        | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 75.32%  |
| WiFi     | 18       | 23.38%  |
| Modem    | 1        | 1.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 47       | 81.03%  |
| WiFi     | 11       | 18.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 84.48%  |
| 2     | 8        | 13.79%  |
| 3     | 1        | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 51       | 85%     |
| Yes  | 9        | 15%     |

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
| Intel            | 43       | 54.43%  |
| AMD              | 20       | 25.32%  |
| Nvidia           | 15       | 18.99%  |
| VIA Technologies | 1        | 1.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 11.46%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 9.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 8.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 6.25%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 6.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4        | 4.17%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 4.17%   |
| Nvidia High Definition Audio Controller                                    | 3        | 3.13%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 3.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 2.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.08%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 2.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 2.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 2.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.08%   |
| AMD FCH Azalia Controller                                                  | 2        | 2.08%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 1.04%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.04%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 1.04%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 1.04%   |
| Nvidia GF100 High Definition Audio Controller                              | 1        | 1.04%   |
| Intel USB PnP Sound Device                                                 | 1        | 1.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 1.04%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.04%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.04%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 1.04%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 1.04%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.04%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1        | 1.04%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 1.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 37.5%   |
| Unknown             | 7        | 29.17%  |
| Corsair             | 3        | 12.5%   |
| Samsung Electronics | 1        | 4.17%   |
| PNY                 | 1        | 4.17%   |
| Micron Technology   | 1        | 4.17%   |
| Crucial             | 1        | 4.17%   |
| A-DATA Technology   | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 3.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 3.33%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 1        | 3.33%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 1        | 3.33%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s            | 1        | 3.33%   |
| Unknown RAM Module 2048MB DIMM DDR2                       | 1        | 3.33%   |
| Unknown RAM Module 1GB DIMM DDR2                          | 1        | 3.33%   |
| Unknown RAM Module 1024MB DIMM 1333MT/s                   | 1        | 3.33%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s       | 1        | 3.33%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 3.33%   |
| PNY RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1        | 3.33%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s               | 1        | 3.33%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 1        | 3.33%   |
| Kingston RAM KHX3000C16D4/16GX 16384MB DIMM DDR4 2400MT/s | 1        | 3.33%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 1        | 3.33%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 1        | 3.33%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s         | 1        | 3.33%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s       | 1        | 3.33%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 3.33%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1600MT/s     | 1        | 3.33%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 3.33%   |
| Kingston RAM 99U5471-038.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 3.33%   |
| Kingston RAM 99U5471-030.A00LF 8192MB DIMM DDR3 1333MT/s  | 1        | 3.33%   |
| Kingston RAM 9905471-017.A00LF 4096MB DIMM DDR3 1333MT/s  | 1        | 3.33%   |
| Kingston RAM 9905402-171.A00LF 2GB DIMM DDR3 1333MT/s     | 1        | 3.33%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s     | 1        | 3.33%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s    | 1        | 3.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s     | 1        | 3.33%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 1        | 3.33%   |
| A-DATA RAM Module 8GB DIMM DDR3 1333MT/s                  | 1        | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 10       | 47.62%  |
| DDR4    | 6        | 28.57%  |
| DDR2    | 3        | 14.29%  |
| SDRAM   | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 95.24%  |
| SODIMM | 1        | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 28%     |
| 2048  | 7        | 28%     |
| 4096  | 6        | 24%     |
| 16384 | 3        | 12%     |
| 1024  | 2        | 8%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 8        | 30.77%  |
| 1600    | 4        | 15.38%  |
| Unknown | 3        | 11.54%  |
| 3600    | 2        | 7.69%   |
| 3466    | 2        | 7.69%   |
| 3200    | 2        | 7.69%   |
| 2933    | 1        | 3.85%   |
| 2400    | 1        | 3.85%   |
| 2133    | 1        | 3.85%   |
| 1866    | 1        | 3.85%   |
| 800     | 1        | 3.85%   |

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
| 0     | 52       | 85.25%  |
| 1     | 8        | 13.11%  |
| 2     | 1        | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 70%     |
| Net/wireless             | 2        | 20%     |
| Communication controller | 1        | 10%     |

