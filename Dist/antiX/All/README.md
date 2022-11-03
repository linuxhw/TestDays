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

Total: 70

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Fujitsu       | FMVNU6G1C                   | Notebook    | [1351f25388](https://linux-hardware.org/?probe=1351f25388) | Sep 30, 2022 |
| ASUSTek       | 1011CX                      | Notebook    | [4ce8b4c2fe](https://linux-hardware.org/?probe=4ce8b4c2fe) | Sep 18, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [a225baa8a4](https://linux-hardware.org/?probe=a225baa8a4) | Aug 05, 2022 |
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

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| antiX 21       | 28        | 50.91%  |
| antiX 19.2     | 8         | 14.55%  |
| antiX 19.3     | 4         | 7.27%   |
| antiX 17.4.1   | 4         | 7.27%   |
| antiX 21-runit | 3         | 5.45%   |
| antiX 19.4     | 2         | 3.64%   |
| antiX 19.1     | 2         | 3.64%   |
| antiX 17.2.1   | 1         | 1.82%   |
| antiX 17.1     | 1         | 1.82%   |
| antiX 17       | 1         | 1.82%   |
| antiX 15       | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 55        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 14        | 25.45%  |
| 4.9.0-279-antix.1-amd64-smp  | 8         | 14.55%  |
| 5.10.57-antix.1-amd64-smp    | 7         | 12.73%  |
| 4.9.160-antix.2-486-smp      | 4         | 7.27%   |
| 4.9.235-antix.1-amd64-smp    | 3         | 5.45%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 5.45%   |
| 4.9.212-antix.1-486-smp      | 3         | 5.45%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 3.64%   |
| 4.9.200-antix.1-486-smp      | 2         | 3.64%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.82%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.82%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 1.82%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.82%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.82%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.82%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.82%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.82%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 23        | 41.82%  |
| 5.10.57  | 7         | 12.73%  |
| 4.9.212  | 6         | 10.91%  |
| 4.9.160  | 5         | 9.09%   |
| 4.9.235  | 3         | 5.45%   |
| 5.10.88  | 2         | 3.64%   |
| 4.9.200  | 2         | 3.64%   |
| 5.14.0   | 1         | 1.82%   |
| 5.10.27  | 1         | 1.82%   |
| 4.9.87   | 1         | 1.82%   |
| 4.19.202 | 1         | 1.82%   |
| 4.19.100 | 1         | 1.82%   |
| 4.19.0   | 1         | 1.82%   |
| 4.10.5   | 1         | 1.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 40        | 72.73%  |
| 5.10    | 10        | 18.18%  |
| 4.19    | 3         | 5.45%   |
| 5.14    | 1         | 1.82%   |
| 4.10    | 1         | 1.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 28        | 50.91%  |
| i686   | 26        | 47.27%  |
| i586   | 1         | 1.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 31        | 56.36%  |
| icewm        | 17        | 30.91%  |
| XFCE         | 4         | 7.27%   |
| jwm          | 1         | 1.82%   |
| herbstluftwm | 1         | 1.82%   |
| GNOME        | 1         | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 54        | 98.18%  |
| Tty  | 1         | 1.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 25        | 45.45%  |
| SLiM    | 21        | 38.18%  |
| LightDM | 5         | 9.09%   |
| SLIMSKI | 3         | 5.45%   |
| SDDM    | 1         | 1.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 25        | 45.45%  |
| ru_RU   | 4         | 7.27%   |
| ja_JP   | 3         | 5.45%   |
| de_DE   | 3         | 5.45%   |
| Unknown | 3         | 5.45%   |
| sk_SK   | 2         | 3.64%   |
| pt_BR   | 2         | 3.64%   |
| pl_PL   | 2         | 3.64%   |
| en_GB   | 2         | 3.64%   |
| en_AU   | 2         | 3.64%   |
| zh_HK   | 1         | 1.82%   |
| uk_UA   | 1         | 1.82%   |
| nl_NL   | 1         | 1.82%   |
| it_IT   | 1         | 1.82%   |
| es_VE   | 1         | 1.82%   |
| es_MX   | 1         | 1.82%   |
| es_AR   | 1         | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 45        | 81.82%  |
| EFI  | 10        | 18.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 46        | 83.64%  |
| Overlay  | 8         | 14.55%  |
| Reiserfs | 1         | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 43        | 78.18%  |
| GPT     | 10        | 18.18%  |
| Unknown | 2         | 3.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 81.82%  |
| Yes       | 10        | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 61.82%  |
| Yes       | 21        | 38.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 10        | 18.18%  |
| Hewlett-Packard     | 7         | 12.73%  |
| Lenovo              | 5         | 9.09%   |
| IBM                 | 5         | 9.09%   |
| MSI                 | 3         | 5.45%   |
| Dell                | 3         | 5.45%   |
| Unknown             | 3         | 5.45%   |
| KOHJINSHA           | 2         | 3.64%   |
| Gigabyte Technology | 2         | 3.64%   |
| Fujitsu             | 2         | 3.64%   |
| Acer                | 2         | 3.64%   |
| Toshiba             | 1         | 1.82%   |
| Samsung Electronics | 1         | 1.82%   |
| Radiant Systems     | 1         | 1.82%   |
| Packard Bell        | 1         | 1.82%   |
| Medion              | 1         | 1.82%   |
| Intel               | 1         | 1.82%   |
| Compaq              | 1         | 1.82%   |
| Biostar             | 1         | 1.82%   |
| AZW                 | 1         | 1.82%   |
| Apple               | 1         | 1.82%   |
| AMI                 | 1         | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 4         | 7.27%   |
| MSI US Desktop                     | 2         | 3.64%   |
| IBM 260921H                        | 2         | 3.64%   |
| Toshiba Satellite 1905             | 1         | 1.82%   |
| Samsung SQ1S                       | 1         | 1.82%   |
| Radiant Systems P845               | 1         | 1.82%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.82%   |
| MSI GE62 7RE                       | 1         | 1.82%   |
| Medion WIM2170                     | 1         | 1.82%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.82%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.82%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 1.82%   |
| Lenovo G550 2958                   | 1         | 1.82%   |
| KOHJINSHA SX series                | 1         | 1.82%   |
| KOHJINSHA SC series                | 1         | 1.82%   |
| Intel D525MW AAE93082-401          | 1         | 1.82%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.82%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.82%   |
| IBM ThinkPad T40 237342G           | 1         | 1.82%   |
| HP t5740                           | 1         | 1.82%   |
| HP Pavilion dv2700                 | 1         | 1.82%   |
| HP Mini 5101                       | 1         | 1.82%   |
| HP Mini 110-3700                   | 1         | 1.82%   |
| HP EliteBook 8770w                 | 1         | 1.82%   |
| HP EliteBook 2570p                 | 1         | 1.82%   |
| HP All-in-One 24-f0xx              | 1         | 1.82%   |
| Gigabyte F2A85XM-D3H               | 1         | 1.82%   |
| Gigabyte 945GCMX-S2                | 1         | 1.82%   |
| Fujitsu FMVS54EB                   | 1         | 1.82%   |
| Fujitsu FMVNU6G1C                  | 1         | 1.82%   |
| Dell OptiPlex 960                  | 1         | 1.82%   |
| Dell Latitude E6400                | 1         | 1.82%   |
| Dell Latitude 5480                 | 1         | 1.82%   |
| Compaq Tablet PC TC1000            | 1         | 1.82%   |
| Biostar G31-M7 TE                  | 1         | 1.82%   |
| AZW GK mini                        | 1         | 1.82%   |
| ASUS X71SL                         | 1         | 1.82%   |
| ASUS X51RL                         | 1         | 1.82%   |
| ASUS VivoBook_ASUSLaptop X509MA    | 1         | 1.82%   |
| ASUS VivoBook E14 E402YA_L402YA    | 1         | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 4         | 7.27%   |
| IBM ThinkPad          | 3         | 5.45%   |
| MSI US                | 2         | 3.64%   |
| Lenovo ThinkPad       | 2         | 3.64%   |
| IBM 260921H           | 2         | 3.64%   |
| HP Mini               | 2         | 3.64%   |
| HP EliteBook          | 2         | 3.64%   |
| Dell Latitude         | 2         | 3.64%   |
| ASUS VivoBook         | 2         | 3.64%   |
| Toshiba Satellite     | 1         | 1.82%   |
| Samsung SQ1S          | 1         | 1.82%   |
| Radiant Systems P845  | 1         | 1.82%   |
| Packard Bell EasyNote | 1         | 1.82%   |
| MSI GE62              | 1         | 1.82%   |
| Medion WIM2170        | 1         | 1.82%   |
| Lenovo ThinkCentre    | 1         | 1.82%   |
| Lenovo G550           | 1         | 1.82%   |
| KOHJINSHA SX          | 1         | 1.82%   |
| KOHJINSHA SC          | 1         | 1.82%   |
| Intel D525MW          | 1         | 1.82%   |
| HP t5740              | 1         | 1.82%   |
| HP Pavilion           | 1         | 1.82%   |
| HP All-in-One         | 1         | 1.82%   |
| Gigabyte F2A85XM-D3H  | 1         | 1.82%   |
| Gigabyte 945GCMX-S2   | 1         | 1.82%   |
| Fujitsu FMVS54EB      | 1         | 1.82%   |
| Fujitsu FMVNU6G1C     | 1         | 1.82%   |
| Dell OptiPlex         | 1         | 1.82%   |
| Compaq Tablet         | 1         | 1.82%   |
| Biostar G31-M7        | 1         | 1.82%   |
| AZW GK                | 1         | 1.82%   |
| ASUS X71SL            | 1         | 1.82%   |
| ASUS X51RL            | 1         | 1.82%   |
| ASUS P5KPL            | 1         | 1.82%   |
| ASUS A8R-MVP          | 1         | 1.82%   |
| ASUS A3L              | 1         | 1.82%   |
| ASUS 900HA            | 1         | 1.82%   |
| ASUS 900A             | 1         | 1.82%   |
| ASUS 1011CX           | 1         | 1.82%   |
| Apple MacBook7        | 1         | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 9         | 16.36%  |
| 2009    | 8         | 14.55%  |
| 2007    | 8         | 14.55%  |
| 2012    | 4         | 7.27%   |
| 2021    | 3         | 5.45%   |
| 2011    | 3         | 5.45%   |
| 2005    | 3         | 5.45%   |
| 2003    | 3         | 5.45%   |
| 2018    | 2         | 3.64%   |
| 2013    | 2         | 3.64%   |
| 2010    | 2         | 3.64%   |
| 1999    | 2         | 3.64%   |
| 2020    | 1         | 1.82%   |
| 2019    | 1         | 1.82%   |
| 2017    | 1         | 1.82%   |
| 2016    | 1         | 1.82%   |
| 2004    | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 37        | 67.27%  |
| Desktop    | 14        | 25.45%  |
| Mini pc    | 3         | 5.45%   |
| All in one | 1         | 1.82%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 55        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 12        | 21.82%  |
| 0.51-1.0   | 10        | 18.18%  |
| 2.01-3.0   | 8         | 14.55%  |
| 1.01-2.0   | 8         | 14.55%  |
| 4.01-8.0   | 4         | 7.27%   |
| 32.01-64.0 | 4         | 7.27%   |
| 0.01-0.5   | 4         | 7.27%   |
| 8.01-16.0  | 3         | 5.45%   |
| 16.01-24.0 | 2         | 3.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 23        | 41.82%  |
| 0.51-1.0 | 19        | 34.55%  |
| 1.01-2.0 | 7         | 12.73%  |
| 2.01-3.0 | 5         | 9.09%   |
| 4.01-8.0 | 1         | 1.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 39        | 70.91%  |
| 2      | 8         | 14.55%  |
| 3      | 4         | 7.27%   |
| 0      | 3         | 5.45%   |
| 4      | 1         | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 60%     |
| Yes       | 22        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 89.09%  |
| No        | 6         | 10.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 78.18%  |
| No        | 12        | 21.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 67.27%  |
| Yes       | 18        | 32.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 20%     |
| Hong Kong   | 9         | 16.36%  |
| Russia      | 6         | 10.91%  |
| Germany     | 5         | 9.09%   |
| Japan       | 3         | 5.45%   |
| Slovakia    | 2         | 3.64%   |
| Poland      | 2         | 3.64%   |
| Brazil      | 2         | 3.64%   |
| Australia   | 2         | 3.64%   |
| Ukraine     | 1         | 1.82%   |
| UK          | 1         | 1.82%   |
| Netherlands | 1         | 1.82%   |
| Mexico      | 1         | 1.82%   |
| Kenya       | 1         | 1.82%   |
| Kazakhstan  | 1         | 1.82%   |
| Italy       | 1         | 1.82%   |
| Hungary     | 1         | 1.82%   |
| Greece      | 1         | 1.82%   |
| France      | 1         | 1.82%   |
| Denmark     | 1         | 1.82%   |
| Chile       | 1         | 1.82%   |
| Argentina   | 1         | 1.82%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 7         | 12.73%  |
| Sydney                    | 2         | 3.64%   |
| Moscow                    | 2         | 3.64%   |
| Bratislava                | 2         | 3.64%   |
| Zagnansk                  | 1         | 1.82%   |
| Yuzhno-Sakhalinsk         | 1         | 1.82%   |
| Yokohama                  | 1         | 1.82%   |
| Violes                    | 1         | 1.82%   |
| Toms River                | 1         | 1.82%   |
| Sheung Shui               | 1         | 1.82%   |
| Schloss Holte-Stukenbrock | 1         | 1.82%   |
| Santiago                  | 1         | 1.82%   |
| Salto                     | 1         | 1.82%   |
| Rotterdam                 | 1         | 1.82%   |
| Reutlingen                | 1         | 1.82%   |
| Portland                  | 1         | 1.82%   |
| Otwock                    | 1         | 1.82%   |
| Nova Londrina             | 1         | 1.82%   |
| Norden                    | 1         | 1.82%   |
| Neyagawa                  | 1         | 1.82%   |
| Nairobi                   | 1         | 1.82%   |
| Mittegrossefehn           | 1         | 1.82%   |
| Mechanicsburg             | 1         | 1.82%   |
| Mason                     | 1         | 1.82%   |
| Maidstone                 | 1         | 1.82%   |
| Kazan’                  | 1         | 1.82%   |
| Karaganda                 | 1         | 1.82%   |
| Kagoshima                 | 1         | 1.82%   |
| Jonesboro                 | 1         | 1.82%   |
| Inveruno                  | 1         | 1.82%   |
| Houston                   | 1         | 1.82%   |
| Heraklion                 | 1         | 1.82%   |
| Greenville                | 1         | 1.82%   |
| Godley                    | 1         | 1.82%   |
| Frankfurt am Main         | 1         | 1.82%   |
| Elektrostal               | 1         | 1.82%   |
| El Cerrito                | 1         | 1.82%   |
| Domodedovo                | 1         | 1.82%   |
| Dnipro                    | 1         | 1.82%   |
| Covington                 | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 16.67%  |
| Hitachi             | 11        | 12     | 16.67%  |
| WDC                 | 10        | 11     | 15.15%  |
| Samsung Electronics | 7         | 8      | 10.61%  |
| Toshiba             | 5         | 5      | 7.58%   |
| Unknown             | 3         | 3      | 4.55%   |
| Kingston            | 2         | 2      | 3.03%   |
| BHT                 | 2         | 2      | 3.03%   |
| Zheino              | 1         | 1      | 1.52%   |
| Unknown (CF)        | 1         | 1      | 1.52%   |
| Transcend           | 1         | 1      | 1.52%   |
| SanDisk             | 1         | 1      | 1.52%   |
| RECADATA            | 1         | 1      | 1.52%   |
| OCZ                 | 1         | 1      | 1.52%   |
| Maxtor              | 1         | 1      | 1.52%   |
| Intel               | 1         | 1      | 1.52%   |
| HGST                | 1         | 1      | 1.52%   |
| Hewlett-Packard     | 1         | 1      | 1.52%   |
| Fujitsu             | 1         | 1      | 1.52%   |
| Crucial             | 1         | 1      | 1.52%   |
| China               | 1         | 1      | 1.52%   |
| ASUS-PHISON         | 1         | 1      | 1.52%   |
| Unknown             | 1         | 1      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB               | 2         | 2.94%   |
| Hitachi HTS723232A7A364 320GB           | 2         | 2.94%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 2.94%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 1.47%   |
| WDC WD8088AADS-00M2B0 809GB             | 1         | 1.47%   |
| WDC WD800JB-00ETA0 80GB                 | 1         | 1.47%   |
| WDC WD800AAJS-75M0A0 80GB               | 1         | 1.47%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.47%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.47%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.47%   |
| WDC WD205BA 21GB                        | 1         | 1.47%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 1.47%   |
| WDC WD1600AAJS-00PSA0 160GB             | 1         | 1.47%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.47%   |
| WDC WD10SPZX-80Z10T2 1TB                | 1         | 1.47%   |
| Unknown SR64G  64GB                     | 1         | 1.47%   |
| Unknown SD/MMC/MS PRO 1TB               | 1         | 1.47%   |
| Unknown 2GB ATA Flash Disk              | 1         | 1.47%   |
| Unknown (CF) Card 16GB SSD              | 1         | 1.47%   |
| Transcend SSD 2GB                       | 1         | 1.47%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.47%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.47%   |
| Toshiba MQ01ABD050V -63 500GB           | 1         | 1.47%   |
| Toshiba MK2576GSX 250GB                 | 1         | 1.47%   |
| Toshiba DT01ACA100 1TB                  | 1         | 1.47%   |
| Seagate ST9320325AS 320GB               | 1         | 1.47%   |
| Seagate ST9160411AS 160GB               | 1         | 1.47%   |
| Seagate ST9160314AS 160GB               | 1         | 1.47%   |
| Seagate ST9160310AS 160GB               | 1         | 1.47%   |
| Seagate ST9160301AS 160GB               | 1         | 1.47%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 1.47%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1.47%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1.47%   |
| Seagate ST3320620AS 320GB               | 1         | 1.47%   |
| Seagate ST3320413CS 320GB               | 1         | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 1.47%   |
| SanDisk sandisk120 120GB SSD            | 1         | 1.47%   |
| Samsung SSD 850 EVO 120GB               | 1         | 1.47%   |
| Samsung HS06THB 64GB                    | 1         | 1.47%   |
| Samsung HD250HJ 250GB                   | 1         | 1.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 25.58%  |
| Hitachi             | 11        | 12     | 25.58%  |
| WDC                 | 10        | 11     | 23.26%  |
| Samsung Electronics | 4         | 5      | 9.3%    |
| Toshiba             | 3         | 3      | 6.98%   |
| Unknown             | 2         | 2      | 4.65%   |
| HGST                | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 13.64%  |
| Toshiba             | 2         | 2      | 9.09%   |
| Kingston            | 2         | 2      | 9.09%   |
| BHT                 | 2         | 2      | 9.09%   |
| Zheino              | 1         | 1      | 4.55%   |
| Unknown (CF)        | 1         | 1      | 4.55%   |
| Transcend           | 1         | 1      | 4.55%   |
| SanDisk             | 1         | 1      | 4.55%   |
| RECADATA            | 1         | 1      | 4.55%   |
| OCZ                 | 1         | 1      | 4.55%   |
| Maxtor              | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| Hewlett-Packard     | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |
| China               | 1         | 1      | 4.55%   |
| ASUS-PHISON         | 1         | 1      | 4.55%   |
| Unknown             | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 46     | 63.33%  |
| SSD  | 21        | 22     | 35%     |
| MMC  | 1         | 1      | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 52        | 67     | 96.3%   |
| SAS  | 1         | 1      | 1.85%   |
| MMC  | 1         | 1      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 60     | 87.93%  |
| 0.51-1.0   | 6         | 7      | 10.34%  |
| 1.01-2.0   | 1         | 1      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 29.09%  |
| 1-20       | 16        | 29.09%  |
| 51-100     | 8         | 14.55%  |
| 21-50      | 6         | 10.91%  |
| 251-500    | 4         | 7.27%   |
| 501-1000   | 3         | 5.45%   |
| 1001-2000  | 1         | 1.82%   |
| Unknown    | 1         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 43        | 78.18%  |
| 21-50    | 5         | 9.09%   |
| 101-250  | 3         | 5.45%   |
| 51-100   | 2         | 3.64%   |
| 501-1000 | 1         | 1.82%   |
| Unknown  | 1         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD8088AADS-00M2B0 809GB     | 1         | 1      | 4.76%   |
| WDC WD800JB-00ETA0 80GB         | 1         | 1      | 4.76%   |
| WDC WD800AAJS-75M0A0 80GB       | 1         | 1      | 4.76%   |
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 4.76%   |
| WDC WD205BA 21GB                | 1         | 1      | 4.76%   |
| Seagate ST9320325AS 320GB       | 1         | 1      | 4.76%   |
| Seagate ST9160314AS 160GB       | 1         | 1      | 4.76%   |
| Seagate ST9160310AS 160GB       | 1         | 1      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 4.76%   |
| Seagate ST3320620AS 320GB       | 1         | 1      | 4.76%   |
| Seagate ST3320413CS 320GB       | 1         | 1      | 4.76%   |
| SanDisk sandisk120 120GB SSD    | 1         | 1      | 4.76%   |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 4.76%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 4.76%   |
| Hitachi HTS721060G9AT00 64GB    | 1         | 1      | 4.76%   |
| Hitachi HTS548040M9AT00 40GB    | 1         | 1      | 4.76%   |
| Hitachi HTS542525K9SA00 250GB   | 1         | 1      | 4.76%   |
| Hitachi HTS541612J9SA00 120GB   | 1         | 1      | 4.76%   |
| Hitachi HTC426040G8CE00 40GB    | 1         | 1      | 4.76%   |
| Hitachi DK23AA-60 6GB           | 1         | 1      | 4.76%   |
| China M.2 SSD 128GB             | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 38.1%   |
| Seagate | 6         | 6      | 28.57%  |
| WDC     | 5         | 5      | 23.81%  |
| SanDisk | 1         | 1      | 4.76%   |
| China   | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 8         | 8      | 42.11%  |
| Seagate | 6         | 6      | 31.58%  |
| WDC     | 5         | 5      | 26.32%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 19     | 90.48%  |
| SSD  | 2         | 2      | 9.52%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 32        | 40     | 53.33%  |
| Malfunc  | 21        | 21     | 35%     |
| Detected | 7         | 8      | 11.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44        | 73.33%  |
| AMD                              | 4         | 6.67%   |
| Nvidia                           | 3         | 5%      |
| ASMedia Technology               | 3         | 5%      |
| Silicon Integrated Systems [SiS] | 2         | 3.33%   |
| VIA Technologies                 | 1         | 1.67%   |
| ULi Electronics                  | 1         | 1.67%   |
| Silicon Image                    | 1         | 1.67%   |
| JMicron Technology               | 1         | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 8%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 5.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 4%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 4%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 4%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 4%      |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 3         | 4%      |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 3         | 4%      |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 4%      |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 4%      |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 2.67%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 2.67%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 2.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.67%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.33%   |
| ULi ULi M5288 SATA                                                             | 1         | 1.33%   |
| ULi M5229 IDE                                                                  | 1         | 1.33%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.33%   |
| Nvidia nForce3 Serial ATA Controller                                           | 1         | 1.33%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.33%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                     | 1         | 1.33%   |
| Nvidia CK804 Serial ATA Controller                                             | 1         | 1.33%   |
| Nvidia CK804 IDE                                                               | 1         | 1.33%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.33%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.33%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 1.33%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.33%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.33%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1         | 1.33%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| IDE  | 33        | 51.56%  |
| SATA | 27        | 42.19%  |
| RAID | 4         | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 48        | 87.27%  |
| AMD          | 6         | 10.91%  |
| GenuineTMx86 | 1         | 1.82%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                  | 4         | 7.27%   |
| Intel Pentium M processor 1.60GHz              | 2         | 3.64%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz           | 2         | 3.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz           | 2         | 3.64%   |
| Intel Celeron (Mendocino)                      | 2         | 3.64%   |
| Intel Atom CPU Z520 @ 1.33GHz                  | 2         | 3.64%   |
| Intel Atom CPU N280 @ 1.66GHz                  | 2         | 3.64%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz        | 2         | 3.64%   |
| Intel Xeon CPU L5410 @ 2.33GHz                 | 1         | 1.82%   |
| Intel Pentium M processor 1600MHz              | 1         | 1.82%   |
| Intel Pentium M processor 1.86GHz              | 1         | 1.82%   |
| Intel Pentium M processor 1.00GHz              | 1         | 1.82%   |
| Intel Pentium II (Deschutes)                   | 1         | 1.82%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz    | 1         | 1.82%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz         | 1         | 1.82%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz         | 1         | 1.82%   |
| Intel Pentium 4 CPU 2.00GHz                    | 1         | 1.82%   |
| Intel Genuine processor 800MHz                 | 1         | 1.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.82%   |
| Intel Core i7-7600U CPU @ 2.80GHz              | 1         | 1.82%   |
| Intel Core i7-3740QM CPU @ 2.70GHz             | 1         | 1.82%   |
| Intel Core i7 CPU M 620 @ 2.67GHz              | 1         | 1.82%   |
| Intel Core i5-4300M CPU @ 2.60GHz              | 1         | 1.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 1.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1         | 1.82%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 1         | 1.82%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz          | 1         | 1.82%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz           | 1         | 1.82%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz           | 1         | 1.82%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 1.82%   |
| Intel Celeron M processor 900MHz               | 1         | 1.82%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1         | 1.82%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz    | 1         | 1.82%   |
| Intel Celeron CPU J1900 @ 1.99GHz              | 1         | 1.82%   |
| Intel Celeron CPU 540 @ 1.86GHz                | 1         | 1.82%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 1         | 1.82%   |
| Intel Atom CPU N2600 @ 1.60GHz                 | 1         | 1.82%   |
| Intel Atom CPU D525 @ 1.80GHz                  | 1         | 1.82%   |
| GenuineTMx86 Transmeta Crusoe Processor TM5800 | 1         | 1.82%   |
| AMD Sempron Processor 3000+                    | 1         | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 11        | 20%     |
| Intel Core 2 Duo        | 6         | 10.91%  |
| Intel Celeron           | 6         | 10.91%  |
| Intel Pentium M         | 5         | 9.09%   |
| Other                   | 4         | 7.27%   |
| Intel Core i7           | 4         | 7.27%   |
| Intel Core i5           | 3         | 5.45%   |
| Intel Pentium Dual      | 2         | 3.64%   |
| Intel Xeon              | 1         | 1.82%   |
| Intel Pentium Dual-Core | 1         | 1.82%   |
| Intel Pentium 4         | 1         | 1.82%   |
| Intel Pentium           | 1         | 1.82%   |
| Intel Genuine           | 1         | 1.82%   |
| Intel Core i3           | 1         | 1.82%   |
| Intel Core 2 Quad       | 1         | 1.82%   |
| Intel Celeron M         | 1         | 1.82%   |
| Intel Celeron Dual-Core | 1         | 1.82%   |
| AMD Sempron             | 1         | 1.82%   |
| AMD E2                  | 1         | 1.82%   |
| AMD Athlon 64 X2        | 1         | 1.82%   |
| AMD Athlon 64           | 1         | 1.82%   |
| AMD A6                  | 1         | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 45.45%  |
| 2      | 21        | 38.18%  |
| 4      | 7         | 12.73%  |
| 6      | 2         | 3.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 61.82%  |
| 2      | 21        | 38.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 61.82%  |
| 32-bit         | 21        | 38.18%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x106c2    | 8         | 14.55%  |
| 0x1067a    | 6         | 10.91%  |
| 0x6fd      | 5         | 9.09%   |
| Unknown    | 4         | 7.27%   |
| 0x6d8      | 3         | 5.45%   |
| 0x6d6      | 3         | 5.45%   |
| 0xa0671    | 2         | 3.64%   |
| 0x66a      | 2         | 3.64%   |
| 0x306a9    | 2         | 3.64%   |
| 0x206a7    | 2         | 3.64%   |
| 0x106ca    | 2         | 3.64%   |
| 0xf24      | 1         | 1.82%   |
| 0x906e9    | 1         | 1.82%   |
| 0x806e9    | 1         | 1.82%   |
| 0x706a8    | 1         | 1.82%   |
| 0x706a1    | 1         | 1.82%   |
| 0x695      | 1         | 1.82%   |
| 0x652      | 1         | 1.82%   |
| 0x306c3    | 1         | 1.82%   |
| 0x30678    | 1         | 1.82%   |
| 0x30661    | 1         | 1.82%   |
| 0x20655    | 1         | 1.82%   |
| 0x10676    | 1         | 1.82%   |
| 0x10661    | 1         | 1.82%   |
| 0x07030106 | 1         | 1.82%   |
| 0x06006705 | 1         | 1.82%   |
| 0x06001116 | 1         | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Bonnell       | 11        | 20%     |
| Penryn        | 7         | 12.73%  |
| P6            | 7         | 12.73%  |
| Core          | 6         | 10.91%  |
| Unknown       | 6         | 10.91%  |
| K8 Hammer     | 3         | 5.45%   |
| SandyBridge   | 2         | 3.64%   |
| KabyLake      | 2         | 3.64%   |
| IvyBridge     | 2         | 3.64%   |
| Goldmont plus | 2         | 3.64%   |
| Westmere      | 1         | 1.82%   |
| Silvermont    | 1         | 1.82%   |
| Puma          | 1         | 1.82%   |
| Piledriver    | 1         | 1.82%   |
| NetBurst      | 1         | 1.82%   |
| Haswell       | 1         | 1.82%   |
| Excavator     | 1         | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 29        | 51.79%  |
| AMD                              | 13        | 23.21%  |
| Nvidia                           | 11        | 19.64%  |
| Neomagic                         | 2         | 3.57%   |
| Silicon Integrated Systems [SiS] | 1         | 1.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 6         | 8.96%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 7.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 4.48%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 2.99%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 2.99%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 2.99%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 2.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 2         | 2.99%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 2.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 2.99%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 2.99%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.49%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.49%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.49%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.49%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.49%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1         | 1.49%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1         | 1.49%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.49%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 1.49%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.49%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.49%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.49%   |
| Intel HD Graphics 630                                                         | 1         | 1.49%   |
| Intel HD Graphics 620                                                         | 1         | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.49%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.49%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1         | 1.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.49%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 1.49%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.49%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.49%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 1.49%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 1         | 1.49%   |
| AMD RV515 [Radeon X1300/X1550]                                                | 1         | 1.49%   |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 1.49%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 49.09%  |
| 1 x Nvidia     | 10        | 18.18%  |
| 1 x AMD        | 9         | 16.36%  |
| 2 x AMD        | 4         | 7.27%   |
| 1 x Neomagic   | 2         | 3.64%   |
| Other          | 1         | 1.82%   |
| 1 x SiS        | 1         | 1.82%   |
| Intel + Nvidia | 1         | 1.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 44        | 80%     |
| Unknown     | 8         | 14.55%  |
| Proprietary | 3         | 5.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 26        | 47.27%  |
| Unknown    | 19        | 34.55%  |
| 1.01-2.0   | 7         | 12.73%  |
| 5.01-6.0   | 1         | 1.82%   |
| 3.01-4.0   | 1         | 1.82%   |
| 0.51-1.0   | 1         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 16.67%  |
| Samsung Electronics | 5         | 13.89%  |
| LG Display          | 5         | 13.89%  |
| HannStar            | 3         | 8.33%   |
| Goldstar            | 3         | 8.33%   |
| Acer                | 3         | 8.33%   |
| Vizio               | 1         | 2.78%   |
| LG Philips          | 1         | 2.78%   |
| Lenovo              | 1         | 2.78%   |
| HJW                 | 1         | 2.78%   |
| Hewlett-Packard     | 1         | 2.78%   |
| Dell                | 1         | 2.78%   |
| CPT                 | 1         | 2.78%   |
| Chimei Innolux      | 1         | 2.78%   |
| BOE                 | 1         | 2.78%   |
| Arnos Instruments   | 1         | 2.78%   |
| Apple               | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 2         | 5.56%   |
| Vizio E280i-B1 VIZ1002 1360x768 607x345mm 27.5-inch                  | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch | 1         | 2.78%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 2.78%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 2.78%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 1         | 2.78%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 1         | 2.78%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch          | 1         | 2.78%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 2.78%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 1         | 2.78%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                | 1         | 2.78%   |
| Hewlett-Packard Contino HPN4018 1920x1080 527x296mm 23.8-inch        | 1         | 2.78%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 1         | 2.78%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 2.78%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch            | 1         | 2.78%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 1         | 2.78%   |
| Goldstar M2250D GSM57EF 1920x1080 477x268mm 21.5-inch                | 1         | 2.78%   |
| Goldstar M198WA GSM4B36 1440x900 410x260mm 19.1-inch                 | 1         | 2.78%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                     | 1         | 2.78%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 2.78%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch         | 1         | 2.78%   |
| Arnos Instruments F-417 AIC7450 1280x1024 338x270mm 17.0-inch        | 1         | 2.78%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 1         | 2.78%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                    | 1         | 2.78%   |
| Acer V243H ACR00A3 1920x1080 531x298mm 24.0-inch                     | 1         | 2.78%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                    | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 9         | 25.71%  |
| 1366x768 (WXGA)  | 9         | 25.71%  |
| 1280x800 (WXGA)  | 5         | 14.29%  |
| 1024x600         | 5         | 14.29%  |
| 1440x900 (WXGA+) | 3         | 8.57%   |
| 1600x1200        | 2         | 5.71%   |
| 2560x1080        | 1         | 2.86%   |
| 1280x1024 (SXGA) | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 6         | 16.67%  |
| 21     | 4         | 11.11%  |
| 14     | 4         | 11.11%  |
| 13     | 4         | 11.11%  |
| 10     | 4         | 11.11%  |
| 17     | 3         | 8.33%   |
| 8      | 2         | 5.56%   |
| 38     | 1         | 2.78%   |
| 34     | 1         | 2.78%   |
| 32     | 1         | 2.78%   |
| 27     | 1         | 2.78%   |
| 24     | 1         | 2.78%   |
| 23     | 1         | 2.78%   |
| 19     | 1         | 2.78%   |
| 18     | 1         | 2.78%   |
| 12     | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 33.33%  |
| 201-300     | 8         | 22.22%  |
| 401-500     | 6         | 16.67%  |
| 501-600     | 3         | 8.33%   |
| 701-800     | 2         | 5.56%   |
| 351-400     | 2         | 5.56%   |
| 101-200     | 2         | 5.56%   |
| 801-900     | 1         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 62.86%  |
| 16/10 | 8         | 22.86%  |
| 4/3   | 2         | 5.71%   |
| 5/4   | 1         | 2.86%   |
| 3/2   | 1         | 2.86%   |
| 21/9  | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 6         | 16.67%  |
| 101-110        | 6         | 16.67%  |
| 201-250        | 5         | 13.89%  |
| 41-50          | 4         | 11.11%  |
| 71-80          | 2         | 5.56%   |
| 351-500        | 2         | 5.56%   |
| 1-40           | 2         | 5.56%   |
| 151-200        | 2         | 5.56%   |
| 141-150        | 2         | 5.56%   |
| 61-70          | 1         | 2.78%   |
| 301-350        | 1         | 2.78%   |
| 131-140        | 1         | 2.78%   |
| 121-130        | 1         | 2.78%   |
| 501-1000       | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 13        | 37.14%  |
| 101-120 | 12        | 34.29%  |
| 121-160 | 9         | 25.71%  |
| 1-50    | 1         | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 81.82%  |
| 0     | 8         | 14.55%  |
| 2     | 2         | 3.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 23        | 26.44%  |
| Realtek Semiconductor            | 21        | 24.14%  |
| Qualcomm Atheros                 | 16        | 18.39%  |
| Broadcom                         | 9         | 10.34%  |
| Nvidia                           | 3         | 3.45%   |
| Marvell Technology Group         | 3         | 3.45%   |
| Silicon Integrated Systems [SiS] | 2         | 2.3%    |
| Qualcomm Atheros Communications  | 2         | 2.3%    |
| Texas Instruments                | 1         | 1.15%   |
| Ralink Technology                | 1         | 1.15%   |
| Ralink                           | 1         | 1.15%   |
| MediaTek                         | 1         | 1.15%   |
| LSI                              | 1         | 1.15%   |
| Hewlett-Packard                  | 1         | 1.15%   |
| Attansic Technology              | 1         | 1.15%   |
| ASIX Electronics                 | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 6.6%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 6         | 5.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5         | 4.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 2.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 2.83%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 1.89%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 1.89%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2         | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.89%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 1.89%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 1.89%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.89%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 2         | 1.89%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 1.89%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 1.89%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.89%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.94%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.94%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.94%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.94%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.94%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.94%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.94%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.94%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 0.94%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.94%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.94%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 0.94%   |
| Nvidia CK8S Ethernet Controller                                               | 1         | 0.94%   |
| Nvidia CK804 Ethernet Controller                                              | 1         | 0.94%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 0.94%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 0.94%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 0.94%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1         | 0.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 37.5%   |
| Qualcomm Atheros                | 14        | 29.17%  |
| Broadcom                        | 6         | 12.5%   |
| Realtek Semiconductor           | 4         | 8.33%   |
| Qualcomm Atheros Communications | 2         | 4.17%   |
| Texas Instruments               | 1         | 2.08%   |
| Ralink Technology               | 1         | 2.08%   |
| Ralink                          | 1         | 2.08%   |
| MediaTek                        | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 14.29%  |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 6.12%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 4.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 4.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 4.08%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 4.08%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 4.08%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 4.08%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 2.04%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 2.04%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 2.04%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 2.04%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 2.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 2.04%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 2.04%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 2.04%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.04%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 2.04%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 2.04%   |
| Intel Wireless 7260                                                           | 1         | 2.04%   |
| Intel Wireless 3165                                                           | 1         | 2.04%   |
| Intel WiFi Link 5100                                                          | 1         | 2.04%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 2.04%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 2.04%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 2.04%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 2.04%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 2.04%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 20        | 39.22%  |
| Intel                            | 13        | 25.49%  |
| Broadcom                         | 5         | 9.8%    |
| Qualcomm Atheros                 | 3         | 5.88%   |
| Nvidia                           | 3         | 5.88%   |
| Marvell Technology Group         | 3         | 5.88%   |
| Silicon Integrated Systems [SiS] | 2         | 3.92%   |
| Attansic Technology              | 1         | 1.96%   |
| ASIX Electronics                 | 1         | 1.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 11.76%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 9.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.88%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 3.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.92%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 3.92%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 3.92%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 3.92%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 3.92%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.96%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.96%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.96%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 1.96%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 1.96%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.96%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.96%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.96%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 1.96%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.96%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.96%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.96%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 1.96%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.96%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.96%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.96%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 1.96%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 49        | 50%     |
| WiFi     | 43        | 43.88%  |
| Modem    | 6         | 6.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 64.29%  |
| Ethernet | 20        | 35.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 36        | 65.45%  |
| 1     | 19        | 34.55%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 48        | 87.27%  |
| Yes  | 7         | 12.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


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

![Bluetooth Model](./images/pie_chart/bt_model.svg)


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

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 39        | 61.9%   |
| Nvidia                           | 7         | 11.11%  |
| AMD                              | 6         | 9.52%   |
| Silicon Integrated Systems [SiS] | 2         | 3.17%   |
| ESS Technology                   | 2         | 3.17%   |
| Creative Labs                    | 2         | 3.17%   |
| C-Media Electronics              | 2         | 3.17%   |
| VIA Technologies                 | 1         | 1.59%   |
| ULi Electronics                  | 1         | 1.59%   |
| Ensoniq                          | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 16.67%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 4.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 4.55%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 3         | 4.55%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 3.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 3.03%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 3.03%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 3.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 3.03%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 3.03%   |
| AMD FCH Azalia Controller                                                  | 2         | 3.03%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.52%   |
| ULi Electronics HD Audio Controller                                        | 1         | 1.52%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.52%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.52%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.52%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.52%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.52%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.52%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.52%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.52%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.52%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.52%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1         | 1.52%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1         | 1.52%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 1.52%   |
| C-Media Electronics CM6501                                                 | 1         | 1.52%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.52%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.52%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.52%   |
| AMD High Definition Audio Controller                                       | 1         | 1.52%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 26        | 44.07%  |
| SK hynix            | 6         | 10.17%  |
| Unknown             | 5         | 8.47%   |
| Samsung Electronics | 4         | 6.78%   |
| Kingston            | 4         | 6.78%   |
| Micron Technology   | 3         | 5.08%   |
| Crucial             | 2         | 3.39%   |
| Corsair             | 2         | 3.39%   |
| Unknown (ABCD)      | 1         | 1.69%   |
| Unknown (8A02)      | 1         | 1.69%   |
| tigo                | 1         | 1.69%   |
| Smart               | 1         | 1.69%   |
| Patriot             | 1         | 1.69%   |
| Kllisre             | 1         | 1.69%   |
| Avant               | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 7.94%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3         | 4.76%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 4.76%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 3.17%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 3.17%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 3.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 2         | 3.17%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s         | 2         | 3.17%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 1.59%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1         | 1.59%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                      | 1         | 1.59%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 1.59%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                       | 1         | 1.59%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 1.59%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 1.59%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.59%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 1.59%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1         | 1.59%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                        | 1         | 1.59%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1         | 1.59%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 1.59%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 1.59%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 1         | 1.59%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s   | 1         | 1.59%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 1.59%   |
| tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                     | 1         | 1.59%   |
| Smart RAM SG564568FG8N6KFSQR 2GB DIMM DDR2 800MT/s             | 1         | 1.59%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 1.59%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 1.59%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s          | 1         | 1.59%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.59%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 1.59%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 1.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 1.59%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 1.59%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 667MT/s                 | 1         | 1.59%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s             | 1         | 1.59%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 13        | 25.49%  |
| SDRAM   | 9         | 17.65%  |
| DDR2    | 9         | 17.65%  |
| DDR     | 8         | 15.69%  |
| DDR4    | 6         | 11.76%  |
| DRAM    | 3         | 5.88%   |
| Unknown | 2         | 3.92%   |
| LPDDR4  | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 34        | 66.67%  |
| DIMM   | 17        | 33.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 15        | 25.42%  |
| 1024  | 15        | 25.42%  |
| 4096  | 8         | 13.56%  |
| 512   | 7         | 11.86%  |
| 16384 | 4         | 6.78%   |
| 8192  | 4         | 6.78%   |
| 256   | 3         | 5.08%   |
| 64    | 2         | 3.39%   |
| 232   | 1         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 18        | 33.96%  |
| 1600    | 8         | 15.09%  |
| 667     | 5         | 9.43%   |
| 1067    | 3         | 5.66%   |
| 800     | 3         | 5.66%   |
| 3266    | 2         | 3.77%   |
| 3200    | 2         | 3.77%   |
| 2400    | 2         | 3.77%   |
| 1333    | 2         | 3.77%   |
| 533     | 2         | 3.77%   |
| 2667    | 1         | 1.89%   |
| 975     | 1         | 1.89%   |
| 400     | 1         | 1.89%   |
| 333     | 1         | 1.89%   |
| 266     | 1         | 1.89%   |
| 200     | 1         | 1.89%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 20%     |
| Microdia                               | 3         | 12%     |
| IMC Networks                           | 3         | 12%     |
| Cheng Uei Precision Industry (Foxlink) | 3         | 12%     |
| Pixart Imaging                         | 2         | 8%      |
| Acer                                   | 2         | 8%      |
| Suyin                                  | 1         | 4%      |
| Sunplus Innovation Technology          | 1         | 4%      |
| Silicon Motion                         | 1         | 4%      |
| Lite-On Technology                     | 1         | 4%      |
| Lenovo                                 | 1         | 4%      |
| Importek                               | 1         | 4%      |
| Apple                                  | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 8%      |
| Microdia Sonix USB 2.0 Camera                           | 2         | 8%      |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 8%      |
| Suyin Lenovo EasyCamera                                 | 1         | 4%      |
| Sunplus Integrated_Webcam_HD                            | 1         | 4%      |
| Silicon Motion Lenovo EasyCamera                        | 1         | 4%      |
| Microdia Integrated Webcam                              | 1         | 4%      |
| Lite-On HP TrueVision HD Camera                         | 1         | 4%      |
| Lenovo Integrated Webcam                                | 1         | 4%      |
| Importek FJ Camera                                      | 1         | 4%      |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 4%      |
| Chicony VGA 30fps UVC Webcam                            | 1         | 4%      |
| Chicony Integrated HP HD Webcam                         | 1         | 4%      |
| Chicony HP HD Webcam [Fixed]                            | 1         | 4%      |
| Chicony CNF8243 Webcam                                  | 1         | 4%      |
| Chicony CNF7050                                         | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 4%      |
| Apple Built-in iSight                                   | 1         | 4%      |
| Acer Lenovo EasyCamera                                  | 1         | 4%      |
| Acer BisonCam, NB Pro                                   | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 3         | 60%     |
| Validity Sensors | 1         | 20%     |
| Upek             | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 40%     |
| Validity Sensors VFS491                                | 1         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 20%     |
| AuthenTec AES1600                                      | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 41        | 74.55%  |
| 1     | 9         | 16.36%  |
| 3     | 3         | 5.45%   |
| 2     | 2         | 3.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 42.86%  |
| Fingerprint reader       | 5         | 23.81%  |
| Communication controller | 3         | 14.29%  |
| Sound                    | 1         | 4.76%   |
| Net/ethernet             | 1         | 4.76%   |
| Modem                    | 1         | 4.76%   |
| Chipcard                 | 1         | 4.76%   |

