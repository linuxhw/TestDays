Oracle Linux - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad P16s Gen 1 21BT... | [97c2387841](https://linux-hardware.org/?probe=97c2387841) | Apr 12, 2024 |
| Lenovo    | ThinkPad P16s Gen 1 21BT... | [e47633811b](https://linux-hardware.org/?probe=e47633811b) | Apr 12, 2024 |
| ASUSTek   | X541SA                      | [23ea4a0287](https://linux-hardware.org/?probe=23ea4a0287) | Apr 09, 2024 |
| ASUSTek   | X541SA                      | [0f5bd53c6f](https://linux-hardware.org/?probe=0f5bd53c6f) | Apr 08, 2024 |
| ASUSTek   | X541SA                      | [b3f083db5c](https://linux-hardware.org/?probe=b3f083db5c) | Apr 06, 2024 |
| HP        | EliteBook 640 14 inch G1... | [90a116696c](https://linux-hardware.org/?probe=90a116696c) | Mar 24, 2024 |
| Lenovo    | ThinkBook 15-IIL 20SM       | [692db635b4](https://linux-hardware.org/?probe=692db635b4) | Mar 23, 2024 |
| HP        | ZBook Fury 15.6 inch G8 ... | [b27420dd64](https://linux-hardware.org/?probe=b27420dd64) | Feb 21, 2024 |
| Dell      | Latitude 7420               | [30e1dc7b9f](https://linux-hardware.org/?probe=30e1dc7b9f) | Feb 13, 2024 |
| Dell      | Latitude 7430               | [153f1a144c](https://linux-hardware.org/?probe=153f1a144c) | Jan 19, 2024 |
| Dell      | Latitude 7430               | [a05210eeb4](https://linux-hardware.org/?probe=a05210eeb4) | Jan 19, 2024 |
| Lenovo    | ThinkPad T490 20N3S3XR00    | [63ec999c70](https://linux-hardware.org/?probe=63ec999c70) | Jan 16, 2024 |
| Lenovo    | ThinkPad W520 42844DG       | [52cd813233](https://linux-hardware.org/?probe=52cd813233) | Dec 20, 2023 |
| HP        | ZBook Fury 15.6 inch G8 ... | [58ad170a68](https://linux-hardware.org/?probe=58ad170a68) | Dec 10, 2023 |
| Dell      | XPS 15 9570                 | [35a10a1ae2](https://linux-hardware.org/?probe=35a10a1ae2) | Dec 10, 2023 |
| Toshiba   | TECRA R950                  | [8ab7278f60](https://linux-hardware.org/?probe=8ab7278f60) | Dec 01, 2023 |
| Toshiba   | TECRA R950                  | [9634f68cab](https://linux-hardware.org/?probe=9634f68cab) | Dec 01, 2023 |
| Dell      | XPS 15 9570                 | [7728d0ab4b](https://linux-hardware.org/?probe=7728d0ab4b) | Nov 22, 2023 |
| HP        | EliteBook 840 G4            | [7d2d46e750](https://linux-hardware.org/?probe=7d2d46e750) | Nov 17, 2023 |
| Lenovo    | Legion Y540-15IRH 81SX      | [1da691596b](https://linux-hardware.org/?probe=1da691596b) | Nov 06, 2023 |
| Lenovo    | Legion Y540-15IRH 81SX      | [d385d4714c](https://linux-hardware.org/?probe=d385d4714c) | Nov 06, 2023 |
| Dell      | Precision 5550              | [033e294199](https://linux-hardware.org/?probe=033e294199) | Nov 03, 2023 |
| HP        | 240 G8 Notebook PC          | [0a98dcd952](https://linux-hardware.org/?probe=0a98dcd952) | Oct 11, 2023 |
| HP        | 240 G8 Notebook PC          | [6fec1bd640](https://linux-hardware.org/?probe=6fec1bd640) | Sep 11, 2023 |
| Dell      | Latitude 7440               | [47f28d7b00](https://linux-hardware.org/?probe=47f28d7b00) | Sep 04, 2023 |
| Dell      | Latitude 7440               | [27b2ae9d5b](https://linux-hardware.org/?probe=27b2ae9d5b) | Sep 04, 2023 |
| HP        | ZBook Fury 16 G9 Mobile ... | [4b7e25150a](https://linux-hardware.org/?probe=4b7e25150a) | Aug 15, 2023 |
| MSI       | P65 Creator 8RE             | [853567f156](https://linux-hardware.org/?probe=853567f156) | Aug 06, 2023 |
| MSI       | P65 Creator 8RE             | [f26344a920](https://linux-hardware.org/?probe=f26344a920) | Aug 05, 2023 |
| Dell      | Latitude 7430               | [299e6897d2](https://linux-hardware.org/?probe=299e6897d2) | Jun 05, 2023 |
| Lenovo    | ThinkPad T490 20N3S3XR00    | [0f80e19e5b](https://linux-hardware.org/?probe=0f80e19e5b) | May 23, 2023 |
| Lenovo    | ThinkPad W541 20EGS1PL00    | [751cc5dbc7](https://linux-hardware.org/?probe=751cc5dbc7) | May 22, 2023 |
| ASUSTek   | ZenBook UX425EA_UX425EA     | [9be6e0f395](https://linux-hardware.org/?probe=9be6e0f395) | Apr 18, 2023 |
| HP        | Laptop 17-cp0xxx            | [e87b8175b1](https://linux-hardware.org/?probe=e87b8175b1) | Jan 27, 2023 |
| HP        | Laptop 17-cp0xxx            | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| Google    | Lick                        | [d792b79719](https://linux-hardware.org/?probe=d792b79719) | Jan 12, 2023 |
| Panasonic | CF-53AAG54FM                | [cf7f652846](https://linux-hardware.org/?probe=cf7f652846) | Dec 21, 2022 |
| Lenovo    | ThinkPad T470 20HES0E71M    | [85fc801717](https://linux-hardware.org/?probe=85fc801717) | Dec 05, 2022 |
| Lenovo    | ThinkPad P70 20ESS04S00     | [01b85c4c2a](https://linux-hardware.org/?probe=01b85c4c2a) | Nov 10, 2022 |
| Lenovo    | ThinkPad T470 20HES21434    | [39ff1846e3](https://linux-hardware.org/?probe=39ff1846e3) | Oct 23, 2022 |
| Dynabook  | PORTEGE X40-G               | [fc68a9cdbf](https://linux-hardware.org/?probe=fc68a9cdbf) | Oct 03, 2022 |
| HP        | EliteBook 840 G5            | [2709daf415](https://linux-hardware.org/?probe=2709daf415) | Sep 13, 2022 |
| Lenovo    | Legion 5 15IMH05 82AU       | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Dell      | Inspiron 5502               | [28dcf01e88](https://linux-hardware.org/?probe=28dcf01e88) | Aug 03, 2022 |
| Lenovo    | Legion 5 15IMH05 82AU       | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| Lenovo    | ThinkPad P70 20ESS04S00     | [fc29967bed](https://linux-hardware.org/?probe=fc29967bed) | Jun 17, 2022 |
| HP        | Compaq 6730b                | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| Lenovo    | ThinkPad T410 2518A37       | [04e81b8b3f](https://linux-hardware.org/?probe=04e81b8b3f) | Jun 04, 2022 |
| Lenovo    | ThinkPad T430s 2355C33      | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Lenovo    | ThinkPad T430s 2355C33      | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Dell      | Precision M4600             | [0ac2adfe5a](https://linux-hardware.org/?probe=0ac2adfe5a) | Apr 21, 2022 |
| Dell      | Precision M4800             | [fb13b19803](https://linux-hardware.org/?probe=fb13b19803) | Apr 21, 2022 |
| Lenovo    | ThinkPad P50s 20FL000MUS    | [99fbb4446c](https://linux-hardware.org/?probe=99fbb4446c) | Apr 16, 2022 |
| Lenovo    | ThinkPad X1 Extreme 2nd ... | [b708e920f3](https://linux-hardware.org/?probe=b708e920f3) | Mar 21, 2022 |
| Lenovo    | ThinkPad T450 20BUS14900    | [bd60aae97a](https://linux-hardware.org/?probe=bd60aae97a) | Mar 11, 2022 |
| Lenovo    | ThinkPad T480 20L5A07TAU    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Lenovo    | ThinkPad X280 20KES4H34G    | [2b8a4f4664](https://linux-hardware.org/?probe=2b8a4f4664) | Mar 10, 2022 |
| Dell      | Latitude 7420               | [af5f1055fe](https://linux-hardware.org/?probe=af5f1055fe) | Mar 10, 2022 |
| HP        | ProBook 445 G6              | [88d8b32328](https://linux-hardware.org/?probe=88d8b32328) | Jan 26, 2022 |
| Lenovo    | ThinkPad T450 20BUS14900    | [44c8e11f02](https://linux-hardware.org/?probe=44c8e11f02) | Dec 22, 2021 |
| Lenovo    | IdeaPad 300-15ISK 80RS      | [1c9ca21f4e](https://linux-hardware.org/?probe=1c9ca21f4e) | Dec 10, 2021 |
| Dell      | Latitude 7410               | [3efa87284e](https://linux-hardware.org/?probe=3efa87284e) | Nov 18, 2021 |
| Dell      | Latitude E6420              | [b809392380](https://linux-hardware.org/?probe=b809392380) | Oct 08, 2021 |
| Dell      | Latitude 7410               | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell      | Latitude 7410               | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| Dell      | Inspiron 3542               | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | [0225c17d79](https://linux-hardware.org/?probe=0225c17d79) | Jul 02, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| ASUSTek   | UX305FA                     | [0bf50fba2d](https://linux-hardware.org/?probe=0bf50fba2d) | Mar 15, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [ff355a9bb1](https://linux-hardware.org/?probe=ff355a9bb1) | Mar 11, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [9f67379954](https://linux-hardware.org/?probe=9f67379954) | Mar 04, 2021 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | [db0f24aee5](https://linux-hardware.org/?probe=db0f24aee5) | Mar 01, 2021 |
| Dell      | Latitude 7410               | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Dell      | Latitude 7410               | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Lenovo    | ThinkPad T490 20N3S77600    | [26e61c39f2](https://linux-hardware.org/?probe=26e61c39f2) | Feb 24, 2021 |
| Dell      | Latitude 7410               | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [8af2c8d83c](https://linux-hardware.org/?probe=8af2c8d83c) | Feb 05, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [7ea3c87bfe](https://linux-hardware.org/?probe=7ea3c87bfe) | Jan 06, 2021 |
| Standard  | BW Series                   | [1f6cf82ba8](https://linux-hardware.org/?probe=1f6cf82ba8) | Jun 13, 2020 |
| HP        | Notebook                    | [e3c242a846](https://linux-hardware.org/?probe=e3c242a846) | May 24, 2020 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | [d8b2c132c1](https://linux-hardware.org/?probe=d8b2c132c1) | Apr 09, 2020 |
| HP        | ZBook 15                    | [4723616d8c](https://linux-hardware.org/?probe=4723616d8c) | Apr 09, 2020 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | [1acbabb197](https://linux-hardware.org/?probe=1acbabb197) | Apr 06, 2020 |
| Lenovo    | ThinkPad T480 20L6S56Y2X    | [5343997520](https://linux-hardware.org/?probe=5343997520) | Feb 23, 2020 |
| ASUSTek   | X510UR                      | [914b9fbe64](https://linux-hardware.org/?probe=914b9fbe64) | Feb 04, 2020 |
| ASUSTek   | X510UR                      | [014d5ef0c8](https://linux-hardware.org/?probe=014d5ef0c8) | Jan 28, 2020 |
| ASUSTek   | X510UR                      | [9d05b420d4](https://linux-hardware.org/?probe=9d05b420d4) | Jan 28, 2020 |
| Lenovo    | ThinkPad L540 20AVCTO1WW    | [8c1dba9d6e](https://linux-hardware.org/?probe=8c1dba9d6e) | Sep 10, 2019 |
| Lenovo    | ThinkPad T480 20L6S56Y2X    | [f012a475eb](https://linux-hardware.org/?probe=f012a475eb) | Apr 11, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Oracle Linux 8.5 | 11        | 16.42%  |
| Oracle Linux 9.3 | 6         | 8.96%   |
| Oracle Linux 9.2 | 6         | 8.96%   |
| Oracle Linux 8.3 | 6         | 8.96%   |
| Oracle Linux 8.9 | 5         | 7.46%   |
| Oracle Linux 8.8 | 5         | 7.46%   |
| Oracle Linux 8.4 | 5         | 7.46%   |
| Oracle Linux 7.9 | 4         | 5.97%   |
| Oracle Linux 9.1 | 3         | 4.48%   |
| Oracle Linux 9.0 | 3         | 4.48%   |
| Oracle Linux 8.1 | 3         | 4.48%   |
| Oracle Linux 8.7 | 2         | 2.99%   |
| Oracle Linux 8.6 | 2         | 2.99%   |
| Oracle Linux 7.8 | 2         | 2.99%   |
| Oracle Linux 7.7 | 2         | 2.99%   |
| Oracle Linux 8.2 | 1         | 1.49%   |
| Oracle Linux 7.6 | 1         | 1.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Oracle Linux | 58        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 5.4.17-2036.103.3.1.el8uek.x86_64 | 3         | 4.05%   |
| 5.15.0-200.131.27.el9uek.x86_64   | 3         | 4.05%   |
| 4.18.0-348.12.2.el8_5.x86_64      | 3         | 4.05%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64 | 2         | 2.7%    |
| 5.4.17-2102.202.5.el8uek.x86_64   | 2         | 2.7%    |
| 5.15.0-200.131.27.el8uek.x86_64   | 2         | 2.7%    |
| 5.15.0-200.131.27.1.el8uek.x86_64 | 2         | 2.7%    |
| 5.15.0-2.52.3.el9uek.x86_64       | 2         | 2.7%    |
| 5.15.0-106.131.4.el9uek.x86_64    | 2         | 2.7%    |
| 5.15.0-100.96.32.el8uek.x86_64    | 2         | 2.7%    |
| 4.18.0-147.3.1.el8_1.x86_64       | 2         | 2.7%    |
| 5.4.17-2136.326.6.el8uek.x86_64   | 1         | 1.35%   |
| 5.4.17-2136.318.7.2.el8uek.x86_64 | 1         | 1.35%   |
| 5.4.17-2136.312.3.4.el7uek.x86_64 | 1         | 1.35%   |
| 5.4.17-2136.310.7.el8uek.x86_64   | 1         | 1.35%   |
| 5.4.17-2136.309.4.el8uek.x86_64   | 1         | 1.35%   |
| 5.4.17-2136.308.9.el7uek.x86_64   | 1         | 1.35%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64 | 1         | 1.35%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64 | 1         | 1.35%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64 | 1         | 1.35%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64 | 1         | 1.35%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64 | 1         | 1.35%   |
| 5.4.17-2136.300.7.el8uek.x86_64   | 1         | 1.35%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64 | 1         | 1.35%   |
| 5.4.17-2102.204.4.4.el8uek.x86_64 | 1         | 1.35%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64 | 1         | 1.35%   |
| 5.4.17-2102.201.3.el8uek.x86_64   | 1         | 1.35%   |
| 5.4.17-2102.200.13.el8uek.x86_64  | 1         | 1.35%   |
| 5.4.17-2036.104.4.el8uek.x86_64   | 1         | 1.35%   |
| 5.4.17-2011.0.7.el8uek.x86_64     | 1         | 1.35%   |
| 5.15.2-1.el8.elrepo.x86_64        | 1         | 1.35%   |
| 5.15.0-5.76.5.1.el9uek.x86_64     | 1         | 1.35%   |
| 5.15.0-204.147.6.3.el9uek.x86_64  | 1         | 1.35%   |
| 5.15.0-203.146.5.1.el9uek.x86_64  | 1         | 1.35%   |
| 5.15.0-104.119.4.2.el9uek.x86_64  | 1         | 1.35%   |
| 5.15.0-101.103.2.1.el9uek.x86_64  | 1         | 1.35%   |
| 5.15.0-101.103.2.1.el8uek.x86_64  | 1         | 1.35%   |
| 5.15.0-100.76.15.el9uek.x86_64    | 1         | 1.35%   |
| 5.15.0-0.30.20.1.el9uek.x86_64    | 1         | 1.35%   |
| 5.14.1-1.el8.elrepo.x86_64        | 1         | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 18        | 30%     |
| 5.4.17  | 17        | 28.33%  |
| 4.18.0  | 11        | 18.33%  |
| 4.14.35 | 5         | 8.33%   |
| 5.14.0  | 4         | 6.67%   |
| 5.15.2  | 1         | 1.67%   |
| 5.14.1  | 1         | 1.67%   |
| 5.11.1  | 1         | 1.67%   |
| 4.1.12  | 1         | 1.67%   |
| 3.10.0  | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 19        | 31.67%  |
| 5.4     | 17        | 28.33%  |
| 4.18    | 11        | 18.33%  |
| 5.14    | 5         | 8.33%   |
| 4.14    | 5         | 8.33%   |
| 5.11    | 1         | 1.67%   |
| 4.1     | 1         | 1.67%   |
| 3.10    | 1         | 1.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 58        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 47        | 75.81%  |
| GNOME Classic | 4         | 6.45%   |
| Unknown       | 3         | 4.84%   |
| XFCE          | 2         | 3.23%   |
| MATE          | 2         | 3.23%   |
| KDE5          | 2         | 3.23%   |
| KDE4          | 2         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 36        | 59.02%  |
| X11     | 23        | 37.7%   |
| Unknown | 2         | 3.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 34        | 56.67%  |
| Unknown | 25        | 41.67%  |
| SDDM    | 1         | 1.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 38        | 64.41%  |
| en_GB   | 6         | 10.17%  |
| en_AU   | 3         | 5.08%   |
| de_DE   | 3         | 5.08%   |
| pl_PL   | 2         | 3.39%   |
| Unknown | 2         | 3.39%   |
| zh_HK   | 1         | 1.69%   |
| pt_BR   | 1         | 1.69%   |
| it_IT   | 1         | 1.69%   |
| en_IN   | 1         | 1.69%   |
| en_DE   | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 40        | 67.8%   |
| BIOS | 19        | 32.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 53        | 88.33%  |
| Ext4    | 5         | 8.33%   |
| Unknown | 2         | 3.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 28        | 46.67%  |
| Unknown | 25        | 41.67%  |
| MBR     | 7         | 11.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 93.22%  |
| Yes       | 4         | 6.78%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 88.14%  |
| Yes       | 7         | 11.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 23        | 39.66%  |
| Dell             | 13        | 22.41%  |
| Hewlett-Packard  | 11        | 18.97%  |
| ASUSTek Computer | 5         | 8.62%   |
| Toshiba          | 1         | 1.72%   |
| Standard         | 1         | 1.72%   |
| Panasonic        | 1         | 1.72%   |
| MSI              | 1         | 1.72%   |
| Google           | 1         | 1.72%   |
| Dynabook         | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                             | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900                  | 2         | 3.45%   |
| Dell Latitude 7430                               | 2         | 3.45%   |
| Dell Latitude 7420                               | 2         | 3.45%   |
| ASUS X510UR                                      | 2         | 3.45%   |
| Toshiba TECRA R950                               | 1         | 1.72%   |
| Standard BW Series                               | 1         | 1.72%   |
| Panasonic CF-53AAG54FM                           | 1         | 1.72%   |
| MSI P65 Creator 8RE                              | 1         | 1.72%   |
| Lenovo ThinkPad X280 20KES4H34G                  | 1         | 1.72%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800        | 1         | 1.72%   |
| Lenovo ThinkPad W541 20EGS1PL00                  | 1         | 1.72%   |
| Lenovo ThinkPad W520 42844DG                     | 1         | 1.72%   |
| Lenovo ThinkPad T490 20N3S77600                  | 1         | 1.72%   |
| Lenovo ThinkPad T490 20N3S3XR00                  | 1         | 1.72%   |
| Lenovo ThinkPad T480 20L6S56Y2X                  | 1         | 1.72%   |
| Lenovo ThinkPad T480 20L5A07TAU                  | 1         | 1.72%   |
| Lenovo ThinkPad T470 20HES21434                  | 1         | 1.72%   |
| Lenovo ThinkPad T470 20HES0E71M                  | 1         | 1.72%   |
| Lenovo ThinkPad T430s 2355C33                    | 1         | 1.72%   |
| Lenovo ThinkPad P70 20ESS04S00                   | 1         | 1.72%   |
| Lenovo ThinkPad P50s 20FL000MUS                  | 1         | 1.72%   |
| Lenovo ThinkPad P16s Gen 1 21BTS0FR00            | 1         | 1.72%   |
| Lenovo ThinkPad L540 20AVCTO1WW                  | 1         | 1.72%   |
| Lenovo ThinkPad L490 20Q5CTO1WW                  | 1         | 1.72%   |
| Lenovo ThinkBook 15-IIL 20SM                     | 1         | 1.72%   |
| Lenovo Legion Y540-15IRH 81SX                    | 1         | 1.72%   |
| Lenovo Legion 5 15IMH05 82AU                     | 1         | 1.72%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS              | 1         | 1.72%   |
| Lenovo IdeaPad 300-15ISK 80RS                    | 1         | 1.72%   |
| HP ZBook Fury 16 G9 Mobile Workstation PC        | 1         | 1.72%   |
| HP ZBook Fury 15.6 inch G8 Mobile Workstation PC | 1         | 1.72%   |
| HP ZBook 15                                      | 1         | 1.72%   |
| HP ProBook 445 G6                                | 1         | 1.72%   |
| HP Notebook                                      | 1         | 1.72%   |
| HP Laptop 17-cp0xxx                              | 1         | 1.72%   |
| HP EliteBook 840 G5                              | 1         | 1.72%   |
| HP EliteBook 840 G4                              | 1         | 1.72%   |
| HP EliteBook 640 14 inch G10 Notebook PC         | 1         | 1.72%   |
| HP Compaq 6730b                                  | 1         | 1.72%   |
| HP 240 G8 Notebook PC                            | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 18        | 31.03%  |
| Dell Latitude          | 7         | 12.07%  |
| HP ZBook               | 3         | 5.17%   |
| HP EliteBook           | 3         | 5.17%   |
| Dell Precision         | 3         | 5.17%   |
| Lenovo Legion          | 2         | 3.45%   |
| Lenovo IdeaPad         | 2         | 3.45%   |
| Dell Inspiron          | 2         | 3.45%   |
| ASUS X510UR            | 2         | 3.45%   |
| Toshiba TECRA          | 1         | 1.72%   |
| Standard BW            | 1         | 1.72%   |
| Panasonic CF-53AAG54FM | 1         | 1.72%   |
| MSI P65                | 1         | 1.72%   |
| Lenovo ThinkBook       | 1         | 1.72%   |
| HP ProBook             | 1         | 1.72%   |
| HP Notebook            | 1         | 1.72%   |
| HP Laptop              | 1         | 1.72%   |
| HP Compaq              | 1         | 1.72%   |
| HP 240                 | 1         | 1.72%   |
| Google Lick            | 1         | 1.72%   |
| Dynabook PORTEGE       | 1         | 1.72%   |
| Dell XPS               | 1         | 1.72%   |
| ASUS ZenBook           | 1         | 1.72%   |
| ASUS X541SA            | 1         | 1.72%   |
| ASUS UX305FA           | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 13.79%  |
| 2019 | 8         | 13.79%  |
| 2022 | 5         | 8.62%   |
| 2018 | 5         | 8.62%   |
| 2017 | 5         | 8.62%   |
| 2016 | 4         | 6.9%    |
| 2014 | 4         | 6.9%    |
| 2011 | 4         | 6.9%    |
| 2021 | 3         | 5.17%   |
| 2015 | 3         | 5.17%   |
| 2013 | 3         | 5.17%   |
| 2012 | 3         | 5.17%   |
| 2023 | 2         | 3.45%   |
| 2008 | 1         | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 58        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 48        | 81.36%  |
| Enabled  | 11        | 18.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 98.28%  |
| Yes  | 1         | 1.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 19        | 32.2%   |
| 32.01-64.0  | 17        | 28.81%  |
| 4.01-8.0    | 8         | 13.56%  |
| 3.01-4.0    | 6         | 10.17%  |
| 16.01-24.0  | 5         | 8.47%   |
| 64.01-256.0 | 3         | 5.08%   |
| 24.01-32.0  | 1         | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 21        | 30.88%  |
| 2.01-3.0   | 16        | 23.53%  |
| 3.01-4.0   | 13        | 19.12%  |
| 8.01-16.0  | 11        | 16.18%  |
| 1.01-2.0   | 3         | 4.41%   |
| 32.01-64.0 | 2         | 2.94%   |
| 24.01-32.0 | 1         | 1.47%   |
| 0.51-1.0   | 1         | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 83.33%  |
| 2      | 8         | 13.33%  |
| 4      | 1         | 1.67%   |
| 3      | 1         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 81.03%  |
| Yes       | 11        | 18.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 84.48%  |
| No        | 9         | 15.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 98.28%  |
| No        | 1         | 1.72%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 71.67%  |
| No        | 17        | 28.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 20        | 33.9%   |
| UK          | 6         | 10.17%  |
| Germany     | 5         | 8.47%   |
| Poland      | 3         | 5.08%   |
| Netherlands | 3         | 5.08%   |
| Brazil      | 3         | 5.08%   |
| Australia   | 3         | 5.08%   |
| Italy       | 2         | 3.39%   |
| Yemen       | 1         | 1.69%   |
| Turkey      | 1         | 1.69%   |
| Sweden      | 1         | 1.69%   |
| Spain       | 1         | 1.69%   |
| Romania     | 1         | 1.69%   |
| Peru        | 1         | 1.69%   |
| Pakistan    | 1         | 1.69%   |
| Latvia      | 1         | 1.69%   |
| India       | 1         | 1.69%   |
| Hungary     | 1         | 1.69%   |
| Hong Kong   | 1         | 1.69%   |
| Finland     | 1         | 1.69%   |
| Bulgaria    | 1         | 1.69%   |
| Argentina   | 1         | 1.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| San Diego          | 3         | 4.62%   |
| Siegen             | 2         | 3.08%   |
| Seattle            | 2         | 3.08%   |
| London             | 2         | 3.08%   |
| Amsterdam          | 2         | 3.08%   |
| West Linn          | 1         | 1.54%   |
| Warsaw             | 1         | 1.54%   |
| Utrecht            | 1         | 1.54%   |
| Sydney             | 1         | 1.54%   |
| Stockholm          | 1         | 1.54%   |
| Sofia              | 1         | 1.54%   |
| Shrewsbury         | 1         | 1.54%   |
| Sao Paulo          | 1         | 1.54%   |
| Sao Caetano do Sul | 1         | 1.54%   |
| Sanaa              | 1         | 1.54%   |
| San Jose           | 1         | 1.54%   |
| Rocklin            | 1         | 1.54%   |
| Riga               | 1         | 1.54%   |
| Richfield          | 1         | 1.54%   |
| Redwood City       | 1         | 1.54%   |
| Port Saint Lucie   | 1         | 1.54%   |
| Pleven             | 1         | 1.54%   |
| Ngau Wu Tok        | 1         | 1.54%   |
| Nagercoil          | 1         | 1.54%   |
| Milano             | 1         | 1.54%   |
| Melbourne          | 1         | 1.54%   |
| Maple Valley       | 1         | 1.54%   |
| Madrid             | 1         | 1.54%   |
| Lynnwood           | 1         | 1.54%   |
| Ludwigsburg        | 1         | 1.54%   |
| Lima               | 1         | 1.54%   |
| Las Vegas          | 1         | 1.54%   |
| Katowice           | 1         | 1.54%   |
| Karachi            | 1         | 1.54%   |
| Helsinki           | 1         | 1.54%   |
| Harringay          | 1         | 1.54%   |
| Greven             | 1         | 1.54%   |
| Galion             | 1         | 1.54%   |
| Fremont            | 1         | 1.54%   |
| Evansville         | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 22        | 30     | 32.35%  |
| SanDisk                     | 8         | 9      | 11.76%  |
| Unknown                     | 5         | 8      | 7.35%   |
| WDC                         | 4         | 4      | 5.88%   |
| Seagate                     | 3         | 3      | 4.41%   |
| Micron Technology           | 3         | 6      | 4.41%   |
| HGST                        | 3         | 6      | 4.41%   |
| Toshiba                     | 2         | 2      | 2.94%   |
| SK hynix                    | 2         | 2      | 2.94%   |
| Phison Electronics          | 2         | 3      | 2.94%   |
| Micron/Crucial Technology   | 2         | 3      | 2.94%   |
| KIOXIA                      | 2         | 2      | 2.94%   |
| Union Memory (Shenzhen)     | 1         | 2      | 1.47%   |
| Lite-On                     | 1         | 1      | 1.47%   |
| Lenovo                      | 1         | 1      | 1.47%   |
| Kingston Technology Company | 1         | 1      | 1.47%   |
| Kingston                    | 1         | 7      | 1.47%   |
| KingFast                    | 1         | 1      | 1.47%   |
| JMicron Technology          | 1         | 1      | 1.47%   |
| Intel                       | 1         | 1      | 1.47%   |
| Fujitsu                     | 1         | 1      | 1.47%   |
| Crucial                     | 1         | 2      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 128GB                       | 2         | 2.86%   |
| SanDisk SSD PLUS 1000GB                           | 2         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 2.86%   |
| Samsung MZVLB512HAJQ-000L7 512GB                  | 2         | 2.86%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD              | 2         | 2.86%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                  | 1         | 1.43%   |
| WDC WDS200T2G0A-00JH30 2TB SSD                    | 1         | 1.43%   |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 1.43%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 1         | 1.43%   |
| Unknown MMC64G  64GB                              | 1         | 1.43%   |
| Unknown MMC Card  256GB                           | 1         | 1.43%   |
| Unknown MMC Card  1TB                             | 1         | 1.43%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB      | 1         | 1.43%   |
| Toshiba THNSNJ512GCSU 512GB SSD                   | 1         | 1.43%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 1.43%   |
| SK hynix BC901 NVMe 512GB                         | 1         | 1.43%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 1         | 1.43%   |
| Seagate ST9750420AS 752GB                         | 1         | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1.43%   |
| Seagate BUP Slim BK 2TB                           | 1         | 1.43%   |
| Sandisk WD PC SN740 SDDPNQD-256G-1006 256GB       | 1         | 1.43%   |
| SanDisk SDSSDH3512G 512GB                         | 1         | 1.43%   |
| SanDisk SD7SN3Q256G1002 256GB SSD                 | 1         | 1.43%   |
| SanDisk SD6SB1M-256G-1006 256GB SSD               | 1         | 1.43%   |
| Sandisk PC SN740 NVMe WD 512GB                    | 1         | 1.43%   |
| SanDisk NVMe SSD Drive 512GB                      | 1         | 1.43%   |
| Samsung SSD SM841N 2.5 7mm 512GB                  | 1         | 1.43%   |
| Samsung SSD PM830 2.5 7mm 256GB                   | 1         | 1.43%   |
| Samsung SSD 870 EVO 500GB                         | 1         | 1.43%   |
| Samsung SSD 860 PRO 256GB                         | 1         | 1.43%   |
| Samsung SSD 850 PRO 256GB                         | 1         | 1.43%   |
| Samsung PM9A1 NVMe 512GB                          | 1         | 1.43%   |
| Samsung NVMe SSD Drive 512GB                      | 1         | 1.43%   |
| Samsung NVMe SSD Drive 1TB                        | 1         | 1.43%   |
| Samsung MZVLW256HEHP-000L7 256GB                  | 1         | 1.43%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                    | 1         | 1.43%   |
| Samsung MZVLB1T0HALR-000H1 1TB                    | 1         | 1.43%   |
| Samsung MZVL2512HCJQ-00BH1 512GB                  | 1         | 1.43%   |
| Samsung MZNLN512HCJH-000L1 512GB SSD              | 1         | 1.43%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD              | 1         | 1.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 3         | 3      | 23.08%  |
| HGST               | 3         | 6      | 23.08%  |
| WDC                | 2         | 2      | 15.38%  |
| Unknown            | 2         | 4      | 15.38%  |
| Toshiba            | 1         | 1      | 7.69%   |
| JMicron Technology | 1         | 1      | 7.69%   |
| Fujitsu            | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 15     | 52.63%  |
| SanDisk             | 5         | 5      | 26.32%  |
| WDC                 | 2         | 2      | 10.53%  |
| Toshiba             | 1         | 1      | 5.26%   |
| Crucial             | 1         | 2      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 31        | 48     | 46.97%  |
| SSD     | 19        | 25     | 28.79%  |
| HDD     | 12        | 18     | 18.18%  |
| MMC     | 3         | 4      | 4.55%   |
| Unknown | 1         | 1      | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 31        | 48     | 47.69%  |
| SATA | 28        | 38     | 43.08%  |
| SAS  | 3         | 6      | 4.62%   |
| MMC  | 3         | 4      | 4.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 15        | 22     | 50%     |
| 0.01-0.5   | 12        | 18     | 40%     |
| 1.01-2.0   | 2         | 2      | 6.67%   |
| 3.01-4.0   | 1         | 1      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 16        | 26.67%  |
| 101-250    | 10        | 16.67%  |
| 1-20       | 10        | 16.67%  |
| 501-1000   | 10        | 16.67%  |
| Unknown    | 6         | 10%     |
| 51-100     | 3         | 5%      |
| 2001-3000  | 2         | 3.33%   |
| 1001-2000  | 2         | 3.33%   |
| 21-50      | 1         | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 22        | 35.48%  |
| 21-50     | 11        | 17.74%  |
| 51-100    | 11        | 17.74%  |
| Unknown   | 6         | 9.68%   |
| 251-500   | 5         | 8.06%   |
| 101-250   | 4         | 6.45%   |
| 501-1000  | 2         | 3.23%   |
| 1001-2000 | 1         | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9750420AS 752GB                        | 1         | 1      | 33.33%  |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 33.33%  |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 2      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 66.67%  |
| Samsung Electronics | 1         | 2      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 2      | 33.33%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 31        | 52     | 49.21%  |
| Works    | 29        | 40     | 46.03%  |
| Malfunc  | 3         | 4      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 29        | 45.31%  |
| Samsung Electronics         | 12        | 18.75%  |
| AMD                         | 4         | 6.25%   |
| SanDisk                     | 3         | 4.69%   |
| Micron Technology           | 3         | 4.69%   |
| SK hynix                    | 2         | 3.13%   |
| Phison Electronics          | 2         | 3.13%   |
| Micron/Crucial Technology   | 2         | 3.13%   |
| KIOXIA                      | 2         | 3.13%   |
| Kingston Technology Company | 2         | 3.13%   |
| Union Memory (Shenzhen)     | 1         | 1.56%   |
| Lite-On Technology          | 1         | 1.56%   |
| Lenovo                      | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 12.12%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 7.58%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 6.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 4.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 4.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 3.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.03%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                  | 1         | 1.52%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                | 1         | 1.52%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 1.52%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 1.52%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                            | 1         | 1.52%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 1.52%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.52%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.52%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                         | 1         | 1.52%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 1.52%   |
| Micron 2550 NVMe SSD (DRAM-less)                                                 | 1         | 1.52%   |
| Micron 2300 NVMe SSD [Santana]                                                   | 1         | 1.52%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 1         | 1.52%   |
| Lite-On CA5-8D512 NVMe SSD                                                       | 1         | 1.52%   |
| Lenovo LENSE30512GMSP34MEAT3TA                                                   | 1         | 1.52%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                       | 1         | 1.52%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 1.52%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                               | 1         | 1.52%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                         | 1         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.52%   |
| Intel SSD 660P Series                                                            | 1         | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.52%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.52%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 1.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 31        | 48.44%  |
| SATA | 28        | 43.75%  |
| RAID | 4         | 6.25%   |
| IDE  | 1         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 93.1%   |
| AMD    | 4         | 6.9%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 5.17%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 3.45%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 2         | 3.45%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 3.45%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 2         | 3.45%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 3.45%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 2         | 3.45%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 3.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 3.45%   |
| Intel 12th Gen Core i7-1270P            | 2         | 3.45%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 2         | 3.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 3.45%   |
| Intel Processor 5Y10 CPU @ 0.80GHz      | 1         | 1.72%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 1.72%   |
| Intel Core i9-9880H CPU @ 2.30GHz       | 1         | 1.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 1.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.72%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 1.72%   |
| Intel Core i7-4940MX CPU @ 3.10GHz      | 1         | 1.72%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz      | 1         | 1.72%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 1         | 1.72%   |
| Intel Core i7-2860QM CPU @ 2.50GHz      | 1         | 1.72%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.72%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 1         | 1.72%   |
| Intel Core i7-10850H CPU @ 2.70GHz      | 1         | 1.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.72%   |
| Intel Core i5-9300HF CPU @ 2.40GHz      | 1         | 1.72%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 1.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 1.72%   |
| Intel Core i5-4210M CPU @ 2.60GHz       | 1         | 1.72%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 1.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 1.72%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 1         | 1.72%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 1.72%   |
| Intel Celeron CPU N3010 @ 1.04GHz       | 1         | 1.72%   |
| Intel 13th Gen Core i7-1370P            | 1         | 1.72%   |
| Intel 13th Gen Core i5-1345U            | 1         | 1.72%   |
| Intel 12th Gen Core i7-12800HX          | 1         | 1.72%   |
| Intel 12th Gen Core i7-1260P            | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 22        | 37.93%  |
| Intel Core i5    | 14        | 24.14%  |
| Other            | 13        | 22.41%  |
| Intel Celeron    | 3         | 5.17%   |
| Intel Pentium    | 1         | 1.72%   |
| Intel Core i9    | 1         | 1.72%   |
| Intel Core 2 Duo | 1         | 1.72%   |
| AMD Ryzen 7 PRO  | 1         | 1.72%   |
| AMD Ryzen 7      | 1         | 1.72%   |
| AMD A8           | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 24        | 41.38%  |
| 2      | 20        | 34.48%  |
| 6      | 4         | 6.9%    |
| 12     | 3         | 5.17%   |
| 8      | 3         | 5.17%   |
| 16     | 1         | 1.72%   |
| 14     | 1         | 1.72%   |
| 10     | 1         | 1.72%   |
| 1      | 1         | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 58        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 47        | 81.03%  |
| 1      | 11        | 18.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 96.61%  |
| Unknown        | 2         | 3.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 11.67%  |
| 0x806ec    | 5         | 8.33%   |
| 0x806ea    | 4         | 6.67%   |
| 0x306c3    | 4         | 6.67%   |
| 0x206a7    | 4         | 6.67%   |
| 0x806e9    | 3         | 5%      |
| 0x806c1    | 3         | 5%      |
| 0x306d4    | 3         | 5%      |
| 0xa0652    | 2         | 3.33%   |
| 0x906ed    | 2         | 3.33%   |
| 0x906ea    | 2         | 3.33%   |
| 0x906a3    | 2         | 3.33%   |
| 0x706a8    | 2         | 3.33%   |
| 0x406e3    | 2         | 3.33%   |
| 0x406c4    | 2         | 3.33%   |
| 0x306a9    | 2         | 3.33%   |
| 0xb06a2    | 1         | 1.67%   |
| 0x90672    | 1         | 1.67%   |
| 0x806d1    | 1         | 1.67%   |
| 0x706e5    | 1         | 1.67%   |
| 0x506e3    | 1         | 1.67%   |
| 0x40651    | 1         | 1.67%   |
| 0x10676    | 1         | 1.67%   |
| 0x08608103 | 1         | 1.67%   |
| 0x0810100b | 1         | 1.67%   |
| 0x07030105 | 1         | 1.67%   |
| 0x06006705 | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 31.03%  |
| Haswell          | 5         | 8.62%   |
| Alderlake Hybrid | 5         | 8.62%   |
| TigerLake        | 4         | 6.9%    |
| SandyBridge      | 4         | 6.9%    |
| Skylake          | 3         | 5.17%   |
| Broadwell        | 3         | 5.17%   |
| Silvermont       | 2         | 3.45%   |
| IvyBridge        | 2         | 3.45%   |
| Icelake          | 2         | 3.45%   |
| Goldmont plus    | 2         | 3.45%   |
| CometLake        | 2         | 3.45%   |
| Unknown          | 2         | 3.45%   |
| Zen              | 1         | 1.72%   |
| Puma             | 1         | 1.72%   |
| Penryn           | 1         | 1.72%   |
| Excavator        | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 48        | 64%     |
| Nvidia | 19        | 25.33%  |
| AMD    | 8         | 10.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 5         | 6.67%   |
| Intel UHD Graphics 620                                                                   | 4         | 5.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 5.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 5.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 4%      |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 4%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 2.67%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 2.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 2.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.67%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.67%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                                        | 1         | 1.33%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 1.33%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 1.33%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.33%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.33%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.33%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 1.33%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                            | 1         | 1.33%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 1.33%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 1.33%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.33%   |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                                   | 1         | 1.33%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.33%   |
| Intel Raptor Lake-P [UHD Graphics]                                                       | 1         | 1.33%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 1         | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.33%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.33%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.33%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.33%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 50.85%  |
| Intel + Nvidia | 14        | 23.73%  |
| 1 x Nvidia     | 6         | 10.17%  |
| 1 x AMD        | 5         | 8.47%   |
| Intel + AMD    | 3         | 5.08%   |
| Other          | 1         | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 52        | 86.67%  |
| Proprietary | 4         | 6.67%   |
| Unknown     | 4         | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 55.93%  |
| 1.01-2.0   | 10        | 16.95%  |
| 3.01-4.0   | 9         | 15.25%  |
| 0.51-1.0   | 3         | 5.08%   |
| 0.01-0.5   | 3         | 5.08%   |
| 5.01-6.0   | 1         | 1.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 14        | 17.5%   |
| Chimei Innolux       | 12        | 15%     |
| LG Display           | 10        | 12.5%   |
| BOE                  | 9         | 11.25%  |
| Dell                 | 7         | 8.75%   |
| Samsung Electronics  | 6         | 7.5%    |
| Lenovo               | 5         | 6.25%   |
| ViewSonic            | 3         | 3.75%   |
| InfoVision           | 3         | 3.75%   |
| BenQ                 | 3         | 3.75%   |
| Sharp                | 2         | 2.5%    |
| Acer                 | 2         | 2.5%    |
| Sceptre Tech         | 1         | 1.25%   |
| BOE Technology Group | 1         | 1.25%   |
| ASUSTek Computer     | 1         | 1.25%   |
| Ancor Communications | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 2.38%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 2.38%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 2         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 2.38%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 2.38%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 2.38%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 2.38%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                      | 2         | 2.38%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 1.19%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 1.19%   |
| ViewSonic VG2439 SERIES VSCD22B 1920x1080 521x293mm 23.5-inch         | 1         | 1.19%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 1.19%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 1.19%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch        | 1         | 1.19%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 1.19%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch     | 1         | 1.19%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 1.19%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 1.19%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1         | 1.19%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 1.19%   |
| LG Display LCD Monitor LGD0725 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0628 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.19%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 1.19%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1         | 1.19%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch              | 1         | 1.19%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 1         | 1.19%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 1         | 1.19%   |
| InfoVision LCD Monitor IVO048E 1366x768 256x144mm 11.6-inch           | 1         | 1.19%   |
| Dell U2718Q DELA0EA 3840x2160 609x349mm 27.6-inch                     | 1         | 1.19%   |
| Dell S3221QS DELD105 3840x2160 697x392mm 31.5-inch                    | 1         | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 39        | 59.09%  |
| 1366x768 (WXGA)    | 7         | 10.61%  |
| 3840x2160 (4K)     | 5         | 7.58%   |
| 1600x900 (HD+)     | 5         | 7.58%   |
| 1920x1200 (WUXGA)  | 3         | 4.55%   |
| 1680x1050 (WSXGA+) | 2         | 3.03%   |
| 3840x2400          | 1         | 1.52%   |
| 2560x1440 (QHD)    | 1         | 1.52%   |
| 2560x1080          | 1         | 1.52%   |
| 1280x800 (WXGA)    | 1         | 1.52%   |
| 1280x1024 (SXGA)   | 1         | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 23        | 28.05%  |
| 14      | 15        | 18.29%  |
| 27      | 9         | 10.98%  |
| 13      | 9         | 10.98%  |
| 24      | 5         | 6.1%    |
| 23      | 4         | 4.88%   |
| 31      | 3         | 3.66%   |
| 38      | 2         | 2.44%   |
| 17      | 2         | 2.44%   |
| 16      | 2         | 2.44%   |
| 29      | 1         | 1.22%   |
| 22      | 1         | 1.22%   |
| 21      | 1         | 1.22%   |
| 20      | 1         | 1.22%   |
| 19      | 1         | 1.22%   |
| 12      | 1         | 1.22%   |
| 11      | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 60%     |
| 501-600     | 16        | 20%     |
| 601-700     | 5         | 6.25%   |
| 401-500     | 3         | 3.75%   |
| 201-300     | 3         | 3.75%   |
| 801-900     | 2         | 2.5%    |
| 351-400     | 2         | 2.5%    |
| Unknown     | 1         | 1.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 52        | 83.87%  |
| 16/10   | 7         | 11.29%  |
| 5/4     | 1         | 1.61%   |
| 21/9    | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 23        | 28.4%   |
| 101-110        | 23        | 28.4%   |
| 301-350        | 10        | 12.35%  |
| 201-250        | 10        | 12.35%  |
| 351-500        | 3         | 3.7%    |
| 151-200        | 2         | 2.47%   |
| 121-130        | 2         | 2.47%   |
| 111-120        | 2         | 2.47%   |
| 501-1000       | 2         | 2.47%   |
| 71-80          | 1         | 1.23%   |
| 61-70          | 1         | 1.23%   |
| 51-60          | 1         | 1.23%   |
| Unknown        | 1         | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 53.33%  |
| 51-100        | 18        | 24%     |
| 101-120       | 10        | 13.33%  |
| 161-240       | 4         | 5.33%   |
| More than 240 | 2         | 2.67%   |
| Unknown       | 1         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 33        | 55%     |
| 2     | 16        | 26.67%  |
| 3     | 6         | 10%     |
| 0     | 4         | 6.67%   |
| 4     | 1         | 1.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 48        | 52.75%  |
| Realtek Semiconductor             | 23        | 25.27%  |
| Qualcomm Atheros                  | 4         | 4.4%    |
| Lenovo                            | 3         | 3.3%    |
| Samsung Electronics               | 2         | 2.2%    |
| ASIX Electronics                  | 2         | 2.2%    |
| Ralink Technology                 | 1         | 1.1%    |
| NetGear                           | 1         | 1.1%    |
| Huawei Technologies               | 1         | 1.1%    |
| FIBOCOM                           | 1         | 1.1%    |
| Ericsson Business Mobile Networks | 1         | 1.1%    |
| Edimax Technology                 | 1         | 1.1%    |
| DisplayLink                       | 1         | 1.1%    |
| Broadcom Limited                  | 1         | 1.1%    |
| Broadcom                          | 1         | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 7.26%   |
| Intel Wireless 8265 / 8275                                             | 9         | 7.26%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 4.84%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 4.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 2.42%   |
| Intel Wireless 7265                                                    | 3         | 2.42%   |
| Intel Wireless 7260                                                    | 3         | 2.42%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 2.42%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 2.42%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 2.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 2.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 2.42%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 1.61%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 1.61%   |
| Intel Wireless 8260                                                    | 2         | 1.61%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 1.61%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.61%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                         | 2         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.61%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.81%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.81%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                        | 1         | 0.81%   |
| Lenovo ThinkPad TBT3 LAN                                               | 1         | 0.81%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1         | 0.81%   |
| Intel Wi-Fi 6 AX200                                                    | 1         | 0.81%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 75.81%  |
| Realtek Semiconductor | 6         | 9.68%   |
| Qualcomm Atheros      | 4         | 6.45%   |
| Ralink Technology     | 1         | 1.61%   |
| NetGear               | 1         | 1.61%   |
| FIBOCOM               | 1         | 1.61%   |
| Edimax Technology     | 1         | 1.61%   |
| Broadcom              | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 9         | 14.52%  |
| Intel Wireless 7265                                            | 3         | 4.84%   |
| Intel Wireless 7260                                            | 3         | 4.84%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 4.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 4.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 4.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 3.23%   |
| Intel Wireless 8260                                            | 2         | 3.23%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 3.23%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 3.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 3.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.61%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.61%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.61%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                | 1         | 1.61%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 1.61%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.61%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.61%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.61%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1         | 1.61%   |
| FIBOCOM L830-EB-00                                             | 1         | 1.61%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 48.33%  |
| Realtek Semiconductor | 21        | 35%     |
| Lenovo                | 3         | 5%      |
| Samsung Electronics   | 2         | 3.33%   |
| ASIX Electronics      | 2         | 3.33%   |
| Huawei Technologies   | 1         | 1.67%   |
| DisplayLink           | 1         | 1.67%   |
| Broadcom Limited      | 1         | 1.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 14.75%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 13.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 9.84%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 8.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 4.92%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 4.92%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 4.92%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 3.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 3.28%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 3.28%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 3.28%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 3.28%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 3.28%   |
| Lenovo ThinkPad TBT3 LAN                                               | 1         | 1.64%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.64%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.64%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.64%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.64%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 1.64%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.64%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 1.64%   |
| Intel Ethernet Connection (14) I219-V                                  | 1         | 1.64%   |
| Huawei Mobile                                                          | 1         | 1.64%   |
| DisplayLink Dell Universal Dock D6000                                  | 1         | 1.64%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 1         | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 53.27%  |
| Ethernet | 49        | 45.79%  |
| Modem    | 1         | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 63.33%  |
| Ethernet | 22        | 36.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 40        | 68.97%  |
| 1     | 18        | 31.03%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 70.97%  |
| Yes  | 18        | 29.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 74.42%  |
| Realtek Semiconductor           | 4         | 9.3%    |
| Qualcomm Atheros Communications | 4         | 9.3%    |
| Broadcom                        | 2         | 4.65%   |
| Alps Electric                   | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                         | 7         | 16.28%  |
| Intel AX201 Bluetooth                          | 7         | 16.28%  |
| Intel AX211 Bluetooth                          | 6         | 13.95%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 5         | 11.63%  |
| Intel Bluetooth wireless interface             | 4         | 9.3%    |
| Realtek Bluetooth Radio                        | 3         | 6.98%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 4.65%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 2.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 2.33%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 2.33%   |
| Intel AX210 Bluetooth                          | 1         | 2.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 2.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 2.33%   |
| Alps Electric UGTZ4 Bluetooth                  | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 62.79%  |
| Nvidia                | 10        | 11.63%  |
| AMD                   | 6         | 6.98%   |
| Lenovo                | 4         | 4.65%   |
| GN Netcom             | 4         | 4.65%   |
| Plantronics           | 2         | 2.33%   |
| Unknown               | 1         | 1.16%   |
| TEAC                  | 1         | 1.16%   |
| RME                   | 1         | 1.16%   |
| Realtek Semiconductor | 1         | 1.16%   |
| JMTek                 | 1         | 1.16%   |
| C-Media Electronics   | 1         | 1.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 11.34%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 4.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 4.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 4.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 3.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 3.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 3.09%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 3.09%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 3.09%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 2.06%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 2.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 2.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.06%   |
| Unknown Definitive Sym1                                                                           | 1         | 1.03%   |
| TEAC US-2x2                                                                                       | 1         | 1.03%   |
| RME ADI-2 DAC (56760369)                                                                          | 1         | 1.03%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.03%   |
| Plantronics Poly BT700                                                                            | 1         | 1.03%   |
| Plantronics BT600                                                                                 | 1         | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.03%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.03%   |
| Nvidia Audio device                                                                               | 1         | 1.03%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 1.03%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 1.03%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 1.03%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.03%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 26.32%  |
| SK hynix            | 8         | 21.05%  |
| Micron Technology   | 7         | 18.42%  |
| Unknown             | 3         | 7.89%   |
| Unknown             | 2         | 5.26%   |
| Kingston            | 2         | 5.26%   |
| Corsair             | 2         | 5.26%   |
| Nanya Technology    | 1         | 2.63%   |
| Crucial             | 1         | 2.63%   |
| Avant               | 1         | 2.63%   |
| 4ea5                | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 7.69%   |
| Unknown                                                      | 3         | 7.69%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 2.56%   |
| Unknown RAM Module 32GB SODIMM DDR4 2667MT/s                 | 1         | 2.56%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                | 1         | 2.56%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                | 1         | 2.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 2.56%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 2.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s | 1         | 2.56%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 2.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 2.56%   |
| SK hynix RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s          | 1         | 2.56%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                  | 1         | 2.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 2.56%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 2.56%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 1         | 2.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 2.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.56%   |
| Nanya RAM NT8GA64D88AX3S-HR 8GB SODIMM DDR4 2667MT/s         | 1         | 2.56%   |
| Micron RAM Module 32GB SODIMM DDR4 2667MT/s                  | 1         | 2.56%   |
| Micron RAM Module 16384MB SODIMM DDR4 2400MT/s               | 1         | 2.56%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s        | 1         | 2.56%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 2.56%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s      | 1         | 2.56%   |
| Micron RAM 16JTF1G64HZ-1G4D1 8GB SODIMM DDR3 1333MT/s        | 1         | 2.56%   |
| Micron RAM 16ATF2G64HZ-2G1A1 16GB SODIMM DDR4 2133MT/s       | 1         | 2.56%   |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s             | 1         | 2.56%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s             | 1         | 2.56%   |
| Crucial RAM CT32G4SFD8266.C16FF 32GB SODIMM DDR4 2667MT/s    | 1         | 2.56%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s    | 1         | 2.56%   |
| Corsair RAM CMSX32GX4M2A2400C16 16GB SODIMM DDR4 2400MT/s    | 1         | 2.56%   |
| Avant RAM H6451U66G1600G 4096MB SODIMM DDR3 1600MT/s         | 1         | 2.56%   |
| 4ea5 RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s              | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 57.14%  |
| DDR3   | 9         | 25.71%  |
| LPDDR5 | 3         | 8.57%   |
| LPDDR4 | 2         | 5.71%   |
| DDR5   | 1         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 80%     |
| Row Of Chips | 6         | 17.14%  |
| Unknown      | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 14        | 38.89%  |
| 16384 | 9         | 25%     |
| 4096  | 7         | 19.44%  |
| 32768 | 4         | 11.11%  |
| 2048  | 2         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 11        | 30.56%  |
| 1600  | 7         | 19.44%  |
| 3200  | 5         | 13.89%  |
| 2400  | 4         | 11.11%  |
| 6400  | 3         | 8.33%   |
| 1333  | 2         | 5.56%   |
| 4800  | 1         | 2.78%   |
| 4267  | 1         | 2.78%   |
| 2133  | 1         | 2.78%   |
| 1866  | 1         | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 25.49%  |
| Realtek Semiconductor                  | 5         | 9.8%    |
| Logitech                               | 5         | 9.8%    |
| IMC Networks                           | 5         | 9.8%    |
| Microdia                               | 4         | 7.84%   |
| Suyin                                  | 3         | 5.88%   |
| Quanta                                 | 3         | 5.88%   |
| Luxvisions Innotech Limited            | 3         | 5.88%   |
| Lite-On Technology                     | 3         | 5.88%   |
| Bison Electronics                      | 3         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.92%   |
| Microsoft                              | 1         | 1.96%   |
| Apple                                  | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 6         | 11.54%  |
| Microdia Integrated_Webcam_HD                                   | 3         | 5.77%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 3.85%   |
| Realtek Integrated_Webcam_FHD                                   | 2         | 3.85%   |
| Quanta HP HD Camera                                             | 2         | 3.85%   |
| Lite-On Integrated Camera                                       | 2         | 3.85%   |
| IMC Networks VGA UVC WebCam                                     | 2         | 3.85%   |
| IMC Networks Integrated Camera                                  | 2         | 3.85%   |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 3.85%   |
| Bison SunplusIT Integrated Camera                               | 2         | 3.85%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 1.92%   |
| Suyin HP Truevision HD                                          | 1         | 1.92%   |
| Suyin Asus Integrated Webcam                                    | 1         | 1.92%   |
| Realtek EasyCamera                                              | 1         | 1.92%   |
| Quanta HP Webcam                                                | 1         | 1.92%   |
| Microsoft LifeCam HD-3000                                       | 1         | 1.92%   |
| Microdia Webcam Vitade AF                                       | 1         | 1.92%   |
| Luxvisions Innotech Limited Integrated RGB Camera               | 1         | 1.92%   |
| Luxvisions Innotech Limited HP 5MP Camera                       | 1         | 1.92%   |
| Luxvisions Innotech Limited EasyCamera 1M                       | 1         | 1.92%   |
| Logitech Webcam C925e                                           | 1         | 1.92%   |
| Logitech Webcam C920-C                                          | 1         | 1.92%   |
| Logitech HD Webcam C615                                         | 1         | 1.92%   |
| Logitech HD Webcam C510                                         | 1         | 1.92%   |
| Logitech BRIO Ultra HD Webcam                                   | 1         | 1.92%   |
| Lite-On HP HD Camera                                            | 1         | 1.92%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 1         | 1.92%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 1         | 1.92%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 1.92%   |
| Chicony TOSHIBA Web Camera - FHD                                | 1         | 1.92%   |
| Chicony ThinkPad T490 Webcam                                    | 1         | 1.92%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 1         | 1.92%   |
| Chicony Integrated IR Camera                                    | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 1.92%   |
| Bison Integrated Camera                                         | 1         | 1.92%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 40.91%  |
| Synaptics                  | 9         | 40.91%  |
| Upek                       | 1         | 4.55%   |
| Shenzhen Goodix Technology | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |
| AuthenTec                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 13.64%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 13.64%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 13.64%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 9.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 9.09%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 9.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 4.55%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 4.55%   |
| Synaptics WBDI                                                             | 1         | 4.55%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                                      | 1         | 4.55%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 69.23%  |
| Alcor Micro | 3         | 23.08%  |
| Lenovo      | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 6         | 46.15%  |
| Broadcom BCM5880 Secure Applications Processor | 3         | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 15.38%  |
| Lenovo Integrated Smart Card Reader            | 1         | 7.69%   |
| Alcor Micro Watchdata W 1981                   | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 45.16%  |
| 0     | 21        | 33.87%  |
| 2     | 9         | 14.52%  |
| 3     | 3         | 4.84%   |
| 7     | 1         | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 22        | 40%     |
| Chipcard                 | 10        | 18.18%  |
| Net/wireless             | 9         | 16.36%  |
| Graphics card            | 6         | 10.91%  |
| Storage                  | 2         | 3.64%   |
| Card reader              | 2         | 3.64%   |
| Sound                    | 1         | 1.82%   |
| Multimedia controller    | 1         | 1.82%   |
| Communication controller | 1         | 1.82%   |
| Bluetooth                | 1         | 1.82%   |

