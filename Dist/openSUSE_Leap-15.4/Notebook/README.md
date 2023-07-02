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

Total: 98

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.14.21-150400.22-default    | 12        | 16.44%  |
| 5.14.21-150400.24.21-default | 9         | 12.33%  |
| 5.14.21-150400.24.38-default | 8         | 10.96%  |
| 5.14.21-150400.24.46-default | 7         | 9.59%   |
| 5.14.21-150400.24.41-default | 5         | 6.85%   |
| 5.14.21-150400.24.63-default | 4         | 5.48%   |
| 5.14.21-150400.24.33-default | 4         | 5.48%   |
| 5.14.21-150400.24.18-default | 4         | 5.48%   |
| 5.14.21-150400.19-default    | 4         | 5.48%   |
| 5.14.21-150400.24.60-default | 3         | 4.11%   |
| 5.14.21-150400.24.55-default | 3         | 4.11%   |
| 5.14.21-150400.24.11-default | 3         | 4.11%   |
| 5.14.21-150400.24.28-default | 2         | 2.74%   |
| 6.3.5-lp154.6-default        | 1         | 1.37%   |
| 5.14.21-150400.9-default     | 1         | 1.37%   |
| 5.14.21-150400.3-default     | 1         | 1.37%   |
| 5.14.21-150400.24.66-default | 1         | 1.37%   |
| 5.14.21-150400.15-default    | 1         | 1.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.21 | 63        | 98.44%  |
| 6.3.5   | 1         | 1.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 63        | 98.44%  |
| 6.3     | 1         | 1.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 64        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 47        | 73.44%  |
| GNOME      | 6         | 9.38%   |
| XFCE       | 3         | 4.69%   |
| Cinnamon   | 2         | 3.13%   |
| Unknown    | 2         | 3.13%   |
| X-Cinnamon | 1         | 1.56%   |
| LXDE       | 1         | 1.56%   |
| ICEWM      | 1         | 1.56%   |
| Deepin     | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 54        | 83.08%  |
| Wayland | 8         | 12.31%  |
| Tty     | 3         | 4.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 26        | 40.63%  |
| SDDM    | 25        | 39.06%  |
| LightDM | 10        | 15.63%  |
| XDM     | 3         | 4.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 22        | 34.38%  |
| de_DE | 13        | 20.31%  |
| pt_BR | 9         | 14.06%  |
| POSIX | 5         | 7.81%   |
| es_ES | 3         | 4.69%   |
| ru_RU | 2         | 3.13%   |
| nn_NO | 2         | 3.13%   |
| it_IT | 2         | 3.13%   |
| en_GB | 2         | 3.13%   |
| nl_NL | 1         | 1.56%   |
| hu_HU | 1         | 1.56%   |
| fr_FR | 1         | 1.56%   |
| en_IN | 1         | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 34        | 53.13%  |
| EFI  | 30        | 46.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 48        | 75%     |
| Ext4  | 11        | 17.19%  |
| Xfs   | 5         | 7.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 36        | 56.25%  |
| Unknown | 26        | 40.63%  |
| MBR     | 2         | 3.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 92.19%  |
| Yes       | 5         | 7.81%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 85.94%  |
| Yes       | 9         | 14.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 25%     |
| Hewlett-Packard     | 11        | 17.19%  |
| Dell                | 9         | 14.06%  |
| ASUSTek Computer    | 6         | 9.38%   |
| Acer                | 5         | 7.81%   |
| Toshiba             | 2         | 3.13%   |
| Samsung Electronics | 2         | 3.13%   |
| Fujitsu             | 2         | 3.13%   |
| Unknown             | 2         | 3.13%   |
| TUXEDO              | 1         | 1.56%   |
| Sony                | 1         | 1.56%   |
| Schenker            | 1         | 1.56%   |
| Notebook            | 1         | 1.56%   |
| Multilaser          | 1         | 1.56%   |
| MSI                 | 1         | 1.56%   |
| LG Electronics      | 1         | 1.56%   |
| Jumper              | 1         | 1.56%   |
| Gateway             | 1         | 1.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung 550XDA                           | 2         | 3.13%   |
| Unknown                                  | 2         | 3.13%   |
| TUXEDO InfinityBook S 15/17 Gen7         | 1         | 1.56%   |
| Toshiba Satellite P55t-A                 | 1         | 1.56%   |
| Toshiba Satellite L500                   | 1         | 1.56%   |
| Sony VPCEH25EN                           | 1         | 1.56%   |
| Schenker VIA 15 Pro                      | 1         | 1.56%   |
| Notebook NLx0MU                          | 1         | 1.56%   |
| Multilaser PC150                         | 1         | 1.56%   |
| MSI Delta 15 A5EFK                       | 1         | 1.56%   |
| LG C400-G.BC22P1                         | 1         | 1.56%   |
| Lenovo V15-ADA 82C7                      | 1         | 1.56%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDS3B600 | 1         | 1.56%   |
| Lenovo ThinkPad W541 20EF001UGE          | 1         | 1.56%   |
| Lenovo ThinkPad T530 2394D56             | 1         | 1.56%   |
| Lenovo ThinkPad T520 42435GG             | 1         | 1.56%   |
| Lenovo ThinkPad T495s 20QJ0012UK         | 1         | 1.56%   |
| Lenovo ThinkPad T470 20HES0FW00          | 1         | 1.56%   |
| Lenovo ThinkPad T410 25223FG             | 1         | 1.56%   |
| Lenovo ThinkPad T16 Gen 1 21BVCTO1WW     | 1         | 1.56%   |
| Lenovo ThinkPad P50 20EQS0VV0C           | 1         | 1.56%   |
| Lenovo ThinkPad P16s Gen 1 21BT000MUK    | 1         | 1.56%   |
| Lenovo ThinkPad Edge E530 3259HHG        | 1         | 1.56%   |
| Lenovo ThinkPad Edge E431 62779XP        | 1         | 1.56%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 1         | 1.56%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG     | 1         | 1.56%   |
| Lenovo IdeaPad 330-15IKB 81FD            | 1         | 1.56%   |
| Jumper EZbook                            | 1         | 1.56%   |
| HP ZBook 17 G2                           | 1         | 1.56%   |
| HP ZBook 17                              | 1         | 1.56%   |
| HP Victus by Laptop 16-e0xxx             | 1         | 1.56%   |
| HP ProBook 455 G8 Notebook PC            | 1         | 1.56%   |
| HP ProBook 4540s                         | 1         | 1.56%   |
| HP Pavilion Notebook                     | 1         | 1.56%   |
| HP Mini 210-1000                         | 1         | 1.56%   |
| HP Laptop 15s-eq0xxx                     | 1         | 1.56%   |
| HP EliteBook 865 16 inch G9 Notebook PC  | 1         | 1.56%   |
| HP EliteBook 840 G8 Notebook PC          | 1         | 1.56%   |
| HP Compaq 6730s                          | 1         | 1.56%   |
| Gateway NV55C                            | 1         | 1.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 12        | 18.75%  |
| Dell Inspiron       | 4         | 6.25%   |
| Lenovo IdeaPad      | 3         | 4.69%   |
| Dell Latitude       | 3         | 4.69%   |
| Acer Aspire         | 3         | 4.69%   |
| Toshiba Satellite   | 2         | 3.13%   |
| Samsung 550XDA      | 2         | 3.13%   |
| HP ZBook            | 2         | 3.13%   |
| HP ProBook          | 2         | 3.13%   |
| HP EliteBook        | 2         | 3.13%   |
| Fujitsu LIFEBOOK    | 2         | 3.13%   |
| Dell Vostro         | 2         | 3.13%   |
| Unknown             | 2         | 3.13%   |
| TUXEDO InfinityBook | 1         | 1.56%   |
| Sony VPCEH25EN      | 1         | 1.56%   |
| Schenker VIA        | 1         | 1.56%   |
| Notebook NLx0MU     | 1         | 1.56%   |
| Multilaser PC150    | 1         | 1.56%   |
| MSI Delta           | 1         | 1.56%   |
| LG C400-G.BC22P1    | 1         | 1.56%   |
| Lenovo V15-ADA      | 1         | 1.56%   |
| Jumper EZbook       | 1         | 1.56%   |
| HP Victus           | 1         | 1.56%   |
| HP Pavilion         | 1         | 1.56%   |
| HP Mini             | 1         | 1.56%   |
| HP Laptop           | 1         | 1.56%   |
| HP Compaq           | 1         | 1.56%   |
| Gateway NV55C       | 1         | 1.56%   |
| ASUS Z450LA         | 1         | 1.56%   |
| ASUS X55CR          | 1         | 1.56%   |
| ASUS ROG            | 1         | 1.56%   |
| ASUS N750JV         | 1         | 1.56%   |
| ASUS N550JX         | 1         | 1.56%   |
| ASUS F3Sv           | 1         | 1.56%   |
| Acer Swift          | 1         | 1.56%   |
| Acer Nitro          | 1         | 1.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 16        | 25%     |
| 2019 | 7         | 10.94%  |
| 2012 | 6         | 9.38%   |
| 2022 | 4         | 6.25%   |
| 2020 | 4         | 6.25%   |
| 2015 | 4         | 6.25%   |
| 2014 | 4         | 6.25%   |
| 2013 | 4         | 6.25%   |
| 2009 | 4         | 6.25%   |
| 2018 | 3         | 4.69%   |
| 2011 | 3         | 4.69%   |
| 2017 | 1         | 1.56%   |
| 2016 | 1         | 1.56%   |
| 2010 | 1         | 1.56%   |
| 2008 | 1         | 1.56%   |
| 2007 | 1         | 1.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 64        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 54        | 84.38%  |
| Enabled  | 10        | 15.63%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 15        | 23.44%  |
| 3.01-4.0    | 13        | 20.31%  |
| 16.01-24.0  | 10        | 15.63%  |
| 8.01-16.0   | 10        | 15.63%  |
| 32.01-64.0  | 7         | 10.94%  |
| 64.01-256.0 | 3         | 4.69%   |
| 24.01-32.0  | 2         | 3.13%   |
| 2.01-3.0    | 2         | 3.13%   |
| 1.01-2.0    | 1         | 1.56%   |
| 0.51-1.0    | 1         | 1.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 25        | 35.71%  |
| 4.01-8.0  | 16        | 22.86%  |
| 2.01-3.0  | 14        | 20%     |
| 3.01-4.0  | 7         | 10%     |
| 0.51-1.0  | 5         | 7.14%   |
| 8.01-16.0 | 2         | 2.86%   |
| 0.01-0.5  | 1         | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 73.85%  |
| 2      | 15        | 23.08%  |
| 4      | 1         | 1.54%   |
| 3      | 1         | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 68.75%  |
| Yes       | 20        | 31.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 84.38%  |
| No        | 10        | 15.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 98.44%  |
| No        | 1         | 1.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 78.13%  |
| No        | 14        | 21.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 14        | 21.88%  |
| USA          | 9         | 14.06%  |
| Brazil       | 9         | 14.06%  |
| Russia       | 4         | 6.25%   |
| Italy        | 4         | 6.25%   |
| UK           | 3         | 4.69%   |
| Spain        | 3         | 4.69%   |
| Norway       | 2         | 3.13%   |
| Netherlands  | 2         | 3.13%   |
| Mexico       | 2         | 3.13%   |
| France       | 2         | 3.13%   |
| Sweden       | 1         | 1.56%   |
| South Africa | 1         | 1.56%   |
| Slovenia     | 1         | 1.56%   |
| Serbia       | 1         | 1.56%   |
| Poland       | 1         | 1.56%   |
| Indonesia    | 1         | 1.56%   |
| India        | 1         | 1.56%   |
| Hungary      | 1         | 1.56%   |
| Czechia      | 1         | 1.56%   |
| Australia    | 1         | 1.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Madrid           | 3         | 4.48%   |
| Sao Paulo        | 2         | 2.99%   |
| Paris            | 2         | 2.99%   |
| London           | 2         | 2.99%   |
| Joinville        | 2         | 2.99%   |
| Berlin           | 2         | 2.99%   |
| Yekaterinburg    | 1         | 1.49%   |
| Vladivostok      | 1         | 1.49%   |
| Vaksdal          | 1         | 1.49%   |
| Sydney           | 1         | 1.49%   |
| Stockholm        | 1         | 1.49%   |
| Stazione-Fornola | 1         | 1.49%   |
| Skokie           | 1         | 1.49%   |
| Saki             | 1         | 1.49%   |
| Rome             | 1         | 1.49%   |
| Reggio Emilia    | 1         | 1.49%   |
| Recife           | 1         | 1.49%   |
| Pretoria         | 1         | 1.49%   |
| Poznan           | 1         | 1.49%   |
| Pirmasens        | 1         | 1.49%   |
| Peize            | 1         | 1.49%   |
| Pedro Leopoldo   | 1         | 1.49%   |
| Overland Park    | 1         | 1.49%   |
| Osorio           | 1         | 1.49%   |
| Oberhausen       | 1         | 1.49%   |
| Nuremberg        | 1         | 1.49%   |
| Novi Sad         | 1         | 1.49%   |
| Northallerton    | 1         | 1.49%   |
| Moscow           | 1         | 1.49%   |
| Mikulov          | 1         | 1.49%   |
| Mexico City      | 1         | 1.49%   |
| Merano           | 1         | 1.49%   |
| Maua             | 1         | 1.49%   |
| Louisville       | 1         | 1.49%   |
| Lesce            | 1         | 1.49%   |
| Lehrte           | 1         | 1.49%   |
| Lakeland         | 1         | 1.49%   |
| Jakarta          | 1         | 1.49%   |
| Ithaca           | 1         | 1.49%   |
| Itajaí          | 1         | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 16        | 21     | 20%     |
| Seagate                        | 10        | 11     | 12.5%   |
| WDC                            | 5         | 6      | 6.25%   |
| Toshiba                        | 5         | 7      | 6.25%   |
| SK hynix                       | 5         | 5      | 6.25%   |
| Unknown                        | 4         | 5      | 5%      |
| Kingston                       | 4         | 6      | 5%      |
| Crucial                        | 4         | 4      | 5%      |
| Sandisk                        | 3         | 3      | 3.75%   |
| Micron Technology              | 2         | 2      | 2.5%    |
| HGST                           | 2         | 2      | 2.5%    |
| A-DATA Technology              | 2         | 2      | 2.5%    |
| Unknown                        | 2         | 2      | 2.5%    |
| VISIPRO                        | 1         | 1      | 1.25%   |
| Union Memory (Shenzhen)        | 1         | 1      | 1.25%   |
| Solid State Storage Technology | 1         | 1      | 1.25%   |
| Solid State Storage            | 1         | 1      | 1.25%   |
| PNY                            | 1         | 2      | 1.25%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 1.25%   |
| KIOXIA                         | 1         | 1      | 1.25%   |
| Kingston Technology Company    | 1         | 1      | 1.25%   |
| JMicron Technology             | 1         | 1      | 1.25%   |
| Intenso                        | 1         | 1      | 1.25%   |
| Intel                          | 1         | 1      | 1.25%   |
| Hitachi                        | 1         | 2      | 1.25%   |
| Hewlett-Packard                | 1         | 3      | 1.25%   |
| Gigabyte Technology            | 1         | 1      | 1.25%   |
| China                          | 1         | 1      | 1.25%   |
| Biwin Storage Technology       | 1         | 1      | 1.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  128GB                            | 2         | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 2.38%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 2.38%   |
| Unknown                                            | 2         | 2.38%   |
| WDC WD3200BPVT-22JJ5T0 320GB                       | 1         | 1.19%   |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 1.19%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 1.19%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 1.19%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB               | 1         | 1.19%   |
| VISIPRO SSD 256GB                                  | 1         | 1.19%   |
| Unknown MMC Card  7GB                              | 1         | 1.19%   |
| Unknown MMC Card  32GB                             | 1         | 1.19%   |
| Unknown MMC Card  16GB                             | 1         | 1.19%   |
| Union Memory (Shenzhen) UMIS RPETJ1T24MGE2QDQ 1TB  | 1         | 1.19%   |
| Toshiba MQ04ABF100 1TB                             | 1         | 1.19%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1.19%   |
| Toshiba MQ01ABD050 500GB                           | 1         | 1.19%   |
| Toshiba MK5055GSX 500GB                            | 1         | 1.19%   |
| Toshiba MK3265GSX 320GB                            | 1         | 1.19%   |
| Solid State Storage NVMe SSD Drive 256GB           | 1         | 1.19%   |
| Solid State Storage CL1-3D512-Q11 NVMe SSSTC 512GB | 1         | 1.19%   |
| SK hynix SC300 M.2 2280 256GB SSD                  | 1         | 1.19%   |
| SK hynix NVMe SSD Drive 512GB                      | 1         | 1.19%   |
| SK hynix BC711 NVMe 512GB                          | 1         | 1.19%   |
| SK hynix BC711 HFM512GD3JX013N 512GB               | 1         | 1.19%   |
| SK hynix BC501 NVMe Solid State Drive 512GB        | 1         | 1.19%   |
| Seagate ST9500325AS 500GB                          | 1         | 1.19%   |
| Seagate ST9250827AS 250GB                          | 1         | 1.19%   |
| Seagate ST320LT007-9ZV142 320GB                    | 1         | 1.19%   |
| Seagate ST2000LM015-2E8174 2TB                     | 1         | 1.19%   |
| Seagate ST1000LX015-1U7172 1TB                     | 1         | 1.19%   |
| Seagate ST1000LM048-2E7172 1TB                     | 1         | 1.19%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 1.19%   |
| Seagate ST1000LM014-1EJ164 1TB                     | 1         | 1.19%   |
| Sandisk WD Black SN850 1TB                         | 1         | 1.19%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 1         | 1.19%   |
| SanDisk NVMe SSD Drive 256GB                       | 1         | 1.19%   |
| Samsung SSD PM851 2.5 7mm 128GB                    | 1         | 1.19%   |
| Samsung SSD 980 PRO 2TB                            | 1         | 1.19%   |

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
| NVMe    | 28        | 32     | 36.36%  |
| SSD     | 23        | 32     | 29.87%  |
| HDD     | 21        | 26     | 27.27%  |
| MMC     | 4         | 5      | 5.19%   |
| Unknown | 1         | 1      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 57     | 55.41%  |
| NVMe | 28        | 32     | 37.84%  |
| MMC  | 4         | 5      | 5.41%   |
| SAS  | 1         | 2      | 1.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 40     | 61.36%  |
| 0.51-1.0   | 14        | 15     | 31.82%  |
| 1.01-2.0   | 3         | 3      | 6.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 18        | 28.13%  |
| 1001-2000      | 15        | 23.44%  |
| 2001-3000      | 10        | 15.63%  |
| 251-500        | 8         | 12.5%   |
| 501-1000       | 7         | 10.94%  |
| 101-250        | 5         | 7.81%   |
| Unknown        | 1         | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 34.29%  |
| 51-100         | 11        | 15.71%  |
| 251-500        | 10        | 14.29%  |
| 1-20           | 9         | 12.86%  |
| 501-1000       | 6         | 8.57%   |
| More than 3000 | 4         | 5.71%   |
| 1001-2000      | 4         | 5.71%   |
| 2001-3000      | 1         | 1.43%   |
| Unknown        | 1         | 1.43%   |

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
| Works    | 31        | 38     | 46.27%  |
| Detected | 30        | 48     | 44.78%  |
| Malfunc  | 6         | 10     | 8.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 47        | 59.49%  |
| Samsung Electronics            | 8         | 10.13%  |
| SanDisk                        | 5         | 6.33%   |
| AMD                            | 5         | 6.33%   |
| SK hynix                       | 4         | 5.06%   |
| Solid State Storage Technology | 2         | 2.53%   |
| Micron Technology              | 2         | 2.53%   |
| Kingston Technology Company    | 2         | 2.53%   |
| Union Memory (Shenzhen)        | 1         | 1.27%   |
| MAXIO Technology (Hangzhou)    | 1         | 1.27%   |
| KIOXIA                         | 1         | 1.27%   |
| Biwin Storage Technology       | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 7.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 6.1%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 6.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 4.88%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 3.66%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 3.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 3.66%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 3.66%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 3.66%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 3.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 3.66%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.44%   |
| Micron NVMe Storage Controller                                                 | 2         | 2.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 2.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 2.44%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 1.22%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.22%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.22%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 1.22%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602                                   | 1         | 1.22%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.22%   |
| Kingston Company NVMe Controller                                               | 1         | 1.22%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.22%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 1.22%   |
| Intel SSD 600P Series                                                          | 1         | 1.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.22%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.22%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.22%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 46        | 57.5%   |
| NVMe | 27        | 33.75%  |
| RAID | 5         | 6.25%   |
| IDE  | 2         | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 81.25%  |
| AMD    | 12        | 18.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 3.13%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 3.13%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 3.13%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 3.13%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 3.13%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 2         | 3.13%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 3.13%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 3.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 3.13%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 3.13%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 3.13%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 3.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.13%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.56%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 1.56%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.56%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 1.56%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.56%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 1.56%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.56%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.56%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.56%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.56%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 1.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.56%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.56%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 1.56%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 1.56%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.56%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz          | 1         | 1.56%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 1         | 1.56%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1         | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 12        | 18.75%  |
| Intel Core i5           | 12        | 18.75%  |
| Other                   | 10        | 15.63%  |
| Intel Core i3           | 8         | 12.5%   |
| AMD Ryzen 5             | 5         | 7.81%   |
| AMD Ryzen 7             | 4         | 6.25%   |
| Intel Core 2 Duo        | 3         | 4.69%   |
| Intel Celeron           | 3         | 4.69%   |
| Intel Pentium           | 2         | 3.13%   |
| Intel Pentium Dual-Core | 1         | 1.56%   |
| Intel Atom              | 1         | 1.56%   |
| AMD Ryzen 9             | 1         | 1.56%   |
| AMD Ryzen 7 PRO         | 1         | 1.56%   |
| AMD A4                  | 1         | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 42.19%  |
| 4      | 20        | 31.25%  |
| 8      | 6         | 9.38%   |
| 6      | 6         | 9.38%   |
| 12     | 2         | 3.13%   |
| 1      | 2         | 3.13%   |
| 10     | 1         | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 64        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 52        | 81.25%  |
| 1      | 12        | 18.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 64        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 40.63%  |
| 0x806c1    | 5         | 7.81%   |
| 0x206a7    | 3         | 4.69%   |
| 0x0a50000c | 3         | 4.69%   |
| 0x906a3    | 2         | 3.13%   |
| 0x706a8    | 2         | 3.13%   |
| 0x1067a    | 2         | 3.13%   |
| 0x08108109 | 2         | 3.13%   |
| 0x906ea    | 1         | 1.56%   |
| 0x906a4    | 1         | 1.56%   |
| 0x806ec    | 1         | 1.56%   |
| 0x806ea    | 1         | 1.56%   |
| 0x806e9    | 1         | 1.56%   |
| 0x806d1    | 1         | 1.56%   |
| 0x706e5    | 1         | 1.56%   |
| 0x6fb      | 1         | 1.56%   |
| 0x506e3    | 1         | 1.56%   |
| 0x506ca    | 1         | 1.56%   |
| 0x406e3    | 1         | 1.56%   |
| 0x40651    | 1         | 1.56%   |
| 0x306c3    | 1         | 1.56%   |
| 0x306a9    | 1         | 1.56%   |
| 0x20655    | 1         | 1.56%   |
| 0x106ca    | 1         | 1.56%   |
| 0x0a404102 | 1         | 1.56%   |
| 0x08608103 | 1         | 1.56%   |
| 0x08108102 | 1         | 1.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Haswell          | 9         | 14.06%  |
| KabyLake         | 8         | 12.5%   |
| Zen 3            | 5         | 7.81%   |
| TigerLake        | 5         | 7.81%   |
| SandyBridge      | 5         | 7.81%   |
| IvyBridge        | 4         | 6.25%   |
| Zen+             | 3         | 4.69%   |
| Westmere         | 3         | 4.69%   |
| Penryn           | 3         | 4.69%   |
| Alderlake Hybrid | 3         | 4.69%   |
| Unknown          | 3         | 4.69%   |
| Skylake          | 2         | 3.13%   |
| Icelake          | 2         | 3.13%   |
| Goldmont plus    | 2         | 3.13%   |
| Zen 2            | 1         | 1.56%   |
| Goldmont         | 1         | 1.56%   |
| Excavator        | 1         | 1.56%   |
| Core             | 1         | 1.56%   |
| CometLake        | 1         | 1.56%   |
| Broadwell        | 1         | 1.56%   |
| Bonnell          | 1         | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 56.25%  |
| Nvidia | 20        | 25%     |
| AMD    | 15        | 18.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 5         | 6.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 4.94%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 4.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 4.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 3.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 3.7%    |
| Intel HD Graphics 620                                                     | 3         | 3.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 3.7%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 2         | 2.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.47%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 2.47%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 2         | 2.47%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 2.47%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 2.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 2.47%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 2.47%   |
| Nvidia TU117M                                                             | 1         | 1.23%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                         | 1         | 1.23%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.23%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 1.23%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 1.23%   |
| Nvidia GK208GLM [Quadro K610M]                                            | 1         | 1.23%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 1.23%   |
| Nvidia GK107M [GeForce GT 640M]                                           | 1         | 1.23%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 1.23%   |
| Nvidia GK104GLM [Quadro K3100M]                                           | 1         | 1.23%   |
| Nvidia GF119M [GeForce 410M]                                              | 1         | 1.23%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.23%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 1.23%   |
| Nvidia G86M [GeForce 8600M GS]                                            | 1         | 1.23%   |
| Intel UHD Graphics 620                                                    | 1         | 1.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.23%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 1.23%   |
| Intel HD Graphics 5500                                                    | 1         | 1.23%   |
| Intel HD Graphics 530                                                     | 1         | 1.23%   |
| Intel HD Graphics 500                                                     | 1         | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 50%     |
| Intel + Nvidia | 12        | 18.75%  |
| 1 x AMD        | 10        | 15.63%  |
| 1 x Nvidia     | 5         | 7.81%   |
| AMD + Nvidia   | 3         | 4.69%   |
| 2 x AMD        | 1         | 1.56%   |
| Intel + AMD    | 1         | 1.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 55        | 84.62%  |
| Proprietary | 7         | 10.77%  |
| Unknown     | 3         | 4.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 70.77%  |
| 0.01-0.5   | 6         | 9.23%   |
| 3.01-4.0   | 5         | 7.69%   |
| 1.01-2.0   | 5         | 7.69%   |
| 0.51-1.0   | 2         | 3.08%   |
| 8.01-16.0  | 1         | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 23.94%  |
| BOE                     | 12        | 16.9%   |
| LG Display              | 9         | 12.68%  |
| Samsung Electronics     | 6         | 8.45%   |
| Chimei Innolux          | 6         | 8.45%   |
| Lenovo                  | 4         | 5.63%   |
| Dell                    | 3         | 4.23%   |
| Sharp                   | 2         | 2.82%   |
| InfoVision              | 2         | 2.82%   |
| Hewlett-Packard         | 2         | 2.82%   |
| Goldstar                | 2         | 2.82%   |
| ViewSonic               | 1         | 1.41%   |
| Insignia                | 1         | 1.41%   |
| HannStar                | 1         | 1.41%   |
| Fujitsu Siemens         | 1         | 1.41%   |
| Eizo                    | 1         | 1.41%   |
| Chi Mei Optoelectronics | 1         | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE08CD 1366x768 344x194mm 15.5-inch                  | 3         | 4.23%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch             | 2         | 2.82%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 2.82%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 2         | 2.82%   |
| ViewSonic VA2265 SERIES VSCB330 1920x1080 476x268mm 21.5-inch         | 1         | 1.41%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 1.41%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 1.41%   |
| Samsung Electronics S23B350 SAM08F4 1920x1080 510x287mm 23.0-inch     | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SDC894F 1920x1080 344x194mm 15.5-inch | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch  | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 1.41%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD0584 1920x1080 294x165mm 13.3-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 1.41%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 1.41%   |
| Lenovo LEN P32p-20 LEN62A2 3840x2160 697x392mm 31.5-inch              | 1         | 1.41%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 1.41%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch               | 1         | 1.41%   |
| Insignia NS39DR510NA17 BBY3963 1920x1080 853x480mm 38.5-inch          | 1         | 1.41%   |
| InfoVision LCD Monitor IVO3E94 1920x1200 345x215mm 16.0-inch          | 1         | 1.41%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 1.41%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch              | 1         | 1.41%   |
| Goldstar T710SH GSM436B 1280x960 310x230mm 15.2-inch                  | 1         | 1.41%   |
| Goldstar IPS235 GSM587D 1920x1080 510x290mm 23.1-inch                 | 1         | 1.41%   |
| Fujitsu Siemens 5110 FA FUS0420 1600x1200 408x306mm 20.1-inch         | 1         | 1.41%   |
| Eizo EV2450 ENC2568 1920x1080 528x297mm 23.9-inch                     | 1         | 1.41%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 1         | 1.41%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                    | 1         | 1.41%   |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 1         | 1.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 36        | 55.38%  |
| 1366x768 (WXGA)   | 19        | 29.23%  |
| 1920x1200 (WUXGA) | 2         | 3.08%   |
| 1600x900 (HD+)    | 2         | 3.08%   |
| 3840x2160 (4K)    | 1         | 1.54%   |
| 1600x1200         | 1         | 1.54%   |
| 1440x900 (WXGA+)  | 1         | 1.54%   |
| 1280x960          | 1         | 1.54%   |
| 1280x800 (WXGA)   | 1         | 1.54%   |
| 1024x600          | 1         | 1.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 33        | 47.14%  |
| 13     | 8         | 11.43%  |
| 14     | 7         | 10%     |
| 17     | 6         | 8.57%   |
| 16     | 3         | 4.29%   |
| 27     | 2         | 2.86%   |
| 24     | 2         | 2.86%   |
| 23     | 2         | 2.86%   |
| 21     | 2         | 2.86%   |
| 38     | 1         | 1.43%   |
| 31     | 1         | 1.43%   |
| 20     | 1         | 1.43%   |
| 12     | 1         | 1.43%   |
| 10     | 1         | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 66.67%  |
| 351-400     | 8         | 11.59%  |
| 501-600     | 6         | 8.7%    |
| 201-300     | 4         | 5.8%    |
| 401-500     | 3         | 4.35%   |
| 801-900     | 1         | 1.45%   |
| 601-700     | 1         | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 57        | 90.48%  |
| 16/10 | 4         | 6.35%   |
| 4/3   | 2         | 3.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 49.28%  |
| 81-90          | 13        | 18.84%  |
| 121-130        | 7         | 10.14%  |
| 201-250        | 5         | 7.25%   |
| 71-80          | 2         | 2.9%    |
| 301-350        | 2         | 2.9%    |
| 61-70          | 1         | 1.45%   |
| 351-500        | 1         | 1.45%   |
| 41-50          | 1         | 1.45%   |
| 151-200        | 1         | 1.45%   |
| 111-120        | 1         | 1.45%   |
| 501-1000       | 1         | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 32        | 47.06%  |
| 101-120 | 21        | 30.88%  |
| 51-100  | 12        | 17.65%  |
| 161-240 | 3         | 4.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 50        | 76.92%  |
| 2     | 9         | 13.85%  |
| 0     | 4         | 6.15%   |
| 3     | 2         | 3.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 37        | 35.92%  |
| Realtek Semiconductor    | 36        | 34.95%  |
| Qualcomm Atheros         | 13        | 12.62%  |
| Broadcom                 | 4         | 3.88%   |
| Ralink                   | 2         | 1.94%   |
| MediaTek                 | 2         | 1.94%   |
| Lenovo                   | 2         | 1.94%   |
| Broadcom Limited         | 2         | 1.94%   |
| TP-Link                  | 1         | 0.97%   |
| Sierra Wireless          | 1         | 0.97%   |
| Samsung Electronics      | 1         | 0.97%   |
| Qualcomm                 | 1         | 0.97%   |
| Marvell Technology Group | 1         | 0.97%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 17.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.44%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.44%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.44%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.63%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 1.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.63%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.63%   |
| Intel Wireless 8260                                               | 2         | 1.63%   |
| Intel Wireless 7265                                               | 2         | 1.63%   |
| Intel Wireless 7260                                               | 2         | 1.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.63%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 1.63%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.63%   |
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
| Intel                 | 35        | 55.56%  |
| Qualcomm Atheros      | 11        | 17.46%  |
| Realtek Semiconductor | 8         | 12.7%   |
| Ralink                | 2         | 3.17%   |
| MediaTek              | 2         | 3.17%   |
| Broadcom              | 2         | 3.17%   |
| Sierra Wireless       | 1         | 1.59%   |
| Qualcomm              | 1         | 1.59%   |
| Broadcom Limited      | 1         | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 3         | 4.62%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 4.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 4.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 3.08%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 3.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 3.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 3.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 3.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 3.08%   |
| Intel Wireless 8265 / 8275                                     | 2         | 3.08%   |
| Intel Wireless 8260                                            | 2         | 3.08%   |
| Intel Wireless 7265                                            | 2         | 3.08%   |
| Intel Wireless 7260                                            | 2         | 3.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 3.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 3.08%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 3.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 3.08%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 3.08%   |
| Sierra Wireless EM7455                                         | 1         | 1.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.54%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.54%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.54%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.54%   |
| Intel Wireless-AC 9260                                         | 1         | 1.54%   |
| Intel Wireless Gigabit 17265                                   | 1         | 1.54%   |
| Intel WiFi Link 5100                                           | 1         | 1.54%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.54%   |

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
| WiFi     | 62        | 53.45%  |
| Ethernet | 54        | 46.55%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 72.06%  |
| Ethernet | 19        | 27.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 48        | 75%     |
| 1     | 12        | 18.75%  |
| 0     | 3         | 4.69%   |
| 3     | 1         | 1.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 46        | 69.7%   |
| Yes  | 20        | 30.3%   |

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
| Intel                 | 52        | 62.65%  |
| AMD                   | 13        | 15.66%  |
| Nvidia                | 10        | 12.05%  |
| Lenovo                | 2         | 2.41%   |
| C-Media Electronics   | 2         | 2.41%   |
| Realtek Semiconductor | 1         | 1.2%    |
| Plantronics           | 1         | 1.2%    |
| Logitech              | 1         | 1.2%    |
| GN Netcom             | 1         | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 10.48%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 6.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 6.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 4.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 4.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.81%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.86%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 2.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 2.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.86%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.9%    |
| Realtek Semiconductor USB Audio                                            | 1         | 0.95%   |
| Plantronics Blackwire 3220 Series                                          | 1         | 0.95%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.95%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.95%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.95%   |
| Nvidia Audio device                                                        | 1         | 0.95%   |
| Logitech 960 Headset                                                       | 1         | 0.95%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 0.95%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 0.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.95%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.95%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.95%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.95%   |

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
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 6.52%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 4.35%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 2         | 4.35%   |
| Unknown                                                          | 2         | 4.35%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 2.17%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 2.17%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 2.17%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 2.17%   |
| Toshiba RAM 64T128020EDL2.5C2 1GB SODIMM 1066MT/s                | 1         | 2.17%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 1         | 2.17%   |
| Smart RAM SH564288FH8NWPHSFR 1024MB SODIMM DDR3 1067MT/s         | 1         | 2.17%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 2.17%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 2.17%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.17%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.17%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 2.17%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.17%   |
| Samsung RAM Module 32GB SODIMM DDR5 4800MT/s                     | 1         | 2.17%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 2.17%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 2.17%   |
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
| Crucial RAM CT16G4SFD824A.M16FE 16384MB SODIMM DDR4 2400MT/s     | 1         | 2.17%   |
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
| Chicony Electronics                    | 18        | 27.69%  |
| Sunplus Innovation Technology          | 7         | 10.77%  |
| Bison Electronics                      | 5         | 7.69%   |
| Syntek                                 | 4         | 6.15%   |
| Microdia                               | 4         | 6.15%   |
| Luxvisions Innotech Limited            | 4         | 6.15%   |
| Alcor Micro                            | 4         | 6.15%   |
| Lite-On Technology                     | 3         | 4.62%   |
| Quanta                                 | 2         | 3.08%   |
| Logitech                               | 2         | 3.08%   |
| IMC Networks                           | 2         | 3.08%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.08%   |
| Acer                                   | 2         | 3.08%   |
| vivo                                   | 1         | 1.54%   |
| Suyin                                  | 1         | 1.54%   |
| Realtek Semiconductor                  | 1         | 1.54%   |
| Lenovo                                 | 1         | 1.54%   |
| kingcome                               | 1         | 1.54%   |
| 2M UVC CAMERA                          | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 6.15%   |
| Microdia Integrated_Webcam_HD                        | 3         | 4.62%   |
| Alcor Micro USB 2.0 Camera                           | 3         | 4.62%   |
| Syntek Integrated Camera                             | 2         | 3.08%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 3.08%   |
| Sunplus HD WebCam                                    | 2         | 3.08%   |
| Logitech HD Webcam C615                              | 2         | 3.08%   |
| Chicony FJ Camera                                    | 2         | 3.08%   |
| Bison Integrated Camera                              | 2         | 3.08%   |
| vivo V2023                                           | 1         | 1.54%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                 | 1         | 1.54%   |
| Syntek EasyCamera                                    | 1         | 1.54%   |
| Suyin USB 2.0 Camera                                 | 1         | 1.54%   |
| Sunplus Laptop Integrated Webcam HD                  | 1         | 1.54%   |
| Sunplus HD 720P webcam                               | 1         | 1.54%   |
| Sunplus Dell E5570 integrated webcam                 | 1         | 1.54%   |
| Realtek USB2.0 camera                                | 1         | 1.54%   |
| Quanta HP HD Camera                                  | 1         | 1.54%   |
| Quanta HD User Facing                                | 1         | 1.54%   |
| Microdia Integrated Webcam                           | 1         | 1.54%   |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.54%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.54%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 1.54%   |
| Lite-On TOSHIBA Web Camera - HD                      | 1         | 1.54%   |
| Lite-On Integrated Camera                            | 1         | 1.54%   |
| Lite-On HP HD Webcam                                 | 1         | 1.54%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.54%   |
| kingcome 480p VGA Camera                             | 1         | 1.54%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 1         | 1.54%   |
| IMC Networks Integrated Camera                       | 1         | 1.54%   |
| Chicony UVC 1.00 device HD UVC WebCam                | 1         | 1.54%   |
| Chicony USB2.0 VGA UVC WebCam                        | 1         | 1.54%   |
| Chicony USB2.0 Camera                                | 1         | 1.54%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 1         | 1.54%   |
| Chicony HP Wide Vision HD                            | 1         | 1.54%   |
| Chicony HP HD Webcam [Fixed]                         | 1         | 1.54%   |
| Chicony HP 5MP Camera                                | 1         | 1.54%   |
| Chicony HD Webcam                                    | 1         | 1.54%   |
| Chicony HD User Facing                               | 1         | 1.54%   |

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
| 0     | 32        | 49.23%  |
| 1     | 20        | 30.77%  |
| 2     | 11        | 16.92%  |
| 4     | 1         | 1.54%   |
| 3     | 1         | 1.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 31.91%  |
| Chipcard              | 8         | 17.02%  |
| Graphics card         | 7         | 14.89%  |
| Net/wireless          | 5         | 10.64%  |
| Multimedia controller | 3         | 6.38%   |
| Camera                | 3         | 6.38%   |
| Sound                 | 2         | 4.26%   |
| Network               | 2         | 4.26%   |
| Card reader           | 1         | 2.13%   |
| Bluetooth             | 1         | 2.13%   |

