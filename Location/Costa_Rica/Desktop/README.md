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

Total: 79

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
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
| OpenMandriva 4.2    | 9        | 13.85%  |
| Ubuntu 20.04        | 8        | 12.31%  |
| Ubuntu 18.04        | 3        | 4.62%   |
| OpenMandriva 4.3    | 3        | 4.62%   |
| Linux Mint 20.2     | 3        | 4.62%   |
| Ubuntu 22.04        | 2        | 3.08%   |
| Pop!_OS 21.04       | 2        | 3.08%   |
| Lubuntu 22.04       | 2        | 3.08%   |
| Linux Mint 19.3     | 2        | 3.08%   |
| Fedora 32           | 2        | 3.08%   |
| Zorin 15            | 1        | 1.54%   |
| Zorin 12            | 1        | 1.54%   |
| UbuntuDDE 20.04     | 1        | 1.54%   |
| Ubuntu 20.10        | 1        | 1.54%   |
| Ubuntu 19.10        | 1        | 1.54%   |
| ROSA R8.1           | 1        | 1.54%   |
| ROSA R11.1          | 1        | 1.54%   |
| ROSA R11            | 1        | 1.54%   |
| Pop!_OS 20.10       | 1        | 1.54%   |
| Pop!_OS 20.04       | 1        | 1.54%   |
| OpenMandriva 4.50   | 1        | 1.54%   |
| Manjaro 22.0.0      | 1        | 1.54%   |
| Manjaro 21.3.5      | 1        | 1.54%   |
| Manjaro 21.2.5      | 1        | 1.54%   |
| Manjaro 21.2.0      | 1        | 1.54%   |
| Lubuntu 21.10       | 1        | 1.54%   |
| Lubuntu 20.04       | 1        | 1.54%   |
| Linux Mint 19.1     | 1        | 1.54%   |
| KDE neon 18.04      | 1        | 1.54%   |
| Fedora 36           | 1        | 1.54%   |
| Fedora 34           | 1        | 1.54%   |
| EndeavourOS Rolling | 1        | 1.54%   |
| Elementary 6        | 1        | 1.54%   |
| Elementary 5.1.7    | 1        | 1.54%   |
| Debian Testing      | 1        | 1.54%   |
| Debian 11           | 1        | 1.54%   |
| BlackPanther 18.1   | 1        | 1.54%   |
| Arch Rolling        | 1        | 1.54%   |
| Arch                | 1        | 1.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 15       | 24.59%  |
| OpenMandriva | 13       | 21.31%  |
| Linux Mint   | 6        | 9.84%   |
| Pop!_OS      | 4        | 6.56%   |
| Fedora       | 4        | 6.56%   |
| Manjaro      | 3        | 4.92%   |
| Zorin        | 2        | 3.28%   |
| ROSA         | 2        | 3.28%   |
| Lubuntu      | 2        | 3.28%   |
| Elementary   | 2        | 3.28%   |
| Debian       | 2        | 3.28%   |
| Arch         | 2        | 3.28%   |
| UbuntuDDE    | 1        | 1.64%   |
| KDE neon     | 1        | 1.64%   |
| EndeavourOS  | 1        | 1.64%   |
| BlackPanther | 1        | 1.64%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.14-desktop-1omv4002    | 9        | 13.24%  |
| 5.4.0-70-generic            | 3        | 4.41%   |
| 5.16.7-desktop-1omv4003     | 3        | 4.41%   |
| 5.4.0-42-generic            | 2        | 2.94%   |
| 6.0.2-2-MANJARO             | 1        | 1.47%   |
| 5.9.9-arch1-1               | 1        | 1.47%   |
| 5.9.14-arch1-1              | 1        | 1.47%   |
| 5.8.0-7630-generic          | 1        | 1.47%   |
| 5.8.0-50-generic            | 1        | 1.47%   |
| 5.8.0-41-generic            | 1        | 1.47%   |
| 5.8.0-34-generic            | 1        | 1.47%   |
| 5.7.0-1-amd64               | 1        | 1.47%   |
| 5.6.19-300.fc32.x86_64      | 1        | 1.47%   |
| 5.6.16-300.fc32.x86_64      | 1        | 1.47%   |
| 5.6.14-desktop-2bP          | 1        | 1.47%   |
| 5.6.13-arch1-1              | 1        | 1.47%   |
| 5.4.40-generic-1rosa-x86_64 | 1        | 1.47%   |
| 5.4.0-91-generic            | 1        | 1.47%   |
| 5.4.0-88-generic            | 1        | 1.47%   |
| 5.4.0-60-generic            | 1        | 1.47%   |
| 5.4.0-56-generic            | 1        | 1.47%   |
| 5.4.0-52-generic            | 1        | 1.47%   |
| 5.4.0-29-generic            | 1        | 1.47%   |
| 5.4.0-26-generic            | 1        | 1.47%   |
| 5.3.0-62-generic            | 1        | 1.47%   |
| 5.3.0-51-generic            | 1        | 1.47%   |
| 5.18.13-200.fc36.x86_64     | 1        | 1.47%   |
| 5.18.12-3-MANJARO           | 1        | 1.47%   |
| 5.15.11-1-MANJARO           | 1        | 1.47%   |
| 5.15.0-48-generic           | 1        | 1.47%   |
| 5.15.0-47-generic           | 1        | 1.47%   |
| 5.15.0-30-generic           | 1        | 1.47%   |
| 5.15.0-27-generic           | 1        | 1.47%   |
| 5.15.0-25-generic           | 1        | 1.47%   |
| 5.14.14-desktop-1omv4050    | 1        | 1.47%   |
| 5.13.9-200.fc34.x86_64      | 1        | 1.47%   |
| 5.13.0-7620-generic         | 1        | 1.47%   |
| 5.13.0-16-generic           | 1        | 1.47%   |
| 5.11.11-arch1-1             | 1        | 1.47%   |
| 5.11.0-7620-generic         | 1        | 1.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 11       | 16.67%  |
| 5.10.14  | 9        | 13.64%  |
| 4.15.0   | 6        | 9.09%   |
| 5.15.0   | 5        | 7.58%   |
| 5.8.0    | 4        | 6.06%   |
| 5.11.0   | 4        | 6.06%   |
| 5.16.7   | 3        | 4.55%   |
| 5.3.0    | 2        | 3.03%   |
| 5.13.0   | 2        | 3.03%   |
| 6.0.2    | 1        | 1.52%   |
| 5.9.9    | 1        | 1.52%   |
| 5.9.14   | 1        | 1.52%   |
| 5.7.0    | 1        | 1.52%   |
| 5.6.19   | 1        | 1.52%   |
| 5.6.16   | 1        | 1.52%   |
| 5.6.14   | 1        | 1.52%   |
| 5.6.13   | 1        | 1.52%   |
| 5.4.40   | 1        | 1.52%   |
| 5.18.13  | 1        | 1.52%   |
| 5.18.12  | 1        | 1.52%   |
| 5.15.11  | 1        | 1.52%   |
| 5.14.14  | 1        | 1.52%   |
| 5.13.9   | 1        | 1.52%   |
| 5.11.11  | 1        | 1.52%   |
| 5.10.94  | 1        | 1.52%   |
| 5.10.105 | 1        | 1.52%   |
| 5.10.0   | 1        | 1.52%   |
| 4.18.0   | 1        | 1.52%   |
| 4.1.38   | 1        | 1.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 12       | 18.18%  |
| 5.10    | 12       | 18.18%  |
| 5.15    | 6        | 9.09%   |
| 4.15    | 6        | 9.09%   |
| 5.11    | 5        | 7.58%   |
| 5.8     | 4        | 6.06%   |
| 5.6     | 4        | 6.06%   |
| 5.16    | 3        | 4.55%   |
| 5.13    | 3        | 4.55%   |
| 5.9     | 2        | 3.03%   |
| 5.3     | 2        | 3.03%   |
| 5.18    | 2        | 3.03%   |
| 6.0     | 1        | 1.52%   |
| 5.7     | 1        | 1.52%   |
| 5.14    | 1        | 1.52%   |
| 4.18    | 1        | 1.52%   |
| 4.1     | 1        | 1.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 55       | 94.83%  |
| i686   | 3        | 5.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 24       | 40%     |
| KDE5          | 16       | 26.67%  |
| Unknown       | 6        | 10%     |
| X-Cinnamon    | 4        | 6.67%   |
| Pantheon      | 2        | 3.33%   |
| MATE          | 2        | 3.33%   |
| LXQt          | 2        | 3.33%   |
| XFCE          | 1        | 1.67%   |
| KDE           | 1        | 1.67%   |
| GNOME Classic | 1        | 1.67%   |
| Deepin        | 1        | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 50       | 84.75%  |
| Wayland | 8        | 13.56%  |
| Tty     | 1        | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 47.46%  |
| SDDM    | 18       | 30.51%  |
| GDM     | 7        | 11.86%  |
| GDM3    | 3        | 5.08%   |
| TDM     | 2        | 3.39%   |
| LightDM | 1        | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 27       | 44.26%  |
| es_CR   | 25       | 40.98%  |
| Unknown | 5        | 8.2%    |
| es_ES   | 3        | 4.92%   |
| de_DE   | 1        | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 32       | 55.17%  |
| BIOS | 26       | 44.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 41       | 69.49%  |
| Overlay | 12       | 20.34%  |
| Btrfs   | 4        | 6.78%   |
| Xfs     | 1        | 1.69%   |
| Unknown | 1        | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 50.85%  |
| GPT     | 23       | 38.98%  |
| MBR     | 6        | 10.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 81.36%  |
| Yes       | 11       | 18.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 53.45%  |
| Yes       | 27       | 46.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 11       | 18.97%  |
| ASUSTek Computer    | 11       | 18.97%  |
| Gigabyte Technology | 9        | 15.52%  |
| ASRock              | 6        | 10.34%  |
| MSI                 | 4        | 6.9%    |
| Hewlett-Packard     | 3        | 5.17%   |
| Intel               | 2        | 3.45%   |
| Unknown             | 2        | 3.45%   |
| ZOTAC               | 1        | 1.72%   |
| TPV-INVENTA         | 1        | 1.72%   |
| Supermicro          | 1        | 1.72%   |
| Pegatron            | 1        | 1.72%   |
| MACHINIST           | 1        | 1.72%   |
| Lenovo              | 1        | 1.72%   |
| Gateway             | 1        | 1.72%   |
| Biostar             | 1        | 1.72%   |
| Alienware           | 1        | 1.72%   |
| ABIT                | 1        | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Dell OptiPlex 3020                       | 5        | 8.62%   |
| Gigabyte B250M-DS3H                      | 2        | 3.45%   |
| Dell OptiPlex 7040                       | 2        | 3.45%   |
| ASUS PRIME A320M-K                       | 2        | 3.45%   |
| ASRock B450 Steel Legend                 | 2        | 3.45%   |
| Unknown                                  | 2        | 3.45%   |
| ZOTAC NM10                               | 1        | 1.72%   |
| TPV-INVENTA 18-2003LA                    | 1        | 1.72%   |
| Supermicro X9DAi                         | 1        | 1.72%   |
| Pegatron CQ2728LA                        | 1        | 1.72%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1        | 1.72%   |
| MSI MS-7B86                              | 1        | 1.72%   |
| MSI MS-7693                              | 1        | 1.72%   |
| MSI MS-7636                              | 1        | 1.72%   |
| MACHINIST X79 V2.82H                     | 1        | 1.72%   |
| Lenovo H530S 10132                       | 1        | 1.72%   |
| Intel DG41WV AAE90316-103                | 1        | 1.72%   |
| Intel D33217CK G76541-302                | 1        | 1.72%   |
| HP Z800 Workstation                      | 1        | 1.72%   |
| HP ProDesk 600 G4 SFF                    | 1        | 1.72%   |
| HP EliteDesk 800 G1 TWR                  | 1        | 1.72%   |
| Gigabyte Z690 UD AX DDR4                 | 1        | 1.72%   |
| Gigabyte Z170X-Gaming 7                  | 1        | 1.72%   |
| Gigabyte X570 I AORUS PRO WIFI           | 1        | 1.72%   |
| Gigabyte H110M-S2                        | 1        | 1.72%   |
| Gigabyte H110M-H                         | 1        | 1.72%   |
| Gigabyte GA-970A-D3                      | 1        | 1.72%   |
| Gigabyte GA-78LMT-USB3 6.0               | 1        | 1.72%   |
| Gateway LX6810-01                        | 1        | 1.72%   |
| Dell Precision WorkStation T5400         | 1        | 1.72%   |
| Dell Precision WorkStation T3500         | 1        | 1.72%   |
| Dell OptiPlex 755                        | 1        | 1.72%   |
| Dell OptiPlex 3010                       | 1        | 1.72%   |
| Biostar H61MGV3                          | 1        | 1.72%   |
| ASUS TUF Gaming X570-PLUS                | 1        | 1.72%   |
| ASUS TUF Gaming B550M-PLUS               | 1        | 1.72%   |
| ASUS STRIX Z270G GAMING                  | 1        | 1.72%   |
| ASUS SABERTOOTH 990FX R2.0               | 1        | 1.72%   |
| ASUS ROG STRIX B550-F GAMING             | 1        | 1.72%   |
| ASUS PRIME Z370-A                        | 1        | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 9        | 15.52%  |
| ASUS PRIME             | 4        | 6.9%    |
| Gigabyte B250M-DS3H    | 2        | 3.45%   |
| Dell Precision         | 2        | 3.45%   |
| ASUS TUF               | 2        | 3.45%   |
| ASRock B450            | 2        | 3.45%   |
| Unknown                | 2        | 3.45%   |
| ZOTAC NM10             | 1        | 1.72%   |
| TPV-INVENTA 18-2003LA  | 1        | 1.72%   |
| Supermicro X9DAi       | 1        | 1.72%   |
| Pegatron CQ2728LA      | 1        | 1.72%   |
| MSI Z390               | 1        | 1.72%   |
| MSI MS-7B86            | 1        | 1.72%   |
| MSI MS-7693            | 1        | 1.72%   |
| MSI MS-7636            | 1        | 1.72%   |
| MACHINIST X79          | 1        | 1.72%   |
| Lenovo H530S           | 1        | 1.72%   |
| Intel DG41WV           | 1        | 1.72%   |
| Intel D33217CK         | 1        | 1.72%   |
| HP Z800                | 1        | 1.72%   |
| HP ProDesk             | 1        | 1.72%   |
| HP EliteDesk           | 1        | 1.72%   |
| Gigabyte Z690          | 1        | 1.72%   |
| Gigabyte Z170X-Gaming  | 1        | 1.72%   |
| Gigabyte X570          | 1        | 1.72%   |
| Gigabyte H110M-S2      | 1        | 1.72%   |
| Gigabyte H110M-H       | 1        | 1.72%   |
| Gigabyte GA-970A-D3    | 1        | 1.72%   |
| Gigabyte GA-78LMT-USB3 | 1        | 1.72%   |
| Gateway LX6810-01      | 1        | 1.72%   |
| Biostar H61MGV3        | 1        | 1.72%   |
| ASUS STRIX             | 1        | 1.72%   |
| ASUS SABERTOOTH        | 1        | 1.72%   |
| ASUS ROG               | 1        | 1.72%   |
| ASUS H110M-K           | 1        | 1.72%   |
| ASUS All               | 1        | 1.72%   |
| ASRock N68-S           | 1        | 1.72%   |
| ASRock H81M-VG4        | 1        | 1.72%   |
| ASRock 970             | 1        | 1.72%   |
| ASRock 775i65GV        | 1        | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 8        | 13.79%  |
| 2019 | 7        | 12.07%  |
| 2016 | 7        | 12.07%  |
| 2013 | 6        | 10.34%  |
| 2017 | 5        | 8.62%   |
| 2012 | 5        | 8.62%   |
| 2010 | 4        | 6.9%    |
| 2008 | 3        | 5.17%   |
| 2021 | 2        | 3.45%   |
| 2020 | 2        | 3.45%   |
| 2018 | 2        | 3.45%   |
| 2011 | 2        | 3.45%   |
| 2005 | 2        | 3.45%   |
| 2022 | 1        | 1.72%   |
| 2009 | 1        | 1.72%   |
| 2007 | 1        | 1.72%   |

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
| Disabled | 54       | 93.1%   |
| Enabled  | 4        | 6.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 18       | 30.51%  |
| 8.01-16.0       | 13       | 22.03%  |
| 3.01-4.0        | 10       | 16.95%  |
| 4.01-8.0        | 6        | 10.17%  |
| 1.01-2.0        | 5        | 8.47%   |
| 32.01-64.0      | 4        | 6.78%   |
| More than 256.0 | 1        | 1.69%   |
| 2.01-3.0        | 1        | 1.69%   |
| 64.01-256.0     | 1        | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 28       | 44.44%  |
| 2.01-3.0   | 11       | 17.46%  |
| 4.01-8.0   | 8        | 12.7%   |
| 3.01-4.0   | 5        | 7.94%   |
| 0.51-1.0   | 4        | 6.35%   |
| 0.01-0.5   | 3        | 4.76%   |
| 8.01-16.0  | 2        | 3.17%   |
| 24.01-32.0 | 1        | 1.59%   |
| 16.01-24.0 | 1        | 1.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 51.67%  |
| 2      | 15       | 25%     |
| 3      | 6        | 10%     |
| 4      | 5        | 8.33%   |
| 8      | 1        | 1.67%   |
| 7      | 1        | 1.67%   |
| 5      | 1        | 1.67%   |

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
| Yes       | 57       | 98.28%  |
| No        | 1        | 1.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 59.32%  |
| Yes       | 24       | 40.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 77.97%  |
| Yes       | 13       | 22.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Costa Rica | 58       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Desktops | Percent |
|------------|----------|---------|
| San José  | 25       | 40.32%  |
| Heredia    | 16       | 25.81%  |
| Escazu     | 3        | 4.84%   |
| Alajuela   | 3        | 4.84%   |
| Liberia    | 2        | 3.23%   |
| Cartago    | 2        | 3.23%   |
| Tres Rios  | 1        | 1.61%   |
| Tibas      | 1        | 1.61%   |
| Santa Fe   | 1        | 1.61%   |
| Santa Ana  | 1        | 1.61%   |
| San Pedro  | 1        | 1.61%   |
| Palmares   | 1        | 1.61%   |
| Nosara     | 1        | 1.61%   |
| Grecia     | 1        | 1.61%   |
| Curridabat | 1        | 1.61%   |
| Bajo Perez | 1        | 1.61%   |
| Alajuelita | 1        | 1.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 23       | 39     | 23.71%  |
| WDC                   | 16       | 20     | 16.49%  |
| A-DATA Technology     | 10       | 10     | 10.31%  |
| Kingston              | 8        | 13     | 8.25%   |
| Toshiba               | 7        | 8      | 7.22%   |
| Samsung Electronics   | 5        | 9      | 5.15%   |
| Hitachi               | 5        | 7      | 5.15%   |
| XPG                   | 4        | 4      | 4.12%   |
| Realtek Semiconductor | 3        | 4      | 3.09%   |
| ZOTAC                 | 2        | 3      | 2.06%   |
| SanDisk               | 2        | 2      | 2.06%   |
| Patriot               | 2        | 2      | 2.06%   |
| Maxtor                | 2        | 2      | 2.06%   |
| HGST                  | 2        | 2      | 2.06%   |
| Crucial               | 2        | 2      | 2.06%   |
| WD MediaMax           | 1        | 1      | 1.03%   |
| JMicron Technology    | 1        | 1      | 1.03%   |
| Intel                 | 1        | 1      | 1.03%   |
| CT120BX5              | 1        | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| A-DATA SU630 480GB SSD           | 5        | 4.63%   |
| Kingston SA400S37240G 240GB SSD  | 4        | 3.7%    |
| WDC WD10EZEX-75WN4A1 1TB         | 3        | 2.78%   |
| Toshiba DT01ACA100 1TB           | 3        | 2.78%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 2.78%   |
| XPG GAMMIX S11 Pro 1TB           | 2        | 1.85%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.85%   |
| Seagate ST8000DM004-2CX188 8TB   | 2        | 1.85%   |
| Seagate ST380815AS 80GB          | 2        | 1.85%   |
| ZOTAC ZTSSD-S11-240G-P 240GB     | 1        | 0.93%   |
| ZOTAC ZTSSD-S11-120G-MD 120GB    | 1        | 0.93%   |
| XPG NVMe SSD Drive 512GB         | 1        | 0.93%   |
| XPG NVMe SSD Drive 1TB           | 1        | 0.93%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 0.93%   |
| WDC WD6400AAKS-22A7B0 640GB      | 1        | 0.93%   |
| WDC WD5000LPCX-60VHAT0 500GB     | 1        | 0.93%   |
| WDC WD5000AAKS-00V1A0 500GB      | 1        | 0.93%   |
| WDC WD2500AAJS-00VTA0 250GB      | 1        | 0.93%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1        | 0.93%   |
| WDC WD1600BEVS-26VAT0 160GB      | 1        | 0.93%   |
| WDC WD1500HLFS-01G6U0 150GB      | 1        | 0.93%   |
| WDC WD10SPZX-24Z10T0 1TB         | 1        | 0.93%   |
| WDC WD10JPVX-00JC3T0 1TB         | 1        | 0.93%   |
| WDC WD10EZEX-60WN4A0 1TB         | 1        | 0.93%   |
| WDC WD10EZEX-08M2NA0 1TB         | 1        | 0.93%   |
| WD MediaMax WL3000GSA6472 3TB    | 1        | 0.93%   |
| Toshiba THNSN5512GPUK NVMe 512GB | 1        | 0.93%   |
| Toshiba RD400 256GB              | 1        | 0.93%   |
| Toshiba MQ01ABD100 1TB           | 1        | 0.93%   |
| Toshiba HDWD105 500GB            | 1        | 0.93%   |
| Seagate ST9160412AS 160GB        | 1        | 0.93%   |
| Seagate ST9160301AS 160GB        | 1        | 0.93%   |
| Seagate ST8000DM005-2EH112 8TB   | 1        | 0.93%   |
| Seagate ST6000VN0033-2EE110 6TB  | 1        | 0.93%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 0.93%   |
| Seagate ST4000DM006-2G5107 4TB   | 1        | 0.93%   |
| Seagate ST3500418AS 500GB        | 1        | 0.93%   |
| Seagate ST3500414CS 500GB        | 1        | 0.93%   |
| Seagate ST3500320AS 500GB        | 1        | 0.93%   |
| Seagate ST3320418AS 320GB        | 1        | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 22       | 38     | 42.31%  |
| WDC     | 16       | 19     | 30.77%  |
| Toshiba | 5        | 6      | 9.62%   |
| Hitachi | 5        | 7      | 9.62%   |
| Maxtor  | 2        | 2      | 3.85%   |
| HGST    | 2        | 2      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 8        | 13     | 28.57%  |
| A-DATA Technology   | 8        | 8      | 28.57%  |
| ZOTAC               | 2        | 3      | 7.14%   |
| SanDisk             | 2        | 2      | 7.14%   |
| Samsung Electronics | 2        | 4      | 7.14%   |
| Patriot             | 2        | 2      | 7.14%   |
| WDC                 | 1        | 1      | 3.57%   |
| Intel               | 1        | 1      | 3.57%   |
| CT120BX5            | 1        | 1      | 3.57%   |
| Crucial             | 1        | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 42       | 74     | 51.85%  |
| SSD     | 25       | 36     | 30.86%  |
| NVMe    | 13       | 19     | 16.05%  |
| Unknown | 1        | 2      | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 56       | 103    | 76.71%  |
| NVMe | 12       | 18     | 16.44%  |
| SAS  | 5        | 10     | 6.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 43       | 65     | 58.11%  |
| 0.51-1.0   | 22       | 27     | 29.73%  |
| 4.01-10.0  | 4        | 12     | 5.41%   |
| 1.01-2.0   | 3        | 4      | 4.05%   |
| 3.01-4.0   | 2        | 2      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 12       | 19.67%  |
| 501-1000       | 12       | 19.67%  |
| 1-20           | 9        | 14.75%  |
| 251-500        | 8        | 13.11%  |
| More than 3000 | 6        | 9.84%   |
| 51-100         | 6        | 9.84%   |
| 1001-2000      | 5        | 8.2%    |
| 21-50          | 1        | 1.64%   |
| 2001-3000      | 1        | 1.64%   |
| Unknown        | 1        | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 27       | 43.55%  |
| 21-50          | 7        | 11.29%  |
| 101-250        | 7        | 11.29%  |
| 251-500        | 5        | 8.06%   |
| More than 3000 | 4        | 6.45%   |
| 1001-2000      | 3        | 4.84%   |
| 501-1000       | 3        | 4.84%   |
| 51-100         | 3        | 4.84%   |
| 2001-3000      | 2        | 3.23%   |
| Unknown        | 1        | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST9160412AS 160GB           | 1        | 1      | 14.29%  |
| Seagate ST500DM002-1BD142 500GB     | 1        | 2      | 14.29%  |
| SanDisk SD6SB1M-128G-1006 128GB SSD | 1        | 1      | 14.29%  |
| Maxtor STM3160215AS 160GB           | 1        | 1      | 14.29%  |
| Kingston SV300S37A120G 120GB SSD    | 1        | 1      | 14.29%  |
| Hitachi HDE721010SLA330 1TB         | 1        | 1      | 14.29%  |
| A-DATA Technology SX8100NP 256GB    | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 2        | 3      | 28.57%  |
| SanDisk           | 1        | 1      | 14.29%  |
| Maxtor            | 1        | 1      | 14.29%  |
| Kingston          | 1        | 1      | 14.29%  |
| Hitachi           | 1        | 1      | 14.29%  |
| A-DATA Technology | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 3      | 50%     |
| Maxtor  | 1        | 1      | 25%     |
| Hitachi | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 5      | 50%     |
| SSD  | 2        | 2      | 33.33%  |
| NVMe | 1        | 1      | 16.67%  |

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
| Detected | 35       | 75     | 54.69%  |
| Works    | 23       | 48     | 35.94%  |
| Malfunc  | 6        | 8      | 9.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 40       | 50%     |
| AMD                          | 16       | 20%     |
| Realtek Semiconductor        | 4        | 5%      |
| ASMedia Technology           | 4        | 5%      |
| ADATA Technology             | 4        | 5%      |
| Samsung Electronics          | 3        | 3.75%   |
| Nvidia                       | 2        | 2.5%    |
| Toshiba America Info Systems | 1        | 1.25%   |
| Silicon Image                | 1        | 1.25%   |
| OCZ Technology Group         | 1        | 1.25%   |
| Micron/Crucial Technology    | 1        | 1.25%   |
| Marvell Technology Group     | 1        | 1.25%   |
| LSI Logic / Symbios Logic    | 1        | 1.25%   |
| JMicron Technology           | 1        | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9        | 9.78%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 7.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 5.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5        | 5.43%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 4.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 4.35%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 4.35%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 4        | 4.35%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 3        | 3.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 3.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 2.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 2.17%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 2.17%   |
| AMD FCH SATA Controller D                                                      | 2        | 2.17%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 2.17%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 1.09%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 1.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 1.09%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.09%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1        | 1.09%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 1.09%   |
| Nvidia MCP79 RAID Controller                                                   | 1        | 1.09%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.09%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.09%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 1.09%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 1.09%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                   | 1        | 1.09%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                  | 1        | 1.09%   |
| JMicron JMB368 IDE controller                                                  | 1        | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1        | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.09%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 1.09%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 1.09%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 1.09%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                   | 1        | 1.09%   |
| Intel 82801EB (ICH5) SATA Controller                                           | 1        | 1.09%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1        | 1.09%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 48       | 61.54%  |
| NVMe | 12       | 15.38%  |
| IDE  | 11       | 14.1%   |
| RAID | 5        | 6.41%   |
| SAS  | 1        | 1.28%   |
| SCSI | 1        | 1.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 41       | 70.69%  |
| AMD    | 17       | 29.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 8.62%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 6.9%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 3.45%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 3.45%   |
| Intel Xeon CPU X5667 @ 3.07GHz              | 1        | 1.72%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 1.72%   |
| Intel Xeon CPU E5405 @ 2.00GHz              | 1        | 1.72%   |
| Intel Xeon CPU E5-2660 v2 @ 2.20GHz         | 1        | 1.72%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1        | 1.72%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.72%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 1.72%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 1.72%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1        | 1.72%   |
| Intel Core i9-9900KF CPU @ 3.60GHz          | 1        | 1.72%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.72%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 1        | 1.72%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 1.72%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 1.72%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.72%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.72%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.72%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.72%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.72%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.72%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.72%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1        | 1.72%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 1.72%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.72%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 1        | 1.72%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.72%   |
| Intel Celeron CPU 2.66GHz                   | 1        | 1.72%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 1.72%   |
| Intel 12th Gen Core i5-12600K               | 1        | 1.72%   |
| AMD Sempron 140 Processor                   | 1        | 1.72%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics  | 1        | 1.72%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 1        | 1.72%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 15       | 25.86%  |
| Intel Core i3           | 6        | 10.34%  |
| Intel Xeon              | 5        | 8.62%   |
| AMD Ryzen 5             | 5        | 8.62%   |
| AMD FX                  | 4        | 6.9%    |
| Intel Core i7           | 3        | 5.17%   |
| Intel Pentium           | 2        | 3.45%   |
| Intel Celeron           | 2        | 3.45%   |
| AMD Ryzen 7             | 2        | 3.45%   |
| Other                   | 1        | 1.72%   |
| Intel Pentium Dual-Core | 1        | 1.72%   |
| Intel Pentium 4         | 1        | 1.72%   |
| Intel Core i9           | 1        | 1.72%   |
| Intel Core 2 Quad       | 1        | 1.72%   |
| Intel Core 2 Duo        | 1        | 1.72%   |
| Intel Core 2            | 1        | 1.72%   |
| Intel Atom              | 1        | 1.72%   |
| AMD Sempron             | 1        | 1.72%   |
| AMD Ryzen 7 PRO         | 1        | 1.72%   |
| AMD Ryzen 3             | 1        | 1.72%   |
| AMD Phenom II X4        | 1        | 1.72%   |
| AMD E2                  | 1        | 1.72%   |
| AMD E1                  | 1        | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 28       | 48.28%  |
| 2      | 11       | 18.97%  |
| 8      | 6        | 10.34%  |
| 6      | 6        | 10.34%  |
| 1      | 4        | 6.9%    |
| 20     | 1        | 1.72%   |
| 10     | 1        | 1.72%   |
| 3      | 1        | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 96.55%  |
| 2      | 2        | 3.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 60.34%  |
| 2      | 23       | 39.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 56       | 96.55%  |
| 32-bit         | 1        | 1.72%   |
| Unknown        | 1        | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 8        | 13.33%  |
| Unknown    | 8        | 13.33%  |
| 0x906e9    | 4        | 6.67%   |
| 0x306a9    | 4        | 6.67%   |
| 0x08701021 | 4        | 6.67%   |
| 0x906eb    | 2        | 3.33%   |
| 0x506e3    | 2        | 3.33%   |
| 0x306e4    | 2        | 3.33%   |
| 0x10676    | 2        | 3.33%   |
| 0x06000852 | 2        | 3.33%   |
| 0x05000119 | 2        | 3.33%   |
| 0xf49      | 1        | 1.67%   |
| 0xf29      | 1        | 1.67%   |
| 0x906ec    | 1        | 1.67%   |
| 0x906ea    | 1        | 1.67%   |
| 0x90672    | 1        | 1.67%   |
| 0x706a8    | 1        | 1.67%   |
| 0x6f6      | 1        | 1.67%   |
| 0x106e5    | 1        | 1.67%   |
| 0x106ca    | 1        | 1.67%   |
| 0x106a5    | 1        | 1.67%   |
| 0x10677    | 1        | 1.67%   |
| 0x08701011 | 1        | 1.67%   |
| 0x0870100a | 1        | 1.67%   |
| 0x08600106 | 1        | 1.67%   |
| 0x08108109 | 1        | 1.67%   |
| 0x0800820d | 1        | 1.67%   |
| 0x0500010d | 1        | 1.67%   |
| 0x010000c8 | 1        | 1.67%   |
| 0x010000c7 | 1        | 1.67%   |
| 0x00000000 | 1        | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 9        | 15.52%  |
| Haswell       | 9        | 15.52%  |
| Zen 2         | 6        | 10.34%  |
| IvyBridge     | 6        | 10.34%  |
| Skylake       | 4        | 6.9%    |
| Penryn        | 4        | 6.9%    |
| Piledriver    | 3        | 5.17%   |
| Zen+          | 2        | 3.45%   |
| NetBurst      | 2        | 3.45%   |
| Nehalem       | 2        | 3.45%   |
| K10           | 2        | 3.45%   |
| Bobcat        | 2        | 3.45%   |
| Zen 3         | 1        | 1.72%   |
| Westmere      | 1        | 1.72%   |
| Goldmont plus | 1        | 1.72%   |
| Core          | 1        | 1.72%   |
| Bulldozer     | 1        | 1.72%   |
| Bonnell       | 1        | 1.72%   |
| Unknown       | 1        | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 26       | 40.63%  |
| Nvidia | 24       | 37.5%   |
| AMD    | 14       | 21.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 12.12%  |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 6.06%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 4.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 4.55%   |
| Intel HD Graphics 630                                                       | 3        | 4.55%   |
| Intel HD Graphics 530                                                       | 3        | 4.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 4.55%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 2        | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.03%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 3.03%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 3.03%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.52%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.52%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.52%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.52%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                        | 1        | 1.52%   |
| Nvidia GT218 [ION]                                                          | 1        | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.52%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 1.52%   |
| Nvidia GK106 [GeForce GTX 645 OEM]                                          | 1        | 1.52%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.52%   |
| Nvidia G96C [GeForce GT 120]                                                | 1        | 1.52%   |
| Nvidia G71GL [Quadro FX 3500]                                               | 1        | 1.52%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.52%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.52%   |
| Intel 82865G Integrated Graphics Controller                                 | 1        | 1.52%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device          | 1        | 1.52%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.52%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 1.52%   |
| AMD Wrestler [Radeon HD 7340]                                               | 1        | 1.52%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.52%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.52%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 1        | 1.52%   |
| AMD RV530LE [Radeon X1600/X1650 PRO]                                        | 1        | 1.52%   |
| AMD RV530 [Radeon X1650] (Secondary)                                        | 1        | 1.52%   |
| AMD Renoir                                                                  | 1        | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 23       | 38.98%  |
| 1 x Nvidia     | 21       | 35.59%  |
| 1 x AMD        | 10       | 16.95%  |
| 2 x AMD        | 2        | 3.39%   |
| AMD + Nvidia   | 2        | 3.39%   |
| Intel + Nvidia | 1        | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 47       | 79.66%  |
| Proprietary | 11       | 18.64%  |
| Unknown     | 1        | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 38.71%  |
| 1.01-2.0   | 11       | 17.74%  |
| 3.01-4.0   | 7        | 11.29%  |
| 0.51-1.0   | 7        | 11.29%  |
| 0.01-0.5   | 7        | 11.29%  |
| 5.01-6.0   | 5        | 8.06%   |
| 7.01-8.0   | 1        | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| AOC                  | 17       | 25%     |
| Hewlett-Packard      | 10       | 14.71%  |
| Dell                 | 9        | 13.24%  |
| Goldstar             | 7        | 10.29%  |
| ViewSonic            | 4        | 5.88%   |
| BenQ                 | 3        | 4.41%   |
| Sony                 | 2        | 2.94%   |
| Samsung Electronics  | 2        | 2.94%   |
| AGO                  | 2        | 2.94%   |
| Acer                 | 2        | 2.94%   |
| Xerox                | 1        | 1.47%   |
| Unknown (XXX)        | 1        | 1.47%   |
| Royal Information    | 1        | 1.47%   |
| Philips              | 1        | 1.47%   |
| Panasonic            | 1        | 1.47%   |
| MSI                  | 1        | 1.47%   |
| LTM                  | 1        | 1.47%   |
| Lenovo               | 1        | 1.47%   |
| Haier                | 1        | 1.47%   |
| Ancor Communications | 1        | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5        | 6.94%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2        | 2.78%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2        | 2.78%   |
| Dell LCD Monitor DELA102 1920x1080 540x300mm 24.3-inch               | 2        | 2.78%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 2        | 2.78%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1        | 1.39%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1        | 1.39%   |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1        | 1.39%   |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1        | 1.39%   |
| ViewSonic LCD Monitor VX2260WM                                       | 1        | 1.39%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 1.39%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                        | 1        | 1.39%   |
| Sony TV SNY0902 1360x768                                             | 1        | 1.39%   |
| Royal Information Monitor TRL1012 1280x1024 320x240mm 15.7-inch      | 1        | 1.39%   |
| Philips LCD Monitor 170B4 1280x1024                                  | 1        | 1.39%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                   | 1        | 1.39%   |
| MSI MAG271CQP MSI3FA7 2560x1440 597x336mm 27.0-inch                  | 1        | 1.39%   |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                    | 1        | 1.39%   |
| Lenovo LEN D186wA LEN0A14 1366x768 410x230mm 18.5-inch               | 1        | 1.39%   |
| Hewlett-Packard V193 HWP3178 1366x768 410x230mm 18.5-inch            | 1        | 1.39%   |
| Hewlett-Packard P223a HPN3391 1920x1080 477x268mm 21.5-inch          | 1        | 1.39%   |
| Hewlett-Packard LCD Monitor L1908w 1440x900                          | 1        | 1.39%   |
| Hewlett-Packard LCD Monitor Compaq W185q 3286x1080                   | 1        | 1.39%   |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch         | 1        | 1.39%   |
| Hewlett-Packard L1910 HWP26E6 1280x1024 380x300mm 19.1-inch          | 1        | 1.39%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch           | 1        | 1.39%   |
| Hewlett-Packard Compaq W1952a HWP3010 1366x768 410x230mm 18.5-inch   | 1        | 1.39%   |
| Hewlett-Packard Compaq CQ-1 HWP410E 1366x768 410x230mm 18.5-inch     | 1        | 1.39%   |
| Haier AQUA TV HRE0030 1920x1080 708x398mm 32.0-inch                  | 1        | 1.39%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 1        | 1.39%   |
| Goldstar MP59G GSM5B33 1920x1080 480x270mm 21.7-inch                 | 1        | 1.39%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch             | 1        | 1.39%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 1        | 1.39%   |
| Goldstar HDR WFHD GSM5B9F 2560x1080 798x334mm 34.1-inch              | 1        | 1.39%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                | 1        | 1.39%   |
| Goldstar FULL HD GSM5B9E 1920x1080 600x340mm 27.2-inch               | 1        | 1.39%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1        | 1.39%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 1        | 1.39%   |
| Dell S3219D DELD0EE 2560x1440 708x399mm 32.0-inch                    | 1        | 1.39%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 1        | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 25       | 37.31%  |
| 1366x768 (WXGA)   | 8        | 11.94%  |
| 1440x900 (WXGA+)  | 6        | 8.96%   |
| 1280x1024 (SXGA)  | 6        | 8.96%   |
| 3840x2160 (4K)    | 5        | 7.46%   |
| 1600x900 (HD+)    | 4        | 5.97%   |
| 3286x1080         | 2        | 2.99%   |
| 2560x1440 (QHD)   | 2        | 2.99%   |
| 2560x1080         | 2        | 2.99%   |
| 1280x720 (HD)     | 2        | 2.99%   |
| Unknown           | 2        | 2.99%   |
| 1920x1200 (WUXGA) | 1        | 1.49%   |
| 1360x768          | 1        | 1.49%   |
| 1280x960          | 1        | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 10       | 14.71%  |
| 24      | 8        | 11.76%  |
| 23      | 8        | 11.76%  |
| 18      | 7        | 10.29%  |
| Unknown | 7        | 10.29%  |
| 21      | 5        | 7.35%   |
| 27      | 4        | 5.88%   |
| 17      | 4        | 5.88%   |
| 72      | 2        | 2.94%   |
| 43      | 2        | 2.94%   |
| 34      | 2        | 2.94%   |
| 32      | 2        | 2.94%   |
| 15      | 2        | 2.94%   |
| 12      | 2        | 2.94%   |
| 84      | 1        | 1.47%   |
| 54      | 1        | 1.47%   |
| 40      | 1        | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 29.41%  |
| 401-500     | 20       | 29.41%  |
| Unknown     | 7        | 10.29%  |
| 301-350     | 5        | 7.35%   |
| 701-800     | 4        | 5.88%   |
| 351-400     | 3        | 4.41%   |
| 1501-2000   | 3        | 4.41%   |
| 201-300     | 2        | 2.94%   |
| 901-1000    | 2        | 2.94%   |
| 801-900     | 1        | 1.47%   |
| 1001-1500   | 1        | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 38       | 61.29%  |
| 16/10   | 7        | 11.29%  |
| Unknown | 7        | 11.29%  |
| 5/4     | 5        | 8.06%   |
| 4/3     | 3        | 4.84%   |
| 21/9    | 2        | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 16       | 23.19%  |
| 151-200        | 13       | 18.84%  |
| 141-150        | 9        | 13.04%  |
| Unknown        | 7        | 10.14%  |
| More than 1000 | 4        | 5.8%    |
| 351-500        | 4        | 5.8%    |
| 301-350        | 4        | 5.8%    |
| 251-300        | 4        | 5.8%    |
| 501-1000       | 3        | 4.35%   |
| 71-80          | 2        | 2.9%    |
| 131-140        | 1        | 1.45%   |
| 111-120        | 1        | 1.45%   |
| 101-110        | 1        | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 40       | 61.54%  |
| 101-120 | 9        | 13.85%  |
| Unknown | 7        | 10.77%  |
| 1-50    | 5        | 7.69%   |
| 161-240 | 4        | 6.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 78.33%  |
| 2     | 11       | 18.33%  |
| 0     | 2        | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 40       | 48.19%  |
| Intel                 | 17       | 20.48%  |
| Qualcomm Atheros      | 7        | 8.43%   |
| Ralink                | 3        | 3.61%   |
| Broadcom              | 3        | 3.61%   |
| Xiaomi                | 2        | 2.41%   |
| TP-Link               | 2        | 2.41%   |
| Nvidia                | 2        | 2.41%   |
| Linksys               | 2        | 2.41%   |
| Ralink Technology     | 1        | 1.2%    |
| Huawei Technologies   | 1        | 1.2%    |
| Davicom Semiconductor | 1        | 1.2%    |
| D-Link                | 1        | 1.2%    |
| Broadcom Limited      | 1        | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 35.96%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 3.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 2.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 2.25%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.25%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.25%   |
| Intel Centrino Advanced-N 6235                                    | 2        | 2.25%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 1.12%   |
| TP-Link 802.11n NIC                                               | 1        | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 1.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.12%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 1        | 1.12%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.12%   |
| Realtek 802.11ac WLAN Adapter                                     | 1        | 1.12%   |
| Realtek 802.11ac NIC                                              | 1        | 1.12%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.12%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 1.12%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                              | 1        | 1.12%   |
| Ralink RT2800 802.11n PCI                                         | 1        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.12%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.12%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.12%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 1.12%   |
| Nvidia MCP79 Ethernet                                             | 1        | 1.12%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.12%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]    | 1        | 1.12%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                         | 1        | 1.12%   |
| Intel Wireless-AC 9260                                            | 1        | 1.12%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.12%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.12%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 1.12%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 1.12%   |
| Intel 82801DB PRO/100 VE (CNR) Ethernet Controller                | 1        | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 26.92%  |
| Intel                 | 6        | 23.08%  |
| Qualcomm Atheros      | 4        | 15.38%  |
| Ralink                | 3        | 11.54%  |
| TP-Link               | 2        | 7.69%   |
| Linksys               | 2        | 7.69%   |
| Ralink Technology     | 1        | 3.85%   |
| D-Link                | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3        | 11.54%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2        | 7.69%   |
| Intel Centrino Advanced-N 6235                                 | 2        | 7.69%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 3.85%   |
| TP-Link 802.11n NIC                                            | 1        | 3.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 3.85%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 1        | 3.85%   |
| Realtek 802.11ac WLAN Adapter                                  | 1        | 3.85%   |
| Realtek 802.11ac NIC                                           | 1        | 3.85%   |
| Ralink MT7601U Wireless Adapter                                | 1        | 3.85%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1        | 3.85%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                           | 1        | 3.85%   |
| Ralink RT2800 802.11n PCI                                      | 1        | 3.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1        | 3.85%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 1        | 3.85%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236] | 1        | 3.85%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                      | 1        | 3.85%   |
| Intel Wireless-AC 9260                                         | 1        | 3.85%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 3.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1        | 3.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 3.85%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 37       | 59.68%  |
| Intel                 | 12       | 19.35%  |
| Qualcomm Atheros      | 3        | 4.84%   |
| Broadcom              | 3        | 4.84%   |
| Xiaomi                | 2        | 3.23%   |
| Nvidia                | 2        | 3.23%   |
| Huawei Technologies   | 1        | 1.61%   |
| Davicom Semiconductor | 1        | 1.61%   |
| Broadcom Limited      | 1        | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 50.79%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 3.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 3.17%   |
| Intel Ethernet Controller I225-V                                  | 2        | 3.17%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 3.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.59%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.59%   |
| Nvidia MCP79 Ethernet                                             | 1        | 1.59%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.59%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.59%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.59%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.59%   |
| Intel 82801DB PRO/100 VE (CNR) Ethernet Controller                | 1        | 1.59%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.59%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 1.59%   |
| Huawei LYA-L09                                                    | 1        | 1.59%   |
| Davicom DM9102 Fast Ethernet Controller                           | 1        | 1.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.59%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.59%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.59%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 57       | 70.37%  |
| WiFi     | 24       | 29.63%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 47       | 77.05%  |
| WiFi     | 14       | 22.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 57.63%  |
| 2     | 24       | 40.68%  |
| 4     | 1        | 1.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 42.86%  |
| Cambridge Silicon Radio | 5        | 35.71%  |
| ASUSTek Computer        | 2        | 14.29%  |
| Broadcom                | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 5        | 35.71%  |
| Intel Centrino Bluetooth Wireless Transceiver                | 2        | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 1        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 1        | 7.14%   |
| Intel AX201 Bluetooth                                        | 1        | 7.14%   |
| Intel AX200 Bluetooth                                        | 1        | 7.14%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1        | 7.14%   |
| ASUS Qualcomm Bluetooth 4.1                                  | 1        | 7.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 38       | 41.76%  |
| Nvidia                  | 22       | 24.18%  |
| AMD                     | 21       | 23.08%  |
| C-Media Electronics     | 2        | 2.2%    |
| Soundprese              | 1        | 1.1%    |
| Realtek Semiconductor   | 1        | 1.1%    |
| Medeli Electronics      | 1        | 1.1%    |
| Logitech                | 1        | 1.1%    |
| GN Netcom               | 1        | 1.1%    |
| Corsair                 | 1        | 1.1%    |
| BEHRINGER International | 1        | 1.1%    |
| Argosy Research         | 1        | 1.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9        | 8.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 6.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 5.71%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 5.71%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 5.71%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 4.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 3.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 2.86%   |
| Nvidia High Definition Audio Controller                                    | 3        | 2.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 2.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 2.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.9%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.9%    |
| Soundprese HD-II                                                           | 1        | 0.95%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                          | 1        | 0.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.95%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.95%   |
| Nvidia MCP79 High Definition Audio                                         | 1        | 0.95%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.95%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.95%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.95%   |
| Medeli Electronics USB Audio Device                                        | 1        | 0.95%   |
| Logitech AudioHub Speaker                                                  | 1        | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.95%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 0.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 0.95%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                       | 1        | 0.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 0.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 0.95%   |
| GN Netcom Jabra EVOLVE Link MS                                             | 1        | 0.95%   |
| Corsair VIRTUOSO USB Gaming Headset                                        | 1        | 0.95%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 11       | 26.83%  |
| Micron Technology   | 9        | 21.95%  |
| SK hynix            | 5        | 12.2%   |
| Samsung Electronics | 4        | 9.76%   |
| Crucial             | 3        | 7.32%   |
| Corsair             | 3        | 7.32%   |
| A-DATA Technology   | 2        | 4.88%   |
| Unknown             | 1        | 2.44%   |
| Patriot             | 1        | 2.44%   |
| Kimtigo             | 1        | 2.44%   |
| G.Skill             | 1        | 2.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s        | 5        | 10.87%  |
| Kingston RAM 9905584-015.A00LF 4GB DIMM 1600MT/s           | 3        | 6.52%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s       | 2        | 4.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 1        | 2.17%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s              | 1        | 2.17%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                | 1        | 2.17%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s    | 1        | 2.17%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s       | 1        | 2.17%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1        | 2.17%   |
| Samsung RAM M393B2G70BH0 16GB DIMM DDR3 1866MT/s           | 1        | 2.17%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s        | 1        | 2.17%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s        | 1        | 2.17%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s       | 1        | 2.17%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s            | 1        | 2.17%   |
| Micron RAM 8JTF25664HZ-1G6M1 2048MB SODIMM DDR3 1600MT/s   | 1        | 2.17%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| Micron RAM 16JTF25664AZ-1G4F1 2GB DIMM DDR3 1333MT/s       | 1        | 2.17%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2400MT/s     | 1        | 2.17%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 2.17%   |
| Kingston RAM KHX2666C15/16G 16GB DIMM DDR4 2666MT/s        | 1        | 2.17%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s          | 1        | 2.17%   |
| Kingston RAM 99U5624-001.A00G 8GB SODIMM DDR4 2400MT/s     | 1        | 2.17%   |
| Kingston RAM 99U5403-067.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 2.17%   |
| Kingston RAM 99U5403-050.A00 F 4GB DIMM DDR3 667MT/s       | 1        | 2.17%   |
| Kingston RAM 9905713-030.A00G 8GB DIMM DDR4 2667MT/s       | 1        | 2.17%   |
| Kingston RAM 9905702-017.A00G 8GB DIMM DDR4 2933MT/s       | 1        | 2.17%   |
| Kingston RAM 9905402-413.A00LF 2GB DIMM DDR3 1333MT/s      | 1        | 2.17%   |
| Kimtigo RAM KTR1333U4G 4096MB DIMM DDR3 1333MT/s           | 1        | 2.17%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s        | 1        | 2.17%   |
| Crucial RAM CT4G4DFS824A.C8FBD1 4096MB DIMM DDR4 2400MT/s  | 1        | 2.17%   |
| Crucial RAM BLS8G4D240FSE.16FBD 8GB DIMM DDR4 2400MT/s     | 1        | 2.17%   |
| Crucial RAM BLS8G4D240FSB.16FBD2 8192MB DIMM DDR4 2400MT/s | 1        | 2.17%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s       | 1        | 2.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s   | 1        | 2.17%   |
| Corsair RAM CMD16GX4M2B3000C15 8GB DIMM DDR4 3100MT/s      | 1        | 2.17%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s               | 1        | 2.17%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                | 1        | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 16       | 50%     |
| DDR3  | 13       | 40.63%  |
| SDRAM | 2        | 6.25%   |
| DDR2  | 1        | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 26       | 86.67%  |
| SODIMM | 4        | 13.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 12       | 36.36%  |
| 8192  | 10       | 30.3%   |
| 16384 | 5        | 15.15%  |
| 2048  | 5        | 15.15%  |
| 32768 | 1        | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 11       | 28.95%  |
| 2400  | 5        | 13.16%  |
| 2667  | 4        | 10.53%  |
| 1333  | 3        | 7.89%   |
| 3600  | 2        | 5.26%   |
| 3400  | 2        | 5.26%   |
| 667   | 2        | 5.26%   |
| 3866  | 1        | 2.63%   |
| 3466  | 1        | 2.63%   |
| 3100  | 1        | 2.63%   |
| 2934  | 1        | 2.63%   |
| 2933  | 1        | 2.63%   |
| 2800  | 1        | 2.63%   |
| 2666  | 1        | 2.63%   |
| 1866  | 1        | 2.63%   |
| 1800  | 1        | 2.63%   |

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


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seiko Epson L3110 Series           | 1        | 16.67%  |
| HP DeskJet 2620 All-in-One Printer | 1        | 16.67%  |
| HP DeskJet 2130 series             | 1        | 16.67%  |
| HP Deskjet 2050 J510               | 1        | 16.67%  |
| Canon G2000 series                 | 1        | 16.67%  |
| Canon E400 series                  | 1        | 16.67%  |

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
| Logitech                | 6        | 35.29%  |
| Microsoft               | 3        | 17.65%  |
| Microdia                | 2        | 11.76%  |
| Z-Star Microelectronics | 1        | 5.88%   |
| Philips (or NXP)        | 1        | 5.88%   |
| Huawei Technologies     | 1        | 5.88%   |
| Chicony Electronics     | 1        | 5.88%   |
| Aveo Technology         | 1        | 5.88%   |
| Arkmicro Technologies   | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 3        | 17.65%  |
| Microsoft LifeCam HD-3000             | 2        | 11.76%  |
| Microdia USB 2.0 Camera               | 2        | 11.76%  |
| Z-Star USB2.0 Camera                  | 1        | 5.88%   |
| Philips (or NXP) SPC 1300NC PC Camera | 1        | 5.88%   |
| Microsoft LifeCam Cinema              | 1        | 5.88%   |
| Logitech Webcam Pro 9000              | 1        | 5.88%   |
| Logitech Webcam C310                  | 1        | 5.88%   |
| Logitech HD Pro Webcam C920           | 1        | 5.88%   |
| Huawei HiCamera                       | 1        | 5.88%   |
| Chicony HP High Definition 1MP Webcam | 1        | 5.88%   |
| Aveo USB2.0 UVC PC Camera             | 1        | 5.88%   |
| Arkmicro USB2.0 PC CAMERA             | 1        | 5.88%   |

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
| OmniKey                    | 1        | 50%     |
| Athena Smartcard Solutions | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121              | 1        | 50%     |
| Athena Smartcard Solutions ASEDrive CCID | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 48       | 80%     |
| 1     | 9        | 15%     |
| 3     | 2        | 3.33%   |
| 2     | 1        | 1.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 5        | 31.25%  |
| Graphics card            | 4        | 25%     |
| Communication controller | 3        | 18.75%  |
| Chipcard                 | 2        | 12.5%   |
| Sound                    | 1        | 6.25%   |
| Network                  | 1        | 6.25%   |

