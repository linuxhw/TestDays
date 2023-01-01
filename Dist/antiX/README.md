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

Total: 78

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 2120               | Notebook    | [b52922b482](https://linux-hardware.org/?probe=b52922b482) | Dec 27, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
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
| antiX 21       | 29        | 46.03%  |
| antiX 19.2     | 8         | 12.7%   |
| antiX 22       | 7         | 11.11%  |
| antiX 19.3     | 4         | 6.35%   |
| antiX 17.4.1   | 4         | 6.35%   |
| antiX 21-runit | 3         | 4.76%   |
| antiX 19.4     | 2         | 3.17%   |
| antiX 19.1     | 2         | 3.17%   |
| antiX 17.2.1   | 1         | 1.59%   |
| antiX 17.1     | 1         | 1.59%   |
| antiX 17       | 1         | 1.59%   |
| antiX 15       | 1         | 1.59%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 62        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.0-279-antix.1-486-smp    | 14        | 22.22%  |
| 5.10.57-antix.1-amd64-smp    | 8         | 12.7%   |
| 4.9.0-279-antix.1-amd64-smp  | 8         | 12.7%   |
| 4.9.160-antix.2-486-smp      | 4         | 6.35%   |
| 4.9.235-antix.1-amd64-smp    | 3         | 4.76%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 4.76%   |
| 4.9.212-antix.1-486-smp      | 3         | 4.76%   |
| 4.9.0-326-antix.1-amd64-smp  | 3         | 4.76%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 3.17%   |
| 5.10.142-antix.2-amd64-smp   | 2         | 3.17%   |
| 4.9.200-antix.1-486-smp      | 2         | 3.17%   |
| 4.9.0-326-antix.1-486-smp    | 2         | 3.17%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 1.59%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 1.59%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 1.59%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 1.59%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 1.59%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 1.59%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 1.59%   |
| 4.19.0-222-antix.1-amd64-smp | 1         | 1.59%   |
| 4.10.5-antix.1-486-smp       | 1         | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.0    | 27        | 43.55%  |
| 5.10.57  | 8         | 12.9%   |
| 4.9.212  | 6         | 9.68%   |
| 4.9.160  | 5         | 8.06%   |
| 4.9.235  | 3         | 4.84%   |
| 5.10.88  | 2         | 3.23%   |
| 5.10.142 | 2         | 3.23%   |
| 4.9.200  | 2         | 3.23%   |
| 5.14.0   | 1         | 1.61%   |
| 5.10.27  | 1         | 1.61%   |
| 4.9.87   | 1         | 1.61%   |
| 4.19.202 | 1         | 1.61%   |
| 4.19.100 | 1         | 1.61%   |
| 4.19.0   | 1         | 1.61%   |
| 4.10.5   | 1         | 1.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 44        | 70.97%  |
| 5.10    | 13        | 20.97%  |
| 4.19    | 3         | 4.84%   |
| 5.14    | 1         | 1.61%   |
| 4.10    | 1         | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 53.23%  |
| i686   | 28        | 45.16%  |
| i586   | 1         | 1.61%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 33        | 53.23%  |
| icewm        | 21        | 33.87%  |
| XFCE         | 4         | 6.45%   |
| jwm          | 1         | 1.61%   |
| herbstluftwm | 1         | 1.61%   |
| GNOME        | 1         | 1.61%   |
| fluxbox      | 1         | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 61        | 98.39%  |
| Tty  | 1         | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 32        | 51.61%  |
| SLiM    | 21        | 33.87%  |
| LightDM | 5         | 8.06%   |
| SLIMSKI | 3         | 4.84%   |
| SDDM    | 1         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 27        | 43.55%  |
| ru_RU   | 6         | 9.68%   |
| de_DE   | 4         | 6.45%   |
| ja_JP   | 3         | 4.84%   |
| Unknown | 3         | 4.84%   |
| sk_SK   | 2         | 3.23%   |
| pt_BR   | 2         | 3.23%   |
| pl_PL   | 2         | 3.23%   |
| nl_NL   | 2         | 3.23%   |
| en_GB   | 2         | 3.23%   |
| en_AU   | 2         | 3.23%   |
| zh_HK   | 1         | 1.61%   |
| uk_UA   | 1         | 1.61%   |
| it_IT   | 1         | 1.61%   |
| es_VE   | 1         | 1.61%   |
| es_MX   | 1         | 1.61%   |
| es_AR   | 1         | 1.61%   |
| de_AT   | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 51        | 82.26%  |
| EFI  | 11        | 17.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 53        | 85.48%  |
| Overlay  | 8         | 12.9%   |
| Reiserfs | 1         | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 49        | 79.03%  |
| GPT     | 11        | 17.74%  |
| Unknown | 2         | 3.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 79.37%  |
| Yes       | 13        | 20.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 61.29%  |
| Yes       | 24        | 38.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 11        | 17.74%  |
| Hewlett-Packard     | 8         | 12.9%   |
| Lenovo              | 6         | 9.68%   |
| IBM                 | 5         | 8.06%   |
| Dell                | 4         | 6.45%   |
| MSI                 | 3         | 4.84%   |
| Acer                | 3         | 4.84%   |
| Unknown             | 3         | 4.84%   |
| Toshiba             | 2         | 3.23%   |
| KOHJINSHA           | 2         | 3.23%   |
| Gigabyte Technology | 2         | 3.23%   |
| Fujitsu             | 2         | 3.23%   |
| Samsung Electronics | 1         | 1.61%   |
| Radiant Systems     | 1         | 1.61%   |
| Packard Bell        | 1         | 1.61%   |
| Medion              | 1         | 1.61%   |
| Intel               | 1         | 1.61%   |
| Google              | 1         | 1.61%   |
| Compaq              | 1         | 1.61%   |
| Biostar             | 1         | 1.61%   |
| AZW                 | 1         | 1.61%   |
| Apple               | 1         | 1.61%   |
| AMI                 | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 4         | 6.45%   |
| MSI US Desktop                     | 2         | 3.23%   |
| IBM 260921H                        | 2         | 3.23%   |
| HP Mini 110-3700                   | 2         | 3.23%   |
| Toshiba Satellite C50-A-1HF        | 1         | 1.61%   |
| Toshiba Satellite 1905             | 1         | 1.61%   |
| Samsung SQ1S                       | 1         | 1.61%   |
| Radiant Systems P845               | 1         | 1.61%   |
| Packard Bell EasyNote_MX37-U-057NL | 1         | 1.61%   |
| MSI GE62 7RE                       | 1         | 1.61%   |
| Medion WIM2170                     | 1         | 1.61%   |
| Lenovo ThinkPad X201 3249CTO       | 1         | 1.61%   |
| Lenovo ThinkPad T440p 20AWS3RH00   | 1         | 1.61%   |
| Lenovo ThinkCentre M91p 4480B9U    | 1         | 1.61%   |
| Lenovo G550 2958                   | 1         | 1.61%   |
| Lenovo 3000 V100 076346G           | 1         | 1.61%   |
| KOHJINSHA SX series                | 1         | 1.61%   |
| KOHJINSHA SC series                | 1         | 1.61%   |
| Intel D525MW AAE93082-401          | 1         | 1.61%   |
| IBM ThinkPad T43 2668WEJ           | 1         | 1.61%   |
| IBM ThinkPad T41 2374K50           | 1         | 1.61%   |
| IBM ThinkPad T40 237342G           | 1         | 1.61%   |
| HP t5740                           | 1         | 1.61%   |
| HP Pavilion dv2700                 | 1         | 1.61%   |
| HP Mini 5101                       | 1         | 1.61%   |
| HP EliteBook 8770w                 | 1         | 1.61%   |
| HP EliteBook 2570p                 | 1         | 1.61%   |
| HP All-in-One 24-f0xx              | 1         | 1.61%   |
| Google Candy                       | 1         | 1.61%   |
| Gigabyte F2A85XM-D3H               | 1         | 1.61%   |
| Gigabyte 945GCMX-S2                | 1         | 1.61%   |
| Fujitsu FMVS54EB                   | 1         | 1.61%   |
| Fujitsu FMVNU6G1C                  | 1         | 1.61%   |
| Dell OptiPlex 960                  | 1         | 1.61%   |
| Dell Latitude E6400                | 1         | 1.61%   |
| Dell Latitude 5480                 | 1         | 1.61%   |
| Dell Latitude 2120                 | 1         | 1.61%   |
| Compaq Tablet PC TC1000            | 1         | 1.61%   |
| Biostar G31-M7 TE                  | 1         | 1.61%   |
| AZW GK mini                        | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 4         | 6.45%   |
| IBM ThinkPad          | 3         | 4.84%   |
| HP Mini               | 3         | 4.84%   |
| Dell Latitude         | 3         | 4.84%   |
| Toshiba Satellite     | 2         | 3.23%   |
| MSI US                | 2         | 3.23%   |
| Lenovo ThinkPad       | 2         | 3.23%   |
| IBM 260921H           | 2         | 3.23%   |
| HP EliteBook          | 2         | 3.23%   |
| ASUS VivoBook         | 2         | 3.23%   |
| Acer Aspire           | 2         | 3.23%   |
| Samsung SQ1S          | 1         | 1.61%   |
| Radiant Systems P845  | 1         | 1.61%   |
| Packard Bell EasyNote | 1         | 1.61%   |
| MSI GE62              | 1         | 1.61%   |
| Medion WIM2170        | 1         | 1.61%   |
| Lenovo ThinkCentre    | 1         | 1.61%   |
| Lenovo G550           | 1         | 1.61%   |
| Lenovo 3000           | 1         | 1.61%   |
| KOHJINSHA SX          | 1         | 1.61%   |
| KOHJINSHA SC          | 1         | 1.61%   |
| Intel D525MW          | 1         | 1.61%   |
| HP t5740              | 1         | 1.61%   |
| HP Pavilion           | 1         | 1.61%   |
| HP All-in-One         | 1         | 1.61%   |
| Google Candy          | 1         | 1.61%   |
| Gigabyte F2A85XM-D3H  | 1         | 1.61%   |
| Gigabyte 945GCMX-S2   | 1         | 1.61%   |
| Fujitsu FMVS54EB      | 1         | 1.61%   |
| Fujitsu FMVNU6G1C     | 1         | 1.61%   |
| Dell OptiPlex         | 1         | 1.61%   |
| Compaq Tablet         | 1         | 1.61%   |
| Biostar G31-M7        | 1         | 1.61%   |
| AZW GK                | 1         | 1.61%   |
| ASUS X71SL            | 1         | 1.61%   |
| ASUS X51RL            | 1         | 1.61%   |
| ASUS S3N              | 1         | 1.61%   |
| ASUS P5KPL            | 1         | 1.61%   |
| ASUS A8R-MVP          | 1         | 1.61%   |
| ASUS A3L              | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 9         | 14.52%  |
| 2007    | 9         | 14.52%  |
| 2009    | 8         | 12.9%   |
| 2012    | 4         | 6.45%   |
| 2011    | 4         | 6.45%   |
| 2021    | 3         | 4.84%   |
| 2013    | 3         | 4.84%   |
| 2010    | 3         | 4.84%   |
| 2005    | 3         | 4.84%   |
| 2003    | 3         | 4.84%   |
| 2018    | 2         | 3.23%   |
| 2004    | 2         | 3.23%   |
| 1999    | 2         | 3.23%   |
| 2022    | 1         | 1.61%   |
| 2020    | 1         | 1.61%   |
| 2019    | 1         | 1.61%   |
| 2017    | 1         | 1.61%   |
| 2016    | 1         | 1.61%   |
| 2006    | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 44        | 70.97%  |
| Desktop    | 14        | 22.58%  |
| Mini pc    | 3         | 4.84%   |
| All in one | 1         | 1.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 62        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 61        | 98.39%  |
| Yes  | 1         | 1.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 14        | 22.58%  |
| 1.01-2.0   | 11        | 17.74%  |
| 0.51-1.0   | 10        | 16.13%  |
| 2.01-3.0   | 8         | 12.9%   |
| 4.01-8.0   | 5         | 8.06%   |
| 0.01-0.5   | 5         | 8.06%   |
| 32.01-64.0 | 4         | 6.45%   |
| 8.01-16.0  | 3         | 4.84%   |
| 16.01-24.0 | 2         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 25        | 40.32%  |
| 0.51-1.0 | 22        | 35.48%  |
| 1.01-2.0 | 9         | 14.52%  |
| 2.01-3.0 | 5         | 8.06%   |
| 4.01-8.0 | 1         | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 44        | 70.97%  |
| 2      | 10        | 16.13%  |
| 3      | 4         | 6.45%   |
| 0      | 3         | 4.84%   |
| 4      | 1         | 1.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 58.06%  |
| Yes       | 26        | 41.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 88.71%  |
| No        | 7         | 11.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 80.65%  |
| No        | 12        | 19.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 66.13%  |
| Yes       | 21        | 33.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 12        | 19.35%  |
| Hong Kong   | 9         | 14.52%  |
| Russia      | 8         | 12.9%   |
| Germany     | 6         | 9.68%   |
| Netherlands | 3         | 4.84%   |
| Japan       | 3         | 4.84%   |
| Slovakia    | 2         | 3.23%   |
| Poland      | 2         | 3.23%   |
| Brazil      | 2         | 3.23%   |
| Australia   | 2         | 3.23%   |
| Ukraine     | 1         | 1.61%   |
| UK          | 1         | 1.61%   |
| Mexico      | 1         | 1.61%   |
| Kenya       | 1         | 1.61%   |
| Kazakhstan  | 1         | 1.61%   |
| Italy       | 1         | 1.61%   |
| Hungary     | 1         | 1.61%   |
| Greece      | 1         | 1.61%   |
| France      | 1         | 1.61%   |
| Denmark     | 1         | 1.61%   |
| Chile       | 1         | 1.61%   |
| Austria     | 1         | 1.61%   |
| Argentina   | 1         | 1.61%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Shatin                    | 7         | 11.11%  |
| Sydney                    | 2         | 3.17%   |
| St Petersburg             | 2         | 3.17%   |
| Moscow                    | 2         | 3.17%   |
| Bratislava                | 2         | 3.17%   |
| Zagnansk                  | 1         | 1.59%   |
| Yuzhno-Sakhalinsk         | 1         | 1.59%   |
| Yokohama                  | 1         | 1.59%   |
| Ybbs an der Donau         | 1         | 1.59%   |
| Whitney                   | 1         | 1.59%   |
| Violes                    | 1         | 1.59%   |
| Toms River                | 1         | 1.59%   |
| Sheung Shui               | 1         | 1.59%   |
| Schloss Holte-Stukenbrock | 1         | 1.59%   |
| Santiago                  | 1         | 1.59%   |
| Salto                     | 1         | 1.59%   |
| Rotterdam                 | 1         | 1.59%   |
| Reutlingen                | 1         | 1.59%   |
| Purmerend                 | 1         | 1.59%   |
| Portland                  | 1         | 1.59%   |
| Otwock                    | 1         | 1.59%   |
| Nova Londrina             | 1         | 1.59%   |
| Norden                    | 1         | 1.59%   |
| Neyagawa                  | 1         | 1.59%   |
| Nairobi                   | 1         | 1.59%   |
| Mittegrossefehn           | 1         | 1.59%   |
| Mechanicsburg             | 1         | 1.59%   |
| Mason                     | 1         | 1.59%   |
| Maidstone                 | 1         | 1.59%   |
| Kazan’                  | 1         | 1.59%   |
| Karaganda                 | 1         | 1.59%   |
| Kagoshima                 | 1         | 1.59%   |
| Jonesboro                 | 1         | 1.59%   |
| Inveruno                  | 1         | 1.59%   |
| Houston                   | 1         | 1.59%   |
| Hobbs                     | 1         | 1.59%   |
| Heraklion                 | 1         | 1.59%   |
| Hagenbach                 | 1         | 1.59%   |
| Greenville                | 1         | 1.59%   |
| Godley                    | 1         | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 16.22%  |
| Seagate             | 12        | 12     | 16.22%  |
| Hitachi             | 12        | 13     | 16.22%  |
| Samsung Electronics | 8         | 9      | 10.81%  |
| Toshiba             | 6         | 6      | 8.11%   |
| Unknown             | 4         | 4      | 5.41%   |
| Kingston            | 2         | 2      | 2.7%    |
| BHT                 | 2         | 3      | 2.7%    |
| Zheino              | 1         | 1      | 1.35%   |
| Unknown (CF)        | 1         | 1      | 1.35%   |
| Transcend           | 1         | 1      | 1.35%   |
| SanDisk             | 1         | 1      | 1.35%   |
| RECADATA            | 1         | 1      | 1.35%   |
| OCZ                 | 1         | 1      | 1.35%   |
| Maxtor              | 1         | 1      | 1.35%   |
| Intel               | 1         | 1      | 1.35%   |
| IBM/Hitachi         | 1         | 1      | 1.35%   |
| HGST                | 1         | 1      | 1.35%   |
| Hewlett-Packard     | 1         | 1      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |
| Crucial             | 1         | 1      | 1.35%   |
| China               | 1         | 1      | 1.35%   |
| ASUS-PHISON         | 1         | 1      | 1.35%   |
| Unknown             | 1         | 1      | 1.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 120GB               | 2         | 2.63%   |
| Samsung SSD 750 EVO 120GB               | 2         | 2.63%   |
| Hitachi HTS723232A7A364 320GB           | 2         | 2.63%   |
| Hitachi HTS548040M9AT00 40GB            | 2         | 2.63%   |
| Zheino CHN mSATAM3 128 128GB SSD        | 1         | 1.32%   |
| WDC WD8088AADS-00M2B0 809GB             | 1         | 1.32%   |
| WDC WD800JB-00ETA0 80GB                 | 1         | 1.32%   |
| WDC WD800AAJS-75M0A0 80GB               | 1         | 1.32%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 1.32%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1.32%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.32%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1.32%   |
| WDC WD205BA 21GB                        | 1         | 1.32%   |
| WDC WD2003FZEX-00Z4SA0 2TB              | 1         | 1.32%   |
| WDC WD1600BEVS-22RST0 160GB             | 1         | 1.32%   |
| WDC WD1600AAJS-00PSA0 160GB             | 1         | 1.32%   |
| WDC WD1200BEVE-00A0HT0 120GB            | 1         | 1.32%   |
| WDC WD10SPZX-80Z10T2 1TB                | 1         | 1.32%   |
| Unknown SR64G  64GB                     | 1         | 1.32%   |
| Unknown SD/MMC/MS PRO 64GB              | 1         | 1.32%   |
| Unknown HAG2e  16GB                     | 1         | 1.32%   |
| Unknown 2GB ATA Flash Disk              | 1         | 1.32%   |
| Unknown (CF) Card 16GB SSD              | 1         | 1.32%   |
| Transcend SSD 2GB                       | 1         | 1.32%   |
| Toshiba THNSNJ256G8NY 256GB SSD         | 1         | 1.32%   |
| Toshiba THNS128GG4BAAA-NonFDE 128GB SSD | 1         | 1.32%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.32%   |
| Toshiba MQ01ABD050V -63 500GB           | 1         | 1.32%   |
| Toshiba MK2576GSX 250GB                 | 1         | 1.32%   |
| Toshiba DT01ACA100 1TB                  | 1         | 1.32%   |
| Seagate ST9320325AS 320GB               | 1         | 1.32%   |
| Seagate ST9250421ASG 250GB              | 1         | 1.32%   |
| Seagate ST9160411AS 160GB               | 1         | 1.32%   |
| Seagate ST9160314AS 160GB               | 1         | 1.32%   |
| Seagate ST9160310AS 160GB               | 1         | 1.32%   |
| Seagate ST9160301AS 160GB               | 1         | 1.32%   |
| Seagate ST500LM030-1RK17D 500GB         | 1         | 1.32%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1.32%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1.32%   |
| Seagate ST3320620AS 320GB               | 1         | 1.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 24.49%  |
| Seagate             | 12        | 12     | 24.49%  |
| Hitachi             | 12        | 13     | 24.49%  |
| Toshiba             | 4         | 4      | 8.16%   |
| Samsung Electronics | 4         | 5      | 8.16%   |
| Unknown             | 2         | 2      | 4.08%   |
| IBM/Hitachi         | 1         | 1      | 2.04%   |
| HGST                | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 17.39%  |
| Toshiba             | 2         | 2      | 8.7%    |
| Kingston            | 2         | 2      | 8.7%    |
| BHT                 | 2         | 3      | 8.7%    |
| Zheino              | 1         | 1      | 4.35%   |
| Unknown (CF)        | 1         | 1      | 4.35%   |
| Transcend           | 1         | 1      | 4.35%   |
| SanDisk             | 1         | 1      | 4.35%   |
| RECADATA            | 1         | 1      | 4.35%   |
| OCZ                 | 1         | 1      | 4.35%   |
| Maxtor              | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| Hewlett-Packard     | 1         | 1      | 4.35%   |
| Crucial             | 1         | 1      | 4.35%   |
| China               | 1         | 1      | 4.35%   |
| ASUS-PHISON         | 1         | 1      | 4.35%   |
| Unknown             | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 52     | 64.18%  |
| SSD  | 22        | 24     | 32.84%  |
| MMC  | 2         | 2      | 2.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 58        | 75     | 95.08%  |
| MMC  | 2         | 2      | 3.28%   |
| SAS  | 1         | 1      | 1.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 69     | 89.23%  |
| 0.51-1.0   | 6         | 6      | 9.23%   |
| 1.01-2.0   | 1         | 1      | 1.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 30.16%  |
| 1-20       | 18        | 28.57%  |
| 51-100     | 9         | 14.29%  |
| 21-50      | 8         | 12.7%   |
| 251-500    | 4         | 6.35%   |
| 501-1000   | 3         | 4.76%   |
| 1001-2000  | 1         | 1.59%   |
| Unknown    | 1         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 49        | 79.03%  |
| 21-50    | 6         | 9.68%   |
| 101-250  | 3         | 4.84%   |
| 51-100   | 2         | 3.23%   |
| 501-1000 | 1         | 1.61%   |
| Unknown  | 1         | 1.61%   |

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
| Works    | 36        | 46     | 53.73%  |
| Malfunc  | 23        | 23     | 34.33%  |
| Detected | 8         | 9      | 11.94%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 49        | 74.24%  |
| Nvidia                           | 4         | 6.06%   |
| AMD                              | 4         | 6.06%   |
| ASMedia Technology               | 3         | 4.55%   |
| Silicon Integrated Systems [SiS] | 2         | 3.03%   |
| VIA Technologies                 | 1         | 1.52%   |
| ULi Electronics                  | 1         | 1.52%   |
| Silicon Image                    | 1         | 1.52%   |
| JMicron Technology               | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 8.43%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5         | 6.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 4.82%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 4.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 3.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 3.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 3.61%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 3         | 3.61%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 3.61%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 3.61%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 2         | 2.41%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 2.41%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 2         | 2.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 2.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.41%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.2%    |
| ULi ULi M5288 SATA                                                             | 1         | 1.2%    |
| ULi M5229 IDE                                                                  | 1         | 1.2%    |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.2%    |
| Nvidia nForce3 Serial ATA Controller                                           | 1         | 1.2%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 1.2%    |
| Nvidia MCP67 IDE Controller                                                    | 1         | 1.2%    |
| Nvidia MCP67 AHCI Controller                                                   | 1         | 1.2%    |
| Nvidia CK8S Parallel ATA Controller (v2.5)                                     | 1         | 1.2%    |
| Nvidia CK804 Serial ATA Controller                                             | 1         | 1.2%    |
| Nvidia CK804 IDE                                                               | 1         | 1.2%    |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.2%    |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.2%    |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.2%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 1         | 1.2%    |
| Intel 82801DB (ICH4) IDE Controller                                            | 1         | 1.2%    |
| Intel 82801BA IDE U100 Controller                                              | 1         | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| IDE  | 36        | 50.7%   |
| SATA | 31        | 43.66%  |
| RAID | 4         | 5.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 54        | 87.1%   |
| AMD          | 7         | 11.29%  |
| GenuineTMx86 | 1         | 1.61%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 4         | 6.45%   |
| Intel Pentium M processor 1.60GHz           | 2         | 3.23%   |
| Intel Pentium M processor 1.00GHz           | 2         | 3.23%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz        | 2         | 3.23%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 3.23%   |
| Intel Celeron (Mendocino)                   | 2         | 3.23%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 3.23%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 3.23%   |
| Intel Atom CPU N280 @ 1.66GHz               | 2         | 3.23%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz     | 2         | 3.23%   |
| Intel Xeon CPU L5410 @ 2.33GHz              | 1         | 1.61%   |
| Intel Pentium M processor 1600MHz           | 1         | 1.61%   |
| Intel Pentium M processor 1.86GHz           | 1         | 1.61%   |
| Intel Pentium II (Deschutes)                | 1         | 1.61%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1         | 1.61%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.61%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 1.61%   |
| Intel Pentium 4 CPU 2.00GHz                 | 1         | 1.61%   |
| Intel Genuine processor 800MHz              | 1         | 1.61%   |
| Intel Genuine CPU T2400 @ 1.83GHz           | 1         | 1.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.61%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.61%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.61%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 1.61%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 1.61%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.61%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 1.61%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1         | 1.61%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz        | 1         | 1.61%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz        | 1         | 1.61%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.61%   |
| Intel Celeron M processor 900MHz            | 1         | 1.61%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1         | 1.61%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz | 1         | 1.61%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 1         | 1.61%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1         | 1.61%   |
| Intel Celeron CPU 540 @ 1.86GHz             | 1         | 1.61%   |
| Intel Atom CPU N550 @ 1.50GHz               | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 13        | 20.97%  |
| Intel Celeron           | 7         | 11.29%  |
| Intel Pentium M         | 6         | 9.68%   |
| Intel Core 2 Duo        | 6         | 9.68%   |
| Other                   | 4         | 6.45%   |
| Intel Core i7           | 4         | 6.45%   |
| Intel Core i5           | 3         | 4.84%   |
| Intel Pentium Dual      | 2         | 3.23%   |
| Intel Genuine           | 2         | 3.23%   |
| Intel Core i3           | 2         | 3.23%   |
| AMD Athlon 64 X2        | 2         | 3.23%   |
| Intel Xeon              | 1         | 1.61%   |
| Intel Pentium Dual-Core | 1         | 1.61%   |
| Intel Pentium 4         | 1         | 1.61%   |
| Intel Pentium           | 1         | 1.61%   |
| Intel Core 2 Quad       | 1         | 1.61%   |
| Intel Celeron M         | 1         | 1.61%   |
| Intel Celeron Dual-Core | 1         | 1.61%   |
| AMD Sempron             | 1         | 1.61%   |
| AMD E2                  | 1         | 1.61%   |
| AMD Athlon 64           | 1         | 1.61%   |
| AMD A6                  | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 43.55%  |
| 2      | 26        | 41.94%  |
| 4      | 7         | 11.29%  |
| 6      | 2         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 61.29%  |
| 2      | 24        | 38.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 39        | 62.9%   |
| 32-bit         | 23        | 37.1%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x106c2    | 8         | 12.9%   |
| 0x1067a    | 6         | 9.68%   |
| 0x6fd      | 5         | 8.06%   |
| Unknown    | 5         | 8.06%   |
| 0x6d6      | 4         | 6.45%   |
| 0x106ca    | 4         | 6.45%   |
| 0x6d8      | 3         | 4.84%   |
| 0x306a9    | 3         | 4.84%   |
| 0xa0671    | 2         | 3.23%   |
| 0x66a      | 2         | 3.23%   |
| 0x30678    | 2         | 3.23%   |
| 0x206a7    | 2         | 3.23%   |
| 0xf24      | 1         | 1.61%   |
| 0x906e9    | 1         | 1.61%   |
| 0x806e9    | 1         | 1.61%   |
| 0x706a8    | 1         | 1.61%   |
| 0x706a1    | 1         | 1.61%   |
| 0x6e8      | 1         | 1.61%   |
| 0x695      | 1         | 1.61%   |
| 0x652      | 1         | 1.61%   |
| 0x306c3    | 1         | 1.61%   |
| 0x30661    | 1         | 1.61%   |
| 0x20655    | 1         | 1.61%   |
| 0x10676    | 1         | 1.61%   |
| 0x10661    | 1         | 1.61%   |
| 0x07030106 | 1         | 1.61%   |
| 0x06006705 | 1         | 1.61%   |
| 0x06001116 | 1         | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Bonnell       | 13        | 20.97%  |
| P6            | 9         | 14.52%  |
| Penryn        | 7         | 11.29%  |
| Core          | 6         | 9.68%   |
| Unknown       | 6         | 9.68%   |
| K8 Hammer     | 4         | 6.45%   |
| IvyBridge     | 3         | 4.84%   |
| Silvermont    | 2         | 3.23%   |
| SandyBridge   | 2         | 3.23%   |
| KabyLake      | 2         | 3.23%   |
| Goldmont plus | 2         | 3.23%   |
| Westmere      | 1         | 1.61%   |
| Puma          | 1         | 1.61%   |
| Piledriver    | 1         | 1.61%   |
| NetBurst      | 1         | 1.61%   |
| Haswell       | 1         | 1.61%   |
| Excavator     | 1         | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 35        | 54.69%  |
| Nvidia                           | 13        | 20.31%  |
| AMD                              | 13        | 20.31%  |
| Neomagic                         | 2         | 3.13%   |
| Silicon Integrated Systems [SiS] | 1         | 1.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 7         | 9.21%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 5         | 6.58%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 4         | 5.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 3.95%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 3         | 3.95%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 2         | 2.63%   |
| Neomagic NM2160 [MagicGraph 128XD]                                            | 2         | 2.63%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 2         | 2.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 2.63%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 2.63%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 2.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 2.63%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 2.63%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter             | 1         | 1.32%   |
| Nvidia NV11M [GeForce2 Go]                                                    | 1         | 1.32%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.32%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.32%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.32%   |
| Nvidia GF119 [GeForce GT 520]                                                 | 1         | 1.32%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1         | 1.32%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 1.32%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 1.32%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 1.32%   |
| Nvidia C67 [GeForce 7000M / nForce 610M]                                      | 1         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.32%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.32%   |
| Intel HD Graphics 630                                                         | 1         | 1.32%   |
| Intel HD Graphics 620                                                         | 1         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.32%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.32%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1         | 1.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.32%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                  | 1         | 1.32%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 1.32%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 1         | 1.32%   |
| AMD RV515 [Radeon X1300/X1550]                                                | 1         | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 50%     |
| 1 x Nvidia     | 11        | 17.74%  |
| 1 x AMD        | 9         | 14.52%  |
| 2 x AMD        | 4         | 6.45%   |
| Other          | 2         | 3.23%   |
| 1 x Neomagic   | 2         | 3.23%   |
| Intel + Nvidia | 2         | 3.23%   |
| 1 x SiS        | 1         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 51        | 82.26%  |
| Unknown     | 8         | 12.9%   |
| Proprietary | 3         | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 29        | 46.77%  |
| Unknown    | 22        | 35.48%  |
| 1.01-2.0   | 8         | 12.9%   |
| 5.01-6.0   | 1         | 1.61%   |
| 3.01-4.0   | 1         | 1.61%   |
| 0.51-1.0   | 1         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 21.43%  |
| LG Display              | 6         | 14.29%  |
| Samsung Electronics     | 5         | 11.9%   |
| HannStar                | 3         | 7.14%   |
| Goldstar                | 3         | 7.14%   |
| Acer                    | 3         | 7.14%   |
| LG Philips              | 2         | 4.76%   |
| Vizio                   | 1         | 2.38%   |
| Lenovo                  | 1         | 2.38%   |
| HJW                     | 1         | 2.38%   |
| Hewlett-Packard         | 1         | 2.38%   |
| Dell                    | 1         | 2.38%   |
| CPT                     | 1         | 2.38%   |
| Chimei Innolux          | 1         | 2.38%   |
| Chi Mei Optoelectronics | 1         | 2.38%   |
| BOE                     | 1         | 2.38%   |
| Arnos Instruments       | 1         | 2.38%   |
| Apple                   | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 2         | 4.76%   |
| Vizio E280i-B1 VIZ1002 1360x768 607x345mm 27.5-inch                      | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 2.38%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 1         | 2.38%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 1         | 2.38%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch            | 1         | 2.38%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch              | 1         | 2.38%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 2.38%   |
| HJW HDMI TO USB HJW0001 1920x1080 708x398mm 32.0-inch                    | 1         | 2.38%   |
| Hewlett-Packard Contino HPN4018 1920x1080 527x296mm 23.8-inch            | 1         | 2.38%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch                 | 1         | 2.38%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 1         | 2.38%   |
| HannStar HSD100IFW4A HSD03EE 1024x600 220x129mm 10.0-inch                | 1         | 2.38%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 1         | 2.38%   |
| Goldstar M2250D GSM57EF 1920x1080 477x268mm 21.5-inch                    | 1         | 2.38%   |
| Goldstar M198WA GSM4B36 1440x900 410x260mm 19.1-inch                     | 1         | 2.38%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 1         | 2.38%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 1         | 2.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1025 1024x600 222x125mm 10.0-inch | 1         | 2.38%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO3214 1280x800 261x163mm 12.1-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 1         | 2.38%   |
| Arnos Instruments F-417 AIC7450 1280x1024 338x270mm 17.0-inch            | 1         | 2.38%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch                   | 1         | 2.38%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                        | 1         | 2.38%   |
| Acer V243H ACR00A3 1920x1080 531x298mm 24.0-inch                         | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 11        | 26.83%  |
| 1920x1080 (FHD)  | 9         | 21.95%  |
| 1024x600         | 7         | 17.07%  |
| 1280x800 (WXGA)  | 6         | 14.63%  |
| 1440x900 (WXGA+) | 4         | 9.76%   |
| 1600x1200        | 2         | 4.88%   |
| 2560x1080        | 1         | 2.44%   |
| 1280x1024 (SXGA) | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 7         | 16.67%  |
| 10     | 6         | 14.29%  |
| 21     | 4         | 9.52%   |
| 17     | 4         | 9.52%   |
| 14     | 4         | 9.52%   |
| 13     | 4         | 9.52%   |
| 12     | 2         | 4.76%   |
| 8      | 2         | 4.76%   |
| 38     | 1         | 2.38%   |
| 34     | 1         | 2.38%   |
| 32     | 1         | 2.38%   |
| 27     | 1         | 2.38%   |
| 24     | 1         | 2.38%   |
| 23     | 1         | 2.38%   |
| 19     | 1         | 2.38%   |
| 18     | 1         | 2.38%   |
| 11     | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 30.95%  |
| 201-300     | 12        | 28.57%  |
| 401-500     | 6         | 14.29%  |
| 501-600     | 3         | 7.14%   |
| 351-400     | 3         | 7.14%   |
| 701-800     | 2         | 4.76%   |
| 101-200     | 2         | 4.76%   |
| 801-900     | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 26        | 63.41%  |
| 16/10 | 10        | 24.39%  |
| 4/3   | 2         | 4.88%   |
| 5/4   | 1         | 2.44%   |
| 3/2   | 1         | 2.44%   |
| 21/9  | 1         | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 16.67%  |
| 81-90          | 6         | 14.29%  |
| 41-50          | 6         | 14.29%  |
| 201-250        | 5         | 11.9%   |
| 71-80          | 2         | 4.76%   |
| 61-70          | 2         | 4.76%   |
| 351-500        | 2         | 4.76%   |
| 1-40           | 2         | 4.76%   |
| 151-200        | 2         | 4.76%   |
| 141-150        | 2         | 4.76%   |
| 131-140        | 2         | 4.76%   |
| 51-60          | 1         | 2.38%   |
| 301-350        | 1         | 2.38%   |
| 121-130        | 1         | 2.38%   |
| 501-1000       | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 15        | 36.59%  |
| 51-100  | 14        | 34.15%  |
| 121-160 | 11        | 26.83%  |
| 1-50    | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 53        | 84.13%  |
| 0     | 8         | 12.7%   |
| 2     | 2         | 3.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 26        | 26.53%  |
| Realtek Semiconductor            | 24        | 24.49%  |
| Qualcomm Atheros                 | 18        | 18.37%  |
| Broadcom                         | 11        | 11.22%  |
| Nvidia                           | 4         | 4.08%   |
| Marvell Technology Group         | 3         | 3.06%   |
| Silicon Integrated Systems [SiS] | 2         | 2.04%   |
| Qualcomm Atheros Communications  | 2         | 2.04%   |
| Texas Instruments                | 1         | 1.02%   |
| Ralink Technology                | 1         | 1.02%   |
| Ralink                           | 1         | 1.02%   |
| MediaTek                         | 1         | 1.02%   |
| LSI                              | 1         | 1.02%   |
| Hewlett-Packard                  | 1         | 1.02%   |
| Attansic Technology              | 1         | 1.02%   |
| ASIX Electronics                 | 1         | 1.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 6.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 7         | 5.83%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 6         | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 4.17%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 2.5%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 3         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 2.5%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 2.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 2         | 1.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 1.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 1.67%   |
| Intel Wireless 7260                                                           | 2         | 1.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.67%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.67%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 1.67%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 2         | 1.67%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.67%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.83%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.83%   |
| Realtek 802.11n WLAN Adapter                                                  | 1         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.83%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.83%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 0.83%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 0.83%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.83%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 0.83%   |
| Nvidia MCP67 Ethernet                                                         | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 38.18%  |
| Qualcomm Atheros                | 16        | 29.09%  |
| Broadcom                        | 8         | 14.55%  |
| Realtek Semiconductor           | 4         | 7.27%   |
| Qualcomm Atheros Communications | 2         | 3.64%   |
| Texas Instruments               | 1         | 1.82%   |
| Ralink Technology               | 1         | 1.82%   |
| Ralink                          | 1         | 1.82%   |
| MediaTek                        | 1         | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 8         | 14.29%  |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 3         | 5.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 5.36%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 3         | 5.36%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 3.57%   |
| Intel Wireless 7260                                                           | 2         | 3.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 3.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 3.57%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 3.57%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 3.57%   |
| Texas Instruments ACX 100 22Mbps Wireless Interface                           | 1         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.79%   |
| Realtek 802.11n WLAN Adapter                                                  | 1         | 1.79%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.79%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.79%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.79%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.79%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.79%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.79%   |
| MediaTek 802.11 n WLAN                                                        | 1         | 1.79%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.79%   |
| Intel Wireless 3165                                                           | 1         | 1.79%   |
| Intel WiFi Link 5100                                                          | 1         | 1.79%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.79%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.79%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.79%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.79%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.79%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 23        | 40.35%  |
| Intel                            | 13        | 22.81%  |
| Broadcom                         | 6         | 10.53%  |
| Qualcomm Atheros                 | 4         | 7.02%   |
| Nvidia                           | 4         | 7.02%   |
| Marvell Technology Group         | 3         | 5.26%   |
| Silicon Integrated Systems [SiS] | 2         | 3.51%   |
| Attansic Technology              | 1         | 1.75%   |
| ASIX Electronics                 | 1         | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 12.28%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 10.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.26%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 3.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.51%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 3.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 3.51%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 3.51%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 3.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.75%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.75%   |
| Nvidia MCP67 Ethernet                                             | 1         | 1.75%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 1.75%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 1.75%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.75%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.75%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 1.75%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.75%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 1.75%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 1.75%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.75%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.75%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 1.75%   |
| Broadcom NetXtreme BCM57760 Gigabit Ethernet PCIe                 | 1         | 1.75%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.75%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.75%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 1.75%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 55        | 49.11%  |
| WiFi     | 50        | 44.64%  |
| Modem    | 7         | 6.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 67.19%  |
| Ethernet | 21        | 32.81%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 42        | 67.74%  |
| 1     | 20        | 32.26%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 87.3%   |
| Yes  | 8         | 12.7%   |

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
| Intel                            | 45        | 64.29%  |
| Nvidia                           | 8         | 11.43%  |
| AMD                              | 6         | 8.57%   |
| Silicon Integrated Systems [SiS] | 2         | 2.86%   |
| ESS Technology                   | 2         | 2.86%   |
| Creative Labs                    | 2         | 2.86%   |
| C-Media Electronics              | 2         | 2.86%   |
| VIA Technologies                 | 1         | 1.43%   |
| ULi Electronics                  | 1         | 1.43%   |
| Ensoniq                          | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 19.18%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 5.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 4.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 4.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.11%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 2.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.74%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 2         | 2.74%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 2.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.74%   |
| ESS Technology ES1938/ES1946/ES1969 Solo-1 Audiodrive                      | 2         | 2.74%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.74%   |
| VIA Technologies VT82C686 AC97 Audio Controller                            | 1         | 1.37%   |
| ULi Electronics HD Audio Controller                                        | 1         | 1.37%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.37%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 1.37%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.37%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.37%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.37%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.37%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 1.37%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.37%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.37%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.37%   |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1         | 1.37%   |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1         | 1.37%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 1.37%   |
| C-Media Electronics CM6501                                                 | 1         | 1.37%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.37%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 1         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.37%   |
| AMD High Definition Audio Controller                                       | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 29        | 43.28%  |
| SK hynix            | 9         | 13.43%  |
| Samsung Electronics | 6         | 8.96%   |
| Unknown             | 5         | 7.46%   |
| Kingston            | 4         | 5.97%   |
| Micron Technology   | 3         | 4.48%   |
| Crucial             | 2         | 2.99%   |
| Corsair             | 2         | 2.99%   |
| Unknown (ABCD)      | 1         | 1.49%   |
| Unknown (8A02)      | 1         | 1.49%   |
| tigo                | 1         | 1.49%   |
| Smart               | 1         | 1.49%   |
| Patriot             | 1         | 1.49%   |
| Kllisre             | 1         | 1.49%   |
| Avant               | 1         | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 7.04%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3         | 4.23%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 4.23%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 2.82%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 2         | 2.82%   |
| Unknown RAM Module 256MB SODIMM DRAM                           | 2         | 2.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 2         | 2.82%   |
| Corsair RAM CMK32GX4M2E3200C16 16384MB DIMM DDR4 3200MT/s      | 2         | 2.82%   |
| Unknown RAM Module 512MB SODIMM SDRAM                          | 1         | 1.41%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 1.41%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1         | 1.41%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s                      | 1         | 1.41%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 1.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.41%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.41%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 1         | 1.41%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                       | 1         | 1.41%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 1.41%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 1.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.41%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 1.41%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 1.41%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1         | 1.41%   |
| Unknown RAM Module 1GB DIMM DDR 333MT/s                        | 1         | 1.41%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1         | 1.41%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 1.41%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 1.41%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 1         | 1.41%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s   | 1         | 1.41%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 1.41%   |
| tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                     | 1         | 1.41%   |
| Smart RAM SG564568FG8N6KFSQR 2GB DIMM DDR2 800MT/s             | 1         | 1.41%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 1.41%   |
| SK hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 1.41%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s          | 1         | 1.41%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.41%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.41%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1         | 1.41%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.41%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 17        | 29.31%  |
| DDR2    | 11        | 18.97%  |
| SDRAM   | 10        | 17.24%  |
| DDR     | 8         | 13.79%  |
| DDR4    | 6         | 10.34%  |
| DRAM    | 3         | 5.17%   |
| Unknown | 2         | 3.45%   |
| LPDDR4  | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 41        | 70.69%  |
| DIMM   | 17        | 29.31%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 19        | 28.36%  |
| 1024  | 16        | 23.88%  |
| 4096  | 10        | 14.93%  |
| 512   | 8         | 11.94%  |
| 16384 | 4         | 5.97%   |
| 8192  | 4         | 5.97%   |
| 256   | 3         | 4.48%   |
| 64    | 2         | 2.99%   |
| 232   | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 21        | 35%     |
| 1600    | 10        | 16.67%  |
| 667     | 5         | 8.33%   |
| 3200    | 3         | 5%      |
| 1067    | 3         | 5%      |
| 800     | 3         | 5%      |
| 3266    | 2         | 3.33%   |
| 2400    | 2         | 3.33%   |
| 1333    | 2         | 3.33%   |
| 533     | 2         | 3.33%   |
| 2667    | 1         | 1.67%   |
| 1334    | 1         | 1.67%   |
| 975     | 1         | 1.67%   |
| 400     | 1         | 1.67%   |
| 333     | 1         | 1.67%   |
| 266     | 1         | 1.67%   |
| 200     | 1         | 1.67%   |

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
| Chicony Electronics                    | 5         | 17.24%  |
| IMC Networks                           | 4         | 13.79%  |
| Cheng Uei Precision Industry (Foxlink) | 4         | 13.79%  |
| Microdia                               | 3         | 10.34%  |
| Acer                                   | 3         | 10.34%  |
| Suyin                                  | 2         | 6.9%    |
| Pixart Imaging                         | 2         | 6.9%    |
| Sunplus Innovation Technology          | 1         | 3.45%   |
| Silicon Motion                         | 1         | 3.45%   |
| Lite-On Technology                     | 1         | 3.45%   |
| Lenovo                                 | 1         | 3.45%   |
| Importek                               | 1         | 3.45%   |
| Apple                                  | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 2         | 6.9%    |
| Microdia Sonix USB 2.0 Camera                           | 2         | 6.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 6.9%    |
| Suyin Lenovo EasyCamera                                 | 1         | 3.45%   |
| Suyin Integrated_Webcam_HD                              | 1         | 3.45%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 3.45%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 3.45%   |
| Microdia Integrated Webcam                              | 1         | 3.45%   |
| Lite-On HP TrueVision HD Camera                         | 1         | 3.45%   |
| Lenovo Integrated Webcam                                | 1         | 3.45%   |
| Importek FJ Camera                                      | 1         | 3.45%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 1         | 3.45%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 3.45%   |
| Chicony VGA 30fps UVC Webcam                            | 1         | 3.45%   |
| Chicony Integrated HP HD Webcam                         | 1         | 3.45%   |
| Chicony HP HD Webcam [Fixed]                            | 1         | 3.45%   |
| Chicony CNF8243 Webcam                                  | 1         | 3.45%   |
| Chicony CNF7050                                         | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)     | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) FO23FF-58 PC-CAM | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) FM13FF-78        | 1         | 3.45%   |
| Apple Built-in iSight                                   | 1         | 3.45%   |
| Acer Lenovo EasyCamera                                  | 1         | 3.45%   |
| Acer Crystal Eye Webcam                                 | 1         | 3.45%   |
| Acer BisonCam, NB Pro                                   | 1         | 3.45%   |

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
| 0     | 46        | 74.19%  |
| 1     | 11        | 17.74%  |
| 2     | 3         | 4.84%   |
| 3     | 2         | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 10        | 43.48%  |
| Fingerprint reader       | 6         | 26.09%  |
| Communication controller | 3         | 13.04%  |
| Sound                    | 1         | 4.35%   |
| Net/ethernet             | 1         | 4.35%   |
| Modem                    | 1         | 4.35%   |
| Chipcard                 | 1         | 4.35%   |

