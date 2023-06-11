Linux in Kenya - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Kenya.

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

Total: 55

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Unknown  | Q-790                    | [5f41d7d182](https://linux-hardware.org/?probe=5f41d7d182) | Apr 04, 2023 |
| HP       | 3047h                    | [bdb6af834f](https://linux-hardware.org/?probe=bdb6af834f) | Feb 08, 2023 |
| Dell     | 0C8810                   | [1df9a88e4a](https://linux-hardware.org/?probe=1df9a88e4a) | Feb 06, 2023 |
| Intel    | DG35EC AAE29266-205      | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| ASRock   | X570 Steel Legend        | [0de958194e](https://linux-hardware.org/?probe=0de958194e) | Dec 15, 2022 |
| ASRock   | X570 Steel Legend        | [84c7e04946](https://linux-hardware.org/?probe=84c7e04946) | Dec 08, 2022 |
| ASRock   | X570 Steel Legend        | [580fb6172f](https://linux-hardware.org/?probe=580fb6172f) | Dec 07, 2022 |
| Dell     | 0M5DCD A00               | [c3049c59a8](https://linux-hardware.org/?probe=c3049c59a8) | Oct 30, 2022 |
| Dell     | 0M5DCD A00               | [daae18ab91](https://linux-hardware.org/?probe=daae18ab91) | Oct 30, 2022 |
| Gigabyte | TRX40 AORUS PRO WIFI     | [85f2638273](https://linux-hardware.org/?probe=85f2638273) | Oct 05, 2022 |
| Dell     | 040DDP A01               | [20d37d51bd](https://linux-hardware.org/?probe=20d37d51bd) | Sep 21, 2022 |
| Dell     | 040DDP A01               | [cabebaa0e6](https://linux-hardware.org/?probe=cabebaa0e6) | Sep 21, 2022 |
| Foxconn  | 2ABF                     | [6d7ce1962d](https://linux-hardware.org/?probe=6d7ce1962d) | Aug 24, 2022 |
| HP       | 097Ch                    | [ac391817bc](https://linux-hardware.org/?probe=ac391817bc) | Aug 19, 2022 |
| HP       | 1493                     | [2925e7a321](https://linux-hardware.org/?probe=2925e7a321) | Aug 01, 2022 |
| HP       | 3397                     | [0679103825](https://linux-hardware.org/?probe=0679103825) | Jun 13, 2022 |
| HP       | 3397                     | [e86ba79fcf](https://linux-hardware.org/?probe=e86ba79fcf) | Jun 09, 2022 |
| Dell     | 0HHV7N A00               | [1f7a666022](https://linux-hardware.org/?probe=1f7a666022) | Jun 02, 2022 |
| Lenovo   | NOK                      | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Dell     | 0773VG A02               | [ec8ec429fc](https://linux-hardware.org/?probe=ec8ec429fc) | Mar 07, 2022 |
| Dell     | 055H3G A01               | [7e00973942](https://linux-hardware.org/?probe=7e00973942) | Mar 06, 2022 |
| Dell     | 055H3G A01               | [05f63f2396](https://linux-hardware.org/?probe=05f63f2396) | Feb 04, 2022 |
| Gigabyte | H110M-A-CF               | [e6a3a69257](https://linux-hardware.org/?probe=e6a3a69257) | Jan 29, 2022 |
| HP       | 83E0                     | [4a54d6921c](https://linux-hardware.org/?probe=4a54d6921c) | Jan 13, 2022 |
| Gigabyte | B450 I AORUS PRO WIFI-CF | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Dell     | 0R790T A00               | [b5a01103fd](https://linux-hardware.org/?probe=b5a01103fd) | Sep 14, 2021 |
| Dell     | 0R790T A00               | [a5290e7cb6](https://linux-hardware.org/?probe=a5290e7cb6) | Sep 14, 2021 |
| Acer     | Veriton X680G            | [3b8774337b](https://linux-hardware.org/?probe=3b8774337b) | Jul 23, 2021 |
| MSI      | B450 TOMAHAWK            | [8513c961a4](https://linux-hardware.org/?probe=8513c961a4) | Jun 21, 2021 |
| Dell     | 0HN7XN A01               | [2c35ee27d9](https://linux-hardware.org/?probe=2c35ee27d9) | May 20, 2021 |
| Dell     | 0773VG A02               | [a4d5cb7e11](https://linux-hardware.org/?probe=a4d5cb7e11) | Mar 10, 2021 |
| MSI      | B450 TOMAHAWK            | [f56f2da985](https://linux-hardware.org/?probe=f56f2da985) | Jan 28, 2021 |
| HP       | 3396                     | [12e6dc258e](https://linux-hardware.org/?probe=12e6dc258e) | Oct 31, 2020 |
| HP       | 3396                     | [876ee024dc](https://linux-hardware.org/?probe=876ee024dc) | Oct 31, 2020 |
| MSI      | B450 TOMAHAWK            | [6ea891ad6b](https://linux-hardware.org/?probe=6ea891ad6b) | Oct 13, 2020 |
| Dell     | 0773VG A02               | [8307343ab3](https://linux-hardware.org/?probe=8307343ab3) | Oct 09, 2020 |
| Dell     | 0773VG A02               | [2c6d570678](https://linux-hardware.org/?probe=2c6d570678) | Oct 09, 2020 |
| MSI      | B450 TOMAHAWK            | [dc38793462](https://linux-hardware.org/?probe=dc38793462) | Sep 08, 2020 |
| MSI      | 0A90                     | [4f8d53458d](https://linux-hardware.org/?probe=4f8d53458d) | Aug 11, 2020 |
| MSI      | 0A90                     | [04bdc6569a](https://linux-hardware.org/?probe=04bdc6569a) | Aug 09, 2020 |
| MSI      | 2AE0                     | [54a32fea6e](https://linux-hardware.org/?probe=54a32fea6e) | Aug 02, 2020 |
| Dell     | 0VNP2H A00               | [de21e4bff4](https://linux-hardware.org/?probe=de21e4bff4) | Jul 04, 2020 |
| HP       | 0AA8h                    | [e60c30f572](https://linux-hardware.org/?probe=e60c30f572) | Jun 25, 2020 |
| HP       | 0AA8h                    | [4017115305](https://linux-hardware.org/?probe=4017115305) | Jun 19, 2020 |
| HP       | 0AA8h                    | [752505c134](https://linux-hardware.org/?probe=752505c134) | Jun 17, 2020 |
| HP       | 3032h                    | [8aa1dd8ecd](https://linux-hardware.org/?probe=8aa1dd8ecd) | Jun 13, 2020 |
| Dell     | 0PU052                   | [5d99be49f0](https://linux-hardware.org/?probe=5d99be49f0) | May 31, 2020 |
| Dell     | 0PU052                   | [6b4292fc06](https://linux-hardware.org/?probe=6b4292fc06) | May 30, 2020 |
| Dell     | 0G214D A00               | [a8caa085de](https://linux-hardware.org/?probe=a8caa085de) | May 04, 2020 |
| Gigabyte | Z68XP-UD3                | [a26feb7507](https://linux-hardware.org/?probe=a26feb7507) | Apr 18, 2020 |
| HP       | 0B4Ch D                  | [2807f4c586](https://linux-hardware.org/?probe=2807f4c586) | Mar 12, 2020 |
| HP       | 09F0h                    | [bff6b4f556](https://linux-hardware.org/?probe=bff6b4f556) | Jan 21, 2020 |
| HP       | 09F0h                    | [ad09a9a9d4](https://linux-hardware.org/?probe=ad09a9a9d4) | Jan 21, 2020 |
| HP       | 0AA0h                    | [1787c13656](https://linux-hardware.org/?probe=1787c13656) | Jun 15, 2019 |
| ASUSTek  | M5A97 R2.0               | [304aa59840](https://linux-hardware.org/?probe=304aa59840) | Dec 14, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 10       | 24.39%  |
| Ubuntu 18.04        | 3        | 7.32%   |
| Linux Mint 21       | 3        | 7.32%   |
| ArcoLinux Rolling   | 3        | 7.32%   |
| Zorin 15            | 2        | 4.88%   |
| Ubuntu Studio 21.10 | 1        | 2.44%   |
| Ubuntu 22.04        | 1        | 2.44%   |
| Pop!_OS 20.10       | 1        | 2.44%   |
| Pop!_OS 20.04       | 1        | 2.44%   |
| OpenMandriva 4.50   | 1        | 2.44%   |
| OpenMandriva 4.2    | 1        | 2.44%   |
| Manjaro             | 1        | 2.44%   |
| Mageia 6            | 1        | 2.44%   |
| Lubuntu 20.10       | 1        | 2.44%   |
| Linux Mint 20.3     | 1        | 2.44%   |
| Kali 2020.1         | 1        | 2.44%   |
| Fedora 36           | 1        | 2.44%   |
| Fedora 34           | 1        | 2.44%   |
| Fedora 33           | 1        | 2.44%   |
| Fedora 32           | 1        | 2.44%   |
| Endless 3.8.3       | 1        | 2.44%   |
| Elementary 6.1      | 1        | 2.44%   |
| Elementary 6        | 1        | 2.44%   |
| Debian 11           | 1        | 2.44%   |
| BlackPanther 18.1   | 1        | 2.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 14       | 35.9%   |
| Linux Mint    | 4        | 10.26%  |
| Fedora        | 3        | 7.69%   |
| ArcoLinux     | 3        | 7.69%   |
| Zorin         | 2        | 5.13%   |
| OpenMandriva  | 2        | 5.13%   |
| Elementary    | 2        | 5.13%   |
| Ubuntu Studio | 1        | 2.56%   |
| Pop!_OS       | 1        | 2.56%   |
| Manjaro       | 1        | 2.56%   |
| Mageia        | 1        | 2.56%   |
| Lubuntu       | 1        | 2.56%   |
| Kali          | 1        | 2.56%   |
| Endless       | 1        | 2.56%   |
| Debian        | 1        | 2.56%   |
| BlackPanther  | 1        | 2.56%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 2        | 4.76%   |
| 5.15.0-41-generic        | 2        | 4.76%   |
| 5.8.4-200.fc32.x86_64    | 1        | 2.38%   |
| 5.8.13-200.fc32.x86_64   | 1        | 2.38%   |
| 5.8.0-7642-generic       | 1        | 2.38%   |
| 5.8.0-63-generic         | 1        | 2.38%   |
| 5.8.0-53-generic         | 1        | 2.38%   |
| 5.8.0-43-generic         | 1        | 2.38%   |
| 5.4.0-7642-generic       | 1        | 2.38%   |
| 5.4.0-37-generic         | 1        | 2.38%   |
| 5.4.0-33-generic         | 1        | 2.38%   |
| 5.4.0-28-generic         | 1        | 2.38%   |
| 5.4.0-19-generic         | 1        | 2.38%   |
| 5.4.0-137-generic        | 1        | 2.38%   |
| 5.4.0-124-generic        | 1        | 2.38%   |
| 5.3.0-kali2-amd64        | 1        | 2.38%   |
| 5.3.0-62-generic         | 1        | 2.38%   |
| 5.3.0-28-generic         | 1        | 2.38%   |
| 5.19.9-200.fc36.x86_64   | 1        | 2.38%   |
| 5.19.5-desktop-1omv4090  | 1        | 2.38%   |
| 5.16.2-zen1-1-zen        | 1        | 2.38%   |
| 5.15.85-1-MANJARO        | 1        | 2.38%   |
| 5.15.26-1-lts            | 1        | 2.38%   |
| 5.15.10-arch1-1          | 1        | 2.38%   |
| 5.15.0-58-generic        | 1        | 2.38%   |
| 5.15.0-52-generic        | 1        | 2.38%   |
| 5.13.0-48-generic        | 1        | 2.38%   |
| 5.13.0-40-generic        | 1        | 2.38%   |
| 5.13.0-30-generic        | 1        | 2.38%   |
| 5.13.0-28-lowlatency     | 1        | 2.38%   |
| 5.12.11-300.fc34.x86_64  | 1        | 2.38%   |
| 5.11.0-43-generic        | 1        | 2.38%   |
| 5.11.0-40-generic        | 1        | 2.38%   |
| 5.10.14-desktop-1omv4002 | 1        | 2.38%   |
| 5.10.10-200.fc33.x86_64  | 1        | 2.38%   |
| 5.10.0-21-amd64          | 1        | 2.38%   |
| 5.0.0-37-generic         | 1        | 2.38%   |
| 4.9.56-server-1.mga6     | 1        | 2.38%   |
| 4.18.16-desktop-1bP      | 1        | 2.38%   |
| 4.15.0-51-generic        | 1        | 2.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 9        | 21.43%  |
| 5.8.0   | 4        | 9.52%   |
| 5.15.0  | 4        | 9.52%   |
| 5.13.0  | 4        | 9.52%   |
| 5.3.0   | 3        | 7.14%   |
| 5.11.0  | 2        | 4.76%   |
| 5.8.4   | 1        | 2.38%   |
| 5.8.13  | 1        | 2.38%   |
| 5.19.9  | 1        | 2.38%   |
| 5.19.5  | 1        | 2.38%   |
| 5.16.2  | 1        | 2.38%   |
| 5.15.85 | 1        | 2.38%   |
| 5.15.26 | 1        | 2.38%   |
| 5.15.10 | 1        | 2.38%   |
| 5.12.11 | 1        | 2.38%   |
| 5.10.14 | 1        | 2.38%   |
| 5.10.10 | 1        | 2.38%   |
| 5.10.0  | 1        | 2.38%   |
| 5.0.0   | 1        | 2.38%   |
| 4.9.56  | 1        | 2.38%   |
| 4.18.16 | 1        | 2.38%   |
| 4.15.0  | 1        | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 9        | 21.95%  |
| 5.15    | 7        | 17.07%  |
| 5.8     | 5        | 12.2%   |
| 5.13    | 4        | 9.76%   |
| 5.3     | 3        | 7.32%   |
| 5.10    | 3        | 7.32%   |
| 5.19    | 2        | 4.88%   |
| 5.11    | 2        | 4.88%   |
| 5.16    | 1        | 2.44%   |
| 5.12    | 1        | 2.44%   |
| 5.0     | 1        | 2.44%   |
| 4.9     | 1        | 2.44%   |
| 4.18    | 1        | 2.44%   |
| 4.15    | 1        | 2.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 38       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 20       | 51.28%  |
| KDE5       | 6        | 15.38%  |
| X-Cinnamon | 4        | 10.26%  |
| Unknown    | 3        | 7.69%   |
| Pantheon   | 2        | 5.13%   |
| LXQt       | 1        | 2.56%   |
| DWM        | 1        | 2.56%   |
| Cinnamon   | 1        | 2.56%   |
| awesome    | 1        | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 32       | 84.21%  |
| Wayland | 3        | 7.89%   |
| Tty     | 2        | 5.26%   |
| Unknown | 1        | 2.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 19       | 48.72%  |
| SDDM    | 7        | 17.95%  |
| LightDM | 6        | 15.38%  |
| GDM3    | 5        | 12.82%  |
| GDM     | 2        | 5.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 32       | 84.21%  |
| en_GB   | 3        | 7.89%   |
| Unknown | 3        | 7.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 25       | 65.79%  |
| EFI  | 13       | 34.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 30       | 76.92%  |
| Overlay | 5        | 12.82%  |
| Btrfs   | 3        | 7.69%   |
| Unknown | 1        | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 60.53%  |
| GPT     | 9        | 23.68%  |
| MBR     | 6        | 15.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 76.32%  |
| Yes       | 9        | 23.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 57.89%  |
| Yes       | 16       | 42.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 12       | 31.58%  |
| Hewlett-Packard     | 11       | 28.95%  |
| MSI                 | 4        | 10.53%  |
| Gigabyte Technology | 4        | 10.53%  |
| Lenovo              | 1        | 2.63%   |
| Intel               | 1        | 2.63%   |
| Foxconn             | 1        | 2.63%   |
| ASUSTek Computer    | 1        | 2.63%   |
| ASRock              | 1        | 2.63%   |
| Acer                | 1        | 2.63%   |
| Unknown             | 1        | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| MSI MS-7C02                            | 2        | 5.26%   |
| Dell OptiPlex 7010                     | 2        | 5.26%   |
| MSI 500-007A                           | 1        | 2.63%   |
| MSI 0A90                               | 1        | 2.63%   |
| Lenovo ThinkCentre E73 10AS00CVUM      | 1        | 2.63%   |
| Intel Starmax Desktop                  | 1        | 2.63%   |
| HP Z400 Workstation                    | 1        | 2.63%   |
| HP xw4600 Workstation                  | 1        | 2.63%   |
| HP EliteDesk 800 G4 TWR                | 1        | 2.63%   |
| HP Compaq Elite 8300 SFF               | 1        | 2.63%   |
| HP Compaq Elite 8300 CMT               | 1        | 2.63%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 2.63%   |
| HP Compaq dc7800 Small Form Factor     | 1        | 2.63%   |
| HP Compaq dc7600 Convertible Minitower | 1        | 2.63%   |
| HP Compaq dc7100 SFF(DX878AV)          | 1        | 2.63%   |
| HP Compaq 6005 Pro MT PC               | 1        | 2.63%   |
| HP Compaq 4000 Pro SFF PC              | 1        | 2.63%   |
| Gigabyte Z68XP-UD3                     | 1        | 2.63%   |
| Gigabyte TRX40 AORUS PRO WIFI          | 1        | 2.63%   |
| Gigabyte H110M-A                       | 1        | 2.63%   |
| Gigabyte B450 I AORUS PRO WIFI         | 1        | 2.63%   |
| Foxconn Pro3500 Series                 | 1        | 2.63%   |
| Dell Precision Tower 5810              | 1        | 2.63%   |
| Dell OptiPlex GX520                    | 1        | 2.63%   |
| Dell OptiPlex 990                      | 1        | 2.63%   |
| Dell OptiPlex 760                      | 1        | 2.63%   |
| Dell OptiPlex 755                      | 1        | 2.63%   |
| Dell OptiPlex 7050                     | 1        | 2.63%   |
| Dell OptiPlex 5040                     | 1        | 2.63%   |
| Dell OptiPlex 390                      | 1        | 2.63%   |
| Dell OptiPlex 380                      | 1        | 2.63%   |
| Dell OptiPlex 3020                     | 1        | 2.63%   |
| ASUS M5A97 R2.0                        | 1        | 2.63%   |
| ASRock X570 Steel Legend               | 1        | 2.63%   |
| Acer Veriton X680G                     | 1        | 2.63%   |
| Unknown                                | 1        | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 11       | 28.95%  |
| HP Compaq          | 8        | 21.05%  |
| MSI MS-7C02        | 2        | 5.26%   |
| MSI 500-007A       | 1        | 2.63%   |
| MSI 0A90           | 1        | 2.63%   |
| Lenovo ThinkCentre | 1        | 2.63%   |
| Intel Starmax      | 1        | 2.63%   |
| HP Z400            | 1        | 2.63%   |
| HP xw4600          | 1        | 2.63%   |
| HP EliteDesk       | 1        | 2.63%   |
| Gigabyte Z68XP-UD3 | 1        | 2.63%   |
| Gigabyte TRX40     | 1        | 2.63%   |
| Gigabyte H110M-A   | 1        | 2.63%   |
| Gigabyte B450      | 1        | 2.63%   |
| Foxconn Pro3500    | 1        | 2.63%   |
| Dell Precision     | 1        | 2.63%   |
| ASUS M5A97         | 1        | 2.63%   |
| ASRock X570        | 1        | 2.63%   |
| Acer Veriton       | 1        | 2.63%   |
| Unknown            | 1        | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 5        | 13.16%  |
| 2011 | 4        | 10.53%  |
| 2008 | 4        | 10.53%  |
| 2019 | 3        | 7.89%   |
| 2013 | 3        | 7.89%   |
| 2012 | 3        | 7.89%   |
| 2010 | 3        | 7.89%   |
| 2007 | 3        | 7.89%   |
| 2016 | 2        | 5.26%   |
| 2014 | 2        | 5.26%   |
| 2005 | 2        | 5.26%   |
| 2022 | 1        | 2.63%   |
| 2015 | 1        | 2.63%   |
| 2009 | 1        | 2.63%   |
| 2004 | 1        | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 38       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 37       | 94.87%  |
| Enabled  | 2        | 5.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 9        | 23.08%  |
| 16.01-24.0      | 7        | 17.95%  |
| 1.01-2.0        | 6        | 15.38%  |
| 8.01-16.0       | 5        | 12.82%  |
| 4.01-8.0        | 4        | 10.26%  |
| 32.01-64.0      | 4        | 10.26%  |
| More than 256.0 | 1        | 2.56%   |
| 24.01-32.0      | 1        | 2.56%   |
| 2.01-3.0        | 1        | 2.56%   |
| 64.01-256.0     | 1        | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 13       | 32.5%   |
| 2.01-3.0  | 10       | 25%     |
| 4.01-8.0  | 6        | 15%     |
| 0.51-1.0  | 5        | 12.5%   |
| 3.01-4.0  | 3        | 7.5%    |
| 0.01-0.5  | 2        | 5%      |
| 8.01-16.0 | 1        | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 44.74%  |
| 2      | 13       | 34.21%  |
| 4      | 3        | 7.89%   |
| 3      | 3        | 7.89%   |
| 6      | 1        | 2.63%   |
| 5      | 1        | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 52.63%  |
| Yes       | 18       | 47.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 37       | 97.37%  |
| No        | 1        | 2.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 55.26%  |
| Yes       | 17       | 44.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 84.21%  |
| Yes       | 6        | 15.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Kenya   | 38       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City    | Desktops | Percent |
|---------|----------|---------|
| Nairobi | 36       | 92.31%  |
| Nyeri   | 1        | 2.56%   |
| Nakuru  | 1        | 2.56%   |
| Mombasa | 1        | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 22       | 27     | 32.35%  |
| WDC                 | 13       | 15     | 19.12%  |
| Toshiba             | 5        | 5      | 7.35%   |
| Samsung Electronics | 4        | 7      | 5.88%   |
| HGST                | 4        | 6      | 5.88%   |
| SPCC                | 3        | 7      | 4.41%   |
| Hitachi             | 3        | 3      | 4.41%   |
| Team                | 2        | 2      | 2.94%   |
| Sandisk             | 2        | 2      | 2.94%   |
| Maxtor              | 2        | 2      | 2.94%   |
| Intel               | 2        | 2      | 2.94%   |
| Unknown             | 2        | 2      | 2.94%   |
| Unknown             | 1        | 1      | 1.47%   |
| LITEON              | 1        | 1      | 1.47%   |
| HUAWEI              | 1        | 1      | 1.47%   |
| China               | 1        | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WD3200AAJS-56M0A0 320GB        | 3        | 4.05%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 4.05%   |
| Toshiba DT01ACA100 1TB             | 2        | 2.7%    |
| Team T253X2001T 1024GB SSD         | 2        | 2.7%    |
| SPCC Solid State Disk 256GB        | 2        | 2.7%    |
| SPCC M.2 PCIe SSD 512GB            | 2        | 2.7%    |
| Seagate ST500VT000-1BS142 500GB    | 2        | 2.7%    |
| Seagate ST3320418AS 320GB          | 2        | 2.7%    |
| Seagate ST3250318AS 250GB          | 2        | 2.7%    |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 2.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 2.7%    |
| Samsung SSD 840 EVO 250GB          | 2        | 2.7%    |
| Unknown                            | 2        | 2.7%    |
| WDC WD800GD-75FLC3 80GB            | 1        | 1.35%   |
| WDC WD60EZAZ-00SF3B0 6TB           | 1        | 1.35%   |
| WDC WD5003AZEX-00K1GA0 500GB       | 1        | 1.35%   |
| WDC WD5000AVVS-63M8B0 500GB        | 1        | 1.35%   |
| WDC WD5000AVDS-63U7B1 500GB        | 1        | 1.35%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 1        | 1.35%   |
| WDC WD3200AAKS-75L9A0 320GB        | 1        | 1.35%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 1.35%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1        | 1.35%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1.35%   |
| WDC WD2500AAKX-08U6AA0 250GB       | 1        | 1.35%   |
| Unknown L200 Hard drive 2TB        | 1        | 1.35%   |
| Toshiba THNSNJ128GCSU 128GB SSD    | 1        | 1.35%   |
| Toshiba MK2555GSX 250GB            | 1        | 1.35%   |
| Toshiba DT01ABA100V 1TB            | 1        | 1.35%   |
| Seagate ST_M13FQBL QNR 4GB         | 1        | 1.35%   |
| Seagate ST380817AS 80GB            | 1        | 1.35%   |
| Seagate ST3808110AS 80GB           | 1        | 1.35%   |
| Seagate ST380013AS 80GB            | 1        | 1.35%   |
| Seagate ST380011A 80GB             | 1        | 1.35%   |
| Seagate ST3250312AS 250GB          | 1        | 1.35%   |
| Seagate ST3160812AS Q 160GB        | 1        | 1.35%   |
| Seagate ST3000DM001-1CH166 3TB     | 1        | 1.35%   |
| Seagate ST2000DM001-1ER164 2TB     | 1        | 1.35%   |
| Seagate ST2000DM001-1CH164 2TB     | 1        | 1.35%   |
| Seagate ST1000VM002-1CT162 1TB     | 1        | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 21       | 26     | 42%     |
| WDC                 | 13       | 15     | 26%     |
| Toshiba             | 4        | 4      | 8%      |
| HGST                | 4        | 6      | 8%      |
| Hitachi             | 3        | 3      | 6%      |
| Maxtor              | 2        | 2      | 4%      |
| Unknown             | 1        | 1      | 2%      |
| Samsung Electronics | 1        | 1      | 2%      |
| Unknown             | 1        | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Team                | 2        | 2      | 15.38%  |
| SPCC                | 2        | 3      | 15.38%  |
| Samsung Electronics | 2        | 4      | 15.38%  |
| Intel               | 2        | 2      | 15.38%  |
| Toshiba             | 1        | 1      | 7.69%   |
| SanDisk             | 1        | 1      | 7.69%   |
| LITEON              | 1        | 1      | 7.69%   |
| China               | 1        | 1      | 7.69%   |
| Unknown             | 1        | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 35       | 59     | 68.63%  |
| SSD     | 10       | 16     | 19.61%  |
| NVMe    | 4        | 7      | 7.84%   |
| Unknown | 2        | 2      | 3.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 38       | 76     | 88.37%  |
| NVMe | 4        | 7      | 9.3%    |
| SAS  | 1        | 1      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 51     | 64%     |
| 0.51-1.0   | 9        | 11     | 18%     |
| 1.01-2.0   | 5        | 8      | 10%     |
| 4.01-10.0  | 2        | 3      | 4%      |
| 3.01-4.0   | 1        | 1      | 2%      |
| 2.01-3.0   | 1        | 1      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 8        | 19.05%  |
| 101-250        | 7        | 16.67%  |
| 51-100         | 7        | 16.67%  |
| 501-1000       | 6        | 14.29%  |
| 251-500        | 5        | 11.9%   |
| More than 3000 | 4        | 9.52%   |
| 1-20           | 2        | 4.76%   |
| 21-50          | 1        | 2.38%   |
| 2001-3000      | 1        | 2.38%   |
| Unknown        | 1        | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 16       | 38.1%   |
| 1001-2000 | 6        | 14.29%  |
| 21-50     | 5        | 11.9%   |
| 101-250   | 5        | 11.9%   |
| 251-500   | 4        | 9.52%   |
| 501-1000  | 3        | 7.14%   |
| 51-100    | 2        | 4.76%   |
| Unknown   | 1        | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 1      | 16.67%  |
| Toshiba MK2555GSX 250GB            | 1        | 1      | 16.67%  |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 16.67%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 16.67%  |
| HGST HTS721010A9 1TB               | 1        | 2      | 16.67%  |
| Unknown                            | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 33.33%  |
| WDC     | 1        | 1      | 16.67%  |
| Toshiba | 1        | 1      | 16.67%  |
| HGST    | 1        | 2      | 16.67%  |
| Unknown | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 33.33%  |
| WDC     | 1        | 1      | 16.67%  |
| Toshiba | 1        | 1      | 16.67%  |
| HGST    | 1        | 2      | 16.67%  |
| Unknown | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 7      | 100%    |

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
| Detected | 27       | 42     | 62.79%  |
| Works    | 11       | 35     | 25.58%  |
| Malfunc  | 5        | 7      | 11.63%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 30       | 65.22%  |
| AMD                       | 8        | 17.39%  |
| Silicon Motion            | 1        | 2.17%   |
| SanDisk                   | 1        | 2.17%   |
| Samsung Electronics       | 1        | 2.17%   |
| Realtek Semiconductor     | 1        | 2.17%   |
| Marvell Technology Group  | 1        | 2.17%   |
| LSI Logic / Symbios Logic | 1        | 2.17%   |
| JMicron Technology        | 1        | 2.17%   |
| Broadcom / LSI            | 1        | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 9.52%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 6.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 6.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 6.35%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 4.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 4.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 4.76%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 3.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 3.17%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 3.17%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.59%   |
| SanDisk Non-Volatile memory controller                                                  | 1        | 1.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.59%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 1.59%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 1.59%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 1        | 1.59%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.59%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.59%   |
| Intel Elkhart Lake SATA AHCI                                                            | 1        | 1.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.59%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.59%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.59%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.59%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.59%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.59%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.59%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                           | 1        | 1.59%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 1        | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 1.59%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.59%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.59%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 25       | 51.02%  |
| IDE  | 14       | 28.57%  |
| RAID | 5        | 10.2%   |
| NVMe | 4        | 8.16%   |
| SCSI | 1        | 2.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 30       | 78.95%  |
| AMD    | 8        | 21.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Pentium 4 CPU 2.80GHz                    | 2        | 5.26%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 2        | 5.26%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 2        | 5.26%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 5.26%   |
| Intel Xeon CPU W3680 @ 3.33GHz                 | 1        | 2.63%   |
| Intel Xeon CPU E5-1630 v3 @ 3.70GHz            | 1        | 2.63%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz    | 1        | 2.63%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 2.63%   |
| Intel Pentium 4 CPU 3.00GHz                    | 1        | 2.63%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 2.63%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 1        | 2.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 2.63%   |
| Intel Core i5-4430S CPU @ 2.70GHz              | 1        | 2.63%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 1        | 2.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 2.63%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 1        | 2.63%   |
| Intel Core i3-3240 CPU @ 3.40GHz               | 1        | 2.63%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 2.63%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 1        | 2.63%   |
| Intel Core i3 CPU 550 @ 3.20GHz                | 1        | 2.63%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 2.63%   |
| Intel Core 2 Quad CPU @ 2.40GHz                | 1        | 2.63%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz           | 1        | 2.63%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz           | 1        | 2.63%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 1        | 2.63%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz           | 1        | 2.63%   |
| Intel Core 2 CPU 6420 @ 2.13GHz                | 1        | 2.63%   |
| Intel Celeron J6412 @ 2.00GHz                  | 1        | 2.63%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 2.63%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 2.63%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 2.63%   |
| AMD Phenom II X3 B75 Processor                 | 1        | 2.63%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 2.63%   |
| AMD A4-5300 APU with Radeon HD Graphics        | 1        | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 7        | 18.42%  |
| Intel Core i3           | 5        | 13.16%  |
| Intel Pentium 4         | 4        | 10.53%  |
| Intel Core 2 Duo        | 4        | 10.53%  |
| Intel Core i7           | 3        | 7.89%   |
| Intel Xeon              | 2        | 5.26%   |
| Intel Core 2 Quad       | 2        | 5.26%   |
| AMD Ryzen 5             | 2        | 5.26%   |
| Intel Pentium Dual-Core | 1        | 2.63%   |
| Intel Core 2            | 1        | 2.63%   |
| Intel Celeron           | 1        | 2.63%   |
| AMD Ryzen Threadripper  | 1        | 2.63%   |
| AMD Ryzen 9             | 1        | 2.63%   |
| AMD Ryzen 7             | 1        | 2.63%   |
| AMD Phenom II X3        | 1        | 2.63%   |
| AMD FX                  | 1        | 2.63%   |
| AMD A4                  | 1        | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 34.21%  |
| 2      | 11       | 28.95%  |
| 1      | 5        | 13.16%  |
| 6      | 4        | 10.53%  |
| 3      | 2        | 5.26%   |
| 32     | 1        | 2.63%   |
| 12     | 1        | 2.63%   |
| 8      | 1        | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 38       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 50%     |
| 1      | 19       | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 38       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 5        | 12.82%  |
| Unknown    | 5        | 12.82%  |
| 0x506e3    | 3        | 7.69%   |
| 0x206a7    | 3        | 7.69%   |
| 0x1067a    | 3        | 7.69%   |
| 0x0800820d | 3        | 7.69%   |
| 0x10676    | 2        | 5.13%   |
| 0xf65      | 1        | 2.56%   |
| 0xf49      | 1        | 2.56%   |
| 0xf43      | 1        | 2.56%   |
| 0x906ea    | 1        | 2.56%   |
| 0x90661    | 1        | 2.56%   |
| 0x6f7      | 1        | 2.56%   |
| 0x6f6      | 1        | 2.56%   |
| 0x306f2    | 1        | 2.56%   |
| 0x306c3    | 1        | 2.56%   |
| 0x206c2    | 1        | 2.56%   |
| 0x20655    | 1        | 2.56%   |
| 0x0a201016 | 1        | 2.56%   |
| 0x08301039 | 1        | 2.56%   |
| 0x06001119 | 1        | 2.56%   |
| 0x0600084f | 1        | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 5        | 13.16%  |
| IvyBridge   | 5        | 13.16%  |
| NetBurst    | 4        | 10.53%  |
| Zen+        | 3        | 7.89%   |
| Skylake     | 3        | 7.89%   |
| SandyBridge | 3        | 7.89%   |
| Haswell     | 3        | 7.89%   |
| Core        | 3        | 7.89%   |
| Westmere    | 2        | 5.26%   |
| Piledriver  | 2        | 5.26%   |
| Zen 3       | 1        | 2.63%   |
| Zen 2       | 1        | 2.63%   |
| Tremont     | 1        | 2.63%   |
| KabyLake    | 1        | 2.63%   |
| K10         | 1        | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 47.62%  |
| Nvidia | 13       | 30.95%  |
| AMD    | 9        | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 9.52%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 7.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 7.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 7.14%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 4.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 4.76%   |
| Intel HD Graphics 530                                                       | 2        | 4.76%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 4.76%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 4.76%   |
| Nvidia GT218 [NVS 300]                                                      | 1        | 2.38%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 2.38%   |
| Nvidia GK107GL [Quadro 410]                                                 | 1        | 2.38%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 2.38%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 2.38%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 2.38%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 2.38%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.38%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.38%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                | 1        | 2.38%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.38%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 2.38%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 2.38%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 1        | 2.38%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.38%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 2.38%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 2.38%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 17       | 43.59%  |
| 1 x Nvidia     | 12       | 30.77%  |
| 1 x AMD        | 9        | 23.08%  |
| Intel + Nvidia | 1        | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 33       | 86.84%  |
| Proprietary | 4        | 10.53%  |
| Unknown     | 1        | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 52.63%  |
| 0.51-1.0   | 5        | 13.16%  |
| 7.01-8.0   | 3        | 7.89%   |
| 3.01-4.0   | 3        | 7.89%   |
| 1.01-2.0   | 3        | 7.89%   |
| 0.01-0.5   | 3        | 7.89%   |
| 8.01-16.0  | 1        | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 12       | 30%     |
| Dell                | 10       | 25%     |
| Sony                | 4        | 10%     |
| Samsung Electronics | 3        | 7.5%    |
| Lenovo              | 3        | 7.5%    |
| VIE                 | 1        | 2.5%    |
| Unknown (XXX)       | 1        | 2.5%    |
| Unknown             | 1        | 2.5%    |
| S2-Tek              | 1        | 2.5%    |
| NEC Computers       | 1        | 2.5%    |
| Hitachi             | 1        | 2.5%    |
| BenQ                | 1        | 2.5%    |
| Unknown             | 1        | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S22E450 SAM0C7A 1920x1080 477x268mm 21.5-inch     | 2        | 4.65%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                  | 2        | 4.65%   |
| Dell E1910H DELD023 1366x768 410x230mm 18.5-inch                      | 2        | 4.65%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 2.33%   |
| Unknown LCD Monitor Hitachi Engineering Company Ltd HISENSE 3200x1080 | 1        | 2.33%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 1        | 2.33%   |
| Sony TV SNYEF03 1600x900                                              | 1        | 2.33%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                         | 1        | 2.33%   |
| Sony TV SNY6F02 1360x768                                              | 1        | 2.33%   |
| Sony TV SNY0902 1360x768                                              | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1        | 2.33%   |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                       | 1        | 2.33%   |
| NEC Computers EA193Mi NEC6956 1280x1024 375x300mm 18.9-inch           | 1        | 2.33%   |
| Lenovo LEN LI1931ewA LEN65A1 1366x768 409x230mm 18.5-inch             | 1        | 2.33%   |
| Lenovo LEN E2054A LEN60DF 1440x900 419x262mm 19.5-inch                | 1        | 2.33%   |
| Hitachi HISENSE HEC0030 1920x1080 580x330mm 26.3-inch                 | 1        | 2.33%   |
| Hewlett-Packard Z27s HWP317F 3840x2160 596x335mm 26.9-inch            | 1        | 2.33%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1        | 2.33%   |
| Hewlett-Packard P222va HWP322C 1920x1080 477x268mm 21.5-inch          | 1        | 2.33%   |
| Hewlett-Packard LE2202x HWP2966 1920x1080 476x268mm 21.5-inch         | 1        | 2.33%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 1        | 2.33%   |
| Hewlett-Packard LCD Monitor L1710                                     | 1        | 2.33%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x287mm 23.0-inch          | 1        | 2.33%   |
| Hewlett-Packard LA2206 HWP2948 1920x1080 476x268mm 21.5-inch          | 1        | 2.33%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch          | 1        | 2.33%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1        | 2.33%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch            | 1        | 2.33%   |
| Hewlett-Packard E222 HWP3262 1920x1080 476x268mm 21.5-inch            | 1        | 2.33%   |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x287mm 23.0-inch            | 1        | 2.33%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1        | 2.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1        | 2.33%   |
| Dell P2314T DEL40A0 1920x1080 509x286mm 23.0-inch                     | 1        | 2.33%   |
| Dell P1914S DELF04B 1280x1024 376x301mm 19.0-inch                     | 1        | 2.33%   |
| Dell E2316H DELF06B 1920x1080 509x286mm 23.0-inch                     | 1        | 2.33%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 1        | 2.33%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 1        | 2.33%   |
| Dell 1908FP DEL4026 1280x1024 376x301mm 19.0-inch                     | 1        | 2.33%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                     | 1        | 2.33%   |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                        | 1        | 2.33%   |
| Unknown                                                               | 1        | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 13       | 33.33%  |
| 1280x1024 (SXGA)   | 7        | 17.95%  |
| 3840x2160 (4K)     | 3        | 7.69%   |
| 1366x768 (WXGA)    | 3        | 7.69%   |
| 1920x1200 (WUXGA)  | 2        | 5.13%   |
| 1600x900 (HD+)     | 2        | 5.13%   |
| 1440x900 (WXGA+)   | 2        | 5.13%   |
| 1024x768 (XGA)     | 2        | 5.13%   |
| 3200x1080          | 1        | 2.56%   |
| 2560x1440 (QHD)    | 1        | 2.56%   |
| 1680x1050 (WSXGA+) | 1        | 2.56%   |
| 1360x768           | 1        | 2.56%   |
| Unknown            | 1        | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 6        | 15.38%  |
| 19      | 5        | 12.82%  |
| 18      | 4        | 10.26%  |
| 72      | 3        | 7.69%   |
| 24      | 3        | 7.69%   |
| 23      | 3        | 7.69%   |
| 17      | 3        | 7.69%   |
| 22      | 2        | 5.13%   |
| Unknown | 2        | 5.13%   |
| 84      | 1        | 2.56%   |
| 54      | 1        | 2.56%   |
| 46      | 1        | 2.56%   |
| 42      | 1        | 2.56%   |
| 27      | 1        | 2.56%   |
| 26      | 1        | 2.56%   |
| 20      | 1        | 2.56%   |
| 15      | 1        | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 11       | 30.56%  |
| 501-600     | 8        | 22.22%  |
| 351-400     | 4        | 11.11%  |
| 301-350     | 4        | 11.11%  |
| 1501-2000   | 4        | 11.11%  |
| 1001-1500   | 2        | 5.56%   |
| Unknown     | 2        | 5.56%   |
| 901-1000    | 1        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 22       | 56.41%  |
| 5/4     | 7        | 17.95%  |
| 16/10   | 7        | 17.95%  |
| Unknown | 2        | 5.13%   |
| 4/3     | 1        | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 9        | 24.32%  |
| 201-250        | 7        | 18.92%  |
| 141-150        | 6        | 16.22%  |
| More than 1000 | 5        | 13.51%  |
| 251-300        | 3        | 8.11%   |
| 301-350        | 2        | 5.41%   |
| 501-1000       | 2        | 5.41%   |
| Unknown        | 2        | 5.41%   |
| 101-110        | 1        | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 58.82%  |
| 101-120 | 7        | 20.59%  |
| 1-50    | 4        | 11.76%  |
| Unknown | 2        | 5.88%   |
| 161-240 | 1        | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 68.42%  |
| 2     | 9        | 23.68%  |
| 0     | 3        | 7.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 35.59%  |
| Realtek Semiconductor | 16       | 27.12%  |
| MediaTek              | 4        | 6.78%   |
| Broadcom Limited      | 4        | 6.78%   |
| Qualcomm Atheros      | 3        | 5.08%   |
| Broadcom              | 3        | 5.08%   |
| Xiaomi                | 2        | 3.39%   |
| Samsung Electronics   | 2        | 3.39%   |
| Ralink Technology     | 1        | 1.69%   |
| Qualcomm              | 1        | 1.69%   |
| OPPO Electronics      | 1        | 1.69%   |
| Huawei Technologies   | 1        | 1.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 13.24%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7        | 10.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 7.35%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 4        | 5.88%   |
| MediaTek TECNO SPARK 9T                                           | 4        | 5.88%   |
| Intel I211 Gigabit Network Connection                             | 3        | 4.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 2.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 2.94%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 2.94%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.94%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 2.94%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2        | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 1.47%   |
| Qualcomm Redmi Note 9 Pro                                         | 1        | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1        | 1.47%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 1.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.47%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 1        | 1.47%   |
| Intel Wireless-AC 9260                                            | 1        | 1.47%   |
| Intel Wireless 8265 / 8275                                        | 1        | 1.47%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.47%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.47%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.47%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.47%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.47%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1        | 1.47%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 1.47%   |
| Huawei Mass Storage                                               | 1        | 1.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.47%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 1.47%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 61.11%  |
| Intel                 | 4        | 22.22%  |
| Qualcomm Atheros      | 2        | 11.11%  |
| Ralink Technology     | 1        | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7        | 38.89%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4        | 22.22%  |
| Intel Wi-Fi 6 AX200                                            | 2        | 11.11%  |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 5.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 5.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 5.56%   |
| Intel Wireless-AC 9260                                         | 1        | 5.56%   |
| Intel Wireless 8265 / 8275                                     | 1        | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 43.75%  |
| Realtek Semiconductor | 9        | 18.75%  |
| MediaTek              | 4        | 8.33%   |
| Broadcom Limited      | 4        | 8.33%   |
| Broadcom              | 3        | 6.25%   |
| Xiaomi                | 2        | 4.17%   |
| Samsung Electronics   | 2        | 4.17%   |
| Qualcomm Atheros      | 1        | 2.08%   |
| Qualcomm              | 1        | 2.08%   |
| OPPO Electronics      | 1        | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 18.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 10.2%   |
| MediaTek TECNO SPARK 9T                                           | 4        | 8.16%   |
| Intel I211 Gigabit Network Connection                             | 3        | 6.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 4.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 4.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 4.08%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 4.08%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2        | 4.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.04%   |
| Qualcomm Redmi Note 9 Pro                                         | 1        | 2.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 2.04%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 1        | 2.04%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.04%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.04%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.04%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.04%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 2.04%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1        | 2.04%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 2.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.04%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 2.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 2.04%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 2.04%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 37       | 67.27%  |
| WiFi     | 17       | 30.91%  |
| Modem    | 1        | 1.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 77.14%  |
| WiFi     | 8        | 22.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 76.32%  |
| 2     | 6        | 15.79%  |
| 4     | 1        | 2.63%   |
| 3     | 1        | 2.63%   |
| 0     | 1        | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 37       | 97.37%  |
| Yes  | 1        | 2.63%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 66.67%  |
| Cambridge Silicon Radio | 2        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 2        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 33.33%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 16.67%  |
| Intel Bluetooth wireless interface                  | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 29       | 48.33%  |
| Nvidia                 | 12       | 20%     |
| AMD                    | 11       | 18.33%  |
| Texas Instruments      | 2        | 3.33%   |
| Lenovo                 | 2        | 3.33%   |
| Medeli Electronics     | 1        | 1.67%   |
| Giga-Byte Technology   | 1        | 1.67%   |
| Generalplus Technology | 1        | 1.67%   |
| C-Media Electronics    | 1        | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 6.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 6.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 6.15%   |
| Nvidia High Definition Audio Controller                                    | 3        | 4.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 4.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 4.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 4.62%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 3.08%   |
| Lenovo T2224zD                                                             | 2        | 3.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 3.08%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 3.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 3.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 3.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 3.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 3.08%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.54%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.54%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.54%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.54%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.54%   |
| Medeli Electronics MU900                                                   | 1        | 1.54%   |
| Intel Elkhart Lake High Density Audio bus interface                        | 1        | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.54%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 1.54%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 1.54%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1        | 1.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.54%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.54%   |
| Giga-Byte Technology USB Audio                                             | 1        | 1.54%   |
| Generalplus Technology USB Audio Device                                    | 1        | 1.54%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.54%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.54%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.54%   |
| AMD FCH Azalia Controller                                                  | 1        | 1.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 5        | 26.32%  |
| Kingston            | 4        | 21.05%  |
| Crucial             | 3        | 15.79%  |
| Micron Technology   | 2        | 10.53%  |
| G.Skill             | 2        | 10.53%  |
| TwinMOS             | 1        | 5.26%   |
| Team                | 1        | 5.26%   |
| Samsung Electronics | 1        | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s | 2        | 9.52%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s        | 1        | 4.76%   |
| TwinMOS RAM 9DECBMZB-TATP 2048MB DIMM DDR3 1333MT/s     | 1        | 4.76%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s     | 1        | 4.76%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s    | 1        | 4.76%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s    | 1        | 4.76%   |
| SK hynix RAM HMT125U7BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 4.76%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 4.76%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8192MB DIMM DDR4 2667MT/s | 1        | 4.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s  | 1        | 4.76%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s          | 1        | 4.76%   |
| Micron RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s    | 1        | 4.76%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s    | 1        | 4.76%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 1        | 4.76%   |
| Kingston RAM HP497157-D88-ELFW 2GB DIMM DDR3 1333MT/s   | 1        | 4.76%   |
| Kingston RAM 99P5663-013.A00G 8GB SODIMM DDR4 2667MT/s  | 1        | 4.76%   |
| Kingston RAM 9905734-102.A00G 32GB DIMM DDR4 3200MT/s   | 1        | 4.76%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s   | 1        | 4.76%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s   | 1        | 4.76%   |
| Crucial RAM CB16GU2400.C16J 16384MB DIMM DDR4 2400MT/s  | 1        | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 8        | 50%     |
| DDR3  | 7        | 43.75%  |
| SDRAM | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 13       | 86.67%  |
| SODIMM | 2        | 13.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 29.41%  |
| 4096  | 4        | 23.53%  |
| 16384 | 3        | 17.65%  |
| 2048  | 3        | 17.65%  |
| 32768 | 2        | 11.76%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 4        | 25%     |
| 2667  | 3        | 18.75%  |
| 1333  | 3        | 18.75%  |
| 3600  | 2        | 12.5%   |
| 3800  | 1        | 6.25%   |
| 3200  | 1        | 6.25%   |
| 2400  | 1        | 6.25%   |
| 1867  | 1        | 6.25%   |

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


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| HP LaserJet M101-M106 | 1        | 100%    |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 40%     |
| MacroSilicon          | 1        | 20%     |
| Logitech              | 1        | 20%     |
| Cubeternet            | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek FULL HD 1080P Webcam    | 2        | 40%     |
| MacroSilicon usb video          | 1        | 20%     |
| Logitech Webcam C270            | 1        | 20%     |
| Cubeternet GL-UPC822 UVC WebCam | 1        | 20%     |

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
| 0     | 33       | 86.84%  |
| 1     | 5        | 13.16%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 3        | 60%     |
| Unassigned class | 1        | 20%     |
| Net/wireless     | 1        | 20%     |

