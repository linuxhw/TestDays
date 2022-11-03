Linux in Bosnia and Herzegovina - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bosnia and Herzegovina.

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

Total: 62

| Vendor        | Model                    | Probe                                                      | Date         |
|---------------|--------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | H110M-K                  | [4241008f07](https://linux-hardware.org/?probe=4241008f07) | Oct 16, 2022 |
| ASRock        | H61M-HVGS                | [f646dceb7c](https://linux-hardware.org/?probe=f646dceb7c) | Aug 10, 2022 |
| ASUSTek       | Z97-P                    | [eeb9068dca](https://linux-hardware.org/?probe=eeb9068dca) | Jul 27, 2022 |
| HP            | 0A54h                    | [0efed10555](https://linux-hardware.org/?probe=0efed10555) | Mar 29, 2022 |
| ASUSTek       | H61M-K                   | [456ab60c06](https://linux-hardware.org/?probe=456ab60c06) | Feb 22, 2022 |
| ASUSTek       | H81M-R                   | [95ccf112af](https://linux-hardware.org/?probe=95ccf112af) | Feb 14, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1 | [bc32230a7f](https://linux-hardware.org/?probe=bc32230a7f) | Feb 09, 2022 |
| HP            | 3396                     | [97720dddd1](https://linux-hardware.org/?probe=97720dddd1) | Jan 10, 2022 |
| MSI           | B150 GAMING M3           | [3514e82b43](https://linux-hardware.org/?probe=3514e82b43) | Jan 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS     | [52eb9930ad](https://linux-hardware.org/?probe=52eb9930ad) | Nov 14, 2021 |
| Medion        | MS-7366                  | [da9961f1ee](https://linux-hardware.org/?probe=da9961f1ee) | Nov 04, 2021 |
| Gigabyte      | B450M DS3H-CF            | [63b6ade950](https://linux-hardware.org/?probe=63b6ade950) | Sep 13, 2021 |
| Gigabyte      | GA-990FX-GAMING          | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING          | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| HP            | 1497                     | [e68557fd01](https://linux-hardware.org/?probe=e68557fd01) | Jul 07, 2021 |
| Wistron       | ProLiant ML110 G5        | [bc2d293d15](https://linux-hardware.org/?probe=bc2d293d15) | Jun 18, 2021 |
| Wistron       | ProLiant ML110 G5        | [ef21ac93c3](https://linux-hardware.org/?probe=ef21ac93c3) | Jun 18, 2021 |
| ASRock        | H61M-HVGS                | [3f3962df59](https://linux-hardware.org/?probe=3f3962df59) | May 16, 2021 |
| Gigabyte      | B450M DS3H-CF            | [10dd12b38c](https://linux-hardware.org/?probe=10dd12b38c) | May 15, 2021 |
| ASUSTek       | H81M-A                   | [30aeb41807](https://linux-hardware.org/?probe=30aeb41807) | May 14, 2021 |
| ASUSTek       | H81M-A                   | [bee3da385c](https://linux-hardware.org/?probe=bee3da385c) | Mar 23, 2021 |
| HP            | 198E                     | [85ba542969](https://linux-hardware.org/?probe=85ba542969) | Mar 10, 2021 |
| HP            | 198E                     | [8a79f9e398](https://linux-hardware.org/?probe=8a79f9e398) | Mar 10, 2021 |
| ASUSTek       | P5KPL-AM SE              | [9b37eaa9f8](https://linux-hardware.org/?probe=9b37eaa9f8) | Feb 02, 2021 |
| ASUSTek       | P5KPL-AM SE              | [7d18048067](https://linux-hardware.org/?probe=7d18048067) | Jan 26, 2021 |
| HP            | 1496                     | [7d2d9cd210](https://linux-hardware.org/?probe=7d2d9cd210) | Dec 22, 2020 |
| ASUSTek       | H97-PRO                  | [5532ead8e7](https://linux-hardware.org/?probe=5532ead8e7) | Nov 21, 2020 |
| HP            | 3032h                    | [63d3c61c19](https://linux-hardware.org/?probe=63d3c61c19) | Nov 03, 2020 |
| HP            | 3032h                    | [d8cfe55684](https://linux-hardware.org/?probe=d8cfe55684) | Nov 03, 2020 |
| Gigabyte      | X570 AORUS ELITE WIFI    | [1f8e16d74f](https://linux-hardware.org/?probe=1f8e16d74f) | Oct 25, 2020 |
| ASUSTek       | Z170-P                   | [188328b998](https://linux-hardware.org/?probe=188328b998) | Sep 27, 2020 |
| ASUSTek       | PRIME A320M-K            | [35560a3a70](https://linux-hardware.org/?probe=35560a3a70) | Sep 16, 2020 |
| ECS           | G31T-M7                  | [70c5208ec6](https://linux-hardware.org/?probe=70c5208ec6) | Sep 13, 2020 |
| Dell          | 0M858N A01               | [5b7ae4f768](https://linux-hardware.org/?probe=5b7ae4f768) | Aug 13, 2020 |
| Dell          | 0RF703                   | [e23b194d28](https://linux-hardware.org/?probe=e23b194d28) | Jul 25, 2020 |
| ASUSTek       | Z97-P                    | [d0375fe030](https://linux-hardware.org/?probe=d0375fe030) | Jul 15, 2020 |
| Acer          | Aspire M1200             | [9311c4fa37](https://linux-hardware.org/?probe=9311c4fa37) | Jun 27, 2020 |
| Acer          | Aspire M1200             | [8d9a1aefd5](https://linux-hardware.org/?probe=8d9a1aefd5) | Jun 27, 2020 |
| ASUSTek       | P5G41T-M LX3             | [1a6102d9f3](https://linux-hardware.org/?probe=1a6102d9f3) | Jun 17, 2020 |
| Acer          | Aspire M1200             | [2cbc71cc6f](https://linux-hardware.org/?probe=2cbc71cc6f) | May 24, 2020 |
| ASUSTek       | PRIME H310M-R R2.0       | [c668c517d8](https://linux-hardware.org/?probe=c668c517d8) | Apr 24, 2020 |
| ASUSTek       | PRIME H310M-R R2.0       | [4e3e7a0cca](https://linux-hardware.org/?probe=4e3e7a0cca) | Apr 20, 2020 |
| Gigabyte      | nForce                   | [46e8276491](https://linux-hardware.org/?probe=46e8276491) | Apr 03, 2020 |
| ASUSTek       | P5G41T-M LX2/GB          | [fa5624c697](https://linux-hardware.org/?probe=fa5624c697) | Mar 27, 2020 |
| Wistron       | ProLiant ML110 G5        | [0dbb663114](https://linux-hardware.org/?probe=0dbb663114) | Mar 26, 2020 |
| Wistron       | ProLiant ML110 G5        | [ce73a67dba](https://linux-hardware.org/?probe=ce73a67dba) | Mar 26, 2020 |
| ASUSTek       | P5G41T-M LX2/GB          | [84bed079c2](https://linux-hardware.org/?probe=84bed079c2) | Mar 23, 2020 |
| ASUSTek       | P5G41T-M LX2/GB          | [10793053f1](https://linux-hardware.org/?probe=10793053f1) | Mar 23, 2020 |
| MSI           | GF615M-P33               | [34605f2e7f](https://linux-hardware.org/?probe=34605f2e7f) | Feb 06, 2020 |
| ASUSTek       | PRIME A320M-K            | [64c7222709](https://linux-hardware.org/?probe=64c7222709) | Dec 22, 2019 |
| Dell          | 0RF703                   | [3cc8664913](https://linux-hardware.org/?probe=3cc8664913) | Nov 09, 2019 |
| Pegatron      | Eureka3                  | [5d42e73d08](https://linux-hardware.org/?probe=5d42e73d08) | Oct 20, 2019 |
| Dell          | 0RF703                   | [e97de552d8](https://linux-hardware.org/?probe=e97de552d8) | Jul 29, 2019 |
| Dell          | 0RF703                   | [08019d8b5f](https://linux-hardware.org/?probe=08019d8b5f) | Jul 29, 2019 |
| Dell          | 0MM599                   | [0b9fef01ec](https://linux-hardware.org/?probe=0b9fef01ec) | Jun 19, 2019 |
| Dell          | 0MM599                   | [8376d2c77c](https://linux-hardware.org/?probe=8376d2c77c) | Jun 19, 2019 |
| ASUSTek       | P8H61-M LX3 R2.0         | [aa5f7a836b](https://linux-hardware.org/?probe=aa5f7a836b) | May 04, 2019 |
| ASUSTek       | PRIME A320M-K            | [3aed29ae25](https://linux-hardware.org/?probe=3aed29ae25) | Apr 27, 2019 |
| HP            | 0A64h                    | [ab563902ff](https://linux-hardware.org/?probe=ab563902ff) | Apr 22, 2019 |
| ASUSTek       | P8H61-M LX3 R2.0         | [3ce6d97f47](https://linux-hardware.org/?probe=3ce6d97f47) | Apr 21, 2019 |
| Gigabyte      | Z390 UD                  | [48041296ca](https://linux-hardware.org/?probe=48041296ca) | Mar 15, 2019 |
| ASUSTek       | M2N-SLI                  | [77800cbaf6](https://linux-hardware.org/?probe=77800cbaf6) | Mar 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 7        | 15.91%  |
| Ubuntu 18.04        | 5        | 11.36%  |
| OpenMandriva 4.3    | 4        | 9.09%   |
| Linux Mint 19.1     | 3        | 6.82%   |
| Xubuntu 20.04       | 2        | 4.55%   |
| Linux Mint 20.1     | 2        | 4.55%   |
| KDE neon 20.04      | 2        | 4.55%   |
| Debian 10           | 2        | 4.55%   |
| Zorin 15            | 1        | 2.27%   |
| Ubuntu Unity 21.10  | 1        | 2.27%   |
| Ubuntu Unity 18.04  | 1        | 2.27%   |
| Ubuntu Studio 20.04 | 1        | 2.27%   |
| ROSA R10            | 1        | 2.27%   |
| Pop!_OS 20.10       | 1        | 2.27%   |
| Pop!_OS 20.04       | 1        | 2.27%   |
| Manjaro 20.2        | 1        | 2.27%   |
| Manjaro             | 1        | 2.27%   |
| Lubuntu 18.04       | 1        | 2.27%   |
| Linux Mint 19.3     | 1        | 2.27%   |
| KDE neon 18.04      | 1        | 2.27%   |
| Fedora 33           | 1        | 2.27%   |
| Fedora 32           | 1        | 2.27%   |
| Endless 3.7.8       | 1        | 2.27%   |
| Debian 9            | 1        | 2.27%   |
| Debian 11           | 1        | 2.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 11       | 25.58%  |
| Linux Mint    | 6        | 13.95%  |
| OpenMandriva  | 4        | 9.3%    |
| Debian        | 4        | 9.3%    |
| KDE neon      | 3        | 6.98%   |
| Xubuntu       | 2        | 4.65%   |
| Ubuntu Unity  | 2        | 4.65%   |
| Pop!_OS       | 2        | 4.65%   |
| Manjaro       | 2        | 4.65%   |
| Fedora        | 2        | 4.65%   |
| Zorin         | 1        | 2.33%   |
| Ubuntu Studio | 1        | 2.33%   |
| ROSA          | 1        | 2.33%   |
| Lubuntu       | 1        | 2.33%   |
| Endless       | 1        | 2.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003         | 4        | 7.84%   |
| 5.8.0-59-generic                | 2        | 3.92%   |
| 5.4.0-52-generic                | 2        | 3.92%   |
| 5.3.0-42-generic                | 2        | 3.92%   |
| 4.19.0-13-amd64                 | 2        | 3.92%   |
| 4.18.0-15-generic               | 2        | 3.92%   |
| 4.15.0-94-generic               | 2        | 3.92%   |
| 4.15.0-47-generic               | 2        | 3.92%   |
| 4.15.0-20-generic               | 2        | 3.92%   |
| 5.9.8-2-MANJARO                 | 1        | 1.96%   |
| 5.8.11-200.fc32.x86_64          | 1        | 1.96%   |
| 5.8.0-7630-generic              | 1        | 1.96%   |
| 5.4.0-7634-generic              | 1        | 1.96%   |
| 5.4.0-74-generic                | 1        | 1.96%   |
| 5.4.0-73-generic                | 1        | 1.96%   |
| 5.4.0-67-generic                | 1        | 1.96%   |
| 5.4.0-66-generic                | 1        | 1.96%   |
| 5.4.0-47-generic                | 1        | 1.96%   |
| 5.4.0-42-generic                | 1        | 1.96%   |
| 5.4.0-40-generic                | 1        | 1.96%   |
| 5.4.0-39-generic                | 1        | 1.96%   |
| 5.4.0-37-generic                | 1        | 1.96%   |
| 5.4.0-31-generic                | 1        | 1.96%   |
| 5.3.0-28-generic                | 1        | 1.96%   |
| 5.15.0-50-generic               | 1        | 1.96%   |
| 5.14.18-100.fc33.x86_64         | 1        | 1.96%   |
| 5.13.0-23-generic               | 1        | 1.96%   |
| 5.11.19-200.fc33.x86_64         | 1        | 1.96%   |
| 5.11.0-44-lowlatency            | 1        | 1.96%   |
| 5.11.0-38-generic               | 1        | 1.96%   |
| 5.10.60-1-MANJARO               | 1        | 1.96%   |
| 5.10.34-1-MANJARO               | 1        | 1.96%   |
| 5.10.0-7-amd64                  | 1        | 1.96%   |
| 5.0.0-32-generic                | 1        | 1.96%   |
| 5.0.0-31-generic                | 1        | 1.96%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 1        | 1.96%   |
| 4.9.0-11-amd64                  | 1        | 1.96%   |
| 4.18.0-25-generic               | 1        | 1.96%   |
| 4.15.0-73-generic               | 1        | 1.96%   |
| 4.15.0-173-generic              | 1        | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 11       | 23.4%   |
| 4.15.0  | 6        | 12.77%  |
| 5.16.7  | 4        | 8.51%   |
| 5.8.0   | 3        | 6.38%   |
| 5.3.0   | 3        | 6.38%   |
| 4.18.0  | 3        | 6.38%   |
| 5.11.0  | 2        | 4.26%   |
| 5.0.0   | 2        | 4.26%   |
| 4.19.0  | 2        | 4.26%   |
| 5.9.8   | 1        | 2.13%   |
| 5.8.11  | 1        | 2.13%   |
| 5.15.0  | 1        | 2.13%   |
| 5.14.18 | 1        | 2.13%   |
| 5.13.0  | 1        | 2.13%   |
| 5.11.19 | 1        | 2.13%   |
| 5.10.60 | 1        | 2.13%   |
| 5.10.34 | 1        | 2.13%   |
| 5.10.0  | 1        | 2.13%   |
| 4.9.60  | 1        | 2.13%   |
| 4.9.0   | 1        | 2.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 11       | 23.91%  |
| 4.15    | 6        | 13.04%  |
| 5.8     | 4        | 8.7%    |
| 5.16    | 4        | 8.7%    |
| 5.3     | 3        | 6.52%   |
| 5.11    | 3        | 6.52%   |
| 4.18    | 3        | 6.52%   |
| 5.10    | 2        | 4.35%   |
| 5.0     | 2        | 4.35%   |
| 4.9     | 2        | 4.35%   |
| 4.19    | 2        | 4.35%   |
| 5.9     | 1        | 2.17%   |
| 5.15    | 1        | 2.17%   |
| 5.14    | 1        | 2.17%   |
| 5.13    | 1        | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 38       | 90.48%  |
| i686   | 4        | 9.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 16       | 35.56%  |
| Unknown    | 9        | 20%     |
| XFCE       | 6        | 13.33%  |
| KDE5       | 5        | 11.11%  |
| X-Cinnamon | 3        | 6.67%   |
| Unity      | 2        | 4.44%   |
| KDE        | 2        | 4.44%   |
| LXDE       | 1        | 2.22%   |
| KDE4       | 1        | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 38       | 88.37%  |
| Wayland | 4        | 9.3%    |
| Unknown | 1        | 2.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 66.67%  |
| SDDM    | 5        | 11.9%   |
| TDM     | 3        | 7.14%   |
| LightDM | 3        | 7.14%   |
| GDM     | 2        | 4.76%   |
| KDM     | 1        | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 26       | 59.09%  |
| Unknown | 9        | 20.45%  |
| bs_BA   | 3        | 6.82%   |
| hr_HR   | 2        | 4.55%   |
| sr_RS   | 1        | 2.27%   |
| it_IT   | 1        | 2.27%   |
| en_CA   | 1        | 2.27%   |
| en_AU   | 1        | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 32       | 76.19%  |
| EFI  | 10       | 23.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 31       | 73.81%  |
| Overlay | 5        | 11.9%   |
| Unknown | 4        | 9.52%   |
| Ext2    | 1        | 2.38%   |
| Btrfs   | 1        | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 71.43%  |
| GPT     | 8        | 19.05%  |
| MBR     | 4        | 9.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 85.37%  |
| Yes       | 6        | 14.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 70.73%  |
| Yes       | 12       | 29.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 17       | 41.46%  |
| Hewlett-Packard     | 7        | 17.07%  |
| Gigabyte Technology | 5        | 12.2%   |
| Dell                | 3        | 7.32%   |
| MSI                 | 2        | 4.88%   |
| Wistron             | 1        | 2.44%   |
| Pegatron            | 1        | 2.44%   |
| Medion              | 1        | 2.44%   |
| Fujitsu Siemens     | 1        | 2.44%   |
| ECS                 | 1        | 2.44%   |
| ASRock              | 1        | 2.44%   |
| Acer                | 1        | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 4        | 9.76%   |
| Dell OptiPlex 745                      | 2        | 4.88%   |
| ASUS P8H61-M LX3 R2.0                  | 2        | 4.88%   |
| ASUS P5KPL-AM SE                       | 2        | 4.88%   |
| Wistron ProLiant ML110 G5              | 1        | 2.44%   |
| Pegatron VS170AA-UUZ p6244ch           | 1        | 2.44%   |
| MSI MS-7978                            | 1        | 2.44%   |
| MSI MS-7597                            | 1        | 2.44%   |
| Medion MS-7366                         | 1        | 2.44%   |
| HP ProDesk 400 G2 MT (TPM DP)          | 1        | 2.44%   |
| HP Compaq Elite 8300 CMT               | 1        | 2.44%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 2.44%   |
| HP Compaq dc7700p Small Form Factor    | 1        | 2.44%   |
| HP Compaq dc5750 Small Form Factor     | 1        | 2.44%   |
| HP Compaq 8200 Elite USDT PC           | 1        | 2.44%   |
| HP Compaq 6200 Pro MT PC               | 1        | 2.44%   |
| Gigabyte Z390 UD                       | 1        | 2.44%   |
| Gigabyte X570 AORUS ELITE WIFI         | 1        | 2.44%   |
| Gigabyte nForce                        | 1        | 2.44%   |
| Gigabyte GA-990FX-GAMING               | 1        | 2.44%   |
| Gigabyte B450M DS3H                    | 1        | 2.44%   |
| Fujitsu Siemens ESPRIMO P5730          | 1        | 2.44%   |
| ECS G31T-M7                            | 1        | 2.44%   |
| Dell OptiPlex 760                      | 1        | 2.44%   |
| ASUS Z170-P                            | 1        | 2.44%   |
| ASUS TUF Gaming X570-PLUS              | 1        | 2.44%   |
| ASUS PRIME H310M-R R2.0                | 1        | 2.44%   |
| ASUS PRIME A320M-K                     | 1        | 2.44%   |
| ASUS P5G41T-M LX3                      | 1        | 2.44%   |
| ASUS P5G41T-M LX2/GB                   | 1        | 2.44%   |
| ASUS M2N-SLI                           | 1        | 2.44%   |
| ASUS H61M-K                            | 1        | 2.44%   |
| ASUS H110M-K                           | 1        | 2.44%   |
| ASRock H61M-HVGS                       | 1        | 2.44%   |
| Acer Aspire M1200                      | 1        | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| HP Compaq                | 6        | 14.63%  |
| ASUS All                 | 4        | 9.76%   |
| Dell OptiPlex            | 3        | 7.32%   |
| ASUS PRIME               | 2        | 4.88%   |
| ASUS P8H61-M             | 2        | 4.88%   |
| ASUS P5KPL-AM            | 2        | 4.88%   |
| ASUS P5G41T-M            | 2        | 4.88%   |
| Wistron ProLiant         | 1        | 2.44%   |
| Pegatron VS170AA-UUZ     | 1        | 2.44%   |
| MSI MS-7978              | 1        | 2.44%   |
| MSI MS-7597              | 1        | 2.44%   |
| Medion MS-7366           | 1        | 2.44%   |
| HP ProDesk               | 1        | 2.44%   |
| Gigabyte Z390            | 1        | 2.44%   |
| Gigabyte X570            | 1        | 2.44%   |
| Gigabyte nForce          | 1        | 2.44%   |
| Gigabyte GA-990FX-GAMING | 1        | 2.44%   |
| Gigabyte B450M           | 1        | 2.44%   |
| Fujitsu Siemens ESPRIMO  | 1        | 2.44%   |
| ECS G31T-M7              | 1        | 2.44%   |
| ASUS Z170-P              | 1        | 2.44%   |
| ASUS TUF                 | 1        | 2.44%   |
| ASUS M2N-SLI             | 1        | 2.44%   |
| ASUS H61M-K              | 1        | 2.44%   |
| ASUS H110M-K             | 1        | 2.44%   |
| ASRock H61M-HVGS         | 1        | 2.44%   |
| Acer Aspire              | 1        | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 6        | 14.63%  |
| 2008 | 5        | 12.2%   |
| 2014 | 4        | 9.76%   |
| 2007 | 4        | 9.76%   |
| 2018 | 3        | 7.32%   |
| 2012 | 3        | 7.32%   |
| 2011 | 3        | 7.32%   |
| 2019 | 2        | 4.88%   |
| 2016 | 2        | 4.88%   |
| 2015 | 2        | 4.88%   |
| 2013 | 2        | 4.88%   |
| 2006 | 2        | 4.88%   |
| 2017 | 1        | 2.44%   |
| 2010 | 1        | 2.44%   |
| 2005 | 1        | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 41       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 41       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 9        | 20.93%  |
| 3.01-4.0   | 8        | 18.6%   |
| 8.01-16.0  | 8        | 18.6%   |
| 16.01-24.0 | 6        | 13.95%  |
| 1.01-2.0   | 6        | 13.95%  |
| 2.01-3.0   | 3        | 6.98%   |
| 32.01-64.0 | 1        | 2.33%   |
| 0.51-1.0   | 1        | 2.33%   |
| 0.01-0.5   | 1        | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 23       | 47.92%  |
| 2.01-3.0  | 8        | 16.67%  |
| 4.01-8.0  | 6        | 12.5%   |
| 0.51-1.0  | 6        | 12.5%   |
| 3.01-4.0  | 3        | 6.25%   |
| 8.01-16.0 | 1        | 2.08%   |
| 0.01-0.5  | 1        | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 57.78%  |
| 2      | 13       | 28.89%  |
| 3      | 3        | 6.67%   |
| 5      | 1        | 2.22%   |
| 4      | 1        | 2.22%   |
| 0      | 1        | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 23       | 53.49%  |
| No        | 20       | 46.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 40       | 97.56%  |
| No        | 1        | 2.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 68.29%  |
| Yes       | 13       | 31.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 90.24%  |
| Yes       | 4        | 9.76%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| Bosnia and Herzegovina | 41       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Sarajevo     | 12       | 28.57%  |
| Banja Luka   | 7        | 16.67%  |
| Tuzla        | 2        | 4.76%   |
| Teslic       | 2        | 4.76%   |
| Prnjavor     | 2        | 4.76%   |
| Prijedor     | 2        | 4.76%   |
| Gracanica    | 2        | 4.76%   |
| Zvornik      | 1        | 2.38%   |
| Zepce        | 1        | 2.38%   |
| Zenica       | 1        | 2.38%   |
| Vitez        | 1        | 2.38%   |
| Tarcin       | 1        | 2.38%   |
| Novi Travnik | 1        | 2.38%   |
| Nova Topola  | 1        | 2.38%   |
| Jablanica    | 1        | 2.38%   |
| Foca         | 1        | 2.38%   |
| Drvar        | 1        | 2.38%   |
| Doboj        | 1        | 2.38%   |
| Brcko        | 1        | 2.38%   |
| Bijeljina    | 1        | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 25     | 25.86%  |
| Seagate             | 12       | 16     | 20.69%  |
| Kingston            | 10       | 12     | 17.24%  |
| Hitachi             | 6        | 6      | 10.34%  |
| Samsung Electronics | 5        | 7      | 8.62%   |
| Toshiba             | 3        | 3      | 5.17%   |
| Transcend           | 1        | 2      | 1.72%   |
| ORGE                | 1        | 1      | 1.72%   |
| Maxtor              | 1        | 1      | 1.72%   |
| Intel               | 1        | 1      | 1.72%   |
| Fujitsu             | 1        | 1      | 1.72%   |
| China               | 1        | 3      | 1.72%   |
| ASMT                | 1        | 1      | 1.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Hitachi HDS721050CLA362 500GB    | 3        | 4.62%   |
| Toshiba DT01ACA050 500GB         | 2        | 3.08%   |
| Seagate ST3500413AS 500GB        | 2        | 3.08%   |
| Seagate ST250LT021-1AF14C 250GB  | 2        | 3.08%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 3.08%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 3.08%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 1.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 1.54%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD | 1        | 1.54%   |
| WDC WD800JD-75MSA3 80GB          | 1        | 1.54%   |
| WDC WD800JD-60LSA5 80GB          | 1        | 1.54%   |
| WDC WD800JD-00MSA1 80GB          | 1        | 1.54%   |
| WDC WD7500BPVX-22JC3T0 752GB     | 1        | 1.54%   |
| WDC WD7500AACS-00D6B0 752GB      | 1        | 1.54%   |
| WDC WD5000LPVT-22G33T0 500GB     | 1        | 1.54%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 1        | 1.54%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 1.54%   |
| WDC WD40EZRZ-75GXCB0 4TB         | 1        | 1.54%   |
| WDC WD40EZAZ-00ZGHB0 4TB         | 1        | 1.54%   |
| WDC WD3200SD-01KNB0 320GB        | 1        | 1.54%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 1.54%   |
| WDC WD2000JD-00HBB0 200GB        | 1        | 1.54%   |
| WDC WD1600AAJS-00B4A0 160GB      | 1        | 1.54%   |
| WDC WD15EARS-00S8B1 1TB          | 1        | 1.54%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1        | 1.54%   |
| Transcend TS120GSSD220S 120GB    | 1        | 1.54%   |
| Toshiba DT01ACA100 1TB           | 1        | 1.54%   |
| Seagate STM3500418AS 500GB       | 1        | 1.54%   |
| Seagate ST980811AS 80GB          | 1        | 1.54%   |
| Seagate ST8000AS0002-1NA17Z 8TB  | 1        | 1.54%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 1.54%   |
| Seagate ST3500630AS 500GB        | 1        | 1.54%   |
| Seagate ST3250820AS 250GB        | 1        | 1.54%   |
| Seagate ST3250318AS 250GB        | 1        | 1.54%   |
| Seagate ST3250312AS 250GB        | 1        | 1.54%   |
| Seagate ST3120813AS 120GB        | 1        | 1.54%   |
| Seagate ST3000DM001-1CH166 3TB   | 1        | 1.54%   |
| Samsung SSD 850 EVO 250GB        | 1        | 1.54%   |
| Samsung SSD 850 EVO 120GB        | 1        | 1.54%   |
| Samsung SSD 840 PRO Series 256GB | 1        | 1.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 22     | 34.21%  |
| Seagate             | 12       | 16     | 31.58%  |
| Hitachi             | 6        | 6      | 15.79%  |
| Toshiba             | 3        | 3      | 7.89%   |
| Samsung Electronics | 2        | 2      | 5.26%   |
| Maxtor              | 1        | 1      | 2.63%   |
| Fujitsu             | 1        | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 8        | 10     | 44.44%  |
| WDC                 | 3        | 3      | 16.67%  |
| Samsung Electronics | 3        | 5      | 16.67%  |
| Transcend           | 1        | 2      | 5.56%   |
| Intel               | 1        | 1      | 5.56%   |
| China               | 1        | 3      | 5.56%   |
| ASMT                | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 33       | 51     | 64.71%  |
| SSD     | 15       | 25     | 29.41%  |
| NVMe    | 2        | 2      | 3.92%   |
| Unknown | 1        | 1      | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 38       | 75     | 90.48%  |
| SAS  | 2        | 2      | 4.76%   |
| NVMe | 2        | 2      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 37       | 63     | 80.43%  |
| 0.51-1.0   | 5        | 7      | 10.87%  |
| 3.01-4.0   | 1        | 2      | 2.17%   |
| 2.01-3.0   | 1        | 2      | 2.17%   |
| 1.01-2.0   | 1        | 1      | 2.17%   |
| 4.01-10.0  | 1        | 1      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 51-100         | 9        | 20.45%  |
| 101-250        | 8        | 18.18%  |
| 1-20           | 7        | 15.91%  |
| 251-500        | 6        | 13.64%  |
| 501-1000       | 5        | 11.36%  |
| 21-50          | 3        | 6.82%   |
| 1001-2000      | 3        | 6.82%   |
| More than 3000 | 2        | 4.55%   |
| Unknown        | 1        | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 23       | 47.92%  |
| 21-50     | 8        | 16.67%  |
| 251-500   | 4        | 8.33%   |
| 101-250   | 4        | 8.33%   |
| 51-100    | 4        | 8.33%   |
| 501-1000  | 3        | 6.25%   |
| 2001-3000 | 1        | 2.08%   |
| Unknown   | 1        | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 1      | 20%     |
| Seagate ST3120813AS 120GB        | 1        | 1      | 20%     |
| Seagate ST3000DM001-1CH166 3TB   | 1        | 2      | 20%     |
| Seagate ST250LT021-1AF14C 250GB  | 1        | 1      | 20%     |
| Hitachi HDS721050CLA362 500GB    | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 4      | 60%     |
| WDC     | 1        | 1      | 20%     |
| Hitachi | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 4      | 75%     |
| Hitachi | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 5      | 75%     |
| SSD  | 1        | 1      | 25%     |

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
| Detected | 32       | 58     | 74.42%  |
| Works    | 7        | 15     | 16.28%  |
| Malfunc  | 4        | 6      | 9.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 30       | 69.77%  |
| AMD                         | 7        | 16.28%  |
| Nvidia                      | 4        | 9.3%    |
| Kingston Technology Company | 2        | 4.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 7.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 6.15%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 6.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 4.62%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 4.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 4.62%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 3.08%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 3.08%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1        | 1.54%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 1.54%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.54%   |
| Nvidia MCP61 IDE                                                                        | 1        | 1.54%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 1.54%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                              | 1        | 1.54%   |
| Nvidia CK804 Serial ATA Controller                                                      | 1        | 1.54%   |
| Nvidia CK804 IDE                                                                        | 1        | 1.54%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1        | 1.54%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 1.54%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.54%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.54%   |
| Intel 82Q963/Q965 PT IDER Controller                                                    | 1        | 1.54%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 1.54%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.54%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.54%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.54%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 1        | 1.54%   |
| AMD SB600 IDE                                                                           | 1        | 1.54%   |
| AMD FCH SATA Controller D                                                               | 1        | 1.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 22       | 45.83%  |
| SATA | 22       | 45.83%  |
| RAID | 2        | 4.17%   |
| NVMe | 2        | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 31       | 75.61%  |
| AMD    | 10       | 24.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 4.88%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 2        | 4.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 4.88%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 2        | 4.88%   |
| Intel Xeon CPU X3210 @ 2.13GHz              | 1        | 2.44%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 2.44%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 2.44%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 2.44%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 2.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 2.44%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 2.44%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 2.44%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 2.44%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 2.44%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 2.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 2.44%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 2.44%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 2.44%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1        | 2.44%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 2.44%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 1        | 2.44%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 1        | 2.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 2.44%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 2.44%   |
| Intel Core 2 CPU 6700 @ 2.66GHz             | 1        | 2.44%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 1        | 2.44%   |
| Intel Celeron D CPU 3.33GHz                 | 1        | 2.44%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 2.44%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 2.44%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 2.44%   |
| AMD Phenom 8650 Triple-Core Processor       | 1        | 2.44%   |
| AMD FX-4100 Quad-Core Processor             | 1        | 2.44%   |
| AMD Athlon X4 950 Quad Core Processor       | 1        | 2.44%   |
| AMD Athlon II X3 450 Processor              | 1        | 2.44%   |
| AMD Athlon 64 X2 Dual Core Processor 6400+  | 1        | 2.44%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 1        | 2.44%   |
| AMD Athlon 64 Processor 3000+               | 1        | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 8        | 19.51%  |
| Intel Pentium Dual-Core | 4        | 9.76%   |
| Intel Core i3           | 4        | 9.76%   |
| Intel Core i7           | 3        | 7.32%   |
| Intel Pentium           | 2        | 4.88%   |
| Intel Core 2 Quad       | 2        | 4.88%   |
| Intel Core 2 Duo        | 2        | 4.88%   |
| Intel Core 2            | 2        | 4.88%   |
| Intel Celeron           | 2        | 4.88%   |
| AMD Ryzen 5             | 2        | 4.88%   |
| AMD Athlon 64 X2        | 2        | 4.88%   |
| Intel Xeon              | 1        | 2.44%   |
| Intel Celeron D         | 1        | 2.44%   |
| AMD Ryzen 9             | 1        | 2.44%   |
| AMD Phenom              | 1        | 2.44%   |
| AMD FX                  | 1        | 2.44%   |
| AMD Athlon X4           | 1        | 2.44%   |
| AMD Athlon II X3        | 1        | 2.44%   |
| AMD Athlon 64           | 1        | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 17       | 41.46%  |
| 4      | 15       | 36.59%  |
| 1      | 4        | 9.76%   |
| 3      | 2        | 4.88%   |
| 12     | 1        | 2.44%   |
| 8      | 1        | 2.44%   |
| 6      | 1        | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 41       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 75.61%  |
| 2      | 10       | 24.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 38       | 92.68%  |
| Unknown        | 3        | 7.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 21.43%  |
| 0x1067a    | 6        | 14.29%  |
| 0x306c3    | 5        | 11.9%   |
| 0x206a7    | 4        | 9.52%   |
| 0x506e3    | 3        | 7.14%   |
| 0x306a9    | 2        | 4.76%   |
| 0xf65      | 1        | 2.38%   |
| 0x906ec    | 1        | 2.38%   |
| 0x906eb    | 1        | 2.38%   |
| 0x6fb      | 1        | 2.38%   |
| 0x6f6      | 1        | 2.38%   |
| 0x6f2      | 1        | 2.38%   |
| 0x10676    | 1        | 2.38%   |
| 0x10661    | 1        | 2.38%   |
| 0x08701021 | 1        | 2.38%   |
| 0x08108109 | 1        | 2.38%   |
| 0x06006118 | 1        | 2.38%   |
| 0x0600063d | 1        | 2.38%   |
| 0x01000083 | 1        | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 8        | 19.51%  |
| SandyBridge | 5        | 12.2%   |
| Haswell     | 5        | 12.2%   |
| Core        | 5        | 12.2%   |
| Skylake     | 3        | 7.32%   |
| K8 Hammer   | 3        | 7.32%   |
| Zen+        | 2        | 4.88%   |
| KabyLake    | 2        | 4.88%   |
| K10         | 2        | 4.88%   |
| IvyBridge   | 2        | 4.88%   |
| Zen 2       | 1        | 2.44%   |
| NetBurst    | 1        | 2.44%   |
| Excavator   | 1        | 2.44%   |
| Bulldozer   | 1        | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 15       | 34.88%  |
| AMD                        | 15       | 34.88%  |
| Nvidia                     | 12       | 27.91%  |
| Matrox Electronics Systems | 1        | 2.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 8.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 6.52%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 4.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 4.35%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 4.35%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 2.17%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 2.17%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 2.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 2.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 2.17%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.17%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 2.17%   |
| Nvidia GF106 [GeForce GT 440]                                               | 1        | 2.17%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 2.17%   |
| Nvidia G84 [GeForce 8600 GTS]                                               | 1        | 2.17%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 1        | 2.17%   |
| Intel HD Graphics 530                                                       | 1        | 2.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.17%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 2.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 2.17%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 1        | 2.17%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 1        | 2.17%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 2.17%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 1        | 2.17%   |
| AMD RV350 [Radeon 9550] (Secondary)                                         | 1        | 2.17%   |
| AMD RV350 [Radeon 9550]                                                     | 1        | 2.17%   |
| AMD RS482/RS485 [Radeon Xpress 1100/1150]                                   | 1        | 2.17%   |
| AMD RS480 [Radeon Xpress 1150] (Secondary)                                  | 1        | 2.17%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                   | 1        | 2.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.17%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 1        | 2.17%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 2.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 2.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 2.17%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 2.17%   |
| AMD Barts PRO [Radeon HD 6850]                                              | 1        | 2.17%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.17%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 14       | 33.33%  |
| 1 x AMD    | 13       | 30.95%  |
| 1 x Nvidia | 12       | 28.57%  |
| 3 x AMD    | 1        | 2.38%   |
| 2 x AMD    | 1        | 2.38%   |
| 1 x Matrox | 1        | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 32       | 76.19%  |
| Proprietary | 7        | 16.67%  |
| Unknown     | 3        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 42.86%  |
| 1.01-2.0   | 8        | 19.05%  |
| 0.01-0.5   | 7        | 16.67%  |
| 0.51-1.0   | 6        | 14.29%  |
| 7.01-8.0   | 1        | 2.38%   |
| 5.01-6.0   | 1        | 2.38%   |
| 3.01-4.0   | 1        | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 28.21%  |
| Goldstar             | 5        | 12.82%  |
| AOC                  | 4        | 10.26%  |
| Philips              | 3        | 7.69%   |
| Unknown              | 2        | 5.13%   |
| Sony                 | 2        | 5.13%   |
| IBM                  | 2        | 5.13%   |
| Fujitsu Siemens      | 2        | 5.13%   |
| Dell                 | 2        | 5.13%   |
| ViewSonic            | 1        | 2.56%   |
| Vestel Elektronik    | 1        | 2.56%   |
| BenQ                 | 1        | 2.56%   |
| Belinea              | 1        | 2.56%   |
| ASUSTek Computer     | 1        | 2.56%   |
| Ancor Communications | 1        | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| IBM C170 CRT IBM1A51 1280x1024 310x230mm 15.2-inch                     | 2        | 4.88%   |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch                          | 2        | 4.88%   |
| ViewSonic VA702 VSC1C1C 1280x1024 338x270mm 17.0-inch                  | 1        | 2.44%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1        | 2.44%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                   | 1        | 2.44%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B_101920 1280x1024                 | 1        | 2.44%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1        | 2.44%   |
| Sony TV *00 SNY4904 3840x2160                                          | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch    | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM03E2 1680x1050 433x271mm 20.1-inch   | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch   | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM0169 1280x1024 376x301mm 19.0-inch   | 1        | 2.44%   |
| Samsung Electronics SAMTRON 50X/V STN0011 1024x768 304x228mm 15.0-inch | 1        | 2.44%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch      | 1        | 2.44%   |
| Samsung Electronics S24D391 SAM0B87 1920x1080 521x293mm 23.5-inch      | 1        | 2.44%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1        | 2.44%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch      | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch   | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1        | 2.44%   |
| Philips LCD Monitor FTV                                                | 1        | 2.44%   |
| Philips LCD Monitor 170S 3200x1080                                     | 1        | 2.44%   |
| Philips 192EL PHLC04E 1366x768 410x230mm 18.5-inch                     | 1        | 2.44%   |
| Philips 170S PHL0856 1280x1024 338x270mm 17.0-inch                     | 1        | 2.44%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                    | 1        | 2.44%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch               | 1        | 2.44%   |
| Goldstar L227W GSM566F 1680x1050 474x296mm 22.0-inch                   | 1        | 2.44%   |
| Goldstar IPS231 GSM5816 1920x1080 510x290mm 23.1-inch                  | 1        | 2.44%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 1        | 2.44%   |
| Fujitsu Siemens B22W-6 LED FUS07F3 1680x1050 474x296mm 22.0-inch       | 1        | 2.44%   |
| Fujitsu Siemens A17-1 FUS0565 1280x1024 340x270mm 17.1-inch            | 1        | 2.44%   |
| Dell S2409W DELA038 1920x1080 531x298mm 24.0-inch                      | 1        | 2.44%   |
| Dell 2208WFP DEL403C 1680x1050 473x296mm 22.0-inch                     | 1        | 2.44%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                     | 1        | 2.44%   |
| Belinea b.disp2.1_22W MAX08A0 1680x1050 474x297mm 22.0-inch            | 1        | 2.44%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch           | 1        | 2.44%   |
| AOC LCD Monitor 24E1W1 1920x1080                                       | 1        | 2.44%   |
| AOC LCD Monitor 2262w 1920x1080                                        | 1        | 2.44%   |
| Ancor Communications ASUS VH228 ACI22FC 1920x1080 477x268mm 21.5-inch  | 1        | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 30.77%  |
| 1280x1024 (SXGA)   | 8        | 20.51%  |
| 1680x1050 (WSXGA+) | 6        | 15.38%  |
| 3840x2160 (4K)     | 4        | 10.26%  |
| 1440x900 (WXGA+)   | 2        | 5.13%   |
| 1366x768 (WXGA)    | 2        | 5.13%   |
| 3200x1080          | 1        | 2.56%   |
| 1600x900 (HD+)     | 1        | 2.56%   |
| 1360x768           | 1        | 2.56%   |
| 1024x768 (XGA)     | 1        | 2.56%   |
| Unknown            | 1        | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 17.5%   |
| 19      | 4        | 10%     |
| 27      | 3        | 7.5%    |
| 24      | 3        | 7.5%    |
| 23      | 3        | 7.5%    |
| 22      | 3        | 7.5%    |
| 21      | 3        | 7.5%    |
| 17      | 3        | 7.5%    |
| 15      | 3        | 7.5%    |
| 72      | 2        | 5%      |
| 20      | 2        | 5%      |
| 18      | 2        | 5%      |
| 84      | 1        | 2.5%    |
| 31      | 1        | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 12       | 31.58%  |
| 501-600     | 7        | 18.42%  |
| Unknown     | 7        | 18.42%  |
| 301-350     | 6        | 15.79%  |
| 1501-2000   | 3        | 7.89%   |
| 351-400     | 2        | 5.26%   |
| 601-700     | 1        | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 15       | 41.67%  |
| 16/10   | 6        | 16.67%  |
| Unknown | 6        | 16.67%  |
| 5/4     | 5        | 13.89%  |
| 4/3     | 3        | 8.33%   |
| 3/2     | 1        | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 26.32%  |
| Unknown        | 7        | 18.42%  |
| 151-200        | 6        | 15.79%  |
| 141-150        | 5        | 13.16%  |
| More than 1000 | 3        | 7.89%   |
| 301-350        | 3        | 7.89%   |
| 111-120        | 2        | 5.26%   |
| 351-500        | 1        | 2.63%   |
| 101-110        | 1        | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 55.56%  |
| Unknown | 7        | 19.44%  |
| 101-120 | 5        | 13.89%  |
| 1-50    | 2        | 5.56%   |
| 161-240 | 2        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 78.57%  |
| 2     | 7        | 16.67%  |
| 0     | 2        | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 19       | 35.19%  |
| Intel                                  | 9        | 16.67%  |
| Qualcomm Atheros                       | 5        | 9.26%   |
| Ralink Technology                      | 3        | 5.56%   |
| Qualcomm Atheros Communications        | 3        | 5.56%   |
| Nvidia                                 | 3        | 5.56%   |
| TP-Link                                | 2        | 3.7%    |
| Sony Ericsson Mobile Communications AB | 2        | 3.7%    |
| Broadcom Limited                       | 2        | 3.7%    |
| Broadcom                               | 2        | 3.7%    |
| Ralink                                 | 1        | 1.85%   |
| Mercucys                               | 1        | 1.85%   |
| Marvell Technology Group               | 1        | 1.85%   |
| ICS Advent                             | 1        | 1.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 16       | 29.09%  |
| Ralink MT7601U Wireless Adapter                                     | 3        | 5.45%   |
| Qualcomm Atheros AR9271 802.11n                                     | 3        | 5.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 5.45%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 3        | 5.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 2        | 3.64%   |
| Sony Ericsson Mobile AB D2005                                       | 2        | 3.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 3.64%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express             | 2        | 3.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                     | 1        | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 1.82%   |
| Realtek 802.11ac NIC                                                | 1        | 1.82%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 1.82%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                          | 1        | 1.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 1.82%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 1.82%   |
| Nvidia MCP73 Ethernet                                               | 1        | 1.82%   |
| Nvidia CK8S Ethernet Controller                                     | 1        | 1.82%   |
| Nvidia CK804 Ethernet Controller                                    | 1        | 1.82%   |
| Mercucys 802.11n NIC                                                | 1        | 1.82%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller             | 1        | 1.82%   |
| Intel I211 Gigabit Network Connection                               | 1        | 1.82%   |
| Intel Ethernet Connection (2) I218-V                                | 1        | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1        | 1.82%   |
| Intel 82566DM Gigabit Network Connection                            | 1        | 1.82%   |
| ICS Advent DM9601 Fast Ethernet Adapter                             | 1        | 1.82%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express     | 1        | 1.82%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express     | 1        | 1.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 3        | 23.08%  |
| Qualcomm Atheros Communications | 3        | 23.08%  |
| TP-Link                         | 2        | 15.38%  |
| Realtek Semiconductor           | 1        | 7.69%   |
| Ralink                          | 1        | 7.69%   |
| Qualcomm Atheros                | 1        | 7.69%   |
| Mercucys                        | 1        | 7.69%   |
| Intel                           | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                     | 3        | 23.08%  |
| Qualcomm Atheros AR9271 802.11n                                     | 3        | 23.08%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 2        | 15.38%  |
| Realtek 802.11ac NIC                                                | 1        | 7.69%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 7.69%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 7.69%   |
| Mercucys 802.11n NIC                                                | 1        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1        | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 18       | 42.86%  |
| Intel                                  | 9        | 21.43%  |
| Qualcomm Atheros                       | 4        | 9.52%   |
| Nvidia                                 | 3        | 7.14%   |
| Sony Ericsson Mobile Communications AB | 2        | 4.76%   |
| Broadcom Limited                       | 2        | 4.76%   |
| Broadcom                               | 2        | 4.76%   |
| Marvell Technology Group               | 1        | 2.38%   |
| ICS Advent                             | 1        | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 38.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 7.14%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 7.14%   |
| Sony Ericsson Mobile AB D2005                                     | 2        | 4.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 4.76%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 4.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 2.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.38%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.38%   |
| Nvidia MCP73 Ethernet                                             | 1        | 2.38%   |
| Nvidia CK8S Ethernet Controller                                   | 1        | 2.38%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 2.38%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 2.38%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.38%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.38%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 2.38%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 2.38%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 2.38%   |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express   | 1        | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 40       | 75.47%  |
| WiFi     | 13       | 24.53%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 75.61%  |
| WiFi     | 10       | 24.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 78.57%  |
| 2     | 5        | 11.9%   |
| 0     | 4        | 9.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 1        | 25%     |
| Integrated System Solution | 1        | 25%     |
| Cambridge Silicon Radio    | 1        | 25%     |
| Broadcom                   | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 25%     |
| Integrated System Solution Bluetooth Device         | 1        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 25%     |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 29       | 46.77%  |
| AMD                 | 16       | 25.81%  |
| Nvidia              | 13       | 20.97%  |
| VIA Technologies    | 1        | 1.61%   |
| Logitech            | 1        | 1.61%   |
| Creative Labs       | 1        | 1.61%   |
| C-Media Electronics | 1        | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 8.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 7.35%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 4.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 4.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 4.41%   |
| Nvidia High Definition Audio Controller                                    | 2        | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 2.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 2.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 2.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.94%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 2.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 2.94%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.94%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 1        | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.47%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 1.47%   |
| Nvidia nForce3 250Gb AC'97 Audio Controller                                | 1        | 1.47%   |
| Nvidia MCP73 High Definition Audio                                         | 1        | 1.47%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.47%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.47%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 1.47%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 1.47%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 1.47%   |
| Logitech ClearChat Pro USB                                                 | 1        | 1.47%   |
| Intel USB PnP Sound Device                                                 | 1        | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.47%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 1.47%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.47%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                  | 1        | 1.47%   |
| C-Media Electronics CM6501                                                 | 1        | 1.47%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.47%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 1.47%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 1.47%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 1.47%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Kingston          | 9        | 50%     |
| Unknown           | 4        | 22.22%  |
| SK hynix          | 3        | 16.67%  |
| Micron Technology | 1        | 5.56%   |
| Corsair           | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 2        | 9.09%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s                   | 2        | 9.09%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                | 1        | 4.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                             | 1        | 4.55%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                                 | 1        | 4.55%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                                | 1        | 4.55%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                              | 1        | 4.55%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                    | 1        | 4.55%   |
| SK hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 1333MT/s                       | 1        | 4.55%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s                    | 1        | 4.55%   |
| Micron RAM 16HTF25664AY-800G1 2GB DIMM DDR2 800MT/s                     | 1        | 4.55%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                    | 1        | 4.55%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                       | 1        | 4.55%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s                     | 1        | 4.55%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s                   | 1        | 4.55%   |
| Kingston RAM 99U5584-009.A00LF 4GB DIMM DDR3 1600MT/s                   | 1        | 4.55%   |
| Kingston RAM 99U5584-007.A 4GB DIMM DDR3 1333MT/s                       | 1        | 4.55%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s                | 1        | 4.55%   |
| Kingston RAM 393955353432392D3030372E4130304C4600 2GB DIMM DDR2 800MT/s | 1        | 4.55%   |
| Corsair RAM CMK16GX4M2B2800C14 8GB DIMM DDR4 2800MT/s                   | 1        | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 8        | 47.06%  |
| DDR2    | 4        | 23.53%  |
| DDR4    | 3        | 17.65%  |
| DDR     | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 16       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 7        | 36.84%  |
| 2048 | 5        | 26.32%  |
| 4096 | 4        | 21.05%  |
| 1024 | 3        | 15.79%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 4        | 20%     |
| 800   | 4        | 20%     |
| 1867  | 2        | 10%     |
| 1866  | 2        | 10%     |
| 1333  | 2        | 10%     |
| 3600  | 1        | 5%      |
| 3400  | 1        | 5%      |
| 2800  | 1        | 5%      |
| 1800  | 1        | 5%      |
| 1066  | 1        | 5%      |
| 333   | 1        | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| HP DeskJet F2100 Printer series | 1        | 100%    |

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


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Logitech  | 5        | 83.33%  |
| Guillemot | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Logitech Webcam C270         | 1        | 16.67%  |
| Logitech Webcam C210         | 1        | 16.67%  |
| Logitech Webcam C170         | 1        | 16.67%  |
| Logitech QuickCam Vision Pro | 1        | 16.67%  |
| Logitech HD Webcam C510      | 1        | 16.67%  |
| Guillemot Hercules HD Twist  | 1        | 16.67%  |

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
| 0     | 39       | 92.86%  |
| 1     | 3        | 7.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 3        | 100%    |

