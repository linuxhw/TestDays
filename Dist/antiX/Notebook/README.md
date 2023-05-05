antiX - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for antiX.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu       | FMVNU6G1C                   | [969957b527](https://linux-hardware.org/?probe=969957b527) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [52086c894a](https://linux-hardware.org/?probe=52086c894a) | Apr 24, 2023 |
| Intel         | powered classmate PC        | [79b262de52](https://linux-hardware.org/?probe=79b262de52) | Apr 12, 2023 |
| Acer          | Aspire E5-511               | [f66d23c175](https://linux-hardware.org/?probe=f66d23c175) | Apr 10, 2023 |
| HP            | G61                         | [d00ad3f0fb](https://linux-hardware.org/?probe=d00ad3f0fb) | Apr 07, 2023 |
| Acer          | Aspire 4315                 | [0bf18c8c90](https://linux-hardware.org/?probe=0bf18c8c90) | Mar 26, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [1525ad44e2](https://linux-hardware.org/?probe=1525ad44e2) | Mar 12, 2023 |
| Acer          | Aspire E1-572               | [bde56e1cc3](https://linux-hardware.org/?probe=bde56e1cc3) | Mar 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [ffbffb33ae](https://linux-hardware.org/?probe=ffbffb33ae) | Mar 09, 2023 |
| Acer          | Aspire 5740                 | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
| Acer          | Aspire E5-571G              | [07fe4333eb](https://linux-hardware.org/?probe=07fe4333eb) | Feb 25, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [7e8f09a90e](https://linux-hardware.org/?probe=7e8f09a90e) | Feb 07, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [30676c5e14](https://linux-hardware.org/?probe=30676c5e14) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08bf9ddbcf](https://linux-hardware.org/?probe=08bf9ddbcf) | Feb 05, 2023 |
| Dell          | Latitude 2120               | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Toshiba       | Satellite C50-A-1HF         | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
| Lenovo        | 3000 V100 076346G           | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| Acer          | Aspire 7520                 | [d2f4caca66](https://linux-hardware.org/?probe=d2f4caca66) | Nov 22, 2022 |
| ASUSTek       | S3N                         | [e4c4a500b8](https://linux-hardware.org/?probe=e4c4a500b8) | Nov 21, 2022 |
| Google        | Candy                       | [5c5ea3b081](https://linux-hardware.org/?probe=5c5ea3b081) | Nov 17, 2022 |
| HP            | Mini 110-3700               | [4e9f54f23c](https://linux-hardware.org/?probe=4e9f54f23c) | Nov 15, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [213d8f5688](https://linux-hardware.org/?probe=213d8f5688) | Nov 13, 2022 |
| Fujitsu       | FMVNU6G1C                   | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| ASUSTek       | 1011CX                      | [4ce8b4c2fe](https://linux-hardware.org/?probe=4ce8b4c2fe) | Sep 18, 2022 |
| KOHJINSHA     | SC series                   | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| IBM           | 260921H                     | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Lenovo        | ThinkPad X201 3249CTO       | [f6a90dcc74](https://linux-hardware.org/?probe=f6a90dcc74) | Jul 16, 2022 |
| IBM           | 260921H                     | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| Lenovo        | Unknown                     | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Compaq        | Tablet PC TC1000            | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [e904df65f2](https://linux-hardware.org/?probe=e904df65f2) | Jun 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [cb13f37895](https://linux-hardware.org/?probe=cb13f37895) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Lenovo        | G550 2958                   | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Acer          | Aspire 5920G                | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| Packard Be... | EasyNote_MX37-U-057NL       | [41760b3852](https://linux-hardware.org/?probe=41760b3852) | Apr 27, 2022 |
| Apple         | MacBook7,1                  | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP            | EliteBook 2570p             | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba       | Satellite 1905              | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek       | X71SL                       | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek       | A3L                         | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek       | A3L                         | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek       | X51RL                       | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer          | AOA150                      | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell          | Latitude E6400              | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI           | GE62 7RE                    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI           | GE62 7RE                    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| HP            | EliteBook 8770w             | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu       | FMVS54EB                    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Latitude 5480               | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| HP            | Mini 110-3700               | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| IBM           | ThinkPad T41 2374K50        | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM           | ThinkPad T41 2374K50        | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM           | ThinkPad T43 2668WEJ        | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP            | Pavilion dv2700             | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP            | Mini 5101                   | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek       | 900A                        | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek       | 900HA                       | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion        | WIM2170                     | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion        | WIM2170                     | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| antiX 21       | 22        | 40%     |
| antiX 22       | 14        | 25.45%  |
| antiX 19.2     | 6         | 10.91%  |
| antiX 19.3     | 3         | 5.45%   |
| antiX 21-runit | 2         | 3.64%   |
| antiX 19.4     | 2         | 3.64%   |
| antiX 19.1     | 2         | 3.64%   |
| antiX 19.5     | 1         | 1.82%   |
| antiX 17.4.1   | 1         | 1.82%   |
| antiX 17.2.1   | 1         | 1.82%   |
| antiX 17       | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 54        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 14        | 25.45%  |
| 5.10.142-antix.2-amd64-smp   | 6         | 10.91%  |
| 4.9.0-326-antix.1-amd64-smp  | 5         | 9.09%   |
| 5.10.57-antix.1-amd64-smp    | 4         | 7.27%   |
| 4.9.0-279-antix.1-amd64-smp  | 4         | 7.27%   |
| 4.9.0-326-antix.1-486-smp    | 3         | 5.45%   |
| 4.9.235-antix.1-amd64-smp    | 2         | 3.64%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 3.64%   |
| 4.9.212-antix.1-486-smp      | 2         | 3.64%   |
| 4.9.200-antix.1-486-smp      | 2         | 3.64%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.82%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 1.82%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.82%   |
| 4.9.160-antix.2-486-smp      | 1         | 1.82%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.82%   |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 1.82%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.82%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.82%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.82%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.82%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 27        | 50%     |
| 5.10.142 | 6         | 11.11%  |
| 5.10.57  | 4         | 7.41%   |
| 4.9.212  | 4         | 7.41%   |
| 4.9.235  | 2         | 3.7%    |
| 4.9.200  | 2         | 3.7%    |
| 4.9.160  | 2         | 3.7%    |
| 5.14.0   | 1         | 1.85%   |
| 5.10.88  | 1         | 1.85%   |
| 5.10.27  | 1         | 1.85%   |
| 4.19.202 | 1         | 1.85%   |
| 4.19.100 | 1         | 1.85%   |
| 4.19.0   | 1         | 1.85%   |
| 4.10.5   | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 37        | 68.52%  |
| 5.10    | 12        | 22.22%  |
| 4.19    | 3         | 5.56%   |
| 5.14    | 1         | 1.85%   |
| 4.10    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 51.85%  |
| i686   | 25        | 46.3%   |
| i586   | 1         | 1.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 26        | 48.15%  |
| icewm   | 24        | 44.44%  |
| fluxbox | 2         | 3.7%    |
| XFCE    | 1         | 1.85%   |
| GNOME   | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 54        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 31        | 57.41%  |
| SLiM    | 15        | 27.78%  |
| SLIMSKI | 3         | 5.56%   |
| LightDM | 3         | 5.56%   |
| XDM     | 1         | 1.85%   |
| SDDM    | 1         | 1.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 24        | 44.44%  |
| ru_RU | 6         | 11.11%  |
| de_DE | 4         | 7.41%   |
| pt_BR | 3         | 5.56%   |
| nl_NL | 2         | 3.7%    |
| ja_JP | 2         | 3.7%    |
| it_IT | 2         | 3.7%    |
| es_ES | 2         | 3.7%    |
| en_AU | 2         | 3.7%    |
| zh_HK | 1         | 1.85%   |
| uk_UA | 1         | 1.85%   |
| es_VE | 1         | 1.85%   |
| es_MX | 1         | 1.85%   |
| en_NZ | 1         | 1.85%   |
| en_GB | 1         | 1.85%   |
| de_AT | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 46        | 85.19%  |
| EFI  | 8         | 14.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 46        | 85.19%  |
| Overlay  | 7         | 12.96%  |
| Reiserfs | 1         | 1.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 43        | 79.63%  |
| GPT     | 10        | 18.52%  |
| Unknown | 1         | 1.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 80%     |
| Yes       | 11        | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 57.41%  |
| Yes       | 23        | 42.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 9         | 16.67%  |
| Lenovo              | 8         | 14.81%  |
| Acer                | 8         | 14.81%  |
| Hewlett-Packard     | 6         | 11.11%  |
| IBM                 | 5         | 9.26%   |
| Fujitsu             | 3         | 5.56%   |
| Dell                | 3         | 5.56%   |
| Toshiba             | 2         | 3.7%    |
| KOHJINSHA           | 2         | 3.7%    |
| Samsung Electronics | 1         | 1.85%   |
| Packard Bell        | 1         | 1.85%   |
| MSI                 | 1         | 1.85%   |
| Medion              | 1         | 1.85%   |
| Intel               | 1         | 1.85%   |
| Google              | 1         | 1.85%   |
| Compaq              | 1         | 1.85%   |
| Apple               | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| IBM 260921H                        | 2         | 3.7%    |
| HP Mini 110-3700                   | 2         | 3.7%    |
| Fujitsu FMVNU6G1C                  | 2         | 3.7%    |
| Toshiba Satellite C50-A-1HF        | 1         | 1.85%   |
| Toshiba Satellite 1905             | 1         | 1.85%   |
| Samsung SQ1S                       | 1         | 1.85%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.85%   |
| MSI GE62 7RE                       | 1         | 1.85%   |
| Medion WIM2170                     | 1         | 1.85%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.85%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.85%   |
| Lenovo IdeaPad S12 20021,2959      | 1         | 1.85%   |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 1.85%   |
| Lenovo IdeaPad 3 15IGL05 81WQ      | 1         | 1.85%   |
| Lenovo G550 2958                   | 1         | 1.85%   |
| Lenovo 3000 V100 076346G           | 1         | 1.85%   |
| KOHJINSHA SX series                | 1         | 1.85%   |
| KOHJINSHA SC series                | 1         | 1.85%   |
| Intel powered classmate PC         | 1         | 1.85%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.85%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.85%   |
| IBM ThinkPad T40 237342G           | 1         | 1.85%   |
| HP Pavilion dv2700                 | 1         | 1.85%   |
| HP Mini 5101                       | 1         | 1.85%   |
| HP EliteBook 8770w                 | 1         | 1.85%   |
| HP EliteBook 2570p                 | 1         | 1.85%   |
| Google Candy                       | 1         | 1.85%   |
| Fujitsu FMVS54EB                   | 1         | 1.85%   |
| Dell Latitude E6400                | 1         | 1.85%   |
| Dell Latitude 5480                 | 1         | 1.85%   |
| Dell Latitude 2120                 | 1         | 1.85%   |
| Compaq Tablet PC TC1000            | 1         | 1.85%   |
| ASUS X71SL                         | 1         | 1.85%   |
| ASUS X51RL                         | 1         | 1.85%   |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 1.85%   |
| ASUS VivoBook E14 E402YA_L402YA    | 1         | 1.85%   |
| ASUS S3N                           | 1         | 1.85%   |
| ASUS A3L                           | 1         | 1.85%   |
| ASUS 900HA                         | 1         | 1.85%   |
| ASUS 900A                          | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 7         | 12.96%  |
| Lenovo IdeaPad        | 3         | 5.56%   |
| IBM ThinkPad          | 3         | 5.56%   |
| HP Mini               | 3         | 5.56%   |
| Dell Latitude         | 3         | 5.56%   |
| Toshiba Satellite     | 2         | 3.7%    |
| Lenovo ThinkPad       | 2         | 3.7%    |
| IBM 260921H           | 2         | 3.7%    |
| HP EliteBook          | 2         | 3.7%    |
| Fujitsu FMVNU6G1C     | 2         | 3.7%    |
| ASUS VivoBook         | 2         | 3.7%    |
| Samsung SQ1S          | 1         | 1.85%   |
| Packard Bell EasyNote | 1         | 1.85%   |
| MSI GE62              | 1         | 1.85%   |
| Medion WIM2170        | 1         | 1.85%   |
| Lenovo G550           | 1         | 1.85%   |
| Lenovo 3000           | 1         | 1.85%   |
| KOHJINSHA SX          | 1         | 1.85%   |
| KOHJINSHA SC          | 1         | 1.85%   |
| Intel powered         | 1         | 1.85%   |
| HP Pavilion           | 1         | 1.85%   |
| Google Candy          | 1         | 1.85%   |
| Fujitsu FMVS54EB      | 1         | 1.85%   |
| Compaq Tablet         | 1         | 1.85%   |
| ASUS X71SL            | 1         | 1.85%   |
| ASUS X51RL            | 1         | 1.85%   |
| ASUS S3N              | 1         | 1.85%   |
| ASUS A3L              | 1         | 1.85%   |
| ASUS 900HA            | 1         | 1.85%   |
| ASUS 900A             | 1         | 1.85%   |
| ASUS 1011CX           | 1         | 1.85%   |
| Apple MacBook7        | 1         | 1.85%   |
| Acer AOA150           | 1         | 1.85%   |
| Unknown               | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2007 | 9         | 16.67%  |
| 2009 | 8         | 14.81%  |
| 2008 | 5         | 9.26%   |
| 2013 | 4         | 7.41%   |
| 2012 | 4         | 7.41%   |
| 2010 | 3         | 5.56%   |
| 2003 | 3         | 5.56%   |
| 2020 | 2         | 3.7%    |
| 2017 | 2         | 3.7%    |
| 2014 | 2         | 3.7%    |
| 2011 | 2         | 3.7%    |
| 2005 | 2         | 3.7%    |
| 2004 | 2         | 3.7%    |
| 1999 | 2         | 3.7%    |
| 2022 | 1         | 1.85%   |
| 2019 | 1         | 1.85%   |
| 2016 | 1         | 1.85%   |
| 2006 | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 54        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 54        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 53        | 98.15%  |
| Yes  | 1         | 1.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 15        | 27.78%  |
| 0.51-1.0   | 10        | 18.52%  |
| 1.01-2.0   | 9         | 16.67%  |
| 2.01-3.0   | 7         | 12.96%  |
| 4.01-8.0   | 4         | 7.41%   |
| 0.01-0.5   | 4         | 7.41%   |
| 32.01-64.0 | 2         | 3.7%    |
| 8.01-16.0  | 2         | 3.7%    |
| 16.01-24.0 | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 21        | 38.89%  |
| 0.51-1.0 | 18        | 33.33%  |
| 1.01-2.0 | 11        | 20.37%  |
| 2.01-3.0 | 4         | 7.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 81.48%  |
| 2      | 8         | 14.81%  |
| 3      | 1         | 1.85%   |
| 0      | 1         | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 51.85%  |
| Yes       | 26        | 48.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 83.33%  |
| No        | 9         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 98.15%  |
| No        | 1         | 1.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 57.41%  |
| Yes       | 23        | 42.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Hong Kong   | 9         | 16.67%  |
| USA         | 8         | 14.81%  |
| Russia      | 7         | 12.96%  |
| Germany     | 5         | 9.26%   |
| Netherlands | 3         | 5.56%   |
| Brazil      | 3         | 5.56%   |
| Japan       | 2         | 3.7%    |
| Italy       | 2         | 3.7%    |
| Australia   | 2         | 3.7%    |
| Uruguay     | 1         | 1.85%   |
| Ukraine     | 1         | 1.85%   |
| Spain       | 1         | 1.85%   |
| Poland      | 1         | 1.85%   |
| New Zealand | 1         | 1.85%   |
| Mexico      | 1         | 1.85%   |
| Kenya       | 1         | 1.85%   |
| Kazakhstan  | 1         | 1.85%   |
| Hungary     | 1         | 1.85%   |
| Denmark     | 1         | 1.85%   |
| Chile       | 1         | 1.85%   |
| Bulgaria    | 1         | 1.85%   |
| Austria     | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 6         | 10.91%  |
| Sydney                    | 2         | 3.64%   |
| St Petersburg             | 2         | 3.64%   |
| Moscow                    | 2         | 3.64%   |
| Central                   | 2         | 3.64%   |
| Żyrardów                | 1         | 1.82%   |
| Yuzhno-Sakhalinsk         | 1         | 1.82%   |
| Yokohama                  | 1         | 1.82%   |
| Ybbs an der Donau         | 1         | 1.82%   |
| Whitney                   | 1         | 1.82%   |
| Villanueva de la Torre    | 1         | 1.82%   |
| Torricella Sicura         | 1         | 1.82%   |
| Toms River                | 1         | 1.82%   |
| Sofia                     | 1         | 1.82%   |
| Sheung Shui               | 1         | 1.82%   |
| Schloss Holte-Stukenbrock | 1         | 1.82%   |
| Santiago                  | 1         | 1.82%   |
| Salto                     | 1         | 1.82%   |
| Rotterdam                 | 1         | 1.82%   |
| Reutlingen                | 1         | 1.82%   |
| Purmerend                 | 1         | 1.82%   |
| Portland                  | 1         | 1.82%   |
| Norden                    | 1         | 1.82%   |
| Neyagawa                  | 1         | 1.82%   |
| Nairobi                   | 1         | 1.82%   |
| Montevideo                | 1         | 1.82%   |
| Mittegrossefehn           | 1         | 1.82%   |
| Milan                     | 1         | 1.82%   |
| Mechanicsburg             | 1         | 1.82%   |
| Karaganda                 | 1         | 1.82%   |
| Jonesboro                 | 1         | 1.82%   |
| Hortolândia              | 1         | 1.82%   |
| Hobbs                     | 1         | 1.82%   |
| Hagenbach                 | 1         | 1.82%   |
| Grozny                    | 1         | 1.82%   |
| Greenville                | 1         | 1.82%   |
| Granja                    | 1         | 1.82%   |
| Godley                    | 1         | 1.82%   |
| Elektrostal               | 1         | 1.82%   |
| El Cerrito                | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 12        | 12     | 20.34%  |
| WDC                 | 10        | 10     | 16.95%  |
| Seagate             | 9         | 9      | 15.25%  |
| Toshiba             | 5         | 5      | 8.47%   |
| Samsung Electronics | 5         | 5      | 8.47%   |
| Unknown             | 2         | 2      | 3.39%   |
| Kingston            | 2         | 2      | 3.39%   |
| Zheino              | 1         | 1      | 1.69%   |
| Unknown (CF)        | 1         | 1      | 1.69%   |
| Transcend           | 1         | 1      | 1.69%   |
| RECADATA            | 1         | 1      | 1.69%   |
| PNY                 | 1         | 1      | 1.69%   |
| OCZ                 | 1         | 1      | 1.69%   |
| Intel               | 1         | 1      | 1.69%   |
| IBM/Hitachi         | 1         | 1      | 1.69%   |
| HGST                | 1         | 1      | 1.69%   |
| Hewlett-Packard     | 1         | 1      | 1.69%   |
| Fujitsu             | 1         | 1      | 1.69%   |
| BIWIN               | 1         | 1      | 1.69%   |
| BHT                 | 1         | 2      | 1.69%   |
| ASUS-PHISON         | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 3.39%   |
| Samsung SSD 750 EVO 120GB               | 2         | 3.39%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 3.39%   |
| Hitachi HTS542525K9SA00 250GB           | 2         | 3.39%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 1.69%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.69%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 1.69%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 1.69%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.69%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.69%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1.69%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 1.69%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.69%   |
| Unknown SR64G  64GB                     | 1         | 1.69%   |
| Unknown HAG2e  16GB                     | 1         | 1.69%   |
| Unknown (CF) Card 16GB SSD              | 1         | 1.69%   |
| Transcend SSD 2GB                       | 1         | 1.69%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.69%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.69%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.69%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1.69%   |
| Toshiba MK2576GSX 250GB                 | 1         | 1.69%   |
| Seagate ST980811AS 80GB                 | 1         | 1.69%   |
| Seagate ST9320325AS 320GB               | 1         | 1.69%   |
| Seagate ST9250421ASG 250GB              | 1         | 1.69%   |
| Seagate ST9160411AS 160GB               | 1         | 1.69%   |
| Seagate ST9160314AS 160GB               | 1         | 1.69%   |
| Seagate ST9160310AS 160GB               | 1         | 1.69%   |
| Seagate ST9160301AS 160GB               | 1         | 1.69%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 1.69%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1.69%   |
| Samsung SSD 850 EVO 120GB               | 1         | 1.69%   |
| Samsung MZALQ256HBJD-00BL2 256GB        | 1         | 1.69%   |
| Samsung HS06THB 64GB                    | 1         | 1.69%   |
| RECADATA RD-S350MCN-N0642 64GB SSD      | 1         | 1.69%   |
| PNY CS900 960GB SSD                     | 1         | 1.69%   |
| OCZ AGILITY3 120GB SSD                  | 1         | 1.69%   |
| Kingston SUV500MS120G 120GB SSD         | 1         | 1.69%   |
| Kingston SUV400S37120G 120GB SSD        | 1         | 1.69%   |
| Intel SSDSC2BW180A3H 180GB              | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 12        | 12     | 31.58%  |
| WDC                 | 10        | 10     | 26.32%  |
| Seagate             | 9         | 9      | 23.68%  |
| Toshiba             | 3         | 3      | 7.89%   |
| Samsung Electronics | 1         | 1      | 2.63%   |
| IBM/Hitachi         | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| Fujitsu             | 1         | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 16.67%  |
| Toshiba             | 2         | 2      | 11.11%  |
| Kingston            | 2         | 2      | 11.11%  |
| Zheino              | 1         | 1      | 5.56%   |
| Unknown (CF)        | 1         | 1      | 5.56%   |
| Transcend           | 1         | 1      | 5.56%   |
| RECADATA            | 1         | 1      | 5.56%   |
| PNY                 | 1         | 1      | 5.56%   |
| OCZ                 | 1         | 1      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |
| Hewlett-Packard     | 1         | 1      | 5.56%   |
| BIWIN               | 1         | 1      | 5.56%   |
| BHT                 | 1         | 2      | 5.56%   |
| ASUS-PHISON         | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 38     | 64.91%  |
| SSD  | 17        | 19     | 29.82%  |
| MMC  | 2         | 2      | 3.51%   |
| NVMe | 1         | 1      | 1.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 57     | 94.44%  |
| MMC  | 2         | 2      | 3.7%    |
| NVMe | 1         | 1      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 53     | 92.45%  |
| 0.51-1.0   | 4         | 4      | 7.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 17        | 30.91%  |
| 1-20       | 17        | 30.91%  |
| 51-100     | 7         | 12.73%  |
| 21-50      | 6         | 10.91%  |
| 251-500    | 5         | 9.09%   |
| 501-1000   | 2         | 3.64%   |
| Unknown    | 1         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 41        | 75.93%  |
| 21-50   | 6         | 11.11%  |
| 101-250 | 3         | 5.56%   |
| 51-100  | 3         | 5.56%   |
| Unknown | 1         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS542525K9SA00 250GB | 2         | 2      | 11.11%  |
| WDC WD5000LPVX-22V0TT0 500GB  | 1         | 1      | 5.56%   |
| WDC WD5000BEVT-22A0RT0 500GB  | 1         | 1      | 5.56%   |
| WDC WD3200BEVT-60ZCT1 320GB   | 1         | 1      | 5.56%   |
| WDC WD2500BEVT-22ZCT0 250GB   | 1         | 1      | 5.56%   |
| Seagate ST980811AS 80GB       | 1         | 1      | 5.56%   |
| Seagate ST9320325AS 320GB     | 1         | 1      | 5.56%   |
| Seagate ST9160314AS 160GB     | 1         | 1      | 5.56%   |
| Seagate ST9160310AS 160GB     | 1         | 1      | 5.56%   |
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 5.56%   |
| Hitachi HTS723232A7A364 320GB | 1         | 1      | 5.56%   |
| Hitachi HTS721060G9AT00 64GB  | 1         | 1      | 5.56%   |
| Hitachi HTS548040M9AT00 40GB  | 1         | 1      | 5.56%   |
| Hitachi HTS543225A7A384 250GB | 1         | 1      | 5.56%   |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 5.56%   |
| Hitachi HTC426040G8CE00 40GB  | 1         | 1      | 5.56%   |
| BIWIN SSD 32GB                | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 50%     |
| WDC     | 4         | 4      | 22.22%  |
| Seagate | 4         | 4      | 22.22%  |
| BIWIN   | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 52.94%  |
| WDC     | 4         | 4      | 23.53%  |
| Seagate | 4         | 4      | 23.53%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 17     | 94.44%  |
| SSD  | 1         | 1      | 5.56%   |

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
| Works    | 33        | 38     | 60%     |
| Malfunc  | 18        | 18     | 32.73%  |
| Detected | 4         | 4      | 7.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44        | 78.57%  |
| AMD                              | 3         | 5.36%   |
| VIA Technologies                 | 2         | 3.57%   |
| Silicon Integrated Systems [SiS] | 2         | 3.57%   |
| Nvidia                           | 2         | 3.57%   |
| Silicon Image                    | 1         | 1.79%   |
| Samsung Electronics              | 1         | 1.79%   |
| JMicron Technology               | 1         | 1.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5         | 7.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 7.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 5.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 5.97%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 5.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 4.48%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 2.99%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 2.99%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 2.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.99%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 2.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.99%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 2.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.99%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 2.99%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.49%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller                | 1         | 1.49%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.49%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.49%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.49%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 1.49%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 1.49%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.49%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.49%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.49%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.49%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.49%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 1.49%   |
| AMD SB600 IDE                                                                  | 1         | 1.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| IDE  | 29        | 47.54%  |
| SATA | 28        | 45.9%   |
| RAID | 3         | 4.92%   |
| NVMe | 1         | 1.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 49        | 90.74%  |
| AMD          | 3         | 5.56%   |
| GenuineTMx86 | 1         | 1.85%   |
| CentaurHauls | 1         | 1.85%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                          | 4         | 7.41%   |
| Intel Pentium M processor 1.60GHz                      | 2         | 3.7%    |
| Intel Pentium M processor 1.00GHz                      | 2         | 3.7%    |
| Intel Genuine processor 800MHz                         | 2         | 3.7%    |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz                   | 2         | 3.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                   | 2         | 3.7%    |
| Intel Celeron (Mendocino)                              | 2         | 3.7%    |
| Intel Atom CPU Z520 @ 1.33GHz                          | 2         | 3.7%    |
| Intel Atom CPU N455 @ 1.66GHz                          | 2         | 3.7%    |
| Intel Atom CPU N2600 @ 1.60GHz                         | 2         | 3.7%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz               | 1         | 1.85%   |
| Intel Pentium M processor 1600MHz                      | 1         | 1.85%   |
| Intel Pentium M processor 1.86GHz                      | 1         | 1.85%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz                 | 1         | 1.85%   |
| Intel Pentium 4 CPU 2.00GHz                            | 1         | 1.85%   |
| Intel Genuine CPU T2400 @ 1.83GHz                      | 1         | 1.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                     | 1         | 1.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz                      | 1         | 1.85%   |
| Intel Core i7-3740QM CPU @ 2.70GHz                     | 1         | 1.85%   |
| Intel Core i7 CPU M 620 @ 2.67GHz                      | 1         | 1.85%   |
| Intel Core i5-4300M CPU @ 2.60GHz                      | 1         | 1.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz                      | 1         | 1.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz                      | 1         | 1.85%   |
| Intel Core i5 CPU M 430 @ 2.27GHz                      | 1         | 1.85%   |
| Intel Core i3-4005U CPU @ 1.70GHz                      | 1         | 1.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz                      | 1         | 1.85%   |
| Intel Core i3-2330M CPU @ 2.20GHz                      | 1         | 1.85%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                   | 1         | 1.85%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz                   | 1         | 1.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz                      | 1         | 1.85%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz            | 1         | 1.85%   |
| Intel Celeron CPU N2940 @ 1.83GHz                      | 1         | 1.85%   |
| Intel Celeron CPU N2840 @ 2.16GHz                      | 1         | 1.85%   |
| Intel Celeron CPU 540 @ 1.86GHz                        | 1         | 1.85%   |
| Intel Celeron CPU 530 @ 1.73GHz                        | 1         | 1.85%   |
| Intel Atom CPU N550 @ 1.50GHz                          | 1         | 1.85%   |
| Intel Atom CPU N280 @ 1.66GHz                          | 1         | 1.85%   |
| GenuineTMx86 Transmeta Crusoe Processor TM5800         | 1         | 1.85%   |
| CentaurHauls VIA Nano processor U2250 (1.6GHz Capable) | 1         | 1.85%   |
| AMD E2-9000 RADEON R2, 4 COMPUTE CORES 2C+2G           | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 12        | 22.22%  |
| Intel Celeron           | 7         | 12.96%  |
| Intel Pentium M         | 6         | 11.11%  |
| Intel Core 2 Duo        | 6         | 11.11%  |
| Intel Core i7           | 4         | 7.41%   |
| Intel Core i5           | 4         | 7.41%   |
| Intel Genuine           | 3         | 5.56%   |
| Intel Core i3           | 3         | 5.56%   |
| AMD E2                  | 2         | 3.7%    |
| Other                   | 1         | 1.85%   |
| Intel Pentium Silver    | 1         | 1.85%   |
| Intel Pentium Dual      | 1         | 1.85%   |
| Intel Pentium 4         | 1         | 1.85%   |
| Intel Celeron Dual-Core | 1         | 1.85%   |
| CentaurHauls VIA Nano   | 1         | 1.85%   |
| AMD Athlon 64 X2        | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 48.15%  |
| 1      | 24        | 44.44%  |
| 4      | 4         | 7.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 57.41%  |
| 2      | 23        | 42.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 61.11%  |
| 32-bit         | 21        | 38.89%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 7         | 12.96%  |
| 0x6fd      | 4         | 7.41%   |
| 0x6d6      | 4         | 7.41%   |
| 0x1067a    | 4         | 7.41%   |
| 0x6d8      | 3         | 5.56%   |
| 0x306a9    | 3         | 5.56%   |
| 0x106ca    | 3         | 5.56%   |
| Unknown    | 3         | 5.56%   |
| 0x66a      | 2         | 3.7%    |
| 0x40651    | 2         | 3.7%    |
| 0x30678    | 2         | 3.7%    |
| 0x30661    | 2         | 3.7%    |
| 0x10661    | 2         | 3.7%    |
| 0xf24      | 1         | 1.85%   |
| 0x906e9    | 1         | 1.85%   |
| 0x806e9    | 1         | 1.85%   |
| 0x706a8    | 1         | 1.85%   |
| 0x706a1    | 1         | 1.85%   |
| 0x6e8      | 1         | 1.85%   |
| 0x695      | 1         | 1.85%   |
| 0x306c3    | 1         | 1.85%   |
| 0x206a7    | 1         | 1.85%   |
| 0x20655    | 1         | 1.85%   |
| 0x20652    | 1         | 1.85%   |
| 0x07030106 | 1         | 1.85%   |
| 0x06006704 | 1         | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Bonnell       | 12        | 22.22%  |
| P6            | 9         | 16.67%  |
| Core          | 6         | 11.11%  |
| Penryn        | 4         | 7.41%   |
| Unknown       | 4         | 7.41%   |
| IvyBridge     | 3         | 5.56%   |
| Haswell       | 3         | 5.56%   |
| Westmere      | 2         | 3.7%    |
| Silvermont    | 2         | 3.7%    |
| KabyLake      | 2         | 3.7%    |
| Goldmont plus | 2         | 3.7%    |
| SandyBridge   | 1         | 1.85%   |
| Puma          | 1         | 1.85%   |
| NetBurst      | 1         | 1.85%   |
| K8 Hammer     | 1         | 1.85%   |
| Excavator     | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 35        | 61.4%   |
| Nvidia                           | 9         | 15.79%  |
| AMD                              | 9         | 15.79%  |
| Neomagic                         | 2         | 3.51%   |
| VIA Technologies                 | 1         | 1.75%   |
| Silicon Integrated Systems [SiS] | 1         | 1.75%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 8         | 11.94%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 7.46%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 3         | 4.48%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 4.48%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 2.99%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 2.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 2.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 2.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 2.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 2.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 2.99%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 2         | 2.99%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 2.99%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 2.99%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 2.99%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                 | 1         | 1.49%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.49%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.49%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.49%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.49%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.49%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.49%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.49%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.49%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.49%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 1.49%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.49%   |
| Intel HD Graphics 630                                                         | 1         | 1.49%   |
| Intel HD Graphics 620                                                         | 1         | 1.49%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.49%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.49%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.49%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 1.49%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 1.49%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 1.49%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 55.56%  |
| 1 x AMD        | 9         | 16.67%  |
| 1 x Nvidia     | 6         | 11.11%  |
| Intel + Nvidia | 3         | 5.56%   |
| Other          | 2         | 3.7%    |
| 1 x Neomagic   | 2         | 3.7%    |
| 1 x VIA        | 1         | 1.85%   |
| 1 x SiS        | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 85.19%  |
| Unknown     | 6         | 11.11%  |
| Proprietary | 2         | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 25        | 46.3%   |
| Unknown    | 22        | 40.74%  |
| 1.01-2.0   | 5         | 9.26%   |
| 3.01-4.0   | 1         | 1.85%   |
| 0.51-1.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 31.58%  |
| LG Display              | 7         | 18.42%  |
| Samsung Electronics     | 3         | 7.89%   |
| LG Philips              | 3         | 7.89%   |
| HannStar                | 3         | 7.89%   |
| Lenovo                  | 2         | 5.26%   |
| Chimei Innolux          | 2         | 5.26%   |
| InfoVision              | 1         | 2.63%   |
| HJW                     | 1         | 2.63%   |
| CPT                     | 1         | 2.63%   |
| Chi Mei Optoelectronics | 1         | 2.63%   |
| BOE                     | 1         | 2.63%   |
| Apple                   | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 2         | 5.26%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 2.63%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch              | 1         | 2.63%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 2.63%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 2.63%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 2.63%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 2.63%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 527x296mm 23.8-inch                 | 1         | 2.63%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.63%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 1         | 2.63%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 2.63%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 2.63%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch                 | 1         | 2.63%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 2.63%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 2.63%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO3214 1280x800 261x163mm 12.1-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 2.63%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch                   | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 13        | 35.14%  |
| 1024x600          | 7         | 18.92%  |
| 1920x1080 (FHD)   | 6         | 16.22%  |
| 1280x800 (WXGA)   | 6         | 16.22%  |
| 1440x900 (WXGA+)  | 3         | 8.11%   |
| 2288x1287         | 1         | 2.7%    |
| 1920x1200 (WUXGA) | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 13        | 34.21%  |
| 10     | 6         | 15.79%  |
| 14     | 5         | 13.16%  |
| 13     | 4         | 10.53%  |
| 17     | 3         | 7.89%   |
| 12     | 2         | 5.26%   |
| 8      | 2         | 5.26%   |
| 32     | 1         | 2.63%   |
| 24     | 1         | 2.63%   |
| 11     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 50%     |
| 201-300     | 12        | 31.58%  |
| 351-400     | 3         | 7.89%   |
| 101-200     | 2         | 5.26%   |
| 701-800     | 1         | 2.63%   |
| 501-600     | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 69.44%  |
| 16/10 | 10        | 27.78%  |
| 3/2   | 1         | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 34.21%  |
| 81-90          | 7         | 18.42%  |
| 41-50          | 6         | 15.79%  |
| 71-80          | 2         | 5.26%   |
| 61-70          | 2         | 5.26%   |
| 1-40           | 2         | 5.26%   |
| 131-140        | 2         | 5.26%   |
| 51-60          | 1         | 2.63%   |
| 351-500        | 1         | 2.63%   |
| 201-250        | 1         | 2.63%   |
| 121-130        | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 19        | 50%     |
| 121-160 | 12        | 31.58%  |
| 51-100  | 7         | 18.42%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 89.09%  |
| 2     | 3         | 5.45%   |
| 0     | 3         | 5.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Qualcomm Atheros                 | 23        | 26.44%  |
| Intel                            | 20        | 22.99%  |
| Realtek Semiconductor            | 15        | 17.24%  |
| Broadcom                         | 14        | 16.09%  |
| Marvell Technology Group         | 3         | 3.45%   |
| Silicon Integrated Systems [SiS] | 2         | 2.3%    |
| Nvidia                           | 2         | 2.3%    |
| Texas Instruments                | 1         | 1.15%   |
| Ralink                           | 1         | 1.15%   |
| Qualcomm Atheros Communications  | 1         | 1.15%   |
| MediaTek                         | 1         | 1.15%   |
| Hewlett-Packard                  | 1         | 1.15%   |
| Broadcom Limited                 | 1         | 1.15%   |
| Attansic Technology              | 1         | 1.15%   |
| ASIX Electronics                 | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 9         | 8.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 5.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5         | 4.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 3.7%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 3         | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 2.78%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 2.78%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 3         | 2.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 2.78%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.85%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 2         | 1.85%   |
| Intel Wireless 7260                                                           | 2         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 1.85%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 1.85%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 1.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.85%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.93%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 0.93%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.93%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.93%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 0.93%   |
| Nvidia MCP67 Ethernet                                                         | 1         | 0.93%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 0.93%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 0.93%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 0.93%   |
| Intel WiFi Link 5100                                                          | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 21        | 37.5%   |
| Intel                           | 18        | 32.14%  |
| Broadcom                        | 10        | 17.86%  |
| Realtek Semiconductor           | 3         | 5.36%   |
| Texas Instruments               | 1         | 1.79%   |
| Ralink                          | 1         | 1.79%   |
| Qualcomm Atheros Communications | 1         | 1.79%   |
| MediaTek                        | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 9         | 15.79%  |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 7.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 5.26%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 5.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 3.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 3.51%   |
| Intel Wireless 7260                                                           | 2         | 3.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 3.51%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 3.51%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 3.51%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.75%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.75%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1         | 1.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.75%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.75%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.75%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.75%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.75%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.75%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.75%   |
| Intel WiFi Link 5100                                                          | 1         | 1.75%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.75%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.75%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.75%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.75%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.75%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 14        | 31.11%  |
| Intel                            | 10        | 22.22%  |
| Broadcom                         | 7         | 15.56%  |
| Qualcomm Atheros                 | 4         | 8.89%   |
| Marvell Technology Group         | 3         | 6.67%   |
| Silicon Integrated Systems [SiS] | 2         | 4.44%   |
| Nvidia                           | 2         | 4.44%   |
| Broadcom Limited                 | 1         | 2.22%   |
| Attansic Technology              | 1         | 2.22%   |
| ASIX Electronics                 | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 13.33%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 11.11%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 6.67%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 4.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 4.44%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 2         | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.44%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 4.44%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 4.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.22%   |
| Nvidia MCP89 Ethernet                                             | 1         | 2.22%   |
| Nvidia MCP67 Ethernet                                             | 1         | 2.22%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.22%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.22%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 2.22%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.22%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.22%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 2.22%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.22%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 2.22%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 2.22%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.22%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 2.22%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 2.22%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 50.96%  |
| Ethernet | 45        | 43.27%  |
| Modem    | 6         | 5.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 88.89%  |
| Ethernet | 6         | 11.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 43        | 79.63%  |
| 1     | 11        | 20.37%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 80%     |
| Yes  | 11        | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Broadcom                | 8         | 34.78%  |
| Intel                   | 4         | 17.39%  |
| Lite-On Technology      | 2         | 8.7%    |
| IMC Networks            | 2         | 8.7%    |
| Taiyo Yuden             | 1         | 4.35%   |
| Realtek Semiconductor   | 1         | 4.35%   |
| Ralink Technology       | 1         | 4.35%   |
| Foxconn / Hon Hai       | 1         | 4.35%   |
| Cambridge Silicon Radio | 1         | 4.35%   |
| ASUSTek Computer        | 1         | 4.35%   |
| Apple                   | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 8.7%    |
| Intel Bluetooth wireless interface                  | 2         | 8.7%    |
| IMC Networks Bluetooth Device                       | 2         | 8.7%    |
| Broadcom HP Portable SoftSailing                    | 2         | 8.7%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 8.7%    |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 4.35%   |
| Realtek RTL8821A Bluetooth                          | 1         | 4.35%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 4.35%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 4.35%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 4.35%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 4.35%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 4.35%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 4.35%   |
| Apple Bluetooth Host Controller                     | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 43        | 75.44%  |
| AMD                              | 5         | 8.77%   |
| Nvidia                           | 3         | 5.26%   |
| VIA Technologies                 | 2         | 3.51%   |
| Silicon Integrated Systems [SiS] | 2         | 3.51%   |
| ESS Technology                   | 2         | 3.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 20.97%  |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 6.45%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 6.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.84%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 3.23%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 3.23%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.23%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 3.23%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 1.61%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.61%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.61%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 1.61%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.61%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.61%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.61%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.61%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.61%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.61%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.61%   |
| AMD High Definition Audio Controller                                       | 1         | 1.61%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 24        | 42.11%  |
| SK hynix            | 10        | 17.54%  |
| Unknown             | 7         | 12.28%  |
| Samsung Electronics | 5         | 8.77%   |
| Micron Technology   | 4         | 7.02%   |
| Kingston            | 3         | 5.26%   |
| Crucial             | 2         | 3.51%   |
| Unknown (8A02)      | 1         | 1.75%   |
| Avant               | 1         | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 7         | 11.67%  |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 5%      |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 3.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 3.33%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 3.33%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 1.67%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 1.67%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                   | 1         | 1.67%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 1.67%   |
| Unknown RAM Module 2GB SODIMM DRAM                             | 1         | 1.67%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                     | 1         | 1.67%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.67%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.67%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 1.67%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 1.67%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 1.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.67%   |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 1.67%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 1.67%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 1.67%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 1.67%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 1.67%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 1.67%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 1.67%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 1.67%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s           | 1         | 1.67%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.67%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.67%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1         | 1.67%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.67%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s      | 1         | 1.67%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 1.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 1.67%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 1         | 1.67%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s          | 1         | 1.67%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 1.67%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s          | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 1.67%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 15        | 30%     |
| DDR2  | 11        | 22%     |
| SDRAM | 10        | 20%     |
| DDR4  | 5         | 10%     |
| DDR   | 5         | 10%     |
| DRAM  | 4         | 8%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 92%     |
| DIMM         | 3         | 6%      |
| Row Of Chips | 1         | 2%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 18        | 31.03%  |
| 1024  | 14        | 24.14%  |
| 4096  | 10        | 17.24%  |
| 512   | 5         | 8.62%   |
| 8192  | 4         | 6.9%    |
| 256   | 3         | 5.17%   |
| 64    | 2         | 3.45%   |
| 16384 | 1         | 1.72%   |
| 232   | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 37.25%  |
| 1600    | 9         | 17.65%  |
| 1067    | 3         | 5.88%   |
| 533     | 3         | 5.88%   |
| 2400    | 2         | 3.92%   |
| 800     | 2         | 3.92%   |
| 667     | 2         | 3.92%   |
| 200     | 2         | 3.92%   |
| 4199    | 1         | 1.96%   |
| 3266    | 1         | 1.96%   |
| 3200    | 1         | 1.96%   |
| 2667    | 1         | 1.96%   |
| 1866    | 1         | 1.96%   |
| 1334    | 1         | 1.96%   |
| 1333    | 1         | 1.96%   |
| 975     | 1         | 1.96%   |
| 266     | 1         | 1.96%   |

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
| Chicony Electronics                    | 8         | 22.22%  |
| IMC Networks                           | 4         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) | 4         | 11.11%  |
| Suyin                                  | 3         | 8.33%   |
| Microdia                               | 3         | 8.33%   |
| Acer                                   | 3         | 8.33%   |
| Sunplus Innovation Technology          | 2         | 5.56%   |
| Pixart Imaging                         | 2         | 5.56%   |
| Syntek                                 | 1         | 2.78%   |
| Silicon Motion                         | 1         | 2.78%   |
| Realtek Semiconductor                  | 1         | 2.78%   |
| Lenovo                                 | 1         | 2.78%   |
| Importek                               | 1         | 2.78%   |
| Bison Electronics                      | 1         | 2.78%   |
| Apple                                  | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 5.56%   |
| Microdia Sonix USB 2.0 Camera                           | 2         | 5.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 5.56%   |
| Acer BisonCam, NB Pro                                   | 2         | 5.56%   |
| Syntek Integrated Camera                                | 1         | 2.78%   |
| Suyin USB2.0 UVC 1.3M WebCam                            | 1         | 2.78%   |
| Suyin USB 2.0 Camera                                    | 1         | 2.78%   |
| Suyin Integrated_Webcam_HD                              | 1         | 2.78%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 2.78%   |
| Sunplus HD WebCam                                       | 1         | 2.78%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 2.78%   |
| Realtek HD WebCam                                       | 1         | 2.78%   |
| Microdia Integrated Webcam                              | 1         | 2.78%   |
| Lenovo Integrated Webcam                                | 1         | 2.78%   |
| Importek FJ Camera                                      | 1         | 2.78%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 2.78%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 2.78%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 2.78%   |
| Chicony Integrated HP HD Webcam                         | 1         | 2.78%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 2.78%   |
| Chicony HD WebCam                                       | 1         | 2.78%   |
| Chicony EasyCamera                                      | 1         | 2.78%   |
| Chicony CNF8243 Webcam                                  | 1         | 2.78%   |
| Chicony CNF7050                                         | 1         | 2.78%   |
| Chicony Acer CrystalEye Webcam                          | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 2.78%   |
| Bison Lenovo EasyCamera                                 | 1         | 2.78%   |
| Apple Built-in iSight                                   | 1         | 2.78%   |
| Acer Crystal Eye Webcam                                 | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 5         | 71.43%  |
| Validity Sensors | 1         | 14.29%  |
| Upek             | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 3         | 42.86%  |
| AuthenTec AES1600                                      | 2         | 28.57%  |
| Validity Sensors VFS491                                | 1         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 36        | 66.67%  |
| 1     | 17        | 31.48%  |
| 2     | 1         | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 11        | 57.89%  |
| Fingerprint reader | 7         | 36.84%  |
| Chipcard           | 1         | 5.26%   |

