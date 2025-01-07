UbuntuDDE - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for UbuntuDDE.

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | IdeaPad Pro 5 14IMH9 83D... | [1482125b7f](https://linux-hardware.org/?probe=1482125b7f) | Dec 10, 2024 |
| Lenovo    | IdeaPad Pro 5 14IMH9 83D... | [64809e77e6](https://linux-hardware.org/?probe=64809e77e6) | Dec 10, 2024 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | [1f9f468508](https://linux-hardware.org/?probe=1f9f468508) | Nov 28, 2024 |
| HP        | EliteBook 820 G3            | [abbc44e591](https://linux-hardware.org/?probe=abbc44e591) | Nov 06, 2024 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | [f0a53e90c1](https://linux-hardware.org/?probe=f0a53e90c1) | Aug 25, 2024 |
| ASUSTek   | ASUS Vivobook S 14 M5406... | [f25f2b97ef](https://linux-hardware.org/?probe=f25f2b97ef) | Aug 01, 2024 |
| HUAWEI    | MACHC-WAX9                  | [f9ce9e4174](https://linux-hardware.org/?probe=f9ce9e4174) | Jul 17, 2024 |
| HP        | EliteBook 8570p             | [103b3dc25f](https://linux-hardware.org/?probe=103b3dc25f) | Feb 25, 2024 |
| Chuwi     | HeroBook Pro                | [f34f3d183d](https://linux-hardware.org/?probe=f34f3d183d) | Feb 23, 2024 |
| HP        | 250 G3                      | [784033212e](https://linux-hardware.org/?probe=784033212e) | Oct 29, 2023 |
| HP        | 250 G3                      | [43fbeb0886](https://linux-hardware.org/?probe=43fbeb0886) | Oct 26, 2023 |
| Lenovo    | 100-14IBY 80R7              | [f6389f0244](https://linux-hardware.org/?probe=f6389f0244) | Oct 06, 2023 |
| Dell      | Latitude E7450              | [d7a8f0a599](https://linux-hardware.org/?probe=d7a8f0a599) | Jul 22, 2023 |
| Apple     | MacBookPro12,1              | [fc6e3f084f](https://linux-hardware.org/?probe=fc6e3f084f) | Jun 04, 2023 |
| Apple     | MacBookPro12,1              | [a9c6f5e0e6](https://linux-hardware.org/?probe=a9c6f5e0e6) | Jun 04, 2023 |
| Acer      | Aspire A317-53              | [406fc17c32](https://linux-hardware.org/?probe=406fc17c32) | Jun 04, 2023 |
| Samsung   | 355V4C/356V4C/3445VC/354... | [65a009e9dd](https://linux-hardware.org/?probe=65a009e9dd) | Apr 20, 2023 |
| Dell      | Latitude E6430              | [7fe3f11f56](https://linux-hardware.org/?probe=7fe3f11f56) | Dec 22, 2022 |
| Dell      | Latitude E6430              | [60832751d1](https://linux-hardware.org/?probe=60832751d1) | Nov 16, 2022 |
| HP        | Notebook                    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| Dell      | Inspiron N4030              | [ac4c492fcf](https://linux-hardware.org/?probe=ac4c492fcf) | Mar 05, 2022 |
| Dell      | Inspiron N4030              | [e5e17e5138](https://linux-hardware.org/?probe=e5e17e5138) | Mar 05, 2022 |
| HP        | ProBook 650 G3              | [32fcb78172](https://linux-hardware.org/?probe=32fcb78172) | Jan 23, 2022 |
| Framework | Laptop                      | [081416685c](https://linux-hardware.org/?probe=081416685c) | Jan 18, 2022 |
| Dell      | XPS 15 9570                 | [b8d4a9ee87](https://linux-hardware.org/?probe=b8d4a9ee87) | Jan 17, 2022 |
| Google    | Banon                       | [a6febddf28](https://linux-hardware.org/?probe=a6febddf28) | Jan 06, 2022 |
| ASUSTek   | G550JK                      | [b26b378274](https://linux-hardware.org/?probe=b26b378274) | Jan 01, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop X421... | [b2a9183e6d](https://linux-hardware.org/?probe=b2a9183e6d) | Oct 09, 2021 |
| Lenovo    | IdeaPad 510-15IKB 80SV      | [71958172cf](https://linux-hardware.org/?probe=71958172cf) | Oct 08, 2021 |
| Dell      | XPS 15 9570                 | [661937dcfa](https://linux-hardware.org/?probe=661937dcfa) | Sep 12, 2021 |
| Dell      | XPS 15 9570                 | [a950c391ee](https://linux-hardware.org/?probe=a950c391ee) | Sep 12, 2021 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | [f3199bc88b](https://linux-hardware.org/?probe=f3199bc88b) | Jul 25, 2021 |
| MSI       | GS60 2QE                    | [7ef8c79c08](https://linux-hardware.org/?probe=7ef8c79c08) | May 24, 2021 |
| MSI       | GS60 2QE                    | [1660ac34ec](https://linux-hardware.org/?probe=1660ac34ec) | May 24, 2021 |
| Acer      | Predator PH317-52           | [5737732bb0](https://linux-hardware.org/?probe=5737732bb0) | May 15, 2021 |
| HP        | OMEN by Laptop 17-cb1xxx    | [ca2397cddf](https://linux-hardware.org/?probe=ca2397cddf) | May 12, 2021 |
| HP        | EliteBook 2540p             | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| ASUSTek   | S551LN                      | [1c51e0899d](https://linux-hardware.org/?probe=1c51e0899d) | Apr 06, 2021 |
| ASUSTek   | S551LN                      | [d03bb12703](https://linux-hardware.org/?probe=d03bb12703) | Apr 06, 2021 |
| Dell      | Latitude E6320              | [8e7c6ced02](https://linux-hardware.org/?probe=8e7c6ced02) | Dec 15, 2020 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | [e070ae2fd4](https://linux-hardware.org/?probe=e070ae2fd4) | Oct 19, 2020 |
| ASUSTek   | X555QG                      | [ae5665efc4](https://linux-hardware.org/?probe=ae5665efc4) | Oct 02, 2020 |
| Dell      | Inspiron 5447               | [a316ca39ef](https://linux-hardware.org/?probe=a316ca39ef) | Sep 25, 2020 |
| HP        | Pavilion dm4                | [7ab3fbd60d](https://linux-hardware.org/?probe=7ab3fbd60d) | Aug 26, 2020 |
| HP        | Pavilion dm4                | [f3f1ea6d44](https://linux-hardware.org/?probe=f3f1ea6d44) | Aug 26, 2020 |
| HUAWEI    | MACH-WX9                    | [b7c774660b](https://linux-hardware.org/?probe=b7c774660b) | Aug 23, 2020 |
| HUAWEI    | MACH-WX9                    | [08bdddfbb1](https://linux-hardware.org/?probe=08bdddfbb1) | Aug 23, 2020 |
| Dell      | System XPS L502X            | [caa5473285](https://linux-hardware.org/?probe=caa5473285) | Aug 13, 2020 |
| Lenovo    | G480 20150                  | [4531dd50a5](https://linux-hardware.org/?probe=4531dd50a5) | Aug 11, 2020 |
| Lenovo    | G480 20150                  | [8e51b2cb2d](https://linux-hardware.org/?probe=8e51b2cb2d) | Aug 11, 2020 |
| Dell      | System XPS L502X            | [019fc71c57](https://linux-hardware.org/?probe=019fc71c57) | Aug 05, 2020 |
| ASUSTek   | TP300LA                     | [4cb4390fa3](https://linux-hardware.org/?probe=4cb4390fa3) | Aug 01, 2020 |
| ASUSTek   | TP300LA                     | [e273444401](https://linux-hardware.org/?probe=e273444401) | Aug 01, 2020 |
| Acer      | Aspire 5750                 | [19876e9920](https://linux-hardware.org/?probe=19876e9920) | Jul 25, 2020 |
| Dell      | G7 7588                     | [34805cf5b8](https://linux-hardware.org/?probe=34805cf5b8) | Jul 24, 2020 |
| Toshiba   | Satellite S55t-B            | [01aa2bca69](https://linux-hardware.org/?probe=01aa2bca69) | Jun 28, 2020 |
| Toshiba   | Satellite S55t-B            | [71ae60ebc0](https://linux-hardware.org/?probe=71ae60ebc0) | Jun 27, 2020 |
| Lenovo    | IdeaPad 520-15IKB 81BF      | [2a82822b1d](https://linux-hardware.org/?probe=2a82822b1d) | Jun 24, 2020 |
| Lenovo    | IdeaPad 520-15IKB 81BF      | [9f58b08659](https://linux-hardware.org/?probe=9f58b08659) | Jun 24, 2020 |
| Dell      | Inspiron 1525               | [f01a10328b](https://linux-hardware.org/?probe=f01a10328b) | Jun 17, 2020 |
| HP        | Presario CQ56               | [211a5c9ec1](https://linux-hardware.org/?probe=211a5c9ec1) | Jun 17, 2020 |
| Acer      | Aspire V5-471               | [346de9f5d8](https://linux-hardware.org/?probe=346de9f5d8) | Jun 14, 2020 |
| Unknown   | Unknown                     | [1da538b1cf](https://linux-hardware.org/?probe=1da538b1cf) | Jun 04, 2020 |
| Unknown   | Unknown                     | [950be7ae19](https://linux-hardware.org/?probe=950be7ae19) | Jun 04, 2020 |
| Lenovo    | ThinkPad T430 2349DS5       | [77d17289e7](https://linux-hardware.org/?probe=77d17289e7) | May 31, 2020 |
| HP        | Laptop 15-dy1xxx            | [ea23c3bbdb](https://linux-hardware.org/?probe=ea23c3bbdb) | May 16, 2020 |
| HP        | Laptop 15-dy1xxx            | [d55c3ee4b0](https://linux-hardware.org/?probe=d55c3ee4b0) | May 16, 2020 |
| Acer      | Aspire 5733                 | [42424919ae](https://linux-hardware.org/?probe=42424919ae) | May 14, 2020 |
| HP        | 250 G4 Notebook PC          | [2406267563](https://linux-hardware.org/?probe=2406267563) | May 12, 2020 |
| HP        | 250 G4 Notebook PC          | [7e8fdf4b86](https://linux-hardware.org/?probe=7e8fdf4b86) | May 11, 2020 |
| Toshiba   | Satellite C55-B             | [2a1a979433](https://linux-hardware.org/?probe=2a1a979433) | May 11, 2020 |
| HP        | Pavilion 14                 | [f366f5c4e4](https://linux-hardware.org/?probe=f366f5c4e4) | May 11, 2020 |
| Lenovo    | G550 2958                   | [cfd6e82a6f](https://linux-hardware.org/?probe=cfd6e82a6f) | May 11, 2020 |
| Lenovo    | ThinkPad X200 Tablet 744... | [6c9138359f](https://linux-hardware.org/?probe=6c9138359f) | May 10, 2020 |
| Dell      | Inspiron N7010              | [2568ca0355](https://linux-hardware.org/?probe=2568ca0355) | May 07, 2020 |
| HP        | Pavilion dv6                | [46c69aad2a](https://linux-hardware.org/?probe=46c69aad2a) | Apr 30, 2020 |
| HP        | Laptop 15-da0xxx            | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek   | N750JK                      | [f38f6111a4](https://linux-hardware.org/?probe=f38f6111a4) | Apr 07, 2020 |
| Dell      | Latitude E5440              | [6c3cb81d00](https://linux-hardware.org/?probe=6c3cb81d00) | Aug 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| UbuntuDDE 20.04 | 31        | 56.36%  |
| UbuntuDDE 23.04 | 5         | 9.09%   |
| UbuntuDDE 22.04 | 5         | 9.09%   |
| UbuntuDDE 21.04 | 5         | 9.09%   |
| UbuntuDDE 21.10 | 4         | 7.27%   |
| UbuntuDDE 24.04 | 2         | 3.64%   |
| UbuntuDDE 20.10 | 2         | 3.64%   |
| UbuntuDDE 18.10 | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| UbuntuDDE | 55        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 7         | 12.07%  |
| 5.4.0-29-generic   | 7         | 12.07%  |
| 5.4.0-37-generic   | 4         | 6.9%    |
| 6.2.0-39-generic   | 3         | 5.17%   |
| 5.4.0-48-generic   | 2         | 3.45%   |
| 5.4.0-21-generic   | 2         | 3.45%   |
| 5.11.0-17-generic  | 2         | 3.45%   |
| 6.8.0-49-generic   | 1         | 1.72%   |
| 6.8.0-45-generic   | 1         | 1.72%   |
| 6.2.0-34-generic   | 1         | 1.72%   |
| 6.2.0-27-generic   | 1         | 1.72%   |
| 5.8.0-33-generic   | 1         | 1.72%   |
| 5.8.0-23-generic   | 1         | 1.72%   |
| 5.6.0-1008-oem     | 1         | 1.72%   |
| 5.4.0-96-generic   | 1         | 1.72%   |
| 5.4.0-94-generic   | 1         | 1.72%   |
| 5.4.0-88-generic   | 1         | 1.72%   |
| 5.4.0-84-generic   | 1         | 1.72%   |
| 5.4.0-70-generic   | 1         | 1.72%   |
| 5.4.0-52-generic   | 1         | 1.72%   |
| 5.4.0-39-generic   | 1         | 1.72%   |
| 5.4.0-34-generic   | 1         | 1.72%   |
| 5.4.0-33-generic   | 1         | 1.72%   |
| 5.19.0-38-generic  | 1         | 1.72%   |
| 5.15.0-88-generic  | 1         | 1.72%   |
| 5.15.0-57-generic  | 1         | 1.72%   |
| 5.15.0-53-generic  | 1         | 1.72%   |
| 5.15.0-48-generic  | 1         | 1.72%   |
| 5.15.0-119-generic | 1         | 1.72%   |
| 5.15.0-107-generic | 1         | 1.72%   |
| 5.13.0-30-generic  | 1         | 1.72%   |
| 5.13.0-23-generic  | 1         | 1.72%   |
| 5.13.0-22-generic  | 1         | 1.72%   |
| 5.13.0-21-generic  | 1         | 1.72%   |
| 5.11.0-46-generic  | 1         | 1.72%   |
| 5.11.0-25-generic  | 1         | 1.72%   |
| 5.11.0-16-generic  | 1         | 1.72%   |
| 4.15.0-29-generic  | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 54.55%  |
| 6.2.0   | 5         | 9.09%   |
| 5.11.0  | 5         | 9.09%   |
| 5.15.0  | 4         | 7.27%   |
| 5.13.0  | 4         | 7.27%   |
| 6.8.0   | 2         | 3.64%   |
| 5.8.0   | 2         | 3.64%   |
| 5.6.0   | 1         | 1.82%   |
| 5.19.0  | 1         | 1.82%   |
| 4.15.0  | 1         | 1.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 54.55%  |
| 6.2     | 5         | 9.09%   |
| 5.11    | 5         | 9.09%   |
| 5.15    | 4         | 7.27%   |
| 5.13    | 4         | 7.27%   |
| 6.8     | 2         | 3.64%   |
| 5.8     | 2         | 3.64%   |
| 5.6     | 1         | 1.82%   |
| 5.19    | 1         | 1.82%   |
| 4.15    | 1         | 1.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 55        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Deepin | 55        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 52        | 94.55%  |
| Wayland | 3         | 5.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 26        | 46.43%  |
| LightDM | 17        | 30.36%  |
| GDM     | 8         | 14.29%  |
| GDM3    | 3         | 5.36%   |
| TDM     | 1         | 1.79%   |
| SDDM    | 1         | 1.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 18        | 32.73%  |
| pt_BR   | 6         | 10.91%  |
| es_ES   | 3         | 5.45%   |
| de_DE   | 3         | 5.45%   |
| C       | 3         | 5.45%   |
| ru_RU   | 2         | 3.64%   |
| fr_FR   | 2         | 3.64%   |
| es_MX   | 2         | 3.64%   |
| es_AR   | 2         | 3.64%   |
| en_GB   | 2         | 3.64%   |
| en_AU   | 2         | 3.64%   |
| sr_RS   | 1         | 1.82%   |
| nl_NL   | 1         | 1.82%   |
| it_IT   | 1         | 1.82%   |
| id_ID   | 1         | 1.82%   |
| es_CO   | 1         | 1.82%   |
| en_ZA   | 1         | 1.82%   |
| en_IN   | 1         | 1.82%   |
| en_BW   | 1         | 1.82%   |
| cs_CZ   | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 30        | 53.57%  |
| EFI  | 26        | 46.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 45        | 81.82%  |
| Tmpfs   | 5         | 9.09%   |
| Overlay | 3         | 5.45%   |
| Zfs     | 1         | 1.82%   |
| Ext2    | 1         | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 29        | 52.73%  |
| GPT     | 23        | 41.82%  |
| MBR     | 3         | 5.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 83.64%  |
| Yes       | 9         | 16.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 52.73%  |
| No        | 26        | 47.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 14        | 25.45%  |
| Dell                | 11        | 20%     |
| Lenovo              | 8         | 14.55%  |
| ASUSTek Computer    | 8         | 14.55%  |
| Acer                | 4         | 7.27%   |
| Toshiba             | 2         | 3.64%   |
| HUAWEI              | 2         | 3.64%   |
| Samsung Electronics | 1         | 1.82%   |
| MSI                 | 1         | 1.82%   |
| Google              | 1         | 1.82%   |
| Framework           | 1         | 1.82%   |
| Chuwi               | 1         | 1.82%   |
| Unknown             | 1         | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba Satellite S55t-B             | 1         | 1.82%   |
| Toshiba Satellite C55-B              | 1         | 1.82%   |
| Samsung 355V4C/356V4C/3445VC/3545VC  | 1         | 1.82%   |
| MSI GS60 2QE                         | 1         | 1.82%   |
| Lenovo ThinkPad X200 Tablet 7449FWG  | 1         | 1.82%   |
| Lenovo ThinkPad T430 2349DS5         | 1         | 1.82%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0A300 | 1         | 1.82%   |
| Lenovo IdeaPad Pro 5 14IMH9 83D2     | 1         | 1.82%   |
| Lenovo IdeaPad 520-15IKB 81BF        | 1         | 1.82%   |
| Lenovo IdeaPad 510-15IKB 80SV        | 1         | 1.82%   |
| Lenovo G480 20150                    | 1         | 1.82%   |
| Lenovo 100-14IBY 80R7                | 1         | 1.82%   |
| HUAWEI MACHC-WAX9                    | 1         | 1.82%   |
| HUAWEI MACH-WX9                      | 1         | 1.82%   |
| HP ProBook 650 G3                    | 1         | 1.82%   |
| HP Presario CQ56                     | 1         | 1.82%   |
| HP Pavilion dv6                      | 1         | 1.82%   |
| HP Pavilion dm4                      | 1         | 1.82%   |
| HP Pavilion 14                       | 1         | 1.82%   |
| HP OMEN by Laptop 17-cb1xxx          | 1         | 1.82%   |
| HP Notebook                          | 1         | 1.82%   |
| HP Laptop 15-dy1xxx                  | 1         | 1.82%   |
| HP Laptop 15-da0xxx                  | 1         | 1.82%   |
| HP EliteBook 8570p                   | 1         | 1.82%   |
| HP EliteBook 820 G3                  | 1         | 1.82%   |
| HP EliteBook 2540p                   | 1         | 1.82%   |
| HP 250 G4 Notebook PC                | 1         | 1.82%   |
| HP 250 G3                            | 1         | 1.82%   |
| Google Banon                         | 1         | 1.82%   |
| Framework Laptop                     | 1         | 1.82%   |
| Dell XPS 15 9570                     | 1         | 1.82%   |
| Dell System XPS L502X                | 1         | 1.82%   |
| Dell Latitude E7450                  | 1         | 1.82%   |
| Dell Latitude E6430                  | 1         | 1.82%   |
| Dell Latitude E6320                  | 1         | 1.82%   |
| Dell Latitude E5440                  | 1         | 1.82%   |
| Dell Inspiron N7010                  | 1         | 1.82%   |
| Dell Inspiron N4030                  | 1         | 1.82%   |
| Dell Inspiron 5447                   | 1         | 1.82%   |
| Dell Inspiron 1525                   | 1         | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Latitude     | 4         | 7.27%   |
| Dell Inspiron     | 4         | 7.27%   |
| Lenovo ThinkPad   | 3         | 5.45%   |
| Lenovo IdeaPad    | 3         | 5.45%   |
| HP Pavilion       | 3         | 5.45%   |
| HP EliteBook      | 3         | 5.45%   |
| ASUS VivoBook     | 3         | 5.45%   |
| Acer Aspire       | 3         | 5.45%   |
| Toshiba Satellite | 2         | 3.64%   |
| HP Laptop         | 2         | 3.64%   |
| HP 250            | 2         | 3.64%   |
| Samsung 355V4C    | 1         | 1.82%   |
| MSI GS60          | 1         | 1.82%   |
| Lenovo G480       | 1         | 1.82%   |
| Lenovo 100-14IBY  | 1         | 1.82%   |
| HUAWEI MACHC-WAX9 | 1         | 1.82%   |
| HUAWEI MACH-WX9   | 1         | 1.82%   |
| HP ProBook        | 1         | 1.82%   |
| HP Presario       | 1         | 1.82%   |
| HP OMEN           | 1         | 1.82%   |
| HP Notebook       | 1         | 1.82%   |
| Google Banon      | 1         | 1.82%   |
| Framework Laptop  | 1         | 1.82%   |
| Dell XPS          | 1         | 1.82%   |
| Dell System       | 1         | 1.82%   |
| Dell G7           | 1         | 1.82%   |
| Chuwi HeroBook    | 1         | 1.82%   |
| ASUS X555QG       | 1         | 1.82%   |
| ASUS TP300LA      | 1         | 1.82%   |
| ASUS S551LN       | 1         | 1.82%   |
| ASUS G550JK       | 1         | 1.82%   |
| ASUS ASUS         | 1         | 1.82%   |
| Acer Predator     | 1         | 1.82%   |
| Unknown           | 1         | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2014 | 9         | 16.36%  |
| 2018 | 7         | 12.73%  |
| 2012 | 5         | 9.09%   |
| 2010 | 5         | 9.09%   |
| 2020 | 4         | 7.27%   |
| 2011 | 4         | 7.27%   |
| 2021 | 3         | 5.45%   |
| 2015 | 3         | 5.45%   |
| 2013 | 3         | 5.45%   |
| 2008 | 3         | 5.45%   |
| 2023 | 2         | 3.64%   |
| 2017 | 2         | 3.64%   |
| 2016 | 2         | 3.64%   |
| 2024 | 1         | 1.82%   |
| 2019 | 1         | 1.82%   |
| 2009 | 1         | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 55        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 49        | 87.5%   |
| Enabled  | 7         | 12.5%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 98.18%  |
| Yes  | 1         | 1.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 17        | 30.91%  |
| 3.01-4.0   | 14        | 25.45%  |
| 16.01-24.0 | 12        | 21.82%  |
| 8.01-16.0  | 6         | 10.91%  |
| 32.01-64.0 | 4         | 7.27%   |
| 2.01-3.0   | 1         | 1.82%   |
| 1.01-2.0   | 1         | 1.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 22        | 37.93%  |
| 1.01-2.0  | 22        | 37.93%  |
| 3.01-4.0  | 7         | 12.07%  |
| 4.01-8.0  | 6         | 10.34%  |
| 8.01-16.0 | 1         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 72.73%  |
| 2      | 15        | 27.27%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 63.64%  |
| Yes       | 20        | 36.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 81.82%  |
| No        | 10        | 18.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 80%     |
| No        | 11        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 9         | 16.07%  |
| Brazil       | 8         | 14.29%  |
| Germany      | 4         | 7.14%   |
| India        | 3         | 5.36%   |
| Argentina    | 3         | 5.36%   |
| Ukraine      | 2         | 3.57%   |
| Spain        | 2         | 3.57%   |
| Portugal     | 2         | 3.57%   |
| Mexico       | 2         | 3.57%   |
| Hungary      | 2         | 3.57%   |
| France       | 2         | 3.57%   |
| Australia    | 2         | 3.57%   |
| Uruguay      | 1         | 1.79%   |
| Thailand     | 1         | 1.79%   |
| South Africa | 1         | 1.79%   |
| Serbia       | 1         | 1.79%   |
| Poland       | 1         | 1.79%   |
| Netherlands  | 1         | 1.79%   |
| Jamaica      | 1         | 1.79%   |
| Indonesia    | 1         | 1.79%   |
| Hong Kong    | 1         | 1.79%   |
| Georgia      | 1         | 1.79%   |
| Czechia      | 1         | 1.79%   |
| Costa Rica   | 1         | 1.79%   |
| Colombia     | 1         | 1.79%   |
| Austria      | 1         | 1.79%   |
| Algeria      | 1         | 1.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Budapest                    | 2         | 3.57%   |
| Zaporizhzhia                | 1         | 1.79%   |
| Zapopan                     | 1         | 1.79%   |
| Wolfheze                    | 1         | 1.79%   |
| Villahermosa                | 1         | 1.79%   |
| Vienna                      | 1         | 1.79%   |
| Tuen Mun                    | 1         | 1.79%   |
| Tiete                       | 1         | 1.79%   |
| Tbilisi                     | 1         | 1.79%   |
| Surabaya                    | 1         | 1.79%   |
| Siquirres                   | 1         | 1.79%   |
| Seville                     | 1         | 1.79%   |
| Sao Jose do Rio Preto       | 1         | 1.79%   |
| San Nicolás de los Arroyos | 1         | 1.79%   |
| Salvador                    | 1         | 1.79%   |
| Ratingen                    | 1         | 1.79%   |
| Quilmes                     | 1         | 1.79%   |
| Porto                       | 1         | 1.79%   |
| Patna                       | 1         | 1.79%   |
| Paris                       | 1         | 1.79%   |
| Ostrava                     | 1         | 1.79%   |
| Nanterre                    | 1         | 1.79%   |
| Nakhon Pathom               | 1         | 1.79%   |
| Montevideo                  | 1         | 1.79%   |
| Milwaukee                   | 1         | 1.79%   |
| Midlothian                  | 1         | 1.79%   |
| Melbourne                   | 1         | 1.79%   |
| Manaus                      | 1         | 1.79%   |
| Maitland                    | 1         | 1.79%   |
| Luhansk                     | 1         | 1.79%   |
| Lisbon                      | 1         | 1.79%   |
| Lee's Summit                | 1         | 1.79%   |
| Las Vegas                   | 1         | 1.79%   |
| Krakow                      | 1         | 1.79%   |
| Kingston                    | 1         | 1.79%   |
| Johannesburg                | 1         | 1.79%   |
| Decatur                     | 1         | 1.79%   |
| Dearborn Heights            | 1         | 1.79%   |
| Charlottesville             | 1         | 1.79%   |
| Caxias                      | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 19.12%  |
| WDC                 | 8         | 8      | 11.76%  |
| Toshiba             | 8         | 8      | 11.76%  |
| Samsung Electronics | 8         | 8      | 11.76%  |
| Micron Technology   | 4         | 4      | 5.88%   |
| Unknown             | 3         | 4      | 4.41%   |
| Kingston            | 3         | 3      | 4.41%   |
| HGST                | 3         | 3      | 4.41%   |
| Crucial             | 3         | 3      | 4.41%   |
| SanDisk             | 2         | 2      | 2.94%   |
| Fujitsu             | 2         | 2      | 2.94%   |
| XrayDisk            | 1         | 1      | 1.47%   |
| WDC WDS5            | 1         | 1      | 1.47%   |
| Timetec             | 1         | 1      | 1.47%   |
| SK hynix            | 1         | 3      | 1.47%   |
| KingSpec            | 1         | 1      | 1.47%   |
| Intenso             | 1         | 1      | 1.47%   |
| Hitachi             | 1         | 1      | 1.47%   |
| Dahua               | 1         | 1      | 1.47%   |
| China               | 1         | 1      | 1.47%   |
| Apple               | 1         | 1      | 1.47%   |
| A-DATA Technology   | 1         | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 4.35%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2.9%    |
| Seagate ST9500325AS 500GB           | 2         | 2.9%    |
| Seagate ST2000LM007-1R8174 2TB      | 2         | 2.9%    |
| XrayDisk 240GB                      | 1         | 1.45%   |
| WDC WDS5 00G1B0A-00H9H0 500GB SSD   | 1         | 1.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 1.45%   |
| WDC WDS100T3X0C-00SJG0 1TB          | 1         | 1.45%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 1         | 1.45%   |
| WDC WD20SPZX-00CRAT0 2TB            | 1         | 1.45%   |
| WDC WD1200BEVS-00UST0 120GB         | 1         | 1.45%   |
| WDC WD10SPZX-75Z10T2 1TB            | 1         | 1.45%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1.45%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1.45%   |
| Unknown SD16G  16GB                 | 1         | 1.45%   |
| Unknown MMC Card  536GB             | 1         | 1.45%   |
| Unknown HAG4a2  16GB                | 1         | 1.45%   |
| Toshiba NVMe SSD Drive 256GB        | 1         | 1.45%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1.45%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1.45%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1.45%   |
| Toshiba MK7559GSXP 752GB            | 1         | 1.45%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1.45%   |
| Timetec M.2 SATA 256GB              | 1         | 1.45%   |
| SK hynix PC401 NVMe 1TB             | 1         | 1.45%   |
| SK hynix NVMe SSD Drive 1024GB      | 1         | 1.45%   |
| Seagate ST500LT015-1DJ142 500GB     | 1         | 1.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1.45%   |
| Seagate ST2000LM015-2E8174 2TB      | 1         | 1.45%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1.45%   |
| Seagate ST1000LM014-1EJ164 1TB      | 1         | 1.45%   |
| Seagate NVMe SSD Drive 250GB        | 1         | 1.45%   |
| SanDisk Ultra II 480GB SSD          | 1         | 1.45%   |
| SanDisk SSD PLUS 240GB              | 1         | 1.45%   |
| Samsung SSD 850 PRO 256GB           | 1         | 1.45%   |
| Samsung SSD 850 EVO mSATA 1TB       | 1         | 1.45%   |
| Samsung NVMe SSD Drive 512GB        | 1         | 1.45%   |
| Samsung MZVLQ256HAJD-00000 256GB    | 1         | 1.45%   |
| Samsung MZVLB1T0HBLR-00000 1TB      | 1         | 1.45%   |
| Samsung MZALQ512HALU-000L1 512GB    | 1         | 1.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 14     | 36.36%  |
| Toshiba             | 7         | 7      | 21.21%  |
| WDC                 | 6         | 6      | 18.18%  |
| HGST                | 3         | 3      | 9.09%   |
| Fujitsu             | 2         | 2      | 6.06%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| Hitachi             | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 15.79%  |
| SanDisk             | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Micron Technology   | 2         | 2      | 10.53%  |
| Crucial             | 2         | 2      | 10.53%  |
| WDC WDS5            | 1         | 1      | 5.26%   |
| WDC                 | 1         | 1      | 5.26%   |
| Timetec             | 1         | 1      | 5.26%   |
| KingSpec            | 1         | 1      | 5.26%   |
| Intenso             | 1         | 1      | 5.26%   |
| Dahua               | 1         | 1      | 5.26%   |
| China               | 1         | 1      | 5.26%   |
| A-DATA Technology   | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 31        | 35     | 48.44%  |
| SSD     | 18        | 19     | 28.13%  |
| NVMe    | 11        | 14     | 17.19%  |
| MMC     | 3         | 4      | 4.69%   |
| Unknown | 1         | 1      | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 54     | 74.14%  |
| NVMe | 11        | 14     | 18.97%  |
| MMC  | 3         | 4      | 5.17%   |
| SAS  | 1         | 1      | 1.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 31     | 58%     |
| 0.51-1.0   | 17        | 18     | 34%     |
| 1.01-2.0   | 4         | 5      | 8%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 22        | 40%     |
| 251-500    | 9         | 16.36%  |
| 501-1000   | 9         | 16.36%  |
| 51-100     | 7         | 12.73%  |
| 1001-2000  | 3         | 5.45%   |
| 1-20       | 3         | 5.45%   |
| 21-50      | 1         | 1.82%   |
| Unknown    | 1         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 27        | 47.37%  |
| 21-50     | 13        | 22.81%  |
| 101-250   | 7         | 12.28%  |
| 51-100    | 4         | 7.02%   |
| 251-500   | 3         | 5.26%   |
| 1001-2000 | 1         | 1.75%   |
| 501-1000  | 1         | 1.75%   |
| Unknown   | 1         | 1.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000LM014-1EJ164 1TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 37        | 48     | 64.91%  |
| Works    | 19        | 24     | 33.33%  |
| Malfunc  | 1         | 1      | 1.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 43        | 72.88%  |
| Samsung Electronics              | 5         | 8.47%   |
| AMD                              | 3         | 5.08%   |
| Micron Technology                | 2         | 3.39%   |
| Toshiba America Info Systems     | 1         | 1.69%   |
| SK hynix                         | 1         | 1.69%   |
| Silicon Integrated Systems [SiS] | 1         | 1.69%   |
| Seagate Technology               | 1         | 1.69%   |
| SanDisk                          | 1         | 1.69%   |
| Micron/Crucial Technology        | 1         | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 14.52%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 6.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 6.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 4.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 4.84%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 4.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 4.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 4.84%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 4.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 3.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 3.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.23%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1         | 1.61%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 1.61%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 1.61%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 1.61%   |
| Seagate FireCuda/IronWolf 510 SSD                                              | 1         | 1.61%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 1.61%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                 | 1         | 1.61%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.61%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 1         | 1.61%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 1         | 1.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.61%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.61%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 36        | 61.02%  |
| NVMe | 11        | 18.64%  |
| RAID | 9         | 15.25%  |
| IDE  | 3         | 5.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 51        | 92.73%  |
| AMD    | 4         | 7.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz       | 3         | 5.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 3.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 3.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 3.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 3.64%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 2         | 3.64%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 3.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 3.64%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz  | 1         | 1.82%   |
| Intel Pentium CPU B980 @ 2.40GHz        | 1         | 1.82%   |
| Intel Core Ultra 5 125H                 | 1         | 1.82%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 1         | 1.82%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.82%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.82%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz      | 1         | 1.82%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1.82%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 1         | 1.82%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 1.82%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 1.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.82%   |
| Intel Core i5-4310U CPU @ 2.00GHz       | 1         | 1.82%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.82%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 1         | 1.82%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 1         | 1.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 1.82%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 1         | 1.82%   |
| Intel Core i5 CPU M 540 @ 2.53GHz       | 1         | 1.82%   |
| Intel Core i3-7020U CPU @ 2.30GHz       | 1         | 1.82%   |
| Intel Core i3-5020U CPU @ 2.20GHz       | 1         | 1.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.82%   |
| Intel Core i3-4030U CPU @ 1.90GHz       | 1         | 1.82%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 1         | 1.82%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz    | 1         | 1.82%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz    | 1         | 1.82%   |
| Intel Celeron N4020C CPU @ 1.10GHz      | 1         | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 27.27%  |
| Intel Core i7           | 13        | 23.64%  |
| Intel Core i3           | 9         | 16.36%  |
| Intel Celeron           | 5         | 9.09%   |
| Other                   | 3         | 5.45%   |
| Intel Core 2 Duo        | 2         | 3.64%   |
| Intel Pentium Dual      | 1         | 1.82%   |
| Intel Pentium           | 1         | 1.82%   |
| Intel Core i9           | 1         | 1.82%   |
| Intel Core              | 1         | 1.82%   |
| Intel Celeron Dual-Core | 1         | 1.82%   |
| AMD Ryzen 9             | 1         | 1.82%   |
| AMD A8                  | 1         | 1.82%   |
| AMD A10                 | 1         | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 40        | 72.73%  |
| 4      | 9         | 16.36%  |
| 6      | 4         | 7.27%   |
| 14     | 1         | 1.82%   |
| 8      | 1         | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 55        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 44        | 80%     |
| 1      | 11        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 55        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 33.93%  |
| 0x206a7    | 6         | 10.71%  |
| 0x40651    | 4         | 7.14%   |
| 0x906ea    | 3         | 5.36%   |
| 0x806ea    | 3         | 5.36%   |
| 0x806c1    | 2         | 3.57%   |
| 0x706e5    | 2         | 3.57%   |
| 0x306d4    | 2         | 3.57%   |
| 0x306a9    | 2         | 3.57%   |
| 0x20655    | 2         | 3.57%   |
| 0x1067a    | 2         | 3.57%   |
| 0xa0652    | 1         | 1.79%   |
| 0x806e9    | 1         | 1.79%   |
| 0x6fd      | 1         | 1.79%   |
| 0x406c4    | 1         | 1.79%   |
| 0x306c3    | 1         | 1.79%   |
| 0x30678    | 1         | 1.79%   |
| 0x10676    | 1         | 1.79%   |
| 0x0a705203 | 1         | 1.79%   |
| 0x0600611a | 1         | 1.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 10        | 18.18%  |
| Haswell           | 7         | 12.73%  |
| SandyBridge       | 6         | 10.91%  |
| Westmere          | 4         | 7.27%   |
| Silvermont        | 4         | 7.27%   |
| IvyBridge         | 4         | 7.27%   |
| Broadwell         | 4         | 7.27%   |
| Penryn            | 3         | 5.45%   |
| TigerLake         | 2         | 3.64%   |
| IceLake           | 2         | 3.64%   |
| Excavator         | 2         | 3.64%   |
| Skylake           | 1         | 1.82%   |
| Piledriver        | 1         | 1.82%   |
| Meteorlake Hybrid | 1         | 1.82%   |
| Goldmont plus     | 1         | 1.82%   |
| Core              | 1         | 1.82%   |
| CometLake         | 1         | 1.82%   |
| Unknown           | 1         | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 49        | 68.06%  |
| Nvidia                           | 15        | 20.83%  |
| AMD                              | 7         | 9.72%   |
| Silicon Integrated Systems [SiS] | 1         | 1.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 8%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 6.67%   |
| Intel HD Graphics 5500                                                                   | 4         | 5.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 5.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 5.33%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 4%      |
| Intel UHD Graphics 620                                                                   | 3         | 4%      |
| Intel HD Graphics 620                                                                    | 3         | 4%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 4%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 4%      |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 2.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 2.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 1.33%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 1.33%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 1.33%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.33%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                               | 1         | 1.33%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.33%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.33%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1.33%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.33%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.33%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                                 | 1         | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.33%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.33%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.33%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 1         | 1.33%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.33%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.33%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 58.18%  |
| Intel + Nvidia | 14        | 25.45%  |
| Intel + AMD    | 3         | 5.45%   |
| 2 x AMD        | 2         | 3.64%   |
| 1 x AMD        | 2         | 3.64%   |
| 1 x SiS        | 1         | 1.82%   |
| 1 x Nvidia     | 1         | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 43        | 76.79%  |
| Proprietary | 9         | 16.07%  |
| Unknown     | 4         | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 69.64%  |
| 3.01-4.0   | 6         | 10.71%  |
| 1.01-2.0   | 6         | 10.71%  |
| 0.51-1.0   | 2         | 3.57%   |
| 7.01-8.0   | 1         | 1.79%   |
| 2.01-3.0   | 1         | 1.79%   |
| 0.01-0.5   | 1         | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 15        | 24.59%  |
| BOE                     | 11        | 18.03%  |
| LG Display              | 10        | 16.39%  |
| AU Optronics            | 10        | 16.39%  |
| JDI                     | 2         | 3.28%   |
| Chimei Innolux          | 2         | 3.28%   |
| Chi Mei Optoelectronics | 2         | 3.28%   |
| Sharp                   | 1         | 1.64%   |
| MSI                     | 1         | 1.64%   |
| Lenovo                  | 1         | 1.64%   |
| InfoVision              | 1         | 1.64%   |
| Hewlett-Packard         | 1         | 1.64%   |
| Goldstar                | 1         | 1.64%   |
| Eizo                    | 1         | 1.64%   |
| AOC                     | 1         | 1.64%   |
| Ancor Communications    | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 3.17%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                    | 2         | 3.17%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 1.59%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch        | 1         | 1.59%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch        | 1         | 1.59%   |
| Samsung Electronics S27E500 SAM0D0D 1920x1080 598x336mm 27.0-inch        | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC419D 2880x1800 302x189mm 14.0-inch    | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC344A 1366x768 344x194mm 15.5-inch     | 1         | 1.59%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                  | 1         | 1.59%   |
| LG Display LCD Monitor LGD0611 1920x1080 382x215mm 17.3-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD037C 1366x768 310x174mm 14.0-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD024F 1280x800 260x160mm 12.0-inch              | 1         | 1.59%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.59%   |
| InfoVision LCD Monitor IVO057C 1366x768 309x174mm 14.0-inch              | 1         | 1.59%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch               | 1         | 1.59%   |
| Goldstar M2380A GSM57EE 1920x1080 509x286mm 23.0-inch                    | 1         | 1.59%   |
| Eizo EV2450 ENC2532 1920x1080 528x297mm 23.9-inch                        | 1         | 1.59%   |
| Eizo EV2450 ENC2531 1920x1080 528x297mm 23.9-inch                        | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1489 1366x768 309x174mm 14.0-inch          | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1469 1366x768 309x174mm 14.0-inch | 1         | 1.59%   |
| BOE LCD Monitor BOE0B09 1920x1080 309x174mm 14.0-inch                    | 1         | 1.59%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 27        | 44.26%  |
| 1920x1080 (FHD)  | 21        | 34.43%  |
| 3000x2000        | 2         | 3.28%   |
| 2880x1800        | 2         | 3.28%   |
| 1600x900 (HD+)   | 2         | 3.28%   |
| 1440x900 (WXGA+) | 2         | 3.28%   |
| 1280x800 (WXGA)  | 2         | 3.28%   |
| 3840x2160 (4K)   | 1         | 1.64%   |
| 3440x1440        | 1         | 1.64%   |
| 2256x1504        | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 28        | 45.16%  |
| 14     | 13        | 20.97%  |
| 13     | 5         | 8.06%   |
| 17     | 4         | 6.45%   |
| 12     | 3         | 4.84%   |
| 24     | 2         | 3.23%   |
| 23     | 2         | 3.23%   |
| 34     | 1         | 1.61%   |
| 31     | 1         | 1.61%   |
| 27     | 1         | 1.61%   |
| 21     | 1         | 1.61%   |
| 19     | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 64.52%  |
| 201-300     | 7         | 11.29%  |
| 351-400     | 6         | 9.68%   |
| 501-600     | 5         | 8.06%   |
| 401-500     | 2         | 3.23%   |
| 701-800     | 1         | 1.61%   |
| 601-700     | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 47        | 81.03%  |
| 16/10 | 6         | 10.34%  |
| 3/2   | 4         | 6.9%    |
| 21/9  | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 45.16%  |
| 81-90          | 17        | 27.42%  |
| 201-250        | 5         | 8.06%   |
| 121-130        | 4         | 6.45%   |
| 71-80          | 2         | 3.23%   |
| 61-70          | 2         | 3.23%   |
| 351-500        | 2         | 3.23%   |
| 301-350        | 1         | 1.61%   |
| 151-200        | 1         | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 28        | 45.9%   |
| 121-160       | 18        | 29.51%  |
| 51-100        | 9         | 14.75%  |
| More than 240 | 4         | 6.56%   |
| 161-240       | 2         | 3.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 80%     |
| 2     | 8         | 14.55%  |
| 0     | 2         | 3.64%   |
| 3     | 1         | 1.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 27        | 31.03%  |
| Intel                            | 27        | 31.03%  |
| Qualcomm Atheros                 | 16        | 18.39%  |
| Broadcom                         | 6         | 6.9%    |
| Ralink                           | 2         | 2.3%    |
| Xiaomi                           | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] | 1         | 1.15%   |
| Ralink Technology                | 1         | 1.15%   |
| MediaTek                         | 1         | 1.15%   |
| Marvell Technology Group         | 1         | 1.15%   |
| Hewlett-Packard                  | 1         | 1.15%   |
| Dell                             | 1         | 1.15%   |
| Broadcom Limited                 | 1         | 1.15%   |
| ASUSTek Computer                 | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 15        | 14.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 6.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 3.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 3.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 2.86%   |
| Intel Wireless 7265                                                     | 3         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 2.86%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.9%    |
| Intel Wireless 3160                                                     | 2         | 1.9%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1.9%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.9%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.95%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.95%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.95%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 1         | 0.95%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.95%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.95%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.95%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 0.95%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.95%   |
| Intel Wireless 8260                                                     | 1         | 0.95%   |
| Intel Wireless 7260                                                     | 1         | 0.95%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 0.95%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.95%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.95%   |
| Intel Meteor Lake PCH CNVi WiFi                                         | 1         | 0.95%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 43.1%   |
| Qualcomm Atheros      | 13        | 22.41%  |
| Realtek Semiconductor | 8         | 13.79%  |
| Broadcom              | 5         | 8.62%   |
| Ralink                | 2         | 3.45%   |
| Ralink Technology     | 1         | 1.72%   |
| MediaTek              | 1         | 1.72%   |
| Dell                  | 1         | 1.72%   |
| Broadcom Limited      | 1         | 1.72%   |
| ASUSTek Computer      | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 8.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 6.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 5.17%   |
| Intel Wireless 7265                                                     | 3         | 5.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 5.17%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 3.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 3.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.45%   |
| Intel Wireless 3160                                                     | 2         | 3.45%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 3.45%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 3.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.72%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.72%   |
| Intel Wireless 8260                                                     | 1         | 1.72%   |
| Intel Wireless 7260                                                     | 1         | 1.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 1.72%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.72%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.72%   |
| Intel Meteor Lake PCH CNVi WiFi                                         | 1         | 1.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.72%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.72%   |
| Dell Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card          | 1         | 1.72%   |
| Broadcom Limited BCM4311 802.11a/b/g                                    | 1         | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.72%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]     | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 25        | 54.35%  |
| Intel                            | 10        | 21.74%  |
| Qualcomm Atheros                 | 6         | 13.04%  |
| Broadcom                         | 2         | 4.35%   |
| Xiaomi                           | 1         | 2.17%   |
| Silicon Integrated Systems [SiS] | 1         | 2.17%   |
| Marvell Technology Group         | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15        | 32.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 15.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 8.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 6.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 2.17%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 2.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 2.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 2.17%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 2.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 2.17%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 2.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 2.17%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 2.17%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 2.17%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 2.17%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.17%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 2.17%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 2.17%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 2.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 2.17%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 2.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 54.46%  |
| Ethernet | 45        | 44.55%  |
| Modem    | 1         | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 77.78%  |
| Ethernet | 14        | 22.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 42        | 76.36%  |
| 1     | 13        | 23.64%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 81.82%  |
| Yes  | 10        | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 40.91%  |
| Qualcomm Atheros Communications | 6         | 13.64%  |
| Realtek Semiconductor           | 5         | 11.36%  |
| IMC Networks                    | 4         | 9.09%   |
| Broadcom                        | 3         | 6.82%   |
| Dell                            | 2         | 4.55%   |
| Toshiba                         | 1         | 2.27%   |
| Ralink Technology               | 1         | 2.27%   |
| Ralink                          | 1         | 2.27%   |
| Hewlett-Packard                 | 1         | 2.27%   |
| Foxconn / Hon Hai               | 1         | 2.27%   |
| Cambridge Silicon Radio         | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 20.45%  |
| Realtek Bluetooth Radio                             | 3         | 6.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 6.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 6.82%   |
| IMC Networks Bluetooth Radio                        | 3         | 6.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 4.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 4.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 4.55%   |
| Intel AX201 Bluetooth                               | 2         | 4.55%   |
| Toshiba Bluetooth Device                            | 1         | 2.27%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 2.27%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.27%   |
| Intel AX211 Bluetooth                               | 1         | 2.27%   |
| Intel AX210 Bluetooth                               | 1         | 2.27%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 2.27%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.27%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.27%   |
| Dell Wireless 355 Bluetooth                         | 1         | 2.27%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.27%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.27%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 2.27%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 50        | 79.37%  |
| Nvidia                                          | 4         | 6.35%   |
| AMD                                             | 4         | 6.35%   |
| Silicon Integrated Systems [SiS]                | 1         | 1.59%   |
| Realtek Semiconductor                           | 1         | 1.59%   |
| Razer USA                                       | 1         | 1.59%   |
| Logitech                                        | 1         | 1.59%   |
| Licensed by Sony Computer Entertainment America | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 8.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 6.41%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 6.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 6.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 6.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 5.13%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 5.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 5.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 3.85%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.56%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.28%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 1.28%   |
| Razer USA Kraken 7.1 V2                                                                           | 1         | 1.28%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.28%   |
| Logitech Speaker Lapdesk N700                                                                     | 1         | 1.28%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset                           | 1         | 1.28%   |
| Intel Meteor Lake-P HD Audio Controller                                                           | 1         | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.28%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.28%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.28%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.28%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.28%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 1         | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 34.38%  |
| SK hynix            | 7         | 21.88%  |
| Micron Technology   | 6         | 18.75%  |
| Kingston            | 2         | 6.25%   |
| Unknown (ABCD)      | 1         | 3.13%   |
| Unknown (2C0B)      | 1         | 3.13%   |
| Teikon              | 1         | 3.13%   |
| Ramaxel Technology  | 1         | 3.13%   |
| Elpida              | 1         | 3.13%   |
| Crucial             | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 6.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 3.13%   |
| Unknown (2C0B) RAM Module 16GB SODIMM DDR4 2133MT/s              | 1         | 3.13%   |
| Teikon RAM TMT251S6CFR8C-PBHC 4096MB SODIMM DDR3 1600MT/s        | 1         | 3.13%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 3.13%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 3.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s              | 1         | 3.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 3.13%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 3.13%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 1         | 3.13%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 3.13%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 3.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 3.13%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 3.13%   |
| Ramaxel RAM RMSA3270MB86H9F2400 4GB SODIMM DDR4 2400MT/s         | 1         | 3.13%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s       | 1         | 3.13%   |
| Micron RAM MT62F2G32D4DS-026 4GB Row Of Chips LPDDR5 7467MT/s    | 1         | 3.13%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 3.13%   |
| Micron RAM 8ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2400MT/s             | 1         | 3.13%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 3.13%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 1         | 3.13%   |
| Kingston RAM KHX2133C13S4/4G 4GB SODIMM DDR4 2133MT/s            | 1         | 3.13%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s         | 1         | 3.13%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 3.13%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 11        | 44%     |
| DDR3   | 9         | 36%     |
| LPDDR5 | 2         | 8%      |
| LPDDR3 | 2         | 8%      |
| LPDDR4 | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 22        | 88%     |
| Row Of Chips | 2         | 8%      |
| Unknown      | 1         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 11        | 40.74%  |
| 4096  | 9         | 33.33%  |
| 16384 | 5         | 18.52%  |
| 2048  | 2         | 7.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 10        | 35.71%  |
| 2667  | 5         | 17.86%  |
| 2400  | 4         | 14.29%  |
| 3200  | 3         | 10.71%  |
| 2133  | 3         | 10.71%  |
| 7500  | 1         | 3.57%   |
| 7467  | 1         | 3.57%   |
| 1334  | 1         | 3.57%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 13        | 26.53%  |
| Microdia                      | 6         | 12.24%  |
| Suyin                         | 4         | 8.16%   |
| Sunplus Innovation Technology | 4         | 8.16%   |
| Realtek Semiconductor         | 3         | 6.12%   |
| Quanta                        | 3         | 6.12%   |
| IMC Networks                  | 3         | 6.12%   |
| Silicon Motion                | 2         | 4.08%   |
| Bison Electronics             | 2         | 4.08%   |
| Acer                          | 2         | 4.08%   |
| Syntek                        | 1         | 2.04%   |
| Shinetech                     | 1         | 2.04%   |
| Luxvisions Innotech Limited   | 1         | 2.04%   |
| Lite-On Technology            | 1         | 2.04%   |
| kingcome                      | 1         | 2.04%   |
| Importek                      | 1         | 2.04%   |
| Alcor Micro                   | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                          | 2         | 4.08%   |
| Microdia Integrated_Webcam_HD                                         | 2         | 4.08%   |
| Microdia Integrated Webcam                                            | 2         | 4.08%   |
| Chicony HP Webcam                                                     | 2         | 4.08%   |
| Syntek Lenovo EasyCamera                                              | 1         | 2.04%   |
| Suyin WebCam                                                          | 1         | 2.04%   |
| Suyin HP Truevision HD                                                | 1         | 2.04%   |
| Suyin Asus Integrated Webcam                                          | 1         | 2.04%   |
| Suyin 1.3M HD WebCam                                                  | 1         | 2.04%   |
| Sunplus Laptop_Integrated_Webcam_HD                                   | 1         | 2.04%   |
| Sunplus HD WebCam                                                     | 1         | 2.04%   |
| Silicon Motion WebCam SC-13HDL11939N                                  | 1         | 2.04%   |
| Silicon Motion HP Webcam-101 Integrated Camera                        | 1         | 2.04%   |
| Shinetech USB2.0 FHD UVC WebCam                                       | 1         | 2.04%   |
| Realtek USB2.0 VGA UVC WebCam                                         | 1         | 2.04%   |
| Realtek Laptop Camera                                                 | 1         | 2.04%   |
| Realtek HP Truevision HD                                              | 1         | 2.04%   |
| Quanta Laptop_Integrated_Webcam_2HDM                                  | 1         | 2.04%   |
| Quanta HP TrueVision HD Camera                                        | 1         | 2.04%   |
| Quanta HD Webcam                                                      | 1         | 2.04%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam                        | 1         | 2.04%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 2.04%   |
| Luxvisions Innotech Limited Integrated RGB Camera                     | 1         | 2.04%   |
| Lite-On HP HD Webcam                                                  | 1         | 2.04%   |
| kingcome HD Camera                                                    | 1         | 2.04%   |
| Importek HP Truevision HD Integrated Webcam                           | 1         | 2.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                                    | 1         | 2.04%   |
| IMC Networks USB2.0 UVC HD Webcam                                     | 1         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 1         | 2.04%   |
| Chicony USB2.0 VGA UVC WebCam                                         | 1         | 2.04%   |
| Chicony USB 2.0 Camera                                                | 1         | 2.04%   |
| Chicony TOSHIBA Web Camera - HD                                       | 1         | 2.04%   |
| Chicony Lenovo EasyCamera                                             | 1         | 2.04%   |
| Chicony Integrated HP HD Webcam                                       | 1         | 2.04%   |
| Chicony Integrated Camera                                             | 1         | 2.04%   |
| Chicony HP Wide Vision HD Camera                                      | 1         | 2.04%   |
| Chicony HP Webcam [2 MP Macro]                                        | 1         | 2.04%   |
| Chicony HP HD Camera                                                  | 1         | 2.04%   |
| Chicony HD WebCam                                                     | 1         | 2.04%   |
| Chicony EasyCamera                                                    | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 71.43%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |
| AuthenTec                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 2         | 28.57%  |
| Validity Sensors Fingerprint scanner       | 2         | 28.57%  |
| Validity Sensors VFS491                    | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device        | 1         | 14.29%  |
| AuthenTec AES2810                          | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 66.67%  |
| Upek     | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 66.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 38        | 69.09%  |
| 1     | 14        | 25.45%  |
| 2     | 3         | 5.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 7         | 38.89%  |
| Graphics card      | 5         | 27.78%  |
| Chipcard           | 3         | 16.67%  |
| Network            | 1         | 5.56%   |
| Net/ethernet       | 1         | 5.56%   |
| Bluetooth          | 1         | 5.56%   |

