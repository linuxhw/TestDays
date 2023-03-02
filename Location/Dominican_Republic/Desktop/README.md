Linux in Dominican Republic - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Dominican Republic.

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

Total: 57

| Vendor   | Model                | Probe                                                      | Date         |
|----------|----------------------|------------------------------------------------------------|--------------|
| Gigabyte | Z170X-Gaming 7       | [0620aa7f6f](https://linux-hardware.org/?probe=0620aa7f6f) | Feb 25, 2023 |
| Gigabyte | Z170X-Gaming 7       | [df734c276f](https://linux-hardware.org/?probe=df734c276f) | Feb 25, 2023 |
| Gigabyte | Z170X-Gaming 7       | [00e573a880](https://linux-hardware.org/?probe=00e573a880) | Feb 23, 2023 |
| HP       | 18E5                 | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| Dell     | OptiPlex 3020        | [2adcd09348](https://linux-hardware.org/?probe=2adcd09348) | Nov 25, 2022 |
| Dell     | 0VNP2H A00           | [dff6013531](https://linux-hardware.org/?probe=dff6013531) | Nov 09, 2022 |
| Dell     | 08NPPY A00           | [55cf772a79](https://linux-hardware.org/?probe=55cf772a79) | Sep 09, 2022 |
| Gigabyte | A520I AC             | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| Gigabyte | A520I AC             | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| Dell     | 042P49 A02           | [2b09076619](https://linux-hardware.org/?probe=2b09076619) | Jul 30, 2022 |
| Dell     | OptiPlex 780         | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| Dell     | 08NPPY A00           | [e1e9853d49](https://linux-hardware.org/?probe=e1e9853d49) | May 26, 2022 |
| Dell     | 08NPPY A00           | [62c1081de8](https://linux-hardware.org/?probe=62c1081de8) | May 23, 2022 |
| Gigabyte | B450M DS3H V2        | [3e9f067939](https://linux-hardware.org/?probe=3e9f067939) | May 13, 2022 |
| Gigabyte | Z87X-UD5 TH-CF       | [5dc83ea64b](https://linux-hardware.org/?probe=5dc83ea64b) | Apr 24, 2022 |
| Unknown  | K8M800-8237          | [791e4eeaae](https://linux-hardware.org/?probe=791e4eeaae) | Apr 07, 2022 |
| Unknown  | K8M800-8237          | [3447b4c67a](https://linux-hardware.org/?probe=3447b4c67a) | Apr 07, 2022 |
| Dell     | 0CRH6C A02           | [726633bbcc](https://linux-hardware.org/?probe=726633bbcc) | Feb 18, 2022 |
| Dell     | 0N4YC8 A00           | [b32bc24608](https://linux-hardware.org/?probe=b32bc24608) | Jan 26, 2022 |
| Dell     | 0T10XW A01           | [53e23140c0](https://linux-hardware.org/?probe=53e23140c0) | Jan 23, 2022 |
| Dell     | 0T10XW A01           | [9164883468](https://linux-hardware.org/?probe=9164883468) | Nov 27, 2021 |
| Dell     | 0T10XW A01           | [b137bf3459](https://linux-hardware.org/?probe=b137bf3459) | Nov 27, 2021 |
| ASRock   | B450M-HDV R4.0       | [fb31c8d088](https://linux-hardware.org/?probe=fb31c8d088) | Oct 23, 2021 |
| Dell     | 0GTK4K A02           | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| HP       | 8265                 | [9a7e706a6b](https://linux-hardware.org/?probe=9a7e706a6b) | Aug 07, 2021 |
| Gigabyte | GA-78LMT-S2P         | [7fc508d633](https://linux-hardware.org/?probe=7fc508d633) | Jul 19, 2021 |
| Gigabyte | B450M DS3H-CF        | [891b06178e](https://linux-hardware.org/?probe=891b06178e) | Jun 29, 2021 |
| ASUSTek  | H110M-E/M.2          | [dc8b47f73d](https://linux-hardware.org/?probe=dc8b47f73d) | Feb 14, 2021 |
| Dell     | 0F6X5P A00           | [4adcccb57c](https://linux-hardware.org/?probe=4adcccb57c) | Feb 14, 2021 |
| Unknown  | Unknown              | [2cf1c789ec](https://linux-hardware.org/?probe=2cf1c789ec) | Dec 29, 2020 |
| HP       | 3647h                | [5788758b90](https://linux-hardware.org/?probe=5788758b90) | Oct 08, 2020 |
| Dell     | 0MM599               | [fce90bd449](https://linux-hardware.org/?probe=fce90bd449) | Oct 06, 2020 |
| Gigabyte | GA-78LMT-USB3 R2 sex | [9b34b0a6c3](https://linux-hardware.org/?probe=9b34b0a6c3) | Sep 03, 2020 |
| MSI      | H81M-E33             | [d24cd3858d](https://linux-hardware.org/?probe=d24cd3858d) | Aug 29, 2020 |
| MSI      | H81M-E33             | [9eda45f755](https://linux-hardware.org/?probe=9eda45f755) | Aug 20, 2020 |
| MSI      | H81M-E33             | [ba3577fb00](https://linux-hardware.org/?probe=ba3577fb00) | Aug 14, 2020 |
| Gigabyte | GA-78LMT-USB3 SEx    | [081a2c3e4c](https://linux-hardware.org/?probe=081a2c3e4c) | Aug 03, 2020 |
| MSI      | H81M-E33             | [6bedf88c28](https://linux-hardware.org/?probe=6bedf88c28) | Jul 30, 2020 |
| MSI      | B350 GAMING PLUS     | [ca22d3b169](https://linux-hardware.org/?probe=ca22d3b169) | Jul 24, 2020 |
| ASRock   | G41M-VS3             | [4877877772](https://linux-hardware.org/?probe=4877877772) | Jul 04, 2020 |
| MSI      | H81M-E33             | [2d531766ab](https://linux-hardware.org/?probe=2d531766ab) | Jun 26, 2020 |
| Biostar  | G41D3C               | [15959c0828](https://linux-hardware.org/?probe=15959c0828) | Jun 15, 2020 |
| HP       | 3031h                | [0278ac4043](https://linux-hardware.org/?probe=0278ac4043) | Apr 07, 2020 |
| ASUSTek  | H170 PRO GAMING      | [87496c419f](https://linux-hardware.org/?probe=87496c419f) | Apr 07, 2020 |
| Dell     | 0WG864               | [b7c74749f8](https://linux-hardware.org/?probe=b7c74749f8) | Mar 30, 2020 |
| Foxconn  | 2ABF                 | [44fe9bdc7d](https://linux-hardware.org/?probe=44fe9bdc7d) | Mar 20, 2020 |
| Foxconn  | 2ABF                 | [970faeadaf](https://linux-hardware.org/?probe=970faeadaf) | Mar 19, 2020 |
| HP       | 3031h                | [3b10a92ee2](https://linux-hardware.org/?probe=3b10a92ee2) | Mar 19, 2020 |
| ASUSTek  | H170 PRO GAMING      | [4f152e3015](https://linux-hardware.org/?probe=4f152e3015) | Mar 06, 2020 |
| Dell     | 06D7TR A00           | [4775efe228](https://linux-hardware.org/?probe=4775efe228) | Feb 27, 2020 |
| Gigabyte | B450 AORUS M         | [628a2983df](https://linux-hardware.org/?probe=628a2983df) | Nov 05, 2019 |
| Dell     | 0M132G A00           | [b79e419f05](https://linux-hardware.org/?probe=b79e419f05) | Aug 24, 2019 |
| HP       | 3397                 | [24770f4baf](https://linux-hardware.org/?probe=24770f4baf) | Jun 06, 2019 |
| HP       | 3396                 | [46d189dc80](https://linux-hardware.org/?probe=46d189dc80) | May 20, 2019 |
| Gigabyte | GA-78LMT-USB3 SEx    | [e30bc2b8f2](https://linux-hardware.org/?probe=e30bc2b8f2) | Nov 02, 2018 |
| Dell     | 0PU052               | [a5f063bc44](https://linux-hardware.org/?probe=a5f063bc44) | Apr 19, 2018 |
| Dell     | 0PU052               | [e8fb115c06](https://linux-hardware.org/?probe=e8fb115c06) | Jan 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 18.04                 | 10       | 23.81%  |
| Ubuntu 20.04                 | 5        | 11.9%   |
| Arch Rolling                 | 4        | 9.52%   |
| OpenMandriva 4.2             | 3        | 7.14%   |
| Ubuntu 22.04                 | 2        | 4.76%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 4.76%   |
| OpenMandriva 4.3             | 2        | 4.76%   |
| Fedora 34                    | 2        | 4.76%   |
| Ubuntu 22.10                 | 1        | 2.38%   |
| Ubuntu 19.10                 | 1        | 2.38%   |
| ROSA R10                     | 1        | 2.38%   |
| Pop!_OS 22.04                | 1        | 2.38%   |
| OpenMandriva 4.90            | 1        | 2.38%   |
| Manjaro 21.2.3               | 1        | 2.38%   |
| Linux Mint 20.3              | 1        | 2.38%   |
| Linux Mint 19.3              | 1        | 2.38%   |
| Fedora 33                    | 1        | 2.38%   |
| CentOS 8                     | 1        | 2.38%   |
| BlackPanther 18.1            | 1        | 2.38%   |
| Arch                         | 1        | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 18       | 43.9%   |
| OpenMandriva | 6        | 14.63%  |
| Arch         | 5        | 12.2%   |
| Fedora       | 3        | 7.32%   |
| openSUSE     | 2        | 4.88%   |
| Linux Mint   | 2        | 4.88%   |
| ROSA         | 1        | 2.44%   |
| Pop!_OS      | 1        | 2.44%   |
| Manjaro      | 1        | 2.44%   |
| CentOS       | 1        | 2.44%   |
| BlackPanther | 1        | 2.44%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 3        | 6.25%   |
| 5.16.7-desktop-1omv4003         | 2        | 4.17%   |
| 5.9.16-200.fc33.x86_64          | 1        | 2.08%   |
| 5.8.5-arch1-1                   | 1        | 2.08%   |
| 5.7.7-zen1-1-zen                | 1        | 2.08%   |
| 5.7.7-arch1-1                   | 1        | 2.08%   |
| 5.4.0-42-generic                | 1        | 2.08%   |
| 5.4.0-37-generic                | 1        | 2.08%   |
| 5.4.0-125-generic               | 1        | 2.08%   |
| 5.4.0-110-generic               | 1        | 2.08%   |
| 5.4.0-107-generic               | 1        | 2.08%   |
| 5.3.0-46-generic                | 1        | 2.08%   |
| 5.3.0-42-generic                | 1        | 2.08%   |
| 5.3.0-40-generic                | 1        | 2.08%   |
| 5.19.0-32-generic               | 1        | 2.08%   |
| 5.19.0-23-generic               | 1        | 2.08%   |
| 5.18.12-desktop-3omv4090        | 1        | 2.08%   |
| 5.18.10-76051810-generic        | 1        | 2.08%   |
| 5.17.6-xanmod1                  | 1        | 2.08%   |
| 5.15.21-1-MANJARO               | 1        | 2.08%   |
| 5.15.0-53-generic               | 1        | 2.08%   |
| 5.14.13-200.fc34.x86_64         | 1        | 2.08%   |
| 5.13.0-40-generic               | 1        | 2.08%   |
| 5.13.0-27-generic               | 1        | 2.08%   |
| 5.12.15-arch1-1                 | 1        | 2.08%   |
| 5.12.12-300.fc34.x86_64         | 1        | 2.08%   |
| 5.11.0-40-generic               | 1        | 2.08%   |
| 5.11.0-25-generic               | 1        | 2.08%   |
| 5.1.6-050106-generic            | 1        | 2.08%   |
| 5.1.2-zen1-1-zen                | 1        | 2.08%   |
| 5.0.0-32-generic                | 1        | 2.08%   |
| 5.0.0-25-generic                | 1        | 2.08%   |
| 4.9.87-nrj-desktop-2rosa-x86_64 | 1        | 2.08%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 1        | 2.08%   |
| 4.18.16-desktop-1bP             | 1        | 2.08%   |
| 4.18.15-1-default               | 1        | 2.08%   |
| 4.18.0-305.19.1.el8_4.x86_64    | 1        | 2.08%   |
| 4.15.0-99-generic               | 1        | 2.08%   |
| 4.15.0-96-generic               | 1        | 2.08%   |
| 4.15.0-91-generic               | 1        | 2.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15.0  | 5        | 11.36%  |
| 5.4.0   | 4        | 9.09%   |
| 5.3.0   | 3        | 6.82%   |
| 5.10.14 | 3        | 6.82%   |
| 5.7.7   | 2        | 4.55%   |
| 5.19.0  | 2        | 4.55%   |
| 5.16.7  | 2        | 4.55%   |
| 5.13.0  | 2        | 4.55%   |
| 5.11.0  | 2        | 4.55%   |
| 5.0.0   | 2        | 4.55%   |
| 5.9.16  | 1        | 2.27%   |
| 5.8.5   | 1        | 2.27%   |
| 5.18.12 | 1        | 2.27%   |
| 5.18.10 | 1        | 2.27%   |
| 5.17.6  | 1        | 2.27%   |
| 5.15.21 | 1        | 2.27%   |
| 5.15.0  | 1        | 2.27%   |
| 5.14.13 | 1        | 2.27%   |
| 5.12.15 | 1        | 2.27%   |
| 5.12.12 | 1        | 2.27%   |
| 5.1.6   | 1        | 2.27%   |
| 5.1.2   | 1        | 2.27%   |
| 4.9.87  | 1        | 2.27%   |
| 4.9.60  | 1        | 2.27%   |
| 4.18.16 | 1        | 2.27%   |
| 4.18.15 | 1        | 2.27%   |
| 4.18.0  | 1        | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15    | 5        | 11.63%  |
| 5.4     | 4        | 9.3%    |
| 5.3     | 3        | 6.98%   |
| 5.10    | 3        | 6.98%   |
| 4.18    | 3        | 6.98%   |
| 5.7     | 2        | 4.65%   |
| 5.19    | 2        | 4.65%   |
| 5.18    | 2        | 4.65%   |
| 5.16    | 2        | 4.65%   |
| 5.15    | 2        | 4.65%   |
| 5.13    | 2        | 4.65%   |
| 5.12    | 2        | 4.65%   |
| 5.11    | 2        | 4.65%   |
| 5.1     | 2        | 4.65%   |
| 5.0     | 2        | 4.65%   |
| 5.9     | 1        | 2.33%   |
| 5.8     | 1        | 2.33%   |
| 5.17    | 1        | 2.33%   |
| 5.14    | 1        | 2.33%   |
| 4.9     | 1        | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 40       | 97.56%  |
| i686   | 1        | 2.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 22       | 53.66%  |
| KDE5       | 9        | 21.95%  |
| Unknown    | 4        | 9.76%   |
| XFCE       | 2        | 4.88%   |
| X-Cinnamon | 2        | 4.88%   |
| KDE4       | 1        | 2.44%   |
| KDE        | 1        | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 34       | 82.93%  |
| Wayland | 4        | 9.76%   |
| Tty     | 2        | 4.88%   |
| Unknown | 1        | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 43.9%   |
| SDDM    | 12       | 29.27%  |
| GDM     | 5        | 12.2%   |
| GDM3    | 4        | 9.76%   |
| LightDM | 1        | 2.44%   |
| KDM     | 1        | 2.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_DO   | 17       | 40.48%  |
| en_US   | 15       | 35.71%  |
| Unknown | 7        | 16.67%  |
| es_ES   | 2        | 4.76%   |
| es_US   | 1        | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 26       | 63.41%  |
| EFI  | 15       | 36.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 27       | 65.85%  |
| Overlay | 6        | 14.63%  |
| Btrfs   | 5        | 12.2%   |
| Xfs     | 2        | 4.88%   |
| Unknown | 1        | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 50%     |
| GPT     | 14       | 33.33%  |
| MBR     | 7        | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 75.61%  |
| Yes       | 10       | 24.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 57.14%  |
| Yes       | 18       | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 15       | 36.59%  |
| Gigabyte Technology | 10       | 24.39%  |
| Hewlett-Packard     | 6        | 14.63%  |
| MSI                 | 2        | 4.88%   |
| ASUSTek Computer    | 2        | 4.88%   |
| ASRock              | 2        | 4.88%   |
| Unknown             | 2        | 4.88%   |
| Foxconn             | 1        | 2.44%   |
| Biostar             | 1        | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte GA-78LMT-USB3 6.0         | 2        | 4.88%   |
| Dell OptiPlex 990                  | 2        | 4.88%   |
| Dell OptiPlex 3010                 | 2        | 4.88%   |
| Unknown                            | 2        | 4.88%   |
| MSI MS-7A34                        | 1        | 2.44%   |
| MSI MS-7817                        | 1        | 2.44%   |
| HP EliteDesk 800 G1 USDT           | 1        | 2.44%   |
| HP EliteDesk 705 G3 SFF            | 1        | 2.44%   |
| HP Compaq Elite 8300 SFF           | 1        | 2.44%   |
| HP Compaq Elite 8300 CMT           | 1        | 2.44%   |
| HP Compaq dc7900 Small Form Factor | 1        | 2.44%   |
| HP Compaq 8000 Elite CMT PC        | 1        | 2.44%   |
| Gigabyte Z87X-UD5 TH               | 1        | 2.44%   |
| Gigabyte Z170X-Gaming 7            | 1        | 2.44%   |
| Gigabyte GA-78LMT-USB3 R2          | 1        | 2.44%   |
| Gigabyte GA-78LMT-S2P              | 1        | 2.44%   |
| Gigabyte B450M DS3H V2             | 1        | 2.44%   |
| Gigabyte B450M DS3H                | 1        | 2.44%   |
| Gigabyte B450 AORUS M              | 1        | 2.44%   |
| Gigabyte A520I AC                  | 1        | 2.44%   |
| Foxconn p6-2040fr                  | 1        | 2.44%   |
| Dell Precision WorkStation T5500   | 1        | 2.44%   |
| Dell PowerEdge T40                 | 1        | 2.44%   |
| Dell OptiPlex 9020                 | 1        | 2.44%   |
| Dell OptiPlex 780                  | 1        | 2.44%   |
| Dell OptiPlex 755                  | 1        | 2.44%   |
| Dell OptiPlex 745                  | 1        | 2.44%   |
| Dell OptiPlex 390                  | 1        | 2.44%   |
| Dell OptiPlex 3050                 | 1        | 2.44%   |
| Dell OptiPlex 3020                 | 1        | 2.44%   |
| Dell OptiPlex 160                  | 1        | 2.44%   |
| Dell DM061                         | 1        | 2.44%   |
| Biostar G41D3C                     | 1        | 2.44%   |
| ASUS H170 PRO GAMING               | 1        | 2.44%   |
| ASUS H110M-E/M.2                   | 1        | 2.44%   |
| ASRock G41M-VS3                    | 1        | 2.44%   |
| ASRock B450M-HDV R4.0              | 1        | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 12       | 29.27%  |
| HP Compaq              | 4        | 9.76%   |
| Gigabyte GA-78LMT-USB3 | 3        | 7.32%   |
| HP EliteDesk           | 2        | 4.88%   |
| Gigabyte B450M         | 2        | 4.88%   |
| Unknown                | 2        | 4.88%   |
| MSI MS-7A34            | 1        | 2.44%   |
| MSI MS-7817            | 1        | 2.44%   |
| Gigabyte Z87X-UD5      | 1        | 2.44%   |
| Gigabyte Z170X-Gaming  | 1        | 2.44%   |
| Gigabyte GA-78LMT-S2P  | 1        | 2.44%   |
| Gigabyte B450          | 1        | 2.44%   |
| Gigabyte A520I         | 1        | 2.44%   |
| Foxconn p6-2040fr      | 1        | 2.44%   |
| Dell Precision         | 1        | 2.44%   |
| Dell PowerEdge         | 1        | 2.44%   |
| Dell DM061             | 1        | 2.44%   |
| Biostar G41D3C         | 1        | 2.44%   |
| ASUS H170              | 1        | 2.44%   |
| ASUS H110M-E           | 1        | 2.44%   |
| ASRock G41M-VS3        | 1        | 2.44%   |
| ASRock B450M-HDV       | 1        | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 6        | 14.63%  |
| 2017 | 5        | 12.2%   |
| 2013 | 4        | 9.76%   |
| 2018 | 3        | 7.32%   |
| 2015 | 3        | 7.32%   |
| 2014 | 3        | 7.32%   |
| 2012 | 3        | 7.32%   |
| 2016 | 2        | 4.88%   |
| 2010 | 2        | 4.88%   |
| 2009 | 2        | 4.88%   |
| 2008 | 2        | 4.88%   |
| 2007 | 2        | 4.88%   |
| 2021 | 1        | 2.44%   |
| 2020 | 1        | 2.44%   |
| 2019 | 1        | 2.44%   |
| 2006 | 1        | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 41       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 40       | 97.56%  |
| Enabled  | 1        | 2.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 9        | 21.95%  |
| 4.01-8.0    | 8        | 19.51%  |
| 3.01-4.0    | 8        | 19.51%  |
| 16.01-24.0  | 8        | 19.51%  |
| 24.01-32.0  | 2        | 4.88%   |
| 0.51-1.0    | 2        | 4.88%   |
| 32.01-64.0  | 1        | 2.44%   |
| 2.01-3.0    | 1        | 2.44%   |
| 64.01-256.0 | 1        | 2.44%   |
| 1.01-2.0    | 1        | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 18       | 42.86%  |
| 2.01-3.0  | 11       | 26.19%  |
| 3.01-4.0  | 6        | 14.29%  |
| 4.01-8.0  | 3        | 7.14%   |
| 0.51-1.0  | 3        | 7.14%   |
| 8.01-16.0 | 1        | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 54.76%  |
| 2      | 9        | 21.43%  |
| 3      | 6        | 14.29%  |
| 4      | 4        | 9.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 53.66%  |
| Yes       | 19       | 46.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 40       | 97.56%  |
| No        | 1        | 2.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 21       | 50%     |
| No        | 21       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 78.05%  |
| Yes       | 9        | 21.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| Dominican Republic | 41       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Santo Domingo Este         | 23       | 54.76%  |
| Santiago de los Caballeros | 4        | 9.52%   |
| San Pedro de Macorís      | 2        | 4.76%   |
| San Juan                   | 2        | 4.76%   |
| San Cristobal              | 2        | 4.76%   |
| Nacional                   | 2        | 4.76%   |
| Sosua, Cabarete            | 1        | 2.38%   |
| Santo Domingo              | 1        | 2.38%   |
| San Francisco de Macorís  | 1        | 2.38%   |
| Moca                       | 1        | 2.38%   |
| La Romana                  | 1        | 2.38%   |
| Constanza                  | 1        | 2.38%   |
| Alejandro Bass             | 1        | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 27     | 30.3%   |
| Samsung Electronics | 9        | 12     | 13.64%  |
| WDC                 | 7        | 9      | 10.61%  |
| Toshiba             | 7        | 10     | 10.61%  |
| Kingston            | 7        | 8      | 10.61%  |
| Hitachi             | 6        | 8      | 9.09%   |
| SanDisk             | 2        | 3      | 3.03%   |
| Intel               | 2        | 2      | 3.03%   |
| Unknown             | 1        | 1      | 1.52%   |
| Phison Electronics  | 1        | 1      | 1.52%   |
| Patriot             | 1        | 1      | 1.52%   |
| Maxtor              | 1        | 1      | 1.52%   |
| Crucial             | 1        | 1      | 1.52%   |
| A-DATA Technology   | 1        | 1      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA050 500GB           | 2        | 2.67%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 2.67%   |
| Seagate ST380815AS 80GB            | 2        | 2.67%   |
| Seagate ST3500418AS 500GB          | 2        | 2.67%   |
| Seagate ST3160815AS 160GB          | 2        | 2.67%   |
| Kingston SV300S37A120G 120GB SSD   | 2        | 2.67%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 2.67%   |
| Hitachi HTS545050A7E380 500GB      | 2        | 2.67%   |
| WDC WD6400AAKS-22A7B2 640GB        | 1        | 1.33%   |
| WDC WD5000AZLX-60K2TA0 500GB       | 1        | 1.33%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1        | 1.33%   |
| WDC WD40EZRZ-75GXCB0 4TB           | 1        | 1.33%   |
| WDC WD2500AAKX-001CA0 250GB        | 1        | 1.33%   |
| WDC WD2500AAJS-75M0A0 250GB        | 1        | 1.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1        | 1.33%   |
| WDC WD10EZEX-75M2NA0 1TB           | 1        | 1.33%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 1.33%   |
| Unknown FK0032CAAZP 32GB           | 1        | 1.33%   |
| Toshiba NVMe SSD Drive 256GB       | 1        | 1.33%   |
| Toshiba MQ01ACF050 500GB           | 1        | 1.33%   |
| Toshiba MQ01ABD050V 500GB          | 1        | 1.33%   |
| Toshiba MK3275GSX 320GB            | 1        | 1.33%   |
| Toshiba MK2556GSY 250GB            | 1        | 1.33%   |
| Toshiba HDWE160 6TB                | 1        | 1.33%   |
| Seagate ST980412ASG 80GB           | 1        | 1.33%   |
| Seagate ST9250410AS 250GB          | 1        | 1.33%   |
| Seagate ST8000DM004-2CX188 8TB     | 1        | 1.33%   |
| Seagate ST500LM000-1EJ162 500GB    | 1        | 1.33%   |
| Seagate ST3320620AS 320GB          | 1        | 1.33%   |
| Seagate ST3320418AS 320GB          | 1        | 1.33%   |
| Seagate ST3250318AS 250GB          | 1        | 1.33%   |
| Seagate ST3160215AS 160GB          | 1        | 1.33%   |
| Seagate ST3160212SCE 160GB         | 1        | 1.33%   |
| Seagate ST31000528AS 1TB           | 1        | 1.33%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 1.33%   |
| Seagate ST2000DM001-1ER164 2TB     | 1        | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1.33%   |
| Seagate ST1000DM003-1SB102 1TB     | 1        | 1.33%   |
| Seagate BUP Slim SL 2TB            | 1        | 1.33%   |
| SanDisk SDSSDA240G 240GB           | 1        | 1.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 27     | 46.51%  |
| WDC                 | 7        | 9      | 16.28%  |
| Toshiba             | 6        | 8      | 13.95%  |
| Hitachi             | 6        | 8      | 13.95%  |
| Samsung Electronics | 3        | 5      | 6.98%   |
| Maxtor              | 1        | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 7        | 8      | 38.89%  |
| Samsung Electronics | 5        | 5      | 27.78%  |
| Intel               | 2        | 2      | 11.11%  |
| SanDisk             | 1        | 2      | 5.56%   |
| Patriot             | 1        | 1      | 5.56%   |
| Crucial             | 1        | 1      | 5.56%   |
| A-DATA Technology   | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 33       | 58     | 60%     |
| SSD     | 16       | 20     | 29.09%  |
| NVMe    | 5        | 6      | 9.09%   |
| Unknown | 1        | 1      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 40       | 78     | 86.96%  |
| NVMe | 5        | 6      | 10.87%  |
| SAS  | 1        | 1      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 36       | 58     | 67.92%  |
| 0.51-1.0   | 10       | 12     | 18.87%  |
| 1.01-2.0   | 4        | 5      | 7.55%   |
| 4.01-10.0  | 2        | 2      | 3.77%   |
| 3.01-4.0   | 1        | 1      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 12       | 27.27%  |
| 501-1000       | 8        | 18.18%  |
| 251-500        | 6        | 13.64%  |
| 1-20           | 6        | 13.64%  |
| 51-100         | 5        | 11.36%  |
| More than 3000 | 3        | 6.82%   |
| 21-50          | 2        | 4.55%   |
| 1001-2000      | 1        | 2.27%   |
| Unknown        | 1        | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 18       | 39.13%  |
| 21-50          | 8        | 17.39%  |
| 251-500        | 6        | 13.04%  |
| 501-1000       | 4        | 8.7%    |
| 51-100         | 4        | 8.7%    |
| 101-250        | 3        | 6.52%   |
| More than 3000 | 1        | 2.17%   |
| 2001-3000      | 1        | 2.17%   |
| Unknown        | 1        | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 1      | 7.69%   |
| WDC WD5000AZLX-60K2TA0 500GB    | 1        | 1      | 7.69%   |
| Toshiba MQ01ABD050V 500GB       | 1        | 1      | 7.69%   |
| Toshiba MK3275GSX 320GB         | 1        | 1      | 7.69%   |
| Toshiba MK2556GSY 250GB         | 1        | 1      | 7.69%   |
| Seagate ST500LM000-1EJ162 500GB | 1        | 1      | 7.69%   |
| Seagate ST3250318AS 250GB       | 1        | 1      | 7.69%   |
| Samsung Electronics HD154UI 1TB | 1        | 1      | 7.69%   |
| Hitachi HTS722020K9SA00 200GB   | 1        | 1      | 7.69%   |
| Hitachi HTS547564A9E384 640GB   | 1        | 1      | 7.69%   |
| Hitachi HTS545050A7E380 500GB   | 1        | 1      | 7.69%   |
| Hitachi HDT721025SLA380 250GB   | 1        | 1      | 7.69%   |
| Crucial CT240BX500SSD1 240GB    | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Hitachi             | 4        | 4      | 30.77%  |
| Toshiba             | 3        | 3      | 23.08%  |
| WDC                 | 2        | 2      | 15.38%  |
| Seagate             | 2        | 2      | 15.38%  |
| Samsung Electronics | 1        | 1      | 7.69%   |
| Crucial             | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Hitachi             | 4        | 4      | 33.33%  |
| Toshiba             | 3        | 3      | 25%     |
| WDC                 | 2        | 2      | 16.67%  |
| Seagate             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 12     | 90%     |
| SSD  | 1        | 1      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| Hitachi HDS721025CLA382 250GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 24       | 47     | 48.98%  |
| Works    | 15       | 24     | 30.61%  |
| Malfunc  | 9        | 13     | 18.37%  |
| Failed   | 1        | 1      | 2.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 27       | 56.25%  |
| AMD                              | 12       | 25%     |
| Samsung Electronics              | 2        | 4.17%   |
| VIA Technologies                 | 1        | 2.08%   |
| Toshiba America Info Systems     | 1        | 2.08%   |
| Silicon Integrated Systems [SiS] | 1        | 2.08%   |
| SanDisk                          | 1        | 2.08%   |
| Phison Electronics               | 1        | 2.08%   |
| Marvell Technology Group         | 1        | 2.08%   |
| ASMedia Technology               | 1        | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel SATA Controller [RAID mode]                                                       | 5        | 7.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 7.35%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 7.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 5.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 5.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 4.41%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 4.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 4.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 2.94%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 2.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 2.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 2.94%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 2.94%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 1.47%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 1.47%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 1.47%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1        | 1.47%   |
| SanDisk Non-Volatile memory controller                                                  | 1        | 1.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.47%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.47%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 1.47%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.47%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 1.47%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.47%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.47%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 1.47%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.47%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 1.47%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 31       | 55.36%  |
| IDE  | 15       | 26.79%  |
| RAID | 5        | 8.93%   |
| NVMe | 5        | 8.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 28       | 68.29%  |
| AMD    | 13       | 31.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 7.32%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 4.88%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 4.88%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1        | 2.44%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 2.44%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 2.44%   |
| Intel Pentium D CPU 3.00GHz                 | 1        | 2.44%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 2.44%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 2.44%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 2.44%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 2.44%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 2.44%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 1        | 2.44%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 2.44%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 2.44%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 2.44%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 2.44%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 2.44%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 2.44%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 2.44%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1        | 2.44%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 2.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 2.44%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 2.44%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 1        | 2.44%   |
| Intel Atom CPU 330 @ 1.60GHz                | 1        | 2.44%   |
| AMD Sempron Processor LE-1100               | 1        | 2.44%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 1        | 2.44%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 2.44%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 2.44%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 2.44%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 2.44%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 2.44%   |
| AMD PRO A10-8770 R7, 10 COMPUTE CORES 4C+6G | 1        | 2.44%   |
| AMD Phenom II X4 B95 Processor              | 1        | 2.44%   |
| AMD FX-6350 Six-Core Processor              | 1        | 2.44%   |
| AMD FX-4100 Quad-Core Processor             | 1        | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 13       | 31.71%  |
| AMD Ryzen 5             | 5        | 12.2%   |
| AMD FX                  | 4        | 9.76%   |
| Intel Core 2 Duo        | 3        | 7.32%   |
| Intel Xeon              | 2        | 4.88%   |
| Intel Core i3           | 2        | 4.88%   |
| Intel Pentium Dual-Core | 1        | 2.44%   |
| Intel Pentium D         | 1        | 2.44%   |
| Intel Pentium 4         | 1        | 2.44%   |
| Intel Pentium           | 1        | 2.44%   |
| Intel Core i7           | 1        | 2.44%   |
| Intel Core 2 Quad       | 1        | 2.44%   |
| Intel Celeron           | 1        | 2.44%   |
| Intel Atom              | 1        | 2.44%   |
| AMD Sempron             | 1        | 2.44%   |
| AMD Ryzen 3             | 1        | 2.44%   |
| AMD PRO A10             | 1        | 2.44%   |
| AMD Phenom II X4        | 1        | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 51.22%  |
| 2      | 11       | 26.83%  |
| 6      | 4        | 9.76%   |
| 1      | 3        | 7.32%   |
| 12     | 1        | 2.44%   |
| 3      | 1        | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 40       | 97.56%  |
| 2      | 1        | 2.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 60.98%  |
| 2      | 16       | 39.02%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 41       | 97.62%  |
| 64-bit         | 1        | 2.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 14.29%  |
| 0x306c3    | 5        | 11.9%   |
| 0x306a9    | 4        | 9.52%   |
| 0x506e3    | 3        | 7.14%   |
| 0x206a7    | 3        | 7.14%   |
| 0x1067a    | 3        | 7.14%   |
| 0x0800820d | 3        | 7.14%   |
| 0x06000852 | 3        | 7.14%   |
| 0x6fb      | 2        | 4.76%   |
| 0xf65      | 1        | 2.38%   |
| 0xf49      | 1        | 2.38%   |
| 0x906ea    | 1        | 2.38%   |
| 0x906e9    | 1        | 2.38%   |
| 0x106c2    | 1        | 2.38%   |
| 0x10661    | 1        | 2.38%   |
| 0x08108109 | 1        | 2.38%   |
| 0x08101013 | 1        | 2.38%   |
| 0x0600611a | 1        | 2.38%   |
| 0x010000db | 1        | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 5        | 12.2%   |
| Zen+        | 4        | 9.76%   |
| SandyBridge | 4        | 9.76%   |
| IvyBridge   | 4        | 9.76%   |
| Skylake     | 3        | 7.32%   |
| Piledriver  | 3        | 7.32%   |
| Penryn      | 3        | 7.32%   |
| Core        | 3        | 7.32%   |
| NetBurst    | 2        | 4.88%   |
| KabyLake    | 2        | 4.88%   |
| Zen 3       | 1        | 2.44%   |
| Zen         | 1        | 2.44%   |
| Westmere    | 1        | 2.44%   |
| K8 Hammer   | 1        | 2.44%   |
| K10         | 1        | 2.44%   |
| Excavator   | 1        | 2.44%   |
| Bulldozer   | 1        | 2.44%   |
| Bonnell     | 1        | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 19       | 44.19%  |
| AMD                              | 12       | 27.91%  |
| Nvidia                           | 10       | 23.26%  |
| VIA Technologies                 | 1        | 2.33%   |
| Silicon Integrated Systems [SiS] | 1        | 2.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 11.63%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 6.98%   |
| Nvidia GF119 [GeForce GT 520]                                               | 2        | 4.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 4.65%   |
| Intel HD Graphics 530                                                       | 2        | 4.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 4.65%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 4.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 4.65%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                   | 1        | 2.33%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter           | 1        | 2.33%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 2.33%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 2.33%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 2.33%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 2.33%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 2.33%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 2.33%   |
| Intel HD Graphics 630                                                       | 1        | 2.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                  | 1        | 2.33%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 2.33%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 2.33%   |
| Intel 82G965 Integrated Graphics Controller                                 | 1        | 2.33%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 2.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.33%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.33%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 2.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 2.33%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 2.33%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 17       | 41.46%  |
| 1 x AMD    | 12       | 29.27%  |
| 1 x Nvidia | 10       | 24.39%  |
| 1 x VIA    | 1        | 2.44%   |
| 1 x SiS    | 1        | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 34       | 80.95%  |
| Proprietary | 6        | 14.29%  |
| Unknown     | 2        | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 45.24%  |
| 1.01-2.0   | 7        | 16.67%  |
| 3.01-4.0   | 4        | 9.52%   |
| 0.51-1.0   | 4        | 9.52%   |
| 0.01-0.5   | 4        | 9.52%   |
| 7.01-8.0   | 3        | 7.14%   |
| 2.01-3.0   | 1        | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 9        | 27.27%  |
| Hewlett-Packard      | 5        | 15.15%  |
| AOC                  | 5        | 15.15%  |
| Acer                 | 3        | 9.09%   |
| Sony                 | 2        | 6.06%   |
| Samsung Electronics  | 2        | 6.06%   |
| ViewSonic            | 1        | 3.03%   |
| NEC Computers        | 1        | 3.03%   |
| LG Electronics       | 1        | 3.03%   |
| KTC                  | 1        | 3.03%   |
| Goldstar             | 1        | 3.03%   |
| BenQ                 | 1        | 3.03%   |
| Ancor Communications | 1        | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Sony TV SNYDD02 1920x1080 708x398mm 32.0-inch                           | 2        | 5.71%   |
| AOC 2269W AOC2269 1920x1080 477x268mm 21.5-inch                         | 2        | 5.71%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1        | 2.86%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 2.86%   |
| Samsung Electronics LCD Monitor SAM0664 1360x768 410x256mm 19.0-inch    | 1        | 2.86%   |
| NEC Computers EA274WMi NEC695F 2560x1440 597x336mm 27.0-inch            | 1        | 2.86%   |
| LG Electronics LCD Monitor W1943 1984x768                               | 1        | 2.86%   |
| LG Electronics LCD Monitor LG TV                                        | 1        | 2.86%   |
| KTC 32T72-H-AN KTC3200 1360x768 698x392mm 31.5-inch                     | 1        | 2.86%   |
| Hewlett-Packard w1858 HWP281A 1366x768 413x234mm 18.7-inch              | 1        | 2.86%   |
| Hewlett-Packard V244h HPN3358 1920x1080 531x299mm 24.0-inch             | 1        | 2.86%   |
| Hewlett-Packard LE2201w HWP2843 1680x1050 470x300mm 22.0-inch           | 1        | 2.86%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch            | 1        | 2.86%   |
| Hewlett-Packard L1730 HWP260E 1280x1024 338x270mm 17.0-inch             | 1        | 2.86%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                     | 1        | 2.86%   |
| Goldstar TV GSM75E3 1024x768 920x518mm 41.6-inch                        | 1        | 2.86%   |
| Dell SP2208WFP DEL403A 1680x1050 473x296mm 22.0-inch                    | 1        | 2.86%   |
| Dell SE2717H/HX DELD0A0 1920x1080 598x336mm 27.0-inch                   | 1        | 2.86%   |
| Dell P2017H DELD094 1600x900 434x236mm 19.4-inch                        | 1        | 2.86%   |
| Dell E2020H DELA159 1600x900 434x236mm 19.4-inch                        | 1        | 2.86%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                        | 1        | 2.86%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                       | 1        | 2.86%   |
| Dell DEL 1708FPBLK DEL4045 1280x1024 338x270mm 17.0-inch                | 1        | 2.86%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                         | 1        | 2.86%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                       | 1        | 2.86%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                       | 1        | 2.86%   |
| AOC TFT1780 AOC1780 1280x1024 304x228mm 15.0-inch                       | 1        | 2.86%   |
| AOC LCD Monitor 2243W 1920x1080                                         | 1        | 2.86%   |
| AOC 2060W AOC2060 1600x900 432x240mm 19.5-inch                          | 1        | 2.86%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch   | 1        | 2.86%   |
| Acer V223W ACR0027 1680x1050 473x296mm 22.0-inch                        | 1        | 2.86%   |
| Acer P225HQL ACR014E 1920x1080 476x268mm 21.5-inch                      | 1        | 2.86%   |
| Acer P193W ACR000C 1440x900 410x256mm 19.0-inch                         | 1        | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 32.35%  |
| 1280x1024 (SXGA)   | 5        | 14.71%  |
| 1680x1050 (WSXGA+) | 4        | 11.76%  |
| 2560x1440 (QHD)    | 2        | 5.88%   |
| 1600x900 (HD+)     | 2        | 5.88%   |
| 1440x900 (WXGA+)   | 2        | 5.88%   |
| 1366x768 (WXGA)    | 2        | 5.88%   |
| 1360x768           | 2        | 5.88%   |
| 3840x2160 (4K)     | 1        | 2.94%   |
| 1984x768           | 1        | 2.94%   |
| 1024x768 (XGA)     | 1        | 2.94%   |
| Unknown            | 1        | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 5        | 14.71%  |
| 17      | 5        | 14.71%  |
| 27      | 4        | 11.76%  |
| 22      | 4        | 11.76%  |
| 21      | 4        | 11.76%  |
| 18      | 3        | 8.82%   |
| 50      | 2        | 5.88%   |
| 24      | 2        | 5.88%   |
| Unknown | 2        | 5.88%   |
| 84      | 1        | 2.94%   |
| 41      | 1        | 2.94%   |
| 32      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 15       | 45.45%  |
| 501-600     | 6        | 18.18%  |
| 301-350     | 5        | 15.15%  |
| 1001-1500   | 2        | 6.06%   |
| Unknown     | 2        | 6.06%   |
| 701-800     | 1        | 3.03%   |
| 1501-2000   | 1        | 3.03%   |
| 901-1000    | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 56.25%  |
| 16/10   | 7        | 21.88%  |
| 5/4     | 5        | 15.63%  |
| Unknown | 2        | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 9        | 26.47%  |
| 141-150        | 8        | 23.53%  |
| 201-250        | 6        | 17.65%  |
| 301-350        | 4        | 11.76%  |
| More than 1000 | 3        | 8.82%   |
| Unknown        | 2        | 5.88%   |
| 351-500        | 1        | 2.94%   |
| 501-1000       | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 72.73%  |
| 101-120 | 4        | 12.12%  |
| 1-50    | 3        | 9.09%   |
| Unknown | 2        | 6.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 33       | 78.57%  |
| 2     | 5        | 11.9%   |
| 0     | 4        | 9.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 23       | 37.1%   |
| Intel                           | 16       | 25.81%  |
| Ralink Technology               | 6        | 9.68%   |
| Broadcom                        | 6        | 9.68%   |
| Qualcomm Atheros                | 5        | 8.06%   |
| VIA Technologies                | 1        | 1.61%   |
| Tul Corporation / PowerColor    | 1        | 1.61%   |
| TP-Link                         | 1        | 1.61%   |
| Qualcomm Atheros Communications | 1        | 1.61%   |
| Linksys                         | 1        | 1.61%   |
| HTC (High Tech Computer)        | 1        | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 27.54%  |
| Ralink MT7601U Wireless Adapter                                   | 5        | 7.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 5.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 4.35%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 2.9%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.9%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.45%   |
| Tul Corporation / PowerColor Network controller                   | 1        | 1.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 1.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 1.45%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 1.45%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 1.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 1.45%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1        | 1.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.45%   |
| Realtek 802.11ac NIC                                              | 1        | 1.45%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 1.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.45%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]     | 1        | 1.45%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 1.45%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.45%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 1.45%   |
| HTC (High Tech Computer) UMI HAMMER                               | 1        | 1.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.45%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.45%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.45%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 1.45%   |
| Broadcom BCM43217 802.11b/g/n                                     | 1        | 1.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 10       | 41.67%  |
| Ralink Technology               | 6        | 25%     |
| Qualcomm Atheros                | 2        | 8.33%   |
| Broadcom                        | 2        | 8.33%   |
| TP-Link                         | 1        | 4.17%   |
| Qualcomm Atheros Communications | 1        | 4.17%   |
| Linksys                         | 1        | 4.17%   |
| Intel                           | 1        | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                | 5        | 20.83%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3        | 12.5%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2        | 8.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1        | 4.17%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 4.17%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 4.17%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 4.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 4.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 4.17%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1        | 4.17%   |
| Realtek 802.11ac NIC                                           | 1        | 4.17%   |
| Ralink RT5370 Wireless Adapter                                 | 1        | 4.17%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 4.17%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]  | 1        | 4.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 4.17%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1        | 4.17%   |
| Broadcom BCM43217 802.11b/g/n                                  | 1        | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 20       | 45.45%  |
| Intel                    | 15       | 34.09%  |
| Broadcom                 | 4        | 9.09%   |
| Qualcomm Atheros         | 3        | 6.82%   |
| VIA Technologies         | 1        | 2.27%   |
| HTC (High Tech Computer) | 1        | 2.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 43.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 9.09%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 6.82%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 4.55%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 4.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 2.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 2.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 2.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 2.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.27%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.27%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.27%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.27%   |
| Intel 82562V 10/100 Network Connection                            | 1        | 2.27%   |
| HTC (High Tech Computer) UMI HAMMER                               | 1        | 2.27%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.27%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 2.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 2.27%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 40       | 64.52%  |
| WiFi     | 21       | 33.87%  |
| Unknown  | 1        | 1.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 66.67%  |
| WiFi     | 14       | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 75.61%  |
| 2     | 9        | 21.95%  |
| 0     | 1        | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 40       | 97.56%  |
| Yes  | 1        | 2.44%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 6        | 66.67%  |
| Intel                   | 1        | 11.11%  |
| IMC Networks            | 1        | 11.11%  |
| ASUSTek Computer        | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6        | 66.67%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 11.11%  |
| IMC Networks BCM20702A0                             | 1        | 11.11%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 25       | 43.1%   |
| AMD                              | 15       | 25.86%  |
| Nvidia                           | 10       | 17.24%  |
| VIA Technologies                 | 1        | 1.72%   |
| Silicon Integrated Systems [SiS] | 1        | 1.72%   |
| Logitech                         | 1        | 1.72%   |
| JMTek                            | 1        | 1.72%   |
| Creative Labs                    | 1        | 1.72%   |
| C-Media Electronics              | 1        | 1.72%   |
| Blue Microphones                 | 1        | 1.72%   |
| BigBen Interactive               | 1        | 1.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 8.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 7.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 7.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 7.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 4.23%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 4.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 4.23%   |
| Nvidia High Definition Audio Controller                                    | 2        | 2.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 2.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 2.82%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 2        | 2.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2        | 2.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 2.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 2.82%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 1.41%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1        | 1.41%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.41%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 1.41%   |
| Logitech Headset H390                                                      | 1        | 1.41%   |
| JMTek USB Speaker                                                          | 1        | 1.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.41%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 1.41%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                         | 1        | 1.41%   |
| C-Media Electronics USB Audio Device                                       | 1        | 1.41%   |
| Blue Microphones Yeti Stereo Microphone                                    | 1        | 1.41%   |
| BigBen Interactive Revolution Pro Controller                               | 1        | 1.41%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1        | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 1.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK hynix            | 7        | 22.58%  |
| Samsung Electronics | 5        | 16.13%  |
| Unknown             | 4        | 12.9%   |
| Micron Technology   | 2        | 6.45%   |
| Kingston            | 2        | 6.45%   |
| Corsair             | 2        | 6.45%   |
| V-Color             | 1        | 3.23%   |
| Ramaxel Technology  | 1        | 3.23%   |
| Qimonda             | 1        | 3.23%   |
| Patriot             | 1        | 3.23%   |
| Nanya Technology    | 1        | 3.23%   |
| G.Skill             | 1        | 3.23%   |
| Elpida              | 1        | 3.23%   |
| Crucial             | 1        | 3.23%   |
| Avant               | 1        | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s     | 2        | 6.06%   |
| V-Color RAM TL48G32S8KGRGB16 8GB DIMM DDR4 3200MT/s      | 1        | 3.03%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                | 1        | 3.03%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                  | 1        | 3.03%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 3.03%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 3.03%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 3.03%   |
| SK hynix RAM HYMP512U64CP8-Y5 1024MB DIMM DDR2 1331MT/s  | 1        | 3.03%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s     | 1        | 3.03%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s  | 1        | 3.03%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1        | 3.03%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s     | 1        | 3.03%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 1        | 3.03%   |
| Samsung RAM M378B5673FH0-CF8 2GB DIMM DDR3 1067MT/s      | 1        | 3.03%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s           | 1        | 3.03%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s   | 1        | 3.03%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 3.03%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s    | 1        | 3.03%   |
| Qimonda RAM 64T128020HU3SB 1GB DIMM DDR2 667MT/s         | 1        | 3.03%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s          | 1        | 3.03%   |
| Nanya RAM NT1GT64U88D0BY-AD 1GB DIMM DDR2 49926MT/s      | 1        | 3.03%   |
| Nanya RAM NT1GT64U88D0BY-3C 1GB DIMM DDR2 667MT/s        | 1        | 3.03%   |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s    | 1        | 3.03%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s      | 1        | 3.03%   |
| Kingston RAM HP497157-D88-ELFWG 2GB DIMM DDR3 1333MT/s   | 1        | 3.03%   |
| Kingston RAM 9965745-028.A00G 16384MB DIMM DDR4 2666MT/s | 1        | 3.03%   |
| G.Skill RAM F4-2666C15-4GVR 4GB DIMM DDR4 2933MT/s       | 1        | 3.03%   |
| Elpida RAM SyncMAX 512MB DIMM DDR 533MT/s                | 1        | 3.03%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s    | 1        | 3.03%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 1        | 3.03%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s    | 1        | 3.03%   |
| Avant RAM F6428U52E6800F 1024MB DIMM DDR 533MT/s         | 1        | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 8        | 34.78%  |
| DDR3    | 7        | 30.43%  |
| SDRAM   | 4        | 17.39%  |
| Unknown | 2        | 8.7%    |
| DDR2    | 1        | 4.35%   |
| DDR     | 1        | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 19       | 95%     |
| SODIMM | 1        | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 33.33%  |
| 4096  | 7        | 29.17%  |
| 2048  | 5        | 20.83%  |
| 1024  | 2        | 8.33%   |
| 16384 | 1        | 4.17%   |
| 512   | 1        | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 18.52%  |
| 1333    | 5        | 18.52%  |
| 2933    | 2        | 7.41%   |
| 2133    | 2        | 7.41%   |
| 49926   | 1        | 3.7%    |
| 3600    | 1        | 3.7%    |
| 3200    | 1        | 3.7%    |
| 2934    | 1        | 3.7%    |
| 2666    | 1        | 3.7%    |
| 2400    | 1        | 3.7%    |
| 1867    | 1        | 3.7%    |
| 1648    | 1        | 3.7%    |
| 1331    | 1        | 3.7%    |
| 1067    | 1        | 3.7%    |
| 667     | 1        | 3.7%    |
| 533     | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Microsoft               | 3        | 33.33%  |
| OmniVision Technologies | 2        | 22.22%  |
| Samsung Electronics     | 1        | 11.11%  |
| Logitech                | 1        | 11.11%  |
| Jieli Technology        | 1        | 11.11%  |
| Apple                   | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Microsoft MicrosoftÂ LifeCam HD-5001 | 2        | 22.22%  |
| Samsung Galaxy A5 (MTP)               | 1        | 11.11%  |
| OmniVision Monitor Webcam             | 1        | 11.11%  |
| OmniVision Monitor Integrated Webcam  | 1        | 11.11%  |
| Microsoft LifeCam VX-2000             | 1        | 11.11%  |
| Logitech Webcam Pro 9000              | 1        | 11.11%  |
| Jieli USB PHY 2.0                     | 1        | 11.11%  |
| Apple iPhone 5/5C/5S/6/SE             | 1        | 11.11%  |

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
| 0     | 36       | 85.71%  |
| 1     | 6        | 14.29%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 4        | 66.67%  |
| Network       | 1        | 16.67%  |
| Camera        | 1        | 16.67%  |

