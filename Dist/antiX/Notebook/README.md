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

Total: 64

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| antiX 21       | 21        | 41.18%  |
| antiX 22       | 11        | 21.57%  |
| antiX 19.2     | 6         | 11.76%  |
| antiX 19.3     | 3         | 5.88%   |
| antiX 21-runit | 2         | 3.92%   |
| antiX 19.4     | 2         | 3.92%   |
| antiX 19.1     | 2         | 3.92%   |
| antiX 19.5     | 1         | 1.96%   |
| antiX 17.4.1   | 1         | 1.96%   |
| antiX 17.2.1   | 1         | 1.96%   |
| antiX 17       | 1         | 1.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| antiX | 50        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 13        | 25.49%  |
| 5.10.57-antix.1-amd64-smp    | 4         | 7.84%   |
| 5.10.142-antix.2-amd64-smp   | 4         | 7.84%   |
| 4.9.0-326-antix.1-amd64-smp  | 4         | 7.84%   |
| 4.9.0-279-antix.1-amd64-smp  | 4         | 7.84%   |
| 4.9.0-326-antix.1-486-smp    | 3         | 5.88%   |
| 4.9.235-antix.1-amd64-smp    | 2         | 3.92%   |
| 4.9.212-antix.1-amd64-smp    | 2         | 3.92%   |
| 4.9.212-antix.1-486-smp      | 2         | 3.92%   |
| 4.9.200-antix.1-486-smp      | 2         | 3.92%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.96%   |
| 5.10.88-antix.1-amd64-smp    | 1         | 1.96%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.96%   |
| 4.9.160-antix.2-486-smp      | 1         | 1.96%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.96%   |
| 4.9.0-294-antix.1-amd64-smp  | 1         | 1.96%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.96%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.96%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.96%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.96%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.9.0    | 25        | 50%     |
| 5.10.57  | 4         | 8%      |
| 5.10.142 | 4         | 8%      |
| 4.9.212  | 4         | 8%      |
| 4.9.235  | 2         | 4%      |
| 4.9.200  | 2         | 4%      |
| 4.9.160  | 2         | 4%      |
| 5.14.0   | 1         | 2%      |
| 5.10.88  | 1         | 2%      |
| 5.10.27  | 1         | 2%      |
| 4.19.202 | 1         | 2%      |
| 4.19.100 | 1         | 2%      |
| 4.19.0   | 1         | 2%      |
| 4.10.5   | 1         | 2%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 35        | 70%     |
| 5.10    | 10        | 20%     |
| 4.19    | 3         | 6%      |
| 5.14    | 1         | 2%      |
| 4.10    | 1         | 2%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 25        | 50%     |
| i686   | 24        | 48%     |
| i586   | 1         | 2%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 26        | 52%     |
| icewm   | 21        | 42%     |
| XFCE    | 1         | 2%      |
| GNOME   | 1         | 2%      |
| fluxbox | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 50        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 28        | 56%     |
| SLiM    | 15        | 30%     |
| SLIMSKI | 3         | 6%      |
| LightDM | 2         | 4%      |
| XDM     | 1         | 2%      |
| SDDM    | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 23        | 46%     |
| ru_RU | 5         | 10%     |
| de_DE | 4         | 8%      |
| nl_NL | 2         | 4%      |
| ja_JP | 2         | 4%      |
| it_IT | 2         | 4%      |
| es_ES | 2         | 4%      |
| en_AU | 2         | 4%      |
| zh_HK | 1         | 2%      |
| uk_UA | 1         | 2%      |
| pt_BR | 1         | 2%      |
| es_VE | 1         | 2%      |
| es_MX | 1         | 2%      |
| en_NZ | 1         | 2%      |
| en_GB | 1         | 2%      |
| de_AT | 1         | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 43        | 86%     |
| EFI  | 7         | 14%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 42        | 84%     |
| Overlay  | 7         | 14%     |
| Reiserfs | 1         | 2%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 40        | 80%     |
| GPT     | 9         | 18%     |
| Unknown | 1         | 2%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 78.43%  |
| Yes       | 11        | 21.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 58%     |
| Yes       | 21        | 42%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 9         | 18%     |
| Lenovo              | 7         | 14%     |
| Acer                | 7         | 14%     |
| Hewlett-Packard     | 6         | 12%     |
| IBM                 | 5         | 10%     |
| Dell                | 3         | 6%      |
| Toshiba             | 2         | 4%      |
| KOHJINSHA           | 2         | 4%      |
| Fujitsu             | 2         | 4%      |
| Samsung Electronics | 1         | 2%      |
| Packard Bell        | 1         | 2%      |
| MSI                 | 1         | 2%      |
| Medion              | 1         | 2%      |
| Google              | 1         | 2%      |
| Compaq              | 1         | 2%      |
| Apple               | 1         | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| IBM 260921H                        | 2         | 4%      |
| HP Mini 110-3700                   | 2         | 4%      |
| Toshiba Satellite C50-A-1HF        | 1         | 2%      |
| Toshiba Satellite 1905             | 1         | 2%      |
| Samsung SQ1S                       | 1         | 2%      |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 2%      |
| MSI GE62 7RE                       | 1         | 2%      |
| Medion WIM2170                     | 1         | 2%      |
| Lenovo ThinkPad X201 3249CTO       | 1         | 2%      |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 2%      |
| Lenovo IdeaPad S12 20021,2959      | 1         | 2%      |
| Lenovo IdeaPad 320-15AST 80XV      | 1         | 2%      |
| Lenovo G550 2958                   | 1         | 2%      |
| Lenovo 3000 V100 076346G           | 1         | 2%      |
| KOHJINSHA SX series                | 1         | 2%      |
| KOHJINSHA SC series                | 1         | 2%      |
| IBM ThinkPad T43 2668WEJ           | 1         | 2%      |
| IBM ThinkPad T41 2374K50           | 1         | 2%      |
| IBM ThinkPad T40 237342G           | 1         | 2%      |
| HP Pavilion dv2700                 | 1         | 2%      |
| HP Mini 5101                       | 1         | 2%      |
| HP EliteBook 8770w                 | 1         | 2%      |
| HP EliteBook 2570p                 | 1         | 2%      |
| Google Candy                       | 1         | 2%      |
| Fujitsu FMVS54EB                   | 1         | 2%      |
| Fujitsu FMVNU6G1C                  | 1         | 2%      |
| Dell Latitude E6400                | 1         | 2%      |
| Dell Latitude 5480                 | 1         | 2%      |
| Dell Latitude 2120                 | 1         | 2%      |
| Compaq Tablet PC TC1000            | 1         | 2%      |
| ASUS X71SL                         | 1         | 2%      |
| ASUS X51RL                         | 1         | 2%      |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 2%      |
| ASUS VivoBook E14 E402YA_L402YA    | 1         | 2%      |
| ASUS S3N                           | 1         | 2%      |
| ASUS A3L                           | 1         | 2%      |
| ASUS 900HA                         | 1         | 2%      |
| ASUS 900A                          | 1         | 2%      |
| ASUS 1011CX                        | 1         | 2%      |
| Apple MacBook7,1                   | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 6         | 12%     |
| IBM ThinkPad          | 3         | 6%      |
| HP Mini               | 3         | 6%      |
| Dell Latitude         | 3         | 6%      |
| Toshiba Satellite     | 2         | 4%      |
| Lenovo ThinkPad       | 2         | 4%      |
| Lenovo IdeaPad        | 2         | 4%      |
| IBM 260921H           | 2         | 4%      |
| HP EliteBook          | 2         | 4%      |
| ASUS VivoBook         | 2         | 4%      |
| Samsung SQ1S          | 1         | 2%      |
| Packard Bell EasyNote | 1         | 2%      |
| MSI GE62              | 1         | 2%      |
| Medion WIM2170        | 1         | 2%      |
| Lenovo G550           | 1         | 2%      |
| Lenovo 3000           | 1         | 2%      |
| KOHJINSHA SX          | 1         | 2%      |
| KOHJINSHA SC          | 1         | 2%      |
| HP Pavilion           | 1         | 2%      |
| Google Candy          | 1         | 2%      |
| Fujitsu FMVS54EB      | 1         | 2%      |
| Fujitsu FMVNU6G1C     | 1         | 2%      |
| Compaq Tablet         | 1         | 2%      |
| ASUS X71SL            | 1         | 2%      |
| ASUS X51RL            | 1         | 2%      |
| ASUS S3N              | 1         | 2%      |
| ASUS A3L              | 1         | 2%      |
| ASUS 900HA            | 1         | 2%      |
| ASUS 900A             | 1         | 2%      |
| ASUS 1011CX           | 1         | 2%      |
| Apple MacBook7        | 1         | 2%      |
| Acer AOA150           | 1         | 2%      |
| Unknown               | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2009 | 8         | 16%     |
| 2007 | 8         | 16%     |
| 2008 | 5         | 10%     |
| 2013 | 4         | 8%      |
| 2012 | 3         | 6%      |
| 2010 | 3         | 6%      |
| 2003 | 3         | 6%      |
| 2017 | 2         | 4%      |
| 2011 | 2         | 4%      |
| 2005 | 2         | 4%      |
| 2004 | 2         | 4%      |
| 1999 | 2         | 4%      |
| 2022 | 1         | 2%      |
| 2020 | 1         | 2%      |
| 2019 | 1         | 2%      |
| 2016 | 1         | 2%      |
| 2014 | 1         | 2%      |
| 2006 | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 50        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 50        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 98%     |
| Yes  | 1         | 2%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 14        | 28%     |
| 0.51-1.0   | 9         | 18%     |
| 1.01-2.0   | 8         | 16%     |
| 2.01-3.0   | 7         | 14%     |
| 0.01-0.5   | 4         | 8%      |
| 4.01-8.0   | 3         | 6%      |
| 32.01-64.0 | 2         | 4%      |
| 8.01-16.0  | 2         | 4%      |
| 16.01-24.0 | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 20        | 40%     |
| 0.51-1.0 | 17        | 34%     |
| 1.01-2.0 | 10        | 20%     |
| 2.01-3.0 | 3         | 6%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 82%     |
| 2      | 7         | 14%     |
| 3      | 1         | 2%      |
| 0      | 1         | 2%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 50%     |
| No        | 25        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 86%     |
| No        | 7         | 14%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 98%     |
| No        | 1         | 2%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 60%     |
| Yes       | 20        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 16%     |
| Hong Kong   | 8         | 16%     |
| Russia      | 6         | 12%     |
| Germany     | 5         | 10%     |
| Netherlands | 3         | 6%      |
| Japan       | 2         | 4%      |
| Italy       | 2         | 4%      |
| Australia   | 2         | 4%      |
| Uruguay     | 1         | 2%      |
| Ukraine     | 1         | 2%      |
| Spain       | 1         | 2%      |
| Poland      | 1         | 2%      |
| New Zealand | 1         | 2%      |
| Mexico      | 1         | 2%      |
| Kenya       | 1         | 2%      |
| Kazakhstan  | 1         | 2%      |
| Hungary     | 1         | 2%      |
| Denmark     | 1         | 2%      |
| Chile       | 1         | 2%      |
| Bulgaria    | 1         | 2%      |
| Brazil      | 1         | 2%      |
| Austria     | 1         | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 6         | 11.76%  |
| Sydney                    | 2         | 3.92%   |
| St Petersburg             | 2         | 3.92%   |
| Moscow                    | 2         | 3.92%   |
| Żyrardów                | 1         | 1.96%   |
| Yuzhno-Sakhalinsk         | 1         | 1.96%   |
| Yokohama                  | 1         | 1.96%   |
| Ybbs an der Donau         | 1         | 1.96%   |
| Whitney                   | 1         | 1.96%   |
| Villanueva de la Torre    | 1         | 1.96%   |
| Torricella Sicura         | 1         | 1.96%   |
| Toms River                | 1         | 1.96%   |
| Sofia                     | 1         | 1.96%   |
| Sheung Shui               | 1         | 1.96%   |
| Schloss Holte-Stukenbrock | 1         | 1.96%   |
| Santiago                  | 1         | 1.96%   |
| Salto                     | 1         | 1.96%   |
| Rotterdam                 | 1         | 1.96%   |
| Reutlingen                | 1         | 1.96%   |
| Purmerend                 | 1         | 1.96%   |
| Portland                  | 1         | 1.96%   |
| Norden                    | 1         | 1.96%   |
| Neyagawa                  | 1         | 1.96%   |
| Nairobi                   | 1         | 1.96%   |
| Montevideo                | 1         | 1.96%   |
| Mittegrossefehn           | 1         | 1.96%   |
| Milan                     | 1         | 1.96%   |
| Mechanicsburg             | 1         | 1.96%   |
| Karaganda                 | 1         | 1.96%   |
| Jonesboro                 | 1         | 1.96%   |
| Hobbs                     | 1         | 1.96%   |
| Hagenbach                 | 1         | 1.96%   |
| Greenville                | 1         | 1.96%   |
| Godley                    | 1         | 1.96%   |
| Elektrostal               | 1         | 1.96%   |
| El Cerrito                | 1         | 1.96%   |
| Dnipro                    | 1         | 1.96%   |
| Copenhagen                | 1         | 1.96%   |
| Central                   | 1         | 1.96%   |
| Celaya                    | 1         | 1.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 11        | 11     | 20%     |
| WDC                 | 9         | 9      | 16.36%  |
| Seagate             | 9         | 9      | 16.36%  |
| Toshiba             | 5         | 5      | 9.09%   |
| Samsung Electronics | 4         | 4      | 7.27%   |
| Unknown             | 2         | 2      | 3.64%   |
| Kingston            | 2         | 2      | 3.64%   |
| Zheino              | 1         | 1      | 1.82%   |
| Unknown (CF)        | 1         | 1      | 1.82%   |
| Transcend           | 1         | 1      | 1.82%   |
| RECADATA            | 1         | 1      | 1.82%   |
| PNY                 | 1         | 1      | 1.82%   |
| OCZ                 | 1         | 1      | 1.82%   |
| Intel               | 1         | 1      | 1.82%   |
| IBM/Hitachi         | 1         | 1      | 1.82%   |
| HGST                | 1         | 1      | 1.82%   |
| Hewlett-Packard     | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |
| BHT                 | 1         | 2      | 1.82%   |
| ASUS-PHISON         | 1         | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB               | 2         | 3.64%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 3.64%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 1.82%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 1.82%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.82%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 1.82%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 1.82%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.82%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.82%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1.82%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 1.82%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.82%   |
| Unknown SR64G  64GB                     | 1         | 1.82%   |
| Unknown HAG2e  16GB                     | 1         | 1.82%   |
| Unknown (CF) Card 16GB SSD              | 1         | 1.82%   |
| Transcend SSD 2GB                       | 1         | 1.82%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.82%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.82%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.82%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1.82%   |
| Toshiba MK2576GSX 250GB                 | 1         | 1.82%   |
| Seagate ST980811AS 80GB                 | 1         | 1.82%   |
| Seagate ST9320325AS 320GB               | 1         | 1.82%   |
| Seagate ST9250421ASG 250GB              | 1         | 1.82%   |
| Seagate ST9160411AS 160GB               | 1         | 1.82%   |
| Seagate ST9160314AS 160GB               | 1         | 1.82%   |
| Seagate ST9160310AS 160GB               | 1         | 1.82%   |
| Seagate ST9160301AS 160GB               | 1         | 1.82%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 1.82%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1.82%   |
| Samsung SSD 850 EVO 120GB               | 1         | 1.82%   |
| Samsung HS06THB 64GB                    | 1         | 1.82%   |
| RECADATA RD-S350MCN-N0642 64GB SSD      | 1         | 1.82%   |
| PNY CS900 960GB SSD                     | 1         | 1.82%   |
| OCZ AGILITY3 120GB SSD                  | 1         | 1.82%   |
| Kingston SUV500MS120G 120GB SSD         | 1         | 1.82%   |
| Kingston SUV400S37120G 120GB SSD        | 1         | 1.82%   |
| Intel SSDSC2BW180A3H 180GB              | 1         | 1.82%   |
| IBM/Hitachi IC25N080ATMR04-0 80GB       | 1         | 1.82%   |
| Hitachi HTS725050A7E630 500GB           | 1         | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 11        | 11     | 30.56%  |
| WDC                 | 9         | 9      | 25%     |
| Seagate             | 9         | 9      | 25%     |
| Toshiba             | 3         | 3      | 8.33%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| IBM/Hitachi         | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 17.65%  |
| Toshiba             | 2         | 2      | 11.76%  |
| Kingston            | 2         | 2      | 11.76%  |
| Zheino              | 1         | 1      | 5.88%   |
| Unknown (CF)        | 1         | 1      | 5.88%   |
| Transcend           | 1         | 1      | 5.88%   |
| RECADATA            | 1         | 1      | 5.88%   |
| PNY                 | 1         | 1      | 5.88%   |
| OCZ                 | 1         | 1      | 5.88%   |
| Intel               | 1         | 1      | 5.88%   |
| Hewlett-Packard     | 1         | 1      | 5.88%   |
| BHT                 | 1         | 2      | 5.88%   |
| ASUS-PHISON         | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 36     | 66.04%  |
| SSD  | 16        | 18     | 30.19%  |
| MMC  | 2         | 2      | 3.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 48        | 54     | 96%     |
| MMC  | 2         | 2      | 4%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 50     | 92%     |
| 0.51-1.0   | 4         | 4      | 8%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 16        | 31.37%  |
| 101-250    | 15        | 29.41%  |
| 51-100     | 7         | 13.73%  |
| 21-50      | 6         | 11.76%  |
| 251-500    | 4         | 7.84%   |
| 501-1000   | 2         | 3.92%   |
| Unknown    | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 39        | 78%     |
| 21-50   | 5         | 10%     |
| 101-250 | 3         | 6%      |
| 51-100  | 2         | 4%      |
| Unknown | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB  | 1         | 1      | 6.67%   |
| WDC WD3200BEVT-60ZCT1 320GB   | 1         | 1      | 6.67%   |
| WDC WD2500BEVT-22ZCT0 250GB   | 1         | 1      | 6.67%   |
| Seagate ST980811AS 80GB       | 1         | 1      | 6.67%   |
| Seagate ST9320325AS 320GB     | 1         | 1      | 6.67%   |
| Seagate ST9160314AS 160GB     | 1         | 1      | 6.67%   |
| Seagate ST9160310AS 160GB     | 1         | 1      | 6.67%   |
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 6.67%   |
| Hitachi HTS723232A7A364 320GB | 1         | 1      | 6.67%   |
| Hitachi HTS721060G9AT00 64GB  | 1         | 1      | 6.67%   |
| Hitachi HTS548040M9AT00 40GB  | 1         | 1      | 6.67%   |
| Hitachi HTS543225A7A384 250GB | 1         | 1      | 6.67%   |
| Hitachi HTS542525K9SA00 250GB | 1         | 1      | 6.67%   |
| Hitachi HTS541612J9SA00 120GB | 1         | 1      | 6.67%   |
| Hitachi HTC426040G8CE00 40GB  | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 53.33%  |
| Seagate | 4         | 4      | 26.67%  |
| WDC     | 3         | 3      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 53.33%  |
| Seagate | 4         | 4      | 26.67%  |
| WDC     | 3         | 3      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 100%    |

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
| Works    | 32        | 37     | 62.75%  |
| Malfunc  | 15        | 15     | 29.41%  |
| Detected | 4         | 4      | 7.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 40        | 78.43%  |
| AMD                              | 3         | 5.88%   |
| VIA Technologies                 | 2         | 3.92%   |
| Silicon Integrated Systems [SiS] | 2         | 3.92%   |
| Nvidia                           | 2         | 3.92%   |
| Silicon Image                    | 1         | 1.96%   |
| JMicron Technology               | 1         | 1.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 6.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 6.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 6.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 6.45%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 6.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 4.84%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 3.23%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 3.23%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 3.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.23%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 3.23%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 3.23%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.61%   |
| VIA CX700M2/VX700/VX800/820-Series Serial ATA & EIDE-Controller                | 1         | 1.61%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.61%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.61%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 1.61%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 1.61%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 1         | 1.61%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.61%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.61%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.61%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 1.61%   |
| AMD SB600 IDE                                                                  | 1         | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| IDE  | 28        | 50%     |
| SATA | 25        | 44.64%  |
| RAID | 3         | 5.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 45        | 90%     |
| AMD          | 3         | 6%      |
| GenuineTMx86 | 1         | 2%      |
| CentaurHauls | 1         | 2%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                          | 4         | 8%      |
| Intel Pentium M processor 1.60GHz                      | 2         | 4%      |
| Intel Pentium M processor 1.00GHz                      | 2         | 4%      |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz                   | 2         | 4%      |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                   | 2         | 4%      |
| Intel Celeron (Mendocino)                              | 2         | 4%      |
| Intel Atom CPU Z520 @ 1.33GHz                          | 2         | 4%      |
| Intel Atom CPU N455 @ 1.66GHz                          | 2         | 4%      |
| Intel Pentium M processor 1600MHz                      | 1         | 2%      |
| Intel Pentium M processor 1.86GHz                      | 1         | 2%      |
| Intel Pentium Dual CPU T2390 @ 1.86GHz                 | 1         | 2%      |
| Intel Pentium 4 CPU 2.00GHz                            | 1         | 2%      |
| Intel Genuine processor 800MHz                         | 1         | 2%      |
| Intel Genuine CPU T2400 @ 1.83GHz                      | 1         | 2%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz                     | 1         | 2%      |
| Intel Core i7-7600U CPU @ 2.80GHz                      | 1         | 2%      |
| Intel Core i7-3740QM CPU @ 2.70GHz                     | 1         | 2%      |
| Intel Core i7 CPU M 620 @ 2.67GHz                      | 1         | 2%      |
| Intel Core i5-4300M CPU @ 2.60GHz                      | 1         | 2%      |
| Intel Core i5-4200U CPU @ 1.60GHz                      | 1         | 2%      |
| Intel Core i5-3320M CPU @ 2.60GHz                      | 1         | 2%      |
| Intel Core i5 CPU M 430 @ 2.27GHz                      | 1         | 2%      |
| Intel Core i3-4005U CPU @ 1.70GHz                      | 1         | 2%      |
| Intel Core i3-3110M CPU @ 2.40GHz                      | 1         | 2%      |
| Intel Core i3-2330M CPU @ 2.20GHz                      | 1         | 2%      |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                   | 1         | 2%      |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz                   | 1         | 2%      |
| Intel Celeron N4000 CPU @ 1.10GHz                      | 1         | 2%      |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz            | 1         | 2%      |
| Intel Celeron CPU N2840 @ 2.16GHz                      | 1         | 2%      |
| Intel Celeron CPU 540 @ 1.86GHz                        | 1         | 2%      |
| Intel Celeron CPU 530 @ 1.73GHz                        | 1         | 2%      |
| Intel Atom CPU N550 @ 1.50GHz                          | 1         | 2%      |
| Intel Atom CPU N280 @ 1.66GHz                          | 1         | 2%      |
| Intel Atom CPU N2600 @ 1.60GHz                         | 1         | 2%      |
| GenuineTMx86 Transmeta Crusoe Processor TM5800         | 1         | 2%      |
| CentaurHauls VIA Nano processor U2250 (1.6GHz Capable) | 1         | 2%      |
| AMD E2-9000 RADEON R2, 4 COMPUTE CORES 2C+2G           | 1         | 2%      |
| AMD E2-7015 APU with AMD Radeon R2 Graphics            | 1         | 2%      |
| AMD Athlon 64 X2 Dual-Core Processor TK-53             | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 11        | 22%     |
| Intel Pentium M         | 6         | 12%     |
| Intel Core 2 Duo        | 6         | 12%     |
| Intel Celeron           | 6         | 12%     |
| Intel Core i7           | 4         | 8%      |
| Intel Core i5           | 4         | 8%      |
| Intel Core i3           | 3         | 6%      |
| Intel Genuine           | 2         | 4%      |
| AMD E2                  | 2         | 4%      |
| Other                   | 1         | 2%      |
| Intel Pentium Dual      | 1         | 2%      |
| Intel Pentium 4         | 1         | 2%      |
| Intel Celeron Dual-Core | 1         | 2%      |
| CentaurHauls VIA Nano   | 1         | 2%      |
| AMD Athlon 64 X2        | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 50%     |
| 1      | 23        | 46%     |
| 4      | 2         | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 56%     |
| 2      | 22        | 44%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 30        | 60%     |
| 32-bit         | 20        | 40%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x106c2    | 7         | 14%     |
| 0x6fd      | 4         | 8%      |
| 0x6d6      | 4         | 8%      |
| 0x1067a    | 4         | 8%      |
| 0x306a9    | 3         | 6%      |
| 0x106ca    | 3         | 6%      |
| Unknown    | 3         | 6%      |
| 0x6d8      | 2         | 4%      |
| 0x66a      | 2         | 4%      |
| 0x40651    | 2         | 4%      |
| 0x10661    | 2         | 4%      |
| 0xf24      | 1         | 2%      |
| 0x906e9    | 1         | 2%      |
| 0x806e9    | 1         | 2%      |
| 0x706a1    | 1         | 2%      |
| 0x6e8      | 1         | 2%      |
| 0x695      | 1         | 2%      |
| 0x306c3    | 1         | 2%      |
| 0x30678    | 1         | 2%      |
| 0x30661    | 1         | 2%      |
| 0x206a7    | 1         | 2%      |
| 0x20655    | 1         | 2%      |
| 0x20652    | 1         | 2%      |
| 0x07030106 | 1         | 2%      |
| 0x06006704 | 1         | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Bonnell       | 11        | 22%     |
| P6            | 8         | 16%     |
| Core          | 6         | 12%     |
| Penryn        | 4         | 8%      |
| Unknown       | 4         | 8%      |
| IvyBridge     | 3         | 6%      |
| Haswell       | 3         | 6%      |
| Westmere      | 2         | 4%      |
| KabyLake      | 2         | 4%      |
| Silvermont    | 1         | 2%      |
| SandyBridge   | 1         | 2%      |
| Puma          | 1         | 2%      |
| NetBurst      | 1         | 2%      |
| K8 Hammer     | 1         | 2%      |
| Goldmont plus | 1         | 2%      |
| Excavator     | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 31        | 58.49%  |
| Nvidia                           | 9         | 16.98%  |
| AMD                              | 9         | 16.98%  |
| Neomagic                         | 2         | 3.77%   |
| VIA Technologies                 | 1         | 1.89%   |
| Silicon Integrated Systems [SiS] | 1         | 1.89%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 7         | 11.29%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 8.06%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 4.84%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 3.23%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 3.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 3.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 3.23%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 3.23%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 3.23%   |
| VIA Technologies VX800/VX820 Chrome 9 HC3 Integrated Graphics                 | 1         | 1.61%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.61%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.61%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.61%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.61%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.61%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.61%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.61%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.61%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 1.61%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.61%   |
| Intel HD Graphics 630                                                         | 1         | 1.61%   |
| Intel HD Graphics 620                                                         | 1         | 1.61%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.61%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.61%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.61%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 1.61%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 1.61%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 1.61%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 1.61%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                      | 1         | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 52%     |
| 1 x AMD        | 9         | 18%     |
| 1 x Nvidia     | 6         | 12%     |
| Intel + Nvidia | 3         | 6%      |
| Other          | 2         | 4%      |
| 1 x Neomagic   | 2         | 4%      |
| 1 x VIA        | 1         | 2%      |
| 1 x SiS        | 1         | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 42        | 84%     |
| Unknown     | 6         | 12%     |
| Proprietary | 2         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 24        | 48%     |
| Unknown    | 19        | 38%     |
| 1.01-2.0   | 5         | 10%     |
| 3.01-4.0   | 1         | 2%      |
| 0.51-1.0   | 1         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 32.35%  |
| LG Display              | 6         | 17.65%  |
| Samsung Electronics     | 3         | 8.82%   |
| LG Philips              | 3         | 8.82%   |
| HannStar                | 3         | 8.82%   |
| Chimei Innolux          | 2         | 5.88%   |
| Lenovo                  | 1         | 2.94%   |
| HJW                     | 1         | 2.94%   |
| CPT                     | 1         | 2.94%   |
| Chi Mei Optoelectronics | 1         | 2.94%   |
| BOE                     | 1         | 2.94%   |
| Apple                   | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 2.94%   |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch              | 1         | 2.94%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 2.94%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 2.94%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 2.94%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 2.94%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 2.94%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 2.94%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 2.94%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 2.94%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.94%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 2.94%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 2.94%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch                 | 1         | 2.94%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 2.94%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.94%   |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 2.94%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO3214 1280x800 261x163mm 12.1-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 2.94%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch                   | 1         | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 12        | 36.36%  |
| 1024x600         | 7         | 21.21%  |
| 1280x800 (WXGA)  | 6         | 18.18%  |
| 1920x1080 (FHD)  | 4         | 12.12%  |
| 1440x900 (WXGA+) | 3         | 9.09%   |
| 2288x1287        | 1         | 3.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 29.41%  |
| 10     | 6         | 17.65%  |
| 14     | 5         | 14.71%  |
| 13     | 4         | 11.76%  |
| 17     | 3         | 8.82%   |
| 12     | 2         | 5.88%   |
| 8      | 2         | 5.88%   |
| 32     | 1         | 2.94%   |
| 11     | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 47.06%  |
| 201-300     | 12        | 35.29%  |
| 351-400     | 3         | 8.82%   |
| 101-200     | 2         | 5.88%   |
| 701-800     | 1         | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 66.67%  |
| 16/10 | 10        | 30.3%   |
| 3/2   | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 29.41%  |
| 81-90          | 7         | 20.59%  |
| 41-50          | 6         | 17.65%  |
| 71-80          | 2         | 5.88%   |
| 61-70          | 2         | 5.88%   |
| 1-40           | 2         | 5.88%   |
| 131-140        | 2         | 5.88%   |
| 51-60          | 1         | 2.94%   |
| 351-500        | 1         | 2.94%   |
| 121-130        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 17        | 50%     |
| 121-160 | 11        | 32.35%  |
| 51-100  | 6         | 17.65%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 46        | 90.2%   |
| 0     | 3         | 5.88%   |
| 2     | 2         | 3.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Qualcomm Atheros                 | 21        | 25.61%  |
| Intel                            | 19        | 23.17%  |
| Broadcom                         | 14        | 17.07%  |
| Realtek Semiconductor            | 13        | 15.85%  |
| Marvell Technology Group         | 3         | 3.66%   |
| Silicon Integrated Systems [SiS] | 2         | 2.44%   |
| Nvidia                           | 2         | 2.44%   |
| Texas Instruments                | 1         | 1.22%   |
| Ralink                           | 1         | 1.22%   |
| Qualcomm Atheros Communications  | 1         | 1.22%   |
| MediaTek                         | 1         | 1.22%   |
| Hewlett-Packard                  | 1         | 1.22%   |
| Broadcom Limited                 | 1         | 1.22%   |
| Attansic Technology              | 1         | 1.22%   |
| ASIX Electronics                 | 1         | 1.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 7.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 4.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5         | 4.9%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 3.92%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 2.94%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 3         | 2.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 2.94%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 1.96%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.96%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.96%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 2         | 1.96%   |
| Intel Wireless 7260                                                           | 2         | 1.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.96%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 1.96%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 1.96%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 1.96%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.96%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.98%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.98%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.98%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.98%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 0.98%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.98%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.98%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 0.98%   |
| Nvidia MCP67 Ethernet                                                         | 1         | 0.98%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 0.98%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 0.98%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 0.98%   |
| Intel WiFi Link 5100                                                          | 1         | 0.98%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 19        | 36.54%  |
| Intel                           | 17        | 32.69%  |
| Broadcom                        | 10        | 19.23%  |
| Realtek Semiconductor           | 2         | 3.85%   |
| Texas Instruments               | 1         | 1.92%   |
| Ralink                          | 1         | 1.92%   |
| Qualcomm Atheros Communications | 1         | 1.92%   |
| MediaTek                        | 1         | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 15.09%  |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 4         | 7.55%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 5.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 5.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 3.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 3.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 3.77%   |
| Intel Wireless 7260                                                           | 2         | 3.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 3.77%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 3.77%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 3.77%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.89%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.89%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.89%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.89%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.89%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.89%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.89%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.89%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.89%   |
| Intel WiFi Link 5100                                                          | 1         | 1.89%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.89%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.89%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.89%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.89%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.89%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 1         | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 12        | 27.91%  |
| Intel                            | 10        | 23.26%  |
| Broadcom                         | 7         | 16.28%  |
| Qualcomm Atheros                 | 4         | 9.3%    |
| Marvell Technology Group         | 3         | 6.98%   |
| Silicon Integrated Systems [SiS] | 2         | 4.65%   |
| Nvidia                           | 2         | 4.65%   |
| Broadcom Limited                 | 1         | 2.33%   |
| Attansic Technology              | 1         | 2.33%   |
| ASIX Electronics                 | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.63%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 11.63%  |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 4.65%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2         | 4.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 4.65%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 2         | 4.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.65%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 4.65%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 4.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.33%   |
| Nvidia MCP89 Ethernet                                             | 1         | 2.33%   |
| Nvidia MCP67 Ethernet                                             | 1         | 2.33%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.33%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 2.33%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.33%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 2.33%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.33%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 2.33%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 2.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.33%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 2.33%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 2.33%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 50%     |
| Ethernet | 43        | 43.88%  |
| Modem    | 6         | 6.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 88%     |
| Ethernet | 6         | 12%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 41        | 82%     |
| 1     | 9         | 18%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 80.39%  |
| Yes  | 10        | 19.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Broadcom                | 8         | 40%     |
| Intel                   | 3         | 15%     |
| IMC Networks            | 2         | 10%     |
| Realtek Semiconductor   | 1         | 5%      |
| Ralink Technology       | 1         | 5%      |
| Lite-On Technology      | 1         | 5%      |
| Foxconn / Hon Hai       | 1         | 5%      |
| Cambridge Silicon Radio | 1         | 5%      |
| ASUSTek Computer        | 1         | 5%      |
| Apple                   | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 2         | 10%     |
| IMC Networks Bluetooth Device                       | 2         | 10%     |
| Broadcom HP Portable SoftSailing                    | 2         | 10%     |
| Broadcom BCM2045 Bluetooth                          | 2         | 10%     |
| Realtek RTL8821A Bluetooth                          | 1         | 5%      |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 5%      |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 5%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 5%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 5%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 5%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 5%      |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 5%      |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 5%      |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 5%      |
| Apple Bluetooth Host Controller                     | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 39        | 73.58%  |
| AMD                              | 5         | 9.43%   |
| Nvidia                           | 3         | 5.66%   |
| VIA Technologies                 | 2         | 3.77%   |
| Silicon Integrated Systems [SiS] | 2         | 3.77%   |
| ESS Technology                   | 2         | 3.77%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 18.97%  |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 6.9%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 6.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 5.17%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 3.45%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 3.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 3.45%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.45%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 3.45%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 1.72%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.72%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.72%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 1.72%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.72%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.72%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.72%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.72%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.72%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.72%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.72%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.72%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.72%   |
| AMD High Definition Audio Controller                                       | 1         | 1.72%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 23        | 42.59%  |
| SK hynix            | 10        | 18.52%  |
| Unknown             | 6         | 11.11%  |
| Samsung Electronics | 5         | 9.26%   |
| Micron Technology   | 3         | 5.56%   |
| Kingston            | 3         | 5.56%   |
| Crucial             | 2         | 3.7%    |
| Unknown (8A02)      | 1         | 1.85%   |
| Avant               | 1         | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 6         | 10.53%  |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 5.26%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 3.51%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 3.51%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 3.51%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 1.75%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 1.75%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                   | 1         | 1.75%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 1.75%   |
| Unknown RAM Module 2GB SODIMM DRAM                             | 1         | 1.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.75%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.75%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 1.75%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 1.75%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 1.75%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.75%   |
| Unknown RAM Module 1GB SODIMM DRAM                             | 1         | 1.75%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 1.75%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 1.75%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 1.75%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 1.75%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 1.75%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 1.75%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 1.75%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s           | 1         | 1.75%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.75%   |
| SK hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.75%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1         | 1.75%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.75%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 1.75%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 1.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 1.75%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 1         | 1.75%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s          | 1         | 1.75%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 1.75%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s          | 1         | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 1.75%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 1.75%   |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 14        | 29.79%  |
| SDRAM | 10        | 21.28%  |
| DDR2  | 10        | 21.28%  |
| DDR   | 5         | 10.64%  |
| DRAM  | 4         | 8.51%   |
| DDR4  | 4         | 8.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 44        | 93.62%  |
| DIMM   | 3         | 6.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 17        | 30.91%  |
| 1024  | 13        | 23.64%  |
| 4096  | 9         | 16.36%  |
| 512   | 5         | 9.09%   |
| 8192  | 4         | 7.27%   |
| 256   | 3         | 5.45%   |
| 64    | 2         | 3.64%   |
| 16384 | 1         | 1.82%   |
| 232   | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 39.58%  |
| 1600    | 9         | 18.75%  |
| 1067    | 3         | 6.25%   |
| 533     | 3         | 6.25%   |
| 667     | 2         | 4.17%   |
| 4199    | 1         | 2.08%   |
| 3266    | 1         | 2.08%   |
| 3200    | 1         | 2.08%   |
| 2667    | 1         | 2.08%   |
| 2400    | 1         | 2.08%   |
| 1866    | 1         | 2.08%   |
| 1334    | 1         | 2.08%   |
| 1333    | 1         | 2.08%   |
| 975     | 1         | 2.08%   |
| 800     | 1         | 2.08%   |
| 266     | 1         | 2.08%   |
| 200     | 1         | 2.08%   |

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
| Chicony Electronics                    | 7         | 21.21%  |
| IMC Networks                           | 4         | 12.12%  |
| Cheng Uei Precision Industry (Foxlink) | 4         | 12.12%  |
| Acer                                   | 4         | 12.12%  |
| Microdia                               | 3         | 9.09%   |
| Suyin                                  | 2         | 6.06%   |
| Sunplus Innovation Technology          | 2         | 6.06%   |
| Pixart Imaging                         | 2         | 6.06%   |
| Silicon Motion                         | 1         | 3.03%   |
| Realtek Semiconductor                  | 1         | 3.03%   |
| Lenovo                                 | 1         | 3.03%   |
| Importek                               | 1         | 3.03%   |
| Apple                                  | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 6.06%   |
| Microdia Sonix USB 2.0 Camera                           | 2         | 6.06%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 6.06%   |
| Acer BisonCam, NB Pro                                   | 2         | 6.06%   |
| Suyin USB2.0 UVC 1.3M WebCam                            | 1         | 3.03%   |
| Suyin Integrated_Webcam_HD                              | 1         | 3.03%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 3.03%   |
| Sunplus HD WebCam                                       | 1         | 3.03%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 3.03%   |
| Realtek HD WebCam                                       | 1         | 3.03%   |
| Microdia Integrated Webcam                              | 1         | 3.03%   |
| Lenovo Integrated Webcam                                | 1         | 3.03%   |
| Importek FJ Camera                                      | 1         | 3.03%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 3.03%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 3.03%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 3.03%   |
| Chicony Integrated HP HD Webcam                         | 1         | 3.03%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 3.03%   |
| Chicony EasyCamera                                      | 1         | 3.03%   |
| Chicony CNF8243 Webcam                                  | 1         | 3.03%   |
| Chicony CNF7050                                         | 1         | 3.03%   |
| Chicony Acer CrystalEye Webcam                          | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 3.03%   |
| Apple Built-in iSight                                   | 1         | 3.03%   |
| Acer Lenovo EasyCamera                                  | 1         | 3.03%   |
| Acer Crystal Eye Webcam                                 | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| AuthenTec        | 4         | 66.67%  |
| Validity Sensors | 1         | 16.67%  |
| Upek             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 33.33%  |
| AuthenTec AES1600                                      | 2         | 33.33%  |
| Validity Sensors VFS491                                | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |

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
| 0     | 32        | 64%     |
| 1     | 17        | 34%     |
| 2     | 1         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 12        | 63.16%  |
| Fingerprint reader | 6         | 31.58%  |
| Chipcard           | 1         | 5.26%   |

