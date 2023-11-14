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

Total: 62

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Dell     | 0XR1GT A00               | [f01a35c9a7](https://linux-hardware.org/?probe=f01a35c9a7) | Nov 06, 2023 |
| HP       | 18E7                     | [855ab006c1](https://linux-hardware.org/?probe=855ab006c1) | Oct 13, 2023 |
| Dell     | 0N4YC8 A00               | [fd4fb61bac](https://linux-hardware.org/?probe=fd4fb61bac) | Oct 05, 2023 |
| MSI      | MPG Z690 EDGE WIFI       | [2ad1c71fce](https://linux-hardware.org/?probe=2ad1c71fce) | Sep 13, 2023 |
| ASRock   | B450M Pro4               | [c8e3010177](https://linux-hardware.org/?probe=c8e3010177) | Sep 10, 2023 |
| Lenovo   | NOK                      | [30f2c89249](https://linux-hardware.org/?probe=30f2c89249) | Sep 07, 2023 |
| HP       | 3047h                    | [e60df0b6d1](https://linux-hardware.org/?probe=e60df0b6d1) | Jun 23, 2023 |
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
| Ubuntu 20.04        | 10       | 21.28%  |
| ArcoLinux Rolling   | 4        | 8.51%   |
| Ubuntu 18.04        | 3        | 6.38%   |
| Linux Mint 21       | 3        | 6.38%   |
| Zorin 15            | 2        | 4.26%   |
| Ubuntu 22.04        | 2        | 4.26%   |
| Fedora 38           | 2        | 4.26%   |
| Ubuntu Studio 21.10 | 1        | 2.13%   |
| Pop!_OS 20.10       | 1        | 2.13%   |
| Pop!_OS 20.04       | 1        | 2.13%   |
| OpenMandriva 4.50   | 1        | 2.13%   |
| OpenMandriva 4.2    | 1        | 2.13%   |
| Manjaro             | 1        | 2.13%   |
| Mageia 6            | 1        | 2.13%   |
| Lubuntu 20.10       | 1        | 2.13%   |
| Linux Mint 21.2     | 1        | 2.13%   |
| Linux Mint 20.3     | 1        | 2.13%   |
| Kali 2020.1         | 1        | 2.13%   |
| Fedora 36           | 1        | 2.13%   |
| Fedora 34           | 1        | 2.13%   |
| Fedora 33           | 1        | 2.13%   |
| Fedora 32           | 1        | 2.13%   |
| Endless 3.8.3       | 1        | 2.13%   |
| Elementary 6.1      | 1        | 2.13%   |
| Elementary 6        | 1        | 2.13%   |
| Deepin 23           | 1        | 2.13%   |
| Debian 11           | 1        | 2.13%   |
| BlackPanther 18.1   | 1        | 2.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 15       | 33.33%  |
| Linux Mint    | 5        | 11.11%  |
| Fedora        | 5        | 11.11%  |
| ArcoLinux     | 4        | 8.89%   |
| Zorin         | 2        | 4.44%   |
| OpenMandriva  | 2        | 4.44%   |
| Elementary    | 2        | 4.44%   |
| Ubuntu Studio | 1        | 2.22%   |
| Pop!_OS       | 1        | 2.22%   |
| Manjaro       | 1        | 2.22%   |
| Mageia        | 1        | 2.22%   |
| Lubuntu       | 1        | 2.22%   |
| Kali          | 1        | 2.22%   |
| Endless       | 1        | 2.22%   |
| Deepin        | 1        | 2.22%   |
| Debian        | 1        | 2.22%   |
| BlackPanther  | 1        | 2.22%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 2        | 4.08%   |
| 5.15.0-41-generic        | 2        | 4.08%   |
| 6.5.6-arch2-1            | 1        | 2.04%   |
| 6.5.5-200.fc38.x86_64    | 1        | 2.04%   |
| 6.4.15-200.fc38.x86_64   | 1        | 2.04%   |
| 6.2.0-32-generic         | 1        | 2.04%   |
| 6.1.32-amd64-desktop-hwe | 1        | 2.04%   |
| 5.8.4-200.fc32.x86_64    | 1        | 2.04%   |
| 5.8.13-200.fc32.x86_64   | 1        | 2.04%   |
| 5.8.0-7642-generic       | 1        | 2.04%   |
| 5.8.0-63-generic         | 1        | 2.04%   |
| 5.8.0-53-generic         | 1        | 2.04%   |
| 5.8.0-43-generic         | 1        | 2.04%   |
| 5.4.0-7642-generic       | 1        | 2.04%   |
| 5.4.0-37-generic         | 1        | 2.04%   |
| 5.4.0-33-generic         | 1        | 2.04%   |
| 5.4.0-28-generic         | 1        | 2.04%   |
| 5.4.0-19-generic         | 1        | 2.04%   |
| 5.4.0-137-generic        | 1        | 2.04%   |
| 5.4.0-124-generic        | 1        | 2.04%   |
| 5.3.0-kali2-amd64        | 1        | 2.04%   |
| 5.3.0-62-generic         | 1        | 2.04%   |
| 5.3.0-28-generic         | 1        | 2.04%   |
| 5.19.9-200.fc36.x86_64   | 1        | 2.04%   |
| 5.19.5-desktop-1omv4090  | 1        | 2.04%   |
| 5.19.0-45-generic        | 1        | 2.04%   |
| 5.16.2-zen1-1-zen        | 1        | 2.04%   |
| 5.15.85-1-MANJARO        | 1        | 2.04%   |
| 5.15.26-1-lts            | 1        | 2.04%   |
| 5.15.10-arch1-1          | 1        | 2.04%   |
| 5.15.0-76-generic        | 1        | 2.04%   |
| 5.15.0-58-generic        | 1        | 2.04%   |
| 5.15.0-52-generic        | 1        | 2.04%   |
| 5.13.0-48-generic        | 1        | 2.04%   |
| 5.13.0-40-generic        | 1        | 2.04%   |
| 5.13.0-30-generic        | 1        | 2.04%   |
| 5.13.0-28-lowlatency     | 1        | 2.04%   |
| 5.12.11-300.fc34.x86_64  | 1        | 2.04%   |
| 5.11.0-43-generic        | 1        | 2.04%   |
| 5.11.0-40-generic        | 1        | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 9        | 18.37%  |
| 5.15.0  | 5        | 10.2%   |
| 5.8.0   | 4        | 8.16%   |
| 5.13.0  | 4        | 8.16%   |
| 5.3.0   | 3        | 6.12%   |
| 5.11.0  | 2        | 4.08%   |
| 6.5.6   | 1        | 2.04%   |
| 6.5.5   | 1        | 2.04%   |
| 6.4.15  | 1        | 2.04%   |
| 6.2.0   | 1        | 2.04%   |
| 6.1.32  | 1        | 2.04%   |
| 5.8.4   | 1        | 2.04%   |
| 5.8.13  | 1        | 2.04%   |
| 5.19.9  | 1        | 2.04%   |
| 5.19.5  | 1        | 2.04%   |
| 5.19.0  | 1        | 2.04%   |
| 5.16.2  | 1        | 2.04%   |
| 5.15.85 | 1        | 2.04%   |
| 5.15.26 | 1        | 2.04%   |
| 5.15.10 | 1        | 2.04%   |
| 5.12.11 | 1        | 2.04%   |
| 5.10.14 | 1        | 2.04%   |
| 5.10.10 | 1        | 2.04%   |
| 5.10.0  | 1        | 2.04%   |
| 5.0.0   | 1        | 2.04%   |
| 4.9.56  | 1        | 2.04%   |
| 4.18.16 | 1        | 2.04%   |
| 4.15.0  | 1        | 2.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 9        | 18.75%  |
| 5.15    | 8        | 16.67%  |
| 5.8     | 5        | 10.42%  |
| 5.13    | 4        | 8.33%   |
| 5.3     | 3        | 6.25%   |
| 5.19    | 3        | 6.25%   |
| 5.10    | 3        | 6.25%   |
| 6.5     | 2        | 4.17%   |
| 5.11    | 2        | 4.17%   |
| 6.4     | 1        | 2.08%   |
| 6.2     | 1        | 2.08%   |
| 6.1     | 1        | 2.08%   |
| 5.16    | 1        | 2.08%   |
| 5.12    | 1        | 2.08%   |
| 5.0     | 1        | 2.08%   |
| 4.9     | 1        | 2.08%   |
| 4.18    | 1        | 2.08%   |
| 4.15    | 1        | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 44       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 23       | 51.11%  |
| KDE5       | 6        | 13.33%  |
| X-Cinnamon | 5        | 11.11%  |
| Unknown    | 3        | 6.67%   |
| Pantheon   | 2        | 4.44%   |
| XFCE       | 1        | 2.22%   |
| LXQt       | 1        | 2.22%   |
| DWM        | 1        | 2.22%   |
| DDE        | 1        | 2.22%   |
| Cinnamon   | 1        | 2.22%   |
| awesome    | 1        | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 35       | 79.55%  |
| Wayland | 6        | 13.64%  |
| Tty     | 2        | 4.55%   |
| Unknown | 1        | 2.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 46.67%  |
| SDDM    | 8        | 17.78%  |
| LightDM | 7        | 15.56%  |
| GDM3    | 5        | 11.11%  |
| GDM     | 4        | 8.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 35       | 79.55%  |
| en_GB   | 6        | 13.64%  |
| Unknown | 3        | 6.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 29       | 65.91%  |
| EFI  | 15       | 34.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 34       | 73.91%  |
| Overlay | 5        | 10.87%  |
| Btrfs   | 5        | 10.87%  |
| Tmpfs   | 1        | 2.17%   |
| Unknown | 1        | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 56.82%  |
| GPT     | 12       | 27.27%  |
| MBR     | 7        | 15.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 79.55%  |
| Yes       | 9        | 20.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 59.09%  |
| Yes       | 18       | 40.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 14       | 31.82%  |
| Hewlett-Packard     | 12       | 27.27%  |
| MSI                 | 5        | 11.36%  |
| Gigabyte Technology | 4        | 9.09%   |
| Lenovo              | 2        | 4.55%   |
| ASRock              | 2        | 4.55%   |
| Intel               | 1        | 2.27%   |
| Foxconn             | 1        | 2.27%   |
| ASUSTek Computer    | 1        | 2.27%   |
| Acer                | 1        | 2.27%   |
| Unknown             | 1        | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| MSI MS-7C02                            | 2        | 4.55%   |
| Dell OptiPlex 7010                     | 2        | 4.55%   |
| MSI MS-7D31                            | 1        | 2.27%   |
| MSI 500-007A                           | 1        | 2.27%   |
| MSI 0A90                               | 1        | 2.27%   |
| Lenovo ThinkCentre E73 10AS00HRUM      | 1        | 2.27%   |
| Lenovo ThinkCentre E73 10AS00CVUM      | 1        | 2.27%   |
| Intel Starmax Desktop                  | 1        | 2.27%   |
| HP Z400 Workstation                    | 1        | 2.27%   |
| HP xw4600 Workstation                  | 1        | 2.27%   |
| HP ProDesk 600 G1 TWR                  | 1        | 2.27%   |
| HP EliteDesk 800 G4 TWR                | 1        | 2.27%   |
| HP Compaq Elite 8300 SFF               | 1        | 2.27%   |
| HP Compaq Elite 8300 CMT               | 1        | 2.27%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 2.27%   |
| HP Compaq dc7800 Small Form Factor     | 1        | 2.27%   |
| HP Compaq dc7600 Convertible Minitower | 1        | 2.27%   |
| HP Compaq dc7100 SFF(DX878AV)          | 1        | 2.27%   |
| HP Compaq 6005 Pro MT PC               | 1        | 2.27%   |
| HP Compaq 4000 Pro SFF PC              | 1        | 2.27%   |
| Gigabyte Z68XP-UD3                     | 1        | 2.27%   |
| Gigabyte TRX40 AORUS PRO WIFI          | 1        | 2.27%   |
| Gigabyte H110M-A                       | 1        | 2.27%   |
| Gigabyte B450 I AORUS PRO WIFI         | 1        | 2.27%   |
| Foxconn Pro3500 Series                 | 1        | 2.27%   |
| Dell Vostro 270                        | 1        | 2.27%   |
| Dell Precision Tower 5810              | 1        | 2.27%   |
| Dell OptiPlex GX520                    | 1        | 2.27%   |
| Dell OptiPlex 990                      | 1        | 2.27%   |
| Dell OptiPlex 9020                     | 1        | 2.27%   |
| Dell OptiPlex 760                      | 1        | 2.27%   |
| Dell OptiPlex 755                      | 1        | 2.27%   |
| Dell OptiPlex 7050                     | 1        | 2.27%   |
| Dell OptiPlex 5040                     | 1        | 2.27%   |
| Dell OptiPlex 390                      | 1        | 2.27%   |
| Dell OptiPlex 380                      | 1        | 2.27%   |
| Dell OptiPlex 3020                     | 1        | 2.27%   |
| ASUS M5A97 R2.0                        | 1        | 2.27%   |
| ASRock X570 Steel Legend               | 1        | 2.27%   |
| ASRock B450M Pro4                      | 1        | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 12       | 27.27%  |
| HP Compaq          | 8        | 18.18%  |
| MSI MS-7C02        | 2        | 4.55%   |
| Lenovo ThinkCentre | 2        | 4.55%   |
| MSI MS-7D31        | 1        | 2.27%   |
| MSI 500-007A       | 1        | 2.27%   |
| MSI 0A90           | 1        | 2.27%   |
| Intel Starmax      | 1        | 2.27%   |
| HP Z400            | 1        | 2.27%   |
| HP xw4600          | 1        | 2.27%   |
| HP ProDesk         | 1        | 2.27%   |
| HP EliteDesk       | 1        | 2.27%   |
| Gigabyte Z68XP-UD3 | 1        | 2.27%   |
| Gigabyte TRX40     | 1        | 2.27%   |
| Gigabyte H110M-A   | 1        | 2.27%   |
| Gigabyte B450      | 1        | 2.27%   |
| Foxconn Pro3500    | 1        | 2.27%   |
| Dell Vostro        | 1        | 2.27%   |
| Dell Precision     | 1        | 2.27%   |
| ASUS M5A97         | 1        | 2.27%   |
| ASRock X570        | 1        | 2.27%   |
| ASRock B450M       | 1        | 2.27%   |
| Acer Veriton       | 1        | 2.27%   |
| Unknown            | 1        | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 6        | 13.64%  |
| 2013 | 4        | 9.09%   |
| 2012 | 4        | 9.09%   |
| 2011 | 4        | 9.09%   |
| 2008 | 4        | 9.09%   |
| 2019 | 3        | 6.82%   |
| 2015 | 3        | 6.82%   |
| 2010 | 3        | 6.82%   |
| 2007 | 3        | 6.82%   |
| 2022 | 2        | 4.55%   |
| 2016 | 2        | 4.55%   |
| 2014 | 2        | 4.55%   |
| 2005 | 2        | 4.55%   |
| 2009 | 1        | 2.27%   |
| 2004 | 1        | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 44       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 42       | 93.33%  |
| Enabled  | 3        | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 44       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 10       | 22.22%  |
| 16.01-24.0      | 10       | 22.22%  |
| 1.01-2.0        | 6        | 13.33%  |
| 4.01-8.0        | 5        | 11.11%  |
| 32.01-64.0      | 5        | 11.11%  |
| 8.01-16.0       | 5        | 11.11%  |
| More than 256.0 | 1        | 2.22%   |
| 24.01-32.0      | 1        | 2.22%   |
| 2.01-3.0        | 1        | 2.22%   |
| 64.01-256.0     | 1        | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 14       | 30.43%  |
| 2.01-3.0  | 11       | 23.91%  |
| 4.01-8.0  | 9        | 19.57%  |
| 0.51-1.0  | 5        | 10.87%  |
| 3.01-4.0  | 3        | 6.52%   |
| 8.01-16.0 | 2        | 4.35%   |
| 0.01-0.5  | 2        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 45.45%  |
| 2      | 15       | 34.09%  |
| 3      | 4        | 9.09%   |
| 4      | 3        | 6.82%   |
| 6      | 1        | 2.27%   |
| 5      | 1        | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 54.55%  |
| Yes       | 20       | 45.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 43       | 97.73%  |
| No        | 1        | 2.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 54.55%  |
| Yes       | 20       | 45.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 84.09%  |
| Yes       | 7        | 15.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Kenya   | 44       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City    | Desktops | Percent |
|---------|----------|---------|
| Nairobi | 41       | 91.11%  |
| Nyeri   | 1        | 2.22%   |
| Nakuru  | 1        | 2.22%   |
| Mombasa | 1        | 2.22%   |
| Kericho | 1        | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 24       | 31     | 31.17%  |
| WDC                       | 15       | 18     | 19.48%  |
| Toshiba                   | 5        | 5      | 6.49%   |
| Samsung Electronics       | 5        | 8      | 6.49%   |
| HGST                      | 5        | 7      | 6.49%   |
| SPCC                      | 3        | 7      | 3.9%    |
| Intel                     | 3        | 3      | 3.9%    |
| Hitachi                   | 3        | 3      | 3.9%    |
| Team                      | 2        | 2      | 2.6%    |
| SanDisk                   | 2        | 2      | 2.6%    |
| Maxtor                    | 2        | 2      | 2.6%    |
| Unknown                   | 2        | 2      | 2.6%    |
| Unknown                   | 1        | 1      | 1.3%    |
| Micron/Crucial Technology | 1        | 2      | 1.3%    |
| LITEON                    | 1        | 1      | 1.3%    |
| Kingston                  | 1        | 1      | 1.3%    |
| HUAWEI                    | 1        | 1      | 1.3%    |
| China                     | 1        | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WD3200AAJS-56M0A0 320GB        | 3        | 3.61%   |
| Seagate ST500DM002-1BD142 500GB    | 3        | 3.61%   |
| Toshiba DT01ACA100 1TB             | 2        | 2.41%   |
| Team T253X2001T 1TB SSD            | 2        | 2.41%   |
| SPCC Solid State Disk 256GB        | 2        | 2.41%   |
| SPCC M.2 PCIe SSD 512GB            | 2        | 2.41%   |
| Seagate ST500VT000-1BS142 500GB    | 2        | 2.41%   |
| Seagate ST3320418AS 320GB          | 2        | 2.41%   |
| Seagate ST3250318AS 250GB          | 2        | 2.41%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 2.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 2.41%   |
| Samsung SSD 840 EVO 250GB          | 2        | 2.41%   |
| Unknown                            | 2        | 2.41%   |
| WDC WD800GD-75FLC3 80GB            | 1        | 1.2%    |
| WDC WD60EZAZ-00SF3B0 6TB           | 1        | 1.2%    |
| WDC WD5003AZEX-00K1GA0 500GB       | 1        | 1.2%    |
| WDC WD5000AZLX-08K2TA0 500GB       | 1        | 1.2%    |
| WDC WD5000AVVS-63M8B0 500GB        | 1        | 1.2%    |
| WDC WD5000AVDS-63U7B1 500GB        | 1        | 1.2%    |
| WDC WD5000AAKX-08U6AA0 500GB       | 1        | 1.2%    |
| WDC WD3200AAKS-75L9A0 320GB        | 1        | 1.2%    |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 1.2%    |
| WDC WD3200AAJS-00B4A0 320GB        | 1        | 1.2%    |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1.2%    |
| WDC WD2500AAKX-08U6AA0 250GB       | 1        | 1.2%    |
| WDC WD10EARX-00N0YB0 1TB           | 1        | 1.2%    |
| Unknown L200 Hard drive 2TB        | 1        | 1.2%    |
| Toshiba THNSNJ128GCSU 128GB SSD    | 1        | 1.2%    |
| Toshiba MK2555GSX 250GB            | 1        | 1.2%    |
| Toshiba DT01ABA100V 1TB            | 1        | 1.2%    |
| Seagate ST_M13FQBL QNR 4GB         | 1        | 1.2%    |
| Seagate ST380817AS 80GB            | 1        | 1.2%    |
| Seagate ST3808110AS 80GB           | 1        | 1.2%    |
| Seagate ST380013AS 80GB            | 1        | 1.2%    |
| Seagate ST380011A 80GB             | 1        | 1.2%    |
| Seagate ST3500418AS 500GB          | 1        | 1.2%    |
| Seagate ST3500410SV 500GB          | 1        | 1.2%    |
| Seagate ST3250312AS 250GB          | 1        | 1.2%    |
| Seagate ST3160812AS Q 160GB        | 1        | 1.2%    |
| Seagate ST3000DM001-1CH166 3TB     | 1        | 1.2%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 30     | 41.82%  |
| WDC                 | 15       | 18     | 27.27%  |
| HGST                | 5        | 7      | 9.09%   |
| Toshiba             | 4        | 4      | 7.27%   |
| Hitachi             | 3        | 3      | 5.45%   |
| Maxtor              | 2        | 2      | 3.64%   |
| Unknown             | 1        | 1      | 1.82%   |
| Samsung Electronics | 1        | 1      | 1.82%   |
| Unknown             | 1        | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 5      | 18.75%  |
| Intel               | 3        | 3      | 18.75%  |
| Team                | 2        | 2      | 12.5%   |
| SPCC                | 2        | 3      | 12.5%   |
| Toshiba             | 1        | 1      | 6.25%   |
| SanDisk             | 1        | 1      | 6.25%   |
| LITEON              | 1        | 1      | 6.25%   |
| Kingston            | 1        | 1      | 6.25%   |
| China               | 1        | 1      | 6.25%   |
| Unknown             | 1        | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 39       | 67     | 66.1%   |
| SSD     | 13       | 19     | 22.03%  |
| NVMe    | 5        | 9      | 8.47%   |
| Unknown | 2        | 2      | 3.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 43       | 87     | 87.76%  |
| NVMe | 5        | 9      | 10.2%   |
| SAS  | 1        | 1      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 36       | 58     | 63.16%  |
| 0.51-1.0   | 12       | 17     | 21.05%  |
| 1.01-2.0   | 5        | 6      | 8.77%   |
| 4.01-10.0  | 2        | 3      | 3.51%   |
| 3.01-4.0   | 1        | 1      | 1.75%   |
| 2.01-3.0   | 1        | 1      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 9        | 18.75%  |
| 501-1000       | 9        | 18.75%  |
| 251-500        | 7        | 14.58%  |
| 101-250        | 7        | 14.58%  |
| 51-100         | 7        | 14.58%  |
| More than 3000 | 4        | 8.33%   |
| 1-20           | 2        | 4.17%   |
| 21-50          | 1        | 2.08%   |
| 2001-3000      | 1        | 2.08%   |
| Unknown        | 1        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 16       | 32.65%  |
| 251-500   | 6        | 12.24%  |
| 21-50     | 6        | 12.24%  |
| 1001-2000 | 6        | 12.24%  |
| 101-250   | 5        | 10.2%   |
| 501-1000  | 5        | 10.2%   |
| 51-100    | 4        | 8.16%   |
| Unknown   | 1        | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000AZLX-08K2TA0 500GB       | 1        | 1      | 12.5%   |
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 1      | 12.5%   |
| Toshiba MK2555GSX 250GB            | 1        | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 12.5%   |
| Seagate ST3500418AS 500GB          | 1        | 1      | 12.5%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 12.5%   |
| HGST HTS721010A9 1TB               | 1        | 2      | 12.5%   |
| Unknown                            | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 37.5%   |
| WDC     | 2        | 2      | 25%     |
| Toshiba | 1        | 1      | 12.5%   |
| HGST    | 1        | 2      | 12.5%   |
| Unknown | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 37.5%   |
| WDC     | 2        | 2      | 25%     |
| Toshiba | 1        | 1      | 12.5%   |
| HGST    | 1        | 2      | 12.5%   |
| Unknown | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 9      | 100%    |

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
| Detected | 30       | 51     | 61.22%  |
| Works    | 12       | 37     | 24.49%  |
| Malfunc  | 7        | 9      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 35       | 64.81%  |
| AMD                       | 9        | 16.67%  |
| Silicon Motion            | 1        | 1.85%   |
| SanDisk                   | 1        | 1.85%   |
| Samsung Electronics       | 1        | 1.85%   |
| Realtek Semiconductor     | 1        | 1.85%   |
| Micron/Crucial Technology | 1        | 1.85%   |
| Marvell Technology Group  | 1        | 1.85%   |
| LSI Logic / Symbios Logic | 1        | 1.85%   |
| JMicron Technology        | 1        | 1.85%   |
| Broadcom / LSI            | 1        | 1.85%   |
| ASMedia Technology        | 1        | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 9.72%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 6.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 6.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 5.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 5.56%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 4.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 4.17%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.78%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 2.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 1.39%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 1        | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.39%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 1.39%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 1.39%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 1.39%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 1        | 1.39%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.39%   |
| Intel Elkhart Lake SATA AHCI                                                            | 1        | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.39%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.39%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.39%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.39%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.39%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.39%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                           | 1        | 1.39%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 1        | 1.39%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 1.39%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.39%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1        | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 29       | 51.79%  |
| IDE  | 15       | 26.79%  |
| RAID | 6        | 10.71%  |
| NVMe | 5        | 8.93%   |
| SCSI | 1        | 1.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 79.55%  |
| AMD    | 9        | 20.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Pentium 4 CPU 2.80GHz                    | 2        | 4.55%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 2        | 4.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 2        | 4.55%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 2        | 4.55%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 4.55%   |
| Intel Xeon CPU W3680 @ 3.33GHz                 | 1        | 2.27%   |
| Intel Xeon CPU E5-1630 v3 @ 3.70GHz            | 1        | 2.27%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz    | 1        | 2.27%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 2.27%   |
| Intel Pentium 4 CPU 3.00GHz                    | 1        | 2.27%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 2.27%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 1        | 2.27%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 2.27%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 2.27%   |
| Intel Core i5-4430S CPU @ 2.70GHz              | 1        | 2.27%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 1        | 2.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 2.27%   |
| Intel Core i3-4170 CPU @ 3.70GHz               | 1        | 2.27%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 1        | 2.27%   |
| Intel Core i3-3240 CPU @ 3.40GHz               | 1        | 2.27%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 1        | 2.27%   |
| Intel Core i3 CPU 550 @ 3.20GHz                | 1        | 2.27%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 2.27%   |
| Intel Core 2 Quad CPU @ 2.40GHz                | 1        | 2.27%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz           | 1        | 2.27%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz           | 1        | 2.27%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 1        | 2.27%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz           | 1        | 2.27%   |
| Intel Core 2 CPU 6420 @ 2.13GHz                | 1        | 2.27%   |
| Intel Cnre i5-4590S CPU @ 3.00GHz              | 1        | 2.27%   |
| Intel Celeron J6412 @ 2.00GHz                  | 1        | 2.27%   |
| Intel 13th Gen Core i7-13700K                  | 1        | 2.27%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 2.27%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 2.27%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 2.27%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 2.27%   |
| AMD Phenom II X3 B75 Processor                 | 1        | 2.27%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 2.27%   |
| AMD A4-5300 APU with Radeon HD Graphics        | 1        | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 7        | 15.91%  |
| Intel Core i3           | 7        | 15.91%  |
| Intel Pentium 4         | 4        | 9.09%   |
| Intel Core i7           | 4        | 9.09%   |
| Intel Core 2 Duo        | 4        | 9.09%   |
| AMD Ryzen 5             | 3        | 6.82%   |
| Other                   | 2        | 4.55%   |
| Intel Xeon              | 2        | 4.55%   |
| Intel Core 2 Quad       | 2        | 4.55%   |
| Intel Pentium Dual-Core | 1        | 2.27%   |
| Intel Core 2            | 1        | 2.27%   |
| Intel Celeron           | 1        | 2.27%   |
| AMD Ryzen Threadripper  | 1        | 2.27%   |
| AMD Ryzen 9             | 1        | 2.27%   |
| AMD Ryzen 7             | 1        | 2.27%   |
| AMD Phenom II X3        | 1        | 2.27%   |
| AMD FX                  | 1        | 2.27%   |
| AMD A4                  | 1        | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 15       | 34.09%  |
| 2      | 13       | 29.55%  |
| 6      | 5        | 11.36%  |
| 1      | 5        | 11.36%  |
| 3      | 2        | 4.55%   |
| 32     | 1        | 2.27%   |
| 16     | 1        | 2.27%   |
| 12     | 1        | 2.27%   |
| 8      | 1        | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 44       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 24       | 54.55%  |
| 1      | 20       | 45.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 44       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 20%     |
| 0x306a9    | 6        | 13.33%  |
| 0x506e3    | 3        | 6.67%   |
| 0x206a7    | 3        | 6.67%   |
| 0x1067a    | 3        | 6.67%   |
| 0x0800820d | 3        | 6.67%   |
| 0x306c3    | 2        | 4.44%   |
| 0x10676    | 2        | 4.44%   |
| 0xf65      | 1        | 2.22%   |
| 0xf49      | 1        | 2.22%   |
| 0xf43      | 1        | 2.22%   |
| 0x906ea    | 1        | 2.22%   |
| 0x90661    | 1        | 2.22%   |
| 0x6f7      | 1        | 2.22%   |
| 0x6f6      | 1        | 2.22%   |
| 0x306f2    | 1        | 2.22%   |
| 0x206c2    | 1        | 2.22%   |
| 0x20655    | 1        | 2.22%   |
| 0x0a201016 | 1        | 2.22%   |
| 0x08301039 | 1        | 2.22%   |
| 0x06001119 | 1        | 2.22%   |
| 0x0600084f | 1        | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 6        | 13.64%  |
| Haswell          | 6        | 13.64%  |
| Penryn           | 5        | 11.36%  |
| Zen+             | 4        | 9.09%   |
| NetBurst         | 4        | 9.09%   |
| Skylake          | 3        | 6.82%   |
| SandyBridge      | 3        | 6.82%   |
| Core             | 3        | 6.82%   |
| Westmere         | 2        | 4.55%   |
| Piledriver       | 2        | 4.55%   |
| Zen 3            | 1        | 2.27%   |
| Zen 2            | 1        | 2.27%   |
| Tremont          | 1        | 2.27%   |
| KabyLake         | 1        | 2.27%   |
| K10              | 1        | 2.27%   |
| Alderlake Hybrid | 1        | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 25       | 52.08%  |
| Nvidia | 13       | 27.08%  |
| AMD    | 10       | 20.83%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 10.42%  |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 6.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 6.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 6.25%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 4.17%   |
| Intel HD Graphics 530                                                       | 2        | 4.17%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 4.17%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 4.17%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 4.17%   |
| Nvidia GT218 [NVS 300]                                                      | 1        | 2.08%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 2.08%   |
| Nvidia GK107GL [Quadro 410]                                                 | 1        | 2.08%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 2.08%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 2.08%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 2.08%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 2.08%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 2.08%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 1        | 2.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.08%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                | 1        | 2.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.08%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 2.08%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 2.08%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 1        | 2.08%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 2.08%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 2.08%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 22       | 48.89%  |
| 1 x Nvidia     | 12       | 26.67%  |
| 1 x AMD        | 10       | 22.22%  |
| Intel + Nvidia | 1        | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 39       | 88.64%  |
| Proprietary | 4        | 9.09%   |
| Unknown     | 1        | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 59.09%  |
| 0.51-1.0   | 5        | 11.36%  |
| 7.01-8.0   | 3        | 6.82%   |
| 3.01-4.0   | 3        | 6.82%   |
| 1.01-2.0   | 3        | 6.82%   |
| 0.01-0.5   | 3        | 6.82%   |
| 8.01-16.0  | 1        | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 15       | 31.25%  |
| Dell                | 11       | 22.92%  |
| Sony                | 4        | 8.33%   |
| Samsung Electronics | 3        | 6.25%   |
| Lenovo              | 3        | 6.25%   |
| BenQ                | 2        | 4.17%   |
| VIE                 | 1        | 2.08%   |
| Unknown (XXX)       | 1        | 2.08%   |
| Unknown             | 1        | 2.08%   |
| Sceptre Tech        | 1        | 2.08%   |
| S2-Tek              | 1        | 2.08%   |
| NEC Computers       | 1        | 2.08%   |
| Hitachi             | 1        | 2.08%   |
| HannStar            | 1        | 2.08%   |
| Acer                | 1        | 2.08%   |
| Unknown             | 1        | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S22E450 SAM0C7A 1920x1080 477x268mm 21.5-inch     | 2        | 3.92%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                  | 2        | 3.92%   |
| Dell E1910H DELD023 1366x768 410x230mm 18.5-inch                      | 2        | 3.92%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 1.96%   |
| Unknown LCD Monitor Hitachi Engineering Company Ltd HISENSE 3200x1080 | 1        | 1.96%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 1        | 1.96%   |
| Sony TV SNYEF03 1600x900                                              | 1        | 1.96%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                         | 1        | 1.96%   |
| Sony TV SNY6F02 1360x768                                              | 1        | 1.96%   |
| Sony TV SNY0902 1920x1080                                             | 1        | 1.96%   |
| Sceptre Tech Sceptre Y27 SPT0AB9 2560x1440 597x336mm 27.0-inch        | 1        | 1.96%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1        | 1.96%   |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                       | 1        | 1.96%   |
| NEC Computers EA193Mi NEC6956 1280x1024 375x300mm 18.9-inch           | 1        | 1.96%   |
| Lenovo LEN LI1931ewA LEN65A1 1366x768 409x230mm 18.5-inch             | 1        | 1.96%   |
| Lenovo LEN E2054A LEN60DF 1440x900 419x262mm 19.5-inch                | 1        | 1.96%   |
| Hitachi Hisense HEC0030 1920x1080 580x330mm 26.3-inch                 | 1        | 1.96%   |
| Hewlett-Packard Z27s HWP317F 3840x2160 600x340mm 27.2-inch            | 1        | 1.96%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1        | 1.96%   |
| Hewlett-Packard Z22i HWP308B 1920x1080 477x268mm 21.5-inch            | 1        | 1.96%   |
| Hewlett-Packard P222va HWP322C 1920x1080 477x268mm 21.5-inch          | 1        | 1.96%   |
| Hewlett-Packard LE2202x HWP2966 1920x1080 476x268mm 21.5-inch         | 1        | 1.96%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 1        | 1.96%   |
| Hewlett-Packard LCD Monitor L1710                                     | 1        | 1.96%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 509x286mm 23.0-inch          | 1        | 1.96%   |
| Hewlett-Packard LA2206 HWP2948 1920x1080 476x268mm 21.5-inch          | 1        | 1.96%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 470x300mm 22.0-inch          | 1        | 1.96%   |
| Hewlett-Packard L2311c HWP2994 1920x1080 509x286mm 23.0-inch          | 1        | 1.96%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1        | 1.96%   |
| Hewlett-Packard L1706 HWP265C 1280x1024 340x270mm 17.1-inch           | 1        | 1.96%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch            | 1        | 1.96%   |
| Hewlett-Packard E222 HWP3262 1920x1080 476x268mm 21.5-inch            | 1        | 1.96%   |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x287mm 23.0-inch            | 1        | 1.96%   |
| HannStar HW191 HSD8991 1440x900 408x255mm 18.9-inch                   | 1        | 1.96%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1        | 1.96%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1        | 1.96%   |
| Dell P2314T DEL40A0 1920x1080 510x290mm 23.1-inch                     | 1        | 1.96%   |
| Dell P1914S DELF04B 1280x1024 376x301mm 19.0-inch                     | 1        | 1.96%   |
| Dell E2316H DELF06B 1920x1080 509x286mm 23.0-inch                     | 1        | 1.96%   |
| Dell E228WFP DELD014 1680x1050 473x296mm 22.0-inch                    | 1        | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 16       | 34.78%  |
| 1280x1024 (SXGA)   | 8        | 17.39%  |
| 3840x2160 (4K)     | 3        | 6.52%   |
| 1440x900 (WXGA+)   | 3        | 6.52%   |
| 1366x768 (WXGA)    | 3        | 6.52%   |
| 2560x1440 (QHD)    | 2        | 4.35%   |
| 1920x1200 (WUXGA)  | 2        | 4.35%   |
| 1680x1050 (WSXGA+) | 2        | 4.35%   |
| 1600x900 (HD+)     | 2        | 4.35%   |
| 1024x768 (XGA)     | 2        | 4.35%   |
| 3200x1080          | 1        | 2.17%   |
| 1360x768           | 1        | 2.17%   |
| Unknown            | 1        | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 8        | 17.02%  |
| 19      | 6        | 12.77%  |
| 27      | 4        | 8.51%   |
| 23      | 4        | 8.51%   |
| 18      | 4        | 8.51%   |
| 17      | 4        | 8.51%   |
| 72      | 3        | 6.38%   |
| 24      | 3        | 6.38%   |
| 22      | 3        | 6.38%   |
| Unknown | 2        | 4.26%   |
| 84      | 1        | 2.13%   |
| 54      | 1        | 2.13%   |
| 46      | 1        | 2.13%   |
| 42      | 1        | 2.13%   |
| 20      | 1        | 2.13%   |
| 15      | 1        | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 14       | 32.56%  |
| 501-600     | 11       | 25.58%  |
| 301-350     | 5        | 11.63%  |
| 351-400     | 4        | 9.3%    |
| 1501-2000   | 4        | 9.3%    |
| 1001-1500   | 2        | 4.65%   |
| Unknown     | 2        | 4.65%   |
| 901-1000    | 1        | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 26       | 57.78%  |
| 5/4     | 8        | 17.78%  |
| 16/10   | 8        | 17.78%  |
| Unknown | 2        | 4.44%   |
| 4/3     | 1        | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 24.44%  |
| 151-200        | 10       | 22.22%  |
| 141-150        | 7        | 15.56%  |
| More than 1000 | 5        | 11.11%  |
| 301-350        | 4        | 8.89%   |
| 251-300        | 3        | 6.67%   |
| 501-1000       | 2        | 4.44%   |
| Unknown        | 2        | 4.44%   |
| 101-110        | 1        | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 58.54%  |
| 101-120 | 10       | 24.39%  |
| 1-50    | 4        | 9.76%   |
| Unknown | 2        | 4.88%   |
| 161-240 | 1        | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 68.18%  |
| 2     | 11       | 25%     |
| 0     | 3        | 6.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 24       | 34.78%  |
| Realtek Semiconductor | 20       | 28.99%  |
| MediaTek              | 4        | 5.8%    |
| Broadcom Limited      | 4        | 5.8%    |
| Broadcom              | 4        | 5.8%    |
| Xiaomi                | 3        | 4.35%   |
| Qualcomm Atheros      | 3        | 4.35%   |
| Samsung Electronics   | 2        | 2.9%    |
| Ralink Technology     | 1        | 1.45%   |
| Qualcomm              | 1        | 1.45%   |
| OPPO Electronics      | 1        | 1.45%   |
| Huawei Technologies   | 1        | 1.45%   |
| Hewlett-Packard       | 1        | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 15.19%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7        | 8.86%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 5        | 6.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 6.33%   |
| MediaTek Wiko U316AT                                              | 4        | 5.06%   |
| Intel I211 Gigabit Network Connection                             | 3        | 3.8%    |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 2.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 2.53%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 2.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.53%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 2.53%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2        | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 1.27%   |
| Qualcomm Redmi Note 8                                             | 1        | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1        | 1.27%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 1.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.27%   |
| OPPO RMX2027                                                      | 1        | 1.27%   |
| Intel Wireless-AC 9260                                            | 1        | 1.27%   |
| Intel Wireless 8265 / 8275                                        | 1        | 1.27%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.27%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.27%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.27%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.27%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 1.27%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.27%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.27%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1        | 1.27%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 1.27%   |
| Huawei Mass Storage                                               | 1        | 1.27%   |
| HP L2311c LAN7500 Ethernet                                        | 1        | 1.27%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.27%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.27%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 1.27%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 57.14%  |
| Intel                 | 5        | 23.81%  |
| Qualcomm Atheros      | 2        | 9.52%   |
| Ralink Technology     | 1        | 4.76%   |
| Broadcom              | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7        | 33.33%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 5        | 23.81%  |
| Intel Wi-Fi 6 AX200                                            | 2        | 9.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 4.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 4.76%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 4.76%   |
| Intel Wireless-AC 9260                                         | 1        | 4.76%   |
| Intel Wireless 8265 / 8275                                     | 1        | 4.76%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 4.76%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 24       | 42.86%  |
| Realtek Semiconductor | 12       | 21.43%  |
| MediaTek              | 4        | 7.14%   |
| Broadcom Limited      | 4        | 7.14%   |
| Xiaomi                | 3        | 5.36%   |
| Broadcom              | 3        | 5.36%   |
| Samsung Electronics   | 2        | 3.57%   |
| Qualcomm Atheros      | 1        | 1.79%   |
| Qualcomm              | 1        | 1.79%   |
| OPPO Electronics      | 1        | 1.79%   |
| Hewlett-Packard       | 1        | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 21.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 8.77%   |
| MediaTek Wiko U316AT                                              | 4        | 7.02%   |
| Intel I211 Gigabit Network Connection                             | 3        | 5.26%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 5.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 3.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 3.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 3.51%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 3.51%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2        | 3.51%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.75%   |
| Qualcomm Redmi Note 8                                             | 1        | 1.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.75%   |
| OPPO RMX2027                                                      | 1        | 1.75%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.75%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.75%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.75%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.75%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.75%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.75%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1        | 1.75%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 1.75%   |
| HP L2311c LAN7500 Ethernet                                        | 1        | 1.75%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.75%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.75%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 1.75%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 43       | 67.19%  |
| WiFi     | 20       | 31.25%  |
| Modem    | 1        | 1.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 75%     |
| WiFi     | 10       | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 75%     |
| 2     | 8        | 18.18%  |
| 4     | 1        | 2.27%   |
| 3     | 1        | 2.27%   |
| 0     | 1        | 2.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 43       | 97.73%  |
| Yes  | 1        | 2.27%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 5        | 71.43%  |
| Cambridge Silicon Radio | 2        | 28.57%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 2        | 28.57%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 28.57%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 14.29%  |
| Intel Bluetooth wireless interface                  | 1        | 14.29%  |
| Intel Bluetooth Device                              | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 34       | 49.28%  |
| Nvidia                   | 12       | 17.39%  |
| AMD                      | 12       | 17.39%  |
| Texas Instruments        | 2        | 2.9%    |
| Lenovo                   | 2        | 2.9%    |
| C-Media Electronics      | 2        | 2.9%    |
| Micro Star International | 1        | 1.45%   |
| Medeli Electronics       | 1        | 1.45%   |
| JMTek                    | 1        | 1.45%   |
| Giga-Byte Technology     | 1        | 1.45%   |
| Generalplus Technology   | 1        | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 6.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 6.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 6.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 6.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 5.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 5.13%   |
| Nvidia High Definition Audio Controller                                    | 3        | 3.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 3.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 3.85%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 2.56%   |
| Lenovo T2224zD                                                             | 2        | 2.56%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 2.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.56%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.56%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.28%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.28%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.28%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.28%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.28%   |
| Micro Star International USB Audio                                         | 1        | 1.28%   |
| Medeli Electronics USB Audio Device                                        | 1        | 1.28%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.28%   |
| Intel Elkhart Lake High Density Audio bus interface                        | 1        | 1.28%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.28%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.28%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 1.28%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 1.28%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 1.28%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1        | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.28%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.28%   |
| Giga-Byte Technology USB Audio                                             | 1        | 1.28%   |
| Generalplus Technology USB Audio Device                                    | 1        | 1.28%   |
| C-Media Electronics USB PnP Sound Device                                   | 1        | 1.28%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 1.28%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 6        | 25%     |
| Kingston            | 4        | 16.67%  |
| Crucial             | 4        | 16.67%  |
| Micron Technology   | 3        | 12.5%   |
| Samsung Electronics | 2        | 8.33%   |
| G.Skill             | 2        | 8.33%   |
| TwinMOS             | 1        | 4.17%   |
| Team                | 1        | 4.17%   |
| Corsair             | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 2        | 7.69%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s       | 1        | 3.85%   |
| TwinMOS RAM 9DECBMZB-TATP 2048MB DIMM DDR3 1333MT/s    | 1        | 3.85%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s    | 1        | 3.85%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 3.85%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 3.85%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s   | 1        | 3.85%   |
| SK hynix RAM HMT125U7BFR8C-H9 2GB DIMM DDR3 1333MT/s   | 1        | 3.85%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM 1333MT/s        | 1        | 3.85%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s   | 1        | 3.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s | 1        | 3.85%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s         | 1        | 3.85%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s    | 1        | 3.85%   |
| Micron RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s   | 1        | 3.85%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s   | 1        | 3.85%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s   | 1        | 3.85%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 1        | 3.85%   |
| Kingston RAM HP497157-D88-ELFW 2GB DIMM DDR3 1333MT/s  | 1        | 3.85%   |
| Kingston RAM 99P5663-013.A00G 8GB SODIMM DDR4 2667MT/s | 1        | 3.85%   |
| Kingston RAM 9905734-102.A00G 32GB DIMM DDR4 3200MT/s  | 1        | 3.85%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s  | 1        | 3.85%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s  | 1        | 3.85%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s  | 1        | 3.85%   |
| Crucial RAM CB16GU2400.C16J 16384MB DIMM DDR4 2400MT/s | 1        | 3.85%   |
| Corsair RAM CMK32GX5M2B5600C36 16GB DIMM DDR5 5800MT/s | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 9        | 45%     |
| DDR4  | 8        | 40%     |
| SDRAM | 2        | 10%     |
| DDR5  | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 88.89%  |
| SODIMM | 2        | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 28.57%  |
| 4096  | 6        | 28.57%  |
| 16384 | 4        | 19.05%  |
| 2048  | 3        | 14.29%  |
| 32768 | 2        | 9.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 6        | 30%     |
| 2667  | 3        | 15%     |
| 1333  | 3        | 15%     |
| 3600  | 2        | 10%     |
| 5800  | 1        | 5%      |
| 3800  | 1        | 5%      |
| 3200  | 1        | 5%      |
| 2400  | 1        | 5%      |
| 2000  | 1        | 5%      |
| 1867  | 1        | 5%      |

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
| Realtek Semiconductor | 2        | 33.33%  |
| MacroSilicon          | 1        | 16.67%  |
| Logitech              | 1        | 16.67%  |
| Cubeternet            | 1        | 16.67%  |
| Chicony Electronics   | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek FULL HD 1080P Webcam      | 2        | 33.33%  |
| MacroSilicon USB Video            | 1        | 16.67%  |
| Logitech Webcam C270              | 1        | 16.67%  |
| Cubeternet GL-UPC822 UVC WebCam   | 1        | 16.67%  |
| Chicony HP 720p HD Monitor Webcam | 1        | 16.67%  |

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
| 0     | 38       | 86.36%  |
| 1     | 6        | 13.64%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/ethernet     | 2        | 33.33%  |
| Graphics card    | 2        | 33.33%  |
| Unassigned class | 1        | 16.67%  |
| Net/wireless     | 1        | 16.67%  |

