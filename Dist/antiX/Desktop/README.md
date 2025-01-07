antiX - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

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

Total: 42

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Maxtang       | BYT30                       | [5891779efd](https://linux-hardware.org/?probe=5891779efd) | Oct 27, 2024 |
| Gigabyte      | B450M S2H                   | [bd91238c40](https://linux-hardware.org/?probe=bd91238c40) | Oct 12, 2024 |
| Pegatron      | Eureka3                     | [e1be68932e](https://linux-hardware.org/?probe=e1be68932e) | Jul 17, 2024 |
| Pegatron      | Eureka3                     | [20309be77a](https://linux-hardware.org/?probe=20309be77a) | Jun 15, 2024 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [2689cb3210](https://linux-hardware.org/?probe=2689cb3210) | Jun 14, 2024 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | [e999e71c4a](https://linux-hardware.org/?probe=e999e71c4a) | Jun 07, 2024 |
| Prestigio     | Smartbook PSB116A           | [044fc5c4f8](https://linux-hardware.org/?probe=044fc5c4f8) | Apr 14, 2024 |
| Gigabyte      | G41MT-S2PT                  | [740b57ea8c](https://linux-hardware.org/?probe=740b57ea8c) | Mar 03, 2024 |
| ASUSTek       | P5K                         | [2835d63be5](https://linux-hardware.org/?probe=2835d63be5) | Jan 31, 2024 |
| ASUSTek       | P5K                         | [5db8fad897](https://linux-hardware.org/?probe=5db8fad897) | Jan 31, 2024 |
| Gigabyte      | GA-MA78GM-S2H               | [d6436b1ea4](https://linux-hardware.org/?probe=d6436b1ea4) | Jan 29, 2024 |
| Unknown       | Alviso                      | [fe4096f520](https://linux-hardware.org/?probe=fe4096f520) | Dec 29, 2023 |
| Dell          | 0FG011                      | [4a5701f000](https://linux-hardware.org/?probe=4a5701f000) | Dec 04, 2023 |
| ASUSTek       | PRIME X570-PRO              | [3baedd7e19](https://linux-hardware.org/?probe=3baedd7e19) | Oct 20, 2023 |
| ASUSTek       | PRIME X470-PRO              | [9d63ed7f5f](https://linux-hardware.org/?probe=9d63ed7f5f) | Oct 19, 2023 |
| Pegatron      | Eureka3                     | [e5c7ff0c70](https://linux-hardware.org/?probe=e5c7ff0c70) | Sep 30, 2023 |
| ASRock        | G31M-S                      | [f1325a7f15](https://linux-hardware.org/?probe=f1325a7f15) | Sep 23, 2023 |
| Intel         | DG41TY AAE47335-202         | [cd00ffcda2](https://linux-hardware.org/?probe=cd00ffcda2) | Sep 09, 2023 |
| Intel         | DG41TY AAE47335-202         | [4cdbce3b75](https://linux-hardware.org/?probe=4cdbce3b75) | Sep 09, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [4551c437bf](https://linux-hardware.org/?probe=4551c437bf) | May 18, 2023 |
| Intel         | H61                         | [aa4606c36c](https://linux-hardware.org/?probe=aa4606c36c) | May 02, 2023 |
| Pegatron      | NARRA5                      | [4c8bb5eff0](https://linux-hardware.org/?probe=4c8bb5eff0) | Apr 30, 2023 |
| MSI           | B550-A PRO                  | [d8b51c995c](https://linux-hardware.org/?probe=d8b51c995c) | Apr 23, 2023 |
| Gigabyte      | Z790 AERO G                 | [f33074a4c8](https://linux-hardware.org/?probe=f33074a4c8) | Apr 03, 2023 |
| Gigabyte      | Z790 AERO G                 | [2f380f0d1a](https://linux-hardware.org/?probe=2f380f0d1a) | Apr 03, 2023 |
| VXL           | M6V90AI-VL                  | [935d6b4b24](https://linux-hardware.org/?probe=935d6b4b24) | Feb 21, 2023 |
| Intel         | D525MW AAE93082-401         | [a225baa8a4](https://linux-hardware.org/?probe=a225baa8a4) | Aug 05, 2022 |
| Biostar       | G31-M7 TE                   | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| Dell          | 0F428D A00                  | [fb8a6009f7](https://linux-hardware.org/?probe=fb8a6009f7) | Jul 16, 2022 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | [af73739875](https://linux-hardware.org/?probe=af73739875) | Jul 14, 2022 |
| Unknown       | K8NF3-VSTA                  | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | [8654086b85](https://linux-hardware.org/?probe=8654086b85) | Jun 20, 2022 |
| Gigabyte      | F2A85XM-D3H                 | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| Gigabyte      | 945GCMX-S2                  | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| Unknown       | NF-CK804                    | [dc6287d017](https://linux-hardware.org/?probe=dc6287d017) | Jan 05, 2022 |
| ASUSTek       | A8R-MVP                     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASRock        | H81M-ITX                    | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| HP            | 3641h                       | [f918637d53](https://linux-hardware.org/?probe=f918637d53) | Jul 29, 2020 |
| Unknown       | Unknown                     | [7653370d96](https://linux-hardware.org/?probe=7653370d96) | Dec 16, 2019 |
| ASUSTek       | P5KPL/1600                  | [8ba4b22f71](https://linux-hardware.org/?probe=8ba4b22f71) | Oct 22, 2019 |
| Lenovo        | ThinkCentre M91p 4480B9U    | [e68917ee9f](https://linux-hardware.org/?probe=e68917ee9f) | Nov 04, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| antiX 21       | 9        | 25%     |
| antiX 22       | 7        | 19.44%  |
| antiX 23.1     | 6        | 16.67%  |
| antiX 23       | 5        | 13.89%  |
| antiX 19.2     | 2        | 5.56%   |
| antiX 17.4.1   | 2        | 5.56%   |
| antiX 21-runit | 1        | 2.78%   |
| antiX 19.4     | 1        | 2.78%   |
| antiX 19.3     | 1        | 2.78%   |
| antiX 17.1     | 1        | 2.78%   |
| antiX 15       | 1        | 2.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| antiX | 35       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.142-antix.2-amd64-smp  | 5        | 13.89%  |
| 6.1.60-antix.1-amd64-smp    | 4        | 11.11%  |
| 5.10.57-antix.1-amd64-smp   | 4        | 11.11%  |
| 5.10.188-antix.1-amd64-smp  | 3        | 8.33%   |
| 4.9.0-279-antix.1-amd64-smp | 3        | 8.33%   |
| 5.10.188-antix.1-486-smp    | 2        | 5.56%   |
| 4.9.160-antix.2-486-smp     | 2        | 5.56%   |
| 4.9.0-326-antix.1-amd64-smp | 2        | 5.56%   |
| 6.2.9-1-liquorix-amd64      | 1        | 2.78%   |
| 6.1.105-antix.1-amd64-smp   | 1        | 2.78%   |
| 6.1.0-0.deb11.9-rt-amd64    | 1        | 2.78%   |
| 5.10.88-antix.1-amd64-smp   | 1        | 2.78%   |
| 5.10.197-antix.1-486-smp    | 1        | 2.78%   |
| 4.9.87-antix.1-amd64-smp    | 1        | 2.78%   |
| 4.9.235-antix.1-amd64-smp   | 1        | 2.78%   |
| 4.9.212-antix.1-amd64-smp   | 1        | 2.78%   |
| 4.9.212-antix.1-486-smp     | 1        | 2.78%   |
| 4.9.0-279-antix.1-486-smp   | 1        | 2.78%   |
| 4.9.0-264-antix.1-amd64-smp | 1        | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.9.0    | 7        | 19.44%  |
| 5.10.188 | 5        | 13.89%  |
| 5.10.142 | 5        | 13.89%  |
| 6.1.60   | 4        | 11.11%  |
| 5.10.57  | 4        | 11.11%  |
| 4.9.212  | 2        | 5.56%   |
| 4.9.160  | 2        | 5.56%   |
| 6.2.9    | 1        | 2.78%   |
| 6.1.105  | 1        | 2.78%   |
| 6.1.0    | 1        | 2.78%   |
| 5.10.88  | 1        | 2.78%   |
| 5.10.197 | 1        | 2.78%   |
| 4.9.87   | 1        | 2.78%   |
| 4.9.235  | 1        | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 16       | 45.71%  |
| 4.9     | 13       | 37.14%  |
| 6.1     | 5        | 14.29%  |
| 6.2     | 1        | 2.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 28       | 80%     |
| i686   | 7        | 20%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| icewm        | 21       | 56.76%  |
| Unknown      | 10       | 27.03%  |
| XFCE         | 2        | 5.41%   |
| herbstluftwm | 2        | 5.41%   |
| jwm          | 1        | 2.7%    |
| dwm          | 1        | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 33       | 94.29%  |
| Tty  | 2        | 5.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLIMSKI | 15       | 41.67%  |
| Unknown | 12       | 33.33%  |
| SLiM    | 7        | 19.44%  |
| LightDM | 2        | 5.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 13       | 37.14%  |
| de_DE   | 4        | 11.43%  |
| en_GB   | 3        | 8.57%   |
| Unknown | 3        | 8.57%   |
| pt_BR   | 2        | 5.71%   |
| pl_PL   | 2        | 5.71%   |
| tr_TR   | 1        | 2.86%   |
| sk_SK   | 1        | 2.86%   |
| ru_RU   | 1        | 2.86%   |
| it_IT   | 1        | 2.86%   |
| hu_HU   | 1        | 2.86%   |
| fr_FR   | 1        | 2.86%   |
| es_PE   | 1        | 2.86%   |
| es_AR   | 1        | 2.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 26       | 74.29%  |
| EFI  | 9        | 25.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 29       | 82.86%  |
| Overlay | 4        | 11.43%  |
| Xfs     | 1        | 2.86%   |
| Ext2    | 1        | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 21       | 60%     |
| GPT     | 13       | 37.14%  |
| Unknown | 1        | 2.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 71.43%  |
| Yes       | 10       | 28.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 65.71%  |
| Yes       | 12       | 34.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 6        | 17.14%  |
| ASUSTek Computer    | 6        | 17.14%  |
| MSI                 | 4        | 11.43%  |
| Unknown             | 4        | 11.43%  |
| Intel               | 3        | 8.57%   |
| Pegatron            | 2        | 5.71%   |
| Dell                | 2        | 5.71%   |
| VXL                 | 1        | 2.86%   |
| TYAN Computer       | 1        | 2.86%   |
| Prestigio           | 1        | 2.86%   |
| Maxtang             | 1        | 2.86%   |
| Lenovo              | 1        | 2.86%   |
| Hewlett-Packard     | 1        | 2.86%   |
| Biostar             | 1        | 2.86%   |
| ASRock              | 1        | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 4        | 11.43%  |
| MSI US Desktop                  | 2        | 5.71%   |
| VXL TC7520d                     | 1        | 2.86%   |
| TYAN Intel 440BX/GX Rev. 4      | 1        | 2.86%   |
| Prestigio Smartbook PSB116A     | 1        | 2.86%   |
| Pegatron VC902AA-ABF p6136fr    | 1        | 2.86%   |
| Pegatron AU930AA-ACJ p6270in    | 1        | 2.86%   |
| MSI MS-7C56                     | 1        | 2.86%   |
| MSI MS-7B17                     | 1        | 2.86%   |
| Maxtang BYT30                   | 1        | 2.86%   |
| Lenovo ThinkCentre M91p 4480B9U | 1        | 2.86%   |
| Intel H61                       | 1        | 2.86%   |
| Intel DG41TY AAE47335-202       | 1        | 2.86%   |
| Intel D525MW AAE93082-401       | 1        | 2.86%   |
| HP t5740                        | 1        | 2.86%   |
| Gigabyte Z790 AERO G            | 1        | 2.86%   |
| Gigabyte GA-MA78GM-S2H          | 1        | 2.86%   |
| Gigabyte G41MT-S2PT             | 1        | 2.86%   |
| Gigabyte F2A85XM-D3H            | 1        | 2.86%   |
| Gigabyte B450M S2H              | 1        | 2.86%   |
| Gigabyte 945GCMX-S2             | 1        | 2.86%   |
| Dell OptiPlex GX270             | 1        | 2.86%   |
| Dell OptiPlex 960               | 1        | 2.86%   |
| Biostar G31-M7 TE               | 1        | 2.86%   |
| ASUS PRIME X570-PRO             | 1        | 2.86%   |
| ASUS PRIME X470-PRO             | 1        | 2.86%   |
| ASUS P8H61-M LX3 PLUS R2.0      | 1        | 2.86%   |
| ASUS P5KPL/1600                 | 1        | 2.86%   |
| ASUS P5K                        | 1        | 2.86%   |
| ASUS A8R-MVP                    | 1        | 2.86%   |
| ASRock G31M-S                   | 1        | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 4        | 11.43%  |
| MSI US                 | 2        | 5.71%   |
| Dell OptiPlex          | 2        | 5.71%   |
| ASUS PRIME             | 2        | 5.71%   |
| VXL TC7520d            | 1        | 2.86%   |
| TYAN Intel             | 1        | 2.86%   |
| Prestigio Smartbook    | 1        | 2.86%   |
| Pegatron VC902AA-ABF   | 1        | 2.86%   |
| Pegatron AU930AA-ACJ   | 1        | 2.86%   |
| MSI MS-7C56            | 1        | 2.86%   |
| MSI MS-7B17            | 1        | 2.86%   |
| Maxtang BYT30          | 1        | 2.86%   |
| Lenovo ThinkCentre     | 1        | 2.86%   |
| Intel H61              | 1        | 2.86%   |
| Intel DG41TY           | 1        | 2.86%   |
| Intel D525MW           | 1        | 2.86%   |
| HP t5740               | 1        | 2.86%   |
| Gigabyte Z790          | 1        | 2.86%   |
| Gigabyte GA-MA78GM-S2H | 1        | 2.86%   |
| Gigabyte G41MT-S2PT    | 1        | 2.86%   |
| Gigabyte F2A85XM-D3H   | 1        | 2.86%   |
| Gigabyte B450M         | 1        | 2.86%   |
| Gigabyte 945GCMX-S2    | 1        | 2.86%   |
| Biostar G31-M7         | 1        | 2.86%   |
| ASUS P8H61-M           | 1        | 2.86%   |
| ASUS P5KPL             | 1        | 2.86%   |
| ASUS P5K               | 1        | 2.86%   |
| ASUS A8R-MVP           | 1        | 2.86%   |
| ASRock G31M-S          | 1        | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2008    | 6        | 17.14%  |
| 2009    | 5        | 14.29%  |
| 2018    | 3        | 8.57%   |
| 2011    | 3        | 8.57%   |
| 2007    | 3        | 8.57%   |
| 2021    | 2        | 5.71%   |
| 2012    | 2        | 5.71%   |
| Unknown | 2        | 5.71%   |
| 2022    | 1        | 2.86%   |
| 2020    | 1        | 2.86%   |
| 2019    | 1        | 2.86%   |
| 2017    | 1        | 2.86%   |
| 2016    | 1        | 2.86%   |
| 2015    | 1        | 2.86%   |
| 2014    | 1        | 2.86%   |
| 2005    | 1        | 2.86%   |
| 2004    | 1        | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 35       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 35       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 35       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 9        | 25.71%  |
| 3.01-4.0    | 6        | 17.14%  |
| 32.01-64.0  | 4        | 11.43%  |
| 4.01-8.0    | 3        | 8.57%   |
| 8.01-16.0   | 3        | 8.57%   |
| 2.01-3.0    | 2        | 5.71%   |
| 64.01-256.0 | 2        | 5.71%   |
| 16.01-24.0  | 2        | 5.71%   |
| 0.51-1.0    | 2        | 5.71%   |
| 0.01-0.5    | 2        | 5.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 12       | 33.33%  |
| 1.01-2.0   | 11       | 30.56%  |
| 0.01-0.5   | 7        | 19.44%  |
| 4.01-8.0   | 3        | 8.33%   |
| 2.01-3.0   | 2        | 5.56%   |
| 32.01-64.0 | 1        | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 57.14%  |
| 2      | 5        | 14.29%  |
| 3      | 4        | 11.43%  |
| 4      | 3        | 8.57%   |
| 0      | 2        | 5.71%   |
| 5      | 1        | 2.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 62.86%  |
| Yes       | 13       | 37.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 94.44%  |
| No        | 2        | 5.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 74.29%  |
| Yes       | 9        | 25.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 77.14%  |
| Yes       | 8        | 22.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 5        | 14.29%  |
| Germany   | 5        | 14.29%  |
| Poland    | 4        | 11.43%  |
| UK        | 3        | 8.57%   |
| Russia    | 2        | 5.71%   |
| Italy     | 2        | 5.71%   |
| France    | 2        | 5.71%   |
| Czechia   | 2        | 5.71%   |
| Brazil    | 2        | 5.71%   |
| Spain     | 1        | 2.86%   |
| Slovakia  | 1        | 2.86%   |
| Peru      | 1        | 2.86%   |
| Japan     | 1        | 2.86%   |
| India     | 1        | 2.86%   |
| Hungary   | 1        | 2.86%   |
| Greece    | 1        | 2.86%   |
| Argentina | 1        | 2.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zagnansk          | 1        | 2.7%    |
| Violes            | 1        | 2.7%    |
| Tokyo             | 1        | 2.7%    |
| St Albans         | 1        | 2.7%    |
| Romilly-sur-Seine | 1        | 2.7%    |
| Prague            | 1        | 2.7%    |
| Padova            | 1        | 2.7%    |
| Otwock            | 1        | 2.7%    |
| Olomouc           | 1        | 2.7%    |
| Nova Londrina     | 1        | 2.7%    |
| Miami             | 1        | 2.7%    |
| Mason             | 1        | 2.7%    |
| Maringá          | 1        | 2.7%    |
| Maidstone         | 1        | 2.7%    |
| Lima              | 1        | 2.7%    |
| Kelkheim          | 1        | 2.7%    |
| Kazan’          | 1        | 2.7%    |
| Katowice          | 1        | 2.7%    |
| Hyderabad         | 1        | 2.7%    |
| Houston           | 1        | 2.7%    |
| Heraklion         | 1        | 2.7%    |
| Greenwich         | 1        | 2.7%    |
| Gmina Chełmiec   | 1        | 2.7%    |
| Gava              | 1        | 2.7%    |
| Galliate Lombardo | 1        | 2.7%    |
| Friedrichshafen   | 1        | 2.7%    |
| Frankfurt am Main | 1        | 2.7%    |
| Flensburg         | 1        | 2.7%    |
| Dharmapuri        | 1        | 2.7%    |
| Covington         | 1        | 2.7%    |
| Buenos Aires      | 1        | 2.7%    |
| Budapest          | 1        | 2.7%    |
| Bryansk           | 1        | 2.7%    |
| Bratislava        | 1        | 2.7%    |
| Boulder           | 1        | 2.7%    |
| Bornheim          | 1        | 2.7%    |
| Bengaluru         | 1        | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 10       | 14     | 20%     |
| Seagate                   | 7        | 7      | 14%     |
| Samsung Electronics       | 7        | 9      | 14%     |
| Toshiba                   | 5        | 6      | 10%     |
| SanDisk                   | 3        | 3      | 6%      |
| Kingston                  | 3        | 4      | 6%      |
| Micron/Crucial Technology | 2        | 2      | 4%      |
| Maxtor                    | 2        | 2      | 4%      |
| Hitachi                   | 2        | 4      | 4%      |
| BHT                       | 2        | 2      | 4%      |
| Unknown                   | 1        | 1      | 2%      |
| PNY                       | 1        | 1      | 2%      |
| Patriot                   | 1        | 1      | 2%      |
| NVMe                      | 1        | 1      | 2%      |
| Intel                     | 1        | 1      | 2%      |
| Crucial                   | 1        | 1      | 2%      |
| Apacer                    | 1        | 1      | 2%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| WDC WD800AAJS-75M0A0 80GB                            | 2        | 3.77%   |
| WDC WD10SPZX-80Z10T2 1TB                             | 2        | 3.77%   |
| Toshiba MQ01ABD050V -63 500GB                        | 2        | 3.77%   |
| Seagate ST1000DM010-2EP102 1TB                       | 2        | 3.77%   |
| Kingston SA400S37240G 240GB SSD                      | 2        | 3.77%   |
| BHT WR202F0032G 670270F5 32GB SSD                    | 2        | 3.77%   |
| WDC WD800JB-00ETA0 80GB                              | 1        | 1.89%   |
| WDC WD5000AVDS-63U7B1 500GB                          | 1        | 1.89%   |
| WDC WD5000AAKX-60U6AA0 500GB                         | 1        | 1.89%   |
| WDC WD205BA 21GB                                     | 1        | 1.89%   |
| WDC WD2003FZEX-00Z4SA0 2TB                           | 1        | 1.89%   |
| WDC WD1600AAJS-00PSA0 160GB                          | 1        | 1.89%   |
| WDC WD10EADS-65M2B0 1TB                              | 1        | 1.89%   |
| WDC WD1005FBYZ-01YCBB3 1TB                           | 1        | 1.89%   |
| Unknown 2GB ATA Flash Disk                           | 1        | 1.89%   |
| Toshiba MQ01ABD100 1TB                               | 1        | 1.89%   |
| Toshiba MG06ACA600E 6TB                              | 1        | 1.89%   |
| Toshiba HDWD110 1TB                                  | 1        | 1.89%   |
| Seagate ST500DM002-1BD142 500GB                      | 1        | 1.89%   |
| Seagate ST3500312CS 500GB                            | 1        | 1.89%   |
| Seagate ST3320620AS 320GB                            | 1        | 1.89%   |
| Seagate ST3320413CS 320GB                            | 1        | 1.89%   |
| Seagate ST1000LM048-2E7172 1TB                       | 1        | 1.89%   |
| SanDisk SSD PLUS 240GB                               | 1        | 1.89%   |
| SanDisk sandisk120 120GB SSD                         | 1        | 1.89%   |
| SanDisk DF4032  32GB                                 | 1        | 1.89%   |
| Samsung SSD 860 EVO 500GB                            | 1        | 1.89%   |
| Samsung SSD 850 EVO 120GB                            | 1        | 1.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 1        | 1.89%   |
| Samsung HM321HI 320GB                                | 1        | 1.89%   |
| Samsung HD250HJ 250GB                                | 1        | 1.89%   |
| Samsung HD162GJ 160GB                                | 1        | 1.89%   |
| Samsung HD160JJ 160GB                                | 1        | 1.89%   |
| Samsung HD080HJ/ 80GB                                | 1        | 1.89%   |
| PNY CS900 120GB SSD                                  | 1        | 1.89%   |
| Patriot Flare 64GB SSD                               | 1        | 1.89%   |
| NVMe XPG GAMMIX S50 1TB                              | 1        | 1.89%   |
| Micron/Crucial P1 NVMe PCIe SSD 1TB                  | 1        | 1.89%   |
| Micron/Crucial CT2000P5PSSD8 2TB                     | 1        | 1.89%   |
| Maxtor Z1 SSD 240GB                                  | 1        | 1.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 14     | 33.33%  |
| Seagate             | 7        | 7      | 23.33%  |
| Toshiba             | 5        | 6      | 16.67%  |
| Samsung Electronics | 4        | 5      | 13.33%  |
| Hitachi             | 2        | 4      | 6.67%   |
| Unknown             | 1        | 1      | 3.33%   |
| Maxtor              | 1        | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 3        | 4      | 21.43%  |
| SanDisk             | 2        | 2      | 14.29%  |
| Samsung Electronics | 2        | 2      | 14.29%  |
| BHT                 | 2        | 2      | 14.29%  |
| PNY                 | 1        | 1      | 7.14%   |
| Patriot             | 1        | 1      | 7.14%   |
| Maxtor              | 1        | 1      | 7.14%   |
| Crucial             | 1        | 1      | 7.14%   |
| Apacer              | 1        | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 38     | 54.76%  |
| SSD  | 14       | 15     | 33.33%  |
| NVMe | 4        | 6      | 9.52%   |
| MMC  | 1        | 1      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 31       | 52     | 83.78%  |
| NVMe | 4        | 6      | 10.81%  |
| SAS  | 1        | 1      | 2.7%    |
| MMC  | 1        | 1      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 27       | 41     | 72.97%  |
| 0.51-1.0   | 8        | 9      | 21.62%  |
| 1.01-2.0   | 1        | 1      | 2.7%    |
| 4.01-10.0  | 1        | 2      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 6        | 16.67%  |
| 21-50          | 6        | 16.67%  |
| 101-250        | 6        | 16.67%  |
| 51-100         | 6        | 16.67%  |
| 1-20           | 4        | 11.11%  |
| 501-1000       | 4        | 11.11%  |
| More than 3000 | 2        | 5.56%   |
| 1001-2000      | 2        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 25       | 69.44%  |
| 101-250        | 5        | 13.89%  |
| More than 3000 | 2        | 5.56%   |
| 21-50          | 2        | 5.56%   |
| 501-1000       | 1        | 2.78%   |
| 51-100         | 1        | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB                   | 2        | 2      | 12.5%   |
| WDC WD800JB-00ETA0 80GB                     | 1        | 1      | 6.25%   |
| WDC WD5000AAKX-60U6AA0 500GB                | 1        | 3      | 6.25%   |
| WDC WD205BA 21GB                            | 1        | 1      | 6.25%   |
| WDC WD10EADS-65M2B0 1TB                     | 1        | 1      | 6.25%   |
| Toshiba MQ01ABD100 1TB                      | 1        | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB             | 1        | 1      | 6.25%   |
| Seagate ST3500312CS 500GB                   | 1        | 1      | 6.25%   |
| Seagate ST3320620AS 320GB                   | 1        | 1      | 6.25%   |
| Seagate ST3320413CS 320GB                   | 1        | 1      | 6.25%   |
| Seagate ST1000DM010-2EP102 1TB              | 1        | 1      | 6.25%   |
| SanDisk sandisk120 120GB SSD                | 1        | 1      | 6.25%   |
| Micron/Crucial Technology CT2000P5PSSD8 2TB | 1        | 1      | 6.25%   |
| Maxtor 2F040L0 41GB                         | 1        | 1      | 6.25%   |
| Apacer 32GB SATA Flash Drive SSD            | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 6        | 8      | 37.5%   |
| Seagate                   | 5        | 5      | 31.25%  |
| Toshiba                   | 1        | 1      | 6.25%   |
| SanDisk                   | 1        | 1      | 6.25%   |
| Micron/Crucial Technology | 1        | 1      | 6.25%   |
| Maxtor                    | 1        | 1      | 6.25%   |
| Apacer                    | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 8      | 46.15%  |
| Seagate | 5        | 5      | 38.46%  |
| Toshiba | 1        | 1      | 7.69%   |
| Maxtor  | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 15     | 81.25%  |
| SSD  | 2        | 2      | 12.5%   |
| NVMe | 1        | 1      | 6.25%   |

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
| Works    | 18       | 33     | 43.9%   |
| Malfunc  | 16       | 18     | 39.02%  |
| Detected | 7        | 9      | 17.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 23       | 52.27%  |
| AMD                       | 6        | 13.64%  |
| ASMedia Technology        | 4        | 9.09%   |
| Nvidia                    | 3        | 6.82%   |
| Micron/Crucial Technology | 2        | 4.55%   |
| VIA Technologies          | 1        | 2.27%   |
| ULi Electronics           | 1        | 2.27%   |
| Samsung Electronics       | 1        | 2.27%   |
| LSI Logic / Symbios Logic | 1        | 2.27%   |
| JMicron Technology        | 1        | 2.27%   |
| ADATA Technology          | 1        | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 10%     |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 6.67%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3        | 5%      |
| Intel 82371AB/EB/MB PIIX4 IDE                                                           | 2        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 3.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 3.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 3.33%   |
| VIA VX900 Series Serial-ATA Controller                                                  | 1        | 1.67%   |
| ULi ULi M5288 SATA                                                                      | 1        | 1.67%   |
| ULi M5229 IDE                                                                           | 1        | 1.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 1.67%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1        | 1.67%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 1.67%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                              | 1        | 1.67%   |
| Nvidia CK804 Serial ATA Controller                                                      | 1        | 1.67%   |
| Nvidia CK804 IDE                                                                        | 1        | 1.67%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 1        | 1.67%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                               | 1        | 1.67%   |
| LSI Logic / Symbios Logic SAS3008 PCI-Express Fusion-MPT SAS-3                          | 1        | 1.67%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.67%   |
| Intel SSD 660P Series                                                                   | 1        | 1.67%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.67%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 1        | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 1.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 1        | 1.67%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 1.67%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.67%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 1        | 1.67%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 1        | 1.67%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 1        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.67%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.67%   |
| ASMedia ASM1061 Serial ATA Controller                                                   | 1        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 21       | 48.84%  |
| SATA | 16       | 37.21%  |
| NVMe | 4        | 9.3%    |
| RAID | 1        | 2.33%   |
| SAS  | 1        | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 24       | 68.57%  |
| AMD          | 10       | 28.57%  |
| CentaurHauls | 1        | 2.86%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2        | 5.71%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2        | 5.71%   |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1        | 2.86%   |
| Intel Pentium M processor 1.73GHz           | 1        | 2.86%   |
| Intel Pentium III (Katmai)                  | 1        | 2.86%   |
| Intel Pentium II (Deschutes)                | 1        | 2.86%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 2.86%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 2.86%   |
| Intel Pentium CPU G2130 @ 3.20GHz           | 1        | 2.86%   |
| Intel Pentium 4 CPU 2.40GHz                 | 1        | 2.86%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 2.86%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 2.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 2.86%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 2.86%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 2.86%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 2.86%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 2.86%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 2.86%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 1        | 2.86%   |
| Intel Atom CPU N280 @ 1.66GHz               | 1        | 2.86%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 2.86%   |
| Intel 13th Gen Core i9-13900K               | 1        | 2.86%   |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz   | 1        | 2.86%   |
| AMD Sempron Processor 3000+                 | 1        | 2.86%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 2.86%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 1        | 2.86%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 1        | 2.86%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 2.86%   |
| AMD Phenom II X4 965 Processor              | 1        | 2.86%   |
| AMD Phenom 9650 Quad-Core Processor         | 1        | 2.86%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+  | 1        | 2.86%   |
| AMD Athlon 64 Processor 3200+               | 1        | 2.86%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 1        | 2.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Other                   | 3        | 8.57%   |
| Intel Pentium Dual-Core | 3        | 8.57%   |
| Intel Core 2 Duo        | 3        | 8.57%   |
| Intel Atom              | 3        | 8.57%   |
| Intel Pentium           | 2        | 5.71%   |
| AMD Ryzen 7             | 2        | 5.71%   |
| Intel Xeon              | 1        | 2.86%   |
| Intel Pentium M         | 1        | 2.86%   |
| Intel Pentium III       | 1        | 2.86%   |
| Intel Pentium Dual      | 1        | 2.86%   |
| Intel Pentium 4         | 1        | 2.86%   |
| Intel Core i9           | 1        | 2.86%   |
| Intel Core i7           | 1        | 2.86%   |
| Intel Core i5           | 1        | 2.86%   |
| Intel Core 2 Quad       | 1        | 2.86%   |
| Intel Celeron           | 1        | 2.86%   |
| CentaurHauls VIA Eden   | 1        | 2.86%   |
| AMD Sempron             | 1        | 2.86%   |
| AMD Ryzen 5             | 1        | 2.86%   |
| AMD Ryzen 3             | 1        | 2.86%   |
| AMD Phenom II X4        | 1        | 2.86%   |
| AMD Phenom              | 1        | 2.86%   |
| AMD Athlon 64 X2        | 1        | 2.86%   |
| AMD Athlon 64           | 1        | 2.86%   |
| AMD A6                  | 1        | 2.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 34.29%  |
| 4      | 9        | 25.71%  |
| 1      | 7        | 20%     |
| 8      | 3        | 8.57%   |
| 6      | 3        | 8.57%   |
| 24     | 1        | 2.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 34       | 97.14%  |
| 2      | 1        | 2.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 68.57%  |
| 2      | 11       | 31.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 30       | 85.71%  |
| 32-bit         | 5        | 14.29%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 6        | 17.14%  |
| Unknown    | 6        | 17.14%  |
| 0xa0671    | 2        | 5.71%   |
| 0x30678    | 2        | 5.71%   |
| 0x206a7    | 2        | 5.71%   |
| 0x10676    | 2        | 5.71%   |
| 0xf29      | 1        | 2.86%   |
| 0x906ed    | 1        | 2.86%   |
| 0x6fd      | 1        | 2.86%   |
| 0x6d8      | 1        | 2.86%   |
| 0x673      | 1        | 2.86%   |
| 0x652      | 1        | 2.86%   |
| 0x306a9    | 1        | 2.86%   |
| 0x106ca    | 1        | 2.86%   |
| 0x106c2    | 1        | 2.86%   |
| 0x08701021 | 1        | 2.86%   |
| 0x08108109 | 1        | 2.86%   |
| 0x08001138 | 1        | 2.86%   |
| 0x06001116 | 1        | 2.86%   |
| 0x010000c8 | 1        | 2.86%   |
| 0x01000095 | 1        | 2.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 8        | 22.86%  |
| Unknown          | 4        | 11.43%  |
| K8 Hammer        | 3        | 8.57%   |
| Zen+             | 2        | 5.71%   |
| Silvermont       | 2        | 5.71%   |
| SandyBridge      | 2        | 5.71%   |
| P6               | 2        | 5.71%   |
| K10              | 2        | 5.71%   |
| Bonnell          | 2        | 5.71%   |
| Zen 2            | 1        | 2.86%   |
| Zen              | 1        | 2.86%   |
| Piledriver       | 1        | 2.86%   |
| NetBurst         | 1        | 2.86%   |
| KabyLake         | 1        | 2.86%   |
| IvyBridge        | 1        | 2.86%   |
| Core             | 1        | 2.86%   |
| Alderlake Hybrid | 1        | 2.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 14       | 37.84%  |
| Intel            | 14       | 37.84%  |
| AMD              | 8        | 21.62%  |
| VIA Technologies | 1        | 2.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 2        | 5%      |
| Nvidia GP108 [GeForce GT 1030]                                            | 2        | 5%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2        | 5%      |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 2        | 5%      |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 2        | 5%      |
| VIA Technologies VX900 Graphics [Chrome9 HD]                              | 1        | 2.5%    |
| Nvidia TU116 [GeForce GTX 1660]                                           | 1        | 2.5%    |
| Nvidia NV44A [GeForce 6200]                                               | 1        | 2.5%    |
| Nvidia GT218 [GeForce G210]                                               | 1        | 2.5%    |
| Nvidia GT216 [GeForce GT 220]                                             | 1        | 2.5%    |
| Nvidia GM204 [GeForce GTX 980]                                            | 1        | 2.5%    |
| Nvidia GF119 [GeForce GT 520]                                             | 1        | 2.5%    |
| Nvidia GF108 [GeForce GT 630]                                             | 1        | 2.5%    |
| Nvidia GF108 [GeForce GT 430]                                             | 1        | 2.5%    |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                        | 1        | 2.5%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                       | 1        | 2.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 2.5%    |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1        | 2.5%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                 | 1        | 2.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1        | 2.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 2.5%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1        | 2.5%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 1        | 2.5%    |
| Intel 82945G/GZ Integrated Graphics Controller                            | 1        | 2.5%    |
| Intel 82865G Integrated Graphics Controller                               | 1        | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 2.5%    |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 2.5%    |
| AMD RV516 [Radeon X1300/X1550 Series]                                     | 1        | 2.5%    |
| AMD RV515 [Radeon X1300/X1550]                                            | 1        | 2.5%    |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 2.5%    |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                   | 1        | 2.5%    |
| AMD RV280 [Radeon 9200 PRO / 9250]                                        | 1        | 2.5%    |
| AMD RS780 [Radeon HD 3200]                                                | 1        | 2.5%    |
| AMD Rage 3 [3D Rage PRO AGP 2X]                                           | 1        | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1        | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 12       | 34.29%  |
| 1 x Intel      | 11       | 31.43%  |
| 1 x AMD        | 5        | 14.29%  |
| 2 x AMD        | 3        | 8.57%   |
| Intel + Nvidia | 2        | 5.71%   |
| 2 x Intel      | 1        | 2.86%   |
| 1 x VIA        | 1        | 2.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 22       | 62.86%  |
| Unknown     | 7        | 20%     |
| Proprietary | 6        | 17.14%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 51.43%  |
| 0.01-0.5   | 7        | 20%     |
| 1.01-2.0   | 4        | 11.43%  |
| 5.01-6.0   | 2        | 5.71%   |
| 0.51-1.0   | 2        | 5.71%   |
| 3.01-4.0   | 1        | 2.86%   |
| 16.01-24.0 | 1        | 2.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Acer                 | 4        | 16.67%  |
| Samsung Electronics  | 3        | 12.5%   |
| Goldstar             | 3        | 12.5%   |
| Ancor Communications | 3        | 12.5%   |
| Vizio                | 1        | 4.17%   |
| ViewSonic            | 1        | 4.17%   |
| Unknown (XXX)        | 1        | 4.17%   |
| OUT                  | 1        | 4.17%   |
| LG Electronics       | 1        | 4.17%   |
| Hewlett-Packard      | 1        | 4.17%   |
| HannStar             | 1        | 4.17%   |
| Dell                 | 1        | 4.17%   |
| BOE                  | 1        | 4.17%   |
| AOC                  | 1        | 4.17%   |
| Unknown              | 1        | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio E320i-A0 VIZ1002 1366x768 698x392mm 31.5-inch                   | 1        | 4.17%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 1        | 4.17%   |
| Unknown (XXX) LCDTV XXX0180 1440x900 884x663mm 43.5-inch              | 1        | 4.17%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 474x296mm 22.0-inch  | 1        | 4.17%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch  | 1        | 4.17%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 477x268mm 21.5-inch   | 1        | 4.17%   |
| OUT Analog OUT0170 1280x768 368x207mm 16.6-inch                       | 1        | 4.17%   |
| LG Electronics LCD Monitor LG Ultra HD 4480x3600                      | 1        | 4.17%   |
| Hewlett-Packard LP2475w HWP26F7 1920x1200 546x352mm 25.6-inch         | 1        | 4.17%   |
| HannStar HE195APB HSD4774 1366x768 410x230mm 18.5-inch                | 1        | 4.17%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 1        | 4.17%   |
| Goldstar TV GSM9CF5 1360x768 700x392mm 31.6-inch                      | 1        | 4.17%   |
| Goldstar M198WA GSM4B36 1440x900 408x255mm 18.9-inch                  | 1        | 4.17%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                      | 1        | 4.17%   |
| BOE LCD Monitor BOE0623 1366x768 256x144mm 11.6-inch                  | 1        | 4.17%   |
| AOC 2280W AOC2280 1920x1080 477x268mm 21.5-inch                       | 1        | 4.17%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 1        | 4.17%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1        | 4.17%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 1        | 4.17%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 1        | 4.17%   |
| Acer V243H ACR00A3 1920x1080 531x298mm 24.0-inch                      | 1        | 4.17%   |
| Acer V223HQV ACR025D 1920x1080 510x287mm 23.0-inch                    | 1        | 4.17%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                     | 1        | 4.17%   |
| Unknown                                                               | 1        | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 45.83%  |
| 1366x768 (WXGA)    | 4        | 16.67%  |
| 4480x3600          | 1        | 4.17%   |
| 2560x1080          | 1        | 4.17%   |
| 1920x1200 (WUXGA)  | 1        | 4.17%   |
| 1680x1050 (WSXGA+) | 1        | 4.17%   |
| 1600x1200          | 1        | 4.17%   |
| 1440x900 (WXGA+)   | 1        | 4.17%   |
| 1360x768           | 1        | 4.17%   |
| 1280x1024 (SXGA)   | 1        | 4.17%   |
| Unknown            | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 6        | 26.09%  |
| 27      | 3        | 13.04%  |
| 18      | 2        | 8.7%    |
| 43      | 1        | 4.35%   |
| 38      | 1        | 4.35%   |
| 34      | 1        | 4.35%   |
| 31      | 1        | 4.35%   |
| 25      | 1        | 4.35%   |
| 24      | 1        | 4.35%   |
| 23      | 1        | 4.35%   |
| 22      | 1        | 4.35%   |
| 19      | 1        | 4.35%   |
| 16      | 1        | 4.35%   |
| 11      | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 10       | 43.48%  |
| 501-600     | 6        | 26.09%  |
| 801-900     | 2        | 8.7%    |
| 701-800     | 1        | 4.35%   |
| 601-700     | 1        | 4.35%   |
| 351-400     | 1        | 4.35%   |
| 201-300     | 1        | 4.35%   |
| Unknown     | 1        | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 16       | 69.57%  |
| 16/10   | 3        | 13.04%  |
| 4/3     | 2        | 8.7%    |
| 21/9    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 34.78%  |
| 301-350        | 3        | 13.04%  |
| 351-500        | 2        | 8.7%    |
| 151-200        | 2        | 8.7%    |
| 141-150        | 2        | 8.7%    |
| 501-1000       | 2        | 8.7%    |
| 51-60          | 1        | 4.35%   |
| 251-300        | 1        | 4.35%   |
| 111-120        | 1        | 4.35%   |
| Unknown        | 1        | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 56.52%  |
| 101-120 | 5        | 21.74%  |
| 1-50    | 3        | 13.04%  |
| 121-160 | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 77.14%  |
| 0     | 7        | 20%     |
| 2     | 1        | 2.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 21       | 45.65%  |
| Intel                           | 10       | 21.74%  |
| Nvidia                          | 3        | 6.52%   |
| Ralink Technology               | 2        | 4.35%   |
| vivo                            | 1        | 2.17%   |
| Samsung Electronics             | 1        | 2.17%   |
| Ralink                          | 1        | 2.17%   |
| Qualcomm Atheros Communications | 1        | 2.17%   |
| Qualcomm Atheros                | 1        | 2.17%   |
| OnePlus Technology (Shenzhen)   | 1        | 2.17%   |
| Marvell Technology Group        | 1        | 2.17%   |
| LSI                             | 1        | 2.17%   |
| Broadcom                        | 1        | 2.17%   |
| 3Com                            | 1        | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 10       | 19.23%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3        | 5.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 5.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 3.85%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 3.85%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2        | 3.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 3.85%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 3.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 3.85%   |
| Intel I211 Gigabit Network Connection                                         | 2        | 3.85%   |
| vivo 1820                                                                     | 1        | 1.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 1.92%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1        | 1.92%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 1.92%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 1.92%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 1.92%   |
| OnePlus (Shenzhen) OnePlus                                                    | 1        | 1.92%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 1.92%   |
| Nvidia CK8S Ethernet Controller                                               | 1        | 1.92%   |
| Nvidia CK804 Ethernet Controller                                              | 1        | 1.92%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 1.92%   |
| LSI 56k WinModem                                                              | 1        | 1.92%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                             | 1        | 1.92%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.92%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 1.92%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 1.92%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE Ethernet Controller                       | 1        | 1.92%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 1        | 1.92%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 1.92%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 1        | 1.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 36.36%  |
| Realtek Semiconductor           | 3        | 27.27%  |
| Ralink Technology               | 2        | 18.18%  |
| Ralink                          | 1        | 9.09%   |
| Qualcomm Atheros Communications | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 18.18%  |
| Ralink RT5370 Wireless Adapter                                                | 2        | 18.18%  |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 18.18%  |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1        | 9.09%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 9.09%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 9.09%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                             | 1        | 9.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 21       | 55.26%  |
| Intel                         | 8        | 21.05%  |
| Nvidia                        | 3        | 7.89%   |
| vivo                          | 1        | 2.63%   |
| Qualcomm Atheros              | 1        | 2.63%   |
| OnePlus Technology (Shenzhen) | 1        | 2.63%   |
| Marvell Technology Group      | 1        | 2.63%   |
| Broadcom                      | 1        | 2.63%   |
| 3Com                          | 1        | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 10       | 25.64%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 3        | 7.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 7.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 5.13%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 5.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 5.13%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 5.13%   |
| vivo 1820                                                              | 1        | 2.56%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 2.56%   |
| OnePlus (Shenzhen) OnePlus                                             | 1        | 2.56%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 2.56%   |
| Nvidia CK8S Ethernet Controller                                        | 1        | 2.56%   |
| Nvidia CK804 Ethernet Controller                                       | 1        | 2.56%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 2.56%   |
| Intel Ethernet Controller I225-V                                       | 1        | 2.56%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 2.56%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 2.56%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE Ethernet Controller                | 1        | 2.56%   |
| Intel 82540EM Gigabit Ethernet Controller                              | 1        | 2.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1        | 2.56%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                          | 1        | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 34       | 75.56%  |
| WiFi     | 9        | 20%     |
| Modem    | 2        | 4.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 83.33%  |
| WiFi     | 6        | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 68.57%  |
| 2     | 9        | 25.71%  |
| 3     | 1        | 2.86%   |
| 0     | 1        | 2.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 74.29%  |
| Yes  | 9        | 25.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 50%     |
| Cambridge Silicon Radio | 3        | 37.5%   |
| Broadcom                | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 37.5%   |
| Intel AX201 Bluetooth                               | 2        | 25%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 12.5%   |
| Intel AX211 Bluetooth                               | 1        | 12.5%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 20       | 41.67%  |
| Nvidia              | 13       | 27.08%  |
| AMD                 | 6        | 12.5%   |
| Creative Labs       | 3        | 6.25%   |
| VIA Technologies    | 2        | 4.17%   |
| C-Media Electronics | 2        | 4.17%   |
| ULi Electronics     | 1        | 2.08%   |
| Ensoniq             | 1        | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 6        | 11.54%  |
| Nvidia TU116 High Definition Audio Controller                               | 3        | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 3        | 5.77%   |
| Nvidia GP108 High Definition Audio Controller                               | 2        | 3.85%   |
| Nvidia GF108 High Definition Audio Controller                               | 2        | 3.85%   |
| Intel Tiger Lake-H HD Audio Controller                                      | 2        | 3.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 2        | 3.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 2        | 3.85%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 1        | 1.92%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 1.92%   |
| VIA Technologies High Definition Audio Controller                           | 1        | 1.92%   |
| ULi Electronics HD Audio Controller                                         | 1        | 1.92%   |
| Nvidia High Definition Audio Controller                                     | 1        | 1.92%   |
| Nvidia GT216 HDMI Audio Controller                                          | 1        | 1.92%   |
| Nvidia GM204 High Definition Audio Controller                               | 1        | 1.92%   |
| Nvidia GF119 HDMI Audio Controller                                          | 1        | 1.92%   |
| Nvidia GA102 High Definition Audio Controller                               | 1        | 1.92%   |
| Nvidia CK804 AC'97 Audio Controller                                         | 1        | 1.92%   |
| Intel Raptor Lake High Definition Audio Controller                          | 1        | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                  | 1        | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller  | 1        | 1.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 1        | 1.92%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 1        | 1.92%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller            | 1        | 1.92%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                        | 1        | 1.92%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                                | 1        | 1.92%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                           | 1        | 1.92%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]   | 1        | 1.92%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                  | 1        | 1.92%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                               | 1        | 1.92%   |
| C-Media Electronics CM6501                                                  | 1        | 1.92%   |
| AMD Starship/Matisse HD Audio Controller                                    | 1        | 1.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 1        | 1.92%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                      | 1        | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 1        | 1.92%   |
| AMD FCH Azalia Controller                                                   | 1        | 1.92%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                  | 1        | 1.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 1        | 1.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 14       | 38.89%  |
| Kingston            | 5        | 13.89%  |
| SK hynix            | 3        | 8.33%   |
| Samsung Electronics | 3        | 8.33%   |
| Corsair             | 3        | 8.33%   |
| Unknown (0x0DA2)    | 1        | 2.78%   |
| Smart               | 1        | 2.78%   |
| Ramaxel Technology  | 1        | 2.78%   |
| Patriot             | 1        | 2.78%   |
| Kllisre             | 1        | 2.78%   |
| GOODRAM             | 1        | 2.78%   |
| G.Skill             | 1        | 2.78%   |
| A-DATA Technology   | 1        | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                        | 2        | 5.13%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s   | 2        | 5.13%   |
| Unknown RAM Module 512MB DIMM SDRAM 333MT/s              | 1        | 2.56%   |
| Unknown RAM Module 512MB DIMM SDRAM                      | 1        | 2.56%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1        | 2.56%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                | 1        | 2.56%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 2.56%   |
| Unknown RAM Module 4GB DIMM 800MT/s                      | 1        | 2.56%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 2.56%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 1        | 2.56%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 2.56%   |
| Unknown RAM Module 256MB DIMM SDRAM 333MT/s              | 1        | 2.56%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 1        | 2.56%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                 | 1        | 2.56%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                  | 1        | 2.56%   |
| Unknown RAM Module 1GB DIMM 667MT/s                      | 1        | 2.56%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s              | 1        | 2.56%   |
| Unknown (0x0DA2) RAM SB-DR5U-32G 32GB DIMM DDR5 4800MT/s | 1        | 2.56%   |
| Smart RAM SG564568FG8N6KFSQR 2GB DIMM DDR2 800MT/s       | 1        | 2.56%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 2.56%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s   | 1        | 2.56%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM 1333MT/s          | 1        | 2.56%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 1333MT/s          | 1        | 2.56%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s     | 1        | 2.56%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 1        | 2.56%   |
| Ramaxel RAM RMUA5180MH78HBF-2666 16GB DIMM DDR4 2400MT/s | 1        | 2.56%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s       | 1        | 2.56%   |
| Kllisre RAM DDR2 2G 2GB DIMM DDR2 800MT/s                | 1        | 2.56%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s      | 1        | 2.56%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.56%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 2.56%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.56%   |
| Kingston RAM 99U5402-060.A 2GB DIMM DDR3 1333MT/s        | 1        | 2.56%   |
| GOODRAM RAM GR2666D464L19S/8G 8GB DIMM DDR4 2667MT/s     | 1        | 2.56%   |
| G.Skill RAM F4-3200C14-8GTZSW 8192MB DIMM DDR4 3200MT/s  | 1        | 2.56%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s    | 1        | 2.56%   |
| A-DATA RAM DDR4 2666 2OZ 16GB DIMM DDR4 2667MT/s         | 1        | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 9        | 28.13%  |
| DDR4    | 7        | 21.88%  |
| SDRAM   | 6        | 18.75%  |
| Unknown | 4        | 12.5%   |
| DDR2    | 3        | 9.38%   |
| DDR     | 2        | 6.25%   |
| DDR5    | 1        | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 30       | 93.75%  |
| SODIMM | 2        | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 9        | 25%     |
| 4096  | 7        | 19.44%  |
| 16384 | 5        | 13.89%  |
| 1024  | 5        | 13.89%  |
| 512   | 5        | 13.89%  |
| 8192  | 3        | 8.33%   |
| 32768 | 1        | 2.78%   |
| 256   | 1        | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 17.65%  |
| 800     | 4        | 11.76%  |
| Unknown | 4        | 11.76%  |
| 1333    | 3        | 8.82%   |
| 3534    | 2        | 5.88%   |
| 3200    | 2        | 5.88%   |
| 2667    | 2        | 5.88%   |
| 2400    | 2        | 5.88%   |
| 667     | 2        | 5.88%   |
| 400     | 2        | 5.88%   |
| 333     | 2        | 5.88%   |
| 4800    | 1        | 2.94%   |
| 3600    | 1        | 2.94%   |
| 2048    | 1        | 2.94%   |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Pixart Imaging         | 1        | 33.33%  |
| Generalplus Technology | 1        | 33.33%  |
| Alcor Micro            | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 1        | 33.33%  |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 33.33%  |
| Alcor Micro USB 2.0 Camera               | 1        | 33.33%  |

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
| 0     | 23       | 65.71%  |
| 1     | 7        | 20%     |
| 2     | 3        | 8.57%   |
| 4     | 1        | 2.86%   |
| 3     | 1        | 2.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 58.82%  |
| Sound                    | 2        | 11.76%  |
| Communication controller | 2        | 11.76%  |
| Net/ethernet             | 1        | 5.88%   |
| Modem                    | 1        | 5.88%   |
| Camera                   | 1        | 5.88%   |

