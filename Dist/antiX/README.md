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

Total: 76

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | 3000 V100 076346G           | Notebook    | [bb04272723](https://linux-hardware.org/?probe=bb04272723) | Dec 01, 2022 |
| Acer          | Aspire 7520                 | Notebook    | [d2f4caca66](https://linux-hardware.org/?probe=d2f4caca66) | Nov 22, 2022 |
| ASUSTek       | S3N                         | Notebook    | [e4c4a500b8](https://linux-hardware.org/?probe=e4c4a500b8) | Nov 21, 2022 |
| Google        | Candy                       | Notebook    | [5c5ea3b081](https://linux-hardware.org/?probe=5c5ea3b081) | Nov 17, 2022 |
| HP            | Mini 110-3700               | Notebook    | [4e9f54f23c](https://linux-hardware.org/?probe=4e9f54f23c) | Nov 15, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [213d8f5688](https://linux-hardware.org/?probe=213d8f5688) | Nov 13, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| antiX 21       | 28        | 45.9%   |
| antiX 19.2     | 8         | 13.11%  |
| antiX 22       | 6         | 9.84%   |
| antiX 19.3     | 4         | 6.56%   |
| antiX 17.4.1   | 4         | 6.56%   |
| antiX 21-runit | 3         | 4.92%   |
| antiX 19.4     | 2         | 3.28%   |
| antiX 19.1     | 2         | 3.28%   |
| antiX 17.2.1   | 1         | 1.64%   |
| antiX 17.1     | 1         | 1.64%   |
| antiX 17       | 1         | 1.64%   |
| antiX 15       | 1         | 1.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 60        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 14        | 22.95%  |
| 4.9.0-279-antix.1-amd64-smp  | 8         | 13.11%  |
| 5.10.57-antix.1-amd64-smp    | 7         | 11.48%  |
| 4.9.160-antix.2-486-smp      | 4         | 6.56%   |
| 4.9.235-antix.1-amd64-smp    | 3         | 4.92%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 4.92%   |
| 4.9.212-antix.1-486-smp      | 3         | 4.92%   |
| 4.9.0-326-antix.1-amd64-smp  | 3         | 4.92%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 3.28%   |
| 4.9.200-antix.1-486-smp      | 2         | 3.28%   |
| 4.9.0-326-antix.1-486-smp    | 2         | 3.28%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.64%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.64%   |
| 5.10.142-antix.2-amd64-smp   | 1         | 1.64%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 1.64%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.64%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.64%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.64%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.64%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.64%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 27        | 45%     |
| 5.10.57  | 7         | 11.67%  |
| 4.9.212  | 6         | 10%     |
| 4.9.160  | 5         | 8.33%   |
| 4.9.235  | 3         | 5%      |
| 5.10.88  | 2         | 3.33%   |
| 4.9.200  | 2         | 3.33%   |
| 5.14.0   | 1         | 1.67%   |
| 5.10.27  | 1         | 1.67%   |
| 5.10.142 | 1         | 1.67%   |
| 4.9.87   | 1         | 1.67%   |
| 4.19.202 | 1         | 1.67%   |
| 4.19.100 | 1         | 1.67%   |
| 4.19.0   | 1         | 1.67%   |
| 4.10.5   | 1         | 1.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 44        | 73.33%  |
| 5.10    | 11        | 18.33%  |
| 4.19    | 3         | 5%      |
| 5.14    | 1         | 1.67%   |
| 4.10    | 1         | 1.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 51.67%  |
| i686   | 28        | 46.67%  |
| i586   | 1         | 1.67%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 33        | 55%     |
| icewm        | 20        | 33.33%  |
| XFCE         | 4         | 6.67%   |
| jwm          | 1         | 1.67%   |
| herbstluftwm | 1         | 1.67%   |
| GNOME        | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 59        | 98.33%  |
| Tty  | 1         | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 50%     |
| SLiM    | 21        | 35%     |
| LightDM | 5         | 8.33%   |
| SLIMSKI | 3         | 5%      |
| SDDM    | 1         | 1.67%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 27        | 45%     |
| ru_RU   | 6         | 10%     |
| de_DE   | 4         | 6.67%   |
| ja_JP   | 3         | 5%      |
| Unknown | 3         | 5%      |
| sk_SK   | 2         | 3.33%   |
| pt_BR   | 2         | 3.33%   |
| pl_PL   | 2         | 3.33%   |
| en_GB   | 2         | 3.33%   |
| en_AU   | 2         | 3.33%   |
| zh_HK   | 1         | 1.67%   |
| uk_UA   | 1         | 1.67%   |
| nl_NL   | 1         | 1.67%   |
| it_IT   | 1         | 1.67%   |
| es_VE   | 1         | 1.67%   |
| es_MX   | 1         | 1.67%   |
| es_AR   | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 49        | 81.67%  |
| EFI  | 11        | 18.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 51        | 85%     |
| Overlay  | 8         | 13.33%  |
| Reiserfs | 1         | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 47        | 78.33%  |
| GPT     | 11        | 18.33%  |
| Unknown | 2         | 3.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 78.69%  |
| Yes       | 13        | 21.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 61.67%  |
| Yes       | 23        | 38.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 11        | 18.33%  |
| Hewlett-Packard     | 8         | 13.33%  |
| Lenovo              | 6         | 10%     |
| IBM                 | 5         | 8.33%   |
| MSI                 | 3         | 5%      |
| Dell                | 3         | 5%      |
| Acer                | 3         | 5%      |
| Unknown             | 3         | 5%      |
| KOHJINSHA           | 2         | 3.33%   |
| Gigabyte Technology | 2         | 3.33%   |
| Fujitsu             | 2         | 3.33%   |
| Toshiba             | 1         | 1.67%   |
| Samsung Electronics | 1         | 1.67%   |
| Radiant Systems     | 1         | 1.67%   |
| Packard Bell        | 1         | 1.67%   |
| Medion              | 1         | 1.67%   |
| Intel               | 1         | 1.67%   |
| Google              | 1         | 1.67%   |
| Compaq              | 1         | 1.67%   |
| Biostar             | 1         | 1.67%   |
| AZW                 | 1         | 1.67%   |
| Apple               | 1         | 1.67%   |
| AMI                 | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 4         | 6.67%   |
| MSI US Desktop                     | 2         | 3.33%   |
| IBM 260921H                        | 2         | 3.33%   |
| HP Mini 110-3700                   | 2         | 3.33%   |
| Toshiba Satellite 1905             | 1         | 1.67%   |
| Samsung SQ1S                       | 1         | 1.67%   |
| Radiant Systems P845               | 1         | 1.67%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.67%   |
| MSI GE62 7RE                       | 1         | 1.67%   |
| Medion WIM2170                     | 1         | 1.67%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.67%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.67%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 1.67%   |
| Lenovo G550 2958                   | 1         | 1.67%   |
| Lenovo 3000 V100 076346G           | 1         | 1.67%   |
| KOHJINSHA SX series                | 1         | 1.67%   |
| KOHJINSHA SC series                | 1         | 1.67%   |
| Intel D525MW AAE93082-401          | 1         | 1.67%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.67%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.67%   |
| IBM ThinkPad T40 237342G           | 1         | 1.67%   |
| HP t5740                           | 1         | 1.67%   |
| HP Pavilion dv2700                 | 1         | 1.67%   |
| HP Mini 5101                       | 1         | 1.67%   |
| HP EliteBook 8770w                 | 1         | 1.67%   |
| HP EliteBook 2570p                 | 1         | 1.67%   |
| HP All-in-One 24-f0xx              | 1         | 1.67%   |
| Google Candy                       | 1         | 1.67%   |
| Gigabyte F2A85XM-D3H               | 1         | 1.67%   |
| Gigabyte 945GCMX-S2                | 1         | 1.67%   |
| Fujitsu FMVS54EB                   | 1         | 1.67%   |
| Fujitsu FMVNU6G1C                  | 1         | 1.67%   |
| Dell OptiPlex 960                  | 1         | 1.67%   |
| Dell Latitude E6400                | 1         | 1.67%   |
| Dell Latitude 5480                 | 1         | 1.67%   |
| Compaq Tablet PC TC1000            | 1         | 1.67%   |
| Biostar G31-M7 TE                  | 1         | 1.67%   |
| AZW GK mini                        | 1         | 1.67%   |
| ASUS X71SL                         | 1         | 1.67%   |
| ASUS X51RL                         | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 4         | 6.67%   |
| IBM ThinkPad          | 3         | 5%      |
| HP Mini               | 3         | 5%      |
| MSI US                | 2         | 3.33%   |
| Lenovo ThinkPad       | 2         | 3.33%   |
| IBM 260921H           | 2         | 3.33%   |
| HP EliteBook          | 2         | 3.33%   |
| Dell Latitude         | 2         | 3.33%   |
| ASUS VivoBook         | 2         | 3.33%   |
| Acer Aspire           | 2         | 3.33%   |
| Toshiba Satellite     | 1         | 1.67%   |
| Samsung SQ1S          | 1         | 1.67%   |
| Radiant Systems P845  | 1         | 1.67%   |
| Packard Bell EasyNote | 1         | 1.67%   |
| MSI GE62              | 1         | 1.67%   |
| Medion WIM2170        | 1         | 1.67%   |
| Lenovo ThinkCentre    | 1         | 1.67%   |
| Lenovo G550           | 1         | 1.67%   |
| Lenovo 3000           | 1         | 1.67%   |
| KOHJINSHA SX          | 1         | 1.67%   |
| KOHJINSHA SC          | 1         | 1.67%   |
| Intel D525MW          | 1         | 1.67%   |
| HP t5740              | 1         | 1.67%   |
| HP Pavilion           | 1         | 1.67%   |
| HP All-in-One         | 1         | 1.67%   |
| Google Candy          | 1         | 1.67%   |
| Gigabyte F2A85XM-D3H  | 1         | 1.67%   |
| Gigabyte 945GCMX-S2   | 1         | 1.67%   |
| Fujitsu FMVS54EB      | 1         | 1.67%   |
| Fujitsu FMVNU6G1C     | 1         | 1.67%   |
| Dell OptiPlex         | 1         | 1.67%   |
| Compaq Tablet         | 1         | 1.67%   |
| Biostar G31-M7        | 1         | 1.67%   |
| AZW GK                | 1         | 1.67%   |
| ASUS X71SL            | 1         | 1.67%   |
| ASUS X51RL            | 1         | 1.67%   |
| ASUS S3N              | 1         | 1.67%   |
| ASUS P5KPL            | 1         | 1.67%   |
| ASUS A8R-MVP          | 1         | 1.67%   |
| ASUS A3L              | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 9         | 15%     |
| 2007    | 9         | 15%     |
| 2009    | 8         | 13.33%  |
| 2012    | 4         | 6.67%   |
| 2011    | 4         | 6.67%   |
| 2021    | 3         | 5%      |
| 2005    | 3         | 5%      |
| 2003    | 3         | 5%      |
| 2018    | 2         | 3.33%   |
| 2013    | 2         | 3.33%   |
| 2010    | 2         | 3.33%   |
| 2004    | 2         | 3.33%   |
| 1999    | 2         | 3.33%   |
| 2022    | 1         | 1.67%   |
| 2020    | 1         | 1.67%   |
| 2019    | 1         | 1.67%   |
| 2017    | 1         | 1.67%   |
| 2016    | 1         | 1.67%   |
| 2006    | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 42        | 70%     |
| Desktop    | 14        | 23.33%  |
| Mini pc    | 3         | 5%      |
| All in one | 1         | 1.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 60        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 98.33%  |
| Yes  | 1         | 1.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 14        | 23.33%  |
| 1.01-2.0   | 10        | 16.67%  |
| 0.51-1.0   | 10        | 16.67%  |
| 2.01-3.0   | 8         | 13.33%  |
| 0.01-0.5   | 5         | 8.33%   |
| 4.01-8.0   | 4         | 6.67%   |
| 32.01-64.0 | 4         | 6.67%   |
| 8.01-16.0  | 3         | 5%      |
| 16.01-24.0 | 2         | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 25        | 41.67%  |
| 0.51-1.0 | 21        | 35%     |
| 1.01-2.0 | 8         | 13.33%  |
| 2.01-3.0 | 5         | 8.33%   |
| 4.01-8.0 | 1         | 1.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 43        | 71.67%  |
| 2      | 9         | 15%     |
| 3      | 4         | 6.67%   |
| 0      | 3         | 5%      |
| 4      | 1         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 58.33%  |
| Yes       | 25        | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 88.33%  |
| No        | 7         | 11.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 80%     |
| No        | 12        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 65%     |
| Yes       | 21        | 35%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 12        | 20%     |
| Hong Kong   | 9         | 15%     |
| Russia      | 8         | 13.33%  |
| Germany     | 6         | 10%     |
| Japan       | 3         | 5%      |
| Slovakia    | 2         | 3.33%   |
| Poland      | 2         | 3.33%   |
| Netherlands | 2         | 3.33%   |
| Brazil      | 2         | 3.33%   |
| Australia   | 2         | 3.33%   |
| Ukraine     | 1         | 1.67%   |
| UK          | 1         | 1.67%   |
| Mexico      | 1         | 1.67%   |
| Kenya       | 1         | 1.67%   |
| Kazakhstan  | 1         | 1.67%   |
| Italy       | 1         | 1.67%   |
| Hungary     | 1         | 1.67%   |
| Greece      | 1         | 1.67%   |
| France      | 1         | 1.67%   |
| Denmark     | 1         | 1.67%   |
| Chile       | 1         | 1.67%   |
| Argentina   | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 7         | 11.48%  |
| Sydney                    | 2         | 3.28%   |
| St Petersburg             | 2         | 3.28%   |
| Moscow                    | 2         | 3.28%   |
| Bratislava                | 2         | 3.28%   |
| Zagnansk                  | 1         | 1.64%   |
| Yuzhno-Sakhalinsk         | 1         | 1.64%   |
| Yokohama                  | 1         | 1.64%   |
| Whitney                   | 1         | 1.64%   |
| Violes                    | 1         | 1.64%   |
| Toms River                | 1         | 1.64%   |
| Sheung Shui               | 1         | 1.64%   |
| Schloss Holte-Stukenbrock | 1         | 1.64%   |
| Santiago                  | 1         | 1.64%   |
| Salto                     | 1         | 1.64%   |
| Rotterdam                 | 1         | 1.64%   |
| Reutlingen                | 1         | 1.64%   |
| Portland                  | 1         | 1.64%   |
| Otwock                    | 1         | 1.64%   |
| Nova Londrina             | 1         | 1.64%   |
| Norden                    | 1         | 1.64%   |
| Neyagawa                  | 1         | 1.64%   |
| Nairobi                   | 1         | 1.64%   |
| Mittegrossefehn           | 1         | 1.64%   |
| Mechanicsburg             | 1         | 1.64%   |
| Mason                     | 1         | 1.64%   |
| Maidstone                 | 1         | 1.64%   |
| Kazan’                  | 1         | 1.64%   |
| Karaganda                 | 1         | 1.64%   |
| Kagoshima                 | 1         | 1.64%   |
| Jonesboro                 | 1         | 1.64%   |
| Inveruno                  | 1         | 1.64%   |
| Houston                   | 1         | 1.64%   |
| Hobbs                     | 1         | 1.64%   |
| Heraklion                 | 1         | 1.64%   |
| Hagenbach                 | 1         | 1.64%   |
| Greenville                | 1         | 1.64%   |
| Godley                    | 1         | 1.64%   |
| Frankfurt am Main         | 1         | 1.64%   |
| Elektrostal               | 1         | 1.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 16.67%  |
| Seagate             | 12        | 12     | 16.67%  |
| Hitachi             | 12        | 13     | 16.67%  |
| Samsung Electronics | 7         | 8      | 9.72%   |
| Toshiba             | 5         | 5      | 6.94%   |
| Unknown             | 4         | 4      | 5.56%   |
| Kingston            | 2         | 2      | 2.78%   |
| BHT                 | 2         | 3      | 2.78%   |
| Zheino              | 1         | 1      | 1.39%   |
| Unknown (CF)        | 1         | 1      | 1.39%   |
| Transcend           | 1         | 1      | 1.39%   |
| SanDisk             | 1         | 1      | 1.39%   |
| RECADATA            | 1         | 1      | 1.39%   |
| OCZ                 | 1         | 1      | 1.39%   |
| Maxtor              | 1         | 1      | 1.39%   |
| Intel               | 1         | 1      | 1.39%   |
| IBM/Hitachi         | 1         | 1      | 1.39%   |
| HGST                | 1         | 1      | 1.39%   |
| Hewlett-Packard     | 1         | 1      | 1.39%   |
| Fujitsu             | 1         | 1      | 1.39%   |
| Crucial             | 1         | 1      | 1.39%   |
| China               | 1         | 1      | 1.39%   |
| ASUS-PHISON         | 1         | 1      | 1.39%   |
| Unknown             | 1         | 1      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB               | 2         | 2.7%    |
| Hitachi HTS723232A7A364 320GB           | 2         | 2.7%    |
| Hitachi HTS548040M9AT00 40GB            | 2         | 2.7%    |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 1.35%   |
| WDC WD8088AADS-00M2B0 809GB             | 1         | 1.35%   |
| WDC WD800JB-00ETA0 80GB                 | 1         | 1.35%   |
| WDC WD800AAJS-75M0A0 80GB               | 1         | 1.35%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.35%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.35%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.35%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1.35%   |
| WDC WD205BA 21GB                        | 1         | 1.35%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 1.35%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 1.35%   |
| WDC WD1600AAJS-00PSA0 160GB             | 1         | 1.35%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.35%   |
| WDC WD10SPZX-80Z10T2 1TB                | 1         | 1.35%   |
| Unknown SR64G  64GB                     | 1         | 1.35%   |
| Unknown SD/MMC/MS PRO 8GB               | 1         | 1.35%   |
| Unknown HAG2e  16GB                     | 1         | 1.35%   |
| Unknown 2GB ATA Flash Disk              | 1         | 1.35%   |
| Unknown (CF) Card 16GB SSD              | 1         | 1.35%   |
| Transcend SSD 2GB                       | 1         | 1.35%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.35%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.35%   |
| Toshiba MQ01ABD050V -63 500GB           | 1         | 1.35%   |
| Toshiba MK2576GSX 250GB                 | 1         | 1.35%   |
| Toshiba DT01ACA100 1TB                  | 1         | 1.35%   |
| Seagate ST9320325AS 320GB               | 1         | 1.35%   |
| Seagate ST9250421ASG 250GB              | 1         | 1.35%   |
| Seagate ST9160411AS 160GB               | 1         | 1.35%   |
| Seagate ST9160314AS 160GB               | 1         | 1.35%   |
| Seagate ST9160310AS 160GB               | 1         | 1.35%   |
| Seagate ST9160301AS 160GB               | 1         | 1.35%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 1.35%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1.35%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1.35%   |
| Seagate ST3320620AS 320GB               | 1         | 1.35%   |
| Seagate ST3320413CS 320GB               | 1         | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 1.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 25%     |
| Seagate             | 12        | 12     | 25%     |
| Hitachi             | 12        | 13     | 25%     |
| Samsung Electronics | 4         | 5      | 8.33%   |
| Toshiba             | 3         | 3      | 6.25%   |
| Unknown             | 2         | 2      | 4.17%   |
| IBM/Hitachi         | 1         | 1      | 2.08%   |
| HGST                | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 13.64%  |
| Toshiba             | 2         | 2      | 9.09%   |
| Kingston            | 2         | 2      | 9.09%   |
| BHT                 | 2         | 3      | 9.09%   |
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

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 42        | 51     | 64.62%  |
| SSD  | 21        | 23     | 32.31%  |
| MMC  | 2         | 2      | 3.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 73     | 94.92%  |
| MMC  | 2         | 2      | 3.39%   |
| SAS  | 1         | 1      | 1.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 56        | 67     | 88.89%  |
| 0.51-1.0   | 6         | 6      | 9.52%   |
| 1.01-2.0   | 1         | 1      | 1.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 18        | 29.51%  |
| 101-250    | 17        | 27.87%  |
| 51-100     | 9         | 14.75%  |
| 21-50      | 8         | 13.11%  |
| 251-500    | 4         | 6.56%   |
| 501-1000   | 3         | 4.92%   |
| 1001-2000  | 1         | 1.64%   |
| Unknown    | 1         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 48        | 80%     |
| 21-50    | 5         | 8.33%   |
| 101-250  | 3         | 5%      |
| 51-100   | 2         | 3.33%   |
| 501-1000 | 1         | 1.67%   |
| Unknown  | 1         | 1.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD8088AADS-00M2B0 809GB     | 1         | 1      | 4.35%   |
| WDC WD800JB-00ETA0 80GB         | 1         | 1      | 4.35%   |
| WDC WD800AAJS-75M0A0 80GB       | 1         | 1      | 4.35%   |
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 4.35%   |
| WDC WD2500BEVT-22ZCT0 250GB     | 1         | 1      | 4.35%   |
| WDC WD205BA 21GB                | 1         | 1      | 4.35%   |
| Seagate ST9320325AS 320GB       | 1         | 1      | 4.35%   |
| Seagate ST9160314AS 160GB       | 1         | 1      | 4.35%   |
| Seagate ST9160310AS 160GB       | 1         | 1      | 4.35%   |
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 4.35%   |
| Seagate ST3320620AS 320GB       | 1         | 1      | 4.35%   |
| Seagate ST3320413CS 320GB       | 1         | 1      | 4.35%   |
| SanDisk sandisk120 120GB SSD    | 1         | 1      | 4.35%   |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 4.35%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 4.35%   |
| Hitachi HTS721060G9AT00 64GB    | 1         | 1      | 4.35%   |
| Hitachi HTS548040M9AT00 40GB    | 1         | 1      | 4.35%   |
| Hitachi HTS543225A7A384 250GB   | 1         | 1      | 4.35%   |
| Hitachi HTS542525K9SA00 250GB   | 1         | 1      | 4.35%   |
| Hitachi HTS541612J9SA00 120GB   | 1         | 1      | 4.35%   |
| Hitachi HTC426040G8CE00 40GB    | 1         | 1      | 4.35%   |
| Hitachi DK23AA-60 6GB           | 1         | 1      | 4.35%   |
| China M.2 SSD 128GB             | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 39.13%  |
| WDC     | 6         | 6      | 26.09%  |
| Seagate | 6         | 6      | 26.09%  |
| SanDisk | 1         | 1      | 4.35%   |
| China   | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 9         | 9      | 42.86%  |
| WDC     | 6         | 6      | 28.57%  |
| Seagate | 6         | 6      | 28.57%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 21     | 91.3%   |
| SSD  | 2         | 2      | 8.7%    |

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
| Works    | 34        | 44     | 52.31%  |
| Malfunc  | 23        | 23     | 35.38%  |
| Detected | 8         | 9      | 12.31%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 47        | 73.44%  |
| Nvidia                           | 4         | 6.25%   |
| AMD                              | 4         | 6.25%   |
| ASMedia Technology               | 3         | 4.69%   |
| Silicon Integrated Systems [SiS] | 2         | 3.13%   |
| VIA Technologies                 | 1         | 1.56%   |
| ULi Electronics                  | 1         | 1.56%   |
| Silicon Image                    | 1         | 1.56%   |
| JMicron Technology               | 1         | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 8.64%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 4.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 4.94%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 4.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 3.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 3.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 3.7%    |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 3         | 3.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 3.7%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 2.47%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 2.47%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 2.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 2.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.47%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.23%   |
| ULi ULi M5288 SATA                                                             | 1         | 1.23%   |
| ULi M5229 IDE                                                                  | 1         | 1.23%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.23%   |
| Nvidia nForce3 Serial ATA Controller                                           | 1         | 1.23%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.23%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 1.23%   |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 1.23%   |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                     | 1         | 1.23%   |
| Nvidia CK804 Serial ATA Controller                                             | 1         | 1.23%   |
| Nvidia CK804 IDE                                                               | 1         | 1.23%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.23%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.23%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.23%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.23%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1         | 1.23%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| IDE  | 36        | 52.17%  |
| SATA | 29        | 42.03%  |
| RAID | 4         | 5.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 52        | 86.67%  |
| AMD          | 7         | 11.67%  |
| GenuineTMx86 | 1         | 1.67%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 4         | 6.67%   |
| Intel Pentium M processor 1.60GHz           | 2         | 3.33%   |
| Intel Pentium M processor 1.00GHz           | 2         | 3.33%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 3.33%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 3.33%   |
| Intel Celeron (Mendocino)                   | 2         | 3.33%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 3.33%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 3.33%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 3.33%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2         | 3.33%   |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1         | 1.67%   |
| Intel Pentium M processor 1600MHz           | 1         | 1.67%   |
| Intel Pentium M processor 1.86GHz           | 1         | 1.67%   |
| Intel Pentium II (Deschutes)                | 1         | 1.67%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 1.67%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.67%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 1.67%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.67%   |
| Intel Genuine processor 800MHz              | 1         | 1.67%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.67%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.67%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.67%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.67%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.67%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.67%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1         | 1.67%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz        | 1         | 1.67%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz        | 1         | 1.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.67%   |
| Intel Celeron M processor 900MHz            | 1         | 1.67%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1         | 1.67%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz | 1         | 1.67%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 1         | 1.67%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1         | 1.67%   |
| Intel Celeron CPU 540 @ 1.86GHz             | 1         | 1.67%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 1         | 1.67%   |
| Intel Atom CPU D525 @ 1.80GHz               | 1         | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 12        | 20%     |
| Intel Celeron           | 7         | 11.67%  |
| Intel Pentium M         | 6         | 10%     |
| Intel Core 2 Duo        | 6         | 10%     |
| Other                   | 4         | 6.67%   |
| Intel Core i7           | 4         | 6.67%   |
| Intel Core i5           | 3         | 5%      |
| Intel Pentium Dual      | 2         | 3.33%   |
| Intel Genuine           | 2         | 3.33%   |
| AMD Athlon 64 X2        | 2         | 3.33%   |
| Intel Xeon              | 1         | 1.67%   |
| Intel Pentium Dual-Core | 1         | 1.67%   |
| Intel Pentium 4         | 1         | 1.67%   |
| Intel Pentium           | 1         | 1.67%   |
| Intel Core i3           | 1         | 1.67%   |
| Intel Core 2 Quad       | 1         | 1.67%   |
| Intel Celeron M         | 1         | 1.67%   |
| Intel Celeron Dual-Core | 1         | 1.67%   |
| AMD Sempron             | 1         | 1.67%   |
| AMD E2                  | 1         | 1.67%   |
| AMD Athlon 64           | 1         | 1.67%   |
| AMD A6                  | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 45%     |
| 2      | 24        | 40%     |
| 4      | 7         | 11.67%  |
| 6      | 2         | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 63.33%  |
| 2      | 22        | 36.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 37        | 61.67%  |
| 32-bit         | 23        | 38.33%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x106c2    | 8         | 13.33%  |
| 0x1067a    | 6         | 10%     |
| 0x6fd      | 5         | 8.33%   |
| Unknown    | 5         | 8.33%   |
| 0x6d6      | 4         | 6.67%   |
| 0x6d8      | 3         | 5%      |
| 0x106ca    | 3         | 5%      |
| 0xa0671    | 2         | 3.33%   |
| 0x66a      | 2         | 3.33%   |
| 0x306a9    | 2         | 3.33%   |
| 0x30678    | 2         | 3.33%   |
| 0x206a7    | 2         | 3.33%   |
| 0xf24      | 1         | 1.67%   |
| 0x906e9    | 1         | 1.67%   |
| 0x806e9    | 1         | 1.67%   |
| 0x706a8    | 1         | 1.67%   |
| 0x706a1    | 1         | 1.67%   |
| 0x6e8      | 1         | 1.67%   |
| 0x695      | 1         | 1.67%   |
| 0x652      | 1         | 1.67%   |
| 0x306c3    | 1         | 1.67%   |
| 0x30661    | 1         | 1.67%   |
| 0x20655    | 1         | 1.67%   |
| 0x10676    | 1         | 1.67%   |
| 0x10661    | 1         | 1.67%   |
| 0x07030106 | 1         | 1.67%   |
| 0x06006705 | 1         | 1.67%   |
| 0x06001116 | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Bonnell       | 12        | 20%     |
| P6            | 9         | 15%     |
| Penryn        | 7         | 11.67%  |
| Core          | 6         | 10%     |
| Unknown       | 6         | 10%     |
| K8 Hammer     | 4         | 6.67%   |
| Silvermont    | 2         | 3.33%   |
| SandyBridge   | 2         | 3.33%   |
| KabyLake      | 2         | 3.33%   |
| IvyBridge     | 2         | 3.33%   |
| Goldmont plus | 2         | 3.33%   |
| Westmere      | 1         | 1.67%   |
| Puma          | 1         | 1.67%   |
| Piledriver    | 1         | 1.67%   |
| NetBurst      | 1         | 1.67%   |
| Haswell       | 1         | 1.67%   |
| Excavator     | 1         | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 33        | 54.1%   |
| AMD                              | 13        | 21.31%  |
| Nvidia                           | 12        | 19.67%  |
| Neomagic                         | 2         | 3.28%   |
| Silicon Integrated Systems [SiS] | 1         | 1.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 7         | 9.59%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 6.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 4.11%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 4.11%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 3         | 4.11%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 2.74%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 2.74%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 2.74%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 2.74%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 2.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 2.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 2.74%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 2.74%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.37%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.37%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.37%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.37%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1         | 1.37%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1         | 1.37%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.37%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 1.37%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.37%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.37%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.37%   |
| Intel HD Graphics 630                                                         | 1         | 1.37%   |
| Intel HD Graphics 620                                                         | 1         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.37%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.37%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.37%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 1.37%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.37%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.37%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 1.37%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 1         | 1.37%   |
| AMD RV515 [Radeon X1300/X1550]                                                | 1         | 1.37%   |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 1.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 50%     |
| 1 x Nvidia     | 11        | 18.33%  |
| 1 x AMD        | 9         | 15%     |
| 2 x AMD        | 4         | 6.67%   |
| Other          | 2         | 3.33%   |
| 1 x Neomagic   | 2         | 3.33%   |
| 1 x SiS        | 1         | 1.67%   |
| Intel + Nvidia | 1         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 49        | 81.67%  |
| Unknown     | 8         | 13.33%  |
| Proprietary | 3         | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 29        | 48.33%  |
| Unknown    | 20        | 33.33%  |
| 1.01-2.0   | 8         | 13.33%  |
| 5.01-6.0   | 1         | 1.67%   |
| 3.01-4.0   | 1         | 1.67%   |
| 0.51-1.0   | 1         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 20%     |
| Samsung Electronics     | 5         | 12.5%   |
| LG Display              | 5         | 12.5%   |
| HannStar                | 3         | 7.5%    |
| Goldstar                | 3         | 7.5%    |
| Acer                    | 3         | 7.5%    |
| LG Philips              | 2         | 5%      |
| Vizio                   | 1         | 2.5%    |
| Lenovo                  | 1         | 2.5%    |
| HJW                     | 1         | 2.5%    |
| Hewlett-Packard         | 1         | 2.5%    |
| Dell                    | 1         | 2.5%    |
| CPT                     | 1         | 2.5%    |
| Chimei Innolux          | 1         | 2.5%    |
| Chi Mei Optoelectronics | 1         | 2.5%    |
| BOE                     | 1         | 2.5%    |
| Arnos Instruments       | 1         | 2.5%    |
| Apple                   | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 2         | 5%      |
| Vizio E280i-B1 VIZ1002 1360x768 607x345mm 27.5-inch                      | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 2.5%    |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 2.5%    |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 2.5%    |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 2.5%    |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 2.5%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 2.5%    |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 2.5%    |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.5%    |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 2.5%    |
| Hewlett-Packard Contino HPN4018 1920x1080 527x296mm 23.8-inch            | 1         | 2.5%    |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch                 | 1         | 2.5%    |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 1         | 2.5%    |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 2.5%    |
| Goldstar M2250D GSM57EF 1920x1080 477x268mm 21.5-inch                    | 1         | 2.5%    |
| Goldstar M198WA GSM4B36 1440x900 410x260mm 19.1-inch                     | 1         | 2.5%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 1         | 2.5%    |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 1         | 2.5%    |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 2.5%    |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO3214 1280x800 261x163mm 12.1-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 2.5%    |
| Arnos Instruments F-417 AIC7450 1280x1024 338x270mm 17.0-inch            | 1         | 2.5%    |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch                   | 1         | 2.5%    |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                        | 1         | 2.5%    |
| Acer V243H ACR00A3 1920x1080 531x298mm 24.0-inch                         | 1         | 2.5%    |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                        | 1         | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 10        | 25.64%  |
| 1920x1080 (FHD)  | 9         | 23.08%  |
| 1280x800 (WXGA)  | 6         | 15.38%  |
| 1024x600         | 6         | 15.38%  |
| 1440x900 (WXGA+) | 4         | 10.26%  |
| 1600x1200        | 2         | 5.13%   |
| 2560x1080        | 1         | 2.56%   |
| 1280x1024 (SXGA) | 1         | 2.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 6         | 15%     |
| 10     | 5         | 12.5%   |
| 21     | 4         | 10%     |
| 17     | 4         | 10%     |
| 14     | 4         | 10%     |
| 13     | 4         | 10%     |
| 12     | 2         | 5%      |
| 8      | 2         | 5%      |
| 38     | 1         | 2.5%    |
| 34     | 1         | 2.5%    |
| 32     | 1         | 2.5%    |
| 27     | 1         | 2.5%    |
| 24     | 1         | 2.5%    |
| 23     | 1         | 2.5%    |
| 19     | 1         | 2.5%    |
| 18     | 1         | 2.5%    |
| 11     | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 30%     |
| 201-300     | 11        | 27.5%   |
| 401-500     | 6         | 15%     |
| 501-600     | 3         | 7.5%    |
| 351-400     | 3         | 7.5%    |
| 701-800     | 2         | 5%      |
| 101-200     | 2         | 5%      |
| 801-900     | 1         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 24        | 61.54%  |
| 16/10 | 10        | 25.64%  |
| 4/3   | 2         | 5.13%   |
| 5/4   | 1         | 2.56%   |
| 3/2   | 1         | 2.56%   |
| 21/9  | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 6         | 15%     |
| 101-110        | 6         | 15%     |
| 41-50          | 5         | 12.5%   |
| 201-250        | 5         | 12.5%   |
| 71-80          | 2         | 5%      |
| 61-70          | 2         | 5%      |
| 351-500        | 2         | 5%      |
| 1-40           | 2         | 5%      |
| 151-200        | 2         | 5%      |
| 141-150        | 2         | 5%      |
| 131-140        | 2         | 5%      |
| 51-60          | 1         | 2.5%    |
| 301-350        | 1         | 2.5%    |
| 121-130        | 1         | 2.5%    |
| 501-1000       | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 14        | 35.9%   |
| 101-120 | 13        | 33.33%  |
| 121-160 | 11        | 28.21%  |
| 1-50    | 1         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 51        | 83.61%  |
| 0     | 8         | 13.11%  |
| 2     | 2         | 3.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 26        | 27.08%  |
| Realtek Semiconductor            | 24        | 25%     |
| Qualcomm Atheros                 | 17        | 17.71%  |
| Broadcom                         | 10        | 10.42%  |
| Nvidia                           | 4         | 4.17%   |
| Marvell Technology Group         | 3         | 3.13%   |
| Silicon Integrated Systems [SiS] | 2         | 2.08%   |
| Qualcomm Atheros Communications  | 2         | 2.08%   |
| Texas Instruments                | 1         | 1.04%   |
| Ralink Technology                | 1         | 1.04%   |
| Ralink                           | 1         | 1.04%   |
| MediaTek                         | 1         | 1.04%   |
| LSI                              | 1         | 1.04%   |
| Hewlett-Packard                  | 1         | 1.04%   |
| Attansic Technology              | 1         | 1.04%   |
| ASIX Electronics                 | 1         | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 6.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7         | 6.03%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 6         | 5.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 4.31%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 2.59%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 3         | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 2.59%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 2.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 1.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 1.72%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2         | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.72%   |
| Intel Wireless 7260                                                           | 2         | 1.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 1.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.72%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.72%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 1.72%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 1.72%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 2         | 1.72%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.86%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.86%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.86%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.86%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.86%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.86%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 0.86%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.86%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.86%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 0.86%   |
| Nvidia MCP67 Ethernet                                                         | 1         | 0.86%   |
| Nvidia CK8S Ethernet Controller                                               | 1         | 0.86%   |
| Nvidia CK804 Ethernet Controller                                              | 1         | 0.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 39.62%  |
| Qualcomm Atheros                | 15        | 28.3%   |
| Broadcom                        | 7         | 13.21%  |
| Realtek Semiconductor           | 4         | 7.55%   |
| Qualcomm Atheros Communications | 2         | 3.77%   |
| Texas Instruments               | 1         | 1.89%   |
| Ralink Technology               | 1         | 1.89%   |
| Ralink                          | 1         | 1.89%   |
| MediaTek                        | 1         | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 14.81%  |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 5.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 5.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 3.7%    |
| Intel Wireless 7260                                                           | 2         | 3.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 3.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 3.7%    |
| Intel Centrino Ultimate-N 6300                                                | 2         | 3.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 3.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 2         | 3.7%    |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.85%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.85%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.85%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.85%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.85%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.85%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.85%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.85%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.85%   |
| Intel Wireless 3165                                                           | 1         | 1.85%   |
| Intel WiFi Link 5100                                                          | 1         | 1.85%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.85%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.85%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.85%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.85%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 23        | 41.82%  |
| Intel                            | 13        | 23.64%  |
| Broadcom                         | 5         | 9.09%   |
| Nvidia                           | 4         | 7.27%   |
| Qualcomm Atheros                 | 3         | 5.45%   |
| Marvell Technology Group         | 3         | 5.45%   |
| Silicon Integrated Systems [SiS] | 2         | 3.64%   |
| Attansic Technology              | 1         | 1.82%   |
| ASIX Electronics                 | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 12.73%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 10.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 3.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.64%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 3.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 3.64%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 3.64%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 3.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.82%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.82%   |
| Nvidia MCP67 Ethernet                                             | 1         | 1.82%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 1.82%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 1.82%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.82%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.82%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.82%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 1.82%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 1.82%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.82%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.82%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 1.82%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.82%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.82%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 1.82%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 53        | 49.07%  |
| WiFi     | 48        | 44.44%  |
| Modem    | 7         | 6.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 66.13%  |
| Ethernet | 21        | 33.87%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 40        | 66.67%  |
| 1     | 20        | 33.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 88.52%  |
| Yes  | 7         | 11.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Broadcom                | 7         | 33.33%  |
| Intel                   | 6         | 28.57%  |
| IMC Networks            | 2         | 9.52%   |
| Cambridge Silicon Radio | 2         | 9.52%   |
| Realtek Semiconductor   | 1         | 4.76%   |
| Ralink Technology       | 1         | 4.76%   |
| ASUSTek Computer        | 1         | 4.76%   |
| Apple                   | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3         | 14.29%  |
| Intel AX201 Bluetooth                               | 2         | 9.52%   |
| IMC Networks Bluetooth Device                       | 2         | 9.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 9.52%   |
| Broadcom HP Portable SoftSailing                    | 2         | 9.52%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 9.52%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 4.76%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 4.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 4.76%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 4.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 4.76%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 4.76%   |
| Apple Bluetooth Host Controller                     | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 43        | 63.24%  |
| Nvidia                           | 8         | 11.76%  |
| AMD                              | 6         | 8.82%   |
| Silicon Integrated Systems [SiS] | 2         | 2.94%   |
| ESS Technology                   | 2         | 2.94%   |
| Creative Labs                    | 2         | 2.94%   |
| C-Media Electronics              | 2         | 2.94%   |
| VIA Technologies                 | 1         | 1.47%   |
| ULi Electronics                  | 1         | 1.47%   |
| Ensoniq                          | 1         | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 18.31%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 5.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 4.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 4.23%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 2.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.82%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 2.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 2.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.82%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 2.82%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.82%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.41%   |
| ULi Electronics HD Audio Controller                                        | 1         | 1.41%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.41%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 1.41%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.41%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.41%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.41%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.41%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.41%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.41%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.41%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.41%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.41%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1         | 1.41%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1         | 1.41%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 1.41%   |
| C-Media Electronics CM6501                                                 | 1         | 1.41%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.41%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.41%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.41%   |
| AMD High Definition Audio Controller                                       | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 29        | 45.31%  |
| SK hynix            | 7         | 10.94%  |
| Samsung Electronics | 5         | 7.81%   |
| Unknown             | 5         | 7.81%   |
| Kingston            | 4         | 6.25%   |
| Micron Technology   | 3         | 4.69%   |
| Crucial             | 2         | 3.13%   |
| Corsair             | 2         | 3.13%   |
| Unknown (ABCD)      | 1         | 1.56%   |
| Unknown (8A02)      | 1         | 1.56%   |
| tigo                | 1         | 1.56%   |
| Smart               | 1         | 1.56%   |
| Patriot             | 1         | 1.56%   |
| Kllisre             | 1         | 1.56%   |
| Avant               | 1         | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 7.35%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3         | 4.41%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 4.41%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 2.94%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 2.94%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 2         | 2.94%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s         | 2         | 2.94%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 1.47%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 1.47%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1         | 1.47%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                      | 1         | 1.47%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 1.47%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                       | 1         | 1.47%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 1.47%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 1.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 1.47%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1         | 1.47%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                        | 1         | 1.47%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1         | 1.47%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 1.47%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 1.47%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 1         | 1.47%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s   | 1         | 1.47%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 1.47%   |
| tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                     | 1         | 1.47%   |
| Smart RAM SG564568FG8N6KFSQR 2GB DIMM DDR2 800MT/s             | 1         | 1.47%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 1.47%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 1.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 800MT/s        | 1         | 1.47%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.47%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1         | 1.47%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 1.47%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM 1067MT/s              | 1         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 15        | 26.79%  |
| DDR2    | 11        | 19.64%  |
| SDRAM   | 10        | 17.86%  |
| DDR     | 8         | 14.29%  |
| DDR4    | 6         | 10.71%  |
| DRAM    | 3         | 5.36%   |
| Unknown | 2         | 3.57%   |
| LPDDR4  | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 39        | 69.64%  |
| DIMM   | 17        | 30.36%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 17        | 26.56%  |
| 1024  | 16        | 25%     |
| 4096  | 9         | 14.06%  |
| 512   | 8         | 12.5%   |
| 16384 | 4         | 6.25%   |
| 8192  | 4         | 6.25%   |
| 256   | 3         | 4.69%   |
| 64    | 2         | 3.13%   |
| 232   | 1         | 1.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 21        | 36.21%  |
| 1600    | 9         | 15.52%  |
| 667     | 5         | 8.62%   |
| 3200    | 3         | 5.17%   |
| 1067    | 3         | 5.17%   |
| 800     | 3         | 5.17%   |
| 3266    | 2         | 3.45%   |
| 2400    | 2         | 3.45%   |
| 1333    | 2         | 3.45%   |
| 533     | 2         | 3.45%   |
| 2667    | 1         | 1.72%   |
| 975     | 1         | 1.72%   |
| 400     | 1         | 1.72%   |
| 333     | 1         | 1.72%   |
| 266     | 1         | 1.72%   |
| 200     | 1         | 1.72%   |

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
| Chicony Electronics                    | 5         | 17.86%  |
| Cheng Uei Precision Industry (Foxlink) | 4         | 14.29%  |
| Microdia                               | 3         | 10.71%  |
| IMC Networks                           | 3         | 10.71%  |
| Acer                                   | 3         | 10.71%  |
| Suyin                                  | 2         | 7.14%   |
| Pixart Imaging                         | 2         | 7.14%   |
| Sunplus Innovation Technology          | 1         | 3.57%   |
| Silicon Motion                         | 1         | 3.57%   |
| Lite-On Technology                     | 1         | 3.57%   |
| Lenovo                                 | 1         | 3.57%   |
| Importek                               | 1         | 3.57%   |
| Apple                                  | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 7.14%   |
| Microdia Sonix USB 2.0 Camera                           | 2         | 7.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 7.14%   |
| Suyin Lenovo EasyCamera                                 | 1         | 3.57%   |
| Suyin Integrated_Webcam_HD                              | 1         | 3.57%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 3.57%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 3.57%   |
| Microdia Integrated Webcam                              | 1         | 3.57%   |
| Lite-On HP TrueVision HD Camera                         | 1         | 3.57%   |
| Lenovo Integrated Webcam                                | 1         | 3.57%   |
| Importek FJ Camera                                      | 1         | 3.57%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 3.57%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 3.57%   |
| Chicony Integrated HP HD Webcam                         | 1         | 3.57%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 3.57%   |
| Chicony CNF8243 Webcam                                  | 1         | 3.57%   |
| Chicony CNF7050                                         | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 3.57%   |
| Apple Built-in iSight                                   | 1         | 3.57%   |
| Acer Lenovo EasyCamera                                  | 1         | 3.57%   |
| Acer Crystal Eye Webcam                                 | 1         | 3.57%   |
| Acer BisonCam, NB Pro                                   | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 4         | 66.67%  |
| Validity Sensors | 1         | 16.67%  |
| Upek             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 33.33%  |
| AuthenTec AES1600                                      | 2         | 33.33%  |
| Validity Sensors VFS491                                | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |

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
| 0     | 45        | 75%     |
| 1     | 10        | 16.67%  |
| 2     | 3         | 5%      |
| 3     | 2         | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 40.91%  |
| Fingerprint reader       | 6         | 27.27%  |
| Communication controller | 3         | 13.64%  |
| Sound                    | 1         | 4.55%   |
| Net/ethernet             | 1         | 4.55%   |
| Modem                    | 1         | 4.55%   |
| Chipcard                 | 1         | 4.55%   |

