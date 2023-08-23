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

Total: 99

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ZenBook UX482EA_UX482EA     | [52d550e878](https://linux-hardware.org/?probe=52d550e878) | Jul 17, 2023 |
| Acer          | Aspire V3-571G              | [9d4c4f5506](https://linux-hardware.org/?probe=9d4c4f5506) | Jun 29, 2023 |
| HP            | Laptop 17-bs0xx             | [1cddf187c5](https://linux-hardware.org/?probe=1cddf187c5) | Jun 13, 2023 |
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
| 5.14.21-150400.22-default    | 12        | 16.22%  |
| 5.14.21-150400.24.21-default | 9         | 12.16%  |
| 5.14.21-150400.24.38-default | 8         | 10.81%  |
| 5.14.21-150400.24.46-default | 7         | 9.46%   |
| 5.14.21-150400.24.41-default | 5         | 6.76%   |
| 5.14.21-150400.24.63-default | 4         | 5.41%   |
| 5.14.21-150400.24.60-default | 4         | 5.41%   |
| 5.14.21-150400.24.33-default | 4         | 5.41%   |
| 5.14.21-150400.24.18-default | 4         | 5.41%   |
| 5.14.21-150400.19-default    | 4         | 5.41%   |
| 5.14.21-150400.24.55-default | 3         | 4.05%   |
| 5.14.21-150400.24.11-default | 3         | 4.05%   |
| 5.14.21-150400.24.28-default | 2         | 2.7%    |
| 6.3.5-lp154.6-default        | 1         | 1.35%   |
| 5.14.21-150400.9-default     | 1         | 1.35%   |
| 5.14.21-150400.3-default     | 1         | 1.35%   |
| 5.14.21-150400.24.66-default | 1         | 1.35%   |
| 5.14.21-150400.15-default    | 1         | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.21 | 64        | 98.46%  |
| 6.3.5   | 1         | 1.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 64        | 98.46%  |
| 6.3     | 1         | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 65        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 48        | 73.85%  |
| GNOME      | 6         | 9.23%   |
| XFCE       | 3         | 4.62%   |
| Cinnamon   | 2         | 3.08%   |
| Unknown    | 2         | 3.08%   |
| X-Cinnamon | 1         | 1.54%   |
| LXDE       | 1         | 1.54%   |
| ICEWM      | 1         | 1.54%   |
| Deepin     | 1         | 1.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 55        | 83.33%  |
| Wayland | 8         | 12.12%  |
| Tty     | 3         | 4.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 26        | 40%     |
| Unknown | 26        | 40%     |
| LightDM | 10        | 15.38%  |
| XDM     | 3         | 4.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 22        | 33.85%  |
| de_DE | 14        | 21.54%  |
| pt_BR | 9         | 13.85%  |
| POSIX | 5         | 7.69%   |
| es_ES | 3         | 4.62%   |
| ru_RU | 2         | 3.08%   |
| nn_NO | 2         | 3.08%   |
| it_IT | 2         | 3.08%   |
| en_GB | 2         | 3.08%   |
| nl_NL | 1         | 1.54%   |
| hu_HU | 1         | 1.54%   |
| fr_FR | 1         | 1.54%   |
| en_IN | 1         | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 34        | 52.31%  |
| EFI  | 31        | 47.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 48        | 73.85%  |
| Ext4    | 11        | 16.92%  |
| Xfs     | 5         | 7.69%   |
| Overlay | 1         | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 37        | 56.92%  |
| Unknown | 26        | 40%     |
| MBR     | 2         | 3.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 92.31%  |
| Yes       | 5         | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 84.62%  |
| Yes       | 10        | 15.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 24.62%  |
| Hewlett-Packard     | 11        | 16.92%  |
| Dell                | 9         | 13.85%  |
| ASUSTek Computer    | 7         | 10.77%  |
| Acer                | 5         | 7.69%   |
| Toshiba             | 2         | 3.08%   |
| Samsung Electronics | 2         | 3.08%   |
| Fujitsu             | 2         | 3.08%   |
| Unknown             | 2         | 3.08%   |
| TUXEDO              | 1         | 1.54%   |
| Sony                | 1         | 1.54%   |
| Schenker            | 1         | 1.54%   |
| Notebook            | 1         | 1.54%   |
| Multilaser          | 1         | 1.54%   |
| MSI                 | 1         | 1.54%   |
| LG Electronics      | 1         | 1.54%   |
| Jumper              | 1         | 1.54%   |
| Gateway             | 1         | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung 550XDA                           | 2         | 3.08%   |
| Unknown                                  | 2         | 3.08%   |
| TUXEDO InfinityBook S 15/17 Gen7         | 1         | 1.54%   |
| Toshiba Satellite P55t-A                 | 1         | 1.54%   |
| Toshiba Satellite L500                   | 1         | 1.54%   |
| Sony VPCEH25EN                           | 1         | 1.54%   |
| Schenker VIA 15 Pro                      | 1         | 1.54%   |
| Notebook NLx0MU                          | 1         | 1.54%   |
| Multilaser PC150                         | 1         | 1.54%   |
| MSI Delta 15 A5EFK                       | 1         | 1.54%   |
| LG C400-G.BC22P1                         | 1         | 1.54%   |
| Lenovo V15-ADA 82C7                      | 1         | 1.54%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDS3B600 | 1         | 1.54%   |
| Lenovo ThinkPad W541 20EF001UGE          | 1         | 1.54%   |
| Lenovo ThinkPad T530 2394D56             | 1         | 1.54%   |
| Lenovo ThinkPad T520 42435GG             | 1         | 1.54%   |
| Lenovo ThinkPad T495s 20QJ0012UK         | 1         | 1.54%   |
| Lenovo ThinkPad T470 20HES0FW00          | 1         | 1.54%   |
| Lenovo ThinkPad T410 25223FG             | 1         | 1.54%   |
| Lenovo ThinkPad T16 Gen 1 21BVCTO1WW     | 1         | 1.54%   |
| Lenovo ThinkPad P50 20EQS0VV0C           | 1         | 1.54%   |
| Lenovo ThinkPad P16s Gen 1 21BT000MUK    | 1         | 1.54%   |
| Lenovo ThinkPad Edge E530 3259HHG        | 1         | 1.54%   |
| Lenovo ThinkPad Edge E431 62779XP        | 1         | 1.54%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 1         | 1.54%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG     | 1         | 1.54%   |
| Lenovo IdeaPad 330-15IKB 81FD            | 1         | 1.54%   |
| Jumper EZbook                            | 1         | 1.54%   |
| HP ZBook 17 G2                           | 1         | 1.54%   |
| HP ZBook 17                              | 1         | 1.54%   |
| HP Victus by Laptop 16-e0xxx             | 1         | 1.54%   |
| HP ProBook 455 G8 Notebook PC            | 1         | 1.54%   |
| HP ProBook 4540s                         | 1         | 1.54%   |
| HP Pavilion Notebook                     | 1         | 1.54%   |
| HP Mini 210-1000                         | 1         | 1.54%   |
| HP Laptop 15s-eq0xxx                     | 1         | 1.54%   |
| HP EliteBook 865 16 inch G9 Notebook PC  | 1         | 1.54%   |
| HP EliteBook 840 G8 Notebook PC          | 1         | 1.54%   |
| HP Compaq 6730s                          | 1         | 1.54%   |
| Gateway NV55C                            | 1         | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 12        | 18.46%  |
| Dell Inspiron       | 4         | 6.15%   |
| Lenovo IdeaPad      | 3         | 4.62%   |
| Dell Latitude       | 3         | 4.62%   |
| Acer Aspire         | 3         | 4.62%   |
| Toshiba Satellite   | 2         | 3.08%   |
| Samsung 550XDA      | 2         | 3.08%   |
| HP ZBook            | 2         | 3.08%   |
| HP ProBook          | 2         | 3.08%   |
| HP EliteBook        | 2         | 3.08%   |
| Fujitsu LIFEBOOK    | 2         | 3.08%   |
| Dell Vostro         | 2         | 3.08%   |
| Unknown             | 2         | 3.08%   |
| TUXEDO InfinityBook | 1         | 1.54%   |
| Sony VPCEH25EN      | 1         | 1.54%   |
| Schenker VIA        | 1         | 1.54%   |
| Notebook NLx0MU     | 1         | 1.54%   |
| Multilaser PC150    | 1         | 1.54%   |
| MSI Delta           | 1         | 1.54%   |
| LG C400-G.BC22P1    | 1         | 1.54%   |
| Lenovo V15-ADA      | 1         | 1.54%   |
| Jumper EZbook       | 1         | 1.54%   |
| HP Victus           | 1         | 1.54%   |
| HP Pavilion         | 1         | 1.54%   |
| HP Mini             | 1         | 1.54%   |
| HP Laptop           | 1         | 1.54%   |
| HP Compaq           | 1         | 1.54%   |
| Gateway NV55C       | 1         | 1.54%   |
| ASUS ZenBook        | 1         | 1.54%   |
| ASUS Z450LA         | 1         | 1.54%   |
| ASUS X55CR          | 1         | 1.54%   |
| ASUS ROG            | 1         | 1.54%   |
| ASUS N750JV         | 1         | 1.54%   |
| ASUS N550JX         | 1         | 1.54%   |
| ASUS F3Sv           | 1         | 1.54%   |
| Acer Swift          | 1         | 1.54%   |
| Acer Nitro          | 1         | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 17        | 26.15%  |
| 2019 | 7         | 10.77%  |
| 2012 | 6         | 9.23%   |
| 2022 | 4         | 6.15%   |
| 2020 | 4         | 6.15%   |
| 2015 | 4         | 6.15%   |
| 2014 | 4         | 6.15%   |
| 2013 | 4         | 6.15%   |
| 2009 | 4         | 6.15%   |
| 2018 | 3         | 4.62%   |
| 2011 | 3         | 4.62%   |
| 2017 | 1         | 1.54%   |
| 2016 | 1         | 1.54%   |
| 2010 | 1         | 1.54%   |
| 2008 | 1         | 1.54%   |
| 2007 | 1         | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 65        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 54        | 83.08%  |
| Enabled  | 11        | 16.92%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 65        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 15        | 23.08%  |
| 3.01-4.0    | 13        | 20%     |
| 16.01-24.0  | 11        | 16.92%  |
| 8.01-16.0   | 10        | 15.38%  |
| 32.01-64.0  | 7         | 10.77%  |
| 64.01-256.0 | 3         | 4.62%   |
| 24.01-32.0  | 2         | 3.08%   |
| 2.01-3.0    | 2         | 3.08%   |
| 1.01-2.0    | 1         | 1.54%   |
| 0.51-1.0    | 1         | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 25        | 35.21%  |
| 4.01-8.0  | 16        | 22.54%  |
| 2.01-3.0  | 14        | 19.72%  |
| 3.01-4.0  | 8         | 11.27%  |
| 0.51-1.0  | 5         | 7.04%   |
| 8.01-16.0 | 2         | 2.82%   |
| 0.01-0.5  | 1         | 1.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 74.24%  |
| 2      | 15        | 22.73%  |
| 4      | 1         | 1.52%   |
| 3      | 1         | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 69.23%  |
| Yes       | 20        | 30.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 83.08%  |
| No        | 11        | 16.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 98.46%  |
| No        | 1         | 1.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 78.46%  |
| No        | 14        | 21.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 15        | 23.08%  |
| USA          | 9         | 13.85%  |
| Brazil       | 9         | 13.85%  |
| Russia       | 4         | 6.15%   |
| Italy        | 4         | 6.15%   |
| UK           | 3         | 4.62%   |
| Spain        | 3         | 4.62%   |
| Norway       | 2         | 3.08%   |
| Netherlands  | 2         | 3.08%   |
| Mexico       | 2         | 3.08%   |
| France       | 2         | 3.08%   |
| Sweden       | 1         | 1.54%   |
| South Africa | 1         | 1.54%   |
| Slovenia     | 1         | 1.54%   |
| Serbia       | 1         | 1.54%   |
| Poland       | 1         | 1.54%   |
| Indonesia    | 1         | 1.54%   |
| India        | 1         | 1.54%   |
| Hungary      | 1         | 1.54%   |
| Czechia      | 1         | 1.54%   |
| Australia    | 1         | 1.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Madrid           | 3         | 4.41%   |
| Sao Paulo        | 2         | 2.94%   |
| Paris            | 2         | 2.94%   |
| London           | 2         | 2.94%   |
| Joinville        | 2         | 2.94%   |
| Berlin           | 2         | 2.94%   |
| Yekaterinburg    | 1         | 1.47%   |
| Vladivostok      | 1         | 1.47%   |
| Vaksdal          | 1         | 1.47%   |
| Sydney           | 1         | 1.47%   |
| Stockholm        | 1         | 1.47%   |
| Stazione-Fornola | 1         | 1.47%   |
| Skokie           | 1         | 1.47%   |
| Saki             | 1         | 1.47%   |
| Rome             | 1         | 1.47%   |
| Reggio Emilia    | 1         | 1.47%   |
| Recife           | 1         | 1.47%   |
| Pretoria         | 1         | 1.47%   |
| Poznan           | 1         | 1.47%   |
| Pirmasens        | 1         | 1.47%   |
| Peize            | 1         | 1.47%   |
| Pedro Leopoldo   | 1         | 1.47%   |
| Overland Park    | 1         | 1.47%   |
| Osorio           | 1         | 1.47%   |
| Oberhausen       | 1         | 1.47%   |
| Nuremberg        | 1         | 1.47%   |
| Novi Sad         | 1         | 1.47%   |
| Northallerton    | 1         | 1.47%   |
| Moscow           | 1         | 1.47%   |
| Mikulov          | 1         | 1.47%   |
| Mexico City      | 1         | 1.47%   |
| Merano           | 1         | 1.47%   |
| Maua             | 1         | 1.47%   |
| Louisville       | 1         | 1.47%   |
| Lesce            | 1         | 1.47%   |
| Lehrte           | 1         | 1.47%   |
| Lakeland         | 1         | 1.47%   |
| Jakarta          | 1         | 1.47%   |
| Ithaca           | 1         | 1.47%   |
| Itajaí          | 1         | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 16        | 21     | 19.75%  |
| Seagate                        | 10        | 11     | 12.35%  |
| SK hynix                       | 6         | 6      | 7.41%   |
| WDC                            | 5         | 6      | 6.17%   |
| Toshiba                        | 5         | 7      | 6.17%   |
| Unknown                        | 4         | 5      | 4.94%   |
| Kingston                       | 4         | 6      | 4.94%   |
| Crucial                        | 4         | 4      | 4.94%   |
| SanDisk                        | 3         | 3      | 3.7%    |
| Micron Technology              | 2         | 2      | 2.47%   |
| HGST                           | 2         | 2      | 2.47%   |
| A-DATA Technology              | 2         | 2      | 2.47%   |
| Unknown                        | 2         | 2      | 2.47%   |
| VISIPRO                        | 1         | 1      | 1.23%   |
| Union Memory (Shenzhen)        | 1         | 1      | 1.23%   |
| Solid State Storage Technology | 1         | 1      | 1.23%   |
| Solid State Storage            | 1         | 1      | 1.23%   |
| PNY                            | 1         | 2      | 1.23%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 1.23%   |
| KIOXIA                         | 1         | 1      | 1.23%   |
| Kingston Technology Company    | 1         | 1      | 1.23%   |
| JMicron Technology             | 1         | 1      | 1.23%   |
| Intenso                        | 1         | 1      | 1.23%   |
| Intel                          | 1         | 1      | 1.23%   |
| Hitachi                        | 1         | 2      | 1.23%   |
| Hewlett-Packard                | 1         | 3      | 1.23%   |
| Gigabyte Technology            | 1         | 1      | 1.23%   |
| China                          | 1         | 1      | 1.23%   |
| Biwin Storage Technology       | 1         | 1      | 1.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  128GB                            | 2         | 2.35%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 2.35%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 2.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 2.35%   |
| Unknown                                            | 2         | 2.35%   |
| WDC WD3200BPVT-22JJ5T0 320GB                       | 1         | 1.18%   |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 1.18%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 1.18%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 1.18%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB               | 1         | 1.18%   |
| VISIPRO SSD 256GB                                  | 1         | 1.18%   |
| Unknown MMC Card  7GB                              | 1         | 1.18%   |
| Unknown MMC Card  32GB                             | 1         | 1.18%   |
| Unknown MMC Card  16GB                             | 1         | 1.18%   |
| Union Memory (Shenzhen) UMIS RPETJ1T24MGE2QDQ 1TB  | 1         | 1.18%   |
| Toshiba MQ04ABF100 1TB                             | 1         | 1.18%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1.18%   |
| Toshiba MQ01ABD050 500GB                           | 1         | 1.18%   |
| Toshiba MK5055GSX 500GB                            | 1         | 1.18%   |
| Toshiba MK3265GSX 320GB                            | 1         | 1.18%   |
| Solid State Storage NVMe SSD Drive 256GB           | 1         | 1.18%   |
| Solid State Storage CL1-3D512-Q11 NVMe SSSTC 512GB | 1         | 1.18%   |
| SK hynix SC300 M.2 2280 256GB SSD                  | 1         | 1.18%   |
| SK hynix NVMe SSD Drive 512GB                      | 1         | 1.18%   |
| SK hynix HFM512GD3JX013N 512GB                     | 1         | 1.18%   |
| SK hynix BC711 NVMe 512GB                          | 1         | 1.18%   |
| SK hynix BC711 HFM512GD3JX013N 512GB               | 1         | 1.18%   |
| SK hynix BC501 NVMe Solid State Drive 512GB        | 1         | 1.18%   |
| Seagate ST9500325AS 500GB                          | 1         | 1.18%   |
| Seagate ST9250827AS 250GB                          | 1         | 1.18%   |
| Seagate ST320LT007-9ZV142 320GB                    | 1         | 1.18%   |
| Seagate ST2000LM015-2E8174 2TB                     | 1         | 1.18%   |
| Seagate ST1000LX015-1U7172 1TB                     | 1         | 1.18%   |
| Seagate ST1000LM048-2E7172 1TB                     | 1         | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 1.18%   |
| Seagate ST1000LM014-1EJ164 1TB                     | 1         | 1.18%   |
| Sandisk WD Black SN850 1TB                         | 1         | 1.18%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB  | 1         | 1.18%   |
| SanDisk NVMe SSD Drive 256GB                       | 1         | 1.18%   |
| Samsung SSD PM851 2.5 7mm 128GB                    | 1         | 1.18%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 11     | 47.62%  |
| Toshiba | 5         | 7      | 23.81%  |
| WDC     | 3         | 4      | 14.29%  |
| HGST    | 2         | 2      | 9.52%   |
| Hitachi | 1         | 2      | 4.76%   |

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
| NVMe    | 29        | 33     | 37.18%  |
| SSD     | 23        | 32     | 29.49%  |
| HDD     | 21        | 26     | 26.92%  |
| MMC     | 4         | 5      | 5.13%   |
| Unknown | 1         | 1      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 57     | 54.67%  |
| NVMe | 29        | 33     | 38.67%  |
| MMC  | 4         | 5      | 5.33%   |
| SAS  | 1         | 2      | 1.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 40     | 61.36%  |
| 0.51-1.0   | 15        | 16     | 34.09%  |
| 1.01-2.0   | 2         | 2      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 18        | 27.69%  |
| 1001-2000      | 15        | 23.08%  |
| 2001-3000      | 10        | 15.38%  |
| 251-500        | 8         | 12.31%  |
| 501-1000       | 8         | 12.31%  |
| 101-250        | 5         | 7.69%   |
| Unknown        | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 33.8%   |
| 51-100         | 11        | 15.49%  |
| 251-500        | 10        | 14.08%  |
| 1-20           | 9         | 12.68%  |
| 501-1000       | 7         | 9.86%   |
| More than 3000 | 4         | 5.63%   |
| 1001-2000      | 4         | 5.63%   |
| 2001-3000      | 1         | 1.41%   |
| Unknown        | 1         | 1.41%   |

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
| Works    | 32        | 39     | 47.06%  |
| Detected | 30        | 48     | 44.12%  |
| Malfunc  | 6         | 10     | 8.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 48        | 59.26%  |
| Samsung Electronics            | 8         | 9.88%   |
| SK hynix                       | 5         | 6.17%   |
| SanDisk                        | 5         | 6.17%   |
| AMD                            | 5         | 6.17%   |
| Solid State Storage Technology | 2         | 2.47%   |
| Micron Technology              | 2         | 2.47%   |
| Kingston Technology Company    | 2         | 2.47%   |
| Union Memory (Shenzhen)        | 1         | 1.23%   |
| MAXIO Technology (Hangzhou)    | 1         | 1.23%   |
| KIOXIA                         | 1         | 1.23%   |
| Biwin Storage Technology       | 1         | 1.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 7.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 5.95%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 5.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 4.76%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 4.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 4.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 3.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 3.57%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 3.57%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 3.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 3.57%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 2.38%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 NVMe SSD 1024GB                         | 1         | 1.19%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.19%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.19%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 1.19%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 1         | 1.19%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.19%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602                                   | 1         | 1.19%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.19%   |
| Kingston Company NVMe Controller                                               | 1         | 1.19%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.19%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 1.19%   |
| Intel SSD 600P Series                                                          | 1         | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.19%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.19%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 46        | 56.1%   |
| NVMe | 28        | 34.15%  |
| RAID | 6         | 7.32%   |
| IDE  | 2         | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 53        | 81.54%  |
| AMD    | 12        | 18.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 4.62%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 3.08%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 3.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 3.08%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 3.08%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 3.08%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 2         | 3.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 3.08%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 3.08%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 3.08%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 3.08%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 3.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.08%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.54%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 1.54%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.54%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 1.54%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.54%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 1.54%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.54%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.54%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.54%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.54%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.54%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.54%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.54%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.54%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.54%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 1.54%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.54%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz          | 1         | 1.54%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 1         | 1.54%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1         | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 12        | 18.46%  |
| Intel Core i5           | 12        | 18.46%  |
| Other                   | 11        | 16.92%  |
| Intel Core i3           | 8         | 12.31%  |
| AMD Ryzen 5             | 5         | 7.69%   |
| AMD Ryzen 7             | 4         | 6.15%   |
| Intel Core 2 Duo        | 3         | 4.62%   |
| Intel Celeron           | 3         | 4.62%   |
| Intel Pentium           | 2         | 3.08%   |
| Intel Pentium Dual-Core | 1         | 1.54%   |
| Intel Atom              | 1         | 1.54%   |
| AMD Ryzen 9             | 1         | 1.54%   |
| AMD Ryzen 7 PRO         | 1         | 1.54%   |
| AMD A4                  | 1         | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 41.54%  |
| 4      | 21        | 32.31%  |
| 8      | 6         | 9.23%   |
| 6      | 6         | 9.23%   |
| 12     | 2         | 3.08%   |
| 1      | 2         | 3.08%   |
| 10     | 1         | 1.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 65        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 53        | 81.54%  |
| 1      | 12        | 18.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 65        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 40%     |
| 0x806c1    | 6         | 9.23%   |
| 0x206a7    | 3         | 4.62%   |
| 0x0a50000c | 3         | 4.62%   |
| 0x906a3    | 2         | 3.08%   |
| 0x706a8    | 2         | 3.08%   |
| 0x1067a    | 2         | 3.08%   |
| 0x08108109 | 2         | 3.08%   |
| 0x906ea    | 1         | 1.54%   |
| 0x906a4    | 1         | 1.54%   |
| 0x806ec    | 1         | 1.54%   |
| 0x806ea    | 1         | 1.54%   |
| 0x806e9    | 1         | 1.54%   |
| 0x806d1    | 1         | 1.54%   |
| 0x706e5    | 1         | 1.54%   |
| 0x6fb      | 1         | 1.54%   |
| 0x506e3    | 1         | 1.54%   |
| 0x506ca    | 1         | 1.54%   |
| 0x406e3    | 1         | 1.54%   |
| 0x40651    | 1         | 1.54%   |
| 0x306c3    | 1         | 1.54%   |
| 0x306a9    | 1         | 1.54%   |
| 0x20655    | 1         | 1.54%   |
| 0x106ca    | 1         | 1.54%   |
| 0x0a404102 | 1         | 1.54%   |
| 0x08608103 | 1         | 1.54%   |
| 0x08108102 | 1         | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Haswell          | 9         | 13.85%  |
| KabyLake         | 8         | 12.31%  |
| TigerLake        | 6         | 9.23%   |
| Zen 3            | 5         | 7.69%   |
| SandyBridge      | 5         | 7.69%   |
| IvyBridge        | 4         | 6.15%   |
| Zen+             | 3         | 4.62%   |
| Westmere         | 3         | 4.62%   |
| Penryn           | 3         | 4.62%   |
| Alderlake Hybrid | 3         | 4.62%   |
| Unknown          | 3         | 4.62%   |
| Skylake          | 2         | 3.08%   |
| Icelake          | 2         | 3.08%   |
| Goldmont plus    | 2         | 3.08%   |
| Zen 2            | 1         | 1.54%   |
| Goldmont         | 1         | 1.54%   |
| Excavator        | 1         | 1.54%   |
| Core             | 1         | 1.54%   |
| CometLake        | 1         | 1.54%   |
| Broadwell        | 1         | 1.54%   |
| Bonnell          | 1         | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 56.79%  |
| Nvidia | 20        | 24.69%  |
| AMD    | 15        | 18.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 5         | 6.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 4.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 4.88%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 4.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 4.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 3.66%   |
| Intel HD Graphics 620                                                     | 3         | 3.66%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 3.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 3.66%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 2         | 2.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.44%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 2.44%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 2         | 2.44%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 2.44%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 2.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 2.44%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 2.44%   |
| Nvidia TU117M                                                             | 1         | 1.22%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                         | 1         | 1.22%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.22%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 1.22%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 1.22%   |
| Nvidia GK208GLM [Quadro K610M]                                            | 1         | 1.22%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 1.22%   |
| Nvidia GK107M [GeForce GT 640M]                                           | 1         | 1.22%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 1.22%   |
| Nvidia GK104GLM [Quadro K3100M]                                           | 1         | 1.22%   |
| Nvidia GF119M [GeForce 410M]                                              | 1         | 1.22%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.22%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 1.22%   |
| Nvidia G86M [GeForce 8600M GS]                                            | 1         | 1.22%   |
| Intel UHD Graphics 620                                                    | 1         | 1.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.22%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.22%   |
| Intel HD Graphics 5500                                                    | 1         | 1.22%   |
| Intel HD Graphics 530                                                     | 1         | 1.22%   |
| Intel HD Graphics 500                                                     | 1         | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 50.77%  |
| Intel + Nvidia | 12        | 18.46%  |
| 1 x AMD        | 10        | 15.38%  |
| 1 x Nvidia     | 5         | 7.69%   |
| AMD + Nvidia   | 3         | 4.62%   |
| 2 x AMD        | 1         | 1.54%   |
| Intel + AMD    | 1         | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 56        | 84.85%  |
| Proprietary | 7         | 10.61%  |
| Unknown     | 3         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 71.21%  |
| 0.01-0.5   | 6         | 9.09%   |
| 3.01-4.0   | 5         | 7.58%   |
| 1.01-2.0   | 5         | 7.58%   |
| 0.51-1.0   | 2         | 3.03%   |
| 8.01-16.0  | 1         | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 24.66%  |
| BOE                     | 13        | 17.81%  |
| LG Display              | 9         | 12.33%  |
| Samsung Electronics     | 6         | 8.22%   |
| Chimei Innolux          | 6         | 8.22%   |
| Lenovo                  | 4         | 5.48%   |
| Dell                    | 3         | 4.11%   |
| Sharp                   | 2         | 2.74%   |
| InfoVision              | 2         | 2.74%   |
| Hewlett-Packard         | 2         | 2.74%   |
| Goldstar                | 2         | 2.74%   |
| ViewSonic               | 1         | 1.37%   |
| Insignia                | 1         | 1.37%   |
| HannStar                | 1         | 1.37%   |
| Fujitsu Siemens         | 1         | 1.37%   |
| Eizo                    | 1         | 1.37%   |
| Chi Mei Optoelectronics | 1         | 1.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE08CD 1366x768 344x194mm 15.5-inch                  | 3         | 4.11%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch             | 2         | 2.74%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 2.74%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 2         | 2.74%   |
| ViewSonic VA2265 SERIES VSCB330 1920x1080 476x268mm 21.5-inch         | 1         | 1.37%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 1.37%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.37%   |
| Samsung Electronics S23B350 SAM08F4 1920x1080 510x287mm 23.0-inch     | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC894F 1920x1080 344x194mm 15.5-inch | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch  | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 1.37%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 1.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0584 1920x1080 294x165mm 13.3-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 1.37%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 1.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 1.37%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 1.37%   |
| Lenovo LEN P32p-20 LEN62A2 3840x2160 697x392mm 31.5-inch              | 1         | 1.37%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 1.37%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 1         | 1.37%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch               | 1         | 1.37%   |
| Insignia NS39DR510NA17 BBY3963 1920x1080 853x480mm 38.5-inch          | 1         | 1.37%   |
| InfoVision LCD Monitor IVO3E94 1920x1200 345x215mm 16.0-inch          | 1         | 1.37%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 1.37%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 1.37%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1         | 1.37%   |
| Goldstar IPS235 GSM587D 1920x1080 510x290mm 23.1-inch                 | 1         | 1.37%   |
| Fujitsu Siemens 5110 FA FUS0420 1600x1200 408x306mm 20.1-inch         | 1         | 1.37%   |
| Eizo EV2450 ENC2568 1920x1080 528x297mm 23.9-inch                     | 1         | 1.37%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 1         | 1.37%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                    | 1         | 1.37%   |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 37        | 55.22%  |
| 1366x768 (WXGA)   | 19        | 28.36%  |
| 1920x1200 (WUXGA) | 2         | 2.99%   |
| 1600x900 (HD+)    | 2         | 2.99%   |
| 3840x2160 (4K)    | 1         | 1.49%   |
| 1920x515          | 1         | 1.49%   |
| 1600x1200         | 1         | 1.49%   |
| 1440x900 (WXGA+)  | 1         | 1.49%   |
| 1280x960          | 1         | 1.49%   |
| 1280x800 (WXGA)   | 1         | 1.49%   |
| 1024x600          | 1         | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 33        | 45.83%  |
| 14      | 8         | 11.11%  |
| 13      | 8         | 11.11%  |
| 17      | 6         | 8.33%   |
| 16      | 3         | 4.17%   |
| 27      | 2         | 2.78%   |
| 24      | 2         | 2.78%   |
| 23      | 2         | 2.78%   |
| 21      | 2         | 2.78%   |
| 38      | 1         | 1.39%   |
| 31      | 1         | 1.39%   |
| 20      | 1         | 1.39%   |
| 12      | 1         | 1.39%   |
| 10      | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 66.2%   |
| 351-400     | 8         | 11.27%  |
| 501-600     | 6         | 8.45%   |
| 201-300     | 4         | 5.63%   |
| 401-500     | 3         | 4.23%   |
| 801-900     | 1         | 1.41%   |
| 601-700     | 1         | 1.41%   |
| Unknown     | 1         | 1.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 58        | 89.23%  |
| 16/10 | 4         | 6.15%   |
| 4/3   | 2         | 3.08%   |
| 3.73  | 1         | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 47.89%  |
| 81-90          | 14        | 19.72%  |
| 121-130        | 7         | 9.86%   |
| 201-250        | 5         | 7.04%   |
| 71-80          | 2         | 2.82%   |
| 301-350        | 2         | 2.82%   |
| 61-70          | 1         | 1.41%   |
| 351-500        | 1         | 1.41%   |
| 41-50          | 1         | 1.41%   |
| 151-200        | 1         | 1.41%   |
| 111-120        | 1         | 1.41%   |
| 501-1000       | 1         | 1.41%   |
| Unknown        | 1         | 1.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 33        | 47.14%  |
| 101-120 | 21        | 30%     |
| 51-100  | 12        | 17.14%  |
| 161-240 | 3         | 4.29%   |
| Unknown | 1         | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 50        | 75.76%  |
| 2     | 10        | 15.15%  |
| 0     | 4         | 6.06%   |
| 3     | 2         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 38        | 36.54%  |
| Realtek Semiconductor    | 36        | 34.62%  |
| Qualcomm Atheros         | 13        | 12.5%   |
| Broadcom                 | 4         | 3.85%   |
| Ralink                   | 2         | 1.92%   |
| MediaTek                 | 2         | 1.92%   |
| Lenovo                   | 2         | 1.92%   |
| Broadcom Limited         | 2         | 1.92%   |
| TP-Link                  | 1         | 0.96%   |
| Sierra Wireless          | 1         | 0.96%   |
| Samsung Electronics      | 1         | 0.96%   |
| Qualcomm                 | 1         | 0.96%   |
| Marvell Technology Group | 1         | 0.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 17.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.03%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 3.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.42%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.42%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.61%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.61%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.61%   |
| Intel Wireless 8260                                               | 2         | 1.61%   |
| Intel Wireless 7265                                               | 2         | 1.61%   |
| Intel Wireless 7260                                               | 2         | 1.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.61%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.61%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.81%   |
| Sierra Wireless EM7455                                            | 1         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.81%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.81%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.81%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.81%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 56.25%  |
| Qualcomm Atheros      | 11        | 17.19%  |
| Realtek Semiconductor | 8         | 12.5%   |
| Ralink                | 2         | 3.13%   |
| MediaTek              | 2         | 3.13%   |
| Broadcom              | 2         | 3.13%   |
| Sierra Wireless       | 1         | 1.56%   |
| Qualcomm              | 1         | 1.56%   |
| Broadcom Limited      | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 4         | 6.06%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 4.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.03%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 3.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 3.03%   |
| Intel Wireless 8265 / 8275                                     | 2         | 3.03%   |
| Intel Wireless 8260                                            | 2         | 3.03%   |
| Intel Wireless 7265                                            | 2         | 3.03%   |
| Intel Wireless 7260                                            | 2         | 3.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 3.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 3.03%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 3.03%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 3.03%   |
| Sierra Wireless EM7455                                         | 1         | 1.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.52%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.52%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.52%   |
| Intel Wireless-AC 9260                                         | 1         | 1.52%   |
| Intel Wireless Gigabit 17265                                   | 1         | 1.52%   |
| Intel WiFi Link 5100                                           | 1         | 1.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 31        | 53.45%  |
| Intel                    | 15        | 25.86%  |
| Qualcomm Atheros         | 4         | 6.9%    |
| Lenovo                   | 2         | 3.45%   |
| Broadcom                 | 2         | 3.45%   |
| TP-Link                  | 1         | 1.72%   |
| Samsung Electronics      | 1         | 1.72%   |
| Marvell Technology Group | 1         | 1.72%   |
| Broadcom Limited         | 1         | 1.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 37.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 5.17%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 5.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.45%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.45%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.72%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 1.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.72%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.72%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.72%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.72%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.72%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.72%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.72%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.72%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.72%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 53.85%  |
| Ethernet | 54        | 46.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 72.46%  |
| Ethernet | 19        | 27.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 48        | 73.85%  |
| 1     | 13        | 20%     |
| 0     | 3         | 4.62%   |
| 3     | 1         | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 47        | 70.15%  |
| Yes  | 20        | 29.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 56.86%  |
| Realtek Semiconductor           | 5         | 9.8%    |
| Qualcomm Atheros Communications | 4         | 7.84%   |
| IMC Networks                    | 4         | 7.84%   |
| Broadcom                        | 3         | 5.88%   |
| Hewlett-Packard                 | 2         | 3.92%   |
| Ralink                          | 1         | 1.96%   |
| Lite-On Technology              | 1         | 1.96%   |
| Edimax Technology               | 1         | 1.96%   |
| Cambridge Silicon Radio         | 1         | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 7         | 13.73%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 13.73%  |
| Realtek Bluetooth Radio                                     | 4         | 7.84%   |
| Intel AX201 Bluetooth                                       | 4         | 7.84%   |
| Intel AX200 Bluetooth                                       | 4         | 7.84%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 3.92%   |
| Intel Bluetooth Device                                      | 2         | 3.92%   |
| Intel AX210 Bluetooth                                       | 2         | 3.92%   |
| IMC Networks Bluetooth Device                               | 2         | 3.92%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 3.92%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.96%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.96%   |
| Qualcomm Atheros  Bluetooth Device                          | 1         | 1.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.96%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.96%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.96%   |
| Lite-On Wireless_Device                                     | 1         | 1.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.96%   |
| IMC Networks Wireless_Device                                | 1         | 1.96%   |
| IMC Networks Atheros AR3012 Bluetooth                       | 1         | 1.96%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 1.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.96%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1         | 1.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.96%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 63.1%   |
| AMD                   | 13        | 15.48%  |
| Nvidia                | 10        | 11.9%   |
| Lenovo                | 2         | 2.38%   |
| C-Media Electronics   | 2         | 2.38%   |
| Realtek Semiconductor | 1         | 1.19%   |
| Plantronics           | 1         | 1.19%   |
| Logitech              | 1         | 1.19%   |
| GN Netcom             | 1         | 1.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 10.38%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 6.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 6.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 5.66%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 4.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 4.72%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.77%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 2.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 2.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.83%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.89%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.94%   |
| Plantronics Blackwire 3220 Series                                          | 1         | 0.94%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.94%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.94%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.94%   |
| Nvidia Audio device                                                        | 1         | 0.94%   |
| Logitech 960 Headset                                                       | 1         | 0.94%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 0.94%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.94%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 25%     |
| Micron Technology   | 8         | 18.18%  |
| SK hynix            | 6         | 13.64%  |
| Kingston            | 5         | 11.36%  |
| Unknown (ABCD)      | 3         | 6.82%   |
| Unknown             | 2         | 4.55%   |
| Crucial             | 2         | 4.55%   |
| Unknown             | 2         | 4.55%   |
| Toshiba             | 1         | 2.27%   |
| Smart               | 1         | 2.27%   |
| Qimonda             | 1         | 2.27%   |
| Corsair             | 1         | 2.27%   |
| A-DATA Technology   | 1         | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 6.38%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 4.26%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 2         | 4.26%   |
| Unknown                                                          | 2         | 4.26%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 2.13%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 2.13%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 2.13%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 1066MT/s            | 1         | 2.13%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s             | 1         | 2.13%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 1         | 2.13%   |
| Smart RAM SH564288FH8NWPHSFR 1024MB SODIMM DDR3 1067MT/s         | 1         | 2.13%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 2.13%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.13%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.13%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 2.13%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.13%   |
| Samsung RAM Module 32GB SODIMM DDR5 4800MT/s                     | 1         | 2.13%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 2.13%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.13%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 2.13%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.13%   |
| Qimonda RAM 64T256020EDL2.5C2 2GB SODIMM DDR2 2048MT/s           | 1         | 2.13%   |
| Micron RAM Module 16384MB SODIMM DDR4 3200MT/s                   | 1         | 2.13%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 2.13%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.13%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 2.13%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| Kingston RAM KKRVFX-MIE 8GB SODIMM DDR4 3200MT/s                 | 1         | 2.13%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 1         | 2.13%   |
| Kingston RAM ACR16D3LS1NBG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.13%   |
| Kingston RAM 99U5700-027.A00G 8GB SODIMM DDR4 2667MT/s           | 1         | 2.13%   |
| Kingston RAM 9905700-086.A00G 8GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB Row Of Chips DDR4 2400MT/s    | 1         | 2.13%   |
| Crucial RAM CT16G4SFD824A.M16FE 16384MB SODIMM DDR4 2400MT/s     | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 52.63%  |
| DDR3   | 7         | 18.42%  |
| LPDDR4 | 5         | 13.16%  |
| DDR2   | 3         | 7.89%   |
| SDRAM  | 1         | 2.63%   |
| LPDDR3 | 1         | 2.63%   |
| DDR5   | 1         | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 87.5%   |
| Row Of Chips | 5         | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 16        | 37.21%  |
| 4096  | 11        | 25.58%  |
| 16384 | 7         | 16.28%  |
| 32768 | 3         | 6.98%   |
| 2048  | 3         | 6.98%   |
| 1024  | 3         | 6.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 11        | 25.58%  |
| 2667  | 8         | 18.6%   |
| 2400  | 6         | 13.95%  |
| 1600  | 5         | 11.63%  |
| 4267  | 2         | 4.65%   |
| 1334  | 2         | 4.65%   |
| 1333  | 2         | 4.65%   |
| 667   | 2         | 4.65%   |
| 8400  | 1         | 2.33%   |
| 4800  | 1         | 2.33%   |
| 2133  | 1         | 2.33%   |
| 2048  | 1         | 2.33%   |
| 1066  | 1         | 2.33%   |

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
| Chicony Electronics                    | 18        | 27.27%  |
| Sunplus Innovation Technology          | 7         | 10.61%  |
| Bison Electronics                      | 5         | 7.58%   |
| Syntek                                 | 4         | 6.06%   |
| Microdia                               | 4         | 6.06%   |
| Luxvisions Innotech Limited            | 4         | 6.06%   |
| Alcor Micro                            | 4         | 6.06%   |
| Lite-On Technology                     | 3         | 4.55%   |
| IMC Networks                           | 3         | 4.55%   |
| Quanta                                 | 2         | 3.03%   |
| Logitech                               | 2         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.03%   |
| Acer                                   | 2         | 3.03%   |
| vivo                                   | 1         | 1.52%   |
| Suyin                                  | 1         | 1.52%   |
| Realtek Semiconductor                  | 1         | 1.52%   |
| Lenovo                                 | 1         | 1.52%   |
| kingcome                               | 1         | 1.52%   |
| 2M UVC CAMERA                          | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 6.06%   |
| Microdia Integrated_Webcam_HD                        | 3         | 4.55%   |
| Alcor Micro USB 2.0 Camera                           | 3         | 4.55%   |
| Syntek Integrated Camera                             | 2         | 3.03%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 3.03%   |
| Sunplus HD WebCam                                    | 2         | 3.03%   |
| Logitech HD Webcam C615                              | 2         | 3.03%   |
| Chicony FJ Camera                                    | 2         | 3.03%   |
| Bison Integrated Camera                              | 2         | 3.03%   |
| vivo V2023                                           | 1         | 1.52%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                 | 1         | 1.52%   |
| Syntek EasyCamera                                    | 1         | 1.52%   |
| Suyin USB 2.0 Camera                                 | 1         | 1.52%   |
| Sunplus Laptop Integrated Webcam HD                  | 1         | 1.52%   |
| Sunplus HD 720P webcam                               | 1         | 1.52%   |
| Sunplus Dell E5570 integrated webcam                 | 1         | 1.52%   |
| Realtek USB Camera                                   | 1         | 1.52%   |
| Quanta HP HD Camera                                  | 1         | 1.52%   |
| Quanta HD User Facing                                | 1         | 1.52%   |
| Microdia Integrated Webcam                           | 1         | 1.52%   |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.52%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.52%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.52%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 1.52%   |
| Lite-On TOSHIBA Web Camera - HD                      | 1         | 1.52%   |
| Lite-On Integrated Camera                            | 1         | 1.52%   |
| Lite-On HP HD Webcam                                 | 1         | 1.52%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.52%   |
| kingcome 480p VGA Camera                             | 1         | 1.52%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 1         | 1.52%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 1         | 1.52%   |
| IMC Networks Integrated Camera                       | 1         | 1.52%   |
| Chicony UVC 1.00 device HD UVC WebCam                | 1         | 1.52%   |
| Chicony USB2.0 VGA UVC WebCam                        | 1         | 1.52%   |
| Chicony USB2.0 Camera                                | 1         | 1.52%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 1         | 1.52%   |
| Chicony HP Wide Vision HD                            | 1         | 1.52%   |
| Chicony HP HD Webcam [Fixed]                         | 1         | 1.52%   |
| Chicony HP 5MP Camera                                | 1         | 1.52%   |
| Chicony HD Webcam                                    | 1         | 1.52%   |

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
| 0     | 32        | 48.48%  |
| 1     | 21        | 31.82%  |
| 2     | 11        | 16.67%  |
| 4     | 1         | 1.52%   |
| 3     | 1         | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 31.25%  |
| Chipcard              | 8         | 16.67%  |
| Graphics card         | 7         | 14.58%  |
| Net/wireless          | 5         | 10.42%  |
| Camera                | 4         | 8.33%   |
| Multimedia controller | 3         | 6.25%   |
| Sound                 | 2         | 4.17%   |
| Network               | 2         | 4.17%   |
| Card reader           | 1         | 2.08%   |
| Bluetooth             | 1         | 2.08%   |

