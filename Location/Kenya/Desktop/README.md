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

Total: 69

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| HP       | 1494                     | [7b5806585f](https://linux-hardware.org/?probe=7b5806585f) | May 04, 2024 |
| Dell     | 0KRC95 A00               | [72ba135dda](https://linux-hardware.org/?probe=72ba135dda) | May 01, 2024 |
| Dell     | 0WWJRX A01               | [21af8ccdc8](https://linux-hardware.org/?probe=21af8ccdc8) | Apr 27, 2024 |
| ASRock   | B450M Pro4               | [20eede7cbf](https://linux-hardware.org/?probe=20eede7cbf) | Jan 12, 2024 |
| Dell     | 0GY6Y8 A02               | [81e91658c9](https://linux-hardware.org/?probe=81e91658c9) | Dec 30, 2023 |
| HP       | 0968h                    | [b1fb94198e](https://linux-hardware.org/?probe=b1fb94198e) | Dec 10, 2023 |
| Dell     | 0XR1GT A00               | [17b5d35090](https://linux-hardware.org/?probe=17b5d35090) | Nov 19, 2023 |
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
| Ubuntu 20.04        | 10       | 18.87%  |
| ArcoLinux Rolling   | 5        | 9.43%   |
| Ubuntu 18.04        | 3        | 5.66%   |
| Linux Mint 21       | 3        | 5.66%   |
| Zorin 15            | 2        | 3.77%   |
| Ubuntu 22.04        | 2        | 3.77%   |
| OpenMandriva 5.0    | 2        | 3.77%   |
| Manjaro             | 2        | 3.77%   |
| Fedora 38           | 2        | 3.77%   |
| Ubuntu Studio 21.10 | 1        | 1.89%   |
| Pop!_OS 20.10       | 1        | 1.89%   |
| Pop!_OS 20.04       | 1        | 1.89%   |
| OpenMandriva 4.50   | 1        | 1.89%   |
| OpenMandriva 4.2    | 1        | 1.89%   |
| Mageia 6            | 1        | 1.89%   |
| Lubuntu 20.10       | 1        | 1.89%   |
| Linux Mint 21.2     | 1        | 1.89%   |
| Linux Mint 20.3     | 1        | 1.89%   |
| Kali 2020.1         | 1        | 1.89%   |
| Fedora 36           | 1        | 1.89%   |
| Fedora 34           | 1        | 1.89%   |
| Fedora 33           | 1        | 1.89%   |
| Fedora 32           | 1        | 1.89%   |
| Endless 3.8.3       | 1        | 1.89%   |
| Elementary 6.1      | 1        | 1.89%   |
| Elementary 6        | 1        | 1.89%   |
| Deepin 23           | 1        | 1.89%   |
| Debian 12           | 1        | 1.89%   |
| Debian 11           | 1        | 1.89%   |
| BlackPanther 18.1   | 1        | 1.89%   |
| Arch Rolling        | 1        | 1.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 15       | 29.41%  |
| Linux Mint    | 5        | 9.8%    |
| Fedora        | 5        | 9.8%    |
| ArcoLinux     | 5        | 9.8%    |
| OpenMandriva  | 4        | 7.84%   |
| Zorin         | 2        | 3.92%   |
| Manjaro       | 2        | 3.92%   |
| Elementary    | 2        | 3.92%   |
| Debian        | 2        | 3.92%   |
| Ubuntu Studio | 1        | 1.96%   |
| Pop!_OS       | 1        | 1.96%   |
| Mageia        | 1        | 1.96%   |
| Lubuntu       | 1        | 1.96%   |
| Kali          | 1        | 1.96%   |
| Endless       | 1        | 1.96%   |
| Deepin        | 1        | 1.96%   |
| BlackPanther  | 1        | 1.96%   |
| Arch          | 1        | 1.96%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 6.6.2-desktop-1omv2390   | 2        | 3.64%   |
| 5.4.0-42-generic         | 2        | 3.64%   |
| 5.15.0-41-generic        | 2        | 3.64%   |
| 6.8.7-arch1-1            | 1        | 1.82%   |
| 6.6.30-1-MANJARO         | 1        | 1.82%   |
| 6.6.11-1-lts             | 1        | 1.82%   |
| 6.5.6-arch2-1            | 1        | 1.82%   |
| 6.5.5-200.fc38.x86_64    | 1        | 1.82%   |
| 6.4.15-200.fc38.x86_64   | 1        | 1.82%   |
| 6.2.0-32-generic         | 1        | 1.82%   |
| 6.1.32-amd64-desktop-hwe | 1        | 1.82%   |
| 6.1.0-14-686-pae         | 1        | 1.82%   |
| 5.8.4-200.fc32.x86_64    | 1        | 1.82%   |
| 5.8.13-200.fc32.x86_64   | 1        | 1.82%   |
| 5.8.0-7642-generic       | 1        | 1.82%   |
| 5.8.0-63-generic         | 1        | 1.82%   |
| 5.8.0-53-generic         | 1        | 1.82%   |
| 5.8.0-43-generic         | 1        | 1.82%   |
| 5.4.0-7642-generic       | 1        | 1.82%   |
| 5.4.0-37-generic         | 1        | 1.82%   |
| 5.4.0-33-generic         | 1        | 1.82%   |
| 5.4.0-28-generic         | 1        | 1.82%   |
| 5.4.0-19-generic         | 1        | 1.82%   |
| 5.4.0-137-generic        | 1        | 1.82%   |
| 5.4.0-124-generic        | 1        | 1.82%   |
| 5.3.0-kali2-amd64        | 1        | 1.82%   |
| 5.3.0-62-generic         | 1        | 1.82%   |
| 5.3.0-28-generic         | 1        | 1.82%   |
| 5.19.9-200.fc36.x86_64   | 1        | 1.82%   |
| 5.19.5-desktop-1omv4090  | 1        | 1.82%   |
| 5.19.0-45-generic        | 1        | 1.82%   |
| 5.16.2-zen1-1-zen        | 1        | 1.82%   |
| 5.15.85-1-MANJARO        | 1        | 1.82%   |
| 5.15.26-1-lts            | 1        | 1.82%   |
| 5.15.10-arch1-1          | 1        | 1.82%   |
| 5.15.0-76-generic        | 1        | 1.82%   |
| 5.15.0-58-generic        | 1        | 1.82%   |
| 5.15.0-52-generic        | 1        | 1.82%   |
| 5.13.0-48-generic        | 1        | 1.82%   |
| 5.13.0-40-generic        | 1        | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 9        | 16.36%  |
| 5.15.0  | 5        | 9.09%   |
| 5.8.0   | 4        | 7.27%   |
| 5.13.0  | 4        | 7.27%   |
| 5.3.0   | 3        | 5.45%   |
| 6.6.2   | 2        | 3.64%   |
| 5.11.0  | 2        | 3.64%   |
| 6.8.7   | 1        | 1.82%   |
| 6.6.30  | 1        | 1.82%   |
| 6.6.11  | 1        | 1.82%   |
| 6.5.6   | 1        | 1.82%   |
| 6.5.5   | 1        | 1.82%   |
| 6.4.15  | 1        | 1.82%   |
| 6.2.0   | 1        | 1.82%   |
| 6.1.32  | 1        | 1.82%   |
| 6.1.0   | 1        | 1.82%   |
| 5.8.4   | 1        | 1.82%   |
| 5.8.13  | 1        | 1.82%   |
| 5.19.9  | 1        | 1.82%   |
| 5.19.5  | 1        | 1.82%   |
| 5.19.0  | 1        | 1.82%   |
| 5.16.2  | 1        | 1.82%   |
| 5.15.85 | 1        | 1.82%   |
| 5.15.26 | 1        | 1.82%   |
| 5.15.10 | 1        | 1.82%   |
| 5.12.11 | 1        | 1.82%   |
| 5.10.14 | 1        | 1.82%   |
| 5.10.10 | 1        | 1.82%   |
| 5.10.0  | 1        | 1.82%   |
| 5.0.0   | 1        | 1.82%   |
| 4.9.56  | 1        | 1.82%   |
| 4.18.16 | 1        | 1.82%   |
| 4.15.0  | 1        | 1.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 9        | 16.67%  |
| 5.15    | 8        | 14.81%  |
| 5.8     | 5        | 9.26%   |
| 6.6     | 4        | 7.41%   |
| 5.13    | 4        | 7.41%   |
| 5.3     | 3        | 5.56%   |
| 5.19    | 3        | 5.56%   |
| 5.10    | 3        | 5.56%   |
| 6.5     | 2        | 3.7%    |
| 6.1     | 2        | 3.7%    |
| 5.11    | 2        | 3.7%    |
| 6.8     | 1        | 1.85%   |
| 6.4     | 1        | 1.85%   |
| 6.2     | 1        | 1.85%   |
| 5.16    | 1        | 1.85%   |
| 5.12    | 1        | 1.85%   |
| 5.0     | 1        | 1.85%   |
| 4.9     | 1        | 1.85%   |
| 4.18    | 1        | 1.85%   |
| 4.15    | 1        | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 48       | 97.96%  |
| i686   | 1        | 2.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 25       | 50%     |
| KDE5       | 8        | 16%     |
| X-Cinnamon | 5        | 10%     |
| XFCE       | 2        | 4%      |
| Pantheon   | 2        | 4%      |
| Unknown    | 2        | 4%      |
| LXQt       | 1        | 2%      |
| KDE6       | 1        | 2%      |
| DWM        | 1        | 2%      |
| DDE        | 1        | 2%      |
| Cinnamon   | 1        | 2%      |
| awesome    | 1        | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 37       | 75.51%  |
| Wayland | 10       | 20.41%  |
| Tty     | 2        | 4.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 44%     |
| SDDM    | 11       | 22%     |
| LightDM | 7        | 14%     |
| GDM3    | 6        | 12%     |
| GDM     | 4        | 8%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 39       | 79.59%  |
| en_GB   | 7        | 14.29%  |
| Unknown | 3        | 6.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 31       | 63.27%  |
| EFI  | 18       | 36.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 39       | 76.47%  |
| Overlay | 5        | 9.8%    |
| Btrfs   | 5        | 9.8%    |
| Tmpfs   | 1        | 1.96%   |
| Unknown | 1        | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 53.06%  |
| GPT     | 15       | 30.61%  |
| MBR     | 8        | 16.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 81.63%  |
| Yes       | 9        | 18.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 59.18%  |
| Yes       | 20       | 40.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 17       | 34.69%  |
| Hewlett-Packard     | 14       | 28.57%  |
| MSI                 | 5        | 10.2%   |
| Gigabyte Technology | 4        | 8.16%   |
| Lenovo              | 2        | 4.08%   |
| ASRock              | 2        | 4.08%   |
| Intel               | 1        | 2.04%   |
| Foxconn             | 1        | 2.04%   |
| ASUSTek Computer    | 1        | 2.04%   |
| Acer                | 1        | 2.04%   |
| Unknown             | 1        | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Dell OptiPlex 7010                     | 4        | 8.16%   |
| MSI MS-7C02                            | 2        | 4.08%   |
| MSI MS-7D31                            | 1        | 2.04%   |
| MSI 500-007A                           | 1        | 2.04%   |
| MSI 0A90                               | 1        | 2.04%   |
| Lenovo ThinkCentre E73 10AS00HRUM      | 1        | 2.04%   |
| Lenovo ThinkCentre E73 10AS00CVUM      | 1        | 2.04%   |
| Intel Starmax Desktop                  | 1        | 2.04%   |
| HP Z400 Workstation                    | 1        | 2.04%   |
| HP xw4600 Workstation                  | 1        | 2.04%   |
| HP ProDesk 600 G1 TWR                  | 1        | 2.04%   |
| HP EliteDesk 800 G4 TWR                | 1        | 2.04%   |
| HP Compaq Elite 8300 SFF               | 1        | 2.04%   |
| HP Compaq Elite 8300 CMT               | 1        | 2.04%   |
| HP Compaq dc7900 Convertible Minitower | 1        | 2.04%   |
| HP Compaq dc7800 Small Form Factor     | 1        | 2.04%   |
| HP Compaq dc7600 Convertible Minitower | 1        | 2.04%   |
| HP Compaq dc7100 SFF(DX878AV)          | 1        | 2.04%   |
| HP Compaq dc7100 CMT(PY244UC)          | 1        | 2.04%   |
| HP Compaq 8200 Elite CMT PC            | 1        | 2.04%   |
| HP Compaq 6005 Pro MT PC               | 1        | 2.04%   |
| HP Compaq 4000 Pro SFF PC              | 1        | 2.04%   |
| Gigabyte Z68XP-UD3                     | 1        | 2.04%   |
| Gigabyte TRX40 AORUS PRO WIFI          | 1        | 2.04%   |
| Gigabyte H110M-A                       | 1        | 2.04%   |
| Gigabyte B450 I AORUS PRO WIFI         | 1        | 2.04%   |
| Foxconn Pro3500 Series                 | 1        | 2.04%   |
| Dell Vostro 270                        | 1        | 2.04%   |
| Dell Precision Tower 5810              | 1        | 2.04%   |
| Dell OptiPlex GX520                    | 1        | 2.04%   |
| Dell OptiPlex 990                      | 1        | 2.04%   |
| Dell OptiPlex 9020                     | 1        | 2.04%   |
| Dell OptiPlex 760                      | 1        | 2.04%   |
| Dell OptiPlex 755                      | 1        | 2.04%   |
| Dell OptiPlex 7050                     | 1        | 2.04%   |
| Dell OptiPlex 5050                     | 1        | 2.04%   |
| Dell OptiPlex 5040                     | 1        | 2.04%   |
| Dell OptiPlex 390                      | 1        | 2.04%   |
| Dell OptiPlex 380                      | 1        | 2.04%   |
| Dell OptiPlex 3020                     | 1        | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 15       | 30.61%  |
| HP Compaq          | 10       | 20.41%  |
| MSI MS-7C02        | 2        | 4.08%   |
| Lenovo ThinkCentre | 2        | 4.08%   |
| MSI MS-7D31        | 1        | 2.04%   |
| MSI 500-007A       | 1        | 2.04%   |
| MSI 0A90           | 1        | 2.04%   |
| Intel Starmax      | 1        | 2.04%   |
| HP Z400            | 1        | 2.04%   |
| HP xw4600          | 1        | 2.04%   |
| HP ProDesk         | 1        | 2.04%   |
| HP EliteDesk       | 1        | 2.04%   |
| Gigabyte Z68XP-UD3 | 1        | 2.04%   |
| Gigabyte TRX40     | 1        | 2.04%   |
| Gigabyte H110M-A   | 1        | 2.04%   |
| Gigabyte B450      | 1        | 2.04%   |
| Foxconn Pro3500    | 1        | 2.04%   |
| Dell Vostro        | 1        | 2.04%   |
| Dell Precision     | 1        | 2.04%   |
| ASUS M5A97         | 1        | 2.04%   |
| ASRock X570        | 1        | 2.04%   |
| ASRock B450M       | 1        | 2.04%   |
| Acer Veriton       | 1        | 2.04%   |
| Unknown            | 1        | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 6        | 12.24%  |
| 2013 | 5        | 10.2%   |
| 2012 | 5        | 10.2%   |
| 2011 | 5        | 10.2%   |
| 2008 | 4        | 8.16%   |
| 2019 | 3        | 6.12%   |
| 2015 | 3        | 6.12%   |
| 2010 | 3        | 6.12%   |
| 2007 | 3        | 6.12%   |
| 2022 | 2        | 4.08%   |
| 2016 | 2        | 4.08%   |
| 2014 | 2        | 4.08%   |
| 2005 | 2        | 4.08%   |
| 2004 | 2        | 4.08%   |
| 2017 | 1        | 2.04%   |
| 2009 | 1        | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 49       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 47       | 94%     |
| Enabled  | 3        | 6%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 11       | 22%     |
| 16.01-24.0      | 11       | 22%     |
| 8.01-16.0       | 8        | 16%     |
| 1.01-2.0        | 6        | 12%     |
| 4.01-8.0        | 5        | 10%     |
| 32.01-64.0      | 5        | 10%     |
| More than 256.0 | 1        | 2%      |
| 24.01-32.0      | 1        | 2%      |
| 2.01-3.0        | 1        | 2%      |
| 64.01-256.0     | 1        | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 17       | 32.69%  |
| 2.01-3.0  | 12       | 23.08%  |
| 4.01-8.0  | 9        | 17.31%  |
| 3.01-4.0  | 5        | 9.62%   |
| 0.51-1.0  | 5        | 9.62%   |
| 8.01-16.0 | 2        | 3.85%   |
| 0.01-0.5  | 2        | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 46.94%  |
| 2      | 16       | 32.65%  |
| 3      | 5        | 10.2%   |
| 4      | 3        | 6.12%   |
| 6      | 1        | 2.04%   |
| 5      | 1        | 2.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 51.02%  |
| Yes       | 24       | 48.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 97.96%  |
| No        | 1        | 2.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 51.02%  |
| Yes       | 24       | 48.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 85.71%  |
| Yes       | 7        | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Kenya   | 49       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City     | Desktops | Percent |
|----------|----------|---------|
| Nairobi  | 45       | 90%     |
| Nyeri    | 1        | 2%      |
| Nakuru   | 1        | 2%      |
| Mombasa  | 1        | 2%      |
| Kericho  | 1        | 2%      |
| Kabarnet | 1        | 2%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 27       | 34     | 31.76%  |
| WDC                       | 15       | 18     | 17.65%  |
| Toshiba                   | 8        | 9      | 9.41%   |
| Samsung Electronics       | 5        | 9      | 5.88%   |
| HGST                      | 5        | 8      | 5.88%   |
| SPCC                      | 3        | 7      | 3.53%   |
| Maxtor                    | 3        | 3      | 3.53%   |
| Intel                     | 3        | 3      | 3.53%   |
| Hitachi                   | 3        | 3      | 3.53%   |
| Team                      | 2        | 2      | 2.35%   |
| Sandisk                   | 2        | 2      | 2.35%   |
| Unknown                   | 2        | 2      | 2.35%   |
| Unknown                   | 1        | 1      | 1.18%   |
| Micron/Crucial Technology | 1        | 2      | 1.18%   |
| LITEON                    | 1        | 1      | 1.18%   |
| Kingston                  | 1        | 1      | 1.18%   |
| HUAWEI                    | 1        | 1      | 1.18%   |
| Dahua                     | 1        | 1      | 1.18%   |
| China                     | 1        | 1      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 5        | 5.38%   |
| WDC WD3200AAJS-56M0A0 320GB        | 3        | 3.23%   |
| Seagate ST3320418AS 320GB          | 3        | 3.23%   |
| Toshiba MQ01ABD050V 500GB          | 2        | 2.15%   |
| Toshiba DT01ACA100 1TB             | 2        | 2.15%   |
| Team T253X2001T 1024GB SSD         | 2        | 2.15%   |
| SPCC Solid State Disk 256GB        | 2        | 2.15%   |
| SPCC M.2 PCIe SSD 512GB            | 2        | 2.15%   |
| Seagate ST500VT000-1BS142 500GB    | 2        | 2.15%   |
| Seagate ST3250318AS 250GB          | 2        | 2.15%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 2.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 2.15%   |
| Samsung SSD 840 EVO 250GB          | 2        | 2.15%   |
| Unknown                            | 2        | 2.15%   |
| WDC WD800GD-75FLC3 80GB            | 1        | 1.08%   |
| WDC WD60EZAZ-00SF3B0 6TB           | 1        | 1.08%   |
| WDC WD5003AZEX-00K1GA0 500GB       | 1        | 1.08%   |
| WDC WD5000AZLX-08K2TA0 500GB       | 1        | 1.08%   |
| WDC WD5000AVVS-63M8B0 500GB        | 1        | 1.08%   |
| WDC WD5000AVDS-63U7B1 500GB        | 1        | 1.08%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 1        | 1.08%   |
| WDC WD3200AAKS-75L9A0 320GB        | 1        | 1.08%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 1.08%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1        | 1.08%   |
| WDC WD2500AAKX-75U6AA0 250GB       | 1        | 1.08%   |
| WDC WD2500AAKX-08U6AA0 250GB       | 1        | 1.08%   |
| WDC WD10EARX-00N0YB0 1TB           | 1        | 1.08%   |
| Unknown L200 Hard drive 2TB        | 1        | 1.08%   |
| Toshiba THNSNJ128GCSU 128GB SSD    | 1        | 1.08%   |
| Toshiba MK2555GSX 250GB            | 1        | 1.08%   |
| Toshiba HDWJ110 1TB                | 1        | 1.08%   |
| Toshiba DT01ACA050 500GB           | 1        | 1.08%   |
| Toshiba DT01ABA100V 1TB            | 1        | 1.08%   |
| Seagate ST_M13FQBL QNR 4GB         | 1        | 1.08%   |
| Seagate ST380817AS 80GB            | 1        | 1.08%   |
| Seagate ST3808110AS 80GB           | 1        | 1.08%   |
| Seagate ST380013AS 80GB            | 1        | 1.08%   |
| Seagate ST380011A 80GB             | 1        | 1.08%   |
| Seagate ST3500418AS 500GB          | 1        | 1.08%   |
| Seagate ST3500410SV 500GB          | 1        | 1.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 33     | 41.94%  |
| WDC                 | 15       | 18     | 24.19%  |
| Toshiba             | 7        | 8      | 11.29%  |
| HGST                | 5        | 8      | 8.06%   |
| Maxtor              | 3        | 3      | 4.84%   |
| Hitachi             | 3        | 3      | 4.84%   |
| Unknown             | 1        | 1      | 1.61%   |
| Samsung Electronics | 1        | 1      | 1.61%   |
| Unknown             | 1        | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 5      | 17.65%  |
| Intel               | 3        | 3      | 17.65%  |
| Team                | 2        | 2      | 11.76%  |
| SPCC                | 2        | 3      | 11.76%  |
| Toshiba             | 1        | 1      | 5.88%   |
| SanDisk             | 1        | 1      | 5.88%   |
| LITEON              | 1        | 1      | 5.88%   |
| Kingston            | 1        | 1      | 5.88%   |
| Dahua               | 1        | 1      | 5.88%   |
| China               | 1        | 1      | 5.88%   |
| Unknown             | 1        | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 44       | 76     | 66.67%  |
| SSD     | 14       | 20     | 21.21%  |
| NVMe    | 6        | 10     | 9.09%   |
| Unknown | 2        | 2      | 3.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 48       | 97     | 87.27%  |
| NVMe | 6        | 10     | 10.91%  |
| SAS  | 1        | 1      | 1.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 41       | 65     | 64.06%  |
| 0.51-1.0   | 14       | 18     | 21.88%  |
| 1.01-2.0   | 5        | 8      | 7.81%   |
| 4.01-10.0  | 2        | 3      | 3.13%   |
| 3.01-4.0   | 1        | 1      | 1.56%   |
| 2.01-3.0   | 1        | 1      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 10       | 18.52%  |
| 501-1000       | 10       | 18.52%  |
| 1001-2000      | 9        | 16.67%  |
| 251-500        | 8        | 14.81%  |
| 51-100         | 8        | 14.81%  |
| More than 3000 | 4        | 7.41%   |
| 1-20           | 2        | 3.7%    |
| 21-50          | 1        | 1.85%   |
| 2001-3000      | 1        | 1.85%   |
| Unknown        | 1        | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 21       | 38.18%  |
| 21-50     | 7        | 12.73%  |
| 251-500   | 6        | 10.91%  |
| 101-250   | 6        | 10.91%  |
| 1001-2000 | 6        | 10.91%  |
| 501-1000  | 5        | 9.09%   |
| 51-100    | 3        | 5.45%   |
| Unknown   | 1        | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Toshiba MQ01ABD050V 500GB          | 2        | 2      | 18.18%  |
| WDC WD5000AZLX-08K2TA0 500GB       | 1        | 1      | 9.09%   |
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 1      | 9.09%   |
| Toshiba MK2555GSX 250GB            | 1        | 1      | 9.09%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 9.09%   |
| Seagate ST3500418AS 500GB          | 1        | 1      | 9.09%   |
| Seagate ST3320418AS 320GB          | 1        | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 9.09%   |
| HGST HTS721010A9 1TB               | 1        | 2      | 9.09%   |
| Unknown                            | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 36.36%  |
| Toshiba | 3        | 3      | 27.27%  |
| WDC     | 2        | 2      | 18.18%  |
| HGST    | 1        | 2      | 9.09%   |
| Unknown | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 36.36%  |
| Toshiba | 3        | 3      | 27.27%  |
| WDC     | 2        | 2      | 18.18%  |
| HGST    | 1        | 2      | 9.09%   |
| Unknown | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 12     | 100%    |

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
| Detected | 31       | 57     | 56.36%  |
| Works    | 14       | 39     | 25.45%  |
| Malfunc  | 10       | 12     | 18.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 40       | 66.67%  |
| AMD                       | 9        | 15%     |
| Samsung Electronics       | 2        | 3.33%   |
| Silicon Motion            | 1        | 1.67%   |
| SanDisk                   | 1        | 1.67%   |
| Realtek Semiconductor     | 1        | 1.67%   |
| Micron/Crucial Technology | 1        | 1.67%   |
| Marvell Technology Group  | 1        | 1.67%   |
| LSI Logic / Symbios Logic | 1        | 1.67%   |
| JMicron Technology        | 1        | 1.67%   |
| Broadcom / LSI            | 1        | 1.67%   |
| ASMedia Technology        | 1        | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 8.86%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 8.86%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 6.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 5.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 5.06%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 3.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 3.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.8%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 2.53%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                           | 2        | 2.53%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 2        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.53%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 2.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 2.53%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 1.27%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 1        | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.27%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 1.27%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 1.27%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 1.27%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 1.27%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 1        | 1.27%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.27%   |
| Intel Elkhart Lake SATA AHCI                                                            | 1        | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.27%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.27%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 1.27%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.27%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.27%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.27%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.27%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.27%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.27%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.27%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1        | 1.27%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 1        | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 33       | 53.23%  |
| IDE  | 16       | 25.81%  |
| RAID | 6        | 9.68%   |
| NVMe | 6        | 9.68%   |
| SCSI | 1        | 1.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 40       | 81.63%  |
| AMD    | 9        | 18.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz               | 3        | 6.12%   |
| Intel Pentium 4 CPU 3.00GHz                    | 2        | 4.08%   |
| Intel Pentium 4 CPU 2.80GHz                    | 2        | 4.08%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 2        | 4.08%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 2        | 4.08%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 2        | 4.08%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 4.08%   |
| Intel Xeon CPU W3680 @ 3.33GHz                 | 1        | 2.04%   |
| Intel Xeon CPU E5-1630 v3 @ 3.70GHz            | 1        | 2.04%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz    | 1        | 2.04%   |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 2.04%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 2.04%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 1        | 2.04%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 2.04%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 2.04%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 1        | 2.04%   |
| Intel Core i5-4430S CPU @ 2.70GHz              | 1        | 2.04%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 1        | 2.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 2.04%   |
| Intel Core i3-4170 CPU @ 3.70GHz               | 1        | 2.04%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 1        | 2.04%   |
| Intel Core i3-3240 CPU @ 3.40GHz               | 1        | 2.04%   |
| Intel Core i3-2100 CPU @ 3.10GHz               | 1        | 2.04%   |
| Intel Core i3 CPU 550 @ 3.20GHz                | 1        | 2.04%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 2.04%   |
| Intel Core 2 Quad CPU @ 2.40GHz                | 1        | 2.04%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz           | 1        | 2.04%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz           | 1        | 2.04%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 1        | 2.04%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz           | 1        | 2.04%   |
| Intel Core 2 CPU 6420 @ 2.13GHz                | 1        | 2.04%   |
| Intel Cnre i5-4590S CPU @ 3.00GHz              | 1        | 2.04%   |
| Intel Celeron J6412 @ 2.00GHz                  | 1        | 2.04%   |
| Intel 13th Gen Core i7-13700K                  | 1        | 2.04%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 2.04%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 2.04%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 2.04%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 2.04%   |
| AMD Phenom II X3 B75 Processor                 | 1        | 2.04%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 8        | 16.33%  |
| Intel Core i7           | 7        | 14.29%  |
| Intel Core i3           | 7        | 14.29%  |
| Intel Pentium 4         | 5        | 10.2%   |
| Intel Core 2 Duo        | 4        | 8.16%   |
| AMD Ryzen 5             | 3        | 6.12%   |
| Other                   | 2        | 4.08%   |
| Intel Xeon              | 2        | 4.08%   |
| Intel Core 2 Quad       | 2        | 4.08%   |
| Intel Pentium Dual-Core | 1        | 2.04%   |
| Intel Core 2            | 1        | 2.04%   |
| Intel Celeron           | 1        | 2.04%   |
| AMD Ryzen Threadripper  | 1        | 2.04%   |
| AMD Ryzen 9             | 1        | 2.04%   |
| AMD Ryzen 7             | 1        | 2.04%   |
| AMD Phenom II X3        | 1        | 2.04%   |
| AMD FX                  | 1        | 2.04%   |
| AMD A4                  | 1        | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 19       | 38.78%  |
| 2      | 13       | 26.53%  |
| 1      | 6        | 12.24%  |
| 6      | 5        | 10.2%   |
| 3      | 2        | 4.08%   |
| 32     | 1        | 2.04%   |
| 16     | 1        | 2.04%   |
| 12     | 1        | 2.04%   |
| 8      | 1        | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 55.1%   |
| 1      | 22       | 44.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 48       | 97.96%  |
| 32-bit         | 1        | 2.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 26%     |
| 0x306a9    | 6        | 12%     |
| 0x506e3    | 3        | 6%      |
| 0x206a7    | 3        | 6%      |
| 0x1067a    | 3        | 6%      |
| 0x0800820d | 3        | 6%      |
| 0x306c3    | 2        | 4%      |
| 0x10676    | 2        | 4%      |
| 0xf65      | 1        | 2%      |
| 0xf49      | 1        | 2%      |
| 0xf43      | 1        | 2%      |
| 0xf41      | 1        | 2%      |
| 0x906ea    | 1        | 2%      |
| 0x90661    | 1        | 2%      |
| 0x6f7      | 1        | 2%      |
| 0x6f6      | 1        | 2%      |
| 0x306f2    | 1        | 2%      |
| 0x206c2    | 1        | 2%      |
| 0x20655    | 1        | 2%      |
| 0x0a201016 | 1        | 2%      |
| 0x08301039 | 1        | 2%      |
| 0x06001119 | 1        | 2%      |
| 0x0600084f | 1        | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 8        | 16.33%  |
| Haswell          | 6        | 12.24%  |
| Penryn           | 5        | 10.2%   |
| NetBurst         | 5        | 10.2%   |
| Zen+             | 4        | 8.16%   |
| SandyBridge      | 4        | 8.16%   |
| Skylake          | 3        | 6.12%   |
| Core             | 3        | 6.12%   |
| Westmere         | 2        | 4.08%   |
| Piledriver       | 2        | 4.08%   |
| KabyLake         | 2        | 4.08%   |
| Zen 3            | 1        | 2.04%   |
| Zen 2            | 1        | 2.04%   |
| Tremont          | 1        | 2.04%   |
| K10              | 1        | 2.04%   |
| Alderlake Hybrid | 1        | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 27       | 50.94%  |
| Nvidia | 16       | 30.19%  |
| AMD    | 10       | 18.87%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 9.26%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 5.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 5.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 5.56%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 3.7%    |
| Nvidia GM107GL [Quadro K2200]                                               | 2        | 3.7%    |
| Intel HD Graphics 530                                                       | 2        | 3.7%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 3.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.7%    |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 3.7%    |
| Nvidia GT218 [NVS 300]                                                      | 1        | 1.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.85%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.85%   |
| Nvidia GK107GL [Quadro 410]                                                 | 1        | 1.85%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.85%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.85%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 1.85%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.85%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 1.85%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 1        | 1.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 1.85%   |
| Intel HD Graphics 630                                                       | 1        | 1.85%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                | 1        | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.85%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.85%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 1.85%   |
| Intel 82946GZ/GL Integrated Graphics Controller                             | 1        | 1.85%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                        | 1        | 1.85%   |
| Intel 82915G Integrated Graphics Controller                                 | 1        | 1.85%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 1.85%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 1.85%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 24       | 48%     |
| 1 x Nvidia     | 14       | 28%     |
| 1 x AMD        | 10       | 20%     |
| 2 x Intel      | 1        | 2%      |
| Intel + Nvidia | 1        | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 43       | 87.76%  |
| Proprietary | 5        | 10.2%   |
| Unknown     | 1        | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 59.18%  |
| 3.01-4.0   | 5        | 10.2%   |
| 0.51-1.0   | 5        | 10.2%   |
| 7.01-8.0   | 3        | 6.12%   |
| 1.01-2.0   | 3        | 6.12%   |
| 0.01-0.5   | 3        | 6.12%   |
| 8.01-16.0  | 1        | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 18       | 34.62%  |
| Dell                | 11       | 21.15%  |
| Sony                | 5        | 9.62%   |
| Samsung Electronics | 3        | 5.77%   |
| Lenovo              | 3        | 5.77%   |
| BenQ                | 2        | 3.85%   |
| VIE                 | 1        | 1.92%   |
| Unknown (XXX)       | 1        | 1.92%   |
| Unknown             | 1        | 1.92%   |
| Sceptre Tech        | 1        | 1.92%   |
| S2-Tek              | 1        | 1.92%   |
| NEC Computers       | 1        | 1.92%   |
| Hitachi             | 1        | 1.92%   |
| HannStar            | 1        | 1.92%   |
| Acer                | 1        | 1.92%   |
| Unknown             | 1        | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S22E450 SAM0C7A 1920x1080 477x268mm 21.5-inch     | 2        | 3.51%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                  | 2        | 3.51%   |
| Hewlett-Packard Z22i HWP308B 1920x1080 477x268mm 21.5-inch            | 2        | 3.51%   |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch          | 2        | 3.51%   |
| Dell E1910H DELD023 1366x768 410x230mm 18.5-inch                      | 2        | 3.51%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 1.75%   |
| Unknown LCD Monitor Hitachi Engineering Company Ltd HISENSE 3200x1080 | 1        | 1.75%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 1        | 1.75%   |
| Sony TV SNYEF03 1600x900                                              | 1        | 1.75%   |
| Sony TV SNYDC02 1920x1080 708x398mm 32.0-inch                         | 1        | 1.75%   |
| Sony TV SNYAC03 1360x768                                              | 1        | 1.75%   |
| Sony TV SNY6F02 1360x768                                              | 1        | 1.75%   |
| Sony TV SNY0902 1920x1080                                             | 1        | 1.75%   |
| Sceptre Tech Sceptre Y27 SPT0AB9 2560x1440 597x336mm 27.0-inch        | 1        | 1.75%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1        | 1.75%   |
| S2-Tek TV STK531A 1920x1080 930x530mm 42.1-inch                       | 1        | 1.75%   |
| NEC Computers EA193Mi NEC6956 1280x1024 375x300mm 18.9-inch           | 1        | 1.75%   |
| Lenovo LEN LI1931ewA LEN65A1 1366x768 409x230mm 18.5-inch             | 1        | 1.75%   |
| Lenovo LEN E2054A LEN60DF 1440x900 419x262mm 19.5-inch                | 1        | 1.75%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch               | 1        | 1.75%   |
| Hewlett-Packard Z27s HWP317F 3840x2160 596x335mm 26.9-inch            | 1        | 1.75%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1        | 1.75%   |
| Hewlett-Packard P222va HWP322C 1920x1080 477x268mm 21.5-inch          | 1        | 1.75%   |
| Hewlett-Packard LE2202x HWP2966 1920x1080 476x268mm 21.5-inch         | 1        | 1.75%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 1        | 1.75%   |
| Hewlett-Packard LCD Monitor L1710                                     | 1        | 1.75%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch          | 1        | 1.75%   |
| Hewlett-Packard LA2206 HWP2948 1920x1080 476x268mm 21.5-inch          | 1        | 1.75%   |
| Hewlett-Packard LA2205 HWP2849 1680x1050 473x296mm 22.0-inch          | 1        | 1.75%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch          | 1        | 1.75%   |
| Hewlett-Packard L2311c HWP2994 1920x1080 509x286mm 23.0-inch          | 1        | 1.75%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1        | 1.75%   |
| Hewlett-Packard L1706 HWP265C 1280x1024 337x270mm 17.0-inch           | 1        | 1.75%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch            | 1        | 1.75%   |
| Hewlett-Packard E222 HWP3262 1920x1080 476x268mm 21.5-inch            | 1        | 1.75%   |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x287mm 23.0-inch            | 1        | 1.75%   |
| HannStar HW191D HSD8991 1440x900 408x255mm 18.9-inch                  | 1        | 1.75%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1        | 1.75%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1        | 1.75%   |
| Dell P2314T DEL40A0 1920x1080 510x290mm 23.1-inch                     | 1        | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 33.33%  |
| 1280x1024 (SXGA)   | 8        | 15.69%  |
| 1600x900 (HD+)     | 4        | 7.84%   |
| 3840x2160 (4K)     | 3        | 5.88%   |
| 1680x1050 (WSXGA+) | 3        | 5.88%   |
| 1440x900 (WXGA+)   | 3        | 5.88%   |
| 1366x768 (WXGA)    | 3        | 5.88%   |
| 2560x1440 (QHD)    | 2        | 3.92%   |
| 1920x1200 (WUXGA)  | 2        | 3.92%   |
| 1360x768           | 2        | 3.92%   |
| 1024x768 (XGA)     | 2        | 3.92%   |
| 3200x1080          | 1        | 1.96%   |
| Unknown            | 1        | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 9        | 17.31%  |
| 19      | 6        | 11.54%  |
| 72      | 4        | 7.69%   |
| 27      | 4        | 7.69%   |
| 23      | 4        | 7.69%   |
| 22      | 4        | 7.69%   |
| 18      | 4        | 7.69%   |
| 17      | 4        | 7.69%   |
| 24      | 3        | 5.77%   |
| 20      | 3        | 5.77%   |
| Unknown | 2        | 3.85%   |
| 84      | 1        | 1.92%   |
| 54      | 1        | 1.92%   |
| 46      | 1        | 1.92%   |
| 42      | 1        | 1.92%   |
| 15      | 1        | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 17       | 36.17%  |
| 501-600     | 11       | 23.4%   |
| 301-350     | 5        | 10.64%  |
| 1501-2000   | 5        | 10.64%  |
| 351-400     | 4        | 8.51%   |
| 1001-1500   | 2        | 4.26%   |
| Unknown     | 2        | 4.26%   |
| 901-1000    | 1        | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 30       | 60%     |
| 16/10   | 9        | 18%     |
| 5/4     | 8        | 16%     |
| Unknown | 2        | 4%      |
| 4/3     | 1        | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 24.49%  |
| 151-200        | 12       | 24.49%  |
| 141-150        | 7        | 14.29%  |
| More than 1000 | 6        | 12.24%  |
| 301-350        | 4        | 8.16%   |
| 251-300        | 3        | 6.12%   |
| 501-1000       | 2        | 4.08%   |
| Unknown        | 2        | 4.08%   |
| 101-110        | 1        | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 27       | 58.7%   |
| 101-120 | 11       | 23.91%  |
| 1-50    | 5        | 10.87%  |
| Unknown | 2        | 4.35%   |
| 161-240 | 1        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 68%     |
| 2     | 12       | 24%     |
| 0     | 4        | 8%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 28       | 35.44%  |
| Realtek Semiconductor | 25       | 31.65%  |
| Broadcom Limited      | 5        | 6.33%   |
| MediaTek              | 4        | 5.06%   |
| Broadcom              | 4        | 5.06%   |
| Xiaomi                | 3        | 3.8%    |
| Qualcomm Atheros      | 3        | 3.8%    |
| Samsung Electronics   | 2        | 2.53%   |
| Ralink Technology     | 1        | 1.27%   |
| Qualcomm              | 1        | 1.27%   |
| OPPO Electronics      | 1        | 1.27%   |
| Huawei Technologies   | 1        | 1.27%   |
| Hewlett-Packard       | 1        | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 13       | 14.61%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 9        | 10.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8        | 8.99%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 6        | 6.74%   |
| MediaTek RMX3085                                                       | 4        | 4.49%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 3.37%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 3.37%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express        | 3        | 3.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 2.25%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 2.25%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 2.25%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 2.25%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 2.25%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 1.12%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 1.12%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 1.12%   |
| Qualcomm SAMSUNG_Android                                               | 1        | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1        | 1.12%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 1.12%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 1.12%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 1        | 1.12%   |
| Intel Wireless 8265 / 8275                                             | 1        | 1.12%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 1.12%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 1.12%   |
| Intel Ethernet Controller I225-V                                       | 1        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.12%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 1.12%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 1.12%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 1.12%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 1.12%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 1.12%   |
| Intel 82576 Gigabit Network Connection                                 | 1        | 1.12%   |
| Intel 82567V-4 Gigabit Network Connection                              | 1        | 1.12%   |
| Intel 82566DC Gigabit Network Connection                               | 1        | 1.12%   |
| Huawei Mass Storage                                                    | 1        | 1.12%   |
| HP HP L2311c LAN7500 Ethernet                                          | 1        | 1.12%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1        | 1.12%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 1.12%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1        | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 64%     |
| Intel                 | 5        | 20%     |
| Qualcomm Atheros      | 2        | 8%      |
| Ralink Technology     | 1        | 4%      |
| Broadcom              | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 9        | 36%     |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 6        | 24%     |
| Intel Wi-Fi 6 AX200                                            | 2        | 8%      |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 4%      |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 4%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 4%      |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 4%      |
| Intel Wireless 8265 / 8275                                     | 1        | 4%      |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1        | 4%      |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 4%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 28       | 45.16%  |
| Realtek Semiconductor | 13       | 20.97%  |
| Broadcom Limited      | 5        | 8.06%   |
| MediaTek              | 4        | 6.45%   |
| Xiaomi                | 3        | 4.84%   |
| Broadcom              | 3        | 4.84%   |
| Samsung Electronics   | 2        | 3.23%   |
| Qualcomm Atheros      | 1        | 1.61%   |
| Qualcomm              | 1        | 1.61%   |
| OPPO Electronics      | 1        | 1.61%   |
| Hewlett-Packard       | 1        | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 13       | 20.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8        | 12.7%   |
| MediaTek RMX3085                                                       | 4        | 6.35%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 4.76%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 4.76%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express        | 3        | 4.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 3.17%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 3.17%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 3.17%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 3.17%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 1.59%   |
| Qualcomm SAMSUNG_Android                                               | 1        | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 1.59%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 1        | 1.59%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 1.59%   |
| Intel Ethernet Controller I225-V                                       | 1        | 1.59%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.59%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 1.59%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 1.59%   |
| Intel 82578DM Gigabit Network Connection                               | 1        | 1.59%   |
| Intel 82576 Gigabit Network Connection                                 | 1        | 1.59%   |
| Intel 82567V-4 Gigabit Network Connection                              | 1        | 1.59%   |
| Intel 82566DC Gigabit Network Connection                               | 1        | 1.59%   |
| HP HP L2311c LAN7500 Ethernet                                          | 1        | 1.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1        | 1.59%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 1.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1        | 1.59%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express        | 1        | 1.59%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express        | 1        | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 65.75%  |
| WiFi     | 24       | 32.88%  |
| Modem    | 1        | 1.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 68.89%  |
| WiFi     | 14       | 31.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 37       | 75.51%  |
| 2     | 9        | 18.37%  |
| 4     | 1        | 2.04%   |
| 3     | 1        | 2.04%   |
| 0     | 1        | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 97.96%  |
| Yes  | 1        | 2.04%   |

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
| Intel Bluetooth Device                              | 1        | 14.29%  |
| Intel AX211 Bluetooth                               | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 39       | 50.65%  |
| Nvidia                   | 15       | 19.48%  |
| AMD                      | 12       | 15.58%  |
| Texas Instruments        | 2        | 2.6%    |
| Lenovo                   | 2        | 2.6%    |
| C-Media Electronics      | 2        | 2.6%    |
| Micro Star International | 1        | 1.3%    |
| Medeli Electronics       | 1        | 1.3%    |
| JMTek                    | 1        | 1.3%    |
| Giga-Byte Technology     | 1        | 1.3%    |
| Generalplus Technology   | 1        | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7        | 8.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 5.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 5.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 5.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 5.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 4.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 4.65%   |
| Nvidia High Definition Audio Controller                                    | 3        | 3.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 3.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 3.49%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 2.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 2.33%   |
| Lenovo T2224zD                                                             | 2        | 2.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 2.33%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 2        | 2.33%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.33%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 2.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.16%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 1.16%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 1.16%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 1.16%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 1.16%   |
| Micro Star International USB Audio                                         | 1        | 1.16%   |
| Medeli Electronics USB Audio Device                                        | 1        | 1.16%   |
| JMTek USB PnP Audio Device                                                 | 1        | 1.16%   |
| Intel Elkhart Lake High Density Audio bus interface                        | 1        | 1.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.16%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.16%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 1.16%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 1.16%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 1        | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.16%   |
| Giga-Byte Technology USB Audio                                             | 1        | 1.16%   |
| Generalplus Technology USB Audio Device                                    | 1        | 1.16%   |
| C-Media Electronics USB PnP Sound Device                                   | 1        | 1.16%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 7        | 22.58%  |
| Kingston            | 5        | 16.13%  |
| Crucial             | 5        | 16.13%  |
| Samsung Electronics | 4        | 12.9%   |
| Micron Technology   | 3        | 9.68%   |
| G.Skill             | 2        | 6.45%   |
| Unknown             | 1        | 3.23%   |
| TwinMOS             | 1        | 3.23%   |
| Team                | 1        | 3.23%   |
| Ramaxel Technology  | 1        | 3.23%   |
| Corsair             | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s     | 2        | 6.06%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 2        | 6.06%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                 | 1        | 3.03%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s        | 1        | 3.03%   |
| TwinMOS RAM 9DECBMZB-TATP 2048MB DIMM DDR3 1333MT/s     | 1        | 3.03%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s      | 1        | 3.03%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 3.03%   |
| SK hynix RAM HMT451U6BFR8A-PB 4096MB DIMM DDR3 1600MT/s | 1        | 3.03%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s    | 1        | 3.03%   |
| SK hynix RAM HMT125U7BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 3.03%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 3.03%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s    | 1        | 3.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s  | 1        | 3.03%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s    | 1        | 3.03%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s     | 1        | 3.03%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s     | 1        | 3.03%   |
| Ramaxel RAM RMUA5110MD78HAF-2666 8GB DIMM DDR4 2667MT/s | 1        | 3.03%   |
| Micron RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s    | 1        | 3.03%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s    | 1        | 3.03%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s    | 1        | 3.03%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s     | 1        | 3.03%   |
| Kingston RAM K 512MB DIMM DDR 667MT/s                   | 1        | 3.03%   |
| Kingston RAM HP497157-D88-ELFW 2GB DIMM DDR3 1333MT/s   | 1        | 3.03%   |
| Kingston RAM 99P5663-013.A00G 8GB SODIMM DDR4 2667MT/s  | 1        | 3.03%   |
| Kingston RAM 9905734-102.A00G 32GB DIMM DDR4 3200MT/s   | 1        | 3.03%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s   | 1        | 3.03%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s   | 1        | 3.03%   |
| Crucial RAM CT12864Z40B.K16T 1GB DIMM DDR 400MT/s       | 1        | 3.03%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s   | 1        | 3.03%   |
| Crucial RAM CB16GU2400.C16J 16384MB DIMM DDR4 2400MT/s  | 1        | 3.03%   |
| Corsair RAM CMK32GX5M2B5600C36 16GB DIMM DDR5 5800MT/s  | 1        | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 11       | 44%     |
| DDR4  | 9        | 36%     |
| SDRAM | 3        | 12%     |
| DDR5  | 1        | 4%      |
| DDR   | 1        | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 90.91%  |
| SODIMM | 2        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 34.62%  |
| 4096  | 6        | 23.08%  |
| 16384 | 4        | 15.38%  |
| 2048  | 4        | 15.38%  |
| 32768 | 2        | 7.69%   |
| 1024  | 1        | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 8        | 29.63%  |
| 2667  | 4        | 14.81%  |
| 1333  | 3        | 11.11%  |
| 3600  | 2        | 7.41%   |
| 5800  | 1        | 3.7%    |
| 3800  | 1        | 3.7%    |
| 3200  | 1        | 3.7%    |
| 2465  | 1        | 3.7%    |
| 2400  | 1        | 3.7%    |
| 2000  | 1        | 3.7%    |
| 1867  | 1        | 3.7%    |
| 667   | 1        | 3.7%    |
| 400   | 1        | 3.7%    |
| 333   | 1        | 3.7%    |

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
| MacroSilicon MiraBox Capture      | 1        | 16.67%  |
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
| 0     | 40       | 81.63%  |
| 1     | 8        | 16.33%  |
| 2     | 1        | 2.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 6        | 60%     |
| Net/ethernet     | 2        | 20%     |
| Unassigned class | 1        | 10%     |
| Net/wireless     | 1        | 10%     |

