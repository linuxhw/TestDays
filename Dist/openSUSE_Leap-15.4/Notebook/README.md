openSUSE Leap-15.4 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 96

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Sony          | VPCEH25EN                   | [2b47c1b9a5](https://linux-hardware.org/?probe=2b47c1b9a5) | Jun 05, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a8baa03316](https://linux-hardware.org/?probe=a8baa03316) | Jun 03, 2023 |
| Acer          | Nitro AN517-54              | [4feb3e3196](https://linux-hardware.org/?probe=4feb3e3196) | May 27, 2023 |
| Dell          | Latitude 5320               | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| Lenovo        | ThinkPad W541 20EF001UGE    | [29c8170a0e](https://linux-hardware.org/?probe=29c8170a0e) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| ASUSTek       | N750JV                      | [3ec3c7aa7b](https://linux-hardware.org/?probe=3ec3c7aa7b) | Apr 26, 2023 |
| ASUSTek       | N750JV                      | [53c0f79af9](https://linux-hardware.org/?probe=53c0f79af9) | Apr 26, 2023 |
| Gateway       | NV55C                       | [e77192c3b1](https://linux-hardware.org/?probe=e77192c3b1) | Apr 20, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [69b2b1c95f](https://linux-hardware.org/?probe=69b2b1c95f) | Apr 19, 2023 |
| HP            | Mini 210-1000               | [e8b0b26e10](https://linux-hardware.org/?probe=e8b0b26e10) | Apr 15, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [19fd2b6d0d](https://linux-hardware.org/?probe=19fd2b6d0d) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [bc402eee2e](https://linux-hardware.org/?probe=bc402eee2e) | Apr 09, 2023 |
| HP            | EliteBook 865 16 inch G9... | [6906a8d309](https://linux-hardware.org/?probe=6906a8d309) | Apr 03, 2023 |
| ASUSTek       | N550JX                      | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| Fujitsu       | LIFEBOOK U938               | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| HP            | Compaq 6730s                | [8d4cea5a81](https://linux-hardware.org/?probe=8d4cea5a81) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| Packard Be... | EasyNote TE11HC             | [6c942c5a39](https://linux-hardware.org/?probe=6c942c5a39) | Mar 26, 2023 |
| Lenovo        | ThinkPad Edge E530 3259H... | [74348d01f3](https://linux-hardware.org/?probe=74348d01f3) | Mar 13, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | [fac1ee2528](https://linux-hardware.org/?probe=fac1ee2528) | Mar 12, 2023 |
| Jumper        | EZbook                      | [ed607c4113](https://linux-hardware.org/?probe=ed607c4113) | Mar 11, 2023 |
| Samsung       | 550XDA                      | [0c3e0dd389](https://linux-hardware.org/?probe=0c3e0dd389) | Feb 13, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [9b92561723](https://linux-hardware.org/?probe=9b92561723) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [8d7c1dbf4d](https://linux-hardware.org/?probe=8d7c1dbf4d) | Jan 30, 2023 |
| Toshiba       | Satellite L500              | [327e2d4e3e](https://linux-hardware.org/?probe=327e2d4e3e) | Jan 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [31698019a3](https://linux-hardware.org/?probe=31698019a3) | Jan 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [004b2669ef](https://linux-hardware.org/?probe=004b2669ef) | Jan 18, 2023 |
| HP            | ProBook 4540s               | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| HP            | ProBook 4540s               | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [9b874af8a4](https://linux-hardware.org/?probe=9b874af8a4) | Jan 16, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [a5ea710efd](https://linux-hardware.org/?probe=a5ea710efd) | Jan 11, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [b68fa80860](https://linux-hardware.org/?probe=b68fa80860) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [60989ad0c4](https://linux-hardware.org/?probe=60989ad0c4) | Dec 31, 2022 |
| Dell          | Inspiron 15 7510            | [d5702b0c66](https://linux-hardware.org/?probe=d5702b0c66) | Dec 24, 2022 |
| Dell          | Vostro 3501                 | [8a3788aa78](https://linux-hardware.org/?probe=8a3788aa78) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | [258dc5c40d](https://linux-hardware.org/?probe=258dc5c40d) | Dec 23, 2022 |
| Schenker      | VIA 15 Pro                  | [b1a40c91d2](https://linux-hardware.org/?probe=b1a40c91d2) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | [75efe6fb52](https://linux-hardware.org/?probe=75efe6fb52) | Dec 22, 2022 |
| Acer          | Aspire E1-572G              | [adc5196d64](https://linux-hardware.org/?probe=adc5196d64) | Dec 17, 2022 |
| ASUSTek       | Z450LA                      | [ffd2220d21](https://linux-hardware.org/?probe=ffd2220d21) | Nov 25, 2022 |
| Dell          | Latitude E5570              | [ed2e9cfb4f](https://linux-hardware.org/?probe=ed2e9cfb4f) | Nov 24, 2022 |
| Lenovo        | ThinkPad T530 2394D56       | [3d44b768e5](https://linux-hardware.org/?probe=3d44b768e5) | Nov 12, 2022 |
| HP            | ZBook 17                    | [e866fa1319](https://linux-hardware.org/?probe=e866fa1319) | Nov 09, 2022 |
| HP            | ZBook 17                    | [af26e94623](https://linux-hardware.org/?probe=af26e94623) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dcd40f9f78](https://linux-hardware.org/?probe=dcd40f9f78) | Oct 28, 2022 |
| Dell          | Latitude 9420               | [a601281b46](https://linux-hardware.org/?probe=a601281b46) | Oct 27, 2022 |
| HP            | ZBook 17                    | [6dc9848327](https://linux-hardware.org/?probe=6dc9848327) | Oct 20, 2022 |
| Toshiba       | Satellite P55t-A            | [60d52e85a0](https://linux-hardware.org/?probe=60d52e85a0) | Oct 12, 2022 |
| ASUSTek       | F3Sv                        | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [33a0cb05e8](https://linux-hardware.org/?probe=33a0cb05e8) | Oct 04, 2022 |
| Dell          | Vostro 3560                 | [79f922d367](https://linux-hardware.org/?probe=79f922d367) | Oct 02, 2022 |
| Dell          | Vostro 3560                 | [59c14fb5c0](https://linux-hardware.org/?probe=59c14fb5c0) | Oct 02, 2022 |
| Dell          | Latitude E5250              | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| HP            | ZBook 17 G2                 | [d6d9af3173](https://linux-hardware.org/?probe=d6d9af3173) | Sep 26, 2022 |
| HP            | ZBook 17 G2                 | [ff70118578](https://linux-hardware.org/?probe=ff70118578) | Sep 26, 2022 |
| Dell          | Inspiron 5515               | [a7f0e24464](https://linux-hardware.org/?probe=a7f0e24464) | Sep 20, 2022 |
| Dell          | Inspiron 3542               | [7f7ef47d4b](https://linux-hardware.org/?probe=7f7ef47d4b) | Sep 20, 2022 |
| ASUSTek       | X55CR                       | [43b77d436c](https://linux-hardware.org/?probe=43b77d436c) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| HP            | ZBook 17                    | [98e643f5af](https://linux-hardware.org/?probe=98e643f5af) | Aug 30, 2022 |
| Google        | Eldrid                      | [6a0c6eb1de](https://linux-hardware.org/?probe=6a0c6eb1de) | Aug 27, 2022 |
| Notebook      | NLx0MU                      | [0e2658915d](https://linux-hardware.org/?probe=0e2658915d) | Aug 17, 2022 |
| HP            | Pavilion Notebook           | [a05b95b836](https://linux-hardware.org/?probe=a05b95b836) | Aug 15, 2022 |
| HP            | Pavilion Notebook           | [aea2bfde6a](https://linux-hardware.org/?probe=aea2bfde6a) | Aug 15, 2022 |
| Acer          | Aspire 4732Z                | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Unknown       | Unknown                     | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Unknown       | Unknown                     | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| Notebook      | NLx0MU                      | [7cb795f428](https://linux-hardware.org/?probe=7cb795f428) | Jul 22, 2022 |
| Toshiba       | Satellite L500              | [5ac3a7aa95](https://linux-hardware.org/?probe=5ac3a7aa95) | Jul 17, 2022 |
| Dell          | Inspiron 5584               | [b6d23c8307](https://linux-hardware.org/?probe=b6d23c8307) | Jul 16, 2022 |
| Multilaser    | PC150                       | [b6fcf6d507](https://linux-hardware.org/?probe=b6fcf6d507) | Jul 04, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [bec2a7697f](https://linux-hardware.org/?probe=bec2a7697f) | Jun 30, 2022 |
| Acer          | Swift SFX14-41G             | [c3c9ce7e40](https://linux-hardware.org/?probe=c3c9ce7e40) | Jun 23, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [ff63b72fd2](https://linux-hardware.org/?probe=ff63b72fd2) | Jun 19, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [3ec9bac70f](https://linux-hardware.org/?probe=3ec9bac70f) | Jun 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [cc0719c813](https://linux-hardware.org/?probe=cc0719c813) | Jun 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [52276b3971](https://linux-hardware.org/?probe=52276b3971) | Jun 16, 2022 |
| HP            | Laptop 15s-eq0xxx           | [74770880f9](https://linux-hardware.org/?probe=74770880f9) | Jun 15, 2022 |
| HP            | Mini 210-1000               | [8746b5b684](https://linux-hardware.org/?probe=8746b5b684) | Jun 10, 2022 |
| Toshiba       | Satellite L500              | [b4b4831c86](https://linux-hardware.org/?probe=b4b4831c86) | Jun 05, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [aae8744a5c](https://linux-hardware.org/?probe=aae8744a5c) | May 31, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [0f70996b58](https://linux-hardware.org/?probe=0f70996b58) | May 15, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| Samsung       | 550XDA                      | [a616d83a41](https://linux-hardware.org/?probe=a616d83a41) | May 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV0C     | [4ce87e4da1](https://linux-hardware.org/?probe=4ce87e4da1) | May 04, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [584ec1055a](https://linux-hardware.org/?probe=584ec1055a) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | [2e4fdc00b2](https://linux-hardware.org/?probe=2e4fdc00b2) | May 03, 2022 |
| LG Electro... | C400-G.BC22P1               | [652cd5fc07](https://linux-hardware.org/?probe=652cd5fc07) | Apr 06, 2022 |
| LG Electro... | C400-G.BC22P1               | [fb656318f6](https://linux-hardware.org/?probe=fb656318f6) | Feb 27, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [af586bb69e](https://linux-hardware.org/?probe=af586bb69e) | Feb 05, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.21-150400.22-default    | 12        | 16.67%  |
| 5.14.21-150400.24.21-default | 9         | 12.5%   |
| 5.14.21-150400.24.38-default | 8         | 11.11%  |
| 5.14.21-150400.24.46-default | 7         | 9.72%   |
| 5.14.21-150400.24.41-default | 5         | 6.94%   |
| 5.14.21-150400.24.63-default | 4         | 5.56%   |
| 5.14.21-150400.24.33-default | 4         | 5.56%   |
| 5.14.21-150400.24.18-default | 4         | 5.56%   |
| 5.14.21-150400.19-default    | 4         | 5.56%   |
| 5.14.21-150400.24.60-default | 3         | 4.17%   |
| 5.14.21-150400.24.55-default | 3         | 4.17%   |
| 5.14.21-150400.24.11-default | 3         | 4.17%   |
| 5.14.21-150400.24.28-default | 2         | 2.78%   |
| 6.3.5-lp154.6-default        | 1         | 1.39%   |
| 5.14.21-150400.9-default     | 1         | 1.39%   |
| 5.14.21-150400.3-default     | 1         | 1.39%   |
| 5.14.21-150400.15-default    | 1         | 1.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.21 | 62        | 98.41%  |
| 6.3.5   | 1         | 1.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 62        | 98.41%  |
| 6.3     | 1         | 1.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 63        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 46        | 73.02%  |
| GNOME      | 6         | 9.52%   |
| XFCE       | 3         | 4.76%   |
| Cinnamon   | 2         | 3.17%   |
| Unknown    | 2         | 3.17%   |
| X-Cinnamon | 1         | 1.59%   |
| LXDE       | 1         | 1.59%   |
| ICEWM      | 1         | 1.59%   |
| Deepin     | 1         | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 53        | 82.81%  |
| Wayland | 8         | 12.5%   |
| Tty     | 3         | 4.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 25        | 39.68%  |
| Unknown | 25        | 39.68%  |
| LightDM | 10        | 15.87%  |
| XDM     | 3         | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 21        | 33.33%  |
| de_DE | 13        | 20.63%  |
| pt_BR | 9         | 14.29%  |
| POSIX | 5         | 7.94%   |
| es_ES | 3         | 4.76%   |
| ru_RU | 2         | 3.17%   |
| nn_NO | 2         | 3.17%   |
| it_IT | 2         | 3.17%   |
| en_GB | 2         | 3.17%   |
| nl_NL | 1         | 1.59%   |
| hu_HU | 1         | 1.59%   |
| fr_FR | 1         | 1.59%   |
| en_IN | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 33        | 52.38%  |
| EFI  | 30        | 47.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 47        | 74.6%   |
| Ext4  | 11        | 17.46%  |
| Xfs   | 5         | 7.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 36        | 57.14%  |
| Unknown | 25        | 39.68%  |
| MBR     | 2         | 3.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 92.06%  |
| Yes       | 5         | 7.94%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 85.71%  |
| Yes       | 9         | 14.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 25.4%   |
| Hewlett-Packard     | 11        | 17.46%  |
| Dell                | 9         | 14.29%  |
| ASUSTek Computer    | 6         | 9.52%   |
| Acer                | 4         | 6.35%   |
| Toshiba             | 2         | 3.17%   |
| Samsung Electronics | 2         | 3.17%   |
| Fujitsu             | 2         | 3.17%   |
| Unknown             | 2         | 3.17%   |
| TUXEDO              | 1         | 1.59%   |
| Sony                | 1         | 1.59%   |
| Schenker            | 1         | 1.59%   |
| Notebook            | 1         | 1.59%   |
| Multilaser          | 1         | 1.59%   |
| MSI                 | 1         | 1.59%   |
| LG Electronics      | 1         | 1.59%   |
| Jumper              | 1         | 1.59%   |
| Gateway             | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung 550XDA                           | 2         | 3.17%   |
| Unknown                                  | 2         | 3.17%   |
| TUXEDO InfinityBook S 15/17 Gen7         | 1         | 1.59%   |
| Toshiba Satellite P55t-A                 | 1         | 1.59%   |
| Toshiba Satellite L500                   | 1         | 1.59%   |
| Sony VPCEH25EN                           | 1         | 1.59%   |
| Schenker VIA 15 Pro                      | 1         | 1.59%   |
| Notebook NLx0MU                          | 1         | 1.59%   |
| Multilaser PC150                         | 1         | 1.59%   |
| MSI Delta 15 A5EFK                       | 1         | 1.59%   |
| LG C400-G.BC22P1                         | 1         | 1.59%   |
| Lenovo V15-ADA 82C7                      | 1         | 1.59%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDS3B600 | 1         | 1.59%   |
| Lenovo ThinkPad W541 20EF001UGE          | 1         | 1.59%   |
| Lenovo ThinkPad T530 2394D56             | 1         | 1.59%   |
| Lenovo ThinkPad T520 42435GG             | 1         | 1.59%   |
| Lenovo ThinkPad T495s 20QJ0012UK         | 1         | 1.59%   |
| Lenovo ThinkPad T470 20HES0FW00          | 1         | 1.59%   |
| Lenovo ThinkPad T410 25223FG             | 1         | 1.59%   |
| Lenovo ThinkPad T16 Gen 1 21BVCTO1WW     | 1         | 1.59%   |
| Lenovo ThinkPad P50 20EQS0VV0C           | 1         | 1.59%   |
| Lenovo ThinkPad P16s Gen 1 21BT000MUK    | 1         | 1.59%   |
| Lenovo ThinkPad Edge E530 3259HHG        | 1         | 1.59%   |
| Lenovo ThinkPad Edge E431 62779XP        | 1         | 1.59%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 1         | 1.59%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG     | 1         | 1.59%   |
| Lenovo IdeaPad 330-15IKB 81FD            | 1         | 1.59%   |
| Jumper EZbook                            | 1         | 1.59%   |
| HP ZBook 17 G2                           | 1         | 1.59%   |
| HP ZBook 17                              | 1         | 1.59%   |
| HP Victus by Laptop 16-e0xxx             | 1         | 1.59%   |
| HP ProBook 455 G8 Notebook PC            | 1         | 1.59%   |
| HP ProBook 4540s                         | 1         | 1.59%   |
| HP Pavilion Notebook                     | 1         | 1.59%   |
| HP Mini 210-1000                         | 1         | 1.59%   |
| HP Laptop 15s-eq0xxx                     | 1         | 1.59%   |
| HP EliteBook 865 16 inch G9 Notebook PC  | 1         | 1.59%   |
| HP EliteBook 840 G8 Notebook PC          | 1         | 1.59%   |
| HP Compaq 6730s                          | 1         | 1.59%   |
| Gateway NV55C                            | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 12        | 19.05%  |
| Dell Inspiron       | 4         | 6.35%   |
| Lenovo IdeaPad      | 3         | 4.76%   |
| Dell Latitude       | 3         | 4.76%   |
| Toshiba Satellite   | 2         | 3.17%   |
| Samsung 550XDA      | 2         | 3.17%   |
| HP ZBook            | 2         | 3.17%   |
| HP ProBook          | 2         | 3.17%   |
| HP EliteBook        | 2         | 3.17%   |
| Fujitsu LIFEBOOK    | 2         | 3.17%   |
| Dell Vostro         | 2         | 3.17%   |
| Acer Aspire         | 2         | 3.17%   |
| Unknown             | 2         | 3.17%   |
| TUXEDO InfinityBook | 1         | 1.59%   |
| Sony VPCEH25EN      | 1         | 1.59%   |
| Schenker VIA        | 1         | 1.59%   |
| Notebook NLx0MU     | 1         | 1.59%   |
| Multilaser PC150    | 1         | 1.59%   |
| MSI Delta           | 1         | 1.59%   |
| LG C400-G.BC22P1    | 1         | 1.59%   |
| Lenovo V15-ADA      | 1         | 1.59%   |
| Jumper EZbook       | 1         | 1.59%   |
| HP Victus           | 1         | 1.59%   |
| HP Pavilion         | 1         | 1.59%   |
| HP Mini             | 1         | 1.59%   |
| HP Laptop           | 1         | 1.59%   |
| HP Compaq           | 1         | 1.59%   |
| Gateway NV55C       | 1         | 1.59%   |
| ASUS Z450LA         | 1         | 1.59%   |
| ASUS X55CR          | 1         | 1.59%   |
| ASUS ROG            | 1         | 1.59%   |
| ASUS N750JV         | 1         | 1.59%   |
| ASUS N550JX         | 1         | 1.59%   |
| ASUS F3Sv           | 1         | 1.59%   |
| Acer Swift          | 1         | 1.59%   |
| Acer Nitro          | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 16        | 25.4%   |
| 2019 | 7         | 11.11%  |
| 2012 | 5         | 7.94%   |
| 2022 | 4         | 6.35%   |
| 2020 | 4         | 6.35%   |
| 2015 | 4         | 6.35%   |
| 2014 | 4         | 6.35%   |
| 2013 | 4         | 6.35%   |
| 2009 | 4         | 6.35%   |
| 2018 | 3         | 4.76%   |
| 2011 | 3         | 4.76%   |
| 2017 | 1         | 1.59%   |
| 2016 | 1         | 1.59%   |
| 2010 | 1         | 1.59%   |
| 2008 | 1         | 1.59%   |
| 2007 | 1         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 63        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 53        | 84.13%  |
| Enabled  | 10        | 15.87%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 14        | 22.22%  |
| 3.01-4.0    | 13        | 20.63%  |
| 16.01-24.0  | 10        | 15.87%  |
| 8.01-16.0   | 10        | 15.87%  |
| 32.01-64.0  | 7         | 11.11%  |
| 64.01-256.0 | 3         | 4.76%   |
| 24.01-32.0  | 2         | 3.17%   |
| 2.01-3.0    | 2         | 3.17%   |
| 1.01-2.0    | 1         | 1.59%   |
| 0.51-1.0    | 1         | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 24        | 34.78%  |
| 4.01-8.0  | 16        | 23.19%  |
| 2.01-3.0  | 14        | 20.29%  |
| 3.01-4.0  | 7         | 10.14%  |
| 0.51-1.0  | 5         | 7.25%   |
| 8.01-16.0 | 2         | 2.9%    |
| 0.01-0.5  | 1         | 1.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 47        | 73.44%  |
| 2      | 15        | 23.44%  |
| 4      | 1         | 1.56%   |
| 3      | 1         | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 68.25%  |
| Yes       | 20        | 31.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 84.13%  |
| No        | 10        | 15.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 98.41%  |
| No        | 1         | 1.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 79.37%  |
| No        | 13        | 20.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 14        | 22.22%  |
| USA          | 9         | 14.29%  |
| Brazil       | 9         | 14.29%  |
| Italy        | 4         | 6.35%   |
| UK           | 3         | 4.76%   |
| Spain        | 3         | 4.76%   |
| Russia       | 3         | 4.76%   |
| Norway       | 2         | 3.17%   |
| Netherlands  | 2         | 3.17%   |
| Mexico       | 2         | 3.17%   |
| France       | 2         | 3.17%   |
| Sweden       | 1         | 1.59%   |
| South Africa | 1         | 1.59%   |
| Slovenia     | 1         | 1.59%   |
| Serbia       | 1         | 1.59%   |
| Poland       | 1         | 1.59%   |
| Indonesia    | 1         | 1.59%   |
| India        | 1         | 1.59%   |
| Hungary      | 1         | 1.59%   |
| Czechia      | 1         | 1.59%   |
| Australia    | 1         | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Madrid           | 3         | 4.55%   |
| Sao Paulo        | 2         | 3.03%   |
| Paris            | 2         | 3.03%   |
| London           | 2         | 3.03%   |
| Joinville        | 2         | 3.03%   |
| Berlin           | 2         | 3.03%   |
| Yekaterinburg    | 1         | 1.52%   |
| Vaksdal          | 1         | 1.52%   |
| Sydney           | 1         | 1.52%   |
| Stockholm        | 1         | 1.52%   |
| Stazione-Fornola | 1         | 1.52%   |
| Skokie           | 1         | 1.52%   |
| Saki             | 1         | 1.52%   |
| Rome             | 1         | 1.52%   |
| Reggio Emilia    | 1         | 1.52%   |
| Recife           | 1         | 1.52%   |
| Pretoria         | 1         | 1.52%   |
| Poznan           | 1         | 1.52%   |
| Pirmasens        | 1         | 1.52%   |
| Peize            | 1         | 1.52%   |
| Pedro Leopoldo   | 1         | 1.52%   |
| Overland Park    | 1         | 1.52%   |
| Osorio           | 1         | 1.52%   |
| Oberhausen       | 1         | 1.52%   |
| Nuremberg        | 1         | 1.52%   |
| Novi Sad         | 1         | 1.52%   |
| Northallerton    | 1         | 1.52%   |
| Moscow           | 1         | 1.52%   |
| Mikulov          | 1         | 1.52%   |
| Mexico City      | 1         | 1.52%   |
| Merano           | 1         | 1.52%   |
| Maua             | 1         | 1.52%   |
| Louisville       | 1         | 1.52%   |
| Lesce            | 1         | 1.52%   |
| Lehrte           | 1         | 1.52%   |
| Lakeland         | 1         | 1.52%   |
| Jakarta          | 1         | 1.52%   |
| Ithaca           | 1         | 1.52%   |
| Itajaí          | 1         | 1.52%   |
| Houten           | 1         | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 16        | 21     | 20.25%  |
| Seagate                        | 10        | 11     | 12.66%  |
| WDC                            | 5         | 6      | 6.33%   |
| SK hynix                       | 5         | 5      | 6.33%   |
| Unknown                        | 4         | 5      | 5.06%   |
| Toshiba                        | 4         | 6      | 5.06%   |
| Kingston                       | 4         | 6      | 5.06%   |
| Crucial                        | 4         | 4      | 5.06%   |
| SanDisk                        | 3         | 3      | 3.8%    |
| Micron Technology              | 2         | 2      | 2.53%   |
| HGST                           | 2         | 2      | 2.53%   |
| A-DATA Technology              | 2         | 2      | 2.53%   |
| Unknown                        | 2         | 2      | 2.53%   |
| VISIPRO                        | 1         | 1      | 1.27%   |
| Union Memory (Shenzhen)        | 1         | 1      | 1.27%   |
| Solid State Storage Technology | 1         | 1      | 1.27%   |
| Solid State Storage            | 1         | 1      | 1.27%   |
| PNY                            | 1         | 2      | 1.27%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 1.27%   |
| KIOXIA                         | 1         | 1      | 1.27%   |
| Kingston Technology Company    | 1         | 1      | 1.27%   |
| JMicron Technology             | 1         | 1      | 1.27%   |
| Intenso                        | 1         | 1      | 1.27%   |
| Intel                          | 1         | 1      | 1.27%   |
| Hitachi                        | 1         | 2      | 1.27%   |
| Hewlett-Packard                | 1         | 3      | 1.27%   |
| Gigabyte Technology            | 1         | 1      | 1.27%   |
| China                          | 1         | 1      | 1.27%   |
| Biwin Storage Technology       | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  128GB                            | 2         | 2.41%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 2.41%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 2.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 2.41%   |
| Unknown                                            | 2         | 2.41%   |
| WDC WD3200BPVT-22JJ5T0 320GB                       | 1         | 1.2%    |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 1.2%    |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 1.2%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 1.2%    |
| WDC PC SN730 SDBPNTY-512G-1006 512GB               | 1         | 1.2%    |
| VISIPRO SSD 256GB                                  | 1         | 1.2%    |
| Unknown MMC Card  7GB                              | 1         | 1.2%    |
| Unknown MMC Card  32GB                             | 1         | 1.2%    |
| Unknown MMC Card  16GB                             | 1         | 1.2%    |
| Union Memory (Shenzhen) UMIS RPETJ1T24MGE2QDQ 1TB  | 1         | 1.2%    |
| Toshiba MQ04ABF100 1TB                             | 1         | 1.2%    |
| Toshiba MQ01ABD100 1TB                             | 1         | 1.2%    |
| Toshiba MK5055GSX 500GB                            | 1         | 1.2%    |
| Toshiba MK3265GSX 320GB                            | 1         | 1.2%    |
| Solid State Storage NVMe SSD Drive 256GB           | 1         | 1.2%    |
| Solid State Storage CL1-3D512-Q11 NVMe SSSTC 512GB | 1         | 1.2%    |
| SK hynix SC300 M.2 2280 256GB SSD                  | 1         | 1.2%    |
| SK hynix NVMe SSD Drive 512GB                      | 1         | 1.2%    |
| SK hynix BC711 NVMe 512GB                          | 1         | 1.2%    |
| SK hynix BC711 HFM512GD3JX013N 512GB               | 1         | 1.2%    |
| SK hynix BC501 NVMe Solid State Drive 512GB        | 1         | 1.2%    |
| Seagate ST9500325AS 500GB                          | 1         | 1.2%    |
| Seagate ST9250827AS 250GB                          | 1         | 1.2%    |
| Seagate ST320LT007-9ZV142 320GB                    | 1         | 1.2%    |
| Seagate ST2000LM015-2E8174 2TB                     | 1         | 1.2%    |
| Seagate ST1000LX015-1U7172 1TB                     | 1         | 1.2%    |
| Seagate ST1000LM048-2E7172 1TB                     | 1         | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 1.2%    |
| Seagate ST1000LM014-1EJ164 1TB                     | 1         | 1.2%    |
| Sandisk WD Black SN850 500GB                       | 1         | 1.2%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB   | 1         | 1.2%    |
| SanDisk NVMe SSD Drive 256GB                       | 1         | 1.2%    |
| Samsung SSD PM851 2.5 7mm 128GB                    | 1         | 1.2%    |
| Samsung SSD 980 PRO 2TB                            | 1         | 1.2%    |
| Samsung SSD 980 250GB                              | 1         | 1.2%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 11     | 50%     |
| Toshiba | 4         | 6      | 20%     |
| WDC     | 3         | 4      | 15%     |
| HGST    | 2         | 2      | 10%     |
| Hitachi | 1         | 2      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 26.92%  |
| Kingston            | 4         | 5      | 15.38%  |
| Crucial             | 3         | 3      | 11.54%  |
| A-DATA Technology   | 2         | 2      | 7.69%   |
| Unknown             | 2         | 2      | 7.69%   |
| VISIPRO             | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| PNY                 | 1         | 2      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |
| Intenso             | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 3      | 3.85%   |
| Gigabyte Technology | 1         | 1      | 3.85%   |
| China               | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 28        | 32     | 36.84%  |
| SSD     | 23        | 32     | 30.26%  |
| HDD     | 20        | 25     | 26.32%  |
| MMC     | 4         | 5      | 5.26%   |
| Unknown | 1         | 1      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 56     | 54.79%  |
| NVMe | 28        | 32     | 38.36%  |
| MMC  | 4         | 5      | 5.48%   |
| SAS  | 1         | 2      | 1.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 39     | 60.47%  |
| 0.51-1.0   | 14        | 15     | 32.56%  |
| 1.01-2.0   | 3         | 3      | 6.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 17        | 26.98%  |
| 1001-2000      | 15        | 23.81%  |
| 2001-3000      | 10        | 15.87%  |
| 251-500        | 8         | 12.7%   |
| 501-1000       | 7         | 11.11%  |
| 101-250        | 5         | 7.94%   |
| Unknown        | 1         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 33.33%  |
| 51-100         | 11        | 15.94%  |
| 251-500        | 10        | 14.49%  |
| 1-20           | 9         | 13.04%  |
| 501-1000       | 6         | 8.7%    |
| More than 3000 | 4         | 5.8%    |
| 1001-2000      | 4         | 5.8%    |
| 2001-3000      | 1         | 1.45%   |
| Unknown        | 1         | 1.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Notebooks | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Toshiba MK5055GSX 500GB                   | 1         | 3      | 16.67%  |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 16.67%  |
| Kingston SUV300S37A240G 240GB SSD         | 1         | 2      | 16.67%  |
| Hitachi HTS725025A9A364 250GB             | 1         | 2      | 16.67%  |
| Crucial CT250BX100SSD1 250GB              | 1         | 1      | 16.67%  |
| Biwin Storage Technology HP SSD EX900 1TB | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba                  | 1         | 3      | 16.67%  |
| Seagate                  | 1         | 1      | 16.67%  |
| Kingston                 | 1         | 2      | 16.67%  |
| Hitachi                  | 1         | 2      | 16.67%  |
| Crucial                  | 1         | 1      | 16.67%  |
| Biwin Storage Technology | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 3      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 2      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 6      | 50%     |
| SSD  | 2         | 3      | 33.33%  |
| NVMe | 1         | 1      | 16.67%  |

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
| Works    | 31        | 38     | 46.97%  |
| Detected | 29        | 47     | 43.94%  |
| Malfunc  | 6         | 10     | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 46        | 58.97%  |
| Samsung Electronics            | 8         | 10.26%  |
| SanDisk                        | 5         | 6.41%   |
| AMD                            | 5         | 6.41%   |
| SK hynix                       | 4         | 5.13%   |
| Solid State Storage Technology | 2         | 2.56%   |
| Micron Technology              | 2         | 2.56%   |
| Kingston Technology Company    | 2         | 2.56%   |
| Union Memory (Shenzhen)        | 1         | 1.28%   |
| MAXIO Technology (Hangzhou)    | 1         | 1.28%   |
| KIOXIA                         | 1         | 1.28%   |
| Biwin Storage Technology       | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 6.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 6.17%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 6.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 4.94%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 3.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 3.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 3.7%    |
| Samsung NVMe SSD Controller 980                                                | 3         | 3.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 3.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 3.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 3.7%    |
| Solid State Storage Non-Volatile memory controller                             | 2         | 2.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.47%   |
| Micron NVMe Storage Controller                                                 | 2         | 2.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 2.47%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 1.23%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.23%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.23%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 1.23%   |
| MAXIO (Hangzhou) Non-Volatile memory controller                                | 1         | 1.23%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.23%   |
| Kingston Company NVMe Controller                                               | 1         | 1.23%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.23%   |
| Intel SSD 600P Series                                                          | 1         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.23%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.23%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.23%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 45        | 56.96%  |
| NVMe | 27        | 34.18%  |
| RAID | 5         | 6.33%   |
| IDE  | 2         | 2.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 51        | 80.95%  |
| AMD    | 12        | 19.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 3.17%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 3.17%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 3.17%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 3.17%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 3.17%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 2         | 3.17%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 3.17%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 3.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 3.17%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 3.17%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 3.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 3.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.17%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 1.59%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.59%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 1.59%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.59%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 1.59%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.59%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.59%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.59%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.59%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.59%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.59%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.59%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 1.59%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.59%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz          | 1         | 1.59%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 1         | 1.59%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1         | 1.59%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 12        | 19.05%  |
| Intel Core i7           | 11        | 17.46%  |
| Other                   | 10        | 15.87%  |
| Intel Core i3           | 8         | 12.7%   |
| AMD Ryzen 5             | 5         | 7.94%   |
| AMD Ryzen 7             | 4         | 6.35%   |
| Intel Core 2 Duo        | 3         | 4.76%   |
| Intel Celeron           | 3         | 4.76%   |
| Intel Pentium           | 2         | 3.17%   |
| Intel Pentium Dual-Core | 1         | 1.59%   |
| Intel Atom              | 1         | 1.59%   |
| AMD Ryzen 9             | 1         | 1.59%   |
| AMD Ryzen 7 PRO         | 1         | 1.59%   |
| AMD A4                  | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 42.86%  |
| 4      | 19        | 30.16%  |
| 8      | 6         | 9.52%   |
| 6      | 6         | 9.52%   |
| 12     | 2         | 3.17%   |
| 1      | 2         | 3.17%   |
| 10     | 1         | 1.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 51        | 80.95%  |
| 1      | 12        | 19.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 39.68%  |
| 0x806c1    | 5         | 7.94%   |
| 0x206a7    | 3         | 4.76%   |
| 0x0a50000c | 3         | 4.76%   |
| 0x906a3    | 2         | 3.17%   |
| 0x706a8    | 2         | 3.17%   |
| 0x1067a    | 2         | 3.17%   |
| 0x08108109 | 2         | 3.17%   |
| 0x906ea    | 1         | 1.59%   |
| 0x906a4    | 1         | 1.59%   |
| 0x806ec    | 1         | 1.59%   |
| 0x806ea    | 1         | 1.59%   |
| 0x806e9    | 1         | 1.59%   |
| 0x806d1    | 1         | 1.59%   |
| 0x706e5    | 1         | 1.59%   |
| 0x6fb      | 1         | 1.59%   |
| 0x506e3    | 1         | 1.59%   |
| 0x506ca    | 1         | 1.59%   |
| 0x406e3    | 1         | 1.59%   |
| 0x40651    | 1         | 1.59%   |
| 0x306c3    | 1         | 1.59%   |
| 0x306a9    | 1         | 1.59%   |
| 0x20655    | 1         | 1.59%   |
| 0x106ca    | 1         | 1.59%   |
| 0x0a404102 | 1         | 1.59%   |
| 0x08608103 | 1         | 1.59%   |
| 0x08108102 | 1         | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Haswell          | 9         | 14.29%  |
| KabyLake         | 8         | 12.7%   |
| Zen 3            | 5         | 7.94%   |
| TigerLake        | 5         | 7.94%   |
| SandyBridge      | 5         | 7.94%   |
| Zen+             | 3         | 4.76%   |
| Westmere         | 3         | 4.76%   |
| Penryn           | 3         | 4.76%   |
| IvyBridge        | 3         | 4.76%   |
| Alderlake Hybrid | 3         | 4.76%   |
| Unknown          | 3         | 4.76%   |
| Skylake          | 2         | 3.17%   |
| Icelake          | 2         | 3.17%   |
| Goldmont plus    | 2         | 3.17%   |
| Zen 2            | 1         | 1.59%   |
| Goldmont         | 1         | 1.59%   |
| Excavator        | 1         | 1.59%   |
| Core             | 1         | 1.59%   |
| CometLake        | 1         | 1.59%   |
| Broadwell        | 1         | 1.59%   |
| Bonnell          | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 56.41%  |
| Nvidia | 19        | 24.36%  |
| AMD    | 15        | 19.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 5         | 6.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 5.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 5.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 3.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 3.8%    |
| Intel HD Graphics 620                                                     | 3         | 3.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 3.8%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 3.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 3.8%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 2         | 2.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.53%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 2.53%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 2         | 2.53%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 2.53%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 2.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 2.53%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 2.53%   |
| Nvidia TU117M                                                             | 1         | 1.27%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                         | 1         | 1.27%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 1.27%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.27%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 1.27%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 1.27%   |
| Nvidia GK208GLM [Quadro K610M]                                            | 1         | 1.27%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 1.27%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 1.27%   |
| Nvidia GK104GLM [Quadro K3100M]                                           | 1         | 1.27%   |
| Nvidia GF119M [GeForce 410M]                                              | 1         | 1.27%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.27%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 1.27%   |
| Nvidia G86M [GeForce 8600M GS]                                            | 1         | 1.27%   |
| Intel UHD Graphics 620                                                    | 1         | 1.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.27%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.27%   |
| Intel HD Graphics 5500                                                    | 1         | 1.27%   |
| Intel HD Graphics 530                                                     | 1         | 1.27%   |
| Intel HD Graphics 500                                                     | 1         | 1.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 1.27%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 1.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 50.79%  |
| Intel + Nvidia | 11        | 17.46%  |
| 1 x AMD        | 10        | 15.87%  |
| 1 x Nvidia     | 5         | 7.94%   |
| AMD + Nvidia   | 3         | 4.76%   |
| 2 x AMD        | 1         | 1.59%   |
| Intel + AMD    | 1         | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 55        | 85.94%  |
| Proprietary | 6         | 9.38%   |
| Unknown     | 3         | 4.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 70.31%  |
| 0.01-0.5   | 6         | 9.38%   |
| 3.01-4.0   | 5         | 7.81%   |
| 1.01-2.0   | 5         | 7.81%   |
| 0.51-1.0   | 2         | 3.13%   |
| 8.01-16.0  | 1         | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 24.29%  |
| BOE                     | 12        | 17.14%  |
| LG Display              | 8         | 11.43%  |
| Samsung Electronics     | 6         | 8.57%   |
| Chimei Innolux          | 6         | 8.57%   |
| Lenovo                  | 4         | 5.71%   |
| Dell                    | 3         | 4.29%   |
| Sharp                   | 2         | 2.86%   |
| InfoVision              | 2         | 2.86%   |
| Hewlett-Packard         | 2         | 2.86%   |
| Goldstar                | 2         | 2.86%   |
| ViewSonic               | 1         | 1.43%   |
| Insignia                | 1         | 1.43%   |
| HannStar                | 1         | 1.43%   |
| Fujitsu Siemens         | 1         | 1.43%   |
| Eizo                    | 1         | 1.43%   |
| Chi Mei Optoelectronics | 1         | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE08CD 1366x768 344x194mm 15.5-inch                  | 3         | 4.29%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch             | 2         | 2.86%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 2.86%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 2         | 2.86%   |
| ViewSonic VA2265 SERIES VSCB330 1920x1080 476x268mm 21.5-inch         | 1         | 1.43%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 1.43%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.43%   |
| Samsung Electronics S23B350 SAM08F4 1920x1080 510x287mm 23.0-inch     | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC894F 1920x1080 344x194mm 15.5-inch | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch  | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 1.43%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 1.43%   |
| LG Display LCD Monitor LGD0584 1920x1080 294x165mm 13.3-inch          | 1         | 1.43%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.43%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.43%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 1.43%   |
| Lenovo LEN P32p-20 LEN62A2 3840x2160 697x392mm 31.5-inch              | 1         | 1.43%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 1.43%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 1         | 1.43%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 1.43%   |
| Insignia NS39DR510NA17 BBY3963 1920x1080 853x480mm 38.5-inch          | 1         | 1.43%   |
| InfoVision LCD Monitor IVO3E94 1920x1200 345x215mm 16.0-inch          | 1         | 1.43%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 1.43%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch              | 1         | 1.43%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1         | 1.43%   |
| Goldstar IPS235 GSM587D 1920x1080 510x290mm 23.1-inch                 | 1         | 1.43%   |
| Fujitsu Siemens 5110 FA FUS0420 1600x1200 408x306mm 20.1-inch         | 1         | 1.43%   |
| Eizo EV2450 ENC2568 1920x1080 528x297mm 23.9-inch                     | 1         | 1.43%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 1         | 1.43%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                    | 1         | 1.43%   |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 1         | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 36        | 56.25%  |
| 1366x768 (WXGA)   | 18        | 28.13%  |
| 1920x1200 (WUXGA) | 2         | 3.13%   |
| 1600x900 (HD+)    | 2         | 3.13%   |
| 3840x2160 (4K)    | 1         | 1.56%   |
| 1600x1200         | 1         | 1.56%   |
| 1440x900 (WXGA+)  | 1         | 1.56%   |
| 1280x960          | 1         | 1.56%   |
| 1280x800 (WXGA)   | 1         | 1.56%   |
| 1024x600          | 1         | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 32        | 46.38%  |
| 13     | 8         | 11.59%  |
| 14     | 7         | 10.14%  |
| 17     | 6         | 8.7%    |
| 16     | 3         | 4.35%   |
| 27     | 2         | 2.9%    |
| 24     | 2         | 2.9%    |
| 23     | 2         | 2.9%    |
| 21     | 2         | 2.9%    |
| 38     | 1         | 1.45%   |
| 31     | 1         | 1.45%   |
| 20     | 1         | 1.45%   |
| 12     | 1         | 1.45%   |
| 10     | 1         | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 45        | 66.18%  |
| 351-400     | 8         | 11.76%  |
| 501-600     | 6         | 8.82%   |
| 201-300     | 4         | 5.88%   |
| 401-500     | 3         | 4.41%   |
| 801-900     | 1         | 1.47%   |
| 601-700     | 1         | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 56        | 90.32%  |
| 16/10 | 4         | 6.45%   |
| 4/3   | 2         | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 48.53%  |
| 81-90          | 13        | 19.12%  |
| 121-130        | 7         | 10.29%  |
| 201-250        | 5         | 7.35%   |
| 71-80          | 2         | 2.94%   |
| 301-350        | 2         | 2.94%   |
| 61-70          | 1         | 1.47%   |
| 351-500        | 1         | 1.47%   |
| 41-50          | 1         | 1.47%   |
| 151-200        | 1         | 1.47%   |
| 111-120        | 1         | 1.47%   |
| 501-1000       | 1         | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 32        | 47.76%  |
| 101-120 | 20        | 29.85%  |
| 51-100  | 12        | 17.91%  |
| 161-240 | 3         | 4.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 76.56%  |
| 2     | 9         | 14.06%  |
| 0     | 4         | 6.25%   |
| 3     | 2         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 37        | 36.63%  |
| Realtek Semiconductor    | 36        | 35.64%  |
| Qualcomm Atheros         | 12        | 11.88%  |
| Broadcom                 | 3         | 2.97%   |
| Ralink                   | 2         | 1.98%   |
| MediaTek                 | 2         | 1.98%   |
| Lenovo                   | 2         | 1.98%   |
| Broadcom Limited         | 2         | 1.98%   |
| TP-Link                  | 1         | 0.99%   |
| Sierra Wireless          | 1         | 0.99%   |
| Samsung Electronics      | 1         | 0.99%   |
| Qualcomm                 | 1         | 0.99%   |
| Marvell Technology Group | 1         | 0.99%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 18.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.48%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.48%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.48%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 2.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.65%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.65%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.65%   |
| Intel Wireless 8260                                               | 2         | 1.65%   |
| Intel Wireless 7265                                               | 2         | 1.65%   |
| Intel Wireless 7260                                               | 2         | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.65%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 1.65%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.65%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.83%   |
| Sierra Wireless EM7455                                            | 1         | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.83%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.83%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.83%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 56.45%  |
| Qualcomm Atheros      | 10        | 16.13%  |
| Realtek Semiconductor | 8         | 12.9%   |
| Ralink                | 2         | 3.23%   |
| MediaTek              | 2         | 3.23%   |
| Broadcom              | 2         | 3.23%   |
| Sierra Wireless       | 1         | 1.61%   |
| Qualcomm              | 1         | 1.61%   |
| Broadcom Limited      | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 3         | 4.69%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 4.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 4.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.13%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 3.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 3.13%   |
| Intel Wireless 8265 / 8275                                     | 2         | 3.13%   |
| Intel Wireless 8260                                            | 2         | 3.13%   |
| Intel Wireless 7265                                            | 2         | 3.13%   |
| Intel Wireless 7260                                            | 2         | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 3.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 3.13%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 3.13%   |
| Sierra Wireless EM7455                                         | 1         | 1.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.56%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.56%   |
| Intel Wireless-AC 9260                                         | 1         | 1.56%   |
| Intel Wireless Gigabit 17265                                   | 1         | 1.56%   |
| Intel WiFi Link 5100                                           | 1         | 1.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 31        | 54.39%  |
| Intel                    | 15        | 26.32%  |
| Qualcomm Atheros         | 4         | 7.02%   |
| Lenovo                   | 2         | 3.51%   |
| TP-Link                  | 1         | 1.75%   |
| Samsung Electronics      | 1         | 1.75%   |
| Marvell Technology Group | 1         | 1.75%   |
| Broadcom Limited         | 1         | 1.75%   |
| Broadcom                 | 1         | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 38.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 5.26%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 5.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.51%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.51%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.75%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.75%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 1.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.75%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.75%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.75%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.75%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.75%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.75%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.75%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 53.51%  |
| Ethernet | 53        | 46.49%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 71.64%  |
| Ethernet | 19        | 28.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 47        | 74.6%   |
| 1     | 12        | 19.05%  |
| 0     | 3         | 4.76%   |
| 3     | 1         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 69.23%  |
| Yes  | 20        | 30.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 56%     |
| Realtek Semiconductor           | 5         | 10%     |
| Qualcomm Atheros Communications | 4         | 8%      |
| IMC Networks                    | 4         | 8%      |
| Broadcom                        | 3         | 6%      |
| Hewlett-Packard                 | 2         | 4%      |
| Ralink                          | 1         | 2%      |
| Lite-On Technology              | 1         | 2%      |
| Edimax Technology               | 1         | 2%      |
| Cambridge Silicon Radio         | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 7         | 14%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 14%     |
| Realtek Bluetooth Radio                                     | 4         | 8%      |
| Intel AX201 Bluetooth                                       | 4         | 8%      |
| Intel AX200 Bluetooth                                       | 3         | 6%      |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 4%      |
| Intel Bluetooth Device                                      | 2         | 4%      |
| Intel AX210 Bluetooth                                       | 2         | 4%      |
| IMC Networks Bluetooth Device                               | 2         | 4%      |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 4%      |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 2%      |
| Ralink RT3290 Bluetooth                                     | 1         | 2%      |
| Qualcomm Atheros  Bluetooth Device                          | 1         | 2%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 2%      |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 2%      |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 2%      |
| Lite-On Wireless_Device                                     | 1         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 2%      |
| IMC Networks Wireless_Device                                | 1         | 2%      |
| IMC Networks Atheros AR3012 Bluetooth                       | 1         | 2%      |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 2%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 2%      |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1         | 2%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 2%      |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 62.2%   |
| AMD                   | 13        | 15.85%  |
| Nvidia                | 10        | 12.2%   |
| Lenovo                | 2         | 2.44%   |
| C-Media Electronics   | 2         | 2.44%   |
| Realtek Semiconductor | 1         | 1.22%   |
| Plantronics           | 1         | 1.22%   |
| Logitech              | 1         | 1.22%   |
| GN Netcom             | 1         | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 10.58%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 6.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 5.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 4.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 4.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 4.81%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.85%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 2.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 2.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.88%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.92%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.96%   |
| Plantronics Blackwire 3220 Series                                          | 1         | 0.96%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.96%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.96%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.96%   |
| Nvidia Audio device                                                        | 1         | 0.96%   |
| Logitech 960 Headset                                                       | 1         | 0.96%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 0.96%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.96%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.96%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 25.58%  |
| Micron Technology   | 7         | 16.28%  |
| SK hynix            | 6         | 13.95%  |
| Kingston            | 5         | 11.63%  |
| Unknown (ABCD)      | 3         | 6.98%   |
| Unknown             | 2         | 4.65%   |
| Crucial             | 2         | 4.65%   |
| Unknown             | 2         | 4.65%   |
| Toshiba             | 1         | 2.33%   |
| Smart               | 1         | 2.33%   |
| Qimonda             | 1         | 2.33%   |
| Corsair             | 1         | 2.33%   |
| A-DATA Technology   | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 6.52%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 4.35%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 2         | 4.35%   |
| Unknown                                                          | 2         | 4.35%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 2.17%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 2.17%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 2.17%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 2.17%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 2.17%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 1         | 2.17%   |
| Smart RAM SH564288FH8NWPHSFR 1024MB SODIMM DDR3 1067MT/s         | 1         | 2.17%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 2.17%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 2.17%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 2.17%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.17%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 2.17%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.17%   |
| Samsung RAM Module 32GB SODIMM DDR5 4800MT/s                     | 1         | 2.17%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 2.17%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.17%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 2.17%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 2.17%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.17%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.17%   |
| Qimonda RAM 64T256020EDL2.5C2 2GB SODIMM DDR2 2048MT/s           | 1         | 2.17%   |
| Micron RAM Module 16384MB SODIMM DDR4 3200MT/s                   | 1         | 2.17%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 2.17%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 2.17%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.17%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 2.17%   |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.17%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 1         | 2.17%   |
| Kingston RAM ACR16D3LS1NBG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.17%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s           | 1         | 2.17%   |
| Kingston RAM 9905700-086.A00G 8GB SODIMM DDR4 3200MT/s           | 1         | 2.17%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB Row Of Chips DDR4 2400MT/s    | 1         | 2.17%   |
| Crucial RAM CT16G4SFD824A.M16FE 16GB SODIMM DDR4 2400MT/s        | 1         | 2.17%   |
| Corsair RAM CMSX64GX4M2A3200C22 32GB SODIMM DDR4 3200MT/s        | 1         | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 54.05%  |
| DDR3   | 7         | 18.92%  |
| LPDDR4 | 4         | 10.81%  |
| DDR2   | 3         | 8.11%   |
| SDRAM  | 1         | 2.7%    |
| LPDDR3 | 1         | 2.7%    |
| DDR5   | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 89.74%  |
| Row Of Chips | 4         | 10.26%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 13        | 31.71%  |
| 4096  | 12        | 29.27%  |
| 16384 | 7         | 17.07%  |
| 32768 | 3         | 7.32%   |
| 2048  | 3         | 7.32%   |
| 1024  | 3         | 7.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 26.19%  |
| 2667  | 8         | 19.05%  |
| 2400  | 6         | 14.29%  |
| 1600  | 5         | 11.9%   |
| 1334  | 2         | 4.76%   |
| 1333  | 2         | 4.76%   |
| 667   | 2         | 4.76%   |
| 8400  | 1         | 2.38%   |
| 4800  | 1         | 2.38%   |
| 4267  | 1         | 2.38%   |
| 2133  | 1         | 2.38%   |
| 2048  | 1         | 2.38%   |
| 1066  | 1         | 2.38%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 28.13%  |
| Sunplus Innovation Technology          | 6         | 9.38%   |
| Syntek                                 | 4         | 6.25%   |
| Microdia                               | 4         | 6.25%   |
| Luxvisions Innotech Limited            | 4         | 6.25%   |
| Bison Electronics                      | 4         | 6.25%   |
| Alcor Micro                            | 4         | 6.25%   |
| Lite-On Technology                     | 3         | 4.69%   |
| Acer                                   | 3         | 4.69%   |
| Quanta                                 | 2         | 3.13%   |
| Logitech                               | 2         | 3.13%   |
| IMC Networks                           | 2         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.13%   |
| webcam                                 | 1         | 1.56%   |
| vivo                                   | 1         | 1.56%   |
| Suyin                                  | 1         | 1.56%   |
| Realtek Semiconductor                  | 1         | 1.56%   |
| Lenovo                                 | 1         | 1.56%   |
| kingcome                               | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 6.25%   |
| Microdia Integrated_Webcam_HD                        | 3         | 4.69%   |
| Alcor Micro USB 2.0 Camera                           | 3         | 4.69%   |
| Syntek Integrated Camera                             | 2         | 3.13%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 3.13%   |
| Logitech HD Webcam C615                              | 2         | 3.13%   |
| Chicony FJ Camera                                    | 2         | 3.13%   |
| Bison Integrated Camera                              | 2         | 3.13%   |
| webcam webcam                                        | 1         | 1.56%   |
| vivo V2023                                           | 1         | 1.56%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                 | 1         | 1.56%   |
| Syntek EasyCamera                                    | 1         | 1.56%   |
| Suyin USB 2.0 Camera                                 | 1         | 1.56%   |
| Sunplus Laptop Integrated Webcam HD                  | 1         | 1.56%   |
| Sunplus HD WebCam                                    | 1         | 1.56%   |
| Sunplus HD 720P webcam                               | 1         | 1.56%   |
| Sunplus Dell E5570 integrated webcam                 | 1         | 1.56%   |
| Realtek USB Camera                                   | 1         | 1.56%   |
| Quanta HP HD Camera                                  | 1         | 1.56%   |
| Quanta HD User Facing                                | 1         | 1.56%   |
| Microdia Integrated Webcam                           | 1         | 1.56%   |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.56%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.56%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 1.56%   |
| Lite-On TOSHIBA Web Camera - HD                      | 1         | 1.56%   |
| Lite-On Integrated Camera                            | 1         | 1.56%   |
| Lite-On HP HD Webcam                                 | 1         | 1.56%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.56%   |
| kingcome 480p VGA Camera                             | 1         | 1.56%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 1         | 1.56%   |
| IMC Networks Integrated Camera                       | 1         | 1.56%   |
| Chicony UVC 1.00 device HD UVC WebCam                | 1         | 1.56%   |
| Chicony USB2.0 VGA UVC WebCam                        | 1         | 1.56%   |
| Chicony USB2.0 Camera                                | 1         | 1.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 1         | 1.56%   |
| Chicony HP Wide Vision HD                            | 1         | 1.56%   |
| Chicony HP HD Webcam [Fixed]                         | 1         | 1.56%   |
| Chicony HP 5MP Camera                                | 1         | 1.56%   |
| Chicony HD Webcam                                    | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 7         | 46.67%  |
| Synaptics        | 4         | 26.67%  |
| Upek             | 3         | 20%     |
| AuthenTec        | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 20%     |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 13.33%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 13.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 6.67%   |
| Validity Sensors VFS491                                  | 1         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 6.67%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 6.67%   |
| AuthenTec AES1600                                        | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 5         | 62.5%   |
| Broadcom    | 2         | 25%     |
| Lenovo      | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 62.5%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom 58200                                                               | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 31        | 48.44%  |
| 1     | 20        | 31.25%  |
| 2     | 11        | 17.19%  |
| 4     | 1         | 1.56%   |
| 3     | 1         | 1.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 32.61%  |
| Chipcard              | 8         | 17.39%  |
| Graphics card         | 7         | 15.22%  |
| Net/wireless          | 5         | 10.87%  |
| Multimedia controller | 3         | 6.52%   |
| Camera                | 3         | 6.52%   |
| Network               | 2         | 4.35%   |
| Sound                 | 1         | 2.17%   |
| Card reader           | 1         | 2.17%   |
| Bluetooth             | 1         | 2.17%   |

