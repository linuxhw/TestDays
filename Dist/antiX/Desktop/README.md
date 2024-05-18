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

Total: 36

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Prestigio | Smartbook PSB116A           | [044fc5c4f8](https://linux-hardware.org/?probe=044fc5c4f8) | Apr 14, 2024 |
| Gigabyte  | G41MT-S2PT                  | [740b57ea8c](https://linux-hardware.org/?probe=740b57ea8c) | Mar 03, 2024 |
| ASUSTek   | P5K                         | [2835d63be5](https://linux-hardware.org/?probe=2835d63be5) | Jan 31, 2024 |
| ASUSTek   | P5K                         | [5db8fad897](https://linux-hardware.org/?probe=5db8fad897) | Jan 31, 2024 |
| Gigabyte  | GA-MA78GM-S2H               | [d6436b1ea4](https://linux-hardware.org/?probe=d6436b1ea4) | Jan 29, 2024 |
| Unknown   | Alviso                      | [fe4096f520](https://linux-hardware.org/?probe=fe4096f520) | Dec 29, 2023 |
| Dell      | 0FG011                      | [4a5701f000](https://linux-hardware.org/?probe=4a5701f000) | Dec 04, 2023 |
| ASUSTek   | PRIME X570-PRO              | [3baedd7e19](https://linux-hardware.org/?probe=3baedd7e19) | Oct 20, 2023 |
| ASUSTek   | PRIME X470-PRO              | [9d63ed7f5f](https://linux-hardware.org/?probe=9d63ed7f5f) | Oct 19, 2023 |
| Pegatron  | Eureka3                     | [e5c7ff0c70](https://linux-hardware.org/?probe=e5c7ff0c70) | Sep 30, 2023 |
| ASRock    | G31M-S                      | [f1325a7f15](https://linux-hardware.org/?probe=f1325a7f15) | Sep 23, 2023 |
| Intel     | DG41TY AAE47335-202         | [cd00ffcda2](https://linux-hardware.org/?probe=cd00ffcda2) | Sep 09, 2023 |
| Intel     | DG41TY AAE47335-202         | [4cdbce3b75](https://linux-hardware.org/?probe=4cdbce3b75) | Sep 09, 2023 |
| MSI       | MPG Z390 GAMING PRO CARB... | [4551c437bf](https://linux-hardware.org/?probe=4551c437bf) | May 18, 2023 |
| Intel     | H61                         | [aa4606c36c](https://linux-hardware.org/?probe=aa4606c36c) | May 02, 2023 |
| Pegatron  | NARRA5                      | [4c8bb5eff0](https://linux-hardware.org/?probe=4c8bb5eff0) | Apr 30, 2023 |
| MSI       | B550-A PRO                  | [d8b51c995c](https://linux-hardware.org/?probe=d8b51c995c) | Apr 23, 2023 |
| Gigabyte  | Z790 AERO G                 | [f33074a4c8](https://linux-hardware.org/?probe=f33074a4c8) | Apr 03, 2023 |
| Gigabyte  | Z790 AERO G                 | [2f380f0d1a](https://linux-hardware.org/?probe=2f380f0d1a) | Apr 03, 2023 |
| VXL       | M6V90AI-VL                  | [935d6b4b24](https://linux-hardware.org/?probe=935d6b4b24) | Feb 21, 2023 |
| Intel     | D525MW AAE93082-401         | [a225baa8a4](https://linux-hardware.org/?probe=a225baa8a4) | Aug 05, 2022 |
| Biostar   | G31-M7 TE                   | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| Dell      | 0F428D A00                  | [fb8a6009f7](https://linux-hardware.org/?probe=fb8a6009f7) | Jul 16, 2022 |
| MSI       | B560M PRO-VDH WIFI [CEC]    | [af73739875](https://linux-hardware.org/?probe=af73739875) | Jul 14, 2022 |
| Unknown   | K8NF3-VSTA                  | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI       | B560M PRO-VDH WIFI [CEC]    | [8654086b85](https://linux-hardware.org/?probe=8654086b85) | Jun 20, 2022 |
| Gigabyte  | F2A85XM-D3H                 | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| Gigabyte  | 945GCMX-S2                  | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| Unknown   | NF-CK804                    | [dc6287d017](https://linux-hardware.org/?probe=dc6287d017) | Jan 05, 2022 |
| ASUSTek   | A8R-MVP                     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek   | M2N-MX SE Plus              | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASRock    | H81M-ITX                    | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| HP        | 3641h                       | [f918637d53](https://linux-hardware.org/?probe=f918637d53) | Jul 29, 2020 |
| Unknown   | Unknown                     | [7653370d96](https://linux-hardware.org/?probe=7653370d96) | Dec 16, 2019 |
| ASUSTek   | P5KPL/1600                  | [8ba4b22f71](https://linux-hardware.org/?probe=8ba4b22f71) | Oct 22, 2019 |
| Lenovo    | ThinkCentre M91p 4480B9U    | [e68917ee9f](https://linux-hardware.org/?probe=e68917ee9f) | Nov 04, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| antiX 21       | 9        | 29.03%  |
| antiX 22       | 6        | 19.35%  |
| antiX 23       | 5        | 16.13%  |
| antiX 23.1     | 2        | 6.45%   |
| antiX 19.2     | 2        | 6.45%   |
| antiX 17.4.1   | 2        | 6.45%   |
| antiX 21-runit | 1        | 3.23%   |
| antiX 19.4     | 1        | 3.23%   |
| antiX 19.3     | 1        | 3.23%   |
| antiX 17.1     | 1        | 3.23%   |
| antiX 15       | 1        | 3.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| antiX | 31       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.10.142-antix.2-amd64-smp  | 5        | 16.13%  |
| 5.10.57-antix.1-amd64-smp   | 4        | 12.9%   |
| 5.10.188-antix.1-amd64-smp  | 3        | 9.68%   |
| 4.9.0-279-antix.1-amd64-smp | 3        | 9.68%   |
| 6.1.60-antix.1-amd64-smp    | 2        | 6.45%   |
| 5.10.188-antix.1-486-smp    | 2        | 6.45%   |
| 4.9.160-antix.2-486-smp     | 2        | 6.45%   |
| 6.2.9-1-liquorix-amd64      | 1        | 3.23%   |
| 6.1.0-0.deb11.9-rt-amd64    | 1        | 3.23%   |
| 5.10.88-antix.1-amd64-smp   | 1        | 3.23%   |
| 4.9.87-antix.1-amd64-smp    | 1        | 3.23%   |
| 4.9.235-antix.1-amd64-smp   | 1        | 3.23%   |
| 4.9.212-antix.1-amd64-smp   | 1        | 3.23%   |
| 4.9.212-antix.1-486-smp     | 1        | 3.23%   |
| 4.9.0-326-antix.1-amd64-smp | 1        | 3.23%   |
| 4.9.0-279-antix.1-486-smp   | 1        | 3.23%   |
| 4.9.0-264-antix.1-amd64-smp | 1        | 3.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.9.0    | 6        | 19.35%  |
| 5.10.188 | 5        | 16.13%  |
| 5.10.142 | 5        | 16.13%  |
| 5.10.57  | 4        | 12.9%   |
| 6.1.60   | 2        | 6.45%   |
| 4.9.212  | 2        | 6.45%   |
| 4.9.160  | 2        | 6.45%   |
| 6.2.9    | 1        | 3.23%   |
| 6.1.0    | 1        | 3.23%   |
| 5.10.88  | 1        | 3.23%   |
| 4.9.87   | 1        | 3.23%   |
| 4.9.235  | 1        | 3.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 15       | 48.39%  |
| 4.9     | 12       | 38.71%  |
| 6.1     | 3        | 9.68%   |
| 6.2     | 1        | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 25       | 80.65%  |
| i686   | 6        | 19.35%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| icewm        | 18       | 58.06%  |
| Unknown      | 9        | 29.03%  |
| XFCE         | 2        | 6.45%   |
| jwm          | 1        | 3.23%   |
| herbstluftwm | 1        | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 29       | 93.55%  |
| Tty  | 2        | 6.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLIMSKI | 11       | 35.48%  |
| Unknown | 11       | 35.48%  |
| SLiM    | 7        | 22.58%  |
| LightDM | 2        | 6.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 11       | 35.48%  |
| en_GB   | 3        | 9.68%   |
| de_DE   | 3        | 9.68%   |
| Unknown | 3        | 9.68%   |
| pt_BR   | 2        | 6.45%   |
| pl_PL   | 2        | 6.45%   |
| tr_TR   | 1        | 3.23%   |
| sk_SK   | 1        | 3.23%   |
| ru_RU   | 1        | 3.23%   |
| it_IT   | 1        | 3.23%   |
| fr_FR   | 1        | 3.23%   |
| es_PE   | 1        | 3.23%   |
| es_AR   | 1        | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 24       | 77.42%  |
| EFI  | 7        | 22.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 25       | 80.65%  |
| Overlay | 4        | 12.9%   |
| Xfs     | 1        | 3.23%   |
| Ext2    | 1        | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 19       | 61.29%  |
| GPT     | 11       | 35.48%  |
| Unknown | 1        | 3.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 70.97%  |
| Yes       | 9        | 29.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 61.29%  |
| Yes       | 12       | 38.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 5        | 16.13%  |
| ASUSTek Computer    | 5        | 16.13%  |
| MSI                 | 4        | 12.9%   |
| Unknown             | 4        | 12.9%   |
| Intel               | 3        | 9.68%   |
| Pegatron            | 2        | 6.45%   |
| Dell                | 2        | 6.45%   |
| VXL                 | 1        | 3.23%   |
| Prestigio           | 1        | 3.23%   |
| Lenovo              | 1        | 3.23%   |
| Hewlett-Packard     | 1        | 3.23%   |
| Biostar             | 1        | 3.23%   |
| ASRock              | 1        | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 4        | 12.9%   |
| MSI US Desktop                  | 2        | 6.45%   |
| VXL TC7520d                     | 1        | 3.23%   |
| Prestigio Smartbook PSB116A     | 1        | 3.23%   |
| Pegatron VC902AA-ABF p6136fr    | 1        | 3.23%   |
| Pegatron AU930AA-ACJ p6270in    | 1        | 3.23%   |
| MSI MS-7C56                     | 1        | 3.23%   |
| MSI MS-7B17                     | 1        | 3.23%   |
| Lenovo ThinkCentre M91p 4480B9U | 1        | 3.23%   |
| Intel H61                       | 1        | 3.23%   |
| Intel DG41TY AAE47335-202       | 1        | 3.23%   |
| Intel D525MW AAE93082-401       | 1        | 3.23%   |
| HP t5740                        | 1        | 3.23%   |
| Gigabyte Z790 AERO G            | 1        | 3.23%   |
| Gigabyte GA-MA78GM-S2H          | 1        | 3.23%   |
| Gigabyte G41MT-S2PT             | 1        | 3.23%   |
| Gigabyte F2A85XM-D3H            | 1        | 3.23%   |
| Gigabyte 945GCMX-S2             | 1        | 3.23%   |
| Dell OptiPlex GX270             | 1        | 3.23%   |
| Dell OptiPlex 960               | 1        | 3.23%   |
| Biostar G31-M7 TE               | 1        | 3.23%   |
| ASUS PRIME X570-PRO             | 1        | 3.23%   |
| ASUS PRIME X470-PRO             | 1        | 3.23%   |
| ASUS P5KPL/1600                 | 1        | 3.23%   |
| ASUS P5K                        | 1        | 3.23%   |
| ASUS A8R-MVP                    | 1        | 3.23%   |
| ASRock G31M-S                   | 1        | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 4        | 12.9%   |
| MSI US                 | 2        | 6.45%   |
| Dell OptiPlex          | 2        | 6.45%   |
| ASUS PRIME             | 2        | 6.45%   |
| VXL TC7520d            | 1        | 3.23%   |
| Prestigio Smartbook    | 1        | 3.23%   |
| Pegatron VC902AA-ABF   | 1        | 3.23%   |
| Pegatron AU930AA-ACJ   | 1        | 3.23%   |
| MSI MS-7C56            | 1        | 3.23%   |
| MSI MS-7B17            | 1        | 3.23%   |
| Lenovo ThinkCentre     | 1        | 3.23%   |
| Intel H61              | 1        | 3.23%   |
| Intel DG41TY           | 1        | 3.23%   |
| Intel D525MW           | 1        | 3.23%   |
| HP t5740               | 1        | 3.23%   |
| Gigabyte Z790          | 1        | 3.23%   |
| Gigabyte GA-MA78GM-S2H | 1        | 3.23%   |
| Gigabyte G41MT-S2PT    | 1        | 3.23%   |
| Gigabyte F2A85XM-D3H   | 1        | 3.23%   |
| Gigabyte 945GCMX-S2    | 1        | 3.23%   |
| Biostar G31-M7         | 1        | 3.23%   |
| ASUS P5KPL             | 1        | 3.23%   |
| ASUS P5K               | 1        | 3.23%   |
| ASUS A8R-MVP           | 1        | 3.23%   |
| ASRock G31M-S          | 1        | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2008    | 6        | 19.35%  |
| 2009    | 5        | 16.13%  |
| 2011    | 3        | 9.68%   |
| 2007    | 3        | 9.68%   |
| 2021    | 2        | 6.45%   |
| 2018    | 2        | 6.45%   |
| 2022    | 1        | 3.23%   |
| 2020    | 1        | 3.23%   |
| 2019    | 1        | 3.23%   |
| 2017    | 1        | 3.23%   |
| 2016    | 1        | 3.23%   |
| 2014    | 1        | 3.23%   |
| 2012    | 1        | 3.23%   |
| 2005    | 1        | 3.23%   |
| 2004    | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 31       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 31       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 9        | 29.03%  |
| 32.01-64.0  | 4        | 12.9%   |
| 3.01-4.0    | 4        | 12.9%   |
| 8.01-16.0   | 3        | 9.68%   |
| 4.01-8.0    | 2        | 6.45%   |
| 2.01-3.0    | 2        | 6.45%   |
| 64.01-256.0 | 2        | 6.45%   |
| 16.01-24.0  | 2        | 6.45%   |
| 0.51-1.0    | 2        | 6.45%   |
| 0.01-0.5    | 1        | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 11       | 35.48%  |
| 1.01-2.0   | 9        | 29.03%  |
| 0.01-0.5   | 6        | 19.35%  |
| 4.01-8.0   | 2        | 6.45%   |
| 2.01-3.0   | 2        | 6.45%   |
| 32.01-64.0 | 1        | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 51.61%  |
| 2      | 5        | 16.13%  |
| 3      | 4        | 12.9%   |
| 4      | 3        | 9.68%   |
| 0      | 2        | 6.45%   |
| 5      | 1        | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 61.29%  |
| Yes       | 12       | 38.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 93.55%  |
| No        | 2        | 6.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 74.19%  |
| Yes       | 8        | 25.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 77.42%  |
| Yes       | 7        | 22.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 5        | 16.13%  |
| Poland    | 4        | 12.9%   |
| Germany   | 4        | 12.9%   |
| UK        | 3        | 9.68%   |
| Russia    | 2        | 6.45%   |
| Italy     | 2        | 6.45%   |
| France    | 2        | 6.45%   |
| Brazil    | 2        | 6.45%   |
| Slovakia  | 1        | 3.23%   |
| Peru      | 1        | 3.23%   |
| Japan     | 1        | 3.23%   |
| India     | 1        | 3.23%   |
| Greece    | 1        | 3.23%   |
| Czechia   | 1        | 3.23%   |
| Argentina | 1        | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zagnansk          | 1        | 3.23%   |
| Violes            | 1        | 3.23%   |
| Tokyo             | 1        | 3.23%   |
| St Albans         | 1        | 3.23%   |
| Romilly-sur-Seine | 1        | 3.23%   |
| Prague            | 1        | 3.23%   |
| Padova            | 1        | 3.23%   |
| Otwock            | 1        | 3.23%   |
| Nova Londrina     | 1        | 3.23%   |
| Miami             | 1        | 3.23%   |
| Mason             | 1        | 3.23%   |
| Maringá          | 1        | 3.23%   |
| Maidstone         | 1        | 3.23%   |
| Lima              | 1        | 3.23%   |
| Kelkheim          | 1        | 3.23%   |
| Kazan’          | 1        | 3.23%   |
| Katowice          | 1        | 3.23%   |
| Houston           | 1        | 3.23%   |
| Heraklion         | 1        | 3.23%   |
| Greenwich         | 1        | 3.23%   |
| Gmina Chełmiec   | 1        | 3.23%   |
| Galliate Lombardo | 1        | 3.23%   |
| Friedrichshafen   | 1        | 3.23%   |
| Frankfurt am Main | 1        | 3.23%   |
| Flensburg         | 1        | 3.23%   |
| Covington         | 1        | 3.23%   |
| Buenos Aires      | 1        | 3.23%   |
| Bryansk           | 1        | 3.23%   |
| Bratislava        | 1        | 3.23%   |
| Boulder           | 1        | 3.23%   |
| Bengaluru         | 1        | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 10       | 12     | 21.74%  |
| Samsung Electronics       | 7        | 9      | 15.22%  |
| Seagate                   | 6        | 6      | 13.04%  |
| Toshiba                   | 5        | 6      | 10.87%  |
| SanDisk                   | 3        | 3      | 6.52%   |
| Micron/Crucial Technology | 2        | 2      | 4.35%   |
| Maxtor                    | 2        | 2      | 4.35%   |
| Kingston                  | 2        | 3      | 4.35%   |
| Hitachi                   | 2        | 4      | 4.35%   |
| BHT                       | 2        | 2      | 4.35%   |
| Unknown                   | 1        | 1      | 2.17%   |
| NVMe                      | 1        | 1      | 2.17%   |
| Intel                     | 1        | 1      | 2.17%   |
| Crucial                   | 1        | 1      | 2.17%   |
| Apacer                    | 1        | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| WDC WD800AAJS-75M0A0 80GB                          | 2        | 4.08%   |
| WDC WD10SPZX-80Z10T2 1TB                           | 2        | 4.08%   |
| Toshiba MQ01ABD050V -63 500GB                      | 2        | 4.08%   |
| Kingston SA400S37240G 240GB SSD                    | 2        | 4.08%   |
| BHT WR202F0032G 670270F5 32GB SSD                  | 2        | 4.08%   |
| WDC WD800JB-00ETA0 80GB                            | 1        | 2.04%   |
| WDC WD5000AVDS-63U7B1 500GB                        | 1        | 2.04%   |
| WDC WD5000AAKX-60U6AA0 500GB                       | 1        | 2.04%   |
| WDC WD205BA 21GB                                   | 1        | 2.04%   |
| WDC WD2003FZEX-00Z4SA0 2TB                         | 1        | 2.04%   |
| WDC WD1600AAJS-00PSA0 160GB                        | 1        | 2.04%   |
| WDC WD10EADS-65M2B0 1TB                            | 1        | 2.04%   |
| WDC WD1005FBYZ-01YCBB3 1TB                         | 1        | 2.04%   |
| Unknown 2GB ATA Flash Disk                         | 1        | 2.04%   |
| Toshiba MQ01ABD100 1TB                             | 1        | 2.04%   |
| Toshiba MG06ACA600E 6TB                            | 1        | 2.04%   |
| Toshiba HDWD110 1TB                                | 1        | 2.04%   |
| Seagate ST500DM002-1BD142 500GB                    | 1        | 2.04%   |
| Seagate ST3500312CS 500GB                          | 1        | 2.04%   |
| Seagate ST3320620AS 320GB                          | 1        | 2.04%   |
| Seagate ST3320413CS 320GB                          | 1        | 2.04%   |
| Seagate ST1000LM048-2E7172 1TB                     | 1        | 2.04%   |
| Seagate ST1000DM010-2EP102 1TB                     | 1        | 2.04%   |
| SanDisk SSD PLUS 240GB                             | 1        | 2.04%   |
| SanDisk sandisk120 120GB SSD                       | 1        | 2.04%   |
| SanDisk DF4032  32GB                               | 1        | 2.04%   |
| Samsung SSD 860 EVO 500GB                          | 1        | 2.04%   |
| Samsung SSD 850 EVO 120GB                          | 1        | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1        | 2.04%   |
| Samsung HM321HI 320GB                              | 1        | 2.04%   |
| Samsung HD250HJ 250GB                              | 1        | 2.04%   |
| Samsung HD162GJ 160GB                              | 1        | 2.04%   |
| Samsung HD160JJ 160GB                              | 1        | 2.04%   |
| Samsung HD080HJ 80GB                               | 1        | 2.04%   |
| NVMe XPG GAMMIX S50 1TB                            | 1        | 2.04%   |
| Micron/Crucial P1 NVMe PCIe SSD 1TB                | 1        | 2.04%   |
| Micron/Crucial CT2000P5PSSD8 2TB                   | 1        | 2.04%   |
| Maxtor Z1 SSD 240GB                                | 1        | 2.04%   |
| Maxtor 2F040L0 41GB                                | 1        | 2.04%   |
| Intel SSDPEKNW010T8 1TB                            | 1        | 2.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 12     | 34.48%  |
| Seagate             | 6        | 6      | 20.69%  |
| Toshiba             | 5        | 6      | 17.24%  |
| Samsung Electronics | 4        | 5      | 13.79%  |
| Hitachi             | 2        | 4      | 6.9%    |
| Unknown             | 1        | 1      | 3.45%   |
| Maxtor              | 1        | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 2        | 2      | 18.18%  |
| Samsung Electronics | 2        | 2      | 18.18%  |
| Kingston            | 2        | 3      | 18.18%  |
| BHT                 | 2        | 2      | 18.18%  |
| Maxtor              | 1        | 1      | 9.09%   |
| Crucial             | 1        | 1      | 9.09%   |
| Apacer              | 1        | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 35     | 57.89%  |
| SSD  | 11       | 12     | 28.95%  |
| NVMe | 4        | 6      | 10.53%  |
| MMC  | 1        | 1      | 2.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 27       | 46     | 81.82%  |
| NVMe | 4        | 6      | 12.12%  |
| SAS  | 1        | 1      | 3.03%   |
| MMC  | 1        | 1      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 36     | 72.73%  |
| 0.51-1.0   | 7        | 8      | 21.21%  |
| 1.01-2.0   | 1        | 1      | 3.03%   |
| 4.01-10.0  | 1        | 2      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 6        | 19.35%  |
| 21-50          | 6        | 19.35%  |
| 101-250        | 6        | 19.35%  |
| 1-20           | 3        | 9.68%   |
| 501-1000       | 3        | 9.68%   |
| 51-100         | 3        | 9.68%   |
| More than 3000 | 2        | 6.45%   |
| 1001-2000      | 2        | 6.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 22       | 70.97%  |
| 101-250        | 4        | 12.9%   |
| More than 3000 | 2        | 6.45%   |
| 21-50          | 1        | 3.23%   |
| 501-1000       | 1        | 3.23%   |
| 51-100         | 1        | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB                   | 2        | 2      | 13.33%  |
| WDC WD800JB-00ETA0 80GB                     | 1        | 1      | 6.67%   |
| WDC WD5000AAKX-60U6AA0 500GB                | 1        | 1      | 6.67%   |
| WDC WD205BA 21GB                            | 1        | 1      | 6.67%   |
| WDC WD10EADS-65M2B0 1TB                     | 1        | 1      | 6.67%   |
| Toshiba MQ01ABD100 1TB                      | 1        | 1      | 6.67%   |
| Seagate ST500DM002-1BD142 500GB             | 1        | 1      | 6.67%   |
| Seagate ST3500312CS 500GB                   | 1        | 1      | 6.67%   |
| Seagate ST3320620AS 320GB                   | 1        | 1      | 6.67%   |
| Seagate ST3320413CS 320GB                   | 1        | 1      | 6.67%   |
| SanDisk sandisk120 120GB SSD                | 1        | 1      | 6.67%   |
| Micron/Crucial Technology CT2000P5PSSD8 2TB | 1        | 1      | 6.67%   |
| Maxtor 2F040L0 41GB                         | 1        | 1      | 6.67%   |
| Apacer 32GB SATA Flash Drive SSD            | 1        | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 6        | 6      | 40%     |
| Seagate                   | 4        | 4      | 26.67%  |
| Toshiba                   | 1        | 1      | 6.67%   |
| SanDisk                   | 1        | 1      | 6.67%   |
| Micron/Crucial Technology | 1        | 1      | 6.67%   |
| Maxtor                    | 1        | 1      | 6.67%   |
| Apacer                    | 1        | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 6      | 50%     |
| Seagate | 4        | 4      | 33.33%  |
| Toshiba | 1        | 1      | 8.33%   |
| Maxtor  | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 12     | 80%     |
| SSD  | 2        | 2      | 13.33%  |
| NVMe | 1        | 1      | 6.67%   |

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
| Malfunc  | 15       | 15     | 40.54%  |
| Works    | 15       | 30     | 40.54%  |
| Detected | 7        | 9      | 18.92%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 20       | 50%     |
| AMD                       | 5        | 12.5%   |
| ASMedia Technology        | 4        | 10%     |
| Nvidia                    | 3        | 7.5%    |
| Micron/Crucial Technology | 2        | 5%      |
| VIA Technologies          | 1        | 2.5%    |
| ULi Electronics           | 1        | 2.5%    |
| Samsung Electronics       | 1        | 2.5%    |
| LSI Logic / Symbios Logic | 1        | 2.5%    |
| JMicron Technology        | 1        | 2.5%    |
| ADATA Technology          | 1        | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 6        | 10.91%  |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 5        | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 4        | 7.27%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                 | 3        | 5.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 3.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2        | 3.64%   |
| VIA VX900 Series Serial-ATA Controller                                        | 1        | 1.82%   |
| ULi ULi M5288 SATA                                                            | 1        | 1.82%   |
| ULi M5229 IDE                                                                 | 1        | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 1.82%   |
| Nvidia nForce3 Serial ATA Controller                                          | 1        | 1.82%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 1.82%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                    | 1        | 1.82%   |
| Nvidia CK804 Serial ATA Controller                                            | 1        | 1.82%   |
| Nvidia CK804 IDE                                                              | 1        | 1.82%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1        | 1.82%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                     | 1        | 1.82%   |
| LSI Logic / Symbios Logic SAS3008 PCI-Express Fusion-MPT SAS-3                | 1        | 1.82%   |
| JMicron JMB363 SATA/IDE Controller                                            | 1        | 1.82%   |
| Intel SSD 660P Series                                                         | 1        | 1.82%   |
| Intel SATA Controller [RAID mode]                                             | 1        | 1.82%   |
| Intel Raptor Lake SATA AHCI Controller                                        | 1        | 1.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1        | 1.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 1        | 1.82%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                    | 1        | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1        | 1.82%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                        | 1        | 1.82%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                  | 1        | 1.82%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                      | 1        | 1.82%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                  | 1        | 1.82%   |
| Intel 82801EB (ICH5) SATA Controller                                          | 1        | 1.82%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                 | 1        | 1.82%   |
| Intel 4 Series Chipset PT IDER Controller                                     | 1        | 1.82%   |
| ASMedia ASM1061 Serial ATA Controller                                         | 1        | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1        | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 1        | 1.82%   |
| AMD 500 Series Chipset SATA Controller                                        | 1        | 1.82%   |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 1.82%   |
| ADATA XPG GAMMIX S50, S50 Lite NVMe SSD                                       | 1        | 1.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 19       | 50%     |
| SATA | 13       | 34.21%  |
| NVMe | 4        | 10.53%  |
| RAID | 1        | 2.63%   |
| SAS  | 1        | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 21       | 67.74%  |
| AMD          | 9        | 29.03%  |
| CentaurHauls | 1        | 3.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2        | 6.45%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2        | 6.45%   |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1        | 3.23%   |
| Intel Pentium M processor 1.73GHz           | 1        | 3.23%   |
| Intel Pentium II (Deschutes)                | 1        | 3.23%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 3.23%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 3.23%   |
| Intel Pentium 4 CPU 2.40GHz                 | 1        | 3.23%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 3.23%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 3.23%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 3.23%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 3.23%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 3.23%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 3.23%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 3.23%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 1        | 3.23%   |
| Intel Atom CPU N280 @ 1.66GHz               | 1        | 3.23%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 3.23%   |
| Intel 13th Gen Core i9-13900K               | 1        | 3.23%   |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz   | 1        | 3.23%   |
| AMD Sempron Processor 3000+                 | 1        | 3.23%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 3.23%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 1        | 3.23%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 1        | 3.23%   |
| AMD Phenom II X4 965 Processor              | 1        | 3.23%   |
| AMD Phenom 9650 Quad-Core Processor         | 1        | 3.23%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+  | 1        | 3.23%   |
| AMD Athlon 64 Processor 3200+               | 1        | 3.23%   |
| AMD A6-5400K APU with Radeon HD Graphics    | 1        | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Other                   | 3        | 9.68%   |
| Intel Pentium Dual-Core | 3        | 9.68%   |
| Intel Core 2 Duo        | 3        | 9.68%   |
| Intel Atom              | 3        | 9.68%   |
| AMD Ryzen 7             | 2        | 6.45%   |
| Intel Xeon              | 1        | 3.23%   |
| Intel Pentium M         | 1        | 3.23%   |
| Intel Pentium Dual      | 1        | 3.23%   |
| Intel Pentium 4         | 1        | 3.23%   |
| Intel Pentium           | 1        | 3.23%   |
| Intel Core i9           | 1        | 3.23%   |
| Intel Core i7           | 1        | 3.23%   |
| Intel Core i5           | 1        | 3.23%   |
| Intel Core 2 Quad       | 1        | 3.23%   |
| CentaurHauls VIA Eden   | 1        | 3.23%   |
| AMD Sempron             | 1        | 3.23%   |
| AMD Ryzen 5             | 1        | 3.23%   |
| AMD Phenom II X4        | 1        | 3.23%   |
| AMD Phenom              | 1        | 3.23%   |
| AMD Athlon 64 X2        | 1        | 3.23%   |
| AMD Athlon 64           | 1        | 3.23%   |
| AMD A6                  | 1        | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 32.26%  |
| 4      | 7        | 22.58%  |
| 1      | 7        | 22.58%  |
| 8      | 3        | 9.68%   |
| 6      | 3        | 9.68%   |
| 24     | 1        | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 64.52%  |
| 2      | 11       | 35.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 27       | 87.1%   |
| 32-bit         | 4        | 12.9%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 6        | 19.35%  |
| Unknown    | 6        | 19.35%  |
| 0xa0671    | 2        | 6.45%   |
| 0x206a7    | 2        | 6.45%   |
| 0x10676    | 2        | 6.45%   |
| 0xf29      | 1        | 3.23%   |
| 0x906ed    | 1        | 3.23%   |
| 0x6fd      | 1        | 3.23%   |
| 0x6d8      | 1        | 3.23%   |
| 0x652      | 1        | 3.23%   |
| 0x30678    | 1        | 3.23%   |
| 0x106ca    | 1        | 3.23%   |
| 0x106c2    | 1        | 3.23%   |
| 0x08701021 | 1        | 3.23%   |
| 0x08001138 | 1        | 3.23%   |
| 0x06001116 | 1        | 3.23%   |
| 0x010000c8 | 1        | 3.23%   |
| 0x01000095 | 1        | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 8        | 25.81%  |
| Unknown          | 4        | 12.9%   |
| K8 Hammer        | 3        | 9.68%   |
| SandyBridge      | 2        | 6.45%   |
| K10              | 2        | 6.45%   |
| Bonnell          | 2        | 6.45%   |
| Zen+             | 1        | 3.23%   |
| Zen 2            | 1        | 3.23%   |
| Zen              | 1        | 3.23%   |
| Silvermont       | 1        | 3.23%   |
| Piledriver       | 1        | 3.23%   |
| P6               | 1        | 3.23%   |
| NetBurst         | 1        | 3.23%   |
| KabyLake         | 1        | 3.23%   |
| Core             | 1        | 3.23%   |
| Alderlake Hybrid | 1        | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 13       | 39.39%  |
| Intel            | 12       | 36.36%  |
| AMD              | 7        | 21.21%  |
| VIA Technologies | 1        | 3.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 2        | 5.56%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 2        | 5.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 2        | 5.56%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 2        | 5.56%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                              | 1        | 2.78%   |
| Nvidia TU116 [GeForce GTX 1660]                                           | 1        | 2.78%   |
| Nvidia GT218 [GeForce G210]                                               | 1        | 2.78%   |
| Nvidia GT216 [GeForce GT 220]                                             | 1        | 2.78%   |
| Nvidia GM204 [GeForce GTX 980]                                            | 1        | 2.78%   |
| Nvidia GF119 [GeForce GT 520]                                             | 1        | 2.78%   |
| Nvidia GF108 [GeForce GT 630]                                             | 1        | 2.78%   |
| Nvidia GF108 [GeForce GT 430]                                             | 1        | 2.78%   |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                        | 1        | 2.78%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                       | 1        | 2.78%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1        | 2.78%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                 | 1        | 2.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1        | 2.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 2.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1        | 2.78%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1        | 2.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 1        | 2.78%   |
| Intel 82945G/GZ Integrated Graphics Controller                            | 1        | 2.78%   |
| Intel 82865G Integrated Graphics Controller                               | 1        | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 2.78%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 2.78%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                     | 1        | 2.78%   |
| AMD RV515 [Radeon X1300/X1550]                                            | 1        | 2.78%   |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 2.78%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                   | 1        | 2.78%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                        | 1        | 2.78%   |
| AMD RS780 [Radeon HD 3200]                                                | 1        | 2.78%   |
| AMD Rage 3 [3D Rage PRO AGP 2X]                                           | 1        | 2.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 11       | 35.48%  |
| 1 x Intel      | 9        | 29.03%  |
| 1 x AMD        | 4        | 12.9%   |
| 2 x AMD        | 3        | 9.68%   |
| Intel + Nvidia | 2        | 6.45%   |
| 2 x Intel      | 1        | 3.23%   |
| 1 x VIA        | 1        | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 20       | 64.52%  |
| Proprietary | 6        | 19.35%  |
| Unknown     | 5        | 16.13%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 48.39%  |
| 0.01-0.5   | 7        | 22.58%  |
| 1.01-2.0   | 3        | 9.68%   |
| 5.01-6.0   | 2        | 6.45%   |
| 0.51-1.0   | 2        | 6.45%   |
| 3.01-4.0   | 1        | 3.23%   |
| 16.01-24.0 | 1        | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Acer                 | 4        | 19.05%  |
| Samsung Electronics  | 3        | 14.29%  |
| Goldstar             | 3        | 14.29%  |
| Ancor Communications | 2        | 9.52%   |
| Vizio                | 1        | 4.76%   |
| ViewSonic            | 1        | 4.76%   |
| Unknown (XXX)        | 1        | 4.76%   |
| LG Electronics       | 1        | 4.76%   |
| Hewlett-Packard      | 1        | 4.76%   |
| Dell                 | 1        | 4.76%   |
| BOE                  | 1        | 4.76%   |
| AOC                  | 1        | 4.76%   |
| Unknown              | 1        | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                   | 1        | 4.76%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 1        | 4.76%   |
| Unknown (XXX) LCDTV XXX0180 1440x900 884x663mm 43.5-inch              | 1        | 4.76%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 474x296mm 22.0-inch  | 1        | 4.76%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch  | 1        | 4.76%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 477x268mm 21.5-inch   | 1        | 4.76%   |
| LG Electronics LCD Monitor LG Ultra HD 4480x3600                      | 1        | 4.76%   |
| Hewlett-Packard LP2475w HWP26F7 1920x1200 546x352mm 25.6-inch         | 1        | 4.76%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1        | 4.76%   |
| Goldstar TV GSM9CF5 1360x768 700x392mm 31.6-inch                      | 1        | 4.76%   |
| Goldstar M198WA GSM4B36 1440x900 408x255mm 18.9-inch                  | 1        | 4.76%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                      | 1        | 4.76%   |
| BOE LCD Monitor BOE0623 1366x768 256x144mm 11.6-inch                  | 1        | 4.76%   |
| AOC 2280W AOC2280 1920x1080 477x268mm 21.5-inch                       | 1        | 4.76%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 1        | 4.76%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 1        | 4.76%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                     | 1        | 4.76%   |
| Acer V243H ACR00A3 1920x1080 531x298mm 24.0-inch                      | 1        | 4.76%   |
| Acer V223HQV ACR025D 1920x1080 510x287mm 23.0-inch                    | 1        | 4.76%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                     | 1        | 4.76%   |
| Unknown                                                               | 1        | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 47.62%  |
| 1366x768 (WXGA)    | 3        | 14.29%  |
| 4480x3600          | 1        | 4.76%   |
| 2560x1080          | 1        | 4.76%   |
| 1920x1200 (WUXGA)  | 1        | 4.76%   |
| 1680x1050 (WSXGA+) | 1        | 4.76%   |
| 1600x1200          | 1        | 4.76%   |
| 1440x900 (WXGA+)   | 1        | 4.76%   |
| 1360x768           | 1        | 4.76%   |
| Unknown            | 1        | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 5        | 25%     |
| 27      | 3        | 15%     |
| 43      | 1        | 5%      |
| 38      | 1        | 5%      |
| 34      | 1        | 5%      |
| 31      | 1        | 5%      |
| 25      | 1        | 5%      |
| 24      | 1        | 5%      |
| 23      | 1        | 5%      |
| 22      | 1        | 5%      |
| 19      | 1        | 5%      |
| 18      | 1        | 5%      |
| 11      | 1        | 5%      |
| Unknown | 1        | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 8        | 40%     |
| 501-600     | 6        | 30%     |
| 801-900     | 2        | 10%     |
| 701-800     | 1        | 5%      |
| 601-700     | 1        | 5%      |
| 201-300     | 1        | 5%      |
| Unknown     | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 65%     |
| 16/10   | 3        | 15%     |
| 4/3     | 2        | 10%     |
| 21/9    | 1        | 5%      |
| Unknown | 1        | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 35%     |
| 301-350        | 3        | 15%     |
| 351-500        | 2        | 10%     |
| 151-200        | 2        | 10%     |
| 501-1000       | 2        | 10%     |
| 51-60          | 1        | 5%      |
| 251-300        | 1        | 5%      |
| 141-150        | 1        | 5%      |
| Unknown        | 1        | 5%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 55%     |
| 101-120 | 4        | 20%     |
| 1-50    | 3        | 15%     |
| 121-160 | 1        | 5%      |
| Unknown | 1        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 77.42%  |
| 0     | 6        | 19.35%  |
| 2     | 1        | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 18       | 45%     |
| Intel                           | 10       | 25%     |
| Nvidia                          | 3        | 7.5%    |
| Ralink Technology               | 2        | 5%      |
| Samsung Electronics             | 1        | 2.5%    |
| Ralink                          | 1        | 2.5%    |
| Qualcomm Atheros Communications | 1        | 2.5%    |
| Qualcomm Atheros                | 1        | 2.5%    |
| Marvell Technology Group        | 1        | 2.5%    |
| LSI                             | 1        | 2.5%    |
| Broadcom                        | 1        | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 7        | 15.56%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3        | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3        | 6.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 4.44%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 4.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2        | 4.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 4.44%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 4.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 4.44%   |
| Intel I211 Gigabit Network Connection                                         | 2        | 4.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 2.22%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 2.22%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 2.22%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 2.22%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 2.22%   |
| Nvidia CK8S Ethernet Controller                                               | 1        | 2.22%   |
| Nvidia CK804 Ethernet Controller                                              | 1        | 2.22%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 2.22%   |
| LSI 56k WinModem                                                              | 1        | 2.22%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                             | 1        | 2.22%   |
| Intel Ethernet Controller I225-V                                              | 1        | 2.22%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 2.22%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 2.22%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE Ethernet Controller                       | 1        | 2.22%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 1        | 2.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 40%     |
| Realtek Semiconductor           | 2        | 20%     |
| Ralink Technology               | 2        | 20%     |
| Ralink                          | 1        | 10%     |
| Qualcomm Atheros Communications | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 20%     |
| Ralink RT5370 Wireless Adapter                                                | 2        | 20%     |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2        | 20%     |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                     | 1        | 10%     |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 10%     |
| Intel Raptor Lake-S PCH CNVi WiFi                                             | 1        | 10%     |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 18       | 54.55%  |
| Intel                    | 8        | 24.24%  |
| Nvidia                   | 3        | 9.09%   |
| Samsung Electronics      | 1        | 3.03%   |
| Qualcomm Atheros         | 1        | 3.03%   |
| Marvell Technology Group | 1        | 3.03%   |
| Broadcom                 | 1        | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 7        | 20.59%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 3        | 8.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 8.82%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 5.88%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 5.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 5.88%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 5.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 2.94%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 2.94%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 2.94%   |
| Nvidia CK8S Ethernet Controller                                        | 1        | 2.94%   |
| Nvidia CK804 Ethernet Controller                                       | 1        | 2.94%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 2.94%   |
| Intel Ethernet Controller I225-V                                       | 1        | 2.94%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1        | 2.94%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1        | 2.94%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE Ethernet Controller                | 1        | 2.94%   |
| Intel 82540EM Gigabit Ethernet Controller                              | 1        | 2.94%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1        | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 76.32%  |
| WiFi     | 8        | 21.05%  |
| Modem    | 1        | 2.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 83.87%  |
| WiFi     | 5        | 16.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 70.97%  |
| 2     | 8        | 25.81%  |
| 0     | 1        | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 74.19%  |
| Yes  | 8        | 25.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 57.14%  |
| Cambridge Silicon Radio | 2        | 28.57%  |
| Broadcom                | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX201 Bluetooth                               | 2        | 28.57%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 28.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 14.29%  |
| Intel AX211 Bluetooth                               | 1        | 14.29%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 18       | 40%     |
| Nvidia              | 13       | 28.89%  |
| AMD                 | 5        | 11.11%  |
| Creative Labs       | 3        | 6.67%   |
| VIA Technologies    | 2        | 4.44%   |
| C-Media Electronics | 2        | 4.44%   |
| ULi Electronics     | 1        | 2.22%   |
| Ensoniq             | 1        | 2.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 6        | 12.5%   |
| Nvidia TU116 High Definition Audio Controller                               | 3        | 6.25%   |
| Nvidia GP108 High Definition Audio Controller                               | 2        | 4.17%   |
| Nvidia GF108 High Definition Audio Controller                               | 2        | 4.17%   |
| Intel Tiger Lake-H HD Audio Controller                                      | 2        | 4.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 2        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 2        | 4.17%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                      | 2        | 4.17%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller              | 1        | 2.08%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 2.08%   |
| VIA Technologies High Definition Audio Controller                           | 1        | 2.08%   |
| ULi Electronics HD Audio Controller                                         | 1        | 2.08%   |
| Nvidia High Definition Audio Controller                                     | 1        | 2.08%   |
| Nvidia GT216 HDMI Audio Controller                                          | 1        | 2.08%   |
| Nvidia GM204 High Definition Audio Controller                               | 1        | 2.08%   |
| Nvidia GF119 HDMI Audio Controller                                          | 1        | 2.08%   |
| Nvidia GA102 High Definition Audio Controller                               | 1        | 2.08%   |
| Nvidia CK804 AC'97 Audio Controller                                         | 1        | 2.08%   |
| Intel Raptor Lake High Definition Audio Controller                          | 1        | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                  | 1        | 2.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 1        | 2.08%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 1        | 2.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller            | 1        | 2.08%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                        | 1        | 2.08%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                                | 1        | 2.08%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                           | 1        | 2.08%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]   | 1        | 2.08%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                  | 1        | 2.08%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                               | 1        | 2.08%   |
| C-Media Electronics CM6501                                                  | 1        | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                                    | 1        | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 1        | 2.08%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                      | 1        | 2.08%   |
| AMD FCH Azalia Controller                                                   | 1        | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 1        | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 14       | 42.42%  |
| SK hynix            | 3        | 9.09%   |
| Samsung Electronics | 3        | 9.09%   |
| Kingston            | 3        | 9.09%   |
| Corsair             | 3        | 9.09%   |
| Unknown (0x0DA2)    | 1        | 3.03%   |
| Smart               | 1        | 3.03%   |
| Ramaxel Technology  | 1        | 3.03%   |
| Patriot             | 1        | 3.03%   |
| Kllisre             | 1        | 3.03%   |
| G.Skill             | 1        | 3.03%   |
| A-DATA Technology   | 1        | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                        | 2        | 5.56%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s   | 2        | 5.56%   |
| Unknown RAM Module 512MB DIMM SDRAM 333MT/s              | 1        | 2.78%   |
| Unknown RAM Module 512MB DIMM SDRAM                      | 1        | 2.78%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1        | 2.78%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                | 1        | 2.78%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 2.78%   |
| Unknown RAM Module 4GB DIMM 800MT/s                      | 1        | 2.78%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1        | 2.78%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                 | 1        | 2.78%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 2.78%   |
| Unknown RAM Module 256MB DIMM SDRAM 333MT/s              | 1        | 2.78%   |
| Unknown RAM Module 1GB DIMM SDRAM                        | 1        | 2.78%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                 | 1        | 2.78%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                  | 1        | 2.78%   |
| Unknown RAM Module 1GB DIMM 667MT/s                      | 1        | 2.78%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s              | 1        | 2.78%   |
| Unknown (0x0DA2) RAM SB-DR5U-32G 32GB DIMM DDR5 4800MT/s | 1        | 2.78%   |
| Smart RAM SG564568FG8N6KFSQR 2GB DIMM DDR2 800MT/s       | 1        | 2.78%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 2.78%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s   | 1        | 2.78%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 2.78%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 1333MT/s          | 1        | 2.78%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s     | 1        | 2.78%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s      | 1        | 2.78%   |
| Ramaxel RAM RMUA5180MH78HBF-2666 16GB DIMM DDR4 2400MT/s | 1        | 2.78%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s       | 1        | 2.78%   |
| Kllisre RAM DDR2 2G 2GB DIMM DDR2 800MT/s                | 1        | 2.78%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 1        | 2.78%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.78%   |
| Kingston RAM 99U5402-060.A 2GB DIMM DDR3 1333MT/s        | 1        | 2.78%   |
| G.Skill RAM F4-3200C14-8GTZSW 8192MB DIMM DDR4 3200MT/s  | 1        | 2.78%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s    | 1        | 2.78%   |
| A-DATA RAM DDR4 2666 2OZ 8GB DIMM DDR4 2667MT/s          | 1        | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 7        | 24.14%  |
| SDRAM   | 6        | 20.69%  |
| DDR4    | 6        | 20.69%  |
| Unknown | 4        | 13.79%  |
| DDR2    | 3        | 10.34%  |
| DDR     | 2        | 6.9%    |
| DDR5    | 1        | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 27       | 93.1%   |
| SODIMM | 2        | 6.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 9        | 27.27%  |
| 16384 | 5        | 15.15%  |
| 4096  | 5        | 15.15%  |
| 1024  | 5        | 15.15%  |
| 512   | 5        | 15.15%  |
| 8192  | 2        | 6.06%   |
| 32768 | 1        | 3.03%   |
| 256   | 1        | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 4        | 12.9%   |
| 800     | 4        | 12.9%   |
| Unknown | 4        | 12.9%   |
| 1333    | 3        | 9.68%   |
| 3534    | 2        | 6.45%   |
| 3200    | 2        | 6.45%   |
| 2400    | 2        | 6.45%   |
| 667     | 2        | 6.45%   |
| 400     | 2        | 6.45%   |
| 333     | 2        | 6.45%   |
| 4800    | 1        | 3.23%   |
| 3600    | 1        | 3.23%   |
| 2667    | 1        | 3.23%   |
| 2048    | 1        | 3.23%   |

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


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro | 1        | 33.33%  |
| Generalplus 808 Camera               | 1        | 33.33%  |
| Alcor Micro USB 2.0 PC cam           | 1        | 33.33%  |

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
| 0     | 23       | 74.19%  |
| 2     | 3        | 9.68%   |
| 1     | 3        | 9.68%   |
| 4     | 1        | 3.23%   |
| 3     | 1        | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 46.15%  |
| Sound                    | 2        | 15.38%  |
| Communication controller | 2        | 15.38%  |
| Net/ethernet             | 1        | 7.69%   |
| Modem                    | 1        | 7.69%   |
| Camera                   | 1        | 7.69%   |

