antiX - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for antiX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/antiX/Desktop/README.md) and [notebooks](/Dist/antiX/Notebook/README.md).

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

Total: 67

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| KOHJINSHA     | SC series                   | Notebook    | [90a25503ee](https://linux-hardware.org/?probe=90a25503ee) | Aug 01, 2022 |
| KOHJINSHA     | SC series                   | Notebook    | [3986e59a55](https://linux-hardware.org/?probe=3986e59a55) | Aug 01, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [353168b909](https://linux-hardware.org/?probe=353168b909) | Jul 18, 2022 |
| IBM           | 260921H                     | Notebook    | [bab4f3f57d](https://linux-hardware.org/?probe=bab4f3f57d) | Jul 17, 2022 |
| IBM           | 260921H                     | Notebook    | [a7483bac34](https://linux-hardware.org/?probe=a7483bac34) | Jul 17, 2022 |
| Dell          | 0F428D A00                  | Desktop     | [fb8a6009f7](https://linux-hardware.org/?probe=fb8a6009f7) | Jul 16, 2022 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [f6a90dcc74](https://linux-hardware.org/?probe=f6a90dcc74) | Jul 16, 2022 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | Desktop     | [af73739875](https://linux-hardware.org/?probe=af73739875) | Jul 14, 2022 |
| IBM           | 260921H                     | Notebook    | [5f9b0998d3](https://linux-hardware.org/?probe=5f9b0998d3) | Jul 11, 2022 |
| IBM           | 260921H                     | Notebook    | [f0430651fd](https://linux-hardware.org/?probe=f0430651fd) | Jul 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [910a4f6587](https://linux-hardware.org/?probe=910a4f6587) | Jul 09, 2022 |
| Compaq        | Tablet PC TC1000            | Notebook    | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | Notebook    | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | Notebook    | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| Unknown       | K8NF3-VSTA                  | Desktop     | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | Desktop     | [8654086b85](https://linux-hardware.org/?probe=8654086b85) | Jun 20, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [e904df65f2](https://linux-hardware.org/?probe=e904df65f2) | Jun 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [cb13f37895](https://linux-hardware.org/?probe=cb13f37895) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| AZW           | GK mini                     | Mini pc     | [9d00f58b53](https://linux-hardware.org/?probe=9d00f58b53) | May 04, 2022 |
| AZW           | GK mini                     | Mini pc     | [d474b9b330](https://linux-hardware.org/?probe=d474b9b330) | May 04, 2022 |
| Packard Be... | EasyNote_MX37-U-057NL       | Notebook    | [41760b3852](https://linux-hardware.org/?probe=41760b3852) | Apr 27, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba       | Satellite 1905              | Notebook    | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Unknown       | NF-CK804                    | Desktop     | [dc6287d017](https://linux-hardware.org/?probe=dc6287d017) | Jan 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | Notebook    | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek       | X71SL                       | Notebook    | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek       | A3L                         | Notebook    | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek       | A3L                         | Notebook    | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek       | X51RL                       | Notebook    | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer          | AOA150                      | Notebook    | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell          | Latitude E6400              | Notebook    | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI           | GE62 7RE                    | Notebook    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI           | GE62 7RE                    | Notebook    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| HP            | EliteBook 8770w             | Notebook    | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu       | FMVS54EB                    | Notebook    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Latitude 5480               | Notebook    | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [4a3e3cd4ee](https://linux-hardware.org/?probe=4a3e3cd4ee) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [e751bd8090](https://linux-hardware.org/?probe=e751bd8090) | Jan 14, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [cac53c0d21](https://linux-hardware.org/?probe=cac53c0d21) | Jan 14, 2021 |
| HP            | Mini 110-3700               | Notebook    | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| HP            | 8430 1000                   | All in one  | [db9e0da88a](https://linux-hardware.org/?probe=db9e0da88a) | Dec 06, 2020 |
| IBM           | ThinkPad T41 2374K50        | Notebook    | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM           | ThinkPad T41 2374K50        | Notebook    | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM           | ThinkPad T43 2668WEJ        | Notebook    | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP            | Pavilion dv2700             | Notebook    | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP            | 3641h                       | Desktop     | [f918637d53](https://linux-hardware.org/?probe=f918637d53) | Jul 29, 2020 |
| HP            | Mini 5101                   | Notebook    | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | Notebook    | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek       | 900A                        | Notebook    | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek       | 900HA                       | Notebook    | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion        | WIM2170                     | Notebook    | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion        | WIM2170                     | Notebook    | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |
| Unknown       | Unknown                     | Desktop     | [7653370d96](https://linux-hardware.org/?probe=7653370d96) | Dec 16, 2019 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [8ba4b22f71](https://linux-hardware.org/?probe=8ba4b22f71) | Oct 22, 2019 |
| Lenovo        | ThinkCentre M91p 4480B9U    | Desktop     | [e68917ee9f](https://linux-hardware.org/?probe=e68917ee9f) | Nov 04, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| antiX 21       | 25        | 48.08%  |
| antiX 19.2     | 8         | 15.38%  |
| antiX 19.3     | 4         | 7.69%   |
| antiX 17.4.1   | 4         | 7.69%   |
| antiX 21-runit | 3         | 5.77%   |
| antiX 19.4     | 2         | 3.85%   |
| antiX 19.1     | 2         | 3.85%   |
| antiX 17.2.1   | 1         | 1.92%   |
| antiX 17.1     | 1         | 1.92%   |
| antiX 17       | 1         | 1.92%   |
| antiX 15       | 1         | 1.92%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 52        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 12        | 23.08%  |
| 5.10.57-antix.1-amd64-smp    | 7         | 13.46%  |
| 4.9.0-279-antix.1-amd64-smp  | 7         | 13.46%  |
| 4.9.160-antix.2-486-smp      | 4         | 7.69%   |
| 4.9.235-antix.1-amd64-smp    | 3         | 5.77%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 5.77%   |
| 4.9.212-antix.1-486-smp      | 3         | 5.77%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 3.85%   |
| 4.9.200-antix.1-486-smp      | 2         | 3.85%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.92%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.92%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 1.92%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.92%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.92%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.92%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.92%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.92%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 20        | 38.46%  |
| 5.10.57  | 7         | 13.46%  |
| 4.9.212  | 6         | 11.54%  |
| 4.9.160  | 5         | 9.62%   |
| 4.9.235  | 3         | 5.77%   |
| 5.10.88  | 2         | 3.85%   |
| 4.9.200  | 2         | 3.85%   |
| 5.14.0   | 1         | 1.92%   |
| 5.10.27  | 1         | 1.92%   |
| 4.9.87   | 1         | 1.92%   |
| 4.19.202 | 1         | 1.92%   |
| 4.19.100 | 1         | 1.92%   |
| 4.19.0   | 1         | 1.92%   |
| 4.10.5   | 1         | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 37        | 71.15%  |
| 5.10    | 10        | 19.23%  |
| 4.19    | 3         | 5.77%   |
| 5.14    | 1         | 1.92%   |
| 4.10    | 1         | 1.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 27        | 51.92%  |
| i686   | 24        | 46.15%  |
| i586   | 1         | 1.92%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 29        | 55.77%  |
| icewm        | 16        | 30.77%  |
| XFCE         | 4         | 7.69%   |
| jwm          | 1         | 1.92%   |
| herbstluftwm | 1         | 1.92%   |
| GNOME        | 1         | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 51        | 98.08%  |
| Tty  | 1         | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 42.31%  |
| SLiM    | 21        | 40.38%  |
| LightDM | 5         | 9.62%   |
| SLIMSKI | 3         | 5.77%   |
| SDDM    | 1         | 1.92%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 24        | 46.15%  |
| ru_RU   | 3         | 5.77%   |
| ja_JP   | 3         | 5.77%   |
| de_DE   | 3         | 5.77%   |
| Unknown | 3         | 5.77%   |
| sk_SK   | 2         | 3.85%   |
| pt_BR   | 2         | 3.85%   |
| pl_PL   | 2         | 3.85%   |
| en_AU   | 2         | 3.85%   |
| zh_HK   | 1         | 1.92%   |
| uk_UA   | 1         | 1.92%   |
| nl_NL   | 1         | 1.92%   |
| it_IT   | 1         | 1.92%   |
| es_VE   | 1         | 1.92%   |
| es_MX   | 1         | 1.92%   |
| es_AR   | 1         | 1.92%   |
| en_GB   | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 42        | 80.77%  |
| EFI  | 10        | 19.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 44        | 84.62%  |
| Overlay  | 7         | 13.46%  |
| Reiserfs | 1         | 1.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 40        | 76.92%  |
| GPT     | 10        | 19.23%  |
| Unknown | 2         | 3.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 80.77%  |
| Yes       | 10        | 19.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 59.62%  |
| Yes       | 21        | 40.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 9         | 17.31%  |
| Hewlett-Packard     | 7         | 13.46%  |
| Lenovo              | 5         | 9.62%   |
| IBM                 | 5         | 9.62%   |
| MSI                 | 3         | 5.77%   |
| Dell                | 3         | 5.77%   |
| Unknown             | 3         | 5.77%   |
| KOHJINSHA           | 2         | 3.85%   |
| Gigabyte Technology | 2         | 3.85%   |
| Acer                | 2         | 3.85%   |
| Toshiba             | 1         | 1.92%   |
| Samsung Electronics | 1         | 1.92%   |
| Radiant Systems     | 1         | 1.92%   |
| Packard Bell        | 1         | 1.92%   |
| Medion              | 1         | 1.92%   |
| Fujitsu             | 1         | 1.92%   |
| Compaq              | 1         | 1.92%   |
| Biostar             | 1         | 1.92%   |
| AZW                 | 1         | 1.92%   |
| Apple               | 1         | 1.92%   |
| AMI                 | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 4         | 7.69%   |
| MSI US Desktop                     | 2         | 3.85%   |
| IBM 260921H                        | 2         | 3.85%   |
| Toshiba Satellite 1905             | 1         | 1.92%   |
| Samsung SQ1S                       | 1         | 1.92%   |
| Radiant Systems P845               | 1         | 1.92%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.92%   |
| MSI GE62 7RE                       | 1         | 1.92%   |
| Medion WIM2170                     | 1         | 1.92%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.92%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.92%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 1.92%   |
| Lenovo G550 2958                   | 1         | 1.92%   |
| KOHJINSHA SX series                | 1         | 1.92%   |
| KOHJINSHA SC series                | 1         | 1.92%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.92%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.92%   |
| IBM ThinkPad T40 237342G           | 1         | 1.92%   |
| HP t5740                           | 1         | 1.92%   |
| HP Pavilion dv2700                 | 1         | 1.92%   |
| HP Mini 5101                       | 1         | 1.92%   |
| HP Mini 110-3700                   | 1         | 1.92%   |
| HP EliteBook 8770w                 | 1         | 1.92%   |
| HP EliteBook 2570p                 | 1         | 1.92%   |
| HP All-in-One 24-f0xx              | 1         | 1.92%   |
| Gigabyte F2A85XM-D3H               | 1         | 1.92%   |
| Gigabyte 945GCMX-S2                | 1         | 1.92%   |
| Fujitsu FMVS54EB                   | 1         | 1.92%   |
| Dell OptiPlex 960                  | 1         | 1.92%   |
| Dell Latitude E6400                | 1         | 1.92%   |
| Dell Latitude 5480                 | 1         | 1.92%   |
| Compaq Tablet PC TC1000            | 1         | 1.92%   |
| Biostar G31-M7 TE                  | 1         | 1.92%   |
| AZW GK mini                        | 1         | 1.92%   |
| ASUS X71SL                         | 1         | 1.92%   |
| ASUS X51RL                         | 1         | 1.92%   |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 1.92%   |
| ASUS VivoBook E14 E402YA_L402YA    | 1         | 1.92%   |
| ASUS P5KPL/1600                    | 1         | 1.92%   |
| ASUS A8R-MVP                       | 1         | 1.92%   |
| ASUS A3L                           | 1         | 1.92%   |
| ASUS 900HA                         | 1         | 1.92%   |
| ASUS 900A                          | 1         | 1.92%   |
| Apple MacBook7,1                   | 1         | 1.92%   |
| AMI Aptio CRB                      | 1         | 1.92%   |
| Acer Aspire 5920G                  | 1         | 1.92%   |
| Acer AOA150                        | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 4         | 7.69%   |
| IBM ThinkPad          | 3         | 5.77%   |
| MSI US                | 2         | 3.85%   |
| Lenovo ThinkPad       | 2         | 3.85%   |
| IBM 260921H           | 2         | 3.85%   |
| HP Mini               | 2         | 3.85%   |
| HP EliteBook          | 2         | 3.85%   |
| Dell Latitude         | 2         | 3.85%   |
| ASUS VivoBook         | 2         | 3.85%   |
| Toshiba Satellite     | 1         | 1.92%   |
| Samsung SQ1S          | 1         | 1.92%   |
| Radiant Systems P845  | 1         | 1.92%   |
| Packard Bell EasyNote | 1         | 1.92%   |
| MSI GE62              | 1         | 1.92%   |
| Medion WIM2170        | 1         | 1.92%   |
| Lenovo ThinkCentre    | 1         | 1.92%   |
| Lenovo G550           | 1         | 1.92%   |
| KOHJINSHA SX          | 1         | 1.92%   |
| KOHJINSHA SC          | 1         | 1.92%   |
| HP t5740              | 1         | 1.92%   |
| HP Pavilion           | 1         | 1.92%   |
| HP All-in-One         | 1         | 1.92%   |
| Gigabyte F2A85XM-D3H  | 1         | 1.92%   |
| Gigabyte 945GCMX-S2   | 1         | 1.92%   |
| Fujitsu FMVS54EB      | 1         | 1.92%   |
| Dell OptiPlex         | 1         | 1.92%   |
| Compaq Tablet         | 1         | 1.92%   |
| Biostar G31-M7        | 1         | 1.92%   |
| AZW GK                | 1         | 1.92%   |
| ASUS X71SL            | 1         | 1.92%   |
| ASUS X51RL            | 1         | 1.92%   |
| ASUS P5KPL            | 1         | 1.92%   |
| ASUS A8R-MVP          | 1         | 1.92%   |
| ASUS A3L              | 1         | 1.92%   |
| ASUS 900HA            | 1         | 1.92%   |
| ASUS 900A             | 1         | 1.92%   |
| Apple MacBook7        | 1         | 1.92%   |
| AMI Aptio             | 1         | 1.92%   |
| Acer Aspire           | 1         | 1.92%   |
| Acer AOA150           | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 9         | 17.31%  |
| 2009    | 8         | 15.38%  |
| 2007    | 7         | 13.46%  |
| 2021    | 3         | 5.77%   |
| 2012    | 3         | 5.77%   |
| 2005    | 3         | 5.77%   |
| 2003    | 3         | 5.77%   |
| 2018    | 2         | 3.85%   |
| 2013    | 2         | 3.85%   |
| 2011    | 2         | 3.85%   |
| 2010    | 2         | 3.85%   |
| 1999    | 2         | 3.85%   |
| 2020    | 1         | 1.92%   |
| 2019    | 1         | 1.92%   |
| 2017    | 1         | 1.92%   |
| 2016    | 1         | 1.92%   |
| 2004    | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 35        | 67.31%  |
| Desktop    | 13        | 25%     |
| Mini pc    | 3         | 5.77%   |
| All in one | 1         | 1.92%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 52        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 12        | 23.08%  |
| 0.51-1.0   | 9         | 17.31%  |
| 2.01-3.0   | 7         | 13.46%  |
| 1.01-2.0   | 7         | 13.46%  |
| 4.01-8.0   | 4         | 7.69%   |
| 32.01-64.0 | 4         | 7.69%   |
| 0.01-0.5   | 4         | 7.69%   |
| 8.01-16.0  | 3         | 5.77%   |
| 16.01-24.0 | 2         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 22        | 42.31%  |
| 0.51-1.0 | 17        | 32.69%  |
| 1.01-2.0 | 7         | 13.46%  |
| 2.01-3.0 | 5         | 9.62%   |
| 4.01-8.0 | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 71.15%  |
| 2      | 8         | 15.38%  |
| 3      | 4         | 7.69%   |
| 0      | 2         | 3.85%   |
| 4      | 1         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 57.69%  |
| Yes       | 22        | 42.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 88.46%  |
| No        | 6         | 11.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 78.85%  |
| No        | 11        | 21.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 65.38%  |
| Yes       | 18        | 34.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 21.15%  |
| Hong Kong   | 8         | 15.38%  |
| Russia      | 5         | 9.62%   |
| Germany     | 5         | 9.62%   |
| Japan       | 3         | 5.77%   |
| Slovakia    | 2         | 3.85%   |
| Poland      | 2         | 3.85%   |
| Brazil      | 2         | 3.85%   |
| Australia   | 2         | 3.85%   |
| Ukraine     | 1         | 1.92%   |
| Netherlands | 1         | 1.92%   |
| Mexico      | 1         | 1.92%   |
| Kenya       | 1         | 1.92%   |
| Kazakhstan  | 1         | 1.92%   |
| Italy       | 1         | 1.92%   |
| Hungary     | 1         | 1.92%   |
| Greece      | 1         | 1.92%   |
| France      | 1         | 1.92%   |
| Denmark     | 1         | 1.92%   |
| Chile       | 1         | 1.92%   |
| Argentina   | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 7         | 13.46%  |
| Sydney                    | 2         | 3.85%   |
| Moscow                    | 2         | 3.85%   |
| Bratislava                | 2         | 3.85%   |
| Zagnansk                  | 1         | 1.92%   |
| Yuzhno-Sakhalinsk         | 1         | 1.92%   |
| Yokohama                  | 1         | 1.92%   |
| Violes                    | 1         | 1.92%   |
| Toms River                | 1         | 1.92%   |
| Sheung Shui               | 1         | 1.92%   |
| Schloss Holte-Stukenbrock | 1         | 1.92%   |
| Santiago                  | 1         | 1.92%   |
| Salto                     | 1         | 1.92%   |
| Rotterdam                 | 1         | 1.92%   |
| Reutlingen                | 1         | 1.92%   |
| Portland                  | 1         | 1.92%   |
| Otwock                    | 1         | 1.92%   |
| Nova Londrina             | 1         | 1.92%   |
| Norden                    | 1         | 1.92%   |
| Neyagawa                  | 1         | 1.92%   |
| Nairobi                   | 1         | 1.92%   |
| Mittegrossefehn           | 1         | 1.92%   |
| Mechanicsburg             | 1         | 1.92%   |
| Mason                     | 1         | 1.92%   |
| Kazan’                  | 1         | 1.92%   |
| Karaganda                 | 1         | 1.92%   |
| Kagoshima                 | 1         | 1.92%   |
| Jonesboro                 | 1         | 1.92%   |
| Inveruno                  | 1         | 1.92%   |
| Houston                   | 1         | 1.92%   |
| Heraklion                 | 1         | 1.92%   |
| Greenville                | 1         | 1.92%   |
| Godley                    | 1         | 1.92%   |
| Frankfurt am Main         | 1         | 1.92%   |
| El Cerrito                | 1         | 1.92%   |
| Domodedovo                | 1         | 1.92%   |
| Dnipro                    | 1         | 1.92%   |
| Covington                 | 1         | 1.92%   |
| Copenhagen                | 1         | 1.92%   |
| Celaya                    | 1         | 1.92%   |
| Buenos Aires              | 1         | 1.92%   |
| Budapest                  | 1         | 1.92%   |
| Boulder                   | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 11        | 12     | 17.19%  |
| WDC                 | 10        | 11     | 15.63%  |
| Seagate             | 10        | 10     | 15.63%  |
| Samsung Electronics | 7         | 8      | 10.94%  |
| Toshiba             | 5         | 5      | 7.81%   |
| Unknown             | 3         | 3      | 4.69%   |
| Kingston            | 2         | 2      | 3.13%   |
| BHT                 | 2         | 2      | 3.13%   |
| Zheino              | 1         | 1      | 1.56%   |
| Unknown (CF)        | 1         | 1      | 1.56%   |
| Transcend           | 1         | 1      | 1.56%   |
| SanDisk             | 1         | 1      | 1.56%   |
| RECADATA            | 1         | 1      | 1.56%   |
| OCZ                 | 1         | 1      | 1.56%   |
| Maxtor              | 1         | 1      | 1.56%   |
| Intel               | 1         | 1      | 1.56%   |
| HGST                | 1         | 1      | 1.56%   |
| Hewlett-Packard     | 1         | 1      | 1.56%   |
| Fujitsu             | 1         | 1      | 1.56%   |
| China               | 1         | 1      | 1.56%   |
| ASUS-PHISON         | 1         | 1      | 1.56%   |
| Unknown             | 1         | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB               | 2         | 3.03%   |
| Hitachi HTS723232A7A364 320GB           | 2         | 3.03%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 3.03%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 1.52%   |
| WDC WD8088AADS-00M2B0 809GB             | 1         | 1.52%   |
| WDC WD800JB-00ETA0 80GB                 | 1         | 1.52%   |
| WDC WD800AAJS-75M0A0 80GB               | 1         | 1.52%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.52%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.52%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.52%   |
| WDC WD205BA 21GB                        | 1         | 1.52%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 1.52%   |
| WDC WD1600AAJS-00PSA0 160GB             | 1         | 1.52%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.52%   |
| WDC WD10SPZX-80Z10T2 1TB                | 1         | 1.52%   |
| Unknown SR64G  64GB                     | 1         | 1.52%   |
| Unknown SD/MMC/MS PRO 64GB              | 1         | 1.52%   |
| Unknown 2GB ATA Flash Disk              | 1         | 1.52%   |
| Unknown (CF) Card 16GB SSD              | 1         | 1.52%   |
| Transcend SSD 2GB                       | 1         | 1.52%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.52%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.52%   |
| Toshiba MQ01ABD050V -63 500GB           | 1         | 1.52%   |
| Toshiba MK2576GSX 250GB                 | 1         | 1.52%   |
| Toshiba DT01ACA100 1TB                  | 1         | 1.52%   |
| Seagate ST9160411AS 160GB               | 1         | 1.52%   |
| Seagate ST9160314AS 160GB               | 1         | 1.52%   |
| Seagate ST9160310AS 160GB               | 1         | 1.52%   |
| Seagate ST9160301AS 160GB               | 1         | 1.52%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 1.52%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1.52%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1.52%   |
| Seagate ST3320620AS 320GB               | 1         | 1.52%   |
| Seagate ST3320413CS 320GB               | 1         | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 1.52%   |
| SanDisk sandisk120 120GB SSD            | 1         | 1.52%   |
| Samsung SSD 850 EVO 120GB               | 1         | 1.52%   |
| Samsung HS06THB 64GB                    | 1         | 1.52%   |
| Samsung HD250HJ 250GB                   | 1         | 1.52%   |
| Samsung HD162GJ 160GB                   | 1         | 1.52%   |
| Samsung HD160JJ/ 160GB                  | 1         | 1.52%   |
| Samsung HD080HJ/ 80GB                   | 1         | 1.52%   |
| RECADATA RD-S350MCN-N0642 64GB SSD      | 1         | 1.52%   |
| OCZ AGILITY3 120GB SSD                  | 1         | 1.52%   |
| Maxtor Z1 SSD 240GB                     | 1         | 1.52%   |
| Kingston SUV500MS120G 120GB SSD         | 1         | 1.52%   |
| Kingston SUV400S37120G 120GB SSD        | 1         | 1.52%   |
| Intel SSDSC2BW180A3H 180GB              | 1         | 1.52%   |
| Hitachi HTS725050A7E630 500GB           | 1         | 1.52%   |
| Hitachi HTS721060G9AT00 64GB            | 1         | 1.52%   |
| Hitachi HTS545025B9A300 250GB           | 1         | 1.52%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 1.52%   |
| Hitachi HTS541612J9SA00 120GB           | 1         | 1.52%   |
| Hitachi HTC426040G8CE00 40GB            | 1         | 1.52%   |
| Hitachi DK23AA-60 6GB                   | 1         | 1.52%   |
| HGST HTS721010A9E630 1TB                | 1         | 1.52%   |
| HP SSD S750 512GB                       | 1         | 1.52%   |
| Fujitsu MHW2120BH 120GB                 | 1         | 1.52%   |
| China M.2 SSD 128GB                     | 1         | 1.52%   |
| BHT WR202I0064G E70245F5 64GB           | 1         | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 11        | 12     | 26.19%  |
| WDC                 | 10        | 11     | 23.81%  |
| Seagate             | 10        | 10     | 23.81%  |
| Samsung Electronics | 4         | 5      | 9.52%   |
| Toshiba             | 3         | 3      | 7.14%   |
| Unknown             | 2         | 2      | 4.76%   |
| HGST                | 1         | 1      | 2.38%   |
| Fujitsu             | 1         | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Kingston            | 2         | 2      | 9.52%   |
| BHT                 | 2         | 2      | 9.52%   |
| Zheino              | 1         | 1      | 4.76%   |
| Unknown (CF)        | 1         | 1      | 4.76%   |
| Transcend           | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| RECADATA            | 1         | 1      | 4.76%   |
| OCZ                 | 1         | 1      | 4.76%   |
| Maxtor              | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| Hewlett-Packard     | 1         | 1      | 4.76%   |
| China               | 1         | 1      | 4.76%   |
| ASUS-PHISON         | 1         | 1      | 4.76%   |
| Unknown             | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 45     | 63.79%  |
| SSD  | 20        | 21     | 34.48%  |
| MMC  | 1         | 1      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 65     | 96.15%  |
| SAS  | 1         | 1      | 1.92%   |
| MMC  | 1         | 1      | 1.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 59     | 87.72%  |
| 0.51-1.0   | 6         | 6      | 10.53%  |
| 1.01-2.0   | 1         | 1      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 30.77%  |
| 1-20       | 15        | 28.85%  |
| 51-100     | 8         | 15.38%  |
| 21-50      | 6         | 11.54%  |
| 501-1000   | 3         | 5.77%   |
| 251-500    | 2         | 3.85%   |
| 1001-2000  | 1         | 1.92%   |
| Unknown    | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 41        | 78.85%  |
| 21-50    | 4         | 7.69%   |
| 101-250  | 3         | 5.77%   |
| 51-100   | 2         | 3.85%   |
| 501-1000 | 1         | 1.92%   |
| Unknown  | 1         | 1.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD8088AADS-00M2B0 809GB     | 1         | 1      | 5%      |
| WDC WD800JB-00ETA0 80GB         | 1         | 1      | 5%      |
| WDC WD800AAJS-75M0A0 80GB       | 1         | 1      | 5%      |
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 5%      |
| WDC WD205BA 21GB                | 1         | 1      | 5%      |
| Seagate ST9160314AS 160GB       | 1         | 1      | 5%      |
| Seagate ST9160310AS 160GB       | 1         | 1      | 5%      |
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 5%      |
| Seagate ST3320620AS 320GB       | 1         | 1      | 5%      |
| Seagate ST3320413CS 320GB       | 1         | 1      | 5%      |
| SanDisk sandisk120 120GB SSD    | 1         | 1      | 5%      |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 5%      |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 5%      |
| Hitachi HTS721060G9AT00 64GB    | 1         | 1      | 5%      |
| Hitachi HTS548040M9AT00 40GB    | 1         | 1      | 5%      |
| Hitachi HTS542525K9SA00 250GB   | 1         | 1      | 5%      |
| Hitachi HTS541612J9SA00 120GB   | 1         | 1      | 5%      |
| Hitachi HTC426040G8CE00 40GB    | 1         | 1      | 5%      |
| Hitachi DK23AA-60 6GB           | 1         | 1      | 5%      |
| China M.2 SSD 128GB             | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 40%     |
| WDC     | 5         | 5      | 25%     |
| Seagate | 5         | 5      | 25%     |
| SanDisk | 1         | 1      | 5%      |
| China   | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 44.44%  |
| WDC     | 5         | 5      | 27.78%  |
| Seagate | 5         | 5      | 27.78%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 18     | 90%     |
| SSD  | 2         | 2      | 10%     |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 31        | 39     | 53.45%  |
| Malfunc  | 20        | 20     | 34.48%  |
| Detected | 7         | 8      | 12.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 41        | 71.93%  |
| AMD                              | 4         | 7.02%   |
| Nvidia                           | 3         | 5.26%   |
| ASMedia Technology               | 3         | 5.26%   |
| Silicon Integrated Systems [SiS] | 2         | 3.51%   |
| VIA Technologies                 | 1         | 1.75%   |
| ULi Electronics                  | 1         | 1.75%   |
| Silicon Image                    | 1         | 1.75%   |
| JMicron Technology               | 1         | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 6.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 5.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 4.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 4.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 4.17%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 3         | 4.17%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 3         | 4.17%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 4.17%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 4.17%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 2.78%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 2.78%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 2.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.78%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.39%   |
| ULi ULi M5288 SATA                                                             | 1         | 1.39%   |
| ULi M5229 IDE                                                                  | 1         | 1.39%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.39%   |
| Nvidia nForce3 Serial ATA Controller                                           | 1         | 1.39%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.39%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                     | 1         | 1.39%   |
| Nvidia CK804 Serial ATA Controller                                             | 1         | 1.39%   |
| Nvidia CK804 IDE                                                               | 1         | 1.39%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.39%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.39%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.39%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 1.39%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.39%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.39%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1         | 1.39%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.39%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 1         | 1.39%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 1.39%   |
| AMD SB600 IDE                                                                  | 1         | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| IDE  | 32        | 52.46%  |
| SATA | 25        | 40.98%  |
| RAID | 4         | 6.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 45        | 86.54%  |
| AMD          | 6         | 11.54%  |
| GenuineTMx86 | 1         | 1.92%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                  | 4         | 7.69%   |
| Intel Pentium M processor 1.60GHz              | 2         | 3.85%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz           | 2         | 3.85%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 2         | 3.85%   |
| Intel Celeron (Mendocino)                      | 2         | 3.85%   |
| Intel Atom CPU Z520 @ 1.33GHz                  | 2         | 3.85%   |
| Intel Atom CPU N280 @ 1.66GHz                  | 2         | 3.85%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz        | 2         | 3.85%   |
| Intel Xeon CPU L5410 @ 2.33GHz                 | 1         | 1.92%   |
| Intel Pentium M processor 1600MHz              | 1         | 1.92%   |
| Intel Pentium M processor 1.86GHz              | 1         | 1.92%   |
| Intel Pentium M processor 1.00GHz              | 1         | 1.92%   |
| Intel Pentium II (Deschutes)                   | 1         | 1.92%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 1         | 1.92%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz         | 1         | 1.92%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz         | 1         | 1.92%   |
| Intel Pentium 4 CPU 2.00GHz                    | 1         | 1.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.92%   |
| Intel Core i7-7600U CPU @ 2.80GHz              | 1         | 1.92%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 1.92%   |
| Intel Core i7 CPU M 620 @ 2.67GHz              | 1         | 1.92%   |
| Intel Core i5-4300M CPU @ 2.60GHz              | 1         | 1.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 1.92%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1         | 1.92%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 1         | 1.92%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz          | 1         | 1.92%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 1.92%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz           | 1         | 1.92%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 1.92%   |
| Intel Celeron M processor 900MHz               | 1         | 1.92%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1         | 1.92%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz    | 1         | 1.92%   |
| Intel Celeron CPU J1900 @ 1.99GHz              | 1         | 1.92%   |
| Intel Celeron CPU 540 @ 1.86GHz                | 1         | 1.92%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 1         | 1.92%   |
| GenuineTMx86 Transmeta Crusoe Processor TM5800 | 1         | 1.92%   |
| AMD Sempron Processor 3000+                    | 1         | 1.92%   |
| AMD E2-7015 APU with AMD Radeon R2 Graphics    | 1         | 1.92%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+     | 1         | 1.92%   |
| AMD Athlon 64 Processor 3200+                  | 1         | 1.92%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 1.92%   |
| AMD A6-5400K APU with Radeon HD Graphics       | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 9         | 17.31%  |
| Intel Core 2 Duo        | 6         | 11.54%  |
| Intel Celeron           | 6         | 11.54%  |
| Intel Pentium M         | 5         | 9.62%   |
| Other                   | 4         | 7.69%   |
| Intel Core i7           | 4         | 7.69%   |
| Intel Core i5           | 3         | 5.77%   |
| Intel Pentium Dual      | 2         | 3.85%   |
| Intel Xeon              | 1         | 1.92%   |
| Intel Pentium Dual-Core | 1         | 1.92%   |
| Intel Pentium 4         | 1         | 1.92%   |
| Intel Pentium           | 1         | 1.92%   |
| Intel Core i3           | 1         | 1.92%   |
| Intel Core 2 Quad       | 1         | 1.92%   |
| Intel Celeron M         | 1         | 1.92%   |
| Intel Celeron Dual-Core | 1         | 1.92%   |
| AMD Sempron             | 1         | 1.92%   |
| AMD E2                  | 1         | 1.92%   |
| AMD Athlon 64 X2        | 1         | 1.92%   |
| AMD Athlon 64           | 1         | 1.92%   |
| AMD A6                  | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 46.15%  |
| 2      | 19        | 36.54%  |
| 4      | 7         | 13.46%  |
| 6      | 2         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 52        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 63.46%  |
| 2      | 19        | 36.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 63.46%  |
| 32-bit         | 19        | 36.54%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x106c2    | 8         | 15.38%  |
| 0x1067a    | 6         | 11.54%  |
| 0x6fd      | 5         | 9.62%   |
| Unknown    | 4         | 7.69%   |
| 0x6d6      | 3         | 5.77%   |
| 0xa0671    | 2         | 3.85%   |
| 0x6d8      | 2         | 3.85%   |
| 0x66a      | 2         | 3.85%   |
| 0x306a9    | 2         | 3.85%   |
| 0x206a7    | 2         | 3.85%   |
| 0xf24      | 1         | 1.92%   |
| 0x906e9    | 1         | 1.92%   |
| 0x806e9    | 1         | 1.92%   |
| 0x706a8    | 1         | 1.92%   |
| 0x706a1    | 1         | 1.92%   |
| 0x695      | 1         | 1.92%   |
| 0x652      | 1         | 1.92%   |
| 0x306c3    | 1         | 1.92%   |
| 0x30678    | 1         | 1.92%   |
| 0x20655    | 1         | 1.92%   |
| 0x106ca    | 1         | 1.92%   |
| 0x10676    | 1         | 1.92%   |
| 0x10661    | 1         | 1.92%   |
| 0x07030106 | 1         | 1.92%   |
| 0x06006705 | 1         | 1.92%   |
| 0x06001116 | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Bonnell       | 9         | 17.31%  |
| Penryn        | 7         | 13.46%  |
| P6            | 6         | 11.54%  |
| Core          | 6         | 11.54%  |
| Unknown       | 6         | 11.54%  |
| K8 Hammer     | 3         | 5.77%   |
| SandyBridge   | 2         | 3.85%   |
| KabyLake      | 2         | 3.85%   |
| IvyBridge     | 2         | 3.85%   |
| Goldmont plus | 2         | 3.85%   |
| Westmere      | 1         | 1.92%   |
| Silvermont    | 1         | 1.92%   |
| Puma          | 1         | 1.92%   |
| Piledriver    | 1         | 1.92%   |
| NetBurst      | 1         | 1.92%   |
| Haswell       | 1         | 1.92%   |
| Excavator     | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 26        | 49.06%  |
| AMD                              | 13        | 24.53%  |
| Nvidia                           | 11        | 20.75%  |
| Neomagic                         | 2         | 3.77%   |
| Silicon Integrated Systems [SiS] | 1         | 1.89%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 7.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 5         | 7.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 4.76%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 3.17%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 3.17%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 3.17%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 3.17%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 3.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 3.17%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 3.17%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.59%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.59%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.59%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.59%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1         | 1.59%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1         | 1.59%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.59%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 1.59%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.59%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.59%   |
| Intel HD Graphics 630                                                         | 1         | 1.59%   |
| Intel HD Graphics 620                                                         | 1         | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.59%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 1.59%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1         | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.59%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 1.59%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.59%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.59%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 1.59%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 1         | 1.59%   |
| AMD RV515 [Radeon X1300/X1550]                                                | 1         | 1.59%   |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 1.59%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 1.59%   |
| AMD RV280 [Radeon 9200 PRO] (Secondary)                                       | 1         | 1.59%   |
| AMD RV280 [Radeon 9200 PRO / 9250]                                            | 1         | 1.59%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 1.59%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 1.59%   |
| AMD Rage 3 [3D Rage PRO AGP 2X]                                               | 1         | 1.59%   |
| AMD Mullins [Radeon R2 Graphics]                                              | 1         | 1.59%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 1         | 1.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 1         | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 46.15%  |
| 1 x Nvidia     | 10        | 19.23%  |
| 1 x AMD        | 9         | 17.31%  |
| 2 x AMD        | 4         | 7.69%   |
| 1 x Neomagic   | 2         | 3.85%   |
| Other          | 1         | 1.92%   |
| 1 x SiS        | 1         | 1.92%   |
| Intel + Nvidia | 1         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 78.85%  |
| Unknown     | 8         | 15.38%  |
| Proprietary | 3         | 5.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 24        | 46.15%  |
| Unknown    | 18        | 34.62%  |
| 1.01-2.0   | 7         | 13.46%  |
| 5.01-6.0   | 1         | 1.92%   |
| 3.01-4.0   | 1         | 1.92%   |
| 0.51-1.0   | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 17.14%  |
| Samsung Electronics | 5         | 14.29%  |
| LG Display          | 5         | 14.29%  |
| Goldstar            | 3         | 8.57%   |
| Acer                | 3         | 8.57%   |
| HannStar            | 2         | 5.71%   |
| Vizio               | 1         | 2.86%   |
| LG Philips          | 1         | 2.86%   |
| Lenovo              | 1         | 2.86%   |
| HJW                 | 1         | 2.86%   |
| Hewlett-Packard     | 1         | 2.86%   |
| Dell                | 1         | 2.86%   |
| CPT                 | 1         | 2.86%   |
| Chimei Innolux      | 1         | 2.86%   |
| BOE                 | 1         | 2.86%   |
| Arnos Instruments   | 1         | 2.86%   |
| Apple               | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 2         | 5.71%   |
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                   | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch | 1         | 2.86%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 2.86%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 2.86%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 1         | 2.86%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 1         | 2.86%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 2.86%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 2.86%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                | 1         | 2.86%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch     | 1         | 2.86%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 2.86%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 1         | 2.86%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 1         | 2.86%   |
| Goldstar M2250D GSM57EF 1920x1080 477x268mm 21.5-inch                | 1         | 2.86%   |
| Goldstar M198WA GSM4B36 1440x900 410x260mm 19.1-inch                 | 1         | 2.86%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                     | 1         | 2.86%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 2.86%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch         | 1         | 2.86%   |
| Arnos Instruments F-417 AIC7450 1280x1024 338x270mm 17.0-inch        | 1         | 2.86%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 1         | 2.86%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                    | 1         | 2.86%   |
| Acer V243H ACR00A3 1920x1080 530x290mm 23.8-inch                     | 1         | 2.86%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                    | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 9         | 26.47%  |
| 1366x768 (WXGA)  | 9         | 26.47%  |
| 1280x800 (WXGA)  | 5         | 14.71%  |
| 1024x600         | 4         | 11.76%  |
| 1440x900 (WXGA+) | 3         | 8.82%   |
| 1600x1200        | 2         | 5.88%   |
| 2560x1080        | 1         | 2.94%   |
| 1280x1024 (SXGA) | 1         | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 6         | 17.14%  |
| 21     | 4         | 11.43%  |
| 14     | 4         | 11.43%  |
| 13     | 4         | 11.43%  |
| 17     | 3         | 8.57%   |
| 10     | 3         | 8.57%   |
| 8      | 2         | 5.71%   |
| 38     | 1         | 2.86%   |
| 34     | 1         | 2.86%   |
| 32     | 1         | 2.86%   |
| 27     | 1         | 2.86%   |
| 24     | 1         | 2.86%   |
| 23     | 1         | 2.86%   |
| 19     | 1         | 2.86%   |
| 18     | 1         | 2.86%   |
| 12     | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 34.29%  |
| 201-300     | 7         | 20%     |
| 401-500     | 6         | 17.14%  |
| 501-600     | 3         | 8.57%   |
| 701-800     | 2         | 5.71%   |
| 351-400     | 2         | 5.71%   |
| 101-200     | 2         | 5.71%   |
| 801-900     | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 21        | 61.76%  |
| 16/10 | 8         | 23.53%  |
| 4/3   | 2         | 5.88%   |
| 5/4   | 1         | 2.94%   |
| 3/2   | 1         | 2.94%   |
| 21/9  | 1         | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 6         | 17.14%  |
| 101-110        | 6         | 17.14%  |
| 201-250        | 5         | 14.29%  |
| 41-50          | 3         | 8.57%   |
| 71-80          | 2         | 5.71%   |
| 351-500        | 2         | 5.71%   |
| 1-40           | 2         | 5.71%   |
| 151-200        | 2         | 5.71%   |
| 141-150        | 2         | 5.71%   |
| 61-70          | 1         | 2.86%   |
| 301-350        | 1         | 2.86%   |
| 131-140        | 1         | 2.86%   |
| 121-130        | 1         | 2.86%   |
| 501-1000       | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 13        | 38.24%  |
| 101-120 | 11        | 32.35%  |
| 121-160 | 9         | 26.47%  |
| 1-50    | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 42        | 80.77%  |
| 0     | 8         | 15.38%  |
| 2     | 2         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 23        | 28.05%  |
| Realtek Semiconductor            | 19        | 23.17%  |
| Qualcomm Atheros                 | 15        | 18.29%  |
| Broadcom                         | 8         | 9.76%   |
| Nvidia                           | 3         | 3.66%   |
| Marvell Technology Group         | 3         | 3.66%   |
| Silicon Integrated Systems [SiS] | 2         | 2.44%   |
| Qualcomm Atheros Communications  | 2         | 2.44%   |
| Texas Instruments                | 1         | 1.22%   |
| Ralink Technology                | 1         | 1.22%   |
| Ralink                           | 1         | 1.22%   |
| MediaTek                         | 1         | 1.22%   |
| LSI                              | 1         | 1.22%   |
| Hewlett-Packard                  | 1         | 1.22%   |
| ASIX Electronics                 | 1         | 1.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 6.93%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5         | 4.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 3.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4         | 3.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 2.97%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 2.97%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 1.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 1.98%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 1.98%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2         | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.98%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 1.98%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 1.98%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.98%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 2         | 1.98%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 1.98%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 1.98%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.98%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.99%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.99%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.99%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.99%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.99%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.99%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.99%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 0.99%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.99%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.99%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 0.99%   |
| Nvidia CK8S Ethernet Controller                                               | 1         | 0.99%   |
| Nvidia CK804 Ethernet Controller                                              | 1         | 0.99%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 0.99%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 0.99%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 0.99%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1         | 0.99%   |
| LSI 56k WinModem                                                              | 1         | 0.99%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 0.99%   |
| Intel Wireless 7260                                                           | 1         | 0.99%   |
| Intel Wireless 3165                                                           | 1         | 0.99%   |
| Intel WiFi Link 5100                                                          | 1         | 0.99%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 0.99%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 0.99%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 0.99%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.99%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 0.99%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 0.99%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 0.99%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller              | 1         | 0.99%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                            | 1         | 0.99%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                                  | 1         | 0.99%   |
| Intel 82801BA/BAM AC'97 Modem Controller                                      | 1         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 0.99%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 39.13%  |
| Qualcomm Atheros                | 13        | 28.26%  |
| Broadcom                        | 5         | 10.87%  |
| Realtek Semiconductor           | 4         | 8.7%    |
| Qualcomm Atheros Communications | 2         | 4.35%   |
| Texas Instruments               | 1         | 2.17%   |
| Ralink Technology               | 1         | 2.17%   |
| Ralink                          | 1         | 2.17%   |
| MediaTek                        | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 14.89%  |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 6.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 4.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 4.26%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 4.26%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 4.26%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 4.26%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 2.13%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 2.13%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 2.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 2.13%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2.13%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 2.13%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 2.13%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.13%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 2.13%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.13%   |
| Intel Wireless 7260                                                           | 1         | 2.13%   |
| Intel Wireless 3165                                                           | 1         | 2.13%   |
| Intel WiFi Link 5100                                                          | 1         | 2.13%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 2.13%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 2.13%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2.13%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 2.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 2.13%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 18        | 37.5%   |
| Intel                            | 13        | 27.08%  |
| Broadcom                         | 5         | 10.42%  |
| Qualcomm Atheros                 | 3         | 6.25%   |
| Nvidia                           | 3         | 6.25%   |
| Marvell Technology Group         | 3         | 6.25%   |
| Silicon Integrated Systems [SiS] | 2         | 4.17%   |
| ASIX Electronics                 | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 10.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 8.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 6.25%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 4.17%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 4.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 4.17%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 4.17%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 4.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 2.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.08%   |
| Nvidia MCP89 Ethernet                                             | 1         | 2.08%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 2.08%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 2.08%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.08%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 2.08%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 2.08%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.08%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 2.08%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 2.08%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 2.08%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.08%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 2.08%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 2.08%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.08%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 49.46%  |
| WiFi     | 41        | 44.09%  |
| Modem    | 6         | 6.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 64.15%  |
| Ethernet | 19        | 35.85%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 65.38%  |
| 1     | 18        | 34.62%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 86.54%  |
| Yes  | 7         | 13.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 5         | 27.78%  |
| Broadcom                | 5         | 27.78%  |
| IMC Networks            | 2         | 11.11%  |
| Cambridge Silicon Radio | 2         | 11.11%  |
| Realtek Semiconductor   | 1         | 5.56%   |
| Ralink Technology       | 1         | 5.56%   |
| ASUSTek Computer        | 1         | 5.56%   |
| Apple                   | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 2         | 11.11%  |
| Intel AX201 Bluetooth                               | 2         | 11.11%  |
| IMC Networks Bluetooth Device                       | 2         | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 11.11%  |
| Broadcom HP Portable SoftSailing                    | 2         | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 5.56%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 5.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 5.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 5.56%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 5.56%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 5.56%   |
| Apple Bluetooth Host Controller                     | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 36        | 60%     |
| Nvidia                           | 7         | 11.67%  |
| AMD                              | 6         | 10%     |
| Silicon Integrated Systems [SiS] | 2         | 3.33%   |
| ESS Technology                   | 2         | 3.33%   |
| Creative Labs                    | 2         | 3.33%   |
| C-Media Electronics              | 2         | 3.33%   |
| VIA Technologies                 | 1         | 1.67%   |
| ULi Electronics                  | 1         | 1.67%   |
| Ensoniq                          | 1         | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 12.7%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 4.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 4.76%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 3         | 4.76%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 3.17%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 3.17%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 3.17%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 3.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 3.17%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 3.17%   |
| AMD FCH Azalia Controller                                                  | 2         | 3.17%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.59%   |
| ULi Electronics HD Audio Controller                                        | 1         | 1.59%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.59%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.59%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.59%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.59%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.59%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.59%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.59%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.59%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.59%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.59%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1         | 1.59%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1         | 1.59%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 1.59%   |
| C-Media Electronics CM6501                                                 | 1         | 1.59%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.59%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.59%   |
| AMD High Definition Audio Controller                                       | 1         | 1.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.59%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 25        | 43.86%  |
| SK hynix            | 6         | 10.53%  |
| Samsung Electronics | 4         | 7.02%   |
| Kingston            | 4         | 7.02%   |
| Unknown             | 4         | 7.02%   |
| Micron Technology   | 3         | 5.26%   |
| Crucial             | 2         | 3.51%   |
| Corsair             | 2         | 3.51%   |
| Unknown (ABCD)      | 1         | 1.75%   |
| Unknown (8A02)      | 1         | 1.75%   |
| tigo                | 1         | 1.75%   |
| Smart               | 1         | 1.75%   |
| Patriot             | 1         | 1.75%   |
| Kllisre             | 1         | 1.75%   |
| Avant               | 1         | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 4         | 6.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3         | 4.92%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 4.92%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 3.28%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 3.28%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 3.28%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 2         | 3.28%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s         | 2         | 3.28%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 1.64%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 1.64%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.64%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 1.64%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1         | 1.64%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                        | 1         | 1.64%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1         | 1.64%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 1.64%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 1.64%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 1         | 1.64%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 1         | 1.64%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 1.64%   |
| tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                     | 1         | 1.64%   |
| Smart RAM SG564568FG8N6KFSQR 2GB DIMM DDR2 800MT/s             | 1         | 1.64%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 1.64%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 1.64%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s           | 1         | 1.64%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.64%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM DDR3 1067MT/s      | 1         | 1.64%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 1.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 1.64%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 667MT/s                 | 1         | 1.64%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s             | 1         | 1.64%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 1.64%   |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 1.64%   |
| Micron RAM 4KTF51264HZ-1G6A1 4GB SODIMM DDR3 1600MT/s          | 1         | 1.64%   |
| Kllisre RAM DDR2 2G 2GB DIMM DDR2 800MT/s                      | 1         | 1.64%   |
| Kingston RAM MSI24D4S7D8MB-16 16GB SODIMM DDR4 2400MT/s        | 1         | 1.64%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s          | 1         | 1.64%   |
| Kingston RAM 99U5402-060.A 2GB DIMM DDR3 1333MT/s              | 1         | 1.64%   |
| Kingston RAM 9905428-095.D00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 1.64%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s        | 1         | 1.64%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1         | 1.64%   |
| Avant RAM H641GU67F1600G 8GB SODIMM DDR3 1600MT/s              | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 12        | 24.49%  |
| SDRAM   | 9         | 18.37%  |
| DDR2    | 8         | 16.33%  |
| DDR     | 8         | 16.33%  |
| DDR4    | 6         | 12.24%  |
| DRAM    | 3         | 6.12%   |
| Unknown | 2         | 4.08%   |
| LPDDR4  | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 33        | 67.35%  |
| DIMM   | 16        | 32.65%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 14        | 24.56%  |
| 1024  | 14        | 24.56%  |
| 4096  | 8         | 14.04%  |
| 512   | 7         | 12.28%  |
| 16384 | 4         | 7.02%   |
| 8192  | 4         | 7.02%   |
| 256   | 3         | 5.26%   |
| 64    | 2         | 3.51%   |
| 232   | 1         | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 18        | 35.29%  |
| 1600    | 8         | 15.69%  |
| 667     | 5         | 9.8%    |
| 1067    | 3         | 5.88%   |
| 3266    | 2         | 3.92%   |
| 3200    | 2         | 3.92%   |
| 2400    | 2         | 3.92%   |
| 1333    | 2         | 3.92%   |
| 800     | 2         | 3.92%   |
| 533     | 2         | 3.92%   |
| 2667    | 1         | 1.96%   |
| 975     | 1         | 1.96%   |
| 400     | 1         | 1.96%   |
| 333     | 1         | 1.96%   |
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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 20.83%  |
| Microdia                               | 3         | 12.5%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 12.5%   |
| Pixart Imaging                         | 2         | 8.33%   |
| IMC Networks                           | 2         | 8.33%   |
| Acer                                   | 2         | 8.33%   |
| Suyin                                  | 1         | 4.17%   |
| Sunplus Innovation Technology          | 1         | 4.17%   |
| Silicon Motion                         | 1         | 4.17%   |
| Lite-On Technology                     | 1         | 4.17%   |
| Lenovo                                 | 1         | 4.17%   |
| Importek                               | 1         | 4.17%   |
| Apple                                  | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 8.33%   |
| Microdia Sonix USB 2.0 Camera                           | 2         | 8.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 8.33%   |
| Suyin USB2.0 UVC 1.3M WebCam                            | 1         | 4.17%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 4.17%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 4.17%   |
| Microdia Integrated Webcam                              | 1         | 4.17%   |
| Lite-On HP TrueVision HD Camera                         | 1         | 4.17%   |
| Lenovo Integrated Webcam                                | 1         | 4.17%   |
| Importek FJ Camera                                      | 1         | 4.17%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 4.17%   |
| Chicony Integrated HP HD Webcam                         | 1         | 4.17%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 4.17%   |
| Chicony CNF8243 Webcam                                  | 1         | 4.17%   |
| Chicony CNF7050                                         | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 4.17%   |
| Apple Built-in iSight                                   | 1         | 4.17%   |
| Acer Lenovo EasyCamera                                  | 1         | 4.17%   |
| Acer BisonCam, NB Pro                                   | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 2         | 50%     |
| Validity Sensors | 1         | 25%     |
| Upek             | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                | 1         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 25%     |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 25%     |
| AuthenTec AES1600                                      | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 39        | 75%     |
| 1     | 8         | 15.38%  |
| 2     | 3         | 5.77%   |
| 3     | 2         | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 45%     |
| Fingerprint reader       | 4         | 20%     |
| Communication controller | 3         | 15%     |
| Sound                    | 1         | 5%      |
| Net/ethernet             | 1         | 5%      |
| Modem                    | 1         | 5%      |
| Chipcard                 | 1         | 5%      |

