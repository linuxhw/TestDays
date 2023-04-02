Linux in Costa Rica - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

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

Total: 95

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| ASRock        | 970 Extreme3             | [906f9d6d04](https://linux-hardware.org/?probe=906f9d6d04) | Mar 30, 2023 |
| MSI           | PRO B650M-A WIFI         | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| ASUSTek       | PRO A320M-R WI-FI        | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| MSI           | 970A GAMING PRO CARBON   | [0649eea8a9](https://linux-hardware.org/?probe=0649eea8a9) | Feb 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx        | [d6fea43eb5](https://linux-hardware.org/?probe=d6fea43eb5) | Feb 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS     | [cc2d26e52e](https://linux-hardware.org/?probe=cc2d26e52e) | Jan 22, 2023 |
| Dell          | 0D28YY A00               | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| MACHINIST     | X79 V2.82H               | [e6028c8640](https://linux-hardware.org/?probe=e6028c8640) | Jan 04, 2023 |
| ZOTAC         | NM10                     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Gigabyte      | B150-HD3-CF              | [173dde2177](https://linux-hardware.org/?probe=173dde2177) | Dec 14, 2022 |
| MSI           | PRO B650M-A WIFI         | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| Gigabyte      | H410M H                  | [09129dad50](https://linux-hardware.org/?probe=09129dad50) | Nov 28, 2022 |
| Gigabyte      | H410M H                  | [88ca303518](https://linux-hardware.org/?probe=88ca303518) | Nov 28, 2022 |
| Gigabyte      | H81M-DS2                 | [f278eb7e59](https://linux-hardware.org/?probe=f278eb7e59) | Nov 27, 2022 |
| ASRock        | B660M Steel Legend       | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend       | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| MACHINIST     | X79 V2.82H               | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| ASUSTek       | PRIME Z370-A             | [5d789a1783](https://linux-hardware.org/?probe=5d789a1783) | Sep 28, 2022 |
| Intel         | DG41WV AAE90316-103      | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Dell          | 0HD5W2 A01               | [1bb8ad599d](https://linux-hardware.org/?probe=1bb8ad599d) | Sep 11, 2022 |
| ASRock        | N68-S UCC                | [1d38f1f08e](https://linux-hardware.org/?probe=1d38f1f08e) | Aug 30, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx        | [b932802b52](https://linux-hardware.org/?probe=b932802b52) | Aug 04, 2022 |
| MACHINIST     | X79 V2.82H               | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H               | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| Unknown       | Unknown                  | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Unknown       | Unknown                  | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| HP            | 0AECh D                  | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| HP            | 83EE                     | [55171637ca](https://linux-hardware.org/?probe=55171637ca) | Apr 29, 2022 |
| Dell          | 040DDP A01               | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| ZOTAC         | NM10                     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| ASUSTek       | STRIX Z270G GAMING       | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| Dell          | 040DDP A01               | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01               | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01               | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01               | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ASRock        | B450 Steel Legend        | [6a631fae48](https://linux-hardware.org/?probe=6a631fae48) | Mar 22, 2022 |
| Dell          | 0RW203 A00               | [21ac06a9f6](https://linux-hardware.org/?probe=21ac06a9f6) | Feb 12, 2022 |
| Dell          | 09KPNV A01               | [8fc6552bc9](https://linux-hardware.org/?probe=8fc6552bc9) | Feb 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI    | [ac53ba49ef](https://linux-hardware.org/?probe=ac53ba49ef) | Jan 28, 2022 |
| Gigabyte      | Z690 UD AX DDR4          | [9158036ed3](https://linux-hardware.org/?probe=9158036ed3) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING  | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| ASUSTek       | H81M-C                   | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| MSI           | H55M-E33                 | [f0786be9c3](https://linux-hardware.org/?probe=f0786be9c3) | Nov 14, 2021 |
| HP            | 18E4                     | [692c64d7c1](https://linux-hardware.org/?probe=692c64d7c1) | Nov 08, 2021 |
| HP            | 18E4                     | [499e85c152](https://linux-hardware.org/?probe=499e85c152) | Nov 07, 2021 |
| MSI           | H55M-E33                 | [3d8c474259](https://linux-hardware.org/?probe=3d8c474259) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS    | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| TPV-INVENT... | 2AF2 A01                 | [23e967d7f5](https://linux-hardware.org/?probe=23e967d7f5) | Oct 06, 2021 |
| ZOTAC         | NM10                     | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| ZOTAC         | NM10                     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| Dell          | 0PU052                   | [25ce6d5bbd](https://linux-hardware.org/?probe=25ce6d5bbd) | Aug 05, 2021 |
| Gigabyte      | B250M-DS3H-CF            | [a5a9cfcd44](https://linux-hardware.org/?probe=a5a9cfcd44) | Jul 18, 2021 |
| Gigabyte      | B250M-DS3H-CF            | [689b83e978](https://linux-hardware.org/?probe=689b83e978) | Jul 18, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI    | [b05fbab283](https://linux-hardware.org/?probe=b05fbab283) | Jun 06, 2021 |
| ASUSTek       | PRIME A320M-K            | [3e92571a0c](https://linux-hardware.org/?probe=3e92571a0c) | May 26, 2021 |
| Pegatron      | 2AE4                     | [604b735ad8](https://linux-hardware.org/?probe=604b735ad8) | May 02, 2021 |
| Intel         | D33217CK G76541-302      | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| ASUSTek       | PRIME A320M-K            | [48f003363a](https://linux-hardware.org/?probe=48f003363a) | Apr 09, 2021 |
| Dell          | 096JG8 A01               | [1cf6d1daea](https://linux-hardware.org/?probe=1cf6d1daea) | Apr 02, 2021 |
| Supermicro    | X9DAi                    | [ff94b1201c](https://linux-hardware.org/?probe=ff94b1201c) | Mar 31, 2021 |
| Unknown       | i845G-W83627HF           | [2ff9864ce6](https://linux-hardware.org/?probe=2ff9864ce6) | Mar 29, 2021 |
| Pegatron      | 2AE4                     | [8570b15385](https://linux-hardware.org/?probe=8570b15385) | Feb 14, 2021 |
| ASUSTek       | H110M-K                  | [34bf1da3fe](https://linux-hardware.org/?probe=34bf1da3fe) | Feb 13, 2021 |
| ASRock        | 970 Extreme3             | [48548effcd](https://linux-hardware.org/?probe=48548effcd) | Feb 13, 2021 |
| Gigabyte      | B250M-DS3H-CF            | [e0de5d87e6](https://linux-hardware.org/?probe=e0de5d87e6) | Feb 04, 2021 |
| Unknown       | i845G-W83627HF           | [6c9d42b55d](https://linux-hardware.org/?probe=6c9d42b55d) | Jan 08, 2021 |
| Unknown       | i845G-W83627HF           | [9ff8161bec](https://linux-hardware.org/?probe=9ff8161bec) | Jan 08, 2021 |
| Gigabyte      | Z170X-Gaming 7           | [6706c380ab](https://linux-hardware.org/?probe=6706c380ab) | Dec 21, 2020 |
| Gigabyte      | H110M-S2-CF              | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS     | [2d9e84acd0](https://linux-hardware.org/?probe=2d9e84acd0) | Dec 13, 2020 |
| Gigabyte      | GA-970A-D3               | [3c6c9b7bd3](https://linux-hardware.org/?probe=3c6c9b7bd3) | Dec 11, 2020 |
| ASUSTek       | PRIME H310M-E R2.0       | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Alienware     | 06G6JW A01               | [812527d15d](https://linux-hardware.org/?probe=812527d15d) | Dec 02, 2020 |
| Dell          | 042P49 A01               | [36ddd61132](https://linux-hardware.org/?probe=36ddd61132) | Aug 12, 2020 |
| Gigabyte      | H110M-H-CF               | [d8a8eb467a](https://linux-hardware.org/?probe=d8a8eb467a) | Aug 02, 2020 |
| Gateway       | FMCP7AM                  | [58e88b2df5](https://linux-hardware.org/?probe=58e88b2df5) | Jul 28, 2020 |
| ABIT          | AW9D-MAX                 | [fca26e4a11](https://linux-hardware.org/?probe=fca26e4a11) | Jul 21, 2020 |
| ASRock        | H81M-VG4 R2.0            | [c00d0feee3](https://linux-hardware.org/?probe=c00d0feee3) | Jul 21, 2020 |
| MSI           | 970 GAMING               | [73c5756fdd](https://linux-hardware.org/?probe=73c5756fdd) | Jul 01, 2020 |
| ASRock        | B450 Steel Legend        | [7d9ad3146b](https://linux-hardware.org/?probe=7d9ad3146b) | Jun 12, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS     | [b9c266ed55](https://linux-hardware.org/?probe=b9c266ed55) | May 20, 2020 |
| MSI           | B450 GAMING PLUS MAX     | [6252910769](https://linux-hardware.org/?probe=6252910769) | May 11, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0    | [8fc4603f6c](https://linux-hardware.org/?probe=8fc4603f6c) | May 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0    | [33cd43676f](https://linux-hardware.org/?probe=33cd43676f) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0    | [1a81d95494](https://linux-hardware.org/?probe=1a81d95494) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0    | [cd09b6b8a5](https://linux-hardware.org/?probe=cd09b6b8a5) | May 09, 2020 |
| ASRock        | 775i65GV                 | [0367c8a291](https://linux-hardware.org/?probe=0367c8a291) | Jan 07, 2020 |
| ASRock        | 775i65GV                 | [d0a8b9d7da](https://linux-hardware.org/?probe=d0a8b9d7da) | Dec 25, 2019 |
| Dell          | 042P49 A01               | [ce3194fcde](https://linux-hardware.org/?probe=ce3194fcde) | Oct 28, 2019 |
| Gigabyte      | GA-78LMT-S2              | [4ddf2bb220](https://linux-hardware.org/?probe=4ddf2bb220) | Oct 06, 2019 |
| Biostar       | H61MGV3                  | [911486bcc2](https://linux-hardware.org/?probe=911486bcc2) | Sep 08, 2019 |
| Biostar       | H61MGV3                  | [0b1e8f1f08](https://linux-hardware.org/?probe=0b1e8f1f08) | Jun 12, 2019 |
| Intel         | DG41WV AAE90316-103      | [7b2dc235f8](https://linux-hardware.org/?probe=7b2dc235f8) | May 18, 2019 |
| Lenovo        | SHARKBAY 31900003 STD    | [e7164fcda2](https://linux-hardware.org/?probe=e7164fcda2) | Dec 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| OpenMandriva 4.2    | 9        | 11.69%  |
| Ubuntu 20.04        | 8        | 10.39%  |
| Ubuntu 22.04        | 4        | 5.19%   |
| Ubuntu 18.04        | 3        | 3.9%    |
| OpenMandriva 4.3    | 3        | 3.9%    |
| Linux Mint 20.2     | 3        | 3.9%    |
| Pop!_OS 21.04       | 2        | 2.6%    |
| OpenMandriva 23.01  | 2        | 2.6%    |
| Lubuntu 22.04       | 2        | 2.6%    |
| Linux Mint 19.3     | 2        | 2.6%    |
| Fedora 32           | 2        | 2.6%    |
| Zorin 16            | 1        | 1.3%    |
| Zorin 15            | 1        | 1.3%    |
| Zorin 12            | 1        | 1.3%    |
| UbuntuDDE 20.04     | 1        | 1.3%    |
| Ubuntu 22.10        | 1        | 1.3%    |
| Ubuntu 20.10        | 1        | 1.3%    |
| Ubuntu 19.10        | 1        | 1.3%    |
| ROSA R8.1           | 1        | 1.3%    |
| ROSA R11.1          | 1        | 1.3%    |
| ROSA R11            | 1        | 1.3%    |
| Pop!_OS 20.10       | 1        | 1.3%    |
| Pop!_OS 20.04       | 1        | 1.3%    |
| OpenMandriva 4.50   | 1        | 1.3%    |
| OpenMandriva 23.03  | 1        | 1.3%    |
| OpenMandriva 22.12  | 1        | 1.3%    |
| Manjaro 22.0.4      | 1        | 1.3%    |
| Manjaro 22.0.0      | 1        | 1.3%    |
| Manjaro 21.3.5      | 1        | 1.3%    |
| Manjaro 21.2.5      | 1        | 1.3%    |
| Manjaro 21.2.0      | 1        | 1.3%    |
| Manjaro             | 1        | 1.3%    |
| Lubuntu 21.10       | 1        | 1.3%    |
| Lubuntu 20.04       | 1        | 1.3%    |
| Linux Mint 19.1     | 1        | 1.3%    |
| KDE neon 18.04      | 1        | 1.3%    |
| Fedora 37           | 1        | 1.3%    |
| Fedora 36           | 1        | 1.3%    |
| Fedora 34           | 1        | 1.3%    |
| EndeavourOS Rolling | 1        | 1.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 18       | 25%     |
| OpenMandriva | 16       | 22.22%  |
| Linux Mint   | 6        | 8.33%   |
| Manjaro      | 5        | 6.94%   |
| Fedora       | 5        | 6.94%   |
| Pop!_OS      | 4        | 5.56%   |
| Zorin        | 3        | 4.17%   |
| ROSA         | 2        | 2.78%   |
| Lubuntu      | 2        | 2.78%   |
| Elementary   | 2        | 2.78%   |
| Debian       | 2        | 2.78%   |
| Arch         | 2        | 2.78%   |
| UbuntuDDE    | 1        | 1.39%   |
| KDE neon     | 1        | 1.39%   |
| EndeavourOS  | 1        | 1.39%   |
| BlackPanther | 1        | 1.39%   |
| ArcoLinux    | 1        | 1.39%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.14-desktop-1omv4002    | 9        | 10.98%  |
| 5.4.0-70-generic            | 3        | 3.66%   |
| 5.16.7-desktop-1omv4003     | 3        | 3.66%   |
| 5.4.0-42-generic            | 2        | 2.44%   |
| 5.15.0-53-generic           | 2        | 2.44%   |
| 6.2.7-200.fc37.x86_64       | 1        | 1.22%   |
| 6.2.6-desktop-1omv2390      | 1        | 1.22%   |
| 6.1.4-desktop-1omv2301      | 1        | 1.22%   |
| 6.1.2-arch1-1               | 1        | 1.22%   |
| 6.1.1-desktop-1omv2290      | 1        | 1.22%   |
| 6.1.1-1-MANJARO             | 1        | 1.22%   |
| 6.1.0-custom                | 1        | 1.22%   |
| 6.0.2-2-MANJARO             | 1        | 1.22%   |
| 6.0.11-300.fc37.x86_64      | 1        | 1.22%   |
| 6.0.10-desktop-2omv22090    | 1        | 1.22%   |
| 5.9.9-arch1-1               | 1        | 1.22%   |
| 5.9.14-arch1-1              | 1        | 1.22%   |
| 5.8.0-7630-generic          | 1        | 1.22%   |
| 5.8.0-50-generic            | 1        | 1.22%   |
| 5.8.0-41-generic            | 1        | 1.22%   |
| 5.8.0-34-generic            | 1        | 1.22%   |
| 5.7.0-1-amd64               | 1        | 1.22%   |
| 5.6.19-300.fc32.x86_64      | 1        | 1.22%   |
| 5.6.16-300.fc32.x86_64      | 1        | 1.22%   |
| 5.6.14-desktop-2bP          | 1        | 1.22%   |
| 5.6.13-arch1-1              | 1        | 1.22%   |
| 5.4.40-generic-1rosa-x86_64 | 1        | 1.22%   |
| 5.4.0-91-generic            | 1        | 1.22%   |
| 5.4.0-88-generic            | 1        | 1.22%   |
| 5.4.0-60-generic            | 1        | 1.22%   |
| 5.4.0-56-generic            | 1        | 1.22%   |
| 5.4.0-52-generic            | 1        | 1.22%   |
| 5.4.0-29-generic            | 1        | 1.22%   |
| 5.4.0-26-generic            | 1        | 1.22%   |
| 5.3.0-62-generic            | 1        | 1.22%   |
| 5.3.0-51-generic            | 1        | 1.22%   |
| 5.19.0-29-generic           | 1        | 1.22%   |
| 5.18.13-200.fc36.x86_64     | 1        | 1.22%   |
| 5.18.12-3-MANJARO           | 1        | 1.22%   |
| 5.15.94-1-MANJARO           | 1        | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 11       | 13.75%  |
| 5.10.14  | 9        | 11.25%  |
| 5.15.0   | 8        | 10%     |
| 4.15.0   | 6        | 7.5%    |
| 5.8.0    | 4        | 5%      |
| 5.11.0   | 4        | 5%      |
| 5.16.7   | 3        | 3.75%   |
| 6.1.1    | 2        | 2.5%    |
| 5.3.0    | 2        | 2.5%    |
| 5.13.0   | 2        | 2.5%    |
| 6.2.7    | 1        | 1.25%   |
| 6.2.6    | 1        | 1.25%   |
| 6.1.4    | 1        | 1.25%   |
| 6.1.2    | 1        | 1.25%   |
| 6.1.0    | 1        | 1.25%   |
| 6.0.2    | 1        | 1.25%   |
| 6.0.11   | 1        | 1.25%   |
| 6.0.10   | 1        | 1.25%   |
| 5.9.9    | 1        | 1.25%   |
| 5.9.14   | 1        | 1.25%   |
| 5.7.0    | 1        | 1.25%   |
| 5.6.19   | 1        | 1.25%   |
| 5.6.16   | 1        | 1.25%   |
| 5.6.14   | 1        | 1.25%   |
| 5.6.13   | 1        | 1.25%   |
| 5.4.40   | 1        | 1.25%   |
| 5.19.0   | 1        | 1.25%   |
| 5.18.13  | 1        | 1.25%   |
| 5.18.12  | 1        | 1.25%   |
| 5.15.94  | 1        | 1.25%   |
| 5.15.11  | 1        | 1.25%   |
| 5.14.14  | 1        | 1.25%   |
| 5.13.9   | 1        | 1.25%   |
| 5.11.11  | 1        | 1.25%   |
| 5.10.94  | 1        | 1.25%   |
| 5.10.105 | 1        | 1.25%   |
| 5.10.0   | 1        | 1.25%   |
| 4.18.0   | 1        | 1.25%   |
| 4.1.38   | 1        | 1.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 15%     |
| 5.10    | 12       | 15%     |
| 5.15    | 10       | 12.5%   |
| 4.15    | 6        | 7.5%    |
| 6.1     | 5        | 6.25%   |
| 5.11    | 5        | 6.25%   |
| 5.8     | 4        | 5%      |
| 5.6     | 4        | 5%      |
| 6.0     | 3        | 3.75%   |
| 5.16    | 3        | 3.75%   |
| 5.13    | 3        | 3.75%   |
| 6.2     | 2        | 2.5%    |
| 5.9     | 2        | 2.5%    |
| 5.3     | 2        | 2.5%    |
| 5.18    | 2        | 2.5%    |
| 5.7     | 1        | 1.25%   |
| 5.19    | 1        | 1.25%   |
| 5.14    | 1        | 1.25%   |
| 4.18    | 1        | 1.25%   |
| 4.1     | 1        | 1.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 64       | 95.52%  |
| i686   | 3        | 4.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 31       | 44.93%  |
| KDE5          | 18       | 26.09%  |
| Unknown       | 6        | 8.7%    |
| X-Cinnamon    | 4        | 5.8%    |
| Pantheon      | 2        | 2.9%    |
| MATE          | 2        | 2.9%    |
| LXQt          | 2        | 2.9%    |
| XFCE          | 1        | 1.45%   |
| KDE           | 1        | 1.45%   |
| GNOME Classic | 1        | 1.45%   |
| Deepin        | 1        | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 54       | 79.41%  |
| Wayland | 13       | 19.12%  |
| Tty     | 1        | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 47.89%  |
| SDDM    | 20       | 28.17%  |
| GDM     | 9        | 12.68%  |
| GDM3    | 5        | 7.04%   |
| TDM     | 2        | 2.82%   |
| LightDM | 1        | 1.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 33       | 46.48%  |
| es_CR   | 27       | 38.03%  |
| Unknown | 5        | 7.04%   |
| es_ES   | 4        | 5.63%   |
| es_MX   | 1        | 1.41%   |
| de_DE   | 1        | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 36       | 52.94%  |
| BIOS | 32       | 47.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 46       | 66.67%  |
| Overlay | 13       | 18.84%  |
| Btrfs   | 7        | 10.14%  |
| Xfs     | 1        | 1.45%   |
| Tmpfs   | 1        | 1.45%   |
| Unknown | 1        | 1.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 36       | 50.7%   |
| GPT     | 29       | 40.85%  |
| MBR     | 6        | 8.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 80.88%  |
| Yes       | 13       | 19.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 58.82%  |
| Yes       | 28       | 41.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 13       | 19.4%   |
| Gigabyte Technology | 12       | 17.91%  |
| Dell                | 12       | 17.91%  |
| ASRock              | 7        | 10.45%  |
| MSI                 | 6        | 8.96%   |
| Hewlett-Packard     | 3        | 4.48%   |
| Intel               | 2        | 2.99%   |
| Unknown             | 2        | 2.99%   |
| ZOTAC               | 1        | 1.49%   |
| TPV-INVENTA         | 1        | 1.49%   |
| Supermicro          | 1        | 1.49%   |
| Pegatron            | 1        | 1.49%   |
| MACHINIST           | 1        | 1.49%   |
| Lenovo              | 1        | 1.49%   |
| Gateway             | 1        | 1.49%   |
| Biostar             | 1        | 1.49%   |
| Alienware           | 1        | 1.49%   |
| ABIT                | 1        | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Dell OptiPlex 3020                       | 5        | 7.46%   |
| Gigabyte B250M-DS3H                      | 2        | 2.99%   |
| Dell OptiPlex 7040                       | 2        | 2.99%   |
| ASUS TUF Gaming X570-PLUS                | 2        | 2.99%   |
| ASUS PRIME A320M-K                       | 2        | 2.99%   |
| ASRock B450 Steel Legend                 | 2        | 2.99%   |
| Unknown                                  | 2        | 2.99%   |
| ZOTAC NM10                               | 1        | 1.49%   |
| TPV-INVENTA 18-2003LA                    | 1        | 1.49%   |
| Supermicro X9DAi                         | 1        | 1.49%   |
| Pegatron CQ2728LA                        | 1        | 1.49%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1        | 1.49%   |
| MSI MS-7D77                              | 1        | 1.49%   |
| MSI MS-7B86                              | 1        | 1.49%   |
| MSI MS-7992                              | 1        | 1.49%   |
| MSI MS-7693                              | 1        | 1.49%   |
| MSI MS-7636                              | 1        | 1.49%   |
| MACHINIST X79 V2.82H                     | 1        | 1.49%   |
| Lenovo H530S 10132                       | 1        | 1.49%   |
| Intel DG41WV AAE90316-103                | 1        | 1.49%   |
| Intel D33217CK G76541-302                | 1        | 1.49%   |
| HP Z800 Workstation                      | 1        | 1.49%   |
| HP ProDesk 600 G4 SFF                    | 1        | 1.49%   |
| HP EliteDesk 800 G1 TWR                  | 1        | 1.49%   |
| Gigabyte Z690 UD AX DDR4                 | 1        | 1.49%   |
| Gigabyte Z170X-Gaming 7                  | 1        | 1.49%   |
| Gigabyte X570 I AORUS PRO WIFI           | 1        | 1.49%   |
| Gigabyte H81M-DS2                        | 1        | 1.49%   |
| Gigabyte H410M H                         | 1        | 1.49%   |
| Gigabyte H110M-S2                        | 1        | 1.49%   |
| Gigabyte H110M-H                         | 1        | 1.49%   |
| Gigabyte GA-970A-D3                      | 1        | 1.49%   |
| Gigabyte GA-78LMT-USB3 6.0               | 1        | 1.49%   |
| Gigabyte B150-HD3                        | 1        | 1.49%   |
| Gateway LX6810-01                        | 1        | 1.49%   |
| Dell Precision WorkStation T5400         | 1        | 1.49%   |
| Dell Precision WorkStation T3500         | 1        | 1.49%   |
| Dell OptiPlex 790                        | 1        | 1.49%   |
| Dell OptiPlex 755                        | 1        | 1.49%   |
| Dell OptiPlex 3010                       | 1        | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 10       | 14.93%  |
| ASUS PRIME             | 4        | 5.97%   |
| ASUS TUF               | 3        | 4.48%   |
| Gigabyte B250M-DS3H    | 2        | 2.99%   |
| Dell Precision         | 2        | 2.99%   |
| ASRock B450            | 2        | 2.99%   |
| Unknown                | 2        | 2.99%   |
| ZOTAC NM10             | 1        | 1.49%   |
| TPV-INVENTA 18-2003LA  | 1        | 1.49%   |
| Supermicro X9DAi       | 1        | 1.49%   |
| Pegatron CQ2728LA      | 1        | 1.49%   |
| MSI Z390               | 1        | 1.49%   |
| MSI MS-7D77            | 1        | 1.49%   |
| MSI MS-7B86            | 1        | 1.49%   |
| MSI MS-7992            | 1        | 1.49%   |
| MSI MS-7693            | 1        | 1.49%   |
| MSI MS-7636            | 1        | 1.49%   |
| MACHINIST X79          | 1        | 1.49%   |
| Lenovo H530S           | 1        | 1.49%   |
| Intel DG41WV           | 1        | 1.49%   |
| Intel D33217CK         | 1        | 1.49%   |
| HP Z800                | 1        | 1.49%   |
| HP ProDesk             | 1        | 1.49%   |
| HP EliteDesk           | 1        | 1.49%   |
| Gigabyte Z690          | 1        | 1.49%   |
| Gigabyte Z170X-Gaming  | 1        | 1.49%   |
| Gigabyte X570          | 1        | 1.49%   |
| Gigabyte H81M-DS2      | 1        | 1.49%   |
| Gigabyte H410M         | 1        | 1.49%   |
| Gigabyte H110M-S2      | 1        | 1.49%   |
| Gigabyte H110M-H       | 1        | 1.49%   |
| Gigabyte GA-970A-D3    | 1        | 1.49%   |
| Gigabyte GA-78LMT-USB3 | 1        | 1.49%   |
| Gigabyte B150-HD3      | 1        | 1.49%   |
| Gateway LX6810-01      | 1        | 1.49%   |
| Biostar H61MGV3        | 1        | 1.49%   |
| ASUS STRIX             | 1        | 1.49%   |
| ASUS SABERTOOTH        | 1        | 1.49%   |
| ASUS ROG               | 1        | 1.49%   |
| ASUS PRO               | 1        | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 9        | 13.43%  |
| 2016 | 8        | 11.94%  |
| 2014 | 8        | 11.94%  |
| 2013 | 6        | 8.96%   |
| 2012 | 6        | 8.96%   |
| 2017 | 5        | 7.46%   |
| 2010 | 4        | 5.97%   |
| 2021 | 3        | 4.48%   |
| 2020 | 3        | 4.48%   |
| 2011 | 3        | 4.48%   |
| 2008 | 3        | 4.48%   |
| 2022 | 2        | 2.99%   |
| 2018 | 2        | 2.99%   |
| 2005 | 2        | 2.99%   |
| 2015 | 1        | 1.49%   |
| 2009 | 1        | 1.49%   |
| 2007 | 1        | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 67       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 62       | 92.54%  |
| Enabled  | 5        | 7.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 67       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 20       | 29.41%  |
| 8.01-16.0       | 14       | 20.59%  |
| 3.01-4.0        | 11       | 16.18%  |
| 32.01-64.0      | 8        | 11.76%  |
| 4.01-8.0        | 6        | 8.82%   |
| 1.01-2.0        | 5        | 7.35%   |
| More than 256.0 | 1        | 1.47%   |
| 24.01-32.0      | 1        | 1.47%   |
| 2.01-3.0        | 1        | 1.47%   |
| 64.01-256.0     | 1        | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 29       | 38.67%  |
| 2.01-3.0   | 15       | 20%     |
| 4.01-8.0   | 12       | 16%     |
| 3.01-4.0   | 7        | 9.33%   |
| 0.51-1.0   | 4        | 5.33%   |
| 0.01-0.5   | 3        | 4%      |
| 16.01-24.0 | 2        | 2.67%   |
| 8.01-16.0  | 2        | 2.67%   |
| 24.01-32.0 | 1        | 1.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 50.72%  |
| 2      | 18       | 26.09%  |
| 4      | 7        | 10.14%  |
| 3      | 6        | 8.7%    |
| 8      | 1        | 1.45%   |
| 7      | 1        | 1.45%   |
| 5      | 1        | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 52.17%  |
| Yes       | 33       | 47.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 66       | 98.51%  |
| No        | 1        | 1.49%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 58.82%  |
| Yes       | 28       | 41.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 72.86%  |
| Yes       | 19       | 27.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Costa Rica | 67       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| San José   | 29       | 39.73%  |
| Heredia     | 17       | 23.29%  |
| Escazu      | 5        | 6.85%   |
| Alajuela    | 4        | 5.48%   |
| Santa Ana   | 2        | 2.74%   |
| Liberia     | 2        | 2.74%   |
| Cartago     | 2        | 2.74%   |
| Tres Rios   | 1        | 1.37%   |
| Tibas       | 1        | 1.37%   |
| Santa Fe    | 1        | 1.37%   |
| San Pedro   | 1        | 1.37%   |
| Rio Segundo | 1        | 1.37%   |
| Pavas       | 1        | 1.37%   |
| Palmares    | 1        | 1.37%   |
| Nosara      | 1        | 1.37%   |
| Grecia      | 1        | 1.37%   |
| Curridabat  | 1        | 1.37%   |
| Bajo Perez  | 1        | 1.37%   |
| Alajuelita  | 1        | 1.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 25       | 42     | 21.93%  |
| WDC                   | 17       | 23     | 14.91%  |
| Kingston              | 11       | 17     | 9.65%   |
| A-DATA Technology     | 10       | 10     | 8.77%   |
| Toshiba               | 9        | 10     | 7.89%   |
| Samsung Electronics   | 6        | 11     | 5.26%   |
| Hitachi               | 5        | 7      | 4.39%   |
| XPG                   | 4        | 4      | 3.51%   |
| Realtek Semiconductor | 3        | 5      | 2.63%   |
| Patriot               | 3        | 4      | 2.63%   |
| HGST                  | 3        | 3      | 2.63%   |
| ZOTAC                 | 2        | 3      | 1.75%   |
| SanDisk               | 2        | 3      | 1.75%   |
| Maxtor                | 2        | 2      | 1.75%   |
| Crucial               | 2        | 2      | 1.75%   |
| WD MediaMax           | 1        | 1      | 0.88%   |
| Unknown               | 1        | 1      | 0.88%   |
| T-FORCE               | 1        | 1      | 0.88%   |
| Phison Electronics    | 1        | 1      | 0.88%   |
| Netac                 | 1        | 1      | 0.88%   |
| JMicron Technology    | 1        | 1      | 0.88%   |
| Intel                 | 1        | 1      | 0.88%   |
| Gigabyte Technology   | 1        | 2      | 0.88%   |
| CT120BX5              | 1        | 1      | 0.88%   |
| ADATA Technology      | 1        | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB           | 5        | 4%      |
| Kingston SA400S37240G 240GB SSD  | 5        | 4%      |
| A-DATA SU630 480GB SSD           | 5        | 4%      |
| WDC WD10EZEX-75WN4A1 1TB         | 3        | 2.4%    |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 2.4%    |
| XPG GAMMIX S11 Pro 256GB         | 2        | 1.6%    |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.6%    |
| Seagate ST8000DM004-2CX188 8TB   | 2        | 1.6%    |
| Seagate ST500DM002-1BD142 500GB  | 2        | 1.6%    |
| Seagate ST380815AS 80GB          | 2        | 1.6%    |
| HGST HTS541075A9E680 752GB       | 2        | 1.6%    |
| ZOTAC ZTSSD-S11-240G-P 240GB     | 1        | 0.8%    |
| ZOTAC ZTSSD-S11-120G-MD 120GB    | 1        | 0.8%    |
| XPG NVMe SSD Drive 512GB         | 1        | 0.8%    |
| XPG NVMe SSD Drive 1TB           | 1        | 0.8%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.8%    |
| WDC WD6400AAKS-22A7B0 640GB      | 1        | 0.8%    |
| WDC WD5000LPCX-60VHAT0 500GB     | 1        | 0.8%    |
| WDC WD5000AAKS-00V1A0 500GB      | 1        | 0.8%    |
| WDC WD2500AAJS-00VTA0 250GB      | 1        | 0.8%    |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.8%    |
| WDC WD1600BEVS-26VAT0 160GB      | 1        | 0.8%    |
| WDC WD1500HLFS-01G6U0 150GB      | 1        | 0.8%    |
| WDC WD10SPZX-24Z10T0 1TB         | 1        | 0.8%    |
| WDC WD10JPVX-00JC3T0 1TB         | 1        | 0.8%    |
| WDC WD10EZEX-60ZF5A0 1TB         | 1        | 0.8%    |
| WDC WD10EZEX-60WN4A0 1TB         | 1        | 0.8%    |
| WDC WD10EZEX-08M2NA0 1TB         | 1        | 0.8%    |
| WD MediaMax WL3000GSA6472 3TB    | 1        | 0.8%    |
| Unknown MB3000EBKAB 3TB          | 1        | 0.8%    |
| Toshiba THNSN5512GPUK NVMe 512GB | 1        | 0.8%    |
| Toshiba RD400 256GB              | 1        | 0.8%    |
| Toshiba MQ01ABD100 1TB           | 1        | 0.8%    |
| Toshiba HDWD105 500GB            | 1        | 0.8%    |
| T-FORCE 2TB                      | 1        | 0.8%    |
| Seagate ST9160412AS 160GB        | 1        | 0.8%    |
| Seagate ST9160301AS 160GB        | 1        | 0.8%    |
| Seagate ST8000DM005-2EH112 8TB   | 1        | 0.8%    |
| Seagate ST6000VN0033-2EE110 6TB  | 1        | 0.8%    |
| Seagate ST500LT012-1DG142 500GB  | 1        | 0.8%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 41     | 40%     |
| WDC                 | 17       | 21     | 28.33%  |
| Toshiba             | 7        | 8      | 11.67%  |
| Hitachi             | 5        | 7      | 8.33%   |
| HGST                | 3        | 3      | 5%      |
| Maxtor              | 2        | 2      | 3.33%   |
| Unknown             | 1        | 1      | 1.67%   |
| Samsung Electronics | 1        | 1      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 10       | 15     | 31.25%  |
| A-DATA Technology   | 8        | 8      | 25%     |
| ZOTAC               | 2        | 3      | 6.25%   |
| SanDisk             | 2        | 3      | 6.25%   |
| Samsung Electronics | 2        | 5      | 6.25%   |
| Patriot             | 2        | 3      | 6.25%   |
| WDC                 | 1        | 2      | 3.13%   |
| JMicron Technology  | 1        | 1      | 3.13%   |
| Intel               | 1        | 1      | 3.13%   |
| Gigabyte Technology | 1        | 2      | 3.13%   |
| CT120BX5            | 1        | 1      | 3.13%   |
| Crucial             | 1        | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 48       | 84     | 50.53%  |
| SSD     | 28       | 45     | 29.47%  |
| NVMe    | 17       | 25     | 17.89%  |
| Unknown | 2        | 3      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 64       | 122    | 74.42%  |
| NVMe | 17       | 25     | 19.77%  |
| SAS  | 5        | 10     | 5.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 77     | 57.14%  |
| 0.51-1.0   | 26       | 33     | 30.95%  |
| 4.01-10.0  | 5        | 13     | 5.95%   |
| 1.01-2.0   | 3        | 4      | 3.57%   |
| 3.01-4.0   | 1        | 1      | 1.19%   |
| 2.01-3.0   | 1        | 1      | 1.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 15       | 20.55%  |
| 101-250        | 13       | 17.81%  |
| 251-500        | 10       | 13.7%   |
| 1-20           | 10       | 13.7%   |
| 1001-2000      | 7        | 9.59%   |
| 51-100         | 7        | 9.59%   |
| More than 3000 | 6        | 8.22%   |
| 2001-3000      | 2        | 2.74%   |
| Unknown        | 2        | 2.74%   |
| 21-50          | 1        | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 32       | 42.11%  |
| 21-50          | 11       | 14.47%  |
| 251-500        | 7        | 9.21%   |
| 101-250        | 7        | 9.21%   |
| More than 3000 | 4        | 5.26%   |
| 501-1000       | 4        | 5.26%   |
| 51-100         | 4        | 5.26%   |
| 1001-2000      | 3        | 3.95%   |
| 2001-3000      | 2        | 2.63%   |
| Unknown        | 2        | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST9160412AS 160GB           | 1        | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB     | 1        | 1      | 11.11%  |
| Seagate ST500DM002-1BD142 500GB     | 1        | 2      | 11.11%  |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1      | 11.11%  |
| SanDisk SD6SB1M-128G-1006 128GB SSD | 1        | 2      | 11.11%  |
| Maxtor STM3160215AS 160GB           | 1        | 1      | 11.11%  |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1      | 11.11%  |
| Hitachi HDE721010SLA330 1TB         | 1        | 1      | 11.11%  |
| A-DATA Technology SX8100NP 256GB    | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 4        | 5      | 44.44%  |
| SanDisk           | 1        | 2      | 11.11%  |
| Maxtor            | 1        | 1      | 11.11%  |
| Kingston          | 1        | 1      | 11.11%  |
| Hitachi           | 1        | 1      | 11.11%  |
| A-DATA Technology | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 66.67%  |
| Maxtor  | 1        | 1      | 16.67%  |
| Hitachi | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 7      | 62.5%   |
| SSD  | 2        | 3      | 25%     |
| NVMe | 1        | 1      | 12.5%   |

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
| Detected | 42       | 83     | 55.26%  |
| Works    | 27       | 63     | 35.53%  |
| Malfunc  | 7        | 11     | 9.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 45       | 47.37%  |
| AMD                          | 20       | 21.05%  |
| ASMedia Technology           | 5        | 5.26%   |
| ADATA Technology             | 5        | 5.26%   |
| Realtek Semiconductor        | 4        | 4.21%   |
| Samsung Electronics          | 3        | 3.16%   |
| Nvidia                       | 2        | 2.11%   |
| Toshiba America Info Systems | 1        | 1.05%   |
| Silicon Motion               | 1        | 1.05%   |
| Silicon Image                | 1        | 1.05%   |
| Phison Electronics           | 1        | 1.05%   |
| OCZ Technology Group         | 1        | 1.05%   |
| Micron/Crucial Technology    | 1        | 1.05%   |
| Marvell Technology Group     | 1        | 1.05%   |
| LSI Logic / Symbios Logic    | 1        | 1.05%   |
| Kingston Technology Company  | 1        | 1.05%   |
| JMicron Technology           | 1        | 1.05%   |
| INNOGRIT                     | 1        | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10       | 9.35%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9        | 8.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6        | 5.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6        | 5.61%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 4.67%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 5        | 4.67%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 3.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 3.74%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 3        | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.8%    |
| AMD FCH SATA Controller D                                                      | 3        | 2.8%    |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 2.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.87%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 1.87%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 1.87%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.87%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 0.93%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.93%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 0.93%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.93%   |
| Realtek NVMe Controller                                                        | 1        | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 0.93%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 0.93%   |
| Nvidia MCP79 RAID Controller                                                   | 1        | 0.93%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.93%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.93%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 0.93%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.93%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                   | 1        | 0.93%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 1        | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                        | 1        | 0.93%   |
| JMicron JMB368 IDE controller                                                  | 1        | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.93%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 0.93%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 56       | 60.87%  |
| NVMe | 17       | 18.48%  |
| IDE  | 11       | 11.96%  |
| RAID | 6        | 6.52%   |
| SAS  | 1        | 1.09%   |
| SCSI | 1        | 1.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 46       | 68.66%  |
| AMD    | 21       | 31.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 7.46%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 5.97%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 2.99%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 2.99%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 2.99%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 2.99%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 2.99%   |
| Intel Xeon CPU X5667 @ 3.07GHz              | 1        | 1.49%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 1.49%   |
| Intel Xeon CPU E5405 @ 2.00GHz              | 1        | 1.49%   |
| Intel Xeon CPU E5-2660 v2 @ 2.20GHz         | 1        | 1.49%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 1.49%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.49%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 1.49%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1.49%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1        | 1.49%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 1.49%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.49%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.49%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.49%   |
| Intel Core i7-2700K CPU @ 3.50GHz           | 1        | 1.49%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 1.49%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.49%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 1.49%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 1.49%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.49%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.49%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.49%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.49%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.49%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.49%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1        | 1.49%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.49%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.49%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 1        | 1.49%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.49%   |
| Intel Celeron CPU 2.66GHz                   | 1        | 1.49%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 1.49%   |
| Intel 12th Gen Core i5-12600K               | 1        | 1.49%   |
| Intel 12th Gen Core i5-12400                | 1        | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 17       | 25.37%  |
| Intel Core i3           | 7        | 10.45%  |
| AMD Ryzen 5             | 6        | 8.96%   |
| Intel Xeon              | 5        | 7.46%   |
| AMD FX                  | 5        | 7.46%   |
| Intel Core i7           | 4        | 5.97%   |
| AMD Ryzen 7             | 3        | 4.48%   |
| Other                   | 2        | 2.99%   |
| Intel Pentium           | 2        | 2.99%   |
| Intel Celeron           | 2        | 2.99%   |
| AMD Ryzen 3             | 2        | 2.99%   |
| Intel Pentium Dual-Core | 1        | 1.49%   |
| Intel Pentium 4         | 1        | 1.49%   |
| Intel Core i9           | 1        | 1.49%   |
| Intel Core 2 Quad       | 1        | 1.49%   |
| Intel Core 2 Duo        | 1        | 1.49%   |
| Intel Core 2            | 1        | 1.49%   |
| Intel Atom              | 1        | 1.49%   |
| AMD Sempron             | 1        | 1.49%   |
| AMD Ryzen 7 PRO         | 1        | 1.49%   |
| AMD Phenom II X4        | 1        | 1.49%   |
| AMD E2                  | 1        | 1.49%   |
| AMD E1                  | 1        | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 32       | 47.76%  |
| 2      | 12       | 17.91%  |
| 6      | 9        | 13.43%  |
| 8      | 7        | 10.45%  |
| 1      | 4        | 5.97%   |
| 20     | 1        | 1.49%   |
| 10     | 1        | 1.49%   |
| 3      | 1        | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 65       | 97.01%  |
| 2      | 2        | 2.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 37       | 55.22%  |
| 2      | 30       | 44.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 65       | 97.01%  |
| 32-bit         | 1        | 1.49%   |
| Unknown        | 1        | 1.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 18.57%  |
| 0x306c3    | 8        | 11.43%  |
| 0x906e9    | 4        | 5.71%   |
| 0x306a9    | 4        | 5.71%   |
| 0x08701021 | 4        | 5.71%   |
| 0x506e3    | 3        | 4.29%   |
| 0x906eb    | 2        | 2.86%   |
| 0x306e4    | 2        | 2.86%   |
| 0x10676    | 2        | 2.86%   |
| 0x06000852 | 2        | 2.86%   |
| 0x05000119 | 2        | 2.86%   |
| 0xf49      | 1        | 1.43%   |
| 0xf29      | 1        | 1.43%   |
| 0x906ec    | 1        | 1.43%   |
| 0x906ea    | 1        | 1.43%   |
| 0x90675    | 1        | 1.43%   |
| 0x90672    | 1        | 1.43%   |
| 0x706a8    | 1        | 1.43%   |
| 0x6f6      | 1        | 1.43%   |
| 0x106e5    | 1        | 1.43%   |
| 0x106ca    | 1        | 1.43%   |
| 0x106a5    | 1        | 1.43%   |
| 0x10677    | 1        | 1.43%   |
| 0x0a601201 | 1        | 1.43%   |
| 0x08701011 | 1        | 1.43%   |
| 0x0870100a | 1        | 1.43%   |
| 0x08600106 | 1        | 1.43%   |
| 0x08108109 | 1        | 1.43%   |
| 0x08101016 | 1        | 1.43%   |
| 0x0800820d | 1        | 1.43%   |
| 0x06000822 | 1        | 1.43%   |
| 0x0500010d | 1        | 1.43%   |
| 0x010000c8 | 1        | 1.43%   |
| 0x010000c7 | 1        | 1.43%   |
| 0x00000000 | 1        | 1.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 10       | 14.93%  |
| KabyLake         | 9        | 13.43%  |
| Zen 2            | 6        | 8.96%   |
| IvyBridge        | 6        | 8.96%   |
| Skylake          | 5        | 7.46%   |
| Piledriver       | 4        | 5.97%   |
| Penryn           | 4        | 5.97%   |
| Zen+             | 2        | 2.99%   |
| Zen 3            | 2        | 2.99%   |
| NetBurst         | 2        | 2.99%   |
| Nehalem          | 2        | 2.99%   |
| K10              | 2        | 2.99%   |
| Bobcat           | 2        | 2.99%   |
| Unknown          | 2        | 2.99%   |
| Zen              | 1        | 1.49%   |
| Westmere         | 1        | 1.49%   |
| SandyBridge      | 1        | 1.49%   |
| Goldmont plus    | 1        | 1.49%   |
| Core             | 1        | 1.49%   |
| CometLake        | 1        | 1.49%   |
| Bulldozer        | 1        | 1.49%   |
| Bonnell          | 1        | 1.49%   |
| Alderlake Hybrid | 1        | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 28       | 37.84%  |
| Intel  | 27       | 36.49%  |
| AMD    | 19       | 25.68%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 10.39%  |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 5.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 5.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.9%    |
| Intel HD Graphics 630                                                       | 3        | 3.9%    |
| Intel HD Graphics 530                                                       | 3        | 3.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.9%    |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 2        | 2.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.6%    |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 2.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.6%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 2.6%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.3%    |
| Nvidia TU106 [GeForce RTX 2060 12GB]                                        | 1        | 1.3%    |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.3%    |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                        | 1        | 1.3%    |
| Nvidia GT218 [ION]                                                          | 1        | 1.3%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.3%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.3%    |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 1.3%    |
| Nvidia GK106 [GeForce GTX 645 OEM]                                          | 1        | 1.3%    |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.3%    |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.3%    |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.3%    |
| Nvidia G96C [GeForce GT 120]                                                | 1        | 1.3%    |
| Nvidia G71GL [Quadro FX 3500]                                               | 1        | 1.3%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.3%    |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.3%    |
| Intel 82865G Integrated Graphics Controller                                 | 1        | 1.3%    |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device          | 1        | 1.3%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 1.3%    |
| AMD Wrestler [Radeon HD 7340]                                               | 1        | 1.3%    |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.3%    |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.3%    |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 1        | 1.3%    |
| AMD RV530LE [Radeon X1600/X1650 PRO]                                        | 1        | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 26       | 37.14%  |
| 1 x Intel      | 24       | 34.29%  |
| 1 x AMD        | 14       | 20%     |
| 2 x AMD        | 3        | 4.29%   |
| AMD + Nvidia   | 2        | 2.86%   |
| Intel + Nvidia | 1        | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 54       | 78.26%  |
| Proprietary | 14       | 20.29%  |
| Unknown     | 1        | 1.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 38.89%  |
| 1.01-2.0   | 12       | 16.67%  |
| 0.51-1.0   | 8        | 11.11%  |
| 3.01-4.0   | 7        | 9.72%   |
| 0.01-0.5   | 7        | 9.72%   |
| 5.01-6.0   | 5        | 6.94%   |
| 7.01-8.0   | 4        | 5.56%   |
| 8.01-16.0  | 1        | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| AOC                  | 18       | 23.68%  |
| Hewlett-Packard      | 12       | 15.79%  |
| Dell                 | 9        | 11.84%  |
| Goldstar             | 6        | 7.89%   |
| ViewSonic            | 4        | 5.26%   |
| Acer                 | 4        | 5.26%   |
| Samsung Electronics  | 3        | 3.95%   |
| BenQ                 | 3        | 3.95%   |
| Sony                 | 2        | 2.63%   |
| Ancor Communications | 2        | 2.63%   |
| AGO                  | 2        | 2.63%   |
| Xerox                | 1        | 1.32%   |
| Unknown (XXX)        | 1        | 1.32%   |
| Royal Information    | 1        | 1.32%   |
| Philips              | 1        | 1.32%   |
| Panasonic            | 1        | 1.32%   |
| MSI                  | 1        | 1.32%   |
| LTM                  | 1        | 1.32%   |
| Lenovo               | 1        | 1.32%   |
| Haier                | 1        | 1.32%   |
| ASRock               | 1        | 1.32%   |
| ASR                  | 1        | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5        | 6.02%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2        | 2.41%   |
| Hewlett-Packard LCD Monitor E232 2944x1080                           | 2        | 2.41%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2        | 2.41%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                  | 2        | 2.41%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 2        | 2.41%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 2        | 2.41%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1        | 1.2%    |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1        | 1.2%    |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1        | 1.2%    |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1        | 1.2%    |
| ViewSonic LCD Monitor VX2260WM                                       | 1        | 1.2%    |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 1.2%    |
| Sony TV SNY1B02 1360x768                                             | 1        | 1.2%    |
| Sony TV SNY0902 1360x768                                             | 1        | 1.2%    |
| Samsung Electronics S24A31x SAM7115 1920x1080 527x296mm 23.8-inch    | 1        | 1.2%    |
| Royal Information Monitor TRL1012 1280x1024 320x240mm 15.7-inch      | 1        | 1.2%    |
| Philips LCD Monitor 170B4 1280x1024                                  | 1        | 1.2%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                   | 1        | 1.2%    |
| MSI MAG271CQR MSI3FA7 2560x1440 597x336mm 27.0-inch                  | 1        | 1.2%    |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                    | 1        | 1.2%    |
| Lenovo LEN LS1922wA LEN0A14 1366x768 410x230mm 18.5-inch             | 1        | 1.2%    |
| Hewlett-Packard V202 HWP330B 1600x900 452x263mm 20.6-inch            | 1        | 1.2%    |
| Hewlett-Packard V193 HWP3178 1366x768 410x230mm 18.5-inch            | 1        | 1.2%    |
| Hewlett-Packard P223a HPN3391 1920x1080 477x268mm 21.5-inch          | 1        | 1.2%    |
| Hewlett-Packard LCD Monitor L1908w 1440x900                          | 1        | 1.2%    |
| Hewlett-Packard LCD Monitor Compaq W185q 3286x1080                   | 1        | 1.2%    |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch         | 1        | 1.2%    |
| Hewlett-Packard L1910 HWP26E6 1280x1024 380x300mm 19.1-inch          | 1        | 1.2%    |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch           | 1        | 1.2%    |
| Hewlett-Packard E221c HWP3093 1920x1080 497x292mm 22.7-inch          | 1        | 1.2%    |
| Hewlett-Packard Compaq W1952a HWP3010 1366x768 410x230mm 18.5-inch   | 1        | 1.2%    |
| Hewlett-Packard All in One HWP410E 1366x768 410x230mm 18.5-inch      | 1        | 1.2%    |
| Haier SMART TV HRE0030 3840x2160 708x398mm 32.0-inch                 | 1        | 1.2%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 1        | 1.2%    |
| Goldstar MP59G GSM5B33 1920x1080 480x270mm 21.7-inch                 | 1        | 1.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 1        | 1.2%    |
| Goldstar HDR WFHD GSM5B9F 2560x1080 798x334mm 34.1-inch              | 1        | 1.2%    |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                | 1        | 1.2%    |
| Goldstar FULL HD GSM5B9E 1920x1080 600x340mm 27.2-inch               | 1        | 1.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 30       | 40%     |
| 1366x768 (WXGA)   | 8        | 10.67%  |
| 1280x1024 (SXGA)  | 7        | 9.33%   |
| 1440x900 (WXGA+)  | 6        | 8%      |
| 1600x900 (HD+)    | 5        | 6.67%   |
| 3840x2160 (4K)    | 4        | 5.33%   |
| 3286x1080         | 2        | 2.67%   |
| 2944x1080         | 2        | 2.67%   |
| 2560x1440 (QHD)   | 2        | 2.67%   |
| 2560x1080         | 2        | 2.67%   |
| 1280x720 (HD)     | 2        | 2.67%   |
| Unknown           | 2        | 2.67%   |
| 1920x1200 (WUXGA) | 1        | 1.33%   |
| 1360x768          | 1        | 1.33%   |
| 1280x960          | 1        | 1.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 10       | 12.99%  |
| 19      | 10       | 12.99%  |
| 24      | 9        | 11.69%  |
| Unknown | 9        | 11.69%  |
| 18      | 7        | 9.09%   |
| 21      | 6        | 7.79%   |
| 17      | 5        | 6.49%   |
| 27      | 4        | 5.19%   |
| 72      | 2        | 2.6%    |
| 43      | 2        | 2.6%    |
| 34      | 2        | 2.6%    |
| 15      | 2        | 2.6%    |
| 12      | 2        | 2.6%    |
| 84      | 1        | 1.3%    |
| 54      | 1        | 1.3%    |
| 40      | 1        | 1.3%    |
| 36      | 1        | 1.3%    |
| 32      | 1        | 1.3%    |
| 22      | 1        | 1.3%    |
| 20      | 1        | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 29.33%  |
| 401-500     | 22       | 29.33%  |
| Unknown     | 9        | 12%     |
| 301-350     | 6        | 8%      |
| 701-800     | 4        | 5.33%   |
| 351-400     | 3        | 4%      |
| 1501-2000   | 3        | 4%      |
| 201-300     | 2        | 2.67%   |
| 901-1000    | 2        | 2.67%   |
| 801-900     | 1        | 1.33%   |
| 1001-1500   | 1        | 1.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 42       | 60.87%  |
| Unknown | 9        | 13.04%  |
| 16/10   | 7        | 10.14%  |
| 5/4     | 6        | 8.7%    |
| 4/3     | 3        | 4.35%   |
| 21/9    | 2        | 2.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 25.97%  |
| 151-200        | 14       | 18.18%  |
| 141-150        | 10       | 12.99%  |
| Unknown        | 9        | 11.69%  |
| More than 1000 | 4        | 5.19%   |
| 301-350        | 4        | 5.19%   |
| 251-300        | 4        | 5.19%   |
| 501-1000       | 4        | 5.19%   |
| 351-500        | 3        | 3.9%    |
| 71-80          | 2        | 2.6%    |
| 131-140        | 1        | 1.3%    |
| 111-120        | 1        | 1.3%    |
| 101-110        | 1        | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 44       | 61.11%  |
| 101-120 | 10       | 13.89%  |
| Unknown | 9        | 12.5%   |
| 1-50    | 5        | 6.94%   |
| 161-240 | 3        | 4.17%   |
| 121-160 | 1        | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 52       | 75.36%  |
| 2     | 13       | 18.84%  |
| 0     | 4        | 5.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 46       | 47.42%  |
| Intel                           | 21       | 21.65%  |
| Qualcomm Atheros                | 7        | 7.22%   |
| TP-Link                         | 3        | 3.09%   |
| Ralink                          | 3        | 3.09%   |
| Broadcom                        | 3        | 3.09%   |
| Xiaomi                          | 2        | 2.06%   |
| Nvidia                          | 2        | 2.06%   |
| Linksys                         | 2        | 2.06%   |
| Huawei Technologies             | 2        | 2.06%   |
| Ralink Technology               | 1        | 1.03%   |
| Qualcomm Atheros Communications | 1        | 1.03%   |
| MediaTek                        | 1        | 1.03%   |
| Davicom Semiconductor           | 1        | 1.03%   |
| D-Link                          | 1        | 1.03%   |
| Broadcom Limited                | 1        | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36       | 34.62%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 3.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 2.88%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 1.92%   |
| Intel Wireless-AC 9260                                            | 2        | 1.92%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.92%   |
| Intel Centrino Advanced-N 6235                                    | 2        | 1.92%   |
| Huawei ANA-NX9                                                    | 2        | 1.92%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.96%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                         | 1        | 0.96%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.96%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 1        | 0.96%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.96%   |
| Realtek 802.11ac WLAN Adapter                                     | 1        | 0.96%   |
| Realtek 802.11ac NIC                                              | 1        | 0.96%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.96%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 0.96%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                              | 1        | 0.96%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 0.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.96%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 0.96%   |
| Nvidia MCP79 Ethernet                                             | 1        | 0.96%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1        | 0.96%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]    | 1        | 0.96%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                         | 1        | 0.96%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 0.96%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 8        | 25.81%  |
| Intel                           | 7        | 22.58%  |
| Qualcomm Atheros                | 4        | 12.9%   |
| TP-Link                         | 3        | 9.68%   |
| Ralink                          | 3        | 9.68%   |
| Linksys                         | 2        | 6.45%   |
| Ralink Technology               | 1        | 3.23%   |
| Qualcomm Atheros Communications | 1        | 3.23%   |
| MediaTek                        | 1        | 3.23%   |
| D-Link                          | 1        | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3        | 9.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 6.45%   |
| Intel Wireless-AC 9260                                         | 2        | 6.45%   |
| Intel Centrino Advanced-N 6235                                 | 2        | 6.45%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1        | 3.23%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 1        | 3.23%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 3.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1        | 3.23%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 1        | 3.23%   |
| Realtek 802.11ac WLAN Adapter                                  | 1        | 3.23%   |
| Realtek 802.11ac NIC                                           | 1        | 3.23%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 3.23%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1        | 3.23%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                           | 1        | 3.23%   |
| Ralink RT2800 802.11n PCI                                      | 1        | 3.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1        | 3.23%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 3.23%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 1        | 3.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1        | 3.23%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1        | 3.23%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                      | 1        | 3.23%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 3.23%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 3.23%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 1        | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 43       | 59.72%  |
| Intel                 | 15       | 20.83%  |
| Qualcomm Atheros      | 3        | 4.17%   |
| Broadcom              | 3        | 4.17%   |
| Xiaomi                | 2        | 2.78%   |
| Nvidia                | 2        | 2.78%   |
| Huawei Technologies   | 2        | 2.78%   |
| Davicom Semiconductor | 1        | 1.39%   |
| Broadcom Limited      | 1        | 1.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36       | 49.32%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 5.48%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 2.74%   |
| Intel I211 Gigabit Network Connection                             | 2        | 2.74%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.74%   |
| Huawei ANA-NX9                                                    | 2        | 2.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.37%   |
| Nvidia MCP79 Ethernet                                             | 1        | 1.37%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.37%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.37%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.37%   |
| Intel 82801DB PRO/100 VE (CNR) Ethernet Controller                | 1        | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.37%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.37%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 1.37%   |
| Davicom DM9102 Fast Ethernet Controller                           | 1        | 1.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.37%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.37%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 1.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 66       | 70.21%  |
| WiFi     | 28       | 29.79%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 55       | 77.46%  |
| WiFi     | 16       | 22.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 41       | 59.42%  |
| 2     | 27       | 39.13%  |
| 4     | 1        | 1.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 67       | 98.53%  |
| Yes  | 1        | 1.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 7        | 35%     |
| Cambridge Silicon Radio | 7        | 35%     |
| ASUSTek Computer        | 3        | 15%     |
| Realtek Semiconductor   | 1        | 5%      |
| MediaTek                | 1        | 5%      |
| Broadcom                | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 7        | 35%     |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 2        | 10%     |
| Intel Centrino Bluetooth Wireless Transceiver                | 2        | 10%     |
| Realtek Bluetooth Radio                                      | 1        | 5%      |
| MediaTek Wireless_Device                                     | 1        | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 1        | 5%      |
| Intel AX201 Bluetooth                                        | 1        | 5%      |
| Intel AX200 Bluetooth                                        | 1        | 5%      |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1        | 5%      |
| ASUS Qualcomm Bluetooth 4.1                                  | 1        | 5%      |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1        | 5%      |
| ASUS Bluetooth Radio                                         | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 43       | 39.09%  |
| Nvidia                  | 26       | 23.64%  |
| AMD                     | 26       | 23.64%  |
| C-Media Electronics     | 2        | 1.82%   |
| Soundprese              | 1        | 0.91%   |
| Sony                    | 1        | 0.91%   |
| Realtek Semiconductor   | 1        | 0.91%   |
| Medeli Electronics      | 1        | 0.91%   |
| Logitech                | 1        | 0.91%   |
| GN Netcom               | 1        | 0.91%   |
| Ensoniq                 | 1        | 0.91%   |
| Creative Labs           | 1        | 0.91%   |
| Corsair                 | 1        | 0.91%   |
| BEHRINGER International | 1        | 0.91%   |
| Astro Gaming            | 1        | 0.91%   |
| Argosy Research         | 1        | 0.91%   |
| A-DATA Technology       | 1        | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10       | 7.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 6.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 5.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 5.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 5.38%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 3.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 3.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.08%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 3.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 2.31%   |
| Nvidia High Definition Audio Controller                                    | 3        | 2.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.31%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.54%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.54%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 1.54%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.54%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.54%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.54%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.54%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.54%   |
| Soundprese HD-II                                                           | 1        | 0.77%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.77%   |
| Realtek Semiconductor USB Condenser Microphone                             | 1        | 0.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.77%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.77%   |
| Nvidia MCP79 High Definition Audio                                         | 1        | 0.77%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.77%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.77%   |
| Medeli Electronics USB Audio Device                                        | 1        | 0.77%   |
| Logitech AudioHub Speaker                                                  | 1        | 0.77%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 0.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 0.77%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                       | 1        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 11       | 24.44%  |
| Micron Technology   | 9        | 20%     |
| SK hynix            | 5        | 11.11%  |
| Samsung Electronics | 4        | 8.89%   |
| Crucial             | 4        | 8.89%   |
| Corsair             | 4        | 8.89%   |
| Unknown             | 2        | 4.44%   |
| A-DATA Technology   | 2        | 4.44%   |
| Patriot             | 1        | 2.22%   |
| Kimtigo             | 1        | 2.22%   |
| G.Skill             | 1        | 2.22%   |
| Unknown             | 1        | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 5        | 10%     |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s    | 3        | 6%      |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s     | 2        | 4%      |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 2%      |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 1        | 2%      |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 1        | 2%      |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s              | 1        | 2%      |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2%      |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 2%      |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 2%      |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s     | 1        | 2%      |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1        | 2%      |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s         | 1        | 2%      |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 1        | 2%      |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s     | 1        | 2%      |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s          | 1        | 2%      |
| Micron RAM 8JTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s | 1        | 2%      |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s     | 1        | 2%      |
| Micron RAM 16JTF25664AZ-1G4F1 2GB DIMM DDR3 1333MT/s     | 1        | 2%      |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2400MT/s   | 1        | 2%      |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 1        | 2%      |
| Kingston RAM KHX2666C15/16G 16GB DIMM DDR4 2666MT/s      | 1        | 2%      |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 1        | 2%      |
| Kingston RAM 99U5624-001.A00G 8GB SODIMM DDR4 2400MT/s   | 1        | 2%      |
| Kingston RAM 99U5403-067.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2%      |
| Kingston RAM 99U5403-050.A00 F 4GB DIMM DDR3 667MT/s     | 1        | 2%      |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 3200MT/s     | 1        | 2%      |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s     | 1        | 2%      |
| Kingston RAM 9905402-413.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 2%      |
| Kimtigo RAM KTR1333U4G 4096MB DIMM DDR3 1333MT/s         | 1        | 2%      |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 1        | 2%      |
| Crucial RAM CT4G4DFS824A.C8FBD1 4GB DIMM DDR4 2933MT/s   | 1        | 2%      |
| Crucial RAM BLS8G4D30AESBK.M8FE 8GB DIMM DDR4 3600MT/s   | 1        | 2%      |
| Crucial RAM BLS8G4D240FSE.16FBD 8GB DIMM DDR4 2400MT/s   | 1        | 2%      |
| Crucial RAM BLS8G4D240FSB.16FBD2 8GB DIMM DDR4 2400MT/s  | 1        | 2%      |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 1        | 2%      |
| Corsair RAM CMK64GX4M8A2133C13 8GB DIMM DDR4 2133MT/s    | 1        | 2%      |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 1        | 2%      |
| Corsair RAM CMD16GX4M2B3000C15 8192MB DIMM DDR4 3100MT/s | 1        | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 18       | 50%     |
| DDR3    | 13       | 36.11%  |
| SDRAM   | 2        | 5.56%   |
| DDR5    | 1        | 2.78%   |
| DDR2    | 1        | 2.78%   |
| Unknown | 1        | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 30       | 88.24%  |
| SODIMM | 4        | 11.76%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 13       | 35.14%  |
| 8192  | 12       | 32.43%  |
| 16384 | 6        | 16.22%  |
| 2048  | 5        | 13.51%  |
| 32768 | 1        | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 11       | 26.19%  |
| 2400  | 4        | 9.52%   |
| 1333  | 4        | 9.52%   |
| 3600  | 3        | 7.14%   |
| 3400  | 2        | 4.76%   |
| 3200  | 2        | 4.76%   |
| 2933  | 2        | 4.76%   |
| 2667  | 2        | 4.76%   |
| 667   | 2        | 4.76%   |
| 4800  | 1        | 2.38%   |
| 3866  | 1        | 2.38%   |
| 3466  | 1        | 2.38%   |
| 3100  | 1        | 2.38%   |
| 2934  | 1        | 2.38%   |
| 2800  | 1        | 2.38%   |
| 2666  | 1        | 2.38%   |
| 2133  | 1        | 2.38%   |
| 1866  | 1        | 2.38%   |
| 1800  | 1        | 2.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 50%     |
| Canon           | 2        | 33.33%  |
| Seiko Epson     | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Seiko Epson L3110 Series | 1        | 16.67%  |
| HP DeskJet 2600 series   | 1        | 16.67%  |
| HP DeskJet 2130 series   | 1        | 16.67%  |
| HP Deskjet 2050 J510     | 1        | 16.67%  |
| Canon G2000 series       | 1        | 16.67%  |
| Canon E400 series        | 1        | 16.67%  |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 6        | 30%     |
| Microsoft               | 3        | 15%     |
| Microdia                | 3        | 15%     |
| Chicony Electronics     | 2        | 10%     |
| Z-Star Microelectronics | 1        | 5%      |
| TANDBERG                | 1        | 5%      |
| Philips (or NXP)        | 1        | 5%      |
| Huawei Technologies     | 1        | 5%      |
| Aveo Technology         | 1        | 5%      |
| Arkmicro Technologies   | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 3        | 15%     |
| Microsoft LifeCam HD-3000             | 2        | 10%     |
| Microdia USB 2.0 Camera               | 2        | 10%     |
| Z-Star Vimicro USB Camera (Altair)    | 1        | 5%      |
| TANDBERG PrecisionHD Camera           | 1        | 5%      |
| Philips (or NXP) SPC 1300NC PC Camera | 1        | 5%      |
| Microsoft LifeCam Cinema              | 1        | 5%      |
| Microdia Integrated Camera            | 1        | 5%      |
| Logitech Webcam Pro 9000              | 1        | 5%      |
| Logitech Webcam C310                  | 1        | 5%      |
| Logitech HD Pro Webcam C920           | 1        | 5%      |
| Huawei UVC Camera                     | 1        | 5%      |
| Chicony HP High Definition 1MP Webcam | 1        | 5%      |
| Chicony HP 720p HD Monitor Webcam     | 1        | 5%      |
| Aveo USB2.0 UVC PC Camera             | 1        | 5%      |
| Arkmicro USB2.0 PC CAMERA             | 1        | 5%      |

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


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| SCM Microsystems           | 1        | 33.33%  |
| OmniKey                    | 1        | 33.33%  |
| Athena Smartcard Solutions | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 33.33%  |
| OmniKey CardMan 3021 / 3121                            | 1        | 33.33%  |
| Athena Smartcard Solutions ASEDrive CCID               | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 56       | 81.16%  |
| 1     | 10       | 14.49%  |
| 3     | 2        | 2.9%    |
| 2     | 1        | 1.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 5        | 29.41%  |
| Graphics card            | 4        | 23.53%  |
| Communication controller | 3        | 17.65%  |
| Chipcard                 | 3        | 17.65%  |
| Sound                    | 1        | 5.88%   |
| Network                  | 1        | 5.88%   |

